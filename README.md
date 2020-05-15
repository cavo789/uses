<!-- This file has been generated automatically by the following script -->
<!-- C:\Christophe\Repository\writing-documentation\concat-md\concat-md.ps1 -->
<!-- So don't modify this file manually but run the tool once more instead -->

<!-- Last refresh date: 2020-05-15 21:29:54 -->

<!-- below, content of ./index.md -->

# Uses

![Banner](./images/banner.jpg)

List of some software I use in software development.

As I'm running under Windows, some of the software below may only be available for that operating system.

 <!-- table-of-contents - start -->
* [File management](#file-management)
    * [7-Zip](#7-zip)
    * [WinSCP](#winscp)
    * [XYplorer](#xyplorer)
* [Writing code](#writing-code)
    * [Code quality tools](#code-quality-tools)
       * [markdownlint](#markdownlint)
       * [phan](#phan)
       * [PHP-CS-Fixer](#php-cs-fixer)
       * [PHP Mess Detector](#php-mess-detector)
       * [PHP Magic Number Detector](#php-magic-number-detector)
       * [PHPStan](#phpstan)
       * [PHP_CodeSniffer](#php_codesniffer)
    * [Composer](#composer)
    * [Custom UI Editor for Microsoft Office](#custom-ui-editor-for-microsoft-office)
    * [GIT](#git)
    * [Github](#github)
    * [Notepad++](#notepad++)
    * [NPM](#npm)
    * [regex101](#regex101)
    * [Visual Studio Code](#visual-studio-code)
    * [Wamp](#wamp)
    * [Winmerge](#winmerge)
* [Documentation](#documentation)
    * [Mermaid](#mermaid)
    * [Pandoc](#pandoc)
       * [Eisvogel](#eisvogel)
       * [Latex](#latex)
    * [reveal.js](#revealjs)
* [Database management](#database-management)
    * [MySQL Workbench](#mysql-workbench)
* [Images](#images)
    * [Canvas](#canvas)
    * [Framapic](#framapic)
    * [Paint.net](#paintnet)
    * [Screenpresso](#screenpresso)
    * [ScreenToGif](#screentogif)
    * [Squoosh](#squoosh)
* [Browsers](#browsers)
    * [Chrome](#chrome)
       * [Adblock Plus](#adblock-plus)
    * [Disable Google Analytics](#disable-google-analytics)
    * [Internet Explorer](#internet-explorer)
    * [JSON Formatter](#json-formatter)
    * [LastPass](#lastpass)
    * [Stylish](#stylish)
* [Others](#others)
    * [Antidot](#antidot)
    * [DeepL](#deepl)
    * [LastPass](#lastpass)
    * [Spotify](#spotify)
<!-- table-of-contents - end -->

<!-- below, content of ./010-file-manager/readme.md -->

## File management

<!-- below, content of ./010-file-manager/7-zip/readme.md -->

### 7-Zip

> [https://www.7-zip.org/](https://www.7-zip.org/)

🗄️ 7-Zip is a file archiver with a high compression ratio.

<!-- below, content of ./010-file-manager/winscp/readme.md -->

### WinSCP

> [https://winscp.net/eng/index.php](https://winscp.net/eng/index.php)

The FTP client of my choice.

WinSCP supports automation! ([https://github.com/cavo789/tools_winscp](https://github.com/cavo789/tools_winscp))

*Also take a look to my [WinSCP repository](https://github.com/cavo789/tools_winscp).*

<!-- below, content of ./010-file-manager/xyplorer/readme.md -->

### XYplorer

> [https://www.xyplorer.com/](https://www.xyplorer.com/)

XYplorer is a file manager for Windows. It features tabbed browsing, a powerful file search, a versatile preview, a highly customizable interface, optional dual pane, and a large array of unique ways to efficiently automate frequently recurring tasks. It’s fast, light, and portable.

A million times better than the old, basic Windows Explorer.

💶 XYplorer is a freemium software, you can use it for free but not all features will be available. On my own, I got a lifetime license in 2015.

*Also take a look to my [XYplorer repository](https://github.com/cavo789/tools_xyplorer).*

<!-- below, content of ./020-code/readme.md -->

## Writing code

<!-- below, content of ./020-code/code_quality/readme.md -->

### Code quality tools

Code quality, linter, formatting tools, ... I'm using.

<!-- below, content of ./020-code/code_quality/markdownlint/readme.md -->

#### markdownlint

> [https://github.com/DavidAnson/markdownlint](https://github.com/DavidAnson/markdownlint)

Linter for markdown files. Thanks to the `--fix` command line arguments, markdownlint will fixes errors for you like removing trailing spaces at the end of lines.

Will warn about problems like using invalid hierarchy (you use a `H3` just after a `H2`).

<!-- below, content of ./020-code/code_quality/phan/readme.md -->

#### phan

> [https://github.com/phan/phan](https://github.com/phan/phan)

Another PHP Static Code Analyzer. To use in conjunction with [PHPSTAN](#phpstan).

<!-- below, content of ./020-code/code_quality/php-cs-fixer/readme.md -->

#### PHP-CS-Fixer

> [https://github.com/FriendsOfPHP/PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)

The PHP Coding Standards Fixer (PHP CS Fixer) tool fixes your code to follow standards; whether you want to follow PHP coding standards as defined in the PSR-1, PSR-2, ...

Greatly increase code quality.

<!-- below, content of ./020-code/code_quality/phpmd/readme.md -->

#### PHP Mess Detector

> [https://phpmd.org/](https://phpmd.org/)

PHP MD is a tool to check for unused variables, dead or duplicate code (*Don't repeat yourself*), ...

<!-- below, content of ./020-code/code_quality/phpmnd/readme.md -->

#### PHP Magic Number Detector

> [https://github.com/povils/phpmnd](https://github.com/povils/phpmnd)

PHPMND will scan your code and search for number. For instance:

```php
if (mb_strlen($password) > 7) {
    throw new InvalidArgumentException("password");
}
```

and suggest to define a constant instead of hard-coding the number. With a constant, the code will immediately be more readable.

<!-- below, content of ./020-code/code_quality/phpstan/readme.md -->

#### PHPStan

> [https://github.com/phpstan/phpstan](https://github.com/phpstan/phpstan)

Static code analyzer for PHP; scan the code without running it and discovered potentials problems and give powerful hints to improve the code quality and stability.

To use in conjunction with [PHAN](#phan).

<!-- below, content of ./020-code/code_quality/php_codesniffer/readme.md -->

#### PHP_CodeSniffer

> [https://github.com/squizlabs/PHP_CodeSniffer/](https://github.com/squizlabs/PHP_CodeSniffer/)

PHP_CodeSniffer tokenizes PHP, JavaScript and CSS files and detects violations of a defined set of coding standards.

Thanks to `phpcbf`, PHP_CodeSniffer will reformat the code to respect standards (by default `PSR2` rules) and fix some formatting errors for you.

Then `phpcs` will warn about other violations you'll need to fix manually.

<!-- below, content of ./020-code/composer/readme.md -->

### Composer

> [https://getcomposer.org/](https://getcomposer.org/)

To install and manage PHP dependencies.

*Also take a look to my [Composer tips](https://github.com/cavo789/composer_tips) repository.*

<!-- below, content of ./020-code/custom_ui_editor/readme.md -->

### Custom UI Editor for Microsoft Office

> [https://bettersolutions.com/vba/ribbon/custom-ui-editor.htm](https://bettersolutions.com/vba/ribbon/custom-ui-editor.htm)

Custom UI Editor for writing ribbons for MS Excel applications.

<!-- below, content of ./020-code/git/readme.md -->

### GIT

> [https://git-scm.com/](https://git-scm.com/)

Is it useful to explain what GIT is?

<!-- below, content of ./020-code/github/readme.md -->

### Github

> [https://github.com/](https://github.com/)

GitHub to store all my public and private repositories. Also for the documentation of tools as `wiki`.

<!-- below, content of ./020-code/notepadplusplus/readme.md -->

### Notepad++

> [https://notepad-plus-plus.org/](https://notepad-plus-plus.org/)

A must-have to replace the very basic Notepad

<!-- below, content of ./020-code/npm/readme.md -->

### NPM

> [https://www.npmjs.com/](https://www.npmjs.com/)

To install javascript tools and libraries.

<!-- below, content of ./020-code/regex101/readme.md -->

### regex101

> [https://regex101.com/](https://regex101.com/)

To create regular expressions and immediately test them.

<!-- below, content of ./020-code/vscode/readme.md -->

### Visual Studio Code

> [https://code.visualstudio.com/](https://code.visualstudio.com/)

Visual Studio Code as my main IDE.

*Also take a look to my [Visual Studio Code tips](https://github.com/cavo789/vscode_tips) repository.*

<!-- below, content of ./020-code/wamp/readme.md -->

### Wamp

> [http://www.wampserver.com/](http://www.wampserver.com/)

Apache localhost webserver.

*Also take a look to my [Wamp tips](https://github.com/cavo789/wamp_tips) repository*

<!-- below, content of ./020-code/winmerge/readme.md -->

### Winmerge

> [https://winmerge.org/](https://winmerge.org/)

To compare two files and detect differences. Works for folders too.
*Also take a look to my [How to create a ribbon in Excel](https://github.com/cavo789/excel_ribbon) repository.*

<!-- below, content of ./030-documentation/readme.md -->

## Documentation

I don't use anymore Word or PowerPoint for my documentations, just a code editor (`Visual Studio Code` most of time) to write markdown files (`.md`).

Most of time, I'm writing multiples *small* `.md` files and I use a tool to merge them into one *big* file. That file is then used by f.i. pandoc for the `docx` generation.

*Also take a look to [markdown-tips](https://github.com/cavo789/markdown-tips) repository.*

<!-- below, content of ./030-documentation/mermaid/readme.md -->

### Mermaid

> [https://mermaid-js.github.io/mermaid-live-editor/](https://mermaid-js.github.io/mermaid-live-editor/)

Mermaid and [Mermaid.cli](https://github.com/mermaidjs/mermaid.cli) to write flow charts, diagrams, sequences, ... just using words.

Mermaid.cli as an automation tool to convert `.mmd` files (simple text files) to a `.png` so I can directly include images in my generated documentation.

<!-- below, content of ./030-documentation/pandoc/readme.md -->

### Pandoc

> [https://pandoc.org/](https://pandoc.org/)

Pandoc to convert markdown files to Word (`.docx`) or PDF documents.

*Also take a look to my [Pandoc](https://github.com/cavo789/pandoc) repository.*

<!-- below, content of ./030-documentation/pandoc/eisvogel/readme.md -->

#### Eisvogel

> [Eisvogel](https://github.com/Wandmalfarbe/pandoc-latex-template)

Very nice PDF template to be used with Pandoc for professional output.

<!-- below, content of ./030-documentation/pandoc/latex/readme.md -->

#### Latex

> [https://www.latex-tutorial.com/installation/](https://www.latex-tutorial.com/installation/)

Needed by Pandoc to generate correct PDF output.

<!-- below, content of ./030-documentation/revealjs/readme.md -->

### reveal.js

> [https://github.com/hakimel/reveal.js/](https://github.com/hakimel/reveal.js/)

Very nice HTML5 slideshow framework. Write your content in Markdown and run it as a beautiful HTML presentation.

<!-- below, content of ./040-database/readme.md -->

## Database management

<!-- below, content of ./040-database/mysql_workbench/readme.md -->

### MySQL Workbench

> [https://www.mysql.com/products/workbench/](https://www.mysql.com/products/workbench/)

MySQL Workbench is a unified visual tool for database architects, developers, and DBAs. MySQL Workbench provides data modeling, SQL development, and comprehensive administration tools for server configuration, user administration, backup, and much more. MySQL Workbench is available on Windows, Linux and Mac OS X.

<!-- below, content of ./050-images/readme.md -->

## Images

<!-- below, content of ./050-images/canvas/readme.md -->

### Canvas

> [https://www.canva.com/](https://www.canva.com/) to create banner, cards, posters, ...

I use it to create the banner above each of my repositories as well as this one. Go to the top of the page to see it.

<!-- below, content of ./050-images/framapic/readme.md -->

### Framapic

> [https://framapic.org/](https://framapic.org/)

When I need to publish temporarily an image on internet before, f.i., using it in a forum or if I need to send it by email (useful for animated gif f.i. not supported in emails).

<!-- below, content of ./050-images/paint/readme.md -->

### Paint.net

> [https://www.getpaint.net/](https://www.getpaint.net/)

Paint.NET is image and photo editing software for PCs that run Windows.

<!-- below, content of ./050-images/screenpresso/readme.md -->

### Screenpresso

> [https://www.screenpresso.com/](https://www.screenpresso.com/)

Image and Video screen capture.

<!-- below, content of ./050-images/screentogif/readme.md -->

### ScreenToGif

> [https://www.screentogif.com/](https://www.screentogif.com/)

Screen, webcam and sketchboard recorder with an integrated editor.

Make it really easy to create animated gifs.

<!-- below, content of ./050-images/squoosh/redme.md -->

### Squoosh

> [https://squoosh.app/](https://squoosh.app/)

Online interface, nothing to install, to optimize images

<!-- below, content of ./060-browsers/readme.md -->

## Browsers

<!-- below, content of ./060-browsers/chrome/readme.md -->

### Chrome

> [https://www.google.com/intl/en/chrome/](https://www.google.com/intl/en/chrome/)

My main browser with a few addons.

<!-- below, content of ./060-browsers/chrome/addblockplus/readme.md -->

#### Adblock Plus

> [https://chrome.google.com/webstore/detail/adblock-plus-free-ad-bloc/cfhdojbkjhnklbpkdaibdccddilifddb](https://chrome.google.com/webstore/detail/adblock-plus-free-ad-bloc/cfhdojbkjhnklbpkdaibdccddilifddb)

To remove as much as possible ads and banners on pages.

<!-- below, content of ./060-browsers/disable_ganalytics/readme.md -->

### Disable Google Analytics

> [https://chrome.google.com/webstore/detail/google-analytics-opt-out/fllaojicojecljbmefodhfapmkghcbnh](https://chrome.google.com/webstore/detail/google-analytics-opt-out/fllaojicojecljbmefodhfapmkghcbnh)

Tells Google to not track my surf session.

<!-- below, content of ./060-browsers/ie/readme.md -->

### Internet Explorer

When I feel like laughing and remember how mediocre that software is 😂.

<!-- below, content of ./060-browsers/json_formatter/readme.md -->

### JSON Formatter

> [https://chrome.google.com/webstore/detail/json-formatter/cfaihfocdnniaholfnjcemnfhcjchohb](https://chrome.google.com/webstore/detail/json-formatter/cfaihfocdnniaholfnjcemnfhcjchohb)

Nicely display json content.

*Also take a look to my [JSONLint](https://github.com/cavo789/jsonlint) repository.*

<!-- below, content of ./060-browsers/lastpass/readme.md -->

### LastPass

> [https://chrome.google.com/webstore/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd](https://chrome.google.com/webstore/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd)

Addon for [LastPass](https://www.lastpass.com/)

<!-- below, content of ./060-browsers/stylish/readme.md -->

### Stylish

> [https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe)

When there is a real need to highlight which is the production web site, I use Stylish to inject CSS in the page to f.i. set the background color of the page to yellow (or whatever) and inject a pre-body content prefix "PRODUCTION" f.i.

<!-- below, content of ./090-others/readme.md -->

## Others

<!-- below, content of ./090-others/antidot/readme.md -->

### Antidot

> [https://www.antidote.info/](https://www.antidote.info/)

🗸 Dictionaries and various proofreaders (spelling, grammar, ...)

💶 **Paid software.**

<!-- below, content of ./090-others/deepl/readme.md -->

### DeepL

> [https://www.deepl.com/translator](https://www.deepl.com/translator)

🌐 Online translation. Give really nice results.

<!-- below, content of ./090-others/lastpass/readme.md -->

### LastPass

> [https://www.lastpass.com/](https://www.lastpass.com/)

🔑 LastPass remembers all your passwords across every device for free!

<!-- below, content of ./090-others/spotify/readme.md -->

### Spotify

> [https://www.spotify.com/](https://www.spotify.com/)

🎧 To listen music while coding.
