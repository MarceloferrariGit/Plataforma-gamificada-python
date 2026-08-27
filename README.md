Plataforma Web Gamificada para Ensino de Programação em Python

Este repositório contém o código-fonte e os artefatos do Trabalho de Conclusão de Curso (TCC) desenvolvido por Marcelo Ferrari RU4501046, cujo objetivo é criar uma plataforma web gamificada voltada ao ensino de programação em Python, com desafios progressivos, pontuação, ranking e feedback automático.

---

Objetivo do Projeto

Desenvolver uma plataforma web interativa que auxilie estudantes iniciantes e intermediários no aprendizado de programação em Python, utilizando elementos de gamificação para aumentar o engajamento, motivação e persistência.

A plataforma inclui:

- Desafios práticos de programação  
- Feedback automático das respostas  
- Sistema de pontuação e níveis  
- Ranking entre usuários  
- Interface web acessível e responsiva  

---

Tecnologias Utilizadas

Frontend (Web)
- HTML5  
- CSS3  
- JavaScript  
- Mockups e protótipos de interface  

Backend
- Python  
- Funções de validação automática  
- Lógica de pontuação e ranking  

Infraestrutura
- GitHub (versionamento)  
- Estrutura modular (frontend + backend + mockups)  

---

Prints / Mockups da Plataforma
Tela Inicial (Mockup Web)

---

Plataforma-gameficada-python
<img width="400" height="494" alt="image" src="https://github.com/user-attachments/assets/404fcf63-1b3a-4857-9b02-4208d37f19a6" />
---

Tela de Desafio (Mockup Web)
<img width="400" height="494" alt="image" src="https://github.com/user-attachments/assets/984267fa-50a6-46ec-b5e8-2c4bd2c81e92" />
---

Tela de Ranking (Mockup Web)
<img width="400" height="494" alt="image" src="https://github.com/user-attachments/assets/02b90d81-bd48-4c2b-8cbc-af1d92aac9b6" />
---

Código-fonte da plataforma web gamificada para ensino de programação em Python

Exemplos de Código
Desafio em Python

```python
## Desafio
def soma_dois_numeros(a, b):
    return a + b

## Validação Automática
def validar_resposta(funcao_estudante):
    try:
        resultado_teste = funcao_estudante(10, 15)
        return resultado_teste == 25
    except Exception:
        return False
