# Requirements Specification

## 1. System Overview
O FoStudy é um aplicativo voltado para estudantes que enfrentam dificuldades na organização dos estudos, foco e baixa constância ao longo do tempo. Muitos usuários apresentam desafios no gerenciamento de tarefas, na realização de revisões eficientes e na manutenção da disciplina, o que impacta diretamente seu desempenho acadêmico.

Com o objetivo de mitigar esses problemas, o FoStudy oferece uma plataforma integrada que reúne funcionalidades como agenda, cronograma de estudos, método Pomodoro, flashcards, métricas de desempenho, sistema de alertas e elementos de gamificação. Essas ferramentas atuam de forma complementar, auxiliando o estudante no planejamento, execução e acompanhamento de seus estudos de maneira estruturada e contínua.

O público-alvo do sistema é composto por estudantes do ensino médio e vestibulandos que estão se preparando para o ENEM, e que buscam aprimorar sua organização, produtividade e desempenho acadêmico.


## 2. Functional Requirements

- FR1: O sistema deve permitir que o usuário crie uma conta com email e senha.

- FR2: O sistema deve permitir ao usuário criar e gerenciar um cronograma semanal de estudos.

- FR3: O sistema deve permitir a execução do método Pomodoro com contagem automática de tempo e intervalos.

- FR4: O sistema deve permitir a criação, edição e revisão de flashcards com registro de desempenho.

- FR5: O sistema deve gerar relatórios com base no tempo de estudo e nos resultados dos flashcards.

- FR6: O sistema deve permitir que o usuário ative ou desative o sistema de alerta.

- FR7: O sistema deve permitir a criação e modificação de uma nova tarefa.

- FR8: O sistema deve permitir o desbloqueio de itens no minigame.

- FR9: O sistema deve permitir a visualização da agenda online e offline.

- FR10: O sistema deve acumular as pontuações obtidas nos quizzes e permitir que sejam usadas para desbloquear itens do mini mundo.

- FR11: O sistema deve identificar e indicar os conteúdos com maior índice de erros nos quizzes, sugerindo revisão prioritária ao usuário. 

- FR12: O sistema deve gerar quizzes automaticamente com base nos flashcards criados pelo usuário. 

- FR13: O sistema deve permitir a personalização do avatar com itens desbloqueados

- FR14: O sistema deve organizar os flashcards por matéria ou tema

- FR15: O sistema deve permitir que o usuário edite seus dados de perfil.

## 3. Non-Functional Requirements

**Performance**:
  
Desempenho (Performance de resposta)

- NFR1: O sistema deve apresentar tempo de resposta inferior a 2 segundos para carregamento de telas principais (agenda, cronograma e flashcards).

**Security**:
  
Autenticação e proteção de acesso
  
- NFR2: O sistema deve exigir autenticação segura (login e senha ou biometria) e implementar proteção contra tentativas de acesso indevidas (ex: bloqueio após múltiplas tentativas inválidas).

**Usability**:

Usabilidade e experiência do usuário

- NFR3: A interface deve ser intuitiva, permitindo realizar tarefas principais em até 5 interações, com navegação simples e feedback visual imediato para o usuário.
