# Desafio Crawler

Por favor, leia atentamente as instruções abaixo antes de iniciar o desafio. Em caso de dúvidas, entre em contato que estaremos à disposição.

## Instruções

1. Crie um repositório no GitHub para armazenar todo o código que utilizar para solucionar o problema. 
2. Copie o link do repositório que criar e envie no e-mail `iurebrandao@gmail.com` com o assunto `Desafio Crawler - Seu Nome` até segunda-feira (22/08) às 10:00, horário de Brasília. Não podendo editar, adicionar e nem excluir qualquer arquivo após esse horário. 
3. Não aceitaremos códigos plagiados.
4. Leia atentamente e siga todos os passos da aba [Requisitos](#requisitos).
5. O candidato que não cumprir os requisitos acima, estará automaticamente eliminado.

## Problema

`Crawler` ou `web crawler` são termos utilizados para definir os algoritmos criados para a coleta de dados de diferentes fontes, também conhecidos por `scraper`. Resumidamente, os `crawlers` são robôs rastreadores ou bots desenvolvidos para realizar a varredura em sites, ou outras fontes (como banco de dados digitais), a fim de capturar informações relevantes. Dessa forma, é possível automatizar diversas tarefas de coleta de dados que são feitas manualmente, ao desenvolver um crawler que execute essas tarefas no lugar do ser humano. 

Nesse contexto, o seu objetivo é desenvolver um web crawler em Python, que acesse o site [https://www.tripadvisor.com.br/](https://www.tripadvisor.com.br/), busque pelo termo `Congresso Nacional - Brasília` e imprima no terminal a nota da avaliação e o número de avaliações desse local, da seguinte forma:

```
## Resultado da coleta de dados ##
Avaliação do local: <avaliacao> de <num_avaliacao> avaliações.
```
Substituindo `<avaliacao` pela nota de avaliação capturada no TripAdvisor e `<num_avaliacao>` pelo número de avaliações. 
Exemplificando, se o crawler desenvolvido capturou uma nota de 4.5 e 5.331 avaliações para esse local, ele deverá imprimir no terminal dessa forma:
```
## Resultado da coleta de dados ##
Avaliação do local: 4.5 de 5.331 avaliações.
```

Para facilitar, nós criamos um vídeo de quais são os passos para encontrar essa informação no TripAdvisor. Clique no link abaixo para ver o vídeo:

[Link do Vídeo](https://drive.google.com/file/d/1nQjPGps8obOJIMGr_i7G5TWvIMta_1kV/view)


## Requisitos

- O código deverá ser exclusivamente feito na linguagem Python.
- O repositório deverá conter uma documentação simples de como rodar o projeto.
- O código deverá imprimir as informações coletadas no terminal com a formatação exemplificada na aba [Problema](#problema)
- Bibliotecas terceiras são bem-vindas para a solução do problema.
- *Dica*: Utilize a biblioteca [Selenium](https://selenium-python.readthedocs.io/) ou [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/) para te auxiliar no desenvolvimento do crawler
