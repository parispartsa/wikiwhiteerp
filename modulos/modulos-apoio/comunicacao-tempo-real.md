# Comunicação em Tempo Real

🏠 [Home](../../../index.md) > 📋 [Módulos](../../index.md) > 🔧 [Módulos de Apoio](index.md) > **Comunicação em Tempo Real**

#socket #websocket #tempo-real #notificacoes #chat #sincronizacao

## 🎯 O que é a Comunicação em Tempo Real

O **Sistema de Comunicação em Tempo Real** utiliza tecnologia WebSocket para fornecer notificações instantâneas, chat interno, sincronização multi-usuário e atualizações automáticas de tela. Permite que múltiplos usuários trabalhem simultaneamente no sistema com total sincronização.

### 🚀 Principais Benefícios
- **Instantâneo**: Comunicação em tempo real (< 200ms)
- **Multi-usuário**: Sincronização entre todos os usuários
- **Automático**: Notificações sem necessidade de refresh
- **Seguro**: Autenticação JWT e canais privados

## 🔧 Como funciona o Sistema

### **Arquitetura WebSocket**

#### **1. Conexão e Autenticação**
- **Protocolo**: WebSocket sobre HTTPS (WSS)
- **Autenticação**: Token JWT com dados do usuário
- **Sessão**: Vinculada à sessão ativa do usuário
- **Multi-tenant**: Isolamento por empresa/tenant

#### **2. Canais de Comunicação**
- **Global**: Notificações para todos os usuários
- **Por Departamento**: Mensagens específicas por setor
- **Privado**: Comunicação direta entre usuários
- **Sistema**: Alertas automáticos do ERP

#### **3. Tipos de Eventos**
- **Notificações**: Alertas e informações importantes
- **Chat**: Mensagens entre usuários
- **Sincronização**: Atualizações de dados em tempo real
- **Status**: Presença online/offline dos usuários

## 🔧 Configuração do Sistema

### **Passo 1: Ativação do Socket**

#### **Configurações Básicas**
1. Acesse **Configurações** > **Sistema** > **Comunicação**
2. Ative **"Habilitar Socket"**
3. Configure **URL do Servidor WebSocket**
4. Defina **Porta de Comunicação** (padrão: 3000)

#### **Configuração do Servidor**
```javascript
// Exemplo de configuração
const socketConfig = {
    host: 'wss://seu-dominio.com',
    port: 3000,
    secure: true,
    auth: {
        type: 'jwt',
        secret: 'sua_chave_secreta'
    }
}
```

### **Passo 2: Configuração por Usuário**

#### **Permissões de Acesso**
- **Socket Habilitado**: Usuário pode usar comunicação em tempo real
- **Chat Interno**: Permissão para enviar mensagens
- **Notificações**: Receber alertas do sistema
- **Presença**: Mostrar status online/offline

#### **Configurações Pessoais**
```
✅ Receber notificações de vendas
✅ Alertas de títulos vencidos
✅ Mensagens de chat
✅ Atualizações de estoque
❌ Notificações de sistema (apenas admin)
```

### **Passo 3: Configuração de Canais**

#### **Canais Padrão**
- **#geral**: Canal público para toda empresa
- **#vendas**: Notificações do módulo de vendas
- **#financeiro**: Alertas financeiros
- **#estoque**: Atualizações de estoque
- **#sistema**: Mensagens automáticas

## 📡 Funcionalidades Disponíveis

### **🔔 Notificações em Tempo Real**

#### **Tipos de Notificação**
```javascript
// Exemplos de notificações automáticas
{
    type: 'success',
    title: 'Venda Realizada',
    message: 'Nova venda de R$ 1.250,00 para Cliente ABC',
    timestamp: '2024-03-15 14:30:25',
    user: 'João Vendedor',
    module: 'vendas'
}

{
    type: 'warning',
    title: 'Título Vencido',
    message: '5 títulos venceram hoje - Total: R$ 8.750,00',
    timestamp: '2024-03-15 09:00:00',
    module: 'financeiro',
    action: '/financeiro/titulos-vencidos'
}
```

