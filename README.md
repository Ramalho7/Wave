- # Como realizar um commit::
- ## CRIAR BRANCH LOCAL::
- git checkout -b <nome_sua_branch>
- ## ADICIONE AS ALTERAÇÕES E ENVIE::
- git add .
- git commit -m "*<TIPOS><PARTE CÓD. AFETADA><DESCRIÇÃO>*"
- ####
  tipos::
- *feat:* Usado para adição de uma nova funcionalidade ou recurso ao projeto.
  Exemplo: feat(login): add password reset option  
- *fix:* correção de um bug ou problema no código.
  fix(api): resolve null pointer exception  
- *docs:* Refere-se a alterações na documentação, como READMEs, comentários no código ou guias
  Exemplo: docs(readme): update installation steps  
- *style:* Alterações que afetam a formatação ou estilo do código, sem mudar sua lógica.
  Exemplo: style(css): adjust indentation  
- ## REALIZAR PUSH PARA SUA BRANCH REMOTA::
- git push origin *<branch_local>*:*<branch_remota>*
