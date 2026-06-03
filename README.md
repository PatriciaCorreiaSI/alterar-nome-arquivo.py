# 📁 Renomeador de Arquivos em Lote

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

Script em Python que renomeia, em lote, todos os arquivos de uma pasta a partir de um padrão de nome informado pelo usuário.

## ⚙️ O que o script faz

1.  Acessa a pasta de trabalho (`C:\Teste`).
2.  Solicita ao usuário um **padrão de nome** (sem a extensão).
3.  Percorre os arquivos da pasta e os renomeia aplicando esse padrão, preservando a extensão original de cada arquivo.

## ▶️ Como Usar

1.  Coloque os arquivos que deseja renomear na pasta `C:\Teste` (ou altere o caminho na linha `os.chdir(...)`).
2.  Execute o script:
    ```bash
    python renomeia_arquivos.py
    ```
3.  Digite o padrão de nome desejado quando solicitado.

## 🛠️ Tecnologias

*   ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) **Python 3**
*   **`os`** — módulo padrão para navegação e manipulação de arquivos do sistema.

## ⚠️ Atenção

A renomeação é **permanente** e não pode ser desfeita automaticamente. Faça um backup dos arquivos antes de executar e teste primeiro em uma pasta com cópias.

## 👩‍💻 Autora

Patricia Correia

<p>
  <a href="https://br.linkedin.com/in/patriciacorreiasi">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>
