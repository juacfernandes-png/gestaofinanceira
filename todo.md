# TODO - Gestão Financeira Pessoal

## Estrutura e Design
- [x] Configurar tema neon (fundo preto com fontes neon)
- [x] Implementar layout com navegação lateral (DashboardLayout)
- [x] Configurar paleta de cores neon no index.css

## Banco de Dados
- [x] Criar tabela de gastos (expenses) com categorias predefinidas
- [x] Criar tabela de entradas (incomes) com tipos predefinidos
- [x] Criar tabela de notas de encontros (meeting_notes)
- [x] Criar tabela de planejamento (planning)
- [x] Executar migrations no banco de dados

## Funcionalidades - Gastos
- [x] Criar página de listagem de gastos
- [x] Implementar formulário de criação de gasto
- [x] Implementar edição de gasto
- [x] Implementar exclusão de gasto
- [ ] Adicionar filtros por categoria e período

## Funcionalidades - Entradas
- [x] Criar página de listagem de entradas
- [x] Implementar formulário de criação de entrada
- [x] Implementar edição de entrada
- [x] Implementar exclusão de entrada
- [ ] Adicionar filtros por tipo e período

## Funcionalidades - Notas de Encontros
- [x] Criar página de notas de encontros
- [x] Implementar criação de nota
- [x] Implementar edição de nota
- [x] Implementar exclusão de nota

## Funcionalidades - Planejamento
- [x] Criar página de planejamento
- [x] Implementar criação de plano futuro
- [x] Implementar edição de plano
- [x] Implementar exclusão de plano

## Dashboard e Gráficos
- [x] Criar página de visão geral
- [x] Implementar gráfico de linha para receitas vs despesas
- [x] Implementar gráfico por categoria de gastos
- [x] Adicionar filtro por período (mensal, anual, customizado)
- [x] Calcular e exibir saldo total (entradas - saídas)
- [x] Exibir resumo de totais por categoria

## Testes e Finalização
- [x] Testar todas as operações CRUD
- [x] Verificar responsividade da interface
- [x] Validar cálculos e gráficos
- [x] Criar checkpoint final

## Ajustes de Design
- [x] Ajustar cores das letras para tons mais claros e legíveis

## Refinamento Visual
- [x] Remover efeitos neon das letras (text-shadow nos títulos)
- [x] Aplicar cores claras e limpas em todos os textos

## Cores Vibrantes
- [x] Aplicar verde, azul, amarelo e roxo nas letras e elementos
- [x] Trocar fonte para ui-sans-serif, system-ui, sans-serif

## Mudança para Tema Claro
- [x] Alterar fundo para claro (branco/cinza claro)
- [x] Aplicar cores vibrantes diretamente nos textos (verde, azul, amarelo, roxo)
- [x] Ajustar contraste para legibilidade em fundo claro

## Novas Funcionalidades
- [x] Adicionar seção de investimentos recomendados no planejamento
- [x] Permitir criar categorias personalizadas em entradas
- [x] Organizar gastos por mês/ano na visualização

## Seção Meu Negócio
- [x] Criar tabelas de banco de dados para negócio (business_expenses, business_incomes, business_notes, business_planning, business_investments, business_metrics)
- [x] Executar migrations para novas tabelas
- [x] Criar funções de banco de dados para CRUD de negócio
- [x] Criar rotas tRPC para todas as entidades de negócio
- [x] Criar página de Gastos do Negócio
- [x] Criar página de Entradas do Negócio (Faturamento)
- [x] Criar página de Notas do Negócio
- [x] Criar página de Planejamento do Negócio
- [x] Criar dashboard de Negócio com métricas (Faturamento, Lucro Líquido, Ticket Médio, CAC, Churn Rate, CLV, ROI)
- [x] Atualizar navegação lateral com seção Pessoal e Negócio separadas
- [x] Testar todas as funcionalidades da seção de negócio

## Novas Melhorias
- [x] Aplicar paleta de cores neutra e suave (cinzas, brancos, tons pastéis)
- [x] Criar sistema de métricas personalizadas editáveis
- [x] Implementar fórmulas automáticas para métricas personalizadas
- [x] Criar funcionalidade de importação de Excel com identificação automática
- [x] Implementar exportação completa de dados para Excel
- [x] Adicionar interface para gerenciar métricas personalizadas
- [x] Adicionar botões de importação e exportação de Excel na interface

## Sistema Multi-Negócios
- [ ] Criar tabela de negócios no banco de dados
- [ ] Adicionar relacionamento de negócio em todas as tabelas business
- [ ] Criar CRUD de negócios no backend
- [ ] Implementar seletor de negócio no topo do menu lateral
- [ ] Filtrar dados por negócio selecionado em todas as páginas

## Contas a Pagar
- [x] Criar tabela de contas a pagar pessoais
- [x] Criar tabela de contas a pagar do negócio
- [x] Implementar CRUD completo de contas a pagar
- [x] Criar página de contas a pagar pessoais
- [ ] Criar página de contas a pagar do negócio
- [x] Adicionar status (pendente/pago) e data de vencimento

## Comparação de Períodos
- [ ] Criar nova aba de comparação de períodos
- [ ] Implementar seleção de dois períodos customizados
- [ ] Calcular indicadores de crescimento percentual
- [ ] Criar gráficos de tendência comparativos
- [ ] Adicionar comparação para Pessoal e Negócio

## Notificações e Lembretes
- [ ] Criar sistema de notificações push no navegador
- [ ] Implementar verificação de limites de gastos
- [ ] Implementar verificação de metas próximas ao vencimento
- [ ] Criar verificação de contas a pagar próximas ao vencimento
- [ ] Implementar integração WhatsApp Business (preparar estrutura)
- [ ] Criar links de WhatsApp para lembretes manuais

## Exportação Google Sheets
- [ ] Configurar OAuth do Google
- [ ] Implementar criação automática de planilha no Google Drive
- [ ] Adicionar botão de exportação Google Sheets na interface

## Recorrência de Transações
- [x] Adicionar campo de recorrência ao schema (expenses, incomes, business_expenses, business_incomes)
- [x] Atualizar rotas tRPC para suportar recorrência
- [ ] Implementar campo de recorrência nas páginas de Gastos (pessoal e negócio)
- [ ] Implementar campo de recorrência nas páginas de Entradas (pessoal e negócio)
- [ ] Criar lógica para gerar transações recorrentes automaticamente

