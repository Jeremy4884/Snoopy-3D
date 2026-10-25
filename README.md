# 🐶 Snoopy & Woodstock 3D (Interactive WebGL Experience)

An authentic, Charles Schulz-inspired 3D web experience starring **Snoopy** and his best friend **Woodstock**, built with Blender 5.2 and Three.js.

![Snoopy and Woodstock](qc_snoopy_and_woodstock_master.png)

## ✨ Features
- **Snoopy 3D Animations**:
  - 🚶 **เดินเล่น (Walk)**: Smooth procedural marching cycle
  - 👋 **โบกมือทักทาย (Wave)**: Joyful cartoon paw wave
  - 🤸 **กระโดดดีใจ (Jump)**: Dynamic joyful jump with cheering paws in the air
- **Woodstock Companion**:
  - 🐤 **เสก Woodstock ออกมา!**: Woodstock swoops in from above and hovers gracefully beside Snoopy
  - 🪶 **24-Frame Flight Cycle (`Woodstock_Fly`)**: Authentic wing flutter and vertical bobbing
  - 📐 **Authentic Sculpt**: 6-spike crest fan, bulbous snout, faceted diamond eyes, and Canary Yellow `#FED128` PBR shader
- **Interactive Controls**:
  - OrbitControls: 360° rotation, pan, zoom
  - Preset camera angles: Perspective, Front, Side
- **Soundtrack**: Floating vinyl record player playing Vince Guaraldi's *"Linus and Lucy"*

## 🚀 Deployment to GitHub Pages
1. Push this repository to your GitHub account.
2. Go to **Settings** > **Pages**.
3. Under **Branch**, select `main` (or `master`) and `/ (root)`, then click **Save**.
4. Your website will be live in ~1 minute at:
   `https://<your-username>.github.io/<repository-name>/`

## 📁 Key Web Files
- `index.html`: Web application with Three.js engine and responsive UI
- `snoopy.glb`: 3D Snoopy model with rigged animations (Walk, Wave, Jump)
- `woodstock.glb`: 3D Woodstock model with flight animation (`Woodstock_Fly`)
- `woodstock_icon_big.png`: Button badge avatar icon
- `snoopy_avatar.png`: Vinyl player disc art

## 🛠️ Created with
- **Blender 5.2.2 LTS** (Sculpting, Rigging, Weight Painting, Action Strips)
- **Three.js r128** (WebGL Rendering & Animation Mixer)
