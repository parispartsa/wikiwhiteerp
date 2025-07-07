# MDFe - Manifesto Eletrônico de Documentos Fiscais

🏠 [Home](../../../index.md) > 📋 [Módulos](../../index.md) > 🚛 [Transportes](index.md) > **MDFe**

#transportes #mdfe #manifesto #sefaz #fiscal #compliance

## 🎯 O que é o MDFe

O **MDFe (Manifesto Eletrônico de Documentos Fiscais)** é um documento fiscal eletrônico obrigatório para o transporte de cargas no Brasil. Ele registra informações sobre as mercadorias transportadas, veículos utilizados, motoristas, rotas e todas as informações necessárias para o controle fiscal do transporte.

### 🚀 Principais Benefícios
- **Compliance Total**: Atende 100% das exigências SEFAZ
- **Controle Automático**: Gestão completa do transporte
- **Redução de Riscos**: Evita multas e autuações
- **Agilidade**: Emissão em minutos, não horas

## 🚀 Como usar o MDFe

### 📋 **Pré-requisitos**
- Certificado digital A1 configurado
- RNTRC (Registro Nacional de Transportadores) válido
- Inscrição estadual ativa
- Ambiente SEFAZ configurado (produção ou homologação)

### 🔧 **Passo a passo para emitir MDFe**

#### **Passo 1: Acessar o módulo**
1. Acesse **Transportes** > **MDFe**
2. Clique em **"Adicionar MDF-e"**
3. Selecione a empresa emitente

#### **Passo 2: Informações Gerais**
1. **Empresa**: Selecione a empresa emitente
2. **Tipo de Transportador**: 
   - Transportador Autônomo de Carga (TAC)
   - Empresa de Transporte de Carga (ETC)
   - Cooperativa de Transporte
3. **Data de Emissão**: Data atual (preenchida automaticamente)
4. **Série e Número**: Numeração sequencial automática
5. **UF Carregamento**: Estado onde a carga foi coletada
6. **UF Descarregamento**: Estado de destino da carga

#### **Passo 3: Informações da Carga**
1. **Descrição do Produto**: Descrição detalhada da mercadoria
2. **Código NCM**: Classificação fiscal dos produtos
3. **Valor Total da Carga**: Valor total das mercadorias
4. **Peso Bruto Total**: Peso total em KG ou TON
5. **Unidade**: Selecione KG ou TON
6. **Quantidade de NFe**: Número de notas fiscais
7. **Quantidade de CTe**: Número de conhecimentos de transporte

#### **Passo 4: Informações do Veículo**
1. **Placa do Veículo**: Placa do veículo principal
2. **UF do Veículo**: Estado de registro do veículo
3. **RNTRC**: Registro Nacional de Transportadores
4. **Tipo de Carroceria**: Selecione o tipo adequado
5. **Tipo de Rodado**: Configuração do veículo
6. **Tara**: Peso do veículo vazio

#### **Passo 5: Proprietário do Veículo**
Se o veículo não pertencer ao emitente:
1. Marque **"Veículo não pertence ao emitente"**
2. **Razão Social**: Nome do proprietário
3. **CPF/CNPJ**: Documento do proprietário
4. **Inscrição Estadual**: IE do proprietário
5. **RNTRC**: Registro do proprietário
6. **UF**: Estado do proprietário

#### **Passo 6: Informações de Pagamento** (Opcional)
1. **Informar Dados de Pagamento**: Marque se necessário
2. **Nome do Responsável**: Responsável pelo pagamento
3. **CPF/CNPJ**: Documento do responsável
4. **Valor Total**: Valor do contrato de transporte
5. **Forma de Pagamento**: À vista ou parcelado
6. **Dados Bancários**: Banco, agência, PIX (se aplicável)

### 🚛 **Gestão de Motoristas**
1. Clique na aba **"Motoristas"**
2. Adicione o motorista principal:
   - **Nome Completo**
   - **CPF**
   - **CNH**: Número da carteira
3. Adicione condutores adicionais se necessário

### 🚗 **Gestão de Reboques**
1. Clique na aba **"Reboques"**
2. Para cada reboque, informe:
   - **Placa do Reboque**
   - **UF do Reboque**
   - **Tipo de Carroceria**
   - **Capacidade e Tara**
   - **Dados do Proprietário** (se diferente)

### 🛡️ **CIOT - Código de Identificação**
1. Clique na aba **"CIOT"**
2. Para cada CIOT, informe:
   - **Código CIOT**: Número fornecido pela ANTT
   - **CPF/CNPJ**: Documento do responsável

