# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 137`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
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
      column: 33
      index: 33
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ClassDeclaration {
      id: BindingIdentifier {
        name: 'A'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 7
            index: 7
            line: 1
          }
          start: Object {
            column: 6
            index: 6
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 33
          index: 33
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      meta: ClassHead {
        implements: undefined
        superClass: undefined
        superTypeParameters: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 33
            index: 33
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        body: Array [
          ClassMethod {
            kind: 'get'
            key: ComputedPropertyKey {
              value: ReferenceIdentifier {
                name: 'foo'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 25
                    index: 25
                    line: 1
                  }
                  start: Object {
                    column: 22
                    index: 22
                    line: 1
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 26
                  index: 26
                  line: 1
                }
                start: Object {
                  column: 21
                  index: 21
                  line: 1
                }
              }
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 31
                index: 31
                line: 1
              }
              start: Object {
                column: 10
                index: 10
                line: 1
              }
            }
            body: BlockStatement {
              body: Array []
              directives: Array []
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 31
                  index: 31
                  line: 1
                }
                start: Object {
                  column: 29
                  index: 29
                  line: 1
                }
              }
            }
            head: FunctionHead {
              async: false
              generator: false
              hasHoistedVars: false
              params: Array []
              predicate: undefined
              rest: undefined
              returnType: undefined
              thisType: undefined
              typeParameters: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 29
                  index: 29
                  line: 1
                }
                start: Object {
                  column: 26
                  index: 26
                  line: 1
                }
              }
            }
            meta: ClassPropertyMeta {
              abstract: false
              accessibility: undefined
              optional: false
              readonly: false
              static: true
              typeAnnotation: undefined
              start: Object {
                column: 10
                index: 10
                line: 1
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 26
                  index: 26
                  line: 1
                }
                start: Object {
                  column: 10
                  index: 10
                  line: 1
                }
              }
            }
          }
        ]
      }
    }
  ]
}
```
