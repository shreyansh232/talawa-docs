[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/updateFund](../README.md) / updateFund

# Variable: updateFund

\> `const` **updateFund**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"updateFund"`\]

This function enables to update an organization specific fund.

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. If the user exists.
2. If the Fund of the organization exists.
3. If the organization exists.
4.If the user is authorized to update the fund.
5. If the fund already exists with the same name.

## Defined in

[src/resolvers/Mutation/updateFund.ts:33](https://github.com/PalisadoesFoundation/talawa-api/blob/0e711c6a6b57f55ab5776fc9c8edfc5ebc0b3d70/src/resolvers/Mutation/updateFund.ts#L33)
