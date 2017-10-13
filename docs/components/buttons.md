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

To use the Genie buttons apply the `.btn` class to any `button`, `a`, or certain types of `input` element. The `.btn` class should always be accompanied by a color class, such as `.btn-primary` or `.btn-default`.

## Button Tags

The .btn classes are designed to be used with the `<button>` element. However, you can also use these classes on `<a>` or `<input>` elements.

<p>
    <a class="btn btn-primary" href="#" role="button">Link</a>
    <button class="btn btn-primary" type="submit">Button</button>
    <input class="btn btn-primary" type="button" value="Input">
    <input class="btn btn-primary" type="submit" value="Submit">
    <input class="btn btn-primary" type="reset" value="Reset">
</p>

```html
<a class="btn btn-primary" href="#" role="button">Link</a>
<button class="btn btn-primary" type="submit">Button</button>
<input class="btn btn-primary" type="button" value="Input">
<input class="btn btn-primary" type="submit" value="Submit">
<input class="btn btn-primary" type="reset" value="Reset">
```

<div class="callout callout-warning">
    <div class="callout-heading">Accessibility Note</div>
    <p markdown="1">
        When using button classes on `<a>` elements that are used to trigger in-page functionality (like collapsing content), rather than linking to new pages or sections within the current page, these links should be given a `role="button"` to appropriately convey their purpose to assistive technologies such as screen readers.
    </p>
</div>

## Basic Buttons

<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-default">Default</button>

```html
<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-default">Default</button>
```

## Button Sizes

### Small

Use the `.btn-sm` class to create smaller buttons.

<button type="button" class="btn btn-primary btn-sm">Primary</button>
<button type="button" class="btn btn-default btn-sm">Default</button>

```html
<button type="button" class="btn btn-primary btn-sm">Primary</button>
<button type="button" class="btn btn-default btn-sm">Default</button>
```

### Large

Use the `.btn-lg` class to create larger buttons.

<button type="button" class="btn btn-primary btn-lg">Primary</button>
<button type="button" class="btn btn-default btn-lg">Default</button>

```html
<button type="button" class="btn btn-primary btn-lg">Primary</button>
<button type="button" class="btn btn-default btn-lg">Default</button>
```

### Extra Large

Use the `.btn-xl` class to create an extra large button with special formatting.

<p>
    <div class="row">
        <div class="col-6">
            <button type="button" class="btn btn-primary btn-xl btn-block">
                Yes
                <small>Continue to the next step</small>
            </button>
        </div>
        <div class="col-6">
            <button type="button" class="btn btn-default btn-xl btn-block">
                No
                <small>Go back to the previous page</small>
            </button>
        </div>
    </div>
</p>

```html
<div class="row">
    <div class="col-6">
        <button type="button" class="btn btn-primary btn-xl btn-block">
            Yes
            <small>Continue to the next step</small>
        </button>
    </div>
    <div class="col-6">
        <button type="button" class="btn btn-default btn-xl btn-block">
            No
            <small>Go back to the previous page</small>
        </button>
    </div>
</div>
```

## States

### Active

Add the `.active` class to display the button with a darker background in order to appear pressed.

<p>
    <a role="button" class="btn btn-primary active" href="#" aria-pressed="true">Primary (active)</a>
    <a role="button" class="btn btn-primary" href="#">Primary (inactive)</a>
</p>

```html
<a role="button" class="btn btn-primary active" href="#" aria-pressed="true">Primary (active)</a>
<a role="button" class="btn btn-primary" href="#">Primary (inactive)</a>
```

<div class="callout callout-warning">
    <div class="callout-heading">Accessibility Note</div>
    <p markdown="1">
        When using `<a>` elements, you should also to include the `aria-pressed="true"` attribute indicate the state of the button to assistive technologies such as screen readers.
    </p>
</div>

### Disabled

Make buttons look inactive by adding the disabled boolean attribute to any `<button>` element.

<p>
    <button type="button" class="btn btn-default">Default (enabled)</button>
    <button type="button" class="btn btn-default" disabled>Default (disabled)</button>
</p>

```html
<button type="button" class="btn btn-default">Default (enabled)</button>
<button type="button" class="btn btn-default" disabled>Default (disabled)</button>
```

## Colors

<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-success">Success</button>

```html
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-success">Success</button>
```

## Block Layout

### Full-width

<button type="button" class="btn btn-primary btn-block">Primary</button>
<button type="button" class="btn btn-default btn-block">Default</button>

```html
<button type="button" class="btn btn-primary btn-block">Primary</button>
<button type="button" class="btn btn-default btn-block">Default</button>
```

### Using Column Layouts

<p>
    <div class="row">
        <div class="col-12 col-md-4">
            <button type="button" class="btn btn-primary btn-block">Primary</button>
        </div>
        <div class="col-12 col-md-4">
            <button type="button" class="btn btn-default btn-block">Default</button>
        </div>
        <div class="col-12 col-md-4">
            <button type="button" class="btn btn-default btn-block">Default</button>
        </div>
    </div>
</p>

```html
<div class="row">
    <div class="col-12 col-md-4">
        <button type="button" class="btn btn-primary btn-block">Primary</button>
    </div>
    <div class="col-12 col-md-4">
        <button type="button" class="btn btn-default btn-block">Default</button>
    </div>
    <div class="col-12 col-md-4">
        <button type="button" class="btn btn-default btn-block">Default</button>
    </div>
</div>
```