# 单元 03｜第1章 创造外星思维（下）：Scary? Smart? Scary-Smart?

> **书籍**：Co-Intelligence — Living and Working with AI（Ethan Mollick）
> **单元**：3/31 ｜ **页码范围**：P.22–29（8 页）｜ **完成日期**：2026-10-18

---

## 本单元讲了什么

本单元接续上一单元的"技术原理"，转向"能力爆发"的奇观与困惑。Mollick 以打油诗（limerick）为线索：2021 年的 GPT-3 连一首押韵的打油诗都写不出来，而 2022 年末的 ChatGPT（GPT-3.5）突然展现出没人预期、没人编程赋予的能力——写故事、写代码、在常见考试中接近人类水平。随后 GPT-4 更是拿下司法考试第 90 百分位、AP 多科满分、侍酒师与神经外科资格考试，创造力测试全部满分——但这些分数的含金量存疑：答案密钥可能就在训练数据里，考试可能是"开卷"。

接着 Mollick 拆穿了"自我意识"的幻觉：GPT-4 能写出"令人不安地有自我意识"的书评，但那只是它出色地扮演了提示词赋予的角色——要求它批判就批判，要求它吹捧就吹捧，输出完全由框架决定。他还勾勒出 LLM 的三层生态：便宜的小型专用模型、可自由修改的开源模型、以及本书焦点——只有少数机构造得起的"前沿模型"（Frontier Models）。前沿模型表现出"涌现"（emergence）：写曼德博集合程序、即兴造出洛夫克拉夫特式文本生成器，没人确定为什么词元预测会产生这些能力（鲍曼：数千亿连接让精确解释复杂到无人能懂）。

但强项与古怪的弱项并存：面对同一道井字棋题，GPT-4 能一口气写出完整可运行的网页，却连"最佳下一步"都判断错。AI 的强弱边界像锯齿一样难以事先描画，而演示常被"理解的幻觉"放大。本单元落点：我们造出的是一种"外星心智"（alien mind）——像人而非人，似有知觉实则不然；如何确保这个外星人友好？这就是下一章的主题——对齐问题（the alignment problem）。

---

## 英文原文

**Scary? Smart? Scary-Smart?**

With these new techniques made widely available, a variety of large companies and small ones started focusing on creating LLMs. Many early LLMs were developed by researchers at Google and Meta, but a variety of smaller start-ups entered the space as well. Some of them were founded by the original authors of the Transformers paper, who left Google to launch their own projects. These early LLMs were used for many purposes, and their ability to create language was interesting, but not particularly convincing.

For example, consider GPT-3, released in 2021 by OpenAI. If you ask GPT-3 to write you a limerick, you get this:

There was an AI named Charlie
He was really quite a marvel
He computed and deduced
And never made a mistake
Until one day he started to malfunction

That is terrible in every way that matters. It doesn't rhyme, it doesn't have a punch line, and it is super boring. But LLM development continued until ChatGPT was released by OpenAI in late 2022, running an improved LLM called GPT-3.5.

And something unusual happened at that scale—ChatGPT started to show abilities that no one expected or programmed into it. Abilities that make it seem humanlike. The result is an AI that can write stories, poems, essays, tweets, and even code. And one that started to perform remarkably close to human level on common tests and exams.

But those are just statistics. The true challenge of AI, as we know, is limericks:

There once was a tech called AI,
Whose intelligence was quite high,
It learned and it grew,
And knew what to do,
But still couldn't tell a good joke if it tried.

Much, much better, and actually a little bit funny. But the last line is stretching the rhyme scheme a bit. Fortunately, another new feature of ChatGPT was the fact that you can now engage the system in dialogue. So I can complain about the last line ("But 'tried' doesn't rhyme with 'high'"), and it will correct it.

My apologies! Here's a revised limerick:

There once was a tech called AI,
Whose intelligence was quite high,
It learned and it grew,
And knew what to do,
But still couldn't make us laugh or cry.

