# OpenStack (openstack)

Open source cloud computing platform for building and managing public and private clouds, providing infrastructure as a service (IaaS) through a set of interrelated services including Compute (Nova), Object Storage (Swift), Block Storage (Cinder), Networking (Neutron), Identity (Keystone), Image (Glance), Orchestration (Heat), Database (Trove), DNS (Designate), and Load Balancer (Octavia). Each service exposes its own REST API; clients authenticate against Keystone and use the returned service catalog to discover per-region endpoints for the remaining services.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Cloud Platform, Infrastructure as a Service, Open Source, Virtualization, Linux Foundation

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### OpenStack Identity (Keystone) API
Keystone is the OpenStack Identity service that provides authentication, authorization, and a service catalog. Tokens issued by Keystone are required to call any other OpenStack service API.

**Human URL:** [https://docs.openstack.org/api-ref/identity/v3/](https://docs.openstack.org/api-ref/identity/v3/)

**Base URL:** https://{keystone-host}:5000/v3

#### Tags
- Identity, Authentication, Authorization, Service Catalog

#### Properties
- [Documentation](https://docs.openstack.org/api-ref/identity/v3/)
- [Documentation](https://docs.openstack.org/keystone/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/openapi/openstack-keystone-openapi.yml)
- [JSONLDContext](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/json-ld/openstack-context.jsonld)

### OpenStack Compute (Nova) API
Nova manages the lifecycle of compute instances (virtual machines, bare-metal, containers). The API exposes endpoints for servers, flavors, images, key pairs, security groups, attached volumes, and lifecycle actions such as start, stop, reboot, resize, rebuild, and snapshot.

**Human URL:** [https://docs.openstack.org/api-ref/compute/](https://docs.openstack.org/api-ref/compute/)

**Base URL:** https://{nova-host}/compute/v2.1

#### Tags
- Compute, Virtual Machines, Bare Metal

#### Properties
- [Documentation](https://docs.openstack.org/api-ref/compute/)
- [Documentation](https://docs.openstack.org/nova/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/openapi/openstack-nova-openapi.yml)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/json-schema/openstack-server-schema.json)
- [JSONLDContext](https://raw.githubusercontent.com/api-evangelist/openstack/refs/heads/main/json-ld/openstack-context.jsonld)

### OpenStack Networking (Neutron) API
Networking-as-a-Service: networks, subnets, ports, routers, floating IPs, security groups, load balancers, firewalls, VPNaaS.

**Human URL:** [https://docs.openstack.org/api-ref/network/](https://docs.openstack.org/api-ref/network/)

#### Tags
- Networking, SDN, Security Groups

#### Properties
- [Documentation](https://docs.openstack.org/api-ref/network/)
- [Documentation](https://docs.openstack.org/neutron/)

### OpenStack Block Storage (Cinder) API
Persistent block-level storage volumes that can be attached to Nova instances. v3 API: volumes, snapshots, backups, volume types, attachments, transfers, quotas.

**Human URL:** [https://docs.openstack.org/api-ref/block-storage/](https://docs.openstack.org/api-ref/block-storage/)

#### Tags
- Block Storage, Volumes, Snapshots

#### Properties
- [Documentation](https://docs.openstack.org/api-ref/block-storage/)
- [Documentation](https://docs.openstack.org/cinder/)

### OpenStack Object Storage (Swift) API
Object storage service. Exposes accounts, containers, objects with eventual-consistency replication, large-object support, and configurable access controls.

**Human URL:** [https://docs.openstack.org/api-ref/object-store/](https://docs.openstack.org/api-ref/object-store/)

#### Tags
- Object Storage, Containers, Replication

#### Properties
- [Documentation](https://docs.openstack.org/api-ref/object-store/)
- [Documentation](https://docs.openstack.org/swift/)

### OpenStack Image (Glance) API
Glance manages disk and server images. v2 API: images, image members, tags, image data, tasks, schemas, metadata definitions.

**Human URL:** [https://docs.openstack.org/api-ref/image/](https://docs.openstack.org/api-ref/image/)

#### Tags
- Images, Disk Images

#### Properties
- [Documentation](https://docs.openstack.org/api-ref/image/)
- [Documentation](https://docs.openstack.org/glance/)

### OpenStack Orchestration (Heat) API
Infrastructure-as-code via HOT and AWS CloudFormation-compatible templates. Endpoints for stacks, resources, events, software configs, template validation.

**Human URL:** [https://docs.openstack.org/api-ref/orchestration/](https://docs.openstack.org/api-ref/orchestration/)

#### Tags
- Orchestration, Infrastructure as Code

#### Properties
- [Documentation](https://docs.openstack.org/api-ref/orchestration/)
- [Documentation](https://docs.openstack.org/heat/)

### OpenStack Load Balancer (Octavia) API
LBaaS: load balancers, listeners, pools, members, health monitors, L7 policies/rules, TLS containers.

**Human URL:** [https://docs.openstack.org/api-ref/load-balancer/](https://docs.openstack.org/api-ref/load-balancer/)

#### Tags
- Load Balancer, LBaaS

#### Properties
- [Documentation](https://docs.openstack.org/api-ref/load-balancer/)
- [Documentation](https://docs.openstack.org/octavia/)

### OpenStack DNS (Designate) API
DNSaaS. v2 API: zones, recordsets, pools, transfers, TSIG keys.

**Human URL:** [https://docs.openstack.org/api-ref/dns/](https://docs.openstack.org/api-ref/dns/)

#### Tags
- DNS, DNSaaS

#### Properties
- [Documentation](https://docs.openstack.org/api-ref/dns/)
- [Documentation](https://docs.openstack.org/designate/)

### OpenStack Database (Trove) API
DBaaS that provisions and manages database instances (MySQL, PostgreSQL, MongoDB, Redis, MariaDB, Cassandra, etc.).

**Human URL:** [https://docs.openstack.org/api-ref/database/](https://docs.openstack.org/api-ref/database/)

#### Tags
- Database, DBaaS

#### Properties
- [Documentation](https://docs.openstack.org/api-ref/database/)
- [Documentation](https://docs.openstack.org/trove/)

## Common Properties

- [Website](https://www.openstack.org/)
- [Portal](https://docs.openstack.org/)
- [API Reference](https://docs.openstack.org/api-ref/)
- [API Quick Start](https://docs.openstack.org/api-quick-start/)
- [Community](https://www.openstack.org/community/)
- [Blog](https://www.openstack.org/blog/)
- [GitHubOrganization](https://github.com/openstack)
- [OpenDev Source](https://opendev.org/openstack)
- [Legal](https://www.openstack.org/legal/)
- [License - Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)
- [Open Infrastructure Foundation](https://www.openstack.org/foundation/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
