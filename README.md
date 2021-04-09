# CSH42 - Avaliação de padrões web

Site escolhido: [ShortStay](https://shortstaycuritiba.com.br/) (acesso em 08/04/2021)

Este projeto faz parte da primeira etapa da **Avaliação de Acessbilidade Web**, da matéria de **Acessibilidade e Inclusão Digital** (CSH42, UTFPR, Turma 2020/2).

O objetivo desta parte da atividade é submeter o site escolhido a um validador de padrões web e corrigir os problemas apontados. O validador escolhido foi o **Markup Validation Service**, da W3C. Em uma etapa posterior da atividade (não contemplada neste projeto), é feita uma avaliação da acessibilidade do site escolhido.

## Problemas apontados

Foram apontados ao todo 29 problemas no HTML do site. Contudo, diversos dos problemas possuem natureza parecida. Por conta disso, eles foram agrupados em 9 categorias abaixo. Cada uma das categorias de problemas será resolvido em um PR diferente, que será anexado ao seu lado após sua realização.

- [x] Consider avoiding viewport values that prevent users from resizing documents. ([#1](https://github.com/eduardo-otte/acessibilidade-padroes-web/pull/1))

- [X] Attribute ____ is not serializable as XML 1.0 ([#2](https://github.com/eduardo-otte/acessibilidade-padroes-web/pull/2))

- [X] Attribute ____ not allowed on element ____ at this point ([#3](https://github.com/eduardo-otte/acessibilidade-padroes-web/pull/3))

- [ ] Element _____ not allowed as child of element ____ in this context

- [ ] An `img` element must have an `alt` attribute, except under certain conditions

- [ ] Self-closing syntax (`/>`) used on a non-void HTML element. Ignoring the slash and treating as a start tag.

- [ ] End tag _____ seen, but there were open elements.

- [ ] Unclosed element

- [ ] The type attribute is unnecessary for JavaScript resources.
