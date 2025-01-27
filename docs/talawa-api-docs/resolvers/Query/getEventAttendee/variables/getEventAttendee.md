[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Query/getEventAttendee](../README.md) / getEventAttendee

# Variable: getEventAttendee

\> `const` **getEventAttendee**: [`QueryResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/QueryResolvers.md)\[`"getEventAttendee"`\]

Retrieves an attendee record for a specific event and user from the database.

This function performs the following steps:
1. Queries the database to find an `EventAttendee` record that matches the provided event ID and user ID.
2. Returns the found attendee record, or `null` if no matching record is found.

## Param

This parameter is not used in this resolver function but is included for compatibility with GraphQL resolver signatures.

## Param

The arguments provided by the GraphQL query, including:
  - `eventId`: The ID of the event for which the attendee is being retrieved.
  - `userId`: The ID of the user for whom the attendee record is being retrieved.

## Defined in

[src/resolvers/Query/getEventAttendee.ts:19](https://github.com/PalisadoesFoundation/talawa-api/blob/0e711c6a6b57f55ab5776fc9c8edfc5ebc0b3d70/src/resolvers/Query/getEventAttendee.ts#L19)
