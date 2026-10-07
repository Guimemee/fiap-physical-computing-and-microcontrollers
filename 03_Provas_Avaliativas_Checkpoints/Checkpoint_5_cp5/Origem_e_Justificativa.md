# Origem e Justificativa do Problema

**Disciplina:** Physical Computing & Microcontrollers
**Ano Letivo:** 2025 | **Turma:** 4ECS
**Avaliação:** Checkpoint 5

### Enunciado do Problema
Desenvolver aplicação multitarefa preemptiva no FreeRTOS com xTaskCreatePinnedToCore() distribuindo tarefas de controle crítico no Core 0 e conectividade Wi-Fi no Core 1 com filas de mensagens (Queues) e semáforos binários.

### Formulação Formal
$$\text{Core 0 (Controle)}: \text{TaskPID (Prioridade 5)}, \quad \text{Core 1 (Rede)}: \text{TaskMQTT (Prioridade 2)}$$
