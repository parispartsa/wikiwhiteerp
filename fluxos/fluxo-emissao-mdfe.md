# Fluxo: Emissão Completa de MDFe

🏠 [Home](../../index.md) > 🔄 [Fluxos](index.md) > **Emissão de MDFe**

#fluxo #transportes #mdfe #passo-a-passo #sefaz

## 🎯 Objetivo do Fluxo

Este fluxo demonstra o **processo completo de emissão de um MDFe** (Manifesto Eletrônico de Documentos Fiscais), desde a preparação inicial até a autorização pelo SEFAZ e início do transporte.

### 📊 **Informações do Fluxo**
- **Tempo estimado**: 15-30 minutos
- **Complexidade**: Média
- **Frequência**: Diária/Por demanda
- **Responsável**: Operador de transporte

## 🚀 Pré-requisitos

### ✅ **Checklist Inicial**
- [ ] Certificado digital A1 configurado e válido
- [ ] RNTRC da empresa ativo
- [ ] Ambiente SEFAZ configurado (produção/homologação)
- [ ] Dados da frota cadastrados (veículos, motoristas, reboques)
- [ ] Cadastro de clientes atualizado
- [ ] Seguros de carga contratados
- [ ] CIOT obtido (se necessário para autônomos)

### 📋 **Documentos Necessários**
- Pedidos de venda ou solicitações de transporte
- Notas fiscais das mercadorias (se emitidas)
- Dados do destinatário e remetente
- Informações do veículo e motorista
- Apólices de seguro
- Código CIOT (se aplicável)

## 📝 Passo a Passo Detalhado

### **Fase 1: Preparação da Operação**

#### **Passo 1.1: Analisar a Solicitação**
1. **Receba a solicitação** de transporte
2. **Identifique os dados essenciais**:
   - Origem e destino
   - Tipo de carga
   - Peso e volume
   - Valor da mercadoria
   - Prazo de entrega
3. **Verifique a viabilidade** da operação
4. **Confirme a disponibilidade** de veículo e motorista

#### **Passo 1.2: Definir Recursos**
1. **Selecione o veículo** adequado:
   - Capacidade de carga
   - Tipo de carroceria
   - Documentação em dia
2. **Escolha o motorista**:
   - CNH válida e categoria adequada
   - Disponibilidade de agenda
   - Cursos obrigatórios (MOPP se necessário)
3. **Determine reboques** (se necessário):
   - Compatibilidade com o veículo
   - Capacidade adicional
   - Documentação regular

### **Fase 2: Criação do MDFe**

#### **Passo 2.1: Acessar o Sistema**
1. Acesse **Transportes** > **MDFe**
2. Clique em **"Adicionar MDF-e"**
3. Aguarde o carregamento do formulário

#### **Passo 2.2: Informações Gerais**
1. **Empresa**: Selecione a empresa emitente
2. **Tipo de Transportador**: 
   - ETC (Empresa de Transporte de Carga)
   - TAC (Transportador Autônomo de Carga)
   - CTC (Cooperativa de Transporte de Carga)
3. **Data de Emissão**: Confirme a data atual
4. **Série e Número**: Verifique a numeração automática
5. **UF Carregamento**: Estado de origem
6. **UF Descarregamento**: Estado de destino

#### **Passo 2.3: Dados da Carga**
1. **Descrição do Produto**: Descrição detalhada da mercadoria
2. **NCM**: Código de classificação fiscal
3. **Valor Total da Carga**: Somatória do valor das mercadorias
4. **Peso Bruto Total**: Peso total em KG ou TON
5. **Unidade**: Selecione KG ou TON
6. **Quantidade de NFe**: Número de notas fiscais
7. **Quantidade de CTe**: Número de conhecimentos (se aplicável)
8. **Informações de Lotação**: Detalhes sobre a carga

