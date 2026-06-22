# Mucize — Bootstrap Sürümü (tek dosya)

Özel eğitim / rehabilitasyon merkezleri için **tek sayfalık** statik site.
Stack: Bootstrap 5 (CDN) + vanilla JS + HTML5. Build adımı YOK.

## Çalıştırma
`index.html` dosyasını tarayıcıda aç — bu kadar. (Form ve WhatsApp için
internet gerekir; CDN'ler buradan yüklenir.)

## Yeni müşteriye uyarlama
1. `index.html` aç. En üstteki `<style>` içinde **":root" bloğundaki renkleri**
   değiştir (--brand-primary, --brand-accent ...). Tüm site otomatik değişir.
2. `<title>` ve `<meta name="description">` güncelle.
3. Metinleri (kurum adı, hizmetler, kadro, iletişim) HTML içinde değiştir.
   Telefon/WhatsApp numaralarını ara-değiştir ile topluca güncelleyebilirsin
   (905320000000 ve +902120000000 geçen yerler).
4. Görselleri `assets/img/` ve `assets/img/gallery/` içine koy; hero için
   yer tutucu div'i `<img class="hero-art" ...>` ile değiştir.

## Form
- Formdaki `data-key=""` alanına web3forms.com'dan alacağın ücretsiz anahtarı
  yazarsan mesaj e-posta olarak gelir. Boşsa form WhatsApp'a yönlendirir.

## Yayınlama
Tüm klasörü Cloudflare Pages / Netlify'a sürükle-bırak, ya da herhangi bir
statik hosting'e at. Build ayarı gerekmez.
