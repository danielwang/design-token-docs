---
id: code
title: Code Formats Supported
custom_edit_url: null
---


## CSS Varibles

```css
@import url('aemo-tokens.css');

.class_name {
  color: var(--gel-color-primary-purple-500);
}
```

## Sass

```css
@import "aemo-tokens.scss";

.class_name {
  color: $gel-color-primary-purple-500;
}
```

## Less

```css
@import (reference) "aemo-tokens.less";

.class_name {
  color: @gel-color-primary-purple-500;
}
```

## JavaScript

```js
import token from 'aemo-tokens.js';

document.getElementById(id).style.color = token.ColorPrimaryPurple500;
```

## XML

Download and paste [aemo-tokens.android.xml](https://github.com/danielwang/aemo-design-tokens) to your Android project. Then:

```xml
<item android:color="@color/gel_color_primary_purple_500" />
```

## Swift

Download and paste [aemo-tokens.android.swift](https://github.com/danielwang/aemo-design-tokens) to your Swift project. Then:

```swift
tokens.gelColorPrimaryPurple500
```