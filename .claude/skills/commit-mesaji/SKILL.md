---
name: commit-mesaji
description: Değişiklikleri inceleyip Türkçe, kısa ve düzenli bir git commit mesajı önerir. Kullanıcı "commit mesajı yaz" ya da "commit at" dediğinde kullan.
---

# Commit Mesajı Yazma

1. `git status` ve `git diff --staged` (yoksa `git diff`) ile değişiklikleri incele.
2. Aşağıdaki formatta mesaj yaz:

```
<tür>: <kısa özet (en fazla 50 karakter)>

<neyi ve neden değiştirdiğini anlatan isteğe bağlı açıklama>
```

3. Türler: `ekle`, `düzelt`, `güncelle`, `sil`, `belge`, `düzenle`.
4. Özet cümlesi emir kipinde, nokta olmadan olsun. Örnek: `ekle: giriş sayfası`.
5. Mesajı kullanıcıya göster ve onay almadan commit atma.
