# Tableau Dashboard Crop & Combine Automation Tool

A GUI-based Python application to export Tableau dashboards, crop specific sections (charts/tables), and combine them into a single Word or PDF report.

## 🔧 Features
- Login via Tableau credentials (username/password)
- Dynamically select Project → Workbook → View (Dashboard)
- Export dashboard to PDF → Convert to PNG → Crop specific area
- Crop multiple dashboards and combine into a single report (Word/PDF)
- Auto-clears temporary files and generates a summary file
- Option to name output and folder dynamically

## 🛠️ Tech Stack
- Python
- Tkinter (GUI)
- Tableau REST API
- `pdf2image`, `PIL`, `PyPDF2`, `python-docx`

## 🚀 Setup Instructions
1. Install required packages  
   `pip install -r requirements.txt`
2. Ensure `poppler` is installed and its path set correctly (e.g., in your script as `POPLER_BIN`)
3. Run the app  
   `python Tableau.py`
4. Follow the GUI to log in and start exporting/cropping dashboards.

## 📁 Folder Structure
```bash
📦tableau-crop-combine-tool/
 ┣ 📜Tableau.py
 ┣ 📜README.md
 ┣ 📜requirements.txt
 ┗ 📂screenshots/
    ┗ 📷 example_crop_preview.png
```

👉 Demo/Portfolio: [bharathkumarkammari.com/portfolio.html](https://bharathkumarkammari.com/portfolio.html)