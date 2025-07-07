# Caso: Empresa Industrial com DRE Detalhado

🏠 [Home](../../../index.md) > 💡 [Casos de Uso](../index.md) > 📊 [Contabilidade](index.md) > **Empresa Industrial**

#caso-uso #contabilidade #empresa-industrial #dre #custos #margem

## 🏭 Perfil da Empresa

### **MetalTech Indústria Ltda.**
- **Segmento**: Indústria metalúrgica
- **Localização**: São Bernardo do Campo - SP
- **Funcionários**: 85 colaboradores
- **Faturamento**: R$ 2,5 milhões/mês
- **Produtos**: Peças metálicas sob encomenda e linha própria

### 📊 **Características da Operação**
- **Produção**: 1.500 peças/mês (média)
- **Clientes**: 45% indústria automotiva, 35% construção civil, 20% outros
- **Sazonalidade**: Pico em mar-ago, baixa em dez-fev
- **Margem desejada**: 25% líquida

## 🎯 Desafio Inicial

### 📋 **Situação Problema**
A MetalTech enfrentava dificuldades para:
- **Calcular custos reais** de produção por produto
- **Analisar margem** de cada linha de produto
- **Controlar despesas** operacionais crescentes
- **Gerar DRE** detalhado para tomada de decisão
- **Comparar performance** entre períodos

### ⚠️ **Problemas Identificados**
- Lançamentos contábeis manuais e demorados
- Falta de classificação adequada de custos vs despesas
- Dificuldade para analisar rentabilidade por produto
- DRE genérico sem detalhamento por categoria
- Tempo excessivo para fechamento mensal (15 dias)

## 🚀 Implementação da Solução

### **Fase 1: Configuração do Plano de Contas**

#### **Estrutura Implementada**
```
📊 RECEITAS
├── Receita Operacional Bruta
│   ├── Vendas Peças Automotivas
│   ├── Vendas Peças Construção Civil
│   ├── Vendas Linha Própria
│   └── Serviços de Usinagem
└── Outras Receitas
    ├── Receitas Financeiras
    └── Venda de Sucata

💰 DESPESAS
├── Deduções da Receita Bruta
│   ├── ICMS sobre Vendas
│   ├── PIS/COFINS
│   └── Comissões sobre Vendas
├── Custos de Produção
│   ├── Matéria-Prima
│   │   ├── Aço Carbono
│   │   ├── Aço Inoxidável
│   │   └── Alumínio
│   ├── Mão de Obra Direta
│   │   ├── Salários Produção
│   │   └── Encargos Produção
│   └── Custos Indiretos de Fabricação
│       ├── Energia Elétrica Fábrica
│       ├── Manutenção Equipamentos
│       ├── Depreciação Máquinas
│       └── Material de Consumo
├── Despesas Operacionais
│   ├── Despesas Administrativas
│   │   ├── Salários Administração
│   │   ├── Encargos Administração
│   │   ├── Aluguel Escritório
│   │   └── Material de Escritório
│   └── Despesas Comerciais
│       ├── Salários Vendas
│       ├── Comissões Vendedores
│       ├── Marketing
│       └── Fretes sobre Vendas
├── Outras Despesas
│   ├── Despesas Financeiras
│   └── Perdas Diversas
└── Impostos IR/CSLL
    ├── Imposto de Renda
    └── Contribuição Social
```

### **Fase 2: Integração com Módulo Financeiro**

#### **Configuração de Títulos**
1. **Títulos a Receber**:
   - Vendas automotivas → Conta "Vendas Peças Automotivas"
   - Vendas construção → Conta "Vendas Peças Construção Civil"
   - Linha própria → Conta "Vendas Linha Própria"
   - Serviços → Conta "Serviços de Usinagem"

2. **Títulos a Pagar**:
   - Fornecedores matéria-prima → Contas específicas por material
   - Salários → Contas separadas por departamento
   - Energia elétrica → Conta "Energia Elétrica Fábrica"
   - Demais despesas → Contas apropriadas

### **Fase 3: Lançamentos Automáticos**

#### **Processo Automatizado**
- **Vendas**: Lançamento automático ao baixar títulos a receber
- **Compras**: Lançamento automático ao baixar títulos a pagar
- **Folha de pagamento**: Integração com módulo RH
- **Despesas fixas**: Lançamentos recorrentes configurados

## 📊 Resultados Obtidos

### **DRE Detalhado - Março 2024**

