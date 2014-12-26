# Awesome Sysadmin
A curated list of amazingly awesome open source sysadmin resources inspired by [Awesome PHP](https://github.com/ziadoz/awesome-php)

* [Awesome Sysadmin](#awesome-sysadmin)
  * [Backups](#backups)
  * [Cloning](#cloning)
  * [Cloud Computing](#cloud-computing)
  * [Cloud Storage](#cloud-storage)
  * [Code Review](#code-review)
  * [Collaborative Software](#collaborative-software)
  * [Configuration Management Database](#configuration-management-database)
  * [Configuration Management](#configuration-management)
  * [Continuous Integration & Continuous Deployment](#continuous-integration--continuous-deployment)
  * [Distributed Filesystems](#distributed-filesystems)
  * [DNS](#dns)
  * [Hosting Control Panels](#hosting-control-panels)
  * [IMAP/POP3](#imappop3)
  * [IT Asset Management](#it-asset-management)
  * [LDAP](#ldap)
  * [Log Management](#log-management)
  * [Monitoring](#monitoring)
  * [Metric & Metric Collection](#metric--metric-collection)
  * [Network Configuration Management](#network-configuration-management)
  * [Newsletter](#newsletters)
  * [NoSQL](#nosql)
  * [Packaging](#packaging)
  * [Queuing](#queuing)
  * [RDBMS](#rdbms)
  * [Security](#security)
  * [Service Discovery](#service-discovery)
  * [SMTP](#smtp)
  * [Software Containers](#software-containers)
  * [SSH](#ssh)
  * [Statistics](#statistics)
  * [Ticketing systems](#ticketing-systems)
  * [Troubleshooting](#troubleshooting)
  * [Project Management](#project-management)
  * [Version control](#version-control)
  * [Virtualization](#virtualization)
  * [VPN](#vpn)
  * [XMPP](#xmpp)
  * [Web](#web)
  * [Webmails](#webmails)
  * [Wikis](#wikis)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Books](#books)
  * [Editors](#editors)
  * [Newsletters](#newsletters)
  * [Repositories](#repositories)
  * [Websites](#websites)
* [Contributing](#contributing)

## Backups
*Backup software.*

* [Amanda](http://www.amanda.org/) - Client-server model backup tool.
* [Bacula](http://www.bacula.org) - Another Client-server model backup tool.
* [Backupninja](https://labs.riseup.net/code/projects/backupninja) - Lightweight, extensible meta-backup system.
* [Backuppc](http://backuppc.sourceforge.net/) - Client-server model backup tool with file pooling scheme.
* [Burp](http://burp.grke.org/) - Network backup and restore program.
* [Duplicity](http://duplicity.nongnu.org/) - Encrypted bandwidth-efficient backup using the rsync algorithm.
* [Lsyncd](https://github.com/axkibe/lsyncd) - Watches a local directory trees for changes, and then spawns a process to synchronize the changes. Uses rsync by default.
* [Rsnapshot](http://www.rsnapshot.org/) - Filesystem Snapshotting Utility.
* [SafeKeep](http://safekeep.sourceforge.net/) - Centralized pull-based backup using `rdiff-backup`.
* [TarSnap](https://www.tarsnap.com/) - Secure backup service with an open-source client.
* [UrBackup](http://www.urbackup.org/) - Another client-server backup system.
* [DREBS](https://github.com/dojo4/drebs) - AWS EBS backup script that supports strategies.

## Cloning
*Cloning software.*

* [Clonezilla](http://clonezilla.org/) - Partition and disk imaging/cloning program.
* [Fog](http://www.fogproject.org/) - Another computer cloning solution.
* [Redo Backup](http://redobackup.org/) - Easy Backup, Recovery and Restore.

## Cloud Computing

* [AppScale](http:/github.com/AppScale/appscale) - Open source cloud software with Google App Engine compatibility.
* [Archipel](http://archipelproject.org/) - Manage and supervise virtual machines using Libvirt.
* [CloudStack](http://cloudstack.apache.org/) - Cloud computing software for creating, managing, and deploying infrastructure cloud services.
* [Cobbler](http://www.cobblerd.org/) - Cobbler is a Linux installation server that allows for rapid setup of network installation environments.
* [Eucalyptus](https://www.eucalyptus.com/) - Open source private cloud software with AWS compatibility.
* [Mesos](http://mesos.apache.org/) - Develop and run resource-efficient distributed systems.
* [OpenNebula](http://opennebula.org/) - An user-driven cloud management platform for sysadmins and devops.
* [OpenStack](https://www.openstack.org/) - Open source software for building private and public clouds.
* [The Foreman](http://theforeman.org/) - Foreman is a complete lifecycle management tool for physical and virtual servers. FOSS.

## Cloud Orchestration

* [BOSH](http://docs.cloudfoundry.org/bosh/) -  IaaS orchestration platform originally written for deploying and managing Cloud Foundry PaaS, but also useful for general purpose distributed systems.
* [Cloudify](http://www.getcloudify.org/) -  Open source TOSCA-based cloud orchestration software platform written in Python and YAML.
* [Juju](https://juju.ubuntu.com/) - Cloud orechestration tool which manages services as charms, YAML configuration and deployment script bundles.
* [MCollective](http://puppetlabs.com/mcollective) - Ruby framework to manage server orchestration, developed by Puppet labs.
* [Overcast](http://andrewchilds.github.io/overcast/) - Deploy VMs across different cloud providers, and run commands and scripts across any or all of them in parallel via SSH.
* [Rundeck](http://rundeck.org/) - Simple orchestration tool.
* [Salt](http://www.saltstack.com/) - It's written in Python.

## Cloud Storage

* [git-annex assistant](http://git-annex.branchable.com/assistant/) - A synchronised folder on each of your OSX and Linux computers, Android devices, removable drives, NAS appliances, and cloud services.
* [ownCloud](https://owncloud.org) - Provides universal access to your files via the web, your computer or your mobile devices.
* [Seafile](http://seafile.com) - Another Open Source Cloud Storage solution.
* [SparkleShare](http://sparkleshare.org/) - Provides cloud storage and file synchronization services. By default, it uses Git as a storage backend.
* [Swift](http://docs.openstack.org/developer/swift/) - A highly available, distributed, eventually consistent object/blob store.
* [Syncthing](http://syncthing.net/) - Open Source system for private, encrypted and authenticated distrobution of data.

## Code Review
*Web Based collaborative code review system.*

* [Gerrit](https://code.google.com/p/gerrit/) - Based on the Git version control, it facilitates software developers to review modifications to the source code and approve or reject those changes.
* [Review Board](https://www.reviewboard.org/) - Available as free software uner the MIT License.

## Collaborative Software
*Collaborative software or groupware suites.*

* [Citadel/UX](http://www.citadel.org/) - Collaboration suite (messaging and groupware) that is descended from the Citadel family of programs.
* [EGroupware](http://www.egroupware.org/) - Groupware software written in PHP.
* [Horde Groupware](http://www.horde.org/apps/groupware) - PHP based collaborative software suite that includes email, calendars, wikis, time tracking and file management.
* [Kolab](https://www.kolab.org) - Another groupware suite.
* [SOGo](https://www.sogo.nu/) - Collaborative software server with a focus on simplicity and scalability.
* [Zimbra](https://www.zimbra.com/community/) - Collaborative software suite, that includes an email server and web client.

## Configuration Management Database
*Configuration management database (CMDB) software.*

* [i-doit](http://www.i-doit.org/) - Open Source IT Documentation and CMDB.
* [iTop](http://www.combodo.com/-Overview-.html) - A complete open source, ITIL, web based service management tool.
* [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.
* [Clusto](https://github.com/clusto/clusto) - Helps you keep track of your inventory, where it is, how it's connected, and provides an abstracted interface for interacting with the elements of the infrastructure.

## Configuration Management
*Configuration management tools.*

* [Ansible](http://www.ansibleworks.com/) -  It's written in Python and manages the nodes over SSH.
* [CFEngine](http://cfengine.com/) - Lightweight agent system. Configuration state is specified via a declarative language.
* [Chef](http://www.opscode.com/chef/) - It's written in Ruby and Erlang and uses a pure-Ruby DSL.
* [Fabric](http://www.fabfile.org/) - Python library and cli tool for streamlining the use of SSH for application deployment or systems administration tasks.
* [Pallet](http://palletops.com/) - Infrastructure definition, configuration and management via a Clojure DSL.
* [Puppet](http://puppetlabs.com/) - It's written in Ruby and uses Puppet's declarative language or a Ruby DSL.
* [Salt](http://www.saltstack.com/) - It's written in Python.
* [Slaughter](http://steve.org.uk/Software/slaughter/) - It's written in Perl.

## Continuous Integration & Continuous Deployment
*Continuous integration/deployment software.*

* [Buildbot](http://buildbot.net/) - Python-based toolkit for continuous integration.
* [Drone](https://github.com/drone/drone) - Continuous integration server built on Docker and configured using YAML files.
* [GitLab CI](https://www.gitlab.com/gitlab-ci/) - Based off of ruby. They also provide GitLab, which manages git repositories.
* [Go](http://www.go.cd/) - Open source continuous delivery server.
* [Jenkins](http://jenkins-ci.org/) - An extendable open source continuous integration server.
* [Vlad the Deployer](http://rubyhitsquad.com/Vlad_the_Deployer.html) - Deployment automation.

## Distributed Filesystems
*Network distributed filesystems.*

* [Ceph](http://ceph.com/) - Distributed object store and file system.
* [DRBD](http://www.drbd.org/) - Disributed Replicated Block Device.
* [LeoFS](http://leo-project.net) - Unstructured object/data storage and a highly available, distributed, eventually consistent storage system.
* [GlusterFS](http://www.gluster.org/) - Scale-out network-attached storage file system.
* [HDFS](http://hadoop.apache.org/) - Distributed, scalable, and portable file-system written in Java for the Hadoop framework.
* [Lustre](http://lustre.opensfs.org/) -  A type of parallel distributed file system, generally used for large-scale cluster computing.
* [MooseFS](http://www.moosefs.org/) - Fault tolerant, network distributed file system.
* [MogileFS](http://mogilefs.org/) - Application level, network distributed file system.
* [OpenAFS](http://www.openafs.org/) - Distributed network file system with read-only replicas and multi-OS support.
* [TahoeLAFS](https://tahoe-lafs.org/trac/tahoe-lafs) - secure, decentralized, fault-tolerant, peer-to-peer distributed data store and distributed file system.
* [XtreemFS](http://www.xtreemfs.org/) - XtreemFS is a fault-tolerant distributed file system for all storage needs.

## DNS
*DNS servers.*

* [Bind](https://www.isc.org/downloads/bind/) - The most widely used name server software.
* [djbdns](http://cr.yp.to/djbdns.html) - A collection of DNS applications, including tinydns.
* [Designate](https://wiki.openstack.org/wiki/Designate) - DNS REST API that support several DNS servers as its backend.
* [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) - A lightweight service providing DNS, DHCP and TFTP services to small-scale networks.
* [Knot](https://www.knot-dns.cz/) - High performance authoritative-only DNS server.
* [NSD](http://www.nlnetlabs.nl/projects/nsd/) - Authoritative only, high performance, simple name server.
* [PowerDNS](https://www.powerdns.com/) - DNS server with a variety of data storage back-ends and load balancing features.
* [Unbound](http://unbound.net/) - Validating, recursive, and caching DNS resolver.
* [Yadifa](http://yadifa.eu/) - Lightweight authoritative Name Server with DNSSEC capabilities powering the .eu top-level domain.

## Hosting Control Panels
*Web hosting control panels*

* [Ajenti](http://ajenti.org/) - Control panel for Linux and BSD.
* [Feathur](http://feathur.com) - VPS Provisioning and Management Software.
* [ISPConfig](http://www.ispconfig.org) - Hosting control panel for Linux.
* [VestaCP](http://www.vestacp.com/) - Hosting panel for Linux but with Nginx.
* [Virtualmin](http://www.virtualmin.com/) - Control panel for Linux based on webmin.
* [ZPanel](http://www.zpanelcp.com/) - Control panel for Linux, BSD, and Windows.

## IMAP/POP3
*IMAP/POP3 mail servers.*

* [Courier IMAP/POP3](http://www.courier-mta.org/imap/) - Fast, scalable, enterprise IMAP and POP3 server.
* [Cyrus IMAP/POP3](http://cyrusimap.org/) - Intended to be run on sealed servers, where normal users are not permitted to log in.
* [Dovecot](http://www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind.
* [Qpopper](http://www.eudora.com/products/unsupported/qpopper/) - One of the oldest and most popular server implementations of POP3.

## IT Asset Management
*IT Assets Management software.*

* [GLPI](http://www.glpi-project.org/spip.php?lang=en) - Information Resource-Manager with an additional Administration Interface.
* [OCS Inventory NG](http://www.ocsinventory-ng.org/en/) - Enables users to inventory their IT assets.
* [RackTables](http://racktables.org/) - Datacenter and server room asset management like document hardware assets, network addresses, space in racks, networks configuration.
* [Ralph](https://github.com/allegro/ralph) - Asset management, DCIM and CMDB system for large Data Centers as well as smaller LAN networks.
* [Snipe IT](http://snipeitapp.com/) - Asset & license management software.

## LDAP
*LDAP servers.*

* [389 Directory Server](http://port389.org) - Developed by Red Hat.
* [Apache Directory Server](http://directory.apache.org/) - Apache Software Foundation project written in Java.
* [Fusion Directory](http://www.fusiondirectory.org) - Improve the Management of the services and the company directory based on OpenLDAP.
* [OpenDJ](http://opendj.forgerock.org/) - Fork of OpenDS.
* [OpenDS](https://opends.java.net/) - Another directory server written in Java.
* [OpenLDAP](http://openldap.org/) - Developed by the OpenLDAP Project.

## Log Management
*Log management tools: collect, parse, visualize ...*

* [Elasticsearch](http://www.elasticsearch.org/) - A Lucene Based Document store mainly used for log indexing, storage and analysis.
* [Fluentd](http://www.fluentd.org/) - Log Collector and Shipper.
* [Flume](https://flume.apache.org/) - Distributed log collection and aggregation system.
* [Graylog2](http://graylog2.org/) - Pluggable Log and Event Analysis Server with Alerting options.
* [Heka](http://hekad.readthedocs.org/en/latest/) - Stream processing system which may be used for log aggregation.
* [Kibana](http://www.elasticsearch.org/overview/kibana/) - Visualize logs and time-stamped data.
* [Logstash](http://logstash.net/) - Tool for managing events and logs.
* [Octopussy](http://www.octopussy.pm) - Log Management Solution (Visualize / Alert / Report).

## Monitoring
*Monitoring software.*

* [Cacti](http://www.cacti.net) - Web-based network monitoring and graphing tool.
* [Cabot](http://cabotapp.com/) - Monitoring and alerts, similar to PagerDuty.
* [check_mk](http://mathias-kettner.com/check_mk.html) - Collection of extensions for Nagios.
* [Dash](https://github.com/afaqurk/linux-dash) - A low-overhead monitoring web dashboard for a GNU/Linux machine.
* [Icinga](https://www.icinga.org/) - Fork of Nagios.
* [LibreNMS](https://github.com/librenms/librenms/) - fork of Observium.
* [Monit](http://mmonit.com/monit/#home) - Small Open Source utility for managing and monitoring Unix systems.
* [Munin](http://munin-monitoring.org/) - Networked resource monitoring tool.
* [Naemon](http://www.naemon.org/) - Network monitoring tool based on the Nagios 4 core with performance enhancements and new features.
* [Nagios](http://www.nagios.org/) - Computer system, network and infrastructure monitoring software application.
* [Observium](http://www.observium.org/) - SNMP monitoring for servers and networking devices. Runs on linux.
* [OMD](http://omdistro.org/) - The Open Monitoring Distribution.
* [Opsview](http://www.opsview.com/solutions/core) - Based on Nagios 4, Opsview Core is ideal for small IT and test environments.
* [Riemann](http://riemann.io/) - Flexible and fast events processor allowing complex events/metrics analysis.
* [Sensu](http://sensuapp.org/) - Open source monitoring framework.
* [Sentry](https://getsentry.com/) - Application monitoring, event logging and aggregation.
* [Shinken](http://www.shinken-monitoring.org/) - Another monitoring framework.
* [Thruk](http://www.thruk.org/) - Multibackend monitoring webinterface with support for Naemon, Nagios, Icinga and Shinken.
* [Xymon](http://www.xymon.com/) - Network monitoring inspired by Big Brother.
* [Zabbix](http://www.zabbix.com/) - Enterprise-class software for monitoring of networks and applications.
* [Zenoss](http://community.zenoss.org) - Application, server, and network management platform based on Zope.

## Metric & Metric Collection
*Metric gathering and display software.*

* [Collectd](http://collectd.org/) - System statistic collection daemon.
* [Collectl](http://collectl.sourceforge.net/) - High precision system performance metrics collecting tool.
* [Dashing](http://dashing.io/) - Ruby gem that allows for rapid statistical dashboard development. An all HTML5 approach allows for big screen displays in data centers or conference rooms.
* [Diamond](https://github.com/BrightcoveOS/Diamond) - Python based statistic collection daemon.
* [Ganglia](http://ganglia.sourceforge.net/) - High performance, scalable RRD based monitoring for grids and/or clusters of servers. Compatible with Graphite using a single collection process.
* [Grafana](http://grafana.org/) - A Graphite & InfluxDB Dashboard and Graph Editor.
* [Graphite](http://graphite.readthedocs.org/en/latest/) - Open source scaleable graphing server.
* [InfluxDB](http://influxdb.com/) - Open source distributed time series database with no external dependencies.
* [KairosDB](https://code.google.com/p/kairosdb/) - Fast distributed scalable time series database, fork of OpenTSDB 1.x.
* [OpenTSDB](http://opentsdb.net/) - Store and server massive amounts of time series data without losing granularity.
* [RRDtool](http://oss.oetiker.ch/rrdtool/) - Open source industry standard, high performance data logging and graphing system for time series data.
* [Statsd](https://github.com/etsy/statsd/) - Application statistic listener.

## Network Configuration Management
*Network configuration management tools.*

* [GestióIP](http://www.gestioip.net/) - An automated web based IPv4/IPv6 IP Address Management tool.
* [RANCID](http://www.shrubbery.net/rancid/) - Monitors network device's configurarion and maintain history of changes.
* [rConfig](http://www.rconfig.com/) - Another network device configuration management tool.

## Newsletters
*Newsletter software.*

* [DadaMail](http://dadamailproject.com/) - Mailing List Manager, written in Perl.
* [phpList](http://www.phplist.com/) - Newsletter manager written in PHP.

## NoSQL
*NoSQL databases.*

* Column-Family
  * [Apache HBase](http://hbase.apache.org/) - Hadoop database, a distributed, big data store.
  * [Cassandra](http://cassandra.apache.org/) - Distributed DBMS designed to handle large amounts of data across many servers.
  * [Hypertable](http://hypertable.org/) - C++ based BigTable-like DBMS, communicates through Thrift and runs either as stand-alone or on distributed FS such as Hadoop.
* Document Store
  * [CouchDB](http://couchdb.apache.org/) - Ease of use, with multi-master replication document-oriented database system.
  * [ElasticSearch](http://www.elasticsearch.org/) - Java based database, popular with log aggregation, and email archiving projects.
  * [MongoDB](http://www.mongodb.org/) - Another document-oriented database system.
  * [RavenDB](http://ravendb.net/) - Document based database with ACID/Transactional features.
  * [RethinkDB](http://www.rethinkdb.com/) - Open source distributed document store database, focuses on JSON.
* Graph
  * [FlockDB](https://github.com/twitter/flockdb) - Twitter's distributed, fault-tolerant graph database.
  * [Neo4j](http://www.neo4j.org/) - Open source graph database.
* Key-Value
  * [LevelDB](https://code.google.com/p/leveldb/) - Google's high performance key/value database.
  * [Redis](http://redis.io/) - Networked, in-memory, key-value data store with optional durability.
  * [Riak](http://basho.com/riak/) - Another fault-tolerant key-value NoSQL database.

Comparison of NoSQL servers: http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

## Packaging

* [fpm](https://github.com/jordansissel/fpm) - Versatile multi format package creator.
* [omnibus-ruby](https://github.com/opscode/omnibus-ruby) - Full stack, cross distro packaging software (Ruby).
* [packman](http://packman.readthedocs.org) - Full stack, cross distro packaging software (Python).
* [tito](https://github.com/dgoodwin/tito) - Builds RPMs for git-based projects.

## Queuing

* [BeanstalkD](http://kr.github.io/beanstalkd/) - A simple, fast work queue.
* [Gearman](http://gearman.org/) - Fast multi-language queuing/job processing platform.
* [NSQ](http://nsq.io/) - A realtime distributed messaging platform.
* [RabbitMQ](http://www.rabbitmq.com/) - Robust, fully featured, cross distro queuing system.
* [ZeroMQ](http://zeromq.org/) - Lightweight queuing system.

## RDBMS
*Relational DBMS.*

* [Firebird](http://www.firebirdsql.org/) - True universal open source database.
* [Galera](http://galeracluster.com/) - Galera Cluster for MySQL is an easy-to-use high-availability solution with high system up-time, no data loss, and scalability for future growth.
* [MariaDB](https://mariadb.org/) - Community-developed fork of the MySQL.
* [MySQL](http://dev.mysql.com/) - Most popular RDBMS server.
* [Percona Server](http://www.percona.com/software) - Enhanced, drop-in MySQL replacement.
* [PostgreSQL](http://www.postgresql.org/) - Object-relational database management system (ORDBMS).
* [PostgreSQL-XL](http://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based database cluster.
* [SQLite](http://sqlite.org/) - Library that implements a self-contained, serverless, zero-configuration, transactional SQL DBS.

## Security
*Security tools.*

* [Denyhosts](http://denyhosts.sourceforge.net/) - Thwart SSH dictionary based attacks and brute force attacks.
* [Fail2Ban](http://www.fail2ban.org/wiki/index.php/Main_Page) - Scans log files and takes action on IPs that show malicious behavior.
* [SpamAssassin](https://spamassassin.apache.org/) - A powerful and popular email spam filter employing a variety of detection techniques.

## Service Discovery

* [Consul](http://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
* [Doozerd](https://github.com/ha/doozerd) - Doozer is a highly-available, completely consistent store for small amounts of extremely important data.
* [ZooKeeper](http://zookeeper.apache.org/) - ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.

## SMTP
*SMTP servers.*

* [Exim](http://www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge.
* [Haraka](http://haraka.github.io/) - A high-performance, pluginable SMTP server written in JavaScript.
* [MailCatcher](http://mailcatcher.me/) - Ruby gem that deploys a simply SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development.
* [Maildrop](https://github.com/m242/maildrop) - Open Source disposable email SMTP server, also useful for development.
* [OpenSMTPD](https://opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project.
* [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement.
* [Qmail](http://cr.yp.to/qmail.html) - Secure Sendmail replacement.
* [Sendmail](http://www.sendmail.com/sm/open_source/) - Message transfer agent (MTA).

## Software Containers
*Operating system–level virtualization.*

* [Bitnami](https://bitnami.com/) - Produces open source installers or software packages for web applications and development stacks as well as virtual appliances.
* [Docker](http://www.docker.com/) - Open platform for developers and sysadmins to build, ship, and run distributed applications.
* [OpenVZ](http://openvz.org) - Container-based virtualization for Linux.

## SSH
*SSH tools.*

* [autossh](http://www.harding.motd.ca/autossh/) - Automatically respawn ssh session after network interruption.
* [Cluster SSH](http://sourceforge.net/projects/clusterssh/) - Controls a number of xterm windows via a single graphical console.
* [DSH](http://www.netfort.gr.jp/~dancer/software/dsh.html.en) - Dancer's shell / distributed shell - Wrapper for executing multiple remote shell commands from one command line.
* [Mosh](http://mosh.mit.edu/) - The mobile shell.
* [parallel-ssh](http://code.google.com/p/parallel-ssh/) - Provides parallel versions of OpenSSH and related tools.
* [SSH Power Tool](http://code.google.com/p/sshpt/) - Execute commands and upload files to many servers simultaneously without using pre-shared keys.

## Statistics
*Analytics software.*

* [Analog](http://www.analog.cx/) - The most popular logfile analyser in the world.
* [GoAccess](http://goaccess.io/) - Open source real-time web log analyzer and interactive viewer that runs in a terminal.
* [Piwik](http://piwik.org/) - Free and open source web analytics application.
* [Webalizer](http://www.webalizer.org/) - Fast, free web server log file analysis program.

## Ticketing systems
*Web-based ticketing system.*

* [Bugzilla](http://www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project.
* [Cerb](http://www.cerberusweb.com/) - A group-based e-mail management project built with a commercial open source license.
* [Flyspray](http://flyspray.org) - Web-based bug tracking system written in PHP.
* [MantisBT](http://www.mantisbt.org/) - Another web-based bug tracking system.
* [osTicket](http://osticket.com/) - Open source support ticket system.
* [Otrs](http://www.otrs.com/) - A free and open-source trouble ticket system software package that a company, organization, or other entity can use to assign tickets to incoming queries and track further communications about them.
* [Request Tracker](http://www.bestpractical.com/rt/) - Ticket-tracking system written in Perl.
* [TheBugGenie](http://www.thebuggenie.com) - Open source ticket system with extremely complete users rights granularity.

## Troubleshooting
*Troubleshooting Tools.*

* [mitmproxy](http://mitmproxy.org/) - A Python tool used for intercepting, viewing and modifying network traffic. Invaluable in troubleshooting certain problems.
* [Sysdig](http://www.sysdig.org/) - Capture system state and activity from a running Linux instance, then save, filter and analyze.
* [Wireshark](http://www.wireshark.org/) - The world's foremost network protocol analyzer.

## Project Management
*Web-based project management and bug tracking systems.*

* [ChiliProject](https://www.chiliproject.org) - Fork of Redmine.
* [GitBucket](https://github.com/takezoe/gitbucket) Clone of GitHub written in Scala; single jar install.
* [GitLab](https://www.gitlab.com/) - Clone of GitHub written in Ruby.
* [Gogs](http://gogs.io/) - Written in Go.
* [OpenProject](https://www.openproject.org) - Project collaboration with open source.
* [Phabricator](http://phabricator.org/) Written in PHP.
* [Redmine](http://www.redmine.org/) - Written in ruby on rails.
* [The Bug Genie](http://www.thebuggenie.com/) - Written in PHP.
* [Trac](http://trac.edgewall.org/) - Written in python.

## Version control
*Software versioning and revision control.*

* [Fossil](http://www.fossil-scm.org/) - Distributed version control with built-in wiki and bug tracking.
* [Git](http://git-scm.com/) - Distributed revision control and source code management (SCM) with an emphasis on speed.
* [GNU Bazaar](http://bazaar.canonical.com/) - Distributed revision control system sponsored by Canonical.
* [Mercurial](http://mercurial.selenic.com/) - Another distributed revision control.
* [Subversion](http://subversion.apache.org/) - Client-server revision control system.

## Virtualization
*Virtualization software.*

* [Ganeti](https://code.google.com/p/ganeti/) - Cluster virtual server management software tool built on top of KVM and Xen.
* [KVM](http://www.linux-kvm.org) - Linux kernel virtualization infrastructure.
* [oVirt](http://www.ovirt.org/) - Manages virtual machines, storage and virtual networks.
* [Packer](http://www.packer.io/) - A tool for creating identical machine images for multiple platforms from a single source configuration.
* [Vagrant](https://www.vagrantup.com/) - Tool for building complete development environments.
* [VirtualBox](https://www.virtualbox.org/) - Virtualization product from Oracle Corporation.
* [Xen](http://www.xenproject.org/) - Virtual machine monitor for 32/64 bit Intel / AMD (IA 64) and PowerPC 970 architectures.

## VPN
*VPN software.*

* [OpenVPN](https://community.openvpn.net) - Uses a custom security protocol that utilizes SSL/TLS for key exchange.
* [Pritunl](http://pritunl.com/) - OpenVPN based solution. Easy to set up.
* [SoftEther](https://www.softether.org/) - Multi-protocol software VPN with advanced features
* [sshuttle](https://github.com/apenwarr/sshuttle) - Poor man's VPN.
* [strongSwan](http://www.strongswan.org/) - Complete IPsec implementation for Linux.
* [tinc](http://www.tinc-vpn.org/) - Distributed p2p VPN.

## XMPP
*XMPP servers.*

* [ejabberd](http://www.ejabberd.im/) - XMPP instant messaging server written in Erlang/OTP.
* [Metronome IM](http://www.lightwitch.org/metronome) - Fork of Prosody IM.
* [MongooseIM](https://www.erlang-solutions.com/products/mongooseim-massively-scalable-ejabberd-platform) - Fork of ejabberd.
* [Openfire](http://www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server.
* [Prosody IM](http://prosody.im/) - XMPP server written in Lua.
* [Tigase](https://projects.tigase.org/projects/tigase-server) - XMPP server implementation in Java.

## Webmails
*Webmail applications.*

* [Mailpile](https://www.mailpile.is/) - A modern, fast web-mail client with user-friendly encryption and privacy features.
* [Roundcube](http://roundcube.net/) - Browser-based IMAP client with an application-like user interface.

## Web
*Web servers.*

* [Apache](http://httpd.apache.org/) - Most popular web server.
* [Cherokee](http://cherokee-project.com/) - Lightweight, high-performance web server/reverse proxy.
* [Lighttpd](http://www.lighttpd.net/) - Web server more optimized for speed-critical environments.
* [Nginx](http://nginx.org/) - Reverse proxy, load balancer, HTTP cache, and web server.
* [uWSGI](https://github.com/unbit/uwsgi/) - The uWSGI project aims at developing a full stack for building hosting services.

*Web Performance*

* [HAProxy](http://www.haproxy.org/) - Software based load Balancing, SSL offloading and performance optimization, compression, and general web routing.
* [Varnish](https://www.varnish-cache.org/) - HTTP based web application accelerator focusing on optimizing caching and compression.


## Wikis
*Wiki software.*

* [DokuWiki](https://www.dokuwiki.org/dokuwiki) - Simple to use and highly versatile wiki that doesn't require a database.
* [Gollum](https://github.com/gollum/gollum) - A simple, Git-powered wiki with a sweet API and local frontend.
* [ikiwiki](http://ikiwiki.info/) - A wiki compiler.
* [Mediawiki](http://www.mediawiki.org/wiki/MediaWiki) - Used to power Wikipedia.
* [MoinMoin](http://moinmo.in/) - An advanced, easy to use and extensible WikiEngine with a large community of users.
 * [Ōlelo Wiki](https://github.com/minad/olelo) - A a wiki that stores pages in a Git repository.
* [TiddlyWiki](http://tiddlywiki.com) - Complete interactive wiki in JavaScript.

# Resources
Various resources, such as books, websites and articles, for improving your skills and knowledge.

## Blogs

* [Code as Craft](http://codeascraft.com/) - Etsy's Ops blog, lots of technical posts.
* [DevOpsGuys](http://blog.devopsguys.com/) - Devops consultants who blog about operations.
* [Rackspace Developers](http://developer.rackspace.com/blog/) - Slightly biased blog with lots of Devops Topics.

## Books
*Sysadmin related books.*

* [The Linux Command Line](http://linuxcommand.org/tlcl.php) - A book about the Linux command line by William Shotts.
* [The Phoenix Project: A Novel about IT, DevOps, and Helping Your Business Win](http://itrevolution.com/books/phoenix-project-devops-book/) - How DevOps techniques can fix the problems that happen in IT organizations.
* [The Practice of System and Network Administration](http://everythingsysadmin.com/books.html) - The first and second editions describes the best practices of system and network administration, independent of specific platforms or technologies.
* [The Visible Ops Handbook: Implementing ITIL in 4 Practical and Auditable Steps](http://www.itpi.org/the-visible-ops-handbook-review.html) - Is a methodology designed to jumpstart implementation of controls and process improvement.
* [UNIX and Linux System Administration Handbook](http://www.admin.com/) - Approaches system administration from a practical perspective.

## Editors
*Open source code editors.*

* [Atom](https://atom.io/) - A hackable text editor from Github.
* [Brackets](http://brackets.io/) - Open source code editor for web designers and front-end developers.
* [Eclipse](http://eclipse.org/) - IDE written in Java with an extensible plug-in system.
* [Geany](http://www.geany.org/) - GTK2 text editor.
* [GNU Emacs](http://www.gnu.org/software/emacs/) - An extensible, customizable text editor-and more.
* [Haroopad](http://pad.haroopress.com/) - Markdown editor with live preview.
* [ICEcoder](http://icecoder.net) - Code editor awesomeness, built with common web languages.
* [jotgit](https://github.com/jdleesmiller/jotgit) - Git-backed real-time collaborative code editing.
* [Light Table](http://www.lighttable.com/) - The next generation code editor.
* [Lime](http://limetext.org/) - Aims to provide an open source solution to Sublime Text
* [TextMate](https://github.com/textmate/textmate/) - A graphical text editor for OS X.
* [Vim](http://www.vim.org) - A highly configurable text editor built to enable efficient editing.

## Newsletters

* [Servers for Hackers](http://serversforhackers.com/) - Newsletter for programmers who find themselves needing to know their way around a server.

## Repositories
*Software package repositories.*

* [Dotdeb](http://www.dotdeb.org/) - Repository with LAMP updated packages for Debian.
* [Remi](http://rpms.famillecollet.com/) - Repository with LAMP updated packages for RHEL/Centos/Fedora.

## Websites
*Useful sysadmin related websites.*

* [Ops School](http://www.opsschool.org) - Comprehensive program that will help you learn to be an operations engineer.
* [Digital Ocean Tutorials](https://www.digitalocean.com/community/tutorials) - A surprisingly vast resource for getting the basics of certain applications, tools, or even systems administration topics.

# Contributing
Please see [CONTRIBUTING](https://github.com/kahun/awesome-sysadmin/blob/master/CONTRIBUTING.md) for details.

灵感来自真棒PHP的惊人真棒开源系统管理员资源为策划名单

真棒系统管理员
备份
克隆
云计算
云存储
代码审查
协同软件
配置管理数据库
配置管理
持续集成和持续部署
分布式文件系统
DNS
主机控制面板
IMAP/ POP3
IT资产管理
LDAP
日志管理
监控
公制和指标收集
网络配置管理
通讯
NoSQL的
包装
排队
RDBMS
安全
服务发现
SMTP
软件容器
SSH
统计
票务系统
故障排除
项目管理
版本控制
虚拟化
VPN
XMPP
卷筒纸
提醒服务
维基
资源
博客
书籍
编者
简讯
资料库
网站
特约
备份

备份软件。

阿曼达 - 客户端 - 服务器模式的备份工具。
Bacula的 - 另一个客户端 - 服务器模式的备份工具。
Backupninja - 轻量级的，可扩展的元备份系统。
backuppc的 - 客户端 - 服务器模式的备份工具，文件池方案。
打嗝 - 网络备份和恢复程序。
口是心非 - 加密使用的rsync算法的带宽效率的备份。
Lsyncd - 手表的本地目录树的更改，然后生成一个进程同步的变化。默认使用的rsync。
Rsnapshot - 文件系统快照将实用程序。
保管 - 使用rdiff进行备份集中拉式备份。
TarSnap - 安全备份服务与开放源代码客户端。
UrBackup - 另一个客户 - 服务器备份系统。
DREBS - 支持策略AWS EBS备份脚本。
克隆

克隆软件。

Clonezilla的 - 分区和磁盘映像/克隆计划。
雾 - 另一台计算机克隆的解决方案。
重做备份 - 轻松备份，恢复和还原。
云计算

AppScale - 开源云计算软件与谷歌应用程序引擎的兼容性。
阿希佩尔 - 管理和监督使用libvirt的虚拟机。
的CloudStack - 云计算的软件，用于创建，管理和部署的基础设施云服务。
皮匠 - 鞋匠是一个Linux安装服务器，允许网络安装环境的快速设置。
桉树 - 开源私有云软件与AWS的兼容性。
Mesos - 开发并运行资源节约型分布式系统。
OpenNebula - 为系统管理员和DEVOPS一个用户驱动的云管理平台。
OpenStack的 - 构建私有云和公共云的开源软件。
工头 - 福尔曼是一个完整的生命周期管理工具，为物理和虚拟服务器。 FOSS。
云编排

- 波什的IaaS平台的业务流程最初用于部署和管理云的PaaS铸造写，也有用的通用分布式系统。
Cloudify - 开源TOSCA为基础的云编排软件平台用Python编写的YAML。
朱朱 - 云orechestration工具，管理服务的魅力，YAML配置和部署脚本包。
MCollective - Ruby框架，来管理服务器上的业务流程，通过木偶实验室开发。
阴 - 部署虚拟机在不同的云服务供应商，并通过运行SSH通过任何或所有命令和脚本并行。
Rundeck - 简单的业务流程的工具。
盐 - 它是用Python编写的。
云存储

混帐附件助手 - 在你的每一个OSX和Linux计算机，Android设备，可移动驱动器，NAS设备和云服务同步文件夹。
ownCloud - 提供通过网络，您的计算机或移动设备的普遍访问您的文件。
Seafile - 另一个开源云存储解决方案。
SparkleShare - 提供云存储和文件同步服务。默认情况下，它使用的Git作为存储后端。
斯威夫特 - 高可用，分布式的，最终一致的对象/ BLOB存储。
Syncthing - 数据的私有，加密和验证distrobution开源系统。
代码审查

基于Web的协作代码审查制度。

格里特 - 基于Git版本控制，它有利于软件开发人员审查修改源代码，并批准或拒绝这些更改。
审查委员会 - 可以免费UNER的MIT许可证的软件。
协同软件

协同软件或组件套件。

城堡/ UX - 协作套件（消息和群件），它是从城堡系列节目的后裔。
造成eGroupWare - 群件软件，用PHP编写的。
部落群件 - 基于PHP的协作软件套件，包括电子邮件，日历，维基，实时跟踪和文件管理。
Kolab - 另一个组件套件。
崇光百货 - 协同软件的服务器，重点是简单性和可扩展性。
Zimbra公司 - 协同软件套件，包括电子邮件服务器和Web客户端。
配置管理数据库

配置管理数据库（CMDB）软件。

I-DOIT - 开源IT文档和CMDB。
ITOP - 一个完整的开源，ITIL，基于Web的服务管理工具。
拉尔夫 - 资产管理，DCIM和CMDB系统，为大型数据中心以及较小的局域网。
Clusto - 帮助您保持您的库存，它在哪里，它是如何连接的轨道，并且提供了一个抽象的接口与基础设施元素进行交互。
配置管理

配置管理工具。

Ansible - 它是用Python编写，并通过SSH管理节点。
Cfengine的 - 轻量级代理系统。配置状态通过声明语言来指定。
厨师 - 这是写在Ruby和Erlang和使用纯Ruby DSL。
面料 - Python库和CLI工具简化使用SSH的应用程序部署和系统管理任务。
托盘 - 通过Clojure的DSL基础设施的定义，配置和管理。
木偶 - 它是用Ruby编写的，并使用木偶的声明性语言或Ruby的DSL。
盐 - 它是用Python编写的。
屠宰 - 它是用Perl编写。
持续集成和持续部署

持续集成/部署的软件。

的Buildbot - 基于Python的工具包，用于持续集成。
无人机 - 持续集成服务器构建于泊坞窗，用YAML文件来配置。
GitLab CI - 基于关红宝石。他们还提供GitLab，管理git仓库。
去 - 开源持续交付服务器。
詹金斯 - 一个可扩展的开源持续集成服务器。
弗拉德的部署 - 部署的自动化。
分布式文件系统

网络的分布式文件系统。

Ceph的 - 分布式对象存储和文件系统。
DRBD - Disributed复制块设备。
LeoFS - 非结构化对象/数据存储和高可用性，分布，最终一致的存储系统。
GlusterFS - 横向扩展网络附加存储文件系统。
HDFS - 分布式，可扩展和可移植的文件系统用Java编写的Hadoop框架。
光泽 - 一种并行分布式文件系统，一般用于大规模集群计算。
MooseFS - 容错，网络分布式文件系统。
MogileFS - 应用层，网络分布式文件系统。
OpenAFS的 - 分布式网络文件系统，只读副本和多操作系统的支持。
TahoeLAFS - 安全，分散，容错，对等网络的分布式数据存储和分布式文件系统。
XtreemFS - XtreemFS是所有存储需求的容错分布式文件系统。
DNS

DNS服务器。

结合 - 最广泛使用的域名服务器的软件。
djbdns - 的DNS应用，包括tinydns的集合。
指定 - 支持多个DNS服务器作为其后端DNS REST API。
的dnsmasq - 一个轻量级的服务于小规模的网络提供DNS，DHCP和TFTP服务。
结 - 高性能仅权威DNS服务器。
NSD - 唯一权威，高效，简单的名称服务器。
PowerDNS - 与各种数据存储后端和负载均衡功能的DNS服务器。
未绑定 - 验证，递归和缓存DNS解析。
Yadifa - 轻量级权威名称服务器与DNSSEC功能供电的.eu顶级域名。
主机控制面板

Web主机控制面板

Ajenti - 控制面板Linux和BSD。
Feathur - VPS配置和管理软件。
ISPConfig - 主机控制面板的Linux版本。
VestaCP - 主机面板上的Linux，但与Nginx的。
的Virtualmin - 控制面板Linux的基于webmin的。
ZPanel - 控制面板适用于Linux，BSD和Windows。
IMAP/ POP3

IMAP/ POP3邮件服务器。

快递IMAP/ POP3 - 快速，可扩展，企业的IMAP和POP3服务器。
赛勒斯IMAP/ POP3 - 打算在密封的服务器，其中普通用户不允许登录运行。
达夫科特 - IMAP和书面主要是安全意识POP3服务器。
Qpopper的 - 一个POP3的最古老和最流行的服务器实现的。
IT资产管理

IT资产管理软件。

GLPI - 信息资源管理器与一个额外的管理界面。
OCS库存NG - 使用户能够清查他们的IT资产。
RackTables - 像文档硬件资产，网络地址空间，机架，网络配置数据中心和服务器机房资产管理。
拉尔夫 - 资产管理，DCIM和CMDB系统，为大型数据中心以及较小的局域网。
狙击IT - 资产及许可证管理软件。
LDAP

LDAP服务器。

389目录服务器 - 由Red Hat开发。
Apache目录服务器 - 用Java编写的Apache软件基金会的项目。
融合目录 - 完善的服务和基于OpenLDAP的公司目录的管理。
OpenDJ - 叉OpenDS的了。
OpenDS的 - 用Java编写的另一个目录服务器。
OpenLDAP的 - 开发的OpenLDAP项目。
日志管理

日志管理工具：收集，分析，可视化...

Elasticsearch - 一种基于Lucene的文档存储主要用于日志索引，存储和分析。
Fluentd - 日志收集和托运人。
水槽 - 分布式日志收集和汇总系统。
Graylog2 - 可插拔日志和事件分析服务器与警报选项。
HEKA - 可被用于日志汇聚流处理系统。
Kibana - 可视化的日志和时间标记的数据。
Logstash - 管理事件和日志工具。
八爪 - 日志管理解决方案（可视化/警报/报告）。
监控

监控软件。

仙人掌 - 基于Web的网络监控和绘图工具。
卡博特 - 监控和警报，类似PagerDuty。
check_mk - 集扩展的Nagios。
短跑 - 低开销的监测网络仪表板的GNU/ Linux机器。
Icinga - Nagios的叉。
LibreNMS - Observium叉。
monit的 - 小的开源工具，用于管理和监控Unix系统。
穆宁 - 网络资源监控工具。
Naemon - 基于Nagios的4核心，性能改进和新功能的网络监控工具。
Nagios的 - 计算机系统，网络和基础设施监控的软件应用程序。
Observium - SNMP监测服务器和网络设备。在Linux上运行。
OMD - 开放式监控分布。
Opsview - 基于Nagios的4 Opsview核心非常适合小型IT环境和测试环境。
黎曼 - 灵活和快速的事件处理器，让复杂事件/指标分析。
狭义 - 开源监测框架。
哨兵 - 应用程序监控，事件记录和汇总。
进研 - 另一个监测框架。
Thruk - Multibackend监控webinterface与Naemon，Nagios的，Icinga和进研支持。
Xymon - 网络监控灵感大哥。
ZABBIX - 企业级软件，用于监测网络和应用。
Zenoss的 - 应用程序，服务器和网络管理基于Zope的平台。
公制和指标收集

公制采集和显示软件。

Collectd - 系统统计信息收集守护进程。
Collectl - 高精度系统的性能指标收集工具。
潇洒 - 红宝石的宝石，可以快速统计仪表板的发展。全HTML5方法允许大屏幕显示数据中心或会议室。
钻石 - 基于Python的统计信息收集守护进程。
神经节 - 高性能，可扩展的基于RRD监控电网和/或服务器集群。兼容使用单一收集过程石墨。
Grafana - 石墨及InfluxDB仪表板和图形编辑器。
石墨 - 开源可扩展的图形服务器。
InfluxDB - 开源分布式时间序列数据库，没有外部的依赖。
KairosDB - OpenTSDB1.x的快速分布式可扩展的时间序列数据库，叉
OpenTSDB - 存储与时间序列数据，而不会失去粒度服务器大量。
RRDtool的 - 开源行业标准，高性能的数据记录和绘图系统的时间序列数据。
Statsd - 应用统计听众。
网络配置管理

网络配置管理工具。

GestióIP - 基于IPv4 / IPv6双IP地址管理工具的自动化网络。
RANCID - 监控网络设备的configurarion和维护变化的历史。
rConfig - 另一个网络设备配置管理工具。
简讯

通讯软件。

DadaMail - 邮件列表管理器，用Perl编写的。
phpList - 通讯经理用PHP编写的。
NoSQL的

NoSQL数据库。

列家庭
Apache的HBase的 - Hadoop的数据库，分布式，大数据存储。
卡桑德拉 - 分布式设计来处理大量的跨多个服务器的数据的DBMS。
Hypertable - C++基于BigTable的样DBMS，通信，勤俭运行无论是作为独立或分布式FS如Hadoop的。
文档存储
CouchDB的 - 易于使用，多主复制面向文档的数据库系统。
ElasticSearch - 基于Java的数据库，很受日志聚合和电子邮件归档项目。
MongoDB的 - 另一个面向文档的数据库系统。
RavenDB - 基于文档的数据库与ACID/事务处理功能。
RethinkDB - 开源分布式文档存储数据库，专注于JSON。
图形
FlockDB - Twitter的分布式，容错图形数据库。
Neo4j的 - 开源图形数据库。
键 - 值
LevelDB - 谷歌的高性能键/值数据库。
Redis的 - 网络，内存，键值数据存储可选的耐用性。
Riak - 另一个容错键值的NoSQL数据库。
NoSQL的对服务器的比较：http://kkovacs.eu/cassandra-vs-mongodb-vs-couchdb-vs-redis

包装

FPM - 多功能多格式封装的创造者。
综合红宝石 - 全栈，交叉发行版包装软件（红宝石）。
帕克曼 - 全栈，交叉发行版包装软件（蟒蛇）。
蒂托 - 构建RPM包的git为基础的项目。
排队

BeanstalkD - 一个简单，快捷的工作队列。
Gearman的 - 快速的多语言排队/作业处理平台。
NSQ - 一种实时分布式通讯平台。
RabbitMQ的 - 坚固耐用，功能齐全，交叉发行排队系统。
ZeroMQ - 轻量级排队系统。
RDBMS

关系型数据库管理系统。

火鸟 - 真正的通用的开源数据库。
加莱拉 - 加莱拉集群为MySQL是一种具有高系统正常运行时间，无数据丢失，可扩展性和未来发展的一个易于使用的高可用性解决方案。
MariaDB - 社区开发了MySQL的分支。
MySQL的 - 最流行的RDBMS服务器。
Percona的服务器 - 增强，嵌入式MySQL的更换。
PostgreSQL的 - 对象关系型数据库管理系统（ORDBMS）。
PostgreSQL的-XL - 可扩展的开源基于PostgreSQL数据库集群。
SQLite的 - 库实现了一个自包含的，无服务器，零配置，事务性SQL DBS。
安全

安全工具。

的DenyHosts - 阻止SSH基于字典的攻击和暴力攻击。
的fail2ban - 扫描日志文件，并采取上显示恶意行为的IP行动。
SpamAssassin的 - 采用多种检测技术的强大和受欢迎的垃圾邮件过滤器。
服务发现

领事 - 领事是服务发现，监控和配置的工具。
Doozerd - 道崎是少量的极为重要的数据高可用性，完全一致的商店。
动物园管理员 - 动物园管理员是维护配置信息，命名，提供分布式的同步，并提供团体服务集中服务。
SMTP

SMTP服务器。

进出口 - 邮件传输代理（MTA）开发的剑桥大学。
Haraka - 用JavaScript编写的高性能，pluginable SMTP服务器。
MailCatcher - 红宝石的宝石，部署接受的所有邮件，并显示在网页界面简单SMTP MTA网关。可用于调试或发展。
信箱 - 开源一次性电子邮件的SMTP服务器，也有用开发。
OpenSMTPD - 从OpenBSD项目安全SMTP服务器实现。
后缀 - 快速，易于管理和安全Sendmail的更换。
Qmail的 - 安全Sendmail的替代品。
Sendmail的 - 邮件传输代理（MTA）。
软件容器

操作系统级的虚拟化。

汇出 - 产生开源安装程序或软件包的Web应用程序和开发堆栈以及虚拟设备。
泊坞窗 - 为开发人员和系统管理员建设，船舶和运行分布式应用程序的开放平台。
OpenVZ的 - 基于容器的虚拟化Linux操作系统。
SSH

SSH工具。

autossh - 自动网络中断后重生SSH会话。
集群SSH - 控制了许多的xterm窗口通过单一图形控制台。
DSH - 舞者的shell/分布式外壳 - 包装从一个命令行中执行多个远程shell命令。
MOSH - 移动外壳。
并行的ssh - 提供OpenSSH和相关工具的并行版本。
SSH电动工具 - 执行命令和文件上传到多台服务器同时不使用预共享密钥。
统计

分析软件。

模拟 - 世界上最流行的日志文件分析仪。
GoAccess - 开源实时Web日志分析和互动式阅读器运行在一个终端。
Piwik - 免费和开源的web分析应用。
Webalizer的 - 快速，免费的网络服务器日志文件分析程序。
票务系统

基于Web的售票系统。

Bugzilla的 - 通用的错误追踪系统和测试工具最初开发和使用的Mozilla项目。
Cerb - 建有一个商业开源许可证一组为基础的电子邮件管理项目。
Flyspray - 用PHP编写的基于Web的bug跟踪系统。
MantisBT - 另一种基于Web的bug跟踪系统。
osTicket - 开源的支持票系统。
OTRS - 一个自由和开放源码的故障单系统软件包，一个公司，组织或其他实体可以使用分配门票进入的查询和跟踪有关他们进一步沟通。
请求跟踪 - 用Perl编写的票务追踪系统。
TheBugGenie - 开源售票系统非常完善的用户权限粒度。
故障排除

故障排除工具。

mitmproxy - 用于拦截，查看和修改网络通信的Python的工具。无价的故障排除某些问题。
Sysdig - 捕获系统状态，并从运行Linux实例活动，然后保存，过滤和分析。
Wireshark的 - 世界上最重要的网络协议分析仪。
项目管理

基于Web的项目管理和bug跟踪系统。

ChiliProject - 叉管理平台的。
GitBucket克隆GitHub上用Scala编写的;单罐安装。
GitLab - GitHub上的克隆Ruby编写。
视护目镜 - 写在围棋。
OpenProject - 开源项目合作。
Phabricator用PHP编写的。
管理平台 - 写在Ruby on Rails的。
这个Bug精灵 - 写在PHP。
TRAC - 用Python编写的。
版本控制

软件版本控制和版本控制。

化石 - 分布式版本控制内置的wiki和缺陷跟踪。
Git的 - 分布式版本控制和源代码管理（SCM），重点是速度。
GNU集市 - 分布式由Canonical赞助的版本控制系统。
水银 - 另一个分布式版本控制。
颠覆 - 客户端 - 服务器版本控制系统。
虚拟化

虚拟化软件。

Ganeti - 基于KVM和Xen之上集群虚拟服务器管理软件工具。
KVM - Linux内核的虚拟化基础架构。
oVirt - 管理虚拟机，存储和虚拟网络。
帕克 - 从单一源配置创建相同的机映像为多个平台的工具。
无业游民 - 构建完整的开发环境工具。
VirtualBox虚拟 - 虚拟化的产品从Oracle公司。
Xen的 - 虚拟机监视器的32/64位Intel/ AMD（IA64）和PowerPC970架构。
VPN

VPN软件。

OpenVPN的 - 使用自定义的安全协议，它采用SSL/ TLS密钥交换。
Pritunl - OpenVPN的基础的解决方案。容易建立。
SOFTETHER - 多协议VPN软件具有先进功能
sshuttle - 穷人的VPN。
strongSwan - 完整的IPsec实现Linux操作系统。
TINC - 分布式P2P VPN。
XMPP

XMPP服务器。

的ejabberd - 写在二郎山/ OTP XMPP即时消息服务器。
节拍器IM - 韵律IM的叉。
MongooseIM - 的ejabberd的叉。
的Openfire - 实时协作（RTC）服务器。
韵律IM - XMPP服务器写在Lua。
Tigase - 在Java中XMPP服务器实现。
提醒服务

Webmail应用。

Mailpile - 一个现代的，快速的网络邮件客户端，方便用户加密和隐私保护功能。
Roundcube - 基于浏览器的IMAP客户端与应用程序类似的用户界面。
卷筒纸

Web服务器。

阿帕奇 - 最流行的Web服务器。
切诺基 - 轻型，高性能的Web服务器/反向代理。
lighttpd的 - 速度关键型环境的Web服务器更优化。
Nginx的 - 反向代理，负载平衡器，HTTP缓存和Web服务器。
uWSGI - 该uWSGI项目旨在开发一个完整的堆栈建设托管服务。
Web性能

HAProxy的 - 基于软件的负载均衡，SSL卸载和性能优化，压缩，和一般的网络路由。
清漆 - 基于HTTP的Web应用加速器重在优化缓存和压缩。
维基

维基软件。

DokuWiki的 - 使用简单和高度通用维基不需要数据库。
咕噜 - 一个简单的，Git的供电维基用甜美的API和当地的前端。
ikiwiki - 维基编译器。
对于MediaWiki - 用来为维基百科。
MoinMoin的 - 一个先进的，易于使用和可扩展WikiEngine与用户的大社区。
Ōlelo维基 - 一个维基存储在一个Git仓库页面。
的TW - 在JavaScript中完全互动的维基。
资源
各种资源，如书籍，网站和文章，提高你的技能和知识。

博客

代码工艺 - Etsy的的OPS博客，大量的技术岗位。
DevOpsGuys - DEVOPS顾问谁博客上操作。
Rackspace公司开发 - 略微偏博客，有很多的DevOps话题。
书籍

系统管理员相关书籍。

Linux命令行 - 一本关于威廉Shotts Linux命令行。
凤凰项目：关于IT，DevOps的一本小说，并帮助您的业务运 - 如何DevOps的技术可以解决这个问题发生在IT组织的问题。
系统和网络管理的实践 - 第一和第二版描述了系统和网络管理的独立于特定平台或技术的最佳实践。
可见OPS手册：实施ITIL在4实用和可审核的步骤 - 是一款专为快速启动实施控制和过程改进方法。
UNIX和Linux系统管理手册 - 途径系统管理从实践的角度。
编者

开放源代码编辑器。

原子 - 从Github上一个容易被破解的文本编辑器。
括号 - 开源代码编辑器网页设计师和前端开发人员。
日食 - IDE Java编写的与一个可扩展的插件系统。
Geany - GTK2的文本编辑器。
GNU Emacs的 - 一个可扩展的，可定制的文本编辑器，等等。
Haroopad - 降价编辑器，实时预览。
ICEcoder - 代码编辑器迷死人，建有常见的Web语言。
jotgit - 的Git支持实时协作代码编辑。
光表 - 下一代代码编辑器。
石灰 - 旨在提供一个开放源码的解决方案，以崇高的文本
TextMate的 - 一个图形化的文本编辑器OS X.
Vim的 - 内置，使高效编辑一个高度可配置的文本编辑器。
简讯

服务器的黑客 - 通讯程序员谁发现自己需要了解自己身边的服务器的方式。
资料库

软件库。

Dotdeb - 库与LAMP更新包的Debian。
雷米 - 库与LAMP更新包RHEL/ Centos的/ Fedora的。
网站

有用的系统管理员相关的网站。

训练学校 - 全面的计划，这将帮助你学习是一个操作工程师。
数字海洋教程 - 获取的某些应用程序，工具，甚至是系统管理主题的基础知识令人惊讶的巨大的资源。
特约
请参阅有助于了解详细信息。
