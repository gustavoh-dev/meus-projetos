# 🧺 Sistema de Gestão de Lavanderia (Vasconcelos)

Sistema completo de gestão para lavanderias desenvolvido em Python, focado na simplicidade e eficiência operacional. O projeto inclui interface gráfica, banco de dados e geração de documentos fiscais.

## 🚀 Funcionalidades

* **Gestão de Pedidos:** Cadastro completo com nome, CPF, tipo de roupa e valor.
* **Controle de Estados:** Acompanhamento do fluxo (Pendente ➝ Lavando ➝ Pronto ➝ Concluído).
* **Segurança:** Sistema de Login com níveis de acesso (Admin vs Comum).
* **Financeiro:** Dashboard com faturamento total e contagem de pedidos.
* **Documentação:** Geração automática de **Nota Fiscal (DANFE)** e exportação em **PDF**.
* **Dados:** Exportação de relatórios em CSV (Excel).

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **Gradio:** Interface gráfica web amigável.
* **SQLite:** Banco de dados relacional (SQL) para persistência dos dados.
* **PDFKit & wkhtmltopdf:** Motor de renderização de PDFs.
* **HTML/CSS:** Estilização visual dos documentos fiscais.

## 📦 Como Executar

Este projeto foi otimizado para rodar no **Google Colab**, pois utiliza dependências do sistema Linux (`wkhtmltopdf`) para gerar os PDFs.

1. Abra o arquivo `.ipynb` no Google Colab.
2. Execute a primeira célula para instalar as dependências automaticamente.
3. Crie o primeiro usuário (Admin) através do código inicial.
4. Utilize o link público gerado pelo Gradio para acessar o sistema.

## 📷 Screenshots

<img width="1359" height="682" alt="image" src="https://github.com/user-attachments/assets/5ef270cd-f309-4fd1-a394-c8ddec9b7185" />

---
Desenvolvido por Gustavo Henrique
