# Data Cleaning Pipeline

This repository contains a **Python script** to clean and organize CSV datasets.  
It allows you to keep only the columns you need, discard extra data, and save cleaned versions of your files automatically.  

---

## 📂 Folder Structure

- **input_folder**: Place your original CSV files here.  
- **output_folder**: Cleaned CSV files will be saved here.  
- **cleaning_pipeline.py**: Main script that processes the CSV files.  

> ⚠️ **Important:** Do NOT include any real customer or sensitive data in this repository. Only place your personal CSV files locally in `input_folder`.

---

## 🛠 How to Use

1. Clone this repository:

```bash
git clone https://github.com/kevincs-portfolio/data-cleaning-pipeline.git
cd data-cleaning-pipeline

input_folder = '/path/to/your/input/folder/'
output_folder = '/path/to/your/output/folder/'
python cleaning_pipeline.py
