# Snapshot report for `test/unit/lib/get-config.spec.mjs`

The actual snapshot is saved in `get-config.spec.mjs.snap`.

Generated by [AVA](https://avajs.dev).

## gets default config

> Snapshot 1

    {
      base: '/',
      project: {
        author: 'Pangolin.js',
        name: 'Pangolin.js',
        version: 'none',
      },
      ui: {
        color: 'orange',
        favicon: '/favicon.ico',
        format: 'json',
        lang: 'en',
      },
    }

## gets user config

> Snapshot 1

    {
      base: '/test/',
      project: {
        author: 'Test Author',
        name: 'test',
        version: '1.0.0',
      },
      ui: {
        color: 'teal',
        favicon: '/favicon.ico',
        format: 'json',
        lang: 'en',
      },
    }