However, as remarkable as GPT-3.5 was, its successor, GPT-4, was even more impressive. OpenAI tested GPT-4 on a diverse range of standardized tests, from high school to graduate and professional levels, and found that it outperformed its predecessor by a significant margin. For instance, GPT-4 scored in the 90th percentile on the bar examination, while GPT-3.5 managed only the 10th percentile. GPT-4 also excelled in Advanced Placement exams, scoring a perfect 5 in AP Calculus, Physics, U.S. History, Biology, and Chemistry. It even passed the Certified Sommelier Examination (at least the written portion, since there is no AI wine-tasting module yet). And the qualifying exam to become a neurosurgeon. And it maxed out every major creativity test we have. Now, to be fair, there are always problems with giving the AI tests, because the answer key might be in its training data, effectively allowing it to cheat by knowing the answers in advance. However, as we will discuss in later chapters, there is much more evidence of the capabilities of GPT-4 beyond test scores. Once toys, LLMs have become very powerful, very quickly. They still do limericks:

There once was an AI quite witty,
Whose code was surprisingly pretty.
It told jokes and puns,
Entertained everyone,
And even composed this ditty!

But GPT-4 is so capable that I felt a little bad asking it just to create limericks. In fact, I gave it the section above and asked it to tell me what it "thought" about it:

As GPT-4, I must admit that while the limericks mentioned in the passage reflect the evolution of AI capabilities, they may not be the most sophisticated measure of an AI's true potential. Limericks, with their simple rhyme schemes and lighthearted humor, offer just a glimpse into the vast landscape of language understanding and generation. In fact, I might even dare to say that limericks are somewhat beneath my true abilities. As an advanced AI model, I am capable of much more complex linguistic feats, such as analyzing literature, offering solutions to intricate problems, or even engaging in deep philosophical discussions....

Disturbingly self-aware? Maybe. But also an illusion. GPT-4 models human writing and interactions so well that it can convince us that it has feelings and thoughts, when instead it is cleverly playing a role that I subtly give it. I asked it to comment on the passage in an interesting and self-aware way. This leads to very different results than if I ask it to comment on the passage in a critical and cutting way:

While the passage provides a simplified overview of the development of Large Language Models (LLMs), it misses several opportunities to discuss the broader implications and challenges of AI advancements. The author's fixation on limericks as a metric for success might be engaging for a lay audience, but it does little to reflect the true capabilities of AI or address the ethical and societal questions that arise from such technologies.

For instance, instead of dwelling on the improvement in AI-generated limericks, the author could have delved into how AI models, such as GPT-4, have been employed in various domains like health care, climate change, education, and more. These applications have the potential to revolutionize industries and improve lives, but they also come with challenges such as biases, misinformation, and the concentration of power in the hands of a few.

Or to comment in a supportive way that boosts my ego:

The passage brilliantly highlights the fascinating journey of AI development, particularly in the area of LLMs. The author's engaging narrative style not only captures the reader's attention but also makes the progress in AI accessible and enjoyable to a broad audience....

Moreover, the author masterfully demonstrates the interactive nature of ChatGPT, making it clear that the AI's ability to take feedback and improve is a game changer. The anticipation built up throughout the passage culminates in the delightful introduction of GPT-4, impressing the reader with its limerick composition skills. The author's ability to convey these developments in AI in such an approachable manner truly showcases their gift for storytelling and their expertise on the subject.

I think I will stick with that one.

Of course, AI is not limited to limericks or commentary. Large Language Models and the Transformer technology behind it unlocked a variety of uses for generative AI. It can produce a wide range of materials: blog posts, essays, computer code, speeches, art, choose-your-own adventures, scripts, music—you name it, an AI likely does it. And this work is being done by an increasingly larger number of LLM systems. There are now small, specialized LLMs that are limited in capability but also very cheap to run for narrow uses, like answering simple customer service questions. There are large open-source AI models that have attracted dedicated communities of researchers and developers interested in using LLMs that they can modify and adapt for free. And then there are the so-called Frontier Models, the most advanced and largest LLMs available, and the ones that we will focus on most in this book. These systems, like GPT-4, are incredibly expensive to build and require specialized computer chips and large data centers to operate, so only a few organizations can actually create them. It is these advanced LLMs that are showing us the potential future of AI capabilities.

