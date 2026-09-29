# Test Data

Bu projede test case'lerde kullanmak için örnek test verileri oluşturdum. Gerçek kişi veya kişisel bilgi kullanmadan anonim test verileri belirledim.

## Geçerli Test Verileri

| Alan         | Test Verisi                                           |
| ------------ | ----------------------------------------------------- |
| Ad Soyad     | Test Kullanıcısı                                      |
| E-posta      | [test.user@test.com] |
| Telefon      | 05000000000                                           |
| Başvuru Türü | Bireysel                                              |

## Geçersiz Test Verileri

| Alan         | Test Verisi | Beklenen Sonuç           |
| ------------ | ----------- | ------------------------ |
| Ad Soyad     | Boş         | Uyarı gösterilmeli       |
| E-posta      | test.user   | Geçersiz e-posta uyarısı |
| Telefon      | 123         | Geçersiz telefon uyarısı |
| Başvuru Türü | Boş         | Uyarı gösterilmeli       |

## Test Verisi Kullanımı

Geçerli verilerle başvurunun oluşturulmasını, geçersiz verilerle ise sistemin doğru uyarıları vermesini kontrol ettim.
