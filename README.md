# Аналог интерфейса [IDictionary\<TKey,TValue\>](https://docs.microsoft.com/ru-ru/dotnet/api/system.collections.generic.idictionary-2?view=netframework-4.8) в Ax2009

Оборачиваем класс `Map` и интерфейс `System.Collections.Generic.IDictionary<TKey,TValue>` в один интерфейс в Ax2009.  
Создаём интерфейс `IStruct`.

## Диаграмма классов
<img src="out\schema\IDictionary.png" alt="схема">

### Зависимости от других репозиториев
* [SysEnumerators](https://github.com/mazzy-ax/SysEnumerators)
* [SysCLRReflection](https://github.com/d-tolstov/Ax2009-SysCLRReflection)
* [ICollection](https://github.com/d-tolstov/Ax2009-ICollection)
* [SysJSONConvert](https://github.com/d-tolstov/Ax2009-SysJSONConvert)