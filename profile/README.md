<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/effecttrace/effecttrace/main/docs/assets/art/hero-dark.svg">
  <img src="https://raw.githubusercontent.com/effecttrace/effecttrace/main/docs/assets/art/hero-light.svg" alt="An agent's tool call linked to the Kubernetes changes it caused, with every relationship graded by its evidence and an unrelated change left disconnected." width="820">
</picture>

# EffectTrace

### Trace the effect, not just the call.

</div>

EffectTrace is an Apache-2.0 project for connecting agent/tool actions to observed Kubernetes and operational effects using evidence-graded relationships. It composes OpenTelemetry traces, Kubernetes audit events, object ownership and Prometheus signals into one effect graph, and it keeps direct evidence separate from temporal correlation.

- **Main project:** https://github.com/effecttrace/effecttrace
- **Website:** https://effecttrace.github.io/
- **Docs:** https://github.com/effecttrace/effecttrace/tree/main/docs

<sub>Temporal correlation does not prove causation.</sub>
