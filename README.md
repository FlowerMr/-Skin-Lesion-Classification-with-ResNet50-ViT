Skin Lesion Classification with ResNet50 & ViT

This project focuses on classifying skin lesion images from the HAM10000 dataset using deep learning models. So far, ResNet50 and Vision Transformer (ViT) have been trained and evaluated, including interpretability (XAI) analysis and report generation.

📌 Upcoming Enhancements
Test additional models such as EfficientNet, ConvNeXt, Swin Transformer, etc.

Experiment with ViT hyperparameters (e.g., patch size, depth, hidden dimensions)

Add fairness analysis to assess model performance across underrepresented classes

Improve final report and add interactive dashboard

📁 Project Structure
data_preparation.ipynb: Data setup and image path configuration

resnet_training.ipynb: Training and evaluation of ResNet50

vit_training.ipynb: Training and evaluation of ViT using timm

xai_analysis.ipynb: Interpretability analysis with Grad-CAM and Saliency

report_generation.ipynb: Final HTML report generation

README.md: Project overview and roadmap

🚀 How to Run
Place the HAM10000 dataset in /content/dataset/ham10000_images.

Run the notebooks in order or use the saved models.

The final report will be saved at /content/drive/MyDrive/full_model_report.htm


📦 Dependencies
pip install fastai timm captum seaborn scikit-learn matplotlib pandas


📄 License
This project is open for educational and research purposes. Please cite the source if used.
