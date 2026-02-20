# Code Review Workflow

Tüm geliştirilen kod parçaları, ana dallara birleşmeden (merge) önce mutlaka kontrol edilmelidir. 
Bu incelemeyi **Team Lead** veya rol verilirse diğer ajanlar yapar.

## İnceleme Adımları

1. **Ön Değerlendirme:** Kod standartlara ve belirlenen (`rules.md` veya `.cursorrules`) tasarıma uygun mu?
2. **Güvenlik (Security):** Beklenmedik giriş/çıkış açıkları veya token sızıntısı var mı?
3. **Performans (Performance):** Arayüz yükleme süreleri (Lighthouse / Core Web Vitals eşdeğeri mantık) makul mü? Veritabanı sorguları (N+1 problemi) optimize edilmiş mi?
4. **Erişilebilirlik (Accessibility):** Renk kontrastları, semantik HTML etiketleri (aria-label, roll) test edildi mi?

## Onay (Approve & Merge)
Sadece tüm sorulara "Evet" yanıtı alınınca, veya minor hatalar için not düşülerek (Comment) onay verilir. Aksi halde kod Reddedilir (Changes Requested) ve ilgili ajan tarafından düzeltilir.