## Adição em Lote
- [ ] Criar interface de adição em lote para Gastos
- [ ] Criar interface de adição em lote para Entradas
- [ ] Implementar salvamento de múltiplas transações de uma vez

## Correções Urgentes
- [x] Corrigir erro de businessId em business_incomes e business_expenses
- [ ] Criar seletor de negócios funcional
- [x] Adicionar campo recurring na mutation de criação
- [ ] Criar página de Contas a Pagar para negócios
- [ ] Implementar lembretes via WhatsApp
- [ ] Permitir digitação personalizada no campo "Outros"

## Lembretes WhatsApp
- [x] Criar função para gerar links de WhatsApp com mensagens pré-formatadas
- [x] Adicionar botão de lembrete WhatsApp nas contas a pagar
- [ ] Criar página de notificações com alertas pendentes
- [ ] Implementar detecção automática de contas próximas ao vencimento

## Sistema de Autenticação Seguro
- [x] Criar tabela de usuários locais (email, senha hash, role)
- [x] Criar tabela de tokens 2FA/OTP
- [x] Criar tabela de sessões e audit logs
- [x] Implementar bcrypt para hash de senhas
- [x] Criar utilitários de segurança (JWT, OTP, validações)
- [ ] Criar rotas de registro e login tradicional
- [ ] Implementar geração e validação de OTP (2FA)
- [ ] Adicionar rate limiting para prevenir brute force
- [ ] Implementar proteção CSRF
- [ ] Configurar session timeout (15 min)
- [ ] Criar middleware de permissões baseado em roles
- [ ] Criar página de login tradicional
- [ ] Criar página de registro
- [ ] Criar painel admin para gestão de usuários
- [ ] Implementar permissões admin (view_all, edit_all, export, modify_roles)
- [ ] Implementar permissões cliente (view_own, update_profile, view_summary)

## Campo de Conta Bancária
- [x] Adicionar campo bankAccount ao schema (expenses, incomes, business_expenses, business_incomes, personal_bills, business_bills)
- [ ] Atualizar rotas tRPC para incluir bankAccount
- [ ] Adicionar seletor de banco nas páginas de gastos
- [ ] Adicionar seletor de banco nas páginas de entradas
- [ ] Adicionar seletor de banco nas páginas de contas a pagar
- [x] Corrigir erro de businessId em business_incomes
- [x] Criar página de Contas a Pagar para negócios

## Calendário Integrado e Lembretes Automáticos
- [ ] Criar tabela de configurações de usuário (número WhatsApp, preferências de notificação)
- [ ] Instalar bibliotecas: react-calendar, googleapis, node-cron
- [ ] Implementar OAuth do Google Calendar
- [ ] Criar rotas para sincronizar eventos com Google Calendar
- [ ] Criar componente de calendário visual
- [ ] Exibir contas a pagar e reuniões no calendário
- [ ] Implementar sincronização bidirecional (criar/editar/deletar)
- [ ] Criar sistema de agendamento de lembretes
- [ ] Implementar envio automático de lembretes WhatsApp (3 dias antes)
- [ ] Criar página de configurações de notificações
- [ ] Adicionar campo para cadastrar número de WhatsApp

## Seletor de Conta Bancária

- [x] Adicionar dropdown de seletor de banco na página de Gastos (Pessoal)
- [x] Adicionar dropdown de seletor de banco na página de Entradas (Pessoal)
- [ ] Adicionar dropdown de seletor de banco na página de Contas a Pagar (Pessoal)
- [ ] Adicionar dropdown de seletor de banco na página de Despesas (Negócio)
- [ ] Adicionar dropdown de seletor de banco na página de Faturamento (Negócio)
- [ ] Adicionar dropdown de seletor de banco na página de Contas a Pagar (Negócio)

## Campo de Repetição em Contas a Pagar
- [x] Adicionar campo recurring na interface de Contas a Pagar (Pessoal)
- [x] Adicionar campo recurring na interface de Contas a Pagar (Negócio)
- [x] Atualizar rotas tRPC para suportar recurring em bills

## Sistema de Login Tradicional (Completo)
- [x] Instalar dependências (bcrypt, speakeasy, qrcode)
- [x] Atualizar schema do banco com campos de autenticação
- [x] Criar helpers de autenticação (hash, OTP, rate limiting)
- [x] Criar rotas de registro (POST /api/auth/register)
- [x] Criar rotas de login (POST /api/auth/login)
- [x] Implementar geração de OTP para 2FA
- [x] Implementar validação de OTP
- [x] Adicionar rate limiting (5 tentativas por 15 min)
- [x] Criar página de registro com validação de senha
- [x] Criar página de login com suporte a OTP
- [x] Criar painel administrativo de gestão de usuários
- [ ] Configurar session timeout (15 min)
- [ ] Criar middleware de permissões baseado em roles
- [ ] Criar página de login tradicional no frontend
- [ ] Criar página de registro no frontend
- [ ] Criar painel admin para gestão de usuários
- [ ] Implementar permissões admin (view_all, edit_all, export, modify_roles)
- [ ] Implementar permissões cliente (view_own, update_profile, view_summary)

## Completar Seletores de Banco
- [x] Adicionar seletor de banco em Despesas (Negócio)
- [x] Adicionar seletor de banco em Faturamento (Negócio)
- [ ] Adicionar seletor de banco na interface de Contas a Pagar (Pessoal)
- [ ] Adicionar seletor de banco na interface de Contas a Pagar (Negócio)

## Filtros Mensais e por Banco
- [ ] Adicionar filtro mensal (mês/ano) na Visão Geral
- [ ] Adicionar filtro mensal na página de Receitas (Entradas)
- [ ] Adicionar filtro mensal na página de Despesas (Gastos)
- [ ] Adicionar filtro por banco na Visão Geral
- [ ] Integrar filtros com queries do backend

## Relatório de Saldo por Banco
- [ ] Criar card na Visão Geral mostrando saldo de cada banco
- [ ] Implementar query no backend para calcular saldo por banco
- [ ] Exibir lista de bancos com saldo individual

