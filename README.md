# Аналог интерфейса [IDictionary\<TKey,TValue\>](https://docs.microsoft.com/ru-ru/dotnet/api/system.collections.generic.idictionary-2?view=netframework-4.8) в Ax2009

Оборачиваем класс `Map` и интерфейс `System.Collections.Generic.IDictionary<TKey,TValue>` в один интерфейс `IDictionary` в Ax2009.  

Оборачиваем классы `Struct`, `System.Collections.Generic.Dictionary<System.String,System.Object>`, `System.Collection.Hashtable` в один интерфейс `IStruct` в Ax2009.  

Интерфейс `IStruct` является аналогом интерфейса `IDictionary`. Кроме функций `Add`, `Item`, `ContainsKey` и `Remove`.

Оба интерфейса наследуют `Enumerable`.

## Диаграмма классов
<img src="out\schema\IDictionary.png" alt="схема">

### Зависимости от других репозиториев
* [SysEnumerators](https://github.com/mazzy-ax/SysEnumerators)
* [SysCLRReflection](https://github.com/d-tolstov/Ax2009-SysCLRReflection)
* [ICollection](https://github.com/d-tolstov/Ax2009-ICollection)
* [SysJSONConvert](https://github.com/d-tolstov/Ax2009-SysJSONConvert)