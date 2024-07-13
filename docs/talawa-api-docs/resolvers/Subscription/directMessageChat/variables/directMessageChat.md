[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Subscription/directMessageChat](../README.md) / directMessageChat

# Variable: directMessageChat

\> `const` **directMessageChat**: [`SubscriptionResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/SubscriptionResolvers.md)\[`"directMessageChat"`\]

This property contained a `subscribe` field, which is used to subscribe
the user to get updates for the `CHAT_CHANNEL` event.

## Remarks

To control updates on a per-client basis, the function uses the `withFilter`
method imported from `apollo-server-express` module.
You can learn about `subscription` [here](https://www.apollographql.com/docs/apollo-server/data/subscriptions/).

## Defined in

[src/resolvers/Subscription/directMessageChat.ts:12](https://github.com/PalisadoesFoundation/talawa-api/blob/d0c167bb942c4778fba221c2cdd27665fc7dbf61/src/resolvers/Subscription/directMessageChat.ts#L12)