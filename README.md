# Setup-openmodelica

Setup-openmodelica is a GitHub action for installing OpenModelica.
It can be used as follows:

```yaml
jobs:
  build:
    name: "My fancy build"
    runs-on: ubuntu-latest
    steps:
      - name: Install OpenModelica
        uses: THM-MoTE/setup-openmodelica@v0.1.5  # replace 0.1.5 with latest tag
        with:
          version: 1.16.2   # must be full version, 1.16 will not work
```
