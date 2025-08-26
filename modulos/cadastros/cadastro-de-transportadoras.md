# 🚛 Cadastro de Transportadoras

🏠 [Home](../../index.md) > 📋 [Módulos](../index.md) > 👥 [Cadastros](index.md) > **Transportadoras**

#cadastros #transportadoras #logistica #frete #entrega #passo-a-passo #iniciante

---

## 📋 O que é

O **Cadastro de Transportadoras** é onde você gerencia todas as empresas responsáveis pelo transporte e entrega das suas mercadorias. Este cadastro é fundamental para:

- **Emissão de CTe** - Conhecimento de Transporte Eletrônico
- **Cálculo de Frete** - Tabelas de preços por região e peso
- **Rastreamento de Entregas** - Acompanhar status das remessas
- **Controle de Prazos** - Monitorar cumprimento de prazos
- **Emissão de MDFe** - Manifesto Eletrônico de Documentos Fiscais
- **Gestão de Custos** - Controlar gastos com logística
- **Compliance Fiscal** - Atender obrigações tributárias

---

## 🚀 Como Fazer

### 📋 Passo 1: Acessar o Módulo
1. No menu principal, clique em **"Cadastros"**
2. Selecione **"Transportadoras"**
3. Clique no botão **"Nova Transportadora"** (ícone +)

### 🏢 Passo 2: Dados da Empresa

#### **Informações Básicas**
- **CNPJ**: Documento obrigatório da transportadora
- **Razão Social**: Nome oficial da empresa
- **Nome Fantasia**: Nome comercial (opcional)
- **Inscrição Estadual**: IE da transportadora
- **Inscrição Municipal**: IM (se aplicável)
- **ANTT**: Registro na Agência Nacional de Transportes Terrestres

#### **Dados de Contato**
- **Telefone Principal**: Central de atendimento
- **Telefone Comercial**: Setor comercial/vendas
- **Email**: Para comunicações oficiais
- **Site**: Website da transportadora (opcional)
- **WhatsApp**: Para comunicação rápida

{% hint style="info" %}
**💡 Dica**: Mantenha sempre os dados de contato atualizados para facilitar a comunicação sobre entregas.
{% endhint %}

### 📍 Passo 3: Endereço e Localização

#### **Endereço Principal**
- **CEP**: Código postal da sede
- **Logradouro**: Rua, avenida, etc.
- **Número**: Número do imóvel
- **Complemento**: Sala, andar, etc. (opcional)
- **Bairro**: Bairro da empresa
- **Cidade**: Município da sede
- **Estado**: UF da sede

#### **Filiais e Pontos de Coleta**
- **Endereços Adicionais**: Outras unidades da transportadora
- **Áreas de Cobertura**: Regiões atendidas
- **Centros de Distribuição**: Locais de triagem
- **Pontos de Entrega**: Locais para retirada

---

## 🔧 Configurações Comerciais

### 💰 **Tabela de Frete**

#### **Tipos de Cálculo**
- **Por Peso**: Valor por kg transportado
- **Por Volume**: Valor por m³ de mercadoria
- **Por Distância**: Valor por km percorrido
- **Tabela Fixa**: Valores pré-definidos por região
- **Percentual sobre NF**: % sobre valor da nota fiscal

#### **Configuração de Fretes**
1. **Frete Mínimo**: Valor mínimo para qualquer entrega
2. **Faixa de Peso**: Valores por escalas de peso
3. **Região de Entrega**: Diferentes valores por localidade
4. **Tipo de Mercadoria**: Fretes específicos por categoria
5. **Prazo de Entrega**: Tempo estimado por região

{% hint style="warning" %}
**⚠️ Atenção**: Configure as tabelas de frete corretamente para evitar erros nos cálculos de custos de entrega.
{% endhint %}

### 📅 **Prazos e Horários**

#### **Prazos de Entrega**
- **Região Metropolitana**: Prazo para cidade sede
- **Interior do Estado**: Prazo para cidades do interior
- **Outros Estados**: Prazo para demais regiões
- **Entrega Expressa**: Serviço premium com prazo reduzido

