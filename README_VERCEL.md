# Deploy no GitHub + Vercel

Esta pasta contém uma build WebGL estática pronta para deploy.

## Vercel

Importe o repositório no Vercel e use:

- Framework Preset: Other
- Build Command: deixe vazio
- Output Directory: `.`
- Install Command: deixe vazio

O `vercel.json` já está incluído para preservar o carregamento dos arquivos comprimidos da build.

## GitHub

Os arquivos grandes da build WebGL devem ser enviados pelo Git/linha de comando. O upload pelo navegador do GitHub tem limite menor.

Se algum arquivo ultrapassar 100 MiB, use Git LFS.

## Importante

Não renomeie os arquivos dentro de `Build/`: o `index.html` referencia esses nomes.
