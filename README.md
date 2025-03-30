- # Como realizar uma pull request::
- ## FAÇA UM FORK DO PROJETO PARA O SEU GITHUB::
- Clone o projeto para sua máquina as alterações necessárias
- *Como clonar::*
- git clone <link do projeto disponível em code>
---
- ## Utilize sua BRANCH
- ### Como trocar de branch e utilizar a sua:
- git switch < nome da sua branch >
- git checkout < nome da sua branch > (esse pode não ser uma boa opção devido a ter várias funcinalidades relacionadas ao checkout)
- Por padrão toda alteração deverá ser feita na sua branch para depois ir para a main, para que não ocorra problemas de compatilibidade ou quebra de código.
---
- ## Como enviar uma pull request::
- git add .
- git commit -m "*< TIPOS > <PARTE CÓD. AFETADA> <DESCRIÇÃO>*"
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
- ## ABRIR SOLICITAÇÃO DE PULL REQUEST::
- ![image](https://github.com/user-attachments/assets/b77dd26e-9d7c-4752-8286-4bcb8ff57d4a)

- Envie do seu Fork para a sua branch no projeto principal::

- ![image](https://github.com/user-attachments/assets/a8999d0b-6351-4e38-a3a7-38ec96d537aa)


