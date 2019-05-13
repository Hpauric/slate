---
title: Chai API Reference

toc_footers:
  - <a href='http://chaijs.com/api/'>Original Chai Documentation</a>
  - <a href='https://github.com/tripit/slate'>Documentation Powered by Slate</a>

search: true
---

# Introduction

The Chai API is broken down by style or task.

## Assertion Styles

The Expect / Should API covers the BDD assertion styles.
The Assert API covers the TDD assertion style.

## Plugins

The Plugin API will be of use to anyone interested in building plugins as helpers to DRY up your tests, or for release to the community.

## Tools

The Online Test Suite is a live run of Chai’s test suite. Use it to ensure browser compatibility.


# Marketplace ABI

Address: 0x19a8ed4860007a66805782ed7e0bed4e44fc6717


## Functions


###setOwnerCutPerMillion

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|_ownerCutPerMillion|uint256|


###setLegacyNFTAddress

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|_legacyNFTAddress|address|


###ERC721_Interface

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bytes4|


###InterfaceId_ValidateFingerprint

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bytes4|


###unpause

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||


###acceptedToken

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###cancelOrder

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|


###paused

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bool|


###cancelOrder

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|nftAddress|address|
|assetId|uint256|


###createOrder

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|nftAddress|address|
|assetId|uint256|
|priceInWei|uint256|
|expiresAt|uint256|


###initialize

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||


###pause

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||


###owner

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###safeExecuteOrder

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|nftAddress|address|
|assetId|uint256|
|price|uint256|
|fingerprint|bytes|


###ownerCutPerMillion

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||uint256|


###createOrder

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|
|priceInWei|uint256|
|expiresAt|uint256|


###publicationFeeInWei

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||uint256|


###executeOrder

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|nftAddress|address|
|assetId|uint256|
|price|uint256|


###setPublicationFee

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|_publicationFee|uint256|


###isMigrated

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|contractName|string|
|migrationId|string|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bool|


###initialize

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|_acceptedToken|address|
|_legacyNFTAddress|address|
|_owner|address|


###initialize

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|_sender|address|


###legacyNFTAddress

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###auctionByAssetId

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bytes32|
||address|
||uint256|
||uint256|


###orderByAssetId

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
||address|
||uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
|id|bytes32|
|seller|address|
|nftAddress|address|
|price|uint256|
|expiresAt|uint256|


###executeOrder

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|
|price|uint256|


###transferOwnership

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|newOwner|address|


## Events

###OrderCreated

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|id|bytes32|
|assetId|uint256|
|seller|address|
|nftAddress|address|
|priceInWei|uint256|
|expiresAt|uint256|


###OrderSuccessful

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|id|bytes32|
|assetId|uint256|
|seller|address|
|nftAddress|address|
|totalPrice|uint256|
|buyer|address|


###OrderCancelled

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|id|bytes32|
|assetId|uint256|
|seller|address|
|nftAddress|address|


###ChangedPublicationFee

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|publicationFee|uint256|


###ChangedOwnerCutPerMillion

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|ownerCutPerMillion|uint256|


###ChangeLegacyNFTAddress

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|legacyNFTAddress|address|


###AuctionCreated

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|id|bytes32|
|assetId|uint256|
|seller|address|
|priceInWei|uint256|
|expiresAt|uint256|


###AuctionSuccessful

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|id|bytes32|
|assetId|uint256|
|seller|address|
|totalPrice|uint256|
|winner|address|


###AuctionCancelled

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|id|bytes32|
|assetId|uint256|
|seller|address|


###Pause

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|


###Unpause

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|


###OwnershipTransferred

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|previousOwner|address|
|newOwner|address|


###Migrated

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|contractName|string|
|migrationId|string|


# Land Registry

Address: 0x37a92ffdb541aca40eabb787e6fa625a87f58263

## Functions

###supportsInterface

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|_interfaceID|bytes4|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bool|


###proxyOwner

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###name

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||string|


