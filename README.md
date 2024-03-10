# 1 - Desafio Engenharia de Software
### Desenvolva uma API REST com os seguintes requisitos:
#### - Buscar o nome do cliente na API de Cadastro (Mock)
#### - Validar se a conta corrente esta ativa , validar se o cliente tem limite disponível na conta corrente para realizar a transferência
#### - Validar se a transferência excedeu o limite diario de 1.000 reais
#### - Apos a transferência é necessario notificar o Bacen(mock) de forma sincrona que a transação foi concluída com sucesso, a api do bacen tem controle de rate limit e pode retornar 429 em caso de chamadas que excedam o limite 
#### - Impedir que falhas momentâneas das dependências da aplicação impactem a experiência do cliente 
#### - Ser desenvolvida em Java / Spring Boot
#### - Apresentar testes unitários 
#### - Explorar designer patterns 
#### - Implementar padroes de resiliência na aplicação


# 2 - Desafio Arquitetura de Solução
### Crie um desenho de solução preferencialmente AWS para a API que foi desenvolvida no desafio de engenharia de software considerando os requisitos abaixo:
#### - Apresentar uma proposta de escalonamento para caos de oscilação de carga
#### - Apresentar uma proposta de observabilidade
#### - Justificar a escolha da solução de banco de dados
#### - Caso utilizado, justificar o uso de caching
#### - O tempo total da requisição até a resposta ao cliente não deve exceder 100ms
#### - A solução precisa ser capaz de suportar um throuput(6 mil tps)
#### - Em caso de falha de alguma dependência, qual seria a estratégia para garantir a notificação do orgão regulador
