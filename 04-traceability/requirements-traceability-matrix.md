# Requirements Traceability Matrix

Bu projede gereksinimlerin test ve UAT süreçlerinde karşılığının bulunup bulunmadığını kontrol etmek için bir gereksinim izlenebilirlik matrisi hazırladım.

| Requirement ID | Requirement                                   | Test Case    | UAT            | Status  |
| -------------- | --------------------------------------------- | ------------ | -------------- | ------- |
| FR-01          | Başvuru formu doldurulabilmeli                | TC-01        | UAT-01         | Covered |
| FR-02          | Zorunlu alanlar kontrol edilmeli              | TC-02        | UAT-02         | Covered |
| FR-03          | Geçerli bilgilerle başvuru oluşturulmalı      | TC-01        | UAT-01         | Covered |
| FR-04          | Başvuru görüntülenebilmeli                    | TC-03        | UAT-03         | Covered |
| FR-05          | Başvuru durumu güncellenebilmeli              | TC-04        | UAT-04         | Covered |
| FR-06          | Başvuru onaylanabilmeli veya reddedilebilmeli | TC-05, TC-06 | UAT-05, UAT-06 | Covered |
| BR-01          | Eksik bilgilerle başvuru oluşturulmamalı      | TC-02        | UAT-02         | Covered |
| BR-05          | Red nedeni kaydedilmeli                       | TC-06        | UAT-06         | Covered |

## Sonuç

Tüm gereksinimlerin en az bir test case ve UAT senaryosu ile eşleştirildiğini kontrol ettim. Böylece gereksinimlerin test sürecinde izlenebilir olmasını sağladım.