#### **Horários de Funcionamento**
- **Coleta**: Horários para retirada de mercadorias
- **Entrega**: Períodos de entrega ao cliente final
- **Atendimento**: Horário do suporte/SAC
- **Dias Úteis**: Quais dias da semana funcionam

---

## 🚛 Configurações de Transporte

### 🎯 **Tipos de Serviço**
- **Normal**: Entrega padrão da transportadora
- **Expressa**: Entrega rápida com prazo reduzido
- **Agendada**: Entrega com data/hora marcada
- **Refrigerada**: Para produtos que precisam de temperatura controlada
- **Frágil**: Cuidados especiais para produtos delicados
- **Perigoso**: Transporte de produtos químicos/perigosos

### 📦 **Limitações e Restrições**
- **Peso Máximo**: Limite de peso por volume
- **Dimensões**: Medidas máximas aceitas
- **Valor Declarado**: Limite de valor segurado
- **Tipos Proibidos**: Produtos que não transporta
- **Regiões Não Atendidas**: Locais onde não entrega

### 🔐 **Documentação Necessária**
- **ANTT Vigente**: Registro atualizado
- **Seguro Obrigatório**: RCTR-C em dia
- **Alvará Municipal**: Para transporte urbano
- **Licenças Especiais**: Para produtos específicos

---

## 📊 Funcionalidades Avançadas

### 🗺️ **Gestão de Rotas**
- **Mapeamento de Regiões**: Áreas de cobertura detalhadas
- **Otimização de Rotas**: Caminhos mais eficientes
- **Pontos de Parada**: Locais intermediários
- **Tempo de Percurso**: Estimativas realistas

### 📱 **Integração e Rastreamento**
- **API de Rastreamento**: Integração para acompanhar entregas
- **Código de Rastreio**: Número para consulta de status
- **Notificações**: Avisos automáticos de status
- **Portal do Cliente**: Acesso para consulta de entregas

### 💼 **Contratos e Acordos**
- **Contrato Comercial**: Termos e condições acordadas
- **Desconto por Volume**: Reduções por quantidade
- **Prazo de Pagamento**: Condições financeiras
- **SLA de Entrega**: Acordo de nível de serviço

---

## 💡 Casos de Uso

### 🏪 **Cenário 1: E-commerce**
**Situação**: Loja online com entregas para todo Brasil
- **Transportadora Principal**: Correios para encomendas pequenas
- **Transportadora Expressa**: Jadlog para entregas rápidas
- **Transportadora Regional**: Empresa local para cidade/região
- **Cálculo**: Automático baseado em CEP e peso

### 🏭 **Cenário 2: Indústria**
**Situação**: Fábrica com produtos pesados e volumosos
- **Transportadora Especializada**: Para cargas pesadas
- **Caminhão Próprio**: Para entregas locais
- **Transportadora Refrigerada**: Para produtos perecíveis
- **Seguro Alto**: Para produtos de alto valor

### 🛒 **Cenário 3: Distribuidor**
**Situação**: Distribuidor com múltiplas rotas diárias
- **Frota Própria**: Para clientes fixos/rotas definidas
- **Transportadora Terceirizada**: Para entregas esporádicas
- **Entrega Agendada**: Para clientes que exigem horário
- **Rastreamento**: Controle total da operação

---

## 🔍 Busca e Filtros

### 🔎 **Localizar Transportadoras**
- **Por Nome**: Busca pela razão social ou fantasia
- **Por CNPJ**: Localização direta pelo documento
- **Por Região**: Transportadoras que atendem determinada área
- **Por Tipo de Serviço**: Filtrar por especialidade
- **Por Status**: Ativa, inativa, bloqueada

### 📊 **Filtros Avançados**
- **Prazo de Entrega**: Por tempo de entrega
- **Faixa de Preço**: Por custo de frete
- **Tipo de Carga**: Especialização da transportadora
- **Cobertura**: Por área geográfica atendida
- **Avaliação**: Por performance/qualidade

---

## 📊 Relatórios Disponíveis

### 📈 **Relatórios Operacionais**
- **Performance de Entregas**: Pontualidade por transportadora
- **Custos de Frete**: Gastos por período e região
- **Volume de Envios**: Quantidade por transportadora
- **Tempo Médio**: Prazo real vs. prometido

