# Hi, I'm ASHIK 👋 (ASHIK27445)

I'm a web developer with a strong interest in 3D, data, and computer vision workflows. I build interactive frontends, RESTful backends, and work on data pipelines for training and annotating ML models. I enjoy combining design tools like Blender and CAD with web technologies to create useful visual and data-driven applications.

---

## 🚀 Quick facts
- Location: (add your city / timezone)
- Primary focus: Web development, 3D visualization, data labeling & augmentation, computer vision (YOLO)
- Open to: freelance projects, collaborations, mentoring, and full-time roles

---

## 💻 Tech stack

### Frontend
- HTML5 · CSS3 · JavaScript (ES6+) · React · Tailwind CSS · DaisyUI
- Three.js (3D scenes, WebGL integrations)

### Backend & Databases
- Node.js · Express.js · Flask
- MongoDB · MySQL · Firebase
- XAMPP (local PHP / MySQL dev stacks)

### Languages
- C · C++ · Java · JavaScript

### ML / CV / Data
- Data labeling (Label Studio)
- Data augmentation pipelines
- YOLO (training / inference / annotation prep)

### Design & CAD
- Blender (3D modeling, rendering)
- 2D CAD drawing (technical drawings, exports for web/print)

### Tools & workflows
- Git · GitHub · Postman · VS Code
- Docker (optional) · Bash scripting

---

## 🔧 What I do (examples)
- Build responsive, accessible web apps with React, Tailwind and DaisyUI
- Create interactive 3D visualizations and scenes using Three.js
- Set up Node/Express APIs and connect them to MongoDB or MySQL
- Prepare datasets, annotate with Label Studio, perform augmentation, and train YOLO-style models
- Use Blender and CAD tools to prepare assets for web/AR projects

---

## ⭐ Selected project ideas to showcase
(Replace these placeholders with actual repositories and links)

- Portfolio / Demo: Interactive Three.js portfolio with projects rendered in WebGL — /portfolio
- Annotation Pipeline: Label Studio + augmentation scripts + YOLO training config — /label-augmentation-yolo
- MERN App: Full-stack app with React, Express, MongoDB and authentication — /mern-sample
- CAD-to-Web: 2D CAD export workflow and viewer integration — /cad-viewer

---

## 🧩 Example — minimal Three.js scene
```html
<!-- Minimal Three.js scene (replace with your actual project file) -->
<!doctype html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Three.js Demo</title>
    <style>body { margin: 0 } canvas { display: block }</style>
  </head>
  <body>
    <script src="https://unpkg.com/three@0.153.0/build/three.min.js"></script>
    <script>
      const scene = new THREE.Scene();
      const camera = new THREE.PerspectiveCamera(75, innerWidth/innerHeight, 0.1, 1000);
      const renderer = new THREE.WebGLRenderer({ antialias: true });
      renderer.setSize(innerWidth, innerHeight);
      document.body.appendChild(renderer.domElement);

      const geometry = new THREE.BoxGeometry();
      const material = new THREE.MeshNormalMaterial();
      const cube = new THREE.Mesh(geometry, material);
      scene.add(cube);
      camera.position.z = 3;

      function animate() {
        requestAnimationFrame(animate);
        cube.rotation.x += 0.01;
        cube.rotation.y += 0.01;
        renderer.render(scene, camera);
      }
      animate();
    </script>
  </body>
</html>
```

---

## 📂 How I organize code & data
- Keep frontend and backend in separate folders (e.g., /client, /server)
- Use clear dataset folders with README for annotation format and augmentation steps
- Store model configs (YOLO) and training scripts in a /models or /ml folder
- Use Label Studio projects with exported JSON for reproducible annotation

---

## 📫 Contact
- GitHub: [@ASHIK27445](https://github.com/ASHIK27445)
- Email: add-your-email@example.com
- LinkedIn: add-your-linkedin (optional)

---

## 🔜 Want me to add
- Dynamic GitHub stats / languages cards
- Project badges and repo links inserted automatically
- A shorter one-line bio for social profiles
Tell me which repos to highlight and I’ll update this README with direct links, screenshots, and project summaries.

Thanks for visiting — let’s build something awesome!
