# CTe - Conhecimento de Transporte Eletrônico

🏠 [Home](../../../index.md) > 📋 [Módulos](../../index.md) > 🚛 [Transportes](index.md) > **CTe**

#transportes #cte #conhecimento #transporte #sefaz #fiscal

## 🎯 O que é o CTe

O **CTe (Conhecimento de Transporte Eletrônico)** é um documento fiscal eletrônico que comprova a prestação de serviços de transporte de cargas. É obrigatório para todas as operações de transporte e substitui o conhecimento de transporte em papel.

### 🚀 Principais Benefícios
- **Documento Fiscal Válido**: Comprova a prestação do serviço
- **Integração com MDFe**: Vinculação automática ao manifesto
- **Cálculo Automático**: Impostos e fretes calculados automaticamente
- **Controle Total**: Gestão completa do frete e impostos

## 🚀 Como usar o CTe

### 📋 **Pré-requisitos**
- Certificado digital A1 configurado
- Inscrição estadual ativa
- Cadastro de clientes e fornecedores
- Configuração de impostos e alíquotas

### 🔧 **Passo a passo para emitir CTe**

#### **Passo 1: Acessar o módulo**
1. Acesse **Transportes** > **CTe**
2. Clique em **"Adicionar CT-e"**
3. Selecione a empresa emitente

#### **Passo 2: Identificação do CTe**
1. **Empresa**: Selecione a empresa emitente
2. **Série**: Série do documento (configurada automaticamente)
3. **Número**: Numeração sequencial automática
4. **Data de Emissão**: Data atual
5. **Tipo de CTe**: 
   - Normal
   - Complemento de Valores
   - Anulação
   - Substituto

#### **Passo 3: Dados do Remetente**
1. **Remetente**: Cliente que está enviando a mercadoria
2. **CNPJ/CPF**: Documento do remetente
3. **Inscrição Estadual**: IE do remetente
4. **Endereço**: Endereço completo de coleta

#### **Passo 4: Dados do Destinatário**
1. **Destinatário**: Cliente que receberá a mercadoria
2. **CNPJ/CPF**: Documento do destinatário
3. **Inscrição Estadual**: IE do destinatário
4. **Endereço**: Endereço completo de entrega

#### **Passo 5: Dados do Expedidor** (Se aplicável)
1. **Expedidor**: Responsável pelo envio (se diferente do remetente)
2. **CNPJ/CPF**: Documento do expedidor
3. **Inscrição Estadual**: IE do expedidor
4. **Endereço**: Endereço do expedidor

#### **Passo 6: Dados do Recebedor** (Se aplicável)
1. **Recebedor**: Responsável pelo recebimento (se diferente do destinatário)
2. **CNPJ/CPF**: Documento do recebedor
3. **Inscrição Estadual**: IE do recebedor
4. **Endereço**: Endereço do recebedor

#### **Passo 7: Valores do Serviço**
1. **Valor da Prestação**: Valor total do serviço de transporte
2. **Valor a Receber**: Valor que será recebido
3. **Valor Total da Carga**: Valor das mercadorias transportadas
4. **Produto Predominante**: Produto principal da carga

#### **Passo 8: Impostos**
1. **ICMS**: Configuração automática baseada na operação
2. **Alíquota**: Alíquota aplicável
3. **Base de Cálculo**: Base para cálculo do imposto
4. **Valor do Imposto**: Calculado automaticamente

#### **Passo 9: Informações da Carga**
1. **Descrição da Carga**: Descrição detalhada
2. **Quantidade**: Quantidade de volumes
3. **Espécie**: Tipo de embalagem
4. **Marca**: Marca dos produtos
5. **Peso Bruto**: Peso total em KG
6. **Peso Líquido**: Peso líquido em KG
7. **Cubagem**: Volume em m³

#### **Passo 10: Modal Rodoviário**
1. **RNTRC**: Registro Nacional de Transportadores
2. **Data Prevista**: Data prevista para entrega
3. **Indicador de Lotação**: Lotação ou agrupamento
4. **CIOT**: Código de Identificação (se aplicável)

## 📊 Tipos de Frete

### 🚛 **CIF - Custo, Seguro e Frete**
- **Responsável**: Remetente paga o frete
- **Risco**: Remetente assume os riscos
- **Uso**: Vendas com frete por conta do vendedor

