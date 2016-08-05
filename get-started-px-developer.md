# Get Started with PX-Developer

## Step 1: Verify requirements

* Linux kernel 3.10 or greater
* Docker 1.10 or greater, configured with [devicemapper](https://docs.docker.com/engine/userguide/storagedriver/device-mapper-driver/#/configure-docker-with-devicemapper)
* An etcd 2.0 key/value store (Consul coming soon)
* Minimum resources per server:
  * 4 CPU cores
  * 4 GB RAM
*Recommended resources per server:
  * 12 CPU cores
  * 16 GB RAM
  * 128 GB Storage
  * 10Gb

## Step 2: Install and run PX-Developer

See our quick start guides:

* [Docker Compose Quick Start Installation for PX-Developer](https://github.com/portworx/px-dev/blob/master/install_with_compose.md)
* [Run PX-Developer on Ubuntu](https://github.com/portworx/px-dev/blob/master/install_run_ubuntu.md), [CentOS](https://github.com/portworx/px-dev/blob/master/install_run_rhel.md), and [CoreOS](https://github.com/portworx/px-dev/blob/master/install_run_coreos.md)

Run PX-Developer with Schedulers:

* Docker Swarm
* [Running PX-Developer with Kubernetes](https://github.com/portworx/px-dev/blob/master/install_with_k8s.md)
* [Running PX-Developer with Mesosphere](https://github.com/portworx/px-dev/blob/master/install_with_mesosphere.md)
* [Running PX-Developer with Rancher](https://github.com/portworx/px-dev/blob/master/run_with_rancher.md)

Run stateful containers with Docker volumes:

* [Scaling a Cassandra database with PX-Dev](cassandra.md)
* [Running the Docker registry with high availability](./blob/master/px-dev/examples/registry.md)
* [Running PostgreSQL from CrunchyData on PX volumes]()

Use our [pxctl CLI](https://github.com/portworx/px-dev/blob/master/cli_reference.md) to directly:

* View the cluster global capacity and health
* Create, inspect, and delete storage volumes
* Attach policies for IOPs prioritization, maximum volume size, and enable storage replication

Refer to [Technical FAQ and Troubleshooting](https://github.com/portworx/px-dev/blob/master/faq.md) if you run into an issue.

As you use PX-Developer, please share your feedback and ask questions. Find the team on [Google Groups](https://groups.google.com/forum/#!forum/portworx).

If your requirements extend beyond the scope of PX-Developer, please [contact Portworx](http://portworx.com/contact-us/) for information on PX-Enterprise.