# 🛒 Caso de Uso: Venda no Balcão

🏠 [Home](../../index.md) > 💡 [Casos de Uso](../index.md) > 🏪 [Comércio Geral](index.md) > **🛒 Venda no Balcão**

#caso-uso #venda #balcao #pratico #exemplo #passo-a-passo

---

## 🎯 Cenário do Caso

### 📋 **Situação**
**Maria Silva** é proprietária de uma loja de produtos para casa e jardim. É uma tarde de sábado e **João Santos** entra na loja procurando itens para reformar seu jardim. Maria precisa atendê-lo rapidamente, pois há outros clientes aguardando.

### 👥 **Personagens**
- **Maria Silva**: Proprietária da loja, usuária do ERP
- **João Santos**: Cliente que precisa de produtos para jardim
- **Sistema ERP**: White configurado para comércio varejista

### 🎯 **Objetivo**
Realizar uma venda completa no balcão, desde o atendimento inicial até a entrega dos produtos, utilizando o PDV do ERP White de forma eficiente.

---

## 📋 Contexto Detalhado

### 🏪 **Sobre a Loja**
- **Nome**: Casa & Jardim Maria Silva
- **Tipo**: Comércio varejista
- **Produtos**: Ferramentas, sementes, vasos, adubos, decoração
- **Movimento**: Alto aos sábados
- **Equipe**: Maria (proprietária) + 2 funcionários

### 👤 **Perfil do Cliente**
- **Nome**: João Santos
- **Perfil**: Cliente eventual (não cadastrado)
- **Necessidade**: Reformar jardim de casa
- **Orçamento**: Aproximadamente R$ 300,00
- **Urgência**: Quer comprar hoje

### 🎯 **Desafios do Atendimento**
- ⏰ **Rapidez**: Outros clientes aguardando
- 🎯 **Assertividade**: Identificar necessidades rapidamente
- 💰 **Vendas**: Sugerir produtos complementares
- 📄 **Fiscal**: Emitir nota fiscal corretamente

---

## 🔄 Fluxo do Atendimento

### 1️⃣ **Recepção do Cliente (30 segundos)**

#### **Situação**
João entra na loja e olha ao redor, um pouco perdido.

#### **Ação da Maria**
```
Maria: "Bom dia! Em que posso ajudá-lo?"
João: "Bom dia! Estou reformando meu jardim e preciso de algumas coisas."
Maria: "Perfeito! Que tipo de jardim você tem em mente?"
```

#### **No Sistema**
- Maria mantém o **PDV aberto** em segundo plano
- **Caixa já está aberto** desde a manhã
- **Impressora fiscal** funcionando normalmente

---

### 2️⃣ **Qualificação Rápida (2 minutos)**

#### **Conversa**
```
João: "Quero plantar algumas flores e melhorar a terra. O espaço é pequeno, uns 10m²."
Maria: "Entendi! Você já tem as ferramentas básicas?"
João: "Tenho uma pá pequena, mas acho que vou precisar de mais coisa."
Maria: "Perfeito! Vou te mostrar um kit completo que vai resolver tudo."
```

#### **Identificação das Necessidades**
- 🌱 **Sementes/Mudas**: Flores para jardim pequeno
- 🌿 **Terra/Adubo**: Melhorar qualidade do solo
- 🔧 **Ferramentas**: Complementar o que já tem
- 🏺 **Vasos**: Possível interesse
- 💰 **Orçamento**: R$ 300,00 (informação obtida indiretamente)

---

### 3️⃣ **Apresentação dos Produtos (3 minutos)**

#### **Estratégia de Vendas**
Maria decide mostrar um **kit completo** ao invés de produtos isolados.

#### **Produtos Selecionados**
1. **Kit Ferramentas Jardim** - R$ 89,90
   - Pá grande, rastelo, enxada pequena, regador
2. **Terra Adubada 20kg** - R$ 24,90
3. **Sementes Flores Mistas** - R$ 18,90
4. **Adubo Orgânico 2kg** - R$ 16,90
5. **Luvas de Jardinagem** - R$ 12,90

