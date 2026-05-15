# VardiyaApp

Bu proje, çalışan vardiya takibi, giriş-çıkış raporları, izin talepleri ve yönetici / personel yönetimi işlevlerini içeren bir uygulamadır.

## İçerik

- MainCode.tro ve uygulama ekranlarını içeren .tro dosyaları
- calisan.tro, calisangiris.tro, izintalebi.tro, yoneticigiris.tro gibi çalışan ve giriş ekranları
- personelyonetim.tro, yonetici.tro, izin.tro, ardiyaatama.tro vb. yönetim ekranları

## Supabase yapılandırması

Bu uygulama Supabase REST API ile çalışmak üzere tasarlanmıştır. GitHub'a yüklemeden önce aşağıdaki değerleri kesinlikle proje dosyalarına sabit olarak yazmayın:

- SUPABASE_URL
- SUPABASE_KEY

Projede bu değerler tüm .tro dosyalarında boş bırakıldı ve GitHub'a yüklenirken gizlilik korunması için kaldırıldı.

## Nasıl kullanılır

1. Projeyi açın ve geliştirme ortamınızda çalıştırın.
2. Supabase yapılandırmasını güvenli biçimde sağlayın.
3. SupabaseAyarla fonksiyonlarına kendi Supabase URL ve anahtar bilgilerinizi ekleyin ya da proje için güvenli bir yapılandırma yöntemi kullanın.

## Ekran görüntüleri ve demo videosu

Aşağıdaki ekran görüntüleri proje kökünde yer alan `ScreenShots/` klasöründe bulunuyor. Bu dosyalar, uygulamanın hem personel hem yönetici tarafındaki çalışan sayfa tasarımlarını gösterir.

- `ScreenShots/Giris.png`
- `ScreenShots/personelgiris.png`
- `ScreenShots/yönetisigiris.png`
- `ScreenShots/yöneticianasayfa.png`
- `ScreenShots/yöneticivardiyatama.png`
- `ScreenShots/yöneticivardiyatama2.png`
- `ScreenShots/yöneticiizintalebi.png`
- `ScreenShots/yönetiverilenpingecmisi.png`
- `ScreenShots/yöneticigiriscikistakibi.png`
- `ScreenShots/calisananasayfa.png`
- `ScreenShots/calisanizintalebi.png`
- `ScreenShots/calisanmolatalebi.png`
- `ScreenShots/calisanprofil.png`

### Sayfa tanımları ve yapılabilecek işlemler

#### `ScreenShots/Giris.png`
- Uygulama açılış ekranı.
- Personel veya yönetici giriş ekranına yönlendirme.

#### `ScreenShots/personelgiris.png`
- Personel e-posta ve şifre ile giriş.
- Yeni kayıt oluşturma seçeneği.
- Demo personel girişi.

#### `ScreenShots/yönetisigiris.png`
- Yönetici kullanıcı girişi.
- Yönetici hesap geçmişi ve yetkilendirme.
- Demo yönetici girişi.

#### `ScreenShots/yöneticianasayfa.png`
- Yönetici kontrol paneli.
- Günlük personel durumu özetleri.
- Hızlı işlem butonları: İzin talepleri, vardiya atama.
- Raporlara ve profillere erişim.

#### `ScreenShots/yöneticivardiyatama.png`
- Vardiya atama ekranı.
- Personel seçme, tarih seçimi ve vardiya planlama.
- Vardiya ekleme / düzenleme işlemleri.

#### `ScreenShots/yöneticivardiyatama2.png`
- Haftalık vardiya planı görünümü.
- Seçilen günler ve vardiya detayları.
- Atanmış vardiyaların listelenmesi.

#### `ScreenShots/yöneticiizintalebi.png`
- Yönetici izin talepleri ekranı.
- Bekleyen izinleri onaylama veya reddetme.
- İzin durumunu ve tarih aralığını gösterme.

#### `ScreenShots/yönetiverilenpingecmisi.png`
- Personel PIN geçmişi.
- Geçersiz / başarılı PIN kullanım kayıtları.
- PIN sonuçlarının detaylı açıklamaları.

#### `ScreenShots/yöneticigiriscikistakibi.png`
- Giriş/çıkış raporu ekranı.
- Personelin günlük giriş-çıkış kayıtları.
- Mevcut mesai ve mola durumları.

#### `ScreenShots/calisananasayfa.png`
- Personel ana kontrol paneli.
- Günlük vardiya, izin ve mola durumu.
- PIN kodu oluşturma ve hızlı işlemler.

#### `ScreenShots/calisanizintalebi.png`
- Personel izin talebi ekranı.
- İzin türü seçme, başlangıç / bitiş tarihleri belirleme.
- Talep gönderme ve açıklama ekleme.

#### `ScreenShots/calisanmolatalebi.png`
- Personel mola başlatma ekranı.
- Mola hakkı ve mevcut mola durumunu gösterme.
- Mola başlatma veya durumu güncelleme.

#### `ScreenShots/calisanprofil.png`
- Personel profil ekranı.
- Çalışan detayları, departman, rol, e-posta ve durum bilgisi.
- Kişisel bilgileri görüntüleme.

Bu proje için ayrıca ek bir demo videosu da sağladınız:

- `c:\Users\Lenovo\AppData\Local\Packages\Microsoft.ScreenSketch_8wekyb3d8bbwe\TempState\Recordings\20260515-2110-17.0778274.mp4`

> Not: Bu video dosyası repo içinde yer almıyor. Eğer isterseniz videoyu proje köküne veya `assets`/`media` klasörüne taşıyın, ben sonra README içindeki bağlantıyı güncelleyeyim.

