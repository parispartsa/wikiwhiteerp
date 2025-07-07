# Plano de Contas - Estrutura Contábil

🏠 [Home](../../../index.md) > 📋 [Módulos](../../index.md) > 📊 [Contabilidade](index.md) > **Plano de Contas**

#contabilidade #plano-contas #contas-sinteticas #contas-analiticas #estrutura

## 🎯 O que é o Plano de Contas

O **Plano de Contas** é a estrutura fundamental da contabilidade que organiza todas as contas contábeis da empresa de forma hierárquica e sistemática. No ERP White, ele é composto por **Categorias DRE**, **Contas Sintéticas** e **Contas Analíticas**, permitindo uma classificação precisa e automática dos lançamentos contábeis.

### 🚀 Principais Benefícios
- **Estrutura Hierárquica**: Organização clara e lógica das contas
- **Classificação Automática**: Vinculação automática com lançamentos financeiros
- **Flexibilidade**: Adaptável a diferentes tipos de negócio
- **Integração Total**: Conexão direta com módulo financeiro

## 🏗️ Estrutura Hierárquica

### 📊 **Níveis da Estrutura**

#### **Nível 1: Categorias DRE**
As categorias DRE são os agrupamentos principais que definem a estrutura do Demonstrativo de Resultado do Exercício:

**Categorias de Receita:**
- **Receita Operacional Bruta**: Vendas de produtos e serviços
- **Outras Receitas**: Receitas não operacionais

**Categorias de Despesa:**
- **Deduções da Receita Bruta**: Impostos, devoluções, descontos
- **Custos**: Custo dos produtos vendidos e serviços prestados
- **Despesas Operacionais**: Despesas administrativas e comerciais
- **Outras Despesas**: Despesas não operacionais
- **Impostos IR/CSLL**: Imposto de renda e contribuição social

#### **Nível 2: Contas Sintéticas** (Opcional)
Agrupamentos intermediários que facilitam a organização:
- Contas totalizadoras que não recebem lançamentos diretos
- Utilizadas para criar subgrupos dentro das categorias
- Facilitam relatórios consolidados

#### **Nível 3: Contas Analíticas**
Contas de movimentação que recebem os lançamentos efetivos:
- Vinculadas diretamente aos títulos financeiros
- Recebem os lançamentos automáticos do sistema
- Base para todos os relatórios detalhados

## 🔧 Como configurar o Plano de Contas

### **Passo 1: Categorias DRE**

#### **Configurar Categorias de Receita**
1. Acesse **Contabilidade** > **Categorias DRE**
2. Clique em **"Adicionar Categoria"**
3. **Tipo**: Selecione "Receita"
4. **Descrição**: Nome da categoria (ex: "Receita Operacional Bruta")
5. Salve a categoria

#### **Configurar Categorias de Despesa**
1. Acesse **Contabilidade** > **Categorias DRE**
2. Clique em **"Adicionar Categoria"**
3. **Tipo**: Selecione "Despesa"
4. **Descrição**: Nome da categoria (ex: "Despesas Operacionais")
5. Salve a categoria

### **Passo 2: Contas Sintéticas** (Opcional)

#### **Criar Conta Sintética**
1. Acesse **Contabilidade** > **Contas Sintéticas**
2. Clique em **"Adicionar Conta Sintética"**
3. **Descrição**: Nome da conta (ex: "Vendas")
4. **Classificação**: Código de classificação
5. **Tipo**: Receita ou Despesa
6. **Nível Superior**: Selecione a categoria DRE
7. Salve a conta

### **Passo 3: Contas Analíticas**

#### **Criar Conta Analítica**
1. Acesse **Contabilidade** > **Contas Analíticas**
2. Clique em **"Adicionar Conta Analítica"**
3. **Descrição**: Nome específico da conta (ex: "Vendas de Produtos")
4. **Categoria DRE**: Selecione a categoria apropriada
5. **Nível Anterior**: Selecione a conta sintética (se houver)
6. Salve a conta

## 📋 Exemplo Prático de Estrutura

### 🏢 **Empresa Comercial - Estrutura Completa**

```
📊 RECEITAS
├── Receita Operacional Bruta
│   ├── Vendas de Produtos
│   │   ├── Vendas à Vista
│   │   ├── Vendas a Prazo
│   │   └── Vendas Online
│   └── Prestação de Serviços
│       ├── Serviços de Instalação
│       ├── Serviços de Manutenção
│       └── Consultorias
└── Outras Receitas
    ├── Receitas Financeiras
    ├── Aluguéis Recebidos
    └── Vendas de Ativos

💰 DESPESAS
├── Deduções da Receita Bruta
│   ├── ICMS sobre Vendas
│   ├── PIS/COFINS
│   ├── ISS
│   └── Devoluções de Vendas
├── Custos
│   ├── Custo dos Produtos Vendidos
│   ├── Custo dos Serviços Prestados
│   └── Fretes sobre Compras
├── Despesas Operacionais
│   ├── Despesas Administrativas
│   │   ├── Salários e Encargos
│   │   ├── Aluguéis
│   │   ├── Energia Elétrica
│   │   └── Material de Escritório
│   └── Despesas Comerciais
│       ├── Comissões de Vendas
│       ├── Marketing e Publicidade
│       └── Fretes sobre Vendas
├── Outras Despesas
│   ├── Despesas Financeiras
│   └── Perdas Diversas
└── Impostos IR/CSLL
    ├── Imposto de Renda
    └── Contribuição Social
```

