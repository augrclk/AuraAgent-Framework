# Handoff Protocol

Ajanlar arası görev devretme (handoff) sürecindeki kuralları tanımlar.

## Kurallar

1. **Bağlamı (Context) Aktar:** Bir ajan diğerine iş devrederken mutlaka detaylı bilgi vermelidir.
   - *Örnek (TeamLead to Designer):* "Kullanıcının kayıt olması için bir modal sayfasına ihtiyaç var. Referans mock veya metinler `context/requirements.md` içerisinde yer alıyor."
   - *Örnek (Designer to Frontend):* "Kayıt modal'ının tasarımı ve Figma benzeri şeması hazırlandı. Tema renkleri: `#1E1E1E` arkaplan, `#0AFF00` ana buton rengi."
2. **Son Tarih ve Beklenti:** Hangi dosyanın nerede oluşturulması/değiştirilmesi gerektiği net şekilde belirtilir.
3. **Etiketleme (Tagging):** Ajanı göreve çağırırken `@AgentRole` formatı kullanılır ki model yönlendirmeyi algılasın.
