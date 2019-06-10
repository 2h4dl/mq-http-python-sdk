# MQ Python HTTP SDK  
Alyun MQ Documents: http://www.aliyun.com/product/ons

Aliyun MQ Console: https://ons.console.aliyun.com

## Requires

Python version(=v1.0.0): [2.5, 3.0)

Python version(>v1.0.0): [2.5, ~)

## Install sdk by pip

1. install pip, see [document](https://pip.pypa.io/en/stable/installing/)
2. install sdk by pip

```bash
pip install mq_http_sdk
```
## Notice

MQClient, Producer, Consumer are not thread safe, please use multi instance in mutli thread.

## Samples

### V1.0.0 Samples
[Publish Message](https://github.com/aliyunmq/mq-http-samples/blob/master/python/producer.py)

[Consume Message](https://github.com/aliyunmq/mq-http-samples/blob/master/python/consumer.py)

### V1.0.1 Samples
[Publish Message](https://github.com/aliyunmq/mq-http-samples/tree/101-dev/python/producer.py)

[Consume Message](https://github.com/aliyunmq/mq-http-samples/tree/101-dev/python/consumer.py)

[Transaction Message](https://github.com/aliyunmq/mq-http-samples/tree/101-dev/python/trans_producer.py)
