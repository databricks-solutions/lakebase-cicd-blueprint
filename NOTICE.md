## Support
Databricks does not offer official support for Databricks Solutions and its repository.
For any issue with this assets or the demos installed, please open an issue using github and the team will have a look on a best effort basis.

## Third-party software

This repository does not include third-party code. It uses these tools, which you install or which CI downloads:

| Tool | Used for | License |
|---|---|---|
| Databricks CLI 1.19.0 | Bundle validation and deploy; Lakebase CLI | Databricks License |
| Liquibase 4.33 | Postgres changelogs (Terraform path) | Apache-2.0 (Liquibase 5.0 and later use FSL-1.1-ALv2; stay on 4.x) |
| Terraform | Terraform path | BUSL-1.1 (Terraform 1.6 and later) |
| Databricks Terraform provider | Terraform path | Apache-2.0 |
| psycopg | Postgres client in the migration job and the example | LGPL-3.0 |
| PyYAML | Bundle code generation | MIT |
| pytest | Offline tests | MIT |
| GitHub Actions: actions/checkout, actions/setup-python | CI | MIT |
| GitHub Action: databricks/setup-cli | CI | Databricks License |
| GitHub Action: hashicorp/setup-terraform | CI | MPL-2.0 |
| GitHub Action: liquibase/setup-liquibase | CI | FSL-1.1-ALv2 (current release) |
| gitleaks 8.30.1 (CLI, downloaded in CI) | CI secret scan | MIT |

