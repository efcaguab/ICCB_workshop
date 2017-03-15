FROM rocker/shiny:latest 

MAINTAINER Fernando Cagua "fernando@cagua.co"

# install additional packages
RUN R -e "install.packages(c('dplyr', 'flexdashboard', 'rgdal', 'plotly', 'leaflet', 'magrittr', 'httr', 'wordcloud', 'tm', 'RColorBrewer', 'networkD3'), repos='https://cran.rstudio.com/')"

CMD ["/usr/bin/shiny-server.sh"]