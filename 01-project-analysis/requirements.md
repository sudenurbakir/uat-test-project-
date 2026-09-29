# Requirements

## Functional Requirements

| ID    | Requirement                                            |
| ----- | ------------------------------------------------------ |
| FR-01 | Kullanıcı başvuru formunu doldurabilmelidir.           |
| FR-02 | Zorunlu alanlar kontrol edilmelidir.                   |
| FR-03 | Geçerli bilgilerle başvuru oluşturulabilmelidir.       |
| FR-04 | Kullanıcı oluşturduğu başvuruyu görüntüleyebilmelidir. |
| FR-05 | Başvuru durumu güncellenebilmelidir.                   |
| FR-06 | Başvuru onaylanabilmeli veya reddedilebilmelidir.      |

## Business Rules

| ID    | Rule                                                        |
| ----- | ----------------------------------------------------------- |
| BR-01 | Zorunlu alanlar boş bırakılırsa başvuru oluşturulmamalıdır. |
| BR-02 | Geçersiz bilgiler içeren başvurular kabul edilmemelidir.    |
| BR-03 | Her başvurunun benzersiz bir başvuru numarası olmalıdır.    |
| BR-04 | Onaylanan başvuru tekrar değerlendirmeye alınmamalıdır.     |
| BR-05 | Reddedilen başvurunun red nedeni kaydedilmelidir.           |

## Öncelik

**High:** FR-01, FR-02, FR-03, FR-06
**Medium:** FR-04, FR-05
