# 📦 Cadastro de Produtos e Serviços

🏠 [Home](../../../index.md) > 📋 [Módulos](../../index.md) > 👥 [Cadastros](../index.md) > **📦 Produtos**

#cadastros #produtos #servicos #estoque #fiscal #preco #passo-a-passo

---

## 🎯 O que é o Cadastro de Produtos?

O **Cadastro de Produtos** é o **coração do seu sistema ERP**. Aqui você registra tudo o que vende: produtos físicos, serviços, kits, composições e muito mais. É a base para:

- 🛒 **Vendas no PDV** e orçamentos
- 📊 **Controle de estoque** e movimentações
- 💰 **Precificação** e margens de lucro
- 📄 **Emissão de notas fiscais**
- 📈 **Relatórios** de performance

> **💡 Dica Importante**: Um produto bem cadastrado economiza tempo em todas as vendas futuras!

---

## 🚀 Como Cadastrar um Produto

### **Passo 1: Acessar o Cadastro**
1. No menu principal, clique em **"Cadastros"**
2. Selecione **"Produtos/Serviços"**
3. Clique no botão **"Novo Produto"** (➕)

### **Passo 2: Informações Básicas**

#### **📋 Dados Principais**
- **Código**: Código interno do produto (gerado automaticamente ou manual)
- **Código de Barras**: EAN/UPC para leitura no PDV
- **Descrição**: Nome completo do produto
- **Descrição Resumida**: Nome curto para o PDV
- **Tipo**: Produto, Serviço, Kit ou Composição

#### **💰 Informações Financeiras**
- **Preço de Custo**: Quanto você paga pelo produto
- **Preço de Venda**: Quanto você cobra do cliente
- **Margem de Lucro**: Calculada automaticamente
- **Unidade**: Unidade de medida (UN, KG, M, L, etc.)

#### **📊 Controle de Estoque**
- **Controla Estoque**: Sim/Não
- **Estoque Atual**: Quantidade disponível
- **Estoque Mínimo**: Alerta de reposição
- **Estoque Máximo**: Limite de compra

### **Passo 3: Informações Fiscais**
- **NCM**: Nomenclatura Comum do Mercosul
- **CFOP**: Código Fiscal de Operações
- **CST**: Código de Situação Tributária
- **Alíquota ICMS**: Percentual do imposto
- **Origem**: Nacional, Importado, etc.

### **Passo 4: Categorização**
- **Categoria**: Grupo principal (ex: Ração, Brinquedos)
- **Subcategoria**: Grupo específico (ex: Ração para Cães)
- **Marca**: Fabricante do produto
- **Fornecedor Principal**: Fornecedor padrão

### **Passo 5: Detalhes Adicionais**
- **Foto**: Imagem do produto
- **Descrição Completa**: Detalhes técnicos
- **Observações**: Informações internas
- **Status**: Ativo/Inativo

### **Passo 6: Salvar**
- Clique em **"Salvar"** para finalizar
- O produto estará disponível para venda imediatamente

---

## 🎯 Tipos de Produtos

### 📦 **Produto Físico**
**Características:**
- Controla estoque
- Tem peso e dimensões
- Pode ter código de barras
- Movimenta fisicamente

**Exemplo:**
```
Código: 001
Descrição: Equipamento Industrial Modelo X1
Preço: R$ 89,90
Estoque: 50 unidades
NCM: 2309.10.00
```

### 🔧 **Serviço**
**Características:**
- Não controla estoque
- Pode ter tempo de execução
- Profissional responsável
- Pode usar materiais

**Exemplo:**
```
Código: S001
Descrição: Banho e Tosa Completa
Preço: R$ 45,00
Tempo: 2 horas
Profissional: Qualquer tosador
```

### 📋 **Kit/Composição**
**Características:**
- Agrupa vários produtos
- Preço único ou soma dos itens
- Pode ter desconto especial
- Controla estoque dos componentes

**Exemplo:**
```
Kit Higiene Canina:
- 1x Shampoo Neutro
- 1x Condicionador
- 1x Escova
Preço Kit: R$ 35,00 (desconto de 15%)
```

---

## 🏷️ Códigos de Barras e SKU

### **📊 Código de Barras**
- **EAN-13**: Padrão internacional (13 dígitos)
- **EAN-8**: Versão reduzida (8 dígitos)
- **Código 128**: Para produtos internos
- **QR Code**: Para produtos digitais

