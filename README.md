# MK19 WebGL

Build WebGL otimizada do projeto MK19, preparada para versionamento no GitHub e publicação como aplicação web.

## Estrutura

- `index.html` — página de entrada da aplicação WebGL.
- Arquivos `*.data.gz`, `*.framework.js.gz` e `*.wasm.gz` — arquivos da build WebGL.
- `TemplateData/` — recursos visuais usados pelo template WebGL.
- `.gitignore` — evita enviar arquivos temporários e gerados desnecessários.

## Publicação

Esta pasta contém a build pronta para hospedagem estática. Para publicar, use um serviço compatível com arquivos estáticos, como Vercel, Netlify ou GitHub Pages.

> Observação: arquivos WebGL grandes podem exigir configuração específica de hospedagem e compressão. Se a hospedagem acusar limite de tamanho, uma alternativa é usar Git LFS ou armazenamento de artefatos/CDN.

## Git

```bash
git init
git add .
git commit -m "chore: adiciona build WebGL otimizada"
git branch -M main
git remote add origin SEU_REPOSITORIO
git push -u origin main
```
