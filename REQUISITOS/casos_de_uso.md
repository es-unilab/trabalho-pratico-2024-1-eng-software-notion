# SISTEMA GENOTE

## CASOS DE USO

*1. Cadastro de Usuário*

*Ator Principal:* Usuário

*Fluxo Principal:*
1. O usuário acessa a página de cadastro no sistema;
2. O usuário preenche os campos obrigatórios no formulário de cadastro (nome, e-mail, senha);
3. O usuário clica no botão de "Cadastrar";
4. O sistema valida os dados e cria a conta.

*Extensões:*

4a. Se o e-mail já estiver em uso, o sistema exibe uma mensagem de erro e solicita um e-mail diferente.

*2. Login de Usuário*
*Ator Principal:* Usuário

*Fluxo Principal:*
1. O usuário acessa a página de login no sistema;
2. O usuário insere seus dados (e-mail, senha);
3. O usuário clica no botão de “Entrar”;
4. O sistema valida os dados e entra na conta.

*Extensões:*
3a. Se os dados estiverem incorretos, o sistema exibe uma mensagem de erro.

*4. Inclusão de Categorias*
*Ator Principal:* Usuário

*Fluxo Principal:*
1. O usuário faz login no sistema;
2. O usuário acessa a interface de criação ou edição de uma anotação;
3. O usuário clica em adicionar categoria e acessa a interface de inclusão de categorias;
4. O usuário cria nova(s) categoria(s);
5. O usuário salva as alterações;
6. O sistema armazena a(s) categoria(s) criada(s) e confirma para o usuário.

*Extensões:*
4a. Se o usuário tentar criar uma categoria que já exista, o sistema exibe uma mensagem de erro informando que a categoria já existe e solicita que o usuário escolha um nome diferente.


*5.Pesquisa de anotações*

*Ator Principal:* Usuário

*Fluxo Principal:*
1. O usuário faz login no sistema;
2. O usuário acessa a interface de pesquisa;
3. O usuário insere uma palavra-chave no campo de pesquisa;
4. O sistema filtra as anotações que correspondem à palavra-chave;
5. O sistema exibe uma lista de anotações que correspondem à pesquisa;
6. O usuário seleciona e visualiza as anotações desejadas.

*Extensões:*

5a. Se a pesquisa não retornar resultados, o sistema exibe uma mensagem informando que nenhuma anotação foi encontrada.