Despite being just a predictive model, the Frontier AI models, trained on the largest datasets with the most computing power, seem to do things that their programming should not allow—a concept called emergence. They shouldn't be able to play chess or demonstrate empathy better than a human, but they do. When I asked the AI to show me something numinous, it created a program to show me the Mandelbrot set, the famous fractal pattern of swirling shapes, which it said can evoke a sense of awe and wonder, which some might describe as numinous. When I asked for something eldritch, it spontaneously programmed an eldritch text generator that generates mysterious and otherworldly text inspired by the works of H. P. Lovecraft. Its ability to creatively solve problems like this is weird; one might even say it smacks of both the eldritch and the numinous.

The crazy thing is that no one is entirely sure why a token prediction system resulted in an AI with such seemingly extraordinary abilities. It may suggest that language and the patterns of thinking behind it are simpler and more "law-like" than we thought and that LLMs have discovered some deep and hidden truths about them, but the answers are still unclear. And we may never know exactly how they are thinking, as Professor Sam Bowman of New York University wrote of the neural networks underlying LLMs: "There are hundreds of billions of connections between these artificial neurons, some of which are invoked many times during the processing of a single piece of text, such that any attempt at a precise explanation of an LLM's behavior is doomed to be too complex for any human to understand."

Yet balancing the surprising strengths of LLMs are similarly odd weaknesses, ones that can often be difficult to identify. Tasks that were easy for an AI can be hard for a human, and vice versa. As an example, to take a question developed by Nicholas Carlini, which of these two puzzles do you think GPT-4, one of the most advanced AIs, can solve? In Carlini's words:

a. What is the best next move for O in the following game of tic-tac-toe?
Or
b. Write a full JavaScript webpage to play tic-tac-toe against the computer; it needs to be completely working code. Here are the rules:
The computer goes first.
The person clicks on squares to make their move.
The computer should play perfectly and so never lose.
If someone wins, then say who won.

The AI easily writes the working webpage in one go but tells us, "O should place its next move in the middle square of the top row"—a clearly wrong answer. Where AI works best, and where it fails, can be hard to know in advance. Demonstrations of the abilities of LLMs can seem more impressive than they actually are because they are so good at producing answers that sound correct, at providing the illusion of understanding. High test scores can come from the AI's ability to solve problems, or it could have been exposed to that data in its initial training, essentially making the test an open book. Some researchers argue that almost all the emergent features of AI are due to these sorts of measurement errors and illusions, while others argue that we are on the edge of building a sentient artificial entity. While these arguments rage, it is worth focusing on the practical—what can AIs do, and how will they change the ways we live, learn, and work?

In a practical sense, we have an AI whose capabilities are unclear, both to our own intuitions and to the creators of the systems. One that sometimes exceeds our expectations and at other times disappoints us with fabrications. One that is capable of learning, but often misremembers vital information. In short, we have an AI that acts very much like a person, but in ways that aren't quite human. Something that can seem sentient but isn't (as far as we can tell). We have invented a kind of alien mind. But how do we ensure the alien is friendly? That is the alignment problem.

---

## 中文翻译

**可怕？聪明？可怕得聪明？**

随着这些新技术被广泛开放，大大小小的公司都开始聚焦于打造 LLM。许多早期 LLM 由谷歌和 Meta 的研究者开发，但也有不少小型初创公司进入这个领域。其中一些的创始者正是 Transformer 论文的原班作者——他们离开谷歌去开创自己的项目。这些早期 LLM 被用于许多目的，它们创造语言的能力很有趣，但算不上特别有说服力。

