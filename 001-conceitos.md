# Aula 01 - Introdução ao Raciocínio Lógico
**Lógica de Programação Básica - CETAM**
---

## O que vamos aprender hoje?

- O que é lógica e onde usamos ela
- Como organizar ideias para resolver problemas
- Conhecer as ferramentas do curso

---

## Vamos nos conhecer!

### Apresentação dos Alunos

Cada um vai se apresentar dizendo:
- Seu nome
- Por que está fazendo este curso
- Uma coisa que você faz todo dia que precisa pensar

**Exemplos:**
- Escolher que roupa vestir
- Decidir o caminho para a escola
- Fazer um sanduíche

### Perguntas para a turma

1. Quem aqui já mexeu com computador?
2. Quem já jogou videogame ou jogos de celular?
3. Quem já seguiu uma receita ou instruções?
4. O que vocês acham que é "programar"?

---

## O que é Raciocínio Lógico? (45 minutos)

### Conceito Simples

**Raciocínio Lógico** é pensar de forma organizada para resolver problemas.

É como seguir passos para chegar em algum lugar:
- Sair de casa
- Pegar o ônibus
- Descer no ponto certo
- Entrar na escola

### Os 3 Pilares da Lógica

#### 1. SEQUÊNCIA - Ordem dos passos

**Exemplo: Escovar os dentes**
```
1. Pegar a escova
2. Colocar pasta
3. Escovar
4. Enxaguar
```

**Pergunta:** E se a gente escovar ANTES de colocar a pasta? Funciona?

#### 2. CONDIÇÃO - Se isso, então aquilo

**Exemplo: Sair de casa**
```
SE está chovendo
ENTÃO levo guarda-chuva

SE está sol
ENTÃO levo boné
```

**Pergunta:** Vocês fazem isso? Que outras decisões vocês tomam assim?

#### 3. REPETIÇÃO - Fazer de novo até terminar

**Exemplo: Lavar louça**
```
ENQUANTO tiver louça suja:
    Pegar um prato
    Lavar
    Secar
```

**Pergunta:** Que outras coisas a gente repete até acabar?

### Atividade Rápida

**Desafio:** Coloque na ordem certa para fazer um suco:

- ( ) Servir no copo
- ( ) Pegar a jarra
- ( ) Misturar com a colher
- ( ) Colocar água
- ( ) Colocar o pó do suco

---

## Abstração: Simplificando as Coisas (45 minutos)

### O que é Abstração?

**Abstração** é simplificar algo complicado, pegando só o importante.

### Exemplo 1: Indo para a escola

**Versão MUITO detalhada:**
```
1. Acordar
2. Desligar o despertador
3. Sentar na cama
4. Levantar
5. Ir ao banheiro
6. Abrir a torneira
7. Pegar a escova
8. Colocar pasta
9. Escovar dente de cima
10. Escovar dente de baixo
... (mais 30 passos)
40. Entrar na escola
```

**Versão SIMPLES (abstraída):**
```
1. Acordar e me arrumar
2. Tomar café
3. Ir para a escola
```

### Exemplo 2: Fazer um sanduíche

**Detalhado:**
- Abrir a geladeira
- Pegar o queijo
- Fechar a geladeira
- Abrir o armário
- Pegar o pão
- Fechar o armário
- Pegar uma faca
- Abrir o pacote de pão
- Tirar 2 fatias
- Colocar no prato
- Cortar o queijo
- Colocar no pão
- Juntar os pães

**Simplificado:**
- Pegar os ingredientes
- Montar o sanduíche
- Comer

### Por que isso importa?

Na programação, a gente não escreve TUDO detalhado. A gente simplifica para:
- Ficar mais fácil de entender
- Não confundir
- Resolver problemas grandes

### Atividade em Dupla

**Desafio:** Escolha uma dessas atividades e escreva de forma SIMPLES (máximo 5 passos):

1. Tomar banho
2. Fazer o dever de casa
3. Fazer arroz
4. Jogar futebol

**Apresentem para a turma!**

---

## Lógica no Dia a Dia 

