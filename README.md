# Gerador de Prompts SaaS com IA

## Como usar

1. Abra `index.html` com dois cliques.
2. Preencha o conteúdo que seria enviado ao gerador de PRD.
3. Cole o PRD pronto.
4. Selecione funcionalidades, stack, fase atual e a rota de Stripe, se houver.
5. Clique em **Gerar roteiro e prompts**.
6. Copie o prompt da fase atual e só avance depois de cumprir o gate.

## O que a interface garante

- Ordem: planejamento → setup → interface com dados simulados → backend/RLS → colaboração → monetização → auditoria → deploy.
- RLS e isolamento multi-tenant antes de colaboração, cobrança e produção.
- Apenas uma abordagem de Stripe por projeto.
- Segurança e responsividade antes do deploy.
- Prompts personalizados com contexto, tarefa, restrições, entregáveis, testes e critério de passagem.
- Dados e progresso salvos somente no `localStorage` do navegador.

## Privacidade

A versão local não envia o PRD para servidores. O conteúdo permanece no navegador usado para abrir o arquivo.
