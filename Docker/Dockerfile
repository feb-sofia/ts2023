FROM rocker/rstudio
LABEL authors="amarov"

RUN R -e "install.packages(c('tsibble', 'fable', 'forecast', 'urca', 'feasts', 'quantmod', 'lubridate'),dependencies=TRUE, repos='http://cran.rstudio.com/')"

RUN cd $HOME & git clone https://github.com/feb-sofia/ts2023.git
