# Değişiklik Günlüğü / Changelog

## v2.0 — Nötrleştirilmiş Çekim (2026-07-04)

### Kırılan Değişiklikler (Breaking Changes)

- **Cinsiyet sistemi tamamen kaldırıldı.**  
  İsimler doğal son eklerini korur, ancak bu artık "cinsiyet" değil, sadece "isim sonu" olarak işlev görür. Sıfatlar tek formda (invariant) kullanılır.

- **Fiil çekimi sadeleştirildi.**  
  Şahıs zamiri zorunlu hale getirildi. Fiil sadece tekil (`-a`) ve çoğul (`-an`) olarak ayrılır.  
  Eski 6 şahıs çekimi (`amo, amas, amat...`) geçersizdir.

- **Ton / resmiyet ayrımı kaldırıldı.**  
  `non` ve `no` ayrımı yoktur; sadece `no` kullanılır.  
  `vos` artık "saygılı siz" anlamı taşımaz; sadece çoğul "siz"dir. Tek hitap her zaman `tu`dur.

### Yeni Özellikler

- **Düzenli zaman ekleri:**  
  - Şimdiki: `-a` / `-an`  
  - Geçmiş: `-ava` / `-avan`  
  - Gelecek: `-ara` / `-aran`

- **Tekdüze çoğul yapımı:**  
  - `-a` → `-as`  
  - `-o, -u` → `-os`  
  - Ünsüz → `-es`

- **Çekimsiz sıfatlar:**  
  `bonus`, `magnus`, `bellus` gibi sıfatlar tek formda kullanılır.

### Eski Sürümler

- **v1.0 — Klasik Hibrit:** Orijinal Latinol referans kitapçığı. Eril/dişil cinsiyet, 6 şahıs fiil çekimi, `non/no` ton ayrımı içeriyordu.

---

**Sonraki sürüm hedefleri:**  
- Karşılaştırma dereceleri (`-ior`, `-issimus` veya alternatif)  
- Edat kısaltması (11 → 5 temel)  
- Sayı sistemi revizyonu
