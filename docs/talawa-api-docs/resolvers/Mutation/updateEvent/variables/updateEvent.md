[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/updateEvent](../README.md) / updateEvent

# Variable: updateEvent

\> `const` **updateEvent**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"updateEvent"`\]

This function enables to update an event.

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. If the user exists.
2. If the event exists.
3. The the user is an admin of the event.

## Defined in

[src/resolvers/Mutation/updateEvent.ts:41](https://github.com/PalisadoesFoundation/talawa-api/blob/d0c167bb942c4778fba221c2cdd27665fc7dbf61/src/resolvers/Mutation/updateEvent.ts#L41)