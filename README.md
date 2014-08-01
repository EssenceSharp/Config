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

For more information, please see the Essence# site on CodePlex.

