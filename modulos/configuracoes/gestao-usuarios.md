# 👥 Gestão de Usuários e Permissões

🏠 [Home](../../../index.md) > 📋 [Módulos](../../index.md) > ⚙️ [Configurações](../index.md) > **Gestão de Usuários**

#configuracoes #usuarios #permissoes #seguranca #controle-acesso #auditoria

## 🎯 Visão Geral

A **Gestão de Usuários e Permissões** é fundamental para garantir segurança, controle e organização no ERP GerenciaTech. Este módulo permite criar usuários, definir perfis de acesso, controlar permissões específicas e monitorar atividades, garantindo que cada pessoa tenha acesso apenas ao que precisa para executar suas funções.

## 🔐 Conceitos Fundamentais

### **Usuário**
- Pessoa que acessa o sistema
- Possui login e senha únicos
- Vinculado a um ou mais perfis
- Pode ter permissões específicas

### **Perfil de Acesso**
- Conjunto de permissões pré-definidas
- Baseado em função/cargo
- Pode ser atribuído a múltiplos usuários
- Facilita gestão de permissões

### **Permissão**
- Direito específico no sistema
- Pode ser por módulo, funcionalidade ou ação
- Granularidade detalhada
- Controle fino de acesso

## 👤 Criação de Usuários

### **Passo a Passo**

#### 1. **Acessar Gestão de Usuários**
1. **Menu**: Configurações > Usuários e Permissões
2. **Botão**: "Novo Usuário"
3. **Formulário**: Preencher dados básicos

#### 2. **Dados Básicos**
```
Nome Completo: João Silva Santos
Email: joao.silva@empresa.com
Login: joao.silva
Senha: [Gerada automaticamente ou definida]
Confirmar Senha: [Repetir senha]
```

#### 3. **Informações Complementares**
- **CPF**: Para identificação única
- **Telefone**: Para contato e 2FA
- **Cargo**: Função na empresa
- **Departamento**: Área de atuação
- **Data de Admissão**: Para controle
- **Status**: Ativo/Inativo

#### 4. **Definir Perfis**
- **Perfil Principal**: Perfil base do usuário
- **Perfis Adicionais**: Perfis complementares
- **Permissões Específicas**: Ajustes pontuais

#### 5. **Configurações de Segurança**
- **Autenticação 2FA**: Ativar/desativar
- **Alterar Senha**: Forçar na primeira conexão
- **Validade da Senha**: Período de expiração
- **Tentativas de Login**: Limite de tentativas

## 🛡️ Perfis de Acesso

### **Perfis Pré-definidos**

#### 1. **👑 Administrador**
**Descrição**: Acesso total ao sistema
**Responsabilidades**: Configuração e gestão geral

**Permissões**:
- ✅ Todos os módulos
- ✅ Configurações do sistema
- ✅ Gestão de usuários
- ✅ Relatórios financeiros
- ✅ Backup e restauração
- ✅ Logs de auditoria

#### 2. **👨‍💼 Gerente**
**Descrição**: Gestão operacional e relatórios
**Responsabilidades**: Supervisão e análise

**Permissões**:
- ✅ Vendas e relatórios
- ✅ Estoque e compras
- ✅ Financeiro (consulta)
- ✅ Cadastros básicos
- ✅ Aprovação de descontos
- ❌ Configurações críticas

#### 3. **💰 Vendedor**
**Descrição**: Foco em vendas e atendimento
**Responsabilidades**: Vendas e relacionamento

**Permissões**:
- ✅ PDV e vendas
- ✅ Cadastro de clientes
- ✅ Consulta de estoque
- ✅ Orçamentos e pedidos
- ✅ Relatórios de vendas
- ❌ Dados financeiros

#### 4. **💳 Operador de Caixa**
**Descrição**: Operação do PDV
**Responsabilidades**: Vendas no balcão

**Permissões**:
- ✅ PDV básico
- ✅ Sangria e reforço
- ✅ Fechamento de caixa
- ✅ Consulta de produtos
- ❌ Descontos acima de 5%
- ❌ Cancelamento de vendas

#### 5. **📊 Financeiro**
**Descrição**: Gestão financeira
**Responsabilidades**: Contas e fluxo de caixa

**Permissões**:
- ✅ Contas a receber/pagar
- ✅ Fluxo de caixa
- ✅ Conciliação bancária
- ✅ Relatórios financeiros
- ✅ Emissão de boletos
- ❌ Configurações fiscais

