[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/unregisterForEventByUser](../README.md) / unregisterForEventByUser

# Variable: unregisterForEventByUser

\> `const` **unregisterForEventByUser**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"unregisterForEventByUser"`\]

This function enables a user to unregister from an event.

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
3. If the user is a registrant of the event.

## Defined in

[src/resolvers/Mutation/unregisterForEventByUser.ts:24](https://github.com/PalisadoesFoundation/talawa-api/blob/0e711c6a6b57f55ab5776fc9c8edfc5ebc0b3d70/src/resolvers/Mutation/unregisterForEventByUser.ts#L24)
