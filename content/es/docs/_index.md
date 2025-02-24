---
title: Documentación
linkTitle: Docs
menu: { main: { weight: 10 } }
htmltest:
  IgnoreDirs:
    # TODO drop next lines after https://github.com/open-telemetry/opentelemetry.io/issues/5555 is fixed for these pages:
    - ^es/docs/concepts/glossary/
    - ^es/docs/concepts/instrumentation/zero-code/
    - ^es/docs/concepts/signals/baggage/
    - ^es/docs/zero-code/php/
default_lang_commit: f7cb8b65a478450d80d703b34c8473c579702108
---

OpenTelemetry, también conocido como OTel, es un framework de código abierto
neutral para proveedores de
[Observabilidad](concepts/observability-primer/#what-is-observability), diseñado
para instrumentar, generar, recopilar y exportar datos de telemetría como
[trazas](concepts/signals/traces/), [métricas](concepts/signals/metrics/) y
[logs](concepts/signals/logs/).

Como estándar de la industria, OpenTelemetry es
[compatible con más de 40 proveedores de observabilidad](/ecosystem/vendors/),
integrado por muchas
[bibliotecas, servicios y aplicaciones](/ecosystem/integrations/), y adoptado
por [numerosos usuarios finales](/ecosystem/adopters/).

![Arquitectura de Referencia de OpenTelemetry](/img/otel-diagram.svg)
