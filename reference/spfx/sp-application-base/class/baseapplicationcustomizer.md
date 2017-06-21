# BaseApplicationCustomizer <TProperties> class



_Type parameters: `<TProperties>`_

This is in beta mode

This is the base class that third parties should extend when implementing a client-side extension that runs when an application is first starting. In the component manifest, the "extensionType" should be set to "ApplicationCustomizer".



## Properties

| Property	   | Access Modifier | Type	| Description|
|:-------------|:----|:-------|:-----------|
|`context`     | `public` | [`ApplicationCustomizerContext`](../../sp-application-base/class/applicationcustomizercontext.md) | Use context object to access common services and state associated with the component. |




## Methods

| Method	   | Access Modifier | Returns	| Description|
|:-------------|:----|:-------|:-----------|
|[`onRender()`](onrender-baseapplicationcustomizer.md)     | `public` | `void` | This lifecycle event occurs after the shell has constructed the initial page DOM, after the application's onRender() event has occurred. |





