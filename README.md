# PrivacyPages — 10 oyunun herkese açık gizlilik politikaları

2 Ekim 2026 tarihinde Claude tarafından üretildi. Bu klasör olduğu gibi statik bir siteye (GitHub Pages, Cloudflare Pages, Netlify vb.) yüklenebilir.

1. ~~Destek e-postasını yaz~~ — **yapıldı (3 Ekim 2026):** geliştirici `AstorDEV`, e-posta `astordeveloperr@gmail.com`, tüm sayfalara yazıldı.
   Kökteki `app-ads.txt` gerçek AdMob yayıncı kimliğini (`pub-9960326581432207`) içerir; sitenin KÖKÜNDE yayınlanmalı.
2. Klasörü yayınla. **Önerilen GitHub Pages kurulumu:** repo adı tam olarak `bulutyagizkalafat.github.io` olsun (public) → bu klasörün içeriğini repo KÖKÜNE koy → Settings > Pages > Branch: main / root. Böylece site `https://bulutyagizkalafat.github.io/` olur ve `app-ads.txt` doğrudan `https://bulutyagizkalafat.github.io/app-ads.txt` adresinde durur (AdMob bunu ister). Play Console'da her oyunun mağaza girişindeki **Web sitesi** alanına `https://bulutyagizkalafat.github.io` yaz.
3. Her oyunun adresi: `https://bulutyagizkalafat.github.io/<slug>/` (İngilizce, Play Console'a bunu gir) ve `https://bulutyagizkalafat.github.io/<slug>/tr.html` (Türkçe).
4. Aynı adresi o oyunun `Assets/Scripts/UI/ShopPanel.cs` → `PrivacyPolicyUrl` sabitine yaz.

| Oyun | slug |
|---|---|
| Repair Master (Tamirhane Ustası) | `repair-master` |
| Cargo Boss (Kargo Şefi) | `cargo-boss` |
| Coffee Tycoon (Kahve Dükkânı) | `coffee-tycoon` |
| Mine Tycoon (Hurda Madeni) | `mine-tycoon` |
| Parking Boss (Otopark Operatörü) | `parking-boss` |
| Market Tycoon (Mini Market Patronu) | `market-tycoon` |
| Clean Master (Temizlik Ekibi) | `clean-master` |
| Fishing Master (Balıkçı İskelesi) | `fishing-master` |
| Garden Merge (Bahçe Tasarımcısı) | `garden-merge` |
| Airport Boss (Havalimanı Müdürü) | `airport-boss` |

**3 Ekim 2026:** GitHub hesabı `bulutyagizkalafat` → repo adı `bulutyagizkalafat.github.io`, site `https://bulutyagizkalafat.github.io/`. 10 oyunun `ShopPanel.cs` dosyasındaki gizlilik adresleri bu siteye göre zaten yazıldı.
