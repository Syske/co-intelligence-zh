# 单元 23｜第7章：关于AI的教学 Teaching about AI

> **书籍**：Co-Intelligence — Living and Working with AI（Ethan Mollick）
> **单元**：23/31 ｜ **页码范围**：P.134–136（3 页）｜ **完成日期**：2026-11-22

---

## 本单元讲了什么

本单元先接上宾大"AI 必修制"的作业实例：创业课的第一项作业被改成"野心放大到不可能"——不会编程也要承诺做出能跑的应用程序，项目涉及网站就要交付全原创的可用原型，"因过于雄心勃勃而失败不扣分"；作业流程是让 AI 列出项目可能失败的 10 种方式和成功图景，再召唤三位名人（乔布斯、伊丽莎白一世、蕾哈娜等）用他们自己的口吻批评你的战略。这造成课堂的两极分化：论文写作课"回归十九世纪"的课堂手写蓝色考卷，实践型课堂则每天完成"不可能"。接着抛出真正的大问题——该教什么：连美国教育部都迅速表态 AI 要进课堂，而更进一步的观点是从"教知识"转向"教与 AI 协作"：基础 AI 素养（AI literacy）加提示词工程（prompt engineering）。作者给提示词工程泼冷水：2023 年"AI 语者"六位数年薪催生课程/教程/YouTube 发财产业链，但提示词工程是有用的近期技能、并不复杂——"读到这里你已足够当一名好的提示词工程师"，因为它的原理就是已讲过的共智原则。随后是本单元的技术核心：LLM 靠预测下一个词生成文本，默认输出必然泛泛；打破模式 cheapest 的方法是提供背景与约束（context and constraints）；进阶提示是"用散文编程"（programming in prose）——给指令、AI 大体遵循，但伴随随机性、没有程序般的一致性；思维链提示（chain-of-thought prompting）先给推理范例再提请求，或给出层层递进的逐步指令，好处是每步输出可检查、提示词可迭代、整体更准确。实例教学极为直观：单句索要 AI 导师类比只得到"节拍器"式平庸回答；步骤化提示（列清单→批评补充→做对比表→择优解释）让 GPT-4 给出"GPS 导航"的完整类比——质量差异来自提示结构而非模型能力。收尾金句：提示词工程与其说是科学不如说是艺术——谷歌最强模型对"深呼吸，一步一步来"反应最好；AI 不会呼吸也不会惊慌，却最吃这套，再次印证 AI"像人不像软件"。（句子在 P.136 页尾中断，续至单元 24）

---

## 英文原文

...to people at real organizations. And some of the assignments take advantage of the fact that the AI enables the impossible. For example, my first assignment to students in my Wharton entrepreneurship class now reads:

Make what you are planning on doing ambitious to the point of impossible; you are going to be using AI. Can't code? Definitely plan on making a working app. Does it involve a website? You should commit to creating a prototype working site, with all-original images and text. I won't penalize you for failing if you are too ambitious.

Any plan benefits from feedback, even if it just gives you permission to discuss what might go wrong. Ask the AI to give you 10 ways your project could fail and a vision of success, using the prompts from class. And, to make it interesting, ask three famous figures to criticize your plan. You can invoke entrepreneurs (Steve Jobs, Tory Burch, Jack Ma, Rihanna), leaders (Elizabeth I, Julius Caesar), artists, philosophers, or any other people you think would be useful to critique your strategy in their voice.

Thus, while classes that are focused on teaching essays and writing skills will return to the nineteenth century, with in-class essays handwritten in blue books, other classes will feel like the future, with students carrying out the impossible every day.

Of course, all this raises the even bigger question: What should we actually teach? Even slow-moving educational institutions are recognizing that teaching about AI will play an important role in education, with the US Department of Education suggesting, within just months of the release of ChatGPT, that AI will need to be embraced in classrooms. Some pundits go further, arguing that we need to focus on working with AI. We should, they argue, teach basic AI literacy, and probably "prompt engineering," about the art and science of creating good prompts for AIs.

