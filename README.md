# marcosdeobjunior.github.io

Raiz do GitHub Pages da conta. Serve dois propósitos:

- `.well-known/assetlinks.json`: verificação do app Android do Sól de Sóter
  (`io.github.marcosdeobjunior.soldesoter`), para ele abrir em tela cheia, sem barra de
  endereço. Ver `docs/APP_ANDROID.md` no repositório
  [planejamento-pessoal](https://github.com/Marcosdeobjunior/planejamento-pessoal).
- `index.html`: redireciona a raiz para o site, em `/planejamento-pessoal/`.

`.nojekyll` faz o GitHub Pages publicar a pasta `.well-known`, que o Jekyll ignoraria.
