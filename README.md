# Malware Analysis Cheat Sheet

## Summary
This document was designed to be a useful, practical asset for those looking to perform Malware Analysis step by step by a methodology.
This methodology based on the book "Learning Malware Analysis" by Monnappa K A and my professional experience.

## Table of Contents

* [The Starting Point Chart](https://github.com/ptsec/Malware-Analysis/blob/master/chart-01.png)
* [Basic Static Analysis](https://github.com/ptsec/Malware-Analysis/#basic-static-analysis)
* [Basic Dynamic Analysis](https://github.com/ptsec/Malware-Analysis/#basic-dynamic-analysis)
* [Advanced Static Analysis](https://github.com/ptsec/Malware-Analysis/#advanced-static-analysis)
* [Advanced Dynamic Analysis](https://github.com/ptsec/Malware-Analysis/#advanced-dynamic-analysis)


## Basic Static Analysis
* ### Get File Hash
  * [PowerShell](https://github.com/ptsec/Malware-Analysis/blob/master/get-hash.ps1) 
  * [Python](https://github.com/ptsec/Malware-Analysis/blob/master/get-hash.py)
  * [Sigcheck](https://docs.microsoft.com/en-us/sysinternals/downloads/sigcheck)
  
* ### Upload The Hash To VirusTotal
  * [VirusTotal](https://www.virustotal.com/gui/home/search) 
  * [Python](https://github.com/ptsec/Malware-Analysis/blob/master/get-hash.py)

* ### Extract Strings
  * [Strings](https://docs.microsoft.com/en-us/sysinternals/downloads/strings)
  * [Stringsfiter](https://github.com/fireeye/stringsifter) 
  
* ### Deobfuscate Strings
   * [Floss](https://github.com/fireeye/flare-floss)
   
* ### COFF Header Information
   * [Understanding COFF](https://tech-zealots.com/malware-analysis/pe-portable-executable-structure-malware-analysis-part-2/) 
   * [CFF Explorer](https://ntcore.com/?page_id=388)
   * [PE Internals](http://www.andreybazhan.com/pe-internals.html)
   
  
  


## Basic Dynamic Analysis

## Advanced Static Analysis

## Advanced Dynamic Analysis
