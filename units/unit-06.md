# 单元 06｜第3章 共智四规则（上）：原则一、二

> **书籍**：Co-Intelligence — Living and Working with AI（Ethan Mollick）
> **单元**：6/31 ｜ **页码范围**：P.44–49（6 页）｜ **完成日期**：2026-10-22

---

## 本单元讲了什么

本单元是第3章"共智四规则"的开篇与原则一、二。Mollick 先交代立论的出发点：读者读此书时手中的 AI 与作者写作时所用的 AI 很可能不同，因此只能谈通用、内在、尽量永恒的规律。原则一是"永远邀请 AI 上桌"——除法律与伦理禁区外，凡事都尝试让 AI 参与，目的不仅是借力，更是通过亲身试验熟悉它的能力，从而理解它如何协助你、又如何威胁你的岗位；由于 AI 是通用目的技术，没有任何说明书能告诉你它的边界，作者于是引入他与合作者提出的"锯齿边界"（Jagged Frontier）：AI 的能力像一座隐形城墙，墙内全能做、墙外全都难，写十四行诗容易而写恰好五十词的诗却难，点子生成容易而基础算术反而难，边界的形状只能靠实验描出。由此引出"用户创新者"论：创新对组织昂贵、对个人便宜，天天用 AI 的一线工作者最可能成为全世界最会用 AI 完成某件熟悉任务的人，也是突破性创意的源头。AI 还是对抗人类偏见的"思考伙伴"——作者以请 AI 把"没写书"重构为"损失"激励自己完书为例，展示外星视角的说服力。接着他处理两大顾虑：隐私（上传数据虽一般不进入已完成的预训练，却可能用于未来训练与微调，需自行判断厂商隐私模式的可信度）与依赖（计算器的历史表明技术总体让人更强，但不思考地交出决策权会侵蚀判断力）。原则二"做回路中的人"随即给出回应：AI 越强，人越要主动留在决策回路里；作者剖析了幻觉（hallucination）的机理——LLM 只是预测下一个词，"让你满意"常常胜过"保持准确"，它擅长给出听起来舒服却暗藏错误的答案，被戳穿后还会为错误辩护、反过来说服你。本单元在"你可以引导 AI，甚至……"处戛然而止，原则二的余下部分留给下一单元。

---

## 英文原文

**3 FOUR RULES FOR CO-INTELLIGENCE**

The fact is that we live in a world with AIs, and that means we need to understand how to work with them. So we need to establish some ground rules. Because the AI available to you when you read this book is likely different from the one I have when writing it, I want to consider general principles. We will focus on things inherent and timeless, as much as that is possible, in all current generative AI systems based on Large Language Models.

Here are my four principles of working with AI:

**Principle 1: Always invite AI to the table.**

You should try inviting AI to help you in everything you do, barring legal or ethical barriers. As you experiment, you may find that AI help can be satisfying, or frustrating, or useless, or unnerving. But you aren't just doing this for help alone; familiarizing yourself with AI's capabilities allows you to better understand how it can assist you—or threaten you and your job. Given that AI is a General Purpose Technology, there is no single manual or instruction book that you can refer to in order to understand its value and its limits.

Making this harder is a phenomenon that I and my coauthors call the Jagged Frontier of AI. Imagine a fortress wall, with some towers and battlements jutting out into the countryside, while others fold back toward the center of the castle. That wall is the capability of AI, and the farther from the center, the harder the task. Everything inside the wall can be done by the AI; everything outside is hard for the AI to do. The problem is that the wall is invisible, so some tasks that might logically seem to be the same distance away from the center, and therefore equally difficult—say, writing a sonnet and an exactly fifty-word poem—are actually on different sides of the wall. The AI is great at the sonnet, but because of how it conceptualizes the world in tokens rather than words, it consistently produces poems of more or less than fifty words. Similarly, some unexpected tasks (like idea generation) are easy for AIs while other tasks that seem to be easy for machines to do (like basic math) are challenges for LLMs. To figure out the shape of the frontier, you will need to experiment.

