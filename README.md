# Portfolio — Andi Tarmizi

Single-page portfolio untuk software house saya.

## Cara Deploy ke GitHub Pages

### Opsi 1: User Site (matdev90.github.io)

```bash
# 1. Buat repo baru di GitHub dengan nama: matdev90.github.io
# 2. Push file ini ke repo tersebut
git init
git add -A
git commit -m "Initial portfolio"
git remote add origin https://github.com/matdev90/matdev90.github.io.git
git push -u origin main
```

GitHub Pages otomatis aktif untuk user site. Buka `https://matdev90.github.io`.

### Opsi 2: Project Site (portfolio repo)

```bash
# 1. Buat repo baru di GitHub dengan nama: portfolio
# 2. Push ke branch gh-pages
git init
git checkout -b gh-pages
git add -A
git commit -m "Initial portfolio"
git remote add origin https://github.com/matdev90/portfolio.git
git push -u origin gh-pages
# 3. Di GitHub: Settings → Pages → pilih branch gh-pages
```

Buka `https://matdev90.github.io/portfolio`.
