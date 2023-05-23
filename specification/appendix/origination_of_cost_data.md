# Origination of cost data

Cost data presented in the billing datasets originates from various sources depending on the purchasing mechanism. There are at least 3 different pieces of information that are important for understanding where cost originated from.

* Provider: The entity that made the resources and/or services available for purchase.
* Publisher: The entity that produced the resources and/or services that were purchased.
* Invoice Issuer: The entity responsible for invoicing for the resources and/or services consumed.

The value for each of these may be different depending on the various purchasing scenarios for resources and/or services. Use cases for purchasing direct, via a Managed Service Provider (MSP), via a cloud marketplace, and from internal service offerings were considered. The table below presents a few scenarios to show how the value for each dimension may change based on the purchasing scenario.

| #   | Scenario                                                                                                                                      | Provider                 | Publisher                                                                                                              | Invoice Issuer                                              |
|-----|-----------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| 1.1 | Purchasing cloud services directly from cloud provider                                                                                        | Cloud service provider   | Cloud service provider                                                                                                 | Cloud service provider                                     |
| 1.2 | Purchasing cloud services from the cloud provider where the cloud region is operated by a 3rd party                                           | Cloud service provider   | Cloud service provider                                                                                                 | Entity operating the region for the cloud service provider |
| 2.1 | Purchasing cloud services via MSP                                                                                                             | Managed Service Provider | Cloud service provider                                                                                                 | Managed Service Provider                                   |
| 2.2 | Purchasing cloud-agnostic resources and/or services built/sold by an MSP                                                                      | Managed Service Provider | Managed Service Provider                                                                                               | Managed Service Provider                                   |
| 2.3 | Purchasing labor services from managed service provider                                                                                       | Managed Service Provider | Managed Service Provider                                                                                               | Managed Service Provider                                   |
| 3.1 | Purchasing a cloud marketplace offering that runs on the cloud provider                                                                       | Cloud service provider   | Company building the software and/or services (Cloud service provider OR third-party software and/or services company) | Cloud service provider                                     |
| 3.2 | Purchasing a cloud marketplace offering that is not running directly on your cloud infrastructure (e.g,. SaaS product, Professional Services) | Cloud service provider   | Company producing the SaaS or services product                                                                         | Cloud service provider                                     |
| 3.3 | Purchasing a SaaS product that is not directly running on your cloud infrastructure from a 3rd party reseller managed cloud marketplace       | Cloud service provider   | SaaS provider                                                                                                          | Reseller                                                   |
| 4.1 | Purchasing SaaS software directly from provider                                                                                               | SaaS provider            | SaaS provider                                                                                                          | SaaS provider                                              |
| 4.2 | Purchasing SaaS software that additionally runs on your cloud resources (in addition to #4.1)                                                 | Cloud service provider   | Cloud service provider                                                                                                 | Cloud service provider                                     |
| 5.1 | Purchasing internal infrastructure and/or services offerings running on-premise                                                               | Internal product name    | Internal product name                                                                                                  | Internal product name                                      |
| 5.2 | Purchasing internal infrastructure and/or services offerings running on cloud                                                                 | Internal product name    | Internal product name                                                                                                  | Internal product name                                      |
| 5.3 | Associated software license cost for use on an on-premise infrastructure platform (Where license cost is presented separately in cost data)   | Internal product name    | Company producing the software                                                                                         | Internal product name                                      |