```
🏭 METALTECH INDÚSTRIA LTDA.
DEMONSTRAÇÃO DO RESULTADO DO EXERCÍCIO
Período: Março de 2024

(+) RECEITA OPERACIONAL BRUTA
    Vendas Peças Automotivas              R$ 1.125.000,00
    Vendas Peças Construção Civil         R$   875.000,00
    Vendas Linha Própria                  R$   375.000,00
    Serviços de Usinagem                  R$   125.000,00
    ────────────────────────────────────────────────────
    TOTAL RECEITA BRUTA                   R$ 2.500.000,00

(-) DEDUÇÕES DA RECEITA BRUTA
    ICMS sobre Vendas                     R$   300.000,00
    PIS/COFINS                           R$    93.750,00
    Comissões sobre Vendas               R$    31.250,00
    ────────────────────────────────────────────────────
    TOTAL DEDUÇÕES                       R$   425.000,00

(=) RECEITA LÍQUIDA                      R$ 2.075.000,00

(-) CUSTOS DE PRODUÇÃO
    Matéria-Prima
        Aço Carbono                      R$   450.000,00
        Aço Inoxidável                   R$   275.000,00
        Alumínio                         R$   125.000,00
        Subtotal Matéria-Prima           R$   850.000,00
    
    Mão de Obra Direta
        Salários Produção                R$   180.000,00
        Encargos Produção                R$   126.000,00
        Subtotal Mão de Obra Direta      R$   306.000,00
    
    Custos Indiretos de Fabricação
        Energia Elétrica Fábrica         R$    45.000,00
        Manutenção Equipamentos          R$    25.000,00
        Depreciação Máquinas             R$    20.000,00
        Material de Consumo              R$    15.000,00
        Subtotal CIF                     R$   105.000,00
    ────────────────────────────────────────────────────
    TOTAL CUSTOS DE PRODUÇÃO             R$ 1.261.000,00

(=) LUCRO BRUTO                          R$   814.000,00

(-) DESPESAS OPERACIONAIS
    Despesas Administrativas
        Salários Administração           R$    75.000,00
        Encargos Administração           R$    52.500,00
        Aluguel Escritório               R$    15.000,00
        Material de Escritório           R$     3.500,00
        Subtotal Administrativas         R$   146.000,00
    
    Despesas Comerciais
        Salários Vendas                  R$    35.000,00
        Comissões Vendedores             R$    25.000,00
        Marketing                        R$    12.000,00
        Fretes sobre Vendas              R$    18.000,00
        Subtotal Comerciais              R$    90.000,00
    ────────────────────────────────────────────────────
    TOTAL DESPESAS OPERACIONAIS          R$   236.000,00

(=) RESULTADO OPERACIONAL                R$   578.000,00

(+/-) OUTRAS RECEITAS/DESPESAS
    Receitas Financeiras                 R$     8.500,00
    Despesas Financeiras                 R$   (45.000,00)
    Venda de Sucata                      R$     5.500,00
    ────────────────────────────────────────────────────
    TOTAL OUTRAS RECEITAS/DESPESAS       R$   (31.000,00)

(=) RESULTADO ANTES IR/CSLL              R$   547.000,00

(-) IMPOSTOS IR/CSLL
    Imposto de Renda                     R$    82.050,00
    Contribuição Social                  R$    49.230,00
    ────────────────────────────────────────────────────
    TOTAL IMPOSTOS                       R$   131.280,00

(=) RESULTADO LÍQUIDO                    R$   415.720,00
```

### **Análise de Indicadores**

#### **Margens Obtidas**
- **Margem Bruta**: 39,2% (814.000 ÷ 2.075.000)
- **Margem Operacional**: 27,9% (578.000 ÷ 2.075.000)
- **Margem Líquida**: 20,0% (415.720 ÷ 2.075.000)

#### **Análise por Produto**
```
RENTABILIDADE POR LINHA DE PRODUTO - Março 2024
─────────────────────────────────────────────────────────
Produto              Receita    Custo    Margem Bruta   %
Peças Automotivas    1.125.000   567.450    557.550   49,5%
Peças Construção      875.000   472.270    402.730   46,0%
Linha Própria         375.000   188.280    186.720   49,8%
Serviços Usinagem     125.000    33.000     92.000   73,6%
─────────────────────────────────────────────────────────
TOTAL               2.500.000  1.261.000  1.239.000   49,6%
```

## 📈 Análises Realizadas

### **1. Análise de Custos**

#### **Composição dos Custos**
- **Matéria-Prima**: 67,4% dos custos totais
- **Mão de Obra Direta**: 24,3% dos custos totais
- **Custos Indiretos**: 8,3% dos custos totais

#### **Oportunidades Identificadas**
- Negociação de matéria-prima (maior impacto)
- Otimização de processos para reduzir mão de obra
- Controle rigoroso de energia elétrica

