# 📘 Sistema de Cadastro de Usuários – Back-end

Este projeto é a API back-end de um sistema de cadastro de usuários. Foi desenvolvido com o objetivo de aprender e aplicar os conceitos fundamentais do Node.js, incluindo rotas, requisições, middleware, integração com banco de dados e ORM.

---

## 🚀 Tecnologias utilizadas

- **Node.js** – Ambiente de execução JavaScript server-side
- **Express** – Framework minimalista para criação de APIs REST
- **Prisma** – ORM moderno para integração com o MongoDB
- **MongoDB** – Banco de dados NoSQL


🛠 Funcionalidades

📄 Cadastro de usuários;
🔍 Listagem de usuários;
✏️ Atualização de dados;
❌ Exclusão de usuários;

As rotas foram desenvolvidas para reforçar conceitos de CRUD com Express e banco de dados via Prisma.

🧠 Sobre o projeto
Este foi meu primeiro projeto com Node.js, com o foco principal em aprendizado. A escolha do Prisma e do MongoDB foi para estudar a integração entre um ORM moderno e um banco de dados NoSQL.

![image](https://github.com/user-attachments/assets/d2510a89-fc84-4a3e-b725-1be1ec17934a)

![image](https://github.com/user-attachments/assets/737ec900-1687-4b66-aa95-3f5400fcb231)

![image](https://github.com/user-attachments/assets/d0e419f6-105c-4051-bc26-26a2ad1b2521)

![image](https://github.com/user-attachments/assets/04063c8d-70af-40f5-8ba9-234149c64781)

![image](https://github.com/user-attachments/assets/e31e0ff2-5d5c-4304-9542-754f74ed7e98)

🚀 Como executar o projeto

1. **Clone o repositório**:

```bash
git clone https://github.com/Matheus-Figueiredo-Dev/Cadastro-de-usuarios-back-end.git
cd Cadastro-de-usuarios-back-end

2. **Instale as dependências**:
npm install

3. **Configure as variáveis de ambiente**:
Crie um arquivo .env na raiz do projeto e adicione sua string de conexão do MongoDB:

DATABASE_URL=mongodb+srv://SEU_USUARIO:SUA_SENHA@cluster.mongodb.net/nome-do-banco
Importante: certifique-se de que sua senha está URL-encoded (sem caracteres especiais não escapados, como @ ou #).


4. **Gere o Prisma client**:
npx prisma generate

5. **Inicie o servidor**:
npm run dev
