# 📦 Cadastro de Produtos

🏠 [Home](../../index.md) > 📋 [Módulos](../index.md) > 👥 [Cadastros](index.md) > **Produtos**

#cadastros #produto #estoque #passo-a-passo #importante

## 📋 O que é

O **Cadastro de Produtos** é onde você mantém seu catálogo completo de produtos e serviços. Este é o coração do seu negócio, pois aqui você define:

- **Informações Básicas** - Nome, descrição, categoria
- **Preços** - Custo, venda, margem de lucro
- **Estoque** - Quantidade, mínimo, máximo
- **Códigos** - Barras, referência, SKU
- **Dados Fiscais** - NCM, CFOP, impostos
- **Variações** - Cor, tamanho, modelo

## 🚀 Como Fazer

### Passo 1: Acessar o Módulo
1. No menu principal, clique em **"Cadastros"**
2. Selecione **"Produtos"**
3. Clique no botão **"Novo Produto"** (ícone +)

### Passo 2: Definir Tipo do Item
- **Produto**: Item físico com controle de estoque
- **Serviço**: Prestação de serviço sem estoque
- **Produto Digital**: Downloads, licenças, etc.

> **💡 Dica**: Escolha o tipo correto pois isso afeta o comportamento do sistema.

### Passo 3: Informações Básicas

#### 📝 **Identificação**
- **Código do Produto**: Código interno único (gerado automaticamente)
- **Código de Barras**: EAN, UPC ou código personalizado
- **Código de Referência**: Seu código interno personalizado
- **SKU**: Stock Keeping Unit (opcional)

#### 📋 **Descrição**
- **Nome do Produto**: Nome comercial (obrigatório)
- **Descrição Curta**: Resumo para PDV e relatórios
- **Descrição Completa**: Detalhes para e-commerce
- **Marca**: Fabricante ou marca do produto
- **Modelo**: Modelo específico (opcional)

