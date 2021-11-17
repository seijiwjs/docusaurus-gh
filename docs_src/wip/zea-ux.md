---
sidebar_position: 1
title: Zea UX
---

# Zea UX
There are a features that are user specific, not something everyone needs; therefore we created the Zea Ux plug-in. It adds powerful features to the engine, that enrich the user experience like creation tools, UndoRedo System, etc.
</br>
</br>
</br>

# Licensing
The Zea UX plug-in is under a [`MIT`](https://en.wikipedia.org/wiki/MIT_License) license.
</br>
</br>
</br>

# Add it to your project
The process to add Zea UX to your projects is easy. 

## *Using CDNs*
For static websites or quick implementation you can always use CDNs like JsDelivr or Unpkg:

### *JsDelivr*
```html
<script crossorigin src="https://cdn.jsdelivr.net/npm/@zeainc/zea-ux/dist/index.umd.min.js"></script>
```
### *Unpkg*
```html
<script crossorigin src="https://unpkg.com/@zeainc/zea-ux/dist/index.umd.js"></script>
```
### *Use it*
```html
<script>
  const { UndoRedoManager } = globalThis.zeaUx
</script>
```

## *As a Module*
But if you want to use it like a module, then install the package in your project using `npm` or `yarn`:

```bash
npm i @zeainc/zea-ux
## Or
yarn add @zeainc/zea-ux
```

### *Use it*
```javascript
import { UndoRedoManager } from '@zeainc/zea-ux'
// ...
```
</br>

> For questions on licensing, please fill out the contact form on our website: [_zea.live_](https://www.zea.live/contact-us)
