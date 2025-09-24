# 📦 Cadastro de Produtos e Serviços

🏠 [Home](../../../index.md) > 📋 [Módulos](../../index.md) > 👥 [Cadastros](../index.md) > **📦 Produtos**

#cadastros #produtos #servicos #estoque #fiscal #preco #passo-a-passo

---

## 🎯 O que é o Cadastro de Produtos?

O **Cadastro de Produtos e Serviços** é o **coração do seu sistema ERP**. Aqui você registra tudo o que vende: produtos físicos, serviços, kits, composições e muito mais. É a base para:

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
3. Clique no botão **"+ Adicionar" em seguida "+ Produto"** 

### **Passo 2: 📋 Dados Básicos**

- **Nome do Produto**: Nome completo do produto
- **Formato**: Simples, Variação ou Composto
- **Unidade**: Unidade de medida (UN, KG, M, L, etc.)
- **SKU do produto**: Codigo interno ou opção para gerar um aleatório
- **Preço de Custo**: Quanto você paga pelo produto
- **% Margem no varejo**: Calcula automaticamente
- **Preço de Varejo**: Quanto você cobra do cliente
- **Qtd. Min. Atacado**: Defenir uma quantidade minina para vendas em maior quantidade.
- **% Margem no Atacado**: Calculo automaticamente
- **Preço de Atacado**: Quando cobra do cliente em vendas com maior quantidade
- **Categoria**: Grupo principal (ex: Ração, Brinquedos, Roupas)
- **Estoque Mínimo**: Alerta de reposição
- **Estoque Máximo**: Limite de compra
- **Estoque Atual**: Quantidade disponível
- **Descrição Alternativa**: Complementar ao nome do produto
- **Código de Barras**: EAN/UPC para leitura no PDV
- **Status**: Define produto ativo ou inativo
- **Controla Estoque**: Sim/Não
- **Imagem Principal**: Imagem do produto, usado em ecommerces e PDV

**Passo 3: **📋 Caracteristicas**
- **Marca**: Fabricante do produto
- **Modelo**: Tipo do produto
- **Campos de caracteristicas do produto**: Peso Liquido / Peso Bruto / Volume / Profundidade / Altura / Largura / Comprimento / Data de validade

### **Passo 4: Fatores de Conversão**
- **+ Adicionar Fator**: Definir a forma de controle que recebe o produto em nota de compra. Para como irá converter para o estoque da empresa. 

Exemplo: 
Qtde compra: 1 caixa
Qtade estoque: 12 unidade

### **Passo 5: Tributação**
- **Tipo do Item**: Tipo do produto (revenda/uso e consumo/matéria-prima...)
- **Origem ICMS**: Nacional, Importado, etc.
- **CEST**: Código Especificador da Substituição Tributária
- **NCM**: Nomenclatura Comum do Mercosul

### **Passo 6: Informações Adicionais**
- **Campos complementares de Descrição**: Descrição Curta / Complementar / Observações

### **Passo 7: Fornecedores**
- **+ Adicionar Fornecedor**: Vincular os fornecedores do produto

### **Passo 8: Imagens**
- **Escolher Arquivos**: Imagens secundárias do produto

### **Passo 9: Salvar**
- Clique em **"Salvar"** para finalizar
- O produto estará disponível para venda imediatamente

---

## 🎯 Tipos de Produtos


### 📋 **Kit/Composição**

**Características:**
- Agrupa vários produtos
- Preço único ou soma dos itens
- Controla estoque dos componentes e item principal

**Exemplo:**
```
Kit Higiene Femenina:
- 1x Shampoo Neutro
- 1x Condicionador
- 1x Escova
Preço Kit: R$ 35,00 
```
### 📋 **Variação**

**Caracteristicas**
- Facilidade em cadastro de itens iguais com cores / tamanhos / genêros diferentes

**Exemplo:**
```
**Camiseta**
- **Variação 1**: Cor (Azul, Vermelho, Verde)
- **Variação 2**: Tamanho (P, M, G, GG)
- **Resultado**: 12 produtos diferentes
 ```
### **🔧 Como Configurar**
1. **Cadastre o produto pai** (Camiseta Básica)
2. **Defina os atributos** (Cor, Tamanho)
3. **Crie as variações** automaticamente
4. **Ajuste preços** se necessário
5. **Configure estoque** individual
---

## 🏷️ Códigos de Barras e SKU

### **📊 Código de Barras**
- **EAN-13**: Padrão internacional (13 dígitos)
- **EAN-8**: Versão reduzida (8 dígitos)
- **Código 128**: Para produtos internos

### **🔤 SKU (Stock Keeping Unit)**
- **Código interno** único para cada produto
- **Padrão sugerido**: CAT-MARCA-MODELO-VAR
- **Exemplo**: CONJ-BIA-TAMP

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

---

### **🖼️ Dicas Fotos de Produtos**
**Especificações recomendadas:**
- **Formato**: JPG ou PNG
- **Tamanho**: 800x800 pixels
- **Peso**: Máximo 2MB
- **Fundo**: Preferencialmente branco
- **Qualidade**: Alta definição

### **💡 Dicas Fiscais**
1. **Consulte sempre** um contador para NCM
2. **Mantenha atualizado** com mudanças da legislação
3. **Use códigos corretos** para evitar multas
4. **Documente** as justificativas fiscais

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
2. Incluir **impostos no cálculo**
3. Considerar **despesas operacionais**

---

## 🎯 Checklist de Cadastro

### ✅ **Informações Gerais**
- [ ] Código do produto definido
- [ ] Descrição clara e completa
- [ ] Preço de custo informado
- [ ] Preço de venda calculado
- [ ] Unidade de medida selecionada
- [ ] Categoria atribuída
- [ ] Status ativo marcado

### ✅ **Informações Fiscais**
- [ ] NCM correto informado
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
2. **Implemente Kits/Composições** de produto

### 🚀 **Para Especialistas**
1. **Desenvolva regras** de precificação
2. **Implemente controle** de lote
3. **Configure relatórios** personalizados

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
- **Cadastro Básico**: Como cadastrar seu primeiro produto (https://www.youtube.com/watch?v=7FP0nuVIr1c)
---

**💡 Dica Final**: O cadastro de produtos é um investimento. Quanto mais completo e organizado, mais fácil será gerenciar seu negócio. Dedique tempo para fazer bem feito!

---

**Tags relacionadas**: #cadastros #produtos #servicos #estoque #fiscal #preco #passo-a-passo #codigo-barras #variacao 