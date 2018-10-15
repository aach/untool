# Snapshot report for `tests/exports.js`

The actual snapshot is saved in `exports.js.snap`.

Generated by [AVA](https://ava.li).

## basic package exports

> Snapshot 1

    {
      Mixin: 'function:1',
      initialize: 'function:0',
      internal: {
        getConfig: 'function:0',
      },
    }

> Snapshot 2

    {
      configure: 'function:2',
      createRenderer: 'function:0',
      createServer: 'function:0',
      internal: {
        uri: {
          addLeadingSlash: 'function:1',
          addTrailingSlash: 'function:1',
          resolve: 'function:0',
          resolveAbsolute: 'function:0',
          resolveAbsoluteFolder: 'function:0',
          resolveFolder: 'function:0',
          resolveRelative: 'function:0',
          resolveRelativeFolder: 'function:0',
          trimLeadingSlash: 'function:1',
          trimSlashes: 'function:1',
          trimTrailingSlash: 'function:1',
        },
      },
      runServer: 'function:0',
    }

> Snapshot 3

    {
      internal: {
        babelPlugin: 'function:1',
        template: 'function:1',
      },
    }

> Snapshot 4

    {
      build: 'function:0',
      clean: 'function:0',
      configure: 'function:2',
      getBuildConfig: 'function:0',
      internal: {
        RenderPlugin: 'function:2',
        Resolvable: 'function:1',
        StatsFilePlugin: 'function:2',
        StatsPlugin: 'function:1',
        configLoader: 'function:0',
        createAgentMiddleware: 'function:1',
        createStatsMiddleware: 'function:1',
        createWebpackMiddleware: 'function:2',
      },
    }

> Snapshot 5

    {
      configure: 'function:2',
      run: 'function:0',
    }