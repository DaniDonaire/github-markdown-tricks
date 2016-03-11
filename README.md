# github-markdown-tricks

Github allows us to use a limited subset of HTML in our Markdown files – lets see what mischief we can do with that!

## Alignment

<div align="center">This is center aligned!</div>
<div align="left">Left aligned</div>
<div align="right">Right aligned</div>

```HTML
<div align="center">This is center aligned!</div>
<div align="left">Left aligned</div>
<div align="right">Right aligned</div>
```

## Columns

<table>
  <tr>
    <td>Left Column</td>
  </tr>
  <tr>
    <td>Right Column</td>
  </tr>
</table>

```HTML
<div align="left" width="100">Left column</div><div align="right" width="100">Right column</div>
```
