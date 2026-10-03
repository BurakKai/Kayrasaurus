# Kayrasaurus changliensis

Eylül 2026'da tanımlanan therizinosaur *Kayrasaurus changliensis* için, döndürülebilir 3B modelli tek sayfalık bilgilendirme sitesi.

![Lisans: MIT](https://img.shields.io/badge/lisans-MIT-green) ![Three.js r128](https://img.shields.io/badge/three.js-r128-black)

## Özellikler

- **Etkileşimli 3B model.** Three.js ile tamamen kodla kurulmuş bir canlandırma. Sürükleyerek ya da ok tuşlarıyla döndürülür, yakınlaştırılır.
- **Anatomi noktaları.** Kafatası, dişler, boyun, el pençeleri, tüyler ve gövde. Bir noktaya ya da karta tıklayınca kamera o bölgeye döner.
- **Görünüm seçenekleri.** Tüyler açılıp kapatılabilir, ölçek için 1,75 m boyunda bir insan figürü eklenebilir.
- **Bilgi bölümleri.** Künye, adın kökeni, Jehol Biyotası'ndaki akrabaları, haberlerde karışan bilgiler ve kaynaklar.
- **Duyarlı tasarım.** Telefon ve masaüstünde çalışır; açık ve koyu temayı destekler.

## Çalıştırma

Kurulum ve derleme adımı yoktur. Depoyu indirip `index.html` dosyasını tarayıcıda açmak yeterlidir.

```bash
git clone https://github.com/BurakKai/Kayrasaurus.git
cd Kayrasaurus
# index.html dosyasını tarayıcıda açın
```

Three.js ve yazı tipleri CDN üzerinden yüklendiği için internet bağlantısı gerekir.

## Proje yapısı

| Dosya | Açıklama |
| --- | --- |
| `index.html` | Sitenin tamamı: içerik, stil ve 3B model kodu |
| `README.md` | Bu belge |
| `LICENSE` | MIT lisansı |
| `.gitignore` | Depoya girmemesi gereken dosyalar |

## Teknolojiler

- HTML, CSS ve saf JavaScript
- [Three.js r128](https://threejs.org/) (WebGL)
- Google Fonts: Bricolage Grotesque, Newsreader, IBM Plex Mono

## Model hakkında

Model fosilin taraması değildir. Yayımlanan 3,6 m uzunluğa ve therizinosaur vücut planına göre kurulmuş temsili bir canlandırmadır. Tüy rengi ve yüz ayrıntıları tahminidir; bacaklar yakın akrabalara göre tamamlanmıştır.

## Kaynaklar

- Liao C.-C., Freimuth W. J., Zanno L. E., Xu X. (2026). A new therizinosaur from the Early Cretaceous Jehol Biota and ecomorphological patterns among early therizinosaurians. *Journal of Systematic Palaeontology* 24(2): 2710287. [doi:10.1080/14772019.2026.2710287](https://doi.org/10.1080/14772019.2026.2710287)
- [Sci.News, 21 Eylül 2026](https://www.sci.news/paleontology/kayrasaurus-changliensis-15082.html)
- [Greek Reporter, 23 Eylül 2026](https://greekreporter.com/2026/09/23/new-dinosaur-species-teeth-china/)
- [Popular Science](https://www.popsci.com/?p=786289)

## Lisans

Kod [MIT Lisansı](LICENSE) ile sunulmaktadır. Sitedeki bilimsel bilgiler yukarıdaki kaynaklara aittir.
