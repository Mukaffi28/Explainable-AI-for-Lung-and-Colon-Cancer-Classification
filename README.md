# Exploring Explainable AI Techniques for Improved Interpretability in Lung and Colon Cancer Classification
## Abstract
Lung and colon cancer are serious worldwide health challenges that require early and precise identification to reduce mortality risks. However, diagnosis, which is mostly dependent on histopathologists' competence, presents difficulties and hazards when expertise is insufficient. While diagnostic methods like imaging and blood markers contribute to early detection, histopathology remains the gold standard, although time-consuming and vulnerable to inter-observer mistakes. Limited access to high-end technology further limits patients' ability to receive immediate medical care and diagnosis. Recent advances in deep learning have generated interest in its application to medical imaging analysis, specifically the use of histopathological images to diagnose lung and colon cancer. The goal of this investigation is to use and adapt existing pre-trained CNN-based models, such as Xception, DenseNet201, ResNet101, InceptionV3, DenseNet121, DenseNet169, ResNet152, and InceptionResNetV2, to enhance classification through better augmentation strategies. The results show tremendous progress, with all eight models reaching impressive accuracy ranging from 97% to 99%. Furthermore, attention visualization techniques such as GradCAM, GradCAM++, ScoreCAM, Faster Score-CAM, and LayerCAM, as well as Vanilla Saliency and SmoothGrad, are used to provide insights into the models' classification decisions, thereby improving interpretability and understanding of malignant and benign image classification


## Table of Contents
- [Proposed Methodology](#experimental-methodology)
- [Dataset Availability](#dataset-availability)
- [Results](#results)
- [Contact Information](#contact-information)
- [Citation](#citation)


## Proposed Methodology
![Methodology](NLI_with_page-0001.jpg)

    
## Dataset Availability

We utilized the **LC25000** dataset, which comprises 25,000 color pictures of lung and colon tissues classified into five categories: colon cancer, benign colonic tissue, lung adenocarcinoma, lung squamous cell carcinoma, and benign lung tissue. Each class consists of 5,000 images cropped to 768 by 768 pixels. The collection is divided into colon and lung image sets in accordance with HIPAA compliance guidelines. It's instrumental in developing diagnostic tools for lung and colon cancers, driving progress in medical imaging research.

The dataset can be accessed from [here](https://www.kaggle.com/datasets/xilezhu/lc25000).




## Results
### Comparative Analysis of PLMs for Different Performance Metrics

| Model         | Accuracy | Precision | Recall  | F1-Score |
|---------------|----------|-----------|---------|----------|
| **BanglaBERT**| **0.8204** | **0.8222** | **0.8204** | **0.8203** |
| Bangla BERT Base | 0.6803 | 0.6907 | 0.6812 | 0.6833 |
| DistilBERT    | 0.6320   | 0.6358    | 0.6320  | 0.6317   |
| mBERT         | 0.6427   | 0.6496    | 0.6428  | 0.6153   |
| sahajBERT     | 0.6708   | 0.6791    | 0.6709  | 0.6707   |




### Comparative Analysis of LLMs for Different Performance Metrics

| LLMs              | Metric    | Zero-shot | 5-shot | 10-shot | 15-shot |
|-------------------|-----------|-----------|--------|---------|---------|
| **GPT-3.5 Turbo** | Accuracy  | 0.8503    | 0.8657 | 0.8756  | **0.9205** |
|                   | Precision | 0.7025    | 0.8683 | 0.8753  | **0.9219** |
|                   | Recall    | 1.0       | 0.8624 | 0.8759  | **0.9204** |
|                   | F1-Score  | 0.8254    | 0.8640 | 0.8748  | **0.9299** |
| **Gemini 1.5 Pro**| Accuracy  | 0.7287    | 0.8625 | 0.8732  | **0.9146** |
|                   | Precision | 0.5556    | 0.8652 | 0.8763  | **0.9156** |
|                   | Recall    | 0.7143    | 0.8652 | 0.8732  | **0.9146** |
|                   | F1-Score  | 0.6251    | 0.8652 | 0.8701  | **0.9136** |





## Contact Information

For any questions, collaboration opportunities, or further inquiries, please feel free to reach out:

- **Fatema Tuj Johora Faria**
  - Email: [fatema.faria142@gmail.com](mailto:fatema.faria142@gmail.com)

- **Mukaffi Bin Moin**
  - Email: [mukaffi28@gmail.com](mailto:mukaffi28@gmail.com)

- **Pronay Debnath**
  - Email: [pronaydebnath99@gmail.com](mailto:pronaydebnath99@gmail.com)
- **Asif Iftekher Fahim**
  - Email: [fahimthescientist@gmail.com](mailto:fahimthescientist@gmail.com)
    
## Citation

If you find the dataset or the associated research work helpful, please consider citing our paper:

```bibtex
@misc{faria2023vashantor,
  title={Vashantor: A Large-scale Multilingual Benchmark Dataset for Automated Translation of Bangla Regional Dialects to Bangla Language},
  author={Fatema Tuj Johora Faria and Mukaffi Bin Moin and Ahmed Al Wase and Mehidi Ahmmed and Md. Rabius Sani and Tashreef Muhammad},
  year={2023},
  eprint={2311.11142},
  archivePrefix={arXiv},
  primaryClass={cs.CL}
}



