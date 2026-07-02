# 📂 Organizador Automático de Arquivos em Shell Script

Um script em Shell desenvolvido para automatizar a organização de diretórios bagunçados (como a pasta de Downloads), movendo arquivos automaticamente para pastas específicas com base em suas extensões.

## 🚀 Tecnologias Utilizadas
* **Sistema Operacional:** Rocky Linux 9 (ambiente homologado em máquina virtual via VirtualBox)
* **Linguagem:** Shell Script (Bash)
* **Editor de Texto:** Vim

## 🛠️ Como o projeto funciona
O script valida se os diretórios de destino existem e, utilizando caracteres curingas (`*`), mapeia e move os arquivos sem interromper o fluxo do terminal:
* `.pdf` ➡️ Movidos para a pasta `Documentos`
* `.jpg` e `.png` ➡️ Movidos para a pasta `Imagens`
* `.py` e `.html` ➡️ Movidos para a pasta `Codigos`

## ⚙️ Como Executar o Projeto

1. Clone o repositório ou crie o arquivo localmente:
   ```bash
   vim organizador.sh
