# meu-projeto

git init
- Iniciar novo projeto com git

git add <nome-arquivo>/.

git commit -m "mensagem commit" (-m é -msg)
- deixa os arquivos prontos para serem commitados

git log
- mostra os ultimos commits, log  de alterações

git status
- mostra como está o estado de branches

git diff
- mostra o que foi alterado
- o que tem de alteração na branch

git merge
- mescla as branches

git branch
- mostra a branch atual

git checkout <nome-da-branch>
- muda para a branch solicitada

git branch -b <nome-da-nova-branch>
- cria uma nova branch a partir da branch atual

git remote add <nome> <url>
- adiciona um novo repositório remoto

git push <nome> <nome-da-branch>
- manda nossas alterações locais para o repositório remoto, para cada branch

git pull <nome> <nome-da-branch>
- pega as alterações do repositório remoto e atualiza o nosso repositório local

git fetch
- atualiza o novo histórico local de acordo com o histórico salvo no repositório remoto
- sincroniza o repositório local com o remoto