#### 6. **📦 Estoquista**
**Descrição**: Controle de estoque
**Responsabilidades**: Movimentação e inventário

**Permissões**:
- ✅ Entrada de mercadorias
- ✅ Movimentação de estoque
- ✅ Inventário físico
- ✅ Relatórios de estoque
- ✅ Transferências
- ❌ Alteração de preços

## 🔧 Configuração de Permissões

### **Estrutura de Permissões**

#### **Por Módulo**
```
Cadastros:
├── Clientes: Criar, Editar, Visualizar, Excluir
├── Produtos: Criar, Editar, Visualizar, Excluir
├── Fornecedores: Criar, Editar, Visualizar, Excluir
└── Funcionários: Criar, Editar, Visualizar, Excluir

Vendas:
├── PDV: Acessar, Descontos, Cancelar
├── Orçamentos: Criar, Editar, Aprovar
├── Pedidos: Criar, Editar, Faturar
└── Relatórios: Visualizar, Exportar

Financeiro:
├── Contas a Receber: Criar, Editar, Baixar
├── Contas a Pagar: Criar, Editar, Pagar
├── Fluxo de Caixa: Visualizar, Projetar
└── Relatórios: Visualizar, Exportar
```

#### **Por Ação**
- **Criar**: Cadastrar novos registros
- **Editar**: Modificar registros existentes
- **Visualizar**: Consultar informações
- **Excluir**: Remover registros
- **Aprovar**: Aprovar operações
- **Exportar**: Exportar dados

### **Configuração Granular**

#### **Exemplo: Vendedor**
```
Módulo Vendas:
✅ PDV: Acessar, Vendas até R$ 5.000
✅ Descontos: Até 10%
❌ Cancelamento: Vendas acima de R$ 500
✅ Orçamentos: Criar, Editar
❌ Orçamentos: Aprovar

Módulo Cadastros:
✅ Clientes: Criar, Editar, Visualizar
❌ Clientes: Excluir
✅ Produtos: Visualizar
❌ Produtos: Criar, Editar, Excluir

Módulo Financeiro:
✅ Consultar: Contas a receber
❌ Baixar: Contas a receber
❌ Acessar: Contas a pagar
```

## 🔍 Monitoramento e Auditoria

### **Log de Atividades**

#### **Informações Registradas**
- **Usuário**: Quem executou a ação
- **Data/Hora**: Quando foi executada
- **Ação**: O que foi feito
- **Módulo**: Onde foi executada
- **IP**: De onde foi executada
- **Resultado**: Sucesso ou erro

#### **Exemplo de Log**
```
[2024-01-15 14:30:25] João Silva (joao.silva)
Ação: Criação de cliente
Módulo: Cadastros > Clientes
IP: 192.168.1.100
Resultado: Sucesso
Detalhes: Cliente "Maria Santos" criado com ID 1234
```

### **Relatórios de Auditoria**

#### **Relatório de Acessos**
- **Usuários ativos**: Últimos 30 dias
- **Horários de acesso**: Padrões de uso
- **Módulos mais acessados**: Por usuário
- **Tentativas de acesso**: Sucessos e falhas

#### **Relatório de Ações**
- **Ações por usuário**: Quantidade e tipo
- **Ações críticas**: Exclusões, alterações importantes
- **Ações não autorizadas**: Tentativas bloqueadas
- **Padrões suspeitos**: Análise de comportamento

## 🔒 Segurança Avançada

### **Autenticação 2FA**

#### **Configuração**
1. **Ativar 2FA**: Por usuário ou globalmente
2. **Método**: SMS, email ou app autenticador
3. **Backup Codes**: Códigos de emergência
4. **Validade**: Tempo de expiração

#### **Fluxo de Login com 2FA**
1. **Usuário**: Insere login e senha
2. **Sistema**: Valida credenciais
3. **Sistema**: Envia código 2FA
4. **Usuário**: Insere código recebido
5. **Sistema**: Valida código e autoriza acesso

### **Políticas de Senha**

#### **Configurações**
```
Tamanho Mínimo: 8 caracteres
Complexidade: Maiúscula + Minúscula + Número + Símbolo
Histórico: Não repetir últimas 5 senhas
Validade: 90 dias
Tentativas: Máximo 3 tentativas
Bloqueio: 30 minutos após tentativas esgotadas
```

### **Controle de Sessão**

