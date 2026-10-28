# Requisitos — Estrutura do site

## Escopo

Esta fase define e constrói a estrutura e a navegação do site institucional da Etec Sales Gomes, conforme a Fase 02 do roadmap.

Áreas incluídas:

- **Início:** ponto de entrada para estudantes e famílias, com estrutura pronta para divulgar notícias em fase posterior.
- **A escola:** área de apresentação institucional.
- **Cursos:** área de navegação preparada para o catálogo técnico da Fase 03, sem antecipar o conteúdo detalhado do catálogo.
- **Cabeçalho e rodapé:** navegação principal no cabeçalho e links institucionais no rodapé.

Ficam fora do escopo desta fase: cadastro/autenticação da equipe, publicação de notícias, catálogo completo, matrizes curriculares e publicação do site.

## Contexto

A missão do projeto é informar e orientar estudantes e famílias sobre a escola e seus cursos técnicos. O site deverá oferecer um catálogo claro, matrizes curriculares e notícias na página inicial atualizadas por usuários autenticados. A experiência deve ser atraente, responsiva e compatível com navegadores modernos.

A stack de referência é React com TypeScript no frontend, Node.js com TypeScript no backend e SQLite como banco de dados inicial. Frameworks e ferramentas complementares permanecem em aberto, preservando essa base.

Referências: `specs/mission.md`, `specs/tech-stack.md` e Fase 02 de `specs/roadmap.md`.

## Decisões

- Áreas escolhidas para esta fase: Início, A escola e Cursos.
- Navegação escolhida: menu principal no cabeçalho e links institucionais no rodapé.
- A área Cursos deve acomodar o catálogo futuro, sem duplicar o trabalho da Fase 03.
- Não foram fornecidos critérios adicionais pelo solicitante. Como critérios propostos a partir da missão, a estrutura deve ser clara, responsiva e utilizável em navegadores modernos; esses critérios devem ser confirmados durante a implementação.
- Nenhuma identidade visual ou conteúdo institucional específico foi fornecido nesta especificação; utilizar apenas materiais aprovados que estejam disponíveis.