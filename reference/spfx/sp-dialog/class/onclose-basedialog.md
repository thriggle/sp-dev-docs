# onClose()
**Note:** The SharePoint Framework is currently in preview and is subject to change. SharePoint Framework client-side web parts are not currently supported for use in production environments.



This method is called after the dialog is visually closed and gives an opprotunity for doing clean up. The dialog lifecycle completes after closing and there should be no unmanaged resources left inside the object. Even though the dialog may be revived again for a new lifecycle using show() method, this is considered a whole new lifecycle that should reallocate its own resources. If there are any resources that you would like to keep for multiple lifecycles, consider allocating it outside the dialog object and passing its reference to the dialog constructor.

**Signature:** _@virtual protected onClose(): void;_

**Returns**: `void`





#### Parameters
None


