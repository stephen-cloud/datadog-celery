FROM datadog/agent:latest

ADD conf.d/redisdb.yaml /etc/datadog-agent/conf.d/redisdb.yaml
ADD conf.d/celery.yaml  /etc/datadog-agent/conf.d/celery.yaml

ADD checks.d/celery.py  /etc/datadog-agent/checks.d/celery.py
