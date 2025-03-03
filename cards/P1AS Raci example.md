## Sheet1
| Unnamed: 0 | Unnamed: 1 | Unnamed: 2 | Unnamed: 3 | Unnamed: 4 | Unnamed: 5 | Unnamed: 6 | Unnamed: 7 | Unnamed: 8 | Unnamed: 9 | Unnamed: 10 | Unnamed: 11 | Unnamed: 12 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| NaN | Customer | Product Management | Product Development\n(PF, PD, etc) | Professional Services | Development (Beluga and Container) | BRASS\n(beluga devops) | BEOP\n(beluga env ops) | GSO | Ping SRE | Versent SRE | Security | NOTES |
| Infrastructure | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN |
| Definition | NaN | NaN | NaN | C | C | NaN | NaN | I | C | A,R | C | NaN |
| Development | NaN | NaN | NaN | C | C | NaN | NaN | I | C | A,R | C | NaN |
| Deployment | NaN | NaN | NaN | C | C | NaN | NaN | I | C | A,R | NaN | NaN |
| Patching and Upgrades | NaN | NaN | NaN | I | I | NaN | NaN | I | R | A,R | NaN | NaN |
| Break Fix | NaN | NaN | NaN | I | I | NaN | NaN | C | A,R | A,R | NaN | NaN |
| In Scope Components (outside container) | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN |
| Customer Access Portal | NaN | NaN | NaN | I | I | NaN | NaN | I | I | A,R | I | NaN |
| P1AS API (Morty API and Cloud API) | NaN | NaN | NaN | I | I | NaN | NaN | I | I | A,R | I | Morty is API between CAP and Cloud API. Cloud API calls the orchestration factories |
| Orchestration (factories) | NaN | NaN | NaN | I | I | NaN | NaN | I | I | A,R | I | NaN |
| Base Operating System configuration | NaN | NaN | NaN | C | C | NaN | NaN | NaN | C | A,R | NaN | NaN |
| Volume Configuration | NaN | NaN | NaN | C | C | NaN | NaN | NaN | C | A,R | NaN | NaN |
| Build pipelines | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | I | A,R | NaN | NaN |
| Network - Runtime Connectivity | NaN | NaN | NaN | C | I | NaN | NaN | I,C | C | A,R | C | NaN |
| Network - Platform Hub and Infrastructure | NaN | NaN | NaN | I | I | NaN | NaN | I | I | A,R | C | NaN |
| Platform Services (storage, discovery, configuration, SIEM, infra logging, infra alerting) | NaN | NaN | C | C | C | NaN | NaN | A,R | A,R | NaN | NaN | NaN |
| AWS Account Provissioning | NaN | NaN | NaN | I | I | NaN | NaN | I | I | A,R | I | NaN |
| Cluster and Application | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN |
| Definition | NaN | A | R | C | R | NaN | NaN | C | I | I | C | This is split based on the split across architecture responsibilities; product teams are responsible for (e.g., logging) in products, while Beluga team is responsible for the same within the Beluga layer. |
| Development | NaN | A | R | I | R | NaN | NaN | I | I | I | C | This is split based on the split across architecture responsibilities; product teams are responsible for (e.g., logging) in products, while Beluga team is responsible for the same within the Beluga layer. |
| Release Management | NaN | I | NaN | I | R,A | NaN | NaN | I | I | I | NaN | NaN |
| Release Approval | NaN | NaN | NaN | A | C | NaN | NaN | A | R,A | R (If streamlined) | NaN | NaN |
| Deployment (New Customer) | NaN | NaN | NaN | R,A | I | NaN | NaN | I | I | I | NaN | NaN |
| Infrastructure Upgrades and Patches | NaN | NaN | NaN | I | C | NaN | NaN | C,I | R,A | R,A | NaN | NaN |
| Infrastructure Break Fix | NaN | NaN | C | I | C | NaN | NaN | C,I | R,A | R | NaN | NaN |
| In Scope Components (outside container) | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN |
| Ingress (proxy) | NaN | NaN | NaN | R | A | NaN | NaN | R | I | I | NaN | This is based on phase. |
| Loadbalancer | NaN | NaN | NaN | R | A | NaN | NaN | R | I | I | NaN | This is based on phase. |
| Kubernetes (Cluster state repo) | NaN | NaN | NaN | R | A | NaN | NaN | R | I | I | NaN | This is based on phase. |
| Container Management (POD placement / capacity management / storage tuning) | NaN | NaN | C | A,R | C | NaN | NaN | C | C | NaN | NaN | NaN |
| Application Logging (creation, tuning and information) | NaN | A | R | C | R | NaN | NaN | C | C | C | C | This is split based on the split across architecture responsibilities; product teams are responsible for (e.g., logging) in products, while Beluga team is responsible for the same within the Beluga layer. |
| Application Monitoring (creation, tuning and information) | NaN | C | C | R,A | C | NaN | NaN | R,A | I | I | NaN | This is based on phase. |
| Application Alerting (creation, tuning and information) | NaN | C | C | R,A | C | NaN | NaN | R,A | I | I | NaN | This is based on phase. |
| SSL Certificate Customer Management | A | NaN | NaN | R | NaN | NaN | NaN | R | I | NaN | NaN | This is based on phase. |
| SSL Certificate Internal | NaN | NaN | NaN | NaN | A,R | NaN | NaN | NaN | NaN | NaN | NaN | We need to solution this a bit more to account for ongoing maintenance. |
| Initial Application configuration and customer implementation | NaN | NaN | NaN | A,R | NaN | NaN | NaN | C | C | I | NaN | NaN |
| Ongoing Application configuration and customer implementation | NaN | NaN | NaN | C | I | NaN | NaN | A,R | NaN | NaN | NaN | NaN |
| Customer Application on-boarding | NaN | NaN | NaN | A,R | I | NaN | NaN | C | C | I | NaN | NaN |
| Customer backup monitoring and restore. | NaN | NaN | NaN | C | NaN | NaN | NaN | A,R | C | I | NaN | Is there an alarm? - Jason W. |
| Software Product Upgrade validation of customer configuration | NaN | NaN | NaN | NaN | NaN | NaN | NaN | A,R | NaN | NaN | NaN | Is there an alarm for customer upgrades? - Jason W. |
| Beluga Upgrades | C | NaN | NaN | NaN | C | NaN | NaN | A,R | I | I | NaN | NaN |
| Software Product (Public Docker Container) | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN |
| Definition | NaN | R,A | C,I | NaN | C,I | NaN | NaN | NaN | NaN | NaN | NaN | NaN |
| Development | NaN | A | R | I | R | NaN | NaN | I | NaN | NaN | NaN | This is split based on the split across architecture responsibilities; product teams are responsible for (e.g., logging) in products, while Beluga team is responsible for the same within the Beluga layer. |
| Deployment | NaN | NaN | A,R | NaN | A,R | NaN | NaN | I | I | I | NaN | This is split based on the split across architecture responsibilities; product teams are responsible for (e.g., logging) in products, while Beluga team is responsible for the same within the Beluga layer. |
| In Scope Components | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN |
| Ping Federate | NaN | A | R | I | C,I | NaN | NaN | I | NaN | NaN | NaN | NaN |
| Ping Directory | NaN | A | R | I | C,I | NaN | NaN | I | NaN | NaN | NaN | NaN |
| Ping Access | NaN | A | R | I | C,I | NaN | NaN | I | NaN | NaN | NaN | NaN |
| P14C | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN | NaN |
| Connectors Configuration and Deploy | NaN | NaN | NaN | A,R | NaN | NaN | NaN | R | NaN | NaN | NaN | This is based on phase. |
| Connector Customer WAS | NaN | NaN | NaN | A,R | NaN | NaN | NaN | I | NaN | NaN | NaN | BW: See above |
| P14C Administrator Onboard/Off-board | NaN | NaN | NaN | NaN | A | NaN | NaN | NaN | R | NaN | I | NaN |
| Platform Administrator Onboard/Off-board i.e SRE, GSO, Beluga | NaN | NaN | NaN | A | NaN | NaN | NaN | NaN | NaN | NaN | I | This is based on phase. |
| MFA configuration | NaN | NaN | NaN | A,R | NaN | NaN | NaN | I | NaN | NaN | NaN | This is based on phase. |
| CAP Administrator i.e. SRE Beluga | NaN | NaN | NaN | A | NaN | NaN | NaN | NaN | NaN | NaN | I | This is based on phase. |
| CAP Administrator - Customer | NaN | NaN | NaN | A | NaN | NaN | NaN | NaN | NaN | NaN | I | This is based on phase. |
| CAP ProServ/Support user on-boarding/off-boarding | NaN | NaN | NaN | A | NaN | NaN | NaN | A | NaN | R | I | NaN |
| Customer Creation | NaN | NaN | NaN | A / R | I | NaN | NaN | I | I | I | NaN | NaN |