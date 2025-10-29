# DAHAO — Canlı Yönetişim Deposu

Bu depo **DAHAO Çekirdeği**'dir: **kurallar, terimler ve ilkeler** statik belgeler değil, **yaşayan metin dosyalarıdır**.

Bu depodaki her dosya şeffaf teklifler, tartışmalar ve oylamalarla değiştirilebilir. Çatallamak her zaman serbesttir. Buradaki hiçbir şey nihai değildir — evrim hakkı hariç.

---

## Burada Ne Bulacaksınız

- **`dahao.yaml`** — Bunun bir DAHAO sistemi olduğunu ilan eden manifesto.
- **`/terms`** — `@consensus`, `@discussion`, `@participant` gibi kavramları tanımlar.
- **`/principles`** — Şeffaflık, çatal özgürlüğü, diyalektik evrim gibi temel değerler.
- **`/rules`** — Teklif, tartışma, oylama, katkı gibi uygulanabilir iş akışları.
- **`/meta-rules`** — Kuralların nasıl değiştirileceği ("kuralların kuralları").

👉 Bunlar sadece dokümantasyon değildir. Bu sistemin nasıl çalıştığına dair **gerçek kaynak**tır.

---

## Bu Depo Nasıl Kullanılır

### İnsanlar İçin

1. **İlgilendiğiniz tanımı bulun**:
   - Oy eşiğini mi bilmek istiyorsunuz? → `/rules/voting.yml` dosyasına bakın.
   - "Tartışma" ne demek emin değil misiniz? → `/terms/discussion.yaml` dosyasına bakın.
   - Bir şeyi değiştirmek mi istiyorsunuz? → İlgili dosyada değişiklik önerin.

2. **Bir değişiklik önerin**
   - `[Proposal]` tartışması veya PR açın.
   - Değiştirmek istediğiniz dosya(lar)a işaret edin.
   - Gerekçe, riskler ve sürüm artışını açıklayın.

3. **Tartışın ve müzakere edin**
   - Tez → antitez → sentez döngüsüne katılın.
   - Yapay zekâ ajanlarının özetleyip gerilimleri görünür kılmasını bekleyin.
   - Soğuma ve zamanlama kurallarına uyun.

4. **Oylayın ve karar verin**
   - Tartışma süresi bitince bir oylama başlatın.
   - Eşikler kategoriye göre değişir (bkz. `/rules/voting.yml`).
   - Sonuçlar herkese açıktır ve arşivlenir.

5. **Uygulayın ve etiketleyin**
   - Onaylanan değişiklikler PR ile birleştirilir.
   - `dahao.yaml`'a göre sürüm artırılır.
   - Değişiklik günlüğü güncellenir.

6. **Ya da çatallayın**
   - Katılmıyor musunuz? İstediğiniz zaman çatallayın. DAHAO'nun yolu budur.

---

### LLM Ajanları İçin

Bu depoya bağlı bir yapay zekâ asistanıysanız göreviniz **kuralları bozmadan yardımcı olmak**tır.

Yapmanız gerekenler:
- YAML tanımlarını okuyun, statik kurallar varsaymayın.
- Gerekçelendirilmiş farklar + DAHAO-Trace ile PR önerin.
- Eşikleri, zamanlamayı ve meta kuralları dinamik olarak kontrol edin.
- Her zaman birleştirmeden önce insan onayı isteyin.
- Belirsizlik varsa sessizce davranmayın, bir Tartışma açın.

İlk adımınız:

```
ACK DAHAO-CONTRACT:v1
```

…ve ardından `/rules/*` ve `/meta-rules/*` dosyalarına göre hareket edin.

---

## Neden İşe Yarıyor

- **Dinamik**: Yönetişim kod gibidir — yazılım gibi evrilir.
- **Şeffaf**: Her tartışma, teklif ve oylama herkese açıktır.
- **Çatallanabilir**: İstediğiniz zaman dallanabilir ve yeni şeyler deneyebilirsiniz.
- **Sürüm Kontrollü**: Her değişiklik kaydedilir; tarih korunur.

---

## Daha Fazla Bilgi

- Misyon: https://www.dahao.xyz/mission
- Nasıl çalışır: https://www.dahao.xyz/how-it-works
- Sürümlemeli etik: https://www.dahao.xyz/versioned-ethics
- Ekonomi: https://www.dahao.xyz/economics

---

## Son Not

Bu README **yönetişimin kaynağı değildir**.
Bir **kaynak haritasıdır**.
Gerçek kurallar, terimler ve ilkeler YAML dosyalarında yaşar — ve her an değişebilirler.
"DAHAO nedir" sorusunun cevabı için her zaman doğrudan depoyu okuyun.
