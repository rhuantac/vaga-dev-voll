**Desafio para Desenvolvedor Júnior**

### **Objetivo**
Desenvolver uma aplicação para troca de mensagens utilizando **Rails** no backend e **Vue.js** no frontend. O propósito deste desafio é avaliar a capacidade do candidato de projetar e implementar um sistema funcional, bem estruturado e seguindo boas práticas de desenvolvimento.

---

### **Descrição do Projeto**
O candidato deverá desenvolver um sistema onde usuários podem trocar mensagens entre si. A aplicação deve ser composta por uma API REST no backend e um frontend que interaja com essa API.

#### **Requisitos Mínimos**
##### **Backend (Rails API)**
- Implementação de um sistema de usuários (cadastro via seed ou criação manual, sem interface gráfica).
- Endpoint para envio de mensagens entre usuários (`POST /messages`).
- Endpoint para recuperação de mensagens enviadas e recebidas (`GET /messages/{user_id}`).
- Restrições de acesso: apenas usuários autenticados podem enviar mensagens e visualizar seu próprio histórico.
- Utilização de banco de dados relacional (SQLite, PostgreSQL ou equivalente).

##### **Frontend (Vue.js)**
- Interface de autenticação simples (input para inserir `user_id`).
- Exibição das mensagens enviadas e recebidas em uma interface organizada.
- Campo para composição e envio de novas mensagens.

#### **Diferenciais (Extras Opcionais)**
Os seguintes itens não são obrigatórios, mas podem agregar valor à solução apresentada:
- **Comunicação em tempo real via WebSocket** (uso opcional de ActionCable ou outra tecnologia).
- **Suporte ao envio de arquivos** (permitindo anexos como imagens e documentos pequenos).
- **Implementação de paginação na listagem de mensagens** para melhor desempenho.
- **Mecanismo de autenticação** (por exemplo, JWT) para garantir segurança nas requisições.
- **Criação de um endpoint de métricas** (`/metrics`) com estatísticas sobre mensagens enviadas e usuários ativos.
- **Processamento assíncrono de mensagens** utilizando fila de tarefas (exemplo: Redis + Sidekiq).

---

### **Instruções para Entrega**
1. Publicar o código no **GitHub** (ou outra plataforma pública de versionamento).
2. Incluir um **README** contendo:
   - Passo a passo para configurar e executar o projeto (backend e frontend).
   - Tecnologias utilizadas.
   - Quais diferenciais foram implementados (caso aplicável).
3. Enviar o link do repositório junto com o currículo para o email: rh@vollsolutions.com.br.

**Observação:** A publicação online da aplicação não é necessária, apenas a disponibilização do código-fonte em repositório público.

---

### **Critérios de Avaliação**
- Organização, clareza e legibilidade do código.
- Implementação correta dos requisitos básicos.
- Aplicação de boas práticas de desenvolvimento (estrutura modular, separação de responsabilidades, etc.).
- Qualidade da documentação no README.
- Implementação de diferenciais (caso tenha sido realizada).

---

**Bom desafio e sucesso!**

