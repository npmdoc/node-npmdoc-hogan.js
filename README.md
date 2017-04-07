# api documentation for  [hogan.js (v3.0.2)](http://twitter.github.com/hogan.js/)  [![npm package](https://img.shields.io/npm/v/npmdoc-hogan.js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-hogan.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-hogan.js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-hogan.js)
#### A mustache compiler.

[![NPM](https://nodei.co/npm/hogan.js.png?downloads=true)](https://www.npmjs.com/package/hogan.js)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hogan.js/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-hogan.js_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hogan.js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-hogan.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-hogan.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Twitter Inc."
    },
    "bin": {
        "hulk": "./bin/hulk"
    },
    "bugs": {
        "url": "https://github.com/twitter/hogan.js/issues"
    },
    "dependencies": {
        "mkdirp": "0.3.0",
        "nopt": "1.0.10"
    },
    "description": "A mustache compiler.",
    "devDependencies": {
        "jsdom": "0.3.4",
        "rimraf": "2.0.1",
        "step": "0.0.5",
        "uglify-js": "2.x"
    },
    "directories": {},
    "dist": {
        "shasum": "4cd9e1abd4294146e7679e41d7898732b02c7bfd",
        "tarball": "https://registry.npmjs.org/hogan.js/-/hogan.js-3.0.2.tgz"
    },
    "gitHead": "c52d142643e764e3f82e8ad3f2d44a46b82d1640",
    "homepage": "http://twitter.github.com/hogan.js/",
    "keywords": [
        "mustache",
        "template"
    ],
    "licenses": [
        {
            "type": "Apache-2.0",
            "url": "http://www.apache.org/licenses/LICENSE-2.0"
        }
    ],
    "main": "./lib/hogan.js",
    "maintainers": [
        {
            "name": "fat",
            "email": "jacobthornton@gmail.com"
        },
        {
            "name": "sayrer",
            "email": "sayrer@gmail.com"
        }
    ],
    "name": "hogan.js",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/twitter/hogan.js.git"
    },
    "scripts": {},
    "version": "3.0.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module hogan.js](#apidoc.module.hogan.js)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>Template (codeObj, text, compiler, options)](#apidoc.element.hogan.js.Template)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>cacheKey (text, options)](#apidoc.element.hogan.js.cacheKey)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>compile (text, options)](#apidoc.element.hogan.js.compile)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>generate (tree, text, options)](#apidoc.element.hogan.js.generate)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>js.template (codeObj, text, compiler, options)](#apidoc.element.hogan.js.js.template)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>makePartials (codeObj)](#apidoc.element.hogan.js.makePartials)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>makeTemplate (codeObj, text, options)](#apidoc.element.hogan.js.makeTemplate)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>parse (tokens, text, options)](#apidoc.element.hogan.js.parse)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>scan (text, delimiters)](#apidoc.element.hogan.js.scan)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>stringify (codeObj, text, options)](#apidoc.element.hogan.js.stringify)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>template (codeObj, text, compiler, options)](#apidoc.element.hogan.js.template)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>walk (nodelist, context)](#apidoc.element.hogan.js.walk)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>wrapMain (code)](#apidoc.element.hogan.js.wrapMain)
1.  object <span class="apidocSignatureSpan">hogan.js.</span>cache
1.  object <span class="apidocSignatureSpan">hogan.js.</span>codegen
1.  object <span class="apidocSignatureSpan">hogan.js.</span>js.codegen
1.  object <span class="apidocSignatureSpan">hogan.js.</span>js.template.prototype
1.  object <span class="apidocSignatureSpan">hogan.js.</span>tags

