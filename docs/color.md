---
id: color
title: Colours
---

<!-- ideally, it should import from node_modules @danielwang/aemo-design-tokens -->
import * as Token from './tokens'

export const ColorBlock = ({color}) => ( <div style={{
    backgroundColor: color,
    borderRadius: '50%',
    padding: '0.5rem',
    width: '2rem',
    height: '2rem',
  }}></div> );

export const HexCode = ({code}) => ( <div>{code}</div> );

## Primary
| Example | Name | Value | SCSS Varibles 
|---|---|---|---|
| <ColorBlock color={Token.ColorPrimaryPurple700} /> | Purple 700 | <HexCode code={Token.ColorPrimaryPurple700} /> | `$gel-color-primary-purple-700` 
| <ColorBlock color={Token.ColorPrimaryPurple600} /> | Purple 600 | <HexCode code={Token.ColorPrimaryPurple600} /> | `$gel-color-primary-purple-600` 
| <ColorBlock color={Token.ColorPrimaryPurple500} /> | Purple 500 | <HexCode code={Token.ColorPrimaryPurple500} /> | `$gel-color-primary-purple-500` 
| <ColorBlock color={Token.ColorPrimaryPurple400} /> | Purple 400 | <HexCode code={Token.ColorPrimaryPurple400} /> | `$gel-color-primary-purple-400`
| <ColorBlock color={Token.ColorPrimaryPurple300} /> | Purple 300 | <HexCode code={Token.ColorPrimaryPurple300} /> | `$gel-color-primary-purple-300`
| <ColorBlock color={Token.ColorPrimaryPurple200} /> | Purple 200 | <HexCode code={Token.ColorPrimaryPurple200} /> | `$gel-color-primary-purple-200`
| <ColorBlock color={Token.ColorPrimaryPurple100} /> | Purple 100 | <HexCode code={Token.ColorPrimaryPurple100} /> | `$gel-color-primary-purple-100`


## Secondary

| Example | Name | Value | SCSS Varibles 
|---|---|---|---|
| <ColorBlock color={Token.ColorSecondaryBlue500} /> | Blue 500 | <HexCode code={Token.ColorSecondaryBlue500} /> | `$gel-color-secondary-blue-500` 
| <ColorBlock color={Token.ColorSecondaryBlue100} /> | Blue 100 | <HexCode code={Token.ColorSecondaryBlue100} /> | `$gel-color-secondary-blue-100` 
| <ColorBlock color={Token.ColorSecondaryGreen500} /> | Green 500 | <HexCode code={Token.ColorSecondaryGreen500} /> | `$gel-color-secondary-green-500` 
| <ColorBlock color={Token.ColorSecondaryGreen100} /> | Green 100 | <HexCode code={Token.ColorSecondaryGreen100} /> | `$gel-color-secondary-green-100` 
| <ColorBlock color={Token.ColorSecondaryOrange500} /> | Orange 500 | <HexCode code={Token.ColorSecondaryOrange500} /> | `$gel-color-secondary-orange-500` 
| <ColorBlock color={Token.ColorSecondaryOrange100} /> | Orange 100 | <HexCode code={Token.ColorSecondaryOrange100} /> | `$gel-color-secondary-orange-100` 
| <ColorBlock color={Token.ColorSecondaryRed500} /> | Red 500 | <HexCode code={Token.ColorSecondaryRed500} /> | `$gel-color-secondary-red-500` 
| <ColorBlock color={Token.ColorSecondaryRed100} /> | Red 100 | <HexCode code={Token.ColorSecondaryRed100} /> | `$gel-color-secondary-red-100` 

## Tertiary
| Example | Name | Value | SCSS Varibles 
|---|---|---|---|
| <ColorBlock color={Token.ColorSecondaryBlue500} /> | Blue 500 | <HexCode code={Token.ColorSecondaryBlue500} /> | `$gel-color-secondary-blue-500` 

## Fuel
| Example | Name | Value | SCSS Varibles 
|---|---|---|---|
| <ColorBlock color={Token.ColorSecondaryBlue500} /> | Blue 500 | <HexCode code={Token.ColorSecondaryBlue500} /> | `$gel-color-secondary-blue-500` 

## Code Formats

### CSS Varibles

```css
@import url('aemo-tokens.css');

.class_name {
  color: var(--gel-color-primary-purple-500);
}
```

### Sass

```css
@import "aemo-tokens.scss";

.class_name {
  color: $gel-color-primary-purple-500;
}
```

### Less

```css
@import (reference) "aemo-tokens.less";

.class_name {
  color: @gel-color-primary-purple-500;
}
```

### JavaScript

```js
import token from 'aemo-tokens.js';

document.getElementById(id).style.color = token.ColorPrimaryPurple500;
```

### XML

Download and paste [aemo-tokens.android.xml](https://github.com/danielwang/aemo-design-tokens) to your Android project. Then:

```xml
<item android:color="@color/gel_color_primary_purple_500" />
```

### Swift

Download and paste [aemo-tokens.android.swift](https://github.com/danielwang/aemo-design-tokens) to your Swift project. Then:

```swift
tokens.gelColorPrimaryPurple500
```