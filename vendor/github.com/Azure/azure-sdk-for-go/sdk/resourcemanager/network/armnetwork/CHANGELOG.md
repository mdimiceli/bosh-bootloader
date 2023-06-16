# Release History

## 1.1.0 (2022-08-05)
### Features Added

- New const `SecurityConfigurationRuleDirectionInbound`
- New const `IsGlobalFalse`
- New const `EndpointTypeAzureVMSS`
- New const `ScopeConnectionStateConflict`
- New const `SecurityConfigurationRuleDirectionOutbound`
- New const `GroupConnectivityDirectlyConnected`
- New const `ScopeConnectionStateRejected`
- New const `ConfigurationTypeConnectivity`
- New const `AutoLearnPrivateRangesModeEnabled`
- New const `UseHubGatewayFalse`
- New const `NetworkIntentPolicyBasedServiceNone`
- New const `DeleteExistingPeeringFalse`
- New const `EffectiveAdminRuleKindDefault`
- New const `DeploymentStatusFailed`
- New const `AddressPrefixTypeIPPrefix`
- New const `AddressPrefixTypeServiceTag`
- New const `UseHubGatewayTrue`
- New const `WebApplicationFirewallOperatorAny`
- New const `SecurityConfigurationRuleAccessAlwaysAllow`
- New const `CreatedByTypeUser`
- New const `EndpointTypeAzureArcVM`
- New const `DeploymentStatusNotStarted`
- New const `SecurityConfigurationRuleProtocolTCP`
- New const `SecurityConfigurationRuleAccessDeny`
- New const `SecurityConfigurationRuleProtocolEsp`
- New const `IsGlobalTrue`
- New const `DeploymentStatusDeployed`
- New const `NetworkIntentPolicyBasedServiceAll`
- New const `SecurityConfigurationRuleProtocolUDP`
- New const `CreatedByTypeKey`
- New const `PacketCaptureTargetTypeAzureVMSS`
- New const `ApplicationGatewaySSLPolicyTypeCustomV2`
- New const `DeleteExistingPeeringTrue`
- New const `ScopeConnectionStateConnected`
- New const `ApplicationGatewaySSLPolicyNameAppGwSSLPolicy20220101S`
- New const `ConnectivityTopologyMesh`
- New const `CreatedByTypeManagedIdentity`
- New const `AdminRuleKindCustom`
- New const `ApplicationGatewaySSLProtocolTLSv13`
- New const `ConnectivityTopologyHubAndSpoke`
- New const `ScopeConnectionStateRevoked`
- New const `ConfigurationTypeSecurityAdmin`
- New const `SecurityConfigurationRuleProtocolAh`
- New const `CommissionedStateCommissionedNoInternetAdvertise`
- New const `ScopeConnectionStatePending`
- New const `SecurityConfigurationRuleAccessAllow`
- New const `SecurityConfigurationRuleProtocolIcmp`
- New const `AutoLearnPrivateRangesModeDisabled`
- New const `SecurityConfigurationRuleProtocolAny`
- New const `ApplicationGatewaySSLPolicyNameAppGwSSLPolicy20220101`
- New const `CreatedByTypeApplication`
- New const `GroupConnectivityNone`
- New const `EffectiveAdminRuleKindCustom`
- New const `AdminRuleKindDefault`
- New const `DeploymentStatusDeploying`
- New const `PacketCaptureTargetTypeAzureVM`
- New function `*ManagementClient.ListActiveConnectivityConfigurations(context.Context, string, string, ActiveConfigurationParameter, *ManagementClientListActiveConnectivityConfigurationsOptions) (ManagementClientListActiveConnectivityConfigurationsResponse, error)`
- New function `*ManagersClient.NewListBySubscriptionPager(*ManagersClientListBySubscriptionOptions) *runtime.Pager[ManagersClientListBySubscriptionResponse]`
- New function `NewStaticMembersClient(string, azcore.TokenCredential, *arm.ClientOptions) (*StaticMembersClient, error)`
- New function `NewAdminRulesClient(string, azcore.TokenCredential, *arm.ClientOptions) (*AdminRulesClient, error)`
- New function `*EffectiveDefaultSecurityAdminRule.GetEffectiveBaseSecurityAdminRule() *EffectiveBaseSecurityAdminRule`
- New function `PossibleAddressPrefixTypeValues() []AddressPrefixType`
- New function `PossibleUseHubGatewayValues() []UseHubGateway`
- New function `*ScopeConnectionsClient.Delete(context.Context, string, string, string, *ScopeConnectionsClientDeleteOptions) (ScopeConnectionsClientDeleteResponse, error)`
- New function `PossibleIsGlobalValues() []IsGlobal`
- New function `*ManagementClient.ListActiveSecurityAdminRules(context.Context, string, string, ActiveConfigurationParameter, *ManagementClientListActiveSecurityAdminRulesOptions) (ManagementClientListActiveSecurityAdminRulesResponse, error)`
- New function `*ManagersClient.NewListPager(string, *ManagersClientListOptions) *runtime.Pager[ManagersClientListResponse]`
- New function `NewConnectivityConfigurationsClient(string, azcore.TokenCredential, *arm.ClientOptions) (*ConnectivityConfigurationsClient, error)`
- New function `*GroupsClient.Get(context.Context, string, string, string, *GroupsClientGetOptions) (GroupsClientGetResponse, error)`
- New function `PossibleAdminRuleKindValues() []AdminRuleKind`
- New function `*ScopeConnectionsClient.Get(context.Context, string, string, string, *ScopeConnectionsClientGetOptions) (ScopeConnectionsClientGetResponse, error)`
- New function `*AdminRuleCollectionsClient.CreateOrUpdate(context.Context, string, string, string, string, AdminRuleCollection, *AdminRuleCollectionsClientCreateOrUpdateOptions) (AdminRuleCollectionsClientCreateOrUpdateResponse, error)`
- New function `PossibleScopeConnectionStateValues() []ScopeConnectionState`
- New function `*ConnectivityConfigurationsClient.NewListPager(string, string, *ConnectivityConfigurationsClientListOptions) *runtime.Pager[ConnectivityConfigurationsClientListResponse]`
- New function `*BaseAdminRule.GetBaseAdminRule() *BaseAdminRule`
- New function `PossibleSecurityConfigurationRuleProtocolValues() []SecurityConfigurationRuleProtocol`
- New function `*AdminRulesClient.CreateOrUpdate(context.Context, string, string, string, string, string, BaseAdminRuleClassification, *AdminRulesClientCreateOrUpdateOptions) (AdminRulesClientCreateOrUpdateResponse, error)`
- New function `PossibleNetworkIntentPolicyBasedServiceValues() []NetworkIntentPolicyBasedService`
- New function `*ManagementGroupNetworkManagerConnectionsClient.Delete(context.Context, string, string, *ManagementGroupNetworkManagerConnectionsClientDeleteOptions) (ManagementGroupNetworkManagerConnectionsClientDeleteResponse, error)`
- New function `PossibleSecurityConfigurationRuleAccessValues() []SecurityConfigurationRuleAccess`
- New function `*ManagersClient.BeginDelete(context.Context, string, string, *ManagersClientBeginDeleteOptions) (*runtime.Poller[ManagersClientDeleteResponse], error)`
- New function `*ManagementClient.ExpressRouteProviderPort(context.Context, string, *ManagementClientExpressRouteProviderPortOptions) (ManagementClientExpressRouteProviderPortResponse, error)`
- New function `*ActiveBaseSecurityAdminRule.GetActiveBaseSecurityAdminRule() *ActiveBaseSecurityAdminRule`
- New function `*ConnectivityConfigurationsClient.BeginDelete(context.Context, string, string, string, *ConnectivityConfigurationsClientBeginDeleteOptions) (*runtime.Poller[ConnectivityConfigurationsClientDeleteResponse], error)`
- New function `*AdminRuleCollectionsClient.BeginDelete(context.Context, string, string, string, string, *AdminRuleCollectionsClientBeginDeleteOptions) (*runtime.Poller[AdminRuleCollectionsClientDeleteResponse], error)`
- New function `*ConnectivityConfigurationsClient.CreateOrUpdate(context.Context, string, string, string, ConnectivityConfiguration, *ConnectivityConfigurationsClientCreateOrUpdateOptions) (ConnectivityConfigurationsClientCreateOrUpdateResponse, error)`
- New function `*SecurityAdminConfigurationsClient.Get(context.Context, string, string, string, *SecurityAdminConfigurationsClientGetOptions) (SecurityAdminConfigurationsClientGetResponse, error)`
- New function `*StaticMembersClient.Delete(context.Context, string, string, string, string, *StaticMembersClientDeleteOptions) (StaticMembersClientDeleteResponse, error)`
- New function `*ManagerDeploymentStatusClient.List(context.Context, string, string, ManagerDeploymentStatusParameter, *ManagerDeploymentStatusClientListOptions) (ManagerDeploymentStatusClientListResponse, error)`
- New function `*SubscriptionNetworkManagerConnectionsClient.Delete(context.Context, string, *SubscriptionNetworkManagerConnectionsClientDeleteOptions) (SubscriptionNetworkManagerConnectionsClientDeleteResponse, error)`
- New function `PossibleEffectiveAdminRuleKindValues() []EffectiveAdminRuleKind`
- New function `*AdminRulesClient.NewListPager(string, string, string, string, *AdminRulesClientListOptions) *runtime.Pager[AdminRulesClientListResponse]`
- New function `*GroupsClient.NewListPager(string, string, *GroupsClientListOptions) *runtime.Pager[GroupsClientListResponse]`
- New function `*GroupsClient.BeginDelete(context.Context, string, string, string, *GroupsClientBeginDeleteOptions) (*runtime.Poller[GroupsClientDeleteResponse], error)`
- New function `*StaticMembersClient.NewListPager(string, string, string, *StaticMembersClientListOptions) *runtime.Pager[StaticMembersClientListResponse]`
- New function `NewGroupsClient(string, azcore.TokenCredential, *arm.ClientOptions) (*GroupsClient, error)`
- New function `PossibleCreatedByTypeValues() []CreatedByType`
- New function `PossibleAutoLearnPrivateRangesModeValues() []AutoLearnPrivateRangesMode`
- New function `*ManagementGroupNetworkManagerConnectionsClient.CreateOrUpdate(context.Context, string, string, ManagerConnection, *ManagementGroupNetworkManagerConnectionsClientCreateOrUpdateOptions) (ManagementGroupNetworkManagerConnectionsClientCreateOrUpdateResponse, error)`
- New function `*GroupsClient.CreateOrUpdate(context.Context, string, string, string, Group, *GroupsClientCreateOrUpdateOptions) (GroupsClientCreateOrUpdateResponse, error)`
- New function `*ActiveSecurityAdminRule.GetActiveBaseSecurityAdminRule() *ActiveBaseSecurityAdminRule`
- New function `*AdminRuleCollectionsClient.Get(context.Context, string, string, string, string, *AdminRuleCollectionsClientGetOptions) (AdminRuleCollectionsClientGetResponse, error)`
- New function `*ManagersClient.CreateOrUpdate(context.Context, string, string, Manager, *ManagersClientCreateOrUpdateOptions) (ManagersClientCreateOrUpdateResponse, error)`
- New function `*SubscriptionNetworkManagerConnectionsClient.NewListPager(*SubscriptionNetworkManagerConnectionsClientListOptions) *runtime.Pager[SubscriptionNetworkManagerConnectionsClientListResponse]`
- New function `*AdminRule.GetBaseAdminRule() *BaseAdminRule`
- New function `*AdminRulesClient.Get(context.Context, string, string, string, string, string, *AdminRulesClientGetOptions) (AdminRulesClientGetResponse, error)`
- New function `PossiblePacketCaptureTargetTypeValues() []PacketCaptureTargetType`
- New function `*ManagementClient.ListNetworkManagerEffectiveSecurityAdminRules(context.Context, string, string, QueryRequestOptions, *ManagementClientListNetworkManagerEffectiveSecurityAdminRulesOptions) (ManagementClientListNetworkManagerEffectiveSecurityAdminRulesResponse, error)`
- New function `*ManagementGroupNetworkManagerConnectionsClient.Get(context.Context, string, string, *ManagementGroupNetworkManagerConnectionsClientGetOptions) (ManagementGroupNetworkManagerConnectionsClientGetResponse, error)`
- New function `NewExpressRouteProviderPortsLocationClient(string, azcore.TokenCredential, *arm.ClientOptions) (*ExpressRouteProviderPortsLocationClient, error)`
- New function `*DefaultAdminRule.GetBaseAdminRule() *BaseAdminRule`
- New function `*ConnectivityConfigurationsClient.Get(context.Context, string, string, string, *ConnectivityConfigurationsClientGetOptions) (ConnectivityConfigurationsClientGetResponse, error)`
- New function `NewManagersClient(string, azcore.TokenCredential, *arm.ClientOptions) (*ManagersClient, error)`
- New function `*SubscriptionNetworkManagerConnectionsClient.Get(context.Context, string, *SubscriptionNetworkManagerConnectionsClientGetOptions) (SubscriptionNetworkManagerConnectionsClientGetResponse, error)`
- New function `*EffectiveSecurityAdminRule.GetEffectiveBaseSecurityAdminRule() *EffectiveBaseSecurityAdminRule`
- New function `*EffectiveBaseSecurityAdminRule.GetEffectiveBaseSecurityAdminRule() *EffectiveBaseSecurityAdminRule`
- New function `NewScopeConnectionsClient(string, azcore.TokenCredential, *arm.ClientOptions) (*ScopeConnectionsClient, error)`
- New function `NewAdminRuleCollectionsClient(string, azcore.TokenCredential, *arm.ClientOptions) (*AdminRuleCollectionsClient, error)`
- New function `*ManagementClient.ListNetworkManagerEffectiveConnectivityConfigurations(context.Context, string, string, QueryRequestOptions, *ManagementClientListNetworkManagerEffectiveConnectivityConfigurationsOptions) (ManagementClientListNetworkManagerEffectiveConnectivityConfigurationsResponse, error)`
- New function `PossibleGroupConnectivityValues() []GroupConnectivity`
- New function `NewSubscriptionNetworkManagerConnectionsClient(string, azcore.TokenCredential, *arm.ClientOptions) (*SubscriptionNetworkManagerConnectionsClient, error)`
- New function `*AzureFirewallsClient.BeginListLearnedPrefixes(context.Context, string, string, *AzureFirewallsClientBeginListLearnedPrefixesOptions) (*runtime.Poller[AzureFirewallsClientListLearnedPrefixesResponse], error)`
- New function `*ManagersClient.Patch(context.Context, string, string, PatchObject, *ManagersClientPatchOptions) (ManagersClientPatchResponse, error)`
- New function `*ManagersClient.Get(context.Context, string, string, *ManagersClientGetOptions) (ManagersClientGetResponse, error)`
- New function `*StaticMembersClient.CreateOrUpdate(context.Context, string, string, string, string, StaticMember, *StaticMembersClientCreateOrUpdateOptions) (StaticMembersClientCreateOrUpdateResponse, error)`
- New function `*AdminRuleCollectionsClient.NewListPager(string, string, string, *AdminRuleCollectionsClientListOptions) *runtime.Pager[AdminRuleCollectionsClientListResponse]`
- New function `*ScopeConnectionsClient.NewListPager(string, string, *ScopeConnectionsClientListOptions) *runtime.Pager[ScopeConnectionsClientListResponse]`
- New function `*ActiveDefaultSecurityAdminRule.GetActiveBaseSecurityAdminRule() *ActiveBaseSecurityAdminRule`
- New function `*ExpressRouteProviderPortsLocationClient.List(context.Context, *ExpressRouteProviderPortsLocationClientListOptions) (ExpressRouteProviderPortsLocationClientListResponse, error)`
- New function `*ManagerCommitsClient.BeginPost(context.Context, string, string, ManagerCommit, *ManagerCommitsClientBeginPostOptions) (*runtime.Poller[ManagerCommitsClientPostResponse], error)`
- New function `NewManagerCommitsClient(string, azcore.TokenCredential, *arm.ClientOptions) (*ManagerCommitsClient, error)`
- New function `PossibleConfigurationTypeValues() []ConfigurationType`
- New function `NewManagerDeploymentStatusClient(string, azcore.TokenCredential, *arm.ClientOptions) (*ManagerDeploymentStatusClient, error)`
- New function `*ScopeConnectionsClient.CreateOrUpdate(context.Context, string, string, string, ScopeConnection, *ScopeConnectionsClientCreateOrUpdateOptions) (ScopeConnectionsClientCreateOrUpdateResponse, error)`
- New function `*SecurityAdminConfigurationsClient.CreateOrUpdate(context.Context, string, string, string, SecurityAdminConfiguration, *SecurityAdminConfigurationsClientCreateOrUpdateOptions) (SecurityAdminConfigurationsClientCreateOrUpdateResponse, error)`
- New function `NewManagementGroupNetworkManagerConnectionsClient(azcore.TokenCredential, *arm.ClientOptions) (*ManagementGroupNetworkManagerConnectionsClient, error)`
- New function `PossibleDeleteExistingPeeringValues() []DeleteExistingPeering`
- New function `PossibleDeploymentStatusValues() []DeploymentStatus`
- New function `*ManagementGroupNetworkManagerConnectionsClient.NewListPager(string, *ManagementGroupNetworkManagerConnectionsClientListOptions) *runtime.Pager[ManagementGroupNetworkManagerConnectionsClientListResponse]`
- New function `*SecurityAdminConfigurationsClient.NewListPager(string, string, *SecurityAdminConfigurationsClientListOptions) *runtime.Pager[SecurityAdminConfigurationsClientListResponse]`
- New function `PossibleConnectivityTopologyValues() []ConnectivityTopology`
- New function `*StaticMembersClient.Get(context.Context, string, string, string, string, *StaticMembersClientGetOptions) (StaticMembersClientGetResponse, error)`
- New function `PossibleSecurityConfigurationRuleDirectionValues() []SecurityConfigurationRuleDirection`
- New function `*SecurityAdminConfigurationsClient.BeginDelete(context.Context, string, string, string, *SecurityAdminConfigurationsClientBeginDeleteOptions) (*runtime.Poller[SecurityAdminConfigurationsClientDeleteResponse], error)`
- New function `NewSecurityAdminConfigurationsClient(string, azcore.TokenCredential, *arm.ClientOptions) (*SecurityAdminConfigurationsClient, error)`
- New function `*AdminRulesClient.BeginDelete(context.Context, string, string, string, string, string, *AdminRulesClientBeginDeleteOptions) (*runtime.Poller[AdminRulesClientDeleteResponse], error)`
- New function `*SubscriptionNetworkManagerConnectionsClient.CreateOrUpdate(context.Context, string, ManagerConnection, *SubscriptionNetworkManagerConnectionsClientCreateOrUpdateOptions) (SubscriptionNetworkManagerConnectionsClientCreateOrUpdateResponse, error)`
- New struct `ActiveBaseSecurityAdminRule`
- New struct `ActiveConfigurationParameter`
- New struct `ActiveConnectivityConfiguration`
- New struct `ActiveConnectivityConfigurationsListResult`
- New struct `ActiveDefaultSecurityAdminRule`
- New struct `ActiveSecurityAdminRule`
- New struct `ActiveSecurityAdminRulesListResult`
- New struct `AddressPrefixItem`
- New struct `AdminPropertiesFormat`
- New struct `AdminRule`
- New struct `AdminRuleCollection`
- New struct `AdminRuleCollectionListResult`
- New struct `AdminRuleCollectionPropertiesFormat`
- New struct `AdminRuleCollectionsClient`
- New struct `AdminRuleCollectionsClientBeginDeleteOptions`
- New struct `AdminRuleCollectionsClientCreateOrUpdateOptions`
- New struct `AdminRuleCollectionsClientCreateOrUpdateResponse`
- New struct `AdminRuleCollectionsClientDeleteResponse`
- New struct `AdminRuleCollectionsClientGetOptions`
- New struct `AdminRuleCollectionsClientGetResponse`
- New struct `AdminRuleCollectionsClientListOptions`
- New struct `AdminRuleCollectionsClientListResponse`
- New struct `AdminRuleListResult`
- New struct `AdminRulesClient`
- New struct `AdminRulesClientBeginDeleteOptions`
- New struct `AdminRulesClientCreateOrUpdateOptions`
- New struct `AdminRulesClientCreateOrUpdateResponse`
- New struct `AdminRulesClientDeleteResponse`
- New struct `AdminRulesClientGetOptions`
- New struct `AdminRulesClientGetResponse`
- New struct `AdminRulesClientListOptions`
- New struct `AdminRulesClientListResponse`
- New struct `AzureFirewallsClientBeginListLearnedPrefixesOptions`
- New struct `AzureFirewallsClientListLearnedPrefixesResponse`
- New struct `BaseAdminRule`
- New struct `ChildResource`
- New struct `ConfigurationGroup`
- New struct `ConnectivityConfiguration`
- New struct `ConnectivityConfigurationListResult`
- New struct `ConnectivityConfigurationProperties`
- New struct `ConnectivityConfigurationsClient`
- New struct `ConnectivityConfigurationsClientBeginDeleteOptions`
- New struct `ConnectivityConfigurationsClientCreateOrUpdateOptions`
- New struct `ConnectivityConfigurationsClientCreateOrUpdateResponse`
- New struct `ConnectivityConfigurationsClientDeleteResponse`
- New struct `ConnectivityConfigurationsClientGetOptions`
- New struct `ConnectivityConfigurationsClientGetResponse`
- New struct `ConnectivityConfigurationsClientListOptions`
- New struct `ConnectivityConfigurationsClientListResponse`
- New struct `ConnectivityGroupItem`
- New struct `CrossTenantScopes`
- New struct `DefaultAdminPropertiesFormat`
- New struct `DefaultAdminRule`
- New struct `EffectiveBaseSecurityAdminRule`
- New struct `EffectiveConnectivityConfiguration`
- New struct `EffectiveDefaultSecurityAdminRule`
- New struct `EffectiveSecurityAdminRule`
- New struct `ExpressRouteProviderPort`
- New struct `ExpressRouteProviderPortListResult`
- New struct `ExpressRouteProviderPortProperties`
- New struct `ExpressRouteProviderPortsLocationClient`
- New struct `ExpressRouteProviderPortsLocationClientListOptions`
- New struct `ExpressRouteProviderPortsLocationClientListResponse`
- New struct `Group`
- New struct `GroupListResult`
- New struct `GroupProperties`
- New struct `GroupsClient`
- New struct `GroupsClientBeginDeleteOptions`
- New struct `GroupsClientCreateOrUpdateOptions`
- New struct `GroupsClientCreateOrUpdateResponse`
- New struct `GroupsClientDeleteResponse`
- New struct `GroupsClientGetOptions`
- New struct `GroupsClientGetResponse`
- New struct `GroupsClientListOptions`
- New struct `GroupsClientListResponse`
- New struct `Hub`
- New struct `IPPrefixesList`
- New struct `ManagementClientExpressRouteProviderPortOptions`
- New struct `ManagementClientExpressRouteProviderPortResponse`
- New struct `ManagementClientListActiveConnectivityConfigurationsOptions`
- New struct `ManagementClientListActiveConnectivityConfigurationsResponse`
- New struct `ManagementClientListActiveSecurityAdminRulesOptions`
- New struct `ManagementClientListActiveSecurityAdminRulesResponse`
- New struct `ManagementClientListNetworkManagerEffectiveConnectivityConfigurationsOptions`
- New struct `ManagementClientListNetworkManagerEffectiveConnectivityConfigurationsResponse`
- New struct `ManagementClientListNetworkManagerEffectiveSecurityAdminRulesOptions`
- New struct `ManagementClientListNetworkManagerEffectiveSecurityAdminRulesResponse`
- New struct `ManagementGroupNetworkManagerConnectionsClient`
- New struct `ManagementGroupNetworkManagerConnectionsClientCreateOrUpdateOptions`
- New struct `ManagementGroupNetworkManagerConnectionsClientCreateOrUpdateResponse`
- New struct `ManagementGroupNetworkManagerConnectionsClientDeleteOptions`
- New struct `ManagementGroupNetworkManagerConnectionsClientDeleteResponse`
- New struct `ManagementGroupNetworkManagerConnectionsClientGetOptions`
- New struct `ManagementGroupNetworkManagerConnectionsClientGetResponse`
- New struct `ManagementGroupNetworkManagerConnectionsClientListOptions`
- New struct `ManagementGroupNetworkManagerConnectionsClientListResponse`
- New struct `Manager`
- New struct `ManagerCommit`
- New struct `ManagerCommitsClient`
- New struct `ManagerCommitsClientBeginPostOptions`
- New struct `ManagerCommitsClientPostResponse`
- New struct `ManagerConnection`
- New struct `ManagerConnectionListResult`
- New struct `ManagerConnectionProperties`
- New struct `ManagerDeploymentStatus`
- New struct `ManagerDeploymentStatusClient`
- New struct `ManagerDeploymentStatusClientListOptions`
- New struct `ManagerDeploymentStatusClientListResponse`
- New struct `ManagerDeploymentStatusListResult`
- New struct `ManagerDeploymentStatusParameter`
- New struct `ManagerEffectiveConnectivityConfigurationListResult`
- New struct `ManagerEffectiveSecurityAdminRulesListResult`
- New struct `ManagerListResult`
- New struct `ManagerProperties`
- New struct `ManagerPropertiesNetworkManagerScopes`
- New struct `ManagerSecurityGroupItem`
- New struct `ManagersClient`
- New struct `ManagersClientBeginDeleteOptions`
- New struct `ManagersClientCreateOrUpdateOptions`
- New struct `ManagersClientCreateOrUpdateResponse`
- New struct `ManagersClientDeleteResponse`
- New struct `ManagersClientGetOptions`
- New struct `ManagersClientGetResponse`
- New struct `ManagersClientListBySubscriptionOptions`
- New struct `ManagersClientListBySubscriptionResponse`
- New struct `ManagersClientListOptions`
- New struct `ManagersClientListResponse`
- New struct `ManagersClientPatchOptions`
- New struct `ManagersClientPatchResponse`
- New struct `PacketCaptureMachineScope`
- New struct `PatchObject`
- New struct `QueryRequestOptions`
- New struct `ScopeConnection`
- New struct `ScopeConnectionListResult`
- New struct `ScopeConnectionProperties`
- New struct `ScopeConnectionsClient`
- New struct `ScopeConnectionsClientCreateOrUpdateOptions`
- New struct `ScopeConnectionsClientCreateOrUpdateResponse`
- New struct `ScopeConnectionsClientDeleteOptions`
- New struct `ScopeConnectionsClientDeleteResponse`
- New struct `ScopeConnectionsClientGetOptions`
- New struct `ScopeConnectionsClientGetResponse`
- New struct `ScopeConnectionsClientListOptions`
- New struct `ScopeConnectionsClientListResponse`
- New struct `SecurityAdminConfiguration`
- New struct `SecurityAdminConfigurationListResult`
- New struct `SecurityAdminConfigurationPropertiesFormat`
- New struct `SecurityAdminConfigurationsClient`
- New struct `SecurityAdminConfigurationsClientBeginDeleteOptions`
- New struct `SecurityAdminConfigurationsClientCreateOrUpdateOptions`
- New struct `SecurityAdminConfigurationsClientCreateOrUpdateResponse`
- New struct `SecurityAdminConfigurationsClientDeleteResponse`
- New struct `SecurityAdminConfigurationsClientGetOptions`
- New struct `SecurityAdminConfigurationsClientGetResponse`
- New struct `SecurityAdminConfigurationsClientListOptions`
- New struct `SecurityAdminConfigurationsClientListResponse`
- New struct `StaticMember`
- New struct `StaticMemberListResult`
- New struct `StaticMemberProperties`
- New struct `StaticMembersClient`
- New struct `StaticMembersClientCreateOrUpdateOptions`
- New struct `StaticMembersClientCreateOrUpdateResponse`
- New struct `StaticMembersClientDeleteOptions`
- New struct `StaticMembersClientDeleteResponse`
- New struct `StaticMembersClientGetOptions`
- New struct `StaticMembersClientGetResponse`
- New struct `StaticMembersClientListOptions`
- New struct `StaticMembersClientListResponse`
- New struct `SubscriptionNetworkManagerConnectionsClient`
- New struct `SubscriptionNetworkManagerConnectionsClientCreateOrUpdateOptions`
- New struct `SubscriptionNetworkManagerConnectionsClientCreateOrUpdateResponse`
- New struct `SubscriptionNetworkManagerConnectionsClientDeleteOptions`
- New struct `SubscriptionNetworkManagerConnectionsClientDeleteResponse`
- New struct `SubscriptionNetworkManagerConnectionsClientGetOptions`
- New struct `SubscriptionNetworkManagerConnectionsClientGetResponse`
- New struct `SubscriptionNetworkManagerConnectionsClientListOptions`
- New struct `SubscriptionNetworkManagerConnectionsClientListResponse`
- New struct `SystemData`
- New struct `VirtualRouterAutoScaleConfiguration`
- New field `NoInternetAdvertise` in struct `CustomIPPrefixPropertiesFormat`
- New field `FlushConnection` in struct `SecurityGroupPropertiesFormat`
- New field `EnablePacFile` in struct `ExplicitProxySettings`
- New field `Scope` in struct `PacketCaptureParameters`
- New field `TargetType` in struct `PacketCaptureParameters`
- New field `Scope` in struct `PacketCaptureResultProperties`
- New field `TargetType` in struct `PacketCaptureResultProperties`
- New field `AutoLearnPrivateRanges` in struct `FirewallPolicySNAT`
- New field `VirtualRouterAutoScaleConfiguration` in struct `VirtualHubProperties`
- New field `Priority` in struct `ApplicationGatewayRoutingRulePropertiesFormat`


## 1.0.0 (2022-05-16)

The package of `github.com/Azure/azure-sdk-for-go/sdk/resourcemanager/network/armnetwork` is using our [next generation design principles](https://azure.github.io/azure-sdk/general_introduction.html) since version 1.0.0, which contains breaking changes.

To migrate the existing applications to the latest version, please refer to [Migration Guide](https://aka.ms/azsdk/go/mgmt/migration).

To learn more, please refer to our documentation [Quick Start](https://aka.ms/azsdk/go/mgmt).