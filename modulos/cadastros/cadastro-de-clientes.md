# 👥 Cadastro de Clientes

🏠 [Home](../../index.md) > 📋 [Módulos](../index.md) > 👥 [Cadastros](index.md) > **Clientes**

#cadastros #cliente #passo-a-passo #iniciante #importante

## 📋 O que é

O **Cadastro de Clientes** é onde você mantém todas as informações dos seus clientes, sejam pessoas físicas ou jurídicas. Este cadastro é fundamental para:

- **Vendas no PDV** - Identificar cliente e aplicar condições especiais
- **Emissão de Notas Fiscais** - Dados corretos para documentos fiscais
- **Controle de Crédito** - Limites e histórico de pagamentos
- **Relatórios Gerenciais** - Análises de performance e relacionamento

## 🚀 Como Fazer

### Passo 1: Acessar o Módulo
1. No menu principal, clique em **"Cadastros"**
2. Selecione **"Clientes"**
3. Clique no botão **"Adicionar Cliente"** (ícone +)

### Passo 2: Escolher o Tipo de Pessoa
- **Pessoa Física**: Para clientes individuais (CPF)
- **Pessoa Jurídica**: Para empresas (CNPJ)

### Passo 3: Preencher Dados Básicos

#### 📄 **Para Pessoa Física**
- **CPF**: Digite apenas números (validação automática)
- **Nome Completo**: Nome civil do cliente
- **Data de Nascimento**: Para controle de idade e aniversários
- **Sexo**: Masculino/Feminino/Não informado

#### 🏢 **Para Pessoa Jurídica**
- **CNPJ**: Digite apenas números (validação automática)
- **Razão Social**: Nome oficial da empresa
- **Nome Fantasia**: Nome comercial (opcional)
- **Inscrição Estadual**: IE ou "ISENTO"
- **Inscrição Municipal**: IM (se aplicável)

> **Dica**: Campo "É Contribuinte ICMS": 
> - Para clientes PJ: preencher como Contribuinte ICMS ou Isento.
> - Para clientes PF: preencher como Não Contribuinte

### Passo 4: Endereço Completo
- **CEP**: Digite e clique em Pesquisar para busca automática
- **Logradouro**: Rua, avenida, etc.
- **Número**: Número da residência/empresa
- **Complemento**: Apartamento, sala, etc. (opcional)
- **Bairro**: Preenchido automaticamente pelo CEP
- **Cidade**: Preenchida automaticamente pelo CEP
- **Estado**: Preenchido automaticamente pelo CEP

> **💡 Dica**: Use a busca por CEP para agilizar o preenchimento.

### Passo 5: Informações de Contato
- **Telefone Principal**: Celular ou fixo (obrigatório)
- **Telefone Secundário**: Segundo contato (opcional)
- **Email**: Para envio de documentos e comunicações
- **WhatsApp**: Para comunicação direta

> **⚠️ Atenção**: Email é obrigatório para envio automático de boletos e notas fiscais.

### Passo 6: Outras Informações (opcionais)
- **Dados Bancários**: Se optar por pedir os dados do banco do cliente.
- **Dados Contabilidade**: Se o cliente for PJ, e optar por ter o contato da contabilidade.

### Passo 8: Salvar o Cadastro
1. Revise todas as informações
2. Clique em **"Salvar"**
3. O sistema confirma o cadastro com um número único (ID)


## 🔧 Funcionalidades Avançadas

### 💳 **Controle de Crédito**
- **Limite de Crédito**: Define um valor limite para financeiro a receber
- **Bloqueio Automático**: Sistema bloqueia vendas quando limite é atingido
- **Histórico de Financeiro**: Veja o comportamento do cliente
- **Alertas**: Alertar Pop-up, com a mensagem do campo Observações.

### 📊 **Histórico de Relacionamento**
- **Vendas Realizadas**: Todas as compras do cliente

## 💡 Casos de Uso

### 🛍️ **Caso 1: Cliente Pessoa Física**
**Situação**: Maria Silva quer comprar produtos para seu pet.

**Passo a passo**:
1. Selecione "Pessoa Física"
2. Digite CPF: 12345678901
3. Nome: Maria Silva
4. Telefone: (11) 99999-9999
5. Email: maria@email.com
6. Endereço completo
7. Limite de crédito: R$ 500,00
8. Salvar

### 🏢 **Caso 2: Cliente Pessoa Jurídica**
**Situação**: Empresa de Manutenção Industrial precisa comprar equipamentos para serviços.

**Passo a passo**:
1. Selecione "Pessoa Jurídica"
2. Digite CNPJ: 12345678000123
3. Razão Social: Manutenção Industrial Ltda
4. Nome Fantasia: Manutenção Pro
5. Inscrição Estadual: 123456789
6. Contatos e endereço
7. Limite de crédito: R$ 5.000,00
8. Categoria: Atacado
9. Salvar

### 🚀 **Caso 3: Cadastro Rápido no PDV**
**Situação**: Cliente novo no balcão, venda urgente.

