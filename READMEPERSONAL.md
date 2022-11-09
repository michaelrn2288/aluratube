instalar next, react, react-dom e styled components usando comando:
    npm install next react react-dom styled-components

(seguir instruções do docs do site do NEXT.js)

no package.json, colar:
    "scripts": {
  "dev": "next dev",
  "build": "next build",
  "start": "next start",
  "lint": "next lint"
    }

criar pasta 'pages' na raíz do projeto.

criar arquivo index.js na pasta 'pages'

a própria função exportada no index.js já é renderizada, sem importar react nem usar método render.

no terminal, rodar 'npm run dev' para rodar no modo desenvolvedor (arquivos atualizados recarregam a página na hora)
(ctrl+c no terminal para finalizar modo dev)