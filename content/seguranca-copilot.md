---
title: "Melhores Práticas de Segurança com o GitHub Copilot"
date: "2025-05-28"
description: "Aprenda a usar o GitHub Copilot e ferramentas do GitHub para escrever código mais seguro. Descubra como evitar vulnerabilidades com Dependabot, CodeQL, Secret scanning e técnicas de segurança com IA."
tags: ["GitHub Copilot", "Segurança", "Security", "CodeQL", "Dependabot", "DevSecOps", "Vulnerabilidades", "GitHub Security", "Boas Práticas"]
---

# Melhores Práticas de Segurança com o GitHub Copilot

Todo mundo quer escrever código limpo, funcional e... seguro. A parte da segurança às vezes passa batido, principalmente se você não teve treinamento específico nessa área. Mas a boa notícia é que o GitHub Copilot pode ser um ótimo aliado nesse processo.

Neste post, vou te mostrar como usar o Copilot e outras ferramentas do GitHub para tornar seus projetos mais seguros, mesmo que você não seja especialista em segurança.


---

## O desafio da segurança no dia a dia
Equipes de segurança geralmente não têm braço suficiente pra proteger todo o código de uma empresa. Resultado: quem escreve código acaba sendo a primeira linha de defesa. Só que nem todo mundo teve formação ou tempo pra estudar segurança a fundo.

É aí que entra o GitHub. Além do Copilot, existem várias ferramentas que você pode usar, principalmente se estiver trabalhando com projetos Open Source.

---

## O Copilot pode ajudar
O GitHub Copilot não serve só pra escrever código rapidinho. Ele também pode te ajudar a escrever código mais seguro. Mas, claro, ele não faz mágica sozinho. Você precisa saber como usar.

**Um exemplo prático:** digamos que você esteja usando uma query SQL com `INSERT` no seu projeto. Já ouviu falar de SQL injection? É quando alguém mal-intencionado usa campos de entrada (como um campo de nome ou comentário) pra rodar comandos que podem comprometer todo o seu banco de dados.

Uma forma simples de evitar isso é usar consultas parametrizadas. E você pode pedir isso diretamente ao Copilot com um comentário claro, como:

```
/*
inserir do carrinho usando uma consulta parametrizada:
mail, product_name, user_name, product_id, address, phone, ship_date, price
*/
```

O Copilot vai sugerir uma versão mais segura. Revise a sugestão, veja se faz sentido, e só então aceite.

**Outra dica:** selecione um trecho de código e pergunte no Copilot Chat se ele vê alguma vulnerabilidade. Você também pode usar `@workspace` pra analisar o projeto inteiro. Perguntas como "qual é a superfície de ataque?" ou "há alguma vulnerabilidade nesta função?" funcionam muito bem.

Quer sugestões mais específicas? Usa o comando `/fix`, que sugere melhorias de segurança, performance e boas práticas.

Ah, e se você quiser mais ideias de prompts legais, dá uma olhada no [Copilot Chat Cookbook](https://docs.github.com/pt/copilot/copilot-chat-cookbook).


---

## Ferramentas gratuitas de segurança no GitHub
O Copilot ajuda bastante, mas você não deve confiar só nele. Por isso, o GitHub oferece várias ferramentas gratuitas de segurança pra projetos públicos.

Aqui vão algumas que eu recomendo ativar:

### Dependabot
Ele verifica se suas dependências estão atualizadas e cria PRs automáticos quando encontra vulnerabilidades. Pra ativar, vá em **Settings > Code security > Dependabot**.

### Code scanning com CodeQL
Detecta vulnerabilidades e problemas comuns no código. Vá em **Settings > Code security > Code scanning**, clique em **Set up > Default** e ative o CodeQL.

### Copilot Autofix
Quando combinado com o Code scanning, o Copilot pode sugerir automaticamente correções pra vulnerabilidades encontradas. Fica logo abaixo do botão de ativar o CodeQL.

### Secret scanning
Verifica se você expôs tokens, senhas ou chaves no seu repositório. E com a opção de **Push protection** ativada, ele bloqueia commits com segredos em tempo real.

Tem muito mais, mas essas são ótimas pra começar. Se quiser explorar mais, recomendo a [documentação de segurança do GitHub](https://docs.github.com/pt/code-security).

---

## Resumo pra salvar nos favoritos
Se você chegou até aqui, aqui vai um resumão dos próximos passos:

-   Use o Copilot pra identificar e corrigir vulnerabilidades (`/fix`, prompts no chat, etc).
    
-   Ative as ferramentas de segurança do GitHub: Dependabot, CodeQL, Copilot Autofix e Secret scanning.
    
-   Aproveite que tudo isso é gratuito pra repositórios públicos.
    
-   E sempre revise o que o Copilot sugerir. Ele ajuda, mas quem valida é você.
    

Gostou das dicas? Me conta o que você já usa ou se tem alguma dúvida.
💚
