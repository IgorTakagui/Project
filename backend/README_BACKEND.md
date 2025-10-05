[![Tecnologias](https://skillicons.dev/icons?i=nodejs,express,typescript,prisma,sqlite,docker&theme=dark)](https://skillicons.dev)

---

## 👨‍💻 Autor: **Igor Takagui Reis**
Disciplina: Desenvolvimento Web II – UNIFACEF  
Instituição: Centro Universitário Municipal de Franca (UNIFACEF)

---

## 🍽️ Sobre o Projeto  
O backend é o núcleo lógico do sistema *Tri Fratelli*, responsável por gerenciar os dados do cardápio digital, como nome, preço e imagem das pizzas, além de fornecer uma **API RESTful** para integração com o frontend.

Este módulo foi desenvolvido em **Node.js com TypeScript**, utilizando **Express.js** e **Prisma ORM**, conectando-se ao banco **SQLite**.  
O projeto garante uma comunicação eficiente entre a interface (frontend) e o banco de dados, mantendo o fluxo de informações atualizado e seguro.

---

## 🎯 Contribuição Pessoal  
Durante o desenvolvimento do backend, **Igor Takagui Reis** colaborou diretamente com **João Pedro Guinati** na integração do sistema, atuando em pontos estratégicos:

- Apoio na integração entre **frontend e backend**, testando e validando as rotas da API.  
- Auxílio na estruturação dos endpoints e testes de requisição (GET, POST e DELETE).  
- Revisão de comunicação entre o **foodApi.ts** do front e as rotas `/api/foods` do backend.  
- Verificação de respostas JSON, mensagens de erro e status de retorno.  
- Contribuições no design de respostas e organização dos dados para exibição no frontend.

Mesmo não sendo o principal responsável pelo backend, Igor desempenhou um papel importante garantindo que a camada de integração entre ambos funcionasse de forma fluida e padronizada.

---

## ⚙️ Tecnologias Utilizadas  
- **Node.js** – Ambiente de execução do JavaScript  
- **Express.js** – Framework para criação de rotas e APIs REST  
- **TypeScript** – Tipagem estática para melhor controle do código  
- **Prisma ORM** – Mapeamento objeto-relacional  
- **SQLite** – Banco de dados leve e eficiente  
- **Docker** – Containerização e padronização do ambiente  
- **dotenv** – Gerenciamento de variáveis de ambiente  

---

## 📡 Estrutura do Projeto
```
backend/
├── prisma/
│   ├── schema.prisma
│   └── dev.db
├── src/
│   ├── routes/
│   │   └── foodRoutes.ts
│   ├── controllers/
│   │   └── foodController.ts
│   ├── services/
│   │   └── foodService.ts
│   └── server.ts
├── .env
├── Dockerfile
├── package.json
└── tsconfig.json
```

---

## 🌐 Endpoints Principais
| Método | Rota | Descrição |
|--------|------|------------|
| **GET** | `/api/foods` | Retorna todos os alimentos cadastrados |
| **POST** | `/api/foods` | Cadastra um novo alimento |
| **DELETE** | `/api/foods/:id` | Remove um alimento pelo ID |

---

## 🚀 Testes e Integração
Durante o processo de desenvolvimento, Igor auxiliou na **testagem via Postman e Frontend**, garantindo que os endpoints do backend respondessem corretamente e que a aplicação completa funcionasse de ponta a ponta.

Os testes validaram:  
✅ Conexão com o banco via Prisma  
✅ Comunicação entre API e Frontend  
✅ Retorno de mensagens estruturadas em JSON  

---

## 📄 Licença  
Projeto acadêmico desenvolvido para a disciplina de **Desenvolvimento Web II – UNIFACEF (2025)**.  
Todos os direitos reservados ao grupo *Tri Fratelli*.

---

### 👨‍🏫 Desenvolvido por:  
**Igor Takagui Reis**  
📍 *UNIFACEF – Engenharia de Software*  
📚 *Disciplina: Desenvolvimento Web II*  
📧 igor.takagui.reis@example.com
