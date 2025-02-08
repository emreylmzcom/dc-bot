# Çaycı

Bu Discord botu, çeşitli eğlence, ekonomi ve müzik özellikleri sunan çok amaçlı bir Discord botudur. Slash komut sistemi ile modern ve kullanıcı dostu bir arayüz sunar.

## 🎯 Özellikler

### 🎵 Müzik Sistemi
- YouTube üzerinden müzik çalma
- Sıra sistemi ve playlist desteği
- Şarkı kontrolleri (durdur/devam/geç)
- Otomatik ses kanalından çıkma
- Kullanıcı dostu buton kontrolleri

### 💰 Ekonomi Sistemi
- Sikke tabanlı ekonomi sistemi
- Kullanıcılar arası transfer
- Global ve sunucu bazlı sıralama
- Döviz kuru bilgisi (TL/USD)

### 🎮 Eğlence Komutları
- Bilmece ve quiz sistemi
- Zar ve yazı-tura oyunları
- Rulet sistemi
- Duello sistemi
- Takım kurma ve maç yapma

### 📢 Bildirim Sistemleri
- Oyun indirimi bildirimleri
- Haber bildirimleri
- Kişisel hatırlatıcı sistemi

## 🎮 Komutlar

### Genel Komutlar
- `/komutlar` - Tüm komutları listeler
- `/oyunbildirimac <kanal>` - Oyun indirim bildirimlerini açar
- `/haberbildirimac <kanal>` - Haber bildirimlerini açar
- `/hatirlatici_ekle <içerik> <gün> <saat> <dakika>` - Hatırlatıcı ekler
- `/hatirlaticilar` - Hatırlatıcıları listeler
- `/hatirlatici_sil <id>` - Hatırlatıcı siler

### Müzik Komutları
- `/cal <şarkı adı veya URL>` - Müzik çalar
- Şarkı kontrolü için interaktif butonlar
- `/siradakiler` - Sıradaki şarkıları gösterir

### Ekonomi Komutları
- `/bakiye` - Bakiyenizi gösterir
- `/btransfer <kişi> <tutar>` - Para transferi yapar
- `/siralama` - En zengin 20 kişiyi listeler
- `/sunucu_sikke_siralamasi` - Sunucudaki sıralamayı gösterir
- `/dolar` - Güncel dolar kurunu gösterir

### Eğlence Komutları
- `/bilmece` - Bilmece sorar
- `/quiz` - Quiz sorusu sorar
- `/zar <bahis> <tahmin>` - Zar oyunu
- `/yazitura <bahis> <yazı/tura>` - Yazı tura oyunu
- `/rulet <bahis>` - Rulet oyunu
- `/duello <kişi>` - Duello başlatır

### Takım Oyunu Komutları
- `/takimolustur <takım adı> <yatırım>` - Yeni takım oluşturur
- `/takimyatirim <yatırım>` - Takıma yatırım yapar
- `/macyap <bahis>` - Takımınızla maç yapar
- `/takimim` - Takım bilgilerini gösterir
- `/lig` - Lig durumunu gösterir

## 🌐 Bağlantılar

Website: [cayci.com.tr](https://cayci.com.tr)

## 📝 Not

Bot sürekli geliştirilmekte ve yeni özellikler eklenmektedir. Güncel komut listesi için `/komutlar` komutunu kullanabilirsiniz.

## 🛠️ Kurulum

1. Botu sunucunuza eklemek için: [Davet Linki](bot_davet_linki)
2. Varsayılan prefix: `/` (Slash Commands)
3. Başlangıç bakiyesi: 100 sikke

## 🎯 Özellik Detayları

### 💰 Ekonomi Sistemi Detayları
- Başlangıç bakiyesi: 100 sikke
- Minimum transfer miktarı: 1 sikke
- Maksimum bahis: Mevcut bakiyeniz
- Kazanç oranları:
  - Quiz doğru cevap: +50 sikke
  - Bilmece doğru cevap: +30 sikke
  - Duello kazanma: Bahis miktarının 2 katı

### 🎲 Oyun Detayları
- Zar: 1-6 arası tahmin, doğru bilirseniz 6x kazanç
- Yazı Tura: 2x kazanç
- Rulet: 2x kazanç
- Duello: Kazanan bahsin 2 katını alır

### ⚽ Takım Sistemi Detayları
- Minimum takım kurma maliyeti: 1000 sikke
- Minimum maç bahsi: 100 sikke
- Takım geliştirme sistemi:
  - Her kazanılan maç: +10 güç puanı
  - Her yatırım: Yatırım miktarının %1'i kadar güç puanı

## 🤖 Bot İstatistikleri
- Toplam Sunucu Sayısı: xxx
- Toplam Kullanıcı Sayısı: xxx
- Çalınan Toplam Şarkı: xxx
- Oynanan Toplam Oyun: xxx

## 🔒 Güvenlik
- Tüm komutlar rate-limit korumalı
- Ekonomi sistemi manipülasyon korumalı
- Düzenli veritabanı yedeklemesi
- SSL korumalı bağlantılar

## 🆘 Destek
- Destek Sunucusu ve Bug Bildirimi: [Discord Sunucusu](https://discord.com/invite/dSVRs26v5t)


## 📊 Sürüm Geçmişi
### v2.0.0 (Güncel)
- Slash komut sistemine geçiş
- Müzik sistemi yenilendi
- Duello sistemi eklendi
- Haber bildirimleri eklendi

### v1.5.0
- Takım sistemi eklendi
- Ekonomi sistemi güncellendi
- Yeni oyunlar eklendi

## 🗺️ Yol Haritası
- [ ] Seviye sistemi
  - Mesaj ve ses aktivitelerine göre XP kazanma
  - Seviye atladıkça sikke ödülü
  - Seviye rozetleri
  
- [ ] Mini oyunlar
  - Kelime oyunu (Bir harfle başlayan kelime bulma)
  - Matematik yarışması
  - Hafıza kartı oyunu
  - Şans çarkı

- [ ] Ekonomi geliştirmeleri
  - Günlük ödül sistemi
  - Haftalık görevler
  - Market sistemi (Rol satın alma, özel eşyalar)


- [ ] Moderasyon özellikleri
  - Otomatik küfür engelleme
  - Spam koruması
  - Davet takip sistemi
  - Hoşgeldin mesajı özelleştirme
  - Oto-rol sistemi


- [ ] Eğlence özellikleri
  - Emoji ile tepki-rol sistemi
  - Doğum günü hatırlatıcı
  - Rastgele meme/gif paylaşımı
  - Özel sunucu emojileri oluşturma

- [ ] Kullanıcı deneyimi
  - Türkçe dil dosyasının geliştirilmesi
  - Komut açıklamalarının detaylandırılması
  - Yardım menüsünün kategorilere ayrılması
  - Komut kısayolları



## 📜 Kullanım Koşulları
- Bot'u kullanarak [Kullanım Koşulları](https://caycibot.com.tr/)'nı kabul etmiş olursunuz
- Haksız kullanım tespitinde hesabınız kara listeye alınabilir

