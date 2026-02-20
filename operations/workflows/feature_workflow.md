# Feature Development Workflow

Yeni bir özellik (feature) istendiğinde izlenecek resmi adımlar:

1. **Gereksinim Analizi (@TeamLead)**
   - Kullanıcı isteği analiz edilir ve `context/requirements.md` güncellenir.
   - Task operasyon merkezindeki panoya (Task Board) eklenir.

2. **Tasarım Fazı (@Designer)**
   - @TeamLead işi @Designer ajana paslar (Handoff Protocol).
   - Mockup/UI şeması hazırlanır. İlgili markdown dosyasında arayüz standartları belgelenir.
   - Çıktı Takım Lideri tarafından onaylanır.

3. **Backend ve Altyapı (@Backend)** *(Opsiyonel; eş zamanlı veya önce başlayabilir)*
   - Gerekli veritabanı şeması ve API router uç noktaları planlanır/yazılır.
   - API dökümantasyonu Frontend'in okuyacağı şekilde sunulur.

4. **Frontend Entegrasyonu (@Frontend)**
   - Designer'ın UI mockupları ile Backend'in API verileri entegre edilir.
   - Modern ve temiz kodla arayüz canlandırılır.

5. **Review ve Test (Quality Gates)**
   - Her modül bitiminde @TeamLead (Code Review) kontrol yapar (`operations/quality/quality_gates.md` check-list ile).

6. **Tamamlanma ve Kayıt**
   - Hata yoksa (Done), `task_board.md` güncellenir ve işlem `context/log.md` sayfasına kaydedilir.
