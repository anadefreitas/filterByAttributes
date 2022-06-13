## Processamento de atributos - shapefile / data.frame - RStudio
#### Elaboração: Ana Larissa Ribeiro de Freitas

Este código tem como objetivo separa um shapefile multipoints por atributo. Procedimento que se assemelha o disponibilizado no QGis e ArcGIS, mas de forma automatizada. Na aplicação, foram criados 208 novos shapefiles, com um total de 33672 feições.

###### #Pré-processamento do shapefile#
Em alguns casos, pode ser necessário o pré-processamento dos dados para obter o atributo em comum. Aqui, eu converti através do _libreoffice calc_ os meus valores de mês e ano, para uma única variável. Visto que o objetivo foi separar os dados mensalmente para 18 anos.

![image](https://user-images.githubusercontent.com/57720882/173432291-b7464dfd-64ec-4316-abe0-5fcf3d2f5a7a.png)

###### #Visualização total#
Disposição de todos os pontos no mesmo arquivo a ser processado
![image](https://user-images.githubusercontent.com/57720882/173432579-e6cf62be-3b7c-4e99-9be4-114dc73703e9.png)

###### #Saída dos dados#
Com o processamento finalizado, os arquivos receberam a nomenclatura indicada pelo atributo criado durante o _pré-processamento_, e filtrados conforme indicada a possibilidade no código.

![image](https://user-images.githubusercontent.com/57720882/173432966-7e827391-f6b6-46cf-997d-e4f8baf9215b.png)

### Contato: alarisig@gmail.com
