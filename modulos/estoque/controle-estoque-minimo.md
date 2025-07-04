# 📉 Controle de Estoque Mínimo

🏠 [Home](../../index.md) > 📋 [Módulos](../index.md) > 📦 [Estoque](index.md) > **Controle de Estoque Mínimo**

#estoque-minimo #alerta #ruptura #ponto-pedido #reposicao #controle #automacao

---

## 🎯 O que é Estoque Mínimo?

O **Estoque Mínimo** é a **menor quantidade** de um produto que deve ser mantida em estoque para evitar **ruptura** (falta do produto). É um **ponto de alerta** que indica quando é necessário fazer uma nova compra.

### 🚀 **Por que é Fundamental?**
- 🚨 **Evitar ruptura** - Nunca ficar sem produto
- 💰 **Otimizar capital** - Não ter estoque excessivo
- 📈 **Melhorar vendas** - Produto sempre disponível
- 🎯 **Satisfação do cliente** - Atendimento garantido
- 📊 **Planejamento** - Compras organizadas
- 🔄 **Automação** - Alertas automáticos

> **💡 Importante**: O estoque mínimo deve ser calculado considerando tempo de reposição e variação de demanda!

---

## 📊 Conceitos Fundamentais

### **📉 Estoque Mínimo**
**Quantidade** mínima que deve ser mantida

**Características:**
- 🚨 **Ponto de alerta** - Quando chegar neste nível
- 📅 **Tempo de reposição** - Considera prazo de entrega
- 📊 **Variação de demanda** - Considera oscilações
- 🎯 **Margem de segurança** - Proteção contra imprevistos
- 💰 **Custo de oportunidade** - Equilíbrio entre falta e excesso

**Fórmula básica:**
```
Estoque Mínimo = (Consumo Médio Diário × Tempo de Reposição) + Estoque de Segurança
```

### **📈 Ponto de Pedido**
**Momento** exato para fazer nova compra

**Características:**
- 🎯 **Trigger** - Disparador automático
- 📅 **Timing** - Momento certo de comprar
- 📊 **Cálculo** - Baseado em dados históricos
- 🔄 **Automação** - Pode ser automatizado
- 💰 **Otimização** - Reduz custos

**Fórmula:**
```
Ponto de Pedido = Estoque Mínimo + Lote Econômico
```

### **🛡️ Estoque de Segurança**
**Quantidade extra** para imprevistos

**Características:**
- 🚨 **Proteção** - Contra variações
- 📊 **Estatística** - Baseado em desvio padrão
- 🎯 **Confiabilidade** - Nível de serviço desejado
- 💰 **Custo** - Equilibrar proteção e investimento
- 📈 **Flexibilidade** - Adaptação a mudanças

**Fórmula:**
```
Estoque de Segurança = Fator de Segurança × √(Tempo de Reposição) × Desvio Padrão da Demanda
```

### **📦 Lote Econômico**
**Quantidade ideal** para comprar

**Características:**
- 💰 **Otimização** - Menor custo total
- 📊 **Cálculo** - Baseado em custos
- 🔄 **Frequência** - Quantas vezes comprar
- 🎯 **Eficiência** - Melhor relação custo-benefício
- 📈 **Escala** - Aproveitar descontos

**Fórmula:**
```
Lote Econômico = √((2 × Demanda Anual × Custo do Pedido) / Custo de Manutenção)
```

---

## 📊 Métodos de Cálculo

### **📈 Método Estatístico**
**Cálculo** baseado em dados históricos

**Processo:**
1. **Coletar** dados de vendas (6-12 meses)
2. **Calcular** média e desvio padrão
3. **Definir** nível de serviço desejado
4. **Calcular** estoque de segurança
5. **Determinar** estoque mínimo

**Vantagens:**
- 📊 **Precisão** - Baseado em dados reais
- 🎯 **Confiabilidade** - Método científico
- 🔄 **Adaptação** - Considera variações
- 📈 **Otimização** - Melhor resultado
- 🤖 **Automação** - Pode ser automatizado

**Exemplo prático:**
```
Produto: Camiseta Branca
Venda média diária: 10 unidades
Desvio padrão: 3 unidades
Tempo de reposição: 15 dias
Nível de serviço: 95% (fator = 1,65)

Estoque de Segurança = 1,65 × √15 × 3 = 19 unidades
Estoque Mínimo = (10 × 15) + 19 = 169 unidades
```

### **🎯 Método Empírico**
**Cálculo** baseado em experiência

**Processo:**
1. **Analisar** histórico de vendas
2. **Considerar** sazonalidade
3. **Avaliar** tempo de fornecedor
4. **Definir** margem de segurança
5. **Estabelecer** estoque mínimo

