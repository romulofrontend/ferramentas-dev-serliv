# FERRAMENTAS DEV

## TERMINAL (Git Bash) - Comandos UNIX
terminal clear | clear | Limpa o terminal
terminal print | echo  oquedeveserexibido| Escreve no terminal 
directory print work | pwd | Exibe o directorio de trabalho atual
directory make   | mkdir nomediretorio(s) | Criar um ou mais diretórios
directory remove | rmdir nomediretorio | Remover o diretório
directory change | cd nomediretorio | Acessar o diretório 
directory change | cd ~ | Volta ao diretorio User
directory change | cd ../ | Volta um nivel da posição atual
list | ls    | Listar itens presentes no diretorio referente
list | ls -a | Listar itens, inclindo arquivos ocultos, presentes no diretorio
file make   | touch nomedoarquivo.extensão - Criar um arquivo no diretorio
file remove | rm nomedoarquivo.extensão - Remover um arquivo no diretorio
file remove | rm caminhodoarquivo - Remover um arquivo no diretorio
file copy   | cp nomedoarquivo.extensão novodiretoridestino - Faz uma copia do arquivo no diretoriodestino
file move   | mv caminhoarquivoatual novodiretoridestino
file write  ! echo oquedeveserescrito > nomefoarquivo.extensão | Escreve dentro do arquivo
file view   | cat nomedoarquivo.extensão 
directory and file remove | rm -rf nomediretorio



## GIT COMANDOS
git init - inicializa o repositório
git status - Exibe o monitoramento dos arquivos modificados após ter inicializado o repo
git add nomearquivo.extensao - Insere o arquivo no stage (etapa anterior ao commit)
git rm --cached nomearquivo - Remove o arquivo da stage
git commit -m "mensagem" - Guarda a alteração realizada no código e sua mensagem ajuda a marcar a mudança
git commit -a -m "mensagem" | git commit -am "mensagem" - Coloca o arquivo no stage, comita e guarda a mensagem numa mesma operação
git log - Exibe todos os commits efetuados no repo
git log --oneline - Exibe o id do commit e a flag referente



BRANCHS - Ramificações do projeto
git branch - Exibe a lista de branchs do projeto (* na branch atual)
git checkout -b nomedabranch - Cria uma nova branch espelhando a versão atual do projeto (branch master)
git checkout nomedabranch - Passa a acessar a branch passada
git checkout master - Passa a acessar na branch master
git checkout main - Passa a acessar na branch main
git merge nomedabranch - É importante estar na master/main para dar esse comando
git branch -b nomedabranch - Deleta a branch referente (só consegue após ter feito merge na master)
git branch -D nomedabranch - Força o Deleta a branch referente (só consegue após ter feito merge na master)
git diff - Exibe o que foi alterado
git checkout nomearquivo - Defaz alterações (desde que não tenham sido postas em stage)
git checkout . - Defaz alterações (desde que não tenham sido postas em stage)

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
