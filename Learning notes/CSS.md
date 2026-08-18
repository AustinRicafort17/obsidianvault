---
created: 2026-08-04
topic: "[[The Odin Project]]"
source:
tags:
  - learning
category: "[[Study notes]]"
related-notes:
  - "[[Dev]]"
---
Cascading Style Sheets (CSS)

is a file that I put on top of an [[HTML]] file to give a website some ✨STYLE✨

1. **Selector**
    - Chooses which HTML element(s) the rule applies to.
    - Example:
        
        ```
        p
        .container
        #header
        button
        ```
        
2. **Declaration Block**
    - Everything inside the curly braces `{}`.
    - Contains one or more declarations.
    - Example:
        
        ```
        {
          color: blue;
          font-size: 18px;
        }
        ```
        
3. **Declaration**
    - A single `property: value;` pair.
    - Example:
        
        ```
        color: blue;
        ```
        
4. **Property**
    - The thing you want to change.
    - Examples:
        
        ```
        color
        font-size
        margin
        display
        ```
        
5. **Value**
    - The setting you give the property.
    - Examples:
        
        ```
        blue
        18px
        flex
        center
        ```
        

### Visual breakdown

```
.container {          /* Selector */
  display: flex;      /* Declaration */
  color: red;         /* Declaration */
}
```

- **`.container`** → Selector
- **`{ ... }`** → Declaration block
- **`display: flex;`** → Declaration
    - `display` → Property
    - `flex` → Value
- **`color: red;`** → Declaration
    - `color` → Property
    - `red` → Value