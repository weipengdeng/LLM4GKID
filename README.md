# LLM4GKID: A Multimodal Large Language Model-driven Framework for Ghost Kitchen Identification

[![Paper](https://img.shields.io/badge/Paper-IEEE%20TCSS-blue)](https://doi.org/10.1109/TCSS.2026.XXXXXXX)
[![Python](https://img.shields.io/badge/Python-3.8+-green)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue)](LICENSE)

## 🍽️ Overview

LLM4GKID is a novel framework that identifies **ghost kitchens** (delivery-only restaurants without physical storefronts) by matching Points of Interest (POI) across different platforms. The framework leverages multimodal signals — spatial, semantic, and visual — to detect establishments that exist digitally but lack physical presence.

🔗 **Interactive 3D Visualization**: [https://weipengdeng.github.io/LLM4GKID/](https://weipengdeng.github.io/LLM4GKID/)

## 📦 Data

We are progressively releasing datasets associated with this project. Currently available:

| File | Description |
|------|-------------|
| `GK_2024.gdb.zip` | Ghost kitchen identification results for Shenzhen (2024), in ESRI GeoDatabase format |

> **Note on data release**: Additional datasets (e.g., gridded restaurant channel composition) are being prepared and will be released incrementally as we complete cleaning and documentation. We appreciate your patience and understanding.

## 🚧 Development Status

The code and full documentation are under active development. The complete implementation will be released progressively alongside the datasets.

## 📚 Citation

This paper has been published in *IEEE Transactions on Computational Social Systems*. If you use this work or data in your research, please cite:

```bibtex
@article{deng2026llm4gkid,
  title={LLM4GKID: A Multimodal Large Language Model-driven Framework for Ghost Kitchen Identification},
  author={Deng, Weipeng and Tang, Yihong and Wang, Chaofan and Yang, Tianren},
  journal={IEEE Transactions on Computational Social Systems},
  year={2026},
  publisher={IEEE}
}
```

## 📄 License

This project is licensed under the GNU General Public License v3.0 — see the [LICENSE](LICENSE) file for details.

---

**Keywords**: Ghost Kitchen, Large Language Model, POI Matching, Points of Interest, Multi-source Data Fusion, Platform Urbanism
