# 可以关掉

```html
<n-space vertical :size="12">
  <n-alert title="Default 类型" type="default" closable>
    <template #icon>
      <n-icon>
        <ios-airplane />
      </n-icon>
    </template>
    Gee it's good to be back home
  </n-alert>
  <n-alert title="Info 类型" type="info" closable>
    Gee it's good to be back home
  </n-alert>
  <n-alert title="Success 类型" type="success" closable>
    Leave it till tomorrow to unpack my case
  </n-alert>
  <n-alert title="Warning 类型" type="warning" closable>
    Honey disconnect the phone
  </n-alert>
  <n-alert title="Error 类型" type="error" closable>
    I'm back in the U.S.S.R.
  </n-alert>
</n-space>
```

```js
import { IosAirplane } from '@vicons/ionicons-v4'

export default {
  components: {
    IosAirplane
  },
  data () {
    return {
      show: true
    }
  }
}
```