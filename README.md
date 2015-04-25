commonform-annotations
---------------------

[![NPM version](https://img.shields.io/npm/v/commonform-annotations.svg)](https://www.npmjs.com/package/commonform-annotations)

A dummy package for use as an npm peer dependency:

```json
{
  "peerDependencies": {
	"commonform-annotations": "1.x"
  }
}
```

All packages that peer-depend on this package expect as arguments (or return as outputs) Common Form annotation objects of a similar shape:

```json
{
  source: 'name of the module that produced the annotation',
  message: 'a message for users',
  url: 'an optional URL to link to', // or null
  object: 'a valid, non-child content object per commonform-validate',
  path: ['sequence', 'of', 'keys']
}
