# Taşıyo - Özel Okullar İçin Araç ve Servis Yönetim Uygulaması

Taşıyo, özel okullar için geliştirilmiş modern bir araç ve servis yönetim uygulamasıdır. Okul yönetiminden velilere, servis şoförlerinden araç sahip veya yöneticilerine kadar geniş bir kullanıcı kitlesine hitap ederek taşımacılığı hem kolaylaştırır hem de daha güvenli hale getirir.



## Proje Amacı

Taşıyo, servis taşımacılığı sürecini dijitalleştirerek kullanıcıların:

- Araçları, öğrencileri ve rotaları kolayca yönetmesini,
- Öğrenci servis takibini güvenli şekilde yapmasını,
- Raporlama ve iletişim süreçlerini hızlandırmasını sağlar.



## Özellikler

### 1. **Özel Okul Paneli**
- Araç ve şoför atamaları.
- Rota ve güzergah planlaması.
- Raporlama (yakıt tüketimi, öğrenci durumu, vb.).

### 2. **Araç Yöneticisi Paneli**
- Araç durumu ve servis raporları.
- Şoför yönetimi ve görev atamaları.

### 3. **Veli Paneli**
- Anlık servis konumu takibi.
- Servis gecikme veya iptal bildirimleri.
- Servis geçmişi ve iletişim.

### 4. **Servis Şoförü Paneli**
- Rota ve durak bilgilerine erişim.
- Günlük görev yönetimi.
- Öğrenci alma/bırakma geri bildirimi.



## Teknoloji Yığını

- **Mobil Uygulama Geliştirme:** React Native
- **Backend:** MySQL, Firebase (Authentication, Firestore, Realtime Database)
- **Harita Entegrasyonu:** Google Maps API
- **Bildirimler:** Firebase Cloud Messaging (FCM)



## Kurulum

### Gereksinimler

- Node.js (En son sürüm önerilir)
- React Native EXPO
- Firebase SDK

### Adımlar

1. Bu repository'yi klonlayın:
    ```bash
    git clone https://github.com/kullaniciadi/tasiyo.git
    ```

2. Projeyi açın:
    ```bash
    cd tasiyo
    ```

3. Gerekli bağımlılıkları yüklemek için:
    ```bash
    npm install
    ```

4. Firebase yapılandırması için `google-services.json` dosyasını proje kök dizinine ekleyin.

5. Uygulamayı çalıştırın:
    ```bash
    npx react-native run-android    # Android cihazda test etmek için
    npx react-native run-ios        # iOS cihazda test etmek için
    ```



## Yol Haritası

- **1. Sürüm:** Temel özellikler, kullanıcı panelleri, harita entegrasyonu ve anlık bildirimler
- **2. Sürüm:** İleri seviye raporlama özellikleri.



## Branch Tanımları

### `main` Branch
- **Açıklama:** `main` branch'i, projenin üretim (production) sürümünü temsil eder. Bu branch sadece stabil ve test edilmiş kodu içerir. Yeni özellikler veya düzeltmeler için yapılan değişiklikler önce `develop` branch'ine yapılır ve ardından test edildikten sonra `main` branch'ine dahil edilir.
  
### `develop` Branch
- **Açıklama:** `develop` branch'i, geliştirme sürecindeki en son değişiklikleri içerir. Yeni özellikler, iyileştirmeler ve hata düzeltmeleri burada yapılır. Stabil hale geldiğinde, bu branch'deki kod `main` branch'ine merge edilir. Geliştiriciler, her yeni özellik için `develop` branch'inde çalışmalıdır.



## Katkıda Bulunma

Bu projeye katkıda bulunmak için:

1. Bir fork oluşturun.
2. Yeni bir branch oluşturun:
    ```bash
    git checkout -b feature/yeniozellik
    ```

3. Değişikliklerinizi yapın ve commit edin:
    ```bash
    git commit -m "Yeni özellik eklendi"
    ```

4. Branch'inizi push edin:
    ```bash
    git push origin feature/yeniozellik
    ```

5. Bir Pull Request oluşturun.