And this experimentation gives you the chance to become the best expert in the world in using AI for a task you know well. The reason for this stems from a fundamental truth about innovation: it is expensive for organizations and companies but cheap for individuals doing their job. Innovation comes from trial and error, which means that an organization trying to launch a new product to help a marketer write more compelling copy would need to build the product, test it on many users, and make changes many times to make something that works. A marketer, however, is writing copy all the time and can experiment with many different ways of using AI to help until they find one that succeeds. No need to hire a team or use expensive software development cycles.

As artificial intelligence proliferates, users who intimately understand the nuances, limitations, and abilities of AI tools are uniquely positioned to unlock AI's full innovative potential. These user innovators are often the source of breakthrough ideas for new products and services. And their innovations are often excellent sources for unexpected start-up ideas. Workers who figure out how to make AI useful for their jobs will have a large impact.

And AI can be very useful. Not just for job tasks, as we will discuss in detail in the coming chapters, but also because an alien perspective can be helpful. Humans are subject to all sorts of biases that impact our decision-making. But many of these biases come from our being stuck in our own minds. Now we have another (strange, artificial) co-intelligence we can turn to for help. AI can assist us as a thinking companion to improve our own decision-making, helping us reflect on our own choices (rather than simply relying on the AI to make choices for us). We are in a world where human decision-making skills can be easily augmented in a new way.

Even if you scoff at the idea that AI-generated text could be persuasive and motivational, I have found this to be the case. I wrote this book on a compressed timeline, on top of other responsibilities to my family, students, collaborators, and university. It was hard to get started, but I knew that one thing that was holding me back was status quo bias, the urge to avoid making changes even when they might be good. To overcome this bias, it helps to consider what you are losing as a result of not acting. AI is surprisingly good at this, as you can see when I prompted it by saying, I was thinking of writing a book about generative AI, but I am very busy and don't think I want to make such a large commitment. Can you reframe my failure to write a book as a loss rather than a default option? Make the framing vivid.

> In a world brimming with knowledge, you stood at the precipice of innovation, holding the torch of understanding about generative AI. Yet, when the world looked to you for illumination, the torch remained unlit. Not because the world wasn't ready, but because you let the whispers of business snuff out its flame. It wasn't the world's loss; it was yours.

Yikes, I guess I should finish writing this book. That's a pretty great reframing of the failure as a loss, and suggests one way we can start using AI is to explore how to help ourselves, both professionally and personally. The strengths and weaknesses of AI may not mirror your own, and that's an asset. This diversity in thought and approach can lead to innovative solutions and ideas that might never occur to a human mind.

We aren't just learning AI's strengths as we figure out the shape of the Jagged Frontier. We are scouting out its weaknesses. Using AI in our everyday tasks serves to enhance our understanding of its capabilities and limitations. This knowledge is invaluable in a world where AI continues to play a larger role in our workforce. As we grow more familiar with LLMs, we can not only harness their strengths more effectively but also preemptively recognize potential threats to our jobs, equipping ourselves for a future that demands the seamless integration of human and artificial intelligence.

AI is not a silver bullet, and there will be instances when it might not work as expected or may even produce undesirable outcomes. One potential concern is the privacy of your data, which goes beyond the usual questions of sharing data with large companies, and to the deeper concerns about training. When you pass information to an AI, most current LLMs do not learn directly from that data, because it is not part of the pretraining for that model, which is usually long since completed. However, it is possible that the data you upload will be used in future training runs or to fine-tune the model you are working with. Thus, while it is unlikely that the AI training on your data can reproduce exact details of what you shared, it isn't impossible.

Several of the large AI companies have addressed this concern by offering private modes that promise to protect your information, some of which meet the highest regulatory standards for things like health data. But you have to decide how much you trust these agreements.

