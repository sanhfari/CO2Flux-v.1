# CO2Flux-v.1
** Português **
O Plugin CO2flux automatiza as estimativas dos índices de vegetação e do CO2flux (relativo ao calculado nas equações 1, 2, 3 e 4), o usuário deve apenas inserir os arquivos com as imagens já corrigidas das bandas 2 (azul), 3 (verde), 4 (vermelho) e 5 (infravermelho próximo), e será retornado, como arquivo de saída, o índice CO2flux calculado.

NDVI=(ρ_inf-ρ_ver )  / (ρ_inf+ρ_ver )	(1)
Onde:
NDVI = Índice de Vegetação da Diferença Normalizada;
ρinf = Reflectância da banda 5 (infravermelho próximo);
ρver = Reflectância da banda 4 (vermelho).

PRI=(ρ_verde-ρ_azul )  / (ρ_verde+ρ_azul ) (2)
Onde:
PRI = Índice de Reflectância Fotoquímica;
ρverde = Reflectância da banda 3 (verde);
ρazul = Reflectância da banda 2 (azul).

sPRI=(PRI+1)  / 2	(3)
Onde:
PRI = Índice de Reflectância Fotoquímica.

CO_2 flux=NDVI*sPRI	(4)
Onde:
CO2flux = Índice de Sequestro Florestal de Carbono;
NDVI = Índice de Vegetação da Diferença Normalizada;
sPRI = Índice de Reflectância Fotoquímica (PRI) reescalonado para valores positivos.




** English ** 

The CO2flux Plugin automates the estimation of vegetation indices and CO2flux (based on calculations in equations 1, 2, 3, and 4). The user only needs to upload the corrected images for bands 2 (blue), 3 (green), 4 (red), and 5 (near-infrared). As output, the calculated CO2flux index will be provided as a file.

NDVI = (ρ_inf - ρ_ver) / (ρ_inf + ρ_ver) (1)
Where:
NDVI = Normalized Difference Vegetation Index;
ρinf = Reflectance of band 5 (near-infrared);
ρver = Reflectance of band 4 (red).

PRI = (ρ_verde - ρ_azul) / (ρ_verde + ρ_azul) (2)
Where:
PRI = Photochemical Reflectance Index;
ρverde = Reflectance of band 3 (green);
ρazul = Reflectance of band 2 (blue).

sPRI = (PRI + 1) / 2 (3)
Where:
PRI = Photochemical Reflectance Index.

CO2 flux = NDVI * sPRI (4)
Where:
CO2flux = Forest Carbon Sequestration Index;
NDVI = Normalized Difference Vegetation Index;
sPRI = Re-scaled Photochemical Reflectance Index (PRI) to positive values.



