# Quiz de Python
Este é um simples programa de Quiz em Python que faz perguntas sobre a linguagem Python e computa o número de respostas corretas. O programa foi desenvolvido para praticar conceitos básicos de Python, como laços, condições e manipulação de entrada do usuário.

## Funcionalidades
Pergunta ao usuário a quantidade de perguntas que ele gostaria de responder (de 1 a 8).
Exibe uma pergunta com opções de múltipla escolha.
Valida a entrada do usuário e garante que ela está dentro das opções permitidas.
Fornece feedback ao usuário se ele acertou ou errou a resposta.
Exibe a pontuação final do usuário.
### Requisitos
Python 3.x
### Bibliotecas padrão do Python (time, random)
## Como Usar
Execute o script em um terminal ou ambiente de desenvolvimento.
Digite o número de perguntas que deseja responder (entre 1 e 8).
Responda a cada pergunta digitando o número correspondente à opção correta.
Ao final, o programa exibirá quantas perguntas você acertou.
Estrutura do Código
Função validation(num, op=0): Valida a entrada do usuário para garantir que ele insira valores numéricos dentro dos limites permitidos.
Lista answers: Contém as perguntas, opções e respostas corretas.
Loop de Perguntas: Seleciona perguntas aleatoriamente da lista, exibe para o usuário e verifica a resposta.
Exemplo de Uso
plaintext
Copiar código
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
|------> QUIZ DE PYTHON <-------|
<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<

Digite a quantidade de Perguntas que desejas Responder: |De 1 a 8| --> 3

Prepara-se vamos COMEÇAR !!!
[Iniciado]

PERGUNTA:[1]-> Qual é a estrutura de LISTAS em python ?
OPÇÕES: 
0) - lista = (1,2,3,4)
1) - lista = [1,2,3,4]
2) - lista = list()
3) - Opção 1 e 2 estão Corretas
Digite a opção correspondente a sua resposta --> R: 3
|VOCÊ < ACERTOU > !!! [PARABÉNS] !!!|

...

Você ACERTOU 2 Perguntas de uma série de 3 Perguntas !!!
========================================================
Melhorias Futuras
Adicionar mais perguntas e opções para maior variedade.
Implementar um banco de perguntas externo.
Melhorar a interface com cores e formatação.
Contribuição
Sinta-se à vontade para clonar o repositório, fazer melhorias e enviar um pull request!