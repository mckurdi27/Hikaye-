# 📖 Her güne 1 hikaye

# 16 Dilli Günlük hikayeler

# Bu 16 dil ve sıralaması değişmez ama herzaman ingilzce ilk seçili dil ikinci sırada gösterilir 
Bunu  ve days.json dosyasını ana şablon olarak kullan

# Sistem
- Her gün 1 yeni hikaye
- Sırasıyla 
  Kelimeler 
  Kelime alıştırmaları 
  Hikaye
  Hikaye alıştırmaları 
- 16 dil ve sıralaması değişmez 
- İngilizce ilk seçili dil ikinci sırada gösterilir 
- Hikaye ve içerikler ayrı JSON dosyalarında tutulur

# Günlük Dosyalar
Her günün içeriği:`data/day-XX.json`şeklinde eklenir.
Örneğin:
`data/story-0101.json` → 1.Kitap 1. Hikaye – Alıştırmaları - Kelimeleri 
`data/story-0102.json` → 1.Kitap 2. Hikaye – Alıştırmaları - Kelimeleri 
`data/story-0103.json` → 1.Kitap 3. Hikaye – Alıştırmaları - Kelimeleri 
.....
`data/story-0630.json` → 6.Kitap 30. Hikaye – Alıştırmaları - Kelimeleri 


Her günlük JSON dosyası pdf klasöründeki 6 pdf kitap esas alınarak

- `"dayTitle"`
- `"daySubtitle"`
- `"words"`
- `"questions"`
- `"story"`
- `"questions"`

bilgileri bulunur.

# 📊 Proje Özeti

| Özellik | Değer |
|---|---|
| Toplam Kitap | 6 |
| Toplam Hikaye | 6×30 |
| Dil sayısı | 16 |
---
# 📁 Dosya Yapısı

```16 Dilli Günlük hikayeler

/
│
├── index.html
├── app.js
├── style.css
├── README.md
├── stories.json
└── Images/
    ├── A.jpg
    ├── B.jpg
    ├── C.jpg
└── data/
    ├── story-0101.json
    ├── story-0102.json
    ├── story-0103.json
    ├── story-0104.json
    ├── ...
    └── story-0630.json

---
# 📅  16 Dilli Günlük hikayeler

## 1. Kitap — 30 hikaye
** Her hikayede 20 önemli kelime
** 20 önemli kelime alıştırmaları 
** Her hikaye ile ilgili alıştırmalar
---

## 2. Kitap — 30 hikaye
** Her hikayede 20 önemli kelime
** 20 önemli kelime alıştırmaları 
** Her hikaye ile ilgili alıştırmalar 
---
## 3. Kitap — 30 hikaye
** Her hikayede 20 önemli kelime
** 20 önemli kelime alıştırmaları 
** Her hikaye ile ilgili alıştırmalar
---
## 4. Kitap — 30 hikaye
** Her hikayede 20 önemli kelime
** 20 önemli kelime alıştırmaları 
** Her hikaye ile ilgili alıştırmalar
---
## 5. Kitap — 30 hikaye
** Her hikayede 20 önemli kelime
** 20 önemli kelime alıştırmaları 
** Her hikaye ile ilgili alıştırmalar
---
## 6. Kitap — 30 hikaye
** Her hikayede 20 önemli kelime
** 20 önemli kelime alıştırmaları 
** Her hikaye ile ilgili alıştırmalar
---


  
