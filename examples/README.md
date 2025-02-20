# Basic Nodejs example

## How to use

### SET ENV Variables

```
export PRIVATE_KEY=<paste your private key here> // A sample private key prefix with `0x`
export BASE_URL=<Enter Cray Gateway URL here>
export API_KEY=<Enter Cray API KEY here>
```

Be careful with your private key, Use a key your are comfortable with for development purpose.

### Install and run:

```bash
cd .. // make sure you are on AbstractPay directory
npm run build && ts-node examples/simple_pay.ts
```
