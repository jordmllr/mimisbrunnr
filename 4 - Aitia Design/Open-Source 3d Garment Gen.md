## 🧵 Comprehensive List — Garment / Clothing Generation Tools & Models

| **Name** | **Input** | **Output** | **Open Source** | **Mesh-Only Friendly** | **Pattern / Structured Output** | **Best For** | **Link** |
|----------|-----------|------------|------------------|------------------------|-------------------------------|---------------|----------|
| **ChatGarment** | Text / Image / Sketch | JSON sewing pattern + draped 3D garment | ✅ | ⚠️ (mesh via reconstruction) | ⭐⭐⭐⭐⭐ | Pattern-oriented multimodal generator | https://github.com/biansy000/ChatGarment |
| **GarmentDiffusion** | Text / Image / Partial pattern | Vectorized sewing patterns | ✅ | ⚠️ via reconstruction | ⭐⭐⭐⭐ | Efficient, diffusion based pattern output | https://github.com/Shenfu-Research/Garment-Diffusion |
| **DressCode (SewingGPT)** | Text | Pattern tokens + textures | ✅ | ⚠️ pattern code → mesh externally | ⭐⭐⭐⭐ | GPT-based text → structured garment code | https://github.com/IHe-KaiI/DressCode |
| **Design2GarmentCode** | Text / Sketch / Image | Parametric pattern code | ⚠️ | ⚠️ needs conversion | ⭐⭐⭐⭐ | Design language → editable pattern code | https://style3d.github.io/design2garmentcode/ |
| **WordRobe** | Text | Textured 3D garment mesh | ⚠️ (research) | ✅ | ⭐⭐⭐ | Text → standalone mesh | https://wordrobe24.github.io/WordRobe_Page/ |
| **ClotheDreamer** | Text | 3D garment mesh (Gaussian) | ✅ | ⚠️-needs remesh | ⭐⭐⭐ | Detailed shape generation | https://ggxxii.github.io/clothedreamer/ |
| **Garment3DGen** | Image | 3D garment mesh + UV | ✅ | ✅ | ⭐⭐ | Image → garment mesh with UV | https://github.com/nsarafianos/Garment3DGen |
| **GarmageNet** | Text / Sketch / Image / Pattern | Structured 3D garment + panel maps | ⚠️ (emerging) | ✅ | ⭐⭐⭐⭐⭐ | Multimodal with structured panels | https://style3d.github.io/garmagenet/ |
| **Design2Cloth** | Image/Mask | 3D cloth mesh reconstruction | ⚠️ (partial) | ✅ | ⭐⭐⭐ | 2D mask → 3D cloth geometry | https://jiali-zheng.github.io/Design2Cloth/ |
| **Dress-1-to-3** | Image | Simulation-ready 3D garment mesh | ⚠️ | ✅ | ⭐⭐⭐⭐ | Strong image → 3D garment (research) | https://dress-1-to-3.github.io/ |
| **DiffAvatar** | Multi-view scan | Garment mesh + physics params | ⚠️ | ⚠️ | ⚠️ | Reconstruction & physics output | https://people.csail.mit.edu/liyifei/publication/diffavatar/ |
| **CloSe (Clothed Shape Editing)** | Mesh | Editable garment mesh | ✅ | ✅ | ⚠️ | Garment mesh editing for clean shapes | https://github.com/geometryprocessing/close |
| **GET3D (fine-tuned for garments)** | Text / Latent | 3D mesh | ✅ | ⚠️ | ⚠️ | General 3D model used for garment generation | https://github.com/nv-tlabs/GET3D |
