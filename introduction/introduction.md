
## Microservices

Microserviço é uma abordagem de arquitetura **onde a aplicação é dividida em serviços pequenos e independentes, cada um responsável por uma funcionalidade específica.**


Resumindo... você pega um bloco grande (sua aplicacao backend inteira) e o quebra em pequenos bloquinhos (microserviços), onde cada bloquinho é responsável por uma parte específica da aplicação.

<hr>
<br>

## monolithic X microservices

<img src="https://miro.medium.com/v2/resize:fit:1100/format:webp/0*NaFxShP6EuQ4aAc3.png" alt="image example" width="600px">

<br>

- **monolithic** --> Toda a aplicação (front-end, back-end, banco de dados, etc.) é construída e implantada como uma única unidade. Geralmente usada em aplicações mais simples.

<br>

- **microservices** -->  A aplicação é dividida em vários serviços pequenos, cada um responsável por uma funcionalidade específica (ex: autenticação, pagamento, catálogo, etc.)

<hr>
<br>

## Desvantagens de usar monolithic

- **Difícil de manter**: Com o tempo, a aplicação cresce e fica difícil entender e fazer mudanças sem afetar tudo.

<br>

- **Difícil de dividir o trabalho**: Em equipes grandes, pode ser difícil dividir bem as tarefas, já que todos precisam trabalhar no mesmo código. Enquanto nos microserviços, cada time pode ser responsável por um serviço específico, trabalhando de forma mais independente e sem interferir nas outras partes.

<hr>
<br>

### Quando usar monolithic?

- Em aplicações mais simples: Ideal para sistemas menores, onde a complexidade não é tão alta.

- No início de um projeto: Usar um monolito pode ser uma boa escolha quando o projeto está começando, pois permite desenvolver rapidamente. Depois, conforme a aplicação cresce, você pode avaliar como quebrá-la em microserviços, se necessário.

<hr>
<br>





