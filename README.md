# Project 7 - WordPress Pentesting

Time spent: 8 hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) HREF XSS Vulnerability
  - [ ] Summary: Post text with a href can take a Cross-Site Scripting payload.
    - Vulnerability types: XSS
    - Tested in version: 4.0
    - Fixed in version: 4.1
  - [ ] GIF Walkthrough: 
  
  https://github.com/scottmbradley/Week7/blob/master/week%207%20assignment%20%231.gif

  - [ ] Steps to recreate: Upload JPG to attachment page, Change text to Cross-Site Scripting payload.
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)


1. (Required) Vulnerability Name or ID  <INPUT TYPE="BUTTON" ONCLICK="alert('XSS')"/>
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.0
    - Fixed in version: 4.1
  - [ ] GIF Walkthrough: 
  
  https://github.com/scottmbradley/Week7/blob/master/week%207%20assignment%20%23%202.gif
  
  - [ ] Steps to recreate: Uploaded code and ran code
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
    
1. (Required) Vulnerability Name or ID <IFRAME SRC="javascript:alert('XSS');"></IFRAME>
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: 4.0
    - Fixed in version: 4.1
  - [ ] GIF Walkthrough: 
  
  https://github.com/scottmbradley/Week7/blob/master/week%207%20assignment%20%233.gif
  
  - [ ] Steps to recreate: Uploaded code and ran code
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php) 

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [2018] [Scott M. Bradley]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
