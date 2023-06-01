# Xperience Community: VS Code Snippets

A collection of VS Code snippets for Xperience by Kentico, distributed as a VS Code extension

![Animation of snippet being used in VS Code](https://raw.githubusercontent.com/seangwright/xperience-community-vscode-snippets/main/images/snippets-workflow.webp)

## Installation

Install the snippet extension through:

- [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=SeanGWright.xperience-community-vscode-snippets)
- VS Code's Extensions tray by searching for the extension name `Xperience Community VS Code Snippets`
- VS Code's Extensions tray by searching for the extension identifier `SeanGWright.xperience-community-vscode-snippets`

## Snippets

All of the snippets below can be used [using VS Code's snippet Intelliense](https://code.visualstudio.com/docs/editor/userdefinedsnippets) or by [replacing an entire file's contents](https://code.visualstudio.com/docs/editor/userdefinedsnippets#_file-template-snippets).

All snippet generated content is populated by the file name of the file you are using the snippet in. For example, using the `xpc-page-builder-widget` snippet in a file named `HeroWidget` would generate code with C# classes named `HeroWidget`, `HeroWidgetProperties`, and `HeroWidgetViewModel`.

For the best results, name your files with the suffix specified in the table below.

Following the conventions

| Snippet prefix               | Filename suffix convention | Description                                                                                                                                       |
| ---------------------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| xpc-admin-module             | \*AdminModule.cs           | [Admin module](https://docs.xperience.io/x/zgSiCQ) to register customizations and client-side code and define new UI category                     |
| xpc-admin-template           | \*Page.cs                  | [Admin UI Page](https://docs.xperience.io/x/0wSiCQ) with a custom template                                                                        |
| xpc-admin-application        | \*ApplicationPage.cs       | [Admin UI Application Page](https://docs.xperience.io/x/2gSiCQ) to create a root UI application                                                   |
| xpc-admin-listing            | \*ListingPage.cs           | [Admin UI Listing Page](https://docs.xperience.io/x/1oouCw) to list built-in or custom data types in a table                                      |
| xpc-admin-page-extender      | \*PageExtender.cs          | [Admin UI Page Extender](https://docs.xperience.io/x/4gSiCQ) to add or modify functionality of existing pages                                     |
| xpc-page-builder-widget      | \*Widget.cs                | [Page Builder Widget](https://docs.xperience.io/x/7gWiCQ) with properties, view model, and registration                                           |
| xpc-page-builder-section     | \*Section.cs               | [Page Builder Section](https://docs.xperience.io/x/9AWiCQ) with properties, view model, and registration                                          |
| xpc-ui-form-component        | \*FormComponent.cs         | [Admin UI Form Component](https://docs.xperience.io/x/5ASiCQ) with properties, attribute, and registration                                        |
| xpc-ui-form-component-client | \*FormComponent.tsx        | [Admin UI Form Component - Client](https://docs.xperience.io/x/5ASiCQ) React component for rendering the component and managing client-side state |
| xpc-validation-rule          | \*ValidationRule.cs        | [Admin UI Form Component Validation Rule](https://docs.xperience.io/x/6QSiCQ) with registration, attribute, properties, and client properties     |
| xpc-validation-rule-client   | \*ValidationRule.tsx       | [Admin UI Form Component Validation Rule - Client](https://docs.xperience.io/x/6QSiCQ) React component for rendering and client-side state        |
| xpc-visibility-condition     | \*VisibilityCondition.cs   | [Admin UI Form Component Visibility Condition](https://docs.xperience.io/x/7gSiCQ) with registration, properties, and attribute                   |

## Contributions

If you discover a problem, please [open an issue](https://github.com/seangwright/xperience-community-vscode-snippets/issues/new).

If you would like contribute to the code or documentation, please [open a pull request](https://github.com/seangwright/xperience-community-vscode-snippets/compare).
