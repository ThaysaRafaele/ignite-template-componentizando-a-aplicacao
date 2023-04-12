# ignite-template-componentizando-a-aplicacao

Objetivo: Refatorar uma página para listagem de filmes de acordo com gênero. 

A aplicação foi entregue já funcional, mas grande parte do código estava implementada diretamente no arquivo `App.tsx`. 
Para resolver isso da melhor forma, foi necessário dividir a aplicação em **pelo menos** duas partes principais: <br>
sidebar e o conteúdo principal que possui o header e a listagem de filmes (content).

- A aplicação possui apenas uma funcionalidade principal que é a listagem de filmes;
- Na sidebar é possível selecionar qual categoria de filmes deve ser listada;
- A primeira categoria da lista (que é "Ação") já começa como marcada;
- O header da aplicação possui apenas o nome da categoria selecionada que deve muda dinamicamente.

Adicionais:
* Utilizando o JSON Server para simular uma API que possui as informações de gêneros e filmes. 

<br>
Interface da aplicação:

![image](https://user-images.githubusercontent.com/83955839/231316114-6873a324-a3c0-4428-ac61-bfbe9ce6e9b9.png)
