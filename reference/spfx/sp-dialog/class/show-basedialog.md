# show(options)
**Note:** The SharePoint Framework is currently in preview and is subject to change. SharePoint Framework client-side web parts are not currently supported for use in production environments.



Request the framework to show this dialog.

**Signature:** _public show(options?: [IDialogShowingOptions](../../sp-dialog/interface/idialogshowingoptions.md)): [Promise](../../web-apis/class/promise.md)<void>;_

**Returns**: [`Promise`](../../web-apis/class/promise.md)<void>



A promise that resolves once the dialog is successfully closed (after being shown). The promise rejects if the request is rejected or aborted.

#### Parameters


| Parameter	   | Type    | Description |
|:-------------|:---------------|:------------|
| `options`    | [`IDialogShowingOptions`](../../sp-dialog/interface/idialogshowingoptions.md) | _Optional._ Dialog showing options |