## Painel Administrativo
- [ ] Criar página de gestão de usuários
- [ ] Implementar listagem de todos os usuários
- [ ] Adicionar funcionalidade de edição de roles
- [ ] Implementar permissões (view_all, edit_all, export, modify_roles)
- [ ] Adicionar filtros e busca de usuários

## Menu de Administração
- [x] Adicionar link "Gerenciar Usuários" no menu lateral do DashboardLayout
- [x] Implementar proteção visual baseada em role (apenas admin vê o link)

## Personalização de Branding
- [x] Criar página de login personalizada com "Caio Shimamoto Consultoria"
- [x] Atualizar página de registro com mesmo branding

## Responsividade Mobile
- [ ] Corrigir alinhamento e layout mobile em todas as páginas
- [ ] Otimizar tabelas para visualização em telas pequenas (scroll horizontal ou cards)
- [ ] Ajustar formulários para melhor UX mobile
- [ ] Testar todas as páginas em resoluções mobile (375px, 768px)

## Filtros Mensais
- [x] Adicionar seletor de mês/ano em Gastos (Pessoal)
- [x] Adicionar seletor de mês/ano em Entradas (Pessoal)
- [x] Adicionar seletor de mês/ano em Contas a Pagar (Pessoal)
- [x] Adicionar seletor de mês/ano em Despesas (Negócio)
- [x] Adicionar seletor de mês/ano em Faturamento (Negócio)
- [x] Adicionar seletor de mês/ano em Contas a Pagar (Negócio)
- [x] Adicionar range de anos (2020-2030) em todos os filtros

## Totalizadores Dinâmicos
- [ ] Fazer cards de resumo calcularem apenas período selecionado em Gastos
- [ ] Fazer cards de resumo calcularem apenas período selecionado em Entradas
- [ ] Fazer cards de resumo calcularem apenas período selecionado em Contas a Pagar
- [ ] Fazer cards de resumo calcularem apenas período selecionado em Despesas (Negócio)
- [ ] Fazer cards de resumo calcularem apenas período selecionado em Faturamento (Negócio)

## Atualização de Branding
- [x] Trocar "Consultoria" por "Assessoria" nas páginas de login e registro

## Funcionalidade de Logout
- [x] Implementar botão de logout funcional no menu lateral do dashboard
- [x] Redirecionar para página de login após logout

## Visibilidade do Botão Sign Out
- [x] Otimizar visibilidade do botão "Sign out" em telas pequenas
- [x] Garantir acessibilidade do logout mesmo com sidebar colapsado
- [x] Adicionar botão de logout alternativo no header mobile

## Correções de Login
- [x] Corrigir redirecionamento após login para ir ao dashboard interno (/visao-geral)
- [x] Corrigir redirecionamento após registro para ir ao dashboard interno (/visao-geral)
- [x] Implementar login automático após registro

## Tema Escuro Completo
- [x] Implementar fundo preto com fonte branca na página de login
- [x] Implementar fundo preto com fonte branca na página de registro
- [x] Mudar tema do dashboard para dark (fundo preto, fonte branca)
- [x] Ajustar cores de cards e componentes para tema escuro

## Ajuste de Paleta de Cores
- [x] Mudar cores do tema escuro para tons suaves (azul, ciano, verde água)
- [x] Manter fundo preto mas com textos em cores vibrantes e suaves
- [x] Ajustar cores de títulos, cards e elementos da interface

## Ajuste de Cores (Azul/Roxo/Ciano)
- [x] Remover verde-água da paleta
- [x] Ajustar para tons de azul vibrante, roxo/magenta e ciano
- [x] Manter harmonia visual com fundo preto

## Ajuste de Textos (Branco)
- [x] Mudar textos principais de azul para branco
- [x] Manter roxo e verde apenas em elementos de destaque (títulos, botões, gráficos)

## Suavizar Cores
- [x] Reduzir saturação das cores vibrantes (roxo, magenta, ciano)
- [x] Ajustar para tons pastéis mais suaves e confortáveis

## Trocar Roxo por Verde
- [x] Substituir tons de roxo (250-290°) por tons de verde (140-180°)
- [x] Manter saturação baixa para visual pastel

## Suavizar Cores dos Gráficos
- [x] Trocar vermelho vibrante por rosa/coral pastel
- [x] Ajustar todas as cores dos gráficos para tons pastéis harmoniosos

## Esquema de Cores Semântico
- [x] Saldo positivo/Entradas: Verde (oklch 0.7 0.15 140)
- [x] Atenção/Gastos: Vermelho (oklch 0.6 0.2 25)
- [x] Meio termo/Avisos: Amarelo (oklch 0.75 0.18 90)
- [x] Títulos: Branco (mantido)
- [x] Outros elementos: Roxo (oklch 0.65 0.12 280)

## Remover Efeito Neon dos Gráficos
- [x] Reduzir saturação das cores dos gráficos (de 0.15-0.2 para 0.09-0.15)
- [x] Manter esquema semântico mas com cores mais suaves

## Ajuste de Cores - Página de Login
- [x] Mudar todos os textos da página de login para branco
- [x] Incluir títulos, labels, placeholders e textos auxiliares

## Remover OAuth do Manus
- [x] Desabilitar redirecionamento para OAuth do Manus
- [x] Usar apenas sistema de login tradicional (email/senha/OTP)
- [x] Remover dependência do sistema de autenticação do Manus

## Diferenciação Cliente/Admin
- [x] Implementar filtros de dados por usuário nas queries
- [x] Clientes veem apenas suas próprias transações
- [x] Admins veem dados de todos os clientes
- [x] Adicionar seletor de cliente para admins na Visão Geral

## Seletor de Cliente para Admins em Páginas de Transações
- [x] Adicionar seletor de cliente na página de Gastos (Pessoal)
- [x] Adicionar seletor de cliente na página de Entradas (Pessoal)
- [x] Adicionar seletor de cliente na página de Contas a Pagar (Pessoal)
- [x] Integrar seletor com queries existentes usando parâmetro userId

## Correção de Login
- [ ] Investigar problema de login (usuário não consegue acessar)
- [ ] Verificar rotas de autenticação e redirecionamentos
- [ ] Corrigir fluxo de login

## Correção de Erro de Login
- [ ] Investigar erro "Email ou senha inválidos" no login
- [ ] Verificar se usuário existe no banco de dados
- [ ] Verificar hash de senha e comparação
- [ ] Corrigir problema de autenticação

