# Dicionário de Dados

## dim_country
- country_id (int): chave do país
- country_name (text): nome
- region (text): região

## fact_population
- country_id (int)
- year (int)
- population (bigint)

## fact_obesity
- country_id (int)
- year (int)
- obesity_rate_adults (decimal): taxa (0 a 1)

## dim_scenario
- scenario_id (int)
- scenario_name (text)
- uptake_rate (decimal): % adotando
- adherence_rate (decimal): % mantendo
- weeks_on_drug (int): semanas/ano no tratamento

## fact_capacity
- year (int)
- doses_per_year (bigint)
- source_note (text)

## fact_price
- year (int)
- price_per_dose (decimal)
- currency (text)
- source_note (text)
