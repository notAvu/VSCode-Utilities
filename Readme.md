# VSCode Utilities Repo

This repo contains a collection of useful stuff and customization elements for Visual Studio code.

# [Content table](#contents)
- [VSCode Utilities Repo](#vscode-utilities-repo)
- [Content table](#content-table)
- [Shortucts](#shortucts)
- [User Snippets](#user-snippets)
  - [Guide](#guide)
  - [Html (html-snippets.json)](#html-html-snippetsjson)
    - [Html document with Bootstrap](#html-document-with-bootstrap)
    - [#region](#region)


<div style="page-break-after: always;"></div>

# [Shortucts](#shortucts)


# [User Snippets](#snippets) 
In VSCode you can define code snippets that can be accessed with simple words (like for loops or other pre-defined snippets). 
## [Guide](#guide)
TODO 
## [Html](#snippet-html) ([html-snippets.json](./Snippets/html-snippets)) 

  ### [Html document with Bootstrap](#snippets-html-bootstrap)
  An html document with basic Bootstrap 5 implementation
  
  **Shortcuts:** bootstrap
  ### [#region](#snippets-html-code-region)
  Define a code region between the #region and #endregion tag like C# regions

  **Shortcuts:** region, reg
  
  **Usage:**
  ```html
  <!-- #region [name] -->
  <article>
    <p>Region's content</p>
  </article>
  <!-- #endregion -->
  ```