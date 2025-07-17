# Trilha 2025.1 

                                                Aula Git e GitHub Trilha


                                                  Gabriel Ayres :)

# Tópicos 

<!-- stop -->
- Controle de Versão
<!-- stop -->
- Git vs GitHub
<!-- stop -->
- Setup incial Git
<!-- stop -->
- Conceitos Básicos Git
<!-- stop -->
- Branches(Galhos) - Desenvolvimento Paralelo
<!-- stop -->
- Colaboração no GitHub (OpenSource :))
<!-- stop -->
- Conflitos 

# Controle de Versão 

> "O que é controle de versão?"
<!-- stop -->
> É como um histórico dos seus arquivos, pra você não perder nada e voltar no tempo se der algo errado
<!-- stop -->
    -  Mas o que acontece se n tiver controle de versão?
# Problema sem controle de versão

> É como escrever uma redação e sair salvando cópias tipo:
    <!-- stop -->
    - redação_final.docx  
    <!-- stop -->
    - redação_final_corrigida.docx  
    <!-- stop -->
    - redação_final_revisada_valendo.docx  
    <!-- stop -->
    - REDAÇÃO_VALENDO_MESMO_AGORA_VAI.docx  
    <!-- stop -->
Confusão total! :(
<!-- stop -->
> "Mas qual seria a solução?"
<!-- stop -->
    - O Controle de Versão!
# Solução

> É como ter um caderno com **todas as anotações organizadas por data**, podendo revisar cada passo que você deu.
<!-- stop -->
> Você passa a ter controle ao ponto de ver o que mudou, por quê mudou e o que mudar se necessário
<!-- stop -->
                  - Isso é o que o Git faz pra você(mas vamos falar dele mais pra frente)

# Git vs GitHub

> "O que é Git?"
<!-- stop -->
    - Git é a ferramenta de versionamento de código
    <!-- stop -->
      - Permite o controle local das versões do seu projeto
    <!-- stop -->
      - Funciona parecido com o Caderno de anotações de sua redação

> "O que é GitHub?"
<!-- stop -->
    - GitHub é um serviço online hospeda repositórios remotos Git
    <!-- stop -->
      - Funciona parecido com o Caderno de anotações de sua 
        redação mas agora você pode compartilhar com quem quiser
    <!-- stop -->
> Links:
<!-- stop -->
    - Git: https://git-scm.com/
    - GitHub: https://github.com/
<!-- stop -->
## Mas como configurar meu Git?

# Primeiro Passo: Instalar Git
    <!-- stop -->
- Se você usa Windows:
    <!-- stop -->
    > Acesse o Link: 
    - https://git-scm.com/ 
    - Baixe o executável e instale em seu computador incluindo no PATH
    <!-- stop -->
- Se você usa Linux/MacOS:
    <!-- stop -->
    > Abra o seu terminal e execute os comandos
    ```bash
    sudo apt install git  # Linux
    brew install git # MacOS
    ```
    <!-- stop -->
> Pronto! Agora você tem git em sua máquina :)
> E para executar no terminal basta:
  git 

## Agora com o Git, Vamos Configurar!

# Configuração Básica 
<!-- stop -->
> Definindo perfil Git:
<!-- stop -->
```bash
  git config --global user.name "Seu nome"
  git config --global user.email "Seu email da conta  do github"
```
<!-- stop -->
> Definir chave SSH:
<!-- stop -->
```bash
  ssh-keygen -t ed25519 -C "SEU EMAIL DO GITHUB"
  cat ~/.ssh/id_ed25519.pub
```
<!-- stop -->
    - Agora Setup no GitHub

# Conceitos Básicos Git

# O que é um repositório?
# Commit
# Branch
# Criar Repositorio
# Fluxo Basico de commits
