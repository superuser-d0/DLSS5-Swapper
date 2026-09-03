<p align="center">
  <img src="docs/banner.png" alt="DLSS 5 Swapper" width="100%">
</p>

<h1 align="center">DLSS 5 Swapper</h1>

<p align="center">
  Uyumlu oyunlar ve emülatörler için DLSS 5 Neural Rendering kurun ve yönetin.
</p>

<p align="center">
  <a href="https://github.com/rakanki911/DLSS5-Swapper/releases/latest"><img src="https://img.shields.io/github/v/release/rakanki911/DLSS5-Swapper?color=8fd400&label=s%C3%BCr%C3%BCm" alt="Son sürüm"></a>
  <a href="https://github.com/rakanki911/DLSS5-Swapper/releases"><img src="https://img.shields.io/github/downloads/rakanki911/DLSS5-Swapper/total?color=8fd400&label=indirme&cacheSeconds=300" alt="Toplam indirme"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011-8fd400" alt="Windows 10/11">
  <img src="https://img.shields.io/badge/Linux-Proton%20%2F%20Wine-8fd400" alt="Proton veya Wine ile Linux">
  <img src="https://img.shields.io/badge/dil-38-8fd400" alt="38 dil">
</p>

<p align="center">
  <a href="README.md">English</a>
</p>

