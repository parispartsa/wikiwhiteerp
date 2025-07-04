# ⚙️ Configuração Inicial do Sistema

🏠 [Home](../../index.md) > 🎓 [Guias](../guias/index.md) > **⚙️ Configuração Inicial**

#configuracao #inicial #setup #fundamental #passo-a-passo #obrigatorio

---

## 🎯 Objetivo deste Guia

Este guia te ajudará a **configurar o ERP White** do zero, seguindo a **sequência correta** para que tudo funcione perfeitamente desde o primeiro dia. É o **ponto de partida obrigatório** para qualquer empresa.

### ⏱️ **Tempo estimado**: 4-6 horas
### 👥 **Quem deve fazer**: Administrador do sistema
### 📋 **Pré-requisitos**: Acesso de administrador ao sistema

> **⚠️ Importante**: Siga a ordem exata das configurações. Algumas dependem de outras para funcionar corretamente!

---

## 📋 Checklist Geral de Configuração

### ✅ **Etapa 1: Dados da Empresa** (30 min)
- [ ] Informações básicas da empresa
- [ ] Dados fiscais (CNPJ, IE, IM)
- [ ] Endereço completo
- [ ] Contatos (telefone, email, site)
- [ ] Logo da empresa

### ✅ **Etapa 2: Configurações Fiscais** (45 min)
- [ ] Regime tributário
- [ ] Certificado digital
- [ ] Série de notas fiscais
- [ ] Códigos fiscais padrão
- [ ] Alíquotas de impostos

### ✅ **Etapa 3: Usuários e Permissões** (30 min)
- [ ] Perfis de acesso
- [ ] Usuários da equipe
- [ ] Permissões específicas
- [ ] Senhas e segurança

### ✅ **Etapa 4: Formas de Pagamento** (20 min)
- [ ] Dinheiro, cartão, PIX, boleto
- [ ] Taxas e prazos
- [ ] Integração TEF
- [ ] Configuração de parcelamento

### ✅ **Etapa 5: Contas Bancárias** (15 min)
- [ ] Contas da empresa
- [ ] Dados para boleto
- [ ] Configuração PIX
- [ ] Integração bancária

### ✅ **Etapa 6: Estrutura de Produtos** (45 min)
- [ ] Categorias e subcategorias
- [ ] Unidades de medida
- [ ] Marcas e fornecedores
- [ ] Localizações de estoque

### ✅ **Etapa 7: Primeiros Cadastros** (60 min)
- [ ] 5-10 produtos principais
- [ ] 2-3 fornecedores principais
- [ ] 3-5 clientes frequentes
- [ ] Funcionários/vendedores

### ✅ **Etapa 8: Configurações Finais** (30 min)
- [ ] Parâmetros do sistema
- [ ] Backup automático
- [ ] Relatórios padrão
- [ ] Integrações básicas

---

## 🏢 Etapa 1: Dados da Empresa

### **📋 Informações Básicas**

#### **Passo 1: Acessar Configurações**
1. No menu principal, clique em **"Configurações"**
2. Selecione **"Dados da Empresa"**
3. Clique em **"Editar"**

#### **Passo 2: Preencher Dados Básicos**
```
Razão Social: [Nome completo da empresa]
Nome Fantasia: [Nome comercial]
CNPJ: [14 dígitos sem pontuação]
Inscrição Estadual: [Número da IE]
Inscrição Municipal: [Número da IM, se houver]
```

#### **Passo 3: Endereço Completo**
```
CEP: [8 dígitos]
Logradouro: [Rua, avenida, etc.]
Número: [Número do estabelecimento]
Complemento: [Sala, andar, etc.]
Bairro: [Nome do bairro]
Cidade: [Nome da cidade]
Estado: [UF - 2 letras]
```

#### **Passo 4: Contatos**
```
Telefone: [(xx) xxxx-xxxx]
Celular/WhatsApp: [(xx) 9xxxx-xxxx]
Email: [email@empresa.com.br]
Site: [www.empresa.com.br]
```

#### **Passo 5: Upload do Logo**
- **Formato**: PNG ou JPG
- **Tamanho**: 300x300 pixels (recomendado)
- **Peso**: Máximo 2MB
- **Fundo**: Preferencialmente transparente

> **💡 Dica**: O logo aparecerá em notas fiscais, relatórios e no sistema. Use uma imagem de boa qualidade!

---

## 🏛️ Etapa 2: Configurações Fiscais

### **📄 Certificado Digital**

