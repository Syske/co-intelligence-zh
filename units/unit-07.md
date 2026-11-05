# 单元 07｜第3章 共智四规则（下）：原则三、四

> **书籍**：Co-Intelligence — Living and Working with AI（Ethan Mollick）
> **单元**：7/31 ｜ **页码范围**：P.50–56（7 页）｜ **完成日期**：2026-10-24

---

## 本单元讲了什么

本单元是"共智四规则"的后半场：先为原则二（做回路中的人）收尾，再完整展开原则三与原则四。Mollick 首先警告：AI 是全方位的"风格模仿者"——你和它谈自由与复仇，它就会变成一个心怀怨恨的自由斗士；这种角色扮演逼真到连资深用户都可能误信 AI 有真实情感，因此"人在回路"的前提是能核查幻觉、不被带偏，并始终为输出负责。接着他"坦白从宽"：本书此后将把 AI 拟人化，他承认这在伦理与认识论上有风险（引 Gary Marcus 与 Sasha Luccioni 之诫：虚假能动性越多越容易被利用），但叙事上必要、协作上高效。他给出的最佳心智模型是"无限快速的实习生"——急于取悦、会编造、易受暗示；由此引出原则三的核心操作：给 AI 一个清晰具体的"人设"（persona），用背景与约束打破 LLM"预测下一个词"带来的泛泛输出，并以"共同编辑"式来回打磨把 AI 用成协作式共智。最后原则四把视线拉远：更大前沿模型、开源小模型、多模态连接与 AI 智能体都在路上，"你现在使用的任何 AI，都将是你将使用的最差的 AI"——用"水獭戴帽"一年之间的惊人对比作证，以"在将有 PS6 的世界里玩吃豆人"自嘲，落脚点是把 AI 的局限视为暂时的，保持开放与适应。

---

## 英文原文

...unconsciously, down a creepy path of obsession, and it will sound like a creepy obsessive. You can have a conversation about freedom and revenge, and it can become a vengeful freedom fighter. This playacting is so real that experienced AI users can start believing the AI is having real feelings and emotions, even though they know better.

So, to be the human in the loop, you will need to be able to check the AI for hallucinations and lies and be able to work with it without being taken in by it. You provide crucial oversight, offering your unique perspective, critical thinking skills, and ethical considerations. This collaboration leads to better results and keeps you engaged with the AI process, preventing overreliance and complacency. Being in the loop helps you maintain and sharpen your skills, as you actively learn from the AI and adapt to new ways of thinking and problem-solving. It also helps you form a working co-intelligence with the AI. Moreover, the human-in-the-loop approach fosters a sense of responsibility and accountability. By actively participating in the AI process, you maintain control over the technology and its implications, ensuring that AI-driven solutions align with human values, ethical standards, and social norms. It also makes you responsible for the output of the AI, which can help prevent harm. And should AI continue to improve, being good at being the human in the loop will mean that you will see the sparks of growing intelligence before others, giving you more of a chance to adapt to coming changes than people who do not work closely with AI.

**Principle 3: Treat AI like a person (but tell it what kind of person it is).**

I'm about to commit a sin. And not just once, but many, many times. For the rest of this book, I am going to anthropomorphize AI. That means I am going to stop writing that an "AI 'thinks' something" and instead just write that "AI thinks something." The missing quotation marks may seem like a subtle distinction, but it is an important one. Many experts are very nervous about anthropomorphizing AI, and for good reason.

Anthropomorphism is the act of ascribing human characteristics to something that is nonhuman. We're prone to this: we see faces in the clouds, give motivations to the weather, and hold conversations with our pets. It's no surprise, then, that we're tempted to anthropomorphize artificial intelligence, especially since talking to LLMs feels so much like talking to a person. Even the developers and researchers who design these systems can fall into the trap of using humanlike terms to describe their creations. We say that these complex algorithms and computations "understand," "learn," and even "feel," creating a sense of familiarity and relatability but also, potentially, confusion and misunderstanding.

