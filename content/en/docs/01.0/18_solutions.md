---
title: "1.8 Solution Overview"
linkTitle: "1.8 Solution Overview"
weight: 180
sectionnumber: 1.8
description: >
   Solution code for the Quarkus Techlabs
---

We have provided solution code for the labs in the folder `solution` of this `quarkus-techlab` project. You can find the source code of the `quarkus-techlab` on [GitHub]({{% param "github_repo" %}})

{{% alert color="warning" %}}
Be aware that in some solution projects like `quarkus-rest-data-producer` you'll find the solution code for multiple labs.
{{% /alert %}}

Chapter | Chapter Name                   | Solution Project
------- |--------------------------------|---------------------------------------------------------------------------------------
1.3  | Development                    | `dev-services`
2.1  | Your first Quarkus application | `quarkus-getting-started`
2.2  | Implementing REST Services     | `quarkus-rest-data-producer` and `quarkus-rest-data-consumer`
2.3  | REST Fault Tolerance           | `quarkus-rest-data-consumer`
2.4  | Health checks                  | `quarkus-rest-data-producer` and `quarkus-rest-data-consumer`
2.5  | Reactive Programming           | `quarkus-reactive-rest-producer` and `quarkus-reactive-rest-consumer`
3.3  | Hands on testing               | `quarkus-rest-data-producer`
4.2  | JVM Build                      | `quarkus-rest-data-producer` and `quarkus-rest-data-consumer`
8.2  | Reactive messaging with Kafka  | `quarkus-reactive-messaging-producer`, `quarkus-reactive-messaging-consumer` and `kafka-stack`
8.3  | Cloud Events                   | `quarkus-cloudevents-producer`, `quarkus-cloudevents-consumer` and `kafka-stack`
9.2  | Tracing with Jaeger            | `quarkus-opentelemetry-jaeger` and `opentelemetry-stack`
9.3  | Metrics with micrometer        | `quarkus-metrics-data-producer` and `opentelemetry-stack`
10   | Quarkus Extensions             | `techlab-extension-appinfo` and `quarkus-appinfo-application`
