# window.getComputedStyle somehow caches view of element

## Steps to reproduce

1. Open `index.html` in browser

**Actual behavior**

2. `#test` block is visible

**Expected behavior**

2. `#test` block is hidden because of style block added with css

```css
   #test { display: none !important }
```
