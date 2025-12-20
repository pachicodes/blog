---
title: "Adicionando Visuais no seu Markdown com Mermaid 🧜‍♀️"
date: "2025-07-21"
description: "Aprenda a criar diagramas profissionais direto no Markdown com Mermaid. Descubra como adicionar fluxogramas, gráficos e visuais interativos à sua documentação no GitHub sem ferramentas externas."
tags: ["GitHub", "Open Source", "DevRel"]
---

# Adicionando Visuais no seu Markdown com Mermaid 🧜‍♀️

Se a ideia de adicionar diagramas  à sua documentação em Markdown no GitHub (ou em qualquer outra plataforma) parece uma tarefa chata, você precisa conhecer o Mermaid! Com ele, você cria visuais profissionais diretamente no seu arquivo de texto.

Recentemente, lancei um projeto Open Source chamado [DevRel Roadmap](https://www.google.com/search?q=https://github.com/cami-la/devrel-roadmap), que reúne conteúdos educacionais sobre Developer Relations. Como a proposta é ensinar e orientar pessoas desenvolvedoras que querem entrar ou avançar na área, eu precisava de uma maneira leve, prática e bonita de organizar visualmente as informações. Foi exatamente aí que o Mermaid entrou na história.

![diagrama roadmap devrel](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lq6yuabx4vtbgblt3jz2.png)


----------

## Mas afinal, o que é Mermaid?

Mermaid é uma linguagem de marcação baseada em Markdown que transforma simples blocos de texto em diagramas visuais, direto no navegador. Ele funciona de maneira parecida com Markdown: você escreve alguns comandos fáceis de entender, e o Mermaid transforma automaticamente esse texto em gráficos visuais que facilitam muito a compreensão.

Desde diagramas de fluxo, sequência, Gantt, classes até gráficos de pizza, o Mermaid interpreta esses comandos e gera visuais limpos e intuitivos, tudo dentro do seu navegador ou plataforma de código.

Por exemplo, algo simples como isso:



 ```

graph  TD

A[Começar  com  DevRel]  -->  B[Fundamentos]

A  -->  C[Comunicação]

B  -->  D[Técnico]

B  -->  E[Soft  Skills]

  ```

Automaticamente se torna um gráfico bonito e dinâmico, perfeitamente integrado ao seu arquivo Markdown.

----------

## Por que adotar o Mermaid no seu projeto?

Uma das grandes vantagens do Mermaid é a facilidade de uso e a integração natural que ele oferece. Vamos explorar os principais benefícios:

### Integração nativa e facilidade de atualização

Você não precisa sair do arquivo Markdown que já está usando para sua documentação. Essa integração significa que você atualiza os gráficos diretamente no próprio texto, evitando a fragmentação de ferramentas e fluxos de trabalho interrompidos. Diga adeus à necessidade de recriar imagens estáticas a cada pequena mudança!

### Visualização direta em plataformas populares

Plataformas amplamente utilizadas como GitHub já possuem suporte nativo ao Mermaid. Isso quer dizer que você pode visualizar esses diagramas diretamente no navegador, sem precisar instalar nada extra, tanto para quem cria quanto para quem visualiza.

### Versatilidade para diagramas complexos

Tudo isso facilita a criação e manutenção de diagramas complexos como roadmaps de produto, arquitetura de software, fluxogramas de decisão, processos de integração (onboarding), planejamento de projetos e até guias de contribuição open source.

----------

## Sugestões práticas para você começar a usar Mermaid

O Mermaid pode ser especialmente útil em contextos educacionais e técnicos, como acontece no [DevRel Roadmap](https://www.google.com/search?q=https://github.com/cami-la/devrel-roadmap).

### Casos de Uso Reais

No DevRel Roadmap, por exemplo, usei diagramas para explicar as conexões entre as principais competências necessárias para pessoas desenvolvedoras que trabalham com Developer Relations. Isso inclui soft skills, comunicação, habilidades técnicas, estratégias de engajamento, comunidade e muito mais. Um diagrama visual torna essas relações bem mais claras do que longas descrições em texto corrido.

Outras ótimas aplicações incluem:
-   Documentação de API: Ilustrar o fluxo de requisição/resposta entre serviços.
-   Onboarding de Desenvolvedores: Guiar novos membros da equipe através dos primeiros passos com diagramas de sequência.    
-   Decisões de Arquitetura: Representar componentes do sistema e suas dependências.    
-   Tutoriais de Código: Explicar o fluxo lógico de algoritmos complexos.
    

Afinal, uma imagem realmente pode valer mais do que mil palavras — especialmente quando essa imagem é gerada automaticamente com texto simples e fácil de editar.

### Como Começar na Prática

Para começar, basta abrir um arquivo Markdown, criar um bloco de código e adicionar a palavra-chave mermaid logo após as três aspas invertidas. Em seguida, escreva o conteúdo do seu diagrama seguindo a [Documentação Oficial do Mermaid](https://mermaid.js.org/). O diagrama já fica pronto para ser visualizado no GitHub!

Experimente, explore a [Documentação Oficial do Mermaid](https://mermaid.js.org/) e, para inspiração real, confira como aplicamos esses conceitos no [DevRel Roadmap](https://www.google.com/search?q=https://github.com/cami-la/devrel-roadmap).

Quanto mais acessível e visual for seu conteúdo, maior será o engajamento e a contribuição da sua comunidade. 🧜‍♀️✨
