From ubuntu
MAINTAINER Dave Tang <me@davetang.org>
RUN apt-get update
RUN apt-get install -y git build-essential cpanminus
RUN cpanm Bio::Perl Bio::OntologyIO Graph::Directed

RUN mkdir /src && cd /src && git clone https://github.com/WangGenomicsLab/phenolyzer

CMD echo Phenolyzer

