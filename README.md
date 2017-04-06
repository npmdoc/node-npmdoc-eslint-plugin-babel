# api documentation for  [eslint-plugin-babel (v4.1.1)](https://github.com/babel/eslint-plugin-babel#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-eslint-plugin-babel.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-eslint-plugin-babel) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-eslint-plugin-babel.svg)](https://travis-ci.org/npmdoc/node-npmdoc-eslint-plugin-babel)
#### an eslint rule plugin companion to babel-eslint

[![NPM](https://nodei.co/npm/eslint-plugin-babel.png?downloads=true)](https://www.npmjs.com/package/eslint-plugin-babel)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-babel/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-eslint-plugin-babel_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-babel/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-eslint-plugin-babel/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-eslint-plugin-babel/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jason Quense @monasticpanic"
    },
    "bugs": {
        "url": "https://github.com/babel/eslint-plugin-babel/issues"
    },
    "dependencies": {},
    "description": "an eslint rule plugin companion to babel-eslint",
    "devDependencies": {
        "babel-eslint": "^7.1.0",
        "eslint": "^3.0.0",
        "lodash.clonedeep": "^4.5.0",
        "mocha": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ef285c87039b67beb3bbd227f5b0eed4fb376b87",
        "tarball": "https://registry.npmjs.org/eslint-plugin-babel/-/eslint-plugin-babel-4.1.1.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "14b2765794c7c1fe0577304b46548ca620d7969f",
    "homepage": "https://github.com/babel/eslint-plugin-babel#readme",
    "keywords": [
        "babel",
        "eslint",
        "eslintplugin",
        "eslint-plugin",
        "babel-eslint"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "hzoo",
            "email": "hi@henryzoo.com"
        },
        {
            "name": "loganfsmyth",
            "email": "loganfsmyth@gmail.com"
        },
        {
            "name": "monastic.panic",
            "email": "monastic.panic@gmail.com"
        }
    ],
    "name": "eslint-plugin-babel",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": ">=3.0.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/babel/eslint-plugin-babel.git"
    },
    "scripts": {
        "test": "mocha ./tests/rules/*.js"
    },
    "version": "4.1.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module eslint-plugin-babel](#apidoc.module.eslint-plugin-babel)
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>ast_utils
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>rules
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>rules.array-bracket-spacing
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>rules.arrow-parens
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>rules.flow-object-type
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>rules.func-params-comma-dangle
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>rules.generator-star-spacing
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>rules.no-await-in-loop
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>rules.no-invalid-this
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>rules.object-shorthand
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>rules.semi
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.</span>rulesConfig

#### [module eslint-plugin-babel.ast_utils](#apidoc.module.eslint-plugin-babel.ast_utils)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getDirectivePrologue (node)](#apidoc.element.eslint-plugin-babel.ast_utils.getDirectivePrologue)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getLabel (node)](#apidoc.element.eslint-plugin-babel.ast_utils.getLabel)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getModifyingReferences (references)](#apidoc.element.eslint-plugin-babel.ast_utils.getModifyingReferences)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getPrecedence (node)](#apidoc.element.eslint-plugin-babel.ast_utils.getPrecedence)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getStaticPropertyName (node)](#apidoc.element.eslint-plugin-babel.ast_utils.getStaticPropertyName)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getUpperFunction (node)](#apidoc.element.eslint-plugin-babel.ast_utils.getUpperFunction)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getVariableByName (initScope, name)](#apidoc.element.eslint-plugin-babel.ast_utils.getVariableByName)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isArrayFromMethod (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isArrayFromMethod)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isBreakableStatement (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isBreakableStatement)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isCallee (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isCallee)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isDecimalInteger (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isDecimalInteger)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isDefaultThisBinding (node, sourceCode)](#apidoc.element.eslint-plugin-babel.ast_utils.isDefaultThisBinding)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isDirectiveComment (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isDirectiveComment)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isES5Constructor (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isES5Constructor)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isFunction (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isFunction)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isLoop (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isLoop)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isNullOrUndefined (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isNullOrUndefined)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isParenthesised (sourceCode, node)](#apidoc.element.eslint-plugin-babel.ast_utils.isParenthesised)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isStringLiteral (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isStringLiteral)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isSurroundedBy (val, character)](#apidoc.element.eslint-plugin-babel.ast_utils.isSurroundedBy)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isTokenOnSameLine (left, right)](#apidoc.element.eslint-plugin-babel.ast_utils.isTokenOnSameLine)

#### [module eslint-plugin-babel.rules](#apidoc.module.eslint-plugin-babel.rules)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>new-cap (context)](#apidoc.element.eslint-plugin-babel.rules.new-cap)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>object-curly-spacing (context)](#apidoc.element.eslint-plugin-babel.rules.object-curly-spacing)
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>array-bracket-spacing
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>arrow-parens
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>flow-object-type
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>func-params-comma-dangle
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>generator-star-spacing
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>no-await-in-loop
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>no-invalid-this
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>object-shorthand
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>semi

