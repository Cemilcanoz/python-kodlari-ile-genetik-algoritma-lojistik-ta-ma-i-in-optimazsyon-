# python-kodlari-ile-genetik-algoritma-lojistik-ta-ma-i-in-optimazsyon-
bu ödev okulumda aldığım  "BLG 307 Yapay Zeka Sistemleri " için hazırlanmıştır 
|-cemil can öz-|
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
    <img width="881" height="468" alt="image" src="https://github.com/user-attachments/assets/9705f0e0-8db9-4dfc-b5bb-8bc6bdb96862" />


-### Adımlar:
1. **Problemin Tanımlanması**:
   - Ortalama hız (`x1`) ve araç yük kapasitesi (`x2`) değişkenleri belirlendi.
   - Amaç fonksiyonu (`y = -2x1 - 3x2 + 0.1x1x2`) ve kısıtlar (`x1 * x2 ≤ 700`, `x1 ≥ 60`) tanımlandı.

2. **Genetik Algoritmanın Uygulanması**:
   - **Popülasyon oluşturma**: Rastgele bireylerden oluşan bir popülasyon oluşturuldu.
   - **Uygunluk fonksiyonu**: Her bireyin uygunluk değeri, amaç fonksiyonuna ve kısıtlara göre hesaplandı.
   - **Seçim**: **Rulet tekerleği seçimi** kullanılarak, en iyi bireylerin seçilme olasılığı artırıldı.
   - **Çaprazlama**: Seçilen bireylerden yeni çözümler üretilmesi için çaprazlama yapıldı.
   - **Mutasyon**: Popülasyonda çeşitliliği korumak için rastgele mutasyonlar uygulandı.
   - **Yeni nesil oluşturma**: Seçim, çaprazlama ve mutasyon adımlarıyla yeni nesiller üretilerek en iyi çözüme ulaşılması hedeflendi.

3. **Sonuçların Elde Edilmesi**:
   - En iyi `x1` (ortalama hız) ve `x2` (yük kapasitesi) değerleri, genetik algoritma tarafından belirlendi.
   - Elde edilen sonuçlar, yakıt tüketimini ve süreyi optimize eden en iyi çözümü temsil ediyor.

4. **GitHub’a Yüklenmesi**:
   - Proje kodu ve dokümantasyonu GitHub’a yüklendi.
   - `ReadMe.md` dosyası ile proje açıklamaları, nasıl çalıştırılacağı ve sonuçlar paylaşıldı.

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


