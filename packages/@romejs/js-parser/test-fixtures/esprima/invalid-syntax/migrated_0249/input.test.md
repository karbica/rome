# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0249`

```javascript
Program {
  comments: Array []
  corrupt: false
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
      index: 51
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  directives: Array [
    Directive {
      value: 'use strict'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 13
          index: 13
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
  ]
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 45
          index: 45
          line: 1
        }
        start: Object {
          column: 36
          index: 36
          line: 1
        }
      }
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Argument <emphasis>__proto__</emphasis> name clash in strict mode'}
        advice: Array [
          log {
            category: 'info'
            message: 'Defined already here'
          }
          frame {
            location: Object {
              filename: 'input.js'
              end: Object {
                column: 45
                index: 45
                line: 1
              }
              start: Object {
                column: 36
                index: 36
                line: 1
              }
            }
          }
        ]
      }
    }
  ]
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 't'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 24
            index: 24
            line: 1
          }
          start: Object {
            column: 23
            index: 23
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 50
          index: 50
          line: 1
        }
        start: Object {
          column: 14
          index: 14
          line: 1
        }
      }
      body: BlockStatement {
        body: Array []
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 50
            index: 50
            line: 1
          }
          start: Object {
            column: 47
            index: 47
            line: 1
          }
        }
      }
      head: FunctionHead {
        async: false
        generator: false
        hasHoistedVars: false
        predicate: undefined
        rest: undefined
        returnType: undefined
        thisType: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 47
            index: 47
            line: 1
          }
          start: Object {
            column: 24
            index: 24
            line: 1
          }
        }
        params: Array [
          BindingIdentifier {
            name: '__proto__'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 34
                index: 34
                line: 1
              }
              start: Object {
                column: 25
                index: 25
                line: 1
              }
            }
            meta: PatternMeta {
              optional: undefined
              typeAnnotation: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 34
                  index: 34
                  line: 1
                }
                start: Object {
                  column: 25
                  index: 25
                  line: 1
                }
              }
            }
          }
          BindingIdentifier {
            name: '__proto__'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 45
                index: 45
                line: 1
              }
              start: Object {
                column: 36
                index: 36
                line: 1
              }
            }
            meta: PatternMeta {
              optional: undefined
              typeAnnotation: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 45
                  index: 45
                  line: 1
                }
                start: Object {
                  column: 36
                  index: 36
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
