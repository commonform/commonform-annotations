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

All packages that peer-depend on this package expect as arguments (or return as outputs) Common Form annotation objects of a similar shape. For example:

```json
{
  "message": "The heading \"Indemnity\" is referenced, but not used.",
  "object": {"heading": "Indemnity"},
  "path": ["content", 0],
  "source": "commonform-lint",
  "url": null
}
```
