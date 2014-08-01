Config
======

Essence# Configuration Profiles

This repository contains configuration profiles for use with Essence#.

A configuration is a folder whose filename extension is ".profile" and which
(optionally) contains one or more files--each with its own format--that specify 
configuration options.

Currently, the only configuration profile provided is the default configuration
profile (Default.profile,) and the only support configuration file type is
an AssemblyMap.

An AssemblyMap configuration file must be named "AssemblyMap.es." If present,
it must contain an Essence# dictionary literal (which may be empty.) If any,
the keys in the dictionary must be logical assembly names, and the values
must be physical assembly names that can be used to actually load a .Net 
assembly.

Here's an example:

#{
#System 		-> 'System, Version=2.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089'.
#System.Core 		-> 'System.Core, Version=3.5.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089'.
#System.ServiceModel 	-> 'System.ServiceModel, Version=3.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089'.
#Windows.Base		-> 'WindowsBase, Version=3.0.0.0, Culture=neutral, PublicKeyToken=31bf3856ad364e35'
}

