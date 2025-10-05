🍕 Tri Fratelli Frontend

Autor: Igor Takagui Reis
Disciplina: Desenvolvimento Web II – UNIFACEF

📘 Descrição do Projeto

Este repositório contém o módulo Frontend do projeto Tri Fratelli, desenvolvido em grupo como parte da disciplina de Desenvolvimento Web II da UNIFACEF.
O Frontend é responsável por toda a interface gráfica e interação do usuário, sendo a camada que consome as APIs do Backend para exibir e manipular os dados do cardápio digital da pizzaria.

A aplicação foi desenvolvida em React com TypeScript, garantindo uma estrutura modular, de fácil manutenção e visual profissional inspirado em cardápios digitais modernos.

🎯 Objetivo do Código-Fonte

O objetivo deste módulo é oferecer uma interface visual dinâmica e funcional que se comunique com o Backend, permitindo o gerenciamento completo dos produtos cadastrados (pizzas, preços e imagens).

Principais objetivos do código:

Criar um layout limpo, moderno e responsivo para o cardápio digital.

Consumir a API RESTful do Backend via requisições HTTP (GET, POST e DELETE).

Exibir de forma clara os produtos cadastrados, com nome, preço e imagem.

Permitir o cadastro de novos itens de forma intuitiva.

Aplicar feedbacks visuais (carregando, sucesso, erro).

🧠 Integração com o Projeto Final em Grupo

O Frontend é a camada que conecta o usuário final com o sistema.
Enquanto o Backend (criado pelos colegas Mateus e João Pedro) gerencia os dados no banco e fornece a API, o Frontend consome essas rotas para exibir e manipular as informações em tempo real.

Fluxo de integração:

O usuário cadastra uma pizza no formulário.

O Frontend envia os dados via POST para o Backend.

O Backend grava as informações no banco (SQLite via Prisma).

O Frontend atualiza automaticamente a listagem exibindo o novo item.

Assim, o Frontend atua como a camada de apresentação e interação do sistema.

⚙️ Tecnologias Utilizadas

React.js – Biblioteca principal da interface

TypeScript – Tipagem estática e melhor manutenção do código

Axios / Fetch API – Comunicação com o Backend

CSS Modular – Personalização visual e responsividade

Node.js + npm – Ambiente de execução e gerenciamento de dependências

🧩 Estrutura do Projeto
frontend/
├── src/
│   ├── api/
│   │   └── foodApi.ts
│   ├── components/
│   │   ├── FoodForm.tsx
│   │   └── FoodCard.tsx
│   ├── App.tsx
│   ├── index.tsx
│   └── App.css
├── public/
│   └── index.html
├── package.json
├── tsconfig.json
└── README.md

🚀 Como Rodar o Projeto
🧱 Pré-requisitos

Node.js (versão 18 ou superior)

npm ou yarn

Backend em execução (porta padrão: 5000)

💻 Passos
# Clonar o repositório
git clone https://github.com/IgorTakagui/Project.git
cd frontend

# Instalar dependências
npm install

# Executar o projeto
npm start


A aplicação estará disponível em:
👉 http://localhost:3000

🧾 Funcionalidades Principais
Função	Descrição
📝 Cadastro de Pizza	Adiciona um novo produto (nome, preço e imagem)
📋 Listagem de Itens	Exibe todas as pizzas cadastradas
❌ Exclusão	Remove um item específico
🔍 Busca e Filtro	Permite localizar rapidamente um produto
💬 Feedback Visual	Mensagens de erro e sucesso durante o uso
👨‍💻 Autor

Igor Takagui Reis
Responsável pelo desenvolvimento do Frontend completo, design da interface, integração com a API e estrutura visual da aplicação.
