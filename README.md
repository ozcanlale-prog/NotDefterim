# Günün Notu - Android Veri Aktarımı Uygulaması

Günün Notu, Android Studio üzerinde Activity'ler (Ekranlar) arası veri aktarımı (Intent) mantığını uygulamalı olarak gösteren temel seviye bir mobil uygulamadır.



https://github.com/user-attachments/assets/63577076-5261-46cb-a519-e9a5107dd83d



## 🚀 Çalışma Mantığı
Uygulama iki temel aşamadan oluşmaktadır:
1. **MainActivity (Giriş):** Kullanıcı `EditText` aracılığıyla "Bugün ne yapacaksın?" sorusuna yanıt verir ve butona tıklar.
2. **Intent Mekanizması:** Girilen metin, bir Intent nesnesi aracılığıyla ikinci aktiviteye taşınır.
3. **DetailActivity (Görüntüleme):** İlk ekrandan gelen veri yakalanır ve şık bir `TextView` üzerinde kullanıcıya gösterilir.

## 💻 Teknik Detaylar
- **Bileşenler:** EditText, Button, TextView, Intent PutExtra/GetExtra.
- **Layout:** Responsive (esnek) tasarım için ConstraintLayout kullanımı.
- **Navigasyon:** Sayfalar arası geçiş ve geri dönüş buton optimizasyonu.

## 🛠 Kurulum
1. Projeyi bilgisayarınıza clone'layın.
2. Android Studio ile projeyi açın.
3. Gradle senkronizasyonunun tamamlanmasını bekleyin.
4. Herhangi bir Android Emülatör üzerinde çalıştırın.
