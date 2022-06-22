# Estudos sobre Git e GitHub

#### Comandos no Terminal Windows:
- **dir** -> Lista todas as pastas e arquivos dentro do diretórios atual
- **cd** -> navega ente os diretórios
- **cd ..** -> volta para o diretório anterior
- **cls** -> Limpa o terminal
- **TAB** – Atalho para autocompletar 
- **mkdir** -> Cria uma nova pasta
- **del** -> Deleta apenas arquivos
- **rmdir** -> Deleta o diretório

#### Comandos no Terminal Unix:
- **ls** -> Lista todas as pastas e arquivos dentro do diretório
- **cd**-> Navega entre os diretórios
- **mkdir** -> Cria uma nova pasta
- **rm -rf**-> Deleta o diretório
- **Ctrl + L** -> Limpa o terminal
- **TAB** – Atalho para autocompletar 

## Git

#### SHA1:
- Técnica de encriptação que gera conjunto de caracteres identificador de 40 dígitos.
É uma forma curta de representar um arquivo.

#### Objetos Fundamentais:
- Blobs:
Objeto que armazena os arquivos. Esse objeto contem metadados: tipo, tamanho, barra invertida e zero(\0) e o conteúdo do arquivo.
- Trees:
Armazenam blobs. Também contém metadados: aponta para uma blob e contem o sha1 e o título do sha1.
- Commits:
Aponta para uma arvore, parente(commit anterior), autor, mensagem, timestamp(data e hora de quando foi criado). Contém um sha1

#### Sistema distribuído:

#### Segurança:


## GitHub

#### Chave SSH:

#### Token:

#### Comandos Git Bash:

- **git init** -> Inicializa o git no repositório.
- **ls** -> Lista o conteúdo do repositório.
- **ls -a** -> Lista os arquivos ocultos.
- **git add** -> Adiciona os arquivos alterados para serem commitados.
- **git commit** -> Commita os arquivos que foram alterados.
- **git clone** -> Clona um repositório do GitHub.
- **git push** -> Envia os arquivos para o GitHub.
- **git pull** -> Puxa os arquivos do GitHub.
