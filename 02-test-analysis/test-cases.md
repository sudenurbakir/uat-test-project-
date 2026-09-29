# Test Cases

Bu projede belirlediğim test senaryolarını test case'lere dönüştürdüm. Her test case için ön koşul, adımlar ve beklenen sonucu belirledim.

## Test Case Listesi

| Test ID | Senaryo                    | Ön Koşul                         | Test Adımları                                | Beklenen Sonuç                                            |
| ------- | -------------------------- | -------------------------------- | -------------------------------------------- | --------------------------------------------------------- |
| TC-01   | Geçerli başvuru oluşturma  | Başvuru formu açık               | Gerekli alanları doldurup formu gönder       | Başvuru oluşturulur ve başvuru numarası oluşur            |
| TC-02   | Eksik zorunlu alan         | Başvuru formu açık               | Zorunlu alanlardan birini boş bırakıp gönder | Uyarı gösterilir ve başvuru oluşturulmaz                  |
| TC-03   | Başvuru görüntüleme        | Oluşturulmuş başvuru mevcut      | Başvuru numarası ile başvuruyu aç            | Başvuru bilgileri görüntülenir                            |
| TC-04   | Başvuru durumu güncelleme  | Başvuru mevcut                   | Başvuru durumunu değiştir                    | Yeni durum kaydedilir                                     |
| TC-05   | Başvuru onaylama           | Başvuru değerlendirme aşamasında | Başvuruyu onayla                             | Başvuru durumu "Onaylandı" olur                           |
| TC-06   | Başvuru reddetme           | Başvuru değerlendirme aşamasında | Başvuruyu reddet ve neden belirt             | Başvuru durumu "Reddedildi" olur ve red nedeni kaydedilir |
| TC-07   | Geçersiz bilgi ile başvuru | Başvuru formu açık               | Geçersiz bilgi girip gönder                  | Sistem başvuruyu kabul etmez ve uyarı gösterir            |

## Test Sonucu

Test case'lerde beklenen sonuçları gereksinimlerle karşılaştırarak kontrol ettim. Başvuru oluşturma, durum güncelleme ve onay/red süreçlerinin doğru çalışmasını temel aldım.
