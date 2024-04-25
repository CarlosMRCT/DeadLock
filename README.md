# Multi-Processamento Python: Calculando Pi, Fibonacci e Euler

Este é um exemplo de Deadlocks e o algoritmo de avestruz feito em código Python que utiliza multi-processamento para calcular três constantes matemáticas: Pi, Fibonacci e Euler
em paralelo.

## Descrição

Este código Python demonstra como calcular constantes matemáticas como Pi, Fibonacci e Euler de forma paralela usando multi-processamento. O processo é executado da seguinte forma:

1. Três processos são iniciados simultaneamente para calcular Pi, Fibonacci e Euler.
2. Cada processo aloca um recurso e, em seguida, dorme por um tempo simulando um processo de cálculo.
3. Se um processo levar mais de 5 segundos para terminar, é encerrado para evitar deadlocks.
4. Os recursos são liberados após o término dos processos ou em caso de deadlock.

## Obs

Código efetuado para fins acadêmicos de explicar o deadlock e o uso do algoritmo de avestruz, o mesmo foi feito em conjunto com um colega da faculdade.
