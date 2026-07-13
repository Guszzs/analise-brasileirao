 Desempenho vs. Resultado

Análise de dados que compara o desempenho real dos times (medido via xG - Expected Goals)
com os resultados efetivamente obtidos, identificando quais equipes tiveram sorte ou azar
ao longo do campeonato.

Pergunta central

O time que "merece" vencer, baseado no seu desempenho em campo, é realmente o que mais pontua?
Ou existem times sistematicamente "azarados" (jogam bem, pontuam pouco) e "sortudos"
(jogam mal, pontuam muito)?

 Metodologia

1. Coleta de dados de xG (Expected Goals) do Brasileirão pelo FootyStats
2. Coleta de resultados reais e pontos via API de dados esportivos
3. Conversão de xG usando distribuição de Poisson
4. Cálculo do Índice de Sorte/Azar = Pontos Reais - Pontos Esperados
5. Validação da robustez da métrica em múltiplas temporadas

Estrutura do projeto

```
analise-brasileirao/
│ - data/
│ - raw/           
│   └── processed/    
│ notebooks/         
│ - src/              
│ - reports/
│   └── figures/       
│ - requirements.txt
└── README.md
```

Bibliografia

- FootyStats - xG Brasileirão (https://footystats.org/pt/brazil/serie-a/xg)
- API de dados esportivos

Em desenvolvimento

Gustavo Cruz | [LinkedIn](linkedin.com/in/gustavo-goncalves-cruz/) | [GitHub](https://github.com/Guszzs)
