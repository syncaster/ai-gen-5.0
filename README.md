# ai-gen-5.0

Kuliah Tamu - Generative AI untuk Industri 5.0

## Ringkasan proyek

Folder ini berisi dua notebook Jupyter yang menunjukkan aplikasi generative AI dan machine learning untuk Industri 5.0:

1. `difusser_huggingface.ipynb`
   - Contoh penggunaan `diffusers` dengan model Stable Diffusion untuk menghasilkan desain visual.
   - Menggunakan `StableDiffusionPipeline` dan mengeluarkan gambar desain mobil listrik futuristik.

2. `vae_randomForest.ipynb`
   - Contoh pembuatan data dummy sensor dan prediksi Remaining Useful Life (RUL).
   - Menggunakan `numpy`, `pandas`, `scikit-learn`, dan `tensorflow` untuk membangun VAE dan Random Forest.

## Versi Python

- Python: `3.12.12`

## Dependency pip yang direkomendasikan

Instal paket berikut di environment proyek ini:

```bash
pip install diffusers torch numpy pandas matplotlib scikit-learn tensorflow
```

> Jika menjalankan notebook `difusser_huggingface.ipynb` pada GPU, gunakan versi `torch` yang sesuai dengan CUDA di mesin Anda.

## Catatan

- Notebook `difusser_huggingface.ipynb` memuat model Stable Diffusion dari Hugging Face.
- Notebook `vae_randomForest.ipynb` menghasilkan data dummy, melatih model, dan mengevaluasi hasil prediksi.
