---
title: Susan's page
---
export const Highlight = ({children, color}) => (
  <span
    style={{
      backgroundColor: color,
      borderRadius: '2px',
      color: '#fff',
      padding: '0.2rem',
    }}>
    {children}
  </span>
);

<Highlight color="#25c2a0">Docusaurus green</Highlight> and <Highlight color="#1877F2">Facebook blue</Highlight> are my favorite colors.

I can write **Markdown** alongside my _JSX_!

## Let's try this another way
I can conveniently use <Highlight color="#25c2a0">Docusaurus green</Highlight> everywhere!

Let's add some text

## Admonition time
:::note
Some information goes here
:::

:::tip
Here's a tip: use the built-in admonitions to draw attention
:::
:::info
This is different from a Note somehow
:::
:::caution
Be careful, there
:::
:::danger
Now you've really done it
:::
### Inline custom admonitions
<Admonition type="caution" icon="✨" title="New in 8.1.23">
  <p>
    This feature is new!
  </p>
</Admonition>