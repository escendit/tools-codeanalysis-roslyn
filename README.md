# NuGet Package: Escendit.Tools.CodeAnalysis.NetAnalyzers

This NuGet package leverages the power of Roslyn .NET Analyzers
to enforce code quality standards that are tailored to the organization's specific needs.
By default,
the package uses a set of analyzer rules that have been configured to align with the organization's coding practices,
ensuring that our code is always compliant and maintainable.

Key features:

- Utilize Roslyn .NET Analyzers for powerful and customizable code analysis
- Defaults suited to the organization's coding practices
- Ensures code compliance and maintainability

## Installation
To install this package, use the NuGet Package Manager Console:

```shell
PM> Install-Package Escendit.Tools.CodeAnalysis.NetAnalyzers
```
Or you can search for "Escendit.Tools.CodeAnalysis.NetAnalyzers"
in the NuGet Package Manager UI and install it from there.

## Usage
After installing the package, the MSBuild and .editorconfig properties will be set automatically.
- You can modify the MSBuild properties by updating the values in your .csproj or .vbproj file.
- You can modify the .editorconfig properties by creating .editorconfig file and overriding the default values.

## Configuration

The NuGet package includes the following default rules and severity levels:


| Rule    | Severity | Severity |
|---------|----------|----------|
| IDE0065 | error    | ❌        |
| IDE0073 | error    | ❌        |
| IDE0161 | error    | ❌        |
| CA1000  | warning  | ⚠️       |
| CA1001  | warning  | ⚠️       |
| CA1002  | warning  | ⚠️       |
| CA1003  | warning  | ⚠️       |
| CA1004  | warning  | ⚠️       |
| CA1005  | warning  | ⚠️       |
| CA1006  | warning  | ⚠️       |
| CA1007  | warning  | ⚠️       |
| CA1008  | warning  | ⚠️       |
| CA1009  | warning  | ⚠️       |
| CA1010  | warning  | ⚠️       |
| CA1011  | warning  | ⚠️       |
| CA1012  | warning  | ⚠️       |
| CA1013  | warning  | ⚠️       |
| CA1014  | warning  | ⚠️       |
| CA1016  | warning  | ⚠️       |
| CA1017  | warning  | ⚠️       |
| CA1018  | warning  | ⚠️       |
| CA1019  | warning  | ⚠️       |
| CA1020  | warning  | ⚠️       |
| CA1021  | warning  | ⚠️       |
| CA1023  | warning  | ⚠️       |
| CA1024  | warning  | ⚠️       |
| CA1025  | warning  | ⚠️       |
| CA1026  | warning  | ⚠️       |
| CA1027  | warning  | ⚠️       |
| CA1028  | warning  | ⚠️       |
| CA1030  | warning  | ⚠️       |
| CA1031  | warning  | ⚠️       |
| CA1032  | warning  | ⚠️       |
| CA1033  | warning  | ⚠️       |
| CA1034  | warning  | ⚠️       |
| CA1035  | warning  | ⚠️       |
| CA1036  | warning  | ⚠️       |
| CA1038  | warning  | ⚠️       |
| CA1039  | warning  | ⚠️       |
| CA1040  | warning  | ⚠️       |
| CA1041  | warning  | ⚠️       |
| CA1043  | warning  | ⚠️       |
| CA1044  | warning  | ⚠️       |
| CA1045  | warning  | ⚠️       |
| CA1046  | warning  | ⚠️       |
| CA1047  | warning  | ⚠️       |
| CA1048  | warning  | ⚠️       |
| CA1049  | warning  | ⚠️       |
| CA1050  | warning  | ⚠️       |
| CA1051  | warning  | ⚠️       |
| CA1052  | warning  | ⚠️       |
| CA1053  | warning  | ⚠️       |
| CA1054  | warning  | ⚠️       |
| CA1055  | warning  | ⚠️       |
| CA1056  | warning  | ⚠️       |
| CA1057  | warning  | ⚠️       |
| CA1058  | warning  | ⚠️       |
| CA1059  | warning  | ⚠️       |
| CA1060  | warning  | ⚠️       |
| CA1061  | warning  | ⚠️       |
| CA1062  | warning  | ⚠️       |
| CA1063  | warning  | ⚠️       |
| CA1064  | warning  | ⚠️       |
| CA1065  | warning  | ⚠️       |
| CA1066  | warning  | ⚠️       |
| CA1067  | warning  | ⚠️       |
| CA1068  | error    | ❌        |
| CA1069  | error    | ❌        |
| CA1070  | error    | ❌        |
| CA1200  | warning  | ⚠️       |
| CA1300  | warning  | ⚠️       |
| CA1301  | warning  | ⚠️       |
| CA1302  | warning  | ⚠️       |
| CA1303  | warning  | ⚠️       |
| CA1304  | warning  | ⚠️       |
| CA1305  | warning  | ⚠️       |
| CA1306  | warning  | ⚠️       |
| CA1307  | warning  | ⚠️       |
| CA1308  | warning  | ⚠️       |
| CA1309  | warning  | ⚠️       |
| CA1310  | warning  | ⚠️       |
| CA1400  | warning  | ⚠️       |
| CA1401  | warning  | ⚠️       |
| CA1402  | warning  | ⚠️       |
| CA1403  | warning  | ⚠️       |
| CA1404  | warning  | ⚠️       |
| CA1405  | warning  | ⚠️       |
| CA1406  | warning  | ⚠️       |
| CA1407  | warning  | ⚠️       |
| CA1408  | warning  | ⚠️       |
| CA1409  | warning  | ⚠️       |
| CA1410  | warning  | ⚠️       |
| CA1411  | warning  | ⚠️       |
| CA1412  | warning  | ⚠️       |
| CA1413  | warning  | ⚠️       |
| CA1414  | warning  | ⚠️       |
| CA1415  | warning  | ⚠️       |
| CA1419  | warning  | ⚠️       |
| CA1500  | warning  | ⚠️       |
| CA1501  | warning  | ⚠️       |
| CA1502  | warning  | ⚠️       |
| CA1504  | warning  | ⚠️       |
| CA1505  | warning  | ⚠️       |
| CA1506  | warning  | ⚠️       |
| CA1507  | warning  | ⚠️       |
| CA1508  | warning  | ⚠️       |
| CA1509  | warning  | ⚠️       |
| CA1600  | warning  | ⚠️       |
| CA1601  | warning  | ⚠️       |
| CA1700  | warning  | ⚠️       |
| CA1701  | warning  | ⚠️       |
| CA1702  | warning  | ⚠️       |
| CA1703  | warning  | ⚠️       |
| CA1704  | warning  | ⚠️       |
| CA1707  | warning  | ⚠️       |
| CA1708  | warning  | ⚠️       |
| CA1709  | warning  | ⚠️       |
| CA1710  | warning  | ⚠️       |
| CA1711  | warning  | ⚠️       |
| CA1712  | warning  | ⚠️       |
| CA1713  | warning  | ⚠️       |
| CA1714  | warning  | ⚠️       |
| CA1715  | warning  | ⚠️       |
| CA1716  | warning  | ⚠️       |
| CA1717  | warning  | ⚠️       |
| CA1719  | warning  | ⚠️       |
| CA1720  | warning  | ⚠️       |
| CA1721  | warning  | ⚠️       |
| CA1722  | warning  | ⚠️       |
| CA1724  | warning  | ⚠️       |
| CA1725  | warning  | ⚠️       |
| CA1726  | warning  | ⚠️       |
| CA1727  | error    | ❌        |
| CA1800  | warning  | ⚠️       |
| CA1801  | warning  | ⚠️       |
| CA1802  | warning  | ⚠️       |
| CA1804  | warning  | ⚠️       |
| CA1805  | warning  | ⚠️       |
| CA1806  | warning  | ⚠️       |
| CA1809  | warning  | ⚠️       |
| CA1810  | warning  | ⚠️       |
| CA1811  | warning  | ⚠️       |
| CA1812  | error    | ❌        |
| CA1813  | warning  | ⚠️       |
| CA1814  | warning  | ⚠️       |
| CA1815  | warning  | ⚠️       |
| CA1816  | warning  | ⚠️       |
| CA1819  | warning  | ⚠️       |
| CA1820  | warning  | ⚠️       |
| CA1821  | warning  | ⚠️       |
| CA1822  | warning  | ⚠️       |
| CA1823  | warning  | ⚠️       |
| CA1824  | warning  | ⚠️       |
| CA1825  | warning  | ⚠️       |
| CA1826  | warning  | ⚠️       |
| CA1827  | warning  | ⚠️       |
| CA1828  | warning  | ⚠️       |
| CA1829  | warning  | ⚠️       |
| CA1830  | warning  | ⚠️       |
| CA1831  | warning  | ⚠️       |
| CA1832  | warning  | ⚠️       |
| CA1833  | warning  | ⚠️       |
| CA1834  | warning  | ⚠️       |
| CA1835  | warning  | ⚠️       |
| CA1836  | warning  | ⚠️       |
| CA1837  | warning  | ⚠️       |
| CA1838  | error    | ❌        |
| CA1839  | warning  | ⚠️       |
| CA1840  | warning  | ⚠️       |
| CA1841  | warning  | ⚠️       |
| CA1842  | error    | ❌        |
| CA1843  | error    | ❌        |
| CA1844  | error    | ❌        |
| CA1845  | warning  | ⚠️       |
| CA1846  | warning  | ⚠️       |
| CA1847  | warning  | ⚠️       |
| CA1848  | warning  | ⚠️       |
| CA1849  | warning  | ⚠️       |
| CA1900  | warning  | ⚠️       |
| CA1901  | warning  | ⚠️       |
| CA1903  | warning  | ⚠️       |
| CA2000  | warning  | ⚠️       |
| CA2001  | warning  | ⚠️       |
| CA2002  | warning  | ⚠️       |
| CA2003  | warning  | ⚠️       |
| CA2004  | warning  | ⚠️       |
| CA2006  | warning  | ⚠️       |
| CA2007  | none     | ⛔        |
| CA2008  | warning  | ⚠️       |
| CA2009  | error    | ❌        |
| CA2011  | warning  | ⚠️       |
| CA2012  | warning  | ⚠️       |
| CA2013  | warning  | ⚠️       |
| CA2015  | warning  | ⚠️       |
| CA2016  | warning  | ⚠️       |
| CA2017  | warning  | ⚠️       |
| CA2018  | warning  | ⚠️       |
| CA2100  | warning  | ⚠️       |
| CA2101  | warning  | ⚠️       |
| CA2102  | warning  | ⚠️       |
| CA2103  | warning  | ⚠️       |
| CA2104  | warning  | ⚠️       |
| CA2105  | warning  | ⚠️       |
| CA2106  | warning  | ⚠️       |
| CA2107  | warning  | ⚠️       |
| CA2108  | warning  | ⚠️       |
| CA2109  | warning  | ⚠️       |
| CA2111  | warning  | ⚠️       |
| CA2112  | warning  | ⚠️       |
| CA2114  | warning  | ⚠️       |
| CA2115  | warning  | ⚠️       |
| CA2116  | warning  | ⚠️       |
| CA2117  | warning  | ⚠️       |
| CA2118  | warning  | ⚠️       |
| CA2119  | warning  | ⚠️       |
| CA2120  | warning  | ⚠️       |
| CA2121  | warning  | ⚠️       |
| CA2122  | warning  | ⚠️       |
| CA2123  | warning  | ⚠️       |
| CA2124  | warning  | ⚠️       |
| CA2126  | warning  | ⚠️       |
| CA2130  | warning  | ⚠️       |
| CA2131  | warning  | ⚠️       |
| CA2132  | warning  | ⚠️       |
| CA2133  | warning  | ⚠️       |
| CA2134  | warning  | ⚠️       |
| CA2135  | warning  | ⚠️       |
| CA2136  | warning  | ⚠️       |
| CA2137  | warning  | ⚠️       |
| CA2138  | warning  | ⚠️       |
| CA2139  | warning  | ⚠️       |
| CA2140  | warning  | ⚠️       |
| CA2141  | warning  | ⚠️       |
| CA2142  | warning  | ⚠️       |
| CA2143  | warning  | ⚠️       |
| CA2144  | warning  | ⚠️       |
| CA2145  | warning  | ⚠️       |
| CA2146  | warning  | ⚠️       |
| CA2147  | warning  | ⚠️       |
| CA2149  | warning  | ⚠️       |
| CA2151  | warning  | ⚠️       |
| CA2153  | warning  | ⚠️       |
| CA2200  | warning  | ⚠️       |
| CA2201  | warning  | ⚠️       |
| CA2205  | warning  | ⚠️       |
| CA2207  | warning  | ⚠️       |
| CA2208  | warning  | ⚠️       |
| CA2210  | warning  | ⚠️       |
| CA2211  | warning  | ⚠️       |
| CA2212  | warning  | ⚠️       |
| CA2213  | warning  | ⚠️       |
| CA2214  | warning  | ⚠️       |
| CA2215  | error    | ❌        |
| CA2216  | warning  | ⚠️       |
| CA2217  | warning  | ⚠️       |
| CA2218  | warning  | ⚠️       |
| CA2219  | warning  | ⚠️       |
| CA2220  | warning  | ⚠️       |
| CA2221  | warning  | ⚠️       |
| CA2222  | warning  | ⚠️       |
| CA2223  | warning  | ⚠️       |
| CA2224  | warning  | ⚠️       |
| CA2225  | warning  | ⚠️       |
| CA2226  | warning  | ⚠️       |
| CA2227  | warning  | ⚠️       |
| CA2228  | warning  | ⚠️       |
| CA2229  | warning  | ⚠️       |
| CA2230  | warning  | ⚠️       |
| CA2231  | warning  | ⚠️       |
| CA2232  | warning  | ⚠️       |
| CA2233  | warning  | ⚠️       |
| CA2234  | warning  | ⚠️       |
| CA2235  | warning  | ⚠️       |
| CA2236  | warning  | ⚠️       |
| CA2237  | warning  | ⚠️       |
| CA2238  | warning  | ⚠️       |
| CA2239  | warning  | ⚠️       |
| CA2240  | warning  | ⚠️       |
| CA2241  | error    | ❌        |
| CA2242  | warning  | ⚠️       |
| CA2243  | warning  | ⚠️       |
| CA2244  | error    | ❌        |
| CA2245  | error    | ❌        |
| CA2246  | error    | ❌        |
| CA2248  | error    | ❌        |
| CA2249  | warning  | ⚠️       |
| CA2250  | error    | ❌        |
| CA2251  | warning  | ⚠️       |
| CA2252  | error    | ❌        |
| CA2253  | error    | ❌        |
| CA2254  | error    | ❌        |
| CA2300  | warning  | ⚠️       |
| CA2301  | warning  | ⚠️       |
| CA2302  | warning  | ⚠️       |
| CA2305  | warning  | ⚠️       |
| CA2310  | warning  | ⚠️       |
| CA2311  | warning  | ⚠️       |
| CA2312  | warning  | ⚠️       |
| CA2315  | warning  | ⚠️       |
| CA2321  | warning  | ⚠️       |
| CA2322  | warning  | ⚠️       |
| CA2326  | warning  | ⚠️       |
| CA2327  | warning  | ⚠️       |
| CA2328  | warning  | ⚠️       |
| CA2329  | warning  | ⚠️       |
| CA2330  | warning  | ⚠️       |
| CA2350  | warning  | ⚠️       |
| CA2351  | warning  | ⚠️       |
| CA2352  | warning  | ⚠️       |
| CA2353  | warning  | ⚠️       |
| CA2354  | warning  | ⚠️       |
| CA2355  | warning  | ⚠️       |
| CA2356  | warning  | ⚠️       |
| CA2361  | warning  | ⚠️       |
| CA2362  | warning  | ⚠️       |
| CA3001  | warning  | ⚠️       |
| CA3002  | warning  | ⚠️       |
| CA3003  | warning  | ⚠️       |
| CA3004  | warning  | ⚠️       |
| CA3005  | warning  | ⚠️       |
| CA3006  | warning  | ⚠️       |
| CA3007  | warning  | ⚠️       |
| CA3008  | warning  | ⚠️       |
| CA3009  | warning  | ⚠️       |
| CA3010  | warning  | ⚠️       |
| CA3011  | warning  | ⚠️       |
| CA3012  | warning  | ⚠️       |
| CA3061  | error    | ❌        |
| CA3075  | error    | ❌        |
| CA3076  | error    | ❌        |
| CA3077  | error    | ❌        |
| CA3147  | error    | ❌        |
| CA5122  | warning  | ⚠️       |
| CA5350  | warning  | ⚠️       |
| CA5351  | warning  | ⚠️       |
| CA5358  | warning  | ⚠️       |
| CA5359  | warning  | ⚠️       |
| CA5360  | error    | ❌        |
| CA5361  | warning  | ⚠️       |
| CA5362  | warning  | ⚠️       |
| CA5363  | error    | ❌        |
| CA5364  | error    | ❌        |
| CA5365  | error    | ❌        |
| CA5366  | warning  | ⚠️       |
| CA5367  | warning  | ⚠️       |
| CA5368  | warning  | ⚠️       |
| CA5369  | warning  | ⚠️       |
| CA5370  | warning  | ⚠️       |
| CA5371  | warning  | ⚠️       |
| CA5372  | warning  | ⚠️       |
| CA5373  | warning  | ⚠️       |
| CA5374  | warning  | ⚠️       |
| CA5375  | warning  | ⚠️       |
| CA5376  | warning  | ⚠️       |
| CA5377  | warning  | ⚠️       |
| CA5378  | warning  | ⚠️       |
| CA5379  | warning  | ⚠️       |
| CA5380  | warning  | ⚠️       |
| CA5381  | warning  | ⚠️       |
| CA5382  | warning  | ⚠️       |
| CA5383  | warning  | ⚠️       |
| CA5384  | warning  | ⚠️       |
| CA5385  | warning  | ⚠️       |
| CA5386  | warning  | ⚠️       |
| CA5387  | warning  | ⚠️       |
| CA5388  | warning  | ⚠️       |
| CA5389  | warning  | ⚠️       |
| CA5390  | warning  | ⚠️       |
| CA5391  | warning  | ⚠️       |
| CA5392  | warning  | ⚠️       |
| CA5393  | warning  | ⚠️       |
| CA5394  | warning  | ⚠️       |
| CA5395  | warning  | ⚠️       |
| CA5396  | warning  | ⚠️       |
| CA5397  | warning  | ⚠️       |
| CA5398  | warning  | ⚠️       |
| CA5399  | warning  | ⚠️       |
| CA5400  | warning  | ⚠️       |
| CA5401  | warning  | ⚠️       |
| CA5402  | warning  | ⚠️       |
| CA5403  | warning  | ⚠️       |
| CA5404  | warning  | ⚠️       |
| CA5405  | warning  | ⚠️       |

To modify the severity level of a rule, you can add the following code to your .editorconfig file:

```editorconfig
dotnet_diagnostic.<Rule>.severity = <Severity>
```

For example, to change the severity level of `CA9999` to "error", add the following line to your .editorconfig file:

```editorconfig
dotnet_diagnostic.CA9999.severity = error
```


## Contributing
If you find a bug or have a feature request, please create an issue in the GitHub repository.

To contribute code, fork the repository and submit a pull request.
Please ensure that your code follows the project's coding standards and is thoroughly tested.

## License
This package is released under the MIT License. See the LICENSE.txt file for details.
