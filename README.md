# De moto ao posto - Busca Gulosa e A*

Este projeto foi feito para uma atividade de Inteligência Artificial. A moto precisa sair da casa (ponto A) e chegar ao posto de gasolina (ponto B), desviando dos obstáculos.

## Como executar

Abra o arquivo `index.html` em qualquer navegador. Não precisa instalar nada. A cópia em `dist/index.html` é usada para publicação.

## O que foi implementado

- Busca Gulosa, que escolhe o próximo nó usando apenas a heurística H.
- A*, que escolhe usando F = G + H.
- Heurísticas Manhattan, Euclidiana e Diagonal.
- Três mapas prontos e um mapa vazio.
- Edição manual de paredes, início e destino.
- Animação dos nós visitados e do caminho da moto.
- Exibição de G, H e F em cada nó visitado.
- Métricas: tempo, nós explorados e custo do caminho.
- Comparação automática entre os dois algoritmos.

## Resumo dos algoritmos

Na Busca Gulosa, o agente olha somente a distância estimada até o posto. Por isso ela pode chegar mais rápido em alguns casos, mas nem sempre acha o menor caminho.

No A*, o agente soma o custo que já percorreu (G) com a estimativa que falta (H). Com uma heurística admissível, ele encontra o caminho de menor custo.

## Estrutura

O projeto foi mantido propositalmente simples, em um único arquivo principal, para facilitar a leitura e a apresentação.

