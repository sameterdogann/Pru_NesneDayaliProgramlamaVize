# Sinema Müşteri Kaydı ve Bilet Sistemi

Bu proje, bir sinema işletmesi için temel müşteri kaydı ve bilet işlemlerini gerçekleştiren bir konsol tabanlı sistemdir. Kullanıcılar sisteme kayıt olabilir, mevcut filmler arasından seçim yaparak bilet kaydı oluşturabilirler.

##  Proje Sahibi

- **Ad Soyad:** Samet ERDOĞAN  
- **Öğrenci Numarası:** 20230108039
- **Bölüm:** Bilgisayar Programcılığı
- **Ders Adı:** Nesneye Dayalı Programlama 1
- **Ders Kodu:** BIP1026
- **Öğretim Görevlisi:** Emrah SARIÇİÇEK
- **Teslim Tarihi:** 06/04/2025

## Proje Hakkında

Bu Java uygulaması, bir sinema salonu için temel yönetim sistemini simüle eder. Sistem şu özellikleri içerir:

- Kullanıcı kayıt ve yönetimi
- Film ekleme ve listeleme
- Bilet satış ve takip sistemi
- Kullanıcı bazlı bilet sorgulama

**Başlangıç Verileri:**
- 4 önceden tanımlı film
- 3 önceden tanımlı kullanıcı

## Özellikleri

**Film Listeleme:** 
Sistemde kayıtlı tüm filmleri (`filmlist`, `filmsüre`, `filmtür` dizilerini kullanarak) ad, süre ve tür bilgileriyle birlikte görüntüler. 
**Kullanıcı Kayıt:** Yeni kullanıcıları (`k_adi` ve `email` dizilerine kaydederek) sisteme ekler, maksimum 20 kullanıcı kapasitesi bulunur. 
**Bilet Kaydı:** Kullanıcıların seçtiği filmleri (`biletler` matrisinde 1 değeri atayarak) bilet olarak kaydeder. 
**Listeleme:** Hem kullanıcıları (`k_adi` dizisi) hem filmleri (`filmlist` dizisi) kolayca listeleyebilir. 
**Etkileşimli Konsol Arayüzü:** Scanner ile kullanıcı girdilerini alan ve while döngüsüyle sürekli çalışan basit bir metin tabanlı menü sistemi sunar (`k_tercih` değişkeniyle seçim yapılır). Tüm bu özellikler Java dizileri ve temel kontrol yapıları kullanılarak implemente edilmiştir.

## Gereksinimler

Bu projeyi çalıştırabilmek için aşağıdaki gereksinimlerin karşılanması gerekmektedir:
- **Java 8 veya daha yeni bir sürüm**
- **IDE veya metin editörü:** IntelliJ IDEA, Eclipse veya VSCode gibi bir Java IDE'si tercih edilebilir.

## Nasıl Çalıştırılır?

1. Projeyi klonlayın veya indirin:
   ```bash
   git clone [repo-url]
