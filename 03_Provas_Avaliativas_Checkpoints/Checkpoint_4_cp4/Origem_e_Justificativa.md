# Origem e Justificativa do Problema

**Disciplina:** Physical Computing & Microcontrollers
**Ano Letivo:** 2025 | **Turma:** 4ECS
**Avaliação:** Checkpoint 4

### Enunciado do Problema
Calcular a curva de calibração polinomial para compensar a não-linearidade do ADC de 12 bits do ESP32 utilizando as tensões de referência internas eFuse Vref.

### Formulação Formal
$$V_{real} = a \cdot ADC^2 + b \cdot ADC + c, \quad \text{Erro Residual} < 0,5\%$$
