# 🧠 Sistema de Enquetes Inteligentes - CRM

🏠 [Home](../../../index.md) > 📋 [Módulos](../../index.md) > 👥 [CRM](../index.md) > **Sistema de Enquetes**

#crm #enquetes #questionarios #scoring #qualificacao #inteligencia #avancado

## 🎯 O que são Enquetes Inteligentes

O **Sistema de Enquetes Inteligentes** é o diferencial exclusivo do CRM GerenciaTech. Permite criar questionários com **pontuação ponderada** que qualificam leads automaticamente, gerando um **score científico** baseado nas respostas. Cada resposta tem um peso específico que contribui para a classificação final do prospect.

### 🌟 Diferenciais das Enquetes

- **⚖️ Pontuação Ponderada**: Cada resposta tem peso específico na qualificação
- **🎯 Qualificação Automática**: Score calculado automaticamente após as respostas
- **📊 Visualização Gráfica**: Gráficos de resultado gerados automaticamente
- **📧 Email Personalizado**: Envio automático baseado no nível atingido
- **🔄 Integração Completa**: Vinculação direta com gestão de leads

## 🚀 Como Criar e Gerenciar Enquetes

### 📋 **Pré-requisitos**
- Módulo CRM ativo
- Permissões de administrador do CRM
- Templates de email configurados (nv1-nv4)
- Sistema de scoring definido

### 🔧 **Criação de Perguntas**

#### **Passo 1: Acessar Gestão de Perguntas**
1. Acesse **CRM > Enquetes > Perguntas** no menu
2. Clique em **"Nova Pergunta"**
3. Defina o tipo de pergunta

#### **Passo 2: Configurar a Pergunta**
1. **Informações Básicas**:
   - **Título**: Texto da pergunta que será exibido
   - **Descrição**: Detalhamento ou contexto adicional
   - **Tipo de Campo**: Formato da resposta

2. **Tipos de Campo Disponíveis**:
   - **Radio**: Seleção única entre opções
   - **Select**: Lista suspensa de opções
   - **Text**: Campo de texto livre
   - **Checkbox**: Múltipla seleção

#### **Passo 3: Definir Respostas e Pesos**
1. Para cada pergunta, clique em **"Adicionar Resposta"**
2. **Configuração da Resposta**:
   - **Texto**: Conteúdo da opção de resposta
   - **Peso**: Valor numérico para scoring (0-100)

3. **Estratégia de Pontuação**:
   - **Peso 0-25**: Respostas que indicam baixo potencial
   - **Peso 26-50**: Respostas de potencial médio
   - **Peso 51-75**: Respostas de alto potencial
   - **Peso 76-100**: Respostas de altíssimo potencial

### 📊 **Sistema de Scoring**

#### **Cálculo Automático**
O sistema calcula automaticamente o score baseado na fórmula:

```
Score Final = (Soma dos Pesos das Respostas / Peso Máximo Possível) × 100
```

#### **Níveis de Qualificação**
- **Nv1 (0-25%)**: Presença Digital Inexistente
- **Nv2 (25-50%)**: Presença Digital Leve  
- **Nv3 (50-75%)**: Presença Digital Média
- **Nv4 (75-100%)**: Presença Digital Alta e Adequada

### 🎨 **Personalização Visual**

