# QobuzApiService.DeleteUserFavorites method (1 of 2)

Removes the track from the favorites.

```csharp
public QobuzApiStatusResponse DeleteUserFavorites(IEnumerable<string> trackIds, 
    IEnumerable<string> albumIds, IEnumerable<string> artistIds)
```

| parameter | description |
| --- | --- |
| trackIds | Ids of the tracks to remove. |
| albumIds | Ids of the albums to remove. |
| artistIds | Ids of the artists to remove. |

## Return Value

A [`QobuzApiStatusResponse`](../../QobuzApiSharp.Models/QobuzApiStatusResponse.md) that identifies if the request was successful ([`Status`](../../QobuzApiSharp.Models/QobuzApiStatusResponse/Status.md) = "success") or not.

## Exceptions

| exception | condition |
| --- | --- |
| [ApiErrorResponseException](../../QobuzApiSharp.Exceptions/ApiErrorResponseException.md) | Thrown if an error occurs while removing the user favorites. |
| [ApiResponseParseErrorException](../../QobuzApiSharp.Exceptions/ApiResponseParseErrorException.md) | Thrown when the API response could not be parsed. |

## See Also

* class [QobuzApiStatusResponse](../../QobuzApiSharp.Models/QobuzApiStatusResponse.md)
* class [QobuzApiService](../QobuzApiService.md)
* namespace [QobuzApiSharp.Service](../../QobuzApiSharp.md)

---

# QobuzApiService.DeleteUserFavorites method (2 of 2)

Removes tracks, albums &amp; artists from the authenticated user's favorites. At least 1 type of favorite to remove is required as parameter.

```csharp
public QobuzApiStatusResponse DeleteUserFavorites(string trackIds, string albumIds, 
    string artistIds)
```

| parameter | description |
| --- | --- |
| trackIds | Ids of the tracks to remove, comma separated list. (optional) |
| albumIds | Ids of the albums to remove, comma separated list. (optional) |
| artistIds | Ids of the artists to remove, comma separated list. (optional) |

## Return Value

A [`QobuzApiStatusResponse`](../../QobuzApiSharp.Models/QobuzApiStatusResponse.md) that identifies if the request was successful ([`Status`](../../QobuzApiSharp.Models/QobuzApiStatusResponse/Status.md) = "success") or not.

## Exceptions

| exception | condition |
| --- | --- |
| [ApiErrorResponseException](../../QobuzApiSharp.Exceptions/ApiErrorResponseException.md) | Thrown if an error occurs while removing the user favorites. |
| [ApiResponseParseErrorException](../../QobuzApiSharp.Exceptions/ApiResponseParseErrorException.md) | Thrown when the API response could not be parsed. |

## See Also

* class [QobuzApiStatusResponse](../../QobuzApiSharp.Models/QobuzApiStatusResponse.md)
* class [QobuzApiService](../QobuzApiService.md)
* namespace [QobuzApiSharp.Service](../../QobuzApiSharp.md)

<!-- DO NOT EDIT: generated by xmldocmd for QobuzApiSharp.dll -->