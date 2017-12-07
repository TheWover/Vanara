# CoTaskMemoryMethods.AllocSecureStringAnsi Property 
 

Gets the Ansi <a href="http://msdn2.microsoft.com/en-us/library/7kt014s1" target="_blank">SecureString</a> allocation method.

**Namespace:**&nbsp;<a href="46913109-b3e0-3b59-6f7f-071f8aa90bf0">Vanara.InteropServices</a><br />**Assembly:**&nbsp;Vanara.Core (in Vanara.Core.dll) Version: 1.0.3

## Syntax

**C#**<br />
``` C#
public Func<SecureString, IntPtr> AllocSecureStringAnsi { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property AllocSecureStringAnsi As Func(Of SecureString, IntPtr)
	Get
```


#### Property Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/bb549151" target="_blank">Func</a>(<a href="http://msdn2.microsoft.com/en-us/library/7kt014s1" target="_blank">SecureString</a>, <a href="http://msdn2.microsoft.com/en-us/library/5he14kz8" target="_blank">IntPtr</a>)

#### Implements
<a href="03bf3a6c-010f-f6b3-9027-73aa554e7df4">IMemoryMethods.AllocSecureStringAnsi</a><br />

## See Also


#### Reference
<a href="eaeeb474-8f9c-d785-cc32-06312b736aa5">CoTaskMemoryMethods Class</a><br /><a href="46913109-b3e0-3b59-6f7f-071f8aa90bf0">Vanara.InteropServices Namespace</a><br />