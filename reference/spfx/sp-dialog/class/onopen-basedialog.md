# onOpen()
**Note:** The SharePoint Framework is currently in preview and is subject to change. SharePoint Framework client-side web parts are not currently supported for use in production environments.



This method is called before the render method and can be overridden to make preparations for rendering. The loading indicator is displayed during the lifetime of this method.

**Signature:** _@virtual protected onOpen(): [Promise](../../web-apis/class/promise.md)<void>;_

**Returns**: [`Promise`](../../web-apis/class/promise.md)<void>



A promise that resolves when the operations are done and the dialog is ready to render. If the promise is rejected, the dialog will not be rendered and onClose() will not be called.

#### Parameters
None


### Remarks

All resource allocations in onOpen() should be properly disposed in onClose() to a avoid memory leak.

