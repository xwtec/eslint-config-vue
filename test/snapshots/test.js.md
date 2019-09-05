# Snapshot report for `test/test.js`

The actual snapshot is saved in `test.js.snap`.

Generated by [AVA](https://ava.li).

## vue.this-in-template.vue

> Snapshot 1

    {
      errorCount: 2,
      fixableErrorCount: 0,
      fixableWarningCount: 0,
      results: [
        {
          errorCount: 2,
          fixableErrorCount: 0,
          fixableWarningCount: 0,
          messages: [
            {
              column: 13,
              endColumn: 17,
              endLine: 4,
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
              line: 5,
              message: 'Unexpected usage of \'this\'.',
              nodeType: 'ThisExpression',
              ruleId: 'vue/this-in-template',
              severity: 2,
            },
          ],
          source: `<!-- https://eslint.vuejs.org/rules/this-in-template.html -->␊
          ␊
          <template>␊
            <a :href="this.url">␊
              {{ this.text }}␊
            </a>␊
          </template>␊
          `,
          warningCount: 0,
        },
      ],
      usedDeprecatedRules: [],
      warningCount: 0,
    }

## vue.require-component-is.vue

> Snapshot 1

    {
      errorCount: 0,
      fixableErrorCount: 0,
      fixableWarningCount: 0,
      results: [
        {
          errorCount: 0,
          fixableErrorCount: 0,
          fixableWarningCount: 0,
          messages: [],
          warningCount: 0,
        },
      ],
      usedDeprecatedRules: [],
      warningCount: 0,
    }

## vue.require-component-is.2.vue

> Snapshot 1

    {
      errorCount: 0,
      fixableErrorCount: 0,
      fixableWarningCount: 0,
      results: [
        {
          errorCount: 0,
          fixableErrorCount: 0,
          fixableWarningCount: 0,
          messages: [],
          warningCount: 0,
        },
      ],
      usedDeprecatedRules: [],
      warningCount: 0,
    }