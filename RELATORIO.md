# Relatório simples - De moto ao posto

## 1. Objetivo

O trabalho simula uma moto que precisa sair de casa e chegar até um posto de gasolina. No caminho existem paredes que representam ruas bloqueadas. O usuário pode escolher entre a Busca Gulosa e o algoritmo A*.

## 2. Como funciona

O mapa foi representado por uma grade. Cada quadrado é um nó. A moto pode andar para cima, para baixo, para a esquerda ou para a direita. Cada movimento tem custo 1.

Na Busca Gulosa, a escolha é feita usando somente H, que é a distância estimada até o posto. Ela tenta chegar perto do objetivo rapidamente, mas pode escolher um caminho maior.

No A*, o valor usado é F = G + H. O valor G é o custo que a moto já percorreu e H é a estimativa até o posto. Assim, o algoritmo considera tanto o caminho já feito quanto o que ainda falta.

## 3. Recursos da aplicação

- alternância entre Busca Gulosa e A*;
- três mapas prontos e um mapa vazio;
- edição manual de paredes, início e posto;
- heurísticas Manhattan, Euclidiana e Diagonal;
- visualização dos nós explorados;
- valores G, H e F nos nós visitados;
- animação do caminho da moto;
- tempo de convergência, nós explorados e custo total;
- comparação entre os dois algoritmos.

## 4. Resultado

Nos testes, o A* normalmente encontra um caminho de menor custo porque considera G e H. A Busca Gulosa pode explorar menos ou tomar decisões mais diretas, mas não garante o melhor caminho. O resultado depende do mapa escolhido.

## 5. Conclusão

A aplicação mostra de forma visual a diferença entre os algoritmos. Foi possível perceber que uma decisão baseada só na distância até o destino nem sempre é a melhor, principalmente quando existem obstáculos.

