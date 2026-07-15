🚀 SZR Console

SZR Console, Metasploit Framework'ü web arayüzü üzerinden daha rahat yönetebilmek için geliştirdiğim basit ve hafif bir projedir. Amaç, sürekli terminal ile uğraşmadan oturumları, komutları ve çıktıları tek bir panel üzerinden takip edebilmek.

✨ Özellikler

- Web tabanlı Metasploit yönetimi
- Gerçek zamanlı terminal çıktıları (Socket.IO)
- MSF Console entegrasyonu
- Session görüntüleme ve yönetimi
- SQLite veritabanı desteği
- Flask tabanlı hafif yapı
- Karanlık tema arayüzü
- Modüler dosya yapısı

📁 Proje Yapısı
'''
szr-console/
├── app.py
├── api.py
├── socket_events.py
├── rpc_client.py
├── msf_console_manager.py
├── database.py
├── config.py
├── utils.py
├── templates/
└── requirements.txt
'''
⚙️ Kurulum

Projeyi klonlayın:
bash '''
git clone https://github.com/szrkalitr/Szr-console
cd Szr-onsole
unzip szr-console.zip
'''
Gerekli paketleri yükleyin:
'''
pip install -r requirements.txt
'''
Uygulamayı başlatın:
''"
python app.py
'''
Daha sonra tarayıcıdan:

http://127.0.0.1:5000

adresine giderek arayüzü kullanabilirsiniz.

🛠️ Kullanılan Teknolojiler

- Python
- Flask
- Flask-SocketIO
- SQLite
- HTML / CSS / JavaScript

📌 Not

Bu proje tamamen öğrenme ve geliştirme amacıyla ortaya çıktı. Zamanla yeni özellikler, hata düzeltmeleri ve performans iyileştirmeleri eklemeye devam edeceğim.

Kodlar mükemmel olmayabilir ama sürekli gelişiyor. Öneri ve katkılara her zaman açığım.

⭐ Destek

Projeyi beğendiysen yıldız bırakmayı unutma. Geri bildirimler projeyi geliştirmeme gerçekten yardımcı oluyor.

İyi kullanımlar! ☕