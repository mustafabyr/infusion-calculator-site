# İnfüzyon Hesaplayıcı — site

Gizlilik politikası ve destek sayfası; Google Play ve App Store listelemelerinde
kullanılan URL'ler buradan sunuluyor.

Kaynak, uygulama deposunda `site/` altında tutuluyor ve `git subtree` ile bu
depoya itiliyor:

```bash
git subtree push --prefix=site site main
```

Sayfalar: `index.html`, `gizlilik.html` / `privacy.html`, `destek.html` / `support.html`.
Düz HTML, derleme adımı yok.