### **2. Análise Comparativa**

#### **Evolução Mensal - 1º Trimestre 2024**
```
COMPARATIVO TRIMESTRAL - 2024
─────────────────────────────────────────────────────
                     Jan       Fev       Mar    Variação
Receita Líquida   1.950.000 2.025.000 2.075.000    +6,4%
Lucro Bruto         780.000   810.000   814.000    +4,4%
Resultado Operac.   520.000   545.000   578.000   +11,2%
Resultado Líquido   364.000   381.600   415.720   +14,2%
Margem Líquida       18,7%     18,8%     20,0%    +1,3pp
```

### **3. Análise de Despesas Operacionais**

#### **Controle de Despesas**
- **Despesas Administrativas**: 7,0% da receita líquida
- **Despesas Comerciais**: 4,3% da receita líquida
- **Total Operacionais**: 11,4% da receita líquida

#### **Benchmarking Interno**
- Meta: Manter despesas operacionais < 12% da receita
- Resultado: 11,4% ✅ (dentro da meta)

## 🎯 Benefícios Alcançados

### **📊 Melhoria nos Processos**
- **Tempo de fechamento**: De 15 dias para 3 dias
- **Precisão dos dados**: 99,5% de acuracidade
- **Agilidade na análise**: DRE em tempo real
- **Tomada de decisão**: Baseada em dados precisos

### **💰 Impacto Financeiro**
- **Identificação de custos**: Redução de 8% nos custos
- **Otimização de margem**: Aumento de 3pp na margem líquida
- **Controle de despesas**: Redução de 12% nas despesas operacionais
- **ROI da implementação**: 340% em 6 meses

### **🔍 Insights Gerenciais**
- **Linha mais rentável**: Serviços de usinagem (73,6% margem)
- **Oportunidade**: Expandir serviços especializados
- **Atenção**: Controlar custos de matéria-prima
- **Estratégia**: Focar em produtos de maior margem

## 📋 Lições Aprendidas

### **✅ Fatores de Sucesso**
1. **Planejamento detalhado** do plano de contas
2. **Envolvimento da equipe** financeira e operacional
3. **Validação com contador** antes da implementação
4. **Treinamento adequado** dos usuários
5. **Monitoramento constante** dos resultados

### **⚠️ Pontos de Atenção**
1. **Classificação correta** de custos vs despesas
2. **Consistência** na categorização
3. **Revisão periódica** da estrutura contábil
4. **Backup regular** dos dados contábeis
5. **Auditoria** dos lançamentos automáticos

## 🔄 Próximos Passos

### **📈 Melhorias Planejadas**
1. **Implementar centro de custos** por departamento
2. **Análise ABC** dos produtos
3. **Orçamento vs realizado** mensal
4. **Indicadores de produtividade** por linha
5. **Dashboard executivo** em tempo real

### **🎯 Metas para 2024**
- **Margem líquida**: Atingir 22% (atual: 20%)
- **Redução de custos**: Adicional 5% nos custos totais
- **Crescimento**: 15% na receita líquida
- **Eficiência**: DRE diário disponível

## 📊 Resultados Quantitativos

### **Antes vs Depois da Implementação**
```
COMPARATIVO DE RESULTADOS
──────────────────────────────────────────────────
Métrica                    Antes      Depois    Melhoria
Tempo fechamento mensal    15 dias     3 dias      -80%
Precisão dos dados          85%       99,5%      +14,5pp
Margem líquida identificada  17%        20%       +3pp
Controle de custos         Baixo      Alto       +100%
Satisfação gestores        6/10       9/10       +50%
```

### **ROI da Implementação**
- **Investimento**: R$ 25.000 (licenças + consultoria)
- **Economia mensal**: R$ 28.500 (otimizações identificadas)
- **Payback**: 0,9 meses
- **ROI 12 meses**: 1.268%

## 🔗 Veja também

- [Plano de Contas](../../modulos/contabilidade/plano-de-contas.md)
- [DRE - Demonstração do Resultado](../../modulos/contabilidade/dre-demonstracao-resultado.md)
- [Análise de Custos Industriais](empresa-custos-industriais.md)
- [Centro de Custos](../../modulos/contabilidade/centro-de-custos.md)

---

> **🏭 Sucesso Comprovado**: A MetalTech conseguiu aumentar sua margem líquida de 17% para 20% em apenas 3 meses, com controle total sobre custos e despesas através do módulo Contabilidade.

> **📊 Replicabilidade**: Esta estrutura pode ser adaptada para qualquer empresa industrial, respeitando as particularidades de cada segmento. 