#### **Passo 2.4: Dados do Veículo**
1. **Placa**: Placa do veículo principal
2. **UF do Veículo**: Estado de registro
3. **RNTRC**: Registro da empresa
4. **Tipo de Carroceria**: Tipo adequado à carga
5. **Tipo de Rodado**: Configuração do veículo
6. **Tara**: Peso do veículo vazio
7. **Código de Agendamento**: Para operações portuárias (se aplicável)

### **Fase 3: Configuração Complementar**

#### **Passo 3.1: Proprietário do Veículo**
Se o veículo for de terceiros:
1. Marque **"Veículo não pertence ao emitente"**
2. **Razão Social**: Nome do proprietário
3. **CPF/CNPJ**: Documento do proprietário
4. **Inscrição Estadual**: IE do proprietário
5. **RNTRC**: Registro do proprietário
6. **UF**: Estado do proprietário
7. **Tipo de Proprietário**: Pessoa física/jurídica

#### **Passo 3.2: Motoristas**
1. Clique na aba **"Motoristas"**
2. **Adicionar Motorista Principal**:
   - Nome completo
   - CPF
   - Número da CNH
3. **Adicionar Condutores** (se necessário):
   - Motoristas adicionais para revezamento
   - Dados completos de cada condutor

#### **Passo 3.3: Reboques**
1. Clique na aba **"Reboques"**
2. Para cada reboque:
   - **Placa do Reboque**
   - **UF do Reboque**
   - **Tipo de Carroceria**
   - **Capacidade e Tara**
   - **Dados do Proprietário** (se terceiro)

#### **Passo 3.4: CIOT**
Se necessário para autônomos:
1. Clique na aba **"CIOT"**
2. **Código CIOT**: Obtido no portal da ANTT
3. **CPF/CNPJ**: Do motorista autônomo ou transportadora

#### **Passo 3.5: Seguros**
1. Clique na aba **"Seguros"**
2. **Adicionar Seguro RCTR-C** (obrigatório):
   - Responsável: Transportador
   - Seguradora e CNPJ
   - Número da apólice
   - Número da averbação
3. **Adicionar outros seguros** (se aplicável):
   - STN (Seguro de Transporte Nacional)
   - RCF-DC (Responsabilidade Civil Facultativo)

#### **Passo 3.6: Pedágios**
1. Clique na aba **"Pedágios"**
2. Para cada vale-pedágio:
   - **CNPJ do Fornecedor**
   - **Número do Comprovante**
   - **Valor do Vale**
   - **Responsável pelo Pagamento**

### **Fase 4: Municípios e Documentos**

#### **Passo 4.1: Municípios de Carregamento**
1. Configure os pontos de coleta:
   - **Código IBGE** do município
   - **CEP** de carregamento
   - **Coordenadas** (se disponíveis)

#### **Passo 4.2: Municípios de Descarregamento**
1. Configure os pontos de entrega:
   - **Código IBGE** do município
   - **CEP** de descarregamento
   - **Coordenadas** (se disponíveis)

#### **Passo 4.3: Vincular NFe/CTe**
1. **Adicione as chaves** das notas fiscais
2. **Vincule CTe** (se aplicável)
3. **Confirme os totalizadores**:
   - Quantidade de documentos
   - Valores totais
   - Pesos totais

### **Fase 5: Informações de Pagamento**

#### **Passo 5.1: Dados de Pagamento** (Opcional)
Se necessário informar:
1. Marque **"Informar dados de pagamento"**
2. **Nome do Responsável**: Responsável pelo pagamento
3. **CPF/CNPJ**: Documento do responsável
4. **Valor Total**: Valor do contrato de transporte
5. **Forma de Pagamento**: À vista ou parcelado

#### **Passo 5.2: Dados Bancários**
1. **Banco**: Selecione o banco
2. **Agência**: Número da agência
3. **Conta**: Dados da conta
4. **Chave PIX**: Para pagamentos instantâneos (se aplicável)

#### **Passo 5.3: Componentes do Frete**
1. **Adicionar componentes**:
   - Frete peso
   - Frete valor
   - Pedagio
   - Outros custos
