## Comandos básico Git utilizado no Projeto

* **git clone** 
Git clone é uma comando para baixar o código-fonte existente de um repositório remoto (como, por exemplo, o Github). Em outras palavras, git clone, basicamente, faz uma cópia idêntica da versão mais recente de um projeto em um repositório e a salva em seu computador.

Exemplo: 
>git clone https://link-com-o-nome-do-repositório

* **git status**
O comando git status nos dá todas as informações necessárias sobre a branch atual.

Exemplo: 
>git status

* **git add**
Ao criarmos, modificarmos ou excluirmos um arquivo, essas alterações acontecerão em nosso espaço de trabalho local e não serão incluídas no próximo commit (a menos que alteremos as configurações).

Precisamos usar o comando git add para incluir as alterações de um ou vários arquivos em nosso próximo commit.

Exemplo:
Para adicionar um único arquivo:
>git add (arquivo)

Para adicionar tudo ao mesmo tempo:

>git add -A    
ou
git add **.**

* **git commit**
Talvez esse seja o comando mais usado do Git. Quando chegamos a determinado ponto em desenvolvimento, queremos salvar nossas alterações (talvez após uma tarefa ou resolução de problema específica).

Git commit é como definir um ponto de verificação no processo de desenvolvimento. Você pode voltar a esse ponto mais tarde, se necessário.

Também precisamos escrever uma mensagem breve para explicar o que desenvolvemos ou alteramos no código-fonte.

Exemplo: 
>git commit -m "mensagem do commit"

 * **git push**
Após fazer o commit de suas alterações, a próxima coisa a fazer é enviar suas alterações ao servidor remoto. Git push faz o upload dos seus commits no repositório remoto.

Exemplo: 
>git push <repositório-remoto> <nome-da-branch>

Entretanto, se a sua branch foi recém-criada, também é preciso fazer o upload da branch com o seguinte comando:

Exemplo:
>git push -u origin <nome-da-branch>
>git push  origin main


 * **git branch**
Branches (algo como ramificações, em português) são altamente importantes no mundo do git. Usando as branches, vários desenvolvedores conseguem trabalhar em paralelo no mesmo projeto simultaneamente. Podemos usar o comando git branch para criar, listar e excluir as branches.

Exemplo: 
>git branch <nome-da-branch>

 * **git pull**
O comando git pull é usado para obter as atualizações de um repositório remoto. Esse comando é uma combinação de git fetch e git merge, o que significa que, quando usamos git pull, ele recebe as atualizações do repositório remoto (git fetch) e aplica imediatamente as alterações mais recentes em seu espaço de trabalho local (git merge).
 Eexemplo:
>git pull <repositório-remoto>


Fonte de pesquisa:
[Freecodecamp ](https://www.freecodecamp.org/portuguese/news/10-comandos-do-git-que-todo-desenvolvedor-deveria-conhecer/)



