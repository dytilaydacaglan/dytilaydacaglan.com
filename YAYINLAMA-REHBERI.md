# Siteyi Ücretsiz ve Kalıcı Yayınlama Rehberi

Site **GitHub Pages** üzerinde yayınlanır: tamamen ücretsizdir, süresi dolmaz,
Claude'a veya başka bir hesaba bağlı değildir. Site İlayda'nın kendi GitHub
hesabında durur; hesap silinmedikçe site de silinmez.

---

## 1. GitHub hesabı açın (bir kere)

1. https://github.com/signup adresine gidin.
2. **İlayda'nın kendi e-postası** (caglanilayda@gmail.com) ile kayıt olun —
   site onun hesabına ait olsun.
3. Kullanıcı adı seçin, örn. `dytilaydacaglan`. Bu ad sitenin adresinde
   görünecek: `https://dytilaydacaglan.github.io`

## 2. Sitede iki satırı doldurun

`index.html` dosyasını Not Defteri ile açın, şu iki satırı bulun ve doldurun:

```
const GITHUB_KULLANICI = "dytilaydacaglan";
const GITHUB_DEPO = "dytilaydacaglan.github.io";
```

(Kullanıcı adınız farklıysa ikisinde de onu yazın.) Kaydedin.

## 3. Depoyu (repository) oluşturun

1. GitHub'da sağ üstteki **+** → **New repository**.
2. **Repository name:** `dytilaydacaglan.github.io` (kullanıcı adınız + `.github.io`).
3. **Public** seçili olsun → **Create repository**.

## 4. Dosyaları yükleyin

1. Açılan sayfada **uploading an existing file** bağlantısına tıklayın.
2. `ilayda-caglan` klasörünün **içindekileri** (index.html dosyası ve galeri
   klasörü) sürükleyip bırakın.
3. Aşağıdaki yeşil **Commit changes** butonuna basın.

## 5. Yayını açın

1. Depoda **Settings** → soldan **Pages**.
2. **Source:** Deploy from a branch · **Branch:** `main` · klasör `/ (root)` → **Save**.
3. 1–2 dakika sonra site yayında: `https://dytilaydacaglan.github.io`

---

## Galeriye fotoğraf / video ekleme (her zaman)

1. github.com'a girin → depoyu açın → **galeri** klasörüne tıklayın.
2. **Add file** → **Upload files** → fotoğraf/videoları sürükleyin.
3. **Commit changes**. Bir iki dakika içinde sitede görünür.

İpuçları:
- Dosya adını tarihle başlatın: `2026-10-05-ofis.jpg` → en yeniler en üstte görünür.
- Videolar en fazla **25 MB** olabilir (kısa klipler için yeterli). Telefon
  videolarını yüklemeden önce WhatsApp'tan kendinize gönderip geri kaydetmek
  boyutu küçültür.
- Telefondan yüklemek için tarayıcıda github.com'u açın ve menüden
  **"Masaüstü sitesi"**ni seçin.
- Silmek için: dosyaya tıklayın → sağ üstteki **⋯** → **Delete file** → Commit.

## Sitedeki yazıları değiştirmek

Depoda `index.html` → kalem (✏️) simgesi → değiştirin → **Commit changes**.

## İsteğe bağlı: kendi alan adı

`dytilaydacaglan.com` gibi bir adres istenirse alan adı yıllık ücretlidir
(site yine ücretsiz kalır). Alındıktan sonra **Settings → Pages → Custom domain**
kısmına yazılır.
