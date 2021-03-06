---
layout: reference
section: learn
title: InvokeAsync
permalink: /learn/ref/Microsoft.Coyote.Actors.UnitTesting/ActorTestKit-1/InvokeAsync
---
# ActorTestKit&lt;T&gt;.InvokeAsync method (1 of 2)

Invokes the asynchronous actor method with the specified name, and passing the specified optional parameters. Use this method to invoke private methods of the actor.

```csharp
public Task<object> InvokeAsync(string methodName, params object[] parameters)
```

| parameter | description |
| --- | --- |
| methodName | The name of the actor method. |
| parameters | The parameters to the method. |

## See Also

* class [ActorTestKit&lt;T&gt;](../ActorTestKit-1Type)
* namespace [Microsoft.Coyote.Actors.UnitTesting](../ActorTestKit-1Type)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

---

# ActorTestKit&lt;T&gt;.InvokeAsync method (2 of 2)

Invokes the asynchronous actor method with the specified name and parameter types, and passing the specified optional parameters. Use this method to invoke private methods of the actor.

```csharp
public Task<object> InvokeAsync(string methodName, Type[] parameterTypes, 
    params object[] parameters)
```

| parameter | description |
| --- | --- |
| methodName | The name of the actor method. |
| parameterTypes | The parameter types of the method. |
| parameters | The parameters to the method. |

## See Also

* class [ActorTestKit&lt;T&gt;](../ActorTestKit-1Type)
* namespace [Microsoft.Coyote.Actors.UnitTesting](../ActorTestKit-1Type)
* assembly [Microsoft.Coyote](../../MicrosoftCoyoteAssembly)

<!-- DO NOT EDIT: generated by xmldocmd for Microsoft.Coyote.dll -->
