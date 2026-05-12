# Terra

Kadın kooperatifleri için yapay zeka destekli dijital satış ve operasyon asistanı.

## Proje Amacı

Terra, kadın kooperatiflerinin ürün, stok, sipariş ve müşteri iletişimi süreçlerini dijital ortamda daha kolay yönetebilmesini hedefleyen bir hackathon projesidir.

## Kullanılan Teknolojiler

- Python
- FastAPI
- Gemini API
- React / Vite
- GitHub

## Backend Çalıştırma

1. `cd backend`
2. `python3 -m venv venv`
3. `source venv/bin/activate`
4. `pip install -r requirements.txt`
5. `.env.example` dosyasını `.env` olarak kopyala:
   - `cp .env.example .env`
6. `.env` içinde `GEMINI_API_KEY` değerini güncelle
7. `uvicorn main:app --reload`

## Temel Özellikler

- Ürün ve stok takibi
- Sipariş takibi
- Yapay zeka destekli müşteri yanıtları
- Ürün açıklaması oluşturma
- Günlük operasyon özeti
