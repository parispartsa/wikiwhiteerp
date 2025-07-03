# CIOT e Seguros de Carga

🏠 [Home](../../../index.md) > 📋 [Módulos](../../index.md) > 🚛 [Transportes](index.md) > **CIOT e Seguros**

#transportes #ciot #seguros #antt #compliance #carga

## 🎯 O que é CIOT e Seguros

O **CIOT (Código Identificador da Operação de Transporte)** é um código obrigatório emitido pela ANTT para operações com transportadores autônomos. Os **Seguros de Carga** são proteções obrigatórias para mercadorias em transporte. Ambos garantem compliance total e proteção nas operações logísticas.

### 🚀 Principais Benefícios
- **Compliance ANTT**: Atende 100% das exigências regulamentares
- **Proteção Total**: Cobertura completa para cargas
- **Controle Automático**: Gestão integrada com MDFe
- **Redução de Riscos**: Proteção contra perdas e danos

## 🛡️ CIOT - Código Identificador da Operação

### 📋 **O que é o CIOT**
O CIOT é obrigatório para:
- Transporte com **Transportadores Autônomos de Carga (TAC)**
- Operações com **veículos não próprios**
- Contratação de **motoristas autônomos**
- Transporte **terceirizado**

### 🔧 **Como configurar CIOT no MDFe**

#### **Passo 1: Acessar o CIOT**
1. No MDFe, clique na aba **"CIOT"**
2. Clique em **"Adicionar CIOT"**
3. Preencha os dados obrigatórios

#### **Passo 2: Dados do CIOT**
1. **Código CIOT**: Número fornecido pela ANTT
   - Obtido no portal da ANTT
   - Específico para cada operação
   - Válido por período determinado
2. **CPF/CNPJ**: Documento do responsável
   - CPF do motorista autônomo
   - CNPJ da transportadora
   - Deve coincidir com o cadastro ANTT

#### **Passo 3: Validação**
1. Sistema valida o código CIOT automaticamente
2. Verifica se está ativo na ANTT
3. Confirma a vinculação com o responsável
4. Integra automaticamente ao MDFe

### 📱 **Obtendo CIOT na ANTT**

#### **Portal ANTT**
1. Acesse o **Portal de Serviços da ANTT**
2. Faça login com certificado digital
3. Selecione **"Gerar CIOT"**
4. Preencha os dados da operação:
   - **Contratante**: Empresa que contrata
   - **Contratado**: Motorista/Transportadora
   - **Valor do Frete**: Valor acordado
   - **Origem/Destino**: Rotas da operação
5. Confirme e obtenha o código

#### **Validade do CIOT**
- **Período**: Válido conforme configurado
- **Operação**: Específico para cada transporte
- **Renovação**: Automática ou manual
- **Cancelamento**: Possível até início do transporte

## 🏦 Seguros de Carga

### 📋 **Tipos de Seguro**

#### **Seguro de Responsabilidade Civil do Transportador (RCTR-C)**
- **Obrigatório** para todos os transportadores
- Cobre **danos à carga** durante o transporte
- Valor mínimo definido por lei
- Contratado pelo transportador

#### **Seguro de Transporte Nacional (STN)**
- **Opcional**, contratado pelo dono da carga
- Cobertura **mais ampla** que o RCTR-C
- Inclui **riscos adicionais**
- Valor baseado no valor da mercadoria

#### **Seguro de Responsabilidade Civil Facultativo (RCF-DC)**
- **Complementar** ao RCTR-C
- Aumenta o **limite de cobertura**
- Contratado pelo transportador
- Para cargas de **alto valor**

### 🔧 **Configurando Seguros no MDFe**

#### **Passo 1: Acessar Seguros**
1. No MDFe, clique na aba **"Seguros"**
2. Clique em **"Adicionar Seguro"**
3. Selecione o tipo de seguro

#### **Passo 2: Dados Básicos**
1. **Responsável pelo Seguro**:
   - **Emitente**: Empresa emitente do MDFe
   - **Contratante**: Cliente contratante
   - **Transportador**: Empresa de transporte
2. **CPF/CNPJ do Responsável**: Documento do responsável
3. **Tipo de Seguro**: RCTR-C, STN, RCF-DC

#### **Passo 3: Dados da Seguradora**
1. **Nome da Seguradora**: Razão social da seguradora
2. **CNPJ da Seguradora**: CNPJ da empresa de seguros
3. **Número da Apólice**: Número da apólice contratada
4. **Número da Averbação**: Número da averbação (se aplicável)

#### **Passo 4: Cobertura**
1. **Valor Segurado**: Valor total da cobertura
2. **Franquia**: Valor da franquia (se aplicável)
3. **Vigência**: Período de cobertura
4. **Observações**: Informações adicionais

### 📊 **Controle de Apólices**