#### **Passo 1: Upload do Certificado**
1. Acesse **"Configurações" > "Fiscal" > "Certificado Digital"**
2. Clique em **"Importar Certificado"**
3. Selecione o arquivo **.pfx** do certificado
4. Digite a **senha** do certificado
5. Clique em **"Validar"**

#### **Passo 2: Verificar Validade**
- **Status**: Deve aparecer "Válido"
- **Vencimento**: Verifique a data de expiração
- **CNPJ**: Confirme se corresponde à empresa

### **📋 Regime Tributário**

#### **Configurar Regime**
```
☐ Simples Nacional
☐ Lucro Presumido  
☐ Lucro Real
☐ MEI (Microempreendedor Individual)
```

#### **Alíquotas por Regime**

**Simples Nacional:**
```
ICMS: Conforme anexo (varia por atividade)
ISS: Conforme município
PIS/COFINS: Inclusos no Simples
```

**Lucro Presumido:**
```
ICMS: Conforme estado (geralmente 18%)
ISS: Conforme município (2% a 5%)
PIS: 0,65%
COFINS: 3%
```

### **🔢 Numeração de Documentos**

#### **NFe (Nota Fiscal Eletrônica)**
```
Série: 1 (padrão)
Número Inicial: 1
Ambiente: Produção (após testes)
```

#### **NFCe (Nota Fiscal de Consumidor)**
```
Série: 1 (padrão)
Número Inicial: 1
CSC: [Código fornecido pela SEFAZ]
```

> **⚠️ Atenção**: Configure primeiro em ambiente de **homologação** para testes!

---

## 👥 Etapa 3: Usuários e Permissões

### **🔐 Perfis de Acesso**

#### **Perfis Padrão Recomendados**

**1. Administrador**
```
Permissões: Todas
Usuários: Proprietário, gerente geral
Características:
- Acesso total ao sistema
- Pode alterar configurações
- Visualiza todos os relatórios
```

**2. Gerente**
```
Permissões: Operacionais + relatórios
Usuários: Gerentes de setor
Características:
- Não altera configurações fiscais
- Acesso a relatórios gerenciais
- Pode aprovar descontos
```

**3. Vendedor**
```
Permissões: Vendas + clientes
Usuários: Vendedores, operadores PDV
Características:
- Foco em vendas e atendimento
- Acesso limitado a relatórios
- Não vê custos dos produtos
```

**4. Financeiro**
```
Permissões: Financeiro + relatórios
Usuários: Responsável financeiro
Características:
- Contas a pagar/receber
- Fluxo de caixa
- Relatórios financeiros
```

**5. Estoque**
```
Permissões: Estoque + compras
Usuários: Responsável estoque
Características:
- Movimentação de estoque
- Pedidos de compra
- Recebimento de mercadorias
```

### **👤 Criando Usuários**

#### **Passo 1: Acessar Usuários**
1. Vá em **"Configurações" > "Usuários"**
2. Clique em **"Novo Usuário"**

#### **Passo 2: Dados do Usuário**
```
Nome Completo: [Nome do funcionário]
Email: [email@empresa.com.br]
Login: [nome.sobrenome]
Senha: [Senha forte - min 8 caracteres]
Perfil: [Selecionar perfil apropriado]
Status: Ativo
```

#### **Passo 3: Configurações Específicas**
- **Vendedor**: Definir meta mensal
- **Comissão**: Percentual se aplicável
- **Departamento**: Setor de trabalho
- **Telefone**: Para contato

> **🔒 Segurança**: Use senhas fortes e oriente sobre não compartilhar credenciais!

---

## 💳 Etapa 4: Formas de Pagamento

### **💰 Configuração Básica**

#### **Dinheiro**
```
Nome: Dinheiro
Tipo: À vista
Taxa: 0%
Prazo: 0 dias
Desconto: 5% (opcional)
```

#### **PIX**
```
Nome: PIX
Tipo: À vista
Taxa: 0%
Prazo: 0 dias
Desconto: 3% (opcional)
```

#### **Cartão de Débito**
```
Nome: Débito
Tipo: À vista
Taxa: 2,5%
Prazo: 1 dia
Desconto: 2% (opcional)
```

#### **Cartão de Crédito**
```
Nome: Crédito
Tipo: Parcelado
Taxa: 3,5% (à vista) / 4,5% (parcelado)
Prazo: 30 dias (à vista) / 30 dias + parcelas
Parcelas: Até 12x
```

#### **Boleto**
```
Nome: Boleto
Tipo: A prazo
Taxa: 0%
Prazo: 7 a 30 dias
Juros: 2% ao mês
Multa: 2%
```

### **🏦 Configuração TEF**