**Passo a passo**:
1. No PDV, clique em "Referenciar Cliente"
2. Preencha apenas campos obrigatórios:
   - CPF/CNPJ
   - Nome
   - Telefone
3. Clique em "Salvar"
4. Complete os dados depois

## 🔍 Busca e Filtros

### 🔎 **Formas de Buscar Clientes**
- **Por Nome**: Digite parte do nome
- **Por CPF/CNPJ**: Digite o documento
- **Por ID**: Código gerado no sistema
- **Status**: Ativo/Inativo

## 📊 Relatórios Disponíveis

### 📈 **Relatórios Básicos**
- **Lista de Clientes**: Todos os clientes cadastrados
- **Clientes por Categoria**: Segmentação
- **Clientes por Cidade**: Distribuição geográfica
- **Aniversariantes do Mês**: Para campanhas


## 🚨 Alertas e Validações

### ⚠️ **Validações Automáticas**
- **CPF/CNPJ**: Validação de dígitos verificadores
- **Email**: Formato válido de email
- **Telefone**: Formato correto de telefone
- **CEP**: Existência do CEP

## 🔐 Permissões e Segurança

### 👥 **Perfis de Acesso**
- **Vendedor**: Pode cadastrar e consultar clientes
- **Gerente**: Pode alterar limites de crédito
- **Financeiro**: Pode bloquear/desbloquear clientes
- **Administrador**: Acesso total

### 🛡️ **Segurança dos Dados**
- **Criptografia**: Dados sensíveis criptografados
- **Auditoria**: Log de todas as alterações
- **Backup**: Backup automático diário
- **LGPD**: Conformidade com Lei Geral de Proteção de Dados

## 🆘 Troubleshooting

### 🔧 **Problemas Comuns**

#### **Erro: CPF/CNPJ Inválido**
- **Causa**: Dígitos verificadores incorretos
- **Solução**: Verifique os números e digite novamente
- **Prevenção**: Use os dados de documentos oficiais

#### **Erro: Email Duplicado**
- **Causa**: Email já cadastrado para outro cliente
- **Solução**: Verifique se não é o mesmo cliente ou use email alternativo
- **Prevenção**: Sempre busque antes de cadastrar

#### **Erro: CEP Não Encontrado**
- **Causa**: CEP inexistente ou incorreto
- **Solução**: Verifique o CEP ou preencha manualmente
- **Prevenção**: Confirme o CEP com o cliente

### 📞 **Quando Buscar Ajuda**
- **Erro de validação**: Verifique os dados primeiro
- **Problema de integração**: Contate o suporte
- **Dúvida sobre funcionalidade**: Consulte esta documentação
- **Erro do sistema**: Anote a mensagem e contate o suporte

## 🔄 Integrações

### 🌐 **E-commerce**
- **Sincronização Automática**: Clientes da loja online
- **Unificação de Dados**: Mesmo cliente, múltiplos canais
- **Histórico Integrado**: Compras online e física

## 📋 Checklist de Boas Práticas

### ✅ **Antes de Cadastrar**
- [ ] Busque se o cliente já existe
- [ ] Tenha os documentos em mãos
- [ ] Confirme dados de contato

### ✅ **Durante o Cadastro**
- [ ] Preencha todos os campos obrigatórios
- [ ] Valide CPF/CNPJ
- [ ] Confirme email e telefone
- [ ] Use CEP para busca automática de endereço

### ✅ **Após o Cadastro**
- [ ] Teste envio de email
- [ ] Configure limite de crédito
- [ ] Adicione tags relevantes
- [ ] Treine a equipe sobre o novo cliente

## 🎯 Próximos Passos

Após cadastrar seus clientes:

1. **[Cadastro De Produtos](cadastro-de-produtos.md)** - Cadastre seus produtos
2. **[PDV - Ponto de Venda](modulos/vendas/pdv.md)** - Realize sua primeira venda
3. **[Contas a Receber](modulos/financeiro/contas-a-receber.md)** - Acompanhe recebimentos
4. **[Relatorios Clientes](relatorios-clientes.md)** - Analise seus dados

## 📚 Documentação Relacionada

- **[Cadastro Rapido Pdv](cadastro-rapido-pdv.md)** - Cadastro rápido no ponto de venda
- **[Gestao Credito Debito](gestao-credito-debito.md)** - Controle de limite de crédito
- **[Cadastro De Ordens Servico](cadastro-de-ordens-servico.md)** - Para clientes de serviços
- **[Fluxo Vendas Completo](fluxo-vendas-completo.md)** - Fluxo completo de vendas

---

**Tags relacionadas**: #cadastros #cliente #passo-a-passo #iniciante #importante

**Veja também**: [Cadastro De Fornecedores](cadastro-de-fornecedores.md) | [Cadastro De Produtos](cadastro-de-produtos.md) | [Pdv](pdv.md)

---

*💡 **Dica**: Um cadastro completo e correto de clientes é a base para todas as operações do sistema. Invista tempo na qualidade dos dados!* 