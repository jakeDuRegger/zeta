# zeta

zeta is a fast, flexible, and robust distributed system to process tasks across
AMQP 1.0 compatible brokers.

## Goals

1. Support all AMQP 1.0 compatible brokers.
2. Tasks may be written in any WASM compatible language.
3. Tasks may be scheduled to run on a cadence.
4. Modular, configurable design allowing bare metal execution or a full-harness
   that executes and saves task state similar to [Celery](https://docs.celeryq.dev/en/stable/).
5. Monitoring and observability plug-ins.

Libraries

1. [Apache Qpid Proton](https://qpid.apache.org/proton/index.html)
2. [OpenTelemetry Zig](https://github.com/open-telemetry/opentelemetry-zig)
3. [Wasmtime](https://github.com/extism/zig-sdk)
