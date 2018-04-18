*This is work in progress*

# json-form

Renders form based on JSON Schema

![image](https://user-images.githubusercontent.com/184172/38784098-c30536fe-4104-11e8-95bb-58c4f5eca24f.png)

Published in gh-pages: https://1602.github.io/json-form/


Development progress:

- [x] text editing
- [x] flat object editing
- [x] validation (inline errors only, so far)
- [x] material design styles
- [x] demo for two use-cases: text editing, flat object editing
- [x] editing of number and boolean

Next steps will be some of those (not necessarily in this order):

- [ ] required and optional field
- [ ] dealing with `undefined` (erase property)
- [ ] multiline editing
- [ ] editing as json
- [ ] form layout customisation
- [ ] editing array of items
- [ ] editing dictionary (object with additionalItems = true)
- [ ] display of object-level errors
- [ ] expandable mode for large/nested forms

## Setup for development

1. Install dependencies
```
yarn
```
2. Run local dev server to facilitate hot module reloading
```
yarn dev
```

## Project structure

All sources live in `./src`, package code that will be published to a registry is in `./src/Json/Form.elm`, legacy code (with lots of feature covered in a slightly odd way lives here: `./src/LegacyFormComponent.elm`)

Contributors welcome, submit an issue to open a discussion.