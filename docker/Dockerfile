FROM rocker/shiny:latest 

MAINTAINER Fernando Cagua "fernando@cagua.co"

# install additional packages
RUN R -e "install.packages('Rcpp', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('ggplot2', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('httr', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('jsonlite', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('magrittr', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('digest', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('vidrisLite', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('base64enc', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('htmlwidgets', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('tydir', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('tibble', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('hexbin', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('lazyeval', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('purr', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('dplyr', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('plotly', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('leaflet', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('tm', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('wordcloud', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('RColorBrewer', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('networkD3', repos='https://cran.rstudio.com/')"
RUN R -e "install.packages('flexdashboard', repos='https://cran.rstudio.com/')"

CMD ["/usr/bin/shiny-server.sh"]