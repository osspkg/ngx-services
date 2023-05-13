# @uxwb/services

## Installation

```bash
  $ npm i @uxwb/ngx-services --save
```

## Config

```typescript
class Config {
  ajaxPrefixUrl?:string;
  webSocketUrl?:string;
}
```
## Use

```typescript
import { UXWBServicesModule } from '@uxwb/ngx-services';

@NgModule({
  ...
  imports: [
    ...
    UXWBServicesModule.forRoot({ ajaxPrefixUrl:'/api', webSocketUrl:'/ws' }),
  ],
  ...
})
```

## License

BSD-3-Clause License. See the LICENSE file for details.