### **🔤 SKU (Stock Keeping Unit)**
- **Código interno** único para cada produto
- **Padrão sugerido**: CAT-MARCA-MODELO-VAR
- **Exemplo**: RAC-GOL-ADU15-15KG

### **⚡ Dicas de Códigos**
1. **Use padrões consistentes** para facilitar busca
2. **Evite caracteres especiais** (!, @, #, etc.)
3. **Mantenha códigos curtos** mas descritivos
4. **Teste sempre** no leitor de código de barras

---

## 💰 Estratégias de Precificação

### **📈 Precificação por Margem**
```
Preço de Venda = Preço de Custo ÷ (1 - Margem Desejada)

Exemplo:
Custo: R$ 50,00
Margem desejada: 40%
Preço de Venda: R$ 50,00 ÷ 0,6 = R$ 83,33
```

### **🎯 Precificação por Markup**
```
Preço de Venda = Preço de Custo × (1 + Markup)

Exemplo:
Custo: R$ 50,00
Markup: 80%
Preço de Venda: R$ 50,00 × 1,8 = R$ 90,00
```

### **📊 Tabelas de Preços**
- **Preço Atacado**: Para compras acima de X unidades
- **Preço VIP**: Para clientes especiais
- **Preço Promocional**: Para campanhas
- **Preço Funcionário**: Para colaboradores

---

## 🎨 Variações de Produtos

### **👕 Produtos com Variações**
**Exemplo: Camiseta**
- **Variação 1**: Cor (Azul, Vermelho, Verde)
- **Variação 2**: Tamanho (P, M, G, GG)
- **Resultado**: 12 produtos diferentes

### **🔧 Como Configurar**
1. **Cadastre o produto pai** (Camiseta Básica)
2. **Defina os atributos** (Cor, Tamanho)
3. **Crie as variações** automaticamente
4. **Ajuste preços** se necessário
5. **Configure estoque** individual

### **📋 Gestão de Variações**
- **Código único** para cada variação
- **Preços diferenciados** por variação
- **Estoque independente** por variação
- **Fotos específicas** para cada uma

---

## 📸 Imagens e Descrições

### **🖼️ Fotos de Produtos**
**Especificações recomendadas:**
- **Formato**: JPG ou PNG
- **Tamanho**: 800x800 pixels
- **Peso**: Máximo 2MB
- **Fundo**: Preferencialmente branco
- **Qualidade**: Alta definição

### **📝 Descrições Eficazes**
**Estrutura sugerida:**
1. **Título chamativo** (60 caracteres)
2. **Características principais** (bullet points)
3. **Benefícios** para o cliente
4. **Especificações técnicas**
5. **Instruções de uso** (se aplicável)

**Exemplo:**
```
🔧 Equipamento Industrial Modelo X1 - Alta Performance

✅ Características:
• Material de alta resistência
• Rico em funcionalidades avançadas
• Sem componentes descartáveis
• Operação simplificada

🎯 Benefícios:
• Maior produtividade
• Redução de custos operacionais
• Maior durabilidade
• Ideal para operações de 1 a 3 turnos

📊 Especificações:
• Peso: 15kg
• Potência: 2100W
• Voltagem: 220V
• Garantia: 24 meses
```

---

## 🏭 Informações do Fornecedor

### **📋 Dados do Fornecedor**
- **Fornecedor Principal**: Quem fornece normalmente
- **Fornecedores Alternativos**: Opções secundárias
- **Código do Fornecedor**: Referência do produto
- **Prazo de Entrega**: Tempo para reposição
- **Pedido Mínimo**: Quantidade mínima de compra

### **💰 Condições Comerciais**
- **Preço de Compra**: Valor negociado
- **Desconto por Volume**: Tabela de descontos
- **Prazo de Pagamento**: Condições financeiras
- **Frete**: Responsabilidade e valor

---

## 🔄 Controle de Estoque

### **📊 Tipos de Controle**

#### **🎯 Controle Simples**
- **Estoque Atual**: Quantidade disponível
- **Entrada**: Compras e ajustes positivos
- **Saída**: Vendas e ajustes negativos
- **Saldo**: Automático (Entrada - Saída)

#### **📈 Controle Avançado**
- **Múltiplos Depósitos**: Estoque por localização
- **Lote e Validade**: Controle FIFO/FEFO
- **Reservas**: Produtos separados para pedidos
- **Estoque Virtual**: Disponível para venda

### **⚠️ Alertas de Estoque**
- **Estoque Mínimo**: Alerta para reposição
- **Estoque Máximo**: Limite de compra
- **Produtos Vencidos**: Alerta de validade
- **Produtos Parados**: Sem movimento

---

## 📄 Aspectos Fiscais

### **🏛️ Informações Obrigatórias**
- **NCM**: Classificação fiscal do produto
- **CFOP**: Operação fiscal (venda, transferência, etc.)
- **CST**: Situação tributária
- **Alíquota**: Percentual de imposto
- **Origem**: Nacional, importado, etc.

### **💡 Dicas Fiscais**
1. **Consulte sempre** um contador para NCM
2. **Mantenha atualizado** com mudanças da legislação
3. **Use códigos corretos** para evitar multas
4. **Documente** as justificativas fiscais

### **📋 Tabela de CST Comuns**
| CST | Descrição |
|-----|-----------|
| 000 | Tributada integralmente |
| 101 | Tributada com cobrança por ST |
| 102 | Tributada sem cobrança |
| 400 | Isenta |
| 500 | Substituição tributária |

---

## 🔧 Funcionalidades Avançadas

### **📊 Relatórios de Produtos**
- **Produtos Mais Vendidos**: Ranking por quantidade
- **Margem de Lucro**: Análise de rentabilidade
- **Produtos Parados**: Sem movimento
- **Curva ABC**: Classificação por importância
- **Estoque Valorizado**: Valor total do estoque

### **🔄 Importação/Exportação**
- **Importar de Planilha**: Upload de arquivo Excel/CSV
- **Exportar Catálogo**: Gerar arquivo para backup
- **Sincronização**: Com e-commerce e marketplaces
- **API**: Integração com sistemas externos

### **🎯 Automações**
- **Reposição Automática**: Pedidos automáticos
- **Ajuste de Preços**: Baseado em margem
- **Promoções**: Campanhas automáticas
- **Relatórios Agendados**: Envio por email

---

## 💡 Casos de Uso Específicos

### 🔧 **Prestação de Serviços**
**Produtos típicos:**
- **Equipamentos**: Controle de manutenção
- **Materiais**: Controle de estoque
- **Ferramentas**: Variações de modelo e marca
- **Serviços**: Manutenção, consultoria, suporte

**Configurações especiais:**
- **Controle de manutenção**: Para equipamentos
- **Ordem de serviço**: Para materiais utilizados
- **Agendamento**: Para serviços
- **Fichas técnicas**: Para produtos especializados

### 🏪 **Comércio Geral**
**Produtos típicos:**
- **Eletrodomésticos**: Garantia e assistência
- **Roupas**: Variações de cor e tamanho
- **Alimentos**: Controle de validade
- **Eletrônicos**: Número de série

**Configurações especiais:**
- **Garantia**: Prazo e condições
- **Assistência técnica**: Rede autorizada
- **Número de série**: Controle individual
- **Certificações**: Inmetro, Anatel, etc.

### 🔧 **Prestação de Serviços**
**Serviços típicos:**
- **Consultoria**: Por hora ou projeto
- **Manutenção**: Preventiva e corretiva
- **Treinamento**: Presencial ou online
- **Desenvolvimento**: Software ou website

**Configurações especiais:**
- **Tempo de execução**: Estimativa de horas
- **Profissional**: Responsável pelo serviço
- **Materiais**: Produtos utilizados
- **Etapas**: Divisão do projeto

---

## 🚨 Problemas Comuns e Soluções

### ❌ **Produto Não Aparece no PDV**
**Possíveis causas:**
- Produto inativo
- Sem preço de venda
- Categoria desabilitada
- Estoque zerado (se controla estoque)

**Soluções:**
1. Verificar se o produto está **ativo**
2. Conferir se tem **preço de venda**
3. Verificar se a **categoria está ativa**
4. Ajustar **configuração de estoque**

### ❌ **Código de Barras Não Funciona**
**Possíveis causas:**
- Código incorreto
- Produto duplicado
- Leitor descalibrado
- Formato inválido

**Soluções:**
1. Verificar **código no produto**
2. Buscar **produtos duplicados**
3. Testar **leitor de código**
4. Validar **formato do código**

### ❌ **Estoque Negativo**
**Possíveis causas:**
- Venda sem estoque
- Ajuste incorreto
- Produto sem controle
- Erro de sistema

**Soluções:**
1. Fazer **ajuste de estoque**
2. Verificar **histórico de movimentação**
3. Configurar **controle de estoque**
4. Revisar **vendas do período**

### ❌ **Margem de Lucro Incorreta**
**Possíveis causas:**
- Preço de custo errado
- Cálculo manual incorreto
- Impostos não considerados
- Despesas não incluídas

**Soluções:**
1. Verificar **preço de custo**
2. Usar **calculadora automática**
3. Incluir **impostos no cálculo**
4. Considerar **despesas operacionais**

---

## 🎯 Checklist de Cadastro

### ✅ **Informações Obrigatórias**
- [ ] Código do produto definido
- [ ] Descrição clara e completa
- [ ] Preço de custo informado
- [ ] Preço de venda calculado
- [ ] Unidade de medida selecionada
- [ ] Categoria atribuída
- [ ] Status ativo marcado

### ✅ **Informações Fiscais**
- [ ] NCM correto informado
- [ ] CFOP configurado
- [ ] CST definido
- [ ] Alíquota de ICMS
- [ ] Origem do produto

### ✅ **Controle de Estoque**
- [ ] Definir se controla estoque
- [ ] Estoque inicial informado
- [ ] Estoque mínimo configurado
- [ ] Fornecedor principal vinculado

### ✅ **Qualidade do Cadastro**
- [ ] Foto do produto adicionada
- [ ] Descrição detalhada
- [ ] Código de barras testado
- [ ] Preços validados
- [ ] Produto testado no PDV

---

## 🚀 Próximos Passos

### 📚 **Para Iniciantes**
1. **Cadastre 10 produtos** principais
2. **Teste no PDV** se aparecem
3. **Configure categorias** básicas
4. **Adicione fotos** dos produtos

### 🎯 **Para Usuários Avançados**
1. **Implemente variações** de produtos
2. **Configure tabelas** de preços
3. **Automatize reposição** de estoque
4. **Integre com e-commerce**

### 🚀 **Para Especialistas**
1. **Desenvolva regras** de precificação
2. **Implemente controle** de lote
3. **Configure relatórios** personalizados
4. **Integre com ERP** de fornecedores

---

## 📚 Documentação Relacionada

### 🔗 **Módulos Relacionados**
- **[Pdv](../vendas/pdv.md)** - Como usar produtos no PDV
- **[Controle Estoque](../estoque/controle-estoque.md)** - Gestão de estoque
- **[Precificacao](../financeiro/precificacao.md)** - Estratégias de preços
- **[Ecommerce](../integracoes/ecommerce.md)** - Sincronização online

### 📋 **Fluxos Relacionados**
- **[Fluxo Cadastro Produto](../../fluxos/fluxo-cadastro-produto.md)** - Processo completo
- **[Fluxo Compras](../../fluxos/fluxo-compras.md)** - Reposição de estoque
- **[Fluxo Vendas Completo](../../fluxos/fluxo-vendas-completo.md)** - Venda com produtos

### 💡 **Casos de Uso**
- **[Cadastro Equipamento](../../casos-uso/servicos/cadastro-equipamento.md)** - Produto com manutenção
- **[Produto Variacao](../../casos-uso/comercio-geral/produto-variacao.md)** - Variações
- **[Cadastro Servico](../../casos-uso/servicos/cadastro-servico.md)** - Serviços

---

## 🎥 Recursos Multimídia

### 📹 **Vídeos Tutoriais**
- **Cadastro Básico**: Como cadastrar seu primeiro produto
- **Variações**: Configurando produtos com cor e tamanho
- **Códigos de Barras**: Setup e teste de leitores
- **Precificação**: Estratégias de margem e markup

### 🖼️ **Imagens de Apoio**
- **Tela de Cadastro**: Screenshot com campos destacados
- **Fluxo Visual**: Diagrama do processo
- **Exemplos**: Produtos bem cadastrados
- **Erros Comuns**: O que evitar

---

**💡 Dica Final**: O cadastro de produtos é um investimento. Quanto mais completo e organizado, mais fácil será gerenciar seu negócio. Dedique tempo para fazer bem feito!

---

**Tags relacionadas**: #cadastros #produtos #servicos #estoque #fiscal #preco #passo-a-passo #codigo-barras #variacao 