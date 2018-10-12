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

## Hanging indentation

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

## Expandable Content

<details>
  <summary>Expandable ipsum</summary>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean vehicula enim velit, ac maximus felis fermentum vitae. Suspendisse gravida in augue eget vehicula. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus mattis ultricies tortor. Suspendisse ut dignissim libero. Mauris nec finibus diam, at cursus tortor. Pellentesque in pretium odio.

  Ut et est quis ex laoreet mollis ac nec enim. Donec hendrerit lacus eget nisi cursus aliquet. Donec lacinia mauris urna, ac consequat arcu accumsan sit amet. Etiam in faucibus lectus. Aliquam ultrices ligula ligula, nec efficitur dui vulputate non. Quisque pulvinar feugiat sodales. Donec egestas nunc vel lobortis convallis.
</details>

```HTML
<details>
  <summary>label</summary>
  ...goodies in here.
</details>
```
