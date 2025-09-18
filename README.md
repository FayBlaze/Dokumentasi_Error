# Dokumentasi_Error

## Python

### Instalasi ke VScode  

Saat instalasi jangan lupa centang `add to PATH`  
kalau `python --version` python tidak terbaca lakukan ini:  
  
Enviroment Variables\ Enviroment Variables > user variables... > `C:\Users\ASUS\AppData\Local\Programs\Python\Python313\`, Pastikan ini paling atas  
  
Selanjutnya di VScode:  
Ctrl + Shift + P > Python: Select Interpreter > pilih direktori ini `C:\Users\ASUS\AppData\Local\Programs\Python\Python313\`\

### Install jupyter
```
"C:\Users\ASUS\AppData\Local\Programs\Python\Python313\python.exe" -m pip install --upgrade pip
"C:\Users\ASUS\AppData\Local\Programs\Python\Python313\python.exe" -m pip install jupyter ipykernel
```

1. Buat/aktifkan Virtual Environment (opsional tapi disarankan) Supaya paket tidak bercampur:  
```
py -m venv venv
.\venv\Scripts\activate
```
Mengapa penting?  
Menghindari konflik versi paket antar-proyek.  

2. Instal Jupyter
Di terminal aktif (bisa di VS Code terminal):
`pip install notebook`
atau untuk ekosistem modern:
`pip install jupyterlab`
notebook = antarmuka klasik, jupyterlab = versi terbaru lebih powerful.

3. Jalankan Server Notebook

Di folder proyek ketik:
`jupyter notebook`
atau
`jupyter lab`

4. Jalur Cepat di VS Code (tanpa browser)

Install Jupyter extension di VS Code.
Buka file notebook.ipynb.
VS Code akan menyediakan toolbar untuk menjalankan tiap cell.

## Konfigurasi VSCode
New Folder > .vscode >  
settings.json
```
{
    "window.zoomLevel": 0,
    "editor.fontSize": 14,
    "workbench.colorTheme": "Default Dark+",
    "workbench.iconTheme": "vs-seti"
}
```
