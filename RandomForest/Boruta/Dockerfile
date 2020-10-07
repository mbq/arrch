FROM registry.gitlab.com/mbq/arrch:rf.latest

RUN R -e "install.packages(c('xgboost','survival','mlbench','rFerns'),repos='https://cloud.r-project.org')"
RUN Rdevel -e "install.packages(c('xgboost','survival','mlbench','rFerns'),repos='https://cloud.r-project.org')"

