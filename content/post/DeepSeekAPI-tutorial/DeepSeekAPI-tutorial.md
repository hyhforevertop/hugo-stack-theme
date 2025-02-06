+++
date = '2025-02-06T11:01:18+08:00'
draft = false
title = 'DeepSeekAPI Tutorial'
+++

# DeepSeekAPI调用教程



> 最近出来了一个新的国产 **AI** 模型 **DeepSeek**，并且具有深度思考的功能。
>
> 我体验过后感觉比 **ChatGPT** 要好很多，体现在 **DeepSeek** 能更好的理解用户的问题。
>
> 不过官网上的对话，总是要思考一会，从几秒到几十秒不等，问题越复杂考虑的就越久（当然这是好事，对问题分析的越清晰，回答的准确率就越高。也有可能是服务器被攻击了）。

![img](https://www.hyhforever.top/wp-content/uploads/2025/01/image-110-1024x466.png)

因此这篇文章是关于如何通过 **API** 来使用 **DeepSeek**

## GroqCloud

到下面这个官网中进入 **Dev Console**，需要使用谷歌或者 **Github** 账号

- [GroqCloud - Groq is Fast AI Inference](https://groq.com/groqcloud/)

![img](https://www.hyhforever.top/wp-content/uploads/2025/01/image-111-1024x318.png)

切换模型为 **deepseek-r1-distill-llama-70b**

与官网上的模型不同的是，**DeepSeek-R1-Distill-LLAMA-70B** 是 **DeepSeek** 公司基于 **Meta** 的 **LLAMA** 模型，通过知识蒸馏技术开发的一款高效大语言模型。它结合了大规模模型的强大能力和知识蒸馏带来的高效性，广泛应用于自然语言理解和生成任务。随着技术的不断发展，这类模型将在各个领域发挥越来越重要的作用。

![img](https://www.hyhforever.top/wp-content/uploads/2025/01/image-112-1024x500.png)

## Cherry Studio

到官网下载一个对话软件

-  [Cherry Studio - 全能的AI助手](https://cherry-ai.com/)

![img](https://www.hyhforever.top/wp-content/uploads/2025/01/image-114-1024x636.png)

填入 **API** 密钥后，底部添加一个模型，名称一致即可

![img](https://www.hyhforever.top/wp-content/uploads/2025/01/image-115-1024x636.png)

## 对比测试

可以看到使用 **API** 调用的深度思考时间极短，只有 **0.3** 秒

![img](https://www.hyhforever.top/wp-content/uploads/2025/01/image-116-1024x636.png)

当然，**GroqCloud** 上面还有其他的模型，如果不喜欢 **DeepSeek** 也可以尝试其他的

通过 API 调用能够节省很多时间，尽管模型在参数上有一点区别，但是也够用了