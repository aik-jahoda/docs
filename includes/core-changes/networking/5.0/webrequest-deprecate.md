### WinHttpHandler removed from .NET runtime

<xref:System.Net.WebRequest>, <xref:System.Net.WebClient> and <xref:System.Net.ServicePoint> classes was marked as deprecate.

#### Version introduced

5.0

#### Change description

<xref:System.Net.WebRequest>, <xref:System.Net.WebClient> and <xref:System.Net.ServicePoint> classes was marked as deprecate. The classes are still available but they are not recomentded for new development. Only construction methods were marked with ObsoleteAttibute to reduce number of analyser warnings.

#### Recommended action

Use the <xref:System.Net.Http.HttpClient?displayProperty=fullName> class instead.

#### Category

Networking

#### Affected APIs

- <xref:System.Net.WebRequest>
- <xref:System.Net.HttpWebRequest>
- <xref:System.Net.FtpWebRequest>
- <xref:System.Net.WebClient>
- <xref:System.Net.ServicePoint>

<!--

#### Affected APIs

- `T:System.Net.WebRequest`
- `T:System.Net.HttpWebRequest`
- `T:System.Net.FtpWebRequest`
- `T:System.Net.WebClient`
- `T:System.Net.ServicePoint`

-->