> **Bu bir fork.** [rakanki911/DLSS5-Swapper](https://github.com/rakanki911/DLSS5-Swapper) projesine
> Linux desteği ekler; geri kalan her şey özgün projenin emeğidir. Aşağıdaki indirme bağlantıları
> özgün projenin Windows sürümlerine aittir — bu fork hiçbir ikili dosya yayımlamaz. Linux'ta neyin
> çalıştığı ve nasıl derleneceği için [Linux](#linux) bölümüne bakın.

## 2.2.0 indir

[**Windows Kurulumu**](https://github.com/rakanki911/DLSS5-Swapper/releases/download/v2.2.0/DLSS5-Swapper-Setup-2.2.0.exe) ·
[**Taşınabilir**](https://github.com/rakanki911/DLSS5-Swapper/releases/download/v2.2.0/DLSS5-Swapper-2.2.0-portable.exe) ·
[Sağlama toplamları](https://github.com/rakanki911/DLSS5-Swapper/releases/download/v2.2.0/SHA256SUMS.txt)

<p align="center">
  <img src="https://raw.githubusercontent.com/rakanki911/DLSS5-Swapper/7415065e5c5437441d0e0b0a0362d0ada6d86e15/docs/screenshots/01-home.png" alt="Ana ekran" width="100%">
</p>

## Özellikler

- **Kolay kurulum:** DLSS'i yerel olarak destekleyen oyunlar, ya da DLSS5-Feeder üzerinden uyumlu DLSS'siz oyunlar.
- **Kütüphaneniz:** Steam, Epic, GOG, güncel Xbox Game Pass klasörleri ve elle eklenen oyun/emülatörler. Linux'ta: Steam Play, Heroic ve Lutris.
- **Arama ve filtreler:** başlık, grafik API'si, DLSS durumu/sürümü ve eklentileri birlikte süzün; sayaçlara tıklayarak filtreleyin.
- **Esnek düzen:** mağazaya göre gruplayın ya da hepsini tek listede gösterin; oyun görselleri ve açık/koyu tema.
- **Denetimli tarama:** tüm sürücüleri tarama **varsayılan olarak kapalı**. Eklenen klasörler normal şekilde taranır; tüm sürücülerde keşfi açmak veya tarama klasörlerini kaldırmak için Ayarlar'a bakın.
- **Sağ tık kısayolları:** klasörü aç/kopyala, yeniden tara, kapak görselini değiştir, özgün dosyaları geri yükle ya da oyunu gizle.
- **Yedekler ve Geçmiş:** özgün dosyaları geri yükleyin, kurulum kayıtlarını tutun, Geçmiş/etkinlik/kurulum günlüklerini kopyalayın.
- **Özel eklentiler:** Eklentiler sayfası, tümleşik kurulum rotalarının yanında kullanılmaya devam eder.

## 2.2.0 ile gelenler

- **⭐ İsteğe bağlı [OptiScaler DLSS-NR](https://github.com/Dagherbou/OptiScaler_DLSSNR/releases):** oyun sayfasında ReShade yerine bunu seçin. Değişikliği oyun kapalıyken uygulayın; istediğinizde geri dönün. Ayarlar ayrı tutulur.
- **SWTOR / DX9:** yalnızca yerel rota yerine doğru Feeder seçimi; 32 bit DX8 kurulumu eklendi.
- **Feeder onarımları:** 0.12.0 ile eşleşen bileşenler, düzeltilmiş shader/hazır ayar seçenekleri ve eksik Visual C++ çalışma zamanı denetimleri.
- **Daha iyi tespit:** küçük/iç içe çalıştırılabilir dosyalar ve Cyberpunk 2077 / Phantom Liberty kütüphane kayıtları.
- **Daha güvenli kurulum/geri yükleme:** yerel Streamline/FG dosyalarını korur, tekrarlı kurulum ve arka uç değişimlerinde yedekleri korur, çalıştırılabilir dosya kayıpken bile geri yükler.
- **Geçmiş ve çeviriler:** eksik kurulum geçmişini düzeltir; arama, filtreler ve kurulum uyarıları artık 38 dilin hepsini kapsar.

[Tüm düzeltmeler ve bilinen sınırlar →](docs/releases/v2.2.0.md)

## Uyumluluk

| Kategori | Destek |
| --- | --- |
| **Sistem** | Windows 10/11 x64; uyumlu 32 ve 64 bit oyunlar. Linux: Proton veya Wine ile çalışan Windows oyunları — bkz. [Linux](#linux) |
| **ReShade / Feeder GPU'ları** | RTX 20 / 30 / 40 / 50; daha eski serilerin desteği, pakete dahil değiştirilmiş çalışma zamanının yazarınca bildirilir |
| **OptiScaler GPU'ları** | Yalnızca RTX 50, NVIDIA sürücü **616.56+**, yerel DLSS'i açık 64 bit oyunlar |
| **DirectX 12** | Yerel DLSS, Feeder veya uygun OptiScaler oyunları |
| **DirectX 11** | 32/64 bit oyunlar için Feeder; uygun OptiScaler oyunları |
| **DirectX 9 / 8** | DX9: 32/64 bit; DX8: 32 bit, dgVoodoo2 → DX11 → Feeder üzerinden |
| **Vulkan / OpenGL** | ReShade/Feeder; uygun Vulkan oyunları OptiScaler da kullanabilir. Linux'ta Vulkan yalnızca OptiScaler ile |
| **DirectX 10** | Feeder tarafından doğrudan desteklenmez; mümkünse DX11 seçin |

OptiScaler'ın DX11/Vulkan yolu, varsayılan olarak FSR çıktısıyla bir DX12 köprüsü kullanır.
Vulkan arka ucunu değiştirirken **önce özgün dosyaları geri yükleyin**. OptiScaler, emülatör/DLSS'siz rota değildir.

## Linux

Proton veya Wine ile çalıştırılan Windows oyunları. Bir oyunun Linux'a özgü sürümü Windows DLSS
yükünü yükleyemeyeceği için atlanır.

**Neler bulunuyor**

| Başlatıcı | Notlar |
| --- | --- |
| **Steam Play** | Hem normal hem Flatpak kurulumu. Oyunun kendi `compatdata` prefix'i kullanılır |
| **Heroic** | Epic, GOG, Amazon ve elle eklenen oyunlar; normal ve Flatpak. Ayrı bir kurulum olarak listelenen bir DLC (Cyberpunk 2077'nin REDmod'u, bu şekilde bulundu) ana oyunla karıştırılmadan atlanıyor |
| **Lutris** | Wine oyunları; normal ve Flatpak |

Tüm sürücüleri tarama burada hiçbir şey bulmaz — Windows sürücü harflerini sayar. Bunun yerine
Ayarlar'dan klasörleri elle ekleyin.

**Çalışanlar**

- Zaten DLSS taşıyan bir oyunda DLSS çalışma zamanının değiştirilmesi ve Vulkan yolu dahil
  OptiScaler rotası — kurulum olarak. Neural Rendering'in ardından doğru render edip etmediği ayrı
  bir soru, aşağıda cevaplanıyor.
- ReShade Setup, oyunun zaten kullandığı prefix içinde çalıştırılıyor — Steam Play prefix'i ya da
  Heroic veya Lutris'in oyun için oluşturduğu Wine prefix'i. Kuruluma bu adım hiç gelmiyorsa prefix
  de gerekmiyor.
- "Önce oyunu kapatın" denetimi; PowerShell'e sormak yerine `/proc`'u okuyor.

**Çalışmayanlar**

- **Feeder rotası**, tamamen reddediliyor. Oyun yerine launcher'ı yamalıyor ve Proton oyunlarını
  açılamaz hâle getiriyordu — bunu Linux derlemeleri yayımlayıp bozulduklarını gören
  [Febsho](https://github.com/Febsho/DLSS5-Swapper-Linux) buldu. Vulkan zaten buraya hiç
  ulaşamıyordu: Feeder ReShade'i Windows implicit layer olarak kaydediyor, Wine ise katman sayımını
  host Vulkan loader'ına devrediyor, o da `.so` katmanları yüklüyor, Windows ReShade DLL'ini asla
  yüklemiyor. Native DLSS kullanın, Vulkan için de OptiScaler.
- **Non-addon ReShade taşıyan oyunlar.** Mevcut proxy başka bir moda ya da loader'a ait olabilir ve
  onu değiştirmek sağlam oyunları çökertiyordu. Aynı kaynak.
- **Proton runner'ı kullanan Lutris oyunları** (umu üzerinden başlatılıyor) ve **Heroic CrossOver
  bottle'ları**. İkisi de bulunuyor ve düz DLL değişimini yapabiliyor; yalnızca ReShade Setup adımı
  kullanılamıyor.
- **Emülatörler**, pratikte. Linux'ta gerçekten kullanılan derlemeler native; Wine altında
  çalışabilecek Windows derlemeleri ise Feeder'dan geçiyor, o da yukarıda reddediliyor.
- **Neural Rendering'in kendisi, görsel olarak.** Başlıyor, feature'ını oluşturuyor ve gerçek kare
  süresi harcıyor — aynı menü kapalıyken 129 fps, açıkken 54 — ama çizdiği şey siyah. Sahne
  kayboluyor. Log bunun yalnızca hoşa giden yarısını anlatıyor: her toggle'da `feature 18 created`,
  temiz açılışta da `inline feature 18 evaluation succeeded`. Bu dosyanın önceki bir sürümünün
  "çalışıyor" demesinin sebebi buydu. Çalışmıyor; o iddia ekrana değil loga bakılarak yazılmıştı.
- **Kapatıp açmak** bir kez de oyunu çökertti:
  `EXCEPTION_ACCESS_VIOLATION reading address 0xffffffffffffffff`. Aynı adres, tamamen farklı bir
  Proton build'inde çalışan ikinci ve alakasız bir oyunu (Cyberpunk 2077) da çökertti — burada
  toggle'da değil, Neural Rendering feature'ı ilk kez oluşturulurken. Her iki çökme raporu da
  logdaki o feature'ı kuran thread'i işaret ediyor, ve her ikisinde de oyunun kendi çökme
  raporlayıcısı ReShade'ten bağımsız olarak devreye girdi — bu da motora ya da build'e özgü bir
  tuhaflık değil, add-on'un Proton altındaki feature yaşam döngüsünde tek bir hata olduğunu
  gösteriyor.
- OptiScaler'ın GPU denetimi NVIDIA sürücüsünü bir Windows sürüm numarasıyla karşılaştırıyor, oysa
  Linux sürücüsü aynı numaralandırmayı kullanmıyor. Bu eşik, gerçek DLSS 5 gereksinimine karşı
  doğrulanmadı.

**Proton'un önce ihtiyaç duyduğu tek şey**

Add-on çalışma anında bir shader derliyor ve Wine'ın `d3dcompiler_47`'si — 370 KB, arkasında
vkd3d'nin eksik HLSL derleyicisi — `isnan` uygulamıyor; derleme başarısız oluyor ve Neural
Rendering hiç başlamıyor. Microsoft'un 4 MB'lık kendi DLL'inde bu var. Oyunun prefix'ine bir kez
kurun:

```bash
protontricks <appid> d3dcompiler_47
```

Onsuz log `proxy encode compilation failed ... Function "isnan" is not defined` ile doluyor; onunla
bu hata tamamen kayboluyor. Neural Rendering sonrasında doğru render etmese de bu adım yine de
gerekli — onsuz hiçbir şey olmuyor.

**Çalıştırmak**

Linux için hazır bir ikili dosya yok. Kaynaktan çalıştırın (Node 24 ile denendi):

```bash
npm install && npm start
```

Herhangi bir kurulum yapabilmek için ayrıca `payload/` klasörü gerekiyor — DLSS 5 çalışma zamanı,
ReShade Setup ve Feeder bileşenleri. Bu klasör depoda yok, kendiniz temin etmeniz gerekiyor; onsuz
uygulama açılır ve oyunlarınızı listeler ama kurulum yapamaz. `npm run build:linux` için de gerekli.
Ayrıntı için `scripts/collect-payload.js`.

> Gerçek bir Steam Play oyununda denendi — dosyalarının bir kopyası üzerinde ve DLSS çalışma
> zamanının yerine bu deponun taşıyamayacağı için vekil DLL'ler konarak. Kurulum ve geri yükleme
> baştan sona koştu: kütüphane oyunu buluyor, süreç denetimi `/proc`'u okuyor, kurucu oyunun
> `nvngx_dlss.dll`'ini yedekleyip değiştiriyor, çalışma zamanını, add-on'u ve hook'u exe'nin yanına
> ekliyor, ReShade Setup oyunun kendi Proton prefix'i içinde çalışıp add-on destekli bir `dxgi.dll`
> (6.8.0) bırakıyor, geri yükleme ise on bir dosyanın tamamını bayt bayt eski hâline döndürüp
> eklediği her şeyi siliyor. Bunun gösteremediği şey, NVIDIA'nın kendi çalışma zamanının takas
> sonrası çalışıp çalışmadığı: vekiller geçerli PE dosyaları, fazlası değil. Heroic de aynı şekilde
> sınandı: okuyucu Epic oyununu buluyor, prefix'ini ve wine yapısını Heroic'in kendi ayarlarından
> çözüyor ve ReShade Setup o prefix'in içinde de çalışıyor — Heroic bu oyun için düz Wine yerine
> Proton seçtiğinden o dal da denenmiş oldu. Lutris hâlâ kurulu bir oyunla sınanmadı, OptiScaler
> rotası da RTX 50 istiyor. Yedeklerinizi saklayın.

## Emülatörler

Emülatör klasörünü ve etkin renderer'ını seçin, ardından **ReShade/Feeder** kullanın.

<table>
  <tr><th colspan="3">Emülatörler</th></tr>
  <tr><td>DuckStation</td><td>PCSX2</td><td>RPCS3</td></tr>
  <tr><td>Dolphin</td><td>PPSSPP</td><td>Xenia</td></tr>
  <tr><td>Cemu</td><td>Ryujinx</td><td>yuzu / suyu / Eden / Citron / Sudachi</td></tr>
  <tr><td>shadPS4</td><td>Azahar / Citra / Lime3DS</td><td>melonDS</td></tr>
  <tr><td>Flycast</td><td>xemu</td><td>Vita3K</td></tr>
  <tr><td>RetroArch</td><td>mGBA</td><td>Snes9x</td></tr>
  <tr><td>Play!</td><td></td><td></td></tr>
</table>

Uyumluluk renderer'a ve oyuna göre değişir. Xenia HUD düzeltmesi hâlâ deneyseldir.

## 38 dil

<table>
  <tr><th colspan="4">38 dilin tamamı</th></tr>
  <tr><td>English</td><td>العربية</td><td>简体中文</td><td>繁體中文</td></tr>
  <tr><td>Español</td><td>Português</td><td>Русский</td><td>Deutsch</td></tr>
  <tr><td>Français</td><td>日本語</td><td>한국어</td><td>Italiano</td></tr>
  <tr><td>Türkçe</td><td>Polski</td><td>Українська</td><td>Nederlands</td></tr>
  <tr><td>Čeština</td><td>Magyar</td><td>Română</td><td>Ελληνικά</td></tr>
  <tr><td>Svenska</td><td>Dansk</td><td>Norsk</td><td>Suomi</td></tr>
  <tr><td>ไทย</td><td>Tiếng Việt</td><td>Bahasa Indonesia</td><td>Bahasa Melayu</td></tr>
  <tr><td>Filipino</td><td>हिन्दी</td><td>বাংলা</td><td>فارسی</td></tr>
  <tr><td>اردو</td><td>Български</td><td>Српски</td><td>Hrvatski</td></tr>
  <tr><td>Slovenčina</td><td>Català</td><td></td><td></td></tr>
</table>

**Arapça, Farsça ve Urduca sağdan sola düzeni destekler.**

## Ekran görüntüleri

<p><img src="https://raw.githubusercontent.com/rakanki911/DLSS5-Swapper/7415065e5c5437441d0e0b0a0362d0ada6d86e15/docs/screenshots/02-games.png" alt="Oyunlar" width="100%"></p>
<p><img src="https://raw.githubusercontent.com/rakanki911/DLSS5-Swapper/7415065e5c5437441d0e0b0a0362d0ada6d86e15/docs/screenshots/03-library.png" alt="Kütüphane" width="100%"></p>
<p><img src="https://raw.githubusercontent.com/rakanki911/DLSS5-Swapper/7415065e5c5437441d0e0b0a0362d0ada6d86e15/docs/screenshots/04-game.png" alt="Oyun ayrıntıları" width="100%"></p>

## Kurmadan önce

- **Hile önleme (anti-cheat):** kırmızı uyarı ve isteğe bağlı onay verilir, toptan engelleme yapılmaz. Enjeksiyon çökmelere ya da hesap yasaklarına yol açabilir; uygulama hile önleme sistemlerini asla atlatmaz.
- **Gereksinimler:** Feeder, Visual C++ çalışma zamanlarına ihtiyaç duyar (x64, 32 bit oyunlar için ayrıca x86). Bazı bileşenler ilk kullanımda indirilir.
- **Uyumluluk garanti edilmez.** Yedek alın; mevcut modlar çakışabilir. Bildirilen her oyun çökmesi düzeltilmiş değildir.
- **Linux/Proton:** yalnızca kaynak koddan ve gerçek DLSS çalışma zamanı yerine vekil DLL'lerle denenmiş durumda — bkz. [Linux](#linux).

---

**Rakan Alkhaldi** tarafından geliştirildi · MIT · [Üçüncü taraf katkılar ve lisanslar](THIRD_PARTY_NOTICES.md)
Bu fork'ta Linux desteği · [özgün proje](https://github.com/rakanki911/DLSS5-Swapper)
