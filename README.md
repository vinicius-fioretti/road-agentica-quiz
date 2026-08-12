# Road Agêntica Quiz

Aplicação estática do quiz **Road Agêntica: como preparar sua rotina para IA**.

## Local

```bash
cd /root/.hermes/ROAD/projetos/road-agentica-quiz-v1/app
python3 -m http.server 4173
```

Abrir: http://localhost:4173

## Deploy Vercel

Requer autenticação Vercel no ambiente.

```bash
cd /root/.hermes/ROAD/projetos/road-agentica-quiz-v1/app
npx vercel --prod
```

## Coleta de respostas

V1 atual exporta JSON local. Para produção, conectar um endpoint de coleta:

1. Google Apps Script Web App salvando no Google Sheets; ou
2. Vercel Function + KV/Supabase; ou
3. Google Forms, caso a experiência visual não seja prioridade.
