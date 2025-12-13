# python-kodlari-ile-genetik-algoritma-lojistik-ta-ma-i-in-optimazsyon-
bu ödev okulumda aldığım  "BLG 307 Yapay Zeka Sistemleri " için hazırlanmıştır 
----------------------------cemil can öz----------------------------------------------
# Lojistik Rota Optimizasyonu - Genetik Algoritma

Bu proje, bir lojistik firmasının yakıt tüketimini ve süreyi optimize etmek için **genetik algoritma** kullanır.

---

## Proje Açıklaması
- **Amaç**: Rota seçimi sırasında yakıt tüketimini ve süreyi minimize etmek.
- **Değişkenler**:
  - `x1`: Ortalama hız (40 ≤ x1 ≤ 100 km/h)
  - `x2`: Araç yük kapasitesi (2 ≤ x2 ≤ 10 ton)
- **Amaç Fonksiyonu**: `y = -2x1 - 3x2 + 0.1x1x2`
- **Kısıtlar**:
  - `x1 * x2 ≤ 700` (Motor gücü limiti)
  - `x1 ≥ 60` (Minimum hız şartı)

---

## Nasıl Çalıştırılır?
1. Depoyu klonlayın:
   ```bash
   git clone [depo-linkiniz]

   python genetik_algoritma.py


En iyi çözüm, kodun çıktısında görüntülenecektir
|||
VVV

En iyi çözüm: x1 = [değer], x2 = [değer], Uygunluk = [değer]


Katkıda Bulunanlar
|||
VVV
Cemil Can Öz :2312729013 
cemilcanoz15@gmail.com


