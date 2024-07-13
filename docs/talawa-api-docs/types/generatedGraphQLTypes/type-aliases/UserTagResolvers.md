[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / UserTagResolvers

# Type Alias: UserTagResolvers\<ContextType, ParentType\>

\> **UserTagResolvers**\<`ContextType`, `ParentType`\>: `object`

## Type Parameters

• **ContextType** = `any`

• **ParentType** *extends* [`ResolversParentTypes`](ResolversParentTypes.md)\[`"UserTag"`\] = [`ResolversParentTypes`](ResolversParentTypes.md)\[`"UserTag"`\]

## Type declaration

### \_\_isTypeOf?

\> `optional` **\_\_isTypeOf**: [`IsTypeOfResolverFn`](IsTypeOfResolverFn.md)\<`ParentType`, `ContextType`\>

### \_id?

\> `optional` **\_id**: [`Resolver`](Resolver.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"ID"`\], `ParentType`, `ContextType`\>

### childTags?

\> `optional` **childTags**: [`Resolver`](Resolver.md)\<[`Maybe`](Maybe.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"UserTagsConnection"`\]\>, `ParentType`, `ContextType`, `Partial`\<[`UserTagChildTagsArgs`](UserTagChildTagsArgs.md)\>\>

### name?

\> `optional` **name**: [`Resolver`](Resolver.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"String"`\], `ParentType`, `ContextType`\>

### organization?

\> `optional` **organization**: [`Resolver`](Resolver.md)\<[`Maybe`](Maybe.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"Organization"`\]\>, `ParentType`, `ContextType`\>

### parentTag?

\> `optional` **parentTag**: [`Resolver`](Resolver.md)\<[`Maybe`](Maybe.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"UserTag"`\]\>, `ParentType`, `ContextType`\>

### usersAssignedTo?

\> `optional` **usersAssignedTo**: [`Resolver`](Resolver.md)\<[`Maybe`](Maybe.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"UsersConnection"`\]\>, `ParentType`, `ContextType`, `Partial`\<[`UserTagUsersAssignedToArgs`](UserTagUsersAssignedToArgs.md)\>\>

## Defined in

[src/types/generatedGraphQLTypes.ts:4696](https://github.com/PalisadoesFoundation/talawa-api/blob/d0c167bb942c4778fba221c2cdd27665fc7dbf61/src/types/generatedGraphQLTypes.ts#L4696)