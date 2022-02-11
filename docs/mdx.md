---
id: mdx
title: Colours
---

export const ColorBlock = ({color}) => ( <div style={{
      backgroundColor: color,
      borderRadius: '50%',
      padding: '0.5rem',
      width: '2rem',
      height: '2rem',
    }}></div> );


## Primary
| Name | Value | Token | Example |
|---|---|---|---|
| Purple 500 | #702f73 | `$gel-color-primary-purple-500` | <ColorBlock color="#702f73" />
| Purple 400 | #b056bc | `$blue-100` | <ColorBlock color="#b056bc" />
| Purple 300 | #69BDFF | `$blue-200` | 


## Secondary

## Tertiary

## Fuel


You can write JSX and use React components within your Markdown thanks to [MDX](https://mdxjs.com/).

export const Highlight = ({children, color}) => ( <span style={{
      backgroundColor: color,
      borderRadius: '2px',
      color: '#fff',
      padding: '0.2rem',
    }}>{children}</span> );

<Highlight color="#25c2a0">Docusaurus green</Highlight> and <Highlight color="#1877F2">Facebook blue</Highlight> are my favorite colors.

I can write **Markdown** alongside my _JSX_!
