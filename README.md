# ELK

This document uses to record ELK Arch

logstash(shipper) -> redis/rabbitmq -> logstash（indexer） -> es cluster -> kibana  （ELK）

logstash(shipper) -> kafka+zk -> logstash（indexer） -> es cluster -> kibana  （ELK）

logstash/filebat -> kafka+zk -> logstash（indexer） -> es cluster -> kibana  ?

fluentd -> kafka+zoo -> fluentd ->es clsuter -> kibana   EFK