### Passo 4: Categorização
- **Categoria**: Classificação principal (Ração, Brinquedos, etc.)
- **Subcategoria**: Classificação específica (Ração Cães, Ração Gatos)
- **Tags**: Etiquetas para busca (#promocao, #novidade, #sazonal)
- **Localização**: Prateleira, corredor, depósito

### Passo 5: Preços e Custos

#### 💰 **Custos**
- **Preço de Custo**: Valor pago ao fornecedor
- **Custo Adicional**: Frete, impostos, etc.
- **Custo Total**: Custo + Custo Adicional (calculado automaticamente)

#### 💲 **Preços de Venda**
- **Preço de Venda**: Valor para o cliente final
- **Margem de Lucro**: Percentual calculado automaticamente
- **Markup**: Multiplicador sobre o custo

> **💡 Dica**: O sistema calcula automaticamente margem e markup conforme você digita.

### Passo 6: Controle de Estoque

#### 📊 **Quantidades**
- **Estoque Atual**: Quantidade disponível
- **Estoque Mínimo**: Alerta quando atingir este valor
- **Estoque Máximo**: Limite para compras
- **Ponto de Pedido**: Quando fazer nova compra

#### 📦 **Unidades de Medida**
- **Unidade de Venda**: UN, KG, MT, LT, etc.
- **Unidade de Compra**: Pode ser diferente da venda
- **Fator de Conversão**: Relação entre unidades

### Passo 7: Informações Fiscais

#### 🏛️ **Códigos Fiscais**
- **NCM**: Nomenclatura Comum do Mercosul
- **CEST**: Código Especificador da Substituição Tributária
- **CFOP**: Código Fiscal de Operações e Prestações
- **CST**: Código de Situação Tributária

#### 💼 **Impostos**
- **ICMS**: Alíquota do ICMS
- **IPI**: Alíquota do IPI
- **PIS**: Alíquota do PIS
- **COFINS**: Alíquota do COFINS

### Passo 8: Fornecedores
- **Fornecedor Principal**: Fornecedor padrão
- **Fornecedores Alternativos**: Outros fornecedores
- **Código do Fornecedor**: Código do produto no fornecedor
- **Prazo de Entrega**: Tempo para recebimento

### Passo 9: Imagens e Mídia
- **Imagem Principal**: Foto principal do produto
- **Imagens Adicionais**: Múltiplas fotos
- **Vídeo**: Link para vídeo demonstrativo
- **Manual/Ficha**: Anexar documentos

### Passo 10: Salvar o Produto
1. Revise todas as informações
2. Clique em **"Salvar"**
3. O sistema confirma o cadastro

## 🔧 Funcionalidades Avançadas

### 🎨 **Produtos com Variações**
Para produtos que têm variações (cor, tamanho, modelo):

1. **Ativar Variações** no cadastro principal
2. **Definir Atributos**: Cor, Tamanho, Modelo
3. **Criar Combinações**: Azul P, Azul M, Azul G, etc.
4. **Preços Específicos**: Cada variação pode ter preço diferente
5. **Estoque Individual**: Controle separado por variação

### 📦 **Kits e Composições**
Para produtos compostos por outros produtos:

1. **Ativar Composição** no cadastro
2. **Adicionar Componentes**: Produtos que compõem o kit
3. **Definir Quantidades**: Quantidade de cada componente
4. **Preço do Kit**: Pode ser diferente da soma dos componentes
5. **Estoque Automático**: Baseado nos componentes

### 💰 **Tabelas de Preços**
Para preços diferenciados por cliente:

1. **Criar Tabelas**: Varejo, Atacado, VIP
2. **Definir Preços**: Preço específico por tabela
3. **Vincular Clientes**: Associar cliente à tabela
4. **Aplicação Automática**: Sistema aplica preço correto

## 💡 Casos de Uso

### 🐕 **Caso 1: Ração para Cães**
**Situação**: Cadastrar ração com múltiplas variações.

**Passo a passo**:
1. Nome: "Ração Premier Cães Adultos"
2. Categoria: "Ração" > "Cães"
3. Ativar variações: Peso (1kg, 3kg, 15kg)
4. Preços diferentes por peso
5. Estoque individual por variação
6. NCM: 2309.10.00
7. Fornecedor: Premier Pet
8. Salvar

### 🧸 **Caso 2: Kit de Brinquedos**
**Situação**: Kit com 3 brinquedos diferentes.

**Passo a passo**:
1. Nome: "Kit Brinquedos Cães"
2. Tipo: Produto composto
3. Componentes:
   - Bolinha de borracha (1 un)
   - Corda colorida (1 un)
   - Osso de couro (1 un)
4. Preço do kit: R$ 25,00
5. Estoque baseado no componente com menor quantidade
6. Salvar

### 💊 **Caso 3: Medicamento Veterinário**
**Situação**: Produto controlado com lote e validade.

**Passo a passo**:
1. Nome: "Antibiótico Veterinário XYZ"
2. Categoria: "Medicamentos"
3. Ativar controle de lote
4. Ativar controle de validade
5. NCM específico para medicamentos
6. Fornecedor: Laboratório ABC
7. Observações: "Receita veterinária obrigatória"
8. Salvar

## 🔍 Busca e Filtros

### 🔎 **Formas de Buscar Produtos**
- **Por Nome**: Digite parte do nome
- **Por Código**: Código interno ou de barras
- **Por Categoria**: Filtre por categoria
- **Por Marca**: Produtos de uma marca específica
- **Por Fornecedor**: Produtos de um fornecedor
- **Por Tags**: Use #tag para filtrar

### 🏷️ **Filtros Avançados**
- **Status**: Ativo/Inativo
- **Tipo**: Produto/Serviço
- **Estoque**: Com estoque/Sem estoque/Estoque baixo
- **Preço**: Faixa de preços
- **Categoria**: Múltiplas categorias
- **Fornecedor**: Múltiplos fornecedores

## 📊 Relatórios Disponíveis

### 📈 **Relatórios Básicos**
- **Catálogo de Produtos**: Lista completa
- **Produtos por Categoria**: Organizado por categoria
- **Produtos em Falta**: Estoque zerado
- **Produtos com Estoque Baixo**: Abaixo do mínimo

### 📊 **Relatórios Avançados**
- **Produtos Mais Vendidos**: Ranking por vendas
- **Análise de Margem**: Rentabilidade por produto
- **Curva ABC**: Classificação por importância
- **Produtos Inativos**: Sem movimento há X dias

## 🚨 Alertas e Validações

### ⚠️ **Validações Automáticas**
- **Código de Barras**: Validação de formato
- **NCM**: Formato correto
- **Preços**: Não podem ser negativos
- **Estoque**: Não pode ser negativo (configurável)

### 🔔 **Alertas Importantes**
- **Estoque Baixo**: Produtos abaixo do mínimo
- **Sem Preço**: Produtos sem preço de venda
- **Sem Fornecedor**: Produtos sem fornecedor
- **Validade Vencida**: Produtos com validade vencida

## 🔄 Integrações

### 🌐 **E-commerce**
- **Sincronização Automática**: Produtos para loja online
- **Imagens**: Upload automático de fotos
- **Preços**: Sincronização de preços
- **Estoque**: Atualização em tempo real

### 📱 **Código de Barras**
- **Leitura**: Leitor de código de barras
- **Geração**: Criar códigos para produtos sem código
- **Etiquetas**: Impressão de etiquetas

### 📊 **Sistemas Externos**
- **Fornecedores**: Importação de catálogos
- **Contabilidade**: Exportação para sistemas contábeis
- **Marketplaces**: Integração com Mercado Livre, etc.

## 📋 Checklist de Boas Práticas

### ✅ **Antes de Cadastrar**
- [ ] Tenha informações completas do produto
- [ ] Defina categoria apropriada
- [ ] Pesquise NCM correto
- [ ] Tenha fotos de qualidade

### ✅ **Durante o Cadastro**
- [ ] Preencha descrição completa
- [ ] Configure preços corretamente
- [ ] Defina estoque mínimo
- [ ] Adicione código de barras

### ✅ **Após o Cadastro**
- [ ] Teste busca do produto
- [ ] Verifique cálculo de preços
- [ ] Confirme dados fiscais
- [ ] Treine equipe sobre novos produtos

## 🆘 Troubleshooting

### 🔧 **Problemas Comuns**

#### **Erro: Código de Barras Duplicado**
- **Causa**: Código já existe no sistema
- **Solução**: Verifique se não é o mesmo produto ou use código diferente
- **Prevenção**: Sempre busque antes de cadastrar

#### **Erro: NCM Inválido**
- **Causa**: Código NCM incorreto
- **Solução**: Consulte tabela oficial do NCM
- **Prevenção**: Use ferramenta de busca de NCM

#### **Erro: Preço Negativo**
- **Causa**: Preço inserido com valor negativo
- **Solução**: Insira valor positivo
- **Prevenção**: Valide dados antes de salvar

## 🎯 Próximos Passos

Após cadastrar seus produtos:

1. **[[modulos/estoque/entrada-produtos]]** - Registre entrada de estoque
2. **[[modulos/vendas/pdv]]** - Realize vendas
3. **[[modulos/compras/pedido-compra]]** - Faça reposição
4. **[[relatorios-produtos]]** - Analise performance

## 📚 Documentação Relacionada

- **[[gestao-variacoes-produtos]]** - Produtos com variações
- **[[composicao-kits]]** - Kits e produtos compostos
- **[[tabelas-precos]]** - Preços diferenciados
- **[[controle-estoque]]** - Gestão de estoque

---

**Tags relacionadas**: #cadastros #produto #estoque #passo-a-passo #importante

**Veja também**: [[cadastro-de-fornecedores]] | [[controle-estoque]] | [[pdv]]

---

*💡 **Dica**: Um catálogo bem organizado é essencial para vendas eficientes. Invista tempo na qualidade das informações e imagens dos produtos!* 