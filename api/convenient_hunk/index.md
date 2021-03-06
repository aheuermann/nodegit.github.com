---
layout: default
menu_item: api
title: ConvenientHunk
description: Version 0.4.0
menu_item: api
return_to:
  "API Documentation Index": /api/
sections:
  "#header": "#header"
  "#lines": "#lines"
  "#size": "#size"
---

## <a name="header"></a><span>ConvenientHunk#</span>header <span class="tags"><span class="sync">Sync</span></span>

```js
var string = convenientHunk.header();
```

Diff header string that represents the context of this hunk
of the diff. Something like `@@ -169,14 +167,12 @@ ...`

| Returns |  |
| --- | --- |
| String |  |

## <a name="lines"></a><span>ConvenientHunk#</span>lines <span class="tags"><span class="sync">Sync</span></span>

```js
var string = convenientHunk.lines();
```

The lines in this hunk

| Returns |  |
| --- | --- |
| String | array of strings |

## <a name="size"></a><span>ConvenientHunk#</span>size <span class="tags"><span class="sync">Sync</span></span>

```js
var number = convenientHunk.size();
```

Number of lines in this hunk

| Returns |  |
| --- | --- |
| Number |  |

