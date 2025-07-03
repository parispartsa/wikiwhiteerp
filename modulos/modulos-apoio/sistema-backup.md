# Sistema de Backup Automático

🏠 [Home](../../../index.md) > 📋 [Módulos](../../index.md) > 🔧 [Módulos de Apoio](index.md) > **Sistema de Backup**

#backup #automatico #seguranca #criptografia #nuvem #restore

## 🎯 O que é o Sistema de Backup

O **Sistema de Backup Automático** é um módulo crítico de infraestrutura que protege todos os dados do ERP através de backups automatizados, criptografados e armazenados em múltiplos locais. Funciona 24/7 sem intervenção humana, garantindo que nenhum dado seja perdido.

### 🚀 Principais Benefícios
- **Automação Total**: Backup sem intervenção humana
- **Criptografia AES-256**: Máxima segurança dos dados
- **Múltiplos Destinos**: Armazenamento redundante
- **Alertas Inteligentes**: Notificação imediata de falhas

## 🔧 Como funciona o Sistema

### **Arquitetura do Backup**

#### **1. Coleta de Dados**
- **Bancos de Dados**: Dump completo de todos os schemas
- **Arquivos de Sistema**: Configurações críticas (/etc/apache2, /etc/mysql)
- **Dados de Aplicação**: Uploads, logs, configurações
- **Exclusão Inteligente**: Remove dados desnecessários automaticamente

#### **2. Processamento**
- **Compressão**: Reduz tamanho em até 80%
- **Criptografia**: AES-256 com senha única
- **Validação**: Verifica integridade dos arquivos
- **Logs Detalhados**: Registra cada etapa do processo

#### **3. Armazenamento**
- **Local Temporário**: Processamento inicial no servidor
- **Upload Seguro**: Transferência criptografada para nuvem
- **Múltiplos Destinos**: AWS, Google Drive, Dropbox, FTP
- **Retenção**: Mantém últimas 2 versões automaticamente

## 🔧 Configuração do Sistema

### **Passo 1: Configurações Básicas**

#### **Acesso às Configurações**
1. Acesse **Configurações** > **Sistema** > **Backup**
2. Clique em **"Configurar Backup Automático"**
3. Ative a opção **"Habilitar Backup"**

#### **Configurações de Banco de Dados**
```
Host do Banco: localhost
Porta: 3306
Usuário: backup_user
Senha: [senha_segura]
Bancos Excluídos: phpmyadmin, mysql, information_schema
```

### **Passo 2: Configuração de Armazenamento**

#### **Configuração SSH (Servidor)**
```
Host SSH: seu-servidor.com
Porta: 22
Usuário: backup_user
Senha: [senha_ssh]
```

#### **Configuração de Nuvem (Rclone)**
```
Driver: googledrive / aws / dropbox
Pasta: backup/
Usuário: [credenciais_api]
Token: [token_acesso]
```

### **Passo 3: Configuração de Notificações**

#### **Email de Alertas**
```
SMTP: smtp.gmail.com
Porta: 587
Email: backup@suaempresa.com
Destinatários: admin@suaempresa.com, ti@suaempresa.com
```

## ⚙️ Tipos de Backup

### **🔄 Backup Completo Diário**

#### **Horário de Execução**
- **Agendamento**: Diariamente às 02:00
- **Duração**: 30-60 minutos (dependendo do tamanho)
- **Frequência**: Configurável (diário, semanal, personalizado)

#### **Conteúdo do Backup**
```
📁 backup_2024_03_15_02_00_00/
├── 📁 sql/
│   ├── 🔒 empresa1.sql.tar.gz.enc
│   ├── 🔒 empresa2.sql.tar.gz.enc
│   └── 🔒 principal.sql.tar.gz.enc
├── 📁 config/
│   ├── 🔒 _etc_apache2_.tar.gz.enc
│   ├── 🔒 _etc_mysql_.tar.gz.enc
│   └── 🔒 _var_www_data_.tar.gz.enc
└── 📄 backup_log.txt
```

