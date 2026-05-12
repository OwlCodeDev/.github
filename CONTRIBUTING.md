# Guia de Contribuição — OWLCode

Obrigado por seu interesse em contribuir com os projetos da OWLCode. Como uma Software Boutique, mantemos um alto padrão de exigência técnica, tipagem estrita e arquitetura limpa.

## Processo de Desenvolvimento

1. **Fork & Branch:** Crie uma branch a partir da `main` ou `develop` utilizando o padrão:
   * `feat/nome-da-feature`
   * `fix/nome-do-bug`
   * `chore/atualizacao-de-libs`
2. **Arquitetura (FSD):** Se estiver atuando em projetos Next.js/React, respeite rigorosamente as regras de [Feature-Sliced Design (FSD)](https://feature-sliced.design/).
3. **Tipagem e Linting:** É expressamente proibido o uso de `any` em projetos TypeScript. Certifique-se de que o código passa por todos os validadores (`ESLint`, `Prettier`).
4. **Commits:** Utilize o padrão [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) (ex: `feat: adiciona widget de projetos`).

## Abertura de Pull Requests (PR)

* Forneça um contexto claro no corpo do PR sobre o que foi resolvido.
* Faça referência à Issue ou ticket interno correspondente.
* Certifique-se de que os pipelines de CI/CD estejam passando ("verde") antes de solicitar revisão de um Arquiteto de Software.
