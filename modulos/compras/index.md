# 🛒 Módulo: Gestão de Compras

🏠 [Home](../../index.md) > 📋 [Módulos](../index.md) > **Gestão de Compras**

#compras #modulo #intermediario #gestao

---

## 📋 O que é

O módulo de **Gestão de Compras** é responsável por centralizar e automatizar todo o processo de aquisição de produtos da empresa. Este módulo permite controlar desde a cotação de preços até o recebimento de mercadorias, garantindo maior eficiência, controle de custos e organização nas compras.

{% hint style="info" %}
**💡 Benefícios**: Controle total do processo de compras, redução de custos, melhor relacionamento com fornecedores e maior agilidade nas aquisições.
{% endhint %}

## 🎯 Principais Funcionalidades

<table data-view="cards">
<thead>
<tr>
<th></th>
<th></th>
<th data-hidden data-card-target data-type="content-ref"></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>📝 Cotações de Preços</strong></td>
<td>Gerencie cotações de fornecedores de forma organizada</td>
<td></td>
</tr>
<tr>
<td><strong>📋 Pedidos de Compra</strong></td>
<td>Crie e acompanhe pedidos de compra automaticamente</td>
<td></td>
</tr>
<tr>
<td><strong>📦 Recebimento</strong></td>
<td>Controle o recebimento de mercadorias e serviços</td>
<td></td>
</tr>
<tr>
<td><strong>📊 Relatórios</strong></td>
<td>Análises completas de compras e performance</td>
<td></td>
</tr>
</tbody>
</table>

## 🚀 Como Acessar

{% stepper %}
{% step %}
### Acesso ao Módulo
1. No menu principal, clique em **"Módulos"**
2. Selecione **"Compras"**
3. Escolha a funcionalidade desejada no submenu
{% endstep %}

## Notas de Entrada 
**+ Nova Compra**: Lançamento de forma manual, preenchendo os campos: 
- Fornecedor: Empresa da qual receber a compra
- Natureza de Operação: Define como "Entrada de Mercadoria"
- Datas: De Emissão e Entrada.
- **Frete**: Incluir a transportadora e tipo/ valor do frete. 

**OBS**: Para adicionar os itens, clicar em Salvar. 

- **Produtos**: incluir todos os itens da compra para movimentar a entrada do estoque
- **Impostos**: Preencher com as informações de impostos da nota do fornecedor
- **Financeiro**: Gerar o Contas a Pagar, referente a nota de entrada

## Notas de Entrada por Importaçao da Receita Federal
- **Importação a partir de**:
- **XML**: Fazer upload do arquivo xml da nota fiscal
- **Receita (DF-e)**: Realizar uma consulta no servidor da sefaz, buscando notas emitidas contra seu CNPJ
- **Chave da NF**: Consultar uma unica nota com sua chave de acesso (numero da 44 digitos da nota fiscal)


### 📋 Pedidos de Compra
- **Novo Pedido**: Fazer cotação com diferentes fornecedores, incluindo transportadoras, itens desejados, e forma de negociação do pagamento.
- **Controle de status** (pendente, aprovado, enviado, recebido)

### 📦 Recebimento de Mercadorias
- **Conferência de quantidade** e qualidade
- **Registro de divergências**
- **Integração com estoque**
- **Documentação fiscal**


## 🔧 Configurações Necessárias

{% hint style="warning" %}
**⚠️ Pré-requisitos**: Antes de usar o módulo, certifique-se de que os seguintes itens estão configurados:
{% endhint %}

- ✅ **Cadastro de fornecedores** atualizado
- ✅ **Cadastro de produtos** completo
- ✅ **Parâmetros de compra** definidos
- ✅ **Usuários e permissões** configurados

## 💡 Casos de Uso Comuns

### 🏪 Comércio Varejista
- Reposição automática de estoque
- Compras sazonais programadas
- Gestão de fornecedores locais

### 🏭 Indústria
- Compra de matéria-prima
- Equipamentos e manutenção
- Serviços especializados

### 🏢 Prestação de Serviços
- Material de escritório
- Equipamentos de TI
- Serviços terceirizados

## 🚨 Pontos de Atenção

{% hint style="danger" %}
**🚨 Importante**: Sempre verifique as condições de pagamento e prazo de entrega antes de finalizar pedidos de compra.
{% endhint %}

{% hint style="warning" %}
**⚠️ Atenção**: Mantenha os dados de fornecedores sempre atualizados para evitar problemas na comunicação e entrega.
{% endhint %}

## 🔐 Permissões e Segurança

### 👤 Níveis de Acesso
- **Consulta**: Visualizar  pedidos
- **Operacional**: Criar e editar pedidos
- **Aprovação**: Aprovar compras até determinado valor
- **Gerencial**: Acesso total ao módulo

## 📊 Relatórios Disponíveis


### 📋 Relatórios Operacionais
- **Pedidos em aberto**
- **Cotações válidas**
- **Recebimentos pendentes**
- **Divergências encontradas**

## 🔍 Integração com Outros Módulos

O módulo de Compras integra-se perfeitamente com:

- **📦 Estoque**: Entrada automática de mercadorias
- **💰 Financeiro**: Contas a pagar e fluxo de caixa
- **👥 Cadastros**: Fornecedores e produtos
- **📊 Contabilidade**: Lançamentos contábeis
- **🚚 Transportes**: Logística de entrega

---

## 📚 Documentação Relacionada

{% content-ref url="../cadastros/cadastro-de-fornecedores.md" %}
cadastro-de-fornecedores.md
{% endcontent-ref %}

{% content-ref url="../cadastros/cadastro-de-produtos.md" %}
cadastro-de-produtos.md
{% endcontent-ref %}

{% content-ref url="../financeiro/contas-a-pagar.md" %}
contas-a-pagar.md
{% endcontent-ref %}

{% content-ref url="../estoque/entrada-mercadorias.md" %}
entrada-mercadorias.md
{% endcontent-ref %}

## 🏷️ Tags
`#compras` `#modulo` `#intermediario` `#gestao` `#fornecedores` `#cotacao` `#pedidos` `#recebimento`

---

**Última atualização**: Setembro 2025  
**Versão do documento**: 1.0  
**Responsável**: Equipe de Documentação White ERP
