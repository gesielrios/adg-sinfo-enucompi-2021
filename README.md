<p align="center">
    <img src="./img/logos2021.png" width="600px"/><br><br>
</p>

# ADG-SINFO-ENUCOMPI-2021

Repositório com material utilizado no Minicurso: Introdução à Análise de Dados Geoespaciais com Python apresentado no ENUCOMPI & SINFO 2021.


## Resumo

A análise espacial, ou apenas análise geoespacial, é uma abordagem para aplicar a análise estatística e outras técnicas analíticas a dados que possuem um aspecto geográfico ou espacial. Essa análise normalmente é feita utilizando técnicas de renderização de mapas a partir do processamento de dados espaciais e a aplicação de métodos analíticos a conjuntos de dados terrestres ou geográficos. Este minicurso é uma introdução à análise de dados geoespaciais com Python, com foco em dados vetoriais tabulares usando GeoPandas. O conteúdo concentra-se em apresentar as diferentes bibliotecas para trabalhar com dados geoespaciais e as relações no espaço. Isso inclui a importação de dados em diferentes formatos (por exemplo, \verb!shapefile!, \verb!GeoJSON!), visualizando, combinando e organizando-os para análise, fazendo o uso de bibliotecas como pandas, geopandas, shapely, pyproj, matplotlib, cartopy, dentre outras.


O Minicurso cobrirá os seguintes tópicos, usando Jupyter notebooks e exercícios práticos com dados do mundo real:

- Introdução aos dados vetoriais e GeoPandas
- Relações e operações espaciais
- Junções e superposições espaciais
- Visualização de dados geoespaciais


## 🧪 Tecnologias

Este Minicurso exigirá instalações recentes de:

- Python
- pandas
- matplotlib
- geopandas
- folium
- [Jupyter Notebook or Lab] (http://jupyter.org)
- * (opcional para estudo de caso de locais de mineração) * rasterio, rasterstats
- * (opcional para vitrine de visualização) * cartopia, geoplot, ipyleaflet

Se você ainda não tem esses pacotes instalados, recomendamos usar o gerenciador de pacotes conda para instalar todos os requisitos (você pode instalar o miniconda ou instalar a (maior) distribuição Anaconda, encontrada em https://www.anaconda.com/download /).

Usando conda, recomendamos criar um novo ambiente com todos os pacotes usando os seguintes comandos:

```bash
# ensure you have at least conda >=4.6
conda update conda
# setting the configuation so all packages come from the conda-forge channel
conda config --add channels conda-forge
conda config --set channel_priority strict
# navigate to the downloaded (or git cloned) material
cd .../adg-sinfo-enucompi-2021/
# creating the environment
conda create --n adg-sinfo-enucompi-2021 --file environment.yml
# activating the environment
conda activate adg-sinfo-enucompi-2021
```

Para isso, você já precisa fazer o download dos materiais primeiro (veja abaixo), pois ele faz uso do arquivo `environment.yml` incluído neste repositório.

Alternativamente, você pode instalar os pacotes usando conda manualmente, ou você pode usar outra distribuição (por exemplo, Enthought Canopy) ou `` pip``, contanto que você tenha os pacotes acima instalados. Nesse caso, consulte as instruções de instalação dos pacotes individuais.

## 🎓 Agredecimentos

🚀 <a href="https://sinfo2021.enucompi.com.br/" target="_blank">ENUCOMPI & SINFO 2021 </a>.


## 📝 Licença

Este projeto está licenciado sob a Licença MIT.