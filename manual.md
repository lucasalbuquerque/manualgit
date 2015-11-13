Configurações iniciais..

user name:

- git config --global user.name "Lucas Albuquerque"

Configurando e-mail:

- git config --global user.mail "lucastableless@gmail.com"

Após entrar na pasta do futuro repositório..

- git init - inicia um repositório na pasta

- git add nomedoarquivo.txt - adiciona arquivo ao controle de versão

- git status - situação de trabalho atual do repositório

- git add * adiciona todos os arquivos com extensão

- git add . adiciona tudo

Fazendo commit:
- git commit -m "Mensagem do commit" 

Ignorar arquivos: criar arquivo .gitignore e dentro desse arquivo escrever o nome com extensão dos arquivos que devem ser ignorados

- git diff - ver o que foi alterado no arquivo

- git log - mostra todos os commits que você fez no seu projeto, desde o inicio

- git log -p - todos os commits em ordem decrescente

- git log -p -1 me traz somente 1 unico commit

- gitk - exibe uma interface gráfica com o visualizador de
relatórios

- git tag - listar as tags do sistema

- git tag  -a v1.0 -m "versão 1.0' - criando tags v1.0 é o nome da tag e "versão 1.0" o comentário

- git log --pretty=oneline - mostrar todos os commits do sistema

criar uma tag para uma versão antiga do sistema - commit antigo do sistema:

= 

- git tag -a v00 689e1402d496e1c76f6504e51d449c3c712403a0 -m "versão 0.0"

- v00 é o nome dado ao commit 

DELETANDO UMA TAG:

- git checkout master - voltar ao padrão do branch master do sistema

- git tag -d nomedatag

Removendo arquivos monitorados:

- git rm nomedoarquivo.extensao

 Voltar repositório para um commit especifico:
git reset --hard "nome da tag dada ao commit, se não sabe criar veja acima."

Usando github:

- gerar ssh

Comando para gerar ssh:

- ssh-keygen

- pegar a key onde o git indica

- criar chave ssh e colar em

- public keys

Pegar o link https ou ssh e clonar o repositório para a minha máquina

- adicionar arquivos na pasta e depois a ele (git add .)

- fazer commit 

- e por fim subir as alterações e novos arquivos

- git push origin master

Forks:

Para manter um repositório forkado atualizado

- git remote add upstream linkdorepositoriooriginal (adicione somente uma vez)
