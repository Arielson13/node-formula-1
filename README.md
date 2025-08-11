# 🏎️ Node Formula 1
Este projeto é uma aplicação Node.js com Fastify e TypeScript, criada para servir como base para um sistema de Fórmula 1, com suporte a variáveis de ambiente, compilação otimizada e execução em diferentes modos (desenvolvimento, observação e produção).

## 🚀 Tecnologias Utilizadas
* Node.js – Ambiente de execução JavaScript

* Fastify – Framework web rápido e leve

* TypeScript – Tipagem estática para maior segurança no código

* tsup – Empacotamento e build

* tsx – Execução de TypeScript sem compilação prévia

* dotenv – Variáveis de ambiente

* @fastify/cors – Configuração de CORS

## 📂 Estrutura do Projeto
        node-formula-1/
        │-- src/
        │   └── server.ts        # Arquivo principal da aplicação
        │-- .env                 # Configurações de ambiente
        │-- package.json         # Configuração do projeto e scripts
        │-- tsconfig.json        # Configuração do TypeScript
        │-- .gitignore           # Arquivos ignorados no Git

## ⚙️ Instalação e Uso
1️⃣ Clonar o repositório

        git clone https://github.com/Arielson13/node-formula-1.git
        cd node-formula-1

2️⃣ Instalar dependências

        npm install

3️⃣ Configurar variáveis de ambiente

        Crie um arquivo .env na raiz do projeto e adicione as variáveis necessárias.

Exemplo:

        PORT=3000

4️⃣ Executar em desenvolvimento

        npm run start:dev

5️⃣ Executar com hot-reload

        npm run start:watch

6️⃣ Gerar build de produção e executar

        npm run start:dist

## 📜 Scripts Disponíveis
| Script | Descrição |
|--------|-----------|
|`npm run start:dev`|Inicia o servidor com variáveis de ambiente carregadas|
|`npm run start:watch`|Inicia o servidor observando alterações|
|`npm run dist`|Compila o projeto para a pasta `dist`|
|`npm run start:dist`|Compila e executa o build de produção|

## 📄 Licença
Este projeto está sob a licença ISC. Consulte o arquivo [LICENSE]() para mais detalhes.