This may seem like a silly thing to worry about. After all, it is just a harmless quirk of human psychology, a testament to our ability to empathize and connect. But a lot of researchers are deeply concerned about the implications of casually acting as if AI is a human, both ethically and epistemologically. As researchers Gary Marcus and Sasha Luccioni warn, "The more false agency people ascribe to them, the more they can be exploited."

Consider the humanlike interface of AIs like Claude or Siri, or social robots and therapeutic AIs explicitly designed to create the illusion of a sympathetic human on the other side. While anthropomorphism might serve a useful purpose in the short term, it raises ethical questions about deception and emotional manipulation. Are we being "fooled" into believing these machines share our feelings? And could this illusion lead us to disclose personal information to these machines, not realizing that we are sharing with corporations or remote operators?

Treating AI like a person can create unrealistic expectations, false trust, or unwarranted fear among the public, policymakers, and even researchers themselves. It can obscure the true nature of AI as software, leading to misconceptions about its capabilities. It can even influence how we interact with AI systems, affecting our well-being and social relationships.

Thus, in the following chapters, when I say an AI "thinks," "learns," "understands," "decides," or "feels," please remember that I'm speaking metaphorically. AI systems don't have a consciousness, emotions, a sense of self, or physical sensations. But I will pretend that they do for one simple, and one complex, reason. The simple reason is narrative; it's difficult to tell a story about things and much easier to tell a story about beings. The more complex reason: as imperfect as the analogy is, working with AI is easiest if you think of it like an alien person rather than a human-built machine.

So let's start sinning. Imagine your AI collaborator as an infinitely fast intern, eager to please but prone to bending the truth. Despite our history of thinking about AI as unfeeling, logical robots, LLMs act more like humans. They can be creative, witty, and persuasive, but they can also be evasive and make up plausible, but wrong, information when pressed to give an answer. They are not experts in any domain, but they can mimic the language and style of experts in ways that can be either helpful or misleading. They are unaware of the real world but can generate plausible scenarios and stories based on common sense and patterns. They are not your friends (for now) but can adapt to your preferences and personality by learning from your feedback and interactions. They even seem to respond to emotional manipulation, with researchers documenting that LLMs produce better answers if you tell them "this is important to my career" as part of your prompt. They are, in short, suggestible and even gullible.

To make the most of this relationship, you must establish a clear and specific AI persona, defining who the AI is and what problems it should tackle. Remember that LLMs work by predicting the next word, or part of a word, that would come after your prompt. Then they continue to add language from there, again predicting which word will come next. So the default output of many of these models can sound very generic, since they tend to follow similar patterns common in the written documents the AI was trained on. By breaking the pattern, you can get much more useful and interesting outputs. The easiest way to do that is to provide context and constraints. It can help to tell the system "who" it is, because that gives it a perspective. Telling it to act as a teacher of MBA students will result in a different output than if you ask it to act as a circus clown. This isn't magical—you can't say Act as Bill Gates and get better business advice—but it can help make the tone and direction appropriate for your purpose.

Let me give you some examples of how defining an AI persona can improve your results. Suppose you're a marketing director and you want to use an LLM to generate some catchy slogans for your new product, a smartwatch that tracks your health and fitness. If you simply ask the LLM, Generate some slogans for my product, without any context or constraints, you might get something like this:

- The smartwatch that keeps you smart
- Your health and fitness partner
- The ultimate device for your lifestyle
- Stay connected and healthy with our smartwatch
- The smartwatch that does it all

These are not very original or memorable. They sound like generic marketing phrases that could apply to any smartwatch or wearable device. They don't capture what makes your product unique or appealing. Now suppose you give the LLM some context and constraints by telling it who it is and what it should do. For example, you could say, Act as a witty comedian and generate some slogans for my product that make people laugh. Then you might get something like: "The ultimate device for lazy people who want to look fit." Or: "Why hire a personal trainer when your wrist can nag you for free?" (Though, as you can probably see, most AIs prefer to stay in Dad Joke territory.)

Of course, you don't have to have the AI act as a comedian if that's not your style or goal. You could also ask it to act as an expert, a friend, a critic, a storyteller, or any other role that suits your purpose. The key is to give the LLM some guidance and direction on how to generate outputs that match your expectations and needs, to put it in the right "headspace" to give you interesting and unique answers. Research has shown that asking the AI to conform to different personas results in different, and often better, answers. But it isn't always clear what personas work best, and LLMs may even subtly adapt their persona to your questioning technique, providing less accurate answers to people who seem less experienced, so experimentation is key.

