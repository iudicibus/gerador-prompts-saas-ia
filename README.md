# Gerador de Prompts SaaS com IA

## Como usar

1. Abra o gerador incorporado no Notion ou `index.html` localmente.
2. Preencha os mesmos campos de contexto do início do guia do professor.
3. Cole o PRD final completo.
4. Selecione funcionalidades, stack, preferências da Iudex Builder e uma única rota de Stripe.
5. Opcionalmente, adicione fotos nas referências de design e no Design Context.
6. Clique em **Gerar prompts adaptados**.
7. Em cada etapa, compare o prompt original com a caixa adaptada logo abaixo e copie a versão adaptada.

## O que a interface garante

- Os 64 prompts de projeto do guia são preservados integralmente e na ordem original.
- Cada prompt original possui uma versão adaptada diretamente abaixo.
- Ordem: planejamento → setup → interface com dados simulados → backend/RLS → colaboração → monetização → auditoria → deploy.
- RLS e isolamento multi-tenant antes de colaboração, cobrança e produção.
- Apenas uma abordagem de Stripe por projeto.
- Segurança e responsividade antes do deploy.
- Prompts personalizados com contexto, tarefa, restrições, entregáveis, testes e critério de passagem.
- Textos salvos no `localStorage` e fotos salvas no `IndexedDB` do navegador.
- Fotos são exibidas como prévia e citadas pelo nome no prompt; devem ser anexadas manualmente ao Claude Code.

## Privacidade

A aplicação não envia PRD nem fotos para um backend. O conteúdo permanece no navegador usado para abrir o gerador.
