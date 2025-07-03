# 🛒 PDV - Ponto de Venda

🏠 [Home](../../index.md) > 📋 [Módulos](../index.md) > 🛒 [Vendas](index.md) > **PDV**

#pdv #vendas #passo-a-passo #importante #balcao

## 📋 O que é

O **PDV (Ponto de Venda)** é o módulo para vendas rápidas no balcão. É otimizado para:

- **Vendas Ágeis** - Interface simples e intuitiva
- **Múltiplas Formas de Pagamento** - Dinheiro, cartão, PIX, etc.
- **Controle de Estoque** - Baixa automática no estoque
- **Emissão Fiscal** - Notas fiscais automáticas
- **Gestão de Caixa** - Abertura, sangria, fechamento

## 🚀 Como Usar o PDV

### Passo 1: Abrir o Caixa
1. Acesse **"Vendas"** > **"PDV"**
2. Clique em **"Abrir Caixa"**
3. Informe o **valor inicial** em dinheiro
4. Confirme a abertura

> **💡 Dica**: Sempre confira o valor inicial antes de confirmar.

### Passo 2: Identificar o Cliente
- **Cliente Cadastrado**: Digite nome, CPF ou telefone
- **Cliente Novo**: Clique em **"Novo Cliente"** para cadastro rápido
- **Consumidor Final**: Use a opção **"Consumidor Final"**

> **⚠️ Atenção**: Para emissão de nota fiscal, o cliente deve ter CPF/CNPJ válido.

### Passo 3: Adicionar Produtos

#### 🔍 **Formas de Buscar Produtos**
- **Código de Barras**: Use leitor ou digite o código
- **Código do Produto**: Digite o código interno
- **Nome do Produto**: Digite parte do nome
- **Busca Rápida**: Use F2 para busca avançada

#### 📦 **Adicionando Itens**
1. Encontre o produto desejado
2. Informe a **quantidade** (padrão: 1)
3. Confirme com **Enter** ou clique em **"Adicionar"**
4. O item aparece na lista de vendas

### Passo 4: Aplicar Descontos (se necessário)
- **Desconto no Item**: Clique no item e altere o desconto
- **Desconto na Venda**: Use o campo **"Desconto Total"**
- **Desconto em %**: Digite o percentual
- **Desconto em R$**: Digite o valor fixo

> **💡 Dica**: Configure permissões para controlar quem pode dar desconto.

### Passo 5: Escolher Forma de Pagamento

#### 💰 **Opções Disponíveis**
- **Dinheiro**: Pagamento em espécie
- **Cartão de Débito**: Pagamento via POS
- **Cartão de Crédito**: À vista ou parcelado
- **PIX**: Pagamento instantâneo
- **Boleto**: Para pagamento posterior
- **Crediário**: Parcelamento próprio

#### 🔄 **Pagamento Misto**
Para usar múltiplas formas:
1. Selecione a primeira forma
2. Informe o valor parcial
3. Clique em **"Adicionar"**
4. Repita para outras formas
5. Complete até o valor total

### Passo 6: Processar a Venda
1. Revise todos os itens
2. Confirme o total
3. Clique em **"Finalizar Venda"**
4. Aguarde o processamento

### Passo 7: Emitir Comprovantes
- **Cupom Fiscal**: Impressão automática
- **Nota Fiscal**: Emitida automaticamente (se configurado)
- **Comprovante de Cartão**: Via POS (se aplicável)

## 🔧 Funcionalidades Avançadas

### 🎯 **Vendas Rápidas**
- **Teclas de Atalho**: F1 a F12 para produtos frequentes
- **Últimas Vendas**: Acesso rápido a vendas recentes
- **Carrinho Suspenso**: Suspender venda para atender outro cliente
- **Busca Inteligente**: Sistema aprende seus padrões

