# Mezuniyet Tezi – Karadeniz Teknik Üniversitesi

Bu arşiv, **Karadeniz Teknik Üniversitesi'ndeki (KTÜ)** mezuniyet tezimizin LaTeX kaynak dosyalarını içermektedir. Tez, projemizin tasarımını, teorik altyapısını, simülasyonunu ve deneysel sonuçlarını kapsayan üç öğrenci tarafından ortaklaşa hazırlanmıştır.

---

## 📄 Projeye Genel Bakış

Tez dokümanı, profesyonel bir formatta **LaTeX** kullanılarak yapılandırılmış ve derlenmiştir:

- Özel başlık sayfası ve kapak.
- İçindekiler tablosu, şekil listesi ve tablo listesi.
- Giriş, Teori, Tasarım, Simülasyon, Deney, Sonuçlar ve Tartışma gibi bölümler.
- Ekler ve Özgeçmiş bölümü.
- `biblatex` ve `biber` kullanılarak kaynakça yönetimi.

Şekiller, tablolar, denklemler ve kısaltmalar için dikkatli bir biçimlendirmeyle **Türkçe** olarak yazılmıştır.

---

## 🛠️ Özellikler

- **Yüksek kaliteli biçimlendirme**: Uygun aralıklar, bölüm ve alt bölüm başlıkları ve özel şekil/tablo alt yazıları.
- **Bibliyografya yönetimi**: URL'ler ve kitap başlıkları için özel biçimlendirmeyle `biblatex` ve `biber` kullanımı.
- **Diyagramlar**: TikZ diyagramlarını ve DNN çizimlerini destekler.
- **Sözlük ve Kısaltmalar**: Otomatik sembol ve kısaltma listesi.
- **Matematiksel destek**: Denklemler ve referanslar için tam destek.
- **Özel sayfa düzeni**: A4 kağıt, bir buçuk aralık ve belirlenmiş kenar boşlukları.

---

## 📁 Depo Yapısı

```metin
├── Başlıklar/ # Ana bölümler (Giriş, Teori, Tasarım vb.)
├── Ekstra/ # Ek kaynaklar (kapak sayfası, kısaltmalar, çizim dosyaları)
├── medya/ # Tezde kullanılan şekil ve görseller
├── ref.bib # Kaynakça dosyası
├── main.tex # Ana LaTeX dosyası
└── README.md # Proje açıklaması ve talimatları
````

---

## 📌 LaTeX Derlemesi

Tez PDF'sini derlemek için:

1. Bir LaTeX dağıtımının yüklü olduğundan emin olun (örneğin, **TeX Live** veya **MiKTeX**). 2. LaTeX editörünüzde (örneğin, **TeXstudio**, **Overleaf**) `main.tex` dosyasını açın.

3. Kaynakça için `xelatex` veya `pdflatex` ve `biber` ile derleyin.

```bash
xelatex main.tex
biber main
xelatex main.tex
xelatex main.tex
```
4. Nihai PDF dosyası tüm bölümleri, şekilleri, tabloları ve referansları içerecektir.

---

## 👥 Katkıda Bulunanlar

Bu tez aşağıdaki kişiler tarafından ortaklaşa tamamlanmıştır:

* Engin Kaya
* Taha Ramazan Uysal
* İdrishan Kanberi

---

## 📚 Referanslar

Tüm referanslar `ref.bib` dosyasında saklanır ve tezde otomatik olarak `biblatex` ve `biber` kullanılarak biçimlendirilir.

---

## ⚠️ Notlar

* Tüm şekillerin `media/` klasörüne yerleştirildiğinden emin olun.
* Kısaltmalar `Ekstra/acronyms.tex` dosyasında tanımlanır ve otomatik olarak eklenir.
* TikZ diyagramları `Ekstra/drawDNN.tex` dosyasında tanımlanır.

---

## 🎓 Lisans

Bu proje akademik amaçlıdır.

---

*Bu depo, KTÜ mezuniyet tezimizin resmi LaTeX kaynağını içerir.*
