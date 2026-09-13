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
- [ ] Missing / duplicatas / inconsistências
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
Investigar melhor aquelas variáveis que o Pandas classificou como object, mas que conceitualmente representam valores numéricos (mileage, engine, max_power e torque).