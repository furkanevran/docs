# ServiceCollectionExtensions.AddServiceHandlers method
**namespace:** *[Serenity.Extensions.DependencyInjection](../../README.md#serenity.extensions.dependencyinjection-namespace)*   **assembly**: *[Serenity.Net.Services](../../README.md)*

```csharp
public static IServiceCollection AddServiceHandlers(this IServiceCollection collection, 
    ITypeSource customHandlerTypeSource = null, 
    Func<Type, Type, bool> customHandlerPredicate = null)
```

## See Also

* interface [ITypeSource](../Serenity.Net.Core/../../Serenity.Abstractions/ITypeSource.md)
* class [ServiceCollectionExtensions](../ServiceCollectionExtensions.md)