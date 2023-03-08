# DAX-Code-Formatting

# Boas Práticas de Formatação na Linguagem DAX
Este é um exemplo de uma expressão DAX não formatada

```VAR Resultado = 

CALCULATE(\
    SUMX( fFaturamento, 'fFaturamento'[[Preço] * 'fFaturamento'[Qtd] ),\
    FILTER( dProduto, dProduto[Categoria] = "Frutas" )\
    )

RETURN
Resultado
