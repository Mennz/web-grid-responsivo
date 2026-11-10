# Blog da Trilha

Página de blog fictício sobre trilhas, feita pra praticar CSS Grid com
`grid-template-areas` e layout responsivo de verdade, sem framework.

O que pratiquei:

- `grid-template-areas` pra organizar cabeçalho, barra lateral, conteúdo e
  rodapé sem depender de `float` nem `position`
- menu que vira sanduíche no celular, com um `button` e um pouco de JS pra
  trocar a classe que mostra/esconde o `nav`
- imagens que se adaptam ao card (`max-width: 100%`, `height: auto`)
- três pontos de quebra: celular (até 700px, menu sanduíche e tudo em uma
  coluna), tablet (até 1000px, barra lateral mais estreita) e tela larga
  (a partir de 1400px, barra lateral mais folgada)

## Como rodar

Não tem build nem dependência. Só abrir o `index.html` no navegador, ou
servir a pasta com qualquer servidor estático:

```bash
python -m http.server
```

Pra testar os breakpoints, redimensione a janela ou use o modo responsivo
do DevTools (F12 → ícone de celular/tablet).
