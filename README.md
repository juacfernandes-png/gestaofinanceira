# 💰 Gestão Financeira Pessoal - Aurum Assessoria

Sistema completo de gestão financeira pessoal e empresarial desenvolvido com React 19, tRPC, Express e MySQL.

---

## 🚀 **Funcionalidades**

### 📊 **Gestão Pessoal**
- ✅ Controle de gastos e entradas
- ✅ Planejamento financeiro
- ✅ Notas de encontros
- ✅ Contas a pagar/receber
- ✅ Dashboard com gráficos e métricas
- ✅ OCR para reconhecimento de notas fiscais

### 🏢 **Gestão Empresarial**
- ✅ Controle de despesas e faturamento
- ✅ Módulo de Operação completo:
  - Gestão de Produtos e Estoque
  - Cadastro de Funcionários
  - CRM (Clientes)
  - Gestão de Leads
  - Sistema de Vendas
  - Agenda de Compromissos
  - Controle de Caixa
- ✅ Dashboard com KPIs (Ticket Médio, CAC, Churn, CLV, ROI)
- ✅ Contas a pagar/receber
- ✅ Métricas personalizadas

### 🔐 **Autenticação**
- ✅ Sistema de login tradicional (email/senha)
- ✅ Recuperação de senha
- ✅ Roles (admin/user)
- ✅ Integração com Manus OAuth

---

## 🛠️ **Stack Tecnológica**

### **Frontend**
- React 19
- TypeScript
- Tailwind CSS 4
- shadcn/ui
- tRPC Client
- Recharts (gráficos)
- Wouter (roteamento)

### **Backend**
- Node.js 22
- Express 4
- tRPC 11
- Drizzle ORM
- MySQL/TiDB
- JWT para autenticação

### **Ferramentas**
- Vite (build)
- pnpm (gerenciador de pacotes)
- Vitest (testes)

---

## 📦 **Instalação**

### **Pré-requisitos**
- Node.js 22+
- pnpm 9+
- MySQL 8+ ou TiDB

### **1. Clone o repositório**
```bash
git clone https://github.com/seu-usuario/gestao-financeira-pessoal.git
cd gestao-financeira-pessoal
```

### **2. Instale as dependências**
```bash
pnpm install
```

### **3. Configure as variáveis de ambiente**

Crie um arquivo `.env` na raiz do projeto:

```env
# Database
DATABASE_URL=mysql://usuario:senha@localhost:3306/gestao_financeira

# JWT
JWT_SECRET=seu_jwt_secret_aqui_minimo_32_caracteres

# OAuth (opcional - para integração Manus)
OAUTH_SERVER_URL=https://api.manus.im
VITE_OAUTH_PORTAL_URL=https://portal.manus.im
VITE_APP_ID=seu_app_id

# App Config
VITE_APP_TITLE=Gestão Financeira Pessoal
VITE_APP_LOGO=/logo.svg
OWNER_OPEN_ID=seu_open_id
OWNER_NAME=Seu Nome

# APIs (opcional - para funcionalidades avançadas)
BUILT_IN_FORGE_API_URL=https://api.manus.im
BUILT_IN_FORGE_API_KEY=sua_api_key
VITE_FRONTEND_FORGE_API_KEY=sua_frontend_api_key
VITE_FRONTEND_FORGE_API_URL=https://api.manus.im
```

### **4. Execute as migrations do banco de dados**
```bash
pnpm db:push
```

### **5. Inicie o servidor de desenvolvimento**
```bash
pnpm dev
```

O sistema estará disponível em `http://localhost:3000`

---

## 🗄️ **Estrutura do Banco de Dados**

### **Tabelas Principais**

#### **Pessoal**
- `users` - Usuários do sistema
- `expenses` - Gastos pessoais
- `incomes` - Entradas pessoais
- `notes` - Notas de encontros
- `planning` - Planejamento financeiro
- `personal_bills` - Contas a pagar pessoais

