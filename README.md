* git init: Este comando inicializa um novo repositório Git em um diretório existente.
  Ele cria uma nova subpasta chamada .git, onde todos os arquivos e informações de controle de versão são armazenados.

* git clone: Este comando copia um repositório remoto para o seu computador. Ele cria uma cópia completa do repositório,
  incluindo todos os arquivos, branches e histórico de commits. A URL pode ser do GitHub, GitLab, ou de qualquer outro serviço de hospedagem de

* git add .: Este comando adiciona todas as mudanças (novos arquivos, modificações e exclusões) do diretório atual ao "staging area" (área de preparação).
  O ponto (.) indica que você está adicionando todas as alterações no diretório atual.
  
* git commit: Este comando grava as mudanças adicionadas à área de preparação no repositório.
  A opção -m permite que você adicione uma mensagem descritiva para o commit, o que é importante para entender o que foi alterado.
  
* git status: Este comando mostra o estado atual do repositório, incluindo arquivos modificados, arquivos não rastreados e o que está na área de preparação.
  É útil para verificar quais alterações foram feitas antes de um commit.
  
* git push: Este comando envia suas mudanças locais para um repositório remoto. Após um commit, você usa git push para atualizar o repositório remoto com suas alterações.

* git pull: Este comando busca as mudanças mais recentes de um repositório remoto e as integra ao seu repositório local.
  É uma combinação de git fetch (para buscar as alterações) e git merge (para integrar as alterações).
  
* git log: Este comando exibe o histórico de commits do repositório, mostrando uma lista de todos os commits feitos,
  com detalhes como o hash do commit, autor, data e mensagem do commit. É útil para revisar o histórico de mudanças.
