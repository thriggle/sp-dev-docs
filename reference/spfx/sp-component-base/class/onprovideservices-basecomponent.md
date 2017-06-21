# onProvideServices()
**Note:** The SharePoint Framework is currently in preview and is subject to change. SharePoint Framework client-side web parts are not currently supported for use in production environments.



Constructs the object that will be returned by the "services" property.

**Signature:** _@virtual protected onProvideServices(serviceScope: [ServiceScope](../../sp-core-library/class/servicescope.md)): void;_

**Returns**: `void`





#### Parameters
None


### Remarks

Child classes can expose additional services by extending the IExtensionServiceCollection interface, and then overriding consumeServices() function and the "services" property.