## Sistema de Recuperação de Senha por Email
- [x] Criar tabela de tokens de recuperação de senha no schema
- [x] Executar migration para criar tabela
- [x] Criar rota de backend para solicitar reset de senha (envia email)
- [x] Criar rota de backend para validar token de reset
- [x] Criar rota de backend para redefinir senha com token válido
- [x] Criar página "Esqueci minha senha" no frontend
- [x] Criar página "Redefinir senha" com validação de token
- [x] Adicionar link "Esqueci minha senha" na página de login
- [x] Testar fluxo completo de recuperação

## Integração de Email para Recuperação de Senha
- [x] Pesquisar e escolher serviço de email (Resend)
- [x] Implementar envio automático usando Resend (requer configuração de API key no Secrets)
- [x] Implementar função de envio de email no backend
- [x] Atualizar rota requestPasswordReset para enviar email real
- [x] Remover exibição de link na tela (apenas confirmar envio)
- [x] Criar template HTML profissional para email de recuperação

## Login Social (Google e Microsoft)
- [ ] Instalar e configurar passport.js e estratégias OAuth
- [ ] Implementar rota de callback do Google OAuth
- [ ] Implementar rota de callback do Microsoft OAuth
- [ ] Adicionar botões de login social na página de login
- [ ] Criar/vincular usuários após autenticação social
- [ ] Testar fluxo completo de login social

## Configuração Centralizada do Resend
- [ ] Documentar como configurar Resend no painel de gerenciamento
- [ ] Testar envio de email com credenciais configuradas

## Correção de Erro - Resend API Key
- [x] Implementar fallback quando RESEND_API_KEY não estiver configurada
- [x] Retornar link de recuperação em modo desenvolvimento
- [x] Atualizar interface para exibir link quando disponível
- [x] Testar ambos os cenários (com e sem API key)

## Correção de Link de Recuperação de Senha
- [x] Investigar por que link gerado não funciona
- [x] Verificar URL base usada na geração do link
- [x] Corrigir geração de link para usar URL correta
- [x] Testar link de recuperação completo

## Enviar Link Apenas por Email
- [ ] Remover exibição de link na tela (modo desenvolvimento)
- [ ] Atualizar backend para não retornar resetLink
- [ ] Adicionar mensagem de erro clara quando Resend não configurado
- [ ] Atualizar interface para mostrar apenas confirmação ou erro
- [ ] Testar fluxo com e sem Resend configurado

## Otimização Mobile - Despesas e Gastos
- [x] Converter tabela de Gastos (Pessoal) para cards em mobile
- [x] Ajustar formulário de Gastos para melhor UX mobile
- [x] Converter tabela de Despesas (Negócio) para cards em mobile
- [x] Ajustar formulário de Despesas para melhor UX mobile
- [x] Testar em resoluções 375px, 768px e 1024px
- [x] Garantir scroll horizontal suave em tabelas quando necessário

## Melhoria de Esquema de Cores
- [x] Ajustar cores da página de Gastos (vermelho apenas em valores, títulos neutros)
- [x] Ajustar cores da página de Entradas (verde apenas em valores, títulos neutros)
- [x] Ajustar cores da página de Despesas do Negócio (vermelho apenas em valores)
- [x] Ajustar cores da página de Faturamento (verde apenas em valores)
- [x] Usar paleta neutra (branco, cinza) para cards e fundos
- [x] Testar consistência visual em todas as páginas

## Página Administrativa de Clientes com Abas
- [ ] Criar componente de abas para navegação entre clientes
- [ ] Criar página ClientesAdmin com lista de todos os usuários
- [ ] Implementar visualização de dados financeiros por cliente selecionado
- [ ] Mostrar resumo de entradas, gastos e saldo por cliente
- [ ] Adicionar rota /admin/clientes no App.tsx
- [ ] Adicionar link na sidebar apenas para admins
- [ ] Testar navegação entre abas de clientes

## Ajustes na Página de Clientes Admin
- [ ] Mudar todos os títulos para branco dentro das abas de clientes
- [ ] Criar tabela de perfis de clientes (origem/indicação, dados adicionais)
- [ ] Criar rotas CRUD para perfis de clientes
- [ ] Adicionar aba "Perfil do Cliente" na página administrativa
- [ ] Implementar formulário de edição de perfil do cliente
- [ ] Separar seções Cliente e Admin na sidebar do DashboardLayout

## Campos de Perfil Estendido e Verificação de Email
- [x] Adicionar campos de endereço ao schema users (addressLine1, addressLine2, city, state, postalCode, country)
- [x] Adicionar campo dateOfBirth ao schema users
- [x] Adicionar campo emailVerified ao schema users
- [x] Criar tabela email_verification_tokens
- [x] Atualizar rotas tRPC de registro para suportar novos campos
- [x] Implementar helper de envio de email de verificação
- [x] Criar rota de verificação de email (auth.verifyEmail)
- [ ] Criar página de verificação de email (/verify-email)
- [x] Atualizar formulário de registro com campos de endereço
- [x] Adicionar campo de data de nascimento no formulário
- [x] Adicionar validação de campos obrigatórios no frontend
- [ ] Integrar envio de email de verificação após registro
- [ ] Testar fluxo completo de registro com verificação de email

## Correções de UX
- [x] Corrigir erro ao clicar em "Esqueci a senha" quando Resend não está configurado
- [x] Garantir visibilidade do botão "Sair" na sidebar (já existe no dropdown do avatar)

## Página de Verificação de Email
- [x] Criar página VerifyEmail.tsx
- [x] Adicionar rota /verify-email no App.tsx
- [x] Implementar processamento de token via query parameter
- [x] Mostrar feedback visual de sucesso/erro
- [x] Redirecionar para login após verificação bem-sucedida

## Página de Reenvio de Verificação de Email
- [x] Criar rota backend resendVerificationEmail no routers.ts
- [x] Criar página ResendVerification.tsx
- [x] Adicionar rota /resend-verification no App.tsx
- [x] Implementar formulário com campo de email
- [x] Mostrar feedback de sucesso/erro
- [x] Adicionar link na página de login para reenvio

