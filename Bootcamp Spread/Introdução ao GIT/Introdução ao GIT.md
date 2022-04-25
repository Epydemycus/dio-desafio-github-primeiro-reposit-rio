# Introdução ao GIT

#### GIT é um sistema de versionamento distribuído, criado em 2005, por Linus Tovards.

Navegação via Command Line Interface - CLI

- SHA1: Algoritmo de encriptação. A saída dele gera um conjunto de caracteres identificador de 40 dígitos.



#### Objetos Internos do GIT

- Bloobs: Bloco básico de composição. Não guarda o nome do arquivo, apenas o SHA1.
- Trees: Armazenando e apontando para tipos de Bloods diferentes. Será o responsável por montar toda estrutura de onde está o arquivo.
- Commits: Objeto que junta trees e bloods.



#### Alguns comandos do GIT Bash

- git init: cria a pasta ".git". Inicializa o conceito de repositório.
- git add . :Atualiza o repositório
- git commit origin main/master: Envia para o GitHub
- git push origin main/master: Autentica no GitHub
- Ctrl + L: Limpar a área do Git.
- LS: lista os arquivos no diretório