#### **Apresentação**
```
Maria: "Olha só, João! Este kit tem tudo que você precisa. Com essas ferramentas, essa terra adubada e essas sementes, seu jardim vai ficar lindo!"
João: "Parece bom! Quanto fica tudo isso?"
Maria: "Deixe-me calcular no sistema..."
```

---

### 4️⃣ **Processamento no PDV (1 minuto)**

#### **Acesso ao PDV**
1. **Maria clica** no PDV já aberto
2. **Sistema carrega** interface de vendas
3. **Cursor** já está no campo de produtos

#### **Adição dos Produtos**
```
Produto 1: Kit Ferramentas Jardim
- Código: 1001 (Maria digita)
- Quantidade: 1
- Preço: R$ 89,90 ✓

Produto 2: Terra Adubada 20kg  
- Código: 2045 (código de barras)
- Quantidade: 1
- Preço: R$ 24,90 ✓

Produto 3: Sementes Flores Mistas
- Código: 3012 (Maria digita)
- Quantidade: 1
- Preço: R$ 18,90 ✓

Produto 4: Adubo Orgânico 2kg
- Código: 2078 (código de barras)
- Quantidade: 1
- Preço: R$ 16,90 ✓

Produto 5: Luvas de Jardinagem
- Código: 1089 (Maria digita)
- Quantidade: 1
- Preço: R$ 12,90 ✓
```

#### **Total Calculado**
- **Subtotal**: R$ 163,50
- **Desconto**: R$ 0,00
- **Total**: R$ 163,50

---

### 5️⃣ **Venda Adicional (1 minuto)**

#### **Oportunidade Identificada**
```
Maria: "João, o total deu R$ 163,50. Como você disse que tem uns R$ 300 de orçamento, que tal levar também estes vasos? Eles ficam lindos com essas flores!"
João: "Ah, boa ideia! Quanto custam?"
Maria: "Estes dois vasos decorativos saem por R$ 45,00 os dois."
João: "Perfeito! Vou levar."
```

#### **Adição no Sistema**
```
Produto 6: Vasos Decorativos (Kit c/ 2)
- Código: 4025
- Quantidade: 1
- Preço: R$ 45,00 ✓
```

#### **Novo Total**
- **Subtotal**: R$ 208,50
- **Desconto**: R$ 0,00
- **Total**: R$ 208,50

---

### 6️⃣ **Identificação do Cliente (1 minuto)**

#### **Necessidade Fiscal**
```
Maria: "João, preciso do seu CPF para a nota fiscal. É obrigatório para vendas acima de R$ 200."
João: "Claro! É 123.456.789-10."
Maria: "Perfeito! Qual seu nome completo?"
João: "João Santos Silva."
```

#### **Cadastro Rápido no Sistema**
```
Cliente: Consumidor Final → Novo Cliente
- Nome: João Santos Silva
- CPF: 12345678910
- Telefone: (11) 99999-9999 (opcional)
- Email: joao@email.com (opcional)
- Endereço: Rua das Flores, 123 (opcional)
```

> **💡 Dica**: Maria faz apenas o cadastro mínimo para não perder tempo.

---

### 7️⃣ **Processamento do Pagamento (2 minutos)**

#### **Escolha da Forma de Pagamento**
```
Maria: "Como você gostaria de pagar? Temos dinheiro, cartão ou PIX."
João: "Vou pagar no cartão de débito."
Maria: "Perfeito!"
```

#### **No Sistema**
1. **Maria clica** em "Cartão de Débito"
2. **Sistema registra** a forma de pagamento
3. **Valor total**: R$ 208,50 confirmado

#### **Processamento do Cartão**
1. **Maria passa** o cartão na máquina
2. **João digita** a senha
3. **Transação aprovada** ✓
4. **Comprovante** impresso

---

### 8️⃣ **Finalização da Venda (1 minuto)**

