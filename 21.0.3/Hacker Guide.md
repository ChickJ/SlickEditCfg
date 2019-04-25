# SlickEdit 21.0.3 Hacker Guide

## Forms
To open a form _Macro -> Open Form_


| Caption           | Internal Name    | Description        | UI Path                       |
|-------------------|------------------|--------------------|-------------------------------|
| Open Form         |                  |                    |                               |
| PROJECTS          | _tbprojects_form | Project window     |                               |
| Symbol Properties | _tbprops_form    |                    |                               |
| Open              | _tbopen_form     | Open file window   |                               |
| Class             | _tbclass_form    | Class tool window  | View -> Tool Windows -> Class |
| Enumerate         | _enum_form       | Enumerate dialog   |                               |
| Global Find       | _fmfind_form     | Global Find dialog |                               |

## Interesting Files

#### usrprjtemplates.vpt
Custom project templates data. A project template controls which commands and
folders are associated with a new project.

_Project -> New -> Customize..._

#### [SlickEditInstallDir]/macros/tags.e
The `tags.e` module contains auto tagging code used to do things like build
tag files for the .NET Framework which is critical for decent Intellisense
capabilities.

#### vunxs21.0.3.0s.e
This file looks to contain customizations form customizations.

Reference:
  * _cs_buildAutoTagFile
