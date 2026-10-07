# Origem e Justificativa do Problema

**Disciplina:** Physical Computing & Microcontrollers
**Ano Letivo:** 2025 | **Turma:** 4ECS
**Avaliação:** Checkpoint 3

### Enunciado do Problema
Implementar leitor de sensor inercial IMU de 6 eixos (Acelerômetro + Giroscópio) via barramento SPI a 10 MHz com transferência direta por Direct Memory Access (DMA).

### Formulação Formal
$$\text{Taxa SPI} = 10 \text{ MHz}, \quad T_{\text{leitura 14 bytes}} = \frac{14 \times 8}{10 \times 10^6} = 11,2 \, \mu\text{s}$$