### Discussão em Grupo

**Dividir a turma em 4 grupos**

**Tarefa:** Cada grupo vai escolher uma situação e explicar:
1. Qual é a situação?
2. Que passos você segue?
3. Tem decisões (SE/ENTÃO)?
4. Tem repetições?

**Situações para escolher:**
- Usar o celular (desbloquear, abrir app, usar)
- Comprar algo na cantina
- Atravessar a rua
- Jogar um jogo

**Tempo:** 15 minutos para discutir + 15 minutos apresentar

### Exemplo: Comprar Lanche

```
1. Escolher o que quero

2. SE tenho dinheiro ENTÃO
   - Ir até a cantina
   SENÃO
   - Voltar para casa
   
3. Pedir o lanche

4. SE o preço está certo ENTÃO
   - Pagar
   SENÃO
   - Reclamar
   
5. Pegar o lanche

6. Comer
```

---

## Conhecendo as Ferramentas 
### O que vamos usar no curso?

Vamos usar 2 programas para aprender lógica:

### 1. VisualG

**O que é?**
- Programa para escrever algoritmos em português
- É mais simples e direto
- Perfeito para começar

**Exemplo de código:**
```
algoritmo "ola"
var
   nome: caractere
inicio
   escreva("Qual seu nome? ")
   leia(nome)
   escreva("Olá, ", nome, "!")
fimalgoritmo
```

### 2. Portugol Studio

**O que é?**
- Programa mais moderno
- Também em português
- Tem mais recursos (cores, desenhos)

**Exemplo de código:**
```
programa {
  funcao inicio() {
    cadeia nome
    escreva("Qual seu nome? ")
    leia(nome)
    escreva("Olá, ", nome, "!")
  }
}
```

### Qual usar?

- **Começo do curso:** VisualG (mais simples)
- **Depois:** Portugol Studio (mais recursos)


---

## Vamos Praticar!

### Exercícios de Raciocínio Lógico

#### Exercício 1: Sequências

Complete as sequências:

**a)** 2, 4, 6, 8, __, __, __

**b)** 10, 20, 30, 40, __, __, __

**c)** 5, 10, 15, 20, __, __, __

#### Exercício 2: Ordem Lógica

Coloque os passos na ordem certa para **fazer um bolo**:

- ( ) Colocar no forno
- ( ) Misturar tudo
- ( ) Pegar os ingredientes
- ( ) Esperar assar
- ( ) Comer o bolo

#### Exercício 3: Decisões

Complete com SE e ENTÃO:

**a)** ___ está frio ___ uso casaco

**b)** ___ tenho fome ___ como alguma coisa

**c)** ___ o sinal está verde ___ atravesso a rua

#### Exercício 4: Problema Simples

**Situação:** João tem 10 reais. O lanche custa 8 reais.

**Perguntas:**
1. João pode comprar o lanche?
2. Quanto vai sobrar?
3. Se o lanche custasse 12 reais, ele poderia comprar?

#### Exercício 5: Desafio em Grupo

**Desafio:** Criar os passos para um robô fazer um sanduíche.

Lembre-se:
- O robô não sabe NADA
- Você precisa explicar TUDO
- Use passos simples e claros

**Exemplo:**
```
1. Ir até a geladeira
2. Abrir a porta
3. Pegar o queijo
...
```

---

## O que aprendemos hoje?

- Lógica é pensar de forma organizada
- Existem 3 pilares: Sequência, Condição e Repetição
- Abstração é simplificar coisas complicadas
- Usamos lógica TODO DIA sem perceber
- Vamos usar VisualG e Portugol Studio no curso

---

## Para Casa (Opcional)

Escolha UMA atividade:

1. **Escreva os passos** para uma coisa que você faz todo dia (acordar, ir para escola, fazer comida)

2. **Observe uma pessoa** fazendo alguma coisa e anote os passos que ela faz

3. **Pense em 3 decisões** que você toma todo dia usando SE/ENTÃO

**Traga na próxima aula para compartilhar!**

---

**Até a próxima! 👋**
