# Painel Gemba AM

Painel para acompanhar quem realiza as auditorias de Gemba (Manutenção Autônoma), com filtros em cascata (Período → Oficina → UTE → Auditor), ranking dos auditores e histórico diário.

## Como funciona

Site estático em um único arquivo `index.html` (sem backend). Os dados importados (novas auditorias do Forms e a base de colaboradores) ficam salvos no `localStorage` do navegador de quem estiver usando — ou seja, cada pessoa que abrir o link vê os dados que ela mesma importou naquele navegador, sem compartilhamento automático entre usuários.

## Deploy no Vercel

1. Acesse [vercel.com/new](https://vercel.com/new) e importe este repositório.
2. Não é necessário configurar build command nem framework — é um site estático.
3. Clique em "Deploy".

Qualquer atualização enviada para a branch `main` gera um novo deploy automaticamente.
