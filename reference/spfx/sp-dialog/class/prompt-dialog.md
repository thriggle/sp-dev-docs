# prompt(message,defaultValue)
**Note:** The SharePoint Framework is currently in preview and is subject to change. SharePoint Framework client-side web parts are not currently supported for use in production environments.



Prompts the user for a string value with a user-friendly interface. Calling this method sends a request to application to show the dialog.

**Signature:** _public static prompt(message: string, options?: [IPromptOptions](../../sp-dialog/interface/ipromptoptions.md)): [Promise](../../web-apis/class/promise.md)<string | undefined>;_

**Returns**: [`Promise`](../../web-apis/class/promise.md)<string ,` undefined>`





#### Parameters


| Parameter	   | Type    | Description |
|:-------------|:---------------|:------------|
| `message`    | `string` | The message for prompt dialog |
| `defaultValue`    |  | The default value for the input text field |


### Remarks

There might be a delay until the dialog is approved and shown by the application, for example, if there is another dialog currently being shown. The returned promise resolves when the dialog is successfully shown and closed. The promise rejects if the application rejects the request for any reason.

