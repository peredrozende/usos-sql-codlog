Uso do solo em São Paulo por frente de quadra
============

**Elaboração:** Pedro Mendonça
**Data de referência:** 2020, atualização não prevista
**Licença de compartilhamento:** CC Atribuição (CC BY 3.0 BR) (ver arquivo LICENÇA.txt)

## Conteúdo
Dados sobre uso do solo do cadastro fiscal da Prefeitura de São Paulo, referente a 2020, agregados por frente de quadra.

## Metodologia
As geometrias e código SQCODLOG foram obtidos a partir da interseção entre um buffer do shapefile de logradouros oficial e o shapefile de quadras fiscais.
As áreas e contagem de contribuintes foram agregadas a partir dos arquivos originais do cadastro fiscal para cobrança de IPTU da Prefeitura de São Paulo, a partir do pacote pandas (python).
A união das geometrias e dos dados, foram executadas no software QGIS, assim como os algoritmos espaciais.

## Dados externos
- Logradouros e cadastro fiscal - [Geosampa](http://geosampa.prefeitura.sp.gov.br/)
