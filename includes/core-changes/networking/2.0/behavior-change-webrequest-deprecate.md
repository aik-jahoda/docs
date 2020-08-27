### WebRequest in not recomended for new development

Starting in .NET Core 2.0, <xref:System.Net.WebRequest>, <xref:System.Net.WebClient> and <xref:System.Net.ServicePoint> support was added to .NET Core in version 2.0 for backward compatibility. The reason for returning the API is for API backquard compatibility, however there are considerable runtime breaking changes.

#### Change description

For example:
 1. WebRequest.GetRequestStream alocate memory for whole response
 2. WebClient.CancelAsync doesn't always cancel immediately

#### Version introduced

2.0

#### Recommended action

Use the <xref:System.Net.Http.HttpClient?displayProperty=fullName> class instead of <xref:System.Net.WebClient?displayProperty=fullName>, which is deprecated.

#### Category

Networking

#### Affected APIs

- <xref:System.Net.WebClient.CancelAsync?displayProperty=fullName>

<!--

#### Affected APIs

- `M:System.Net.WebClient.CancelAsync`

-->
