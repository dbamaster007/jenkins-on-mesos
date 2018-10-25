jenkins-on-mesos
==================


git clone https://github.com/Dataman-Cloud/jenkins-on-mesos.git && cd jenkins-on-mesos && curl -v -X POST \
-H 'Accept: application/json' \
-H 'Accept-Encoding:gzip,deflate' \
-H 'Content-Type: application/json;charset=utf-8' \
-H 'User-Agent: HTTPie/0.8.0' \
-d@marathon.json \
http://192.168.171.20:8080/v2/apps
