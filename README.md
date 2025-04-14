# PA-RDFKNet
# PA-RDFKNet: Unifying Plant Age Estimation through RGB-Depth Fusion and Knowledge Distillation

![PA-RDFKNet Architecture](https://via.placeholder.com/600x300) *(Optional: Add a diagram if available)*

## Abstract
Agriculture faces significant challenges in the 21st century due to resource scarcity. Artificial intelligence is being integrated with agriculture to address these challenges, unlocking new avenues for sustainability and innovation. A crucial agricultural practice is plant growth monitoring to detect stress early. Previous approaches used RGB and depth images, but depth cameras are often unavailable to farmers. 

In this work, we present **PA-RDFKNet**, a transformer-based **Plant Age RGB-Depth Fusion Knowledge Distillation Network**. This multi-to-single-modal teacher-student network leverages combined RGB-depth knowledge during training to infer plant age using only RGB images at test time. The model employs a distillation loss combining response-based, feature-based, and relation-based knowledge distillation, improving the mean squared error for RGB images from **2 to 0.14 weeks**.

## Key Features
- 🌱 **Multi-modal to single-modal distillation**: Uses RGB-depth pairs during training but only RGB at inference.
- 🧠 **Hybrid knowledge distillation**: Combines response-based, feature-based, and relation-based techniques.
- 📊 **State-of-the-art performance**: Achieves significant improvement in plant age estimation accuracy.
- 🌾 **Validated on multiple datasets**: Tested across three different plant datasets.

## Citation
If you use this work, please cite:

```bibtex
@article{bansal2024pa,
  title={Pa-rdfknet: Unifying plant age estimation through rgb-depth fusion and knowledge distillation},
  author={Bansal, Shreya and Singh, Malya and Barda, Seema and Goel, Neeraj and Saini, Mukesh},
  journal={IEEE Transactions on AgriFood Electronics},
  year={2024},
  publisher={IEEE}
}
For the preliminary work, cite:
@inproceedings{bansal2023radish,
  title={Radish plant growth monitoring using multimodal fusion},
  author={Bansal, Shreya and Singh, Malya and Barda, Seema and Kumar, Vikas and Goel, Neeraj and Saini, Mukesh},
  booktitle={2023 IEEE Conference on AgriFood Electronics (CAFE)},
  pages={25--29},
  year={2023},
  organization={IEEE}
}
