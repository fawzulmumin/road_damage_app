# Deteksi Kerusakan Jalan Berbasis EfficientNet-B0

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Model](https://img.shields.io/badge/Model-EfficientNet--B0-orange)
![Transfer Learning](https://img.shields.io/badge/Transfer%20Learning-yes-2E8B57)

Model klasifikasi citra untuk mendeteksi kerusakan jalan, dikembangkan sebagai skripsi Sarjana Informatika di Universitas Gunadarma. Model dibangun dengan **transfer learning** dari EfficientNet-B0.

## Hasil

| Metrik | Nilai |
|--------|-------|
| Akurasi | 90% |
| Presisi | 89% |
| Recall | 88% |
| F1-score | 90% |

## Pendekatan

1. Memakai EfficientNet-B0 yang sudah dilatih sebelumnya sebagai ekstraktor fitur.
2. Menyesuaikan lapisan keluaran untuk klasifikasi kondisi jalan.
3. Melatih dan mengevaluasi model dengan akurasi, presisi, recall, dan F1-score.

## Teknologi

Python, EfficientNet-B0, transfer learning.

## Status repositori

Repositori ini saat ini berisi dokumentasi proyek. Kode pelatihan, notebook, dan bobot model akan ditambahkan.
