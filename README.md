
# 🎉 Python Nutrition Label

Document is `Python` project base on [Open Food Fact](https://github.com/openfoodfacts) for detect `nutrition label` by optimization image pre-proceesing before use OCR processing

![version](https://img.shields.io/badge/version-1.0-blue)
![rating](https://img.shields.io/badge/rating-★★★★★-yellow)
![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

[![Watch the video](https://www.loom.com/share/4c4eae267b4a4f3bb08a2ae244a0ee65)](https://www.loom.com/share/4c4eae267b4a4f3bb08a2ae244a0ee65)

### 🆕 New Update

- Add Refresh Token

### ⭐ Features

- Python Design Easy Run Command

### 💗 Repository

- azure ( - )
- github (https://github.com/natthasath/python-nutrition-label.git)

```
PS C:\> git remote -v show
PS C:\> git add .
PS C:\> git commit -m "Update"
PS C:\> git push azure
PS C:\> git push github
```

### 💎 Requirement

- [Dataset Open Food Facts](https://world.openfoodfacts.org)

### 🥈 Run

```
mkvirtualenv nutrition
workon nutrition
pip install -r requirements.txt
python main.py
python detection.py -i data/test_images/ocr_eng_07.jpg
```

### 👉🏼 Try it out

```
# data/result/output.jpg
# data/nutrition.csv
```

### 💡 Technical
- Table Detection
- Text Detection & Extraction
- Image Pre-Processing
- Image Processing with Tesseract OCR
- Image Post-Processing