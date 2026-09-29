# UAT Scenarios

Bu projede kullanıcıların başvuru sürecinde gerçekleştireceği temel işlemleri UAT senaryoları olarak belirledim.

| UAT ID | Senaryo                                         | Beklenen Sonuç                                            |
| ------ | ----------------------------------------------- | --------------------------------------------------------- |
| UAT-01 | Kullanıcı geçerli bilgilerle başvuru oluşturur  | Başvuru başarıyla oluşturulur                             |
| UAT-02 | Kullanıcı zorunlu alanlardan birini boş bırakır | Sistem uyarı gösterir ve başvuru oluşturulmaz             |
| UAT-03 | Kullanıcı oluşturduğu başvuruyu görüntüler      | Başvuru bilgileri doğru şekilde görüntülenir              |
| UAT-04 | Kullanıcı başvuru durumunu kontrol eder         | Güncel başvuru durumu görüntülenir                        |
| UAT-05 | Yetkili kullanıcı başvuruyu onaylar             | Başvuru durumu "Onaylandı" olarak güncellenir             |
| UAT-06 | Yetkili kullanıcı başvuruyu reddeder            | Başvuru durumu "Reddedildi" olur ve red nedeni kaydedilir |

## UAT Sonucu

Belirlediğim senaryolarla başvuru sürecinin kullanıcı açısından beklenen şekilde çalışıp çalışmadığını kontrol ettim.
