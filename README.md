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



## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
