# Material Design v3 Colors
##### All Material Design v3 Colors as CSS and SCSS Variables.
---
## Usage

- For installation:
```
npm install --save material-design3-colors
```
---
### For CSS:

To use the **CSS variables**, you can import the css file into your style sheet from the node_modules folder by:
```
@import '~material-design3-colos/md3-colors.css';
```
if it's not located in **the node_modules** folder, just use relative path like:
```
@import 'path/to/material-design3-colors/md3-colors.css';
```
### For SCSS
If you want to use the **SCSS variables**, you can import the **md3-colors.scss** into your scss style files by:
```
@import '~material-design3-colors/md3-colors';
```
if it's not located in **the node_modules** folder, just use relative path like:
```
@import 'path/to/material-design3-colors/md3-colors';
```
---
### Use variables in CSS:
To use variables in **CSS**:

**example:**
```
@import 'path/to/material-design3-colors/md3-colors.css';

body {
    background-color: var(--md3-color-sys-dark-background);
}
```
---
### Use variables in SCSS:
To use variables in **SCSS**:

**example:**
```
@import 'path/to/material-design3-colors/md3-colors';

body {
    background-color: $md3-color-sys-dark-background;
}
```
All colors are copied from **[Material Design3 Figma Kit]** and i just turn them into css and scss variables, so that you be able to use them in your web codes.