### 💳 **Gestão de Pagamentos**
- **Troco Automático**: Cálculo automático do troco
- **Validação de Cartão**: Integração com POS
- **Confirmação PIX**: Validação automática
- **Parcelamento**: Configuração flexível

### 📊 **Controles Operacionais**
- **Sangria**: Retirada de dinheiro do caixa
- **Reforço**: Adição de dinheiro ao caixa
- **Cancelamento**: Cancelar vendas com justificativa
- **Troca/Devolução**: Processar devoluções

## 💡 Casos de Uso

### 🐕 **Caso 1: Venda Simples - Pet Shop**
**Situação**: Cliente compra ração para seu cão.

**Passo a passo**:
1. Identificar cliente: "Maria Silva"
2. Ler código de barras da ração
3. Quantidade: 1
4. Total: R$ 45,00
5. Pagamento: Dinheiro R$ 50,00
6. Troco: R$ 5,00
7. Finalizar venda
8. Imprimir cupom

### 🛍️ **Caso 2: Venda com Desconto**
**Situação**: Cliente VIP com desconto especial.

**Passo a passo**:
1. Identificar cliente VIP
2. Adicionar produtos
3. Sistema aplica desconto automático (10%)
4. Confirmar desconto
5. Pagamento com cartão
6. Finalizar venda

### 💳 **Caso 3: Pagamento Misto**
**Situação**: Cliente paga parte em dinheiro, parte no cartão.

**Passo a passo**:
1. Total da venda: R$ 120,00
2. Primeira forma: Dinheiro R$ 70,00
3. Segunda forma: Cartão R$ 50,00
4. Confirmar pagamento
5. Processar no POS
6. Finalizar venda

### 🔄 **Caso 4: Troca de Produto**
**Situação**: Cliente quer trocar produto comprado ontem.

**Passo a passo**:
1. Localizar venda original
2. Selecionar item para troca
3. Adicionar novo produto
4. Calcular diferença
5. Processar pagamento/troco
6. Finalizar operação

## 🎨 Personalização da Interface

### 🖥️ **Layout do PDV**
- **Tela Cheia**: Maximize para melhor visualização
- **Cores**: Personalize cores da interface
- **Fontes**: Ajuste tamanho das fontes
- **Botões**: Configure botões de acesso rápido

### ⌨️ **Teclas de Atalho**
- **F1**: Buscar produto
- **F2**: Busca avançada
- **F3**: Aplicar desconto
- **F4**: Finalizar venda
- **F5**: Suspender venda
- **F6**: Cancelar item
- **F7**: Sangria
- **F8**: Reforço
- **F9**: Consultar preço
- **F10**: Fechar caixa

### 🎯 **Botões Rápidos**
Configure até 20 botões para produtos mais vendidos:
1. Acesse **"Configurações"** > **"PDV"**
2. Clique em **"Botões Rápidos"**
3. Selecione produtos
4. Defina posição e cor
5. Salve configurações

## 📊 Relatórios do PDV

### 📈 **Relatórios Operacionais**
- **Vendas do Dia**: Todas as vendas realizadas
- **Movimento de Caixa**: Entradas e saídas
- **Produtos Vendidos**: Ranking de produtos
- **Formas de Pagamento**: Distribuição por forma

### 📊 **Relatórios Gerenciais**
- **Performance por Vendedor**: Vendas por operador
- **Análise de Horários**: Picos de movimento
- **Ticket Médio**: Valor médio das vendas
- **Tempo de Atendimento**: Eficiência do atendimento

### 📱 **Dashboard em Tempo Real**
- **Vendas do Dia**: Valor total vendido
- **Quantidade de Vendas**: Número de transações
- **Ticket Médio**: Valor médio por venda
- **Meta do Dia**: Progresso da meta

## 🔒 Segurança e Controle

### 🛡️ **Controles de Acesso**
- **Login Obrigatório**: Cada vendedor tem seu login
- **Permissões**: Controle por funcionalidade
- **Auditoria**: Log de todas as operações
- **Backup**: Backup automático das vendas

