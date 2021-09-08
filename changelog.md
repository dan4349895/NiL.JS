# Changelog

## 2.5.1388 - 03 November 2019
Fixes:
* Variable in "for (const .. of)" is undefined
* TypeError: Unable to cast object of type 'NiL.JS.Core.JSValue' to type 'NiL.JS.Core.JSObject'. #185
* Indexation in NativeList
* Problem when finding json serializer if other serializers have large inheritance tree
* Useless code elimination in root of script
* Using Script vs Module yields different result
* Error during rendering of Handlebars template
* import statement with empty import map
Added:
* Date.CurrentTimeZone is global context dependent

## 2.5.1372 - 17 September 2019
* Fix backward compatibility

## 2.5.1371 - 17 September 2019
* Introduced changelog ¯\\\_(ツ)_/¯
* Implemented: support of `ParamsArrayAttribute` (**`params`** keyword)
* Fixed: object property named `async` cause a syntax error
* Fixed: `__proto__` is null after trying to set to it primitive value
* Fixed: incorrect `StackOverflowError` in multithreading scenarios
* API of resolving of modules fully reworked. Added new interface `IModuleResolver` and halper base class `CachedModuleResolverBase`

