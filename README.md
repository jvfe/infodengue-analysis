# Análise dos dados de 2022 do InfoDengue para o estado do Rio Grande do Norte

Aqui, adquirimos dados de casos de Dengue para todas as cidades do RN através da API
do [InfoDengue](https://info.dengue.mat.br/) e geramos um relatório simples em RMarkdown/[Quarto](https://quarto.org/)
com algumas visualizações.

- O relatório final, em HTML, pode ser [encontrado aqui](https://jvfe.github.io/infodengue-analysis/infodengue-analysis.html)

- Todo o código que adquire os dados da API, cruza com o dicionário local das regiões imediatas do RN
e salva como um binário .rds pode ser encontrado em [src/compile_RN_data.R](src/compile_RN_data.R)

- O código para gerar as visualizações e o relatório HTML se encontra em [infodengue-analysis.qmd](infodengue-analysis.qmd)
