# cross-json-post
tiny lib that only handle json post for both browser and node

```
import postJSON from 'cross-json-post'

// (url: string, data: any, headers?:any) => Promise<any>;
postJSON(url,{abc:123}).then(jsonObj=>console.log(jsonObj))

```