## Correção de Atualização Automática de Entradas
- [x] Investigar página Entradas.tsx para identificar problema de atualização
- [x] Implementar invalidação de cache após criar entrada (com parâmetros corretos)
- [x] Implementar invalidação de cache após editar entrada (com parâmetros corretos)
- [x] Implementar invalidação de cache após deletar entrada (com parâmetros corretos)
- [x] Investigar por que entradas criadas não aparecem na lista
- [x] Verificar rota backend de criação de entradas (encontrado: userId não era passado)
- [x] Adicionar parâmetro userId na rota create do backend
- [x] Passar userId no frontend quando admin cria entrada para cliente
- [x] Implementar correção definitiva

## Correção do Comparador de Passagens
- [ ] Investigar página ComparadorPassagens.tsx
- [ ] Corrigir URL do Google Voos com parâmetros corretos
- [ ] Corrigir URLs dos demais sites (Kayak, Skyscanner, etc.)
- [ ] Testar preenchimento automático em todos os sites

## Correção Urgente - Erro ao Criar Novo Usuário
- [ ] Investigar erro "Email ou senha inválidos" no registro
- [ ] Verificar rota de registro
- [ ] Corrigir problema identificado
- [ ] Testar registro de novo usuário

## Correção Urgente - Entradas Não Sendo Criadas
- [x] Verificar logs do servidor para identificar erro
- [x] Verificar rota backend de criação
- [x] Verificar função createIncome no db.ts
- [x] Adicionar logging e validação na rota create
- [x] Identificar problema: apenas admins conseguem criar, clientes não
- [ ] Verificar permissões da rota incomes.create
- [ ] Corrigir problema de permissão
- [ ] Testar criação com usuário normal (não admin)

## Correção de Recuperação de Senha sem Resend
- [x] Modificar rota requestPasswordReset para retornar link quando email não configurado
- [x] Atualizar página ForgotPassword.tsx para mostrar link de recuperação
- [x] Adicionar botão "Copiar Link" para facilitar uso
- [x] Corrigir URL do link para usar servidor correto
- [x] Testar fluxo completo de recuperação de senha - FUNCIONANDO

## Debug - Problema de Criação de Entradas para Usuários Normais
- [ ] Verificar logs quando usuário normal tenta criar entrada
- [ ] Verificar se cookie de sessão está sendo enviado corretamente
- [ ] Verificar se ctx.user.id está definido para usuários normais
- [ ] Corrigir problema identificado

## Correção de Filtro de Mês (Dezembro/Mês 12)
- [x] Investigar lógica de filtro de mês em Entradas.tsx
- [x] Corrigir comparação de datas no filtro usando toISOString()
- [x] Aplicar mesma correção em Gastos.tsx
- [x] Aplicar mesma correção em ContasPagar.tsx
- [ ] Testar criação e visualização de entradas em dezembro

## Correção - Admin não vê transações individuais do cliente
- [x] Investigar por que totais aparecem mas lista de transações fica vazia
- [x] Verificar query backend de listagem de entradas/gastos (backend correto)
- [x] Identificar problema: quando admin não seleciona cliente, mostra dados vazios do próprio admin
- [x] Adicionar mensagem "Selecione um cliente" em Entradas.tsx
- [x] Adicionar mensagem "Selecione um cliente" em Gastos.tsx
- [x] Adicionar mensagem "Selecione um cliente" em ContasPagar.tsx
- [x] Testar como admin selecionando cliente específico
- [ ] Problema persiste: transações não aparecem mesmo após selecionar cliente
- [ ] Verificar logs do servidor quando admin seleciona cliente
- [ ] Identificar por que query não retorna dados do cliente
- [ ] Corrigir problema de carregamento

## Filtro de Mês na Visão Geral
- [ ] Adicionar seletor de mês na página Home/Visão Geral
- [ ] Filtrar entradas por mês selecionado
- [ ] Filtrar gastos por mês selecionado
- [ ] Atualizar cards de resumo (Total Entradas, Total Gastos, Saldo) com dados do mês
- [ ] Atualizar gráficos com dados do mês selecionado

## Correção URGENTE - Filtro de Mês Impedindo Visualização de Transações
- [x] Remover filtro automático por mês (mostrar TODAS as transações por padrão)
- [x] Adicionar opção "Todos os meses" no seletor de mês (campo vazio = todos)
- [x] Aplicar correção em Gastos (Pessoal)
- [x] Aplicar correção em Entradas (Pessoal)
- [x] Aplicar correção em Contas a Pagar (Pessoal)
- [x] Aplicar correção em Despesas (Negócio)
- [x] Aplicar correção em Faturamento (Negócio)
- [x] Aplicar correção em Contas a Pagar (Negócio)
- [x] Aplicar correção na Visão Geral
- [x] Testar criação e visualização de transações em qualquer mês

## Adicionar Seletor de Mês Visível na Visão Geral
- [x] Adicionar campo input type="month" na seção de filtros da Visão Geral
- [x] Posicionar seletor de forma visível e acessível
- [x] Adicionar botão "Limpar filtro" quando mês está selecionado
- [x] Testar filtro de mês na Visão Geral

## Reorganizar Visão Geral por Mês
- [x] Agrupar transações por mês (Novembro, Dezembro, etc)
- [x] Criar accordion com seção para cada mês
- [x] Mostrar totais de entradas, gastos e saldo por mês
- [x] Ordenar meses do mais recente para o mais antigo
- [x] Funcionar para admin e cliente
- [x] Exibir resumo no header do accordion (entradas, gastos, saldo)
- [x] Testar visualização completa

## Adicionar Dropdown de Seleção de Mês na Visão Geral
- [x] Criar dropdown (Select) com lista de meses disponíveis
- [x] Adicionar opção "Todos os meses" no dropdown
- [x] Filtrar dados do accordion baseado no mês selecionado
- [x] Funcionar para admin e cliente
- [x] Testar seleção de mês específico e "Todos"

## Corrigir Erro SelectItem Value Vazio
- [x] Substituir value="" por value="all" no SelectItem "Todos os meses"
- [x] Atualizar lógica de filtro para usar "all" em vez de string vazia
- [x] Atualizar estado inicial para "all"
- [x] Testar seleção de "Todos os meses"

