# 📖 Manual de Usuário - SmartCall

Bem-vindo ao **SmartCall**, a plataforma inteligente de gerenciamento de chamados (helpdesk) da InfinityWare.

Este manual foi criado para guiar os usuários em suas interações diárias com o sistema. O SmartCall utiliza Inteligência Artificial para classificar e priorizar seus chamados automaticamente, garantindo que os problemas mais urgentes sejam vistos primeiro.

## 1. Acesso ao Sistema

Para acessar o SmartCall, utilize seu navegador web preferido e vá para o endereço fornecido pela sua organização (ex: `http://smartcall.suaempresa.com`).

### 1.1. Primeiro Acesso e Registro (para novos Usuários)
1.  Na tela de login, clique em **"Registrar"** ou "Não tenho uma conta".
2.  Preencha seu nome completo, e-mail corporativo e crie uma senha segura.
3.  Você será levado para a tela de login.

### 1.2. Login
1.  Insira o e-mail e a senha que você cadastrou.
2.  Clique em **"Entrar"**.
3.  Se esquecer sua senha, utilize o link **"Esqueci minha senha"** na tela de login para iniciar o processo de recuperação.

---

## 2. Funcionalidades por Perfil de Usuário

O sistema possui diferentes funcionalidades dependendo do seu nível de acesso.

### 2.1. Perfil: Usuário (Cliente)

O Usuário é o perfil padrão para quem precisa solicitar ajuda e abrir chamados.

#### Como Abrir um Novo Chamado
1.  Após fazer login, clique no botão **"Novo Chamado"** ou "Abrir Ticket" no seu painel.
2.  Preencha o formulário:
    * **Título:** Um resumo curto e objetivo do seu problema (ex: "Impressora do 2º andar não funciona" ou "Erro ao acessar sistema de vendas").
    * **Descrição:** **Esta é a parte mais importante.** Seja o mais detalhado possível.
        * O que aconteceu?
        * Qual mensagem de erro apareceu? (Copie e cole, se possível)
        * Quais passos você tentou antes de dar o erro?
        * A nossa IA usará esta descrição para entender a urgência e o tipo do seu problema.
    * **Anexos:** Se possível, anexe capturas de tela (screenshots) do erro.
3.  Clique em **"Enviar"**. Seu chamado será criado e enviado para triagem da IA.

#### Como Acompanhar Meus Chamados
1.  No menu principal, clique em **"Meus Chamados"**.
2.  Você verá uma lista de todos os tickets que você abriu, com seus respectivos status:
    * **Aberto (ou Triagem):** Seu chamado foi recebido e está sendo analisado pela IA e pela equipe.
    * **Em Atendimento:** Um técnico já assumiu seu chamado e está trabalhando nele.
    * **Pendente:** O técnico está aguardando uma resposta sua ou de terceiros.
    * **Resolvido:** O técnico marcou o problema como solucionado.

#### Como Interagir com um Chamado
1.  Em "Meus Chamados", clique no título do chamado que deseja ver.
2.  Você pode ver o histórico de conversas com o técnico.
3.  Para adicionar uma nova informação ou responder a uma pergunta do técnico, use a caixa **"Adicionar Comentário"** e clique em "Enviar".

---

### 2.2. Perfil: Técnico

O Técnico é o profissional de suporte responsável por atender e resolver os chamados abertos pelos usuários.

#### Dashboard de Atendimento
1.  Ao fazer login, você verá o "Dashboard de Chamados" ou "Fila de Atendimento".
2.  Os chamados já estarão priorizados (ex: Urgente, Alta, Média, Baixa) e categorizados (ex: Infraestrutura, Software, Hardware) pela IA do SmartCall. Os chamados mais urgentes aparecerão no topo.

#### Como Atender um Chamado
1.  Na fila, clique em um chamado com status "Aberto" para visualizá-lo.
2.  Leia a análise da IA (prioridade, categoria) e a descrição do usuário.
3.  Para começar a trabalhar nele, clique em **"Assumir Chamado"** (ou mude o status para **"Em Atendimento"**).
4.  O chamado agora está vinculado ao seu perfil e saiu da fila principal.

#### Como Interagir e Registrar Ações
* **Resposta ao Usuário:** Use a caixa "Adicionar Comentário" ou "Resposta Pública" para se comunicar com o usuário (ex: pedir mais informações).
* **Nota Interna:** Use a aba ou caixa **"Nota Interna"** para adicionar observações técnicas que **apenas outros técnicos e gerentes** poderão ver (ex: "Logs do servidor X verificados, erro na porta 8080").

#### Como Resolver um Chamado
1.  Após solucionar o problema, adicione um comentário final explicando a solução para o usuário.
2.  Mude o status do chamado para **"Resolvido"**.
3.  (Opcional) Você pode ser solicitado a confirmar a categoria que a IA sugeriu, ajudando a treinar o modelo.

---

### 2.3. Perfil: Gerente

O Gerente tem uma visão completa do sistema, focado em métricas (KPIs) e na gestão da equipe de suporte.

#### Visualização de Dashboards e Métricas
1.  Ao fazer login, o Gerente tem acesso a um dashboard principal com métricas de performance da equipe.
2.  Você pode visualizar relatórios e gráficos sobre:
    * Tempo Médio de Resposta (TMR).
    * Tempo Médio de Resolução (TTR).
    * Número de chamados abertos vs. fechados por período.
    * Performance individual por técnico (quantos chamados cada um resolveu).
    * Categorias com maior incidência de problemas (para identificar causas-raiz).

#### Gestão de Chamados
* O Gerente pode visualizar **todos** os chamados no sistema, incluindo os de todos os técnicos.
* É possível **reatribuir (redirecionar)** um chamado de um técnico para outro, caso necessário (ex: em caso de ausência ou escalonamento para um especialista).

#### Gestão de Equipe (Administração)
* O Gerente pode ter acesso a uma área de "Administração" para:
    * Convidar novos usuários (Técnicos ou Gerentes).
    * Alterar perfis de usuários (ex: promover um Usuário para Técnico).
    * Desativar contas de usuários que saíram da empresa.

## 3. Solução de Problemas Comuns

* **Não consigo fazer login:** Tente redefinir sua senha usando o link "Esqueci minha senha". Se o problema persistir, entre em contato com o administrador do sistema na sua empresa.
* **Meu chamado urgente não foi respondido:** Nosso sistema de IA faz uma pré-classificação da urgência com base no que foi escrito na *Descrição*. Se o problema for mais grave do que o descrito, adicione um novo comentário com mais detalhes.
