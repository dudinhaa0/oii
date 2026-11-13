# BookNook — Aluno #19

**Clube de Leitura Digital e Empréstimo de Livros**  
PPDM2 • 4º Semestre • Professor Adriano Rosa Mazetto

## Sobre
Protótipo acadêmico de clube de leitura digital. Permite explorar catálogo demonstrativo, pesquisar livros e autores, filtrar gêneros, salvar títulos na estante e registrar solicitações ilustrativas de empréstimo. Não possui backend: dados e empréstimos são demonstrativos.

## Identidade visual
- Nome: BookNook — Aluno #19
- Paleta: ameixa, lilás, creme e dourado
- `assets/icon.png`: 1024 × 1024, fundo opaco
- `assets/splash.png`: 2732 × 2732

## Tecnologias
React, Vite, Capacitor 7, `@capacitor/assets`, Android e GitHub Actions.

## Rodar no navegador
```bash
npm install
npm run dev
```

## Gerar APK localmente
Requisitos: Node.js 22, JDK 21 e Android SDK configurado.
```bash
npm install
npm run build
npx cap add android
npx capacitor-assets generate --android
npx cap sync android
```
Se a pasta `android` já existir, pule `npx cap add android`.

## GitHub Actions
Envie o projeto para a branch `main` ou `master`, abra **Actions**, aguarde a execução e baixe o artefato `meu-aplicativo-apk`. Extraia o ZIP e instale `app-debug.apk`. Workflow: `.github/workflows/android-build.yml`.

## Identificação
Aluno #19 • PPDM2 • 4º Semestre • Professor Adriano Rosa Mazetto