2. **Valor de cada componente**
3. **Descrição detalhada**

### **Fase 6: Validação e Transmissão**

#### **Passo 6.1: Revisão Final**
1. **Confira todos os dados** inseridos
2. **Verifique totalizadores**:
   - Peso total
   - Valor total
   - Quantidade de documentos
3. **Valide informações obrigatórias**:
   - Dados do veículo
   - Dados do motorista
   - Seguros
   - CIOT (se aplicável)

#### **Passo 6.2: Pré-visualização**
1. Clique em **"Pré-visualizar"**
2. **Analise o DAMDFE** gerado
3. **Verifique se todas as informações** estão corretas
4. **Confirme a formatação** do documento

#### **Passo 6.3: Transmissão SEFAZ**
1. Clique em **"Transmitir"**
2. **Aguarde a validação** automática do sistema
3. **Acompanhe o processo** de transmissão
4. **Verifique o retorno** do SEFAZ:
   - ✅ **Autorizado**: MDFe válido e autorizado
   - ❌ **Rejeitado**: Correções necessárias

### **Fase 7: Pós-Autorização**

#### **Passo 7.1: Documento Autorizado**
1. **Baixe o PDF** autorizado
2. **Imprima o DAMDFE** para o motorista
3. **Arquive o XML** autorizado
4. **Anote o número** do protocolo

#### **Passo 7.2: Início do Transporte**
1. **Entregue o DAMDFE** ao motorista
2. **Confirme que todos os documentos** estão no veículo:
   - DAMDFE autorizado
   - CNH do motorista
   - CRLV do veículo
   - Apólice de seguro
   - Comprovante de CIOT (se aplicável)
3. **Autorize o início** do transporte

#### **Passo 7.3: Acompanhamento**
1. **Monitore o status** do transporte
2. **Mantenha comunicação** com o motorista
3. **Atualize o cliente** sobre o andamento
4. **Prepare-se para o encerramento** do MDFe

## ⚠️ Pontos de Atenção

### 🔴 **Erros Comuns**
- **Dados incorretos** do veículo ou motorista
- **CIOT inválido** ou vencido
- **Seguros vencidos** ou com valor insuficiente
- **Certificado digital** expirado
- **Totalizadores inconsistentes**

### 💡 **Dicas de Sucesso**
- **Valide sempre** no ambiente de homologação primeiro
- **Mantenha backup** de todos os documentos
- **Configure alertas** para vencimentos
- **Treine a equipe** regularmente
- **Monitore as atualizações** da legislação

## 📊 Indicadores de Performance

### 🎯 **Métricas do Processo**
- **Tempo médio de emissão**: 15-20 minutos
- **Taxa de autorização**: >95%
- **Rejeições por erro**: <5%
- **Documentos em conformidade**: 100%

### 📈 **Benefícios Esperados**
- **Compliance total** com SEFAZ/ANTT
- **Redução de 70%** no tempo de emissão
- **Eliminação de 90%** dos erros manuais
- **Melhoria na rastreabilidade** das operações

## 🔄 Próximos Passos

Após autorização do MDFe:
1. **Inicie o transporte** com documentação completa
2. **Monitore a operação** até a entrega
3. **Encerre o MDFe** após conclusão
4. **Archive os documentos** conforme legislação
5. **Analise indicadores** para melhoria contínua

## 🔗 Documentos Relacionados

- [MDFe - Manifesto Eletrônico](../modulos/transportes/mdfe-manifesto-eletronico.md)
- [Gestão de Frota](../modulos/transportes/gestao-frota.md)
- [CIOT e Seguros](../modulos/transportes/ciot-seguros.md)
- [Caso: Transportadora Regional](../casos-uso/transportes/transportadora-regional.md)

---

> **📞 Precisa de ajuda?** Este fluxo pode ser adaptado conforme suas necessidades específicas. Entre em contato: suporte@White.com.br 