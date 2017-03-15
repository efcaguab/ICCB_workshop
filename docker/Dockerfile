FROM rocker/shiny:latest 

MAINTAINER Fernando Cagua "fernando@cagua.co"

# install additional packages
RUN R -e "install.packages('tidyverse')"
RUN R -e "install.packages(c('flexdashboard', 'rgdal', 'plotly', 'leaflet', 'magrittr', 'httr', 'wordcloud', 'tm', 'RColorBrewer'), repos='https://cran.rstudio.com/')"

CMD ["/usr/bin/shiny-server.sh"]