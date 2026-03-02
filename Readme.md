## 📌 Objetivo

Script em Python desenvolvido para:

- Ler relatórios de agenda médica em PDF
- Identificar automaticamente cada profissional
- Agrupar os atendimentos por profissional
- Reordenar pacientes pelo número de prontuário
- Gerar planilha Excel estruturada para impressão

O código foi construído com foco em automação de rotinas administrativas.

---

## 🧠 Estratégia de Processamento

### 1️⃣ Leitura do PDF

Utiliza a biblioteca `pdfplumber` para:

- Extrair texto do cabeçalho
- Extrair tabelas estruturadas
- Identificar páginas pertencentes a cada profissional

A separação ocorre pela identificação do marcador textual:

### 2️⃣ Agrupamento por Profissional
O script:

- Percorre todas as páginas
- Mapeia o intervalo de páginas por profissional
- Consolida todas as tabelas em uma única estrutura em memória

Estrutura utilizada:

```python
dict[str, list[list]]