### 🏦 **Seguros de Carga**
1. Clique na aba **"Seguros"**
2. Para cada seguro, informe:
   - **Responsável**: Emitente, contratante ou transportador
   - **Seguradora**: Nome da seguradora
   - **CNPJ da Seguradora**
   - **Número da Apólice**
   - **Número da Averbação**

### 🛣️ **Controle de Pedágios**
1. Clique na aba **"Pedágios"**
2. Para cada vale-pedágio:
   - **CNPJ do Fornecedor**: Empresa fornecedora
   - **Número do Comprovante**: Código do vale
   - **Valor do Vale**: Valor em reais
   - **CPF/CNPJ Responsável**: Responsável pelo pagamento

### 📍 **Municípios de Carregamento/Descarregamento**
1. Configure os pontos de coleta e entrega
2. Para cada município:
   - **Código IBGE**: Código do município
   - **CEP**: Código postal
   - **Coordenadas**: Latitude e longitude (opcional)
   - **NFe/CTe**: Vincule os documentos fiscais

## 📤 Transmissão e Autorização

### 🔄 **Processo de Transmissão**
1. **Validação**: Sistema valida todos os dados
2. **Assinatura Digital**: Documento é assinado com certificado
3. **Transmissão SEFAZ**: Envio para autorização
4. **Protocolo**: Recebimento do número de protocolo
5. **Autorização**: Confirmação da autorização

### ✅ **Status do MDFe**
- **🟡 Aberto**: MDFe criado, não transmitido
- **🔵 Transmitido**: Enviado para SEFAZ
- **🟢 Autorizado**: Autorizado e válido
- **🔴 Rejeitado**: Rejeitado pelo SEFAZ
- **⚫ Cancelado**: Cancelado pelo emitente
- **🟣 Encerrado**: Transporte finalizado

### 📋 **Pré-visualização e Impressão**
1. Clique em **"Pré-visualizar"** para ver o DAMDFE
2. O documento será gerado em PDF
3. Imprima o DAMDFE para acompanhar o transporte

### 📡 **Transmitir para SEFAZ**
1. Clique em **"Transmitir"**
2. Aguarde a validação automática
3. O sistema enviará para o SEFAZ
4. Receba o protocolo de autorização
5. O PDF autorizado será gerado automaticamente

## 🔧 Funcionalidades Avançadas

### 📊 **Totalizadores Automáticos**
- **Total de NFe**: Contagem automática de notas fiscais
- **Total de CTe**: Contagem automática de conhecimentos
- **Valor Total**: Soma automática dos valores
- **Peso Total**: Cálculo automático do peso bruto

### 🔗 **Integração com Vendas**
- Importação automática de pedidos de venda
- Vinculação de NFe ao MDFe
- Cálculo automático de valores e pesos
- Atualização de status de entrega

### 📱 **Eventos do MDFe**
- **Encerramento**: Finalização do transporte
- **Cancelamento**: Cancelamento antes do transporte
- **Correção**: Carta de correção eletrônica
- **Consulta**: Verificação de status no SEFAZ

## 💡 Dicas importantes

> **⚠️ Atenção**: O MDFe deve ser emitido **antes** do início do transporte. Transportar sem MDFe autorizado é infração grave.

> **💡 Dica**: Use o ambiente de homologação para testes. Só mude para produção após validar todos os processos.

> **🔒 Segurança**: Mantenha seu certificado digital sempre atualizado e com backup seguro.

> **📋 Compliance**: Verifique se todos os dados estão corretos antes da transmissão. Erros podem gerar rejeições.

## 🔄 Próximos passos

Após emitir o MDFe:
1. **Imprima o DAMDFE** e mantenha no veículo
2. **Inicie o transporte** com o documento autorizado
3. **Controle a entrega** através do sistema
4. **Encerre o MDFe** após a entrega
5. **Arquive os documentos** conforme legislação

## 🔗 Veja também

- [CTe - Conhecimento de Transporte](cte-conhecimento-transporte.md)
- [Gestão de Frota](gestao-frota.md)
- [CIOT e Seguros](ciot-seguros.md)
- [Fluxo: Emissão Completa de MDFe](../../fluxos/fluxo-emissao-mdfe.md)

---

> **📞 Precisa de ajuda?** Entre em contato com nosso suporte especializado em transportes: suporte@White.com.br 