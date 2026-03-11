# Mammogram ROI Classification

This repository summarizes my deep learning experiments on mammogram ROI images, with a focus on TensorFlow / Keras transfer learning and fair comparison across multiple vision backbones.

## Contents

- `ConvNeXt.ipynb`: ConvNeXt Tiny transfer learning experiment.
- `ConvNeXt_Unfreeze_Comparison.ipynb`: Comparison of different ConvNeXt unfreezing depths (30 / 60 / 90) under the same data and training setup.
- `VIT.ipynb`: Vision Transformer transfer learning experiment.
- `Swin.ipynb`: Swin Transformer transfer learning experiment.
- `ResNet50_Fair_Comparison.ipynb`: ResNet50 experiment with unified preprocessing and augmentation for fair comparison.
- `ResNet50_Best_Tuned.ipynb`: Tuned ResNet50 version for side-by-side performance comparison.
- `PRE.ipynb`: Early preprocessing exploration notebook.
- `ROI_Cut.ipynb`: ROI extraction and cropping notebook.
- `Untitled0.ipynb`: Early Colab-based training draft.

## Recommended Reading Order

1. `ROI.ipynb`
2. `ConvNeXt.ipynb`
3. `VIT.ipynb`
4. `Swin.ipynb`
5. `ResNet50_Fair_Comparison.ipynb`

## Notes

- The repository does not include datasets or trained weights.
- Some notebooks still contain local disk paths or older Colab paths, so they need to be updated for a new environment.
- If you use DDSM or another mammogram ROI dataset, update variables such as `data_dir` before running training cells.

## Upload Scope

This repository is prepared mainly for notebook-based presentation.
Non-project files such as local documents, PDFs, temporary files, and virtual environments are excluded from Git.

## GitHub Commands

After creating a GitHub repository, run:

```bash
git branch -M main
git add README.md *.ipynb .gitignore
git commit -m "Initial commit"
git remote add origin <your-github-repo-url>
git push -u origin main
```