#### **Cadastro de Seguradoras**
1. **Razão Social**: Nome da seguradora
2. **CNPJ**: Documento da seguradora
3. **Contato**: Telefone e email
4. **Endereço**: Endereço completo
5. **Representante**: Dados do corretor

#### **Gestão de Apólices**
1. **Número da Apólice**: Identificação única
2. **Tipo de Cobertura**: RCTR-C, STN, RCF-DC
3. **Valor da Cobertura**: Limite máximo
4. **Vigência**: Data início e fim
5. **Franquia**: Valor da franquia
6. **Status**: Ativa, vencida, cancelada

#### **Controle de Averbações**
1. **Número da Averbação**: Código único
2. **Apólice Vinculada**: Apólice relacionada
3. **Valor Averbado**: Valor específico da operação
4. **Data da Averbação**: Data de registro
5. **Status**: Ativa, utilizada, cancelada

## 🛣️ Controle de Pedágios

### 📋 **Gestão de Vale-Pedágio**

#### **Passo 1: Configurar Pedágios**
1. No MDFe, clique na aba **"Pedágios"**
2. Clique em **"Adicionar Pedágio"**
3. Preencha os dados do vale

#### **Passo 2: Dados do Vale**
1. **CNPJ do Fornecedor**: Empresa fornecedora do vale
2. **Número do Comprovante**: Código do vale-pedágio
3. **Valor do Vale**: Valor em reais
4. **CPF/CNPJ Responsável**: Responsável pelo pagamento

#### **Fornecedores de Vale-Pedágio**
- **Sem Parar**
- **ConectCar**
- **TaggyPay**
- **Outros fornecedores credenciados**

### 📊 **Relatórios de Pedágio**
1. **Gastos por Rota**: Custos de pedágio por trajeto
2. **Gastos por Veículo**: Custos por veículo
3. **Gastos por Período**: Análise temporal
4. **Fornecedores**: Comparativo de fornecedores
5. **Conciliação**: Conferência de valores

## 💰 Gestão Financeira

### 📋 **Controle de Pagamentos**

#### **Pagamento de Fretes**
1. **Valor do Contrato**: Valor acordado
2. **Forma de Pagamento**: À vista ou parcelado
3. **Dados Bancários**: Conta para pagamento
4. **Chave PIX**: Para pagamentos instantâneos
5. **Parcelas**: Configuração de parcelamento

#### **Comprovantes de Pagamento**
1. **Tipo de Comprovante**: 
   - Vale-Pedágio
   - Adiantamento
   - Combustível
   - Outros
2. **Valor**: Valor do comprovante
3. **Descrição**: Descrição do gasto
4. **Data**: Data do pagamento

### 📊 **Relatórios Financeiros**
1. **Custos por Operação**: Análise detalhada de custos
2. **Margem de Lucro**: Rentabilidade por transporte
3. **Fluxo de Caixa**: Entradas e saídas
4. **Contas a Pagar**: Obrigações pendentes
5. **Contas a Receber**: Valores a receber

## 🔔 Alertas e Compliance

### ⚠️ **Alertas Automáticos**
- **CIOT Vencido**: Código próximo ao vencimento
- **Seguro Vencido**: Apólices próximas ao vencimento
- **Averbação Pendente**: Averbações não realizadas
- **Documentos em Falta**: Documentos obrigatórios

### 📋 **Checklist de Compliance**
- [ ] CIOT válido e ativo
- [ ] Seguro RCTR-C contratado
- [ ] Averbação realizada (se necessário)
- [ ] Vale-pedágio disponível
- [ ] Documentos do motorista válidos
- [ ] Veículo com documentação em dia

## 💡 Dicas importantes

> **⚠️ Atenção**: O CIOT é obrigatório para operações com autônomos. Transportar sem CIOT válido resulta em multa grave.

> **💡 Dica**: Configure alertas para vencimento de seguros com 30 dias de antecedência para renovação sem interrupção.

> **🔒 Segurança**: Mantenha sempre backup das apólices e comprovantes de pagamento de seguros.

> **📋 Compliance**: Verifique se o valor do seguro é adequado ao valor da carga transportada.

## 🔄 Próximos passos

Após configurar CIOT e seguros:
1. **Valide os códigos** no portal da ANTT
2. **Configure alertas** para vencimentos
3. **Treine a equipe** nos procedimentos
4. **Monitore compliance** regularmente
5. **Mantenha documentos** organizados

## 🔗 Veja também

- [MDFe - Manifesto Eletrônico](mdfe-manifesto-eletronico.md)
- [CTe - Conhecimento de Transporte](cte-conhecimento-transporte.md)
- [Gestão de Frota](gestao-frota.md)
- [Fluxo: Controle de Seguros](../../fluxos/fluxo-controle-seguros.md)

---

> **📞 Precisa de ajuda?** Entre em contato com nosso suporte especializado em transportes: suporte@gerenciatech.com.br 