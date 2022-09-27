# Pomodoro
###### Versão 1

Este projeto tem o intuito de desenvolver um aplicativo que utiliza a técnica pomodoro.

O principal objetivo deste projeto é desenvolver e registrar todos os passos de desenvolvimento deste aplicativo.

Ele foi dividido em 3 etapas:

1. Elicitação dos requisitos
2. Prototipação
3. Implementação

## Elicitação dos requisitos

Nesta seção estão listados todos os requisitos desejados para a aplicação.

O método pomodoro consiste em executar uma tarefa por 25 minutos e fazer pausas de 5 minutos. Na quarta pausa o tempo é de 20 minutos e após isso o processo é repetido.

Tendo em vista o método como também outros pontos desejáveis para o aplicativo, foi definido que os requisitos são:

- A tarefa precisa ser identificada;
- É necessário um cronômetro de minutos e segundos;
- O tempo padrão do cronômetro deve ser 25 minutos, mas que pode ser modificado livremente ***mínimo 1 minuto máximo 1 hora***;
- O tempo padrão das pausas curtas deve ser 5 minutos, mas que pode ser modificados somente para 3, 5, 10 ou 15 minutos;
- O tempo padrão da pausa longa deve ser 20 minutos e não pode ser modificado. Isso deve ser informado ao usuário;
- As pausas devem ser contabilizadas automaticamente (3 pausas curtas e 1 longa) e não podem ser alteradas pelo usuário;
- O número de pausas que já foram feitas deve ser mostrado;
- A hora de execução e pausa precisam ser bem identificados visualmente, sendo a hora de pausa obrigatoriamente identificada pela cor verde;
- A transição de execução para pausa, como também de pausa para execução deve possuir um aviso sonoro;
- Deve haver um espaço para anotação de distrações;
- Ao modificar a tarefa as distrações e as pausas devem ser zeradas/excluídas;
- O aplicativo deve ter layout consistente tanto em portrait quanto em landscape.
