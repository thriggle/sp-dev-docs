# close()
**Note:** The SharePoint Framework is currently in preview and is subject to change. SharePoint Framework client-side web parts are not currently supported for use in production environments.



Close the dialog. This will void the permission to show for this dialog. Every dialog should have a mechanism to eventually close to avoid blocking the user interface. If called on an inactive dialog it will abort the request to show.

**Signature:** _public close(): [Promise](../../web-apis/class/promise.md)<void>;_

**Returns**: [`Promise`](../../web-apis/class/promise.md)<void>



A promise that resolves when the dialog is visually closed, or if it was already closed

#### Parameters
None


