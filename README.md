# EKA Cloudflare Bölge Yöneticisi

## Proje Açıklaması
EKA Cloudflare Bölge Yöneticisi, Cloudflare DNS kayıtlarınızı toplu olarak yönetmenizi sağlayan bir web uygulamasıdır. Bu uygulama, özellikle birden fazla DNS kaydının IP adresini hızlı ve etkili bir şekilde değiştirmeniz gerektiğinde kullanışlıdır.

## Özellikler
- Cloudflare hesabınızdaki tüm bölgeleri listeleme
- Seçilen bölgelerdeki DNS kayıtlarını görüntüleme
- Belirli bir IP adresine sahip tüm DNS kayıtlarını toplu olarak güncelleme
- Gerçek zamanlı güncelleme durumu ve sonuçları
- Kullanıcı dostu arayüz
- Kullanıcı kimlik doğrulama sistemi

## Yerel Kurulum ve Çalıştırma
1. Bu projeyi klonlayın:
   ```
   git clone https://github.com/ekayazilim/cloudflare-zone-manager.git
   cd cloudflare-zone-manager
   ```

2. Gerekli Python paketlerini yükleyin:
   ```
   pip install -r requirements.txt
   ```

3. Uygulamayı çalıştırın:
   ```
   python main.py
   ```

4. Tarayıcınızda `http://localhost:5000` adresine gidin.

## Kullanım
1. Uygulama başlatıldığında, önce kayıt olmanız veya giriş yapmanız gerekecektir.
2. Giriş yaptıktan sonra, Cloudflare API anahtarınızı ve e-posta adresinizi girin.
3. "Bölgeleri Listele" butonuna tıklayarak Cloudflare hesabınızdaki bölgeleri görüntüleyin.
4. IP adresini değiştirmek istediğiniz bölgeleri seçin.
5. Eski IP adresini ve yeni IP adresini girin.
6. "IP'yi Değiştir" butonuna tıklayarak güncelleme işlemini başlatın.
7. Gerçek zamanlı güncellemeleri ve sonuçları ekranda takip edin.

## Proje Yapısı
```
cloudflare-zone-manager/
│
├── app.py
├── main.py
├── requirements.txt
├── README.md
│
├── static/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── script.js
│
└── templates/
    ├── index.html
    ├── login.html
    └── register.html
```

## Şirket Bilgileri
EKA Yazılım ve Bilişim Sistemleri, web teknolojileri ve ağ yönetimi alanında uzmanlaşmış bir yazılım şirketidir. Müşterilerimize özel çözümler sunarak, işlerini daha verimli ve etkili bir şekilde yönetmelerine yardımcı oluyoruz.

## Destek
Herhangi bir soru veya sorun için lütfen bizimle iletişime geçin:

- Website: [ekasunucu.com](https://ekasunucu.com)
- Telefon: 0850 307 34 58

---

© 2024 EKA Yazılım ve Bilişim Sistemleri. Tüm hakları saklıdır.
