# 💰 Contas a Receber

🏠 [Home](../../index.md) > 📋 [Módulos](../index.md) > 💰 [Financeiro](index.md) > **Contas a Receber**

#financeiro #receber #cobranca #boleto #passo-a-passo #importante

## 📋 O que é

O módulo **Contas a Receber** é onde você controla todos os valores que seus clientes devem pagar. É essencial para:

- **Fluxo de Caixa** - Previsão de recebimentos futuros
- **Controle de Inadimplência** - Identificar clientes em atraso
- **Gestão de Cobrança** - Automatizar processo de cobrança
- **Conciliação Bancária** - Confirmar recebimentos automaticamente

## 🚀 Como Fazer

### 📋 **Passo 1: Acessar o Módulo**
1. No menu principal, clique em **Financeiro**
2. Selecione **Contas a Receber**
3. Visualize todos os títulos em aberto

### 📊 **Passo 2: Visualizar Títulos**
A tela principal mostra:
- **Títulos em Aberto** - Valores ainda não recebidos
- **Títulos Vencidos** - Em atraso (destacados em vermelho)
- **Títulos a Vencer** - Próximos vencimentos
- **Títulos Recebidos** - Histórico de recebimentos

### 💳 **Passo 3: Processar Recebimento**
1. **Selecionar Título**: Clique no título a receber
2. **Confirmar Dados**: Verifique cliente e valor
3. **Definir Forma de Pagamento**:
   - ✅ **Dinheiro** - Recebimento em espécie
   - ✅ **PIX** - Transferência instantânea
   - ✅ **Cartão de Débito** - Débito em conta
   - ✅ **Cartão de Crédito** - Crédito parcelado
   - ✅ **Transferência** - TED/DOC
   - ✅ **Boleto** - Pagamento em boleto

### 💰 **Passo 4: Aplicar Ajustes (se necessário)**
1. **Juros de Mora**:
   - **Percentual**: Definido nas configurações
   - **Cálculo Automático**: Baseado nos dias de atraso
   - **Valor Manual**: Se necessário ajustar

2. **Multa por Atraso**:
   - **Percentual Fixo**: Geralmente 2%
   - **Aplicação**: Apenas após vencimento
   - **Isenção**: Pode ser removida se necessário

3. **Desconto**:
   - **Desconto por Antecipação**: Pagamento antes do vencimento
   - **Desconto Comercial**: Negociação com cliente
   - **Percentual ou Valor**: Flexível

### 📋 **Passo 5: Confirmar Recebimento**
1. **Revisar Valores**: Confirme valor final
2. **Selecionar Conta**: Conta bancária de destino
3. **Data do Recebimento**: Data real do recebimento
4. **Observações**: Adicione observações se necessário
5. **Confirmar**: Clique em **Confirmar Recebimento**

## 🔄 Funcionalidades Avançadas

### 📧 **Geração Automática de Boletos**
1. **Configuração Inicial**:
   - Configure dados bancários
   - Defina layout do boleto
   - Configure vencimentos

2. **Geração Automática**:
   - Boletos gerados automaticamente nas vendas
   - Envio por email automático
   - Registro automático no banco

3. **Acompanhamento**:
   - Status do boleto (registrado, pago, vencido)
   - Notificações de pagamento
   - Baixa automática

### 📅 **Controle de Vencimentos**
1. **Alertas Automáticos**:
   - **5 dias antes**: Alerta de vencimento próximo
   - **No vencimento**: Notificação de vencimento
   - **Após vencimento**: Alerta de inadimplência

2. **Dashboard de Vencimentos**:
   - **Hoje**: Títulos que vencem hoje
   - **Esta Semana**: Vencimentos da semana
   - **Este Mês**: Vencimentos do mês
   - **Em Atraso**: Títulos vencidos

### 📊 **Relatórios de Inadimplência**
1. **Clientes Inadimplentes**:
   - Lista de clientes em atraso
   - Valor total em atraso
   - Dias de atraso
   - Histórico de pagamentos

2. **Análise de Inadimplência**:
   - Percentual de inadimplência
   - Evolução mensal
   - Perfil dos inadimplentes
   - Ações recomendadas

### 🏦 **Conciliação Bancária**
1. **Importação de Extratos**:
   - Importar arquivo OFX do banco
   - Importar arquivo CSV
   - Conexão automática com API do banco

2. **Conciliação Automática**:
   - Identificação automática de recebimentos
   - Baixa automática de títulos
   - Relatório de conciliação

## 💡 Casos de Uso

### 🛒 **Caso 1: Venda à Vista**
**Situação**: Cliente paga no ato da compra

**Processo**:
1. **Venda no PDV**: Sistema gera título automaticamente
2. **Recebimento Imediato**: Processa pagamento na hora
3. **Baixa Automática**: Título é baixado automaticamente
4. **Comprovante**: Emite comprovante de pagamento

**Benefícios**:
- Processo simplificado
- Controle automático
- Sem inadimplência

### 📅 **Caso 2: Venda Parcelada**
**Situação**: Cliente paga em 3x no cartão

