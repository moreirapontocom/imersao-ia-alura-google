# Objetivos do projeto

Aplicar os conhecimentos obtidos durante a Imersão IA - Alura + Google.

### Tecnologias

* Python
* Gemini (gemini-pro)
* Firebase Functions
* Firebase Firestore

### Funcionamento

Sabemos o quão difícil está a situação no Rio Grande do Sul devido às chuvas de Maio/2024.
À cada vez que rodar o projeto, uma frase de conforto será exibida na tela.
As frases são reais, enviadas pelos próprios usuários do projeto.
Os usuários podem adicionar suas frases para que outros usuários vejam.

**Detalhes do funcionamento**

* As frases vem de uma API criada em NodeJS+Express
* As frases estão salvas em um banco de dados não-relacional (Firestore)
* Antes de adicionar a frase no banco de dados, o Gemini verifica se a frase possui conteúdo abusivo, violento ou que não seja considerada de conforto para os leitores.
* Se o conteúdo for considerado "nao_abusivo", a mensagem é salva no banco de dados.
* A fim de simplificação, não foram adicionadas validações na API.
