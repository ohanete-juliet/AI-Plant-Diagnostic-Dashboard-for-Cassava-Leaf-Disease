# AI Plant Diagnostic Dashboard for Cassava Leaf Disease

A fully immersive demo where users upload cassava leaf images via a **Gradio web app**, powered by the CropNet model (88% accuracy), and view prediction results in **Power BI**. The repository includes:
- `app.py` – Gradio interface for image upload & model inference
- `predictions.csv` – Sample output records with labels and confidence scores
- `dashboard_export.pdf` – Final Power BI dashboard for insights
- `README.md` – Detailed project overview

##  Tools & Technology
- Python, Gradio, TensorFlow Hub, TensorFlow  
- CropNet model (pre-trained on 9,430 cassava leaf images)  
- CSV data handling via Python  
- Power BI for data visualization

##  Purpose
Provides a **full AI pipeline**: capture leaf image → diagnose disease → visualize results — aimed at improving cassava farmer livelihoods and crop management.
