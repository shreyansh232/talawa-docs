[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / MembershipRequestResolvers

# Type Alias: MembershipRequestResolvers\<ContextType, ParentType\>

\> **MembershipRequestResolvers**\<`ContextType`, `ParentType`\>: `object`

## Type Parameters

• **ContextType** = `any`

• **ParentType** *extends* [`ResolversParentTypes`](ResolversParentTypes.md)\[`"MembershipRequest"`\] = [`ResolversParentTypes`](ResolversParentTypes.md)\[`"MembershipRequest"`\]

## Type declaration

### \_\_isTypeOf?

\> `optional` **\_\_isTypeOf**: [`IsTypeOfResolverFn`](IsTypeOfResolverFn.md)\<`ParentType`, `ContextType`\>

### \_id?

\> `optional` **\_id**: [`Resolver`](Resolver.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"ID"`\], `ParentType`, `ContextType`\>

### organization?

\> `optional` **organization**: [`Resolver`](Resolver.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"Organization"`\], `ParentType`, `ContextType`\>

### user?

\> `optional` **user**: [`Resolver`](Resolver.md)\<[`ResolversTypes`](ResolversTypes.md)\[`"User"`\], `ParentType`, `ContextType`\>

## Defined in

[src/types/generatedGraphQLTypes.ts:4174](https://github.com/PalisadoesFoundation/talawa-api/blob/d0c167bb942c4778fba221c2cdd27665fc7dbf61/src/types/generatedGraphQLTypes.ts#L4174)