#### [module eslint-plugin-babel.rules.array-bracket-spacing](#apidoc.module.eslint-plugin-babel.rules.array-bracket-spacing)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.array-bracket-spacing.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.array-bracket-spacing.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.array-bracket-spacing.</span>meta

#### [module eslint-plugin-babel.rules.arrow-parens](#apidoc.module.eslint-plugin-babel.rules.arrow-parens)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.arrow-parens.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.arrow-parens.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.arrow-parens.</span>meta

#### [module eslint-plugin-babel.rules.flow-object-type](#apidoc.module.eslint-plugin-babel.rules.flow-object-type)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.flow-object-type.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.flow-object-type.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.flow-object-type.</span>meta

#### [module eslint-plugin-babel.rules.func-params-comma-dangle](#apidoc.module.eslint-plugin-babel.rules.func-params-comma-dangle)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.func-params-comma-dangle.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.func-params-comma-dangle.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.func-params-comma-dangle.</span>meta

#### [module eslint-plugin-babel.rules.generator-star-spacing](#apidoc.module.eslint-plugin-babel.rules.generator-star-spacing)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.generator-star-spacing.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.generator-star-spacing.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.generator-star-spacing.</span>meta

#### [module eslint-plugin-babel.rules.no-await-in-loop](#apidoc.module.eslint-plugin-babel.rules.no-await-in-loop)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.no-await-in-loop.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.no-await-in-loop.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.no-await-in-loop.</span>meta

#### [module eslint-plugin-babel.rules.no-invalid-this](#apidoc.module.eslint-plugin-babel.rules.no-invalid-this)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.no-invalid-this.</span>create (context)](#apidoc.element.eslint-plugin-babel.rules.no-invalid-this.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.no-invalid-this.</span>meta

#### [module eslint-plugin-babel.rules.object-shorthand](#apidoc.module.eslint-plugin-babel.rules.object-shorthand)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.object-shorthand.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.object-shorthand.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.object-shorthand.</span>meta