**Vantagens:**
- ⚡ **Rapidez** - Implementação rápida
- 💰 **Baixo custo** - Não precisa sistema complexo
- 🎯 **Flexibilidade** - Ajustes fáceis
- 📋 **Simplicidade** - Fácil entendimento
- 🔄 **Adaptação** - Mudanças rápidas

**Exemplo prático:**
```
Produto: Tênis Esportivo
Venda média mensal: 50 pares
Tempo de reposição: 30 dias
Margem de segurança: 50%

Consumo no prazo = 50 ÷ 30 = 1,67 pares/dia
Estoque mínimo = 1,67 × 30 × 1,5 = 75 pares
```

### **📊 Método ABC**
**Cálculo** por importância do produto

**Classificação:**
- 🅰️ **Classe A** - 20% dos produtos, 80% do faturamento
- 🅱️ **Classe B** - 30% dos produtos, 15% do faturamento
- 🅲️ **Classe C** - 50% dos produtos, 5% do faturamento

**Estratégias:**
- 🅰️ **Classe A** - Controle rigoroso, estoque baixo
- 🅱️ **Classe B** - Controle moderado, estoque médio
- 🅲️ **Classe C** - Controle simples, estoque alto

**Processo:**
1. **Classificar** produtos por importância
2. **Definir** estratégia por classe
3. **Calcular** estoque mínimo específico
4. **Monitorar** conforme criticidade
5. **Ajustar** periodicamente

---

## 🚨 Sistema de Alertas

### **📱 Alertas Automáticos**
**Notificações** quando atingir estoque mínimo

**Tipos de alerta:**
- 🔔 **Sistema** - Notificação no ERP
- 📧 **E-mail** - Mensagem automática
- 📱 **WhatsApp** - Notificação mobile
- 📊 **Dashboard** - Indicador visual
- 📋 **Relatório** - Lista de produtos

**Configurações:**
- 🎯 **Nível** - Quando disparar (estoque mínimo)
- 👥 **Destinatários** - Quem recebe
- ⏰ **Frequência** - Quantas vezes avisar
- 📊 **Formato** - Como apresentar
- 🔄 **Integração** - Com outros sistemas

### **🚨 Níveis de Alerta**
**Diferentes** intensidades de aviso

#### **🟡 Alerta Amarelo**
**Atenção** - Estoque baixo

**Características:**
- 📊 **Nível** - 120% do estoque mínimo
- 🎯 **Ação** - Monitorar de perto
- ⏰ **Urgência** - Baixa
- 👥 **Responsável** - Comprador
- 📋 **Frequência** - Diária

#### **🟠 Alerta Laranja**
**Cuidado** - Estoque crítico

**Características:**
- 📊 **Nível** - 100% do estoque mínimo
- 🎯 **Ação** - Iniciar processo de compra
- ⏰ **Urgência** - Média
- 👥 **Responsável** - Gerente de compras
- 📋 **Frequência** - Imediata

#### **🔴 Alerta Vermelho**
**Perigo** - Ruptura iminente

**Características:**
- 📊 **Nível** - Abaixo do estoque mínimo
- 🎯 **Ação** - Compra urgente
- ⏰ **Urgência** - Alta
- 👥 **Responsável** - Diretor
- 📋 **Frequência** - Contínua

### **📊 Dashboard de Controle**
**Painel** visual para monitoramento

**Indicadores:**
- 📈 **Gráfico** - Evolução do estoque
- 🚨 **Alertas** - Produtos críticos
- 📊 **Percentual** - Nível atual vs. mínimo
- 🎯 **Ranking** - Produtos mais críticos
- 📅 **Previsão** - Quando chegará ao mínimo

**Funcionalidades:**
- 🔍 **Filtros** - Por categoria, fornecedor
- 📊 **Drill-down** - Detalhamento
- 📱 **Mobile** - Acesso remoto
- 🔄 **Tempo real** - Atualização automática
- 📋 **Exportação** - Relatórios

---

## 🔄 Automação de Reposição

### **🤖 Compra Automática**
**Geração** automática de pedidos

**Como funciona:**
1. **Monitorar** estoque continuamente
2. **Detectar** quando atingir ponto de pedido
3. **Calcular** quantidade a comprar
4. **Gerar** pedido automaticamente
5. **Enviar** para fornecedor
6. **Acompanhar** status do pedido

**Configurações:**
- 🎯 **Produtos** - Quais podem ser automáticos
- 🏢 **Fornecedores** - Parceiros integrados
- 💰 **Limites** - Valor máximo automático
- 👥 **Aprovação** - Níveis de autorização
- 📋 **Validação** - Regras de negócio

### **📊 Integração com Fornecedores**
**Conexão** direta para reposição

