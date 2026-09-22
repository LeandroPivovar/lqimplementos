# LQI Implementos

Site institucional estático da LQI Implementos, publicado com Sites.

## Deploy na Vercel

Importe o repositório `LeandroPivovar/lqimplementos` na Vercel. O arquivo `vercel.json` configura o projeto sem framework ou etapa de build e publica os arquivos estáticos da pasta `dist`.

## Prévia local

```sh
python -m http.server 4173 --directory dist
```

Acesse `http://localhost:4173/`.

## Conteúdo

- `dist/index.html`: página principal.
- `dist/assets/logo-lqi.png`: logo recortada do material fornecido, com fundo transparente.
- `dist/assets/equipamento.png`: imagem ilustrativa baseada no material fornecido.
- `dist/assets/styles.css` e `main.js`: estilos e navegação móvel.