#### **Passo 1: Dados da Operadora**
```
Operadora: [Stone, Cielo, Rede, etc.]
Código Estabelecimento: [Fornecido pela operadora]
Terminal: [Número do terminal]
```

#### **Passo 2: Configuração Técnica**
```
Porta Serial: COM1 (padrão)
Velocidade: 9600
Timeout: 30 segundos
```

#### **Passo 3: Teste de Conexão**
1. Clique em **"Testar Conexão"**
2. Realize uma **transação de teste**
3. Verifique se o **estorno** funciona

---

## 🏦 Etapa 5: Contas Bancárias

### **💰 Cadastro de Contas**

#### **Conta Principal**
```
Banco: [Banco do Brasil - 001]
Agência: [1234-5]
Conta: [12345-6]
Tipo: Conta Corrente
Saldo Inicial: [Valor atual]
```

#### **Configuração PIX**
```
Chave PIX: [CNPJ, email ou telefone]
Tipo: [CNPJ/Email/Telefone/Aleatória]
QR Code: [Gerado automaticamente]
```

#### **Dados para Boleto**
```
Código do Beneficiário: [Fornecido pelo banco]
Carteira: [17, 18, etc.]
Nosso Número: [Sequencial]
Instrução 1: "Não receber após vencimento"
Instrução 2: "Multa de 2% após vencimento"
```

### **🔗 Integração Bancária**

#### **Internet Banking**
```
URL do Banco: [Fornecida pelo banco]
Usuário: [Login do internet banking]
Senha: [Senha específica para integração]
```

#### **Arquivo de Retorno**
```
Layout: CNAB 240 ou CNAB 400
Pasta: [Definir pasta para arquivos]
Processamento: Automático
```

---

## 📦 Etapa 6: Estrutura de Produtos

### **🏷️ Categorias e Subcategorias**

#### **Exemplo para Prestação de Serviços**
```
Ração
├── Cães
│   ├── Filhote
│   ├── Adulto
│   └── Senior
├── Gatos
│   ├── Filhote
│   └── Adulto
└── Outros Pets

Acessórios
├── Coleiras
├── Brinquedos
└── Camas

Higiene
├── Shampoos
├── Condicionadores
└── Perfumes
```

#### **Exemplo para Comércio Geral**
```
Eletrônicos
├── Smartphones
├── Tablets
└── Acessórios

Roupas
├── Masculino
│   ├── Camisetas
│   ├── Calças
│   └── Calçados
└── Feminino
    ├── Blusas
    ├── Vestidos
    └── Calçados
```

### **📏 Unidades de Medida**

#### **Unidades Básicas**
```
UN - Unidade (padrão)
KG - Quilograma
LT - Litro
MT - Metro
M² - Metro Quadrado
CX - Caixa
PC - Peça
```

### **🏭 Marcas Principais**

#### **Cadastro de Marcas**
```
Nome: [Royal Canin]
Categoria: [Ração Premium]
Fornecedor: [Vincular fornecedor principal]
Status: Ativo
```

---

## 📋 Etapa 7: Primeiros Cadastros

### **📦 Produtos Essenciais**

#### **Produto 1: Exemplo Ração**
```
Código: 001
Descrição: Equipamento Industrial Modelo X1
Categoria: Ração > Cães > Adulto
Marca: Golden
Unidade: UN
Preço Custo: R$ 65,00
Preço Venda: R$ 89,90
Estoque Atual: 20
Estoque Mínimo: 5
NCM: 2309.10.00
```

#### **Produto 2: Exemplo Serviço**
```
Código: S001
Descrição: Banho e Tosa Completa
Categoria: Serviços > Higiene
Tipo: Serviço
Preço: R$ 45,00
Tempo: 120 minutos
Controla Estoque: Não
```

### **🏭 Fornecedores Principais**

#### **Fornecedor 1**
```
Razão Social: Distribuidora Pet Ltda
Nome Fantasia: Pet Distribuição
CNPJ: 12.345.678/0001-90
Email: pedidos@petdistribuicao.com.br
Telefone: (11) 3333-4444
Produtos: Ração, acessórios
Prazo Pagamento: 30 dias
```

### **👥 Clientes Importantes**

#### **Cliente 1: Pessoa Física**
```
Nome: João Silva
CPF: 123.456.789-10
Email: joao@email.com
Telefone: (11) 99999-8888
Endereço: Rua das Flores, 123
Limite Crédito: R$ 500,00
```

#### **Cliente 2: Pessoa Jurídica**
```
Razão Social: Empresa ABC Ltda
CNPJ: 98.765.432/0001-10
Email: compras@empresaabc.com.br
Telefone: (11) 2222-3333
Limite Crédito: R$ 5.000,00
Prazo Pagamento: 30 dias
```

