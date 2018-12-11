# CodePathweek7
# Project 7 - WordPress Pentesting

Time spent: **10** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. CVE-2016-4566
  - [ ] Summary: 
    - Vulnerability types: WordPress <= 4.5.1 - Pupload Same Origin Method Execution (SOME)
    - Tested in version: 3.1.1
    - Fixed in version: 4.5.2
  - [ ] GIF Walkthrough: 
	![](https://github.com/JamesNornand/CodePathweek7/blob/master/exploit1/exploit1.gif)
  - [ ] Steps to recreate: 
	- Create a new post.
	- Leave new Javascript code comment below the post, which will create a button. 
  - [ ] Affected source code:
    - [Link 1](https://gist.github.com/cure53/09a81530a44f6b8173f545accc9ed07e)

2. CVE-2015-3440
  - [ ] Summary: 
    - Vulnerability types: WordPress <= 4.2 - Unauthenticated Stored Cross-Site Scripting (XSS)
    - Tested in version: 3.1.1
    - Fixed in version: 4.2.1
  - [ ] GIF Walkthrough: 
	![](https://github.com/JamesNornand/CodePathweek7/blob/master/exploit2/exploit2.gif)
  - [ ] Steps to recreate: 
	- Create a new post.
	- Log out.
	- Leave a new script comment with the data size exceed 64kb below the post.
  - [ ] Affected source code:
    - [Link 1](https://klikki.fi/adv/wordpress2.html)

3. CVE-2015-5623
  - [ ] Summary: 
    - Vulnerability types: WordPress <= 4.2.2 - Authenticated Stored Cross-Site Scripting (XSS)
    - Tested in version:3.1.1
    - Fixed in version: 4.2.3
  - [ X] GIF Walkthrough: 
	![](https://github.com/JamesNornand/CodePathweek7/blob/master/exploit3/exploit3.gif)
  - [ ] Steps to recreate: 
	- Create a new post.
	- Keep login.
	- Leave a script comment.

  - [ ] Affected source code:
    - [Link 1](https://klikki.fi/adv/wordpress3.html)

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
# Codepathweek7
