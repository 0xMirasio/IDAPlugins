
# IDAPlugins
A non official list of IDA plugins link sorted by categories. Feel feel to create issues/pull request, I will add the plugins. 

Notation : 
As plugins can have the same goal purpose, I will put a (1)/(2)/... ranking. Personnal opinion , can modify !

## Essentials

https://github.com/REhints/HexRaysCodeXplorer For better code navigation in RE process. CodeXplorer automates code reconstruction of C++ applications.  
https://github.com/archercreat/ida_names IDA-names automatically renames pseudocode windows with the current function name.  
https://github.com/david-lazar/IDAPatternSearch The IDA Pattern Search plugin adds a capability of finding functions according to bit-patterns into the well-known IDA Pro disassembler based on Ghidra's function patterns format.  
https://github.com/eternalklaus/RefHunter RefHunter find all references in simple and lightweighted manner.   


## General Information

### Windows
https://github.com/blackberry/pe_tree PETree is a Python module for viewing Portable Executable (PE) files in a tree-view  

## General Decompilation Helper

https://github.com/airbus-cert/Yagi Yagi is a C++ plugin that includes the Ghidra decompiler into IDA 7.5 and 7.6.  
https://github.com/gaasedelen/lucid An Interactive Hex-Rays Microcode Explorer 

## Debug Helper

https://github.com/PwCUK-CTO/SmartJump SmartJump is designed to improve the 'g' keyboard shortcut in IDA. (pure adress isn't necessary anymore, you can input eax or [rsp]+rdi, ....)  

## Time travel Debugging

https://github.com/airbus-cert/ttddbg New debugger for IDA which supports loading Time Travel Debugging traces.  
https://github.com/gaasedelen/tenet/ Tenet is an IDA Pro plugin which enables reverse engineers to explore execution traces of native code.  

## DeObfuscation / Decoder / Malware Reverse
https://gitlab.com/eshard/d810 D-810 is a plugin which aims at removing several obfuscation layer.  
https://github.com/cellebrite-srl/FunctionInliner FunctionInliner is an IDA plugin that can be used to ease the reversing of binaries that have been space-optimized with function outlining  
https://hex-rays.com/contests_details/contest2020/idaDiscover/idaDiscover.7z idaDiscover is essentially a toolbox to assist malware analysis

## Dev Helper

https://github.com/eset/ipyida IPyIDA is a python-only solution to add an IPython console to IDA Pro.  
http://sandsprite.com//blogs/index.php?uid=7&pid=361 jside adds JavaScript scripting to IDA, including an IDE with syntax highlighting, auto-completion and interactive debugger.  
https://github.com/0xeb/ida-qscripts QScripts is an alternative to IDA's plugins IDE management.  
https://github.com/williballenthin/ida-netnode Humane API for storing and accessing persistent data in IDA Pro databases  
https://github.com/synacktiv/bip/ Bip is a project which aims to simplify the usage of Python for interacting with IDA  

## Cryptography

https://github.com/polymorf/findcrypt-yara IDA pro plugin to find crypto constants using yara.  

## Exploit helper

https://github.com/Accenture/VulFi A query based function cross-reference finder for vulnerability research.  

## Binary Information & Exports

https://github.com/quarkslab/quokka Quokka is a binary exporter: from the disassembly of a program, it generates an export file that can be used without a disassembler.  
https://github.com/jhftss/IDA2Obj IDA2Obj is a tool to implement SBI (Static Binary Instrumentation).  
https://github.com/mahaloz/decomp2dbg decomp2dbg aims to shorten the gap of context switching between decompiler and debugger by introducing a generic API for decompiler-to-debugger symbol syncing.  

## Low-Level / Boot

https://github.com/binarly-io/efiXplorer IDA plugin for UEFI firmware analysis and reverse engineering automation  

## External Project Integration

https://github.com/riskeco/SyncReven SyncReven lets the user connect IDA to a running Reven/Axion instance.  
https://github.com/fireeye/capa/ Integrates the FLARE team's open-source framework in IDA.  
https://github.com/Cisco-Talos/DynDataResolver DDR is an IDA plugin that instruments binaries using the DynamoRIO framework.  
https://github.com/qilingframework/qiling/tree/master/qiling/extensions/idaplugin  Ida plugin for Qiling framework integration.  

## Multiple Files / Librairies management

https://github.com/airbus-seclab/AutoResolv Resolves functions imported from external libraries and refactor code.  
https://github.com/nccgroup/idahunt Command-line tool to analyze with IDA all executable files recursively from a given folder.  
 

## IDA Collaboration / IDA Management
(new, check out IDA Team from hexrays website)

https://github.com/Martyx00/CollaRE/ CollaRE enables collaboration using multiple reverse engineering tools for more complex projects  
https://github.com/tmr232/Sark Manager/Auto-Installer for IDA plugins (1)  
https://github.com/tkmru/idapm Manager/Auto-Installer for IDA plugins (2)    

## IOS

https://github.com/cellebrite-labs/ida_kcpp an IDAPython module for way more convienent way to Reverse Engineering iOS kernelcaches. (extension of ida_kernelcache)    
https://github.com/cellebrite-labs/ida_kernelcache IDA Toolkit for analyzing iOS kernelcaches  

## Custom Architecture
### Nitendo Switch

https://github.com/pgarba/switchidaproloader loader for the NRO Nintendo Switch binaries  

### nanoMIPS

https://github.com/0rganizers/nmips IDA plugin to enable nanoMIPS processor support   

### Brainfuck 

https://hex-rays.com/contests_details/contest2020/bf/bf.zip Brainfuck language support  