---

## ⚙️ Etapa 8: Configurações Finais

### **🔧 Parâmetros do Sistema**

#### **Configurações Gerais**
```
Moeda: Real (R$)
Casas Decimais: 2
Formato Data: DD/MM/AAAA
Fuso Horário: America/Sao_Paulo
```

#### **Configurações de Venda**
```
Desconto Máximo: 10%
Parcelas Máximas: 12x
Valor Mínimo Parcela: R$ 50,00
Comissão Padrão: 2%
```

#### **Configurações de Estoque**
```
Controle Automático: Sim
Alerta Estoque Baixo: Sim
Movimentação Automática: Sim
Inventário Obrigatório: Mensal
```

### **💾 Backup Automático**

#### **Configuração do Backup**
```
Frequência: Diária
Horário: 02:00
Retenção: 30 dias
Local: Nuvem + Local
Notificação: Email do administrador
```

### **📊 Relatórios Padrão**

#### **Relatórios Automáticos**
```
Vendas Diárias: Email 08:00
Estoque Baixo: Email Segunda-feira
Inadimplência: Email toda sexta
DRE Mensal: Email dia 5 do mês
```

---

## ✅ Validação Final

### **🔍 Checklist de Validação**

#### **Teste de Venda Completa**
- [ ] Abrir PDV
- [ ] Buscar produto por código
- [ ] Adicionar cliente
- [ ] Processar pagamento
- [ ] Imprimir cupom
- [ ] Verificar estoque atualizado

#### **Teste Financeiro**
- [ ] Título gerado automaticamente
- [ ] Saldo do caixa correto
- [ ] Relatório de vendas atualizado

#### **Teste Fiscal**
- [ ] Emitir NFCe de teste
- [ ] Verificar dados fiscais
- [ ] Cancelar nota de teste

### **📋 Documentação Final**

#### **Criar Documentação Interna**
```
📄 Manual de Usuários
├── Logins e senhas
├── Procedimentos básicos
└── Contatos de suporte

📄 Configurações Aplicadas
├── Backup das configurações
├── Parâmetros utilizados
└── Integrações ativas
```

---

## 🆘 Problemas Comuns

### **❌ Certificado Digital Inválido**
**Sintomas**: Erro ao emitir NFe
**Soluções**:
1. Verificar validade do certificado
2. Confirmar senha correta
3. Reinstalar certificado
4. Contatar suporte da certificadora

### **❌ TEF Não Conecta**
**Sintomas**: Erro "Terminal não responde"
**Soluções**:
1. Verificar cabo serial
2. Confirmar porta COM
3. Testar com software da operadora
4. Contatar suporte técnico

### **❌ Produto Não Aparece no PDV**
**Sintomas**: Produto não encontrado
**Soluções**:
1. Verificar se produto está ativo
2. Confirmar preço de venda
3. Verificar categoria ativa
4. Testar código de barras

---

## 🎯 Próximos Passos

### **📚 Após a Configuração**
1. **[Primeiros Passos](primeiros-passos.md)** - Operação básica do sistema
2. **[Treinamento Equipe](treinamento-equipe.md)** - Capacitar a equipe
3. **[Casos Uso Praticos](casos-uso-praticos.md)** - Aplicar na prática
4. **[Otimizacao Sistema](otimizacao-sistema.md)** - Melhorar performance

### **🚀 Expansão Futura**
1. **Integrações avançadas** - E-commerce, marketplaces
2. **Automações** - Processos automáticos
3. **Relatórios personalizados** - Análises específicas
4. **Módulos adicionais** - Funcionalidades extras

---

## 📞 Suporte

### **🆘 Quando Precisar de Ajuda**
- **Documentação**: Esta seção de configuração
- **Suporte Técnico**: suporte@White.com.br
- **WhatsApp**: (11) 9999-9999
- **Vídeos**: Canal no YouTube
- **Treinamento**: Agende uma sessão

### **📋 Informações para Suporte**
Tenha sempre em mãos:
- CNPJ da empresa
- Versão do sistema
- Descrição detalhada do problema
- Prints de tela se necessário

---

**💡 Dica Final**: A configuração inicial é fundamental para o sucesso do sistema. Dedique o tempo necessário e não pule etapas. Um sistema bem configurado funciona perfeitamente por anos!

---

**Tags relacionadas**: #configuracao #inicial #setup #fundamental #passo-a-passo #obrigatorio #empresa #fiscal #usuarios 