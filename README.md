| README.md |
|:---|

<h1 align="center">augustoproiete.snk :key:</h1>
<div align="center">

Strong Name Key Pair used to sign assemblies of my open-source projects

</div>

### Public key (hash algorithm: sha1):
```
0024000004800000940000000602000000240000525341310004000001000100f9da1733f4a1fe
e7a261abfd4a0847b958ac3bfdb1b6a4690823d0b5dc559ba54337722108b1284870360a8d062a
06994126f1fb321f61dbbbc26a52337f780236f37f4e3e376605f1eed1401813f6f61fff6c9c16
87404584d68a6f7a17348ece3086df267ec73de42eba0898bf609db634b81f51ec7c38200a17a3
c0092dfb
```

### Public key token
```
e9f30f7a3d1ee0f9
```

### csproj

```xml
  <ItemGroup>
    <AssemblyAttribute Include="System.Runtime.CompilerServices.InternalsVisibleTo">
      <_Parameter1>ReplaceWithAssemblyName, PublicKey=0024000004800000940000000602000000240000525341310004000001000100f9da1733f4a1fee7a261abfd4a0847b958ac3bfdb1b6a4690823d0b5dc559ba54337722108b1284870360a8d062a06994126f1fb321f61dbbbc26a52337f780236f37f4e3e376605f1eed1401813f6f61fff6c9c1687404584d68a6f7a17348ece3086df267ec73de42eba0898bf609db634b81f51ec7c38200a17a3c0092dfb</_Parameter1>
    </AssemblyAttribute>
  </ItemGroup>
```

### AssemblyInfo

```csharp
[assembly: InternalsVisibleTo("<ReplaceWithAssemblyName>, PublicKey=" +
    "0024000004800000940000000602000000240000525341310004000001000100f9da1733f4a1fe" +
    "e7a261abfd4a0847b958ac3bfdb1b6a4690823d0b5dc559ba54337722108b1284870360a8d062a" +
    "06994126f1fb321f61dbbbc26a52337f780236f37f4e3e376605f1eed1401813f6f61fff6c9c16" +
    "87404584d68a6f7a17348ece3086df267ec73de42eba0898bf609db634b81f51ec7c38200a17a3" +
    "c0092dfb")]
```

---

_Copyright &copy; 2019-2020 C. Augusto Proiete & Contributors - Provided under the [Apache License, Version 2.0](http://apache.org/licenses/LICENSE-2.0.html)._
