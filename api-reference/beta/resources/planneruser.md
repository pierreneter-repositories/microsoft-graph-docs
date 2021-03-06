# plannerUser resource type

> **Important**: APIs under the /beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

The **plannerUser** resource provide access to Planner resources for a [user](user.md). It doesn't contain any usable properties.


## Methods

| Method		   | Return Type	|Description|
|:---------------|:--------|:----------|
|[List plans](../api/planneruser_list_plans.md) |[plannerPlan](plannerplan.md) collection| Get a **plannerPlan** object collection.|
|[List tasks](../api/planneruser_list_tasks.md) |[plannerTask](plannertask.md) collection| Get a **plannerTask** object collection.|

## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|String| Read-only. Identifier of the planenrUser|

## Relationships
| Relationship | Type	|Description|
|:---------------|:--------|:----------|
|plans|[plannerPlan](plannerplan.md) collection| Read-only. Nullable. Returns the [plannerTasks](plannertask.md) assigned to the user.|
|tasks|[plannerTask](plannertask.md) collection| Read-only. Nullable. Returns the [plannerPlans](plannerplan.md) shared with the user.|

## JSON representation
Here is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.plannerUser"
}-->

```json
{
  "id": "String (identifier)"
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "plannerUser resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->