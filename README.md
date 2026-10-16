# Django Atölyesi

Türkçe, başlangıç seviyesinde Django öğrenme sayfası. URL, view, template ve model kavramlarını kısa dersler ve örnek kodlarla anlatır; ders ilerlemesini tarayıcıda saklar ve mini quiz içerir.

## Çalıştırma

Python 3.12 veya üzeri ve pip gerekir.

```powershell
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Uygulamayı `http://127.0.0.1:8000/` adresinde aç.

Geliştirme ortamında gizli anahtar otomatik üretilir. Kalıcı bir anahtar kullanmak için `DJANGO_SECRET_KEY` ortam değişkenini ayarla. Gerçek anahtarları veya yerel veritabanını Git'e ekleme.