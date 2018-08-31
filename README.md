# CC-Compiladores-Analisador_Lexico
Atividade I de Compiladores. Analizador lexico.

## Descrição da atividade
ver [pdf](Lexico.pdf).

## Alteracoes para fazer em sala de aula:
Em sala de aula temos que implementar as seguintes mudanças:


```
Testar a seguinte string: 12.34.56
O resutado esperado é:
```

token| classificação 
--|--
. | delimitador
12.34 | float
56 | integer


```
numero 3D com o seguinte formato: real+x+real+y+real+z 
```
```
Comentario de linha com '//'
```

## Analisador sintático

A segunda parte do curso é pegar a saída do léxico e fazer uma análise sintática. O método a ser desenvolvido é o **top-down** utilizando uma análise **preditiva recursiva**

[ver pdf](Sintatico.pdf)

### Observação
Antes de começar o desenvolvimento, a linguagem precisa ser tratada pra poder passar pelo algorítimo sem problemas maiores. A linguagem tratada pode ser encontrada [aqui](gramatica_corrigida.txt)