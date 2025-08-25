# Backlog do Sistema de Gestão de Chamados

# Requisitos funcionais

### 1.1 Gerenciamento de Chamados (Alta Prioridade)
*Descrição:*
- Permitir a criação, visualização, atualização e encerramento de chamados de suporte técnico.
- Viabilizar a associação de chamados a funcionários e técnicos responsáveis.
- Habilitar o anexo de arquivos (prints, logs, documentos) para facilitar a resolução de problemas.

*Tarefas:*
- Desenvolver funcionalidades para criação, visualização e fechamento de chamados.
- Implementar um sistema de atribuição automática ou manual de técnicos e funcionários responsáveis.
- Permitir o upload de arquivos (prints, logs, documentos) nos chamados.
- Garantir uma interface de fácil navegação para técnicos e administradores visualizarem chamados pendentes e concluídos.

*Critérios de Aceitação:*
- O sistema deve permitir a criação de chamados com todos os dados necessários.
- Anexos podem ser adicionados sem restrições de formato.
- O fechamento de chamados deve permitir feedback do usuário.

### 1.2 Triagem Inteligente (Alta Prioridade)
*Descrição:*
- Implementar um sistema de inteligência artificial para categorização automática de chamados.
- Sugerir soluções automatizadas com base no histórico de chamados.
- Encaminhar chamados ao técnico mais qualificado para a resolução.

*Tarefas:*
- Desenvolver um modelo de IA para classificar chamados automaticamente.
- Criar um banco de conhecimento para sugerir soluções com base em chamados anteriores.
- Integrar um sistema de roteamento para encaminhar chamados ao técnico mais adequado.

*Critérios de Aceitação:*
- A IA deve classificar chamados corretamente com base em padrões históricos.
- O sistema deve sugerir pelo menos uma solução relevante para chamados comuns.
- Chamados devem ser encaminhados para técnicos com base na sua especialização.

### 1.3 Controle de Acessos e Permissões (Média Prioridade)
*Descrição:*
- Definir diferentes níveis de permissão para usuários (funcionário, técnico e administrador).
- Registrar logs detalhados das ações realizadas no sistema para auditoria e segurança.

*Tarefas:*
- Criar um sistema de gerenciamento de permissões baseado em papéis de usuário.
- Implementar um log detalhado de todas as ações realizadas no sistema.
- Garantir que administradores possam gerenciar acessos de outros usuários.

*Critérios de Aceitação:*
- Apenas usuários com permissões adequadas devem poder realizar ações restritas.
- Todas as ações críticas devem ser registradas no log de auditoria.
- O administrador deve conseguir alterar permissões de outros usuários conforme necessário.

### 1.4 Histórico de Chamados (Média Prioridade)
*Descrição:*
- Armazenar registros completos de todos os chamados gerados no sistema.
- Permitir busca avançada e filtragem por status, categoria e técnico responsável.
- Gerar relatórios analíticos sobre o desempenho da equipe de suporte.

*Tarefas:*
- Desenvolver um banco de dados otimizado para armazenar históricos de chamados.
- Criar funcionalidades de busca e filtragem avançadas para facilitar a consulta de chamados.
- Implementar um sistema de geração de relatórios sobre métricas de atendimento.

*Critérios de Aceitação:*
- O sistema deve armazenar chamados de forma íntegra e acessível para consulta futura.
- Os usuários devem poder filtrar chamados por critérios como status, categoria e técnico.
- Relatórios devem apresentar informações relevantes sobre o desempenho do suporte.
#
## 2. Requisitos Não Funcionais

### 2.1 Segurança (Alta Prioridade)
*Descrição:*
- Implementar autenticação segura para acesso ao sistema.
- Garantir que apenas usuários autorizados possam visualizar e editar chamados.
- Criptografar dados sensíveis armazenados no banco de dados.

*Tarefas:*
- Implementar mecanismos de autenticação, como login e senhas fortes.
- Controlar permissões de acesso para usuários, garantindo visibilidade e edição de chamados conforme o nível de autorização.
- Aplicar criptografia de ponta a ponta nos dados sensíveis no banco de dados, como informações pessoais e relatórios de suporte.

*Critérios de Aceitação:*
- O sistema deve autenticar corretamente usuários, negando acesso não autorizado.
- Apenas usuários com permissões apropriadas devem conseguir visualizar e editar os chamados.
- Dados sensíveis devem ser criptografados de maneira segura.

### 2.2 Tempo de Resposta (Alta Prioridade)
*Descrição:*
- O sistema deve processar chamados e exibir respostas da IA em menos de 2 segundos.
- Evitar travamentos em picos de uso, garantindo alta disponibilidade.

*Tarefas:*
- Otimizar a arquitetura do sistema para processamento rápido de dados.
- Implementar escalabilidade automática para lidar com picos de tráfego.
- Realizar testes de desempenho para garantir que o tempo de resposta seja inferior a 2 segundos.

*Critérios de Aceitação:*
- O tempo de resposta do sistema para processar chamados e exibir respostas da IA deve ser sempre inferior a 2 segundos.
- O sistema deve manter alta disponibilidade, sem travamentos, mesmo durante picos de uso.

### 2.3 Usabilidade (Média Prioridade)
*Descrição:*
- Interface intuitiva e responsiva para facilitar o uso em desktop e mobile.
- Notificações para atualizações de chamados (exemplo: e-mail ou pop-up no sistema).
- Treinamento rápido para novos usuários (onboarding simplificado).

*Tarefas:*
- Desenvolver uma interface gráfica que seja fácil de navegar em diferentes dispositivos.
- Implementar um sistema de notificações para alertar os usuários sobre mudanças nos chamados.
- Criar um processo de onboarding simples e direto para novos usuários, com tutoriais e dicas interativas.

*Critérios de Aceitação:*
- A interface deve ser responsiva, funcionando adequadamente tanto em desktop quanto em dispositivos móveis.
- O sistema deve enviar notificações claras e precisas sobre atualizações de chamados.
- O onboarding para novos usuários deve ser rápido e eficaz, permitindo uma adaptação fácil ao sistema.