## Substituir Inputs Month por Dropdowns e Ajustar Mobile
- [x] Substituir input month por dropdown em Gastos (Pessoal)
- [x] Substituir input month por dropdown em Entradas (Pessoal)
- [x] Substituir input month por dropdown em Contas a Pagar (Pessoal)
- [x] Substituir input month por dropdown em Despesas (Negócio)
- [x] Substituir input month por dropdown em Faturamento (Negócio)
- [x] Substituir input month por dropdown em Contas a Pagar (Negócio)
- [x] Criar lista dinâmica de meses disponíveis com useMemo
- [x] Formatar nomes dos meses em português
- [x] Ordenar meses do mais recente para o mais antigo
- [x] Grid de filtros já responsivo (flex-col sm:flex-row)
- [x] Testar funcionalidade de dropdowns

## Corrigir Responsividade Mobile na Página de Gastos
- [x] Ajustar seção de filtros para empilhar verticalmente em mobile
- [x] Ajustar largura dos selects para w-full em mobile e w-[200px] em desktop
- [x] Grid de cards de estatísticas já responsivo (md:grid-cols-2)
- [x] Adicionar scroll horizontal nas tabelas desktop (overflow-x-auto)
- [x] Cards mobile já implementados para visualização em telas pequenas
- [x] Dropdown de meses atualiza automaticamente quando nova transação é adicionada

## Corrigir Texto Sobreposto no Accordion Mobile
- [x] Investigar causa do texto sobreposto ao valor total
- [x] Ajustar layout do AccordionTrigger para flex-col em mobile e flex-row em desktop
- [x] Adicionar gap-2 e flex-wrap para evitar sobreposição de elementos
- [x] Reduzir tamanho de fonte em mobile (text-base) e manter maior em desktop (text-lg)
- [x] Adicionar whitespace-nowrap no valor monetário
- [x] Testar em diferentes tamanhos de tela mobile

## Sistema de Reconhecimento de Fotos de Notas Fiscais (OCR)
- [x] Adicionar campo `receiptImageUrl` na tabela expenses e incomes
- [x] Executar migração do banco de dados (pnpm db:push)
- [x] Criar helper receiptOCR.ts com processamento via visão do LLM
- [x] Criar procedimento tRPC expenses.processReceipt para upload e processamento
- [x] Implementar extração estruturada com JSON Schema: valor, data, descrição, categoria
- [x] Upload de imagem para S3 com path `receipts/{userId}/{timestamp}`
- [x] Adicionar botão "Escanear Nota Fiscal" no formulário de gastos
- [x] Implementar upload de imagem com validação (tipo e tamanho)
- [x] Preencher automaticamente formulário com dados extraídos
- [x] Mostrar preview da foto anexada
- [x] Loading state durante processamento
- [x] Limpar estado ao resetar formulário

## Correção Definitiva - Sobreposição de Texto no Accordion Mobile
- [x] Investigar código atual do AccordionTrigger em Gastos.tsx
- [x] Ocultar valor monetário do header em mobile (hidden sm:inline)
- [x] Manter valor visível apenas em desktop (sm breakpoint)
- [x] Simplificar layout para flex horizontal sem empilhamento
- [x] Testar em diferentes tamanhos de tela mobile

## Centralizar Conteúdo Mobile e Corrigir Títulos Cortados
- [x] Reduzir tamanho dos títulos principais em mobile (text-2xl sm:text-4xl)
- [x] Ajustar títulos em Gastos (Pessoal)
- [x] Ajustar títulos em Entradas (Pessoal)
- [x] Ajustar títulos em Contas a Pagar (Pessoal)
- [x] Ajustar títulos em Gastos do Negócio
- [x] Ajustar títulos em Faturamento (Negócio)
- [x] Ajustar títulos em Contas a Pagar - Negócio
- [x] Container já possui padding adequado (classe container do Tailwind)

## Corrigir Erro de API em Contas a Pagar do Negócio
- [x] Investigar router businessBills no backend
- [x] Verificar se procedimento tRPC está registrado corretamente no appRouter
- [x] Reiniciar servidor para carregar todas as rotas
- [x] Testar endpoint /negocio/contas-pagar

## Corrigir Sistema de Recuperação de Senha (Email não está sendo enviado)
- [x] Investigar fluxo de "esqueci minha senha" no backend
- [x] Verificar se procedimento tRPC de reset de senha existe (requestPasswordReset)
- [x] Sistema de geração de token já implementado (passwordReset.ts)
- [x] Sistema de envio de email já implementado (email.ts com Resend)
- [x] Problema identificado: RESEND_API_KEY não configurada
- [x] Implementar fallback: notificar owner via Manus quando email falhar
- [x] Retornar mensagem amigável ao usuário
- [x] Página de reset de senha já existe (/reset-password)

## Unificar Página de Entradas (Pessoal + Negócio)
- [x] Analisar estrutura atual da página Entradas.tsx
- [x] Modificar página para buscar dados de incomes E businessIncomes
- [x] Adicionar badge visual para diferenciar "Pessoal" vs "Negócio"
- [x] Unificar cálculo de total (somar ambos os tipos)
- [x] Unificar contador de transações
- [x] Manter filtros de mês funcionando para ambos os tipos
- [x] Testar criação, edição e exclusão de ambos os tipos
- [ ] Aplicar mesma lógica para Gastos e Contas a Pagar (se solicitado)

## Módulo de Operação (Negócios)

### Fase 1: Estrutura de Dados
- [x] Criar tabela `products` (produtos/estoque)
- [x] Criar tabela `employees` (funcionários/vendedores)
- [x] Criar tabela `crm_clients` (clientes CRM)
- [x] Criar tabela `leads` (controle de leads)
- [x] Criar tabela `sales` (vendas/orçamentos)
- [x] Criar tabela `sale_items` (itens da venda)
- [x] Criar tabela `stock_movements` (movimentações de estoque)
- [x] Criar tabela `repurchase_cycles` (ciclos de recompra por produto/serviço)
- [x] Criar tabela `appointments` (agendamentos)
- [x] Criar tabela `client_interactions` (histórico de interações)
- [x] Executar migration (pnpm db:push)

