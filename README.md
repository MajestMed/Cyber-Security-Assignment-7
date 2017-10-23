# Project 7 - WordPress Pentesting

Time spent: **6** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) Unauthenticated XSS
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: Wordpress v4.2
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: Leave a reply on wordpress and type in <script>while(10{alert(document.cookie);}</script>. Clicking submit       will reveal the bug.
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
    
2. (Required) Image File Authenticated XSS
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version: Wordpress v4.2.2
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: upload an image with the name of a.jpeg, and then using the wordpress File system, add the image as an     attachment, and then navigate to the image and “view attachment page”. This will cause an error due to the bug we found!
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
    
3. (Required) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types: XSS
    - Tested in version:4.1
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: Add(3) music files to wordpress, and in the scription of the file "word <script>alert(document.cookie);</script>". Try to post the media file as an attachment as an audio playlist. The playlist creation should cause the bug.
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

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