In 2023, many companies advertised six-figure salaries for "AI whisperer" roles, and for good reason—as we have seen, working with AI is far from intuitive. And any time a new job title with high pay appears, so does a huge number of courses, instruction manuals, and YouTube channels offering the knowledge you (yes, YOU) need to get rich today.

To be clear, prompt engineering is likely a useful near-term skill. But I don't think prompt engineering is so complicated. You actually have likely read enough at this point to be a good prompt engineer.

Let's start with the third principle I shared earlier—treat AI like a person and tell it what kind of person it is. LLMs work by predicting the next word, or part of a word, that would come after your prompt, sort of like a sophisticated autocomplete function. Then they continue to add language from there, again predicting which word will come next. So the default output of many of these models can sound very generic, since they tend to follow similar patterns that are common in the written documents the AI was trained on. By breaking the pattern, you can get much more useful and interesting outputs. The easiest way to do that is to provide context and constraints, as we saw in chapter 5.

For slightly more advanced prompts, think about what you are doing as programming in prose. You can give the AI instructions and it mostly sort-of follows them. Mostly, because there is a lot of randomness associated with AI outputs, so you will not get the consistency of a standard computer program. But it can be worth thinking about how you can provide a very clear and logical prompt to the AI.

A lot of active research is happening around the best way to "program" an LLM, but one practical implication is that it can help to give the AI explicit instructions that go step by step through what you want. One approach, called chain-of-thought prompting, gives the AI an example of how you want it to reason, before you make your request. Even more usefully, you can also provide step-by-step instructions that build on each other, making it easier to check the output of each step (letting you refine the prompt later), and which will tend to make the output of your prompts more accurate.

Here is an example: let's say I wanted to include a good analogy of an AI tutor in this chapter, and wanted to get help from an AI. I could simply ask for one: Tell me a good analogy for an AI tutor. And the response was a little unsatisfying: An AI tutor is like a musical metronome, because it is consistent, adaptable, and a mere tool.

Now we can try applying some of these other techniques: Think this through step by step: come up with good analogies for an AI tutor. First, list possible analogies. Second, critique the list and add three more analogies. Next, create a table listing pluses and minuses of each. Next, pick the best and explain it. Here, GPT-4 considered a dozen suggestions, from personal trainer to gardener, and created a table comparing them all, before settling on a GPS system, which, much like an AI tutor, is designed to assist users in navigating unfamiliar terrain. It provides real-time feedback, adjusts recommendations based on changing conditions (e.g., traffic or construction), and offers alternative routes when the user goes off track. Similarly, an AI tutor guides students through the academic terrain, offering real-time feedback, adjusting based on the student's progress, and providing alternative learning paths when necessary. This analogy also emphasizes the idea that while the tool provides guidance, it's up to the user (or student) to drive and make the journey, reinforcing the collaborative nature of learning with AI. Much improved, due to a little prompt engineering.

However, all of this remains much less a science than an art, and AIs still work more like people than software. For example, in a study where AIs tested many different kinds of prompts, Google's most advanced model responded best to a prompt that began "Take a deep breath and work on this problem step by step!" Given their inability to breathe, or to panic, I don't think anyone would have suspected that this would be the most effective way to get an AI to do

（注：本句在 P.136 页尾中断，续于单元 24 开头。）

---

## 中文翻译

……面向真实组织中的人们。其中一些作业还利用了"AI 让不可能成为可能"这一事实。比如，我如今给沃顿商学院创业课上学生的第一项作业是这样写的：

把你们计划要做的事情，野心放大到不可能的程度；因为你们将会使用 AI。不会编程？那就务必计划做出一个能跑的应用程序。项目涉及网站？那就应该承诺做出一个可运行的原型站点，图片和文字全部原创。如果你因为过于雄心勃勃而失败，我不会因此扣你的分。

