# Open Source Container Resources
A curated list of amazingly awesome open source container resources.


## Table of Contents

- [Spec](#spec)
- [Containers and Runtimes](#containers-and-runtimes)
- [OS and Platforms](#os-and-platforms)
- [Orchestration and Cluster Management](#orchestration-and-cluster-management)
- [Networking](#networking)
- [Monitoring](#monitoring)
- [PaaS](#paas)
- [Hosting](#hosting)
- [Image Registry](image-registry)
- [Security](#security)
- [Infrastructure Services](infrastructure-services)


## Spec

- [App Container (appc)](https://github.com/appc/spec) - Specification for application containers. Appc defines several independent but composable aspects involved in running application containers, including an image format, runtime environment, and discovery mechanism for application containers.
- [Nulecule](https://github.com/projectatomic/nulecule) - A container based app specification that enables the use of existing containers as building blocks for new applications.
- [Opencontainers/specs](https://github.com/opencontainers/specs) - Specifications for standards on Operating System process and application containers.


## Containers and Runtimes

- [Docker](https://github.com/docker/docker) - Pack, ship and run any application as a lightweight container.
- [Docker Engine](https://www.docker.com/docker-engine) - A lightweight runtime and tooling that builds and runs your docker containers.
- [Garden](https://github.com/cloudfoundry-incubator/garden) - A platform-agnostic Go API for container creation and management, with pluggable backends for different platforms and runtimes.
- [Jetpack](https://github.com/3ofcoins/jetpack) - An experimental and incomplete implementation of the App Container Specification for FreeBSD. It uses jails as isolation mechanism, and ZFS for layered storage.
- [libct](https://github.com/xemul/libct) - Libct is a containers management library which provides convenient API for frontend programs to rule a container during its whole lifetime.
- [lmctfy](https://github.com/google/lmctfy) - lmctfy is the open source version of Google’s container stack, which provides Linux application containers.
- [LXC](https://github.com/lxc/lxc) - A set of tools, templates, library and language bindings. Its pretty low level, very flexible and covers just about every containment feature supported by the upstream kernel.
- [LXD](https://github.com/lxc/lxd) - A REST API, command line tool and OpenStack integration plugin for LXC.
- [mbox](https://github.com/tsgates/mbox) - A lightweight sandboxing mechanism that any user can use without special privileges in commodity operating systems.
- [MINCS](https://github.com/mhiramat/mincs) - A collection of shell scripts for light-weight containers.
- [nosecone](https://github.com/cdaylward/nosecone) - A C++ App Container implementation that uses the libappc App Container library.
- [OpenVZ](https://github.com/OpenVZ) - Container-based virtualization for Linux.
- [Rkt](https://github.com/coreos/rkt) - A CLI for running app containers on Linux. rkt is designed to be composable, secure, and fast. Based on AppC specification.
- [runc](https://github.com/opencontainers/runc) - runc is a CLI tool for spawning and running containers according to the OCS specification.
- [systemd-nspawn](http://fedoraproject.org/wiki/Features/SystemdLightweightContainers)
- [Vagga](https://github.com/tailhook/vagga) - A fully-userspace container engine inspired by Vagrant and Docker, specialized for development environments.
- [warden](https://github.com/cloudfoundry/warden) - Manages isolated, ephemeral, and resource controlled environments.
- [zerovm](https://github.com/zerovm/zerovm) - A simple virtual machine that can run (and isolate) 64-bit x86 applications in a 32-bit address space. ZeroVM works under Linux x86_64.


## Development and Deployment Tools

- [Brooklyn](https://github.com/apache/incubator-brooklyn) - A library and control plane for deploying and managing distributed applications.
- [Centurion](https://github.com/newrelic/centurion) - A deployment tool for docker. Ships containers to/from a registry, running them on a fleet of hosts.
- [Chronos](https://github.com/mesos/chronos) - A distributed and fault-tolerant scheduler that runs on top of Mesos that can be used for job orchestration. Able to schedule jobs that run inside Docker containers.
- [Cloudbreak](https://github.com/sequenceiq/cloudbreak) - Cloudbreak helps users launch on-demand Hadoop clusters in the cloud or to any environment that supports Docker containers.
- [Codefresh](https://github.com/codefresh-io/cf-distribution) - Combines Docker tools with a web IDE based on Eclipse Orion. A complete development environment for Node.js with DevOps and QA teams.
- [Decking.io](https://github.com/meetfinch/decking) - Aims to simplify three core areas: building images based on local Dockerfiles, creating containers and orchestration of containers. originally alternative to Fig, now Docker compose. 
- [Docker Compose](https://github.com/docker/compose) - Compose is a tool for defining and running multi-container applications with Docker. 
- [Docker Hub](https://hub.docker.com/) - A cloud registry service for building and shipping application or service containers. It provides a centralised resluce for container image discovery, distribution and change management. 
- [Docker Machine](https://github.com/docker/machine) - Lets you create docker hosts on your computer.
- [Dockersh](https://github.com/Yelp/dockersh) - A login shell for machines with multiple users, it gives access to multiple users but allows for isolation between them. 
- [Dusty](https://github.com/gamechanger/dusty) - A development environment that provides OS X support for containers. Compares the tool to Vagrant and says it uses Docker Compose to orchestrate containers. 
- [Fabric8](https://github.com/fabric8io/fabric8) - An open source DevOps and Integration platform that is built as a set of microservices that run on top of Kubernetes and OpenShift v3. 
- [Ferry](https://github.com/jhorey/ferry) - A big data development environment. Lets you define, run and deploy big data applications on AWS, OpenStack and your local machine using Docker. 
- [Lorry](https://github.com/CenturyLinkLabs/lorry) - A Centurylink Cloud Utility and open source project that provides a graphical user interface for Docker compose YAML validation and composition.
- [Mantl](https://github.com/CiscoCloud/microservices-infrastructure) - An opensource platform for rapidly deloying globally distributed services. It works with tools such as Marathon, Mesos, Docker and Consul.
- [Packer](https://github.com/mitchellh/packer) - A tool for creating machine and container images for multiple platforms from a single source configuration.
- [Panamax](https://github.com/CenturyLinkLabs/panamax-ui) - A containerized app creator with an open source app marketplace hosted on github. Provides an interface for users of Docker, Fleet, CoreOS.
- [Powerstrip](https://github.com/ClusterHQ/powerstrip) - A tool for prototyping Docker extensions.
- [Shutit](https://github.com/ianmiell/shutit) - A tool for managing the Docker image building process, it expands on some of the capabilites of Dockerfiles.
- [Terraform](https://github.com/hashicorp/terraform) - A tool to build and launch infrastructure, including containers. 
- [Totem](https://github.com/totem) - A continuous delivery pipeline tool designed for microservices.
- [Vessel](https://github.com/awvessel/vessel) - Automates the setup and use of dockerized development environments. It requires both OS X and Vagrant to work properly.
- [Zodiac](https://github.com/CenturyLinkLabs/zodiac) - A lightweight tool, build on top of Docker compose, for easy deployment and rollback of Dockerized applications.


## OS and Platforms

- [Boot2docker](http://boot2docker.io/) - A lightweight linux distribution made specifically to run Docker containers. Intended to use with Docker Machine.
- [CoreOS](https://github.com/coreos) - A container-focused OS, designed for painless management in large clusters.
- [Project Atomic](https://github.com/projectatomic/) - Hosts run applications in Docker Containers with components based on RHEL, Fedora and CentOS. 
- [Project Photon](https://github.com/vmware/photon) - A linux container host, focused on running containerized applications in a virtualised environmemt.
- [RancherOS](https://github.com/rancher/os) - A 20MB Linux distro that runs the entire OS as Docker containers.
- [Project Photon](https://github.com/vmware/photon) - A linux container host, focused on running containerized applications in a virtualised environmemt.
- [Snappy Ubuntu Core](http://www.ubuntu.com/cloud/tools/snappy) - Perfect system for large-scale cloud container deployments, bringing transactional updates to the world’s favourite container platform.


## Orchestration and Cluster Management

- [BOSH](https://github.com/cloudfoundry/bosh) - An open source toolchain for orchestration of large distributed services that can be used with Docker containers. BOSH installs and updates software packages on large numbers of VMs over many IaaS providers.
- [Brooklyn](https://github.com/apache/incubator-brooklyn) - A library and control plane for deploying and managing distributed applications. 
- [Chronos](https://github.com/mesos/chronos) - A distributed and fault-tolerant scheduler that runs on top of Mesos that can be used for job orchestration. Chronos is natively able to schedule jobs that run inside Docker containers
- [Cloud Foundry Containers Service Broker](https://github.com/cloudfoundry-community/cf-containers-broker) - Allows users to provision services that runs inside a compatible container backend and bind applications to the service.
- [Cloud Foundry Lattice](https://github.com/cloudfoundry-incubator/lattice-release) - An open source project for running containerized workloads on a cluster. Lattice bundles up HTTP load balancing, a cluster scheduler, log aggregation and streaming and health management into an easy-to-deploy and easy-to-use package
- [CloudSlang](https://github.com/CloudSlang/cloud-slang) - A flow-based orchestration tool for managing deployed applications. It aims to automate DevOps workflows and offers Docker capabilities and integrations
- [Consul](https://github.com/hashicorp/consul) - A tool for service discovery and configuration. Consul is distributed, highly available and extremely scalable. 
- [Crane](https://github.com/michaelsauter/crane) - A lightweight wrapper around the Docker CLI that is used to orchestrate Docker containers. 
- [Docker Swarm](https://github.com/docker/swarm) - Offers native clustering for Docker by turning multiple Docker hosts into a single, virtual host. 
- [Dray](https://github.com/CenturyLinkLabs/dray) - An engine for managing the execution of container based workflows. It is Go application that provides a RESTful API for managing jobs and is most commonly used fo containers hosting long running services.
- [etcd](https://github.com/coreos/etcd) - A distributed, consistent key-value store for shared configuration and service discovery.
- [Fleet](https://github.com/coreos/fleet) - A distributed init system used to support cluster management and orchestration of containers. 
- [Flocker](https://github.com/ClusterHQ/flocker) - A data volume manager for Dockerized applications. 
- [ImageLayers](https://github.com/CenturyLinkLabs/imagelayers) - Allows Docker users to easily discover best practices for image construction, and aids in determining which images are most appropriate for their specific use cases.
- [Kitematic](https://github.com/docker/kitematic) - A graphic interface to manage Docker.
- [Kong](https://github.com/mashape/kong) - A management layer for APIs. It has the capability of orchestrating Dockerfiles.
- [Kontena](https://github.com/kontena/kontena) - A container orchestration tool. Abstracts containers into application services and establishes an internal network between linked services, making it easy to deploy and scale applications across multiple hosts.
- [Kubernetes](https://github.com/kubernetes/kubernetes) - An open source system for managing containerized applications across multiple hosts, providing basic mechanisms for deployment, maintenance, and scaling of applications.
- [MaestroNG](https://github.com/signalfx/maestro-ng) - An Orchestrator for Docker based, multi-host environments.
- [Magnum](https://github.com/openstack/magnum) - An OpenStack project which offers container orchestration engines for deploying and managing containers as first class resources in OpenStack.
- [Marathon](https://github.com/mesosphere/marathon) - An Apache Mesos framework for long running applications. Provides a REST API for starting, stopping and scaling applications. It lets users deploy, run and scale Docker containers. 
- [Mesos](https://github.com/apache/mesos) - A cluster manager that provides efficient resource isolation and sharing across distributed applications or frameworks. 
- [Panamax](https://github.com/CenturyLinkLabs/panamax-api) - A containerized app creator. Provides a friendly interface for users of Docker, Fleet & CoreOS. 
- [Percheron](https://github.com/ashmckenzie/percheron) - Used to manage image and containers.
- [Prometheus](https://github.com/prometheus/prometheus) - An opensource service monitoring system and time series database.
- [Shipyard](https://github.com/shipyard/shipyard) - Enables multihost Docker cluster management and is fully compatible with the Docker remote API.
- [Tectonic](https://tectonic.com/) - A platform combining Kubernetes and the CoreOS stack.


## Networking

- [Flannel](https://github.com/coreos/flannel) - A virtual network for hosting containers
- [Libnetwork](https://github.com/docker/libnetwork) - Provides a native Go implementation for connecting containers.
- [Project Calico](https://github.com/projectcalico/calico) - Provides Networking for OpenStack VMs as well as containers in a Docker environment. Each container gets its own IP and Security policy.
- [Weave](https://github.com/weaveworks/weave) - A container specific implementation of software defined networking across data centers. 
- [Wormhole](https://github.com/vishvananda/wormhole) - A namespace-aware socket-activated tunneling proxy. Allows you to securely connect ports together on different physical machines inside docker containers.


## Monitoring

- [cAdvisor](https://github.com/google/cadvisor) - Provides container users an understanding of the resource usage and performance characteristics of running containers.
- [Cloud Foundry Diego](https://github.com/cloudfoundry-incubator/diego-release) - Supports the scheduling and monitoring of Docker workloads.


## PaaS 

- [Cloud Foundry](https://github.com/cloudfoundry/cf-release) - An open platform as a service (PaaS) that provides a choice of clouds, developer frameworks, and application services. Cloud Foundry makes it faster and easier to build, test, deploy, and scale applications.
- [Deis](https://github.com/deis/deis) - A lightweight, open source PaaS, built on Docker and CoreOS, that makes it easy to deploy and manage applications on your servers. 
- [dokku](https://github.com/progrium/dokku) - A mini-PaaS inspired by Herokus workflow.
- [Flynn](https://github.com/flynn/flynn) - A micro PaaS built on Docker containers and optimized for service-oriented applications.
- [OpenShift v3](https://github.com/openshift/origin) - A PaaS built on Docker containers that orchestrates with Kubernetes. Includes Atomic and Red Hat Linux components.
- [Zenoss Control Center](https://github.com/control-center) -  A PAAS framework for deploying enterprise applications using docker.


## Hosting

- [Amazon EC2 Container Service](http://aws.amazon.com/ecs/)
- [Amazon Elastic Beanstalk](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker.html)
- [Giant Swarm](https://giantswarm.io/)
- [Google Container Engine](https://cloud.google.com/container-engine/)
- [Google App Engine Managed VM](https://cloud.google.com/appengine/docs/managed-vms/)
- [StackDock](https://stackdock.com/)
- [Triton](https://www.joyent.com/)
- [Tutum](https://www.tutum.co/)


## Private Container Image Registry

- [Google Container Registry](https://cloud.google.com/tools/container-registry/)
- [Quay.io](https://quay.io/)


## Security

- [CoreOS Clair](https://github.com/coreos/clair) - Open Source Vulnerability Analysis for containers.
- [Docker bench security](https://github.com/docker/docker-bench-security) - A script that checks for dozens of common best-practices around deploying Docker containers in production.
- [Notary](https://github.com/docker/notary) - Comprises a server and a client for running and interacting with trusted collections. Publishers can sign their content offline using highly secure keys. 


## Infrastructure Services

- [Clocker](https://github.com/brooklyncentral/clocker) - Create and manages a Docker Cloud infrastructure. Includes plugins for Project Calico and Weave.
- [Crate](https://github.com/crate/crate) - Uses SQL syntax for distributed queries across a cluster.
- [Pachydem](https://github.com/pachyderm/pachyderm) - Enables storage and analysis of data using containers. 
- [Portus](https://github.com/SUSE/Portus) - Acts both as an authorization server and as a user interface for Docker registry.
- [Registrator](https://github.com/gliderlabs/registrator) - Automatically registers and deregisters services for any Docker container. Supports pluggable service registries like consul and etcd.


