# Deploy da demo — GitHub Pages (grátis, independente do SCBP)

A pasta `demoboccia/` é AUTÔNOMA e IGNORADA pelo git do SCBP (não sobe no repo privado).
Ela tem git e deploy PRÓPRIOS. Publicamos no repositório público `bocciacompetition`
usando **GitHub Pages** — um site grátis servido pelo próprio GitHub.

---

## Passo 1 — Subir os arquivos ao repositório público

No terminal, DENTRO da pasta `demoboccia`:

```
cd "C:\Users\gabri\OneDrive\Área de Trabalho\Projetos\SC Bocha Paralimpica\demoboccia"
git init
git add .
git commit -m "Public demo SCBP (trilingual, mock data, no commercial code)"
git branch -M main
git remote add origin https://github.com/gabrielrdesousa123/bocciacompetition.git
git push -u origin main
```

Se o GitHub reclamar que o repo já tem um commit inicial:
```
git pull origin main --allow-unrelated-histories
git push -u origin main
```

> Observação: como `demoboccia/` está no `.gitignore` do SCBP, este `git init` cria um
> repositório SEPARADO só da demo. Não mistura com o SCBP. É o que queremos.

---

## Passo 2 — Ativar o GitHub Pages

1. Abra `https://github.com/gabrielrdesousa123/bocciacompetition`
2. **Settings** → **Pages** (menu lateral).
3. Em **Source**, escolha **Deploy from a branch**.
4. Branch: **main** · Folder: **/ (root)** → **Save**.
5. Aguarde ~1 minuto. O GitHub mostra a URL publicada, algo como:
   **https://gabrielrdesousa123.github.io/bocciacompetition/**

Pronto — a demo estará no ar, grátis, sem tocar no seu Firebase.

---

## Passo 3 — (opcional) Colocar o link no README

Depois de publicada, edite o `README.md` e substitua "visit the published page" pelo
link real do GitHub Pages, para quem abrir o repositório clicar e testar direto.

---

## Conferência de segurança (já verificado)
- `index.html`: sem Firebase, sem chaves, sem código comercial (só dados fictícios).
- Nenhum arquivo do `client/` ou `functions/` está aqui.
- O repositório privado `SCPB` permanece separado e com o código real.
