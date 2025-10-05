### 👨‍💻 Autor: **Igor Takagui Reis**  
Disciplina: Desenvolvimento Web II – UNIFACEF  
Instituição: Centro Universitário Municipal de Franca (UNIFACEF)

---

## 🎯 OBJETIVO  
Desenvolver a **interface visual e funcional** do sistema de cardápio digital da pizzaria *Tri Fratelli*, proporcionando uma experiência intuitiva e moderna para o usuário final e permitindo o gerenciamento completo dos produtos em tempo real.

O foco deste módulo foi criar um **frontend totalmente integrado ao backend**, com layout responsivo, design limpo e uma estrutura de componentes reutilizáveis que garantem escalabilidade e manutenção eficiente.

---

## 🧩 TECNOLOGIAS UTILIZADAS

### 💻 **Front-end**
![React](https://skillicons.dev/icons?i=react)
![Typescript](https://skillicons.dev/icons?i=typescript)
![Vite](https://skillicons.dev/icons?i=vite)
![Css3](https://skillicons.dev/icons?i=css)
![Axios](https://skillicons.dev/icons?i=axios)

- **React.js** – Biblioteca para criação da interface do usuário  
- **TypeScript** – Tipagem estática e maior previsibilidade no código  
- **Vite** – Build tool moderna para desenvolvimento rápido  
- **Axios** – Cliente HTTP para comunicação com a API do backend  
- **CSS3** – Estilização moderna, responsiva e alinhada à identidade visual da marca  

---

## ⚙️ FUNCIONALIDADES IMPLEMENTADAS

### 🧠 Estrutura e Lógica
- Criação de toda a **estrutura do Frontend** do projeto em React + TypeScript  
- Implementação da **integração completa com o backend** via API RESTful  
- Utilização de **hooks** e componentes funcionais para controle de estado  
- Implementação de **componentização modular** (FoodForm, FoodCard, etc.)  
- Tratamento de erros e feedback visual ao usuário (mensagens de sucesso e falha)

---

### 💅 Design e Interface
- Desenvolvimento de um **layout inspirado em cardápios reais de pizzarias**  
- Definição e aplicação de uma **paleta de cores personalizada**, com tons terrosos e dourados (inspirados na marca Tri Fratelli)  
- Responsividade total para uso em **desktop, tablets e smartphones**  
- Estilização refinada através de **CSS customizado e variáveis globais**  
- Exibição de produtos em **cards visuais**, com imagem, nome e preço  

---

### 🔗 Integração com o Back-end
- Consumo direto das rotas `/api/foods` via Axios  
- Sincronização em tempo real dos cadastros e exclusões realizadas no backend  
- Atualização automática da listagem após cada ação do usuário  
- Implementação do arquivo `foodApi.ts` para centralizar as chamadas de API  

---

## 🧠 ARQUITETURA DO FRONTEND
```
frontend/
├── src/
│   ├── api/
│   │   └── foodApi.ts        # Comunicação com o backend
│   ├── components/
│   │   ├── FoodForm.tsx      # Formulário de cadastro
│   │   └── FoodCard.tsx      # Exibição dos produtos
│   ├── styles/
│   │   └── App.css           # Estilo geral e paleta de cores
│   ├── App.tsx               # Estrutura principal da aplicação
│   └── index.tsx             # Ponto de entrada
├── package.json
├── tsconfig.json
└── README.md
```

---

## 🧾 FUNCIONALIDADES DO FRONTEND

✅ **Listagem de produtos** – Exibição automática dos itens cadastrados  
✅ **Cadastro de novos produtos** – Formulário dinâmico com validação  
✅ **Exclusão imediata** – Remoção de produtos com atualização instantânea  
✅ **Busca inteligente** – Filtro de produtos por nome  
✅ **Feedback visual** – Mensagens de sucesso e erro em tempo real  
✅ **Design responsivo** – Layout ajustável em qualquer tela  

---

## 🚀 COMO EXECUTAR

### 🧱 Pré-requisitos
- Node.js (versão 18 ou superior)  
- npm ou yarn  
- Backend em execução (porta padrão: 5000)

### 💻 Passos
```bash
# Clonar o repositório
git clone https://github.com/IgorTakagui/Project.git
cd frontend

# Instalar dependências
npm install

# Executar o servidor de desenvolvimento
npm run dev
```

A aplicação estará disponível em:  
👉 **http://localhost:3000**

---

## 🌐 Integração com o Projeto Fullstack
O frontend desenvolvido por Igor Takagui Reis se conecta diretamente ao backend criado por João Pedro Guinati e Mateus Moreira.  
O fluxo de dados segue o modelo:

`Usuário → Frontend (React) → API REST (Node.js + Express) → Banco SQLite (Prisma ORM)`

Essa integração garante que todo cadastro, exclusão ou consulta feita na interface seja refletida instantaneamente no banco de dados do sistema.

---

## 🧠 FUTURAS MELHORIAS
- Implementação do sistema de **carrinho de compras**  
- Adição de **autenticação JWT** para controle de acesso  
- Filtros por **categoria, preço e tipo de pizza**  
- Deploy completo via **Docker e Render**

---

## 📄 LICENÇA
Projeto desenvolvido para fins acadêmicos na disciplina de **Desenvolvimento Web II – UNIFACEF (2025)**.  
Todos os direitos reservados ao grupo *Tri Fratelli*.

---

### 👨‍🏫 Desenvolvido por:
**Igor Takagui Reis**  
📍 *UNIFACEF – Engenharia de Software*  
📚 *Disciplina: Desenvolvimento Web II*  
📧 igor.takagui.reis@example.com  
