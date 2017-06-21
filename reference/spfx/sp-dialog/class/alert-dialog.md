# alert(message)
**Note:** The SharePoint Framework is currently in preview and is subject to change. SharePoint Framework client-side web parts are not currently supported for use in production environments.



Alerts a message to the user with a user-friendly interface. Calling this method sends a request to application to show the alert dialog.

**Signature:** _public static alert(message: string, options?: [IAlertOptions](../../sp-dialog/interface/ialertoptions.md)): [Promise](../../web-apis/class/promise.md)<void>;_

**Returns**: [`Promise`](../../web-apis/class/promise.md)<void>





#### Parameters


| Parameter	   | Type    | Description |
|:-------------|:---------------|:------------|
| `message`    | `string` | The message to alert |


### Remarks

There might be a delay until the dialog is approved and shown by the application, for example, if there is another dialog currently being shown. The returned promise resolves when the dialog is successfully shown and closed. The promise rejects if the application rejects the request for any reason.

