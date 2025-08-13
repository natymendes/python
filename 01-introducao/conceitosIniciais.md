# Introdução ao Python

## O que é Python e por que ele é tão popular
Python é uma linguagem de programação de **alto nível**, criada por **Guido van Rossum** e lançada em 1991.  
Ela é conhecida por sua **simplicidade**, **legibilidade** e por permitir escrever menos código para fazer mais coisas.

**Principais motivos da popularidade:**
- Sintaxe simples e fácil de aprender, parecida com o inglês.
- Usada em diversas áreas: desenvolvimento web, análise de dados, inteligência artificial, automação, jogos, IoT e muito mais.
- Comunidade enorme e ativa, com milhares de bibliotecas prontas para uso.
- Código aberto (open source) e gratuito.

---

## Como instalar o Python no seu sistema

### Windows
1. Acesse [https://www.python.org/downloads/](https://www.python.org/downloads/).
2. Baixe a versão **3.10 ou superior**.
3. Durante a instalação, marque a opção **"Add Python to PATH"**.
4. Clique em **Install Now**.

### MacOS
1. Baixe pelo site oficial: [https://www.python.org/downloads/](https://www.python.org/downloads/)  
   ou instale via terminal com:
   ```bash
   brew install python


  ## Como configurar o ambiente de desenvolvimento (VS Code recomendado)

1. Baixe e instale o **Visual Studio Code**: [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Abra o VS Code e instale a extensão oficial **Python** (Microsoft).
3. Verifique se o interpretador Python está selecionado:
   - Pressione `Ctrl + Shift + P` (Windows/Linux) ou `Cmd + Shift + P` (Mac).
   - Procure por **Python: Select Interpreter**.
   - Escolha a versão instalada.

---

## Como rodar seu primeiro script Python

1. Crie um arquivo `exemplo.py` com o seguinte conteúdo:
   ```python
   print("Olá, mundo! Este é meu primeiro programa em Python.")

