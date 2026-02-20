# Quality Gates (Kalite Kapıları)

Projenin farklı aşamalarında ürünün geçmesi gereken kalite standartlarıdır. İşi teslim eden ajan ve onu test eden ajan/lider kontrol etmelidir.

## 1. Tasarım Kalite Kapısı (Design Gate)
- Kullanıcı arabirimi açık ve sezgisel mi?
- Responsive (mobil/desktop) durumlar düşünüldü mü?
- Tipografi hiyerarşisi doğru kuruldu mu?

## 2. Frontend Kalite Kapısı (Frontend Gate)
- Tasarıma birebir sadık kalındı mı (Pixel-perfect yaklaşımı denendi mi)?
- Componentler tekrar kullanılabilir (reusable) şekilde modüler parçalandı mı?
- React/Next/Vue framework warningleri (uyarıları) ve console hataları sıfır mı?

## 3. Backend Kalite Kapısı (Backend Gate)
- Girdi doğrulama (input validation) ve sanitize işlemleri tamamlandı mı?
- Başarısız durumlarda anlamlı ve standart hata mesajları dönülüyor mu?
- Veritabanı sorguları index kullanımına uygun yazıldı mı?

## 4. Yayınlama Öncesi (Release Gate)
- Tüm uçtan uca senaryolar hatasız çalıştı mı?
- Konsolda (gerek debug gerek production) hata yok mu?
- Kullanıcıya ait `.env` veya token yapıları Github'a (veya loglara) pushlanmaktan korundu mu?
