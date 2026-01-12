## 🖥️ Backend Django

### 1. Tạo virtual environment và cài package

```bash
# di chuyển đến folder backend


# tạo venv
python -m venv venv

# kích hoạt venv

# Windows
venv\Scripts\activate

# Mac/Linux
source venv/bin/activate

# cài dependencies
pip install -r requirements.txt

python manage.py migrate

# cấu hình lại database trong hospital/setting

# tạo migration từ models
python manage.py makemigrations

# áp dụng migration, tạo bảng trong database
python manage.py migrate

# chạy chương trình
python manage.py runserver

```