### **📋 Backup Sob Demanda**

#### **Backup Individual por Cliente**
- **Acionamento**: Manual ou por API
- **Escopo**: Dados específicos de um tenant
- **Formato**: SQL comprimido e criptografado
- **Entrega**: Email com arquivo anexo

#### **Como Solicitar**
1. Acesse **Sistema** > **Backup** > **Backup Individual**
2. Selecione o **cliente/tenant**
3. Informe **email de destino**
4. Clique em **"Gerar Backup"**
5. Arquivo será enviado por email em até 15 minutos

## 🔒 Segurança e Criptografia

### **Criptografia AES-256**

#### **Processo de Criptografia**
```bash
# Exemplo do processo (simplificado)
tar -czf dados.tar.gz dados/
openssl enc -aes-256-cbc -salt -in dados.tar.gz -out dados.tar.gz.enc -k "senha_super_segura"
```

#### **Características de Segurança**
- **Algoritmo**: AES-256-CBC (padrão militar)
- **Senha**: Única por instalação, não armazenada em texto claro
- **Salt**: Adiciona aleatoriedade extra
- **Verificação**: Hash MD5 para validar integridade

### **Controle de Acesso**
- **SSH**: Chaves públicas/privadas
- **APIs**: Tokens com escopo limitado
- **Logs**: Auditoria completa de acessos
- **Exclusão**: Dados antigos removidos automaticamente

## 📊 Monitoramento e Alertas

### **Alertas de Sucesso**
```
✅ BACKUP COMPLETADO COM SUCESSO!

Data início: 15/03/2024 02:00:15
Data fim: 15/03/2024 02:47:32
Duração: 47 minutos e 17 segundos

Bancos processados: 15
Tamanho total: 2.3 GB
Tamanho comprimido: 487 MB
Local: backup/2024_03_15/
```

### **Alertas de Falha**
```
❌ FALHA NO BACKUP!

Data: 15/03/2024 02:15:23
Erro: Falha na conexão SSH
Detalhes: Connection timeout after 30 seconds

Ação necessária:
1. Verificar conectividade de rede
2. Validar credenciais SSH
3. Executar backup manual se necessário
```

### **Dashboard de Monitoramento**
- **Status Atual**: Verde/Amarelo/Vermelho
- **Último Backup**: Data e hora da última execução
- **Próximo Backup**: Agendamento seguinte
- **Tamanho Total**: Espaço ocupado pelos backups
- **Taxa de Sucesso**: Percentual de backups bem-sucedidos

## 🔄 Restore e Recuperação

### **Restore Automático**

#### **Processo de Restore**
1. **Localizar Backup**: Selecionar data específica
2. **Download**: Baixar arquivos criptografados
3. **Descriptografia**: Usar senha do sistema
4. **Descompressão**: Extrair dados originais
5. **Restore DB**: Executar SQL no banco de dados

#### **Tempo de Recuperação**
- **Backup Local**: 15-30 minutos
- **Backup Nuvem**: 45-90 minutos (dependendo da conexão)
- **Restore Parcial**: 5-15 minutos (apenas dados específicos)

### **Restore Manual**

#### **Procedimento de Emergência**
```bash
# 1. Download do backup
rclone copy backup:backup/2024_03_15/ ./restore/

# 2. Descriptografia
openssl enc -d -aes-256-cbc -in dados.sql.tar.gz.enc -out dados.sql.tar.gz -k "senha"

# 3. Descompressão
tar -xzf dados.sql.tar.gz

# 4. Restore do banco
mysql -u root -p empresa1 < empresa1.sql
```

## 🤖 Jobs Automáticos

### **Tarefas Agendadas**

#### **Backup Principal (Diário)**
- **Horário**: 02:00 (configurável)
- **Comando**: `/backup/run-backup-complete`
- **Duração**: 30-60 minutos
- **Logs**: `/var/log/backup-complete.log`

#### **Limpeza de Arquivos (Semanal)**
- **Horário**: Domingo às 04:00
- **Função**: Remove backups com mais de 30 dias
- **Critério**: Mantém últimas 2 versões sempre
- **Logs**: `/var/log/backup-cleanup.log`

