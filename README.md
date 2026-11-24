# Plano de Estudos — Target-Q, Uniamérica & PUC Minas

Painel interativo em página única (`index.html`) para gerenciar **864 horas** de estudo distribuídas em **26 semanas** (segunda a sábado, 6h líquidas/dia, com domingos livres), integrando **Dashboard**, **Foco de Hoje**, **Kanban**, **To-Do** e **Cronograma dinâmico**.

**Site publicado:** https://dekomao.github.io/plano-estudos/

---

## Cursos e Ordem de Prioridade

| Prioridade | Programa | Carga Horária | Estrutura | Prazo do Curso |
| :--- | :--- | :---: | :--- | :---: |
| **1º** | **Combo Qualidade Automotiva (TARGET-Q)** | 144h | 9 cursos (Core Tools, Novo FMEA AIAG & VDA e Auditor Interno IATF-16949:2016) | 180 dias |
| **2º** | **Pós-Graduação em Data Science (Uniamérica Descomplica)** | 360h | 3 módulos (12 disciplinas de 30h) + Prova Objetiva, Estudo de Caso e Pitch | 6 meses |
| **3º** | **Pós-Graduação em Engenharia de Qualidade e Teste de Software (PUC Minas)** | 360h | 15 disciplinas de 24h + TCC opcional | 2 anos |

---

## Estratégia e Rotina Diária

- **Bloco A (08h30 – 10h30 · 2h):** Conteúdo principal da prioridade ativa.
- **Bloco B (11h00 – 13h00 · 2h):** Prática, planilhas (FMEA/MSA), scripts em Python ou labs de testes.
- **Bloco C (14h30 – 16h30 · 2h):** Frente secundária em paralelo e avaliações de módulo.

### Divisão em 3 Fases
1. **Fase 1 (24h/sem Target-Q + 12h/sem Uniamérica):** Conclui os 9 treinamentos da Target-Q (nota mínima 70%) e avança no Módulo 1 de Data Science.
2. **Fase 2 (30h/sem Uniamérica + 6h/sem PUC Minas):** Finaliza os 3 módulos de Data Science e entregas finais, enquanto inicia a PUC Minas.
3. **Fase 3 (36h/sem PUC Minas):** Dedicação integral às disciplinas restantes da PUC Minas até a conclusão das 360h.

---

## Funcionalidades do Painel

- **Dashboard:** Indicadores em tempo real de horas concluídas, módulos finalizados, dias estudados e gráfico interativo de progresso por curso.
- **Calendário de Estudos:** Marcação diária (check) em dias úteis (segunda a sábado) com destaque para a data de início e folgas.
- **Ajuste de Cronograma:** Recalcula automaticamente todas as datas das 36 disciplinas ao alterar a data de início ou registrar dias/semanas perdidas (`+1 dia`, `+1 semana`).
- **Foco de Hoje:** Exibe os 3 blocos diários, os módulos em andamento e os próximos da fila.
- **Kanban:** Colunas *A Fazer*, *Em Andamento* e *Concluído* com arrastar e soltar, filtros por curso e botões rápidos.
- **To-Do:** Checklist agrupado por programa, busca por nome e criação de tarefas extras personalizadas.
- **Persistência e Backup:** Salvamento automático no navegador (`localStorage`) e exportação de backup via **Exportar JSON**.

---

## Tecnologias

- **HTML5** autocontido (`index.html`)
- **Tailwind CSS** (via CDN)
- **Chart.js** (via CDN)
- **JavaScript** puro (sem backend ou build)
- **GitHub Pages** para hospedagem estática
