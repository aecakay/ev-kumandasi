# Ev Kumandası (Vestel TV & Digiturk IR Remote)

Bu Android uygulaması, **Redmi Note 13 Pro** üzerinde dahili olarak bulunan **Kızılötesi (IR Blaster)** donanımını kullanarak:
1. **Vestel 50QA9700 Android TV** (NEC Protokolü / 38 kHz)
2. **Digiturk Uydu Alıcısı** (RC6 / 36 kHz)

cihazlarını tek bir arayüzden kontrol etmeyi sağlar.

---

## Proje Dosyaları
* **Ana Kod:** [`MainActivity.java`](file:///C:/Users/Emre%20AKAY/.gemini/antigravity/scratch/remote_controller_app/app/src/main/java/com/example/remotecontroller/MainActivity.java)
* **Kızılötesi Sinyal Kodlayıcı:** [`IrSignalHelper.java`](file:///C:/Users/Emre%20AKAY/.gemini/antigravity/scratch/remote_controller_app/app/src/main/java/com/example/remotecontroller/IrSignalHelper.java)
* **Arayüz Tasarımı:** [`activity_main.xml`](file:///C:/Users/Emre%20AKAY/.gemini/antigravity/scratch/remote_controller_app/app/src/main/res/layout/activity_main.xml)
* **Manifest (İzinler):** [`AndroidManifest.xml`](file:///C:/Users/Emre%20AKAY/.gemini/antigravity/scratch/remote_controller_app/app/src/main/AndroidManifest.xml)

---

## Nasıl Derlenir / Telefona Yüklenir?
1. **Android Studio**'yu açın.
2. `Open Project` diyerek şu dizini seçin:
   `C:\Users\Emre AKAY\.gemini\antigravity\scratch\remote_controller_app`
3. Redmi Note 13 Pro telefonunuzda **Geliştirici Seçenekleri** ve **USB Hata Ayıklama**'yı açıp bilgisayara bağlayın.
4. Android Studio'da **Run (Oynat)** butonuna basarak uygulamayı doğrudan telefonunuza yükleyin.
