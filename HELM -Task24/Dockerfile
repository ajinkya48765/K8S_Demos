FROM centos
RUN yum install -y  wget
RUN wget https://dl.grafana.com/oss/release/grafana-7.0.3-1.x86_64.rpm
RUN yum install -y grafana-7.0.3-1.x86_64.rpm
WORKDIR /usr/share/grafana
CMD /usr/sbin/grafana-server start && /usr/sbin/grafana-server enable && /bin/bash