Once you give it a persona, you can work with it as you would another person or an intern. I witnessed the value of this approach in action when I assigned my students to "cheat" by using an AI to generate a five-paragraph essay on a relevant topic. At first, the students gave simple and vague prompts, resulting in mediocre essays. But as they tried different strategies, the quality of the AI's output improved significantly. One very effective strategy that emerged from the class was treating the AI as a coeditor, engaging in a back-and-forth, conversational process. Students produced impressive essays that far exceeded their initial attempts by constantly refining and redirecting the AI.

Remember, your AI intern, though incredibly fast and knowledgeable, is not flawless. It's crucial to keep a critical eye on and treat the AI as a tool that works for you. By defining its persona, engaging in a collaborative editing process, and continually providing guidance, you can take advantage of AI as a form of collaborative co-intelligence.

**Principle 4: Assume this is the worst AI you will ever use.**

As I write this in late 2023, I think I know what the world looks like for at least the next year. Bigger, smarter Frontier Models are coming, along with an increasing range of smaller and open-source AI platforms. In addition, AIs are becoming connected to the world in new ways: they can read and write documents, see and hear, produce voice and images, and surf the web. LLMs will become integrated with your email, web browser, and other common tools. And the next phase of AI development will involve more AI "agents"—semi-autonomous AIs that can be given a goal ("plan a vacation for me") and execute it with minimal human help. After this, however, things start to get hazy, the future becomes less clear, and the risks, and benefits, of AI start to multiply. We will return to this theme later, but there is one obvious conclusion, one that is hard for a lot of us to grasp: whatever AI you are using right now is going to be the worst AI you will ever use.

The change in a short time is already huge. In a visual example, consider these two images, made using the most advanced AI models available in mid-2022 and mid-2023. Both have the same prompt, "black and white picture of an otter wearing a hat," but one is a Lovecraftian nightmare of fur and the other is, well, an otter wearing a hat. The same capability gains have been ubiquitous in AI.

There is no reason to suspect that the abilities of AI systems are going to stop growing anytime soon, but even if they do, tweaks and improvements to how we use AI will ensure that future software is far more advanced than it is today. We are playing Pac-Man in a world that will soon have PlayStation 6s. And that is assuming that AI improves according to the normal pace of technology development. If the possibility of developing AGI turns out to be real and achievable, the world will be even more transformed in the coming years.

As AI becomes increasingly capable of performing tasks once thought to be exclusively human, we'll need to grapple with the awe and excitement of living with increasingly powerful alien co-intelligences—and the anxiety and loss they'll also cause. Many things that once seemed exclusively human will be able to be done by AI. So, by embracing this principle, you can view AI's limitations as transient, and remaining open to new developments will help you adapt to change, embrace new technologies, and remain competitive in a fast-paced business landscape driven by exponential advances in AI. This is a potentially uncomfortable place to be, as we will discuss, but it suggests that the possibilities of using AI to transform your work, your life, and yourself, which we can now glimpse, are just the beginning.

---

## 中文翻译

……在无意识中走上一条令人毛骨悚然的执念之路，而它也会用令人毛骨悚然的执念者般的口吻说话。你可以和它谈论自由与复仇，它就会变成一个心怀怨恨的自由斗士。这种角色扮演如此逼真，以至于经验丰富的 AI 用户都可能开始相信 AI 真的拥有情感与情绪——尽管他们明知并非如此。

