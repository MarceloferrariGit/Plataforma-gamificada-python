# Plataforma Web Gamificada para Ensino de Programação em Python

Este repositório contém o código-fonte e os artefatos do Trabalho de Conclusão de Curso (TCC) desenvolvido por **Marcelo Ferrari RU4501046**, cujo objetivo é criar uma **plataforma web gamificada** voltada ao ensino de programação em Python, com desafios progressivos, pontuação, ranking e feedback automático.

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

Plataforma-gameficada-python
+---------------------------------------------------------------+
|                      Plataforma Python+                       |
+---------------------------------------------------------------+
| Menu: [Início] [Desafios] [Ranking] [Meu Progresso]           |
+---------------------------------------------------------------+
| Nível Atual: 1                                                |
| Pontuação: 120 XP                                             |
| Progresso:  [███████-----] 70%                                |
+---------------------------------------------------------------+
| Desafios Disponíveis                                          |
|                                                               |
|  (1) Variáveis e Entrada de Dados        [Iniciar]            |
|  (2) Condicionais                        [Iniciar]            |
|  (3) Laços de Repetição                  [Bloqueado]          |
|                                                               |
+---------------------------------------------------------------+
| Rodapé:       - Plataforma Gamificada Python -                |
+---------------------------------------------------------------+

Tela de Desafio (Mockup Web)
+---------------------------------------------------------------+
|                     Desafio 1: Soma Simples                   |
+---------------------------------------------------------------+
| Enunciado:                                                    |
| Crie uma função que receba dois números e retorne a soma.     |
+---------------------------------------------------------------+
| Área de Código:                                               |
|                                                               |
| def soma(a, b):                                               |
|     # escreva seu código aqui                                 |
|                                                               |
+---------------------------------------------------------------+
| [Executar Código]                                             |
+---------------------------------------------------------------+
| Feedback:                                                     |
| ✔ Sua resposta está correta!                                  |
| ou                                                            |
| ✖ Resultado incorreto. Tente novamente.                       |
+---------------------------------------------------------------+

Tela de Ranking (Mockup Web)
+---------------------------------------------------------------+
|                           Ranking                             |
+---------------------------------------------------------------+
|  Posição | Usuário           | Pontuação | Nível              |
+---------------------------------------------------------------+
|    1     | Aluno_A	       |  980 XP   |   5                |
|    2     | Aluno_B           |  870 XP   |   4                |
|    3     | Aluno_C           |  820 XP   |   4                |
|    4     | Aluno_D           |  600 XP   |   3                |
+---------------------------------------------------------------+
| Observação: Ranking atualizado automaticamente.               |
+---------------------------------------------------------------+

Código-fonte da plataforma web gamificada para ensino de programação em Python

Exemplos de Código
Desafio em Python**

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
