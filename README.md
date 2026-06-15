# OpenStack (openstack)

Open source cloud computing platform for building and managing public and private clouds, providing infrastructure as a service (IaaS) through a set of interrelated services including Compute (Nova), Object Storage (Swift), Block Storage (Cinder), Networking (Neutron), Identity (Keystone), Image (Glance), Orchestration (Heat), Database (Trove), DNS (Designate), and Load Balancer (Octavia). Each service exposes its own REST API; clients authenticate against Keystone and use the returned service catalog to discover per-region endpoints for the remaining services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud Platform
- Infrastructure as a Service
- Open Source
- Virtualization
- Linux Foundation

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### OpenStack Identity (Keystone) API

Keystone is the OpenStack Identity service that provides authentication, authorization, and a service catalog for an OpenStack cloud. Tokens issued by Keystone are required to call any other OpenStack service API. The v3 API exposes endpoints for tokens, users, groups, projects, domains, roles, role assignments, services, endpoints, and the service catalog.

- **Human URL:** [https://docs.openstack.org/api-ref/identity/v3/](https://docs.openstack.org/api-ref/identity/v3/)
- **Base URL:** `https://{keystone-host}:5000/v3`

#### Tags

- Identity
- Authentication
- Authorization
- Service Catalog

#### Properties

- [Documentation](https://docs.openstack.org/api-ref/identity/v3/)
- [Documentation](https://docs.openstack.org/keystone/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/openapi/openstack-keystone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/json-ld/openstack-context.jsonld)
- [Postman Collection](collections/openstack-keystone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-keystone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/openstack-nova.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-nova.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStack Compute (Nova) API

Nova is the OpenStack Compute service that manages the lifecycle of compute instances (virtual machines, bare-metal, containers). The API exposes endpoints for servers, flavors, images, key pairs, security groups, attached volumes, and lifecycle actions such as start, stop, reboot, resize, rebuild, and snapshot.

- **Human URL:** [https://docs.openstack.org/api-ref/compute/](https://docs.openstack.org/api-ref/compute/)
- **Base URL:** `https://{nova-host}/compute/v2.1`

#### Tags

- Compute
- Virtual Machines
- Bare Metal

#### Properties

- [Documentation](https://docs.openstack.org/api-ref/compute/)
- [Documentation](https://docs.openstack.org/nova/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/openapi/openstack-nova-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/json-schema/openstack-server-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/json-ld/openstack-context.jsonld)
- [Postman Collection](collections/openstack-keystone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-keystone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/openstack-nova.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-nova.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStack Networking (Neutron) API

Neutron provides networking as a service, exposing endpoints for networks, subnets, ports, routers, floating IPs, security groups, load balancers, firewalls, and VPN-as-a-Service.

- **Human URL:** [https://docs.openstack.org/api-ref/network/](https://docs.openstack.org/api-ref/network/)
- **Base URL:** `https://{neutron-host}/networking/v2.0`

#### Tags

- Networking
- SDN
- Security Groups

#### Properties

- [Documentation](https://docs.openstack.org/api-ref/network/)
- [Documentation](https://docs.openstack.org/neutron/)
- [Postman Collection](collections/openstack-keystone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-keystone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/openstack-nova.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-nova.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStack Block Storage (Cinder) API

Cinder provides persistent block-level storage volumes that can be attached to Nova instances. The v3 API exposes endpoints for volumes, snapshots, backups, volume types, attachments, transfers, and quotas.

- **Human URL:** [https://docs.openstack.org/api-ref/block-storage/](https://docs.openstack.org/api-ref/block-storage/)
- **Base URL:** `https://{cinder-host}/volume/v3`

#### Tags

- Block Storage
- Volumes
- Snapshots

#### Properties

- [Documentation](https://docs.openstack.org/api-ref/block-storage/)
- [Documentation](https://docs.openstack.org/cinder/)
- [Postman Collection](collections/openstack-keystone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-keystone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/openstack-nova.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-nova.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStack Object Storage (Swift) API

Swift is the OpenStack object storage service. The API exposes endpoints for accounts, containers, and objects with eventual- consistency replication, large-object support, and configurable access controls.

- **Human URL:** [https://docs.openstack.org/api-ref/object-store/](https://docs.openstack.org/api-ref/object-store/)
- **Base URL:** `https://{swift-host}/v1/AUTH_{tenant_id}`

#### Tags

- Object Storage
- Containers
- Replication

#### Properties

- [Documentation](https://docs.openstack.org/api-ref/object-store/)
- [Documentation](https://docs.openstack.org/swift/)
- [Postman Collection](collections/openstack-keystone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-keystone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/openstack-nova.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-nova.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStack Image (Glance) API

Glance manages disk and server images. The v2 API exposes endpoints for images, image members, image tags, image data upload/download, tasks, schemas, and metadata definitions.

- **Human URL:** [https://docs.openstack.org/api-ref/image/](https://docs.openstack.org/api-ref/image/)
- **Base URL:** `https://{glance-host}/image/v2`

#### Tags

- Images
- Disk Images

#### Properties

- [Documentation](https://docs.openstack.org/api-ref/image/)
- [Documentation](https://docs.openstack.org/glance/)
- [Postman Collection](collections/openstack-keystone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-keystone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/openstack-nova.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-nova.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStack Orchestration (Heat) API

Heat is the OpenStack orchestration service that manages infrastructure-as-code deployments via HOT (Heat Orchestration Template) and AWS CloudFormation-compatible templates. The API exposes endpoints for stacks, resources, events, software configs, and template validation.

- **Human URL:** [https://docs.openstack.org/api-ref/orchestration/](https://docs.openstack.org/api-ref/orchestration/)
- **Base URL:** `https://{heat-host}/heat-api/v1`

#### Tags

- Orchestration
- Infrastructure as Code

#### Properties

- [Documentation](https://docs.openstack.org/api-ref/orchestration/)
- [Documentation](https://docs.openstack.org/heat/)
- [Postman Collection](collections/openstack-keystone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-keystone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/openstack-nova.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-nova.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStack Load Balancer (Octavia) API

Octavia provides Load Balancing as a Service. The v2 API exposes endpoints for load balancers, listeners, pools, members, health monitors, L7 policies and rules, and TLS containers.

- **Human URL:** [https://docs.openstack.org/api-ref/load-balancer/](https://docs.openstack.org/api-ref/load-balancer/)
- **Base URL:** `https://{octavia-host}/load-balancer/v2`

#### Tags

- Load Balancer
- LBaaS

#### Properties

- [Documentation](https://docs.openstack.org/api-ref/load-balancer/)
- [Documentation](https://docs.openstack.org/octavia/)
- [Postman Collection](collections/openstack-keystone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-keystone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/openstack-nova.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-nova.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStack DNS (Designate) API

Designate is the OpenStack DNS-as-a-Service. The v2 API exposes endpoints for zones, recordsets, pools, transfers, and TSIG keys.

- **Human URL:** [https://docs.openstack.org/api-ref/dns/](https://docs.openstack.org/api-ref/dns/)
- **Base URL:** `https://{designate-host}/dns/v2`

#### Tags

- DNS
- DNSaaS

#### Properties

- [Documentation](https://docs.openstack.org/api-ref/dns/)
- [Documentation](https://docs.openstack.org/designate/)
- [Postman Collection](collections/openstack-keystone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-keystone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/openstack-nova.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-nova.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStack Database (Trove) API

Trove is the OpenStack Database-as-a-Service that provisions and manages database instances (MySQL, PostgreSQL, MongoDB, Redis, MariaDB, Cassandra, etc.) on top of OpenStack.

- **Human URL:** [https://docs.openstack.org/api-ref/database/](https://docs.openstack.org/api-ref/database/)
- **Base URL:** `https://{trove-host}/database/v1.0`

#### Tags

- Database
- DBaaS

#### Properties

- [Documentation](https://docs.openstack.org/api-ref/database/)
- [Documentation](https://docs.openstack.org/trove/)
- [Postman Collection](collections/openstack-keystone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-keystone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/openstack-nova.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstack-nova.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/openstack)
- [Website](https://www.openstack.org/)
- [Portal](https://docs.openstack.org/)
- [Documentation](https://docs.openstack.org/api-ref/)
- [Getting Started](https://docs.openstack.org/api-quick-start/)
- [Community](https://www.openstack.org/community/)
- [Blog](https://www.openstack.org/blog/)
- [GitHub Organization](https://github.com/openstack)
- [Source Code](https://opendev.org/openstack)
- [Terms of Service](https://www.openstack.org/legal/)
- [License](https://www.apache.org/licenses/LICENSE-2.0)
- [Organization](https://www.openstack.org/foundation/)
- [Integrations](https://www.openstack.org/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
