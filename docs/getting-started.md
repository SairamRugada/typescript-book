* [Getting Started with TypeScript](#getting-started-with-typescript)
* [TypeScript Version](#typescript-version)

# Getting Started With TypeScript

TypeScript compiles into JavaScript. JavaScript is what you are actually going to execute (either in the browser or on the server). So you are going to need the following:

* TypeScript compiler (OSS available [in source](https://github.com/Microsoft/TypeScript/) and on [NPM](https://www.npmjs.com/package/typescript))
* A TypeScript editor (you can use notepad if you want but I use [alm 🌹](http://alm.tools))


![](https://raw.githubusercontent.com/alm-tools/alm-tools.github.io/master/screens/main.png)


## TypeScript Version

Instead of using the *stable* TypeScript compiler we will be presenting a lot of new stuff in this book that may not be associated with a version number yet. I generally recommend people to use the nightly version because **the compiler test suite only catches more bugs over time**.

You can install it on the command line as

```
npm install -g typescript@next
```

Various IDEs support it too, e.g. `alm` always ships with the latest TypeScript version.

## TypeScript definitions
TypeScript has a concept of a *declaration file* for external JavaScript code bases. *High quality* files exist for nearly 90% of the top JavaScript libraries out there in a project called [DefinitelyTyped](http://definitelytyped.org/). You will need `typings` to get these defintions. Don't worry, we will explain what this means later ... just install for now:

```
npm install -g typings
```

## Getting the Source Code
The source for this book is available in the books github repository https://github.com/basarat/typescript-book/tree/master/code most of the code samples can be copied into alm and you can play with them as is. For code samples that need additional setup (e.g. npm modules), we will link you to the code sample before presenting the code. e.g.

`this/will/be/the/link/to/the/code.ts`
```ts
// This will be the code under discussion
```

With a dev setup out of the way lets jump into TypeScript syntax.
