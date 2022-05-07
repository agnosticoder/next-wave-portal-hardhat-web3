# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

```js
import {read} from 'to-vfile'
import {rehype} from 'rehype'
import rehypeHighlight from 'rehype-highlight'

main()

async function main() {
  const file = await rehype()
    .data('settings', {fragment: true})
    .use(rehypeHighlight)
    .process(await read('example.html'))

  console.log(String(file))
}
```