### Fase 2: Procedures tRPC
- [x] CRUD de produtos (create, list, update, delete, alertas de estoque mínimo)
- [x] CRUD de funcionários
- [x] CRUD de clientes CRM
- [x] CRUD de leads
- [ ] CRUD de vendas (com itens múltiplos)
- [ ] CRUD de ciclos de recompra
- [ ] CRUD de agendamentos
- [ ] Procedures de caixa (saldo por conta, fluxo projetado)
- [ ] Procedures de dashboard (KPIs, top vendedores, alertas)

### Fase 3: Páginas - Produtos e Funcionários
- [x] Página Produtos/Estoque com alertas de mínimo
- [x] Página Funcionários/Vendedores

### Fase 4: Sistema de Vendas
- [ ] Página de Vendas com múltiplos itens
- [ ] Fluxo: Orçamento → Aprovado → Pago → Concluído
- [ ] Histórico de vendas por cliente

### Fase 5: CRM e Leads
- [x] Página CRM de Clientes (dados completos, histórico)
- [x] Página de Leads (pipeline, atividades)
- [x] Cálculos automáticos (total gasto, ticket médio, nº compras)

### Fase 6: Caixa da Empresa
- [ ] Página Caixa (saldo por conta + consolidado)
- [ ] Fluxo de caixa projetado

### Fase 7: Agenda Integrada
- [ ] Calendário mensal/semanal/diário
- [ ] Agendamentos vinculados a clientes/serviços/funcionários
- [ ] Sistema de notificações/lembretes

### Fase 8: Dashboard Admin
- [ ] KPIs: taxa conversão, ticket médio, produtos mais vendidos
- [ ] Resultado líquido (negócio vs pessoal)
- [ ] Top 3 vendedores do mês
- [ ] Alertas de reaquecimento (30/60/90/180/360 dias)
- [ ] Atalhos para todas seções

## Dashboard Admin Operacional
- [x] Implementar procedures tRPC para KPIs (taxa conversão, ticket médio, produtos mais vendidos)
- [x] Implementar procedure para resultado líquido (negócio vs pessoal)
- [x] Implementar procedure para ranking de top 3 vendedores
- [x] Implementar procedure para alertas de reaquecimento (30/60/90/180/360 dias)
- [x] Criar página de Dashboard Admin com todas as visualizações
- [x] Adicionar atalhos rápidos para todas as seções
- [x] Integrar com menu de navegação

## Caixa da Empresa
- [x] Implementar procedures tRPC para buscar saldo por conta bancária
- [x] Implementar procedure para saldo consolidado (todas as contas)
- [x] Implementar procedure para fluxo de caixa projetado (entradas/saídas futuras)
- [x] Implementar procedure para histórico de movimentações
- [x] Criar página de Caixa da Empresa com cards de saldo
- [x] Adicionar tabela de fluxo projetado
- [x] Adicionar histórico de movimentações
- [x] Integrar com menu de navegação

## Customização da Página de Login
- [x] Copiar logo da Aurum Assessoria para pasta pública
- [x] Adicionar logo como marca d'água na página de login
- [x] Adicionar texto "Caio Shimamoto" e "Aurum Assessoria"

## Substituir Ícone Padrão pelo Logo Aurum
- [x] Atualizar constante APP_LOGO em client/src/const.ts
- [x] Verificar visualização em todas as páginas

