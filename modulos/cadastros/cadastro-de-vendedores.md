# 👤 Cadastro de Vendedores

🏠 [Home](../../index.md) > 📋 [Módulos](../index.md) > 👥 [Cadastros](index.md) > **Vendedores**

#cadastros #vendedores #equipe #comissao #metas #passo-a-passo #iniciante

---

## 📋 O que é

O **Cadastro de Vendedores** é onde você gerencia sua equipe de vendas, definindo comissões, metas e permissões. Este cadastro é essencial para:

- **Controle de Vendas** - Identificar vendedor responsável por cada venda
- **Cálculo de Comissões** - Comissões automáticas por vendas realizadas
- **Metas de Vendas** - Definir e acompanhar metas individuais e de equipe
- **Relatórios de Performance** - Análises de desempenho por vendedor
- **Controle de Acesso** - Permissões específicas no sistema
- **Gestão de Equipe** - Organização da estrutura comercial

---

## 🚀 Como Fazer

### 📋 Passo 1: Acessar o Módulo
1. No menu principal, clique em **"Cadastros"**
2. Selecione **"Vendedores"**
3. Clique no botão **+ Adicionar Vendedor"** 

### 👤 Passo 2: Dados Pessoais

#### **Informações Básicas**
- **Nome Completo**: Nome do vendedor
- **Tipo da comissão**: Definir se é fixa ou variada por produto/categoria
- **Statu**: Cadastro de vendedor ativo ou inativo
- **Percentual máximo de desconto**: Definir em % o permitido para desconto em vendas
- **Valor máximo de desconto** Caso queira definir o limite de desconto em valor "R$"
- **R$ Meta**: Configurar um valor em meta de vendas, para analisar performance

---

{% hint style="info" %}
**💡 Dica**: Mantenha os dados de contato sempre atualizados para facilitar a comunicação com a equipe.
{% endhint %}

#### **Comissões**
- **Fixa**: Definir se será em % ou R$ e qual o valor.
- **Variadas**: Configurar o "Conjunto de Regras" nas prefêrencias do sistema. 
Menu Configurações > Preferências > Preferências do Vendedor > + Adicionar Regras

---

{% hint style="warning" %}
**⚠️ Atenção**: As comissões são calculadas automaticamente no fechamento das vendas. Verifique se as configurações estão corretas antes de finalizar.
{% endhint %}

## 🔐 Permissões e Acesso

### 👥 **Níveis de Acesso**
- **Vendedor Básico**: Apenas vendas e consultas
- **Vendedor Pleno**: Vendas + relatórios básicos
- **Supervisor de Vendas**: Gestão de equipe + relatórios avançados
- **Gerente Comercial**: Acesso total ao módulo comercial

### 🔧 **Configurações de Permissão**
- **Acesso ao PDV**: Pode utilizar o ponto de venda
- **Consulta Produtos**: Visualizar catálogo e preços
- **Aplicar Descontos**: Limite de desconto permitido
- **Cadastrar Clientes**: Permissão para novos cadastros
- **Relatórios**: Quais relatórios pode acessar

{% hint style="success" %}
**✅ Boa Prática**: Configure permissões específicas por função para manter a segurança e organização do sistema.
{% endhint %}

---

## 📊 Funcionalidades Avançadas

### 🎯 **Gestão de Territórios**
- **Clientes por Vendedor**: Vincular clientes a vendedores responsáveis


### 📈 **Acompanhamento de Performance**
- **Dashboard Individual**: Métricas pessoais de cada vendedor
- **Ranking de Vendas**: Comparativo de performance da equipe
- **Histórico de Vendas**: Todas as vendas realizadas
- **Comissões Calculadas**: Valores a receber automaticamente

### 🔄 **Hierarquia de Vendas**
- **Vendedor Responsável**: Definir supervisor/gerente
- **Estrutura de Equipe**: Organizar hierarquia comercial
- **Comissões Hierárquicas**: Repasse para supervisores
- **Substituições**: Cobrir vendedores em férias/afastamentos

---

## 💡 Casos de Uso

### 🎯 **Cenário 1: Loja de Roupas**
**Situação**: Loja com 3 vendedores e comissão por categoria
- **Vendedor A**: Especialista em roupas femininas (5% comissão)
- **Vendedor B**: Especialista em roupas masculinas (4% comissão)
- **Vendedor C**: Vendedor geral (3% comissão)
- **Meta**: R$ 10.000/mês cada vendedor

