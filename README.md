# idx-potpore-otvoreni-podaci

[Web stranica](https://gradzagreb.github.io/potpore-otvoreni-podaci/) s
kazalom projekata koji su dobili potpore za projekte temeljene na otvorenim
podacima Grada.

Stranica je izrađena koristeći alate MkDocs i MkDocs Material. Za posluživanje
stranice koristimo GitHub Pages servis koji prati promjene na `git` grani
`gh-pages`.

# Upute

Aktivirati virtualno okruženje (za Windows):

```shell
.venv\Scripts\Activate
```

Izgraditi stranicu:

```shell
mkdocs.exe build
```

Prirediti i ažurirati `gh-pages` branch u `origin` za objavu (s `main` grane):

```shell
mkdocs gh-deploy
```
