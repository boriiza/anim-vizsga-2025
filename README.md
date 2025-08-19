# Művtöri & Szaktöri tételek – MkDocs (Material) projekt

## Helyi futtatás
```bash
pip install mkdocs mkdocs-material
mkdocs serve
```
Nyisd meg: http://127.0.0.1:8000

## GitHub Pages publikálás
1. Hozz létre egy új publikus repo-t.
2. Másold be a fájlokat a repo-ba, commit + push a **main** branchre.
3. A GitHub Actions workflow automatikusan buildel és kiteszi a `gh-pages` branchre.
4. Repo beállítások → Pages → Branch: `gh-pages`.
5. Az URL: `https://<felhasznalonev>.github.io/<repo-nev>/`

A menüben 20–20 tétel található a **Művtöri** és **Szaktöri** szekciók alatt. A tartalmat a `docs/` mappában tudod szerkeszteni.