**Tipos de integração:**
- 📧 **E-mail** - Envio automático de pedidos
- 📱 **API** - Integração sistema a sistema
- 🔄 **EDI** - Troca eletrônica de dados
- 📄 **Portal** - Plataforma do fornecedor
- 📱 **WhatsApp** - Mensagem automática

**Benefícios:**
- ⚡ **Agilidade** - Processo mais rápido
- 🎯 **Precisão** - Sem erros de digitação
- 📊 **Rastreabilidade** - Histórico completo
- 💰 **Economia** - Redução de custos
- 🔄 **Automação** - Sem intervenção manual

### **📈 Previsão de Demanda**
**Antecipação** das necessidades

**Métodos:**
- 📊 **Média móvel** - Baseado em histórico
- 📈 **Tendência** - Crescimento/declínio
- 🔄 **Sazonalidade** - Padrões cíclicos
- 🤖 **Machine Learning** - Inteligência artificial
- 📅 **Eventos** - Promoções, datas especiais

**Aplicações:**
- 🎯 **Ajuste** - Estoque mínimo dinâmico
- 📊 **Planejamento** - Compras antecipadas
- 💰 **Otimização** - Redução de custos
- 🔄 **Automação** - Reposição inteligente
- 📈 **Crescimento** - Suporte ao negócio

---

## 📊 Relatórios e Análises

### **📋 Relatório de Estoque Mínimo**
**Lista** de produtos com estoque baixo

**Informações incluídas:**
- 📦 **Produto** - Identificação completa
- 📊 **Estoque atual** - Quantidade disponível
- 📉 **Estoque mínimo** - Ponto de alerta
- 📈 **Percentual** - Atual vs. mínimo
- 📅 **Dias** - Estimativa de ruptura
- 🏢 **Fornecedor** - Principal
- 💰 **Valor** - Investimento necessário

**Filtros:**
- 🚨 **Nível** - Amarelo, laranja, vermelho
- 🏷️ **Categoria** - Grupo de produtos
- 🏢 **Fornecedor** - Específico
- 📍 **Depósito** - Localização
- 💰 **Valor** - Faixa de investimento

### **📈 Relatório de Giro vs. Estoque**
**Análise** de eficiência do estoque

**Informações incluídas:**
- 📦 **Produto** - Identificação
- 🔄 **Giro** - Velocidade de venda
- 📊 **Estoque** - Quantidade atual
- 📅 **Cobertura** - Dias de venda
- 💰 **Investimento** - Valor em estoque
- 🎯 **Classificação** - ABC
- 📈 **Tendência** - Crescimento/declínio

**Análises:**
- 🔄 **Alto giro** - Produtos que vendem muito
- 📊 **Baixo giro** - Produtos parados
- 💰 **Alto investimento** - Produtos caros
- 🎯 **Oportunidade** - Ajustes necessários
- 📈 **Estratégia** - Ações recomendadas

### **🎯 Relatório de Eficiência**
**Performance** do controle de estoque

**Indicadores:**
- 📊 **Acuracidade** - Precisão dos cálculos
- 🚨 **Rupturas** - Quantas vezes faltou
- 💰 **Investimento** - Valor em estoque
- 🔄 **Giro** - Velocidade média
- 📈 **Melhoria** - Evolução dos indicadores

**Metas:**
- 🎯 **Ruptura** - Máximo 2% dos produtos
- 📊 **Giro** - Mínimo 6 vezes por ano
- 💰 **Investimento** - Máximo 30% do faturamento
- 🔄 **Reposição** - Prazo médio de 15 dias
- 📈 **Crescimento** - Melhoria contínua

---

## 🎯 Melhores Práticas

### **✅ Definição Correta**
- 📊 **Dados históricos** - Usar informações reais
- 🎯 **Sazonalidade** - Considerar variações
- 📈 **Tendência** - Crescimento/declínio
- 🔄 **Revisão** - Atualizar regularmente
- 💰 **Custo-benefício** - Equilibrar investimento

### **✅ Monitoramento Contínuo**
- 📱 **Alertas** - Sistema automático
- 📊 **Dashboard** - Acompanhamento visual
- 📋 **Relatórios** - Análise periódica
- 🔍 **Auditoria** - Verificação regular
- 📈 **Melhoria** - Ajustes constantes

### **✅ Integração Sistêmica**
- 🔄 **Automação** - Processos automáticos
- 📊 **Integração** - Módulos conectados
- 🤖 **Inteligência** - Análise preditiva
- 📱 **Mobilidade** - Acesso remoto
- 🔐 **Segurança** - Controle de acesso

