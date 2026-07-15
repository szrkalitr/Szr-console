# 🚀 SZR Console

SZR Console, **Metasploit Framework** için geliştirilmiş web tabanlı bir yönetim panelidir. Terminal kullanımını daha pratik hale getirmek amacıyla geliştirilmiştir. Gerçek zamanlı terminal çıktıları, oturum yönetimi ve modern arayüzü sayesinde Metasploit'i tek panel üzerinden yönetebilirsiniz.

---

## ✨ Özellikler

- 🌐 Web tabanlı Metasploit yönetimi
- 💻 Gerçek zamanlı terminal
- 📡 Socket.IO desteği
- 📂 Session yönetimi
- 🗄️ SQLite veritabanı
- 🌙 Modern karanlık tema
- ⚡ Hızlı ve hafif yapı
- 🧩 Modüler proje mimarisi

---

## 📂 Proje Yapısı

```text
szr-console/
│
├── app.py                 # Ana uygulama
├── config.py              # Yapılandırma
├── database.py            # SQLite işlemleri
├── rpc_client.py          # MSF RPC bağlantısı
├── msf_console_manager.py # Konsol yönetimi
├── socket_events.py       # Socket.IO olayları
├── api.py                 # API endpointleri
├── utils.py               # Yardımcı fonksiyonlar
│
├── templates/             # HTML sayfaları
│
├── requirements.txt
└── README.md
```

---

## 🎯 Amaç

Bu proje, Metasploit Framework ile çalışırken sürekli terminal kullanma ihtiyacını azaltmak için geliştirildi.

Hedefi;

- Daha düzenli bir çalışma ortamı sunmak
- Konsol çıktısını anlık takip etmek
- Session yönetimini kolaylaştırmak
- Tek panel üzerinden hızlı kontrol sağlamaktır.

---

## ⚙️ Kurulum

Projeyi klonlayın.

```bash
git clone https://github.com/KULLANICI/szr-console.git
cd szr-console
unzip szr-console.zip
```

Bağımlılıkları yükleyin.

```bash
pip install -r requirements.txt
```


Projeyi çalıştırın.

```bash
python app.py
```

Tarayıcıdan giriş yapın.

```text
http://127.0.0.1:5000
```

---

## 🛠️ Kullanılan Teknolojiler

- Python
- Flask
- Flask-SocketIO
- SQLite
- HTML5
- CSS3
- JavaScript

---

## 📌 Durum

Proje aktif olarak geliştirilmektedir.

Yeni özellikler, performans iyileştirmeleri ve hata düzeltmeleri düzenli olarak eklenmektedir.

---

## 🤝 Katkı

Hata bildirimi, öneri veya geliştirme fikirlerine her zaman açığım.

Projeyi beğendiysen ⭐ bırakmayı unutma.

---
