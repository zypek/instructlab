# SAP on Red Hat Enterprise Linux - Complete Documentation Corpus

## Red Hat Enterprise Linux for SAP Solutions

# 8.x Release Notes

* * *

Red Hat Enterprise Linux for SAP Solutions 8

## Release Notes for Red Hat Enterprise Linux for SAP Solutions 8.x

Red Hat Customer Content Services

Legal Notice

**Abstract**

The Release Notes provide high-level coverage of the improvements and additions that have been implemented in Red Hat Enterprise Linux for SAP Solutions and document known problems, as well as notable bug fixes, Technology Previews, deprecated functionality, and other details. 

* * *

## Making open source more inclusive

Copy linkLink copied to clipboard!

Red Hat is committed to replacing problematic language in our code and documentation. We are beginning with these four terms: master, slave, blacklist, and whitelist. Due to the enormity of this endeavor, these changes will be gradually implemented over upcoming releases. For more details on making our language more inclusive, see our [CTO Chris Wright’s message](https://www.redhat.com/en/blog/making-open-source-more-inclusive-eradicating-problematic-language). 

## Providing feedback on Red Hat documentation

Copy linkLink copied to clipboard!

We appreciate your feedback on our documentation. Let us know how we can improve it. 

**Submitting feedback through Jira (account required)**

  1. Make sure you are logged in to the [Jira](https://issues.redhat.com/projects/RHELDOCS/issues/RHELDOCS-16677?filter=allopenissues) website. 
  2. Provide feedback by clicking on [this link](https://issues.redhat.com/secure/CreateIssueDetails!init.jspa?pid=12330720&issuetype=3&components=12387093&priority=10200&summary=Doc&description=Please+include+the+Document+URL,+the+section+number+and%20+describe+the+issue&labels=SAP_DOCS&customfield_12311140=SAPOCP-775&assignee=rh-ee-pmohta). 
  3. Enter a descriptive title in the **Summary** field. 
  4. Enter your suggestion for improvement in the **Description** field. Include links to the relevant parts of the documentation. 
  5. If you want to be notified about future updates, please make sure you are assigned as **Reporter**. 
  6. Click **Create** at the bottom of the dialogue. 



## Chapter 1. Overview

Copy linkLink copied to clipboard!

Red Hat® Enterprise Linux® for SAP Solutions combines the reliability, scalability, and performance of Linux with technologies that meet the specific requirements of SAP workloads. It is certified for integration with SAP S/4HANA® and built on the same foundation as the world’s leading enterprise Linux platform, Red Hat Enterprise Linux (RHEL). 

For more information on RHEL for SAP Solutions, see the [Red Hat Enterprise Linux for SAP Solutions](https://access.redhat.com/ecosystem/sap) product page. 

## Chapter 2. Supported architectures

Copy linkLink copied to clipboard!

The first version of Red Hat Enterprise Linux 8 for SAP Solutions to include E4S repositories and packages for SAP was RHEL 8.0 (kernel 4.18.0-80), which provides support for the following architectures: 

  * Intel 64-bit architecture (x86_64) 
  * IBM Power, Little Endian (ppc64le) 



For more information, see [Red Hat Enterprise Linux Technology Capabilities and Limits](https://access.redhat.com/articles/rhel-limits). 

Subsequent RHEL 8 versions that included E4S repositories and packages for SAP were: 

  * RHEL 8.1 (kernel 4.18.0-147) 
  * RHEL 8.2 (kernel 4.18.0-193) 
  * RHEL 8.4 (kernel 4.18.0-305) 
  * RHEL 8.6 (kernel 4.18.0-372) 



## Chapter 3. Included features

Copy linkLink copied to clipboard!

Built on the foundation of Red Hat Enterprise Linux, the RHEL for SAP Solutions subscription includes the following additional components: 

  * SAP-specific technical components to support S/4HANA, SAP HANA, and SAP Business Applications. 
  * High Availability solutions for S/4HANA, SAP HANA, and SAP Business Applications. 
  * RHEL System Roles for SAP, which can be used to automate the configuration of a RHEL system to run SAP workloads. 
  * Smart Management and Red Hat Insights for lifecycle management and proactive optimization. 
  * SAP HANA tested in-place upgrades and live kernel patching capabilities to maximize SAP business uptime. 
  * Update Services for SAP Solutions / Extended Update Support, providing up to four years of support on specified minor releases. 



## Chapter 4. Distribution of content

Copy linkLink copied to clipboard!

RHEL 8 for SAP Solutions is installed using ISO images. For more information, see [Installing RHEL 8 for SAP Solutions](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/configuring_rhel_8_for_sap_hana2_installation/proc_installing-rhel-8_configuring-rhel-8-for-sap-hana2-installation). 

For information on RHEL for SAP Solutions offerings on Certified Cloud Providers, see [SAP Offerings on Certified Cloud Providers](https://access.redhat.com/articles/3751271). 

**Installation Steps for Red Hat Enterprise Linux for SAP Solutions**

  1. After downloading, [perform your installation of Red Hat Enterprise Linux](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/configuring_rhel_8_for_sap_hana2_installation/proc_installing-rhel-8_configuring-rhel-8-for-sap-hana2-installation). 
  2. [Register and attach your server to a repository source](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/configuring_rhel_8_for_sap_hana2_installation/proc_registering-your-host_configuring-rhel-8-for-sap-hana2-installation) — either a local Red Hat Satellite instance or the Customer Portal Subscription Management service. 
  3. [Apply the release lock](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/configuring_rhel_8_for_sap_hana2_installation/proc_applying-the-rhel-release-lock_configuring-rhel-8-for-sap-hana2-installation) and [activate the SAP repositories in the Red Hat subscription manager](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/configuring_rhel_8_for_sap_hana2_installation/proc_enabling-required-repositories_configuring-rhel-8-for-sap-hana2-installation) to get access to the additional packages provided by the Red Hat Enterprise Linux for SAP Solutions subscription. 
  4. Execute the [Red Hat Enterprise Linux system roles for SAP](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/configuring_rhel_8_for_sap_hana2_installation/assembly_rhel-system-roles-for-sap_configuring-rhel-8-for-sap-hana2-installation) to automatically perform all required OS preconfiguration tasks to get started with the SAP workload installation afterwards. 
  5. When your Red Hat Enterprise Linux for SAP Solutions system is ready, you can [start your SAP installation](https://help.sap.com/docs/SAP_HANA_PLATFORM/2c1988d620e04368aa4103bf26f17727/7eb0167eb35e4e2885415205b8383584.html?version=2.0.04), for example SAP HANA Express Edition. 
  6. [Get predictive IT analytics](https://access.redhat.com/products/red-hat-insights#getstarted) with connecting your system to Red Hat Insights. This is included with your subscription. 



If you need help installing your product, contact Red Hat [Customer Service](https://access.redhat.com/support/contact/customerService) or [Technical Support](https://access.redhat.com/support/contact/technicalSupport). 

SAP specific content is available on separate SAP repositories and ISOs and only for SAP-supported architectures (Intel x86_64, IBM Power LE). 

See [How to subscribe SAP HANA systems to the Update Services for SAP Solutions](https://access.redhat.com/solutions/4714781). 

**Additional resources**

  * [Performing a standard RHEL installation](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html-single/performing_a_standard_rhel_installation/index)
  * [Package manifest](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/package_manifest/index)
  * [Considerations in adopting RHEL 8](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/considerations_in_adopting_rhel_8/index)



## Chapter 5. New features and enhancements

Copy linkLink copied to clipboard!

### 5.1. Red Hat Enterprise Linux 8.1 for SAP Solutions

Copy linkLink copied to clipboard!

  * You can use live patching to patch critical CVEs in the kernel without interrupting business critical SAP applications. With this enhancement, interruptions that result from system reboots are minimized. In previous releases, the initialization of in-memory databases, such as SAP HANA, could take several hours to load data into memory after an outage. 
  * SAPInstance: Integrating the upstream patch for systemd-based [SAP Start-Up Framework](https://access.redhat.com/articles/6884531). 
  * The `resource-agents-sap-hana` and `resource-agents-sap-hana-scaleout` packages provide resource agents for managing SAP HANA System Replication setups in combination with the RHEL HA Add-On. 
  * A new [rhel-system-roles-sap](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/red_hat_enterprise_linux_system_roles_for_sap/index) package is now available for Red Hat Enterprise Linux 8 as a Technology Preview. The `rhel-system-roles-sap` package provides Red Hat Enterprise Linux System Roles for SAP, which can be used to automate the configuration of a RHEL system to run SAP workloads. These roles greatly reduce the time to configure a system to run SAP workloads by automatically applying the optimal settings that are based on best practices outlined in relevant SAP Notes. 

Note

Access is limited to RHEL for SAP Solutions offerings. Contact Red Hat Customer Support if you need assistance with your subscription. 

This enhancement update adds `rhel-system-roles-sap` to Red Hat Enterprise Linux 8 for SAP Solutions The following new roles are now available: 

    * sap-preconfigure 
    * sap-netweaver-preconfigure 
    * sap-hana-preconfigure 

  * An update for `resource-agents-sap-hana-scaleout` is now available for Red Hat Enterprise Linux 8.1 Extended Update Support. 

The `resource-agents-sap-hana-scaleout` packages provide an SAP HANA scale-out resource agent interface with Pacemaker that allows SAP HANA scale-out instances to be managed in a cluster environment. For more information, see [Red Hat Enterprise Linux HA Solution for SAP HANA Scale-Out and System Replication](https://access.redhat.com/solutions/4386601). 




**Additional resources**

  * [Release Notes for Red Hat Enterprise Linux 8.1](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html-single/8.1_release_notes/index#masthead)



### 5.2. Red Hat Enterprise Linux 8.2 for SAP Solutions

Copy linkLink copied to clipboard!

  * SAP HANA users can now use the RHEL in-place upgrade to upgrade SAP environments from RHEL 7 to RHEL 8. For more information, see [How to in-place upgrade SAP environments from RHEL 7 to RHEL 8](https://access.redhat.com/solutions/5154031). 
  * Introducing support for IBM virtual Persistent Memory (vPMEM) and increasing [maximum amount of supported logical CPUs and physical memory](https://access.redhat.com/articles/rhel-limits) as an enhancement to IBM advanced virtualization platform (PowerVM) on Power9 processor. 
  * Introducing support for [Intel’s 3rd Generation Intel Xeon Scalable Processors](https://docs.google.com/document/d/1fJ6D9wiIshnBJuNNnS-GdtymAhHynKHZ02-e7fyOI3g/edit#heading=h.h6jcpoeulgwx) (formerly code-named Cooper Lake). 
  * RHEL System Roles for SAP, earlier shipped as a Tech Preview in RHEL 8.1 for SAP Solutions, are now General Available (GA). For more information, see [Red Hat Enterprise Linux System Roles for SAP](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html-single/red_hat_enterprise_linux_system_roles_for_sap/index). 
  * With this release, cgroup v2 is now fully supported. You can use V2 to protect the memory, where SAP Applications store data, for fast access from the Linux kernel memory management to obtain higher performance for SAP systems. 
  * The newly introduced [PCP HA Cluster PMDA](https://access.redhat.com/articles/6139852) for high-availability / pacemaker clusters allows customers using RHEL HA solutions for SAP to view their cluster health, node health, resource health and location constraints in near real-time, and marks an integral part of the Azure Monitor for SAP Solutions. 
  * By introducing a SAP application-focused view into Red Hat Insights, SAP administrators can automatically detect and display all of their SAP applications across numerous environments, to include accessing their application status and risk information, from a single panel. 
  * The resource agents for managing SAP HANA Scale-Out System Replication have been updated to also support HANA Multitarget Replication, with manual takeover. For more invormation, see [Red Hat Enterprise Linux HA Solution for SAP HANA Scale-Out and System Replication](https://access.redhat.com/solutions/4386601). 



**Additional resources**

  * [Release Notes for Red Hat Enterprise Linux 8.2](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html-single/8.2_release_notes/index#masthead)



### 5.3. Red Hat Enterprise Linux 8.4 for SAP Solutions

Copy linkLink copied to clipboard!

  * With the enhancement to Red Hat Enterprise Linux System Roles for SAP, customers can now not only configure, but also verify existing RHEL systems to be configured in-line with SAP Best Practices. 
  * Adding further automation to the RHEL HA solutions for SAP HANA, allowing pacemaker-based clusters configured for SAP HANA Multitarget System Replication to promote its secondary SAP HANA instances automatically as the new primary node for a third site, if the original primary instance fails. 
  * Enhancing support of [Red Hat Smart Management and Red Hat Insights](https://www.redhat.com/en/blog/red-hat-smart-management-sap) for SAP workloads. 
  * An update for the resource-agents-sap package is now available for Red Hat Enterprise Linux 8.4 Extended Update Support. 

The resource-agents-sap package contains SAP resource agents interface with Pacemaker to allow SAP instances to be managed in a cluster environment. 

  * An update for rhel-system-roles-sap is now available for Red Hat Enterprise Linux 8.4 Extended Update Support. The rhel-system-roles-sap package provides Red Hat Enterprise Linux (RHEL) System Roles for SAP that can be used to automate the configuration of a RHEL system to run SAP workloads. These roles greatly reduce the time to configure a system to run SAP workloads by automatically applying the optimal settings that are based on best practices outlined in relevant SAP Notes. 

Note

Access is limited to RHEL for SAP Solutions offerings. Contact Red Hat Customer Support if you need assistance with your subscription. 

  * An update for resource-agents-sap-hana-scaleout is now available for Red Hat Enterprise Linux 8. The resource agents for managing HANA Scale-Out System Replication have been updated to also support HANA Multitarget Replication. For more information, [Red Hat Enterprise Linux HA Solution for SAP HANA Scale-Out and System Replication](https://access.redhat.com/solutions/4386601). 
  * RHEL customers running SAP HANA still on RHEL 7.9 can now upgrade their operating system directly to RHEL 8.4 using the in-place upgrade tooling (LEAPP). 
  * The package compat-sap-c++-10 is now also available for RHEL 8.4 and later on platform s390x (IBM System Z). 



**Additional resources**

  * [Release Notes for Red Hat Enterprise Linux 8.4](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/8.4_release_notes/index)



### 5.4. Red Hat Enterprise Linux 8.6 for SAP Solutions

Copy linkLink copied to clipboard!

  * Adding support for SAP HANA cost-optimized RHEL HA scenarios, enabling customers to: 

    * Seamlessly run a QA/Test instance of SAP HANA on the secondary instance instead of idling the system. 
    * Have a S/4HANA application server and SAP HANA database managed within the same cluster. 
    * Run an SAP NetWeaver primary application server and additional application server on the same cluster node. 

For more information, see [Supported HA Scenarios for SAP HANA, SAP S/4HANA, and SAP NetWeaver](https://access.redhat.com/articles/4079981). 

  * Introduction of RHEL HA fencing agents for IBM Cloud Virtual Server (VPC) and IBM Power Systems Virtual Servers (VS), to allow secure and reliable setup of highly available SAP environments in context of IBM Cloud. 
  * Enhancing existing RHEL system roles for SAP by including the new role `sap_hana_install`, which can be used to install SAP HANA scale-up or scale-out database instances by means of Ansible automation. For more information, see [Red Hat Enterprise Linux System Roles for SAP](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/red_hat_enterprise_linux_system_roles_for_sap/con_new-features_rhel-system-roles-for-sap). 
  * Inclusion of Processor Counter Monitor (PCM) to ease monitoring of performance and energy metrics of Intel Core, Xeon, Atom and Xeon Phi processors, such as in the context of SAP HANA in-memory workloads. 
  * Starting with the latest SAP kernel packages / patch levels (shipping from April 2022 onward) SAP is supporting and enabling by default the systemd environment. All RHEL versions with Update Services for SAP Solutions, starting with RHEL 8.1, have been tested and verified by both Red Hat and SAP to assure the SAP changes with the new `systemd` based SAP startup framework run with no issues. 
  * Added in-place upgrade tool support for SAP HANA customers to go from RHEL 7.9 for SAP Solutions to RHEL 8.6 for SAP Solutions. For more information, see [How to in-place upgrade SAP environments from RHEL 7 to RHEL 8 - Red Hat Customer Portal](https://access.redhat.com/solutions/5154031). 
  * With the release of RHEL 8.6, the location of `sap.conf`, which is used to permanently increase `kernel.pid_max` to ensure the number of tasks per user satisfies the need of the SAP HANA database, has changed from `/etc/sysctl.d/` to `/usr/lib/sysctl.d/`. For more information, see [SAP Note 2777782 - SAP HANA DB: Recommended OS Settings for RHEL 8](https://launchpad.support.sap.com/#/notes/2777782). 



**Additional resources**

  * [Release Notes for Red Hat Enterprise Linux 8.6](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/8.6_release_notes/index)



### 5.5. Red Hat Enterprise Linux 8.9 for SAP Solutions

Copy linkLink copied to clipboard!

  * When using the HA solutions for managing HANA Multitarget System Replication, it is also possible to set up a separate inactive cluster for managing the HANA instances at the DR site, which can be activated manually in the event of the primary cluster becoming unavailable. For more details, please refer to [Configuring SAP HANA Scale-Up Multitarget System Replication for disaster recovery](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/configuring_sap_hana_scale-up_multitarget_system_replication_for_disaster_recovery/index). 
  * RHEL HA solutions for SAP now support managing SAP HANA Multitarget System Replication for both HANA Scale-Up and HANA Scale-Out environments, allowing for automated failover with 3 and more replicates. For more details, please refer to [Multitarget System Replication](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/red_hat_ha_solutions_for_sap_hana_s4hana_and_netweaver_based_sap_applications/asmb_sh_ha_sol_for_hana_ha-sol-hana-netweaver#con_sh_multitarget_system_replication_ha-sol-hana-netweaver). 



### 5.6. Red Hat Enterprise Linux 8.10 for SAP Solutions

Copy linkLink copied to clipboard!

  * The following enhancements have been made for the roles given below: 

    * `collection`: Ensures Ansible 2.16.1, 2.15.8, 2.14.12 (cve-2023-5764) compatibility. 
    * `collection`: Minimum Ansible version is now 2.14. 
    * `preconfigure`: Includes SLES related code. Configuring SLES managed nodes is nevertheless unsupported by Red Hat. 
    * `sap_hana_preconfigure`: Implements SAP HANA requirements for RHEL 8.8 and is less restrictive with RHEL versions that are not yet supported for SAP HANA. 
    * `sap_ha_pacemaker_cluster`: Improves VIP resource and constraint setup per platform. 

For more details refer to [Red Hat Enterprise Linux System Roles for SAP](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/red_hat_enterprise_linux_system_roles_for_sap/index). 

  * You need to enable standard repositories instead of the E4S variant for RHEL 8.10. 

For more details refer to [RHEL for SAP Subscriptions and Repositories](https://dxp-docp-prod.apps.ext-waf.spoke.prod.us-west-2.aws.paas.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html-single/rhel_for_sap_subscriptions_and_repositories/index?lb_target=preview#con_hana_10rhel-for-sap-subscriptions-and-repositories-8). 




## Chapter 6. Bug fixes

Copy linkLink copied to clipboard!

The following describes bugs fixed in Red Hat Enterprise Linux that have a significant impact on users. 

### 6.1. Red Hat Enterprise Linux 8.1 for SAP Solutions

Copy linkLink copied to clipboard!

  * [RHBA-2020:2206](https://access.redhat.com/errata/RHBA-2020:2206) Fixes issue in `sap_cluster_connector` where nodenames contain hyphens. 
  * [RHBA-2021:3175](https://access.redhat.com/errata/RHBA-2021:3175) SAPHana: `check_for_primary()` uses mode instead of actual mode in `global.ini` as fallback. 
  * [RHBA-2021:5221](https://access.redhat.com/errata/RHBA-2021:5221) The `HANA_CALL_TIMEOUT` parameter can’t be used because the value is hardcoded, therefore the description should be removed. 



### 6.2. Red Hat Enterprise Linux 8.2 for SAP Solutions

Copy linkLink copied to clipboard!

  * [RHBA-2021:3374](https://access.redhat.com/errata/RHBA-2021:3374) SAPHana: `check_for_primary()` uses mode instead of actual mode in `global.ini` as fallback. 



### 6.3. Red Hat Enterprise Linux 8.4 for SAP Solutions

Copy linkLink copied to clipboard!

  * [RHBA-2021:3087](https://access.redhat.com/errata/RHBA-2021:3087) SAPHana: `check_for_primary()` uses mode instead of actual mode in `global.ini` as fallback. 
  * [RHBA-2021:5115](https://access.redhat.com/errata/RHBA-2021:5115) The `HANA_CALL_TIMEOUT` parameter can’t be used because the value is hardcoded, therefore the description should be removed. 



### 6.4. Red Hat Enterprise Linux 8.6 for SAP Solutions

Copy linkLink copied to clipboard!

  * [RHBA-2022:2106](https://access.redhat.com/errata/RHBA-2022:2106) Users could not provide their custom ansible_managed header because of a hard-coded value in the `tuned.conf` file. 
  * [RHBA-2022:1983](https://access.redhat.com/errata/RHBA-2022:1983) SAPHANAController: Integrating systemd-based SAP Start-Up Framework for HA solutions for SAP HANA Scale-Out. 
  * [RHBA-2022:1979](https://access.redhat.com/errata/RHBA-2022:1979) System roles need to be ansible-lint clean. This update prepares rhel-system-roles-sap for Ansible Collections. 
  * [RHBA-2022:1981](https://access.redhat.com/errata/RHBA-2022:1981) SAPHana: Integrating systemd based SAP Start-Up Framework for HA solutions for SAP HANA. 



## Chapter 7. Deprecated functionality

Copy linkLink copied to clipboard!

  * [RHBA-2020:3591](https://access.redhat.com/errata/RHBA-2020:3591) `sapconf` is deprecated and has been replaced by the [RHEL System Roles for SAP](https://access.redhat.com/articles/4488731). 



## Chapter 8. Known issues

Copy linkLink copied to clipboard!

  * There are no known issues to date. 



## Chapter 9. Certified SAP applications on RHEL 8

Copy linkLink copied to clipboard!

  * SAP Max DB 7.9.10.02 and later (See SAP Note [1444241](https://launchpad.support.sap.com/#/notes/1444241)) 
  * SAP ASE 16 (See SAP Note [2489781](https://launchpad.support.sap.com/#/notes/2489781)) 
  * SAP HANA 2.0 SPS04 and later (See SAP Note [2235581](https://launchpad.support.sap.com/#/notes/2235581)) 
  * SAP BI 4.3 and later (See SAP Note [1338845](https://launchpad.support.sap.com/#/notes/1338845)) 
  * SAP NetWeaver (See SAP Note [2772999](https://launchpad.support.sap.com/#/notes/2772999)) 



In general, SAP documents support of their products for certain versions of Red Hat Linux Enterprise in their [SAP Product Availability Matrix](https://support.sap.com/en/release-upgrade-maintenance.html#section_1969201630). 

## Chapter 10. Support policies

Copy linkLink copied to clipboard!

  * Supported for certain RHEL releases: RHEL for SAP Solutions follows the general [RHEL product lifecycle and related policies](https://access.redhat.com/support/policy/updates/errata). 

Important

SAP defines its own release strategy regarding the support of operating systems and operating system versions. For SAP NetWeaver-based solutions, refer to the [SAP Product Availability Matrix](https://support.sap.com/en/release-upgrade-maintenance.html#section_1969201630). For SAP HANA, see SAP Note [2235581](https://accounts.sap.com/saml2/idp/sso). For general information, see SAP Note [2369910](https://accounts.sap.com/saml2/idp/sso). 

Production environments must comply with Red Hat and SAP support conditions. Additional SAP certifications may apply. 

  * Intel Optane DC Persistent Memory File System DAX support: Red Hat fully supports Intel Optane DC Persistent Memory (pMEM) File System DAX (FS-DAX) as part of RHEL for SAP Solutions for production deployments of SAP HANA 2.0 SPS 04, revision 40 (or later). 

For more information, see [Red Hat fully supports persistent memory (pMEM) FS-DAX mode in RHEL 7.6 and later versions for SAP Solutions](https://access.redhat.com/articles/3830541). 

  * Support for RHEL HA clusters, as part of RHEL for SAP Solutions: The RHEL for SAP Solutions subscription includes the Red Hat Enterprise Linux (RHEL) High Availability Add-on. Users of RHEL High Availability clusters should adhere to general [Support Policies for RHEL High Availability Clusters](https://access.redhat.com/articles/2912891) in order to be eligible for support. 

In addition, RHEL for SAP Solutions provides resource agents, scripts and documentation for integration with & support of the following SAP applications and scenarios: [Red Hat HA Solutions for SAP HANA, S/4HANA and NetWeaver based SAP Applications](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html/red_hat_ha_solutions_for_sap_hana_s4hana_and_netweaver_based_sap_applications/index). 




## Legal Notice

Copy linkLink copied to clipboard!

Copyright © 2024 Red Hat, Inc. 

The text of and illustrations in this document are licensed by Red Hat under a Creative Commons Attribution–Share Alike 3.0 Unported license ("CC-BY-SA"). An explanation of CC-BY-SA is available at <http://creativecommons.org/licenses/by-sa/3.0/>. In accordance with CC-BY-SA, if you distribute this document or an adaptation of it, you must provide the URL for the original version. 

Red Hat, as the licensor of this document, waives the right to enforce, and agrees not to assert, Section 4d of CC-BY-SA to the fullest extent permitted by applicable law. 

Red Hat, Red Hat Enterprise Linux, the Shadowman logo, the Red Hat logo, JBoss, OpenShift, Fedora, the Infinity logo, and RHCE are trademarks of Red Hat, Inc., registered in the United States and other countries. 

Linux® is the registered trademark of Linus Torvalds in the United States and other countries. 

Java® is a registered trademark of Oracle and/or its affiliates. 

XFS® is a trademark of Silicon Graphics International Corp. or its subsidiaries in the United States and/or other countries. 

MySQL® is a registered trademark of MySQL AB in the United States, the European Union and other countries. 

Node.js® is an official trademark of Joyent. Red Hat is not formally related to or endorsed by the official Joyent Node.js open source or commercial project. 

The OpenStack® Word Mark and OpenStack logo are either registered trademarks/service marks or trademarks/service marks of the OpenStack Foundation, in the United States and other countries and are used with the OpenStack Foundation's permission. We are not affiliated with, endorsed or sponsored by the OpenStack Foundation, or the OpenStack community. 

All other trademarks are the property of their respective owners. 

FormatMulti-pageSingle-pageView full doc as PDF

[![Red Hat logo](/Logo-Red_Hat-Documentation-A-Reverse-RGB.svg)](/en)[Github](https://github.com/redhat-documentation)[![reddit](data:image/svg+xml,%3csvg%20xmlns='http://www.w3.org/2000/svg'%20data-icon-name='reddit'%20height='512'%20width='512'%20viewBox='0%200%20512%20512'%3e%3cpath%20fill='rgb\(163,163,163\)'%20d='M201.5%20305.5c-13.8%200-24.9-11.1-24.9-24.6%200-13.8%2011.1-24.9%2024.9-24.9%2013.6%200%2024.6%2011.1%2024.6%2024.9%200%2013.6-11.1%2024.6-24.6%2024.6zM504%20256c0%20137-111%20248-248%20248S8%20393%208%20256%20119%208%20256%208s248%20111%20248%20248zm-132.3-41.2c-9.4%200-17.7%203.9-23.8%2010-22.4-15.5-52.6-25.5-86.1-26.6l17.4-78.3%2055.4%2012.5c0%2013.6%2011.1%2024.6%2024.6%2024.6%2013.8%200%2024.9-11.3%2024.9-24.9s-11.1-24.9-24.9-24.9c-9.7%200-18%205.8-22.1%2013.8l-61.2-13.6c-3-.8-6.1%201.4-6.9%204.4l-19.1%2086.4c-33.2%201.4-63.1%2011.3-85.5%2026.8-6.1-6.4-14.7-10.2-24.1-10.2-34.9%200-46.3%2046.9-14.4%2062.8-1.1%205-1.7%2010.2-1.7%2015.5%200%2052.6%2059.2%2095.2%20132%2095.2%2073.1%200%20132.3-42.6%20132.3-95.2%200-5.3-.6-10.8-1.9-15.8%2031.3-16%2019.8-62.5-14.9-62.5zM302.8%20331c-18.2%2018.2-76.1%2017.9-93.6%200-2.2-2.2-6.1-2.2-8.3%200-2.5%202.5-2.5%206.4%200%208.6%2022.8%2022.8%2087.3%2022.8%20110.2%200%202.5-2.2%202.5-6.1%200-8.6-2.2-2.2-6.1-2.2-8.3%200zm7.7-75c-13.6%200-24.6%2011.1-24.6%2024.9%200%2013.6%2011.1%2024.6%2024.6%2024.6%2013.8%200%2024.9-11.1%2024.9-24.6%200-13.8-11-24.9-24.9-24.9z'/%3e%3c/svg%3e)](https://www.reddit.com/r/redhat/)[Youtube](https://www.youtube.com/@redhat)[Twitter](https://twitter.com/RedHat)

### Learn

  * [Developer resources](https://developers.redhat.com/learn)
  * [Cloud learning hub](/learn/learning-paths)
  * [Interactive labs](https://www.redhat.com/en/interactive-labs)
  * [Training and certification](https://www.redhat.com/services/training-and-certification)
  * [Customer support](https://access.redhat.com/support)
  * [See all documentation](/en/products)



### Try, buy, & sell

  * [Product trial center](https://redhat.com/en/products/trials)
  * [Red Hat Ecosystem Catalog](https://catalog.redhat.com/)
  * [Red Hat Store](https://www.redhat.com/en/store)
  * [Buy online (Japan)](https://www.redhat.com/about/japan-buy)



### Communities

  * [Customer Portal Community](https://access.redhat.com/community)
  * [Events](https://www.redhat.com/events)
  * [How we contribute](https://www.redhat.com/about/our-community-contributions)



### About Red Hat Documentation

We help Red Hat users innovate and achieve their goals with our products and services with content they can trust. [Explore our recent updates](https://www.redhat.com/en/blog/whats-new-docsredhatcom). 

### Making open source more inclusive

Red Hat is committed to replacing problematic language in our code, documentation, and web properties. For more details, see the [Red Hat Blog]( https://www.redhat.com/en/blog/making-open-source-more-inclusive-eradicating-problematic-language). 

### About Red Hat

We deliver hardened solutions that make it easier for enterprises to work across platforms and environments, from the core datacenter to the network edge.

### Theme

### Red Hat legal and privacy links

  * [About Red Hat](https://redhat.com/en/about/company)
  * [Jobs](https://redhat.com/en/jobs)
  * [Events](https://redhat.com/en/events)
  * [Locations](https://redhat.com/en/about/office-locations)
  * [Contact Red Hat](https://redhat.com/en/contact)
  * [Red Hat Blog](https://redhat.com/en/blog)
  * [Inclusion at Red Hat](https://redhat.com/en/about/our-culture/diversity-equity-inclusion)
  * [Cool Stuff Store](https://coolstuff.redhat.com/)
  * [Red Hat Summit](https://www.redhat.com/en/summit)

© 2026 Red Hat

### Red Hat legal and privacy links

  * [Privacy statement](https://redhat.com/en/about/privacy-policy)
  * [Terms of use](https://redhat.com/en/about/terms-use)
  * [All policies and guidelines](https://redhat.com/en/about/all-policies-guidelines)
  * [Digital accessibility](https://redhat.com/en/about/digital-accessibility)
  * 
Back to top


---



# rhel8_scaleout_sr

**Source:** https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux_for_sap_solutions/8/html-single/automating_sap_hana_scale-out_system_replication_using_the_rhel_ha_add-on/index

---

  1. [Home](/)
  2. [Products](/en/products)
  3. [Red Hat Enterprise Linux for SAP Solutions](/en/documentation/red_hat_enterprise_linux_for_sap_solutions/)
  4. [8](/en/documentation/red_hat_enterprise_linux_for_sap_solutions/8/)
  5. Automating SAP HANA Scale-Out System Replication using the RHEL HA Add-On



## Red Hat Enterprise Linux for SAP Solutions

# Automating SAP HANA Scale-Out System Replication using the RHEL HA Add-On

* * *

Red Hat Enterprise Linux for SAP Solutions 8

## 

Red Hat Customer Content Services

Legal Notice

**Abstract**

This document describes how to plan and implement automated takeover for SAP HANA Scale-Out deployments. 

* * *

## Making open source more inclusive

Copy linkLink copied to clipboard!

Red Hat is committed to replacing problematic language in our code and documentation. We are beginning with these four terms: master, slave, blacklist, and whitelist. Due to the enormity of this endeavor, these changes will be gradually implemented over upcoming releases. For more details on making our language more inclusive, see our [CTO Chris Wright’s message](https://www.redhat.com/en/blog/making-open-source-more-inclusive-eradicating-problematic-language). 

## Providing feedback on Red Hat documentation

Copy linkLink copied to clipboard!

We appreciate your feedback on our documentation. Let us know how we can improve it. 

