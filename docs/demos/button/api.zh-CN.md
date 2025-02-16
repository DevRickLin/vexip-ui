### Button 属性

| 名称         | 类型                                                                    | 说明                                           | 默认值      | 始于    |
| ------------ | ----------------------------------------------------------------------- | ---------------------------------------------- | ----------- | ------- |
| type         | `'default' \| 'primary' \| 'info' \| 'success' \| 'warning' \| 'error'` | 设置按钮类型                                   | `'default'` | -       |
| simple       | `boolean`                                                               | 开启后，按钮将变为浅色系的简约风格             | `false`     | -       |
| ghost        | `boolean`                                                               | 开启后，按钮将变成背景颜色透明的样式           | `false`     | -       |
| text         | `boolean`                                                               | 设置是否为文本按钮                             | `false`     | `2.0.0` |
| dashed       | `boolean`                                                               | 设置是否为虚线边框按钮                         | `false`     | `2.0.0` |
| size         | `'small' \| 'default' \| 'large'`                                       | 按钮的大小                                     | `'default'` | -       |
| disabled     | `boolean`                                                               | 设置是否为禁用状态 设置                        | `false`     | -       |
| loading      | `boolean`                                                               | 设置是否为加载状态 设置                        | `false`     | -       |
| circle       | `boolean`                                                               | 设置是否为圆形按钮                             | `false`     | -       |
| icon         | `Record<string, any>`                                                   | 按钮的辅助图标，加载状态时会切换为加载图标     | `''`        | -       |
| loading-icon | `Record<string, any>`                                                   | 加载状态时显示的图标，具有脉冲效果             | `Spinner`   | -       |
| loading-spin | `boolean`                                                               | 开启后，加载中图标原有的脉冲效果将变位旋转效果 | `false`     | -       |
| button-type  | `'button' \| 'submit' \| 'reset'`                                       | 设置原生 button 的 type 属性                   | `'button'`  | -       |
| block        | `boolean`                                                               | 是否为块级元素，设置后宽度变为 `100%`          | `false`     | -       |
| color        | `string`                                                                | 设置按钮的主题色                               | `null`      | `2.0.0` |
| tag          | `string`                                                                | 设置按钮的渲染标签                             | `'button'`  | `2.0.0` |
| no-pulse     | `boolean`                                                               | 设置是否禁用点击后的脉冲效果                   | `false`     | `2.0.0` |
| badge        | `number \| string`                                                      | 设置内置徽标内容                               | `null`      | `2.0.4` |

### Button 事件

| 名称  | 说明                                    | 参数                  | 始于 |
| ----- | --------------------------------------- | --------------------- | ---- |
| click | 左键点击按钮时触发， 返回点击的事件对象 | `(event: MouseEvent)` | -    |

### Button 插槽

| 名称    | 说明                                             | 参数 | 始于    |
| ------- | ------------------------------------------------ | ---- | ------- |
| default | 按钮的内容插槽                                   | -    | -       |
| icon    | 按钮前置图标的插槽                               | -    | `2.0.0` |
| loading | 加载图标的插槽，需要更多定制化加载图标效果时使用 | -    | -       |