#### **No Sistema**
1. **Maria clica** em "Finalizar Venda"
2. **Sistema processa** a transação
3. **NFCe é gerada** automaticamente
4. **Estoque é baixado** automaticamente

#### **Resultados Automáticos**
```
✅ Venda registrada: #001234
✅ NFCe emitida: 35210812345678901234550010000012341234567890
✅ Estoque baixado:
   - Kit Ferramentas: 15 → 14 unidades
   - Terra Adubada: 45 → 44 unidades
   - Sementes: 30 → 29 unidades
   - Adubo: 25 → 24 unidades
   - Luvas: 12 → 11 unidades
   - Vasos: 8 → 7 unidades
✅ Financeiro atualizado: +R$ 208,50
```

---

### 9️⃣ **Entrega e Finalização (2 minutos)**

#### **Preparação dos Produtos**
```
Maria: "Vou separar tudo para você. A terra é um pouco pesada, você consegue carregar?"
João: "Sim, tranquilo!"
Maria: "Ótimo! Vou embalar tudo direitinho."
```

#### **Documentos Entregues**
- 📄 **NFCe** (cupom fiscal)
- 💳 **Comprovante** do cartão
- 📋 **Nota fiscal** (DANFE da NFCe)

#### **Orientações Finais**
```
Maria: "João, qualquer dúvida sobre o plantio, pode voltar aqui que eu te ajudo! E se precisar de mais alguma coisa para o jardim, temos tudo!"
João: "Perfeito! Muito obrigado pelo atendimento!"
```

---

## 📊 Resultados da Venda

### 💰 **Financeiro**
- **Valor Total**: R$ 208,50
- **Forma de Pagamento**: Cartão de Débito
- **Margem Estimada**: 35% (R$ 73,00)
- **Ticket Médio**: Acima da média da loja

### 📦 **Produtos Vendidos**
- **6 itens** diferentes
- **Venda cruzada** bem-sucedida (vasos)
- **Kit completo** vendido
- **Estoque atualizado** automaticamente

### 👤 **Cliente**
- **Novo cliente** cadastrado
- **Experiência positiva** de compra
- **Potencial** para recompra
- **Indicação** provável

### ⏱️ **Tempo de Atendimento**
- **Total**: 11 minutos
- **Qualificação**: 2 minutos
- **Apresentação**: 3 minutos
- **Processamento**: 4 minutos
- **Finalização**: 2 minutos

---

## 🎯 Pontos de Sucesso

### ✅ **Atendimento Eficiente**
- **Qualificação rápida** das necessidades
- **Sugestão de kit** ao invés de produtos isolados
- **Venda adicional** bem executada
- **Atendimento personalizado**

### ✅ **Uso do Sistema**
- **PDV funcionando** perfeitamente
- **Códigos de barras** agilizaram processo
- **Cadastro rápido** do cliente
- **Integração automática** funcionou

### ✅ **Compliance Fiscal**
- **NFCe emitida** corretamente
- **CPF coletado** conforme legislação
- **Documentos entregues** ao cliente
- **Rastreabilidade** completa

---

## 📚 Lições Aprendidas

### 💡 **Dicas de Atendimento**
1. **Mantenha o PDV aberto** durante o expediente
2. **Qualifique rapidamente** as necessidades
3. **Sugira kits** ao invés de produtos isolados
4. **Aproveite** oportunidades de venda adicional
5. **Faça cadastro mínimo** para não perder tempo

### 🔧 **Otimizações do Sistema**
1. **Configure códigos** de produtos frequentes
2. **Mantenha preços** sempre atualizados
3. **Teste equipamentos** antes do expediente
4. **Treine** uso de códigos de barras
5. **Configure** formas de pagamento

### 📊 **Métricas Importantes**
- **Tempo de atendimento**: 11 minutos (excelente)
- **Ticket médio**: R$ 208,50 (acima da média)
- **Venda adicional**: +R$ 45,00 (27% do total)
- **Satisfação**: Cliente satisfeito

---

## 🔄 Variações do Caso