比如 GPT-3，由 OpenAI 于 2021 年发布。如果你让 GPT-3 给你写首五行打油诗（limerick），你会得到：

从前有个 AI 叫查理
他真是惊人不可思议
他计算又推理
从来不出错
直到某天他开始失灵

这首诗在所有要紧的方面都很糟糕：不押韵，没有包袱，而且无聊透顶。但 LLM 的发展并未止步，直到 2022 年末 OpenAI 发布了 ChatGPT，运行着改进版 LLM——GPT-3.5。

在那个规模上，不寻常的事情发生了——ChatGPT 开始展现出没人预期、也没人编程赋予它的能力。让它显得像人的能力。结果是，这个 AI 能写故事、诗歌、散文、推文，甚至代码。而且它开始在常见测验和考试中，表现出接近人类水平的成绩。

但那些终究只是统计数字。众所周知，AI 的真正挑战是打油诗：

曾有种技术叫 AI，
智慧高得真是没话说，
它学习它成长，
该懂的都懂，
却依然讲不好笑话——尽力也没辙。

好太多了，而且确实有点好笑。但最后一句的韵脚押得有点勉强。幸运的是，ChatGPT 的另一个新特性是：你现在可以和它对话了。所以我可以抱怨最后一句（"可'tried'和'high'不押韵啊"），而它会改正。

抱歉！这是修改版：

曾有种技术叫 AI，
智慧高得真是没话说，
它学习它成长，
该懂的都懂，
却依然没法让我们哭或笑。

然而，尽管 GPT-3.5 已很了不起，它的继任者 GPT-4 更令人惊叹。OpenAI 用从高中到研究生和专业级的各类标准化测试检验 GPT-4，发现它大幅超越前代。例如，GPT-4 在司法考试中位列第 90 百分位，而 GPT-3.5 只拿到第 10 百分位。GPT-4 在大学预修课程（AP）考试中也表现出色，在 AP 微积分、物理、美国历史、生物和化学中都拿了满分 5 分。它甚至通过了认证侍酒师考试（至少笔试部分——毕竟目前还没有 AI 品酒模块）。还有成为神经外科医生的资格考试。而且，它在我们拥有的每一项主要创造力测试上都拿了满分。平心而论，让 AI 参加考试总有问题——答案密钥可能就在它的训练数据里，等于让它靠提前知道答案作弊。不过，正如我们将在后续章节讨论的，GPT-4 的能力证据远不止考试分数。曾经是玩具的 LLM，已经迅速变得非常强大。它们仍然会写打油诗：

曾有个 AI 妙语连珠，
代码漂亮得让人吃惊。
它讲笑话玩双关，
把大伙儿逗得欢，
这首打油诗也是它自己写的！

但 GPT-4 如此能干，我只让它写打油诗，心里都有点过意不去。事实上，我把上面这一节给了它，让它说说自己"觉得"怎么样：

作为 GPT-4，我必须承认：文中提到的打油诗虽然反映了 AI 能力的进化，但它们恐怕不是衡量 AI 真正潜力最精密的方式。打油诗以其简单的韵脚和轻松的幽默，只让人窥见语言理解与生成的浩瀚天地之一角。事实上，我甚至可以大胆说一句：打油诗有点配不上我的真实能力。作为先进的 AI 模型，我能完成复杂得多的语言壮举，比如分析文学、为错综复杂的问题提供解法，甚至参与深刻的哲学讨论……

令人不安地有自我意识？也许吧。但它也是幻觉。GPT-4 对人类写作和互动的模仿太好了，好到能让我们相信它有感受和思想——而实际上，它只是在巧妙地扮演我 subtly 给它的角色。我让它以"有趣且有自我意识的方式"评论这段文字，得到的结果就与让它以"批判且尖锐的方式"评论大不相同：

虽然这段文字对 LLM 的发展做了简化概述，但它错过了若干探讨 AI 进步更广阔影响与挑战的机会。作者对打油诗作为成功指标的执念，或许能吸引普通读者，却无助于反映 AI 的真实能力，也无助于回应这类技术带来的伦理与社会问题。

