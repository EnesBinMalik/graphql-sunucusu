<div align="center">

<img src="docs/01-kapak.png" alt="GraphQL Sunucusu — Enes Öztürk imzalı proje" width="100%">

# GraphQL Sunucusu

**Ödev 1 — şema, çözümleyiciler, 11 doğrulama adımı ve etkileşimli playground içeren GraphQL backend çalışması.**

[![GraphQL](https://img.shields.io/badge/GraphQL-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-sunucusu)
[![Express](https://img.shields.io/badge/Express-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-sunucusu)
[![TypeScript](https://img.shields.io/badge/TypeScript-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-sunucusu)
[![Backend](https://img.shields.io/badge/Backend-58BDF8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik/graphql-sunucusu)
[![Doğrulama](https://img.shields.io/badge/Do%C4%9Frulama-lint%20%2B%20build%20ge%C3%A7ti-2EA043?style=for-the-badge)](https://github.com/EnesBinMalik/graphql-sunucusu)
[![Enes Öztürk](https://img.shields.io/badge/Enes%20%C3%96zt%C3%BCrk-imzal%C4%B1-EA4338?style=for-the-badge&logo=badge&logoColor=white)](https://github.com/EnesBinMalik)

<img src="docs/rozet-enes-ozturk.png" alt="Enes Öztürk imzalı tasarım rozeti" width="420">

</div>

---

## Hakkında

GraphQL Sunucusu, Patika.dev'in ilk GraphQL ödevidir. Kullanıcılar, etkinlikler, konumlar ve katılımcılar arasındaki ilişkileri sorgulayan bir şema kurulur; doğrulama robotu 11 ayrı kriteri adım adım kontrol eder. Playground gerçek sorguları çalıştırır, sonuçları ve cURL çıktısını gösterir.

> Bu proje **Enes Öztürk** tarafından tasarlanmış, geliştirilmiş ve imzalanmıştır.

---

## Öne çıkan özellikler

| Özellik | Açıklama |
| --- | --- |
| **11 doğrulama** | Ödev gereksinimlerini tek tek denetleyen robot. |
| **Playground & IDE** | Sorgu yazma, çalıştırma ve sonuç görüntüleme. |
| **Ödev ana sorgusu** | İlişkisel `events` sorgusu için hazır şablon. |
| **Türkçe sözdizimi** | Türkçe alan adlarıyla alternatif sorgu. |
| **Derin ilişki** | 3 seviyeli çözümleyici zinciri. |
| **Mutation** | Yeni etkinlik oluşturma sorgusu. |

---

## Doğrulama

| Ölçü | Değer |
| --- | --- |
| Kriter | 11 |
| Tip | 5 |
| Sorgu | 9 hazır |
| Uç | /graphql |

---

## Galeri

<img src="docs/02-ekran.png" alt="GraphQL Sunucusu ana ekran" width="100%">

<img src="docs/03-ekran.png" alt="GraphQL Sunucusu etkileşimli görünüm" width="100%">

<img src="docs/04-ekran.png" alt="GraphQL Sunucusu detay görünümü" width="100%">

---

## Kurulum

**Gereksinim:** Node.js 20+

```bash
git clone https://github.com/EnesBinMalik/graphql-sunucusu.git
cd graphql-sunucusu
npm install
npm run start
```

> Doğrulama robotu hem şemayı hem dönüş verisini kontrol eder.

Diğer komutlar:

```bash
npm run build     # Üretim derlemesi
npm run preview   # Derlemeyi önizle
npm run lint      # TypeScript tip kontrolü
```

---

## Teknik mimari

```text
src/graphql/schema.ts      Şema tanımı
src/graphql/presets.ts     Hazır sorgular
src/graphql/data.json      Veri kümesi
src/components/Playground.tsx  Sorgu editörü
src/components/HomeworkVerifier.tsx  Doğrulama robotu
server.ts                  Express sunucusu
```

---

## İmza

<div align="center">

[![Geliştirici](https://img.shields.io/badge/Geli%C5%9Ftirici-Enes%20%C3%96zt%C3%BCrk-EA4338?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnesBinMalik)
[![İmza](https://img.shields.io/badge/%C4%B0mza-Enes%20%C3%96zt%C3%BCrk-FFD700?style=for-the-badge&logo=verified&logoColor=white)](https://github.com/EnesBinMalik)

**Bu kod, tasarım ve deneyim Enes Öztürk'ün kişisel imzasını taşır.**

© 2026 Enes Öztürk — Tüm hakları saklıdır.

</div>