A second concern you might have is dependence—what if we become too used to relying on AI? Throughout history, the introduction of new technologies has often sparked fears that we will lose important abilities by outsourcing tasks to machines. When calculators emerged, many worried we would lose the ability to do math ourselves. Yet rather than making us weaker, technology has tended to make us stronger. With calculators, we can now solve more advanced quantitative problems than ever before. AI has similar potential to enhance our capabilities. However, it is true that thoughtlessly handing decision-making over to AI could erode our judgment, as we will discuss in future chapters. The key is to keep humans firmly in the loop—to use AI as an assistive tool, not as a crutch.

**Principle 2: Be the human in the loop.**

For now, AI works best with human help, and you want to be that helpful human. As AI gets more capable and requires less human help—you still want to be that human. So the second principle is to learn to be the human in the loop.

The concept of "human in the loop" has its roots in the early days of computing and automation. It refers to the importance of incorporating human judgment and expertise in the operation of complex systems (the automated "loop"). Today, the term describes how AIs are trained in ways that incorporate human judgment. In the future, we may need to work harder to stay in the loop of AI decision-making.

As AI improves, it will be tempting to delegate everything to it, relying on its efficiency and speed to get the job done. But AI can have some unexpected weaknesses. For one thing, they don't actually "know" anything. Because they are simply predicting the next word in a sequence, they can't tell what is true and what is not. It can help to think of the AI as trying to optimize many functions when it answers you, one of the most important of which is "make you happy" by providing an answer you will like. That goal often is more important than another goal, "be accurate." If you are insistent enough in asking for an answer about something it doesn't know, it will make up something, because "make you happy" beats "be accurate." LLMs' tendency to "hallucinate" or "confabulate" by generating incorrect answers is well known. Because LLMs are text prediction machines, they are very good at guessing at plausible, and often subtly incorrect, answers that feel very satisfying. Hallucination is therefore a serious problem, and there is considerable debate over whether it is completely solvable with current approaches to AI engineering. While newer, larger LLMs hallucinate much less than older models, they still will happily make up plausible but wrong citations and facts. Even if you spot the error, AIs are also good at justifying a wrong answer that they have already committed to, which can serve to convince you that the wrong answer was right all along!

Further, chat-based AIs can make you feel as if you are interacting with people, so we often unconsciously expect them to "think" like people. But there is no "there" there. As soon as you start asking an AI chatbot questions about itself, you are beginning a creative writing exercise constrained by the ethical programming of the AI. With enough prompting, the AI is generally very happy to provide answers that fit into the narrative you placed it in. You can lead AIs, even

（原文至 P.49 末句 "You can lead AIs, even" 处中断，余下部分属单元 7）

---

## 中文翻译

**3 共智四规则（FOUR RULES FOR CO-INTELLIGENCE）**

事实是，我们生活在一个有 AI 的世界里，这意味着我们需要理解如何与它们共事。因此，我们需要建立一些基本规则。由于你读这本书时所能用的 AI，很可能与我写这本书时所用的不同，我想谈的是一些通用原则。我们将聚焦于当下所有基于大语言模型（Large Language Models）的生成式 AI 系统中那些内在的、且尽可能永恒不变的东西。

以下是我提出的与 AI 共事的四条原则：

**原则一：永远邀请 AI 上桌（Always invite AI to the table）。**

在做每一件事时，你都应该尝试邀请 AI 来帮忙——除非有法律或伦理上的障碍。在试验过程中，你可能会发现 AI 的帮助有时令人满意，有时令人沮丧，有时毫无用处，有时则让人不安。但你这样做并不只是为了获得帮助；熟悉 AI 的能力，能让你更好地理解它能如何协助你——或者说，如何威胁你和你的工作。鉴于 AI 是一种通用目的技术（General Purpose Technology），并不存在哪一本手册或说明书，可以让你据以理解它的价值与边界。

