---
home: true
tagline: A simple syntax for complex argumentation
heroText: Argdown
heroImage: /argdown-arrow.png
actionText: Get Started →
actionLink: /guide/
features:
- title: Simple
  details: Writing pro & contra lists in Argdown is as simple as writing a Twitter message. You don't have to learn anything new, except a few simple rules that will feel very natural. 
- title: Expressive
  details: With these simple rules you will be able to define complex dialectical relations between arguments or dive into the details of their logical premise-conclusion structures. 
- title: Powerful
  details: Your document is transformed into an argument map while you are typing. You can export your analysis as HTML, SVG, PDF, PNG or JSON. If that is not enough, you can easily extend Argdown with your own plugin.

footer: MIT Licensed | Copyright © 2018-present Christian Voigt | Funded by Debatelab, KIT Karlsuhe

---

## Learn Argdown in 3 Minutes

Argdown's formula consists of three ingredients:

### _1_ Nested pro-contra-lists

Statement titles come in square brackets, argument titles in angle brackets.

```argdown
[Argdown is the best]: Argdown is the best 
tool for analyzing complex argumentation 
and creating argument maps.
  - <Editors easier>: Argument map editors 
    are way easier to use. #pro-editor
    + <WYSIWYG>: In argument map editors what 
      you see during editing is what you get 
      at the end: an argument map. #pro-editor
  + <Pure Data>: With Argdown no user interface 
    gets in your way. You can focus on writing 
    without getting distracted.
```

Click on the **Map** button in the upper right corner to see the resulting argument map.

### _2_ Premise-conclusion-structures

Let's logically reconstruct an additional argument in detail:

```argdown
<Word Analogy>

(1) [Word @#*%!]: It is much easier to write 
    and format a text with Markdown than it is with Word.
(2) Markdown and Word are comparable in their ease of use 
    to Argdown and argument map editors respectively.
----
(3) It is much easier to analyze complex argumentation and 
    create argument maps with Argdown than it is with 
    argument map editors.
    -> <Editors easier>


[Argdown is the best]
  - <Editors easier> #pro-editor
    + <WYSIWYG> #pro-editor
  + <Pure Data>
```

Click on the **Map** button in the upper right corner to see the resulting argument map.

### _3_ Markdown-like text-formatting

```argdown
# Headings are used to group statement and arguments in the map

You can use __many__  (though not all) *features* of [Markdown](http://commonmark.org/) to format Argdown text.
And you can use #hashtags to color statements and arguments in the map.
```

For this example, no map will be generated, as the Argdown source code contains no statements or arguments connected by support or attack relations.

## Getting started

Now that you have learned the basics of Argdown you can:

::: buttonlist

* [Browser Sandbox](https://christianvoigt.github.io/argdown/sandbox/) Try out Argdown in your browser. Includes a live preview of the generated map.
* [VS Code Extension](/guide/installing-the-vscode-extension.html) Install the Argdown VS Code extension for full Argdown language support in one of the best code editors around. Includes a live preview, syntax highlighting, content assist, code linting and export options.
* [Commandline Tool](/guide/installing-the-commandline-tool.html) If you prefer to work with the commandline install the Argdown commandline tool. You can define custom processes in your config file and use them in a task runner to export several argument maps for the same document at once.

:::

If you are getting unexpected results in your map, take a look at the [syntax rules](/syntax) of Argdown and do not forget to separate top-level elements by empty lines.