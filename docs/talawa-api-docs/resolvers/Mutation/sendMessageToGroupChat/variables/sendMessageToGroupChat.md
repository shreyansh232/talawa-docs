[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/sendMessageToGroupChat](../README.md) / sendMessageToGroupChat

# Variable: sendMessageToGroupChat

\> `const` **sendMessageToGroupChat**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"sendMessageToGroupChat"`\]

This function enables to send message to group chat.

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. If the group chat exists.
2. If the user exists
3. If the group chat contains the user.

## Defined in

[src/resolvers/Mutation/sendMessageToGroupChat.ts:20](https://github.com/PalisadoesFoundation/talawa-api/blob/d0c167bb942c4778fba221c2cdd27665fc7dbf61/src/resolvers/Mutation/sendMessageToGroupChat.ts#L20)