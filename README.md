# mvp-contributions

MVP contributions — Eber Perez.

Tracker público de contribuciones comunitarias hacia Microsoft MVP
(áreas objetivo: **Microsoft Foundry** e infraestructura de Azure).

## Fuente de verdad

- [`data/2026.yml`](data/2026.yml) — registro de entradas de este repositorio (`date`, `type`, `title`, `area`, `language`, `url`, `metric`, `role`, `impact`, `status`).
- La tabla de abajo se armó a mano a partir de esas entradas.

## Semana del 2026-11-02 al 2026-11-06

Cinco entradas con `status: published` en [`data/2026.yml`](data/2026.yml): 2 Article/Blog y 3 Online Support en Microsoft Q&A. Si `url` o `metric` está vacío en el YAML, la celda dice **pending**.

| Fecha | Tipo | Título | Área | Idioma | Rol | URL | Métrica |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 2026-11-02 | Article/Blog | Microsoft LiteBox: sandboxing local para agentes que escriben y ejecutan código | Microsoft Security / AI Agents | Spanish | Author | pending | pending |
| 2026-11-04 | Online Support | Azure OpenAI quota requests are not being approved | Microsoft Foundry / Azure OpenAI | English | Answerer | <https://learn.microsoft.com/en-us/answers/questions/6060484/azure-openai-quota-requests-are-not-being-approved> | pending |
| 2026-11-04 | Online Support | File Shares HDD: read latency different by access tier? | Azure Storage (Azure Files) | English | Answerer | <https://learn.microsoft.com/en-us/answers/questions/6025969/file-shares-hdd-read-latency-different-by-access-t> | pending |
| 2026-11-04 | Online Support | Flex Consumption scales beyond maximumInstanceCount | Azure Functions | English | Answerer | <https://learn.microsoft.com/en-us/answers/questions/6060474/flex-consumption-scales-beyond-maximuminstancecoun> | pending |
| 2026-11-06 | Article/Blog | Microsoft Execution Containers (MXC) en GA: contención del SO para agentes locales en Windows | Microsoft Security / Windows AI Agents | Spanish | Author | <https://www.linkedin.com/feed/update/urn:li:ugcPost:7524470068639125504/> | pending |

Impacto registrado en el YAML:

1. **2026-11-02 — Microsoft LiteBox.** Post comunitario sobre LiteBox v0.1.0 y su vínculo con Hyperlight/CodeAct en Agent Framework.
2. **2026-11-04 — Azure OpenAI quota requests are not being approved.** Respuesta en Microsoft Q&A sobre tiers de cuota Foundry/Azure OpenAI y qué revisar antes de reintentar.
3. **2026-11-04 — File Shares HDD: read latency different by access tier?** Respuesta en Microsoft Q&A aclarando que la latencia de Azure Files HDD no cambia por access tier.
4. **2026-11-04 — Flex Consumption scales beyond maximumInstanceCount.** Respuesta técnica en Microsoft Q&A sobre el techo real de maximumInstanceCount en Flex Consumption.
5. **2026-11-06 — Microsoft Execution Containers (MXC) en GA.** Post comunitario explicando MXC GA (Process/AppContainer, Session, WSL, MicroVM) para limitar agentes locales.

## Nota aparte

El 2026-11-04 se publicó un post de LinkedIn sobre Azure OpenAI Decisions API. El permalink sigue pendiente. Esa publicación no está en [`data/2026.yml`](data/2026.yml) y no forma parte de la tabla.

## Repo

https://github.com/eberd1977-blip/mvp-contributions
