

## Getting past the error

Making the `renovate.json` file use this to block the `build.properties` file and get past the error.


```json
{
    "extends": ["config:base"],
    "ignorePaths": ["**/server/project/build.properties"]
}
```
