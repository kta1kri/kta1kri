### Hi, I'm kta1kri 👋

Independent **security researcher** working on **coordinated vulnerability disclosure**.

I audit open-source projects and self-hosted software and report issues through each
project's responsible-disclosure channel. My focus:

- **Authorization & access control** — broken access control, IDOR, missing permission checks
- **Web & API security** — SSRF, injection, auth/scope bypass, webhook/IPN authenticity
- **Secrets & supply chain** — secret exposure in tooling/IaC, insecure defaults in CI/build

#### Merged security fixes (public)
- **[chirpstack/chirpstack #1024](https://github.com/chirpstack/chirpstack/pull/1024)** — restore a missing `ValidateGatewaysAccess` authorization check in the gateway API
- **[datalayer/jupyter-mcp-server #453](https://github.com/datalayer/jupyter-mcp-server/pull/453)** — bind the streamable-HTTP server to loopback by default and decouple CORS
- **[aiven/aiven-client #480](https://github.com/aiven/aiven-client/pull/480)** — restrict file mode on downloaded `service.key` / `service.cert`
- **[dmpe/terraform-provider-storagegrid #57](https://github.com/dmpe/terraform-provider-storagegrid/pull/57)** — mark `secret_access_key` as `Sensitive` on the S3-key resources (prevents secret exposure in plan/state)
- **[kamailio/kamailio-credits #11](https://github.com/kamailio/kamailio-credits/pull/11)** — credited for a security report

I also run small **security labs / PoCs** here on GitHub for CI/CD and IaC issue patterns,
and file coordinated-disclosure reports to many other projects (kept private while under
embargo).

#### Support
If my work has helped your project, sponsorship funds continued security research and
responsible disclosure. Thank you 🙏

_For security matters, please use the relevant project's security channel._