## Aplicar Cores da Marca Aurum
- [x] Identificar cor bege/dourado da logo Aurum
- [x] Substituir cor roxa por bege/dourado no index.css
- [x] Adicionar logo completo na página de login (não apenas marca d'água)
- [x] Verificar consistência visual em todo o sistema

## Correções de Bugs e Ajustes Visuais
- [x] Corrigir duplicação de estilo color no Total de Entradas
- [x] Investigar erro "Email ou senha inválidos" na página Visão Geral
- [x] Aplicar cores personalizadas (verde para entradas, azul para saldo)

## Ajuste de Cores do Saldo Mensal
- [x] Corrigir duplicação de style no saldo mensal da tabela
- [x] Aplicar cor azul claro (#478af5) consistentemente

## Sistema de Vendas Completo
- [x] Implementar procedures tRPC para CRUD de vendas
- [x] Suporte para múltiplos produtos por venda
- [x] Pipeline de status (orçamento → aprovado → pago → concluído)
- [x] Vinculação a clientes CRM e vendedores
- [x] Formas de pagamento (Dinheiro, PIX, Cartão Crédito/Débito, Boleto)
- [x] Criar página frontend de Vendas
- [x] Integração automática com Caixa da Empresa
- [x] Atualização automática dos KPIs do Dashboard
- [x] Adicionar rota e link no menu de navegação

## Ajuste de Cor - Página Notas
- [x] Alterar cor do título "Notas de Encontros" para cinza claro (#f3f2f2)

## Ajuste Visual - Dashboard Admin
- [x] Alterar título para branco (#f3f2f2)
- [x] Aplicar cores variadas nos cards (verde, azul, roxo, laranja, etc.)
- [x] Manter consistência visual com outras páginas

## Ajuste Visual - Dashboard do Negócio
- [x] Aplicar cores variadas nos valores (verde, azul, roxo, etc.)
- [x] Remover cor dourada uniforme
- [x] Manter consistência visual com outras páginas

## Ajuste de Cor - Contas a Pagar Negócio
- [x] Alterar cor do título "Contas a Pagar - Negócio" para cinza claro (#efebeb)

## Ajuste de Cor - Título Planejamento
- [x] Alterar cor do título "Planejamento" para cinza claro (#f3ecec)

## Ajuste de Cor - Títulos Planejamento e Notas de Reuniões
- [x] Corrigir duplicação de propriedade color em Planejamento (#f3ecec)
- [x] Alterar cor do título "Notas de Reuniões" (Negócio) para #f8f1f1

## Ajuste de Cor - Título Planejamento (Negócio)
- [x] Alterar cor do título "Planejamento" (Negócio) para #f7f3f3

## Sistema de Vendas Completo
- [x] Criar rotas tRPC para vendas (criar, listar, atualizar, deletar)
- [x] Implementar suporte a múltiplos produtos por venda
- [x] Adicionar pipeline de status (orçamento, aprovado, pago, concluído)
- [x] Implementar formas de pagamento (Cash, PIX, Cartão Crédito, Cartão Débito, Boleto)
- [x] Vincular vendas a clientes CRM e funcionários/vendedores
- [x] Criar atualização automática de estoque ao finalizar venda
- [x] Integrar vendas com Caixa da Empresa (registrar transações)
- [x] Atualizar Dashboard Admin com dados de vendas
- [x] Criar página frontend de Vendas com formulário de múltiplos produtos
- [x] Adicionar visualização de histórico de vendas
- [x] Implementar filtros por status, cliente, vendedor e período

## Agenda Integrada
- [x] Criar tabela de agendamentos no banco de dados
- [x] Implementar rotas tRPC para agendamentos (CRUD completo)
- [x] Adicionar campos: cliente, serviço/descrição, funcionário, data/hora, status
- [x] Criar visualização de calendário mensal
- [x] Criar visualização de calendário semanal
- [x] Criar visualização de calendário diária
- [x] Implementar criação de agendamentos via modal
- [x] Adicionar edição e exclusão de agendamentos
- [x] Integrar com alertas de reaquecimento de clientes
- [x] Criar notificações para agendamentos próximos
- [x] Adicionar filtro por funcionário e status

## Integração Vendas com Caixa da Empresa
- [x] Analisar estrutura da tabela de transações do Caixa
- [x] Criar registro automático no Caixa quando venda é marcada como "paga"
- [x] Incluir forma de pagamento, data e valor na transação
- [x] Atualizar saldo do Caixa automaticamente
- [x] Testar fluxo completo de venda até registro no Caixa

## Dashboard de Vendas
- [x] Criar rotas tRPC para análises de vendas
- [x] Implementar análise de vendas por período (diário, semanal, mensal, anual)
- [x] Criar análise de produtos mais vendidos
- [x] Implementar análise de performance por vendedor
- [x] Calcular taxa de conversão de orçamentos
- [x] Criar comparação mensal/anual de vendas
- [x] Implementar gráficos interativos (linha, barra, pizza)
- [x] Criar cards de métricas principais (total vendas, ticket médio, conversão)
- [x] Adicionar filtros por período e vendedor
- [x] Criar página frontend do Dashboard de Vendas
- [x] Adicionar rota no menu lateral

## Correções Vendas
- [x] Corrigir dropdown de clientes (não está carregando)
- [x] Adicionar campo de prazo de recebimento (30/60/90 dias)
- [x] Atualizar schema do banco se necessário
- [x] Testar criação de venda com prazo

## Integração Vendas com Lançamentos Futuros
- [x] Analisar estrutura de lançamentos futuros no sistema
- [x] Criar lançamento futuro automático quando venda tem prazo (30/60/90 dias)
- [x] Calcular data de recebimento baseada no prazo
- [x] Vincular lançamento futuro à venda original
- [x] Atualizar lançamento quando status da venda mudar
- [x] Testar criação de venda com prazo e verificar lançamento futuro

## Correção UX - Scroll Automático
- [x] Remover scroll automático ao clicar em itens do menu
- [x] Manter posição da página ao navegar entre seções
- [x] Testar navegação em diferentes páginas

## Correção Completa - Scroll Automático Persistente
- [x] Investigar causa do scroll que ainda acontece para seções mais abaixo
- [x] Implementar solução robusta que previne 100% do scroll automático
- [x] Testar navegação em todas as seções do menu
- [x] Garantir que scroll só acontece manualmente

## Melhorias em Vendas e Contas a Receber
- [x] Adicionar coluna de Prazo na tabela de vendas
- [x] Criar badges coloridos para prazo (À Vista, 30/60/90 dias)
- [x] Criar página de Contas a Receber
- [x] Implementar listagem de vendas a prazo pendentes
- [x] Adicionar cálculo de data prevista de recebimento
- [x] Criar alertas visuais para recebimentos vencidos
- [x] Implementar filtros por período em Contas a Receber
- [x] Adicionar filtros avançados na página de Vendas
- [x] Implementar filtro por período (hoje, semana, mês, personalizado)
- [x] Adicionar filtro por status
- [x] Adicionar filtro por forma de pagamento
- [x] Adicionar filtro por prazo de recebimento
- [x] Adicionar filtro por cliente

## Correções Urgentes - Vendas
- [x] Corrigir erro saleId NaN ao criar venda
- [x] Corrigir erro de Select.Item com value vazio
- [x] Adicionar campo customizado quando selecionar "Outros" em forma de pagamento
- [x] Testar criação de venda completa

## Correção Urgente - Página de Gastos
- [x] Corrigir erro de Select.Item com value vazio na página de Gastos
- [x] Testar criação e edição de gastos

## Correção URGENTE - Select.Item ainda com erro
- [x] Encontrar e corrigir TODOS os Select.Item com value vazio em BusinessGastos
- [x] Testar página completamente

## Campo Customizado em Categoria "Outros"
- [x] Adicionar campo customizado em BusinessGastos quando "Outros" for selecionado
- [x] Adicionar campo customizado em Gastos pessoal quando "Outros" for selecionado
- [x] Testar criação de despesas com categoria customizada

## Correção - Dropdown de Clientes em Agendamentos
- [x] Corrigir query de clientes em página de Agenda
- [x] Testar carregamento de clientes

## Sistema de Autenticação Tradicional com Recuperação de Senha
- [ ] Atualizar schema com campos de autenticação (passwordHash, resetToken, etc)
- [ ] Aplicar migração no banco de dados
- [ ] Implementar funções de hash de senha (bcrypt)
- [ ] Criar rotas de registro (signup)
- [ ] Criar rotas de login tradicional
- [ ] Criar rotas de recuperação de senha (request + reset)
- [ ] Implementar sistema de envio de emails
- [x] Criar página de Login/Registro
- [x] Criar página de Recuperação de Senha
- [x] Criar página de Reset de Senha
- [ ] Testar fluxo completo

## Correção - Link de Recuperação
- [x] Investigar por que resetLink não está sendo retornado
- [x] Corrigir backend para retornar resetLink em modo desenvolvimento
- [x] Testar fluxo completo de recuperação de senha

## Correções de Métricas
- [x] Corrigir cálculo do Ticket Médio no Dashboard do Negócio (usar vendas reais ao invés de business_metrics)
- [x] Implementar atualização automática de métricas CRM quando vendas são criadas/atualizadas
- [x] Criar função para recalcular métricas de todos os clientes CRM baseado em vendas existentes
