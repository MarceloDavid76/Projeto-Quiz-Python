Projeto Quiz

Este é um projeto de quiz em Python, onde o usuário responde perguntas de verdadeiro ou falso sobre ciência da computação. O objetivo é responder o maior número de questões corretamente para alcançar a maior pontuação possível.

Estrutura do Projeto

# data/question_data.py: Contém uma lista de perguntas e respostas.

# question_model.py: Define a classe Question, que representa uma pergunta com seu texto e resposta correta.

# quiz_brain.py: Contém a lógica principal do quiz, incluindo a contagem de pontuação e o fluxo de perguntas.

# main.py: Arquivo principal que executa o quiz, gerencia as perguntas e interage com o usuário.

## Como Rodar o Projeto

1. Clonar o Repositório

2. Instalar Dependências

Este projeto não possui dependências externas no momento, então você pode rodá-lo diretamente.

3. Executar o Quiz

Para rodar o quiz, execute o arquivo main.py:

4. Responda às Perguntas

O quiz irá apresentar uma pergunta de verdadeiro ou falso. Digite True ou False para cada pergunta. Ao final, o programa mostrará a sua pontuação.

## Como Funciona

O programa carrega as perguntas e respostas a partir da variável question_data localizada no arquivo data/question_data.py.

Cada pergunta é representada por um objeto da classe Question (definida em question_model.py).

O quiz é executado pela classe QuizBrain (em quiz_brain.py), que gerencia a lógica das perguntas, pontuação e interação com o usuário.

## Contribuindo

Faça um fork deste repositório.

Crie uma branch para sua feature (git checkout -b feature/nova-pergunta).

Faça o commit das suas alterações (git commit -am 'Adiciona nova pergunta').

Faça um push para a sua branch (git push origin feature/nova-pergunta).

Crie um Pull Request.
