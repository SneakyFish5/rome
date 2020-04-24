# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-template-literals > unclosed-interpolation`

```javascript
Program {
  comments: Array []
  corrupt: false
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
      column: 0
      index: 18
      line: 2
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
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unclosed template expression value'}
        advice: Array [
          log {
            category: 'info'
            message: 'We expected to find the closing character <emphasis>}</emphasis> here'
          }
          frame {
            location: Object {
              filename: 'input.js'
              end: Object {
                column: 11
                index: 11
                line: 1
              }
              start: Object {
                column: 11
                index: 11
                line: 1
              }
            }
          }
        ]
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 0
          index: 18
          line: 2
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: TemplateLiteral {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 0
            index: 18
            line: 2
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        quasis: Array [
          TemplateElement {
            cooked: 'hello '
            raw: 'hello '
            tail: false
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 7
                index: 7
                line: 1
              }
              start: Object {
                column: 1
                index: 1
                line: 1
              }
            }
          }
          TemplateElement {
            cooked: ';'
            raw: ';'
            tail: false
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 12
                index: 12
                line: 1
              }
              start: Object {
                column: 11
                index: 11
                line: 1
              }
            }
          }
          TemplateElement {
            cooked: ''
            raw: ''
            tail: false
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 0
                index: 18
                line: 2
              }
              start: Object {
                column: 0
                index: 18
                line: 2
              }
            }
          }
        ]
        expressions: Array [
          NumericLiteral {
            value: 10
            format: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 11
                index: 11
                line: 1
              }
              start: Object {
                column: 9
                index: 9
                line: 1
              }
            }
          }
          TaggedTemplateExpression {
            typeArguments: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 17
                index: 17
                line: 1
              }
              start: Object {
                column: 12
                index: 12
                line: 1
              }
            }
            tag: ReferenceIdentifier {
              name: 'test'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 16
                  index: 16
                  line: 1
                }
                start: Object {
                  column: 12
                  index: 12
                  line: 1
                }
              }
            }
            quasi: TemplateLiteral {
              expressions: Array []
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 17
                  index: 17
                  line: 1
                }
                start: Object {
                  column: 16
                  index: 16
                  line: 1
                }
              }
              quasis: Array [
                TemplateElement {
                  cooked: ''
                  raw: ''
                  tail: false
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 17
                      index: 17
                      line: 1
                    }
                    start: Object {
                      column: 17
                      index: 17
                      line: 1
                    }
                  }
                }
              ]
            }
          }
        ]
      }
    }
  ]
}
```