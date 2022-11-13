
## Explicação básica de github

## <pre><b>✒️GitHub para que utilizamos?</pre> 
> Utilizamos para que toda a equipe de desenvolvimento, reúna todos os arquivos do projeto é um único local (repositório) dessa forma fica mais fácil gerenciar as alterações que ocorreu no projeto. 
Exemplo.: Em uma equipe de desenvolvimento os desenvolvedores estão trabalhando é um determinado projeto que ocorrera algumas mudanças no sistema, uns estão trabalhando no  FrontEnd, outros Backend  e outros fazendo a correções de bugs, perceba que essas mudanças estão ocorrendo simultaneamente, então a equipe precisa ter acesso ao código atualizado com todas as mudanças que foram feitas no código. E o GitHub serve para fazer isso.
## <pre><b>📏Algumas ações do GIT </pre> 
>
 * Commit  Quando realizamos um commit estamos adicionando as alterações mais recentes do projeto, ou seja guardando aquele estado atual que se encontra o projeto.
 * Git clone  É utilizado para selecionar um repositório existente e criar um clone (cópia) dele em um repositório local.
 * Git pull Usado para Fazer atualização (Se acaso outra pessoa tiver feito alguma alteração)ele informara qual arquivo que sofreu alteração e qual alteração foi feita.
 * Git push É  usado para enviar as alterações que foram feitas no seu repositório local para um repositório remoto.
git add .
 * git commit -m "mensagem de commit"
 * git push origin main
Precisamos adicionar os arquivos com o git add e depois fazer o commit com git commit. Assim é possível enviar/empurrar as alterações para o repositório remoto utilizando o git push origin main.
 * Git Restore  Volta para certo momento da aplicação, colocando o ponto vai para todo os arquivos desse diretório. 
git restore --source af7ea9a.
Git Status  Verificar o status atual 
Git log  Serve para verificar o histórico de alterações, com ele é possível visualizar o autor que realizou o commit e as alterações feitas.
git log
Com esse comando é possível visualizar o nome do autor que realizou o commit
git log --author="user_name"
É possível fazer uma pesquisa de commit por data 
git log --since=1.month.ago --until=1.day.ago
git add + nome da página  Incluir uma  página especifica no commit 
git add contato.html
## <pre><b>📝Ramificações e Merge</pre>
* Main  Onde fica o Projeto principal
* Branch É uma outra ramificação, criada para colocar o código de desenvolvimento, para não mexer no código principal. Que ficará na branch main.
Com o código abaixo criamos a branch desenvolvimento
* git checkout -b desenvolvimento
Para voltar para  branch main  é só digitar o comando abaixo.
git switch main
* Merge É Pegar tudo que está em determinada branch e mandar para a branch main. 
O comando git branch nós permitir visualizar todas as branches 
* git log –oneline conseguimos visualizar o último push e visualizar o número identificador  
* git merge  com o nome da branch que quero juntar.
Estamos trabalhando com duas branches: a branch main e a branch title. Fizemos várias alterações na branch title, mas, agora, queremos trazer tudo o que está na title para a main. Como podemos fazer isso?
