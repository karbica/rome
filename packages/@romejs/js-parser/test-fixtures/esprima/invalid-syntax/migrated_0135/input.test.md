# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0135`

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
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 13
          index: 13
          line: 1
        }
        start: Object {
          column: 13
          index: 13
          line: 1
        }
      }
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unclosed catch clause param'}
        advice: Array [
          log {
            category: 'info'
            message: 'We expected to find the closing character <emphasis>)</emphasis> here'
          }
          frame {
            location: Object {
              filename: 'input.js'
              end: Object {
                column: 20
                index: 20
                line: 1
              }
              start: Object {
                column: 20
                index: 20
                line: 1
              }
            }
          }
        ]
      }
    }
  ]
  body: Array [
    TryStatement {
      finalizer: undefined
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
      block: BlockStatement {
        body: Array []
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 6
            index: 6
            line: 1
          }
          start: Object {
            column: 4
            index: 4
            line: 1
          }
        }
      }
      handler: CatchClause {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 26
            index: 26
            line: 1
          }
          start: Object {
            column: 7
            index: 7
            line: 1
          }
        }
        param: BindingIdentifier {
          name: 'answer'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 20
              index: 20
              line: 1
            }
            start: Object {
              column: 14
              index: 14
              line: 1
            }
          }
        }
        body: BlockStatement {
          directives: Array []
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 26
              index: 26
              line: 1
            }
            start: Object {
              column: 20
              index: 20
              line: 1
            }
          }
          body: Array [
            ExpressionStatement {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 22
                  index: 22
                  line: 1
                }
                start: Object {
                  column: 20
                  index: 20
                  line: 1
                }
              }
              expression: ReferenceIdentifier {
                name: 'INVALID_PLACEHOLDER'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 21
                    index: 21
                    line: 1
                  }
                  start: Object {
                    column: 21
                    index: 21
                    line: 1
                  }
                }
              }
            }
            ExpressionStatement {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 23
                  index: 23
                  line: 1
                }
                start: Object {
                  column: 22
                  index: 22
                  line: 1
                }
              }
              expression: ReferenceIdentifier {
                name: 'INVALID_PLACEHOLDER'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 23
                    index: 23
                    line: 1
                  }
                  start: Object {
                    column: 22
                    index: 22
                    line: 1
                  }
                }
              }
            }
            BlockStatement {
              body: Array []
              directives: Array []
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 26
                  index: 26
                  line: 1
                }
                start: Object {
                  column: 24
                  index: 24
                  line: 1
                }
              }
            }
          ]
        }
      }
    }
  ]
}
```