#### **Configurações**
- **Timeout**: Tempo de inatividade
- **Sessão Única**: Um login por usuário
- **Controle de IP**: Restringir por IP
- **Horário de Acesso**: Permitir apenas em horários específicos

## 📊 Dashboard de Usuários

### **Métricas Principais**
- **Usuários Ativos**: Últimos 30 dias
- **Novos Usuários**: Criados no mês
- **Logins Hoje**: Acessos do dia
- **Sessões Ativas**: Usuários conectados

### **Gráficos e Análises**
- **Acessos por Hora**: Padrão de uso
- **Módulos Mais Usados**: Por usuário
- **Tentativas de Acesso**: Sucessos vs falhas
- **Distribuição de Perfis**: Quantidade por perfil

## 🚨 Alertas e Notificações

### **Alertas de Segurança**
- **Tentativas de Login**: Múltiplas tentativas falhadas
- **Acesso Suspeito**: Horários ou IPs incomuns
- **Ações Críticas**: Exclusões ou alterações importantes
- **Sessões Longas**: Sessões muito longas

### **Notificações Automáticas**
- **Novo Usuário**: Criação de conta
- **Alteração de Perfil**: Mudanças de permissão
- **Senha Expirada**: Lembrete de renovação
- **Bloqueio de Usuário**: Tentativas excessivas

## 🔧 Configuração Avançada

### **Integração LDAP/AD**

#### **Configuração**
```
Servidor LDAP: ldap.empresa.com
Porta: 389 (ou 636 para SSL)
Base DN: DC=empresa,DC=com
Usuário de Bind: admin@empresa.com
Senha: [senha do usuário bind]
```

#### **Mapeamento de Campos**
```
Nome: displayName
Email: mail
Login: sAMAccountName
Departamento: department
Cargo: title
```

### **Single Sign-On (SSO)**

#### **Configuração SAML**
- **Identity Provider**: Configurar IdP
- **Service Provider**: Configurar SP
- **Certificados**: Trocar certificados
- **Mapeamento**: Mapear atributos

## 💡 Boas Práticas

### ✅ **Segurança**
- **Princípio do Menor Privilégio**: Dar apenas permissões necessárias
- **Revisão Regular**: Revisar permissões periodicamente
- **Senhas Fortes**: Exigir senhas complexas
- **2FA Obrigatório**: Para usuários críticos
- **Monitoramento**: Acompanhar logs regularmente

### ✅ **Gestão**
- **Perfis Padronizados**: Usar perfis ao invés de permissões individuais
- **Documentação**: Documentar perfis e permissões
- **Treinamento**: Treinar usuários sobre segurança
- **Backup**: Fazer backup das configurações
- **Teste**: Testar permissões após alterações

## 🆘 Troubleshooting

### **Problema: Usuário não consegue acessar**
**Soluções**:
1. Verificar se usuário está ativo
2. Confirmar login e senha
3. Verificar se não está bloqueado
4. Validar permissões do perfil

### **Problema: Permissão negada**
**Soluções**:
1. Verificar perfil do usuário
2. Conferir permissões específicas
3. Verificar se módulo está ativo
4. Consultar logs de auditoria

### **Problema: 2FA não funciona**
**Soluções**:
1. Verificar configuração do 2FA
2. Confirmar número de telefone/email
3. Usar códigos de backup
4. Resetar configuração 2FA

## 📋 Checklist de Implementação

### **Configuração Inicial**
- [ ] Definir perfis de acesso
- [ ] Criar usuários básicos
- [ ] Configurar políticas de senha
- [ ] Ativar logs de auditoria
- [ ] Testar permissões

### **Segurança Avançada**
- [ ] Configurar 2FA
- [ ] Definir controle de sessão
- [ ] Configurar alertas
- [ ] Implementar backup
- [ ] Treinar usuários

### **Monitoramento**
- [ ] Configurar dashboard
- [ ] Definir relatórios
- [ ] Configurar alertas
- [ ] Agendar revisões
- [ ] Documentar processos

---

**🔒 Segurança**: A gestão adequada de usuários e permissões é fundamental para proteger os dados da empresa e garantir compliance com regulamentações.

**🎯 Objetivo**: Criar um ambiente seguro e controlado, onde cada usuário tem acesso apenas ao que precisa para executar suas funções de forma eficiente.

**📞 Suporte**: Para configurações avançadas de segurança ou integração com sistemas corporativos, entre em contato com nossa equipe técnica especializada. 