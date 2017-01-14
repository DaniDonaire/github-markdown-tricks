# github-markdown-tricks

GitHub allows us to use a limited subset of HTML in our Markdown files – lets see what mischief we can do with that!

> **Note:** These tricks don't show up when you "Preview changes", you have to actually commit and view in the GitHub webinterface to see it.

## Alignment

<div align="center">This is center aligned!</div>
<div align="left">Left aligned</div>
<div align="right">Right aligned</div>

```HTML
<div align="center">This is center aligned!</div>
<div align="left">Left aligned</div>
<div align="right">Right aligned</div>
```

## Hanging indendation

<dl>
  <dt>This is a list</dt>
  <dd>With hanging indentation</dd>
  
  <dt>Another list item</dt>
  <dd>With some description that might wrap over more than one line hopefully. This is to showcase that the hanging indentation persists even with a very long description and a bunch of line breaks!</dd>
</dl>

```HTML
<dl>
  <dt>This is a list</dt>
  <dd>With hanging indentation</dd>
</dl>
```

## Meta tags

<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:creator" content="@mxstbr">
<meta name="twitter:title" content="GitHub Markdown Tricks">
<meta name="twitter:description" content="A repo full of tricks you can use in your projects README on GitHub.">
<meta name="twitter:image" content="http://graphics8.nytimes.com/images/2012/02/19/us/19whitney-span/19whitney-span-articleLarge.jpg">
