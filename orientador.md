# Orientador do projeto

## Decisões já tomadas
- Dataset: Car details v3.csv
- Problema: regressão
- Target: selling_price
- EDA aprofundada apenas sobre treino
- Não aplicar conceitos de desbalanceamento/separabilidade de classes

## Fluxo do projeto
- [X] Carregar dataset
- [X] head / shape / info
- [X] Dicionário das variáveis
- [X] Investigar qualidade dos dados:
        - Missing / duplicatas / 
        - inconsistências / Cardinalidade / 
        - inspeção de categorias / Variáveis númericas armazenadas como texto
- [ ] Investigar as duplicatas e decidir se devem ser mantidas ou removidas.
- [ ] Separar treino e teste
- [ ] EDA univariada
- [ ] EDA bivariada/multivariada
- [ ] Outliers
- [ ] Tratamentos
- [ ] Encoding
- [ ] Scaling
- [ ] PCA
- [ ] ColumnTransformer + Pipeline
- [ ] Conclusões finais

## Regra para o notebook
Para cada etapa:
1. mostrar evidência;
2. interpretar;
3. justificar decisão.

Nunca concluir algo antes de mostrar a análise que sustenta.

## Próximo passo:
Duplicatas como próximo passo antes do train/test split, porque se concluirmos que são registros repetidos de fato, é melhor resolver isso antes da separação para não correr o risco de uma mesma observação aparecer tanto no treino quanto no teste.