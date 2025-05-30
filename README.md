# Var-Occ-Dataset
The **Var-Occ-Dataset** is a large-scale, diverse dataset specifically designed for **video de-occlusion tasks** in urban environments. It contains challenging scenarios with various types of occlusions, including static structures, dynamic objects, and dense coverage, to support research on robust scene recovery and reconstruction.

---
![Var-Occ Dataset](https://github.com/user-attachments/assets/2f60295a-3a07-4391-854a-c00d018569d2)

## 📦 Dataset Structure

Each sequence includes:
- `frames/`: RGB frames of the video (with occlusions)
- `masks/`: Binary occlusion masks for each frame
- `info.json`: Metadata including occlusion type, motion type, frame rate, resolution, etc.

```bash
UrbanDeocc/
  ├── sequence_001/
  │   ├── frames/
  │   ├── masks/
  │   └── info.json
  ├── sequence_002/
  └── ...
