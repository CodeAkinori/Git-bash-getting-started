# Git-bash-getting-started
#### Um guia passo a passo para iniciantes no Git, abrangendo desde a configuração inicial até o primeiro commit.

## Material do Repositório:

### Introdução ao Git Bash:

O Git é um sistema de controle de versão distribuído amplamente utilizado para rastrear mudanças no código fonte durante o desenvolvimento de software. Ele permite que múltiplos desenvolvedores trabalhem simultaneamente em um mesmo projeto, gerenciando diferentes versões de arquivos e facilitando a colaboração.

Por outro lado, o Bash é um shell de linha de comando comumente encontrado em sistemas Unix-like, como Linux e macOS. Ele fornece uma interface para interagir com o sistema operacional através de comandos textuais, permitindo a execução de tarefas como navegação de diretórios, manipulação de arquivos, e execução de programas.

O Git Bash combina essas duas tecnologias ao oferecer uma emulação do ambiente Bash dentro do Windows, junto com todas as funcionalidades do Git. Isso permite aos usuários executar comandos Git familiarizados em um ambiente confortável e eficiente, independentemente do sistema operacional utilizado, garantindo consistência no fluxo de trabalho de desenvolvimento.

### Configuração Inicial:

**Instruções detalhadas sobre como configurar o Git Bash no seu sistema.**

1. **Links para download do Git Bash para diferentes sistemas operacionais:**
   - [Git for Windows](https://gitforwindows.org/)
   - [Git para macOS](https://git-scm.com/download/mac)
   - [Git para Linux](https://git-scm.com/download/linux)

2. **Passos para instalação e configuração inicial do Git Bash:**
   - **Windows:**
     1. Faça o download do instalador do Git for Windows e execute o arquivo.
     2. Siga as instruções de instalação, deixando as opções padrão ou configurando conforme necessário.
     3. Abra o Git Bash a partir do menu iniciar ou usando o atalho criado durante a instalação.

   - **macOS:**
     1. Instale o Git através do Homebrew usando o comando `brew install git`.
     2. Alternativamente, faça o download do pacote de instalação do site oficial e siga as instruções.

   - **Linux:**
     1. Use o gerenciador de pacotes da sua distribuição para instalar o Git (por exemplo, `sudo apt install git` para Ubuntu/Debian).
     2. Para outras distribuições, consulte a documentação específica de instalação do Git.

3. **Configuração global do Git (nome de usuário, e-mail):**
   - Após instalar o Git Bash, abra o terminal e configure seu nome de usuário e endereço de e-mail globalmente usando os seguintes comandos:
     ```
     git config --global user.name "Seu Nome"
     git config --global user.email "seu-email@example.com"
     ```
   - Substitua `"Seu Nome"` pelo seu nome e `"seu-email@example.com"` pelo seu endereço de e-mail Git.

### Primeiros Passos:

1. **Comandos básicos do Git:**
   - `git init`: Inicia um novo repositório Git localmente.
   - `git add`: Adiciona arquivos ao staging area para prepará-los para commit.
   - `git commit`: Registra as mudanças feitas nos arquivos no repositório.

2. **Como criar um repositório local:**
   - Abra o Git Bash.
   - Navegue até o diretório onde deseja iniciar o repositório usando comandos como `cd`.
   - Execute o comando `git init` para criar um novo repositório Git vazio.

3. **Como adicionar arquivos ao staging area e realizar o primeiro commit:**
   - Após fazer mudanças nos arquivos, use `git add .` para adicionar todos os arquivos ao staging area. Substitua `.` pelo nome específico do arquivo para adicionar apenas um arquivo.
   - Para confirmar as alterações, use `git commit -m "mensagem do commit"` para confirmar as alterações.

**Plugar um Repositório Remoto:**

1. **Adicionar um repositório remoto:**
   - Após criar um repositório local com `git init`, você pode adicionar um repositório remoto utilizando o comando `git remote add`. Por exemplo:
     ```
     git remote add origin https://github.com/seu-usuario/seu-repositorio.git
     ```
     Substitua `https://github.com/seu-usuario/seu-repositorio.git` pelo URL do seu repositório remoto.

2. **Verificar repositórios remotos:**
   - Para verificar os repositórios remotos associados ao seu projeto, você pode usar `git remote -v`. Isso mostra os URLs dos repositórios remotos configurados.

3. **Enviar alterações para o repositório remoto:**
   - Depois de adicionar um repositório remoto, você pode enviar as alterações locais para ele usando `git push`. Por exemplo, para enviar a branch principal (geralmente chamada de `main` ou `master`):
     ```
     git push -u origin main
     ```
     Isso envia suas alterações locais para o repositório remoto chamado `origin`, na branch `main`.

### Recursos Adicionais:

- **Documentação oficial do Git:**
  - [Git Documentation](https://git-scm.com/doc) - Documentação oficial do Git que abrange todos os aspectos do sistema de controle de versão.


Enjoy ;D