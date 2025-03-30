### Cherry Studio 的MCP 设置方法：

1. 打开 https://mcp.so/
2. 选择 Fetch

![](attachment/4d645c7002d6d86fa95320c8255e153a.png)

右边点“Connect”， 记下红色的URL 地址

![](attachment/9998500c813f4f1500da716bc6177665.png)

3. 在Cherry Studio 中新建“MCP 服务器”， 类型选择“SSE”（也就是远程连接的意思），填入URL，保存。
   ![](attachment/115bcc403aed9140663e1dde709ac3c4.png)

4. 打开“模型服务”，选择一个合适的模型平台和模型（例如， 选择“硅基流动”和Qwen/Qwen2.5-32B-Instruct 这个模型），注意，模型必须是能支持函数调用的模型。

![](attachment/9a5358c41b4e495695c7164ad9d4af1a.png)

5. 在Charry Studio 中新建对话， 选择AI 模型， 在下面的选项对话中选择刚才的“Fetch” MCP 服务器。

![](attachment/0bc92271ebc871fe39891f106f6bc16c.png)

问AI 一个最新的话题，例如让它去获取当天网站的内容：

![](attachment/6714d3ad48b3683c0556d6dd6a947a5f.png)