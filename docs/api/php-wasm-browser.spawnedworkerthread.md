<!-- Do not edit this file. It is automatically generated by API Documenter. -->

## SpawnedWorkerThread class
<b>Signature:</b>

```typescript
class SpawnedWorkerThread 
```
## Constructors

### SpawnedWorkerThread<!-- -->(<!-- -->messageChannel<!-- -->: [any](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)<!-- -->, serverUrl<!-- -->: [any](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)<!-- -->)


Constructs a new instance of the `SpawnedWorkerThread` class

## Properties

* `messageChannel`    [any](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)
* `serverUrl`    [any](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)

## Methods

### fileExists<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[boolean](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->&gt;

* `path` – 



### HTTPRequest<!-- -->(<!-- -->request<!-- -->: [PHPServerRequest](./php-wasm.phpserverrequest.md)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[PHPResponse](./php-wasm.phpresponse.md)<!-- -->&amp;<!-- -->{<!-- -->text<!-- -->:[string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->;<!-- -->}<!-- -->&gt;

* `request` – 



### internalUrlToPath<!-- -->(<!-- -->internalUrl<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)

* `internalUrl` – An absolute URL based at the PHPServer root.
* Returns: The relative path.


Converts an absolute URL based at the PHPServer to a relative path
without the server pathname and scope.


### isDir<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[boolean](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->&gt;

* `path` – 



### listFiles<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->[]<!-- -->&gt;

* `path` – 



### mkdirTree<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)<!-- -->&gt;

* `path` – 



### pathToInternalUrl<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)

* `path` – The server path to convert to an absolute URL.
* Returns: The absolute URL.


Converts a path to an absolute URL based at the PHPServer
root.


### readFile<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->&gt;

* `path` – 



### run<!-- -->(<!-- -->code<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[PHPOutput](./php-wasm.phpoutput.md)<!-- -->&gt;

* `code` – 



### unlink<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)<!-- -->&gt;

* `path` – 



### writeFile<!-- -->(<!-- -->path<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->, contents<!-- -->: [string](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)<!-- -->)<!-- -->: [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)<!-- -->&lt;[void](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)<!-- -->&gt;

* `path` – 
* `contents` – 




