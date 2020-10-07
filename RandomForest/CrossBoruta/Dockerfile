FROM registry.gitlab.com/mbq/arrch:rf.latest

RUN R -e "install.packages(c('ggraph','ggplot2','Boruta'),repos='https://cloud.r-project.org')"
RUN Rdevel -e "install.packages(c('ggraph','ggplot2','Boruta'),repos='https://cloud.r-project.org')"

