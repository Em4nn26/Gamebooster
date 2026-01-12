# Gamebooster

🎮 FPS Booster Premium (Python)

FPS Booster Premium, Python ve Tkinter kullanılarak geliştirilmiş, Windows için basit ama etkili bir oyun performans yardımcı aracıdır.
Amaç; oyun oynarken sistemi daha temiz, stabil ve oyuna öncelik veren bir hale getirmektir.

Bu araç FPS mucizesi vaat etmez, fakat:

Sistem yükünü azaltır

Oyun işlemine öncelik verir

Gecikme ve takılmaları azaltmaya yardımcı olur



---

✨ Özellikler

✔ Temp (Geçici) dosyaları temizleme
✔ DNS cache temizleme
✔ Windows güç planını Yüksek Performans moduna alma
✔ Seçilen oyunun/uygulamanın işlem önceliğini artırma
✔ Modern, neon efektli Premium GUI
✔ Gerçek zamanlı log (kayıt) ekranı


---

🧠 Program Ne Yapar?

Program şu işlemleri yapar:

🧹 Temp Temizleme

%TEMP%

%TMP%

C:\Windows\Temp


klasörlerini temizler.
Kilitli dosyalar atlanır, sistem dosyalarına zarar verilmez.


---

🌐 DNS Cache Temizleme

Windows’un DNS önbelleğini sıfırlar:

ipconfig /flushdns

Bu işlem bazı online oyunlarda bağlantı stabilitesine yardımcı olabilir.


---

⚡ Yüksek Performans Modu

Windows güç planını High Performance moduna alır:

powercfg /S 8c5e7fda-e8bf-4a96-9a85-a6e23a8c635c

Bu sayede CPU daha agresif çalışır.


---

🚀 İşlem Önceliği Artırma

Açık olan işlemler listelenir (örnek: valorant.exe, cs2.exe).

Seçilen uygulamanın önceliği:

High

Above Normal

Normal

Below Normal

Idle


olarak ayarlanabilir.

Bu sayede oyun, CPU kaynaklarında öncelik kazanır.


---

🖥️ Arayüz Özellikleri

Neon yeşil premium tema

Glow (parlama) animasyonları

Buton tıklama animasyonu

Scrollbar’lı log ekranı


Tamamen Tkinter ile yapılmıştır, harici GUI kütüphanesi yoktur.


---

📦 Gereksinimler

Windows 10 / 11

Python 3.8 veya üzeri

Yönetici (Admin) yetkisi önerilir


Gerekli Python kütüphaneleri:

pip install psutil

(Tkinter Python ile birlikte gelir.)


---

📥 Kurulum

1️⃣ Python Kurulu Değilse

👉 https://www.python.org/downloads/
Kurarken “Add Python to PATH” işaretli olsun.


---

2️⃣ Dosyayı İndir

GitHub’dan dosyayı indir veya klonla:

git clone https://github.com/Em4nn26/Gamebooster.git
cd Gamebooster


---

3️⃣ Gerekli Kütüphaneyi Kur

pip install psutil


---

▶️ Nasıl Çalıştırılır?

Komut satırında dosyanın olduğu klasörde:

python gamebooster.py

💡 En iyi sonuç için:

> Sağ tık → Yönetici olarak çalıştır




---

🕹️ Kullanım

🔹 Tek tek kullanmak için:

🧹 Temp Temizle

🌐 DNS Cache Temizle

⚡ Yüksek Performans Modu

🚀 İşlem Önceliğini Yükselt


🔥 Hepsi birden:

👉 “TÜM FPS BOOST Ayarlarını Uygula”


---

⚠️ Önemli Uyarılar

Bu yazılım hile değildir

Online oyunlarda ban sebebi DEĞİLDİR

Sistem dosyalarına zarar vermez

FPS artışı donanıma göre değişir


> Gerçek FPS artışı için:

SSD

Dual channel RAM

Doğru GPU ayarları
her zaman daha etkilidir.
