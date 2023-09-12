# NET-Reactor-action
---
An action that download, install and execute NET-Reactor by Eziriz. 
https://www.eziriz.com/dotnet_reactor.htm

Works for Linux and Windows.

## Inputs
### `projectfile`
Path to .NET Reactor project file (nrproj-file) (*required*)

## Example
```yaml
steps:
  -
    name: Checkout code
    uses: actions/checkout@v2
  -
    name: Obfuscate with NET Reactor
    uses: tts-sdrissen/NET-Reactor-action@v1
    with:
      projectfile: "myProject.nrproj"
```
