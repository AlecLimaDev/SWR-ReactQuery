# SWR-ReactQuery
SWR/React Query no lugar de useEffect + Fetch

Dica React: Use SWR/React Query no lugar de useEffect + Fetch

Ainda é muito comum recorrermos ao clássico fetch dentro de useEffect para buscar dados em React. Mas será que essa é a abordagem mais eficiente?

useEffect + Fetch:
✖ Sequencial, manual, e você gerencia o estado de loading/error.
✖ Precisa de caching? Revalidação? Você vai praticamente criar uma solução personalizada do zero.

No lugar disso, experimente SWR ou React Query:
✔ Operações paralelas, automáticas, e com gerenciamento de estado já embutido.
✔ Caching, revalidação, e sincronização de dados
✔ Escreva menos código, evitando boilerplate repetitivo.

No fim do dia...
- Melhor performance: Menos tempo de espera = melhor experiência de usuário.
- Mais produtividade: Menos boilerplate = mais tempo para focar no que importa.
- Sempre atualizado: Mantem sua interface sempre com as informações mais recentes, automaticamente.

E entre SWR e React-Query, eu particularmente prefiro SWR por ter uma interface mais minimalista e simples.



![IMAGEM](public/swr-reactQuery.png)