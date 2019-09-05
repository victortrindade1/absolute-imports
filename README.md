# Absolute Imports

Fonte: https://create-react-app.dev/docs/importing-a-component#absolute-imports

É criado um arquivinho teta pra podermos importar sem precisar de punhetar esses monte de pontinhos até chegar no arquivo q queremos.

Ex:
Sem absolute imports:
`import Foobar from './../../../components/Foobar';`

Com absolute imports:
`import Foobar from 'components/Foobar';`

Para importar path absoluto, crie o arquivo jsconfig.json no root.

## jsconfig.json

```
{
  "compilerOptions": {
    "baseUrl": "src"
  },
  "include": ["src"]
}
```
