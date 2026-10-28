# Fronteiras administrativas — Brasil e Argentina

- `br_arg_admin1.geojson`: unidades de primeiro nível (estados brasileiros e províncias argentinas) da camada Natural Earth 1:10m Admin-1 States and Provinces.
- `brazil_municipalities_<região>.geojson`: limites municipais brasileiros por região, quando uma das fontes de malha pôde ser acessada.

Fonte Natural Earth: https://www.naturalearthdata.com/
Fonte municipal preferencial: https://servicodados.ibge.gov.br/api/v3/malhas/BR?formato=application%2Fvnd.geo%2Bjson&resolucao=5&qualidade=intermediaria
Alternativa oficial: https://geoftp.ibge.gov.br/organizacao_do_territorio/malhas_territoriais/malhas_municipais/municipio_2025/Brasil/BR_Municipios_2025.zip
Espelho de contingência (pode estar desatualizado): https://github.com/tbrugz/geodata-br
Referência IBGE: https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html

Fonte usada nesta execução: https://geoftp.ibge.gov.br/organizacao_do_territorio/malhas_territoriais/malhas_municipais/municipio_2025/Brasil/BR_Municipios_2025.zip
Arquivos municipais incluídos: 6

Os GeoJSONs são camadas cartográficas separadas e não alteram a grade meteorológica de 0,25°. Os contornos municipais não recebem rótulos no PNG para manter a legibilidade; nomes e códigos ficam nas propriedades das feições quando fornecidos pela fonte.
