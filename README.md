Example for TypeDoc Issue: [https://github.com/TypeStrong/typedoc/issues/2754](https://github.com/TypeStrong/typedoc/issues/2754)

Steps:
- Run `npm install`
- Go to Project1 directory and run `..\node_modules\.bin\tsc`
- Go to Project2/A directroy and run `..\..\node_modules\.bin\tsc`
- Go to Project2/B directroy and run `..\..\node_modules\.bin\tsc`
- Go to Project1 directroy and run `npx typedoc`
- Go to Project2 directroy and run `npx typedoc`
