FROM elasticsearch:5.5.2



#安装x-pack插件
RUN elasticsearch-plugin install x-pack

#安装IK分词插件
RUN cd /usr/share/elasticsearch/plugins && wget https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v5.5.2/elasticsearch-analysis-ik-5.5.2.zip && unzip elasticsearch-analysis-ik-5.5.2.zip && mv elasticsearch ik && rm -rf elasticsearch-analysis-ik-5.5.2.zip
