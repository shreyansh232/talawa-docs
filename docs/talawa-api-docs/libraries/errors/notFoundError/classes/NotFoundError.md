[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [libraries/errors/notFoundError](../README.md) / NotFoundError

# Class: NotFoundError

This class detects Not Found errors and sends those errors to the superclass ApplicationError.

## Extends

- [`ApplicationError`](../../applicationError/classes/ApplicationError.md)

## Constructors

### new NotFoundError()

\> **new NotFoundError**(`message`, `code`, `param`, `metadata`): [`NotFoundError`](NotFoundError.md)

#### Parameters

• **message**: `string` = `"Not Found"`

• **code**: `null` \| `string` = `null`

• **param**: `null` \| `string` = `null`

• **metadata**: `Record`\<`any`, `any`\> = `\{\}`

#### Returns

[`NotFoundError`](NotFoundError.md)

#### Overrides

[`ApplicationError`](../../applicationError/classes/ApplicationError.md).[`constructor`](../../applicationError/classes/ApplicationError.md#constructors)

#### Defined in

[src/libraries/errors/notFoundError.ts:6](https://github.com/PalisadoesFoundation/talawa-api/blob/d0c167bb942c4778fba221c2cdd27665fc7dbf61/src/libraries/errors/notFoundError.ts#L6)

## Properties

### errors

\> **errors**: [`InterfaceError`](../../applicationError/interfaces/InterfaceError.md)[]

#### Inherited from

[`ApplicationError`](../../applicationError/classes/ApplicationError.md).[`errors`](../../applicationError/classes/ApplicationError.md#errors)

#### Defined in

[src/libraries/errors/applicationError.ts:11](https://github.com/PalisadoesFoundation/talawa-api/blob/d0c167bb942c4778fba221c2cdd27665fc7dbf61/src/libraries/errors/applicationError.ts#L11)

***

### httpCode

\> **httpCode**: `number`

#### Inherited from

[`ApplicationError`](../../applicationError/classes/ApplicationError.md).[`httpCode`](../../applicationError/classes/ApplicationError.md#httpcode)

#### Defined in

[src/libraries/errors/applicationError.ts:12](https://github.com/PalisadoesFoundation/talawa-api/blob/d0c167bb942c4778fba221c2cdd27665fc7dbf61/src/libraries/errors/applicationError.ts#L12)

***

### message

\> **message**: `string`

#### Inherited from

[`ApplicationError`](../../applicationError/classes/ApplicationError.md).[`message`](../../applicationError/classes/ApplicationError.md#message)

#### Defined in

node\_modules/typescript/lib/lib.es5.d.ts:1077

***

### name

\> **name**: `string`

#### Inherited from

[`ApplicationError`](../../applicationError/classes/ApplicationError.md).[`name`](../../applicationError/classes/ApplicationError.md#name)

#### Defined in

node\_modules/typescript/lib/lib.es5.d.ts:1076

***

### stack?

\> `optional` **stack**: `string`

#### Inherited from

[`ApplicationError`](../../applicationError/classes/ApplicationError.md).[`stack`](../../applicationError/classes/ApplicationError.md#stack)

#### Defined in

node\_modules/typescript/lib/lib.es5.d.ts:1078

***

### prepareStackTrace()?

\> `static` `optional` **prepareStackTrace**: (`err`, `stackTraces`) =\> `any`

Optional override for formatting stack traces

#### Parameters

• **err**: `Error`

• **stackTraces**: `CallSite`[]

#### Returns

`any`

#### See

https://v8.dev/docs/stack-trace-api#customizing-stack-traces

#### Inherited from

[`ApplicationError`](../../applicationError/classes/ApplicationError.md).[`prepareStackTrace`](../../applicationError/classes/ApplicationError.md#preparestacktrace)

#### Defined in

node\_modules/@types/node/globals.d.ts:28

***

### stackTraceLimit

\> `static` **stackTraceLimit**: `number`

#### Inherited from

[`ApplicationError`](../../applicationError/classes/ApplicationError.md).[`stackTraceLimit`](../../applicationError/classes/ApplicationError.md#stacktracelimit)

#### Defined in

node\_modules/@types/node/globals.d.ts:30

## Methods

### captureStackTrace()

\> `static` **captureStackTrace**(`targetObject`, `constructorOpt`?): `void`

Create .stack property on a target object

#### Parameters

• **targetObject**: `object`

• **constructorOpt?**: `Function`

#### Returns

`void`

#### Inherited from

[`ApplicationError`](../../applicationError/classes/ApplicationError.md).[`captureStackTrace`](../../applicationError/classes/ApplicationError.md#capturestacktrace)

#### Defined in

node\_modules/@types/node/globals.d.ts:21