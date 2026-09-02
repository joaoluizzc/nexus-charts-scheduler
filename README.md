# Nexus Charts Scheduler

Agendador mínimo para manter a coleta de audiência do Nexus Charts ativa sem
depender de um computador ou navegador aberto.

- O endpoint e os tokens ficam protegidos em GitHub Actions Secrets.
- O workflow público não contém credenciais nem dados privados do painel.
- Cada execução valida apenas o código HTTP e não publica a resposta da API.
