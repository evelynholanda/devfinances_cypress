INICIALIZAR PROJETO NODE
npm init- y

INSTALAR CYPRESS
npm install -D cypress ou
npm install -D ctpress@12.5.0 Versao específica

ABRIR CYPRESS MODO INTERATIVO
npm cypress open

ABRIR CYPRESS MODO HEADLESS
npx cypress run

UTILIZANDO MODO HEADLESS PARA VERSAO MOBILE
npx cypress run --config viewportWidth=375,viewportHeight=667

CRIANDO SCRIPTS
adicionar- 
"scripts": {
    "test": "npx cypress run"
  }
Linha de Comando Executar: npm test
