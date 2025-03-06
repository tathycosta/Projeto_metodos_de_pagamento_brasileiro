# Métodos de Pagamento Brasileiros

Dataset com estatísticas mensais sobre transações de pagamento no Brasil, coletadas do Banco Central. Inclui métodos como PIX, TED, TEC, DOC, Cheque e Boleto, com dados de quantidade e valor total das transações a partir de janeiro de 2016.

## Link do Dataset
[Link para o dataset](https://docs.google.com/spreadsheets/d/1py2jGg9y4raWJ-fr7p97lyWfchzWXZzc3u8F2V9WvYc/edit?usp=sharing)

## Colunas
- `YearMonth`: Mês e ano (AAAAMM).
- `quantityPix`, `valuePix`: Número e valor total das transações PIX.
- `quantityTED`, `valueTED`: Número e valor total das transações TED.
- `quantityTEC`, `valueTEC`: Número e valor total das transações TEC.
- `quantityBankCheck`, `valueBankCheck`: Número e valor total das transações de cheque.
- `quantityBrazilianBoletoPayment`, `valueBrazilianBoletoPayment`: Número e valor total das transações de boleto.
- `quantityDOC`, `valueDOC`: Número e valor total das transações DOC.

## Análises Sugeridas
1. **Carregamento e Visualização**: Carregue o dataset e exiba as primeiras 5 linhas.
2. **Tradução das Colunas**: Renomeie as colunas para português.
3. **Seleção de Colunas**: Selecione e exiba as colunas `YearMonth`, `quantityPix` e `valuePix`.
4. **Filtragem**: Filtre transações PIX com `valuePix > 1.000.000`.
5. **Criação de Coluna**: Calcule o valor médio por transação PIX (`valuePix / quantityPix`).
6. **Agrupamento por Ano**: Agrupe por ano e some o valor total das transações PIX.
7. **Ordenação**: Ordene por `valuePix` em ordem decrescente e exiba as 10 maiores.
8. **Contagem**: Conte meses com mais de 1.000.000 transações PIX.
9. **Média e Mediana**: Calcule média e mediana de `valueTED`.
10. **Agregação por Ano**: Calcule a média de `valueBrazilianBoletoPayment` por ano.
11. **Gráfico de Linha**: Plote a evolução de `valuePix` ao longo do tempo.
12. **Substituição de Valores**: Substitua `0.0` em `quantityDOC` por `NaN`.
13. **Correlação**: Calcule a correlação entre `valuePix` e `valueTED`.
14. **Crescimento Percentual**: Compare o crescimento de `valuePix` e `valueTED`.
15. **Participação Percentual**: Calcule a participação de cada método no último mês.
16. **Tendência de Declínio**: Analise o declínio de `valueDOC`.
17. **Comparação PIX vs Boleto**: Identifique quando o PIX ultrapassou o boleto.
18. **Método Mais Utilizado**: Descubra o método mais usado no último ano.
19. **Valor Médio por Transação**: Calcule o valor médio por transação no último mês.
20. **Boxplot e Variância**: Analise dispersão de `valuePix` e compare com outros métodos.

## Questões Extras
- **Boxplot e Outliers**: Identifique outliers em `valueTED`.
- **Dispersão do Valor Médio PIX**: Analise a consistência do valor médio por transação PIX.
- **Gráficos de Barras**: Compare valor total e quantidade de transações por método no último mês/ano.

## Como Usar
Clone o repositório e utilize o dataset para análises personalizadas ou siga as questões sugeridas para explorar os dados.