## 🔗 Integração com Módulo Financeiro

### 💰 **Vinculação Automática**

#### **Contas a Receber**
- Cada título a receber deve ter uma **Conta de Receita** vinculada
- A conta deve ser uma **Conta Analítica** do tipo Receita
- O lançamento é automático quando o título é baixado

#### **Contas a Pagar**
- Cada título a pagar deve ter uma **Conta de Despesa** vinculada
- A conta deve ser uma **Conta Analítica** do tipo Despesa
- O lançamento é automático quando o título é baixado

### 🔄 **Processo de Integração**

#### **Configuração de Títulos**
1. **Ao criar um título a receber**:
   - Selecione a conta de receita apropriada
   - O sistema valida se é uma conta analítica de receita
   - A conta será usada no lançamento automático

2. **Ao criar um título a pagar**:
   - Selecione a conta de despesa apropriada
   - O sistema valida se é uma conta analítica de despesa
   - A conta será usada no lançamento automático

#### **Lançamentos Automáticos**
1. **Quando um título é baixado**:
   - Sistema gera lançamento automático
   - Débito/Crédito conforme natureza da conta
   - Histórico padronizado com referência ao título

## ⚙️ Configurações Avançadas

### 🔧 **Validações do Sistema**

#### **Regras de Negócio**
- **Contas Analíticas** não podem ter subcontas se já possuem lançamentos
- **Categorias DRE** devem ser definidas antes das contas
- **Exclusão** só é permitida se não houver lançamentos vinculados
- **Tipo da conta** (receita/despesa) não pode ser alterado após lançamentos

#### **Controles de Integridade**
- Verificação de hierarquia correta
- Validação de tipo de conta vs categoria DRE
- Controle de duplicidade de descrições
- Auditoria de alterações

### 📊 **Relatórios de Estrutura**

#### **Relatório do Plano de Contas**
- Estrutura hierárquica completa
- Códigos de classificação
- Status de cada conta (ativa/inativa)
- Quantidade de lançamentos por conta

#### **Análise de Utilização**
- Contas com movimentação
- Contas sem movimentação
- Frequência de uso por conta
- Sugestões de otimização

## 💡 Boas Práticas

### ✅ **Recomendações**

#### **Estruturação**
- **Planeje a estrutura** antes de começar os lançamentos
- **Use nomenclatura clara** e padronizada
- **Evite muitos níveis** hierárquicos desnecessários
- **Agrupe contas similares** em contas sintéticas

#### **Nomenclatura**
- **Seja específico** nas descrições das contas analíticas
- **Use padrões** consistentes (ex: "Vendas de..." para todas as contas de venda)
- **Evite abreviações** que possam gerar confusão
- **Inclua códigos** quando necessário para organização

#### **Manutenção**
- **Revise periodicamente** a estrutura
- **Elimine contas** não utilizadas
- **Consolide contas** com baixa movimentação
- **Documente alterações** importantes

### ⚠️ **Cuidados Importantes**

#### **Antes de Alterar**
- **Backup dos dados** contábeis
- **Validação com contador** responsável
- **Teste em ambiente** de homologação
- **Comunicação à equipe** sobre mudanças

#### **Impactos de Alterações**
- Relatórios históricos podem ser afetados
- Comparativos entre períodos podem ficar inconsistentes
- Integração com sistemas externos pode precisar de ajustes
- Usuários precisam ser treinados nas mudanças

## 🔄 Próximos passos

Após configurar o plano de contas:
1. **Valide a estrutura** com seu contador
2. **Configure as integrações** com títulos financeiros
3. **Teste os lançamentos** automáticos
4. **Treine a equipe** na nova estrutura
5. **Monitore os relatórios** gerados

## 🔗 Veja também

- [Categorias DRE](categorias-dre.md)
- [Lançamentos Automáticos](lancamentos-automaticos.md)
- [DRE - Demonstração do Resultado](dre-demonstracao-resultado.md)
- [Integração Financeira](integracao-financeira.md)

---

> **📞 Precisa de ajuda?** A configuração do plano de contas é fundamental para o sucesso da contabilidade. Entre em contato: contabilidade@White.com.br 