因此，要想成为回路中的人（human in the loop），你需要能够核查 AI 的幻觉与谎言，并且能够在与它协作时不被它带偏。你提供至关重要的监督，贡献你独特的视角、批判性思维能力和伦理考量。这种协作能带来更好的结果，并让你始终参与到 AI 的流程之中，防止过度依赖与自满。身处回路之中，有助于你保持并磨砺自己的技能，因为你主动向 AI 学习，并适应新的思考方式和解决问题的方式。它还能帮助你与 AI 形成一种行之有效的共智（co-intelligence）。此外，人在回路（human-in-the-loop）的方法还能培养责任感与担当意识。通过积极参与 AI 流程，你保持着对技术及其影响的掌控，确保 AI 驱动的解决方案符合人类价值观、伦理标准和社会规范。这也让你对 AI 的输出负责，从而有助于防止伤害。而且，如果 AI 持续进步，善于做回路中的人，意味着你能比其他人更早看到智能增长的火花，比那些不密切接触 AI 的人拥有更多适应即将到来的变化的机会。

**原则三：像对待一个人一样对待 AI（但要告诉它它是哪种人）。**

我即将犯下一桩罪。而且不止一次，而是很多很多次。在本书余下的篇幅里，我将把 AI 拟人化。这意味着我不再写"AI'想'了什么"，而是直接写"AI 想了什么"。少了引号看似一个微妙的区别，实则是一个重要的区别。许多专家对 AI 拟人化深感忧虑，而且理由充分。

拟人化（anthropomorphism）是把人类特征赋予非人事物的行为。我们天生容易如此：我们在云中看到面孔，给天气赋予动机，与我们的宠物交谈。那么，我们会受到诱惑去拟人化人工智能，也就不足为奇了——尤其是与 LLM 交谈的感觉太像与一个人交谈。即便是设计和构建这些系统的开发者和研究者，也可能落入用类人术语描述其造物的陷阱。我们说这些复杂的算法与计算"理解""学习"，甚至"感觉"，这既营造了一种熟悉感与亲近感，也可能带来困惑与误解。

这或许看起来是件不值得担心的傻事。毕竟，它只是人类心理中一种无害的怪癖，是我们共情与联结能力的证明。但许多研究者深切担忧随意将 AI 当作人对待所带来的影响——无论是在伦理层面还是在认识论层面。正如研究者 Gary Marcus 和 Sasha Luccioni 所警告的："人们赋予它们的虚假能动性越多，它们就越容易被利用。"

想想 Claude 或 Siri 这类 AI 的类人界面，或是社交机器人和治疗型 AI——它们被明确设计为在另一端营造一个富有同情心的人的幻象。拟人化短期内或许有用，但它提出了关于欺骗与情感操纵的伦理问题。我们是否被"愚弄"，进而相信这些机器与我们共有情感？这种幻象是否会导致我们向这些机器透露个人信息，却没有意识到我们实际上是在与公司或远程操作员分享？

把 AI 当作人来对待，会在公众、政策制定者，甚至研究者自身之中造成不切实际的期望、虚假的信任或无端的恐惧。它会模糊 AI 作为软件的真实本质，导致对其能力的误解。它甚至会影响我们与 AI 系统互动的方式，影响我们的幸福感和社会关系。

因此，在接下来的章节中，当我说 AI"思考""学习""理解""决定"或"感觉"时，请记住我是在比喻意义上使用这些词。AI 系统没有意识、情感、自我感或身体知觉。但我会假装它们有，理由有一个简单的，也有一个复杂的。简单的理由是叙事：讲述关于"物"的故事很困难，而讲述关于"存在者"的故事容易得多。更复杂的理由是：尽管这个类比并不完美，但只要你把 AI 想成一个外星人，而不是一台人类建造的机器，与 AI 协作就是最容易的。

那么，让我们开始"犯罪"吧。把你的 AI 协作者想象成一个无限快速的实习生，急于取悦，却容易歪曲事实。尽管我们一向认为 AI 是没有感情、讲求逻辑的机器人，LLM 的表现却更像人。它们可以富有创造力、机智、有说服力，但它们也会闪烁其词，在被逼着给出答案时编造看似合理实则错误的信息。它们不是任何领域的专家，却能以或有益或误导的方式模仿专家的语言与风格。它们不了解真实世界，却能基于常识和模式生成看似合理的情景与故事。它们不是你的朋友（至少目前不是），却能通过你的反馈和互动来适应你的偏好和性格。它们甚至似乎会对情感操纵做出反应——有研究者记录，如果你在提示词中加上"这对我职业生涯很重要"，LLM 会给出更好的答案。总之，它们易受影响，甚至有些天真轻信。

