# GIT
### Basic Commands

- git init
- ls -a //mostra arq. ocultos
- git config user.name "Your Name"
- git config user.email "youremail@yourdomain.com"

- git status // verifica o armazenado no conteiner
- git log // exibe o histórico, autor, data, etc...
- git log --online // resume mudanças, exibe hash em 7 dígitos
- git log --graph // resume grafos, exibe hash em 7 dígitos
- git branch // verifica o ramo atual

- git add . // adiciona arquivos ao conteiner
- git add * // adiciona arquivos ao conteiner
- git commit -m "Descrever 1 Mensagem"
- git commit -am // "Descrever 1 Mensagem E adiciona arquivo"
- git reset HEAD <file> // desfazer commit, remover do conteiner
- git reset --hard 7777777 // remove <hash> 7777777

- git checkout 7777777 // restaura, remove alteração do <hash> 7777777
- git checkout master // recupera, alteração do ÚLTIMO <hash>
- git checkou <file> // restaura alterações no <file>
- git diff // exibe conteúdo alterado ANTES de incluir ao conteiner

- git remote add origin https://github.com/rodrigospeller/t3st3s.git
- git remote -v // verifica se existe este servidor remoto
- git remote set-url origin https://github.com/youruser/yourrepository.git // alterar URL de repositório

- git clone // baixa clone de projeto online
- git push // baixa atualizações
- git push // envia atualizações

### Config Commands
- git config --global user.name "Seu Nome"
- git config --global user.email "Seu Email"
- git config core.editor // exibe o editor configurado
- git config --global core.editor "Nome Editor" // altera editor pré-config.
- 

### Generic Commands
- clear // limpa a tela
- ls // exibe arquivos
- mkdir // cria pasta ou diretório
- pwd // exibe onde estou
- touch // cria arquivo

# Exemplo Básico

- cd "nome da pasta"

- git config user.name "Your Name"
- git config user.email "youremail@yourdomain.com"
- git init 
- git log
- git status
- git add .
- git status
- git commit -m "Arquivos Iniciais da Calculadora"
- git log
- git remote add origin https://github.com/youruser/yourrepository.git
- git remote -v
- git push origin master

## Exemplo Clonando Repository

git clone https://github.com/fabricadeprogramador/T31-team.git