#### [module eslint-plugin-babel.rules.semi](#apidoc.module.eslint-plugin-babel.rules.semi)
1.  [function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.semi.</span>create (context)](#apidoc.element.eslint-plugin-babel.rules.semi.create)
1.  object <span class="apidocSignatureSpan">eslint-plugin-babel.rules.semi.</span>meta



# <a name="apidoc.module.eslint-plugin-babel"></a>[module eslint-plugin-babel](#apidoc.module.eslint-plugin-babel)



# <a name="apidoc.module.eslint-plugin-babel.ast_utils"></a>[module eslint-plugin-babel.ast_utils](#apidoc.module.eslint-plugin-babel.ast_utils)

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.getDirectivePrologue"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getDirectivePrologue (node)](#apidoc.element.eslint-plugin-babel.ast_utils.getDirectivePrologue)
- description and source-code
```javascript
getDirectivePrologue(node) {
    const directives = [];

    // Directive prologues only occur at the top of files or functions.
    if (
        node.type === "Program" ||
        node.type === "FunctionDeclaration" ||
        node.type === "FunctionExpression" ||

        // Do not check arrow functions with implicit return.
        // '() => "use strict";' returns the string '"use strict"'.
        (node.type === "ArrowFunctionExpression" && node.body.type === "BlockStatement")
    ) {
        const statements = node.type === "Program" ? node.body : node.body.body;

        for (const statement of statements) {
            if (
                statement.type === "ExpressionStatement" &&
                statement.expression.type === "Literal"
            ) {
                directives.push(statement);
            } else {
                break;
            }
        }
    }

    return directives;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.getLabel"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getLabel (node)](#apidoc.element.eslint-plugin-babel.ast_utils.getLabel)
- description and source-code
```javascript
getLabel(node) {
    if (node.parent.type === "LabeledStatement") {
        return node.parent.label.name;
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.getModifyingReferences"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getModifyingReferences (references)](#apidoc.element.eslint-plugin-babel.ast_utils.getModifyingReferences)
- description and source-code
```javascript
getModifyingReferences(references) {
    return references.filter(isModifyingReference);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.getPrecedence"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getPrecedence (node)](#apidoc.element.eslint-plugin-babel.ast_utils.getPrecedence)
- description and source-code
```javascript
getPrecedence(node) {
    switch (node.type) {
        case "SequenceExpression":
            return 0;

        case "AssignmentExpression":
        case "ArrowFunctionExpression":
        case "YieldExpression":
            return 1;

        case "ConditionalExpression":
            return 3;

        case "LogicalExpression":
            switch (node.operator) {
                case "||":
                    return 4;
                case "&&":
                    return 5;

                // no default
            }

<span class="apidocCodeCommentSpan">            /* falls through */
</span>
        case "BinaryExpression":

            switch (node.operator) {
                case "|":
                    return 6;
                case "^":
                    return 7;
                case "&":
                    return 8;
                case "==":
                case "!=":
                case "===":
                case "!==":
                    return 9;
                case "<":
                case "<=":
                case ">":
                case ">=":
                case "in":
                case "instanceof":
                    return 10;
                case "<<":
                case ">>":
                case ">>>":
                    return 11;
                case "+":
                case "-":
                    return 12;
                case "*":
                case "/":
                case "%":
                    return 13;

                // no default
            }

            /* falls through */

        case "UnaryExpression":
        case "AwaitExpression":
            return 14;

        case "UpdateExpression":
            return 15;

        case "CallExpression":

            // IIFE is allowed to have parens in any position (#655)
            if (node.callee.type === "FunctionExpression") {
                return -1;
            }
            return 16;

        case "NewExpression":
            return 17;

        // no default
    }
    return 18;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.getStaticPropertyName"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getStaticPropertyName (node)](#apidoc.element.eslint-plugin-babel.ast_utils.getStaticPropertyName)
- description and source-code
```javascript
getStaticPropertyName(node) {
    let prop;

    switch (node && node.type) {
        case "Property":
        case "MethodDefinition":
            prop = node.key;
            break;

        case "MemberExpression":
            prop = node.property;
            break;

        // no default
    }

    switch (prop && prop.type) {
        case "Literal":
            return String(prop.value);

        case "TemplateLiteral":
            if (prop.expressions.length === 0 && prop.quasis.length === 1) {
                return prop.quasis[0].value.cooked;
            }
            break;

        case "Identifier":
            if (!node.computed) {
                return prop.name;
            }
            break;

        // no default
    }

    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.getUpperFunction"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getUpperFunction (node)](#apidoc.element.eslint-plugin-babel.ast_utils.getUpperFunction)
- description and source-code
```javascript
function getUpperFunction(node) {
    while (node) {
        if (anyFunctionPattern.test(node.type)) {
            return node;
        }
        node = node.parent;
    }
    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.getVariableByName"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>getVariableByName (initScope, name)](#apidoc.element.eslint-plugin-babel.ast_utils.getVariableByName)
- description and source-code
```javascript
getVariableByName(initScope, name) {
    let scope = initScope;

    while (scope) {
        const variable = scope.set.get(name);

        if (variable) {
            return variable;
        }

        scope = scope.upper;
    }

    return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isArrayFromMethod"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isArrayFromMethod (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isArrayFromMethod)
- description and source-code
```javascript
function isArrayFromMethod(node) {
    return (
        node.type === "MemberExpression" &&
        node.object.type === "Identifier" &&
        arrayOrTypedArrayPattern.test(node.object.name) &&
        node.property.type === "Identifier" &&
        node.property.name === "from" &&
        node.computed === false
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isBreakableStatement"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isBreakableStatement (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isBreakableStatement)
- description and source-code
```javascript
isBreakableStatement(node) {
    return breakableTypePattern.test(node.type);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isCallee"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isCallee (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isCallee)
- description and source-code
```javascript
function isCallee(node) {
    return node.parent.type === "CallExpression" && node.parent.callee === node;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isDecimalInteger"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isDecimalInteger (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isDecimalInteger)
- description and source-code
```javascript
isDecimalInteger(node) {
    return node.type === "Literal" && typeof node.value === "number" && /^(0|[1-9]\d*)$/.test(node.raw);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isDefaultThisBinding"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isDefaultThisBinding (node, sourceCode)](#apidoc.element.eslint-plugin-babel.ast_utils.isDefaultThisBinding)
- description and source-code
```javascript
isDefaultThisBinding(node, sourceCode) {
    if (isES5Constructor(node) || hasJSDocThisTag(node, sourceCode)) {
        return false;
    }
    const isAnonymous = node.id === null;

    while (node) {
        const parent = node.parent;

        switch (parent.type) {

<span class="apidocCodeCommentSpan">            /*
             * Looks up the destination.
             * e.g., obj.foo = nativeFoo || function foo() { ... };
             */
</span>            case "LogicalExpression":
            case "ConditionalExpression":
                node = parent;
                break;

            // If the upper function is IIFE, checks the destination of the return value.
            // e.g.
            //   obj.foo = (function() {
            //     // setup...
            //     return function foo() { ... };
            //   })();
            case "ReturnStatement": {
                const func = getUpperFunction(parent);

                if (func === null || !isCallee(func)) {
                    return true;
                }
                node = func.parent;
                break;
            }

            // e.g.
            //   var obj = { foo() { ... } };
            //   var obj = { foo: function() { ... } };
            //   class A { constructor() { ... } }
            //   class A { foo() { ... } }
            //   class A { get foo() { ... } }
            //   class A { set foo() { ... } }
            //   class A { static foo() { ... } }
            case "Property":
            case "MethodDefinition":
                return parent.value !== node;

            // e.g.
            //   obj.foo = function foo() { ... };
            //   Foo = function() { ... };
            //   [obj.foo = function foo() { ... }] = a;
            //   [Foo = function() { ... }] = a;
            case "AssignmentExpression":
            case "AssignmentPattern":
                if (parent.right === node) {
                    if (parent.left.type === "MemberExpression") {
                        return false;
                    }
                    if (isAnonymous &&
                        parent.left.type === "Identifier" &&
                        startsWithUpperCase(parent.left.name)
                    ) {
                        return false;
                    }
                }
                return true;

            // e.g.
            //   var Foo = function() { ... };
            case "VariableDeclarator":
                return !(
                    isAnonymous &&
                    parent.init === node &&
                    parent.id.type === "Identifier" &&
                    startsWithUpperCase(parent.id.name)
                );

            // e.g.
            //   var foo = function foo() { ... }.bind(obj);
            //   (function foo() { ... }).call(obj);
            //   (function foo() { ... }).apply(obj, []);
            case "MemberExpression":
                return (
                    parent.object !== node ||
                    parent.property.type !== "Identifier" ||
                    !bindOrCallOrApplyPattern.test(parent.property.name) ||
                    !isCallee(parent) ||
                    parent.parent.arguments.length === 0 ||
                    isNullOrUndefined(parent.parent.arguments[0])
                );

            // e.g.
            //   Reflect.apply(function() {}, obj, []);
            //   Array.from([], function() {}, obj);
            //   list.forEach(function() {}, obj);
            case "CallExpression":
                if (isReflectApply(parent.callee)) {
                    return (
                        parent.arguments.length !== 3 ||
                        parent.arguments[0] !== node ||
                        isNullOrUndefined(parent.arguments[1])
                    );
                }
                if (isArrayFromMethod(parent.callee)) {
                    return (
                        parent.arguments.length !== 3 ||
                        parent.arguments[1] !== node ||
                        isNullOrUndefined(parent.arguments[2])
                    );
                } ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isDirectiveComment"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isDirectiveComment (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isDirectiveComment)
- description and source-code
```javascript
isDirectiveComment(node) {
    const comment = node.value.trim();

    return (
        node.type === "Line" && comment.indexOf("eslint-") === 0 ||
        node.type === "Block" && (
            comment.indexOf("global ") === 0 ||
            comment.indexOf("eslint ") === 0 ||
            comment.indexOf("eslint-") === 0
        )
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isES5Constructor"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isES5Constructor (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isES5Constructor)
- description and source-code
```javascript
function isES5Constructor(node) {
    return (node.id && startsWithUpperCase(node.id.name));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isFunction"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isFunction (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isFunction)
- description and source-code
```javascript
isFunction(node) {
    return Boolean(node && anyFunctionPattern.test(node.type));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isLoop"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isLoop (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isLoop)
- description and source-code
```javascript
isLoop(node) {
    return Boolean(node && anyLoopPattern.test(node.type));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isNullOrUndefined"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isNullOrUndefined (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isNullOrUndefined)
- description and source-code
```javascript
function isNullOrUndefined(node) {
    return (
        (node.type === "Literal" && node.value === null) ||
        (node.type === "Identifier" && node.name === "undefined") ||
        (node.type === "UnaryExpression" && node.operator === "void")
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isParenthesised"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isParenthesised (sourceCode, node)](#apidoc.element.eslint-plugin-babel.ast_utils.isParenthesised)
- description and source-code
```javascript
function isParenthesised(sourceCode, node) {
    const previousToken = sourceCode.getTokenBefore(node),
        nextToken = sourceCode.getTokenAfter(node);

    return Boolean(previousToken && nextToken) &&
        previousToken.value === "(" && previousToken.range[1] <= node.range[0] &&
        nextToken.value === ")" && nextToken.range[0] >= node.range[1];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isStringLiteral"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isStringLiteral (node)](#apidoc.element.eslint-plugin-babel.ast_utils.isStringLiteral)
- description and source-code
```javascript
isStringLiteral(node) {
    return (
        (node.type === "Literal" && typeof node.value === "string") ||
        node.type === "TemplateLiteral"
    );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isSurroundedBy"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isSurroundedBy (val, character)](#apidoc.element.eslint-plugin-babel.ast_utils.isSurroundedBy)
- description and source-code
```javascript
isSurroundedBy(val, character) {
    return val[0] === character && val[val.length - 1] === character;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.ast_utils.isTokenOnSameLine"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.ast_utils.</span>isTokenOnSameLine (left, right)](#apidoc.element.eslint-plugin-babel.ast_utils.isTokenOnSameLine)
- description and source-code
```javascript
isTokenOnSameLine(left, right) {
    return left.loc.end.line === right.loc.start.line;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-babel.rules"></a>[module eslint-plugin-babel.rules](#apidoc.module.eslint-plugin-babel.rules)

#### <a name="apidoc.element.eslint-plugin-babel.rules.new-cap"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>new-cap (context)](#apidoc.element.eslint-plugin-babel.rules.new-cap)
- description and source-code
```javascript
new-cap = function (context) {

    var config = context.options[0] || {};
    var NEW_IS_CAP = config.newIsCap !== false;
    var CAP_IS_NEW = config.capIsNew !== false;

    var newIsCapExceptions = checkArray(config, "newIsCapExceptions", []).reduce(invert, {});

    var capIsNewExceptions = calculateCapIsNewExceptions(config);

    var listeners = {};

    //--------------------------------------------------------------------------
    // Helpers
    //--------------------------------------------------------------------------

<span class="apidocCodeCommentSpan">    /**
     * Get exact callee name from expression
     * @param {ASTNode} node CallExpression or NewExpression node
     * @returns {string} name
     */
</span>    function extractNameFromExpression(node) {

        var name = "",
            property;

        if (node.callee.type === "MemberExpression") {
            property = node.callee.property;

            if (property.type === "Literal" && (typeof property.value === "string")) {
                name = property.value;
            } else if (property.type === "Identifier" && !node.callee.computed) {
                name = property.name;
            }
        } else {
            name = node.callee.name;
        }
        return name;
    }

    /**
     * Returns the capitalization state of the string -
     * Whether the first character is uppercase, lowercase, or non-alphabetic
     * @param {string} str String
     * @returns {string} capitalization state: "non-alpha", "lower", or "upper"
     */
    function getCap(str) {
        var firstChar = str.charAt(0);

        var firstCharLower = firstChar.toLowerCase();
        var firstCharUpper = firstChar.toUpperCase();

        if (firstCharLower === firstCharUpper) {
            // char has no uppercase variant, so it's non-alphabetic
            return "non-alpha";
        } else if (firstChar === firstCharLower) {
            return "lower";
        } else {
            return "upper";
        }
    }

    /**
     * Returns whether a node is under a decorator or not.
     * @param  {ASTNode}  node CallExpression node
     * @returns {Boolean} Returns true if the node is under a decorator.
     */
    function isDecorator(node) {
        return node.parent.type === "Decorator";
    }

    /**
     * Check if capitalization is allowed for a CallExpression
     * @param {Object} allowedMap Object mapping calleeName to a Boolean
     * @param {ASTNode} node CallExpression node
     * @param {string} calleeName Capitalized callee name from a CallExpression
     * @returns {Boolean} Returns true if the callee may be capitalized
     */
    function isCapAllowed(allowedMap, node, calleeName) {
        if (allowedMap[calleeName] || allowedMap[context.getSource(node.callee)]) {
            return true;
        }
        if (calleeName === "UTC" && node.callee.type === "MemberExpression") {
            // allow if callee is Date.UTC
            return node.callee.object.type === "Identifier" &&
                node.callee.object.name === "Date";
        }
        return false;
    }

    /**
     * Reports the given message for the given node. The location will be the start of the property or the callee.
     * @param {ASTNode} node CallExpression or NewExpression node.
     * @param {string} message The message to report.
     * @returns {void}
     */
    function report(node, message) {
        var callee = node.callee;

        if (callee.type === "MemberExpression") {
            callee = callee.property;
        }

        context.report(node, callee.loc.start, message);
    }

    //--------------------------------------------------------------------------
    // Public
    //--------------------------------------------------------------------------

    if (NEW_IS_CAP) {
        listeners.NewExpression = function(node) {

            var constructorName = extractNameFromExpression(node);
            if (constructorName) {
                var capitalization = getCap(constructorName);
                var isAllowed = capitalization !== "lower" || isCapAllowed(newIsCapExceptions, node, constructorNam ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.eslint-plugin-babel.rules.object-curly-spacing"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.</span>object-curly-spacing (context)](#apidoc.element.eslint-plugin-babel.rules.object-curly-spacing)
- description and source-code
```javascript
object-curly-spacing = function (context) {
    var spaced = context.options[0] === "always",
        sourceCode = context.getSourceCode();

<span class="apidocCodeCommentSpan">    /**
     * Determines whether an option is set, relative to the spacing option.
     * If spaced is "always", then check whether option is set to false.
     * If spaced is "never", then check whether option is set to true.
     * @param {Object} option - The option to exclude.
     * @returns {boolean} Whether or not the property is excluded.
     */
</span>    function isOptionSet(option) {
        return context.options[1] != null ? context.options[1][option] === !spaced : false;
    }

    var options = {
        spaced: spaced,
        arraysInObjectsException: isOptionSet("arraysInObjects"),
        objectsInObjectsException: isOptionSet("objectsInObjects")
    };

    //--------------------------------------------------------------------------
    // Helpers
    //--------------------------------------------------------------------------

    /**
     * Determines whether two adjacent tokens are have whitespace between them.
     * @param {Object} left - The left token object.
     * @param {Object} right - The right token object.
     * @returns {boolean} Whether or not there is space between the tokens.
     */
    function isSpaced(left, right) {
        return sourceCode.isSpaceBetweenTokens(left, right);
    }

    /**
     * Determines whether two adjacent tokens are on the same line.
     * @param {Object} left - The left token object.
     * @param {Object} right - The right token object.
     * @returns {boolean} Whether or not the tokens are on the same line.
     */
    function isSameLine(left, right) {
        return left.loc.start.line === right.loc.start.line;
    }

    /**
    * Reports that there shouldn't be a space after the first token
    * @param {ASTNode} node - The node to report in the event of an error.
    * @param {Token} token - The token to use for the report.
    * @returns {void}
    */
    function reportNoBeginningSpace(node, token) {
        context.report({
            node: node,
            loc: token.loc.end,
            message: "There should be no space after '" + token.value + "'",
            fix: function(fixer) {
                var nextToken = sourceCode.getTokenAfter(token);
                return fixer.removeRange([token.range[1], nextToken.range[0]]);
            }
        });
    }

    /**
    * Reports that there shouldn't be a space before the last token
    * @param {ASTNode} node - The node to report in the event of an error.
    * @param {Token} token - The token to use for the report.
    * @returns {void}
    */
    function reportNoEndingSpace(node, token) {
        context.report({
            node: node,
            loc: token.loc.start,
            message: "There should be no space before '" + token.value + "'",
            fix: function(fixer) {
                var previousToken = sourceCode.getTokenBefore(token);
                return fixer.removeRange([previousToken.range[1], token.range[0]]);
            }
        });
    }

    /**
    * Reports that there should be a space after the first token
    * @param {ASTNode} node - The node to report in the event of an error.
    * @param {Token} token - The token to use for the report.
    * @returns {void}
    */
    function reportRequiredBeginningSpace(node, token) {
        context.report({
            node: node,
            loc: token.loc.end,
            message: "A space is required after '" + token.value + "'",
            fix: function(fixer) {
                return fixer.insertTextAfter(token, " ");
            }
        });
    }

    /**
    * Reports that there should be a space before the last token
    * @param {ASTNode} node - The node to report in the event of an error.
    * @param {Token} token - The token to use for the report.
    * @returns {void}
    */
    function reportRequiredEndingSpace(node, token) {
        context.report({
            node: node,
            loc: token.loc.start,
            message: "A space is required before '" + token.value + "'", ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-babel.rules.array-bracket-spacing"></a>[module eslint-plugin-babel.rules.array-bracket-spacing](#apidoc.module.eslint-plugin-babel.rules.array-bracket-spacing)

#### <a name="apidoc.element.eslint-plugin-babel.rules.array-bracket-spacing.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.array-bracket-spacing.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.array-bracket-spacing.create)
- description and source-code
```javascript
create = function () {
    return {
        Program: function() {
            if (isWarnedForDeprecation || /\=-(f|-format)=/.test(process.argv.join('='))) {
                return;
            }

<span class="apidocCodeCommentSpan">            /* eslint-disable no-console */
</span>            console.log('The babel/array-bracket-spacing rule is deprecated. Please ' +
                        'use the built in array-bracket-spacing rule instead.');
            /* eslint-enable no-console */
            isWarnedForDeprecation = true;
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-babel.rules.arrow-parens"></a>[module eslint-plugin-babel.rules.arrow-parens](#apidoc.module.eslint-plugin-babel.rules.arrow-parens)

#### <a name="apidoc.element.eslint-plugin-babel.rules.arrow-parens.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.arrow-parens.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.arrow-parens.create)
- description and source-code
```javascript
create = function () {
    return {
        Program: function() {
            if (isWarnedForDeprecation || /\=-(f|-format)=/.test(process.argv.join('='))) {
                return;
            }

<span class="apidocCodeCommentSpan">            /* eslint-disable no-console */
</span>            console.log('The babel/arrow-parens rule is deprecated. Please ' +
                        'use the built in arrow-parens rule instead.');
            /* eslint-enable no-console */
            isWarnedForDeprecation = true;
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-babel.rules.flow-object-type"></a>[module eslint-plugin-babel.rules.flow-object-type](#apidoc.module.eslint-plugin-babel.rules.flow-object-type)

#### <a name="apidoc.element.eslint-plugin-babel.rules.flow-object-type.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.flow-object-type.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.flow-object-type.create)
- description and source-code
```javascript
create = function () {
    return {
        Program: function() {
            if (isWarnedForDeprecation || /\=-(f|-format)=/.test(process.argv.join('='))) {
                return;
            }

<span class="apidocCodeCommentSpan">            /* eslint-disable no-console */
</span>            console.log('The babel/flow-object-type rule is deprecated. Please ' +
                        'use the flowtype/object-type-delimiter rule instead.\n' +
                        'Check out https://github.com/gajus/eslint-plugin-flowtype#eslint-plugin-flowtype-rules-object-type-delimiter
');
            /* eslint-enable no-console */
            isWarnedForDeprecation = true;
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-babel.rules.func-params-comma-dangle"></a>[module eslint-plugin-babel.rules.func-params-comma-dangle](#apidoc.module.eslint-plugin-babel.rules.func-params-comma-dangle)

#### <a name="apidoc.element.eslint-plugin-babel.rules.func-params-comma-dangle.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.func-params-comma-dangle.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.func-params-comma-dangle.create)
- description and source-code
```javascript
create = function () {
    return {
        Program: function() {
            if (isWarnedForDeprecation || /\=-(f|-format)=/.test(process.argv.join('='))) {
                return;
            }

<span class="apidocCodeCommentSpan">            /* eslint-disable no-console */
</span>            console.log('The babel/func-params-comma-dangle rule is deprecated. Please ' +
                        'use the built in comma-dangle rule instead.');
            /* eslint-enable no-console */
            isWarnedForDeprecation = true;
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-babel.rules.generator-star-spacing"></a>[module eslint-plugin-babel.rules.generator-star-spacing](#apidoc.module.eslint-plugin-babel.rules.generator-star-spacing)

#### <a name="apidoc.element.eslint-plugin-babel.rules.generator-star-spacing.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.generator-star-spacing.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.generator-star-spacing.create)
- description and source-code
```javascript
create = function () {
    return {
        Program: function() {
            if (isWarnedForDeprecation || /\=-(f|-format)=/.test(process.argv.join('='))) {
                return;
            }

<span class="apidocCodeCommentSpan">            /* eslint-disable no-console */
</span>            console.log('The babel/generator-star-spacing rule is deprecated. Please ' +
                        'use the built in generator-star-spacing rule instead.');
            /* eslint-enable no-console */
            isWarnedForDeprecation = true;
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-babel.rules.no-await-in-loop"></a>[module eslint-plugin-babel.rules.no-await-in-loop](#apidoc.module.eslint-plugin-babel.rules.no-await-in-loop)

#### <a name="apidoc.element.eslint-plugin-babel.rules.no-await-in-loop.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.no-await-in-loop.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.no-await-in-loop.create)
- description and source-code
```javascript
create = function () {
    return {
        Program: function() {
            if (isWarnedForDeprecation || /\=-(f|-format)=/.test(process.argv.join('='))) {
                return;
            }

<span class="apidocCodeCommentSpan">            /* eslint-disable no-console */
</span>            console.log('The babel/no-await-in-loop rule is deprecated. Please ' +
                        'use the built in no-await-in-loop rule instead.');
            /* eslint-enable no-console */
            isWarnedForDeprecation = true;
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-babel.rules.no-invalid-this"></a>[module eslint-plugin-babel.rules.no-invalid-this](#apidoc.module.eslint-plugin-babel.rules.no-invalid-this)

#### <a name="apidoc.element.eslint-plugin-babel.rules.no-invalid-this.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.no-invalid-this.</span>create (context)](#apidoc.element.eslint-plugin-babel.rules.no-invalid-this.create)
- description and source-code
```javascript
create(context) {
    const stack = [],
        sourceCode = context.getSourceCode();

    let insideClassProperty = false;

<span class="apidocCodeCommentSpan">    /**
     * Gets the current checking context.
     *
     * The return value has a flag that whether or not 'this' keyword is valid.
     * The flag is initialized when got at the first time.
     *
     * @returns {{valid: boolean}}
     *   an object which has a flag that whether or not 'this' keyword is valid.
     */
</span>    stack.getCurrent = function() {
        const current = this[this.length - 1];

        if (!current.init) {
            current.init = true;
            current.valid = !astUtils.isDefaultThisBinding(
                current.node,
                sourceCode);
        }
        return current;
    };

    /**
     * 'this' should be fair game anywhere inside a class property.
     *
     * @returns {void}
     */
    function enterClassProperty() {
        insideClassProperty = true;
    }

    /**
     * Back to the normal check.
     * @returns {void}
     */
    function exitClassProperty() {
        insideClassProperty = false;
    }

    /**
     * Pushs new checking context into the stack.
     *
     * The checking context is not initialized yet.
     * Because most functions don't have 'this' keyword.
     * When 'this' keyword was found, the checking context is initialized.
     *
     * @param {ASTNode} node - A function node that was entered.
     * @returns {void}
     */
    function enterFunction(node) {

        // 'this' can be invalid only under strict mode.
        stack.push({
            init: !context.getScope().isStrict,
            node,
            valid: true
        });
    }

    /**
     * Pops the current checking context from the stack.
     * @returns {void}
     */
    function exitFunction() {
        stack.pop();
    }

    return {

        /*
         * 'this' is invalid only under strict mode.
         * Modules is always strict mode.
         */
        Program(node) {
            const scope = context.getScope(),
                features = context.parserOptions.ecmaFeatures || {};

            stack.push({
                init: true,
                node,
                valid: !(
                    scope.isStrict ||
                    node.sourceType === "module" ||
                    (features.globalReturn && scope.childScopes[0].isStrict)
                )
            });
        },

        "Program:exit"() {
            stack.pop();
        },

        ClassProperty: enterClassProperty,
        "ClassProperty:exit": exitClassProperty,
        FunctionDeclaration: enterFunction,
        "FunctionDeclaration:exit": exitFunction,
        FunctionExpression: enterFunction,
        "FunctionExpression:exit": exitFunction,

        // Reports if 'this' of the current context is invalid.
        ThisExpression(node) {
            const current = stack.getCurrent();

            if (!insideClassProperty && current && !current.valid) {
                context.report(node, "Unexpected 'this'.");
            }
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-babel.rules.object-shorthand"></a>[module eslint-plugin-babel.rules.object-shorthand](#apidoc.module.eslint-plugin-babel.rules.object-shorthand)

#### <a name="apidoc.element.eslint-plugin-babel.rules.object-shorthand.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.object-shorthand.</span>create ()](#apidoc.element.eslint-plugin-babel.rules.object-shorthand.create)
- description and source-code
```javascript
create = function () {
    return {
        Program: function() {
            if (isWarnedForDeprecation || /\=-(f|-format)=/.test(process.argv.join('='))) {
                return;
            }

<span class="apidocCodeCommentSpan">            /* eslint-disable no-console */
</span>            console.log('The babel/object-shorthand rule is deprecated. Please ' +
                        'use the built in object-shorthand rule instead.');
            /* eslint-enable no-console */
            isWarnedForDeprecation = true;
        }
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.eslint-plugin-babel.rules.semi"></a>[module eslint-plugin-babel.rules.semi](#apidoc.module.eslint-plugin-babel.rules.semi)

#### <a name="apidoc.element.eslint-plugin-babel.rules.semi.create"></a>[function <span class="apidocSignatureSpan">eslint-plugin-babel.rules.semi.</span>create (context)](#apidoc.element.eslint-plugin-babel.rules.semi.create)
- description and source-code
```javascript
create(context) {

    const OPT_OUT_PATTERN = /^[-[(/+']/; // One of [(/+-'
    const options = context.options[1];
    const never = context.options[0] === "never",
        exceptOneLine = options && options.omitLastInOneLineBlock === true,
        sourceCode = context.getSourceCode();

    //--------------------------------------------------------------------------
    // Helpers
    //--------------------------------------------------------------------------

<span class="apidocCodeCommentSpan">    /**
     * Reports a semicolon error with appropriate location and message.
     * @param {ASTNode} node The node with an extra or missing semicolon.
     * @param {boolean} missing True if the semicolon is missing.
     * @returns {void}
     */
</span>    function report(node, missing) {
        const lastToken = sourceCode.getLastToken(node);
        let message,
            fix,
            loc = lastToken.loc;

        if (!missing) {
            message = "Missing semicolon.";
            loc = loc.end;
            fix = function(fixer) {
                return fixer.insertTextAfter(lastToken, ";");
            };
        } else {
            message = "Extra semicolon.";
            loc = loc.start;
            fix = function(fixer) {
                return fixer.remove(lastToken);
            };
        }

        context.report({
            node,
            loc,
            message,
            fix
        });

    }

    /**
     * Checks whether a token is a semicolon punctuator.
     * @param {Token} token The token.
     * @returns {boolean} True if token is a semicolon punctuator.
     */
    function isSemicolon(token) {
        return (token.type === "Punctuator" && token.value === ";");
    }

    /**
     * Check if a semicolon is unnecessary, only true if:
     *   - next token is on a new line and is not one of the opt-out tokens
     *   - next token is a valid statement divider
     * @param {Token} lastToken last token of current node.
     * @returns {boolean} whether the semicolon is unnecessary.
     */
    function isUnnecessarySemicolon(lastToken) {
        if (!isSemicolon(lastToken)) {
            return false;
        }

        const nextToken = sourceCode.getTokenAfter(lastToken);

        if (!nextToken) {
            return true;
        }

        const lastTokenLine = lastToken.loc.end.line;
        const nextTokenLine = nextToken.loc.start.line;
        const isOptOutToken = OPT_OUT_PATTERN.test(nextToken.value) && nextToken.value !== "++" && nextToken.value !== "--";
        const isDivider = (nextToken.value === "}" || nextToken.value === ";");

        return (lastTokenLine !== nextTokenLine && !isOptOutToken) || isDivider;
    }

    /**
     * Checks a node to see if it's in a one-liner block statement.
     * @param {ASTNode} node The node to check.
     * @returns {boolean} whether the node is in a one-liner block statement.
     */
    function isOneLinerBlock(node) {
        const nextToken = sourceCode.getTokenAfter(node);

        if (!nextToken || nextToken.value !== "}") {
            return false;
        }

        const parent = node.parent;

        return parent && parent.type === "BlockStatement" &&
          parent.loc.start.line === parent.loc.end.line;
    }

    /**
     * Checks a node to see if it's followed by a semicolon.
     * @param {ASTNode} node The node to check.
     * @returns {void}
     */
    function checkForSemicolon(node) {
        const lastToken = sourceCode.getLastToken(node);

        if (never) {
            if (isUnnecessarySemicolon(lastToken)) {
                report(node, true);
            }
        } else {
            if (!isSemicolon(lastToken)) {
                if (!exceptOneLine || !isOneLinerBlock(node)) {
                    report(node);
                }
            } else {
                if (exceptOneLine && isOneLinerBlock(node)) {
                    report(node, true);
                }
            }
        }
    }

    /**
     * Checks to see if there's a semicolon after a variable declaration.
     * @param {ASTNode} node The node to check.
     * @return ...
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
