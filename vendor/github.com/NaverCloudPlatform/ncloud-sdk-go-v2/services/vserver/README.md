# Go API client for vserver

    VPC Compute 관련 API<br/>https://ncloud.apigw.ntruss.com/vserver/v2

## Overview
This API client was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project.  By using the [swagger-spec](https://github.com/swagger-api/swagger-spec) from a remote server, you can easily generate an API client.

- API version: 2020-09-17T10:30:17Z
- Package version: 1.0.0
- Build package: io.swagger.codegen.languages.NcpGoForNcloudClientCodegen

## Installation
Put the package under your project folder and add the following in import:
```
"./vserver"
```

## Documentation for API Endpoints

All URIs are relative to *https://ncloud.apigw.ntruss.com/vserver/v2*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*V2Api* | [**AddAccessControlGroupInboundRule**](docs/V2Api.md#addaccesscontrolgroupinboundrule) | **Post** /addAccessControlGroupInboundRule | 
*V2Api* | [**AddAccessControlGroupOutboundRule**](docs/V2Api.md#addaccesscontrolgroupoutboundrule) | **Post** /addAccessControlGroupOutboundRule | 
*V2Api* | [**AddNetworkInterfaceAccessControlGroup**](docs/V2Api.md#addnetworkinterfaceaccesscontrolgroup) | **Post** /addNetworkInterfaceAccessControlGroup | 
*V2Api* | [**AddPlacementGroupServerInstance**](docs/V2Api.md#addplacementgroupserverinstance) | **Post** /addPlacementGroupServerInstance | 
*V2Api* | [**AssociatePublicIpWithServerInstance**](docs/V2Api.md#associatepublicipwithserverinstance) | **Post** /associatePublicIpWithServerInstance | 
*V2Api* | [**AttachBlockStorageInstance**](docs/V2Api.md#attachblockstorageinstance) | **Post** /attachBlockStorageInstance | 
*V2Api* | [**AttachNetworkInterface**](docs/V2Api.md#attachnetworkinterface) | **Post** /attachNetworkInterface | 
*V2Api* | [**ChangeBlockStorageVolumeSize**](docs/V2Api.md#changeblockstoragevolumesize) | **Post** /changeBlockStorageVolumeSize | 
*V2Api* | [**ChangeServerInstanceSpec**](docs/V2Api.md#changeserverinstancespec) | **Post** /changeServerInstanceSpec | 
*V2Api* | [**CreateAccessControlGroup**](docs/V2Api.md#createaccesscontrolgroup) | **Post** /createAccessControlGroup | 
*V2Api* | [**CreateBlockStorageInstance**](docs/V2Api.md#createblockstorageinstance) | **Post** /createBlockStorageInstance | 
*V2Api* | [**CreateBlockStorageSnapshotInstance**](docs/V2Api.md#createblockstoragesnapshotinstance) | **Post** /createBlockStorageSnapshotInstance | 
*V2Api* | [**CreateInitScript**](docs/V2Api.md#createinitscript) | **Post** /createInitScript | 
*V2Api* | [**CreateLoginKey**](docs/V2Api.md#createloginkey) | **Post** /createLoginKey | 
*V2Api* | [**CreateMemberServerImageInstance**](docs/V2Api.md#creatememberserverimageinstance) | **Post** /createMemberServerImageInstance | 
*V2Api* | [**CreateNetworkInterface**](docs/V2Api.md#createnetworkinterface) | **Post** /createNetworkInterface | 
*V2Api* | [**CreatePlacementGroup**](docs/V2Api.md#createplacementgroup) | **Post** /createPlacementGroup | 
*V2Api* | [**CreatePublicIpInstance**](docs/V2Api.md#createpublicipinstance) | **Post** /createPublicIpInstance | 
*V2Api* | [**CreateServerInstances**](docs/V2Api.md#createserverinstances) | **Post** /createServerInstances | 
*V2Api* | [**DeleteAccessControlGroup**](docs/V2Api.md#deleteaccesscontrolgroup) | **Post** /deleteAccessControlGroup | 
*V2Api* | [**DeleteBlockStorageInstances**](docs/V2Api.md#deleteblockstorageinstances) | **Post** /deleteBlockStorageInstances | 
*V2Api* | [**DeleteBlockStorageSnapshotInstances**](docs/V2Api.md#deleteblockstoragesnapshotinstances) | **Post** /deleteBlockStorageSnapshotInstances | 
*V2Api* | [**DeleteInitScripts**](docs/V2Api.md#deleteinitscripts) | **Post** /deleteInitScripts | 
*V2Api* | [**DeleteLoginKeys**](docs/V2Api.md#deleteloginkeys) | **Post** /deleteLoginKeys | 
*V2Api* | [**DeleteMemberServerImageInstances**](docs/V2Api.md#deletememberserverimageinstances) | **Post** /deleteMemberServerImageInstances | 
*V2Api* | [**DeleteNetworkInterface**](docs/V2Api.md#deletenetworkinterface) | **Post** /deleteNetworkInterface | 
*V2Api* | [**DeletePlacementGroup**](docs/V2Api.md#deleteplacementgroup) | **Post** /deletePlacementGroup | 
*V2Api* | [**DeletePublicIpInstance**](docs/V2Api.md#deletepublicipinstance) | **Post** /deletePublicIpInstance | 
*V2Api* | [**DetachBlockStorageInstances**](docs/V2Api.md#detachblockstorageinstances) | **Post** /detachBlockStorageInstances | 
*V2Api* | [**DetachNetworkInterface**](docs/V2Api.md#detachnetworkinterface) | **Post** /detachNetworkInterface | 
*V2Api* | [**DisassociatePublicIpFromServerInstance**](docs/V2Api.md#disassociatepublicipfromserverinstance) | **Post** /disassociatePublicIpFromServerInstance | 
*V2Api* | [**GetAccessControlGroupDetail**](docs/V2Api.md#getaccesscontrolgroupdetail) | **Post** /getAccessControlGroupDetail | 
*V2Api* | [**GetAccessControlGroupList**](docs/V2Api.md#getaccesscontrolgrouplist) | **Post** /getAccessControlGroupList | 
*V2Api* | [**GetAccessControlGroupRuleList**](docs/V2Api.md#getaccesscontrolgrouprulelist) | **Post** /getAccessControlGroupRuleList | 
*V2Api* | [**GetBlockStorageInstanceDetail**](docs/V2Api.md#getblockstorageinstancedetail) | **Post** /getBlockStorageInstanceDetail | 
*V2Api* | [**GetBlockStorageInstanceList**](docs/V2Api.md#getblockstorageinstancelist) | **Post** /getBlockStorageInstanceList | 
*V2Api* | [**GetBlockStorageSnapshotInstanceDetail**](docs/V2Api.md#getblockstoragesnapshotinstancedetail) | **Post** /getBlockStorageSnapshotInstanceDetail | 
*V2Api* | [**GetBlockStorageSnapshotInstanceList**](docs/V2Api.md#getblockstoragesnapshotinstancelist) | **Post** /getBlockStorageSnapshotInstanceList | 
*V2Api* | [**GetInitScriptDetail**](docs/V2Api.md#getinitscriptdetail) | **Post** /getInitScriptDetail | 
*V2Api* | [**GetInitScriptList**](docs/V2Api.md#getinitscriptlist) | **Post** /getInitScriptList | 
*V2Api* | [**GetLoginKeyList**](docs/V2Api.md#getloginkeylist) | **Post** /getLoginKeyList | 
*V2Api* | [**GetMemberServerImageInstanceDetail**](docs/V2Api.md#getmemberserverimageinstancedetail) | **Post** /getMemberServerImageInstanceDetail | 
*V2Api* | [**GetMemberServerImageInstanceList**](docs/V2Api.md#getmemberserverimageinstancelist) | **Post** /getMemberServerImageInstanceList | 
*V2Api* | [**GetNetworkInterfaceDetail**](docs/V2Api.md#getnetworkinterfacedetail) | **Post** /getNetworkInterfaceDetail | 
*V2Api* | [**GetNetworkInterfaceList**](docs/V2Api.md#getnetworkinterfacelist) | **Post** /getNetworkInterfaceList | 
*V2Api* | [**GetPlacementGroupDetail**](docs/V2Api.md#getplacementgroupdetail) | **Post** /getPlacementGroupDetail | 
*V2Api* | [**GetPlacementGroupList**](docs/V2Api.md#getplacementgrouplist) | **Post** /getPlacementGroupList | 
*V2Api* | [**GetPublicIpInstanceDetail**](docs/V2Api.md#getpublicipinstancedetail) | **Post** /getPublicIpInstanceDetail | 
*V2Api* | [**GetPublicIpInstanceList**](docs/V2Api.md#getpublicipinstancelist) | **Post** /getPublicIpInstanceList | 
*V2Api* | [**GetPublicIpTargetServerInstanceList**](docs/V2Api.md#getpubliciptargetserverinstancelist) | **Post** /getPublicIpTargetServerInstanceList | 
*V2Api* | [**GetRegionList**](docs/V2Api.md#getregionlist) | **Post** /getRegionList | 
*V2Api* | [**GetRootPassword**](docs/V2Api.md#getrootpassword) | **Post** /getRootPassword | 
*V2Api* | [**GetRootPasswordServerInstanceList**](docs/V2Api.md#getrootpasswordserverinstancelist) | **Post** /getRootPasswordServerInstanceList | 
*V2Api* | [**GetServerImageProductList**](docs/V2Api.md#getserverimageproductlist) | **Post** /getServerImageProductList | 
*V2Api* | [**GetServerInstanceDetail**](docs/V2Api.md#getserverinstancedetail) | **Post** /getServerInstanceDetail | 
*V2Api* | [**GetServerInstanceList**](docs/V2Api.md#getserverinstancelist) | **Post** /getServerInstanceList | 
*V2Api* | [**GetServerProductList**](docs/V2Api.md#getserverproductlist) | **Post** /getServerProductList | 
*V2Api* | [**GetZoneList**](docs/V2Api.md#getzonelist) | **Post** /getZoneList | 
*V2Api* | [**ImportLoginKey**](docs/V2Api.md#importloginkey) | **Post** /importLoginKey | 
*V2Api* | [**RebootServerInstances**](docs/V2Api.md#rebootserverinstances) | **Post** /rebootServerInstances | 
*V2Api* | [**RemoveAccessControlGroupInboundRule**](docs/V2Api.md#removeaccesscontrolgroupinboundrule) | **Post** /removeAccessControlGroupInboundRule | 
*V2Api* | [**RemoveAccessControlGroupOutboundRule**](docs/V2Api.md#removeaccesscontrolgroupoutboundrule) | **Post** /removeAccessControlGroupOutboundRule | 
*V2Api* | [**RemoveNetworkInterfaceAccessControlGroup**](docs/V2Api.md#removenetworkinterfaceaccesscontrolgroup) | **Post** /removeNetworkInterfaceAccessControlGroup | 
*V2Api* | [**RemovePlacementGroupServerInstance**](docs/V2Api.md#removeplacementgroupserverinstance) | **Post** /removePlacementGroupServerInstance | 
*V2Api* | [**StartServerInstances**](docs/V2Api.md#startserverinstances) | **Post** /startServerInstances | 
*V2Api* | [**StopServerInstances**](docs/V2Api.md#stopserverinstances) | **Post** /stopServerInstances | 
*V2Api* | [**TerminateServerInstances**](docs/V2Api.md#terminateserverinstances) | **Post** /terminateServerInstances | 


## Documentation For Models

 - [AccessControlGroup](docs/AccessControlGroup.md)
 - [AccessControlGroupRule](docs/AccessControlGroupRule.md)
 - [AddAccessControlGroupInboundRuleRequest](docs/AddAccessControlGroupInboundRuleRequest.md)
 - [AddAccessControlGroupInboundRuleResponse](docs/AddAccessControlGroupInboundRuleResponse.md)
 - [AddAccessControlGroupOutboundRuleRequest](docs/AddAccessControlGroupOutboundRuleRequest.md)
 - [AddAccessControlGroupOutboundRuleResponse](docs/AddAccessControlGroupOutboundRuleResponse.md)
 - [AddAccessControlGroupRuleParameter](docs/AddAccessControlGroupRuleParameter.md)
 - [AddNetworkInterfaceAccessControlGroupRequest](docs/AddNetworkInterfaceAccessControlGroupRequest.md)
 - [AddNetworkInterfaceAccessControlGroupResponse](docs/AddNetworkInterfaceAccessControlGroupResponse.md)
 - [AddPlacementGroupServerInstanceRequest](docs/AddPlacementGroupServerInstanceRequest.md)
 - [AddPlacementGroupServerInstanceResponse](docs/AddPlacementGroupServerInstanceResponse.md)
 - [AssociatePublicIpWithServerInstanceRequest](docs/AssociatePublicIpWithServerInstanceRequest.md)
 - [AssociatePublicIpWithServerInstanceResponse](docs/AssociatePublicIpWithServerInstanceResponse.md)
 - [AttachBlockStorageInstanceRequest](docs/AttachBlockStorageInstanceRequest.md)
 - [AttachBlockStorageInstanceResponse](docs/AttachBlockStorageInstanceResponse.md)
 - [AttachNetworkInterfaceRequest](docs/AttachNetworkInterfaceRequest.md)
 - [AttachNetworkInterfaceResponse](docs/AttachNetworkInterfaceResponse.md)
 - [BlockStorageInstance](docs/BlockStorageInstance.md)
 - [BlockStorageSnapshotInstance](docs/BlockStorageSnapshotInstance.md)
 - [ChangeBlockStorageVolumeSizeRequest](docs/ChangeBlockStorageVolumeSizeRequest.md)
 - [ChangeBlockStorageVolumeSizeResponse](docs/ChangeBlockStorageVolumeSizeResponse.md)
 - [ChangeServerInstanceSpecRequest](docs/ChangeServerInstanceSpecRequest.md)
 - [ChangeServerInstanceSpecResponse](docs/ChangeServerInstanceSpecResponse.md)
 - [CommonCode](docs/CommonCode.md)
 - [CreateAccessControlGroupRequest](docs/CreateAccessControlGroupRequest.md)
 - [CreateAccessControlGroupResponse](docs/CreateAccessControlGroupResponse.md)
 - [CreateBlockStorageInstanceRequest](docs/CreateBlockStorageInstanceRequest.md)
 - [CreateBlockStorageInstanceResponse](docs/CreateBlockStorageInstanceResponse.md)
 - [CreateBlockStorageSnapshotInstanceRequest](docs/CreateBlockStorageSnapshotInstanceRequest.md)
 - [CreateBlockStorageSnapshotInstanceResponse](docs/CreateBlockStorageSnapshotInstanceResponse.md)
 - [CreateInitScriptRequest](docs/CreateInitScriptRequest.md)
 - [CreateInitScriptResponse](docs/CreateInitScriptResponse.md)
 - [CreateLoginKeyRequest](docs/CreateLoginKeyRequest.md)
 - [CreateLoginKeyResponse](docs/CreateLoginKeyResponse.md)
 - [CreateMemberServerImageInstanceRequest](docs/CreateMemberServerImageInstanceRequest.md)
 - [CreateMemberServerImageInstanceResponse](docs/CreateMemberServerImageInstanceResponse.md)
 - [CreateNetworkInterfaceRequest](docs/CreateNetworkInterfaceRequest.md)
 - [CreateNetworkInterfaceResponse](docs/CreateNetworkInterfaceResponse.md)
 - [CreatePlacementGroupRequest](docs/CreatePlacementGroupRequest.md)
 - [CreatePlacementGroupResponse](docs/CreatePlacementGroupResponse.md)
 - [CreatePublicIpInstanceRequest](docs/CreatePublicIpInstanceRequest.md)
 - [CreatePublicIpInstanceResponse](docs/CreatePublicIpInstanceResponse.md)
 - [CreateServerInstancesRequest](docs/CreateServerInstancesRequest.md)
 - [CreateServerInstancesResponse](docs/CreateServerInstancesResponse.md)
 - [DeleteAccessControlGroupRequest](docs/DeleteAccessControlGroupRequest.md)
 - [DeleteAccessControlGroupResponse](docs/DeleteAccessControlGroupResponse.md)
 - [DeleteBlockStorageInstancesRequest](docs/DeleteBlockStorageInstancesRequest.md)
 - [DeleteBlockStorageInstancesResponse](docs/DeleteBlockStorageInstancesResponse.md)
 - [DeleteBlockStorageSnapshotInstancesRequest](docs/DeleteBlockStorageSnapshotInstancesRequest.md)
 - [DeleteBlockStorageSnapshotInstancesResponse](docs/DeleteBlockStorageSnapshotInstancesResponse.md)
 - [DeleteInitScriptsRequest](docs/DeleteInitScriptsRequest.md)
 - [DeleteInitScriptsResponse](docs/DeleteInitScriptsResponse.md)
 - [DeleteLoginKeysRequest](docs/DeleteLoginKeysRequest.md)
 - [DeleteLoginKeysResponse](docs/DeleteLoginKeysResponse.md)
 - [DeleteMemberServerImageInstancesRequest](docs/DeleteMemberServerImageInstancesRequest.md)
 - [DeleteMemberServerImageInstancesResponse](docs/DeleteMemberServerImageInstancesResponse.md)
 - [DeleteNetworkInterfaceRequest](docs/DeleteNetworkInterfaceRequest.md)
 - [DeleteNetworkInterfaceResponse](docs/DeleteNetworkInterfaceResponse.md)
 - [DeletePlacementGroupRequest](docs/DeletePlacementGroupRequest.md)
 - [DeletePlacementGroupResponse](docs/DeletePlacementGroupResponse.md)
 - [DeletePublicIpInstanceRequest](docs/DeletePublicIpInstanceRequest.md)
 - [DeletePublicIpInstanceResponse](docs/DeletePublicIpInstanceResponse.md)
 - [DetachBlockStorageInstancesRequest](docs/DetachBlockStorageInstancesRequest.md)
 - [DetachBlockStorageInstancesResponse](docs/DetachBlockStorageInstancesResponse.md)
 - [DetachNetworkInterfaceRequest](docs/DetachNetworkInterfaceRequest.md)
 - [DetachNetworkInterfaceResponse](docs/DetachNetworkInterfaceResponse.md)
 - [DisassociatePublicIpFromServerInstanceRequest](docs/DisassociatePublicIpFromServerInstanceRequest.md)
 - [DisassociatePublicIpFromServerInstanceResponse](docs/DisassociatePublicIpFromServerInstanceResponse.md)
 - [GetAccessControlGroupDetailRequest](docs/GetAccessControlGroupDetailRequest.md)
 - [GetAccessControlGroupDetailResponse](docs/GetAccessControlGroupDetailResponse.md)
 - [GetAccessControlGroupListRequest](docs/GetAccessControlGroupListRequest.md)
 - [GetAccessControlGroupListResponse](docs/GetAccessControlGroupListResponse.md)
 - [GetAccessControlGroupRuleListRequest](docs/GetAccessControlGroupRuleListRequest.md)
 - [GetAccessControlGroupRuleListResponse](docs/GetAccessControlGroupRuleListResponse.md)
 - [GetBlockStorageInstanceDetailRequest](docs/GetBlockStorageInstanceDetailRequest.md)
 - [GetBlockStorageInstanceDetailResponse](docs/GetBlockStorageInstanceDetailResponse.md)
 - [GetBlockStorageInstanceListRequest](docs/GetBlockStorageInstanceListRequest.md)
 - [GetBlockStorageInstanceListResponse](docs/GetBlockStorageInstanceListResponse.md)
 - [GetBlockStorageSnapshotInstanceDetailRequest](docs/GetBlockStorageSnapshotInstanceDetailRequest.md)
 - [GetBlockStorageSnapshotInstanceDetailResponse](docs/GetBlockStorageSnapshotInstanceDetailResponse.md)
 - [GetBlockStorageSnapshotInstanceListRequest](docs/GetBlockStorageSnapshotInstanceListRequest.md)
 - [GetBlockStorageSnapshotInstanceListResponse](docs/GetBlockStorageSnapshotInstanceListResponse.md)
 - [GetInitScriptDetailRequest](docs/GetInitScriptDetailRequest.md)
 - [GetInitScriptDetailResponse](docs/GetInitScriptDetailResponse.md)
 - [GetInitScriptListRequest](docs/GetInitScriptListRequest.md)
 - [GetInitScriptListResponse](docs/GetInitScriptListResponse.md)
 - [GetLoginKeyListRequest](docs/GetLoginKeyListRequest.md)
 - [GetLoginKeyListResponse](docs/GetLoginKeyListResponse.md)
 - [GetMemberServerImageInstanceDetailRequest](docs/GetMemberServerImageInstanceDetailRequest.md)
 - [GetMemberServerImageInstanceDetailResponse](docs/GetMemberServerImageInstanceDetailResponse.md)
 - [GetMemberServerImageInstanceListRequest](docs/GetMemberServerImageInstanceListRequest.md)
 - [GetMemberServerImageInstanceListResponse](docs/GetMemberServerImageInstanceListResponse.md)
 - [GetNetworkInterfaceDetailRequest](docs/GetNetworkInterfaceDetailRequest.md)
 - [GetNetworkInterfaceDetailResponse](docs/GetNetworkInterfaceDetailResponse.md)
 - [GetNetworkInterfaceListRequest](docs/GetNetworkInterfaceListRequest.md)
 - [GetNetworkInterfaceListResponse](docs/GetNetworkInterfaceListResponse.md)
 - [GetPlacementGroupDetailRequest](docs/GetPlacementGroupDetailRequest.md)
 - [GetPlacementGroupDetailResponse](docs/GetPlacementGroupDetailResponse.md)
 - [GetPlacementGroupListRequest](docs/GetPlacementGroupListRequest.md)
 - [GetPlacementGroupListResponse](docs/GetPlacementGroupListResponse.md)
 - [GetPublicIpInstanceDetailRequest](docs/GetPublicIpInstanceDetailRequest.md)
 - [GetPublicIpInstanceDetailResponse](docs/GetPublicIpInstanceDetailResponse.md)
 - [GetPublicIpInstanceListRequest](docs/GetPublicIpInstanceListRequest.md)
 - [GetPublicIpInstanceListResponse](docs/GetPublicIpInstanceListResponse.md)
 - [GetPublicIpTargetServerInstanceListRequest](docs/GetPublicIpTargetServerInstanceListRequest.md)
 - [GetPublicIpTargetServerInstanceListResponse](docs/GetPublicIpTargetServerInstanceListResponse.md)
 - [GetRegionListRequest](docs/GetRegionListRequest.md)
 - [GetRegionListResponse](docs/GetRegionListResponse.md)
 - [GetRootPasswordRequest](docs/GetRootPasswordRequest.md)
 - [GetRootPasswordResponse](docs/GetRootPasswordResponse.md)
 - [GetRootPasswordServerInstanceListRequest](docs/GetRootPasswordServerInstanceListRequest.md)
 - [GetRootPasswordServerInstanceListResponse](docs/GetRootPasswordServerInstanceListResponse.md)
 - [GetServerImageProductListRequest](docs/GetServerImageProductListRequest.md)
 - [GetServerImageProductListResponse](docs/GetServerImageProductListResponse.md)
 - [GetServerInstanceDetailRequest](docs/GetServerInstanceDetailRequest.md)
 - [GetServerInstanceDetailResponse](docs/GetServerInstanceDetailResponse.md)
 - [GetServerInstanceListRequest](docs/GetServerInstanceListRequest.md)
 - [GetServerInstanceListResponse](docs/GetServerInstanceListResponse.md)
 - [GetServerProductListRequest](docs/GetServerProductListRequest.md)
 - [GetServerProductListResponse](docs/GetServerProductListResponse.md)
 - [GetZoneListRequest](docs/GetZoneListRequest.md)
 - [GetZoneListResponse](docs/GetZoneListResponse.md)
 - [ImportLoginKeyRequest](docs/ImportLoginKeyRequest.md)
 - [ImportLoginKeyResponse](docs/ImportLoginKeyResponse.md)
 - [InitScript](docs/InitScript.md)
 - [LoginKey](docs/LoginKey.md)
 - [MemberServerImageInstance](docs/MemberServerImageInstance.md)
 - [NetworkInterface](docs/NetworkInterface.md)
 - [NetworkInterfaceParameter](docs/NetworkInterfaceParameter.md)
 - [PlacementGroup](docs/PlacementGroup.md)
 - [Product](docs/Product.md)
 - [PublicIpInstance](docs/PublicIpInstance.md)
 - [RebootServerInstancesRequest](docs/RebootServerInstancesRequest.md)
 - [RebootServerInstancesResponse](docs/RebootServerInstancesResponse.md)
 - [Region](docs/Region.md)
 - [RemoveAccessControlGroupInboundRuleRequest](docs/RemoveAccessControlGroupInboundRuleRequest.md)
 - [RemoveAccessControlGroupInboundRuleResponse](docs/RemoveAccessControlGroupInboundRuleResponse.md)
 - [RemoveAccessControlGroupOutboundRuleRequest](docs/RemoveAccessControlGroupOutboundRuleRequest.md)
 - [RemoveAccessControlGroupOutboundRuleResponse](docs/RemoveAccessControlGroupOutboundRuleResponse.md)
 - [RemoveAccessControlGroupRuleParameter](docs/RemoveAccessControlGroupRuleParameter.md)
 - [RemoveNetworkInterfaceAccessControlGroupRequest](docs/RemoveNetworkInterfaceAccessControlGroupRequest.md)
 - [RemoveNetworkInterfaceAccessControlGroupResponse](docs/RemoveNetworkInterfaceAccessControlGroupResponse.md)
 - [RemovePlacementGroupServerInstanceRequest](docs/RemovePlacementGroupServerInstanceRequest.md)
 - [RemovePlacementGroupServerInstanceResponse](docs/RemovePlacementGroupServerInstanceResponse.md)
 - [RootPasswordServerInstance](docs/RootPasswordServerInstance.md)
 - [RootPasswordServerInstanceParameter](docs/RootPasswordServerInstanceParameter.md)
 - [ServerInstance](docs/ServerInstance.md)
 - [StartServerInstancesRequest](docs/StartServerInstancesRequest.md)
 - [StartServerInstancesResponse](docs/StartServerInstancesResponse.md)
 - [StopServerInstancesRequest](docs/StopServerInstancesRequest.md)
 - [StopServerInstancesResponse](docs/StopServerInstancesResponse.md)
 - [TerminateServerInstancesRequest](docs/TerminateServerInstancesRequest.md)
 - [TerminateServerInstancesResponse](docs/TerminateServerInstancesResponse.md)
 - [Zone](docs/Zone.md)
