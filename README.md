# TensorFlow

This is the base TensorFlow project.

Conatains:

- Jupyter for interactive development

- Tensorbard for monitoring training process

- Examples of training tasks

- Examples of distributed training tasks

echo $(hostname -i) $PROJECT_NAME-spark >> /etc/hosts && echo "spark.ui.proxyBase=$URL_PREFIX" > /etc/spark.conf  && APPLICATION_WEB_PROXY_BASE=$URL_PREFIX && spark-class -Dspark.ui.proxyBase=$URL_PREFIX org.apache.spark.deploy.master.Master --port 7077 --webui-port 8080 --host $PROJECT_NAME-spark