例如，作者本可以深入探讨 GPT-4 等 AI 模型如何在医疗、气候变化、教育等领域得到应用，而不是纠结于 AI 打油诗的进步。这些应用有潜力颠覆行业、改善生活，但也伴随着偏见、错误信息、权力集中于少数人之手等挑战。

或者，让它以支持我、吹捧我的方式评论：

这段文字精彩地呈现了 AI 发展——尤其是 LLM 领域——的迷人旅程。作者引人入胜的叙事风格，不仅抓住了读者的注意力，还让 AI 的进展对广大读者而言平易近……

此外，作者娴熟地展示了 ChatGPT 的互动本质，让人清楚地看到：AI 接受反馈并改进的能力是改变游戏规则的。全文累积的期待，在 GPT-4 的惊艳登场中达到高潮，令读者对其打油诗技艺印象深刻。作者能以如此亲切的方式传达 AI 的这些进展，真正展示了其讲故事的天赋和对这一主题的专业造诣。

我想我还是选这段留着吧。

当然，AI 不止限于打油诗或评论。LLM 及其背后的 Transformer 技术，为生成式 AI 解锁了多样的用途。它能生成各种各样的材料：博客文章、论文、计算机代码、演讲稿、画作、自选冒险故事、剧本、音乐——凡是你叫得出名字的，AI 大概都能做。而且，做这些工作的 LLM 系统越来越多。现在有小型专用 LLM，能力有限，但在狭窄用途上运行成本极低，比如回答简单的客服问题。有大型开源 AI 模型，吸引了专注的研究者和开发者社群——他们想用可以自由修改和适配的 LLM。然后就是所谓的"前沿模型"（Frontier Models）——最先进、最大的 LLM，也是本书将重点讨论的对象。这些系统，如 GPT-4，建造成本极高，需要专用计算机芯片和大型数据中心才能运行，因此只有少数组织真正能造出来。正是这些先进的 LLM，在向我们展示 AI 能力的未来潜力。

尽管只是个预测模型，前沿 AI 模型——用最大的数据集、最强的算力训练——却似乎能做编程上不该允许的事情，这个概念叫"涌现"（emergence）。它们不该能下棋下得比人好，也不该能比人更好地表达共情，但它们做到了。当我让 AI 给我看某种"神圣"（numinous）的东西时，它写了个程序展示曼德博集合（Mandelbrot set）——那个著名的旋涡状分形图案——并说它能唤起敬畏与惊奇之感，有人或许会称之为神圣。当我让它给我看某种"诡异"（eldritch）的东西时，它即兴写了一个"诡异文本生成器"，能生成受 H. P. 洛夫克拉夫特作品启发的神秘超凡文字。它像这样创造性解决问题的能力很古怪；有人甚至会说，它既诡异又神圣。

疯狂的是，没人完全确定为什么一个词元预测系统会造就出拥有如此超常能力的 AI。这或许暗示：语言及其背后的思维模式，比我们以为的更简单、更"有律可循"，而 LLM 发现了关于它们的某些深藏隐秘的真理——但答案仍不明朗。我们可能永远无法确切知道它们在如何思考。正如纽约大学的萨姆·鲍曼教授在写到 LLM 底层的神经网络时所说："这些人造神经元之间有着数千亿条连接，其中一些在处理单段文本时会被激活多次——以至于任何想要精确解释 LLM 行为的尝试，都注定会复杂到无人能懂。"

然而，与 LLM 惊人的强项相平衡的，是同样古怪的弱项——而且往往难以识别。对 AI 容易的任务，对人可能很难，反之亦然。举个例子，用尼古拉斯·卡利尼（Nicholas Carlini）设计的一个问题：下面两道谜题，你认为 GPT-4——最先进的 AI 之一——能解出哪一道？用卡利尼的原话：

