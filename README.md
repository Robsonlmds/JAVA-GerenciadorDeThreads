# Gerenciador de Threads 

Este projeto demonstra a criação e gerenciamento de múltiplas threads em Java. A classe **MyThread** estende a classe Thread e sobrepõe o método run, onde cada thread executa uma tarefa simples após um breve atraso. O programa principal cria várias instâncias de MyThread, inicia-as e aguarda a conclusão de uma delas antes de exibir uma mensagem final. O projeto ilustra conceitos de concorrência, sincronização e a execução paralela de tarefas em um ambiente multithreaded.

## Estrutura do Código:

### Classes:

- **Main:** Cria e inicia várias instâncias da classe MyThread.
- **MyThread:** Estende a classe Thread e define a lógica a ser executada.

## Técnicas Utilizadas:

- **Threads:** Demonstração de criação de threads em Java.
- **Métodos de Controle:** Uso do método join.
- **Atrasos:** Implementação de um atraso dentro do método run para simular processamento.


