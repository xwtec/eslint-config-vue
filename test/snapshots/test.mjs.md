# Snapshot report for `test/test.mjs`

The actual snapshot is saved in `test.mjs.snap`.

Generated by [AVA](https://avajs.dev).

## new-syntax.vue

> Snapshot 1

    [
      {
        errorCount: 0,
        fixableErrorCount: 0,
        fixableWarningCount: 0,
        messages: [],
        warningCount: 0,
      },
    ]

## vue.require-component-is.2.vue

> Snapshot 1

    [
      {
        errorCount: 0,
        fixableErrorCount: 0,
        fixableWarningCount: 0,
        messages: [],
        warningCount: 0,
      },
    ]

## vue.require-component-is.vue

> Snapshot 1

    [
      {
        errorCount: 0,
        fixableErrorCount: 0,
        fixableWarningCount: 1,
        messages: [
          {
            column: 22,
            endColumn: 38,
            endLine: 1,
            fix: {
              range: [
                21,
                27,
              ],
              text: '',
            },
            line: 1,
            message: 'Unexpected \'v-bind\' before \':\'.',
            nodeType: 'VAttribute',
            ruleId: 'vue/v-bind-style',
            severity: 1,
          },
        ],
        warningCount: 1,
      },
    ]

## vue.this-in-template.vue

> Snapshot 1

    [
      {
        errorCount: 2,
        fixableErrorCount: 2,
        fixableWarningCount: 0,
        messages: [
          {
            column: 13,
            endColumn: 17,
            endLine: 4,
            fix: {
              range: [
                86,
                94,
              ],
              text: 'url',
            },
            line: 4,
            message: 'Unexpected usage of \'this\'.',
            nodeType: 'ThisExpression',
            ruleId: 'vue/this-in-template',
            severity: 2,
          },
          {
            column: 8,
            endColumn: 12,
            endLine: 5,
            fix: {
              range: [
                104,
                113,
              ],
              text: 'text',
            },
            line: 5,
            message: 'Unexpected usage of \'this\'.',
            nodeType: 'ThisExpression',
            ruleId: 'vue/this-in-template',
            severity: 2,
          },
        ],
        warningCount: 0,
      },
    ]