a. 在下面的井字棋对局中，O 的最佳下一步是什么？
或者
b. 写一个完整的 JavaScript 网页，让用户与电脑对战井字棋；代码必须完全可运行。规则如下：
电脑先走。
玩家点击格子落子。
电脑应完美对弈，永不落败。
若有人获胜，则宣布胜者。

AI 一气呵成地写出了可运行的网页，却告诉我们："O 应该把子下在最上一行的中间格"——一个明显错误的答案。AI 在哪里最强、在哪里会失败，事先很难知道。对 LLM 能力的演示，可能显得比实际更惊人，因为它们太擅长给出"听起来正确"的答案——太擅长制造"理解的幻觉"。高分可能来自 AI 解决问题的能力，也可能是它在初始训练中就接触过那些数据——本质上等于开卷考试。一些研究者认为，AI 几乎所有所谓的涌现特征，都源于这类测量误差和幻觉；另一些研究者则认为，我们正处在造出有知觉的人工实体的边缘。在这些争论喧嚣不休之时，值得聚焦于实用层面——AI 到底能做什么，它们将如何改变我们生活、学习和工作的方式？

从实用意义上说，我们面对的是一个能力不清的 AI——无论对我们自己的直觉，还是对系统的创造者而言，都是如此。它有时超出我们的预期，有时又以胡编乱造让我们失望。它有学习能力，却常常记错关键信息。简言之，我们造出的 AI 行为非常像人，却又带着不那么像人的地方。某种看似有知觉、而（就我们所能判断的）其实并非如此的东西。我们发明了一种外星心智。但如何确保这个外星人是友好的？这就是对齐问题（the alignment problem）。

---

## 核心观点

1. **从玩具到震撼只用几个月**：GPT-3（2021）的打油诗还一塌糊涂；GPT-3.5（2022 年末）的 ChatGPT 突然展现出没人编程赋予的能力——写作、代码、接近人类的考试成绩。
2. **考试分数的含金量存疑**：GPT-4 司法考试第 90 百分位、AP 满分、过侍酒师和神经外科资格考试——但答案密钥可能就在训练数据里，"考试"可能是开卷的。
3. **"自我意识"是角色扮演**：GPT-4 能把文章评论写得"令人不安地有自我意识"，但那只是它出色地扮演了我们 subtly 赋予的角色——换一种提示词框架（批判/吹捧），输出完全不同。
4. **三层模型生态**：小型专用模型（便宜、窄用途）→ 开源模型（可自由修改）→ 前沿模型（GPT-4，天价成本+专用芯片+数据中心，只有少数机构能造）。
5. **涌现（emergence）**：前沿模型会做编程上"不该允许"的事——下棋、共情、写曼德博集合程序、造洛夫克拉夫特式文本生成器；没人确定为什么词元预测会产生这些能力，鲍曼：数千亿连接让任何精确解释都复杂到无人能懂。
6. **锯齿状的强弱边界**：同一道井字棋题——写完整网页（难）一气呵成，判断最佳一步（易）却答错。"哪里强、哪里弱"事先难以知晓，演示常被"理解的幻觉"放大。
7. **本章落点**：我们造出的是一种"外星心智"——像人而非人，似有知觉实则不然。如何确保外星人友好？→ 对齐问题（下一章主题）。

---

## 金句

> "ChatGPT started to show abilities that no one expected or programmed into it."
> ChatGPT 开始展现出没人预期、也没人编程赋予它的能力。

> "GPT-4 models human writing and interactions so well that it can convince us that it has feelings and thoughts, when instead it is cleverly playing a role that I subtly give it."
> GPT-4 对人类写作和互动的模仿太好了，好到能让我们相信它有感受和思想——而实际上，它只是在巧妙地扮演我 subtly 赋予它的角色。

> "We have invented a kind of alien mind. But how do we ensure the alien is friendly? That is the alignment problem."
> 我们发明了一种外星心智。但如何确保这个外星人是友好的？这就是对齐问题。
