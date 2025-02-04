

@[TOC](文章目录)

---

# 前言
昨晚OpenAI公开了GPT-4的进展，并可以基于ChatGPT实现GPT-4的使用和访问。博主连夜总结出以下Xmind，那么GPT-4到底有哪些巨大的能力提升呢，让我们来一探究竟！【如需进一步交流，请私信】
![在这里插入图片描述](https://img-blog.csdnimg.cn/06cd3a8ba1ae4d02959638be21d75227.png)


---


# 一、准确性提升
GPT-4 可以更准确地解决难题，这要归功于其更广泛的常识和解决问题的能力。
GPT能力提升主要在三个方面：
## 1.创造力
![在这里插入图片描述](https://img-blog.csdnimg.cn/e12007f74e9744f7bea961ee8e58cac0.png)

如上图所示，是OpenAI官网展示的一个例子，这里我人肉翻译了下：
`Input`
> 用一个句子解释灰姑娘的情节，其中每个单词必须以字母表中从 A 到 Z 的下一个字母开头，> 不重复任何字母。

`Output`

> 美丽的灰姑娘充满热切地生活，最终找到了幸福；她激发了嫉妒的亲戚们，神奇的爱情滋养着富有的王子；她悄悄地拯救了他，水晶鞋取得胜利，奇妙地将他们紧密团结在一起，这对热情洋溢的年轻人友好相处。

从上述例子汇总我们可以发现，GPT-4 比以往任何时候都更具创造性和协作性。官网说它可以生成、编辑并与用户一起迭代创意和技术写作任务，例如创作歌曲、编写剧本或学习用户的写作风格。
## 2.视觉输入
GPT-4还支持视觉输入
![在这里插入图片描述](https://img-blog.csdnimg.cn/69bf64242f434153b51217092cba45f8.png)
![在这里插入图片描述](https://img-blog.csdnimg.cn/9f756821bae3446c83b97be9b57fc6a3.png)
上面给出了一个例子：我可以用这些原料干什么，随后给出一张鸡蛋、面粉、奶油的图片。GPT-4给出如下回复:

`Output`

> 有很多种方法可以用这些食材制作美食！以下是一些可能的选择：
> - 煎饼或华夫饼
> - 可丽饼
> - 法式吐司
> - 煎蛋卷或意式烘蛋
> - 派
> - 蛋奶酥或布丁
> - 蛋糕或纸杯蛋糕
> - 松饼或面包
> - 饼干或饼干
这只是其中的一些例子，但可能性是无穷无尽的！

这回复简直太赞了！

## 3.更长的上下文
![在这里插入图片描述](https://img-blog.csdnimg.cn/ca6ad27d2ec04dc3867417bfe3142899.png)
GPT-4 能够处理超过 25,000 个单词的文本，允许使用长格式内容创建、扩展对话以及文档搜索和分析等用例。



# 二、相比于ChatGPT有哪些提升
## 1.GPT-4 的高级推理能力超越了 ChatGPT
![在这里插入图片描述](https://img-blog.csdnimg.cn/21956e05cb1c4ce88824ae166c9aa40a.png)
`Input`
> 安德鲁从上午11点到下午3点有空，乔安娜从中午12点到下午2点，然后从下午3点半到5点有空。汉娜在中午12点有半小时空闲，然后在下午4点到6点有空。对于安德鲁、汉娜和乔安娜来说，安排一场时长30分钟的会议，有哪些开始时间的选项？

`ChatGPT Output`
> 以下是他们的空闲时间列表：
> - 安德鲁：上午11点至下午3点
> - 乔安娜：中午12点至下午2点，下午3点半至5点
> - 汉娜：中午12点至12点半，下午4点至6点
> 根据他们的空闲时间，有一个30分钟的时间窗口，这三个人都有空，即下午4点至4点半。所以，会议可以安排在下午4点

`GPT-4 Output`
> 安德鲁：上午11点 - 下午3点
乔安娜：中午12点 - 下午2点，下午3点半 - 下午5点
汉娜：中午12点 - 12点半，下午4点 - 下午6点
可以安排30分钟会议的共同空闲时间：中午12点 - 12点半

## 2.GPT-4 在多种测试考试中均优于 ChatGPT。
![在这里插入图片描述](https://img-blog.csdnimg.cn/13c672ea0d31478d87e691b69def71be.png)
在统一律师考试中，ChatGPT排名在倒数10%内，而GPT-4或者了前10%的好成绩，而在生物奥林匹克考试中，GPT-4的领先更加夸张，或者排名前1%的好成绩，而ChatGPT才排31名。

---

# 三、研究团队在GPT-4模型都做了哪些改善
## 1.遵循 GPT、GPT-2 和 GPT-3 的研究路径
我们的深度学习方法利用更多数据和更多计算来创建越来越复杂和强大的语言模型。
## 2.我们花了 6 个月的时间使 GPT-4 更安全、更一致。
在我们的内部评估中，与 GPT-3.5 相比，GPT-4 响应不被允许内容请求的可能性低 82%，产生事实响应的可能性高 40%
## 3.安全与对齐：
  - 1.通过人工反馈进行训练（人工+专家反馈）
    - 我们纳入了更多的人工反馈，包括 ChatGPT 用户提交的反馈，以改进 GPT-4 的行为。我们还与 50 多位专家合作，在 AI 安全和保障等领域获得早期反馈。
  - 2.从现实世界的使用中不断改进（现实世界反馈）
    - 我们已经将我们以前模型在现实世界中使用的经验教训应用到 GPT-4 的安全研究和监控系统中。与 ChatGPT 一样，随着越来越多的人使用它，我们将定期更新和改进 GPT-4。
  - 3. GPT-4 辅助的安全研究（自己使用）
    - GPT-4 的高级推理和指令遵循能力加快了我们的安全工作。我们使用 GPT-4 帮助创建用于模型微调的训练数据，并在训练、评估和监控过程中迭代分类器。

# 四、和一些开发创新产品的组织合作
- Duolingo：一种对话类应用
- Be My Eyes：使用GPT-4提高视觉能力
- Stripe：使用GPT-4简化用户体验并打击欺诈
- Morgan Stanley：使用GPT-4来管理公司内部知识库
- Khan Academy：在试点项目中探索GPT-4的潜力
- Government of Iceland：使用GPT-4保护本土语言
- Etc.

# 五、其他
## 详细研究报告
https://openai.com/research/gpt-4
## 基础设施：
GPT-4 在 Microsoft Azure AI 超级计算机上接受过训练。Azure 的 AI 优化基础架构还使我们能够向世界各地的用户提供 GPT-4。
## 局限性
GPT-4 仍然有许多我们正在努力解决的已知局限性，例如社会偏见、幻觉和对抗性提示。随着社会采用这些模型，我们鼓励并促进透明度、用户教育和更广泛的人工智能素养。我们还旨在扩大人们在塑造我们的模型时的输入途径。
## 可用性
我们在 ChatGPT Plus 上提供 GPT-4，并作为开发人员构建应用程序和服务的 API。

# 总结
GPT-4的横空出世将ChatGPT的很多局限性突破了，虽然基础模型能力只有一点提升（官方团队谦虚之语），但是在各种测试中GPT-4都完爆ChatGPT了，如果想了解更多内容或者加入到AIGC&ChatGPT的研究交流中可以私信我！