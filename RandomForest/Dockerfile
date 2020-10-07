FROM registry.gitlab.com/mbq/arrch:latest

RUN R -e "install.packages(c('randomForest','ranger','rFerns'),repos='https://cloud.r-project.org')"
RUN Rdevel -e "install.packages(c('randomForest','ranger','rFerns'),repos='https://cloud.r-project.org')"

