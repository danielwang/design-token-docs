---
id: opacity
title: Opacity
custom_edit_url: null
---

import * as Token from './_tokens'
import ShowVar from './_showVar'

export const Opacity = ({opacity}) => ( <div style={{
    backgroundColor: Token.ColorPrimaryPurple500,
    width: '2rem',
    height: '2rem',
    opacity: opacity
  }}></div> );

| Demo | Value | SCSS Varibles 
|---|---|---|
| <Opacity opacity={Token.Opacity10} /> | <ShowVar code={Token.Opacity100} /> | `$gel-opacity-100`
| <Opacity opacity={Token.Opacity75} /> | <ShowVar code={Token.Opacity75} /> | `$gel-opacity-75`
| <Opacity opacity={Token.Opacity50} /> | <ShowVar code={Token.Opacity50} /> | `$gel-opacity-50`
| <Opacity opacity={Token.Opacity25} /> | <ShowVar code={Token.Opacity25} /> | `$gel-opacity-25`
| <Opacity opacity={Token.Opacity0} /> | <ShowVar code={Token.Opacity0} /> | `$gel-opacity-0`