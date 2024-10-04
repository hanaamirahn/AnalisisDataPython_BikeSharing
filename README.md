# AnalisisDataPython_BikeSharing

# **Bike Rentals Dashboard 🚴‍♂️**

Dashboard ini dibuat menggunakan Streamlit untuk menganalisis dan memvisualisasikan data penyewaan sepeda berdasarkan berbagai parameter seperti tahun, bulan, dan kondisi cuaca. Pengguna dapat menggunakan sidebar interaktif untuk memfilter data dan melihat visualisasi penyewaan sepeda yang lebih mendalam.

# **Setup Environment - Anaconda**
```
# Membuat environment baru
conda create --name bike-rentals python=3.9

# Mengaktifkan environment
conda activate bike-rentals

# Install dependencies dari file requirements.txt
pip install -r requirements.txt
```

# Setup Environment - Shell/Terminal
```
# Buat direktori proyek
mkdir bike_rentals_dashboard

# Pindah ke direktori proyek
cd bike_rentals_dashboard

# Install dependencies dan setup virtual environment
pipenv install

# Masuk ke shell virtual environment
pipenv shell

# Install dependencies dari file requirements.txt
pip install -r requirements.txt

```

# Requirements
```
streamlit==1.15.0
pandas==1.3.5
matplotlib==3.4.3
seaborn==0.11.2
```

# Menjalankan Streamlit App
```
streamlit run dashboard.py
```
