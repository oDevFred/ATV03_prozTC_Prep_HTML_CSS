# Atividade 03 - Talento Cloud

Este projeto faz parte do curso **Talento Cloud**, oferecido pela **Proz** em parceria com a **AWS**. Atualmente, estou no módulo **Preparação para HTML/CSS**. Nesta atividade, vou elaborar um sistema que imprime na tela os novos produtos que chegaram em uma loja de cosméticos. O código foi desenvolvido no **Google Colab** (Pode ser acessado aqui: https://colab.research.google.com/drive/1ZjQFhKgKOrghYa21uoSc1BUI1Gl78zR9?usp=sharing).

## Descrição da Atividade

Nesta atividade, o objetivo é imprimir no terminal os produtos disponíveis em uma loja de cosméticos, um por um. Para isso, utilizamos um array que contém os produtos e um loop para iterar sobre eles.

Como desafio opcional, a tarefa é imprimir cada produto com a frase "Temos [produto] à venda!".

## Estrutura do Código

O código contém as seguintes etapas:

1. Declaração da lista `lista_produtos` com os produtos da loja.
2. Uso de um loop `for` para iterar sobre cada produto na lista.
3. Impressão da frase formatada no terminal para cada produto.

## Código

```python
# Declaração da lista de produtos da loja de cosméticos
lista_produtos = ['máscaras faciais', 'batons', 'esmaltes', 'perfumes', 'loções', 
                  'xampus', 'sabonetes', 'delineadores']

# Impressão de cada produto na tela
for produto in lista_produtos:
    print(f'Temos {produto} à venda!')
```

## Resultado Esperado

Ao rodar este código, o terminal deverá exibir:

```
Temos máscaras faciais à venda!
Temos batons à venda!
Temos esmaltes à venda!
Temos perfumes à venda!
Temos loções à venda!
Temos xampus à venda!
Temos sabonetes à venda!
Temos delineadores à venda!
```

## Tecnologias Utilizadas

- **Python**: Linguagem de programação usada para realizar a atividade.
- **Google Colab**: Ambiente de desenvolvimento onde o código foi executado.

## Sobre o Projeto Talento Cloud

Este projeto faz parte da formação em programação promovida pela Proz em parceria com a AWS, através do programa Talento Cloud, que visa capacitar alunos com competências em programação e desenvolvimento de software.
