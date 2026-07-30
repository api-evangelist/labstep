# Labstep

Labstep is a cloud-based Electronic Lab Notebook (ELN) and research data management platform for life-science, chemistry and pharma R&D teams. It combines step-by-step interactive protocols, structured experiment data capture, inventory and sample management with QR scanning, order management, instrument/device integration, chemistry and sequence tooling, and integrated Jupyter Notebooks for analysis — all under an audit trail with electronic signatures and sample lineage.

Labstep exposes a public REST API at `https://api.labstep.com` secured with a per-user API key (`apikey` header), plus an officially maintained Python SDK (`labstepPy` / PyPI `labstep`) and an R package (`labstepR`) that wrap the same generic entity surface used by the application itself.

- Website: https://www.labstep.com
- API getting started: https://help.labstep.com/en/articles/1786226-getting-started-with-the-labstep-api
- SDK reference: https://labsteppy.readthedocs.io/en/latest/
- GitHub: https://github.com/Labstep

## Artifacts

| Artifact | Path | Method |
|---|---|---|
| Packages / SDKs | `packages/labstep-packages.yml` | searched |
| Authentication | `authentication/labstep-authentication.yml` | searched |
| Conventions | `conventions/labstep-conventions.yml` | searched |
| Conformance | `conformance/labstep-conformance.yml` | searched |
| Changelog | `changelog/labstep-changelog.yml` | searched |
| Lifecycle | `lifecycle/labstep-lifecycle.yml` | searched |
| Well-known | `well-known/labstep-well-known.yml` | searched (all 404) |
| Domain security | `security/labstep-domain-security.yml` | probed |
| Error contract | `errors/labstep-error-codes.yml` | derived |
| Data model | `data-model/labstep-data-model.yml` | derived |
| llms.txt | `llms/labstep-llms.txt` | generated |

## Not published by Labstep

No OpenAPI/Swagger definition, no AsyncAPI or webhook surface, no MCP server, no OAuth authorization server or scopes, no CLI, no sandbox/test-credential program, no public status page, and no `security.txt` or vulnerability disclosure policy.
