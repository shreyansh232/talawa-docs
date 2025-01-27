[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Query/advertisementsConnection](../README.md) / advertisementsConnection

# Variable: advertisementsConnection

\> `const` **advertisementsConnection**: [`QueryResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/QueryResolvers.md)\[`"advertisementsConnection"`\]

Retrieves a paginated list of advertisements based on the provided connection arguments.

This function handles querying and pagination of advertisements using connection arguments. It performs validation of the connection arguments, applies filters and sorting, and then returns a paginated result containing the advertisements. The media URLs for each advertisement are adjusted based on the API root URL provided in the context.

## Param

This parameter represents the parent resolver in the GraphQL schema and is not used in this function.

## Param

The arguments passed to the GraphQL query, including pagination and filter criteria.

## Param

Provides contextual information, including the API root URL. This is used to construct the media URLs for the advertisements.

## Defined in

[src/resolvers/Query/advertisementsConnection.ts:28](https://github.com/PalisadoesFoundation/talawa-api/blob/0e711c6a6b57f55ab5776fc9c8edfc5ebc0b3d70/src/resolvers/Query/advertisementsConnection.ts#L28)
