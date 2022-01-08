# Introdução Ao Git e GitHub

## AULA 23 - Entendendo o Que é Git e Sua Importância 

### Instrutor: Otavio Reis

**Git:** criado em 2005 pela Microsoft, é um sistema de versionamento de código distribuído.

**GitHub:** é para guardar o software pronto.



**Benefícios:**

- Controle de versão
- Armazenamento em nuvem
- Trabalho em equipe
- Melhorar seu código
- Reconhecimento





## AULA 24 - Comando Básicos Para um Bom Desempenho no Terminal

### Instrutor: Otávio Reis

*Navegação Básica no Terminal e instalação do Git*

GUI (Graphic User Interface) x CLI (Command Line Interface)



**Comandos no sistema Windows:**

- **cd** = comando básico
- **dir**= lista 
- **mkdir** = cria objetos
- **del** = deleta arquivos
- **rmdir** = deleta a objeto
- **cls** = limpa a tela
- **tab** = auto completar
- **echo** = retorna o que eu escrever / criar arquivos após >
- **flag** = variâncias





## AULA 25 - Realizando a Instalação do Git

### Instrutor: Otávio Reis

Instalação do GIT

Nesta aula instalamos o Git Bash



## AULA 26 - Tópicos Fundamentais para Entender o Funcionamento do Git

### Instrutor: Otávio Reis

**SHA1 (Secure Hash Algorithm):**  é um conjunto de funções *hash* criptográficas projetadas pela NSA (Agência de Segurança Nacional dos EUA). A encriptação gera um conjunto de caracteres de 40 dígitos (único).

**Ex.:**

echo "ola mundo | opensssl sha1"

( stdin ) = f9fc856e559b950175f2b7cd7dad61facbe58e7b



Objetos fundamentais 
Sistema Distribuido
Segurança



## AULA 27 - Objetos Internos do Git

### Instrutor: Otávio Reis

**Blobs:**
echo 'conteudo' | git hash-object --stdin

>a8554148411dfb494b5f21ee1ab01b7fc59f78b5

echo -e 'conteudo' | openssl sha1
>f1cf116608cc333ac0e05acf4d6081672ad84c6a

echo -e 'blob 9/0conteudo' | openssl sha1
>f1cf116608cc333ac0e05acf4d6081672ad84c6a



**Trees = Ávores:**
Também contém metadados
aponta para o Blob ou outras árvores (trees)
é responsável por montar toda a estrutura de onde estão localizados os arquivos.



**Commits:**
É objeto que vai juntar tudo eaponta para uma árvore, último commit, autor e mensagem.





## AULA 28 - Chave SSH e Token

### Instrutor: Otávio Reis

**Chave SSH:** é uma forma de estabelecer uma conexão segura entre 2 máquinas, são 2 chaves, uma pública e uma privada.

**Token:**



## AULA 29 - Iniciando o GIT e Criando um Commit

### Instrutor: Otávio Reis

Iniciando o GIT e criando um commit:

**Comandos básicos:**

- git init (inicia o Git naquela pasta de arquivos)
- git add (adiciona todas as modificações feitas ao Git)
- git commit (junta tudo e "renderiza" para enviar ao servidor)



## AULA 30 - Passo a Passo no Ciclo de Vida

### Instrutor: Otávio Reis

tracked

**Estados do ciclo:**

unmodified (não modificado) - modified (modificado) - staged (pronto para comitar)

adiciona o arquivo
edita o arquivo 
stage o arquivo
remove o arquivo
commit

**Repositório:** São 2 ambientes

**Servidor:** Remote Repository (Repositório Remot)



**Ambiente de desenvolvimento: **
working directory	staging area 	local repository

**git add** + ***** ou **.** (adiciona todas as alterações).



## AULA 31 - Trabalhando com GitHub

### Instrutor: Otávio Reis

git config -- global --list
--unset
user.name

*Se você sair e voltar e estiver dando erro use este código:* **rm -f ./.git/index.lock**

comandos para criar e linkar o repossitório ao arquivo:

1. git init
2. git add .
3. git commit -m "descrição"
4. git remote add origin https://github.com/Seu-Nome/Seu-Arquivo.git
5. git remote -v
6. git push origin master



## AULA 32 - Como Resolver os Conflitos Que Acontecem no GitHub e Como Resolve-lôs

### Instrutor: Otávio Reis

**Conflito de merge:**

*Para resolver você vai precisar usar um dos comandos abaixo, **Push (empurrar)** ou **Pull (puchar)**.*

git  push origin master
git  pull origin master



## AULA 33 - O Que São Branches

**Branch:**
É uma ramificação dentro do teu repositório **Git**.

**Ex.:**

Desenvolvedor A está trabalhando na Home Page do Inter.
Desenvolvedor B está trabalhando na Página dos canais de atendimento do Inter.

Os dois desenvolvedores estão trabalhando em funcionalidades distintas dentro de um mesmo Repositório GIT, então é criado para cada tarefa uma **Branch**, onde dentro de cada **branch** cada desenvolvedor vai adicionar o código necessário para cumprir a sua tarefa.

Quando a funcionalidade de uma **branch** está pronta, é criado o *Pull Request*, para se dar andamento na tarefa, o teu código vai passar por *Code Review* e Testes de Qualidade, para depois de ter sido aprovado nestas etapas, essa tua **branch** ser Mesclada (*git merge*) com a **branch** de produção, que é quando a funcionalidade desenvolvida vai ser entregue em produção.

*Tipicamente as **Branches** servem para separar os escopos de desenvolvimento dentro do mesmo projeto.*