### 🔧 **Cenário 2: Prestação de Serviços**
**Situação**: Vendedores técnicos especializados
- **Vendedor Técnico**: Comissão de R$ 200 por serviço fechado
- **Supervisor**: 1% sobre vendas da equipe
- **Meta**: 20 serviços/mês por vendedor
- **Bonificação**: R$ 500 extra por atingir meta

---

## 🔍 Busca e Filtros

### 🔎 **Localizar Vendedores**
- **Por Nome**: Busca direta pelo nome
- **Por Status**: Ativo, inativo
- **Por Performance**: Vendedores acima/abaixo da meta

### 📊 **Filtros Avançados**
- **Faixa de Comissão**: Vendedores por % comissão
- **Nível de Acesso**: Por permissões no sistema
- **Meta Atingida**: Quem está cumprindo objetivos

---

## 📊 Relatórios Disponíveis

### 📈 **Relatórios de Performance**
- **Vendas por Vendedor**: Performance individual detalhada
- **Ranking de Vendas**: Comparativo de toda equipe
- **Acompanhamento de Metas**: % atingido por cada vendedor
- **Comissões Calculadas**: Valores a pagar por período

### 💰 **Relatórios Financeiros**
- **Resumo de Comissões**: Total a pagar por mês
- **Histórico de Pagamentos**: Comissões já pagas

### 🎯 **Relatórios Gerenciais**
- **Performance da Equipe**: Visão geral do time
- **Evolução de Vendas**: Crescimento por vendedor
- **Dashboard Comercial**: Métricas consolidadas

---

## 🚨 Validações


### ✅ **Validações do Sistema**
- **CPF Único**: Não permite vendedores duplicados
- **Comissão Válida**: Percentuais entre 0% e 20%
- **Meta Realista**: Valores coerentes com histórico
- **Hierarquia**: Evita loops na estrutura de equipe

---

## 🔐 Permissões e Segurança

### 👤 **Quem Pode Acessar**
- **Administrador**: Acesso total a todos vendedores
- **Gerente Comercial**: Gestão da equipe comercial
- **Supervisor**: Apenas vendedores da sua equipe
- **RH**: Dados pessoais e contratuais
- **Financeiro**: Comissões e relatórios financeiros

### 🔒 **Controles de Segurança**
- **Senha Individual**: Cada vendedor tem login próprio
- **Bloqueio Automático**: Inativação por período sem uso

---

## 💡 Dicas e Boas Práticas

### ✅ **Para Configuração**
- **Defina metas realistas** baseadas no histórico de vendas
- **Configure comissões justas** para motivar a equipe
- **Mantenha dados atualizados** para comunicação eficaz

### 📊 **Para Gestão**
- **Acompanhe metas mensalmente** e forneça feedback
- **Analise performance** individual e da equipe
- **Pague comissões em dia** para manter motivação
- **Ajuste configurações** conforme necessário

### 🎯 **Para Motivação**
- **Crie rankings visuais** para estimular competição saudável
- **Estabeleça premiações** por atingir metas
- **Ofereça treinamentos** para vendedores com baixa performance
- **Reconheça publicamente** os melhores resultados

---

## 🚨 Pontos de Atenção

### ⚠️ **Configuração de Comissões**
- **Teste os cálculos** antes de implementar novas regras
- **Documente as regras** para transparência com a equipe
- **Considere sazonalidade** ao definir metas
- **Revise periodicamente** as configurações

### 🔍 **Controle de Acesso**
- **Limite permissões** ao necessário para cada função
- **Monitore acessos** e atividades suspeitas
- **Treine a equipe** sobre uso correto do sistema
- **Mantenha senhas seguras** e atualizadas

---

## 📚 Documentação Relacionada

- [Cadastro de Clientes](cadastro-de-clientes.md) - Para entender relacionamento vendedor-cliente
- [PDV - Ponto de Venda](../vendas/pdv.md) - Como vendedores usam o sistema de vendas
- [Relatórios de Vendas](../relatorios/index.md) - Análises de performance da equipe
- [Gestão de Usuários](../configuracoes/usuarios-e-permissoes.md) - Configuração de acessos
- [Comissões e Pagamentos](../financeiro/index.md) - Processamento de comissões

---

## 🏷️ Tags
`#cadastros` `#vendedores` `#equipe` `#comissao` `#metas` `#performance` `#territorial` `#hierarquia`

---

**Última atualização**: Setembro 2025  
**Versão do documento**: 1.0  
**Responsável**: Equipe de Documentação White ERP
