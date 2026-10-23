## Summary / Özet
<!-- What does this PR change and why? Link the issue if there is one: Closes #123
     Bu PR neyi, neden değiştiriyor? Varsa issue bağlantısı: Closes #123 -->

## Change category / Değişiklik kategorisi
<!-- Pick one. / Birini seçin. -->
- [ ] Low: typo, copy, static content / Düşük: yazım hatası, metin, statik içerik
- [ ] Normal: feature, UI change, performance / Normal: özellik, arayüz değişikliği, performans
- [ ] Data-affecting: data model, new API endpoint, permission changes / Veri etkili: veri modeli, yeni API endpoint'i, yetki değişiklikleri
- [ ] Security-critical: authentication, payments, charge point communication, cryptography / Güvenlik kritik: kimlik doğrulama, ödeme, şarj istasyonu haberleşmesi, kriptografi
- [ ] Emergency fix: `hotfix/*` into the default branch (back-merge to `dev` required) / Acil düzeltme: `hotfix/*` ile varsayılan branch'e (sonrasında `dev`'e geri alınmalı)

## Testing / Test
<!-- How was this verified, and where (local / dev)?
     Nasıl ve nerede (yerel / dev) doğrulandı? -->

## Exceptions / İstisnalar
<!-- Any checklist item below that this PR does not meet, and any security check exception added
     (`nosemgrep`, `.gitleaksignore`, `osv-scanner.toml`), with the reason. Write "None" if there are none.
     Aşağıdaki kontrol listesinden bu PR'ın karşılamadığı maddeler ve eklenen güvenlik kontrolü istisnaları
     (`nosemgrep`, `.gitleaksignore`, `osv-scanner.toml`), gerekçeleriyle. Yoksa "Yok" yazın. -->

## Security checklist
By submitting this PR, the author confirms the following for this change (items that do not apply can be ignored):

- Security requirements are defined (authentication, authorization, data classification). (A.8.26)
- No secrets in code or configuration (API keys, passwords, tokens, private keys). (A.8.4, A.5.17)
- Database queries use parameters or the ORM; no SQL built from strings. (A.8.28)
- New or changed endpoints check both authentication and authorization, including object-level access. (A.8.3, A.8.5)
- No personal or sensitive data is written to logs. (A.8.15, A.8.12)
- Error responses do not expose stack traces, internal details or data. (A.8.28)
- New dependencies: license reviewed and no known vulnerabilities. (A.8.8, A.8.30)
- No prohibited cryptography (MD5, SHA-1, DES); tokens are not generated with non-cryptographic random. (A.8.24)
- No real user data is used in tests or test environments. (A.8.33, A.8.11)
- Mobile changes were assessed for mobile app security (MAST). (A.8.29)
- Architectural changes include a security impact assessment. (A.8.27)
- New personal data processing meets KVKK requirements (purpose, retention, consent). (A.5.34)

## Güvenlik kontrol listesi
Bu PR'ı gönderen kişi, bu değişiklik için aşağıdakileri onaylar (uygulanmayan maddeler dikkate alınmayabilir):

- Güvenlik gereksinimleri tanımlıdır (kimlik doğrulama, yetkilendirme, veri sınıflandırması). (A.8.26)
- Kodda veya yapılandırmada sır yoktur (API anahtarı, şifre, token, özel anahtar). (A.8.4, A.5.17)
- Veritabanı sorguları parametre veya ORM kullanır; metin birleştirerek oluşturulmuş SQL yoktur. (A.8.28)
- Yeni veya değişen her endpoint, nesne düzeyinde erişim dahil, hem kimlik doğrulama hem yetkilendirme kontrolü yapar. (A.8.3, A.8.5)
- Log kayıtlarına kişisel veya hassas veri yazılmaz. (A.8.15, A.8.12)
- Hata yanıtları stack trace, iç sistem bilgisi veya veri sızdırmaz. (A.8.28)
- Yeni bağımlılıkların lisansı incelenmiştir ve bilinen güvenlik açığı yoktur. (A.8.8, A.8.30)
- Yasaklı kriptografi (MD5, SHA-1, DES) kullanılmaz; token'lar kriptografik olmayan rastgele üreteçlerle oluşturulmaz. (A.8.24)
- Testlerde veya test ortamlarında gerçek kullanıcı verisi kullanılmaz. (A.8.33, A.8.11)
- Mobil değişiklikler mobil uygulama güvenliği (MAST) açısından değerlendirilmiştir. (A.8.29)
- Mimari değişiklikler için güvenlik etkisi değerlendirmesi yapılmıştır. (A.8.27)
- Yeni işlenen kişisel veriler KVKK gereksinimlerini (amaç, saklama süresi, rıza) karşılar. (A.5.34)

---

- [ ] I confirm this PR meets the security checklist, except for the items listed under "Exceptions". / Bu PR'ın, "İstisnalar" bölümünde belirtilenler dışında, güvenlik kontrol listesini karşıladığını onaylıyorum.
