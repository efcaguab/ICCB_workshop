FROM rocker/shiny:latest 

MAINTAINER Fernando Cagua "fernando@cagua.co"

# install additional packages
RUN R -e "install.packages(c'Rcpp', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'ggplot2', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'httr', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'jsonlite', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'magrittr', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'digest', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'vidrisLite', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'base64enc', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'htmlwidgets', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'tydir', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'tibble', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'hexbin', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'lazyeval', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'purr', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'dplyr', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'plotly', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'leaflet', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'tm', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'wordcloud', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'RColorBrewer', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'networkD3', repos='https://cran.rstudio.com/')
RUN R -e "install.packages(c'flexdashboard', repos='https://cran.rstudio.com/')

CMD ["/usr/bin/shiny-server.sh"]