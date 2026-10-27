# Gezinti (kişisel) — notlar

Bu repo kullanıcının **özel** Adana–Kapadokya gezisi (28 Ekim – 1 Kasım 2026) içindir: https://sozenn.github.io/Gezinti/
Linki başkalarıyla paylaşılmıyor. İçinde kişisel bilgiler var (otel, tarih, ev çıkış noktası).

- Genel, herkese açık gezi uygulaması ayrı repoda: **Sozenn/gezi** → https://sozenn.github.io/gezi/ (ayrıntılı notlar o repodaki CLAUDE.md'de).
- `yeni/index.html` yalnızca yeni uygulamaya yönlendirir.
- Bu uygulama her açılışta gezinin güncel halini cihazın localStorage'ına `v1-aktarim` anahtarıyla bırakır; yeni uygulama ilk açılışta oradan aktarır.
- `firestore.rules` burada da duruyor, ama güncel kaynak artık Sozenn/gezi reposundaki kopya. İkisini aynı tut.
- `sw.js` önbellek sürümü (`gezi-vN`) her değişiklikte artırılır.
