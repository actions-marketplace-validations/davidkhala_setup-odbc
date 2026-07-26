# davidkhala/setup-msodbcsql

Setup ODBC driver for mssql

## Use

```yaml
steps:
- uses: actions/checkout@main
- uses: davidkhala/setup-msodbcsql@main
  with:
    version: "18" # ms odbc sql driver version. Default to 18
```
