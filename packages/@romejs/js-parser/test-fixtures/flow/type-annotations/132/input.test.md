# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > type-annotations > 132`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 27
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
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Cannot overwrite primitive type number'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'module'
        end: Object {
          column: 15
          index: 15
          line: 1
        }
        start: Object {
          column: 9
          index: 9
          line: 1
        }
      }
    }
  ]
  body: Array [
    TypeAliasTypeAnnotation {
      id: BindingIdentifier {
        name: 'foo'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 8
            index: 8
            line: 1
          }
          start: Object {
            column: 5
            index: 5
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 26
          index: 26
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      right: StringKeywordTypeAnnotation {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 25
            index: 25
            line: 1
          }
          start: Object {
            column: 19
            index: 19
            line: 1
          }
        }
      }
      typeParameters: FlowTypeParameterDeclaration {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 16
            index: 16
            line: 1
          }
          start: Object {
            column: 8
            index: 8
            line: 1
          }
        }
        params: Array [
          FlowTypeParameter {
            name: 'number'
            bound: undefined
            default: undefined
            variance: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 15
                index: 15
                line: 1
              }
              start: Object {
                column: 9
                index: 9
                line: 1
              }
            }
          }
        ]
      }
    }
  ]
}
```
