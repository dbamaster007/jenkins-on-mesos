jenkins-on-mesos
==================


MESOS_HOSTNAME=192.168.171.20 \
PORT=8080 \
git clone https://github.com/dbamaster007/jenkins-on-mesos.git && cd jenkins-on-mesos && curl -v -X POST \\
-H 'Accept: application/json' \\
-H 'Accept-Encoding:gzip,deflate' \\
-H 'Content-Type: application/json;charset=utf-8' \\
-H 'User-Agent: HTTPie/0.8.0' \\
-d@marathon.json \\
http://$MESOS_HOSTNAME:$PORT/v2/apps
