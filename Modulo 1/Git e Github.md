# Git e Github 

### Git

> Tecnologia desenvolvida por Linus Torvalds para controlar o versionamento dinâmico de projetos/códigos em que estava trabalhando na época

---

### Github

> Plataforma da web que armazena projetos na nuvem, para de certa forma centralizar os diversos desenvolvedores que estão trabalhando em certo projeto

---

### Comandos - GIT Bash 

> * git init: inicializa um repositório
> * git add: adiciona arquivos ao repositório 
> * git commit: comita as mudanças realizadas para o repositório local
> * git clone: clona um repositório do servidor para sua máquina local
> * git config: realiza configurações no repositório
> * git status: visualiza o estado dos arquivos/diretórios do repositório
> * git push e git pull: "empurra - repositório local para servidor" e "puxa - servidor para o repositório local", respectivamente, as alterações feitas
> * git remote add: adiciona/linka uma conta do github com o repositóro da sua máquina

---

### Estados dos objetos dentro do Git

> * Tracked
>   * Modified
>   * Unmodified 
>   * Staged: Pronto para ser comitado
> * Untracked
> * Ignored: .gitignore (ignora arquivos que não devem ser carregados todas as vezes que realizarem push/pull, e.g. arquivos .class, arquivos binários, etc)

___

### Objetos

> Cada um deles carregam um SHA1 - algoritmo de encriptogração - específico
>
> São estruturas aninhada - Repositório: [n\*Commits[n*Trees: [n\*Blobs]]]
>
> * Blobs
> * Trees
> * Commites
