---
id: color
title: Colours
---

<!-- ideally, it should import from node_modules @danielwang/aemo-design-tokens -->
import * as Token from './_tokens'

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
| <ColorBlock color={Token.ColorSecondaryTeal} /> | Teal | <HexCode code={Token.ColorSecondaryTeal} /> | `$gel-color-secondary-teal` 
| <ColorBlock color={Token.ColorSecondaryYellow} /> | Yellow | <HexCode code={Token.ColorSecondaryYellow} /> | `$gel-color-secondary-yellow` 
| <ColorBlock color={Token.ColorSecondaryAqua} /> | Aqua | <HexCode code={Token.ColorSecondaryAqua} /> | `$gel-color-secondary-aqua` 
| <ColorBlock color={Token.ColorSecondaryBlueViolet} /> | Blue Violet | <HexCode code={Token.ColorSecondaryBlueViolet} /> | `$gel-color-secondary-blue-violet` 

## Tertiary
| Example | Name | Value | SCSS Varibles 
|---|---|---|---|
| <ColorBlock color={Token.ColorTertiaryLink} /> | Link | <HexCode code={Token.ColorTertiaryLink} /> | `$gel-color-tertiary-link`
| <ColorBlock color={Token.ColorTertiaryBlack} /> | Black | <HexCode code={Token.ColorTertiaryBlack} /> | `$gel-color-tertiary-black`
| <ColorBlock color={Token.ColorTertiaryWhite} /> | White | <HexCode code={Token.ColorTertiaryWhite} /> | `$gel-color-tertiary-white`  
| <ColorBlock color={Token.ColorTertiarySlate700} /> | Slate 700 | <HexCode code={Token.ColorTertiarySlate700} /> | `$gel-color-tertiary-slate-700`  
| <ColorBlock color={Token.ColorTertiarySlate500} /> | Slate 500 | <HexCode code={Token.ColorTertiarySlate500} /> | `$gel-color-tertiary-slate-500`  
| <ColorBlock color={Token.ColorTertiarySlate300} /> | Slate 300 | <HexCode code={Token.ColorTertiarySlate300} /> | `$gel-color-tertiary-slate-300`  
| <ColorBlock color={Token.ColorTertiarySlate100} /> | Slate 100 | <HexCode code={Token.ColorTertiarySlate100} /> | `$gel-color-tertiary-slate-100`  
| <ColorBlock color={Token.ColorTertiarySlate50} /> | Slate 50 | <HexCode code={Token.ColorTertiarySlate50} /> | `$gel-color-tertiary-slate-50`  

## Fuel
| Example | Name | Value | SCSS Varibles 
|---|---|---|---|
| <ColorBlock color={Token.ColorFuelCoal} /> | Coal | <HexCode code={Token.ColorFuelCoal} /> | `$gel-color-fuel-coal` 
| <ColorBlock color={Token.ColorFuelBrownCoal} /> | Brown Coal | <HexCode code={Token.ColorFuelBrownCoal} /> | `$gel-color-fuel-brown-coal` 
| <ColorBlock color={Token.ColorFuelDistilate} /> | Distilate | <HexCode code={Token.ColorFuelDistilate} /> | `$gel-color-fuel-distilate` 
| <ColorBlock color={Token.ColorFuelBiomass} /> | Biomass | <HexCode code={Token.ColorFuelBiomass} /> | `$gel-color-fuel-biomass` 
| <ColorBlock color={Token.ColorFuelSolar} /> | Solar | <HexCode code={Token.ColorFuelSolar} /> | `$gel-color-fuel-solar` 
| <ColorBlock color={Token.ColorFuelWind} /> | Wind | <HexCode code={Token.ColorFuelWind} /> | `$gel-color-fuel-wind` 
| <ColorBlock color={Token.ColorFuelHydro} /> | Hydro | <HexCode code={Token.ColorFuelHydro} /> | `$gel-color-fuel-hydro` 
| <ColorBlock color={Token.ColorFuelRenewables} /> | Renewables | <HexCode code={Token.ColorFuelRenewables} /> | `$gel-color-fuel-renewables` 
| <ColorBlock color={Token.ColorFuelDemandSide} /> | DemandSide | <HexCode code={Token.ColorFuelDemandSide} /> | `$gel-color-fuel-demandSide` 
| <ColorBlock color={Token.ColorFuelLandfillGas} /> | Landfill Gas | <HexCode code={Token.ColorFuelLandfillGas} /> | `$gel-color-fuel-landfill-gas` 
| <ColorBlock color={Token.ColorFuelSatPvOrSolarThermal} /> | SatPvOrSolarThermal | <HexCode code={Token.ColorFuelSatPvOrSolarThermal} /> | `$gel-color-fuel-sat-pv-or-solar-thermal` 
| <ColorBlock color={Token.ColorFuelBattery} /> | Battery | <HexCode code={Token.ColorFuelBattery} /> | `$gel-color-fuel-battery` 
| <ColorBlock color={Token.ColorFuelBatteryLoad } /> | Battery Load  | <HexCode code={Token.ColorFuelBatteryLoad } /> | `$gel-color-fuel-battery-load ` 
| <ColorBlock color={Token.ColorFuelVppBatteryLoad} /> | Vpp Battery Load | <HexCode code={Token.ColorFuelVppBatteryLoad} /> | `$gel-color-fuel-vpp-battery-load` 
| <ColorBlock color={Token.ColorFuelMain} /> | Main | <HexCode code={Token.ColorFuelCoal} /> | `$gel-color-fuel-main` 
| <ColorBlock color={Token.ColorFuelLoad} /> | Load | <HexCode code={Token.ColorFuelLoad} /> | `$gel-color-fuel-load` 

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