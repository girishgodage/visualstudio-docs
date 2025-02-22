---
title: Security Rules rule set for managed code
ms.date: 11/04/2016
ms.topic: reference
ms.assetid: 564aeac6-03fa-41b0-b655-88179f0ab01b
author: jillre
ms.author: jillfra
manager: jillfra
ms.workload:
  - "dotnet"
---
# Security Rules rule set for managed code

Use the Microsoft Security Rules rule set for legacy code analysis to maximize the number of potential security issues that are reported.

|Rule|Description|
|----------|-----------------|
|[CA2100](../code-quality/ca2100.md)|Review SQL queries for security vulnerabilities|
|[CA2102](../code-quality/ca2102.md)|Catch non-CLSCompliant exceptions in general handlers|
|[CA2103](../code-quality/ca2103.md)|Review imperative security|
|[CA2104](../code-quality/ca2104.md)|Do not declare read only mutable reference types|
|[CA2105](../code-quality/ca2105.md)|Array fields should not be read only|
|[CA2106](../code-quality/ca2106.md)|Secure asserts|
|[CA2107](../code-quality/ca2107.md)|Review deny and permit only usage|
|[CA2108](../code-quality/ca2108.md)|Review declarative security on value types|
|[CA2109](../code-quality/ca2109.md)|Review visible event handlers|
|[CA2111](../code-quality/ca2111.md)|Pointers should not be visible|
|[CA2112](../code-quality/ca2112.md)|Secured types should not expose fields|
|[CA2114](../code-quality/ca2114.md)|Method security should be a superset of type|
|[CA2115](../code-quality/ca2115.md)|Call GC.KeepAlive when using native resources|
|[CA2116](../code-quality/ca2116.md)|APTCA methods should only call APTCA methods|
|[CA2117](../code-quality/ca2117.md)|APTCA types should only extend APTCA base types|
|[CA2118](../code-quality/ca2118.md)|Review SuppressUnmanagedCodeSecurityAttribute usage|
|[CA2119](../code-quality/ca2119.md)|Seal methods that satisfy private interfaces|
|[CA2120](../code-quality/ca2120.md)|Secure serialization constructors|
|[CA2121](../code-quality/ca2121.md)|Static constructors should be private|
|[CA2122](../code-quality/ca2122.md)|Do not indirectly expose methods with link demands|
|[CA2123](../code-quality/ca2123.md)|Override link demands should be identical to base|
|[CA2124](../code-quality/ca2124.md)|Wrap vulnerable finally clauses in outer try|
|[CA2126](../code-quality/ca2126.md)|Type link demands require inheritance demands|
|[CA2130](../code-quality/ca2130.md)|Security critical constants should be transparent|
|[CA2131](../code-quality/ca2131.md)|Security critical types may not participate in type equivalence|
|[CA2132](../code-quality/ca2132.md)|Default constructors must be at least as critical as base type default constructors|
|[CA2133](../code-quality/ca2133.md)|Delegates must bind to methods with consistent transparency|
|[CA2134](../code-quality/ca2134.md)|Methods must keep consistent transparency when overriding base methods|
|[CA2135](../code-quality/ca2135.md)|Level 2 assemblies should not contain LinkDemands|
|[CA2136](../code-quality/ca2136.md)|Members should not have conflicting transparency annotations|
|[CA2137](../code-quality/ca2137.md)|Transparent methods must contain only verifiable IL|
|[CA2138](../code-quality/ca2138.md)|Transparent methods must not call methods with the SuppressUnmanagedCodeSecurity attribute|
|[CA2139](../code-quality/ca2139.md)|Transparent methods may not use the HandleProcessCorruptingExceptions attribute|
|[CA2140](../code-quality/ca2140.md)|Transparent code must not reference security critical items|
|[CA2141](../code-quality/ca2141.md)|Transparent methods must not satisfy LinkDemands|
|[CA2142](../code-quality/ca2142.md)|Transparent code should not be protected with LinkDemands|
|[CA2143](../code-quality/ca2143.md)|Transparent methods should not use security demands|
|[CA2144](../code-quality/ca2144.md)|Transparent code should not load assemblies from byte arrays|
|[CA2145](../code-quality/ca2145.md)|Transparent methods should not be decorated with the SuppressUnmanagedCodeSecurityAttribute|
|[CA2146](../code-quality/ca2146.md)|Types must be at least as critical as their base types and interfaces|
|[CA2147](../code-quality/ca2147.md)|Transparent methods may not use security asserts|
|[CA2149](../code-quality/ca2149.md)|Transparent methods must not call into native code|
|[CA2210](../code-quality/ca2210.md)|Assemblies should have valid strong names|
|[CA2300](ca2300.md)|Do not use insecure deserializer BinaryFormatter|
|[CA2301](ca2301.md)|Do not call BinaryFormatter.Deserialize without first setting BinaryFormatter.Binder|
|[CA2302](ca2302.md)|Ensure BinaryFormatter.Binder is set before calling BinaryFormatter.Deserialize|
|[CA2305](ca2305.md)|Do not use insecure deserializer LosFormatter|
|[CA2310](ca2310.md)|Do not use insecure deserializer NetDataContractSerializer|
|[CA2311](ca2311.md)|Do not deserialize without first setting NetDataContractSerializer.Binder|
|[CA2312](ca2312.md)|Ensure NetDataContractSerializer.Binder is set before deserializing|
|[CA2315](ca2315.md)|Do not use insecure deserializer ObjectStateFormatter|
|[CA2321](ca2321.md)|Do not deserialize with JavaScriptSerializer using a SimpleTypeResolver|
|[CA2322](ca2322.md)|Ensure JavaScriptSerializer is not initialized with SimpleTypeResolver before deserializing|
|[CA3001](../code-quality/ca3001.md)|Review code for SQL injection vulnerabilities|
|[CA3002](../code-quality/ca3002.md)|Review code for XSS vulnerabilities|
|[CA3003](../code-quality/ca3003.md)|Review code for file path injection vulnerabilities|
|[CA3004](../code-quality/ca3004.md)|Review code for information disclosure vulnerabilities|
|[CA3005](../code-quality/ca3005.md)|Review code for LDAP injection vulnerabilities|
|[CA3006](../code-quality/ca3006.md)|Review code for process command injection vulnerabilities|
|[CA3007](../code-quality/ca3007.md)|Review code for open redirect vulnerabilities|
|[CA3008](../code-quality/ca3008.md)|Review code for XPath injection vulnerabilities|
|[CA3009](../code-quality/ca3009.md)|Review code for XML injection vulnerabilities|
|[CA3010](../code-quality/ca3010.md)|Review code for XAML injection vulnerabilities|
|[CA3011](../code-quality/ca3011.md)|Review code for DLL injection vulnerabilities|
|[CA3012](../code-quality/ca3012.md)|Review code for regex injection vulnerabilities|
