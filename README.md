# GYM RATS ANALYTICS — versão profissional

Painel web em React + Vite para análise dos dados exportados do Gym Rats.

## O que esta versão traz
- Dashboard executivo com progresso do desafio.
- Ranking em estilo competição.
- Perfil individual de cada participante.
- Indicadores de check-ins, tempo, dias ativos e sequência.
- Evolução semanal e atividade dos últimos 14 dias.
- Calendário dos 49 dias do desafio.
- Curiosidades e recordes do grupo.
- Busca de participantes.
- Importação manual de JSON.
- Layout responsivo para desktop, tablet e celular.
- Tratamento de carregamento e erro do arquivo de dados.

## Executar

```bash
npm install
npm run dev
```

Depois acesse `http://localhost:5173`.

O arquivo `public/challenge-data.json` é carregado automaticamente. Também é possível usar **Importar dados** dentro do sistema para carregar outro JSON compatível.

## Observação
Os indicadores desta primeira versão são analíticos. A validação oficial de todas as regras do desafio, especialmente ciclos 6+1, retroatividade e auditoria de evidências, pode ser adicionada em uma próxima camada de fiscalização.