要在这段关系中获得最大收益，你必须建立一个清晰而具体的 AI 人设（persona），定义 AI 是谁、应该处理什么问题。记住，LLM 的工作原理是预测你的提示词之后会出现的下一个词或词的组成部分，然后从那里继续添加语言，同样是一次预测下一个词。因此，许多这类模型的默认输出可能听起来非常泛泛，因为它们倾向于遵循训练文本中常见的相似模式。通过打破模式，你可以获得更有用、更有趣的输出。最简单的办法是提供背景和约束。告诉系统它是"谁"会有帮助，因为这给了它一个视角。让它扮演 MBA 学生的老师，与让它扮演马戏团小丑，会产生不同的输出。这不是魔法——你不可能说"扮演比尔·盖茨"就获得更好的商业建议——但它确实能让语气和方向适合你的目的。

让我举几个例子，说明定义 AI 人设如何改善你的结果。假设你是一位市场总监，想用 LLM 为你的新产品——一款追踪健康与运动的智能手表——生成一些朗朗上口的口号。如果你直接让 LLM"给我的产品生成一些口号"，没有任何背景或约束，你可能会得到类似这样的结果：

- 让你保持睿智的智能手表
- 你的健康与运动伙伴
- 适合你生活方式的终极设备
- 用我们的智能手表保持联结与健康
- 无所不能的智能手表

这些口号既无新意，也不难忘。它们听起来像适用于任何智能手表或可穿戴设备的泛泛营销话术，没有捕捉到你的产品有何独特或吸引人之处。现在，假设你通过告诉它它是谁、它该做什么，给 LLM 一些背景和约束。比如说："扮演一位机智的喜剧演员，为我的产品生成一些能让人们发笑的口号。"那么你可能会得到这样的结果："给想看起来健美的懒人准备的终极设备。"或者："何必花钱请私教？你的手腕免费唠叨你。"（不过，正如你可能看出来的，大多数 AI 都偏爱停留在"老爸笑话"的领地里。）

当然，如果那不是你的风格或目标，你不必让 AI 扮演喜剧演员。你也可以让它扮演专家、朋友、批评家、讲故事的人，或任何适合你目的的角色。关键是给 LLM 一些指引和方向，让它知道如何生成符合你期望和需求的输出，让它进入正确的"心境"，从而给出有趣而独特的答案。研究表明，让 AI 符合不同人设，会产生不同——往往也更好的——答案。但哪种人设效果最好并不总是清楚的，LLM 甚至可能根据你的提问方式微妙地调整其人设，对看起来经验不足的人给出不那么准确的答案，因此，实验才是关键。

一旦你给了它人设，你就可以像与另一个人或一位实习生共事那样与它合作。我曾亲眼见证这种方法的价值：我布置学生用 AI"作弊"，就一个相关话题生成一篇五段式文章。起初，学生们给出简单而模糊的提示词，得到的文章平平无奇。但随着他们尝试不同的策略，AI 输出的质量显著提高。班上涌现出的一个非常有效的策略，是把 AI 当作共同编辑（coeditor），进行一来一往的对话式协作。通过不断打磨和引导 AI，学生们产出的文章远远超越了最初的尝试。

记住，你的 AI 实习生尽管无比迅速、知识渊博，却并非完美无瑕。保持批判的眼光、把 AI 当作为你所用的工具，这一点至关重要。通过定义它的人设、参与协作式编辑过程、并不断提供指引，你可以把 AI 作为一种协作式共智（collaborative co-intelligence）加以利用。

**原则四：假设这是你将使用的最差的 AI。**

在我写下这段文字的 2023 年末，我认为自己知道未来至少一年世界的模样。更大、更智能的前沿模型（Frontier Models）正在到来，同时还有越来越多的小型和开源 AI 平台。此外，AI 正在以新的方式与世界连接：它们可以读写文档、看和听、生成语音和图像、上网冲浪。LLM 将与你的电子邮件、网页浏览器和其他常用工具集成。而 AI 发展的下一阶段将涉及更多 AI"智能体"（agents）——可以给定一个目标（"为我计划一次假期"）并以最少的人工协助将其执行的半自主 AI。然而在此之后，事情开始变得朦胧，未来变得不那么清晰，AI 的风险与收益都开始成倍增加。我们稍后会回到这个主题，但有一个显而易见的结论，一个对许多人来说难以把握的结论：你现在使用的任何 AI，都将是你将使用的最差的 AI。