### 💰 **Variação 1: Pagamento à Vista**
Se João escolhesse pagar em dinheiro:
```
- Valor: R$ 208,50
- Dinheiro recebido: R$ 220,00
- Troco: R$ 11,50
- Sistema calcula troco automaticamente
```

### 💳 **Variação 2: Pagamento Parcelado**
Se João escolhesse cartão de crédito:
```
- Valor: R$ 208,50
- Parcelamento: 2x de R$ 104,25
- Taxa: Conforme configuração
- Títulos gerados automaticamente
```

### 📱 **Variação 3: Pagamento PIX**
Se João escolhesse PIX:
```
- QR Code gerado automaticamente
- Cliente escaneia e paga
- Confirmação em tempo real
- Baixa automática no sistema
```

---

## 🆘 Possíveis Problemas

### ❌ **Problema 1: Produto Sem Estoque**
**Situação**: Terra adubada em falta
**Solução**: 
- Oferecer produto similar
- Verificar prazo de reposição
- Cadastrar interesse do cliente

### ❌ **Problema 2: Erro na NFCe**
**Situação**: NFCe rejeitada pela SEFAZ
**Solução**:
- Verificar dados do cliente
- Tentar reenvio
- Emitir cupom não-fiscal temporário

### ❌ **Problema 3: Cartão Rejeitado**
**Situação**: Transação não aprovada
**Solução**:
- Tentar novamente
- Oferecer outras formas de pagamento
- Verificar limite com o cliente

---

## 📋 Checklist do Atendimento

### ✅ **Antes da Venda**
- [ ] PDV aberto e funcionando
- [ ] Caixa aberto com valor inicial
- [ ] Impressora testada
- [ ] Conexão com internet ok

### ✅ **Durante a Venda**
- [ ] Cliente bem recepcionado
- [ ] Necessidades identificadas
- [ ] Produtos demonstrados
- [ ] Preços confirmados
- [ ] CPF coletado (se necessário)

### ✅ **Finalização**
- [ ] Pagamento processado
- [ ] NFCe emitida
- [ ] Documentos entregues
- [ ] Produtos embalados
- [ ] Cliente orientado

---

## 🎯 Próximos Passos

### 📈 **Para Maria (Lojista)**
1. **Analisar** relatório de vendas do dia
2. **Verificar** produtos com estoque baixo
3. **Acompanhar** retorno do cliente
4. **Planejar** reposição de estoque

### 🛒 **Para João (Cliente)**
1. **Implementar** o jardim com os produtos
2. **Avaliar** qualidade dos produtos
3. **Retornar** se precisar de mais itens
4. **Indicar** a loja para amigos

### 🔄 **Para o Sistema**
1. **Atualizar** relatórios automaticamente
2. **Gerar** alertas de estoque baixo
3. **Processar** conciliação bancária
4. **Backup** dos dados da venda

---

## 📊 Impacto no Negócio

### 📈 **Resultados Imediatos**
- **Receita**: +R$ 208,50
- **Margem**: +R$ 73,00 (aprox.)
- **Cliente**: +1 novo cadastro
- **Estoque**: Atualizado automaticamente

### 🎯 **Resultados de Médio Prazo**
- **Recompra**: Cliente satisfeito pode voltar
- **Indicação**: Potencial para novos clientes
- **Fidelização**: Relacionamento iniciado
- **Dados**: Informações para marketing

### 💼 **Benefícios Operacionais**
- **Eficiência**: Atendimento rápido
- **Controle**: Integração automática
- **Compliance**: Obrigações fiscais atendidas
- **Gestão**: Dados para decisões

---

**💡 Dica Final**: Este caso mostra como um atendimento bem estruturado, aliado ao uso correto do sistema, pode resultar em uma venda eficiente e satisfatória para ambas as partes. A chave é equilibrar rapidez com qualidade no atendimento!

---

**Tags relacionadas**: #caso-uso #venda #balcao #pratico #exemplo #passo-a-passo #pdv #atendimento 