
# Bases de obitos:

_________
Nome:  
Base:[Nome da fonte](Link)  
Colunas:  
Periodo Temporal: Inicio: dd/mm/aaaa a Fim: dd/mm/aaaa  
Intervalo Temporal: dia,semana,ano,semestre e etc...  
Observaçoes:  
___________


_________
**Nome**: @souzajvp  <br>
**Base**:[InfoGripe - FIOCRUZ](https://gitlab.procc.fiocruz.br/mave/repo/tree/master/Dados/InfoGripe)  <br>
**Colunas**: ['data de publicação', 'UF', 'Unidade da Federação', 'Tipo', 'dado',
       'escala', 'Ano epidemiológico', 'Semana epidemiológica',
       'Situação do dado',
       'Casos semanais reportados até a última atualização',
       'limite inferior da estimativa', 'casos estimados', 'média móvel',
       'limite superior da estimativa', 'Percentual em relação ao país',
       'População', 'limiar pré-epidêmico', 'intensidade alta',
       'intensidade muito alta', 'nível semanal', 'nível por média móvel'] <br>
**Periodo Temporal**: Inicio: 1ª Semana epidemiológica de 2009 a Fim: semana epidemilógica atual de 2020. <br>
**Intervalo Temporal**: Semana epidemiológica <br>
**Observaçoes**: Iniciativa que acompanha a situação de Síndrome Respiratória Aguda Grave no Brasil. Dados coletados do sivep-gripe e SINAN. 
As bases tem diversos níveis de filtros aos dados: 1) SRAG sem febre; 2) SRAG com febre; 3)Óbitos ou internações. <br>
Separa os casos/óbitos em: 'srag', 'sragflu', 'sragcovid', 'obito', 'obitoflu', 'obitocovid'. <br>
**Granularidade**: Estado, Região, Regional, País. <br>
**Importante**: Nesta base, **todos os óbitos são adicionados na semana epidemiológica de início dos sintomas**

___________
