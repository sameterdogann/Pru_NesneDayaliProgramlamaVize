# Sinema Müşteri Kaydı ve Bilet Sistemi

Bu proje, bir sinema salonu için temel müşteri kaydı, film yönetimi ve bilet takip işlemlerini gerçekleştiren, konsol tabanlı nesneye dayalı bir Java uygulamasıdır.

## 👨‍💻 Proje Sahibi & Akademik Bilgiler

* **Ad Soyad:** Samet ERDOĞAN
* **Öğrenci Numarası:** 20230108039
* **Bölüm:** Bilgisayar Programcılığı
* **Üniversite:** Piri Reis Üniversitesi
* **Ders Adı:** Nesneye Dayalı Programlama 1
* **Ders Kodu:** BIP1026
* **Öğretim Görevlisi:** Emrah SARIÇİÇEK
* **Teslim Tarihi:** 06/04/2025

---

## 🚀 Proje Hakkında

Uygulama, temel Java kontrol yapıları, diziler (arrays) ve çok boyutlu matris yapıları kullanılarak geliştirilmiştir. Harici bir veritabanı bağımlılığı olmadan bellek içi (in-memory) veri yönetimi sağlar.

### 🌟 Başlangıç Verileri
* **Ön Yüklü Filmler (4 Adet):** Breaking Bad, Mr. Robot, İnception, Die Hard
* **Ön Yüklü Kullanıcılar (3 Adet):** Samet, Ahmet, Ali

---

## 📋 Özellikler ve Menü Seçenekleri

Sistem, kullanıcı çıkış yapana kadar çalışan interaktif bir `while` döngüsü menüsü sunar:

1. **Yeni Film Ekle:** Maksimum 10 film kapasitesiyle sisteme yeni film adı, süresi ve türü ekler.
2. **Filmleri Listele:** Sistemde kayıtlı tüm filmleri detaylarıyla birlikte ekrana yazdırır.
3. **Yeni Kullanıcı Kaydı:** Maksimum 20 kullanıcı kapasitesiyle ad ve e-posta bilgisi alarak kayıt yapar.
4. **Kullanıcıları Listele:** Sistemdeki kayıtlı tüm kullanıcıları listeler.
5. **Bilet Oluştur:** Seçilen kullanıcı ile seçilen film arasında ilişki kurarak 2 boyutlu matris üzerinde (`biletler[kullanıcı][film] = 1`) bilet kaydı oluşturur.
6. **Kullanıcı Biletlerini Görüntüle:** Belirli bir kullanıcının daha önceden bilet aldığı tüm filmleri listeler.
7. **Sistemden Çıkış:** Uygulamayı sonlandırır.

---

## 🛠️ Teknik Altyapı ve Kullanılan Yapılar

* **Programlama Dili:** Java
* **Veri Yapıları:** Tek boyutlu diziler (`String[]`), İki boyutlu matrisler (`int[][]`)
* **Akış Kontrolleri:** `while` döngüleri, `if-else` koşul blokları
* **Kullanıcı Etkileşimi:** `java.util.Scanner`

---

## 📦 Gereksinimler

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki bileşenlerin kurulu olması gerekir:

* **Java Development Kit (JDK):** Sürüm 8 veya üzeri
* **Java IDE:** IntelliJ IDEA, Eclipse, NetBeans veya VS Code

---

## ⚙️ Nasıl Çalıştırılır?

1. Projeyi bilgisayarınıza klonlayın veya indirin:
   ```bash
   git clone [https://github.com/kullanici-adiniz/proje-adi.git](https://github.com/kullanici-adiniz/proje-adi.git)
