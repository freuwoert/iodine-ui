# Iodine UI (WIP) 🎚️
Iodine UI is a Material Design inspired UI library for Vue 3 with a focus on interactive components.  
At the moment this library offers **icons**, **buttons**, **icon buttons**, **single-line inputs**, **select inputs**, **popup modals**, **toggles/checkboxes** and **loaders** all designed with care and accessibility on mind.  
  
We're planning to introduce **date/time pickers**, **colorpickers**, **iconpickers** and **textareas** in the near future.  
<br>

## Installation ⚙️
**Via NPM**
```bash
npm install --save @freuwort/iodine-ui
```
<br>

## Import ⤵️
**Global import**
```javascript
// Import Iodine UI
import IodineUI from "@freuwort/iodine-ui";

// Create app
const app = createApp(App);

// Use components
app.use(IodineUI);

// Mount app
app.mount("#app");
```

**Local import**
```javascript
// Import components individually
import { IodIcon, IodButton, IodIconButton, IodInput, IodSelect, IodPopup, IodLoader } from "@freuwort/iodine-ui";
```
<br>

## Usage 🪛
```html
<IodInput type="text" label="Firstname" v-model="yourValue"/>
```
<br/>

## Demo 🖥️
**Demo site:** [iodine.freuwort.com](https://iodine.freuwort.com/)  
<br>

## Project setup ⚙️
Only important if you work on this project.
```bash
# Install
npm install
# Serve
npm run serve
# Or build
npm run build
```
<br>

## Credits 📜
Developed by [Alyx Freuwört](https://github.com/freuwoert) & [Lynn Schallenberg](https://github.com/LynnCinnamon)  
<br>

## License 📜
[MIT](http://opensource.org/licenses/MIT) – 2023