任何计划都能从反馈中获益，哪怕反馈只是给了你一个机会，去讨论哪些环节可能出问题。请 AI 给出你的项目可能失败的 10 种方式，以及一幅成功的图景，提示词用课堂上讲的那些。还有，为了有趣一点，再请三位名人来批评你的计划。你可以召唤企业家（史蒂夫·乔布斯、Tory Burch、马云、蕾哈娜）、领袖（伊丽莎白一世、尤利乌斯·凯撒）、艺术家、哲学家，或任何你认为适合用他们自己的口吻来批评你的战略的人。

于是，一方面，那些以教授论文和写作技巧为核心的课程将回归十九世纪——学生在课堂上手写蓝色考卷（blue books）完成作文；另一方面，另一些课堂则会充满未来感——学生们日复一日地把"不可能"变成现实。

当然，这一切引出了一个更大的问题：我们究竟应该教什么？就连动作迟缓的教育机构也认识到，关于 AI 的教学将在教育中扮演重要角色——美国教育部在 ChatGPT 发布后仅几个月就提出，AI 需要走进课堂。一些评论家则更进一步，主张我们应聚焦于"与 AI 协作"。他们认为，我们应当教授基础的 AI 素养（AI literacy），很可能还应该包括"提示词工程"（prompt engineering）——这门为 AI 打造优质提示词的艺术与科学。

2023 年，许多公司为"AI 语者"（AI whisperer）岗位打出了六位数年薪的招聘广告，这并非没有道理——正如我们所见，与 AI 协作远不是一件凭直觉就能做好的事。而且，每当一个高薪新头衔出现，随之而来的就是海量的课程、教程和 YouTube 频道，兜售你（没错，就是你）今天发财所需的知识。

需要说明的是，提示词工程很可能确实是一门有用的近期技能。但我并不认为提示词工程有多么复杂。事实上，读到这里，你很可能已经足以成为一名优秀的提示词工程师了。

让我们从前面分享过的第三条原则开始——像对待人一样对待 AI，并告诉它它是哪种人。LLM 的工作方式是预测下一个词（或词的一部分），即在你的提示之后最可能出现的那个词，有点像一种复杂的自动补全功能。然后它们继续预测下一个词，如此往后追加语言。因此，这些模型的默认输出听起来可能非常泛泛，因为它们倾向于遵循训练文本中常见的相似模式。而打破这种模式，你就能得到有用得多、有趣得多的输出。最简单的办法是提供背景和约束（context and constraints），正如我们在第 5 章看到的那样。

对于稍微进阶一点的提示，可以把你的所作所为理解为"用散文编程"（programming in prose）。你可以给 AI 下指令，而它大体上会照着做。之所以说"大体上"，是因为 AI 的输出伴随大量随机性，你不会得到标准计算机程序那样的一致性。但思考如何给 AI 一个非常清晰、合乎逻辑的提示，往往是值得的。

关于"编程"LLM 的最佳方式，眼下有大量活跃的研究，但一个实用的结论是：给 AI 明确的、一步一步展开你要求的指令，会很有帮助。其中一种方法叫思维链提示（chain-of-thought prompting）：在提出请求之前，先给 AI 一个你希望它如何推理的范例。更有用的是，你还可以提供相互衔接的逐步指令——这让你更容易检查每一步的输出（也方便你日后改进提示词），并且往往会让提示的输出更准确。

举个例子：假设我想在本章中加入一个关于 AI 导师的精彩类比，并且想请 AI 帮忙。我可以直接开口要："给我一个好的 AI 导师类比。"而回答有点不令人满意："AI 导师就像音乐节拍器，因为它稳定、可适应，而且不过是个工具。"

