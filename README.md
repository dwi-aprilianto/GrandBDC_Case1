# GrandBDC Case 1 - MBG Classification

## Deskripsi
Project ini dibuat untuk menyelesaikan Big Data Challenge Case 1 mengenai klasifikasi tweet/x terkait Program Makan Bergizi Gratis (MBG).

Model yang digunakan pada project ini adalah:
- TF-IDF Vectorizer
- Logistic Regression

Metode evaluasi menggunakan:
- Balanced Accuracy

---

## Struktur File

| File | Deskripsi |
|------|------------|
| GrandBDC_Case_1.ipynb | Notebook utama |
| submission_case1.xlsx | Hasil prediksi |
| README.md | Dokumentasi project |

---

## Library yang Digunakan

- pandas
- scikit-learn
- openpyxl
- re

---

## Tahapan Pengerjaan

1. Load dataset
2. Text preprocessing
3. Label encoding
4. TF-IDF feature extraction
5. Training Logistic Regression
6. Evaluasi menggunakan Balanced Accuracy
7. Prediksi data test
8. Generate file submission

---

## Cara Menjalankan

1. Upload dataset ke Google Colab:
   - case_1_labeled_data.xlsx
   - case_1_text_to_predict.xlsx
   - case_1_template_sheet.xlsx

2. Jalankan notebook:
   - GrandBDC_Case_1.ipynb

3. Hasil prediksi akan tersimpan sebagai:
   - submission_case1.xlsx
