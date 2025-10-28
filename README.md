[![Github Actions Status for
Guilhermemhz/calculadora_teste_unitario(https://github.com/Guilhermemhz/calculadora_teste_unitario/workflows/Integra%C3%A7%C3%A3o%20continua%20de%20Java%20com%20Maven/badge.svg(https://github.com/Guilhermemhz/calculadora_teste_unitario/actions)
[![Quality Gate
Status](https://sonarcloud.io/api/project_badges/measureproject=osmarbraz_calculadora5&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=osmarbraz_calculadora5)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=osmarbraz_calculadora5&metric=coverage)](https://sonarcloud.io/component_measures?id=osmarbraz_calculadora5&metric=coverage)

# Calculadora com CI.
Utiliza 3 ambientes:
- dev - Desenvolvimento
- hmg - Homologação
- prd - Produção
Pipeline
- dev - Compilação
- hmg - Compilação, Testes, Análise Código, Cobertura Código
- prd - Empacotamento
<br>
- Utiliza o Apache Maven para a automatização da construção.<br>
- A pasta test contêm os testes unitários do projeto utilizando JU
- A cobertura do código é realizada através do JaCoCo.<br>
