---
layout: page
title: Buttons
description: The `.btn` class is designed to be used with the `<button>` element. However, you can also use these classes on `<a>` or `<input>` elements (though some browsers may apply a slightly different rendering).
group: components
permalink: /docs/components/buttons
status: Work in Progress
owner: macklin.hartley
---

## How to use

To use the Genie buttons apply the `.btn` class to any `button`, `a`, or `input type=button` element. The `.btn` class should always be accompanied by a color class, such as `.btn-primary`.

## Button Colors

<button type="button" class="mr-3 mb-3 btn btn-primary">Primary</button>
<button type="button" class="mr-3 mb-3 btn btn-default">Default</button>
<br/>
<button type="button" class="mr-3 mb-3 btn btn-danger">Danger</button>
<button type="button" class="mr-3 mb-3 btn btn-warning">Warning</button>
<button type="button" class="mr-3 mb-3 btn btn-info">Info</button>
<button type="button" class="mr-3 mb-3 btn btn-success">Success</button>

```html
<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-default">Default</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-link">Link</button>
```

## Button Sizes

<button type="button" class="mr-3 mb-3 btn btn-primary btn-lg">Primary</button>
<button type="button" class="mr-3 mb-3 btn btn-default btn-lg">Default</button>

```html
<button type="button" class="btn btn-primary btn-lg">Primary</button>
<button type="button" class="btn btn-default btn-lg">Default</button>
```

<button type="button" class="mr-3 mb-3 btn btn-primary btn-sm">Primary</button>
<button type="button" class="mr-3 mb-3 btn btn-default btn-sm">Default</button>

```html
<button type="button" class="btn btn-primary btn-sm">Primary</button>
<button type="button" class="btn btn-default btn-sm">Default</button>
```