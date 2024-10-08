# Gerador de Nota Fiscal

Desafio Nota Fiscal, para que você possa abordá-lo no conforto da sua casa. Abaixo estão os detalhes do desafio:

Desafio:

- Código difícil de manter e alterar
- Muitas regras diferentes de cálculo e fluxo complexo
- Classe "principal" muito instável
- Baixa cobertura de teste e alguns estão quebrando
- Problema funcional: A primeira execução sempre funciona ok, as demais têm um erro na devolução dos itens acumulando os itens de execuções anteriores
- Para pedidos com mais de 6 itens, o tempo de processamento fica muito elevado
- Após algumas execuções o retorno também fica muito lento
- Existem reclamações de outros sistemas onde estão recebendo dados inconscientes relacionados aos valores da nota e total de itens
<hr>
Premissas:
- O Payload de entrada não deve ser modificado
- Algumas integrações têm seu tempo simulando uma chamada, então essa parte não pode simplesmente ser removida
- A solução proposta deve resolver os problemas funcionais mencionados e melhorar a vida do desenvolvedor, demonstrando uma abordagem abrangente no fluxo de desenvolvimento e entrega de software.
<hr>

# Solução dockerizada
- Refactoring para Clean Architecture
- Clean Code
- Design Patterns
- Cobertura de Testes
- Swagger: <b>http://localhost:8080/swagger-ui/index<b/>
- Dockerização e Compose: docker push <a href="https://hub.docker.com/r/migprogrammer/gerador-notafiscal">docker pull migprogrammer/gerador-notafiscal</a>

## Acesse documentação com aplicação rodando<br>
<img src="https://i.imgur.com/haaGki7.png" width=600/>
