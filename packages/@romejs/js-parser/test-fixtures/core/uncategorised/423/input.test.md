# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 423`

```javascript
Program {
  comments: Array []
  corrupt: true
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 7
      index: 7
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unknown start to an statement expression'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 7
          index: 7
          line: 1
        }
        start: Object {
          column: 7
          index: 7
          line: 1
        }
      }
    }
  ]
  body: Array [
    ForStatement {
      init: undefined
      test: undefined
      update: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 7
          index: 7
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: ExpressionStatement {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 7
            index: 7
            line: 1
          }
          start: Object {
            column: 7
            index: 7
            line: 1
          }
        }
        expression: ReferenceIdentifier {
          name: 'INVALID_PLACEHOLDER'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 7
              index: 7
              line: 1
            }
            start: Object {
              column: 7
              index: 7
              line: 1
            }
          }
        }
      }
    }
  ]
}
```