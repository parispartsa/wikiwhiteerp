# 📄 Configuração da NFe (Nota Fiscal Eletrônica)

🏠 [Home](../../../index.md) > 📋 [Módulos](../../index.md) > 🔗 [Integrações](../index.md) > **Configuração NFe**

#fiscal #nfe #configuracao #obrigatorio #sefaz #certificado

## 🎯 Visão Geral

A **NFe (Nota Fiscal Eletrônica)** é um documento fiscal obrigatório para a maioria das operações comerciais entre empresas. Este guia apresenta o processo completo de configuração da emissão automática de NFe no ERP GerenciaTec, garantindo compliance fiscal e automatização do processo.

## 📋 Pré-requisitos

### ✅ **Obrigatórios**
- **Certificado Digital A1 ou A3** válido
- **CNPJ ativo** na Receita Federal
- **Inscrição Estadual** ativa na SEFAZ
- **Endereço completo** da empresa
- **Regime tributário** definido (Simples Nacional, Lucro Presumido, etc.)

### ⚠️ **Importante**
- Certificado deve ter validade mínima de 30 dias
- Empresa deve estar com situação regular na SEFAZ
- Todos os dados cadastrais devem estar corretos

## 🔧 Configuração Passo a Passo

### **Etapa 1: Configuração da Empresa**

#### 1.1 **Dados Básicos**
1. **Acessar**: Menu > Configurações > Dados da Empresa
2. **Preencher dados obrigatórios**:
   - **CNPJ**: Sem pontuação
   - **Razão Social**: Exatamente como no contrato social
   - **Nome Fantasia**: Se aplicável
   - **Inscrição Estadual**: Sem pontuação
   - **Inscrição Municipal**: Se aplicável

#### 1.2 **Endereço Completo**
```
Logradouro: Rua das Flores, 123
Bairro: Centro
CEP: 01234-567
Cidade: São Paulo
UF: SP
Código IBGE: 3550308
```

#### 1.3 **Regime Tributário**
- **Simples Nacional**: CRT = 1
- **Lucro Presumido**: CRT = 2
- **Lucro Real**: CRT = 3

### **Etapa 2: Instalação do Certificado Digital**

#### 2.1 **Certificado A1 (arquivo)**
1. **Fazer upload** do arquivo .pfx
2. **Inserir senha** do certificado
3. **Testar conexão** com a SEFAZ
4. **Validar dados** do certificado

#### 2.2 **Certificado A3 (token/cartão)**
1. **Conectar dispositivo** USB
2. **Instalar driver** específico
3. **Configurar token** no sistema
4. **Testar assinatura** digital

### **Etapa 3: Configuração da NFe**

#### 3.1 **Parâmetros Gerais**
```
Ambiente: Produção (após testes)
Versão: 4.00
Série: 1 (padrão)
Número Inicial: 1
Tipo de Emissão: 1 (Normal)
```

#### 3.2 **Configuração de Séries**
- **Série 1**: Vendas normais
- **Série 2**: Vendas especiais (se necessário)
- **Série 3**: Devolução/Retorno

#### 3.3 **Numeração**
- **Número Inicial**: Próximo número disponível
- **Controle Sequencial**: Automático
- **Validação SEFAZ**: Ativa

### **Etapa 4: Configuração de Impostos**

#### 4.1 **ICMS por Estado**
| Estado | Alíquota Interna | Alíquota Interestadual |
|--------|------------------|------------------------|
| SP     | 18%              | 12%                    |
| RJ     | 20%              | 12%                    |
| MG     | 18%              | 12%                    |
| RS     | 18%              | 12%                    |

#### 4.2 **Configuração por Produto**
```
NCM: 84715010
CFOP: 5102 (Venda dentro do estado)
CFOP: 6102 (Venda fora do estado)
CST ICMS: 00 (Tributado integralmente)
CST IPI: 99 (Outras saídas)
CST PIS: 01 (Alíquota básica)
CST COFINS: 01 (Alíquota básica)
```

### **Etapa 5: Configuração de CFOPs**

#### 5.1 **CFOPs Principais**
- **5102**: Venda de mercadoria adquirida para revenda (dentro do estado)
- **6102**: Venda de mercadoria adquirida para revenda (fora do estado)
- **5403**: Venda de mercadoria sujeita ao regime de substituição tributária
- **5405**: Venda de mercadoria adquirida para revenda, sujeita ao regime de substituição tributária

#### 5.2 **Configuração Automática**
- **Mesmo Estado**: CFOP 5xxx
- **Estados Diferentes**: CFOP 6xxx
- **Exterior**: CFOP 7xxx

### **Etapa 6: Testes em Homologação**

#### 6.1 **Ambiente de Teste**
1. **Ativar homologação**
2. **Emitir NFe de teste**
3. **Verificar retorno SEFAZ**
4. **Validar DANFE**

#### 6.2 **Cenários de Teste**
- **Venda simples**: 1 produto, 1 cliente
- **Venda múltipla**: Vários produtos
- **Venda interestadual**: Cliente de outro estado
- **Venda com desconto**: Aplicação de desconto
- **Venda com frete**: Cobrança de frete

### **Etapa 7: Ativação em Produção**

