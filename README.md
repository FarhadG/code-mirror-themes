CodeMirror Themes
=================

CodeMirror is a great online editor, however, it's lacking some good themes. So, here are a crap ton for your coding pleasure.

I used this <a href="https://github.com/FarhadG/codeMirror-aceEditor-theme-generator" target="_blank">theme generator</a> to export themes from editors such as Sublime Text, Ace Editor and TextMate.

If something is not working or you would like a new feature, please use the issues page.


## Demo

Here's a theme I extracted from one of my favorite Sublime Themes (itg-flat).

<a href="http://farhadg.github.io/code-mirror-themes/" target="_blank"><img style='width: 100%' src='http://i58.tinypic.com/28vrkt1.png' /></a>

Click <a href="http://farhadg.github.io/code-mirror-themes/" target="_blank">HERE</a> for a demo where you can switch between various themes on the fly. A few modifications were made to the base styling to make the default theme look better; e.g. line-heights, fonts, etc. Some version have a default version included (from CodeMirror).


## Installation

You can install via `bower` and simply refer to the theme you want within the `themes` directory.

```
  $ bower i code-mirror-themes --save
```

You can simply fork and clone (or download) the repo into your local directory and check out the themes folder for the CSS files.

```
  $ git clone https://github.com/FarhadG/code-mirror-themes
  $ cd code-mirror-themes/themes
```

You can also run a server to run `index.html` for a demo showcasing all of the themes.


## Usage

Once you have the desired CSS file, you simply configure your CodeMirror editor and pass in the theme's name as the CodeMirror theme name (use lowercase and treat spaces with hyphens). For example, here's a simple configuration.

```javascript
// Theme Name: Bespin
var myCodeMirror = CodeMirror(document.body, {
    mode: 'javascript',
    lineNumbers: true,
    theme: 'bespin'
});

// Theme Name: All Hallow Eve
var myCodeMirror = CodeMirror(document.body, {
    mode: 'javascript',
    lineNumbers: true,
    theme: 'all-hallow-eve'
});
```


## GUI Interface

Also, here's a <a href="http://tmtheme-editor.herokuapp.com/" target="_blank">LINK</a> for making SublimeText and TextMate themes with a visual interface. After saving the file, you can, then, take the file and run this <a href="https://github.com/FarhadG/codeMirror-aceEditor-theme-generator" target="_blank">theme generator</a> for converting the XML to CodeMirror's CSS.


## Options

I'll be adding more features; that said, if you'd like a feature, let me know so that I'll try and implement it into future updates.