#### **Negócio**
- `business_expenses` - Despesas do negócio
- `business_incomes` - Faturamento
- `business_notes` - Notas do negócio
- `business_planning` - Planejamento empresarial
- `business_bills` - Contas a pagar do negócio
- `business_metrics` - Métricas personalizadas

#### **Operação**
- `products` - Produtos e estoque
- `employees` - Funcionários
- `crm_clients` - Clientes CRM
- `leads` - Leads de vendas
- `sales` - Vendas
- `sale_items` - Itens de venda
- `stock_movements` - Movimentações de estoque
- `appointments` - Agenda de compromissos
- `client_interactions` - Interações com clientes

---

## 📁 **Estrutura de Pastas**

```
gestao-financeira-pessoal/
├── client/                 # Frontend React
│   ├── public/            # Arquivos estáticos
│   └── src/
│       ├── components/    # Componentes reutilizáveis
│       ├── contexts/      # React contexts
│       ├── hooks/         # Custom hooks
│       ├── lib/           # Utilitários e tRPC client
│       └── pages/         # Páginas da aplicação
├── server/                # Backend Express + tRPC
│   ├── _core/            # Infraestrutura (OAuth, LLM, etc)
│   ├── routers/          # Rotas tRPC
│   ├── db.ts             # Queries do banco
│   └── routers.ts        # Configuração de rotas
├── drizzle/              # Schema e migrations
├── shared/               # Código compartilhado
└── package.json
```

---

## 🔧 **Scripts Disponíveis**

```bash
# Desenvolvimento
pnpm dev              # Inicia servidor de desenvolvimento

# Build
pnpm build            # Build para produção
pnpm preview          # Preview do build

# Banco de Dados
pnpm db:push          # Aplica migrations
pnpm db:studio        # Abre Drizzle Studio

# Testes
pnpm test             # Executa testes
pnpm test:ui          # Abre UI de testes

# Linting
pnpm lint             # Verifica código
```

---

## 🚀 **Deploy**

### **Opção 1: Manus Platform**
O projeto já está configurado para deploy na plataforma Manus. Basta fazer push para o repositório conectado.

### **Opção 2: Vercel/Netlify**
1. Configure as variáveis de ambiente
2. Execute `pnpm build`
3. Deploy da pasta `dist`

### **Opção 3: Docker**
```dockerfile
FROM node:22-alpine
WORKDIR /app
COPY package.json pnpm-lock.yaml ./
RUN npm install -g pnpm && pnpm install
COPY . .
RUN pnpm build
EXPOSE 3000
CMD ["pnpm", "start"]
```

---

## 📝 **Uso**

### **Primeiro Acesso**
1. Acesse `http://localhost:3000`
2. Clique em "Entrar"
3. Use as credenciais padrão ou crie uma conta

### **Navegação**
- **Seção CLIENTE**: Dados pessoais (gastos, entradas, planejamento)
- **Seção NEGÓCIO**: Dados empresariais (despesas, faturamento, operação)

### **Funcionalidades Especiais**

#### **OCR de Notas Fiscais**
1. Vá em "Gastos"
2. Clique em "Adicionar Gasto"
3. Clique em "Escanear Nota Fiscal"
4. Tire foto ou selecione imagem
5. Sistema extrai automaticamente: valor, data, descrição e categoria

#### **Métricas CRM**
- Sistema atualiza automaticamente métricas dos clientes quando vendas são finalizadas
- Total gasto, ticket médio, número de compras e última compra

---

## 🤝 **Contribuindo**

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

---

## 📄 **Licença**

Este projeto é privado e proprietário da Aurum Assessoria.

---

## 📧 **Contato**

**Aurum Assessoria**
- Website: [em breve]
- Email: contato@aurumassessoria.com.br

---

## 🙏 **Agradecimentos**

- [Manus Platform](https://manus.im) - Infraestrutura e APIs
- [shadcn/ui](https://ui.shadcn.com) - Componentes UI
- [tRPC](https://trpc.io) - Type-safe APIs
- [Drizzle ORM](https://orm.drizzle.team) - ORM TypeScript

---

**Desenvolvido com ❤️ por Manus AI**
