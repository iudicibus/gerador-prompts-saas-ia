# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Notion, usando páginas, banco de dados, propriedades e fórmulas nativas; sem API do Notion.

## Users

Usuário principal: estudante e criador de projetos SaaS com IA que segue o módulo “Do Zero ao SaaS” e precisa transformar a ideia, os campos do gerador de PRD e o PRD final em instruções prontas para enviar à IA.

## Product Purpose

Receber os dados usados no gerador de PRD e o PRD pronto, organizar o projeto e produzir o prompt correto para cada etapa do desenvolvimento, mantendo a ordem ensinada no curso.

## Positioning

O gerador não cria prompts genéricos: ele preserva a sequência do curso, separa interface com mocks de backend real e aplica gates obrigatórios antes de colaboração, monetização e produção.

## Operating Context

O usuário preenche os dados do projeto no Notion, seleciona a fase atual e copia o prompt gerado para a IA. O mesmo registro acompanha o progresso do projeto.

## Capabilities and Constraints

- Capturar nome, problema, solução, funcionalidades, personas, stack, referências de design e PRD final.
- Gerar prompts por fase na ordem Planejar → Construir → Testar → Iterar.
- Ordem obrigatória: planejamento; interface com dados simulados; Supabase/migrations/RLS; autenticação e dados reais; colaboração; Stripe; segurança; responsividade; deploy.
- RLS e isolamento multi-tenant bloqueiam colaboração, billing e deploy.
- Segurança e responsividade bloqueiam produção.
- Stripe 4.1 e 4.2 são alternativas, nunca cumulativas.
- Não inventar versões, comandos ou ferramentas não confirmados nas aulas 1.3, 1.4 e 2.1.
- Não expor credenciais.

## Evidence on Hand

- `C:\Users\reiud\Downloads\Guia-Desenvolvimento-SaaS-com-IA.md`
- `C:\Users\reiud\Downloads\Matriz-Checklist-Curso-Do-Zero-ao-SaaS.md`
- Página Notion existente com o guia completo.
- 21 materiais do módulo e duas imagens do gerador de PRD já analisados.

## Product Principles

1. Sempre indicar a próxima etapa correta.
2. Gerar prompts específicos ao projeto, sem ampliar o PRD.
3. Exigir evidência de teste antes de avançar.
4. Tratar segurança e isolamento como gates, não como acabamento opcional.
5. Manter o processo reutilizável para novos projetos.
