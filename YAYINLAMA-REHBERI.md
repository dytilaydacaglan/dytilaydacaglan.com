# Site Kullanım Rehberi

Site GitHub Pages üzerinde, ücretsiz ve kalıcı olarak yayında.

- **Site adresi:** https://dytilaydacaglan.github.io/dytilaydacaglan.com/
- **Dosyaların durduğu yer (depo):** https://github.com/dytilaydacaglan/dytilaydacaglan.com
- **GitHub hesabı:** dytilaydacaglan

Site İlayda'nın kendi GitHub hesabındadır; başka bir hesaba bağlı değildir.
Danışanlar sadece web sitesini görür; değişiklik yalnızca bu hesapla yapılabilir.

---

## Galeriye fotoğraf / video ekleme

1. github.com'a giriş yapın → **dytilaydacaglan.com** deposunu açın.
2. **galeri** klasörüne tıklayın.
3. **Add file** → **Upload files** → fotoğraf/videoları sürükleyin.
4. Yeşil **Commit changes** butonuna basın.
5. 1–2 dakika içinde sitede görünür.

İpuçları:
- Dosya adını tarihle başlatın: `2026-10-05-ofis.jpg` → en yeniler en üstte görünür.
- Videolar en fazla **25 MB** olabilir.
- Telefondan yüklemek için tarayıcıda github.com'u açıp menüden **Masaüstü sitesi**ni seçin.
- Silmek için: dosyaya tıklayın → sağ üstteki **⋯** → **Delete file** → **Commit changes**.

## Sitedeki yazıları değiştirme

1. Depoda `index.html` dosyasına tıklayın → sağ üstteki kalem (✏️) simgesi.
2. **Ctrl + F** ile değiştirmek istediğiniz yazıyı bulun ve düzeltin.
3. **Commit changes** → açılan pencerede **Commit directly to the main branch** seçili olsun → **Commit changes**.
4. 1–2 dakika içinde sitede görünür. Eski hali görünürse sayfayı **Ctrl + F5** ile yenileyin.

## dytilaydacaglan.com adresini bağlama

1. Adresi bir alan adı firmasından (ör. natro.com) satın alın. Sadece alan adı yeterli;
   hosting, e-posta, SSL paketi gerekmez.
2. Firmanın panelinde **DNS Yönetimi**ne şu kayıtları ekleyin
   (`@` için önceden var olan başka A kayıtlarını silin):

   | Tür   | Host | Değer                     |
   |-------|------|---------------------------|
   | A     | @    | 185.199.108.153           |
   | A     | @    | 185.199.109.153           |
   | A     | @    | 185.199.110.153           |
   | A     | @    | 185.199.111.153           |
   | CNAME | www  | dytilaydacaglan.github.io |

3. GitHub'da depo → **Settings** → **Pages** → **Custom domain** kutusuna
   `dytilaydacaglan.com` yazın → **Save**.
4. Kontrol tamamlanınca **Enforce HTTPS** kutusunu işaretleyin.
5. DNS'in yayılması birkaç dakika ile birkaç saat sürebilir; ardından site
   **https://dytilaydacaglan.com** adresinden açılır.