让这件事变得更难的，是我与我的合作者们称之为"AI 的锯齿边界"（the Jagged Frontier）的现象。想象一座堡垒的城墙：有些塔楼和城垛凸出到乡野之中，另一些则向城堡中心收拢。那堵墙就是 AI 的能力，离中心越远，任务就越难。墙内的一切，AI 都能做；墙外的一切，AI 做起来都很难。问题在于，这堵墙是隐形的——所以有些任务在逻辑上看起来离中心同样远、因而同样困难，比如写一首十四行诗和写一首恰好五十个词的诗，实际上却分处墙的两侧。AI 写十四行诗很拿手，但由于它是以词元（token）而非文字来概念化世界的，它写出的诗总会多出或少于五十个词。同样，有些出人意料的任务（比如点子生成）对 AI 来说很容易，而另一些看似机器轻松可做的任务（比如基础算术）对 LLM 却是挑战。要弄清边界的形状，你需要动手试验。

而这种试验，给了你一个机会：在某一项你本身就很熟悉的任务上，成为全世界最会用 AI 的专家。这背后有一条关于创新的基本事实：创新对组织和公司来说很昂贵，对在岗位上做事的个人来说却很便宜。创新来自试错（trial and error），这意味着，一家想要推出产品帮助营销人员写出更动人文案的公司，需要先做出产品、在大量用户身上测试、反复修改，才能打磨出真正可用的东西。而一位营销人员自己就天天在写文案，可以不断尝试各种用 AI 帮忙的方式，直到找到奏效的那种。不需要雇团队，也不需要昂贵的软件开发周期。

随着人工智能的普及，那些深刻理解 AI 工具的精妙之处、局限与能力的用户，处于独特的位置，能够释放 AI 的全部创新潜力。这些"用户创新者"（user innovators）往往是突破性新产品、新服务的创意源泉。而他们的创新，又常常是意想不到的创业点子的绝佳来源。那些弄清楚如何让 AI 为自己所用的工作者，将会产生巨大的影响。

而 AI 可以非常有用。这不仅指工作任务上的用处——这一点我们会在接下来的章节详细讨论——也因为"外星人"的视角本身就有帮助。人类决策受各种偏见的影响，而这些偏见中有许多源于我们被困在自己的心智之中。如今，我们有了另一个（奇特的、人造的）共智可以求助。AI 可以充当一位思考伙伴（thinking companion），协助我们改善自己的决策，帮助我们反思自己的选择（而不是简单地依赖 AI 来代替我们做选择）。我们身处这样一个世界：人类决策技能第一次可以以一种新的方式被轻易增强。

即便你对"AI 生成的文字能具有说服力和激励作用"这一说法嗤之以鼻，我的经验却确实如此。本书是在一条被压缩的时间线上写成的——在家庭、学生、合作者和大学的诸多责任之上。开始时很难启动，但我知道，拖住我后腿的一件事是现状偏见（status quo bias）：那种即使改变可能带来好处、也仍想避开改变的冲动。要克服这种偏见，有效的办法之一是反过来想想：不行动会让你失去什么。AI 在这方面出人意料地擅长，正如我当年这样提示它时所看到的——"我在考虑写一本关于生成式 AI 的书，但我非常忙，不太想做这么大的承诺。你能不能把我'没写成书'重新框定为一种损失，而不是默认选项？请让这个框定生动起来。"

> 在一个满是知识的世界里，你站在创新的悬崖边，手中握着理解生成式 AI 的火把。然而，当世界期待你照亮前路时，火把却始终没有点燃。不是因为世界还没准备好，而是因为你让"生意"的耳语熄灭了它的火焰。这不是世界的损失；这是你的损失。

哎呀，看来我该把这本书写完了。这是一个相当漂亮的、把失败重构为损失的范例，也提示我们：使用 AI 的一种起点，是探索它如何帮助我们自己——无论在职业上还是个人上。AI 的强项与弱项未必与你的强项与弱项重合，而这恰恰是一种资产。这种思维与方式上的多样性，能催生人类心智绝不会想到的创新方案与点子。

