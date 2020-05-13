<!-- This file has been generated automatically by the following script -->
<!-- C:\Christophe\Repository\writing-documentation\concat-md\concat-md.ps1 -->
<!-- So don't modify this file manually but run the tool once more instead -->

<!-- Last refresh date: 2020-05-13 22:32:13 -->

<!-- below, content of ./index.md -->

# Uses

![Banner](./images/banner.jpg)

List of some software I use in software development.

As I'm running under Windows, some of the software below may only be available for that operating system.

 <!-- table-of-contents - start -->
* [File management](#file-management)
    * [XYplorer](#xyplorer)
    * [WinSCP](#winscp)
    * [7-Zip](#7-zip)
* [Writing code](#writing-code)
    * [GIT](#git)
    * [Github](#github)
    * [Composer](#composer)
    * [NPM](#npm)
    * [Notepad++](#notepad++)
    * [Visual Studio Code](#visual-studio-code)
    * [Custom UI Editor for Microsoft Office](#custom-ui-editor-for-microsoft-office)
    * [Wamp](#wamp)
* [Documentation](#documentation)
    * [Pandoc](#pandoc)
       * [Latex](#latex)
       * [Pandoc-latex-template](#pandoc-latex-template)
    * [Mermaid](#mermaid)
    * [reveal.js](#revealjs)
* [Database management](#database-management)
    * [MySQL Workbench](#mysql-workbench)
* [Images](#images)
    * [Canvas](#canvas)
    * [Paint.net](#paintnet)
    * [Squoosh](#squoosh)
    * [Screenpresso](#screenpresso)
    * [ScreenToGif](#screentogif)
* [Browers](#browers)
    * [Internet Explorer](#internet-explorer)
    * [Chrome](#chrome)
       * [Adblock Plus](#adblock-plus)
       * [Disable Google Analytics](#disable-google-analytics)
       * [JSON Formatter](#json-formatter)
       * [LastPass](#lastpass)
       * [Stylish](#stylish)
* [Others](#others)
    * [Antidot](#antidot)
    * [LastPass](#lastpass)
    * [Spotify](#spotify)
    * [DeepL](#deepl)
<!-- table-of-contents - end -->

<!-- below, content of ./010-file-manager/readme.md -->

## File management

### XYplorer

> [https://www.xyplorer.com/](https://www.xyplorer.com/)

XYplorer is a file manager for Windows. It features tabbed browsing, a powerful file search, a versatile preview, a highly customizable interface, optional dual pane, and a large array of unique ways to efficiently automate frequently recurring tasks. It’s fast, light, and portable.

A million times better than the old, basic Windows Explorer.

XYplorer is a freemium software, you can use it for free but not all features will be available. On my own, I got a lifetime license in 2015.

*Also take a look to my [XYplorer repository](https://github.com/cavo789/tools_xyplorer).*

### WinSCP

> [https://winscp.net/eng/index.php](https://winscp.net/eng/index.php)

The FTP client of my choice.

WinSCP supports automation! ([https://github.com/cavo789/tools_winscp](https://github.com/cavo789/tools_winscp))

*Also take a look to my [WinSCP repository](https://github.com/cavo789/tools_winscp).*

### 7-Zip

> [https://www.7-zip.org/](https://www.7-zip.org/)

7-Zip is a file archiver with a high compression ratio.

<!-- below, content of ./020-code/readme.md -->

## Writing code

### GIT

> [https://git-scm.com/](https://git-scm.com/)
>
Is it useful to explain what GIT is?

### Github

> [https://github.com/](https://github.com/)

GitHub to store all my public and private repositories. Also for the documentation of tools as `wiki`.

### Composer

> [https://getcomposer.org/](https://getcomposer.org/)

To install and manage PHP dependencies.

*Also take a look to my [Composer tips](https://github.com/cavo789/composer_tips) repository.*

### NPM

> [https://www.npmjs.com/](https://www.npmjs.com/)

To install javascript tools and libraries.

### Notepad++

> [https://notepad-plus-plus.org/](https://notepad-plus-plus.org/)

A must-have to replace the very basic Notepad

### Visual Studio Code

> [https://code.visualstudio.com/](https://code.visualstudio.com/)

Visual Studio Code as my main IDE.

*Also take a look to my [Visual Studio Code tips](https://github.com/cavo789/vscode_tips) repository.*

### Custom UI Editor for Microsoft Office

> [https://bettersolutions.com/vba/ribbon/custom-ui-editor.htm](https://bettersolutions.com/vba/ribbon/custom-ui-editor.htm)

Custom UI Editor for writing ribbons for MS Excel applications.

*Also take a look to my [How to create a ribbon in Excel](https://github.com/cavo789/excel_ribbon) repository.*

### Wamp

> [http://www.wampserver.com/](http://www.wampserver.com/)

Apache localhost webserver.

*Also take a look to my [Wamp tips](https://github.com/cavo789/wamp_tips) repository*

<!-- below, content of ./030-documentation/readme.md -->

## Documentation

I don't use anymore Word or PowerPoint for my documentations, just a code editor (`Visual Studio Code` most of time) to write markdown files (`.md`).

Most of time, I'm writing multiples *small* `.md` files and I use a tool to merge them into one *big* file. That file is then used by f.i. pandoc for the `docx` generation.

*Also take a look to [markdown-tips](https://github.com/cavo789/markdown-tips) repository.*

### Pandoc

> [https://pandoc.org/](https://pandoc.org/)

Pandoc to convert markdown files to Word (`.docx`) or PDF documents.

*Also take a look to my [Pandoc](https://github.com/cavo789/pandoc) repository.*

#### Latex

> [https://www.latex-tutorial.com/installation/](https://www.latex-tutorial.com/installation/)

Needed by Pandoc to generate correct PDF output.

#### Pandoc-latex-template

> [https://github.com/Wandmalfarbe/pandoc-latex-template](https://github.com/Wandmalfarbe/pandoc-latex-template)

Very nice PDF template to be used with Pandoc for professional output.

### Mermaid

> [https://mermaid-js.github.io/mermaid-live-editor/](https://mermaid-js.github.io/mermaid-live-editor/)

Mermaid and [Mermaid.cli](https://github.com/mermaidjs/mermaid.cli) to write flow charts, diagrams, sequences, ... just using words.

Mermaid.cli as an automation tool to convert `.mmd` files (simple text files) to a `.png` so I can directly include images in my generated documentation.

### reveal.js

> [https://github.com/hakimel/reveal.js/](https://github.com/hakimel/reveal.js/)

Very nice HTML5 slideshow framework. Write your content in Markdown and run it as a beautiful HTML presentation.

<!-- below, content of ./040-database/readme.md -->

## Database management

### MySQL Workbench

> [https://www.mysql.com/products/workbench/](https://www.mysql.com/products/workbench/)

MySQL Workbench is a unified visual tool for database architects, developers, and DBAs. MySQL Workbench provides data modeling, SQL development, and comprehensive administration tools for server configuration, user administration, backup, and much more. MySQL Workbench is available on Windows, Linux and Mac OS X.

<!-- below, content of ./050-images/readme.md -->

## Images

### Canvas

> [https://www.canva.com/](https://www.canva.com/) to create banner, cards, posters, ...

I use it to create the banner above each of my repositories as well as this one. Go to the top of the page to see it.

### Paint.net

> [https://www.getpaint.net/](https://www.getpaint.net/)

Paint.NET is image and photo editing software for PCs that run Windows.

### Squoosh

> [https://squoosh.app/](https://squoosh.app/)

Online interface, nothing to install, to optimize images

### Screenpresso

> [https://www.screenpresso.com/](https://www.screenpresso.com/)

Image and Video screen capture.

### ScreenToGif

> [https://www.screentogif.com/](https://www.screentogif.com/)

Screen, webcam and sketchboard recorder with an integrated editor.

Make it really easy to create animated gifs.

<!-- below, content of ./060-browsers/readme.md -->

## Browers

### Internet Explorer

When I feel like laughing and remember how mediocre that software is.

### Chrome

> [https://www.google.com/intl/en/chrome/](https://www.google.com/intl/en/chrome/)

My main browser with a few addons.

#### Adblock Plus

> [https://chrome.google.com/webstore/detail/adblock-plus-free-ad-bloc/cfhdojbkjhnklbpkdaibdccddilifddb](https://chrome.google.com/webstore/detail/adblock-plus-free-ad-bloc/cfhdojbkjhnklbpkdaibdccddilifddb)

To remove as much as possible ads and banners on pages.

#### Disable Google Analytics

> [https://chrome.google.com/webstore/detail/google-analytics-opt-out/fllaojicojecljbmefodhfapmkghcbnh](https://chrome.google.com/webstore/detail/google-analytics-opt-out/fllaojicojecljbmefodhfapmkghcbnh)

Tells Google to not track my surf session.

#### JSON Formatter

> [https://chrome.google.com/webstore/detail/json-formatter/cfaihfocdnniaholfnjcemnfhcjchohb](https://chrome.google.com/webstore/detail/json-formatter/cfaihfocdnniaholfnjcemnfhcjchohb)

Nicely display json content.

*Also take a look to my [JSONLint](https://github.com/cavo789/jsonlint) repository.*

#### LastPass

> [https://chrome.google.com/webstore/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd](https://chrome.google.com/webstore/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd)

Add on for [LastPass](https://www.lastpass.com/)

#### Stylish

> [https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe)

When there is a real need to highlight which is the production web site, I use Stylish to inject CSS in the page to f.i. set the background color of the page to yellow (or whatever) and inject a pre-body content prefix "PRODUCTION" f.i.

<!-- below, content of ./090-others/readme.md -->

## Others

### Antidot

> [https://www.antidote.info/](https://www.antidote.info/)

Dictionaries and various proofreaders (spelling, grammar, ...).

**Paid software.**

### LastPass

> [https://www.lastpass.com/](https://www.lastpass.com/)

LastPass remembers all your passwords across every device for free!

### Spotify

> [https://www.spotify.com/](https://www.spotify.com/)

To listen music while coding.

### DeepL

> [https://www.deepl.com/translator](https://www.deepl.com/translator)