### 💰 **Relatórios Financeiros**
- **Faturamento por Transportadora**: Valores pagos
- **Análise de Custos**: Comparativo entre transportadoras
- **Contas a Pagar**: Fretes a serem pagos
- **Histórico de Pagamentos**: Fretes já quitados

### 🎯 **Relatórios Gerenciais**
- **Ranking de Transportadoras**: Melhores por critério
- **Análise de Rotas**: Performance por região
- **Satisfação do Cliente**: Feedback sobre entregas
- **Dashboard Logístico**: Visão geral da operação

---

## 🚨 Alertas e Validações

### ⚠️ **Alertas Importantes**
- **ANTT Vencido**: Registro próximo do vencimento
- **Seguro em Atraso**: RCTR-C desatualizado
- **Atraso na Entrega**: Prazo não cumprido
- **Frete Divergente**: Valor diferente do acordado
- **Região Não Atendida**: Tentativa de envio para área não coberta

### ✅ **Validações do Sistema**
- **CNPJ Válido**: Formato e dígitos verificadores corretos
- **ANTT Ativo**: Verificação na base da ANTT
- **Seguro Vigente**: Validade do seguro obrigatório
- **Tabela de Frete**: Valores coerentes e completos
- **Cobertura Geográfica**: Áreas atendidas válidas

---

## 🔐 Permissões e Segurança

### 👤 **Quem Pode Acessar**
- **Administrador**: Acesso total ao cadastro
- **Gerente Logístico**: Gestão completa de transportadoras
- **Expedição**: Consulta e seleção para envios
- **Financeiro**: Dados comerciais e pagamentos
- **Compras**: Negociação e contratos

### 🔒 **Controles de Segurança**
- **Log de Alterações**: Histórico de mudanças
- **Aprovação de Cadastro**: Validação antes da ativação
- **Bloqueio por Inadimplência**: Suspensão automática
- **Auditoria de Fretes**: Controle de valores pagos

---

## 💡 Dicas e Boas Práticas

### ✅ **Para Configuração**
- **Mantenha dados atualizados** de contato e documentação
- **Configure fretes realistas** baseados em cotações
- **Defina critérios claros** para seleção de transportadoras
- **Monitore performance** regularmente

### 📊 **Para Gestão**
- **Compare preços** entre diferentes transportadoras
- **Avalie qualidade** além do preço
- **Mantenha relacionamento** próximo com as principais
- **Tenha sempre opções** alternativas

### 🎯 **Para Operação**
- **Automatize seleção** baseada em critérios objetivos
- **Comunique mudanças** para toda equipe
- **Monitore prazos** e cobre cumprimento
- **Documente problemas** para histórico

---

## 🚨 Pontos de Atenção

### ⚠️ **Documentação**
- **Verifique ANTT** antes de contratar
- **Confira seguros** obrigatórios em dia
- **Valide licenças** especiais quando necessário
- **Mantenha contratos** atualizados

### 🔍 **Operacional**
- **Teste serviços** antes de uso massivo
- **Monitore qualidade** constantemente
- **Tenha plano B** para emergências
- **Comunique problemas** rapidamente

---

## 📚 Documentação Relacionada

- [MDFe - Manifesto Eletrônico](../transportes/mdfe-manifesto-eletronico.md) - Para emissão de manifestos
- [CTe - Conhecimento de Transporte](../transportes/cte-conhecimento-transporte.md) - Documentos fiscais de transporte
- [Gestão de Frota](../transportes/gestao-frota.md) - Para transporte próprio
- [Cadastro de Fornecedores](cadastro-de-fornecedores.md) - Para transportadoras como fornecedoras
- [Configurações Fiscais](../configuracoes/parametros-fiscais.md) - Parâmetros para transporte

---

## 🏷️ Tags
`#cadastros` `#transportadoras` `#logistica` `#frete` `#entrega` `#cte` `#mdfe` `#antt` `#rastreamento`

---

**Última atualização**: Janeiro 2025  
**Versão do documento**: 1.0  
**Responsável**: Equipe de Documentação White ERP