现在，我们可以试着运用上面这些技巧："一步步思考：为 AI 导师想出好的类比。第一，列出可能的类比。第二，批评这个清单，再补充三个类比。接下来，制作一张表格，列出每个类比的优缺点。再接下来，选出最好的一个并解释它。"这里，GPT-4 考虑了十多个建议，从私人教练到园丁，然后创建了一张对比表格，最后选定 GPS 导航系统——它与 AI 导师非常相似，都是为帮助用户在陌生地形中导航而设计的。它提供实时反馈，根据变化的情况（如交通或施工）调整建议，并在用户偏离路线时提供替代路线。类似地，AI 导师引导学生穿越学术地形，提供实时反馈，根据学生的进度调整，并在必要时提供替代学习路径。这个类比还强调了一点：工具提供指引，但开车上路的是用户（或学生）自己，这强化了与 AI 协作学习的本质。相比之前，输出大为改观——这都得益于一点点提示词工程。

然而，尽管如此，这一切与其说是一门科学，不如说是一门艺术，AI 的运作方式仍然更像人而非软件。例如，在一项让 AI 测试多种不同提示词的研究中，谷歌最先进的模型对这样开头的提示反应最好："深呼吸，然后一步一步地解决这个问题！"鉴于 AI 既不会呼吸，也不会惊慌，我不认为有人会事先猜到这竟是让 AI 干活最有效的方式……

---

## 核心观点

1. **用"AI 让不可能成为可能"重构作业**：Mollick 把沃顿创业课的第一项作业改成"野心放大到不可能"——不会编程也要承诺做出能跑的应用；失败不罚，过于雄心勃勃反而安全。作业流程：让 AI 给出项目失败的 10 种方式 + 成功图景，再请三位名人（企业家/领袖/艺术家/哲学家）用他们自己的口吻批评计划。
2. **课堂的两极分化**：以论文写作为主的课程将"回归十九世纪"（课堂手写蓝色考卷），而实践型课堂则"奔向未来"（学生每天完成不可能）。AI 没有统一地改变教育，而是按学科性质把教育撕成两半。
3. **真正的大问题：该教什么**：连慢机构都承认 AI 教学的重要性（美国教育部在 ChatGPT 发布数月内即表态）；更进一步的共识是从"教知识"转向"教与 AI 协作"——基础 AI 素养（AI literacy）+ 提示词工程（prompt engineering）。
4. **"AI 语者"泡沫与提示词工程的真相**：2023 年六位数年薪催生课程/教程/YouTube 发财产业链；Mollick 泼冷水——提示词工程是有用的近期技能，但并不复杂，"读到这里你已足够当一名好的提示词工程师"，因为它的原理就是已讲过的共智原则。
5. **默认输出为何泛泛**：LLM 预测下一个词，倾向遵循训练语料中的常见模式；打破模式的最简单方法是提供背景与约束（context and constraints，第 5 章的方法论）。
6. **"用散文编程"（programming in prose）**：进阶提示 = 给指令，AI"大体上"遵循——但有随机性，没有程序般的一致性，所以提示要清晰、合乎逻辑。
7. **思维链提示（chain-of-thought prompting）与逐步分解**：先给推理范例再提请求；或给出层层递进的逐步指令——好处是每步输出可检查、提示词可迭代、整体更准确。
8. **实例教学：节拍器 vs GPS**：单句索要只能得到"节拍器"式的平庸类比；步骤化提示（列清单→批评补充→做对比表→择优解释）让 GPT-4 给出"GPS 导航"的完整类比——质量差异来自提示结构而非模型能力。
9. **收尾金句**：提示词工程与其是科学不如是艺术——谷歌最强模型对"深呼吸，一步一步来"反应最好；AI 不会呼吸也不会惊慌，却最吃这套——再次印证 AI"像人不像软件"。

---

## 金句

1. "Make what you are planning on doing ambitious to the point of impossible; you are going to be using AI... I won't penalize you for failing if you are too ambitious."
   —— "把你们计划要做的事情，野心放大到不可能的程度；因为你们将会使用 AI……如果你因为过于雄心勃勃而失败，我不会因此扣你的分。"
2. "However, all of this remains much less a science than an art, and AIs still work more like people than software."
   —— "然而，尽管如此，这一切与其说是一门科学，不如说是一门艺术，AI 的运作方式仍然更像人而非软件。"
