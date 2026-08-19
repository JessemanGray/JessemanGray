<p align="center">
  <svg width="800" height="250" xmlns="http://www.w3.org/2000/svg">
    <rect width="800" height="250" fill="#0a0a0f"/>
    <g transform="translate(400, 125)">
      <script type="text/javascript">
        const n = 800;
        const goldenAngle = Math.PI * (3 - Math.sqrt(5));
        let dots = '';
        for (let i = 0; i < n; i++) {
          const r = 2.8 * Math.sqrt(i);
          const theta = i * goldenAngle;
          const x = r * Math.cos(theta);
          const y = r * Math.sin(theta);
          const size = 1.5 + 2 * (1 - i/n);
          const hue = 240 + 120 * (i/n);
          dots += `<circle cx="${x}" cy="${y}" r="${size}" fill="hsl(${hue}, 90%, 60%)" opacity="0.8"/>`;
        }
        document.write(dots);
      </script>
    </g>
  </svg>
</p>

---

**Jesse Gray** · ML & Spatial Data Specialist

Data modeler and visualization specialist with experience in Python, SQL, and 3D modeling. Background in project management and technical sales, with a focus on open-source collaboration and self-organization.

---

**recent work**

**ML Consultant** (2026) · 3D point clouds for digital twins · collaboration with top-3 AI lab  
**Data Consultant** (2026) · ML aesthetics & ontologies · AI behavior frameworks  
**Data Science Specialist** (2025–2026) · MCP/RAG pipelines · knowledge graphs

---

**stack**  
`Python` `Open3D` `OpenCV` `YOLO` `PyTorch` `TensorFlow` `scikit-learn` `pandas` `SQLite` `MongoDB` `GCP` `Docker` `Dash` `Three.js` `MCP` `RAG` `LangChain` `KG`

---

**connect**  
[github](https://github.com/jessemangray) · [linkedin](https://linkedin.com/in/jessemangray) · [medium](https://medium.com/@jessemangray) · [huggingface](https://huggingface.co/jessemangray)  
📧 jessemangray@gmail.com

