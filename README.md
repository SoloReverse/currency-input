# An accessible & unstyled Currency Input Component

Based on [input-otp@1.4.1](https://github.com/guilhermerodz/input-otp) [@guilhermerodz](https://twitter.com/guilherme_rodz)

Its just a tiny algorithm tweek to the component and removal of autocomplete attribute.
I'll try to remove all the unnecessary stuff later.
Fully compatible with Shadcn Input OTP just change the imports as below

![](https://github.com/SoloReverse/currency-input/blob/ee2adb30cd37e3f7ccabdb1217b93f8073e65021/examples/output.gif)

## Usage

```bash
npm install @solorev/currency-input
```

I didn't even bother changing the exports so Import with `{OTPInput}` atm

```diff
+'use client'
-import { OTPInput } from 'input-otp'
+import { OTPInput } from '@solorev/currency-otp'

function MyForm() {
  return <form>
+   <OTPInput maxLength={6} render={({slots})  => (...)} />
  </form>
}
```
