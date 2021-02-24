## API Report File for "@firebase/app-types-exp"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { ComponentContainer } from '@firebase/component';

// @public
export interface FirebaseApp {
  automaticDataCollectionEnabled: boolean;

  readonly name: string;

  readonly options: FirebaseOptions;
}

// @public (undocumented)
export interface FirebaseAppConfig {
  // (undocumented)
  automaticDataCollectionEnabled?: boolean;
  // (undocumented)
  name?: string;
}

// @internal (undocumented)
export interface _FirebaseAppInternal extends FirebaseApp {
  // (undocumented)
  checkDestroyed(): void;
  // (undocumented)
  container: ComponentContainer;
  // (undocumented)
  isDeleted: boolean;
}

// @public (undocumented)
export interface FirebaseOptions {
  // (undocumented)
  apiKey?: string;
  // (undocumented)
  appId?: string;
  // (undocumented)
  authDomain?: string;
  // (undocumented)
  databaseURL?: string;
  // (undocumented)
  measurementId?: string;
  // (undocumented)
  messagingSenderId?: string;
  // (undocumented)
  projectId?: string;
  // (undocumented)
  storageBucket?: string;
}

// @internal (undocumented)
export interface _FirebaseService {
  // (undocumented)
  app: FirebaseApp;
  _delete(): Promise<void>;
}

// @internal (undocumented)
export interface _PlatformLoggerService {
  // (undocumented)
  getPlatformInfoString(): string;
}

// @internal (undocumented)
export interface _VersionService {
  // (undocumented)
  library: string;
  // (undocumented)
  version: string;
}


// (No @packageDocumentation comment for this package)

```