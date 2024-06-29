# gcs-atividade-extra

Repositório destinado para desenvolvimento da atividade extra

### Especificação do que foi executado

- Primeiramente criei a branch <b>feature1</b> para concluir a <b>issue #1</b>, onde ao realizar o push, foi aberto utomaticamente um <b>PR #2</b>, e ao autorizar o <b>PR #2</b>, a <b>issue #1</b> foi fechada automaticamente

- Depois criei a branch <b>feature2</b> para resolver a <b>issue #3</b>. Porém, me confundi e pensei que a issue fosse a de <b>número #2</b>, logo, no PR #4, que foi aberto automaticamente ao executar o push da branch <b>feature2</b>, referenciei o fechamento da <b>issue #2</b>, que não existe, pois é um PR. 

- Com isso, tive que realizar um <b>Revert do merge 4</b>, gerando um novo <b>PR #5</b> que agora de fato fechou a <b>issue #3</b>, que estava referenciada corretamente.

- Por fim, criei a branch <b>feature6</b> para concluir a <b>issue #6</b>, e com essas alterações no README, irei realizar o push e creio que o actions irá abrir automaticamente o <b>PR #7</b>,e  ao autorizá-lo, a <b>issue #6</b> será fechada automaticamente.
