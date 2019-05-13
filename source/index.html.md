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

