→ Criação de pasta -- Mkdir

→ Acessar a pasta -- CD nome-da-pasta

→ Para iniciar um repositorio -- git init

→ para retornar um diretorio -- cd ..

→ para renomear uma pasta do diretorio -- mv nome-da-pasta-deverá-sair-da-pasta-primeiro

→ para remover um diretorio
certificar que esta sincronizado com o repositorio remoto e remova a pasta localmente com o codigo 
• git rm -r nome-da-pasta-ou-arquivo

→ para criar um arquivo dentro de uma pasta
• echo "# nome-da-pasta" >> nome-do-arquivo

→ para listar quais arquivos existem dentro da pasta selecionada
• ls

→ para adicionar conteudo os arquivos/pastas
• git add nome-do-arquivo

→para adicionar conteudo os arquivos/pastas
• touch nome-do-arquivo

→ para adicionar todos os arquivos/pastas
• git add .

→ para desfazer um add especifico
• git reset nome-do-arquivo

→ para desfazer um add geral
• git reset 

→ para fazer um comentario no arquivo adicionado ANTES-DO-PUSH (commit)
• git commit -m "Commit-em-Inglês-GABRIEL"

→ para verificar os arquivos na branch
• git status

→ Caso adicione um arquivo errado utilize esse comando para restaurar o ultimo estado confirmado (com a opção --staged) o arquivo sera removido apenas da area de preparação.
• git resotre --staged 

Para desfazer commits errados 

→ Retorna ao último commit, mantendo as alterações feitas nos arquivos
• git reset --soft HEAD~1

→ Retona ao último commit, removendo as alterações feitas nos arquivos
• git reset --hard HEAD~1
