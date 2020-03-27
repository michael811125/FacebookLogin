# Facebook 封裝js

---

### Typescript使用方式
typescript 可以透過require的方式載入
```
import fbSDK = require("/Path/fb_login");
```
```
let fb = new fbSDK.Facebook();
fb.loginWithFacebook();
```
---

### Javascript使用方式
javscript 就直接引入使用就好, 或是html裡面遷入腳本也可
```
<script src="fb_login.js"></script>
```
```
import { Facebook } from '/Path/fb_login.js';
```
```
let fb = new fbSDK.Facebook();
fb.loginWithFacebook();
```

