---
title: "Conectando Git ao GitHub"
date: "2024-12-04"
description: "Aprenda a conectar o Git ao GitHub de forma simples e prática, com um passo a passo detalhado."
tags: ["GitHub"]
---

## Conectando Git ao GitHub

Oi, pessoa incrível que está iniciando sua jornada na programação! 👩‍💻

Hoje vamos aprender a conectar o **Git**, que é a ferramenta de controle de versão no seu computador, ao **GitHub**, onde você pode compartilhar seu código com o mundo e colaborar com outras pessoas. Vou explicar tudo de um jeito bem simples e direto, para que você consiga fazer isso sem muitos problemas. Vamos lá? 🚀

----------

### O que é Controle de Versão?

O controle de versão é como uma máquina do tempo para o seu código. Ele guarda o histórico de todas as mudanças que você faz nos seus projetos. Assim, você pode:

- Voltar a uma versão anterior, se algo der errado.
- Trabalhar em grupo sem sobrescrever o trabalho das outras pessoas.
- Organizar suas melhorias e correções de maneira prática.

O Git é uma ferramenta poderosa que facilita tudo isso no seu computador, e o GitHub leva essa mágica para a internet!

----------

### Por que conectar Git ao GitHub?

O Git ajuda você a gerenciar as versões do seu código localmente. Já o GitHub é como uma "rede social" para pessoas desenvolvedoras: você pode colocar seu código lá, mostrar para o mundo e até trabalhar junto com outras programadoras. Para que o Git e o GitHub conversem entre si, precisamos criar uma **ponte**.

Essa ponte é feita usando algo chamado **chave SSH**. É uma chave de segurança que permite que os dois se conectem sem você precisar digitar sua senha toda hora.

----------

### Passo 1: Criando sua Chave SSH

Vamos começar criando essa chave no seu computador. Siga o passo a passo:

1. Abra o terminal (pode ser o **Git Bash**, se você estiver no Windows).
2. Digite este comando no terminal:

    ```bash
    ssh-keygen -t ed25519 -C "seu-email@email.com"
    
    ```

    **Dica**: Substitua `seu-email@email.com` pelo e-mail que você usou para criar sua conta no GitHub.
3. Pressione **Enter** para aceitar os padrões (não precisa mudar nada).

Pronto! Sua chave foi criada. Agora, vamos adicioná-la ao GitHub.

----------

### Passo 2: Adicionando a Chave ao GitHub

1. No terminal, digite este comando para ver o conteúdo da chave que você acabou de criar:

    ```bash
    cat ~/.ssh/id_ed25519.pub
    
    ```

    Ele vai mostrar um texto longo (é sua chave SSH). **Copie esse texto**.

2. Agora, vá para o site do GitHub e siga esses passos:

- Clique na sua foto de perfil no canto superior direito.
- Vá em **Settings** (Configurações).
- No menu à esquerda, clique em **SSH and GPG Keys**.
- Clique no botão **New SSH Key** (Nova Chave SSH).

3. Dê um nome para a chave (por exemplo, "Meu computador") e cole o texto que você copiou do terminal.

4. Clique em **Add SSH Key** (Adicionar Chave SSH).

----------

### Passo 3: Testando a Conexão

Agora vamos ver se deu tudo certo:

1. No terminal, digite:

    ```bash
    ssh -T git@github.com
    
    ```

2. Se estiver tudo funcionando, você vai ver uma mensagem como esta:

```
Hi [seu user]! You've successfully authenticated, but GitHub does not provide shell access.
```

Parabéns! 🎉 Você acabou de conectar o Git ao GitHub!

----------

### O que vem depois?

Com tudo configurado, agora você pode criar projetos, enviar seu código para o GitHub e colaborar com outras programadoras. Esse é um passo importante na sua jornada, e você acabou de arrasar nele! 💪

Se ficou alguma dúvida, pode comentar aqui que eu respondo!
Pergunte, experimente e pratique. Estamos juntas nessa caminhada! 💜
