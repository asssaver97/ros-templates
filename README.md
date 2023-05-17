English | [简体中文](./README-CN.md)

<h1 align="center">ROS Templates</h1>

> If you are not familiar with Resource Orchestration Service (ROS), please read [What is ROS](https://www.alibabacloud.com/help/resource-orchestration-service/latest/what-is-ros). If you are not familiar with the ROS template syntax, please refer to the [Getting started with templates](https://www.alibabacloud.com/help/resource-orchestration-service/latest/get-started-with-templates).

> Welcome to experience ROS through the ROS [Console](https://ros-intl.console.aliyun.com/cn-beijing/stacks/create), [API](https://api.alibabacloud.com/product/ROS), [SDK](https://api.alibabacloud.com/api-tools/sdk/ROS), [CDK](https://www.alibabacloud.com/help/resource-orchestration-service/latest/ros-cdk-overview).

## Introduction

Examples and best practices of ROS templates. The templates are categorized as follows:

- `resources`: Resource-level template examples that provide templates for single services or resources.
- `examples`: Comprehensive template examples that provide templates for simple scenarios. The template contents are the same as the ROS Console [Sample Templates](https://ros.console.aliyun.com/cn-beijing/samples).
- `solutions`: Solutions that provide template best practices for complex scenarios. The templates are the same as those in the ROS Console [Solution Center](https://ros.console.aliyun.com/cn-beijing/solutions).
- `transform`: Templates based on [Transform syntax](https://www.alibabacloud.com/help/resource-orchestration-service/latest/template-syntax-transform), offering simplified templates for specific scenarios.
- `documents`：The templates involved in the Alibaba Cloud documents.
- `compute-nest-best-practice`: Best practice templates for [Compute Nest](https://www.alibabacloud.com/help/computing-nest), providing templates for basic and advanced Compute Nest scenarios.

## Details

<details>
  <summary>resources</summary>

| Template                                                                                     | Description                                                                                                                                    |
| -------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| [acm/configuration.yml](./resources/acm/configuration.yml)                                   | ACM Namespace/Configuration resource example                                                                                                   |
| [actiontrail/trail-logging.yml](./resources/actiontrail/trail-logging.yml)                   | ACTIONTRAIL Trail/TrailLogging resource example                                                                                                |
| [apigateway/api.yml](./resources/apigateway/api.yml)                                         | ApiGateway Api/Group/App/Deployment/Authorization/Signature/SignatureBinding/TrafficControl/TrafficControlBinding/ resource example            |
| [apigateway/custom-domain.yml](./resources/apigateway/custom-domain.yml)                     | ApiGateway CustomDomain resource example                                                                                                       |
| [apigateway/instance.yml](./resources/apigateway/instance.yml)                               | ApiGateway Instance resource example                                                                                                           |
| [apigateway/stage-config.yml](./resources/apigateway/stage-config.yml)                       | ApiGateway StageConfig resource example                                                                                                        |
| [apigateway/vpc-access-config.yml](./resources/apigateway/vpc-access-config.yml)             | ApiGateway VpcAccessConfig resource example                                                                                                    |
| [arms/alert-contact-group.yml](./resources/arms/alert-contact-group.yml)                     | ARMS AlertContact/AlertContactGroup resource example                                                                                           |
| [arms/retcode-app.yml](./resources/arms/retcode-app.yml)                                     | ARMS RetcodeApp resource example                                                                                                               |
| [asm/service-mesh.yml](./resources/asm/service-mesh.yml)                                     | ASM ServiceMesh resource example                                                                                                               |
| [bss/wait-order.yml](./resources/bss/wait-order.yml)                                         | BSS WaitOrder resource example                                                                                                                 |
| [cas/certificate.yml](./resources/cas/certificate.yml)                                       | CAS Certificate resource example                                                                                                               |
| [cdn/domain.yml](./resources/cdn/domain.yml)                                                 | CDN Domain/DomainConfig resource example                                                                                                       |
| [cen/cen.yml](./resources/cen/cen.yml)                                                       | CEN resource example                                                                                                                           |
| [cms/contact.yml](./resources/cms/contact.yml)                                               | CMS Contact/ContactGroup/DynamicTagGroup resource example                                                                                      |
| [cms/event-rule-targets.yml](./resources/cms/event-rule-targets.yml)                         | CMS EventRuleTargets resource example                                                                                                          |
| [cms/event-rule.yml](./resources/cms/event-rule.yml)                                         | CMS EventRule resource example                                                                                                                 |
| [cms/group-metric-rule.yml](./resources/cms/group-metric-rule.yml)                           | CMS GroupMetricRule/MetricRuleTargets resource example                                                                                         |
| [cms/metric-rule-template.yml](./resources/cms/metric-rule-template.yml)                     | CMS MetricRuleTemplate resource example                                                                                                        |
| [cms/monitor-group.yml](./resources/cms/monitor-group.yml)                                   | CMS MonitorGroup/MonitorGroupInstances resource example                                                                                        |
| [cms/monitoring-agent-process.yml](./resources/cms/monitoring-agent-process.yml)             | CMS MonitoringAgentProcess resource example                                                                                                    |
| [cms/site-monitor.yml](./resources/cms/site-monitor.yml)                                     | CMS SiteMonitor resource example                                                                                                               |
| [config/config.yml](./resources/config/config.yml)                                           | Config Rule resource example                                                                                                                   |
| [cr/instance-endpoint-acl-policy.yml](./resources/cr/instance-endpoint-acl-policy.yml)       | CR InstanceEndpointAclPolicy resource example                                                                                                  |
| [cr/namespace.yml](./resources/cr/namespace.yml)                                             | CR NameSpace resource example                                                                                                                  |
| [cr/repository.yml](./resources/cr/repository.yml)                                           | CR Repository resource example                                                                                                                 |
| [cs/any-cluster.yml](./resources/cs/any-cluster.yml)                                         | CS AnyCluster resource example                                                                                                                 |
| [cs/kubernetes-cluster.yml](./resources/cs/kubernetes-cluster.yml)                           | CS KubernetesCluster resource example                                                                                                          |
| [cs/managed-edge-kubernetes-cluster.yml](./resources/cs/managed-edge-kubernetes-cluster.yml) | CS ManagedEdgeKubernetesCluster resource example                                                                                               |
| [cs/managed-kubernetes-cluster.yml](./resources/cs/managed-kubernetes-cluster.yml)           | CS ManagedKubernetesCluster resource example                                                                                                   |
| [cs/serverless-kubernetes-cluster.yml](./resources/cs/serverless-kubernetes-cluster.yml)     | CS ServerlessKubernetesCluster resource example                                                                                                |
| [datahub/topic.yml](./resources/datahub/topic.yml)                                           | DataHub Project/Topic resource example                                                                                                         |
| [dns/domain-record.yml](./resources/dns/domain-record.yml)                                   | DNS DomainRecord resource example                                                                                                              |
| [dns/domain.yml](./resources/dns/domain.yml)                                                 | DNS Domain/DomainGroup resource example                                                                                                        |
| [drds/drds-instance.yml](./resources/drds/drds-instance.yml)                                 | DrdsInstance resource example                                                                                                                  |
| [dts/consumer-group.yml](./resources/dts/consumer-group.yml)                                 | DTS SubscriptionInstance resource example                                                                                                      |
| [dts/dts.yml](./resources/dts/dts.yml)                                                       | DTS MigrationJob/SynchronizationJob resource example                                                                                           |
| [dts/subscription-instance.yml](./resources/dts/subscription-instance.yml)                   | DTS SubscriptionInstance/ConsumerGroup resource example                                                                                        |
| [eci/container-group.yml](./resources/eci/container-group.yml)                               | ECI ContainerGroup resource example                                                                                                            |
| [eci/image-cache.yml](./resources/eci/image-cache.yml)                                       | ECI ImageCache resource example                                                                                                                |
| [ecs/assign-private-ip-addresses.yml](./resources/ecs/assign-private-ip-addresses.yml)       | ECS AssignPrivateIpAddresses resource example                                                                                                  |
| [ecs/auto-snapshot-policy.yml](./resources/ecs/auto-snapshot-policy.yml)                     | ECS AutoSnapshotPolicy resource example                                                                                                        |
| [ecs/custom-image.yml](./resources/ecs/custom-image.yml)                                     | ECS CustomImage/CopyImage resource example                                                                                                     |
| [ecs/dedicated-host.yml](./resources/ecs/dedicated-host.yml)                                 | ECS DedicatedHost resource example                                                                                                             |
| [ecs/deployment-set.yml](./resources/ecs/deployment-set.yml)                                 | ECS DeploymentSet resource example                                                                                                             |
| [ecs/disk-attachment.yml](./resources/ecs/disk-attachment.yml)                               | ECS DiskAttachment/Snapshot resource example                                                                                                   |
| [ecs/disk.yml](./resources/ecs/disk.yml)                                                     | ECS Disk resource example                                                                                                                      |
| [ecs/forward-entry.yml](./resources/ecs/forward-entry.yml)                                   | ECS ForwardEntry resource example                                                                                                              |
| [ecs/hpc-cluster.yml](./resources/ecs/hpc-cluster.yml)                                       | ECS HpcCluster resource example                                                                                                                |
| [ecs/instance-clone.yml](./resources/ecs/instance-clone.yml)                                 | ECS Instance Clone resource example                                                                                                            |
| [ecs/instance-group.yml](./resources/ecs/instance-group.yml)                                 | ECS InstanceGroup/InstanceGroupClone/Command/Invocation resource example                                                                       |
| [ecs/instance.yml](./resources/ecs/instance.yml)                                             | ECS instance/EIP/NatGateway/SSHKeyPair resource example                                                                                        |
| [ecs/join-security-group.yml](./resources/ecs/join-security-group.yml)                       | ECS JoinSecurityGroup resource example                                                                                                         |
| [ecs/launch-template.yml](./resources/ecs/launch-template.yml)                               | ECS LaunchTemplate/AutoProvisioningGroup resource example                                                                                      |
| [ecs/nat-gateway.yml](./resources/ecs/nat-gateway.yml)                                       | ECS NatGateway/BandwidthPackage resource example                                                                                               |
| [ecs/network-interface-attachment.yml](./resources/ecs/network-interface-attachment.yml)     | ECS NetworkInterface/NetworkInterfaceAttachment resource example                                                                               |
| [ecs/prepay-instance.yml](./resources/ecs/prepay-instance.yml)                               | ECS PrepayInstance resource example                                                                                                            |
| [ecs/route.yml](./resources/ecs/route.yml)                                                   | ECS Route/AssignIpv6Addresses resource example                                                                                                 |
| [ecs/run-command.yml](./resources/ecs/run-command.yml)                                       | ECS RunCommand resource example                                                                                                                |
| [ecs/snat-entry.yml](./resources/ecs/snat-entry.yml)                                         | ECS SecurityGroupIngress resource example                                                                                                      |
| [ecs/security-group-clone.yml](./resources/ecs/security-group-clone.yml)                     | ECS SecurityGroupClone resource example                                                                                                        |
| [ecs/security-group-egress.yml](./resources/ecs/security-group-egress.yml)                   | ECS SecurityGroupEgress resource example                                                                                                       |
| [ecs/security-group-ingress.yml](./resources/ecs/security-group-ingress.yml)                 | ECS SecurityGroupIngress resource example                                                                                                      |
| [edas/cluster-member.yml](./resources/edas/cluster-member.yml)                               | EDAS ClusterMember resource example                                                                                                            |
| [edas/cluster.yml](./resources/edas/cluster.yml)                                             | EDAS Cluster/App/DeployGroup resource example                                                                                                  |
| [ehpc/cluster.yml](./resources/ehpc/cluster.yml)                                             | EHPC Cluster resource example                                                                                                                  |
| [elasticsearch/instance.yml](./resources/elasticsearch/instance.yml)                         | ElasticSearch Instance resource example                                                                                                        |
| [emr/cluster.yml](./resources/emr/cluster.yml)                                               | EMR Cluster resource example                                                                                                                   |
| [ess/scaling-group-enable.yml](./resources/ess/scaling-group-enable.yml)                     | ESS ScalingConfiguration/ScalingGroupEnable resource example                                                                                   |
| [ess/scaling-group.yml](./resources/ess/scaling-group.yml)                                   | ESS ScalingGroup/ScalingRule/AlarmTask/AlarmTaskEnable/LifecycleHook/ScheduledTask resource example                                            |
| [fc/custom-domain.yml](./resources/fc/custom-domain.yml)                                     | FC CustomDomain resource example                                                                                                               |
| [fc/function-invoker.yml](./resources/fc/function-invoker.yml)                               | FC FunctionInvoker/Trigger/Version/Alias/ProvisionConfig resource example                                                                      |
| [fnf/flow.yml](./resources/fnf/flow.yml)                                                     | FNF Flow/Schedule resource example                                                                                                             |
| [ga/ga-ipv6.yml](./resources/ga/ga-ipv6.yml)                                                 | GA Accelerator/ BandwidthPackage/IpSets/Listener/EndpointGroup/BandwidthPackageAcceleratorAddition resource example                            |
| [gws/cluster.yml](./resources/gws/cluster.yml)                                               | GWS Cluster/Instance resource example                                                                                                          |
| [iot/device-group.yml](./resources/iot/device-group.yml)                                     | IOT DeviceGroup resource example                                                                                                               |
| [iot/device.yml](./resources/iot/device.yml)                                                 | IOT Product/Device resource example                                                                                                            |
| [iot/rule.yml](./resources/iot/rule.yml)                                                     | IOT Rule/RuleAction resource example                                                                                                           |
| [kafka/instance.yml](./resources/kafka/instance.yml)                                         | Kafka Instance/Topic resource example                                                                                                          |
| [kms/key.yml](./resources/kms/key.yml)                                                       | KMS Key/Alias resource example                                                                                                                 |
| [kms/secret.yml](./resources/kms/secret.yml)                                                 | KMS Secret resource example                                                                                                                    |
| [marketplace/order.yml](./resources/marketplace/order.yml)                                   | MarketPlace Order resource example                                                                                                             |
| [memcache/instance.yml](./resources/memcache/instance.yml)                                   | Memcache Instance/WhiteList resource example                                                                                                   |
| [mns/subscription.yml](./resources/mns/subscription.yml)                                     | MNS Queue/Topic/Subscription resource example                                                                                                  |
| [mongodb/mongodb-instance.yml](./resources/mongodb/mongodb-instance.yml)                     | MONGODB Instance resource example                                                                                                              |
| [mongodb/serverless-instance.yml](./resources/mongodb/serverless-instance.yml)               | MONGODB ServerlessInstance resource example                                                                                                    |
| [mongodb/sharding-instance.yml](./resources/mongodb/sharding-instance.yml)                   | MONGODB ShardingInstance resource example                                                                                                      |
| [mse/cluster.yml](./resources/mse/cluster.yml)                                               | MSE Cluster resource example                                                                                                                   |
| [nas/nas.yml](./resources/nas/nas.yml)                                                       | NAS AccessGroupName/AccessRule/FileSystem/MountTarget resource example                                                                         |
| [oos/oos.yml](./resources/oos/oos.yml)                                                       | OOS Template/Execution resource example                                                                                                        |
| [oos/parameter.yml](./resources/oos/parameter.yml)                                           | OOS Parameter resource example                                                                                                                 |
| [oss/bucket.yml](./resources/oss/bucket.yml)                                                 | OSS Bucket resource example                                                                                                                    |
| [ots/ots.yml](./resources/ots/ots.yml)                                                       | OTS Table/Instance/VpcBinder resource example                                                                                                  |
| [polardb/polardb.yml](./resources/polardb/polardb.yml)                                       | POLARDB DBCluster/Account/DBInstance/DBNodes/AccountPrivilege/DBClusterAccessWhiteList/DBClusterEndpointAddress resource example               |
| [privatelink/vpc-endpoint.yml](./resources/privatelink/vpc-endpoint.yml)                     | PrivateLink VpcEndpointService/VpcEndpoint resource example                                                                                    |
| [pvtz/pvtz.yml](./resources/pvtz/pvtz.yml)                                                   | PVTZ Zone/ZoneRecord/ZoneVpcBinder resource example                                                                                            |
| [ram/access-key.yml](./resources/ram/access-key.yml)                                         | RAM User/AccessKey resource example                                                                                                            |
| [ram/attach-policy-to-role.yml](./resources/ram/attach-policy-to-role.yml)                   | RAM Role/AttachPolicyToRole resource example                                                                                                   |
| [ram/managed-policy.yml](./resources/ram/managed-policy.yml)                                 | RAM ManagedPolicy resource example                                                                                                             |
| [ram/role.yml](./resources/ram/role.yml)                                                     | RAM Role resource example                                                                                                                      |
| [ram/saml-provider.yml](./resources/ram/saml-provider.yml)                                   | RAM SAMLProvider resource example                                                                                                              |
| [ram/user.yml](./resources/ram/user.yml)                                                     | RAM User/Group/AttachPolicyToUser/UserToGroupAddition resource example                                                                         |
| [rds/db-instance.yml](./resources/rds/db-instance.yml)                                       | RDS DBInstance/Account/AccountPrivilege resource example                                                                                       |
| [rds/prepay-db-instance.yml](./resources/rds/prepay-db-instance.yml)                         | RDS PrepayDBInstance resource example                                                                                                          |
| [redis/instance.yml](./resources/redis/instance.yml)                                         | Redis Instance/Whitelist and Account resource example                                                                                          |
| [redis/prepay-instance.yml](./resources/redis/prepay-instance.yml)                           | Redis PrepayInstance resource example                                                                                                          |
| [resourcemaneger/handshake.yml](./resources/resourcemaneger/handshake.yml)                   | ResourceManager Handshake resource example                                                                                                     |
| [resourcemaneger/resource-group.yml](./resources/resourcemaneger/resource-group.yml)         | ResourceManager ResourceGroup resource example                                                                                                 |
| [rocketmq/rocketmq.yml](./resources/rocketmq/rocketmq.yml)                                   | ROCKETMQ Instance/Topic resource example                                                                                                       |
| [ros/auto-enable-service.yml](./resources/ros/auto-enable-service.yml)                       | ROS AutoEnableService resource example                                                                                                         |
| [ros/custom-resource.yml](./resources/ros/custom-resource.yml)                               | ROS Custom resource example                                                                                                                    |
| [ros/stack.yml](./resources/ros/stack.yml)                                                   | ROS Nested Stack resource example                                                                                                              |
| [ros/wait-condition-handle.yml](./resources/ros/wait-condition-handle.yml)                   | ROS WaitConditionHandle resource example                                                                                                       |
| [ros/wait-condition.yml](./resources/ros/wait-condition.yml)                                 | ROS WaitCondition/WaitConditionHandle resource example                                                                                         |
| [sae/sae.yml](./resources/sae/sae.yml)                                                       | SAE Application/Namespace/SlbBinding resource example                                                                                          |
| [sag/acl.yml](./resources/sag/acl.yml)                                                       | SAG ACL/ACLRule/ACLAssociation resource example                                                                                                |
| [slb/access-control.yml](./resources/slb/access-control.yml)                                 | SLB AccessControl resource example                                                                                                             |
| [slb/backend-server-attachment.yml](./resources/slb/backend-server-attachment.yml)           | SLB LoadBalancer/MasterSlaveServerGroup/BackendServerAttachment resource example                                                               |
| [slb/listener.yml](./resources/slb/listener.yml)                                             | SLB LoadBalancer/Listener/LoadBalancerClone/Certificate/DomainExtension/VServerGroup/Rule resource example                                     |
| [sls/sls.yml](./resources/sls/sls.yml)                                                       | SLS Project/Logstore/Alert/Index/SavedSearch/LogtailConfig/MachineGroup/ApplyConfigToMachineGroup/ApiGatewayLogConfig resource example         |
| [tsdb/hi-tsdb-instance.yml](./resources/tsdb/hi-tsdb-instance.yml)                           | TSDB HiTSDBInstance resource example                                                                                                           |
| [vpc/anycast-eip.yml](./resources/vpc/anycast-eip.yml)                                       | VPC AnycastEIP/AnycastEIPAssociation resource example                                                                                          |
| [vpc/eip-association.yml](./resources/vpc/eip-association.yml)                               | VPC EIP/EIPAssociation resource example                                                                                                        |
| [vpc/eip-segment.yml](./resources/vpc/eip-segment.yml)                                       | VPC EIPSegment resource example                                                                                                                |
| [vpc/eip.yml](./resources/vpc/eip.yml)                                                       | VPC EIP resource example                                                                                                                       |
| [vpc/nat-gateway.yml](./resources/vpc/nat-gateway.yml)                                       | VPC NatGateway resource example                                                                                                                |
| [vpc/network-acl.yml](./resources/vpc/network-acl.yml)                                       | VPC NetworkAcl/NetworkAclAssociation resource example                                                                                          |
| [vpc/route-table.yml](./resources/vpc/route-table.yml)                                       | Vpc RouteTable resource example                                                                                                                |
| [vpc/router-interface-update.yml](./resources/vpc/router-interface-update.yml)               | Vpc RouterInterface resource example                                                                                                           |
| [vpc/router-interface.yml](./resources/vpc/router-interface.yml)                             | Vpc RouterInterface resource example                                                                                                           |
| [vpc/snat-entry.yml](./resources/vpc/snat-entry.yml)                                         | VPC NatGateway/Ipv6Gateway/Ipv6InternetBandwidth/EIP/EIPAssociation/SnatEntry/CommonBandwidthPackage/CommonBandwidthPackageIp resource example |
| [waf/domain-config.yml](./resources/waf/domain-config.yml)                                   | Waf DomainConfig/AclRule/WafSwitch resource example                                                                                            |
| [waf/domain.yml](./resources/waf/domain.yml)                                                 | Waf Domain resource example                                                                                                                    |
| [waf/instance.yml](./resources/waf/instance.yml)                                             | WAF Instance resource example                                                                                                                  |

</details>

<details>
  <summary>documents</summary>

- trail

| Template                                                                                                                           | Description                                            |
| ---------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| [alb-7-layer-load-balancing.yml](./documents/trail/alb-7-layer-load-balancing.yml)                                                 | Implements 7-layer load balancing for IPv4 services    |
| [clb-4-layer-load-balancing.yml](./documents/trail/clb-4-layer-load-balancing.yml)                                                 | 4-layer CLB load balancing                             |
| [clb-7-layer-load-balancing.yml](./documents/trail/clb-7-layer-load-balancing.yml)                                                 | 7-layer CLB load balancing                             |
| [nlb-4-layer-load-balancing.yml](./documents/trail/nlb-4-layer-load-balancing.yml)                                                 | Implements 4-layer load balancing for IPv4 services    |
| [ecs-blog.yml](./documents/trail/ecs-blog.yml)                                                                                     | Deploy a blog on the cloud                             |
| [ecs-lamp.yml](./documents/trail/ecs-lamp.yml)                                                                                     | Deploy a LAMP environment                              |
| [ecs-lnmp.yml](./documents/trail/ecs-lnmp.yml)                                                                                     | Deploy a LNMP environment                              |
| [ecs-mount-nas-file-system.yml](./documents/trail/ecs-mount-nas-file-system.yml)                                                   | Mount NAS to ECS                                       |
| [ecs-online-education-video-course-sharing-website.yml](./documents/trail/ecs-online-education-video-course-sharing-website.yml)   | Build an online education video course sharing website |
| [ecs-website.yml](./documents/trail/ecs-website.yml)                                                                               | Quickly deploy a website                               |
| [ga-accelerated-access-to-specified-ip.yml](./documents/trail/ga-accelerated-access-to-specified-ip.yml)                           | Accelerated access to specified backend services by IP |
| [oos-timing-management-of-ecs.yml](./documents/trail/oos-timing-management-of-ecs.yml)                                             | OOS timing management of ECS                           |
| [polardb-mysql-htap-real-time-data-analysis.yml](./documents/trail/polardb-mysql-htap-real-time-data-analysis.yml)                 | PolarDB MySQL HTAP real-time data analysis             |
| [polardb-postgresql-enterprise-performance-practice.yml](./documents/trail/polardb-postgresql-enterprise-performance-practice.yml) | PolarDB PostgreSQL enterprise performance practice     |
| [ram-create-user-and-authorize.yml](./documents/trail/ram-create-user-and-authorize.yml)                                           | Create RAM user and authorize                          |
| [rds-create-account-database-and-connection.yml](./documents/trail/rds-create-account-database-and-connection.yml)                 | Create account, database, and connection to RDS        |
| [redis-game-player-leaderboard.yml](./documents/trail/redis-game-player-leaderboard.yml)                                           | Redis game player leaderboard                          |
| [tair-restores-data-through-data-flashback.yml](./documents/trail/tair-restores-data-through-data-flashback.yml)                   | Restore data in Tair through data flashback            |

</details>

<details>
  <summary>compute-nest-best-practice</summary>

| Template                                                                                                | Description                                               |
| ------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [ack-app-rds](./compute-nest-best-practice/ack-app-rds/README.md)                                       | Create container application and RDS                      |
| [ack-nginx](./compute-nest-best-practice/ack-nginx/README.md)                                           | Create ACK and deploy Nginx                               |
| [ecs-adbpg](./compute-nest-best-practice/ecs-adbpg/README.md)                                           | Create ECS and ADBPG instances                            |
| [ecs-deploy](./compute-nest-best-practice/ecs-deploy/README.md)                                         | Deployment based on ECS instances                         |
| [ecs-mongodb](./compute-nest-best-practice/ecs-mongodb/README.md)                                       | Create ECS and MongoDB instances                          |
| [ecs-mysql-deploy](./compute-nest-best-practice/ecs-mysql-deploy/README.md)                             | Create ECS instance and create MySQL                      |
| [ecs-polardb](./compute-nest-best-practice/ecs-polardb/README.md)                                       | Create ECS and PolarDB instances                          |
| [ecs-postgresql](./compute-nest-best-practice/ecs-postgresql/README.md)                                 | Create ECS and PostgreSQL instances                       |
| [ecs-ramrole-oss](./compute-nest-best-practice/ecs-ramrole-oss/README.md)                               | Create ECS instance, RAM Role, and OSS                    |
| [ecs-rds](./compute-nest-best-practice/ecs-rds/README.md)                                               | Create ECS and RDS instances                              |
| [ecs-redis](./compute-nest-best-practice/ecs-redis/README.md)                                           | Create ECS and Redis instances                            |
| [ecs-slb](./compute-nest-best-practice/ecs-slb/README.md)                                               | Create ECS and SLB instances                              |
| [ecs-sqlserver](./compute-nest-best-practice/ecs-sqlserver/README.md)                                   | Create ECS and SQL Server instances                       |
| [ehpc-demo](./compute-nest-best-practice/ehpc-demo/README.md)                                           | Create Elastic High Performance Computing cluster         |
| [existing-ecs-nginx](./compute-nest-best-practice/existing-ecs-nginx/README.md)                         | Deploy Nginx on existing ECS instances                    |
| [managed-reverse-vpc-connection](./compute-nest-best-practice/managed-reverse-vpc-connection/README.md) | Best practices for managed reverse VPC connection         |
| [master-slave-ecs](./compute-nest-best-practice/master-slave-ecs/README.md)                             | Create ECS instances in a Master-Slave architecture       |
| [opensource](./compute-nest-best-practice/opensource)                                                   | Best practices for deploying various open source software |
| [pai/pai-dsw.yml](./compute-nest-best-practice/pai/pai-dsw.yml)                                         | Create PAI                                                |
| [scaling-ecs](./compute-nest-best-practice/scaling-ecs/README.md)                                       | Create ECS architecture with an auto-scaling group        |
| [terraform-ecs-nginx](./compute-nest-best-practice/terraform-ecs-nginx/README.md)                       | [Terraform] Create ECS instances and deploy Nginx         |

</details>
