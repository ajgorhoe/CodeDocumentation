
# IGLib Code Documentation Repository

## About this Repository

This repository is part of the [Investigative Generic Library (IGLib)](https://github.com/ajgorhoe/IGLib.modules.IGLibCore/blob/main/README.md). It is a container repository that contains various types of generated code documentation for IGLib. In order to **view code documentation**, you need to **clone the containing repositories** by running the `UpdateRepoGroup_IGLibCodeDocumentation.ps1` PowerShell script.

## Generated Code Documentation

Below are links to starting pages of various types and flavors of generated documentation. Click the appropriate link to start browsing the specific documentation. If the documentation has not be generated yet or it needs to be updated according to changes, run the appropriate scripts.  

#### New IGLib Documentation

The documentation below can be **viewed locally after the code documentation repositories are cloned** locally within this container repository (run the `UpdateRepoGroup_IGLibCodeDocumentation.ps1` script to do that) and this file is open in a browser with markdown viewing addons.

* [**IGLib core documentation**](Doc/IGLib/html/index.html)
  * [index](Doc/IGLib/html/index.html), [class list](Doc/IGLib/html/annotated.html), [class hierarchy](Doc/IGLib/html/hierarchy.html) ([graphical hierarchy](Doc/IGLib/html/inherits.html)), [namespace list](Doc/IGLib/html/namespaces.html), [file list](Doc/IGLib/html/files.html)
    * [Documentation repo's README.md](Doc/IGLib/README.md)
      * [On GitHub](https://github.com/ajgorhoe/CodeDocumentation.IGLib)
* [**All** relevant IGLib-related code](Doc/IGLibAll/html/index.html)
  * [index](Doc/IGLibAll/html/index.html), [class list](Doc/IGLibAll/html/annotated.html), [class hierarchy](Doc/IGLibAll/html/hierarchy.html) ([graphical hierarchy](Doc/IGLibAll/html/inherits.html)), [namespace list](Doc/IGLibAll/html/namespaces.html), [file list](Doc/IGLibAll/html/files.html)
    * [Documentation repo's README.md](Doc/IGLibAll/README.md)
      * [On GitHub](https://github.com/ajgorhoe/CodeDocumentation.IGLibAll)
* [IGLib core documentation **with source code**](DocWithSources/IGLibWithSources/html/index.html)
  * [index](DocWithSources/IGLibWithSources/html/index.html), [class list](DocWithSources/IGLibWithSources/html/annotated.html), [class hierarchy](DocWithSources/IGLibWithSources/html/hierarchy.html) ([graphical hierarchy](DocWithSources/IGLibWithSources/html/inherits.html)), [namespace list](DocWithSources/IGLibWithSources/html/namespaces.html), [file list](DocWithSources/IGLibWithSources/html/files.html)
    * [Documentation repo's README.md](DocWithSources/IGLibWithSources/README.md)
      * [On GitHub](https://github.com/ajgorhoe/CodeDocumentation.IGLibWithSources)
* [**All** relevant IGLib-related code **with source code**](DocWithSources/IGLibAllWithSources/html/index.html)
  * [index](DocWithSources/IGLibAllWithSources/html/index.html), [class list](DocWithSources/IGLibAllWithSources/html/annotated.html), [class hierarchy](DocWithSources/IGLibAllWithSources/html/hierarchy.html) ([graphical hierarchy](DocWithSources/IGLibAllWithSources/html/inherits.html)), [namespace list](DocWithSources/IGLibAllWithSources/html/namespaces.html), [file list](DocWithSources/IGLibAllWithSources/html/files.html)
    * [Documentation repo's README.md](DocWithSources/IGLibAllWithSources/README.md)
      * [On GitHub](https://github.com/ajgorhoe/CodeDocumentation.IGLibAllWithSources)

## Using the Repository

The legacy IGLib Framework can also be cloned by the new IGLib container used for cloning and building the new IGLib. Clone the container repository at:

> *<https://github.com/ajgorhoe/iglibmodules>*

In the cloned container repository, run the update/clone scripts as necessary to clone the desired IGLib repositories, for example,

> *iglibmodules/UpdateRepos_Extended.ps1*

Change to `iglibmodules/_doc/` and run the script

> *UpdateRepo_codedoc.ps1*

This clones the [`codedoc`](https://github.com/ajgorhoe/IGLib.workspace.doc.codedoc) repository containing scripts and other tools for generating code documentation. Run the appropriate scripts in `iglibmodules/_doc/codedoc/` for generation of different kinds of code documentation, such as:

* `generate_iglib.ps1` - basic IGLib documentaton
* `generate_igliball.ps1` - extended IGLib documentation
* `generate_iglib_with_sources.ps1` - basic IGLib documentation with source code included
* `generate_iglib_all_with_sources.ps1` - extended IGLib documentation with source code included

The generated documentation can be browsed via the `code_documentation.html` omdex file. See the [codedoc readme](https://github.com/ajgorhoe/IGLib.workspace.doc.codedoc/blob/master/README.md) for more details.

## License

Copyright © Igor Grešovnik.

See [LICENSE.md](https://github.com/ajgorhoe/CodeDocumentation/blob/main/LICENSE.md) ([local version](./LICENSE.md)) for license information.

Disclaimer:  
The repository owner reserves the right to change the license to one of the permissive open source licenses, such as the Apache-2 or MIT license.