#### 7.1 **Checklist Final**
- [ ] Certificado válido e funcionando
- [ ] Dados da empresa corretos
- [ ] Impostos configurados
- [ ] CFOPs definidos
- [ ] Testes aprovados
- [ ] Numeração definida

#### 7.2 **Ativação**
1. **Alterar ambiente** para Produção
2. **Definir numeração** inicial
3. **Emitir primeira NFe** real
4. **Monitorar emissões**

## 🔄 Processo de Emissão Automática

### **Fluxo Padrão**
1. **Venda Confirmada** → Sistema gera NFe automaticamente
2. **Validação** → Verifica dados obrigatórios
3. **Assinatura** → Assina com certificado digital
4. **Transmissão** → Envia para SEFAZ
5. **Retorno** → Recebe protocolo de autorização
6. **DANFE** → Gera PDF para impressão/envio

### **Validações Automáticas**
- **Dados do Cliente**: CPF/CNPJ válido
- **Produtos**: NCM e tributação corretos
- **Valores**: Cálculos de impostos
- **Sequência**: Numeração sequencial

## 🚨 Contingência

### **Tipos de Contingência**
1. **FS-IA**: Formulário de Segurança para Impressão Auxiliar
2. **EPEC**: Evento Prévio de Emissão em Contingência
3. **Off-line**: Emissão offline da NFCe

### **Configuração**
```
Contingência: Automática
Tipo: FS-IA
Justificativa: "Problemas técnicos na comunicação com SEFAZ"
Tempo limite: 24 horas
```

## 📊 Monitoramento e Relatórios

### **Dashboard NFe**
- **Emitidas hoje**: Quantidade e valor
- **Pendentes**: Aguardando autorização
- **Rejeitadas**: Com erro
- **Canceladas**: Cancelamentos do dia

### **Relatórios Principais**
- **Registro de Saídas**: Todas as NFe emitidas
- **Livro Fiscal**: Para escrituração
- **SPED Fiscal**: Arquivo para EFD
- **Relatório de Rejeições**: Análise de erros

## ❌ Troubleshooting

### **Erro: Certificado Inválido**
**Problema**: "Certificado digital não foi localizado"

**Soluções**:
1. Verificar se certificado está instalado
2. Confirmar senha do certificado
3. Validar validade do certificado
4. Reinstalar certificado se necessário

### **Erro: Rejeição 204**
**Problema**: "Duplicidade de NFe"

**Soluções**:
1. Verificar numeração da NFe
2. Consultar SEFAZ para confirmar situação
3. Inutilizar número se necessário
4. Emitir nova NFe com próximo número

### **Erro: Rejeição 539**
**Problema**: "CNPJ do destinatário inválido"

**Soluções**:
1. Validar CNPJ do cliente
2. Consultar situação na Receita Federal
3. Corrigir cadastro do cliente
4. Reemitir NFe

## 💡 Dicas Importantes

### ✅ **Boas Práticas**
- **Backup diário** do certificado
- **Monitoramento constante** das emissões
- **Atualização regular** das tabelas fiscais
- **Validação mensal** dos relatórios

### ⚠️ **Cuidados**
- **Nunca compartilhar** senha do certificado
- **Renovar certificado** com 30 dias de antecedência
- **Manter backup** de todas as NFe emitidas
- **Acompanhar mudanças** na legislação

## 🔗 Integrações Relacionadas

### **Módulos Conectados**
- **[Pdv](../vendas/pdv.md)** - Vendas que geram NFe
- **[Movimentacao Estoque](../estoque/movimentacao-estoque.md)** - Baixa automática de estoque
- **[Contas A Receber](../financeiro/contas-a-receber.md)** - Geração de títulos
- **[Fiscal](../relatorios/fiscal.md)** - Relatórios fiscais

### **Sistemas Externos**
- **SEFAZ** - Autorização de NFe
- **Receita Federal** - Validação de CNPJ
- **Correios** - Consulta de CEP
- **Bancos** - Conciliação automática

## 📋 Checklist de Configuração

### **Pré-configuração**
- [ ] Certificado digital instalado
- [ ] Dados da empresa completos
- [ ] Regime tributário definido
- [ ] Inscrições estaduais ativas

### **Configuração Fiscal**
- [ ] NCM dos produtos cadastrados
- [ ] CFOPs configurados
- [ ] Alíquotas de impostos definidas
- [ ] CSTs configurados

### **Testes**
- [ ] Ambiente de homologação ativo
- [ ] NFe de teste emitida
- [ ] Retorno SEFAZ validado
- [ ] DANFE gerado corretamente

### **Produção**
- [ ] Ambiente alterado para produção
- [ ] Numeração inicial definida
- [ ] Primeira NFe real emitida
- [ ] Monitoramento ativo

---

**⚠️ Importante**: A configuração da NFe é um processo crítico que exige atenção aos detalhes. Sempre teste em ambiente de homologação antes de ativar em produção.

**🎯 Objetivo**: Automatizar completamente o processo de emissão de NFe, garantindo compliance fiscal e reduzindo erros manuais.

**📞 Suporte**: Para dúvidas específicas sobre configuração fiscal, consulte um contador ou entre em contato com o suporte técnico. 