#### **Notificações por Módulo**
- **Vendas**: Nova venda, cancelamento, alteração
- **Financeiro**: Títulos vencidos, pagamentos recebidos
- **Estoque**: Produtos em falta, movimentações
- **CRM**: Novos leads, conversões
- **Sistema**: Backup concluído, erros críticos

### **💬 Chat Interno**

#### **Mensagens Instantâneas**
- **Chat Direto**: Conversa entre dois usuários
- **Grupos**: Canais por departamento
- **Broadcast**: Mensagens para todos
- **Histórico**: Armazenamento de conversas

#### **Interface do Chat**
```
┌─────────────────────────────────────────┐
│ 💬 Chat Interno - #vendas               │
├─────────────────────────────────────────┤
│ João (14:25): Nova venda confirmada!    │
│ Maria (14:26): Qual cliente?            │
│ João (14:27): Empresa XYZ - R$ 5.000    │
│ Sistema (14:30): 🎉 Meta mensal: 85%    │
├─────────────────────────────────────────┤
│ Digite sua mensagem...            [📤] │
└─────────────────────────────────────────┘
```

### **🔄 Sincronização Multi-usuário**

#### **Atualizações Automáticas**
- **Listas**: Atualização automática de grids
- **Formulários**: Bloqueio quando outro usuário edita
- **Dashboards**: Métricas em tempo real
- **Status**: Indicadores visuais de atividade

#### **Controle de Concorrência**
```
⚠️ ATENÇÃO: Registro sendo editado

👤 Maria Silva está editando este cliente
🕐 Iniciado às 14:25:30
🔒 Bloqueado para edição

[🔄 Atualizar] [👁️ Visualizar] [✉️ Mensagem]
```

### **👥 Presença de Usuários**

#### **Status Online/Offline**
- **🟢 Online**: Usuário ativo no sistema
- **🟡 Ausente**: Inativo por mais de 5 minutos
- **🔴 Offline**: Desconectado do sistema
- **🔵 Ocupado**: Em chamada ou reunião

#### **Lista de Presença**
```
👥 USUÁRIOS ONLINE (8)

🟢 João Silva - Vendas (ativo)
🟢 Maria Santos - Financeiro (ativo)
🟡 Pedro Costa - Estoque (ausente 3min)
🟢 Ana Lima - Administração (ativo)
🔴 Carlos Oliveira - TI (offline)
```

## ⚙️ Configurações Avançadas

### **🔧 Configuração do Servidor Socket**

#### **Parâmetros de Conexão**
```javascript
const socketServer = {
    // Configurações básicas
    host: process.env.SOCKET_HOST || 'localhost',
    port: process.env.SOCKET_PORT || 3000,
    
    // Segurança
    cors: {
        origin: "https://seu-dominio.com",
        credentials: true
    },
    
    // Performance
    pingTimeout: 60000,
    pingInterval: 25000,
    maxConnections: 1000,
    
    // Autenticação
    auth: {
        timeout: 5000,
        required: true
    }
}
```

#### **Configuração de Canais**
```javascript
// Estrutura de canais
const channels = {
    'global': {
        name: 'Global',
        description: 'Canal público geral',
        permissions: ['all']
    },
    'sales': {
        name: 'Vendas',
        description: 'Notificações de vendas',
        permissions: ['vendas', 'admin']
    },
    'finance': {
        name: 'Financeiro',
        description: 'Alertas financeiros',
        permissions: ['financeiro', 'admin']
    }
}
```

### **🛡️ Segurança e Autenticação**

#### **Token JWT**
```javascript
// Estrutura do token
{
    userId: 123,
    username: 'joao.silva',
    tenantHash: 'abc123',
    permissions: ['vendas', 'chat'],
    isPrincipal: false,
    exp: 1710504000 // Expiração
}
```

#### **Validação de Acesso**
- **Autenticação**: Token válido obrigatório
- **Autorização**: Permissões por canal
- **Tenant**: Isolamento por empresa
- **Rate Limiting**: Limite de mensagens por minuto

## 📊 Monitoramento e Métricas

### **Dashboard de Comunicação**

