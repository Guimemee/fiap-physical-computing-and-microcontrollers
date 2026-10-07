# Origem e Justificativa do Problema

**Disciplina:** Physical Computing & Microcontrollers
**Ano Letivo:** 2025 | **Turma:** 4ECS
**Avaliação:** Checkpoint 2

### Enunciado do Problema
Dimensionar o periférico LEDC PWM do ESP32 com resolução de 14 bits na frequência de 5 kHz para controle de velocidade e posicionamento angular suave de atuadores robóticos.

### Formulação Formal
$$f_{PWM} = \frac{f_{clock}}{Prescaler \times 2^{\text{Resolution}}}, \quad 5000 = \frac{80.000.000}{1 \times 2^{14}} = \frac{80.000.000}{16384} \approx 4882,8 \text{ Hz}$$
