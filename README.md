## libft

O projeto libft consiste em criar do zero a biblioteca que será usado no desenvolvimento dos próximos projetos, para cria-lo foi descrito para clonar algumas funções já existentes e criar algumas novas, seguindo diversas limitações.

## get_next_line

O projeto get_next_line é uma função um pouco mais parruda para acrescentar ao libft. Ela consiste em utilizar a função read() da biblioteca unistd.h, para "puxar" uma string com o texto de um arquivo até a quebra de linha.

**Desafios:** Tomar cuidado com os vazamentos de memória, timeouts e controles de erros.

## ft_printf

Está função é um clone parcial da printf original, contemplando apenas as tags (cspdiuxX%).

**Desafios:** Tomar cuidado com os vazamentos de memória, e controle de erros. O printf original tem dezenas de controles de erros e precisei estressar a função original para entender quais controles de erro implementar.