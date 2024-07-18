# OVAL-Website-Redesign


## Figma Working File


- Current prototype in [Viwer Mode](https://www.figma.com/proto/ZzGzh4exIQbatiATwgayE5/OVAL-new-website?node-id=0-1&t=wU1dHKS6KcuQMues-1) 
```html
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fdesign%2FZzGzh4exIQbatiATwgayE5%2FOVAL-new-website%3Fnode-id%3D0-1%26t%3DwU1dHKS6KcuQMues-1" allowfullscreen></iframe>
```
- Current Protype in [Dev ready mode](https://www.figma.com/design/ZzGzh4exIQbatiATwgayE5/OVAL-new-website?m=dev&node-id=0-1&t=wU1dHKS6KcuQMues-1)


- To view interactions, click the play button on top right, and choose a viewing flow to start.

<img width="218" alt="螢幕截圖 2024-07-18 16 14 01" src="https://github.com/user-attachments/assets/922ee2b2-d613-438b-853d-370505467c37">
<img width="249" alt="螢幕截圖 2024-07-18 16 14 19" src="https://github.com/user-attachments/assets/bdcd6ea7-47df-4f85-8859-93cd992cc4a4">

## Landing Animation ideas
### 1️⃣ AfterEffects Working File

### 2️⃣ 3D Interaction
- sample created via Spline 3D 
[file link](https://app.spline.design/file/fdf466b8-b917-483c-8523-2ba6a919cdc1)

#### Public URL
[Public URL](https://my.spline.design/untitled-529caf0b60e7840a8a2c91383be8ce23/) 
```html
<iframe src='https://my.spline.design/untitled-529caf0b60e7840a8a2c91383be8ce23/' frameborder='0' width='100%' height='100%'></iframe>
```

#### Viewer mode
```js
<script type="module" src="https://unpkg.com/@splinetool/viewer@1.8.9/build/spline-viewer.js"></script>
<spline-viewer url="https://prod.spline.design/jPHgShhH3Linuhu9/scene.splinecode"></spline-viewer>
```

#### Code export
```js
import Spline from '@splinetool/react-spline/next';

export default function Home() {
  return (
    <main>
      <Spline
        scene="https://prod.spline.design/jPHgShhH3Linuhu9/scene.splinecode" 
      />
    </main>
  );
}
```

