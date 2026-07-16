# # Simulação Numérica e Visualização do Atrator de Lorenz
Este projeto apresenta uma simulação numérica do sistema de Lorenz, um conjunto de equações diferenciais ordinárias conhecido por representar um comportamento caótico e altamente sensível às condições iniciais.

As equações do sistema são resolvidas numericamente por meio da função solve_ivp, da biblioteca SciPy, utilizando o método de Runge-Kutta de ordem 5(4), representado pelo algoritmo RK45. A simulação considera os parâmetros clássicos do sistema de Lorenz: σ = 10, ρ = 28 e β = 8/3.

A partir do estado inicial definido para as variáveis x, y e z, são calculados 5.000 pontos ao longo do intervalo de tempo entre 0 e 40. Os resultados são apresentados em um gráfico tridimensional produzido com Matplotlib, formando a estrutura característica conhecida como Atrator de Lorenz.

O projeto demonstra a aplicação de métodos numéricos na resolução de equações diferenciais e permite visualizar um dos exemplos mais conhecidos da teoria do caos.