**Processo**:
1. **Venda Parcelada**: Sistema gera 3 títulos
2. **Vencimentos**: Datas automáticas (30, 60, 90 dias)
3. **Recebimento**: Cada parcela é recebida separadamente
4. **Controle**: Acompanha cada parcela individualmente

**Benefícios**:
- Controle por parcela
- Previsão de recebimentos
- Facilita vendas

### 🏢 **Caso 3: Venda B2B com Boleto**
**Situação**: Empresa compra com prazo de 30 dias

**Processo**:
1. **Venda com Prazo**: Sistema gera título para 30 dias
2. **Boleto Automático**: Gera e envia boleto por email
3. **Acompanhamento**: Monitora status do boleto
4. **Recebimento**: Baixa automática quando pago

**Benefícios**:
- Processo automatizado
- Controle de prazo
- Reduz inadimplência

## 🔧 Troubleshooting

### ❌ **Erro: Título Não Encontrado**
**Problema**: Não consegue localizar título para baixa

**Soluções**:
1. **Verifique Filtros**: Confira filtros de data e status
2. **Busque por Cliente**: Use nome ou CPF/CNPJ
3. **Verifique Status**: Título pode já estar baixado
4. **Consulte Histórico**: Verifique histórico de movimentações

### ❌ **Erro: Valor Divergente**
**Problema**: Valor recebido diferente do título

**Soluções**:
1. **Verifique Juros**: Confirme cálculo de juros e multa
2. **Confira Descontos**: Verifique descontos aplicados
3. **Recebimento Parcial**: Registre como recebimento parcial
4. **Ajuste Manual**: Faça ajuste manual se necessário

### ❌ **Erro: Conciliação Falhou**
**Problema**: Não consegue conciliar extrato bancário

**Soluções**:
1. **Verifique Formato**: Confirme formato do arquivo
2. **Confira Datas**: Verifique período do extrato
3. **Dados Bancários**: Confirme configuração da conta
4. **Importação Manual**: Faça importação manual se necessário

## 📋 Boas Práticas

### ✅ **Controle Rigoroso**
- **Acompanhamento Diário**: Verifique recebimentos diariamente
- **Cobrança Proativa**: Cobre antes do vencimento
- **Análise Regular**: Analise inadimplência mensalmente
- **Políticas Claras**: Defina políticas de cobrança

### ✅ **Automação**
- **Boletos Automáticos**: Use boletos registrados
- **Alertas Configurados**: Configure todos os alertas
- **Conciliação Automática**: Conecte com bancos
- **Relatórios Agendados**: Agende relatórios automáticos

### ✅ **Relacionamento com Cliente**
- **Comunicação Clara**: Informe prazos e condições
- **Facilidades**: Ofereça múltiplas formas de pagamento
- **Negociação**: Seja flexível em casos especiais
- **Histórico**: Mantenha histórico de negociações

## 🔗 Fluxos Relacionados

### 💰 **Fluxo de Recebimento**
1. **[Pdv](../vendas/pdv.md)** - Venda gera título automaticamente
2. **[Contas A Receber](contas-a-receber.md)** - Controle de recebimentos
3. **[Fluxo De Caixa](fluxo-de-caixa.md)** - Impacto no fluxo de caixa
4. **[Financeiro](../relatorios/financeiro.md)** - Relatórios de recebimento

### 🏦 **Fluxo de Cobrança**
1. **[Contas A Receber](contas-a-receber.md)** - Identificar títulos vencidos
2. **[Processo Cobranca](processo-cobranca.md)** - Executar cobrança
3. **[Negociacao Dividas](negociacao-dividas.md)** - Negociar com inadimplentes
4. **[Baixa Por Perda](baixa-por-perda.md)** - Baixar perdas irrecuperáveis

## 📊 Relatórios Relacionados

### 📈 **Relatórios Disponíveis**
- **Contas a Receber** - Todos os títulos em aberto
- **Vencimentos** - Títulos por data de vencimento
- **Inadimplência** - Clientes em atraso
- **Recebimentos** - Histórico de recebimentos
- **Projeção de Recebimentos** - Previsão de entrada

### 📋 **Análises Gerenciais**
- **Aging de Recebíveis** - Títulos por tempo de atraso
- **Performance de Cobrança** - Eficácia da cobrança
- **Análise de Clientes** - Perfil de pagamento
- **Tendências** - Evolução da inadimplência

## 🆘 Veja Também

- **[Contas A Pagar](contas-a-pagar.md)** - Gestão de pagamentos
- **[Fluxo De Caixa](fluxo-de-caixa.md)** - Controle de fluxo de caixa
- **[Pdv](../vendas/pdv.md)** - Vendas que geram recebimentos
- **[Parametros Fiscais](../configuracoes/parametros-fiscais.md)** - Configurações fiscais
- **[Financeiro](../relatorios/financeiro.md)** - Relatórios financeiros

---

**Tags relacionadas**: #financeiro #receber #cobranca #boleto #passo-a-passo #importante

**Próximos passos**: Configure **[Processo Cobranca](processo-cobranca.md)** para automatizar a cobrança de títulos vencidos.

---

*💡 **Dica**: Mantenha sempre um controle rigoroso das contas a receber. Uma boa gestão de recebimentos é fundamental para a saúde financeira da empresa.* 