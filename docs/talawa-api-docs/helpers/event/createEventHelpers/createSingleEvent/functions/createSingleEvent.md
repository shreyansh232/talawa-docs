[**talawa-api**](../../../../../README.md) • **Docs**

***

[talawa-api](../../../../../modules.md) / [helpers/event/createEventHelpers/createSingleEvent](../README.md) / createSingleEvent

# Function: createSingleEvent()

\> **createSingleEvent**(`args`, `creatorId`, `organizationId`, `session`): `Promise`\<[`InterfaceEvent`](../../../../../models/Event/interfaces/InterfaceEvent.md)\>

## Parameters

• **args**: [`MutationCreateEventArgs`](../../../../../types/generatedGraphQLTypes/type-aliases/MutationCreateEventArgs.md)

Arguments provided for the createEvent mutation, including event data.

• **creatorId**: `string`

The ID of the current user creating the event.

• **organizationId**: `string`

The ID of the organization to which the event belongs.

• **session**: `ClientSession`

The MongoDB client session for transactional operations.

## Returns

`Promise`\<[`InterfaceEvent`](../../../../../models/Event/interfaces/InterfaceEvent.md)\>

The created event instance.

## Defined in

[src/helpers/event/createEventHelpers/createSingleEvent.ts:29](https://github.com/PalisadoesFoundation/talawa-api/blob/d0c167bb942c4778fba221c2cdd27665fc7dbf61/src/helpers/event/createEventHelpers/createSingleEvent.ts#L29)