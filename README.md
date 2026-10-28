# Keep-alive

Workflow público que a cada 5 minutos faz um `GET` em
`https://metodo-oab-api.onrender.com/api/health` para evitar que o serviço
gratuito do Render entre em suspensão por inatividade.

- Não contém segredos.
- Painel de status: https://status-metodo-oab.web.app
- Para acordar os demais serviços sob demanda, abra o painel.
