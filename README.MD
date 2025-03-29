# 📝 NotesAPI - API para Gerenciamento de Anotações  

NotesAPI é uma API desenvolvida com **Node.js e Express** para criar e gerenciar anotações de forma eficiente. Suporta a adição de **tags, links e descrições** para organizar as anotações.  

## 📌 Funcionalidades  

✅ Criar, editar e excluir anotações  
✅ Adicionar tags e links para organização  
✅ Autenticação com JWT para segurança  
✅ Upload de arquivos com Multer  
✅ Armazenamento em banco de dados SQLite  

## 🛠️ Tecnologias Utilizadas  

- 🚀 **Express** - Framework para criação da API  
- 🔒 **JWT (jsonwebtoken)** - Autenticação segura  
- 🔐 **bcryptjs** - Hash de senhas  
- 🌍 **CORS** - Permissão de acesso entre domínios  
- 🗄️ **Knex + SQLite3** - ORM para banco de dados SQLite  
- 📦 **Multer** - Upload de arquivos  
- 🔄 **PM2** - Gerenciamento da aplicação em produção  
- 🛠️ **Dotenv** - Variáveis de ambiente  
- ⚡ **Express Async Errors** - Tratamento de erros assíncronos  

## 📂 Como rodar o projeto  

- npm install
- npm run knex:migrate
- npm run dev


### 1️⃣ Clone o repositório  
```bash
git clone https://github.com/ivanrods/notes-api.git
cd notes-api