#### **Verificação de Integridade (Semanal)**
- **Horário**: Quarta às 03:00
- **Função**: Valida backups existentes
- **Teste**: Download e verificação de hash
- **Alerta**: Email se encontrar problemas

### **Monitoramento de Sistema**

#### **Verificação de Disponibilidade**
```php
// Exemplo de verificação automática
if (!$database->isConnected()) {
    $alert = "Aplicação sem conexão com banco de dados";
    $emailService->sendAlert($alert);
}

if (!$this->isApacheRunning()) {
    $alert = "Aplicação não está rodando APACHE";
    $emailService->sendAlert($alert);
}
```

## 📈 Métricas e Relatórios

### **Estatísticas de Backup**

#### **Relatório Mensal**
```
📊 RELATÓRIO DE BACKUP - MARÇO 2024

Execuções: 31/31 (100% sucesso)
Tamanho médio: 2.1 GB
Tempo médio: 42 minutos
Economia de espaço: 78% (compressão)

Destinos:
✅ Google Drive: 31/31
✅ AWS S3: 31/31
✅ Backup Local: 31/31

Alertas: 0 falhas críticas
```

### **Análise de Performance**
- **Crescimento dos Dados**: Tendência mensal
- **Tempo de Backup**: Evolução da duração
- **Taxa de Compressão**: Eficiência do processo
- **Uso de Banda**: Impacto na rede

## 💡 Boas Práticas

### ✅ **Recomendações**

#### **Configuração**
- **Teste Inicial**: Sempre teste o restore antes de confiar
- **Múltiplos Destinos**: Configure pelo menos 2 locais diferentes
- **Monitoramento**: Configure alertas para toda a equipe de TI
- **Documentação**: Mantenha procedimentos atualizados

#### **Segurança**
- **Senhas Fortes**: Use senhas complexas para criptografia
- **Acesso Restrito**: Limite quem pode acessar configurações
- **Logs Auditoria**: Monitore todos os acessos ao sistema
- **Teste Regular**: Valide backups mensalmente

#### **Performance**
- **Horário Off-Peak**: Execute durante menor uso do sistema
- **Recursos**: Monitore CPU e memória durante backup
- **Rede**: Use conexão dedicada se possível
- **Exclusões**: Configure exclusões para otimizar tempo

### ⚠️ **Cuidados Importantes**

#### **Antes de Configurar**
- **Espaço em Disco**: Garanta espaço suficiente (3x o tamanho dos dados)
- **Credenciais**: Valide todas as credenciais de acesso
- **Conectividade**: Teste conexão com destinos de backup
- **Permissões**: Configure permissões adequadas nos diretórios

#### **Durante a Operação**
- **Não Interromper**: Nunca cancele backup em execução
- **Monitorar Logs**: Acompanhe logs em tempo real
- **Alertas**: Responda rapidamente a alertas de falha
- **Espaço**: Monitore espaço disponível regularmente

## 🔄 Próximos passos

Após configurar o backup:
1. **Execute um teste** completo de backup e restore
2. **Configure alertas** para toda equipe responsável
3. **Documente procedimentos** de emergência
4. **Agende testes** regulares de integridade
5. **Monitore performance** e otimize conforme necessário

## 🔗 Veja também

- [Monitoramento e Alertas](monitoramento-alertas.md)
- [Configurações de Segurança](configuracoes-seguranca.md)
- [Logs de Auditoria](logs-auditoria.md)
- [Fluxo: Backup Automático](../../fluxos/fluxo-backup-automatico.md)

---

> **🔒 Crítico**: O backup é a última linha de defesa contra perda de dados. Configure adequadamente e teste regularmente para garantir que funciona quando necessário.

> **⚠️ Atenção**: Mantenha sempre pelo menos 2 cópias dos dados em locais diferentes. A regra 3-2-1 (3 cópias, 2 mídias diferentes, 1 offsite) é altamente recomendada. 