### 📋 **Controles Operacionais**
- **Limite de Desconto**: Máximo por vendedor
- **Aprovação de Descontos**: Desconto acima do limite
- **Cancelamento**: Justificativa obrigatória
- **Sangria**: Limite máximo configurável

### 🔍 **Auditoria e Rastreabilidade**
- **Log de Operações**: Todas as ações registradas
- **Histórico de Alterações**: Mudanças em vendas
- **Identificação do Usuário**: Quem fez o quê
- **Timestamp**: Data e hora de cada operação

## 🔄 Integrações

### 💳 **Equipamentos**
- **POS**: Máquinas de cartão
- **Leitor de Código de Barras**: Leitura automática
- **Impressora Fiscal**: Cupons fiscais
- **Gaveta de Dinheiro**: Abertura automática

### 🏦 **Sistemas Financeiros**
- **Bancos**: Confirmação de PIX
- **Adquirentes**: Cielo, Rede, Stone
- **Gateways**: PagSeguro, Mercado Pago
- **Conciliação**: Baixa automática

### 📊 **Sistemas de Gestão**
- **Estoque**: Baixa automática
- **Financeiro**: Títulos a receber
- **Fiscal**: Emissão de notas
- **CRM**: Histórico do cliente

## 🆘 Troubleshooting

### 🔧 **Problemas Comuns**

#### **Erro: Produto Não Encontrado**
- **Causa**: Código incorreto ou produto inativo
- **Solução**: Verifique código ou status do produto
- **Prevenção**: Mantenha cadastro atualizado

#### **Erro: Estoque Insuficiente**
- **Causa**: Quantidade solicitada maior que disponível
- **Solução**: Ajuste quantidade ou registre entrada
- **Prevenção**: Configure alertas de estoque baixo

#### **Erro: Falha na Impressão**
- **Causa**: Impressora desconectada ou sem papel
- **Solução**: Verifique conexão e papel
- **Prevenção**: Manutenção preventiva

#### **Erro: POS Não Responde**
- **Causa**: Conexão ou configuração incorreta
- **Solução**: Verifique cabos e configurações
- **Prevenção**: Teste diário dos equipamentos

## 📋 Checklist de Boas Práticas

### ✅ **Abertura do Caixa**
- [ ] Conferir valor inicial
- [ ] Testar equipamentos
- [ ] Verificar papel da impressora
- [ ] Confirmar conexão com internet

### ✅ **Durante as Vendas**
- [ ] Sempre identificar o cliente
- [ ] Conferir produtos antes de adicionar
- [ ] Validar formas de pagamento
- [ ] Entregar comprovantes

### ✅ **Fechamento do Caixa**
- [ ] Conferir valor em dinheiro
- [ ] Imprimir relatório de fechamento
- [ ] Fazer backup dos dados
- [ ] Guardar dinheiro em local seguro

## 🎯 Próximos Passos

Após dominar o PDV:

1. **[[modulos/financeiro/contas-a-receber]]** - Acompanhe recebimentos
2. **[[modulos/estoque/controle-estoque]]** - Monitore estoque
3. **[[relatorios-vendas]]** - Analise performance
4. **[[configuracoes-pdv-avancadas]]** - Personalize ainda mais

## 📚 Documentação Relacionada

- **[[orcamentos]]** - Criar orçamentos antes da venda
- **[[cadastro-rapido-cliente]]** - Cadastrar clientes no PDV
- **[[controle-estoque]]** - Gestão de estoque
- **[[emissao-fiscal]]** - Notas fiscais automáticas

---

**Tags relacionadas**: #pdv #vendas #passo-a-passo #importante #balcao

**Veja também**: [[orcamentos]] | [[controle-estoque]] | [[contas-a-receber]]

---

*💡 **Dica**: O PDV é o coração das vendas no balcão. Invista tempo no treinamento da equipe para garantir agilidade e precisão no atendimento!* 