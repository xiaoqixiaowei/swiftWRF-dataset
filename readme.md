# SwiftWRF: Spectrum Dataset for Single-Sided Movable Scenarios

This repository provides the open-source **RFID spectrum dataset** used in the paper:  
📄 **[Rasterizing Wireless Radiance Field via Deformable 2D Gaussian Splatting](https://arxiv.org/abs/2506.12787)**.

The dataset covers a variety of **single-sided movable scenarios** and is intended for research on wireless field reconstruction and generative modeling of spectrum data.

---

## 📥 Download

You can download the dataset from the following link:

👉 [OneDrive - OpenRFID Spectrum Dataset](https://1drv.ms/f/c/b1b302e6d09c4153/EpCJ4-YrQjZGgOMjYdWOFTQBQ9tqdCVqmRm-s7iU0mZkJA?e=iLQE6W)

---

## 📁 Dataset Contents

- `spectrum/`: AoA heatmaps in 360×90 PNG format
- `tx_index.txt`: Indices of transmitters in the scene
- `rx_index.txt`: Indices of receivers (or gateways)
- Multiple subfolders for different movable scene configurations

---

## 💻 Code

The official implementation for the SwiftWRF method and dataset usage can be found at:  
👉 [https://github.com/Evan-sudo/Swift_WRF](https://github.com/Evan-sudo/Swift_WRF)

---

## 📚 Citation

If you use this dataset, please cite the following paper:

```bibtex
@misc{liu2025rasterizingwirelessradiancefield,
  title     = {Rasterizing Wireless Radiance Field via Deformable 2D Gaussian Splatting},
  author    = {Mufan Liu and Cixiao Zhang and Qi Yang and Yujie Cao and Yiling Xu and Yin Xu and Shu Sun and Mingzeng Dai and Yunfeng Guan},
  year      = {2025},
  eprint    = {2506.12787},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CV},
  url       = {https://arxiv.org/abs/2506.12787},
}