#### **Gráficos Automáticos**
- Geração automática via QuickChart API
- Gráfico tipo "velocímetro" mostrando o score
- Cores personalizadas por nível:
  - **Nv1**: Laranja (#F57C10)
  - **Nv2**: Azul (#10A9F5)  
  - **Nv3**: Azul escuro (#14A3CA)
  - **Nv4**: Verde (#07C921)

#### **Templates de Email**
- 4 templates específicos por nível de qualificação
- Conteúdo estratégico personalizado
- Plano de ação específico para cada score
- Substituição automática de variáveis

## 💡 Exemplos Práticos de Enquetes

### 🏢 **Enquete: Maturidade Digital Empresarial**

#### **Pergunta 1: "Qual o nível atual da presença digital da sua empresa?"**
- **Não temos site ou redes sociais** (Peso: 10)
- **Temos site básico** (Peso: 30)
- **Site + redes sociais ativas** (Peso: 60)
- **Presença digital completa e estratégica** (Peso: 90)

#### **Pergunta 2: "Como vocês gerenciam relacionamento com clientes?"**
- **Planilhas ou anotações** (Peso: 15)
- **Sistema básico de cadastro** (Peso: 35)
- **CRM simples** (Peso: 65)
- **CRM avançado com automação** (Peso: 95)

#### **Pergunta 3: "Qual o percentual de vendas online?"**
- **0% - Apenas presencial** (Peso: 5)
- **1-25% - Pouco online** (Peso: 25)
- **26-50% - Híbrido equilibrado** (Peso: 55)
- **51%+ - Foco digital** (Peso: 85)

### 📈 **Enquete: Potencial de Investimento**

#### **Pergunta 1: "Qual o faturamento mensal da empresa?"**
- **Até R$ 50.000** (Peso: 20)
- **R$ 50.001 a R$ 200.000** (Peso: 50)
- **R$ 200.001 a R$ 500.000** (Peso: 75)
- **Acima de R$ 500.000** (Peso: 100)

#### **Pergunta 2: "Há orçamento para investir em tecnologia?"**
- **Não há previsão** (Peso: 10)
- **Talvez no futuro** (Peso: 30)
- **Sim, em 6-12 meses** (Peso: 70)
- **Sim, imediatamente** (Peso: 100)

## 🔄 **Aplicação de Enquetes**

### 📝 **Processo de Aplicação**
1. **Seleção do Lead**: Escolher prospect na lista
2. **Escolha da Enquete**: Selecionar questionário apropriado
3. **Coleta de Respostas**: Registrar respostas do lead
4. **Cálculo Automático**: Sistema calcula score automaticamente
5. **Envio de Email**: Template personalizado enviado automaticamente

### 📊 **Análise de Resultados**
- **Score Individual**: Pontuação específica do lead
- **Nível de Qualificação**: Classificação automática (nv1-nv4)
- **Gráfico Visual**: Representação gráfica do resultado
- **Plano de Ação**: Estratégias específicas por nível

## 💡 Dicas para Enquetes Eficazes

### ✅ **Boas Práticas**

#### **Criação de Perguntas**
> **Dica**: Faça perguntas objetivas e específicas. Evite termos técnicos que o lead pode não entender.

#### **Definição de Pesos**
> **Estratégia**: Distribua os pesos de forma que respostas mais qualificadas tenham pontuação significativamente maior.

#### **Quantidade de Perguntas**
> **Recomendação**: Use entre 8-12 perguntas para obter dados suficientes sem cansar o lead.

### ⚠️ **Cuidados Importantes**

#### **Pesos Balanceados**
> **Atenção**: Certifique-se de que a distribuição de pesos permite diferenciação clara entre os níveis.

#### **Validação de Respostas**
> **Importante**: Todas as perguntas devem ter pelo menos 2 opções de resposta com pesos diferentes.

## 📊 Relatórios e Análises

### 📈 **Relatórios Disponíveis**
- **Relatório por Resposta**: Segmentação de leads por características
- **Análise de Score**: Distribuição de pontuações
- **Eficácia de Perguntas**: Quais perguntas melhor qualificam
- **Conversão por Nível**: Taxa de conversão por score

### 🎯 **Métricas Importantes**
- **Score Médio por Origem**: Qualidade dos canais de captação
- **Distribuição por Níveis**: Percentual em cada classificação
- **Taxa de Resposta**: Engajamento com as enquetes
- **Correlação Score-Conversão**: Validação da eficácia

## 🔗 Integrações

### 🤝 **Módulos Relacionados**
- **Gestão de Leads**: Aplicação direta nos prospects
- **Email Marketing**: Envio automático de templates
- **Relatórios**: Análise de eficácia das enquetes
- **Vendas**: Priorização baseada em score

### 🌐 **Ferramentas Externas**
- **QuickChart**: Geração de gráficos visuais
- **Brevo**: Plataforma de email marketing
- **APIs Web**: Integração com formulários online

## 🆘 Troubleshooting

### ❌ **Problemas Comuns**

**Score não calcula corretamente**
- **Causa**: Perguntas sem peso definido ou pesos zerados
- **Solução**: Verificar se todas as respostas têm peso > 0

**Email não é enviado automaticamente**
- **Causa**: Template não configurado para o nível
- **Solução**: Configurar template específico (nv1-nv4)

**Gráfico não aparece no email**
- **Causa**: Problema na API do QuickChart
- **Solução**: Verificar conectividade e formato do gráfico

### ✅ **Soluções Rápidas**
1. **Recalcular Score**: Editar e salvar novamente as respostas
2. **Reenviar Email**: Usar opção de reenvio manual
3. **Validar Pesos**: Verificar distribuição nas configurações

## 🔄 Próximos Passos

- **Configurar Templates**: [Email Marketing](email-marketing.md)
- **Analisar Qualificação**: [Qualificação de Leads](qualificacao-leads.md)
- **Ver Resultados**: [Gestão de Leads](gestao-leads.md)

## 🔗 Veja Também

- [Fluxo: Captação e Qualificação](../../fluxos/fluxo-captacao-qualificacao-leads.md)
- [Caso: Empresa B2B](../../casos-uso/servicos/empresa-b2b-ciclo-longo.md)
- [Templates de Email](email-marketing.md)

---

> **🎯 Resultado Esperado**: Empresas que usam enquetes inteligentes relatam 60% mais precisão na qualificação de leads e 40% de aumento na taxa de conversão através da segmentação automática. 