Config
======

Essence# Configuration Profiles

This repository contains configuration profiles for use with Essence#.

A configuration profile is persistently stored as a folder in the filesystem. 
It must be located in the folder %EssenceSharpPath%\Config. The folder name must 
use ".profile" as its file extension. A configuration profile folder may 
(optionally) contain one or more files--each with its own format--that specify 
configuration options that globally apply to Essence#.

Currently, the only configuration profile that can be defined or used is the 
default configuration profile (Default.profile,) and the only 
recognized/supported configuration file type is an AssemblyMap. Support for 
additional named configuration profiles will be added later; and it is highly 
probable that other types of configuration files will also be defined.

An AssemblyMap configuration file must be named "AssemblyMap.es." If present, 
it must contain an Essence# dictionary literal (which may be empty.) If any, 
the keys in the dictionary must be logical assembly names, and the values must 
be physical assembly names that can be used to actually load a .Net assembly.

For more information, please see the Essence# site on CodePlex.

