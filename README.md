# **PHREEQC Inverse Modeling Data Extractor**

This Python script is designed to extract **phase** and **redox mole transfers** from **PHREEQC output files** generated from **inverse modeling**. The extracted data is then organized into a **pandas DataFrame** and saved to an **Excel file**.

## **Features**

- **Extracts data from PHREEQC output files.**
- **Captures specific elements and phases from "Phase mole transfers" and "Redox mole transfers" sections.**
- **Saves the extracted data in an organized format in an Excel file.**
## **Usage**

1. Clone the repository:

git clone https://github.com/yourusername/phreeqc-inverse-modeling-extractor.git
cd phreeqc-inverse-modeling-extractor

3. Run the script:

python grabber.py

## **Prerequisites**

- **Python 3.x**
- **pandas library**

You can install the required Python packages using pip:

```bash
pip install pandas