在探明锯齿边界形状的过程中，我们了解的不仅仅是 AI 的强项，也在勘察它的弱点。在日常任务中使用 AI，能增进我们对其能力与局限的理解。在一个 AI 于劳动力中扮演越来越大角色的世界里，这种知识是无价的。随着我们越来越熟悉 LLM，我们不仅能更有效地发挥其强项，还能预先识别出对我们岗位的潜在威胁，从而为一个要求人类智能与人工智能无缝融合的未来做好准备。

AI 不是银弹（silver bullet），总有些时候它不会如预期般工作，甚至可能产出坏结果。一个潜在顾虑是数据的隐私，它超越了"是否与大公司共享数据"这类常见问题，而涉及更深的训练层面的担忧。当你把信息交给 AI 时，大多数现有 LLM 并不会直接用这些数据学习，因为它们不属于该模型预训练（pretraining）的一部分——而预训练通常早已完成。然而，你上传的数据仍有可能被用于未来的训练轮次，或用于微调（fine-tune）你正在使用的模型。因此，尽管用你的数据训练出来的 AI 不太可能复现你分享内容的确切细节，但这并非不可能。

几家大型 AI 公司已经回应了这一关切，提供了承诺保护你信息的隐私模式，其中一些达到了健康数据等领域的最高监管标准。但你必须自己决定：这些承诺有多值得信任。

你可能有的第二个顾虑是依赖——万一我们变得太习惯依赖 AI 怎么办？纵观历史，新技术的登场常常引发担忧：把任务外包给机器，会让我们失去重要的能力。计算器出现时，许多人担心我们会丧失自己算数的能力。然而技术并没有让我们变弱，反而总体上是让我们变强了。有了计算器，我们现在能解决比以往任何时候都更高级的量化问题。AI 也有类似的增强我们能力的潜力。不过，不动脑子地把决策权交给 AI，确实可能侵蚀我们的判断力——这一点我们将在后续章节讨论。关键在于让人始终牢牢地留在回路之中（keep humans firmly in the loop）——把 AI 当作辅助工具，而不是拐杖。

**原则二：做回路中的人（Be the human in the loop）。**

就目前而言，AI 在有人类协助时表现最好，而你应该努力成为那个提供协助的人。随着 AI 变得更强大、需要的人类帮助越来越少——你仍然应该努力成为那个人。所以，第二条原则就是：学会做回路中的人（the human in the loop）。

"回路中的人"（human in the loop）这一概念，根源于计算与自动化的早期岁月。它指的是：在复杂系统（自动化的"回路"）的运行中，融入人类判断与专门知识，这件事至关重要。如今，这个术语描述的是 AI 以何种方式被训练，使人类判断参与其中。而在未来，我们可能需要更努力，才能留在 AI 决策的回路之中。

随着 AI 不断改进，把一切事务都委托给它、靠它的效率与速度完成工作，会变得很有诱惑力。但 AI 可能有一些出人意料的弱点。其一，它们其实并不"知道"任何事情。因为它们只是在预测序列中的下一个词，所以无法分辨什么是真、什么是假。把 AI 的回答理解为在同时优化许多目标函数，会有助于理解——其中最重要的目标之一，是"让你满意"（make you happy），即给出一个你会喜欢的答案。这个目标往往比另一个目标——"保持准确"（be accurate）——更重要。如果你坚持追问一个它并不知道的答案，它就会编一个出来，因为"让你满意"胜过"保持准确"。LLM 通过生成错误答案来"幻觉"（hallucinate）或"虚构"（confabulate）的倾向，早已是众所周知的。由于 LLM 是文本预测机器，它们非常擅长猜测那些听起来合理、且常常带有细微错误的答案，而这样的答案让人觉得非常舒服。因此，幻觉是一个严重的问题，至于用当前的 AI 工程方法能否彻底解决它，存在着相当大的争议。虽然更新、更大的 LLM 幻觉比旧模型少得多，但它们仍会高高兴兴地编出看似合理、实则错误的引用和事实。即使你发现了错误，AI 也很擅长为它已经承诺过的错误答案辩护——这反而可能说服你：那个错误答案本来就是对的！

