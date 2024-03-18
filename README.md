# Medidas de redes 🚩
Nesse projeto são apresentadas algumas medidas de redes complexas:
- **Assortatividade (Assortativity):** calcula a tendência de conexão entre vértices, verificando a relação ao grau de cada um (NEWMAN, 2003). O coeficiente de assortatividade r representa o coeficiente de correlação de Pearson de grau entre pares de nós conectados, com isso os valores giram em torno de [-1,1], em que valores positivos indicam uma correlação entre nós de grau semelhante, enquanto valores negativos indicam relações entre nós de grau diferente (CARNEIRO, 2016).
  
- **Coeficiente de agrupamento (Cluster Coefficient):** mede o grau com que os nós de um grafo tendem a agrupar-se (CARNEIRO, 2016). Em outras palavras, dado um determinado nó, o coeficiente de agrupamento estima o quão perto os seus vizinhos estão, e consequentemente a probabilidade de se interligarem.
  
- **Grau médio (Average Degree):** é uma medida simples, que quantifica a quantidade de conexões de um vértice da rede. Dado todos os vértices de uma rede, o grau médio define a quantidade média de vértices adjacentes.
  
- **Menor caminho médio (Shortest Path Length):** seja um par de nós (i,j), o menor caminho possível dentre todos os possíveis é chamado de menor caminho médio ou distância geodésica. Essa medida representa a maneira mais eficiente de percorer a rede, minimizando o tempo e custo para torca de informações (BORGWARDT AND KRIEGEL, 2005; VERA, 2011).
  
- **Proximidade (Closeness):** mede o quão próximo um vértice está dos demais nós da rede, em outras palavras, está medida expressa o inverso da distância geodésica média de um ponto em relação aos demais (CARNEIRO, 2016).
  
- **Intermedialidade (Betweenness):** a intermedialidade, também conhecida como betweenness é uma medida de centralidade de vértices. Tecnicamente, quanto maior o valor de Intermedialidade de um vértice, maior é o tráfego de informações e acesso do mesmo (BILZÃ, 2015).

### Referências
- NEWMAN, M. E. The structure and function of complex networks. SIAM review, SIAM, v. 45, n. 2, p. 167–256, 2003.
- CARNEIRO, M. G. Redes complexas para classificação de dados via conformidade de padrão, caracterização de importância e otimização estrutural. Tese (Doutorado) — Instituto de Ciências Matemáticas e de Computação - USP, São Carlos, 2016.
- BORGWARDT, K. M.; KRIEGEL, H.-P. Shortest-path kernels on graphs. In: IEEE. Fifth IEEE international conference on data mining (ICDM’05). [S.l.], 2005. p. 8–pp.
- VERA, A. M. Propriedades de redes complexas de telecomunicações. Dissertação (Mestrado) — Escola de Engenharia de São Carlos, Agosto 2011.
- BILZã, M. d. A. Rotulação de indivíduos representativos no aprendizado semissupervisionado baseado em redes: caracterização, realce, ganho e filosofia. Tese (Doutorado) — Instituto de Ciências Matemáticas e de Computação - USP, São Carlos, 2015.
