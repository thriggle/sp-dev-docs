# dispose()
**Note:** The SharePoint Framework is currently in preview and is subject to change. SharePoint Framework client-side web parts are not currently supported for use in production environments.



Diposes the attached DOM tree.

**Signature:** _public dispose(): void;_

**Returns**: `void`





#### Parameters
None


### Remarks

This method can be called to immediately dispose the attached DOM element. Otherwise, it will be disposed by the application when the placeholder is disposed. Calling dispose() invokes the IPlaceholderAttachOptions.onDispose() callback, removes the attached DOM element from the DOM, and assigns DOM element to undefined.