### **✅ Capacitação da Equipe**
- 📚 **Treinamento** - Conceitos básicos
- 🎯 **Responsabilidade** - Definir papéis
- 📋 **Procedimentos** - Processos claros
- 🔄 **Melhoria** - Sugestões da equipe
- 📈 **Desenvolvimento** - Capacitação contínua

---

## 🚨 Problemas Comuns e Soluções

### **❌ Ruptura Frequente**
**Problema**: Produtos faltando constantemente

**Possíveis causas:**
- 📉 **Estoque baixo** - Mínimo mal calculado
- 📊 **Demanda subestimada** - Previsão errada
- ⏰ **Atraso fornecedor** - Prazo não cumprido
- 🔄 **Processo lento** - Reposição demorada
- 📋 **Falta de controle** - Sem monitoramento

**Soluções:**
1. **Recalcular** estoque mínimo
2. **Revisar** previsão de demanda
3. **Negociar** prazos com fornecedores
4. **Agilizar** processo de compras
5. **Implementar** alertas automáticos

### **❌ Estoque Excessivo**
**Problema**: Muito dinheiro parado

**Possíveis causas:**
- 📈 **Estoque alto** - Mínimo mal calculado
- 📊 **Demanda superestimada** - Previsão errada
- 💰 **Compras grandes** - Lotes inadequados
- 🔄 **Giro baixo** - Produtos parados
- 📋 **Falta de análise** - Sem acompanhamento

**Soluções:**
1. **Recalcular** estoque mínimo
2. **Revisar** previsão de demanda
3. **Otimizar** lotes de compra
4. **Analisar** giro dos produtos
5. **Implementar** controle rigoroso

### **❌ Alertas Ignorados**
**Problema**: Avisos não são atendidos

**Possíveis causas:**
- 🔔 **Muitos alertas** - Excesso de notificações
- 👥 **Responsabilidade** - Não definida
- 📋 **Processo** - Não estabelecido
- 🎯 **Prioridade** - Não clara
- 📊 **Confiança** - Não acreditam no sistema

**Soluções:**
1. **Ajustar** níveis de alerta
2. **Definir** responsabilidades
3. **Estabelecer** processos claros
4. **Priorizar** alertas críticos
5. **Treinar** equipe no sistema

---

## 📚 Documentação Relacionada

### **🔗 Processos Relacionados**
- **[Movimentacao Estoque](movimentacao-estoque.md)** - Entradas e saídas
- **[Inventario Fisico](inventario-fisico.md)** - Contagem física
- **[Analise Abc](analise-abc.md)** - Classificação de produtos
- **[Previsao Demanda](previsao-demanda.md)** - Planejamento futuro

### **🔗 Módulos Integrados**
- **[Compras](../financeiro/contas-a-pagar.md)** - Processo de compras
- **[Vendas](../vendas/index.md)** - Análise de vendas
- **[Relatórios](../relatorios/index.md)** - Relatórios gerenciais
- **[Financeiro](../financeiro/index.md)** - Impacto financeiro

### **🔗 Fluxos Relacionados**
- **[Fluxo Reposicao](../../fluxos/fluxo-reposicao.md)** - Processo de reposição
- **[Fluxo Compras](../../fluxos/fluxo-compras.md)** - Processo de compras
- **[Fluxo Planejamento](../../fluxos/fluxo-planejamento.md)** - Planejamento de estoque

---

## 📋 Checklist de Controle

### **✅ Configuração Inicial**
- [ ] Estoque mínimo calculado
- [ ] Ponto de pedido definido
- [ ] Estoque de segurança estabelecido
- [ ] Lote econômico determinado
- [ ] Alertas configurados
- [ ] Responsáveis definidos

### **✅ Monitoramento Diário**
- [ ] Alertas verificados
- [ ] Produtos críticos identificados
- [ ] Ações necessárias tomadas
- [ ] Pedidos gerados
- [ ] Status acompanhado
- [ ] Relatórios analisados

### **✅ Revisão Periódica**
- [ ] Parâmetros reavaliados
- [ ] Dados históricos analisados
- [ ] Previsões atualizadas
- [ ] Processos melhorados
- [ ] Equipe treinada
- [ ] Resultados medidos

### **✅ Melhoria Contínua**
- [ ] Indicadores acompanhados
- [ ] Problemas identificados
- [ ] Soluções implementadas
- [ ] Resultados medidos
- [ ] Processos otimizados
- [ ] Conhecimento compartilhado

---

**💡 Dica Final**: O controle de estoque mínimo é essencial para o sucesso do negócio. Mantenha os parâmetros atualizados e monitore constantemente - nunca deixe faltar produto para seu cliente!

---

**Tags relacionadas**: #estoque-minimo #alerta #ruptura #ponto-pedido #reposicao #controle #automacao #otimizacao #planejamento #eficiencia 