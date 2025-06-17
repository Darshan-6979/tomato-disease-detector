# tomato-disease-detector
🍅 A CNN model that classifies tomato‑leaf images into 10 disease / healthy categories with ~91 % validation accuracy.


CNN model trained on PlantVillage tomato‑leaf images  
(classifies Early‑blight, Late‑blight, Yellow‑Leaf‑Curl‑Virus, Healthy, etc.).

| Metric | Score |
|--------|-------|
| Train accuracy | 95 % |
| Validation accuracy | 90 % |

## Dataset
PlantVillage tomato subset (≈ 16 k images, 10 classes).

## How to run
1. Upload `Tomato___*` folders to `tomato_data/`
2. Run `Tomato_Disease_Detector.ipynb`
3. Test with your own leaf photo using the `predict()` helper.

## Tech
TensorFlow / Keras, Python, Google Colab.

