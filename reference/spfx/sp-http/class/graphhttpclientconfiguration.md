# GraphHttpClientConfiguration class

_Implements: [`IGraphHttpClientConfiguration`](../../sp-http/interface/igraphhttpclientconfiguration.md)_



This is in beta mode

The GraphHttpClientConfiguration object provides a set of switches for enabling/disabling various features of the GraphHttpClient class. Normally these switches are set (e.g. when calling GraphHttpClient.fetch()) by providing one of the predefined defaults from GraphHttpClientConfigurations, however switches can also be changed via the GraphHttpClientConfiguration.overrideWith() method.


## Constructor
Constructs a new instance of GraphHttpClientCommonConfiguration with the specified flags. The default values will be used for any flags that are missing or undefined. If overrideFlags is specified, it takes precedence over flags.

**Signature:** _constructor(flags: [IGraphHttpClientConfiguration](../../sp-http/interface/igraphhttpclientconfiguration.md), overrideFlags?: IGraphHttpClientConfiguration);_

**Returns**: 



#### Parameters
None


## Properties

| Property	   | Access Modifier | Type	| Description|
|:-------------|:----|:-------|:-----------|
|`flags`     | `public` | [`IGraphHttpClientConfiguration`](../../sp-http/interface/igraphhttpclientconfiguration.md) |  |







