# Higgs Audio V2 Notebook

<img src="https://github.com/boson-ai/higgs-audio/raw/main/figures/higgs_audio_v2_architecture_combined.png" width=900>

Simple Jupyter notebook to run Higgs Audio models with automatic setup and public URL generation.

## ⚠️ Important: Using Quantized Version

To use the **quantized version** instead of the standard model:

1. Rename `higgs-audio` folder to `higgs-audio_base`
2. Rename `higgs-audio_quantized` folder to `higgs-audio`
3. Run the notebook normally

To **switch back** to the standard version:
1. Rename `higgs-audio` folder to `higgs-audio_quantized`
2. Rename `higgs-audio_base` folder back to `higgs-audio`

**Why?** The notebook always uses the `higgs-audio` folder as the main model source.


## 🚀 Quick Start

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wilzamguerrero/higgs-audio-v2-colab/blob/main/higss%20audio%20v2%20colab.ipynb)

## ✨ Features

- **One-click setup** - Automatic installation of all dependencies
- **Multi-platform** - Works on Colab, Kaggle, Lightning AI, SageMaker
- **Public access** - Automatic LocalTunnel integration
- **Simple interface** - Clean menu-driven operation

## 📋 Usage

1. Run the notebook
2. Select `1` to install
3. Select `2` to run Higgs Audio
4. Use the generated public URL

```
1: Install Higgs Audio
2: >> Run Higgs Audio (Local V2) <<
3: Delete Higgs Audio
0: Exit
```

## 🛠️ Built With

This notebook combines these excellent projects:

- **[higgs-audio](https://github.com/boson-ai/higgs-audio)** - Main implementation
- **[HiggsAudio-V2-Local](https://github.com/PierrunoYT/HiggsAudio-V2-Local)** - Local Gradio interface
- **[higgs-audio_quantized](https://github.com/Nyarlth/higgs-audio_quantized)** - Optimized version

## 🌍 Platform Support

| Platform | Status |
|----------|--------|
| Google Colab | ✅ Recommended |
| Kaggle | ✅ Supported |
| Lightning AI | ✅ Supported |
| SageMaker | ✅ Supported |

## 🤝 Credits

Thanks to the original authors for their amazing work:
- Boson AI Team
- PierrunoYT 
- Nyarlth

## 📜 License

MIT License - Feel free to use and modify!

---
⭐