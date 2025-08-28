PyAutoGUI

### 📖 Descrição

Este repositório foi criado para documentar meus estudos sobre a biblioteca `pyautogui` do Python. O objetivo principal é explorar suas funcionalidades para a automação de tarefas repetitivas na interface gráfica do usuário (GUI).

Ele contém um script de exemplo para automatizar a abertura do LinkedIn e um arquivo de anotações (`Cheat Sheet`) com os principais comandos da biblioteca.

### 🛠️ Tecnologias Utilizadas

* **Python**
* **PyAutoGUI**: A biblioteca principal para a automação da GUI.
* **time**: Biblioteca nativa do Python, utilizada para adicionar pausas e garantir que a automação não seja rápida demais para a interface responder.

### ⚙️ Como Executar o Script

Para executar o script de automação, siga os passos abaixo:

1.  **Clone este repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    cd seu-repositorio
    ```

2.  **Crie um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: .\venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    ```bash
    pip install pyautogui
    ```

4.  **Execute o script:**
    ```bash
    python abrirLinkedin.py
    ```

⚠️ **Atenção:** O script assumirá o controle do seu mouse e teclado. Para interromper a execução a qualquer momento, mova o mouse rapidamente para um dos cantos da tela (fail-safe do PyAutoGUI).
