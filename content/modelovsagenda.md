---
date: 2025-04-21
tag: IA, copilot

---

# Modelos de IA vs. Agentes de IA no GitHub Copilot

Você já deve ter lido vários artigos falando sobre como a Inteligência Artificial está avançando rapidamente, né? Dá até medo!  
Mas hoje vm falar sobre como o **GitHub Copilot** exemplifica essa mudança ao combinar **modelos de IA** e **agentes de IA** para oferecer suporte prático no dia a dia de quem programa.  

Mas qual a diferença entre esses conceitos? E como cada um pode impactar sua experiência de programação?

---

## 1. Modelos de IA (LLMs – *Large Language Models*)

Os modelos de IA são a espinha dorsal do Copilot, funcionando como um "assistente" capaz de compreender e gerar código. Seu poder vem da sua gradne base de conhecimento sobre programação, treinada para responder a comandos específicos.

**Características:**
- Conhecimento estático baseado em dados pré-treinados  
- Capacidade de interpretar linguagem natural e código  
- Geração de respostas com base em padrões aprendidos  
- Trabalha apenas com o contexto imediato fornecido  
- Atua de forma passiva, esperando comandos do usuário  

**Exemplo prático:**  
Se você perguntar *"Como fazer um loop em Python?"*, o modelo responderá com uma explicação e um exemplo de código – mas **não executará nenhuma ação** no ambiente de desenvolvimento.

---

## 2. Agentes de IA – A Evolução do Copilot

Os agentes de IA vão além do conhecimento passivo e adicionam **capacidade de ação e tomada de decisão**. Eles podem interagir diretamente com o código, modificar arquivos e até automatizar tarefas de desenvolvimento.

**O que um agente pode fazer?**
- Executar ações reais dentro do ambiente de programação  
- Reter memória do contexto ao longo da interação  
- Tomar decisões autônomas baseadas no objetivo do usuário  
- Modificar, organizar e testar código dentro do projeto  
- Ser proativo ao sugerir soluções e melhorias  

---

## 3. Comparação Prática – Criando uma API REST

Vou abrir meu VSCode e usar o seguinte prompt:  
**"Vamos criar uma API REST."**  
Pode testar aí também!

### Usando um Modelo de IA:
No Copilot Chat, escolhemos a opção **"Perguntar"**.

![copilot com perguntar](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/jvurc04jdcb4jhxutcpx.png)
**O que o modelo traz como resposta?**
- Explica o conceito de API REST  
- Fornece exemplos de código  
- Sugere uma estrutura de arquivos  

Mas **não implementa** nada diretamente.

Agora vamos trocar para um agente e ver como o comportamento muda:

![agente copilpt](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/2a71y8ixa2u36969526t.png)
### Usando um Agente de IA:

- Analisa o ambiente de desenvolvimento  
- Cria a estrutura de diretórios  
- Inicializa um projeto configurado corretamente  
- Instala dependências  
- Gera código funcional automaticamente  
- Executa testes iniciais para validar a implementação  

---

## 4. Quando Usar Cada Um?

**Modelos de IA** são ideais quando você precisa de:
- Explicações conceituais  
- Exemplos de código  
- Esclarecimento sobre sintaxe  
- Entender padrões de projeto  
- Revisar conceitos  

**Agentes de IA** são úteis quando é hora de:
- Implementar funcionalidades completas  
- Automatizar tarefas repetitivas  
- Configurar ambientes de desenvolvimento  
- Resolver bugs  
- Refatorar código  
- Integrar diferentes tecnologias  

A grande força do Copilot está na **integração de ambas as abordagens**:  
Modelos de IA oferecem conhecimento e contexto, enquanto os agentes de IA **executam ações práticas** dentro do seu fluxo de trabalho.

---

## 5. Dicas para Melhor Aproveitamento

Para extrair o máximo do GitHub Copilot:

- ✏️ **Especifique claramente seus prompts** – comandos vagos geram respostas imprecisas  
- 📌 **Forneça contexto adicional** – quanto mais detalhes, melhor o resultado  
- 🧠 **Aproveite a memória do agente** – deixe que ele acompanhe seu progresso  
- 🧐 **Valide as sugestões** – sempre revise o código gerado pela IA  
- 🔄 **Experimente diferentes abordagens** – combinar modelos e agentes pode otimizar seu fluxo de trabalho  

---

A IA não veio para substituir pessoas desenvolvedoras, mas para **potencializar nossa criatividade e eficiência** na programação.  
Aprender engenharia de prompts e entender como cada tecnologia funciona só vai te ajudar a usar ferramentas que **realmente impulsionam seu trabalho**. 💚