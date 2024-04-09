# openai-images-edits
旨在打造一个使用 OpenAI 图片编辑API（或Chat2API）来让AI编辑图片的服务。

#### 使用官方API：https://platform.openai.com/docs/api-reference/images/createEdit
#### 或者使用Chat2API：https://api.oaifree.com/v1/images/edits [介绍](https://linux.do/t/topic/50789)

去编辑一张几乎任意的图片（需要遵循限制的宽高）。

* `mask-editor.html` 是我让GPT写的一个mask生成页面，页面很简陋，大概意思是对了。

现在需要完善的地方是：
1. 页面更精美
2. 功能更完善
3. 可以设置 `api key` 或 `access token`
4. 可以设置 `api base url`
5. 可以直接一步到位调用图片编辑API生成
6. 可以展示、保存修改后的图片

#### 我抛砖引玉，期待你们的PR。
