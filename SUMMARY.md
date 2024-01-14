# Table of contents

## 🟠 General

* [Getting started](README.md)
* [What is it?](intro/about.md)
* [Features](intro/features.md)
* [Installation](intro/install.md)
* [Configuration](intro/config.md)
* [Contributing](intro/contributing.md)

## 👷 PHP Worker

* [Worker](php/worker.md)
* [Dynamic Workers Scaling](php/scaling.md)
* [Debugging](php/debugging.md)
* [Developer mode](php/developer.md)
* [Environment](php/environment.md)
* [RPC](php/rpc.md)

## 🟢 Customization

* [Building RR with a custom plugin](customization/build.md)
* [Events Bus](customization/events-bus.md)
* [Writing a Plugin](customization/plugin.md)
* [Writing a Middleware](customization/middleware.md)
* [Integrating with Golang Apps](customization/embedding.md)

## 🔵 App Server

* [Production Usage](app-server/production.md)
* [RR as AWS Lambda](app-server/aws-lambda.md)
* [CLI Commands](app-server/cli.md)
* [Docker Images](app-server/images.md)
* [RoadRunner with NGINX](app-server/nginx-with-rr.md)
* [Systemd](app-server/systemd.md)

## 🔌 Plugins

* [Intro into Plugins](plugins/intro.md)
* [Centrifuge (WebSockets)](plugins/centrifuge.md)
* [Configuration](plugins/config.md)
* [gRPC](plugins/grpc.md)
* [Server](plugins/server.md)
* [Service (Systemd)](plugins/service.md)
* [Locks](plugins/locks.md)
* [TCP](plugins/tcp.md)
* [Queues and Jobs](queues/overview.md)
* [KV](kv/overview.md)

## 🔐 Key-Value

* [Intro into KV](kv/overview.md)
* [Redis](kv/redis.md)
* [Memcached](kv/memcached.md)
* [BoltDG](kv/boltdb.md)
* [In-Memory](kv/memory.md)

## 📦 Queues and Jobs

* [Intro into Jobs](queues/overview.md)
* [RabbitMQ](queues/amqp.md)
* [Beanstalk](queues/beanstalk.md)
* [Kafka](queues/kafka.md)
* [BoltDB](queues/boltdb.md)
* [In-Memory](queues/memory.md)
* [NATS](queues/nats.md)
* [SQS](queues/sqs.md)

## 🕸️ HTTP

* [Intro into HTTP](http/http.md)
* [Streaming](http/resp-streaming.md)
* [RFC 7234 cache](http/cache.md)
* [gzip](http/gzip.md)
* [Headers and CORS](http/headers.md)
* [X-Sendfile](http/sendfile.md)
* [Static files](http/static.md)

## 📈 Logging and Observability

* [HTTP Access Logs](lab/access-logs.md)
* [AppLogger](lab/applogger.md)
* [Logger](lab/logger.md)
* [HealthChecks](lab/health.md)
* [Metrics](lab/metrics.md)
* [Grafana](lab/dashboards/dashboards.md)
* [OpenTelemetry](lab/otel.md)

## 🔀 Workflow Engine

* [Temporal.io](workflow/temporal.md)
* [Worker](workflow/worker.md)