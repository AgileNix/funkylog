# FUNKYLOG - Make your console.logs look interactive!
Funkylog lets you add the delay between printing out the characters to the console.

Step 1: configure the delay and add optional randomization

Step 2: just pass in the string!
## INSTALLATION
```console
npm install --save funkylog
```
## USAGE
```js
import funkylog from 'funkylog';

const { log } = funkylog({ delay: 100, randomized: true });
```
```js
log('Hello, Funky World!').then(...);
```
```js
await log('Hello, Funky World!');
```

