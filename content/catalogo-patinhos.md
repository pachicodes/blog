---
title: "Catálogo de Patinhos de Borracha 🦆: Como criamos um site Open Source com GitHub Copilot"
date: 2025-04-08
author: "Pachicodes"
tags: ["Open Source", "copilot", "desenvolvimento web", "live coding"]
description: "Descubra como criamos o 'Catálogo de Patinhos de Borracha', um site open source, usando GitHub Copilot em uma live. Veja o passo a passo do desenvolvimento web e como a IA auxiliou no processo."
---

# Catálogo de Patinhos de Borracha 🦆: Como criamos um site Open Source com GitHub Copilot

Inspirada pelos meus companheiros de trabalho falantes de inglês, que toda quinta-feira fazem uma live chamada *Rubber Duck Thursday*, eu resolvi criar a versão brasileira desse quadro: **Quinta do Patinho**! 💚

A ideia é simples: uma live descontraída, sem grande planejamento, explorando ferramentas do GitHub enquanto conversamos com a comunidade.

E para a live de abertura, decidimos usar o GitHub Copilot para criar um projeto do zero — e, por sugestão do chat, nasceu o nosso **Catálogo de Patinhos de Borracha para Debugging**. 💻🦆

> [Esse site é Open Source](https://github.com/pachicodes/catalogo-patinhos-dev), e você pode contribuir adicionando seu próprio patinho!

---

## 🧠 Concepção e Estruturação Inicial

Queríamos um site simples, que mostrasse diferentes patinhos de borracha temáticos para pessoas desenvolvedoras. Pedi ao GitHub Copilot para criar a estrutura básica em HTML:

- Declaração `DOCTYPE` e configuração do documento
- Um `<head>` com título
- Um container principal para exibir os cards de patinhos

Depois pedi um layout com três patinhos por linha. E, mesmo sem especificar que queria um design responsivo, o Copilot já gerou um layout adaptável para diferentes tamanhos de tela. Com isso, já tínhamos a base funcional do site.

---

## 🖼️ Imagens e Descrições dos Patinhos

Subi três imagens de patinhos, nomeando os arquivos com a "profissão" ou "personalidade" de cada um: `Pedreiro.jpg`, `Rosinha.jpg`, `Secretario.jpeg`.

Reformulamos o conceito: cada patinho seria um parceiro de debugging com uma especialidade:

- **Patinho Pedreiro**: especialista em infraestrutura e CI/CD  
- **Patinho Rosinha**: especialista em frontend e UX/UI  
- **Patinho Secretário**: especialista em organização de código e documentação  

(Durante a live, rimos bastante ao adicionar o **Patinho Cansado**, nosso consultor para problemas de performance 😅)

---

## 🎨 Melhorando o Layout com Copilot

O site já estava funcional e fofo, mas queria deixá-lo ainda mais bonito. Com alguns prompts para o Copilot, ele aplicou melhorias como:

- Layout em grid com três colunas
- Estilização dos cards com efeitos de *hover*
- Padronização de cores e espaçamentos

---

## 🔄 Separação de Dados e Interface

Para melhorar a organização do projeto, separamos os dados do conteúdo HTML:

- Criamos um arquivo `patinhos.js` que funciona como um pequeno "banco de dados"
- Usamos `export default` para modularizar
- Atualizamos o HTML para carregar os cards dinamicamente com JavaScript

---

## 📚 Documentação do Projeto

Queríamos facilitar futuras contribuições, então pedi para o Copilot ajudar com a documentação:

- Criamos um `documentacao.md` com explicações técnicas detalhadas
- Elaboramos um `README.md` profissional para o GitHub
- Adicionamos comentários explicativos no código

---

## ✅ Boas Práticas com Copilot

Mesmo sendo uma live descontraída, o Copilot ajudou a manter boas práticas de desenvolvimento web:

- Separação clara entre HTML, CSS e JS
- Arquitetura modular
- Responsividade embutida
- Código bem comentado
- Documentação clara e útil

Criamos um projeto estruturado, escalável e fácil de contribuir — pronto para receber muitos novos patinhos!

---

## ✨ Próximos Passos

Esse projeto começou como uma forma divertida de testar o Copilot ao vivo, mas acabou se tornando algo que quero continuar desenvolvendo.

Tentei procurar uma API de patinhos para expandir o catálogo, mas... não achei nenhuma. Então quem sabe o próximo passo seja criar **nossa própria API de patinhos**, né? 👀

---

💚 O projeto é Open Source!  
Quer contribuir? Adicione seu patinho aqui: [link para o repositório](https://github.com/pachicodes/catalogo-patinhos-dev)

E se quiser ver como tudo isso foi feito ao vivo, me acompanha na [Twitch do GitHub Brasil](https://www.twitch.tv/githubbrasil)!

---

Obrigada por ler até aqui! Me conta nos comentários:  
✨ Que tipo de patinho você adicionaria ao catálogo?
