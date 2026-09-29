# Test Scenarios

## Test Senaryoları

| Test ID | Gereksinim | Senaryo                                         | Beklenen Sonuç                     |
| ------- | ---------- | ----------------------------------------------- | ---------------------------------- |
| TS-01   | FR-01      | Geçerli bilgilerle başvuru formunu doldurma     | Form doldurulabilmeli              |
| TS-02   | FR-02      | Zorunlu alanları boş bırakarak başvuru gönderme | Sistem uyarı göstermeli            |
| TS-03   | FR-03      | Geçerli bilgilerle başvuru oluşturma            | Başvuru oluşturulmalı              |
| TS-04   | FR-04      | Oluşturulan başvuruyu görüntüleme               | Başvuru bilgileri gösterilmeli     |
| TS-05   | FR-05      | Başvuru durumunu güncelleme                     | Yeni durum kaydedilmeli            |
| TS-06   | FR-06      | Başvuruyu onaylama                              | Başvuru Onaylandı durumuna geçmeli |
| TS-07   | BR-05      | Başvuruyu reddetme                              | Red nedeni kaydedilmeli            |
| TS-08   | BR-01      | Eksik bilgiyle başvuru oluşturma                | Başvuru oluşturulmamalı            |

## Test Türleri

### Positive Test

Geçerli bilgilerle sistemin beklenen şekilde çalıştığını kontrol ettim.

### Negative Test

Eksik veya hatalı bilgilerle sistemin doğru şekilde hata vermesini kontrol ettim.

## Test Akışı

```text
Requirement
     ↓
Test Scenario
     ↓
Test Case
     ↓
Expected Result
```

Bu yapı sayesinde gereksinimleri doğrudan testlerle ilişkilendirdim.