#### [module hogan.js.codegen](#apidoc.module.hogan.js.codegen)
1.  [function <span class="apidocSignatureSpan">hogan.js.codegen.</span>_t (node, context)](#apidoc.element.hogan.js.codegen._t)
1.  [function <span class="apidocSignatureSpan">hogan.js.codegen.</span>_v (node, context)](#apidoc.element.hogan.js.codegen._v)

#### [module hogan.js.template](#apidoc.module.hogan.js.template)
1.  [function <span class="apidocSignatureSpan">hogan.js.</span>template (codeObj, text, compiler, options)](#apidoc.element.hogan.js.template.template)

#### [module hogan.js.template.prototype](#apidoc.module.hogan.js.template.prototype)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>b (s)](#apidoc.element.hogan.js.template.prototype.b)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>ct (text, cx, partials)](#apidoc.element.hogan.js.template.prototype.ct)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>d (key, ctx, partials, returnFound)](#apidoc.element.hogan.js.template.prototype.d)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>ep (symbol, partials)](#apidoc.element.hogan.js.template.prototype.ep)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>f (key, ctx, partials, returnFound)](#apidoc.element.hogan.js.template.prototype.f)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>fl ()](#apidoc.element.hogan.js.template.prototype.fl)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>ls (func, cx, partials, text, tags)](#apidoc.element.hogan.js.template.prototype.ls)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>ms (func, ctx, partials, inverted, start, end, tags)](#apidoc.element.hogan.js.template.prototype.ms)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>mv (func, ctx, partials)](#apidoc.element.hogan.js.template.prototype.mv)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>r (context, partials, indent)](#apidoc.element.hogan.js.template.prototype.r)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>render (context, partials, indent)](#apidoc.element.hogan.js.template.prototype.render)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>ri (context, partials, indent)](#apidoc.element.hogan.js.template.prototype.ri)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>rp (symbol, context, partials, indent)](#apidoc.element.hogan.js.template.prototype.rp)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>rs (context, partials, section)](#apidoc.element.hogan.js.template.prototype.rs)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>s (val, ctx, partials, inverted, start, end, tags)](#apidoc.element.hogan.js.template.prototype.s)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>sub (name, context, partials, indent)](#apidoc.element.hogan.js.template.prototype.sub)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>t (val)](#apidoc.element.hogan.js.template.prototype.t)
1.  [function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>v (str)](#apidoc.element.hogan.js.template.prototype.v)



# <a name="apidoc.module.hogan.js"></a>[module hogan.js](#apidoc.module.hogan.js)

#### <a name="apidoc.element.hogan.js.Template"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>Template (codeObj, text, compiler, options)](#apidoc.element.hogan.js.Template)
- description and source-code
```javascript
Template = function (codeObj, text, compiler, options) {
  codeObj = codeObj || {};
  this.r = codeObj.code || this.r;
  this.c = compiler;
  this.options = options || {};
  this.text = text || '';
  this.partials = codeObj.partials || {};
  this.subs = codeObj.subs || {};
  this.buf = '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.cacheKey"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>cacheKey (text, options)](#apidoc.element.hogan.js.cacheKey)
- description and source-code
```javascript
cacheKey = function (text, options) {
  return [text, !!options.asString, !!options.disableLambda, options.delimiters, !!options.modelGet].join('||');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.compile"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>compile (text, options)](#apidoc.element.hogan.js.compile)
- description and source-code
```javascript
compile = function (text, options) {
  options = options || {};
  var key = Hogan.cacheKey(text, options);
  var template = this.cache[key];

  if (template) {
    var partials = template.partials;
    for (var name in partials) {
      delete partials[name].instance;
    }
    return template;
  }

  template = this.generate(this.parse(this.scan(text, options.delimiters), text, options), text, options);
  return this.cache[key] = template;
}
```
- example usage
```shell
...
Hogan compiles templates to HoganTemplate objects, which have a render method.

'''js
var data = {
  screenName: "dhg",
};

var template = Hogan.compile("Follow @{{screenName}}.");
var output = template.render(data);

// prints "Follow @dhg."
console.log(output);
'''

## Features
...
```

#### <a name="apidoc.element.hogan.js.generate"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>generate (tree, text, options)](#apidoc.element.hogan.js.generate)
- description and source-code
```javascript
generate = function (tree, text, options) {
  serialNo = 0;
  var context = { code: '', subs: {}, partials: {} };
  Hogan.walk(tree, context);

  if (options.asString) {
    return this.stringify(context, text, options);
  }

  return this.makeTemplate(context, text, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.js.template"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>js.template (codeObj, text, compiler, options)](#apidoc.element.hogan.js.js.template)
- description and source-code
```javascript
js.template = function (codeObj, text, compiler, options) {
  codeObj = codeObj || {};
  this.r = codeObj.code || this.r;
  this.c = compiler;
  this.options = options || {};
  this.text = text || '';
  this.partials = codeObj.partials || {};
  this.subs = codeObj.subs || {};
  this.buf = '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.makePartials"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>makePartials (codeObj)](#apidoc.element.hogan.js.makePartials)
- description and source-code
```javascript
makePartials = function (codeObj) {
  var key, template = {subs: {}, partials: codeObj.partials, name: codeObj.name};
  for (key in template.partials) {
    template.partials[key] = this.makePartials(template.partials[key]);
  }
  for (key in codeObj.subs) {
    template.subs[key] = new Function('c', 'p', 't', 'i', codeObj.subs[key]);
  }
  return template;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.makeTemplate"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>makeTemplate (codeObj, text, options)](#apidoc.element.hogan.js.makeTemplate)
- description and source-code
```javascript
makeTemplate = function (codeObj, text, options) {
  var template = this.makePartials(codeObj);
  template.code = new Function('c', 'p', 'i', this.wrapMain(codeObj.code));
  return new this.template(template, text, this, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.parse"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>parse (tokens, text, options)](#apidoc.element.hogan.js.parse)
- description and source-code
```javascript
parse = function (tokens, text, options) {
  options = options || {};
  return buildTree(tokens, '', [], options.sectionTags || []);
}
```
- example usage
```shell
...

Hogan exposes scan and parse methods. These can be useful for
pre-processing templates on the server.

'''js
var text = "{{^check}}{{#i18n}}No{{/i18n}}{{/check}}";
text +=  "{{#check}}{{#i18n}}Yes{{/i18n}}{{/check}}";
var tree = Hogan.parse(Hogan.scan(text));

// outputs "# check"
console.log(tree[0].tag + " " + tree[0].name);

// outputs "Yes"
console.log(tree[1].nodes[0].nodes[0]);
'''
...
```

#### <a name="apidoc.element.hogan.js.scan"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>scan (text, delimiters)](#apidoc.element.hogan.js.scan)
- description and source-code
```javascript
function scan(text, delimiters) {
  var len = text.length,
      IN_TEXT = 0,
      IN_TAG_TYPE = 1,
      IN_TAG = 2,
      state = IN_TEXT,
      tagType = null,
      tag = null,
      buf = '',
      tokens = [],
      seenTag = false,
      i = 0,
      lineStart = 0,
      otag = '{{',
      ctag = '}}';

  function addBuf() {
    if (buf.length > 0) {
      tokens.push({tag: '_t', text: new String(buf)});
      buf = '';
    }
  }

  function lineIsWhitespace() {
    var isAllWhitespace = true;
    for (var j = lineStart; j < tokens.length; j++) {
      isAllWhitespace =
        (Hogan.tags[tokens[j].tag] < Hogan.tags['_v']) ||
        (tokens[j].tag == '_t' && tokens[j].text.match(rIsWhitespace) === null);
      if (!isAllWhitespace) {
        return false;
      }
    }

    return isAllWhitespace;
  }

  function filterLine(haveSeenTag, noNewLine) {
    addBuf();

    if (haveSeenTag && lineIsWhitespace()) {
      for (var j = lineStart, next; j < tokens.length; j++) {
        if (tokens[j].text) {
          if ((next = tokens[j+1]) && next.tag == '>') {
            // set indent to token value
            next.indent = tokens[j].text.toString()
          }
          tokens.splice(j, 1);
        }
      }
    } else if (!noNewLine) {
      tokens.push({tag:'\n'});
    }

    seenTag = false;
    lineStart = tokens.length;
  }

  function changeDelimiters(text, index) {
    var close = '=' + ctag,
        closeIndex = text.indexOf(close, index),
        delimiters = trim(
          text.substring(text.indexOf('=', index) + 1, closeIndex)
        ).split(' ');

    otag = delimiters[0];
    ctag = delimiters[delimiters.length - 1];

    return closeIndex + close.length - 1;
  }

  if (delimiters) {
    delimiters = delimiters.split(' ');
    otag = delimiters[0];
    ctag = delimiters[1];
  }

  for (i = 0; i < len; i++) {
    if (state == IN_TEXT) {
      if (tagChange(otag, text, i)) {
        --i;
        addBuf();
        state = IN_TAG_TYPE;
      } else {
        if (text.charAt(i) == '\n') {
          filterLine(seenTag);
        } else {
          buf += text.charAt(i);
        }
      }
    } else if (state == IN_TAG_TYPE) {
      i += otag.length - 1;
      tag = Hogan.tags[text.charAt(i + 1)];
      tagType = tag ? text.charAt(i + 1) : '_v';
      if (tagType == '=') {
        i = changeDelimiters(text, i);
        state = IN_TEXT;
      } else {
        if (tag) {
          i++;
        }
        state = IN_TAG;
      }
      seenTag = i;
    } else {
      if (tagChange(ctag, text, i)) {
        tokens.push({tag: tagType, n: trim(buf), otag: otag, ctag: ctag,
                     i: (tagType == '/') ? seenTag - otag.length : i + ctag.length});
        buf = '';
        i += ctag.length - 1;
        state = IN_TEXT;
        if (tagType == '{') {
          if (ctag == '}}') {
            i++;
          } else {
            cleanTripleStache(tokens[tokens.length - 1]);
          }
        }
      } else {
        buf += text.charAt(i);
      }
    }
  }

  filterLine(seenTag, true);

  return tokens;
}
```
- example usage
```shell
...

Hogan exposes scan and parse methods. These can be useful for
pre-processing templates on the server.

'''js
var text = "{{^check}}{{#i18n}}No{{/i18n}}{{/check}}";
text +=  "{{#check}}{{#i18n}}Yes{{/i18n}}{{/check}}";
var tree = Hogan.parse(Hogan.scan(text));

// outputs "# check"
console.log(tree[0].tag + " " + tree[0].name);

// outputs "Yes"
console.log(tree[1].nodes[0].nodes[0]);
'''
...
```

#### <a name="apidoc.element.hogan.js.stringify"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>stringify (codeObj, text, options)](#apidoc.element.hogan.js.stringify)
- description and source-code
```javascript
stringify = function (codeObj, text, options) {
  return "{code: function (c,p,i) { " + Hogan.wrapMain(codeObj.code) + " }," + stringifyPartials(codeObj) +  "}";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.template"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>template (codeObj, text, compiler, options)](#apidoc.element.hogan.js.template)
- description and source-code
```javascript
template = function (codeObj, text, compiler, options) {
  codeObj = codeObj || {};
  this.r = codeObj.code || this.r;
  this.c = compiler;
  this.options = options || {};
  this.text = text || '';
  this.partials = codeObj.partials || {};
  this.subs = codeObj.subs || {};
  this.buf = '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.walk"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>walk (nodelist, context)](#apidoc.element.hogan.js.walk)
- description and source-code
```javascript
walk = function (nodelist, context) {
  var func;
  for (var i = 0, l = nodelist.length; i < l; i++) {
    func = Hogan.codegen[nodelist[i].tag];
    func && func(nodelist[i], context);
  }
  return context;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.wrapMain"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>wrapMain (code)](#apidoc.element.hogan.js.wrapMain)
- description and source-code
```javascript
wrapMain = function (code) {
  return 'var t=this;t.b(i=i||"");' + code + 'return t.fl();';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hogan.js.codegen"></a>[module hogan.js.codegen](#apidoc.module.hogan.js.codegen)

#### <a name="apidoc.element.hogan.js.codegen._t"></a>[function <span class="apidocSignatureSpan">hogan.js.codegen.</span>_t (node, context)](#apidoc.element.hogan.js.codegen._t)
- description and source-code
```javascript
_t = function (node, context) {
  context.code += write('"' + esc(node.text) + '"');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.codegen._v"></a>[function <span class="apidocSignatureSpan">hogan.js.codegen.</span>_v (node, context)](#apidoc.element.hogan.js.codegen._v)
- description and source-code
```javascript
_v = function (node, context) {
  context.code += 't.b(t.v(t.' + chooseMethod(node.n) + '("' + esc(node.n) + '",c,p,0)));';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hogan.js.template"></a>[module hogan.js.template](#apidoc.module.hogan.js.template)

#### <a name="apidoc.element.hogan.js.template.template"></a>[function <span class="apidocSignatureSpan">hogan.js.</span>template (codeObj, text, compiler, options)](#apidoc.element.hogan.js.template.template)
- description and source-code
```javascript
template = function (codeObj, text, compiler, options) {
  codeObj = codeObj || {};
  this.r = codeObj.code || this.r;
  this.c = compiler;
  this.options = options || {};
  this.text = text || '';
  this.partials = codeObj.partials || {};
  this.subs = codeObj.subs || {};
  this.buf = '';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.hogan.js.template.prototype"></a>[module hogan.js.template.prototype](#apidoc.module.hogan.js.template.prototype)

#### <a name="apidoc.element.hogan.js.template.prototype.b"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>b (s)](#apidoc.element.hogan.js.template.prototype.b)
- description and source-code
```javascript
b = function (s) { this.buf += s; }
```
- example usage
```shell
...
},

// higher order templates
ls: function(func, cx, partials, text, tags) {
  var oldTags = this.options.delimiters;

  this.options.delimiters = tags;
  this.b(this.ct(coerceToString(func.call(cx, text)), cx, partials));
  this.options.delimiters = oldTags;

  return false;
},

// compile text
ct: function(text, cx, partials) {
...
```

#### <a name="apidoc.element.hogan.js.template.prototype.ct"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>ct (text, cx, partials)](#apidoc.element.hogan.js.template.prototype.ct)
- description and source-code
```javascript
ct = function (text, cx, partials) {
  if (this.options.disableLambda) {
    throw new Error('Lambda features disabled.');
  }
  return this.c.compile(text, this.options).render(cx, partials);
}
```
- example usage
```shell
...
},

// higher order templates
ls: function(func, cx, partials, text, tags) {
  var oldTags = this.options.delimiters;

  this.options.delimiters = tags;
  this.b(this.ct(coerceToString(func.call(cx, text)), cx, partials));
  this.options.delimiters = oldTags;

  return false;
},

// compile text
ct: function(text, cx, partials) {
...
```

#### <a name="apidoc.element.hogan.js.template.prototype.d"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>d (key, ctx, partials, returnFound)](#apidoc.element.hogan.js.template.prototype.d)
- description and source-code
```javascript
d = function (key, ctx, partials, returnFound) {
  var found,
      names = key.split('.'),
      val = this.f(names[0], ctx, partials, returnFound),
      doModelGet = this.options.modelGet,
      cx = null;

  if (key === '.' && isArray(ctx[ctx.length - 2])) {
    val = ctx[ctx.length - 1];
  } else {
    for (var i = 1; i < names.length; i++) {
      found = findInScope(names[i], val, doModelGet);
      if (found !== undefined) {
        cx = val;
        val = found;
      } else {
        val = '';
      }
    }
  }

  if (returnFound && !val) {
    return false;
  }

  if (!returnFound && typeof val == 'function') {
    ctx.push(cx);
    val = this.mv(val, ctx, partials);
    ctx.pop();
  }

  return val;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.template.prototype.ep"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>ep (symbol, partials)](#apidoc.element.hogan.js.template.prototype.ep)
- description and source-code
```javascript
ep = function (symbol, partials) {
  var partial = this.partials[symbol];

  // check to see that if we've instantiated this partial before
  var template = partials[partial.name];
  if (partial.instance && partial.base == template) {
    return partial.instance;
  }

  if (typeof template == 'string') {
    if (!this.c) {
      throw new Error("No compiler available.");
    }
    template = this.c.compile(template, this.options);
  }

  if (!template) {
    return null;
  }

  // We use this to check whether the partials dictionary has changed
  this.partials[symbol].base = template;

  if (partial.subs) {
    // Make sure we consider parent template now
    if (!partials.stackText) partials.stackText = {};
    for (key in partial.subs) {
      if (!partials.stackText[key]) {
        partials.stackText[key] = (this.activeSub !== undefined && partials.stackText[this.activeSub]) ? partials.stackText[this
.activeSub] : this.text;
      }
    }
    template = createSpecializedPartial(template, partial.subs, partial.partials,
      this.stackSubs, this.stackPartials, partials.stackText);
  }
  this.partials[symbol].instance = template;

  return template;
}
```
- example usage
```shell
...
  this.partials[symbol].instance = template;

  return template;
},

// tries to find a partial in the current scope and render it
rp: function(symbol, context, partials, indent) {
  var partial = this.ep(symbol, partials);
  if (!partial) {
    return '';
  }

  return partial.ri(context, partials, indent);
},
...
```

#### <a name="apidoc.element.hogan.js.template.prototype.f"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>f (key, ctx, partials, returnFound)](#apidoc.element.hogan.js.template.prototype.f)
- description and source-code
```javascript
f = function (key, ctx, partials, returnFound) {
  var val = false,
      v = null,
      found = false,
      doModelGet = this.options.modelGet;

  for (var i = ctx.length - 1; i >= 0; i--) {
    v = ctx[i];
    val = findInScope(key, v, doModelGet);
    if (val !== undefined) {
      found = true;
      break;
    }
  }

  if (!found) {
    return (returnFound) ? false : "";
  }

  if (!returnFound && typeof val == 'function') {
    val = this.mv(val, ctx, partials);
  }

  return val;
}
```
- example usage
```shell
...
return pass;
    },

    // find values with dotted names
    d: function(key, ctx, partials, returnFound) {
var found,
    names = key.split('.'),
    val = this.f(names[0], ctx, partials, returnFound),
    doModelGet = this.options.modelGet,
    cx = null;

if (key === '.' && isArray(ctx[ctx.length - 2])) {
  val = ctx[ctx.length - 1];
} else {
  for (var i = 1; i < names.length; i++) {
...
```

#### <a name="apidoc.element.hogan.js.template.prototype.fl"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>fl ()](#apidoc.element.hogan.js.template.prototype.fl)
- description and source-code
```javascript
fl = function () { var r = this.buf; this.buf = ''; return r; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.template.prototype.ls"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>ls (func, cx, partials, text, tags)](#apidoc.element.hogan.js.template.prototype.ls)
- description and source-code
```javascript
ls = function (func, cx, partials, text, tags) {
  var oldTags = this.options.delimiters;

  this.options.delimiters = tags;
  this.b(this.ct(coerceToString(func.call(cx, text)), cx, partials));
  this.options.delimiters = oldTags;

  return false;
}
```
- example usage
```shell
...
      result = func.call(cx);

  if (typeof result == 'function') {
    if (inverted) {
      return true;
    } else {
      textSource = (this.activeSub && this.subsText && this.subsText[this.activeSub]) ? this.subsText[this.activeSub] : this.text
;
      return this.ls(result, cx, partials, textSource.substring(start, end), tags);
    }
  }

  return result;
},

// method replace variable
...
```

#### <a name="apidoc.element.hogan.js.template.prototype.ms"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>ms (func, ctx, partials, inverted, start, end, tags)](#apidoc.element.hogan.js.template.prototype.ms)
- description and source-code
```javascript
ms = function (func, ctx, partials, inverted, start, end, tags) {
  var textSource,
      cx = ctx[ctx.length - 1],
      result = func.call(cx);

  if (typeof result == 'function') {
    if (inverted) {
      return true;
    } else {
      textSource = (this.activeSub && this.subsText && this.subsText[this.activeSub]) ? this.subsText[this.activeSub] : this.text
;
      return this.ls(result, cx, partials, textSource.substring(start, end), tags);
    }
  }

  return result;
}
```
- example usage
```shell
...
var pass;

if (isArray(val) && val.length === 0) {
  return false;
}

if (typeof val == 'function') {
  val = this.ms(val, ctx, partials, inverted, start, end, tags);
}

pass = !!val;

if (!inverted && pass && ctx) {
  ctx.push((typeof val == 'object') ? val : ctx[ctx.length - 1]);
}
...
```

#### <a name="apidoc.element.hogan.js.template.prototype.mv"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>mv (func, ctx, partials)](#apidoc.element.hogan.js.template.prototype.mv)
- description and source-code
```javascript
mv = function (func, ctx, partials) {
  var cx = ctx[ctx.length - 1];
  var result = func.call(cx);

  if (typeof result == 'function') {
    return this.ct(coerceToString(result.call(cx)), cx, partials);
  }

  return result;
}
```
- example usage
```shell
...

  if (returnFound && !val) {
    return false;
  }

  if (!returnFound && typeof val == 'function') {
    ctx.push(cx);
    val = this.mv(val, ctx, partials);
    ctx.pop();
  }

  return val;
},

// find values with normal names
...
```

#### <a name="apidoc.element.hogan.js.template.prototype.r"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>r (context, partials, indent)](#apidoc.element.hogan.js.template.prototype.r)
- description and source-code
```javascript
r = function (context, partials, indent) { return ''; }
```
- example usage
```shell
...

    render: function render(context, partials, indent) {
return this.ri([context], partials || {}, indent);
    },

    // render internal -- a hook for overrides that catches partials too
    ri: function (context, partials, indent) {
return this.r(context, partials, indent);
    },

    // ensurePartial
    ep: function(symbol, partials) {
var partial = this.partials[symbol];

// check to see that if we've instantiated this partial before
...
```

#### <a name="apidoc.element.hogan.js.template.prototype.render"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>render (context, partials, indent)](#apidoc.element.hogan.js.template.prototype.render)
- description and source-code
```javascript
function render(context, partials, indent) {
  return this.ri([context], partials || {}, indent);
}
```
- example usage
```shell
...

'''js
var data = {
  screenName: "dhg",
};

var template = Hogan.compile("Follow @{{screenName}}.");
var output = template.render(data);

// prints "Follow @dhg."
console.log(output);
'''

## Features
...
```

#### <a name="apidoc.element.hogan.js.template.prototype.ri"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>ri (context, partials, indent)](#apidoc.element.hogan.js.template.prototype.ri)
- description and source-code
```javascript
ri = function (context, partials, indent) {
  return this.r(context, partials, indent);
}
```
- example usage
```shell
...
// variable escaping
v: hoganEscape,

// triple stache
t: coerceToString,

render: function render(context, partials, indent) {
  return this.ri([context], partials || {}, indent);
},

// render internal -- a hook for overrides that catches partials too
ri: function (context, partials, indent) {
  return this.r(context, partials, indent);
},
...
```

#### <a name="apidoc.element.hogan.js.template.prototype.rp"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>rp (symbol, context, partials, indent)](#apidoc.element.hogan.js.template.prototype.rp)
- description and source-code
```javascript
rp = function (symbol, context, partials, indent) {
  var partial = this.ep(symbol, partials);
  if (!partial) {
    return '';
  }

  return partial.ri(context, partials, indent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.template.prototype.rs"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>rs (context, partials, section)](#apidoc.element.hogan.js.template.prototype.rs)
- description and source-code
```javascript
rs = function (context, partials, section) {
  var tail = context[context.length - 1];

  if (!isArray(tail)) {
    section(context, partials, this);
    return;
  }

  for (var i = 0; i < tail.length; i++) {
    context.push(tail[i]);
    section(context, partials, this);
    context.pop();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.template.prototype.s"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>s (val, ctx, partials, inverted, start, end, tags)](#apidoc.element.hogan.js.template.prototype.s)
- description and source-code
```javascript
s = function (val, ctx, partials, inverted, start, end, tags) {
  var pass;

  if (isArray(val) && val.length === 0) {
    return false;
  }

  if (typeof val == 'function') {
    val = this.ms(val, ctx, partials, inverted, start, end, tags);
  }

  pass = !!val;

  if (!inverted && pass && ctx) {
    ctx.push((typeof val == 'object') ? val : ctx[ctx.length - 1]);
  }

  return pass;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.template.prototype.sub"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>sub (name, context, partials, indent)](#apidoc.element.hogan.js.template.prototype.sub)
- description and source-code
```javascript
sub = function (name, context, partials, indent) {
  var f = this.subs[name];
  if (f) {
    this.activeSub = name;
    f(context, partials, this, indent);
    this.activeSub = false;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.template.prototype.t"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>t (val)](#apidoc.element.hogan.js.template.prototype.t)
- description and source-code
```javascript
function coerceToString(val) {
  return String((val === null || val === undefined) ? '' : val);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.hogan.js.template.prototype.v"></a>[function <span class="apidocSignatureSpan">hogan.js.template.prototype.</span>v (str)](#apidoc.element.hogan.js.template.prototype.v)
- description and source-code
```javascript
function hoganEscape(str) {
  str = coerceToString(str);
  return hChars.test(str) ?
    str
      .replace(rAmp, '&amp;')
      .replace(rLt, '&lt;')
      .replace(rGt, '&gt;')
      .replace(rApos, '&#39;')
      .replace(rQuot, '&quot;') :
    str;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
