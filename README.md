## Proyek Akhir Bike Sharing

# Description

Proyek ini berfokus pada analisis data menggunakan dataset Bike Sharing. Hasil dari analisis ini akan diintegrasikan ke dalam sebuah dashboard sederhana yang akan dijalankan di platform Streamlit.

# Directory

- `/dashboard`: Memuat file utama yang digunakan untuk menampilkan dashboard, beserta satu dataset yang telah dibersihkan dan satu gambar untuk keperluan dashboard
- `/data` : Menyimpan dataset yang digunakan dalam analisis (Dataset Bike Sharing)
- `notebook.ipynb` : File Jupyter Notebook yang berisi analisis data yang telah dilakukan
- `README.md` : File yang memberikan informasi mengenai proyek ini.
- `requirements.txt` : File yang mencantumkan semua library yang digunakan dalam proyek ini.

# Setup environment

- conda create --name analisisdata python=3.9
- conda activate analisisdata
- pip install requirements.txt

# Run steamlit app

- cd ProyekAlba

```
streamlit run dashboard.py
```