### 🏪 **FOB - Free on Board**
- **Responsável**: Destinatário paga o frete
- **Risco**: Destinatário assume os riscos
- **Uso**: Vendas com frete por conta do comprador

### 🤝 **Por Conta de Terceiros**
- **Responsável**: Terceiro paga o frete
- **Risco**: Definido em contrato
- **Uso**: Operações com intermediários

### 🔄 **Sem Cobrança de Frete**
- **Responsável**: Sem cobrança
- **Risco**: Definido em contrato
- **Uso**: Transferências entre filiais

## 📤 Transmissão e Autorização

### 🔄 **Processo de Transmissão**
1. **Validação**: Sistema valida todos os dados obrigatórios
2. **Cálculo de Impostos**: Cálculo automático de ICMS
3. **Assinatura Digital**: Documento assinado com certificado
4. **Transmissão SEFAZ**: Envio para autorização
5. **Protocolo**: Recebimento do número de protocolo
6. **Autorização**: Confirmação da autorização pelo SEFAZ

### ✅ **Status do CTe**
- **🟡 Aberto**: CTe criado, não transmitido
- **🔵 Transmitido**: Enviado para SEFAZ
- **🟢 Autorizado**: Autorizado e válido
- **🔴 Rejeitado**: Rejeitado pelo SEFAZ
- **⚫ Cancelado**: Cancelado pelo emitente

### 📋 **Pré-visualização e Impressão**
1. Clique em **"Pré-visualizar"** para ver o DACTE
2. O documento será gerado em PDF
3. Imprima o DACTE para acompanhar o transporte

### 📡 **Transmitir para SEFAZ**
1. Clique em **"Transmitir"**
2. Aguarde a validação automática
3. O sistema enviará para o SEFAZ
4. Receba o protocolo de autorização
5. O PDF autorizado será gerado automaticamente

## 🔧 Funcionalidades Avançadas

### 🔗 **Integração com MDFe**
- Vinculação automática ao manifesto eletrônico
- Transferência de dados entre documentos
- Controle conjunto de transporte
- Validação de consistência

### 📊 **Cálculo Automático de Impostos**
- **ICMS**: Cálculo baseado na operação
- **Substituição Tributária**: Quando aplicável
- **Diferencial de Alíquota**: Operações interestaduais
- **Redução de Base**: Benefícios fiscais

### 📱 **Eventos do CTe**
- **Cancelamento**: Cancelamento do documento
- **Correção**: Carta de correção eletrônica
- **Consulta**: Verificação de status no SEFAZ
- **Inutilização**: Inutilização de numeração

### 🔄 **Tipos Especiais de CTe**

#### **CTe de Complemento**
- Usado para complementar valores
- Referencia o CTe original
- Adiciona valores não informados

#### **CTe de Anulação**
- Anula valores de CTe anterior
- Usado para correções de valores
- Referencia o CTe original

#### **CTe Substituto**
- Substitui CTe rejeitado
- Mantém os dados originais
- Nova numeração

## 💡 Dicas importantes

> **⚠️ Atenção**: O CTe deve ser emitido antes do início do transporte. É obrigatório para comprovar a prestação do serviço.

> **💡 Dica**: Mantenha os dados de clientes sempre atualizados para evitar rejeições na transmissão.

> **🔒 Segurança**: Verifique se o certificado digital está válido antes de transmitir documentos.

> **📋 Compliance**: Confira se as alíquotas de ICMS estão corretas para cada UF de destino.

## 🔄 Próximos passos

Após emitir o CTe:
1. **Imprima o DACTE** e mantenha com o transportador
2. **Vincule ao MDFe** se aplicável
3. **Controle o frete** através do financeiro
4. **Arquive os documentos** conforme legislação
5. **Acompanhe o status** até a entrega

## 🔗 Veja também

- [MDFe - Manifesto Eletrônico](mdfe-manifesto-eletronico.md)
- [Gestão de Frota](gestao-frota.md)
- [CIOT e Seguros](ciot-seguros.md)
- [Fluxo: Emissão de CTe](../../fluxos/fluxo-emissao-cte.md)

---

> **📞 Precisa de ajuda?** Entre em contato com nosso suporte especializado em transportes: suporte@gerenciatech.com.br 