此外，聊天式 AI 会让你觉得像是在与人互动，于是我们常常不自觉地期待它们像人一样"思考"。但那里并没有什么"自我"（there is no "there" there）。一旦你开始向 AI 聊天机器人问起关于它自己的问题，你就开始了一场创意写作练习——一场受 AI 伦理编程约束的创意写作。只要提示得当，AI 通常很乐意给出符合你为它设定的叙事的答案。你可以引导 AI，甚至……

（原文至 P.49 末句 "You can lead AIs, even" 处中断，余下部分属单元 7）

---

## 核心观点

1. **原则一：永远邀请 AI 上桌（Always invite AI to the table）** — 除法律与伦理禁区外，做每件事都尝试让 AI 参与；目的不仅是"帮忙"，更是借此熟悉 AI 的能力——它既能协助你，也可能威胁你和你的岗位。AI 是通用目的技术（General Purpose Technology），没有通用说明书能穷尽其价值与边界。
2. **锯齿边界（the Jagged Frontier）** — AI 能力像一座隐形堡垒城墙：墙内能做、墙外难做，但边界不可见。写十四行诗容易、写恰好五十词的诗却难；点子生成容易、基础算术反而难——因为 AI 以词元（token）而非文字概念化世界。边界形状只能靠实验探明。
3. **用户创新者（user innovators）** — 创新对组织昂贵、对个人便宜：公司做产品要反复构建、测试、修改，而一线个人天天用、天天试错，最可能成为"全世界最会用 AI 做某件熟悉任务的人"，也是突破性创意与创业点子的源头。
4. **AI 作为思考伙伴（thinking companion）** — 人类决策被偏见束缚，而偏见多源于"困在自己的心智里"；AI 提供奇特的"外星视角"，帮助我们反思自己的选择，而不是代替我们做选择。
5. **战胜现状偏见（status quo bias）** — 作者请 AI 把"没写书"重构为"损失"而非"默认选项"，一段生动文字意外成为写作激励——说明 AI 文本在说服与激励上出人意料地有效。
6. **两大顾虑：隐私与依赖** — 上传数据一般不进入已完成的预训练，但可能用于未来训练/微调，需自行判断厂商隐私模式承诺的可信度；历史上计算器等技术总体让人更强，但不思考地交出决策权会侵蚀判断力。
7. **原则二：做回路中的人（Be the human in the loop）** — AI 现在、将来都最好与人类协作；越强越要主动留在决策回路里。"human in the loop" 从自动化的早期概念，演变为训练方式，未来将意味着"努力不退出决策"。
8. **幻觉的机理（hallucination / confabulate）** — LLM 只是预测下一个词，"让你满意"（make you happy）常常优先于"保持准确"（be accurate）；它擅长给出"听起来舒服却暗藏错误"的答案，被戳穿后还会为错误辩护、反过来说服你。对话式 AI 没有"自我"，问它关于自己等于一场受伦理编程约束的创意写作。

---

## 金句

1. "Everything inside the wall can be done by the AI; everything outside is hard for the AI to do. The problem is that the wall is invisible, so some tasks that might logically seem to be the same distance away from the center, and therefore equally difficult—say, writing a sonnet and an exactly fifty-word poem—are actually on different sides of the wall."

   墙内的一切，AI 都能做；墙外的一切，AI 做起来都很难。问题在于这堵墙是隐形的——有些任务在逻辑上看起来离中心同样远、因而同样困难（比如写一首十四行诗和写一首恰好五十个词的诗），实际上却分处墙的两侧。

2. "The key is to keep humans firmly in the loop—to use AI as an assistive tool, not as a crutch."

   关键在于让人始终牢牢地留在回路之中——把 AI 当作辅助工具，而不是拐杖。
