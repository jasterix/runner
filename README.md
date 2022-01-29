# runner

### Strategy
1. Find resources that break down how to build an online editor like Codepen or a sendbox
2. Figure out which frameworks or packages I can use
3. Review repos and projects that do something similar

#### Tools / Frameworks- options
- esbuild- https://esbuild.github.io/
- react / typescript or javascript
- JS-Interpreter- https://github.com/NeilFraser/JS-Interpreter

- No file system in the browser. Tell ESBBUild to fetch the modules
		- Make our own plugin and when it comes across x, use 

### Reference points
- [CodeRunner](https://github.com/olga-f/javascript-code-runner)

```mmd
flowchart LR
 A[code]-->B[esbuild]--> C[bundled code]
 ```