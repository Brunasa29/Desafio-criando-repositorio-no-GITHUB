***Links importantes***
- Para download do Git: https://git-scm.com/downloads

O Git Bash é um terminal extentido para otimizar o uso do Git.

- Para acesso ao Github: https://github.com/

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git.

***Como criar um repositorio no GITHUB***

- Abra o Github, faça login com a sua conta e clique em New repository.

- Em seguida, basta colocar o nome e descrição do repositório que você está criando e clicar em Create repository.

- O repositório foi criado, só que ainda está vazio.Vamos enviar nossos arquivos para lá!

- Abra o Git Bash e vá até a pasta onde está o seu projeto.

- Agora, vamos transformar essa minha pasta em um repositório Git.Pra isso, basta digitar git init e dar enter: $ git init

- Ele está falando que iniciou um repositório vazio nessa pasta. Como eu sei que agora tenho um repositório nessa pasta? Se você abrir a pasta no File Explorer e configurar ele para mostrar os arquivos ocultos, verá que tem uma pasta a mais chamada .git.

-O Git usa essa pasta pra controlar as alterações feitas no seu repositório.

- Agora para sincronizar o repositório na sua máquina e um no Github, você entra no github copia o link da pasta e digita no git e dar enter: $git remote ass origin link.

- Para enviar isso para o meu repositório remoto digito git push origin master no git e dar enter: git push -u origin master

- Pronto, você criou seu repositorio no github sincronizado com o seu repositorio local.

