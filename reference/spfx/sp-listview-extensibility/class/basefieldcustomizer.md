# BaseFieldCustomizer <TProperties> class



_Type parameters: `<TProperties>`_

This is in beta mode

This is the base class that third parties should extend when implementing a client-side extension that customizes the appearance of fields in a SharePoint ListView. In the component manifest, the "extensionType" should be set to "FieldCustomizer".



## Properties

| Property	   | Access Modifier | Type	| Description|
|:-------------|:----|:-------|:-----------|
|`context`     | `public` | [`FieldCustomizerContext`](../../sp-listview-extensibility/class/fieldcustomizercontext.md) | Use context object to access common services and state associated with the component. |




## Methods

| Method	   | Access Modifier | Returns	| Description|
|:-------------|:----|:-------|:-----------|
|[`onDisposeCell()`](ondisposecell-basefieldcustomizer.md)     | `public` | `void` |  |
|[`onRenderCell()`](onrendercell-basefieldcustomizer.md)     | `public` | `void` |  |





