# 📄 PDF Agenda → Excel Estruturado

## 📌 Sobre o Projeto

Script desenvolvido em **Python** para:

- Ler relatório de agenda médica em **PDF**
- Identificar automaticamente os profissionais
- Consolidar atendimentos distribuídos em múltiplas páginas
- Reordenar pacientes por número de prontuário
- Gerar um **Excel formatado para impressão**

Este repositório tem finalidade demonstrativa, com foco na análise da lógica e organização do código.

---

## 🧠 Problema Resolvido

Relatórios de agenda em PDF normalmente:

- Fragmentam profissionais em várias páginas  
- Repetem cabeçalhos  
- Não seguem ordenação consistente  
- Não estão prontos para impressão estruturada  

O script reconstrói a agenda de forma lógica, organizada e paginada.

---

## ⚙️ Principais Funcionalidades

- Extração estruturada de tabelas via `pdfplumber`
- Consolidação automática de páginas por profissional
- Conversão e ordenação por prontuário
- Paginação automática (até 14 pacientes por página)
- Layout configurado para impressão
- Formatação programática via `xlsxwriter`

---

## 📊 Estrutura do Excel Gerado

Cada profissional pode gerar:

- 1 aba (até 14 atendimentos)
- Múltiplas abas (acima de 14 atendimentos)

Colunas organizadas:

- Horário  
- Paciente  
- Data de Nascimento  
- Prontuário  
- Exames  
- Telefone  
- Observação  
- CNS  
- Sequência de Atendimento  

---

## 🏗 Tecnologias Utilizadas

- Python 3  
- pdfplumber  
- xlsxwriter  
- pandas  

---

## 🎯 Competências Demonstradas

- Parsing estruturado de PDF  
- Tratamento de dados inconsistentes  
- Ordenação customizada  
- Geração avançada de Excel com layout profissional  
- Lógica de paginação dinâmica  

---

## 📎 Observação

Não há arquivos de exemplo nem instruções de execução.

O objetivo do repositório é demonstrar organização algorítmica, manipulação de dados e geração automatizada de relatórios.
