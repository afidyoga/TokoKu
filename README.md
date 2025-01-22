# Cara Memulai Aplikasi Flask

# 1. Buat dan Aktifkan Virtual Environment
# Windows:
```bash
FlaskEnv\Scripts\activate
```
# Mac/Linux:
```bash
python3 -m venv FlaskEnv
source FlaskEnv/bin/activate  # Untuk Mac/Linux
```
# 2. Pasang Dependensi
```bash
pip install flask
pip install mysql-connector-python
```
# 3. Setel Environment Variables
# Windows:
```bash
set FLASK_APP=app.py
set FLASK_ENV=development
```
# Mac/Linux:
```bash
export FLASK_APP=app.py
export FLASK_ENV=development
```
# 4. Jalankan Aplikasi Flask
```bash
flask run --debug
```
