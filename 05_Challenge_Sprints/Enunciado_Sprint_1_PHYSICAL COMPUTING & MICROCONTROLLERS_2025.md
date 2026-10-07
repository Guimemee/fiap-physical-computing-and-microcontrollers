# Challenge Sprint 1 - PHYSICAL COMPUTING & MICROCONTROLLERS

**Título do Challenge:** SPI / METAINDÚSTRIA - SMART ROBOTICS
**Turma:** 4ECS | **Ano:** 2025
**Período para Entrega:** 09/05/2025 - 18/06/2025
**Status:** NOTA: 100
**Cabeçalho Original:** PHYSICAL COMPUTING & MICROCONTROLLERS - Sandro Aparecido Ferraz NOTA: 100

## 1. Enunciado e Instruções do Professor

Caros alunos. Tudo bem?

Nesta primeira etapa, peço que vocês entreguem:

**Parte 1:** Montem um pitch em formato de vídeo de 3 minutos (no máximo). Este vídeo deve conter:

* Breve apresentação da proposta do projeto;
* Cronograma das etapas a serem desenvolvidas, bem como o nome dos alunos responsáveis (levem em conta especificação do hardware e outros componentes eletro/eletrônicos);
* O grupo deverá também montar um diagrama de blocos da solução proposta (ilustre com diagramas, desenhos, esquemas elétricos etc.);
* Breve descrição do software e hardware (braço robótico) a ser desenvolvido no projeto;
O vídeo deve ser colocado no **Youtube** e o link deve ser postado em arquivo aqui.

**Atenção: **Só será aceito o vídeo e não outra forma de documentação (pdf, docx etc.).

Obs.: A entrega é exclusivamente feita em entrega dos Sprints, qualquer outra forma de envio será desconsiderada! Assim, atenção com os prazos!!!!

Neste item a nota será exclusivamente a dada pela empresa (SPI).

 

**Parte 2:** **Projeto de controle de motor de passo** usando Ahmes:

**1. Objetivo do Projeto**

Criar um sistema para controle de um motor de passo utilizando um microcontrolador programado em linguagem Ahmes. O sistema permitirá o controle da direção e velocidade do motor, podendo ser utilizado em automação ou robótica.

**2. Funcionamento**

* O sistema deve permitir **controle do sentido** do motor (horário e anti-horário).
* O microcontrolador (simulador) enviará sinais aos pinos de saída para alternar a ativação das bobinas do motor.
**3. Fluxo do Programa**

* **Configuração**: Inicialização dos registradores e configuração dos pinos.
* **Leitura dos botões**: O sistema verifica os estados dos botões para definir direção e velocidade.
* **Controle das bobinas**: O código ativa cada bobina de acordo com a sequência necessária para o funcionamento do motor.
* **Loop principal**: Repete o ciclo de ativação das bobinas enquanto aguarda novas entradas do usuário.
**4. Código em Ahmes (Sugestão)**

O código pode incluir:

* Definição dos pinos como saída (TRISB).
* Controle das bobinas com um loop baseado em MOVWF PORTB e delays para ajuste da velocidade.
* Leitura de entrada para definir o sentido do motor.
 

Essa nota será exclusivamente avaliada pelo Professor.

 

A nota desta Sprint será a média das duas notas: (**Nota da parte 1** + **Nota da parte 2**) / **2**

 

Att.

Prof. Sandro