###getApproved

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###approve

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|operator|address|
|assetId|uint256|


###ownerOfLand

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256|
|y|int256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###setLatestToNow

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|user|address|


###totalSupply

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||uint256|


###assignNewParcel

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256|
|y|int256|
|beneficiary|address|


###ownerOfLandMany

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256[]|
|y|int256[]|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address[]|


###latestPing

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
||address|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||uint256|


###updateManyLandData

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256[]|
|y|int256[]|
|data|string|


###transferFrom

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|from|address|
|to|address|
|assetId|uint256|


###isAuthorized

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|operator|address|
|assetId|uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bool|


###authorizedDeploy

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
||address|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bool|


###tokenOfOwnerByIndex

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|owner|address|
|index|uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|


###decimals

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|pure||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||uint256|


###authorizeDeploy

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|beneficiary|address|


###transferLand

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256|
|y|int256|
|to|address|


###safeTransferFrom

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|from|address|
|to|address|
|assetId|uint256|


###initialize

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
||bytes|


###landData

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256|
|y|int256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||string|


###transferManyLand

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256[]|
|y|int256[]|
|to|address|


###exists

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bool|


###tokensOf

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|owner|address|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||uint256[]|


###ping

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||


###ownerOf

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###GET_METADATA

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bytes4|


###isUpdateAuthorized

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|operator|address|
|assetId|uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bool|


###tokenMetadata

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||string|


###encodeTokenId

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|pure||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256|
|y|int256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||uint256|


###balanceOf

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|owner|address|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||uint256|


###currentContract

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###description

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||string|


###decodeTokenId

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|pure||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|value|uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||int256|
||int256|


###assignMultipleParcels

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256[]|
|y|int256[]|
|beneficiary|address|


###createEstateWithMetadata

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256[]|
|y|int256[]|
|beneficiary|address|
|metadata|string|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||uint256|


###landOf

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|owner|address|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||int256[]|
||int256[]|


###owner

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###setEstateRegistry

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|registry|address|


###symbol

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||string|


###updateOperator

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
||uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###setApprovalForAll

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|operator|address|
|authorized|bool|


###exists

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256|
|y|int256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bool|


###setUpdateOperator

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|
|operator|address|


###safeTransferFrom

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|from|address|
|to|address|
|assetId|uint256|
|userData|bytes|


###createEstate

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256[]|
|y|int256[]|
|beneficiary|address|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||uint256|


###updateLandData

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256|
|y|int256|
|data|string|


###estateRegistry

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###isApprovedForAll

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetHolder|address|
|operator|address|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||bool|


###getApprovedAddress

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|view||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|

#### outputs 
| Name | Type |
| ------------- | ------------- |
||address|


###transferOwnership

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|_newOwner|address|


###transferManyLandToEstate

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256[]|
|y|int256[]|
|estateId|uint256|


###transferLandToEstate

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|x|int256|
|y|int256|
|estateId|uint256|


###forbidDeploy

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|function|false|nonpayable||

#### inputs 
| Name | Type |
| ------------- | ------------- |
|beneficiary|address|

## Events

###EstateRegistrySet

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|registry|address|


###Update

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|
|holder|address|
|operator|address|
|data|string|


###UpdateOperator

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|assetId|uint256|
|operator|address|


###Transfer

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|from|address|
|to|address|
|assetId|uint256|
|operator|address|
|userData|bytes|


###Transfer

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|from|address|
|to|address|
|assetId|uint256|


###ApprovalForAll

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|operator|address|
|holder|address|
|authorized|bool|


###Approval

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|owner|address|
|operator|address|
|assetId|uint256|


###OwnerUpdate

| Type | Payable | stateMutability | Anonymous |
| ------------- | ------------- | ------------- | ------------- |
|event|undefined|undefined|false|

#### inputs 
| Name | Type |
| ------------- | ------------- |
|_prevOwner|address|
|_newOwner|address|


