# ts-team-npm-module
Example of implementation typescript npm module

## package.json

section *typings* point to definition for your module.
in this exapmple - /lib/index.d.ts
section *main* point to npm module export

## src/tsconfig.json

section *declarations* should set to *true*
section *outDir* should set to "../lib"  

in another program where u wanna use this package
```javascript
// npm install ts-team-npm-module
import {writeJs} from 'ts-team-npm-module';
// or
import {writeJs} from 'ts-team-npm-module/lib/team-members'
// or
import {writeJs} from 'ts-team-npm-module/lib/team-members/dmtrv'
```
