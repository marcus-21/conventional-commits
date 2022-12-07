# conventional-commits

##Estrututa do commit:
* ```
<tipo>[escopo opcional]: <descrição>

[corpo opcional]

[rodapé(s) opcional(is)]
```

###Sigas
  * `feat` Commits, que adiciona um novo recurso
  * `fix` Commits, que corrige um bug
  * `refactor` Commits, que reescrevem/reestruturam seu código, porém não alteram nenhum comportamento
  * Commits `perf` são commits `refactor` especiais, que melhoram o desempenho
  * Commits `style`, que não afetam o significado (espaço em branco, formatação, falta de ponto-e-vírgula, etc)
  * `test` Commits, que adicionam testes ausentes ou corrigem testes existentes
  * Commits `docs`, que afetam apenas a documentação
  * Commits `build`, que afetam os componentes de compilação, como ferramenta de compilação, ci pipeline, dependências, versão do projeto, ...
  * `ops` Commits, que afetam componentes operacionais como infraestrutura, implantação, backup, recuperação, ...
  * `chore` Commits diversos, por exemplo, modificando `.gitignore`

<img src="https://i.imgur.com/q5Iwfk0.png" width="400" height="400" />

###Principais comandos do git 
  *`git init` (Inicializa o git com o projeto)
  *`git status` (Mostra as pendências e o que ta acontecendo na execução)
  *`git add .` = todos os arquivos ou `nome do arquivo` (Adicionando os arquivos)
  *`git commit -m "EXEMPLO DE TEXTO PARA COMMIT"` (Adicionando mensagem no arquivo. (O "-m" = mensagem))
  *`git remote add origin https://github.com/yourperfil/nomeDaPasta.git` (linkando o repositorio local com o remoto)
  *`git branch -M main` (nomeando o main como a branch principal)
  *`git push -u origin main` (primeiro push para o repositorio remoto)
  *`cd NOMEDAPASTA`(entrando na pasta)
  *`cd ..`(Saindo da pasta)
  *`git checkout -b "Criando uma branch"`("-b nome da branch" = cria um branch. E trocando de branch com checkout) - repositorio local
  *`git push --set-upstream origin teste`(Criando uma branch no repositorio remoto)
  *`git push`(envio para o repositorio local e remoto)
  *`git branch`(listagem e a sinalização dos branch que você se encontra)
  *`git merge nomeDaBranch`(unir o codico da branch atual com a branch citada no git merge(coloca o codigo da branch desejada na atual))
  *`git pull`(pega as atualizações do repositorio remoto para o local)
  *`git clone` https://github.com/yourperfil/nomeDaPasta.git(clonando o projeto todo no repositorio local e automaticamente ele já pareado com o repositorio remoto)
  *`git clean -f` (limpa os que estão sinalizados e você não quer)
  *`git log`(Ver todos os commits do projeto)
