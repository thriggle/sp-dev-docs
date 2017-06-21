# IListViewCommandSetRefreshEventParameters interface





This is in beta mode






## Properties

| Property	   | Type	| Description|
|:-------------|:-------|:-----------|
|`ariaLabel`      | `string` | To customize the ARIA label for the command, the onShowing() handler can assign a different value to this property. Otherwise, it will be the ICommandDefinition.ariaLabel as declared in the component manifest. |
|`commandId`      | `string` | The unique identifier for the command. This is specified as ICommandDefinition.commandId in the component manifest. |
|`selectedRows`      | `ReadonlyArray<RowAccessor>` | The currently selected ListView rows, at the time when the event occurred. |
|`title`      | `string` | To customize the displayed title of the command, the onShowing() handler can assign a different value to this property. Otherwise, it will be the ICommandDefinition.title as declared in the component manifest. |
|`visible`      | `boolean` | Specifies whether the command is displayed or not. To avoid showing the command, the onShowing() handler can assign false to this property. |






