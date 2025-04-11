# 💻 Versionamento de Código com Git e GitHub

**📚 Resumo das Aulas**

- Repositório criado para fins educacionais para trabalhar em modo colaborativo, no intuito de praticar versionamento de código e colaboração.

**🚨 Git**

- Git é um sistema de controle de versão distribuído, utilizado para rastrear alterações em arquivos de código-fonte durante o desenvolvimento de software.

**🚨 GitHub**

- Plataforma de hospedagem de código para controle de versão com Git e colaboração.

**🚨 Passos para criar uma pasta, iniciar um repositório Git, adicionar um arquivo, salvar as alterações e enviar para o repositório remoto**

```mkdir nome-da-pasta``` (cria uma pasta)

```cd nome-da-pasta``` (muda para a pasta)

```git init``` (inicia um repositório git vazio)

```touch nome-do-arquivo.extensão``` (cria um arquivo)

```git status``` (verifica o status)

```git add .``` (adiciona as alterações para a área de preparação)

```git status``` (verifica o status)

```git commit -m "first commit"``` ("comita"/salva as alterações feitas)

```git branch -M main``` (nomeia a branch atual para main)

```git remote add origin https://github.com/[seu usuário]/[nome do seu repositório].git``` (conecta o repositório local a um repositório remoto hospedado no GitHub)

```git push -u origin main``` (faz o "push"/envia as alterações locais para o repositório remoto no GitHub, na branch main)

