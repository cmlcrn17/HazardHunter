# HazardHunter
İSG risk farkındalığını artırmak, çalışanlara gerçek hayattan örneklerle İSG eğitimi vermek ve öğrenmeyi etkileşimli hâle getirmek.

![ExampleUI](https://github.com/cmlcrn17/HazardHunter/blob/main/HazardHunter.png)

# 🎯 Geliştirme Aşamaları (Roadmap)
✅ Firebase Authentication (Gmail ile giriş)

✅ Firestore'da sorular ve doğru cevapları yapılandır

✅ Görsel + çoktan seçmeli seçim ekranı

✅ Kullanıcı cevabını ve doğru cevabı ChatGPT’ye gönder

✅ AI'dan yorum döndür

✅ Geri bildirim + puan ekranı

⏳ Ekstra: AI tarafından yanlış cevaplara göre kişiye özel “eğitim önerisi”

## 🔐 1. Giriş Sistemi (Authentication)
* Firebase Authentication
* Gmail oturum açma
* Kullanıcı bilgileri (UID, ad-soyad, e-posta) Firestore’da saklanır

## 🖼️ 2. Tehlike Gösterimi
* Firestore veya Storage’dan tehlike görselleri çekilir.
* Görsel ile birlikte aşağıdaki öğeler gösterilir:
* 1 görsel
* Çoktan seçmeli (A, B, C, D) açıklama seçenekleri

## 📝 3. Cevaplama & AI Değerlendirmesi talep edilerek ekrana basılır. 
