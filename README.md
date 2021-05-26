# Even More IntelliJ SDK Code Samples
Unofficial IntelliJ SDK Code Samples that Might Not Fit Into the Main SDK Docs

## Structure

Code Samples depend on the [IntelliJ Platform SDK][docs] and [Gradle][docs:gradle] as a build system.

The main plugin definition file is stored in the `plugin.xml` file, which is created according to the [Plugin Configuration File documentation][docs:plugin.xml].
It describes definitions of the actions, extensions, or listeners provided by the plugin.

## Code Samples

In the following table, you may find all available samples provided in the separated directories as stand-alone projects available for running with the Gradle `:runIde` task.

| Code Sample                                                                             | Description                                                                                                                                            |
| ----------------------------------------------------------------------                  | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Directory Project Generator](./directory_project_generator)                            | Alternate way to add project types `File \| New \| Project...` in some of the smaller IDE's.                                                           |
| [Github Tag Downloaded Project Generator](./github_tag_downloaded_project_generator)    | Create a project using files from GitHub with the ability to select a specific version.                                                                 |

[gh:workflow-code-samples]: https://github.com/JetBrains/intellij-sdk-docs/actions?query=workflow%3ACode%20Samples
[gh:template]: https://github.com/JetBrains/intellij-platform-plugin-template

[jb:confluence-on-gh]: https://confluence.jetbrains.com/display/ALL/JetBrains+on+GitHub
[jb:docs]: https://plugins.jetbrains.com/docs/intellij/
[jb:products]: https://www.jetbrains.com/products.html
[jb:slack]: https://plugins.jetbrains.com/slack
[jb:twitter]: https://twitter.com/JBPlatform

[docs]: https://plugins.jetbrains.com/docs/intellij/
[docs:eps]: https://plugins.jetbrains.com/docs/intellij/extension-point-list.html
[docs:gradle]: https://plugins.jetbrains.com/docs/intellij/gradle-build-system.html
[docs:plugin.xml]: https://plugins.jetbrains.com/docs/intellij/plugin-configuration-file.html
[docs:explore-api]: https://plugins.jetbrains.com/docs/intellij/explore-api.html