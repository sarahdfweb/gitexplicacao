
## Explicação básica de github

## <pre><b>✒️GitHub para que utilizamos?</pre> 
> Utilizamos para que toda a equipe de desenvolvimento, reúna todos os arquivos do projeto é um único local (repositório) dessa forma fica mais fácil gerenciar as alterações que ocorreu no projeto. 
Exemplo.: Em uma equipe de desenvolvimento os desenvolvedores estão trabalhando é um determinado projeto que ocorrera algumas mudanças no sistema, uns estão trabalhando no  FrontEnd, outros Backend  e outros fazendo a correções de bugs, perceba que essas mudanças estão ocorrendo simultaneamente, então a equipe precisa ter acesso ao código atualizado com todas as mudanças que foram feitas no código. E o GitHub serve para fazer isso.
## <pre><b>📏Algumas ações do GIT </pre> 
>
 * Commit -->  Quando realizamos um commit estamos adicionando as alterações mais recentes do projeto, ou seja guardando aquele estado atual que se encontra o projeto.
 * Git clone --> É utilizado para selecionar um repositório existente e criar um clone (cópia) dele em um repositório local.
 * Git pull --> Usado para Fazer atualização (Se acaso outra pessoa tiver feito alguma alteração)ele informara qual arquivo que sofreu alteração e qual alteração foi feita.
 * Git push --> É  usado para enviar as alterações que foram feitas no seu repositório local para um repositório remoto.
git add .
 * git commit -m --> "mensagem de commit"
 * git push origin main
Precisamos adicionar os arquivos com o git add e depois fazer o commit com git commit. Assim é possível enviar/empurrar as alterações para o repositório remoto utilizando o git push origin main.
![image](https://user-images.githubusercontent.com/87348787/201507069-b0e5ea5f-c740-43b4-b3e3-6af7ba6cf5e1.png)

 * Git Restore -->  Volta para certo momento da aplicação, colocando o ponto vai para todo os arquivos desse diretório. 
![image](https://user-images.githubusercontent.com/87348787/201507096-843e5c5e-0ae6-4ac5-99d1-46b278b7de76.png)

* Git Status --> Verificar o status atual 
* Git log -->  Serve para verificar o histórico de alterações, com ele é possível visualizar o autor que realizou o commit e as alterações feitas.

> Com esse comando é possível visualizar o nome do autor que realizou o commit

> ![image](https://user-images.githubusercontent.com/87348787/201507232-661e16b5-c14c-41d1-99e9-646415f32223.png)


> É possível fazer uma pesquisa de commit por data 
![image](https://user-images.githubusercontent.com/87348787/201507419-bcabc72f-df60-44a0-a044-8dc5ec844db7.png)

* git add + nome da página  Incluir uma  página especifica no commit 
![image](https://user-images.githubusercontent.com/87348787/201507466-1f3b24c5-a9ae-42dd-b99b-5c3c2a0dae4f.png)

## <pre><b>📝Ramificações e Merge</pre>
* Main --> Onde fica o Projeto principal
* Branch -->  É uma outra ramificação, criada para colocar o código de desenvolvimento, para não mexer no código principal. Que ficará na branch main.
> Com o código abaixo criamos a branch desenvolvimento
![image](https://user-images.githubusercontent.com/87348787/201507567-c1d8c8a9-5f60-4663-bac1-49ef11081e54.png)

> Para voltar para  branch main  é só digitar o comando abaixo.

![image](https://user-images.githubusercontent.com/87348787/201507658-996c3fc9-5e27-43db-9243-1801a8442188.png)

* Merge --> É Pegar tudo que está em determinada branch e mandar para a branch main. 
O comando git branch --> Nós permiti visualizar todas as branches. 
> Usando o comando ![image](https://user-images.githubusercontent.com/87348787/201507752-f9489645-09a3-41aa-8bdb-5f3aa6714bfc.png)
 conseguimos visualizar o último push e visualizar o número identificador.  


