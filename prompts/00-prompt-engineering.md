# 🧠 Conceitos de Prompt Engineering

## O que é Prompt Engineering?

Prompt Engineering é a arte/ciência de criar mensagens claras e eficazes para ferramentas de IA, extraindo o máximo de qualidade e precisão das respostas.

## 🎯 Regras de Ouro para Prompts Profissionais

### 1. **Seja Específico**
❌ **Prompt Fraco:** "Discuta sobre engenharia civil"
✅ **Prompt Forte:** "Descreva os desafios enfrentados na construção de pontes suspensas e forneça exemplos de soluções inovadoras"

### 2. **Forneça Contexto Adequado**
❌ **Prompt Fraco:** "Projete um novo sistema de abastecimento de água"
✅ **Prompt Forte:** "Você foi contratado para projetar um sistema de abastecimento de água em uma área rural com pouca infraestrutura existente. Considere as limitações orçamentárias e ambientais ao propor uma solução sustentável"

### 3. **Estimule Aplicação Prática**
❌ **Prompt Fraco:** "Me explique as leis da termodinâmica"
✅ **Prompt Forte:** "Você está projetando um sistema de refrigeração para um data center. Descreva as leis da termodinâmica relevantes para esse projeto e como elas podem ser aplicadas para maximizar a eficiência energética"

### 4. **Comunique-se Claramente**
❌ **Prompt Fraco:** "ebook, CSS, seis páginas"
✅ **Prompt Forte:** "Crie um ebook de CSS com 6 páginas que aborde os fundamentos da linguagem, com exemplos práticos para iniciantes em web design"

## 🚫 Conceitos Avançados

### **Prompts Negativos**
Use para definir o que você NÃO quer:
```
## REGRAS NEGATIVAS:
- Não use palavras em inglês
- Não seja muito técnico  
- Não ultrapasse 5 minutos
```

### **Passagem de Variáveis**
Crie templates reutilizáveis:
```
Olá [NOME], como posso ajudar hoje?

REGRAS:
- Substitua [NOME] por um nome aleatório feminino
```

### **Patterns de Prompt**
Estrutura padrão para consistência:
```
CONTEXTO: Você é um [PAPEL]
OBJETIVO: Criar [O_QUE]
FORMATO: [COMO_ESTRUTURAR]
REGRAS: [O_QUE_INCLUIR]
REGRAS NEGATIVAS: [O_QUE_EVITAR]
```

## 📝 Template Universal de Prompt

```
Você é um [PAPEL/ESPECIALISTA] e precisa [OBJETIVO_PRINCIPAL].

CONTEXTO:
[Descreva a situação, cenário, público-alvo]

TAREFA:
[O que exatamente você quer que a IA faça]

FORMATO:
[Como você quer que a resposta seja estruturada]

REGRAS:
- [Primeira regra importante]
- [Segunda regra importante]
- [Terceira regra importante]

REGRAS NEGATIVAS:
- Não [primeira coisa a evitar]
- Não [segunda coisa a evitar]
- Evite [terceira coisa a evitar]

EXEMPLO: [Se necessário, forneça um exemplo]
```

## 🎪 Aplicação nos Nossos Prompts

### Nome do Podcast:
- ✅ **Contexto:** "Você é um roteirista de podcast..."
- ✅ **Específico:** "...focado em front-end"
- ✅ **Aplicação:** "...para construir autoridade técnica"
- ✅ **Negativas:** "Não use palavras em inglês"

### Arte Midjourney:
- ✅ **Específico:** Detalhes visuais precisos
- ✅ **Contexto:** Parâmetros técnicos
- ✅ **Qualidade:** Adjetivos de alta qualidade

### Roteiro:
- ✅ **Estrutura:** Formato com variáveis
- ✅ **Contexto:** Público-alvo e duração
- ✅ **Aplicação:** Exemplo de apresentação
- ✅ **Negativas:** Evitar termos técnicos