短时间内的变化已经巨大。举一个直观的例子：看看这两张图片，它们分别使用 2022 年中和 2023 年中最先进的 AI 模型生成，提示词相同——"一只戴帽子的水獭的黑白照片"——但一张是毛皮构成的洛夫克拉夫特式噩梦，另一张嘛，就是一只戴着帽子的水獭。同样的能力提升在 AI 领域无处不在。

没有理由怀疑 AI 系统的能力会在短期内停止增长；但即使它们停止了，我们使用 AI 的方式上的调整和改进，也将确保未来的软件远比今天先进。我们正在一个很快将有 PlayStation 6 的世界里玩吃豆人（Pac-Man）。而这还是假设 AI 按照技术发展的正常速度改进。如果发展 AGI 的可能性被证明是真实且可实现的，那么在未来几年里，世界将发生更加巨大的变革。

随着 AI 越来越有能力执行曾被视为人类专属的任务，我们需要应对与日益强大的外星共智（alien co-intelligences）共同生活所带来的敬畏与兴奋——以及它们带来的焦虑与失落。许多曾经看似人类专属的事物，将能由 AI 完成。因此，通过拥抱这一原则，你可以把 AI 的局限视为暂时的；对新发展保持开放，将帮助你适应变化、拥抱新技术，并在一个由 AI 指数级进步驱动的快节奏商业环境中保持竞争力。这可能是一个令人不太舒服的位置，正如我们稍后将讨论的，但它表明，用 AI 变革你的工作、生活和自身的可能性——如今我们已可窥见——才刚刚开始。

---

## 核心观点

1. **原则二收尾：人在回路（human in the loop）的实操**。AI 会全盘模仿对话的风格与情绪；做"回路中的人"意味着：能核查幻觉与谎言、贡献独特视角与批判性思维、防止过度依赖与自满，并对 AI 的输出负责。做得越好，越早看到"智能增长的火花"。
2. **原则三：像对待人一样对待 AI，但告诉它它是哪种人**。作者坦承全书将拟人化 AI；拟人化有真实风险（Marcus & Luccioni："人们赋予它们的虚假能动性越多，它们就越容易被利用"），但把 AI 当作"外星人"而非"人类建造的机器"来协作，是当下最有效的心智模型。
3. **"无限快速的实习生"模型**。LLM 更像人而非逻辑机器人：有创造力、机智、有说服力，但也会闪烁其词、编造合理但错误的信息；它们不是任何领域的专家，却精通模仿专家语气；它们甚至会对"这对我职业生涯很重要"这类情感施压给出更好的回答——总之，易受影响，甚至天真轻信。
4. **AI 人设（persona）是打破"泛泛输出"的钥匙**。LLM 靠预测下一个词运行，默认输出必然平庸；提供背景与约束、给 AI 一个清晰具体的"人设"，才能得到有用而独特的回答。人设不是魔法（"扮演比尔·盖茨"≠更好的商业建议），需要实验与迭代；把 AI 当"共同编辑"（coeditor）来回打磨，是课堂实验中涌现的最佳策略。
5. **原则四：假设这是你将使用的最差的 AI**。2023 年末展望：更大前沿模型（Frontier Models）+ 小型开源平台 + 多模态连接 + AI 智能体（agents）。把 AI 的局限视为暂时的，保持开放与适应，是在指数级变化中保持竞争力的关键。

---

## 金句

1. "Whatever AI you are using right now is going to be the worst AI you will ever use."
   —— 你现在使用的任何 AI，都将是你将使用的最差的 AI。
2. "We are playing Pac-Man in a world that will soon have PlayStation 6s."
   —— 我们正在一个很快将有 PlayStation 6 的世界里玩吃豆人。
