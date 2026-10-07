# Origem e Justificativa do Problema

**Disciplina:** Physical Computing & Microcontrollers
**Ano Letivo:** 2025 | **Turma:** 4ECS
**Avaliação:** Checkpoint 1

### Enunciado do Problema
Configurar e manipular diretamente registradores de GPIO (GPIO_OUT_REG, GPIO_ENABLE_REG) no ESP32 para acionamento de atuadores industriais sem overhead de funções HAL.

### Formulação Formal
$$\text{REG\_WRITE}(\text{GPIO\_OUT\_W1TS\_REG}, 1 \ll \text{PIN}), \quad \text{REG\_WRITE}(\text{GPIO\_OUT\_W1TC\_REG}, 1 \ll \text{PIN})$$
