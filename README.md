# 🤖 Arduino e Eletrônica Básica com NotebookLM

> Um caderno temático desenvolvido para consolidar conhecimentos em Arduino, Eletrônica Básica e Sistemas Embarcados, utilizando Inteligência Artificial como ferramenta de aprendizagem ativa.

![Projeto](https://img.shields.io/badge/Projeto-DIO-blue)
![NotebookLM](https://img.shields.io/badge/NotebookLM-Google-orange)
![Arduino](https://img.shields.io/badge/Arduino-00979D?logo=arduino&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-success)

---

## 📌 Índice

- [📖 Contexto](#-contexto)
- [🎯 Objetivos](#-objetivos)
- [📚 Curadoria de Fontes](#-curadoria-de-fontes)
- [🔗 Acesso ao NotebookLM](#-acesso-ao-notebooklm)
- [🧠 Engenharia de Prompts e Cicatrizes](#-engenharia-de-prompts-e-cicatrizes)
- [📘 Miniguia de Estudos](#-miniguia-de-estudos)
- [💡 Conclusão](#-conclusão)
- [👨‍💻 Autor](#-autor)

---

# 📖 Contexto

Este projeto foi desenvolvido como parte do desafio Criando um Caderno Temático com NotebookLM da Digital Innovation One (DIO).

O objetivo foi explorar como uma ferramenta de estudos baseada em Inteligência Artificial pode auxiliar no aprendizado, utilizando diversas fontes confiáveis para produzir resumos, glossários e materiais de revisão sobre Arduino e Eletrônica Básica.

Além da geração de conteúdo, este projeto documenta todo o processo de Engenharia de Prompts, registrando os testes realizados, dificuldades encontradas e estratégias utilizadas para obter respostas mais completas e precisas.

---

# 🎯 Objetivos

Este caderno temático foi criado para:

- Revisar os fundamentos da eletrônica básica;
- Estudar a arquitetura da plataforma Arduino;
- Consolidar conceitos de programação embarcada;
- Produzir um material de consulta rápida para estudos futuros;
- Experimentar técnicas de Engenharia de Prompts utilizando IA;
- Demonstrar um fluxo de aprendizagem utilizando NotebookLM.

---

# 📚 Curadoria de Fontes

Foram utilizadas quatro referências abertas, adicionadas ao NotebookLM para servir como base das respostas geradas pela IA.

### Materiais utilizados

- [Apostila Arduino Básico - Eletrogate](https://conteudo.eletrogate.com/apostila-arduino-iniciante)

- [Embedded Controllers Using C and Arduino - Lab Manual](https://milneopentextbooks.org/embedded-controllers-using-c-and-arduino-lab-manual/)

- [Apostila Curso Básico de Arduino - UNIR](https://marcopolo.unir.br/images/downloads/material-extensao/apostila-curso-basico-de-arduino.pdf)

- [Apostila de Eletrônica Básica - CTA Eletrônica](https://www.ctaeletronica.com.br/wp-content/uploads/2019/05/ApostilaM1.pdf)

---

# 🔗 Acesso ao NotebookLM

[🔗 Arduino e Eletrônica Aplicada](https://notebook.google.com/notebook/4732c75c-9754-4810-a67e-e5b27ceb96f2)

---

# 🧠 Engenharia de Prompts e Cicatrizes

Durante o desenvolvimento do projeto foram realizados diversos testes para compreender como pequenas mudanças na forma de perguntar influenciam diretamente na qualidade das respostas produzidas pelo NotebookLM.

## Prompt 1

### Objetivo

Entender o funcionamento da plataforma Arduino.

### Prompt inicial

> O que é Arduino?

### Resultado

O NotebookLM apresentou uma resposta completa, explicando que o Arduino é uma plataforma de prototipagem eletrônica de código aberto, descrevendo sua origem, os componentes de hardware, o ambiente de desenvolvimento (IDE), a linguagem baseada em C/C++ e algumas aplicações práticas.

### Problema

Embora a resposta estivesse correta e bem estruturada, ela abordava diversos assuntos ao mesmo tempo (história, hardware, software e aplicações), dificultando um estudo mais aprofundado de cada tópico individualmente.

### Prompt refinado

> Explique o que é o Arduino considerando separadamente: arquitetura da placa, funcionamento do microcontrolador, ambiente de desenvolvimento (IDE), linguagem de programação, principais aplicações, vantagens e limitações.

### Resultado final

A resposta ficou organizada em tópicos, permitindo identificar facilmente cada aspecto da plataforma Arduino. A estrutura facilitou a compreensão dos conceitos, a localização das informações e a utilização do conteúdo como material de revisão.

---

## Prompt 2

### Objetivo

Compreender o funcionamento do PWM.

### Prompt inicial

> Explique PWM.

### Resultado

O NotebookLM apresentou uma explicação detalhada sobre o PWM, abordando seu funcionamento, o conceito de Duty Cycle, tensão média, frequência, a função `analogWrite()`, os pinos compatíveis do Arduino Uno e suas principais aplicações.

### Problema

Embora a resposta fosse tecnicamente correta e completa, ela estava focada na descrição do conceito. Para fins de estudo, seria interessante incluir uma estrutura mais didática, com exemplos práticos e uma comparação entre diferentes valores de Duty Cycle.

### Prompt refinado

> Explique o funcionamento do PWM considerando definição, frequência, Duty Cycle, aplicações, limitações e um exemplo utilizando Arduino.

### Resultado final

A resposta passou a ser organizada por tópicos, abordando cada conceito separadamente. Além da explicação sobre frequência e Duty Cycle, o NotebookLM incluiu as principais aplicações do PWM, suas limitações e um exemplo completo em código utilizando a função `analogWrite()`, tornando o conteúdo mais didático e adequado para revisão.

---

## Prompt 3

### Objetivo

Criar um resumo organizado para facilitar a revisão dos principais conceitos estudados.

### Prompt inicial

> Faça um resumo deste capítulo.

### Resultado

O NotebookLM gerou um resumo com os principais tópicos do capítulo, porém em formato de texto contínuo, o que dificultava a localização rápida das informações durante a revisão.

### Problema

Embora o conteúdo estivesse correto, o formato em texto corrido não era o mais adequado para consultas rápidas e comparação entre os conceitos apresentados.

### Prompt refinado

> Produza um resumo estruturado contendo conceitos principais, aplicações, exemplos práticos, curiosidades e pontos importantes para revisão.

### Resultado final

O NotebookLM organizou o conteúdo em uma tabela, permitindo visualizar rapidamente cada conceito, sua descrição e um exemplo de aplicação. Essa estrutura tornou o material mais prático para revisão e consulta, facilitando a comparação entre os assuntos estudados.

---

## Dificuldades Encontradas (Troubleshooting)

Durante os testes, foi possível perceber que a qualidade das respostas está diretamente relacionada à clareza e ao nível de detalhamento dos prompts. As principais dificuldades encontradas foram:

| Dificuldade | Solução adotada |
|-------------|-----------------|
| As respostas iniciais apresentavam diversos conceitos em um único texto, dificultando a compreensão de cada assunto. | Refinar os prompts solicitando que o conteúdo fosse organizado por tópicos específicos, como arquitetura, funcionamento, aplicações e limitações. |
| Algumas respostas eram completas, mas pouco práticas para consulta rápida durante os estudos. | Solicitar que a IA estruturasse as informações em seções bem definidas, facilitando a leitura e a revisão do conteúdo. |
| Os resumos gerados em texto corrido dificultavam a comparação entre os principais conceitos. | Refinar o prompt para que a saída fosse apresentada em formato de tabela, tornando o material mais organizado e fácil de consultar. |
| O formato da resposta influenciava diretamente a utilidade do material para estudo. | Passar a definir explicitamente o formato desejado da saída (tópicos, tabelas e exemplos), obtendo respostas mais adequadas para revisão. |

### Lições Aprendidas

A experiência demonstrou que pequenas alterações na forma de elaborar um prompt podem melhorar significativamente a qualidade das respostas geradas. Definir claramente o objetivo da pergunta, o nível de detalhamento esperado e o formato da saída (como tópicos ou tabelas) resultou em materiais mais organizados, completos e úteis para consultas futuras.

---

# 📘 Miniguia de Estudos

Este miniguia reúne os principais conceitos estudados sobre Arduino e Eletrônica Básica a partir das fontes carregadas no NotebookLM. O objetivo é servir como material de consulta rápida e revisão dos conteúdos mais importantes.

---

## Resumos Estruturados

### O que é Arduino?

O Arduino é uma plataforma de prototipagem eletrônica de código aberto (open-source), composta por hardware e software, desenvolvida para facilitar a criação de projetos eletrônicos e sistemas embarcados. Seu uso é amplamente difundido devido ao baixo custo, facilidade de aprendizado e grande comunidade de usuários. Pode ser aplicado em projetos de automação, robótica, monitoramento ambiental, impressoras 3D e Internet das Coisas (IoT).

---

### Arquitetura da Placa Arduino

A placa Arduino Uno é composta por diversos elementos responsáveis pelo funcionamento do sistema:

- **Microcontrolador ATmega328P**: responsável pelo processamento das instruções.
- **14 portas digitais**: utilizadas como entradas ou saídas digitais.
- **6 portas analógicas**: utilizadas para leitura de sensores analógicos.
- **Memória Flash (32 KB)**: armazena o programa.
- **SRAM (2 KB)**: utilizada para variáveis durante a execução.
- **EEPROM (1 KB)**: armazena dados permanentemente.
- **Porta USB**: utilizada para alimentação e comunicação com o computador.
- **Pinos TX/RX**: responsáveis pela comunicação serial.

---

### Microcontrolador

O ATmega328P é o principal componente do Arduino Uno. Ele funciona como o "cérebro" da placa, executando todas as instruções do programa.

Características principais:

- Arquitetura Harvard;
- Processamento RISC;
- Clock de 16 MHz;
- Controle dos pinos através de registradores internos.

---

### Ambiente de Desenvolvimento (IDE)

A Arduino IDE é utilizada para desenvolver e gravar programas na placa.

Principais recursos:

- Escrever o código em C/C++;
- Compilar o programa;
- Enviar o programa para o Arduino;
- Utilizar o Monitor Serial para comunicação e depuração.

---

### Estrutura de um Programa Arduino

Todo programa Arduino possui duas funções obrigatórias:

```cpp
void setup()
{
    // Executado apenas uma vez
}

void loop()
{
    // Executado continuamente
}
```

- **setup()**: realiza as configurações iniciais.
- **loop()**: contém a lógica principal e é executado continuamente.

---

### Entradas e Saídas Digitais

As portas digitais trabalham apenas com dois estados lógicos:

- LOW (0 V)
- HIGH (5 V)

Funções mais utilizadas:

```cpp
pinMode();
digitalWrite();
digitalRead();
```

Aplicações:

- Controle de LEDs;
- Leitura de botões;
- Acionamento de relés;
- Controle de buzzers.

---

### Entradas Analógicas (ADC)

As entradas analógicas permitem ler tensões variáveis provenientes de sensores.

Características:

- Conversão ADC de 10 bits;
- Valores entre 0 e 1023.

Função utilizada:

```cpp
analogRead();
```

Exemplo:

```cpp
analogRead(A0);
```

Aplicação: leitura de potenciômetros e sensores analógicos.

---

### PWM (Pulse Width Modulation)

PWM é uma técnica utilizada para simular uma saída analógica através de um sinal digital.

Características:

- Frequência aproximada de 490 Hz (980 Hz em alguns pinos);
- Controle através do Duty Cycle;
- Escala de 0 a 255 utilizando `analogWrite()`.

Principais aplicações:

- Controle de brilho de LEDs;
- Controle de velocidade de motores DC;
- Controle de temperatura;
- Geração de sons em piezos.

Exemplo:

```cpp
analogWrite(11, 128);
```

Esse comando gera aproximadamente 50% de Duty Cycle no pino 11.

---

### Comunicação Serial

Permite a troca de dados entre o Arduino e o computador.

Principais funções:

```cpp
Serial.begin();
Serial.print();
Serial.println();
Serial.read();
```

É utilizada para:

- Depuração de programas;
- Monitoramento de sensores;
- Comunicação com outros dispositivos.

---

## Glossário

| Termo | Definição |
|--------|-----------|
| Arduino | Plataforma de prototipagem eletrônica de código aberto. |
| Microcontrolador | Circuito responsável pelo processamento do programa. |
| ATmega328P | Microcontrolador utilizado no Arduino Uno. |
| IDE | Ambiente de Desenvolvimento Integrado para criação e envio de programas. |
| Sketch | Nome dado aos programas desenvolvidos para Arduino. |
| GPIO | Pinos configuráveis como entrada ou saída digital. |
| ADC | Conversor Analógico-Digital que converte tensão em valores numéricos. |
| PWM | Técnica para simular uma saída analógica utilizando pulsos digitais. |
| Duty Cycle | Percentual do tempo em que o sinal PWM permanece em nível alto. |
| Flash | Memória onde o programa é armazenado. |
| SRAM | Memória utilizada durante a execução do programa. |
| EEPROM | Memória permanente utilizada para armazenar pequenos dados. |
| UART | Interface utilizada para comunicação serial. |
| Protoboard | Placa utilizada para montagem de circuitos sem solda. |

---

## Prompts Reutilizáveis

### Explicação de Conceitos

```text
Explique este conceito utilizando linguagem simples, destacando definição, funcionamento, aplicações, vantagens e limitações.
```

### Resumo Estruturado

```text
Faça um resumo estruturado deste capítulo destacando os conceitos mais importantes e suas aplicações práticas.
```

### Resumo em Tabela

```text
Apresente um resumo deste conteúdo em formato de tabela contendo as colunas Conceito, Descrição e Exemplo.
```

### Revisão Rápida

```text
Crie um roteiro de revisão para estudar este conteúdo em aproximadamente 15 minutos.
```

### Comparação

```text
Compare este conceito com outro semelhante, destacando diferenças, vantagens, limitações e aplicações.
```

### Projeto Prático

```text
Sugira um projeto prático utilizando apenas os componentes e conceitos apresentados nas fontes adicionadas.
```
---

# 💡 Conclusão

O desenvolvimento deste caderno temático permitiu compreender como o **NotebookLM** pode ser utilizado como uma ferramenta de apoio ao aprendizado, indo além da simples geração de respostas. Ao reunir diferentes fontes de estudo em um único ambiente, foi possível organizar informações, comparar conceitos e produzir um material de consulta estruturado sobre Arduino e Eletrônica Básica.

Durante a realização do projeto, ficou evidente a importância da **Engenharia de Prompts**. Pequenas mudanças na forma de elaborar as perguntas resultaram em respostas mais organizadas, detalhadas e adequadas ao objetivo de estudo. Solicitar uma estrutura por tópicos, incluir exemplos práticos ou definir formatos específicos, como tabelas, contribuiu significativamente para melhorar a qualidade do conteúdo produzido.

Além de revisar conceitos fundamentais da plataforma Arduino, como arquitetura, microcontrolador, programação, comunicação serial e PWM, este projeto também demonstrou a importância da curadoria de fontes confiáveis e da documentação do processo de aprendizagem.

Como resultado, foi criado um **miniguia de estudos** que poderá ser utilizado em futuras revisões e como material de apoio para o desenvolvimento de novos projetos envolvendo Arduino e sistemas embarcados. A experiência reforçou que a Inteligência Artificial, quando utilizada de forma crítica e com boas estratégias de interação, pode se tornar uma excelente aliada na organização do conhecimento e na aprendizagem contínua.

---

# 👨‍💻 Autor

**Wellington Oliveira**

- LinkedIn: [Wellington Oliveira](https://www.linkedin.com/in/wlwellington3)

---

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório.
