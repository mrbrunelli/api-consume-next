# Como consumir dados da API no Next.js e React.js

## Links para outros repositórios
:anchor: [Link para repositório da API em Node.js](https://github.com/mrbrunelli/api-node-express)

:anchor: [Link para o respositório do React.js](https://github.com/mrbrunelli/api-consume-react)

## Lista passo a passo
* Para rodar esse repositório é só clocar, e depois de feito, dentro da pasta raíz digitar esse comando:
```bash
# Instalar dependências
npm install
# Rodar projeto em servidor
npm run dev
```

## Criando do zero
1. Iniciar criação das dependências
```bash
npm init
```

2. Instalar o Next.js e o React.js
```bash
npm install next react react-dom
```

3. Adicionar no "scripts" do package.json
```json
"dev": "next",
"build": "next build",
"start": "next start"
```

4. Iniciar servidor da aplicação
```bash
npm run dev
```

5. Instalar o Axios
```bash
npm install --save axios
```
