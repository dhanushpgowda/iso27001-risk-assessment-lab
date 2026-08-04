# Information Security Management System (ISMS) Scope

## Purpose
## Purpose
The purpose of this document is to define the boundaries and applicability of CloudCart's Information Security Management System (ISMS). Establishing a clearly defined scope ensures that information security risks are assessed consistently and that security controls are applied to the assets, processes, people, and technologies supporting CloudCart's business operations.
## Scope Statement
The ISMS applies to the information assets, business processes, employees, technologies, and cloud infrastructure used by CloudCart Pvt. Ltd. to develop, operate, and support its cloud-based e-commerce platform.
The scope includes the production environment hosted on AWS, collaboration platforms, software development repositories, employee endpoints, customer information, and supporting business functions that contribute to the secure delivery of CloudCart's services.
## Business Functions Included
| Business Function    | Included |
| -------------------- | -------- |
| Software Development | YES       |
| IT Operations        | YES        |
| Information Security | YES        |
| Customer Support     | YES        |
| Human Resources      | YES        |
| Sales & Marketing    | YES        |
| Finance              | YES        |

## Information Assets Included
| Asset             | Reason Included             |
| ----------------- | --------------------------- |
| AWS Cloud         | Hosts SaaS platform         |
| Customer Database | Stores customer information |
| GitHub            | Stores source code          |
| Microsoft 365     | Business communication      |
| Jira              | Project tracking            |
| Confluence        | Documentation               |
| Employee Laptops  | Business operations         |
| Backup Storage    | Disaster recovery           |

## Physical Locations
Head Office

Bengaluru

Included
Remote Employees

Included
## Technology Environment
| Technology    | Purpose                |
| ------------- | ---------------------- |
| AWS           | Cloud hosting          |
| Microsoft 365 | Productivity           |
| GitHub        | Source code management |
| Jira          | Project management     |
| Confluence    | Documentation          |
| VPN           | Secure remote access   |
| MFA           | Authentication         |

## Third-Party Services
| Provider        | Service              |
| --------------- | -------------------- |
| AWS             | Cloud Infrastructure |
| Microsoft       | Productivity Suite   |
| GitHub          | Version Control      |
| Payment Gateway | Payment Processing   |
## Exclusions
| Excluded Item                              | Justification                  |
| ------------------------------------------ | ------------------------------ |
| Employee personal devices                  | Not managed by CloudCart       |
| Customer-owned infrastructure              | Outside organizational control |
| Third-party payment gateway infrastructure | Managed by provider            |
| Personal email accounts                    | Not approved for business use  |

## Assumptions
## Assumptions

This ISMS scope is based on a fictional SaaS organization.

The organization operates from a single office in Bengaluru.

AWS hosts the production environment.

Remote employees access company resources using secure VPN connections.

Third-party providers maintain their own infrastructure security under a shared responsibility model.
## Scope Boundary
                Customers

                     │

               Internet

                     │

          ---------------------

          CloudCart ISMS Scope

          ---------------------

            AWS Cloud

            GitHub

         Microsoft 365

          Employee PCs

         Customer Database

             VPN

             Backup

          ---------------------

      Payment Gateway

       (Outside Scope)
## Conclusion
The defined ISMS scope establishes clear boundaries for CloudCart's information security activities. By identifying the business functions, technologies, assets, and third-party services included within the scope, CloudCart can perform effective risk assessments and implement appropriate security controls that support its business objectives.
## ISO 27001 Mapping
## ISO 27001 Mapping

Primary Clause

- Clause 4.3 – Determining the Scope of the Information Security Management System

Supporting Concepts

- Organizational Context
- Interested Parties
- Risk-Based Thinking
- Asset Management
