<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/hubwriter/open-reusables/master/images/open-reusable-icon.png" alt="logo">
  <br>
  Open a reusable
  <br>
</h1>
<br>

## Overview

This Visual Studio Code extension works with markdown files in the [`docs-internal`](https://github.com/github/docs-internal) and [`docs`](https://github.com/github/docs) repositories. While you are displaying a markdown file for a GitHub help article, you can click the Liquid tag for a variable or a reusable, or the opening tag for feature-based versioning, and then run the extension to open the variable or reusable file in a new tab. 

You can also quickly copy a variable or a reusable. Handy for when you need to use the same variable more than once in a topic.

## Using the extension

* To open a reusable file, a variable file, or a feature-based versioning file:

   Either select some markdown containing a reusable, a variable, or a feature-based versioning tag, or just click inside the tag to place the cursor there, then press:

   **Mac**: <kbd>control</kbd> + <kbd>command</kbd> + <kbd>o</kbd>
   
   **Windows**: <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>o</kbd>

* To copy a [Liquid tag](https://shopify.github.io/liquid/tags/control-flow/), such as the reference to a reusable or variable:

   Click inside the tag to place the cursor there, then press:

   **Mac**: <kbd>control</kbd> + <kbd>command</kbd> + <kbd>c</kbd>

   **Windows**: <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>c</kbd>

Alternatively run the extension from the command palette by choosing **Open reusable file** or **Copy the reusable at the cursor position**.

## Installing the extension

To install this extension:

1. Download the lastest `.vsix` package file from the [https://github.com/hubwriter/open-reusables](https://github.com/hubwriter/open-reusables#) repository.

1. Launch VS Code and display the extensions panel:

   ![Extensions panel](https://raw.githubusercontent.com/hubwriter/open-reusables/master/images/extension-installation1.png)

1. Click the ellipsis button (top right of the panel).

1. Choose **Install from VSIX**:

   ![Install from VSIX option](https://raw.githubusercontent.com/hubwriter/open-reusables/master/images/extension-installation2.png)

1. Browse to the `.vsix` file and click **Install**.

