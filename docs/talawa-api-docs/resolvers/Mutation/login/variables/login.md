[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/login](../README.md) / login

# Variable: login

\> `const` **login**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"login"`\]

This function enables login.

## Param

parent of current request

## Param

payload provided with the request

## Remarks

The following checks are done:
1. If the user exists
2. If the password is valid

## Defined in

[src/resolvers/Mutation/login.ts:25](https://github.com/PalisadoesFoundation/talawa-api/blob/d0c167bb942c4778fba221c2cdd27665fc7dbf61/src/resolvers/Mutation/login.ts#L25)