### Virtualização de Ambientes Python e Gerenciamento de Bibliotecas

**Autor:** Robertson Ebling dos Santos  
**Data:** Junho/2023  

#### Resumo do Tutorial:
Este tutorial detalha os passos para criar, ativar, desativar e gerenciar ambientes virtuais em Python. Ele também aborda como instalar bibliotecas usando `pip` e listar dependências com `pip freeze`.

---

#### Passos Principais:

1. **Instalação do Python 3**  
   - Linux e Mac: já vêm com Python instalado.  
   - Windows: instalação manual via [python.org](https://www.python.org/downloads/).

2. **Por que usar ambientes virtuais?**  
   - Permitem isolar dependências por projeto.  
   - Evitam conflitos de versão entre bibliotecas.

3. **Criação e ativação de um ambiente virtual:**  
   - **Linux/Mac:**  
     ```bash
     python3 -m venv nome_ambiente
     source nome_ambiente/bin/activate
     ```
   - **Windows:**  
     ```cmd
     python -m venv nome_ambiente
     nome_ambiente\Scripts\activate
     ```

4. **Desativação de ambiente virtual:**  
   - Comando:  
     ```bash
     deactivate
     ```

5. **Instalação de bibliotecas via `pip`:**  
   - Exemplo:  
     ```bash
     pip install nome_biblioteca
     ```

6. **Listagem de bibliotecas instaladas:**  
   - Exemplo:  
     ```bash
     pip freeze
     ```

---
