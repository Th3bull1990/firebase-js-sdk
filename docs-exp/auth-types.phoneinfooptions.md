<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/auth-types](./auth-types.md) &gt; [PhoneInfoOptions](./auth-types.phoneinfooptions.md)

## PhoneInfoOptions type

The information required to verify the ownership of a phone number.

<b>Signature:</b>

```typescript
export type PhoneInfoOptions =
  | PhoneSingleFactorInfoOptions
  | PhoneMultiFactorEnrollInfoOptions
  | PhoneMultiFactorSignInInfoOptions;
```
<b>References:</b> [PhoneSingleFactorInfoOptions](./auth-types.phonesinglefactorinfooptions.md)<!-- -->, [PhoneMultiFactorEnrollInfoOptions](./auth-types.phonemultifactorenrollinfooptions.md)<!-- -->, [PhoneMultiFactorSignInInfoOptions](./auth-types.phonemultifactorsignininfooptions.md)

## Remarks

The information that's required depends on whether you are doing single-factor sign-in, multi-factor enrollment or multi-factor sign-in.
