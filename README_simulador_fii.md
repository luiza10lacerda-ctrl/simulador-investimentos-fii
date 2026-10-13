# Simulador 

# Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio prático da DIO
para aplicar recursos do Excel na criação de uma ferramenta de simulação
de investimentos em fundos imobiliários.

A planilha permite testar diferentes valores de aporte mensal, prazos e
taxas de rendimento, além de observar projeções de patrimônio e
dividendos estimados. Também apresenta uma distribuição ilustrativa do
aporte entre tipos de fundos conforme o perfil selecionado.

## O que a ferramenta permite fazer

* Informar o aporte mensal e o prazo do investimento.
* Configurar a taxa de rendimento mensal utilizada na simulação.
* Estimar o patrimônio acumulado ao final do período.
* Estimar os dividendos mensais com base nas premissas informadas.
* Comparar projeções para diferentes horizontes: 2, 5, 10, 20 e 30
anos.
* Selecionar um perfil de investidor e visualizar a divisão do aporte
entre seis tipos de fundos imobiliários.
* Consultar a distribuição do aporte em um gráfico de pizza, quando
disponível na planilha.

## Como utilizar

1. Baixe o arquivo Excel deste repositório e abra-o no Microsoft Excel
ou em um programa compatível.
2. Preencha os campos de entrada, como aporte mensal, prazo e taxa de
rendimento.
3. Selecione o perfil de investidor na lista suspensa.
4. Consulte os resultados da simulação, as projeções e a distribuição
do aporte.
5. Altere os parâmetros para comparar cenários diferentes.

Os resultados são estimativas matemáticas baseadas nos valores
inseridos. Eles não consideram necessariamente impostos, taxas,
inflação, variação dos preços das cotas ou mudanças reais na
distribuição de rendimentos dos fundos.

## Recursos de Excel aplicados

* **VF:** função financeira utilizada para projetar o valor futuro de
aportes periódicos, considerando taxa e número de períodos.
* **PROCV:** busca de percentuais na tabela de apoio conforme o perfil
e o tipo de fundo.
* **Validação de dados:** criação de uma lista suspensa para
selecionar o perfil.
* **Intervalos nomeados:** uso de nomes como `aporte` e `taxa\_mensal`
para tornar fórmulas mais legíveis, quando definidos na pasta de
trabalho.
* **Referências absolutas e relativas:** apoio à cópia das fórmulas
nas projeções.
* **Gráfico de pizza:** visualização da composição percentual ou
financeira do aporte, vinculada aos dados da planilha.

## Perfis e percentuais

A planilha utiliza uma tabela de apoio que relaciona perfil de
investidor, tipo de fundo e percentual de alocação. Os percentuais são
exemplos didáticos definidos para o exercício e devem totalizar **100%
para cada perfil**.

Para conferir ou alterar as distribuições, consulte a aba de apoio da
pasta de trabalho. Qualquer alteração deve preservar o total de 100% por
perfil para que a divisão do aporte faça sentido.

## 