#### **Estatísticas em Tempo Real**
```
📊 COMUNICAÇÃO EM TEMPO REAL

Conexões Ativas: 45 usuários
Mensagens/hora: 127
Notificações/hora: 89
Uptime: 99.8% (30 dias)

Canais Mais Ativos:
1. #vendas - 45 mensagens/hora
2. #geral - 32 mensagens/hora  
3. #financeiro - 18 mensagens/hora

Performance:
Latência média: 145ms
Tempo resposta: 98ms
Taxa de entrega: 99.9%
```

### **Logs de Auditoria**
- **Conexões**: Log de todas as conexões/desconexões
- **Mensagens**: Histórico completo de conversas
- **Eventos**: Registro de notificações enviadas
- **Erros**: Falhas de conexão e problemas

## 🔄 Integração com Módulos

### **Eventos Automáticos**

#### **Módulo de Vendas**
```javascript
// Exemplo de evento automático
onNewSale(sale) {
    socket.emit('notification', {
        channel: 'sales',
        type: 'success',
        title: 'Nova Venda Realizada',
        message: `Venda de ${sale.total} para ${sale.customer}`,
        data: sale,
        timestamp: new Date()
    });
}
```

#### **Módulo Financeiro**
```javascript
// Alerta de títulos vencidos
onOverdueTitles(titles) {
    socket.emit('notification', {
        channel: 'finance',
        type: 'warning',
        title: 'Títulos Vencidos',
        message: `${titles.length} títulos venceram hoje`,
        action: '/financeiro/vencidos',
        urgent: true
    });
}
```

### **Sincronização de Dados**

#### **Atualização de Listas**
```javascript
// Atualização automática de grids
onDataChange(module, action, data) {
    socket.emit('data-sync', {
        module: module,
        action: action, // 'create', 'update', 'delete'
        data: data,
        timestamp: new Date()
    });
}
```

## 💡 Boas Práticas

### ✅ **Recomendações**

#### **Performance**
- **Limite de Conexões**: Configure limite baseado na infraestrutura
- **Compressão**: Use compressão para mensagens grandes
- **Heartbeat**: Configure ping/pong para detectar desconexões
- **Cache**: Implemente cache para mensagens frequentes

#### **Segurança**
- **HTTPS Only**: Sempre use WSS (WebSocket Secure)
- **Validação**: Valide todas as mensagens no servidor
- **Rate Limiting**: Limite mensagens por usuário
- **Logs**: Mantenha logs de auditoria completos

#### **Usabilidade**
- **Notificações Discretas**: Evite spam de notificações
- **Categorização**: Organize notificações por importância
- **Histórico**: Mantenha histórico acessível
- **Offline**: Sincronize mensagens quando usuário volta online

### ⚠️ **Cuidados Importantes**

#### **Recursos do Servidor**
- **Memória**: Monitore uso de RAM com muitas conexões
- **CPU**: WebSocket pode ser intensivo em processamento
- **Rede**: Monitore largura de banda utilizada
- **Conexões**: Limite baseado na capacidade do servidor

#### **Experiência do Usuário**
- **Não Spam**: Evite excesso de notificações
- **Relevância**: Filtre notificações por relevância
- **Performance**: Não impacte performance da aplicação
- **Fallback**: Tenha alternativa se Socket falhar

## 🔄 Próximos passos

Após configurar a comunicação em tempo real:
1. **Teste as conexões** com múltiplos usuários
2. **Configure filtros** de notificação adequados
3. **Treine a equipe** no uso do chat interno
4. **Monitore performance** e ajuste conforme necessário
5. **Configure alertas** para falhas de conexão

## 🔗 Veja também

- [Sistema de Email](sistema-email.md)
- [Notificações Push](notificacoes-push.md)
- [Monitoramento e Alertas](monitoramento-alertas.md)
- [Configurações de Segurança](configuracoes-seguranca.md)

---

> **⚡ Performance**: A comunicação em tempo real melhora significativamente a produtividade da equipe e a experiência do usuário.

> **🔒 Segurança**: Configure adequadamente as permissões para evitar vazamento de informações entre usuários não autorizados. 