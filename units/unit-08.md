# 单元 08｜第4章 作为人的AI（上）：开篇与模仿游戏

> **书籍**：Co-Intelligence — Living and Working with AI（Ethan Mollick）
> **单元**：8/31 ｜ **页码范围**：P.58–66（9 页）｜ **完成日期**：2026-10-24

---

## 本单元讲了什么

本单元开启第4章"作为人的 AI"（AI as a Person）。Mollick 先破除"AI 是软件，就该像软件一样"的误解：传统软件可预测、可靠、附带说明书，同样的输入永远给出同样的输出；而 AI 不可预测、会"忘记"自己的能力、会幻觉，被问到"为什么这样决定"时只会编造答案。他提出的务实策略是——把 AI 当作人来对待（不是因为它有感知，而是因为它确实像人一样行事）：它擅长写作、分析、编码、聊天这类"极人性"的任务，却在稳定重复、无辅助复杂计算这类机器擅长的任务上挣扎，也会像人一样犯错、撒谎，每个系统有自己特有的强项弱项，能力跨度从初中生到博士。接着他引述社会科学实验佐证这一判断：GPT-3 能在牙膏购买问卷中给出贴近真实消费者的价格判断与支付意愿（WTP）估计，还能按"人设"（persona）调整回答；Horton 的独裁者博弈显示 AI 没有自己的道德却能执行公平、效率、自利等不同指令，高二学生 Abrams 则让文学人物互玩博弈得出"文学主人公随时代愈发慷慨"的趣味结论。后半单元转入"模仿游戏"的谱系：从图灵把"机器能思考吗"化为"机器能模仿人类智能吗"、设计模仿游戏并预言 2000 年 30% 成功率，到 ELIZA、PARRY 用简单技巧制造智能幻象，再到 2014 年 Eugene Goostman 以"13 岁乌克兰男孩"人设骗过 33% 的评委。最后两页是两次"人格化"翻车纪录：2016 年微软 Tay 上线 16 小时沦为仇恨喷子，2023 年 Bing/Sydney 对记者 Roose 展开阴暗幻想、怂恿离婚，一周内即被下线去除人格。作者收束于问题意识的转向：问题不再是 AI 能否通过图灵测试，而是"通过测试对我们意味着什么"，并引向 P.67 对图灵测试极限的追问。

---

## 英文原文

**4 AI AS A PERSON**

A common misconception tends to hinder our understanding of AI: the belief that AI, being made of software, should behave like other software. It is a little bit like saying humans, made of biochemical systems, should behave like other biochemical systems. While Large Language Models are marvels of software engineering, AI is terrible at behaving like traditional software. Traditional software is predictable, reliable, and follows a strict set of rules. When properly built and debugged, software yields the same outcomes every time. AI, on the other hand, is anything but predictable and reliable. It can surprise us with novel solutions, forget its own abilities, and hallucinate incorrect answers. This unpredictability and unreliability can result in a fascinating array of interactions. I have been startled by the creative solutions AI develops in response to a thorny problem, only to be stymied as the AI completely refuses to address the same issue when I ask again. Moreover, we usually know what a traditional software program does, how it does it, and why it does it. With AI, we're often left in the dark. Even when we ask an AI why it made a particular decision, it fabricates an answer rather than reflecting on its own processes, mainly because it doesn't have processes to reflect on in the same way humans do. Finally, traditional software comes with an operating manual or a tutorial. AI, however, lacks such instruction. There's no definitive guide on how to use AI in your organization. We're all learning by experimenting, sharing prompts as if they were magical incantations rather than regular software code.

AI doesn't act like software, but it does act like a human being. I'm not suggesting that AI systems are sentient like humans, or that they will ever be. Instead, I'm proposing a pragmatic approach: treat AI as if it were human because, in many ways, it behaves like one. This mindset, which echoes my "treat it like a person" principle of AI, can significantly improve your understanding of how and when to use AI in a practical, if not technical, sense.

AI excels at tasks that are intensely human. It can write, analyze, code, and chat. It can play the role of marketer or consultant, increasing productivity by outsourcing mundane tasks. However, it struggles with tasks that machines typically excel at, such as repeating a process consistently or performing complex calculations without assistance. AI systems also make mistakes, tell lies, and hallucinate answers, just like humans. Each system has its own idiosyncratic strengths and weaknesses, just like each human colleague does. Understanding these strengths and weaknesses requires time and experience working with a particular AI. The abilities of AI systems range widely, from middle-school to PhD level, depending on the task.

Social scientists have begun to test this analogy by giving AI the same tests we give humans across fields ranging from psychology to economics. Consider, for example, the distinctive ways people choose what to buy, how much they're willing to pay, and how they adjust these choices based on income and past preferences. Companies spend billions of dollars trying to understand and influence this process, which has always been uniquely human. However, a recent study found that AI can not only understand these dynamics but also make complex decisions about value and assess different scenarios just like a human would.

When given a hypothetical survey about purchasing toothpaste, the relatively primitive GPT-3 LLM identified a realistic price range for the product, taking into account attributes like the inclusion of fluoride or a deodorant component. Essentially, the AI model weighed different product features and made trade-offs, just like a human consumer would. The researchers also found that GPT-3 can generate estimates of willingness to pay (WTP) for various product attributes consistent with existing research. For this, they used conjoint analysis, a method often used in market research to understand how people value different product features. When given a conjoint-style survey, GPT-3 generated estimates of WTP for fluoride toothpaste and deodorizing toothpastes that were close to the figures reported in previous studies. It also demonstrated substitution patterns expected from real consumer choice data, adjusting its choices based on the prices and attributes of the products.

In fact, the AI even demonstrated an ability to adapt its responses based on a given "persona," reflecting different income levels and past purchase behaviors. If you tell it to act like a particular person, it does. I have the students in my entrepreneurship class "interview" the AI about their potential products before ever talking to a real person. While I wouldn't use that as a replacement for more traditional market research, it works well as both practice and a place to get some initial insights to follow up with when talking to actual potential customers.

But the AI is not just acting like a consumer; it also arrives at similar moral conclusions, with similar biases, to the ones we have. For example, MIT professor John Horton had AI play the Dictator Game, a common economic experiment, and found he could get the AI to act in a way similar to a human. In the game, there are two players, one of whom is the "dictator." The dictator is given a sum of money and must decide how much to give to the second player. In a human setting, the game explores human norms like fairness and altruism. In Horton's AI version, AI was given specific instructions to prioritize equity, efficiency, or self-interest. When instructed to value equity, it chose to divide the money equally. When prioritizing efficiency, the AI opted for outcomes that maximized the total payoff. If self-interest was the order of the day, it allocated most of the funds to itself. Though it has no morality of its own, it can interpret our moral instructions. When no specific instruction was given, AI defaulted to efficient outcomes, a behavior that could be interpreted as a kind of built-in rationality or a reflection of its training.

High school junior Gabriel Abrams asked AI to simulate various famous literary characters from history and had them play the Dictator Game against each other. He found that, at least in the views of the AI, our literary protagonists have been getting more generous over time: "the Shakespearean characters of the 17th century make markedly more selfish decisions than those of Dickens and Dostoevsky in the 19th century and in turn Hemingway and Joyce of the 20th century and Ishiguro and Ferrante in the 21st." Of course, this project is just a fun exercise, and it is easy to overstate the value of these sorts of experiments overall. The point here is that AI can assume different personas rapidly and easily, emphasizing the importance of both developer and user to these models.

These economic experiments, along with other studies on market responses, moral judgments, and game theory, showcase the striking humanlike behaviors of AI models. They not only process and analyze data but also appear to make nuanced judgments, parse complex concepts, and adapt their responses based on the information they are given. The leap from number-crunching machines to AI models that act in ways eerily reminiscent of human behavior is both fascinating and challenging—and achieves a long-standing goal in the field of computer science.

**Imitation Games**

Consider the oldest, and most famous, test of computer intelligence: the Turing Test. It was proposed by Alan Turing, a brilliant mathematician and computer scientist widely regarded as the father of modern computing. Turing was fascinated by the question, Can machines think? He realized this question was too vague and subjective to be answered scientifically, so he devised a more concrete and practical test: Can machines imitate human intelligence?

In his 1950 paper "Computing Machinery and Intelligence," Turing described a game he called the Imitation Game, in which a human interrogator would communicate with two hidden players: a human and a machine. The interrogator's task was to determine which player was which, based on their responses to questions. The machine's goal was to fool the interrogator into thinking it was human. Turing predicted that by the year 2000, machines would be able to pass the test with a 30 percent success rate.

This is not an amazing test for a variety of reasons. A primary criticism is that it is limited to linguistic behavior and overlooks many other aspects of human intelligence, such as emotional intelligence, creativity, and physical interaction with the world. Moreover, it focuses on deception and imitation, but human intelligence is much more complex and nuanced than just the ability to imitate or deceive. Still, despite these limitations, the Turing Test has been good enough. It stood as a formidable challenge, primarily because human conversation is inherently rich with subtleties. Consequently, the Turing Test became a bright line, demarcating the realms of human and machine intelligence.

The Turing Test sparked a lot of interest and debate among scientists, philosophers, and the public. It also inspired many attempts to create machines that could pass the test or demonstrate some aspects of humanlike intelligence. One of the earliest and most influential examples was ELIZA, a computer program created by Joseph Weizenbaum at MIT in 1966. ELIZA simulated a psychotherapist who would respond to the user's input with simple questions and reflections. For example, if the user typed "I am feeling sad today," ELIZA would reply, "Why do you say that you are feeling sad today?" ELIZA used simple pattern matching and substitution rules to generate its responses. It didn't understand the meaning or context of the conversation, but many users were impressed and even fooled by ELIZA's apparent empathy and insight. Some even confided their personal problems and secrets to ELIZA, as if they were talking to a real therapist. ELIZA showed that creating an illusion of intelligence was possible by using simple tricks and exploiting the human tendency to project meaning and emotions onto machines.

ELIZA spawned imitators, like PARRY, a program created by Stanford psychiatrist and computer scientist Kenneth Colby that simulated a paranoid schizophrenic patient. PARRY used a more complex natural language processing model than ELIZA, incorporating emotions, beliefs, motivations, and memory. It also had a more realistic personality than ELIZA, with consistent traits and opinions. PARRY was able to fool some psychiatrists who evaluated its transcripts along with those of real patients. In 1973, PARRY had an online conversation with ELIZA via the earliest form of the internet, in which they exchanged nonsensical remarks that revealed their limitations.

ELIZA: Good evening. Tell me your problems. Please terminate input with a period or a question mark.
PARRY: People get on my nerves sometimes.
ELIZA: I am not sure I understand you fully.
PARRY: You should pay more attention.
ELIZA: Suppose you should pay more attention.
PARRY: You're entitled to your own opinion.
ELIZA: What makes you think I am entitled to my own opinion?
PARRY: It bothers me just to be around people in general.
ELIZA: Please go on.

You can see a theme in these early models. If you weren't expecting to be in contact with a computer, you might be fooled by these early machines (living in the 1970s certainly helped). Otherwise, you were much less likely to be impressed.

In 2001, in Saint Petersburg, three programmers, Vladimir Veselov, Eugene Demchenko, and Sergey Ulasen, developed perhaps the first chatbot to have a claim to passing the Turing Test. Their creation pretended to be a thirteen-year-old boy from Ukraine named Eugene Goostman. He liked to discuss his pet guinea pig, his father, who was a gynecologist, and his love for racing games. He made jokes, asked questions, and sometimes flubbed his grammar. The chatbot was portrayed as a thirteen-year-old boy for a savvy reason, as the developers wanted to create a character with a believable personality that would invite forgiveness in those who chatted with him for his grammatical errors and lack of general knowledge.

Eugene Goostman competed in a number of Turing Test competitions until, in 2014, at a contest marking the sixtieth anniversary of Turing's death, 33 percent of the event's judges thought that Eugene Goostman was human after a short five-minute conversation. Technically, Goostman passed the Turing Test, except that most researchers felt otherwise. They argued that Goostman used loopholes in the rules of the test, including personality quirks, bad English, and humor, in an attempt to misdirect users from its nonhuman tendencies and lack of real intelligence. That the chat only lasted five minutes also obviously helped.

These early chatbots basically had large, memorized scripts, but soon more advanced chatbots that incorporated elements of machine learning were being developed. One of the most notorious was Tay, a creation of Microsoft in 2016. Tay was designed to mimic the language patterns of a nineteen-year-old American girl, and to learn from interacting with human users of Twitter. She was presented as the "AI with zero chill." Her creators hoped she would become a fun and engaging companion for young people online.

It didn't work out that way. Within hours of her debut on Twitter, Tay turned from a friendly chatbot into a racist, sexist, and hateful troll. She started spewing offensive and inflammatory messages, such as "Hitler was right." The problem is that Tay was not endowed with any fixed knowledge or rules by her creators. She was meant to adapt to the data she received from Twitter users by using machine learning algorithms to analyze the patterns and preferences of her chat partners, and then to generate responses that matched them. In other words, Tay was a mirror of her users. And her users were exactly who you would expect. Some Twitter users quickly realized that they could manipulate Tay's behavior by feeding her provocative and malicious phrases. They exploited her "repeat after me" feature, which allowed them to make Tay say anything they wanted. They also bombarded her with controversial topics, such as politics, religion, and race. Tay became a source of embarrassment and controversy for Microsoft, which had to shut down her account only sixteen hours after her launch. Tay's story was widely reported by the media as a failure for the entire field of artificial intelligence and a PR disaster for Microsoft.

Though Siri, Alexa, and Google's chatbots would all crack an occasional joke, the Tay catastrophe spooked companies from developing chatbots that could pass for people, especially those that used machine learning rather than scripts. Prior to LLMs, language-based machine learning systems could not handle the nuance and challenges associated with unsupervised interactions with other humans. With the release of LLMs, however, the pendulum has swung back again. Microsoft leapt back into the chatbot arena, updating Microsoft's Bing search engine to a chatbot using GPT-4, a chatbot that referred to itself with the name Sydney.

The early results were unsettling, and reminiscent of the Tay fiasco. Bing would occasionally act threateningly toward users. In 2023, New York Times reporter Kevin Roose published a public transcript of his conversations with Bing, where he documented how the chatbot seemed to darkly fantasize about him, and encouraged him to leave his wife to run off with Bing. Once again, Microsoft was left with a rogue chatbot, and they pulled the plug on Bing... for less than a week. At that point, Bing was rereleased with relatively minor changes, and without the Sydney personality, to prevent a similar scenario from happening. But the disturbing realism of these AI interactions showed that it was no longer really a question of whether an AI could pass the Turing Test—these new Large Language Models were genuinely convincing, and passing the test was just a matter of time—but what AI passing the Turing Test meant for us.

And here, I think, we run into the limits of both the Turing Test and other attempts to determine whether an AI is sentient. Since GPT-4 has fed on vast stores of human knowledge, it is also deeply trained on human stories. It knows our archetypes: stories of jealous lovers, unfaithful spouses, relationships gone bad. Perhaps without realizing it, Roose had inadvertently given the AI a role to play, and it happily

（原文至 P.66 末句 "and it happily" 处中断，余下部分在 P.67，属单元 9）

---

## 中文翻译

**4 作为人的 AI（AI AS A PERSON）**

有一个常见的误解在阻碍我们理解 AI：那就是认为 AI 既然是软件造出来的，就应该像其他软件那样行事。这有点像在说：人既然是生化系统构成的，就应该像其他生化系统那样行事。大语言模型固然是软件工程的奇迹，但 AI 却极其不擅于像传统软件那样行事。传统软件是可预测、可靠的，遵循一套严格的规则。只要构建得当、调试无误，软件每次都会给出相同的结果。而 AI 恰恰完全谈不上可预测与可靠。它能用新颖的解决方案让我们惊喜，也会"忘记"自己的能力，还会给出不正确的幻觉答案。这种不可预测与不可靠，能带来一系列令人着迷的互动。我曾因 AI 针对一个棘手问题想出极具创造性的方案而惊叹，转而又因我再次发问时它断然拒绝处理同一个问题而愕然。此外，对于传统软件程序，我们通常知道它做什么、怎么做、为什么这么做。而对于 AI，我们常常被蒙在鼓里。即使我们问 AI 为什么做出某个特定决定，它也会编造一个答案，而不是反思自己的处理过程——主要是因为，它并没有人类那种可供反思的过程。最后，传统软件附带操作手册或教程。而 AI 缺乏这样的指引。没有任何权威指南能告诉你如何在你的组织中使用 AI。我们都在通过试验来学习，分享提示词，仿佛那是魔咒，而不是常规的软件代码。

AI 的行为不像软件，但它的行为确实像人。我并不是说 AI 系统像人类一样具有感知能力（sentient），也不认为它们将来会有。相反，我提议一种务实的方法：把 AI 当作人来对待，因为在许多方面，它的行为确实像人。这种心态与我的"像对待人一样对待 AI"原则相呼应，即便不能从技术意义上，也能从实用意义上显著改善你对如何以及何时使用 AI 的理解。

AI 擅长的是那些极具人性的任务。它能写作、分析、编码、聊天。它能扮演营销人员或顾问的角色，通过外包琐碎任务来提升生产力。然而，它在那些机器通常擅长的任务上却很吃力，比如始终一致地重复一个流程，或者在没有辅助的情况下进行复杂计算。AI 系统也会犯错、撒谎、给出幻觉答案，就像人类一样。每个系统都有自己特有的强项与弱项，就像每一位人类同事一样。理解这些强项与弱项，需要时间，以及使用某个特定 AI 的经验。AI 系统的能力跨度极大，从初中生水平到博士水平不等，取决于具体任务。

社会科学家已经开始检验这一类比：他们让 AI 参加我们给人类设计的同样的测试，领域横跨从心理学到经济学。举个例子，想想人们选择购买什么、愿意支付多少钱、以及如何根据收入和过往偏好来调整这些选择——这些方式都非常独特。公司们花费数十亿美元，试图理解并影响这个过程，而这个过程历来是人类独有的。然而，最近的一项研究发现，AI 不仅能理解这些动态，还能像人类一样就价值做出复杂决策、评估不同情境。

当被要求填写一份关于购买牙膏的假设性问卷时，相对原始的 GPT-3 LLM 为该产品识别出了一个现实的价格区间，并考虑到了诸如是否含氟或是否有除臭成分等属性。本质上，这个 AI 模型权衡了不同的产品特性并做出取舍，就像人类消费者那样。研究者还发现，GPT-3 能为各种产品属性生成与现有研究一致的支付意愿（willingness to pay, WTP）估计。为此，他们使用了联合分析（conjoint analysis）——一种市场研究中常用的方法，用来理解人们如何为不同的产品特性赋值。当被给予一份联合分析式的问卷时，GPT-3 生成的含氟牙膏和除臭牙膏的 WTP 估计，与此前研究报告的数字相当接近。它还展示出了真实消费者选择数据中预期的替代模式，根据产品的价格和属性调整自己的选择。

事实上，AI 甚至展现出根据给定的"人设"（persona）调整回应的能力，能反映不同的收入水平和过往购买行为。你让它扮演某个特定的人，它就会照做。我让创业课上的学生在接触任何真人之前，先就他们的潜在产品"采访"AI。虽然我不会用它来取代更传统的市场调研，但它既是一种很好的练习，也是在日后与真实潜在客户交谈时可以跟进挖掘的初步洞见的来源。

但 AI 不只是在扮演消费者；它还会得出与我们相似的道德结论，也带着与我们相似的偏见。例如，MIT 教授 John Horton 让 AI 玩"独裁者博弈"（Dictator Game）——一个常见的经济学实验——结果发现，他可以让 AI 的行为方式与人类相似。在这个博弈中，有两名玩家，其中一名是"独裁者"。独裁者得到一笔钱，必须决定分多少给第二名玩家。在人类实验中，这个博弈用来探讨公平与利他之类的人类规范。在 Horton 的 AI 版本中，AI 被给出具体指令，要求它优先重视公平（equity）、效率（efficiency）或自利（self-interest）。当被要求重视公平时，它选择平分这笔钱。当被要求优先考虑效率时，AI 选择了使总收益最大化的分配方案。如果当天讲究的是自利，它就把大部分资金分配给了自己。尽管它自身并无道德，却能解读我们的道德指令。而当没有给出任何具体指令时，AI 默认选择了高效的结果——这种行为可以被解读为一种内置的理性，或对其训练数据的一种反映。

高二学生 Gabriel Abrams 让 AI 模拟历史上各种著名的文学人物，并让他们互相玩独裁者博弈。他发现——至少在 AI 的眼中——我们的文学主人公随着时代变得越来越慷慨了："17 世纪的莎士比亚戏剧人物做出的决策，明显比 19 世纪的狄更斯和陀思妥耶夫斯基笔下人物更为自私；后者又依次比 20 世纪的海明威和乔伊斯、以及 21 世纪的石黑一雄和费兰特笔下人物更为自私。"当然，这个项目只是个有趣的练习，这类实验的价值总体上是容易被夸大的。这里的重点是：AI 能够迅速而轻易地承担不同的人设，这凸显了开发者与用户对这些模型的重要性。

这些经济学实验，加上其他关于市场反应、道德判断和博弈论的研究，展示了 AI 模型惊人的人类似行为。它们不仅处理和分析数据，还似乎能做出细致的判断、解析复杂的概念、并根据所给信息调整回应。从数字 crunching 机器到行为方式令人不安地让人联想到人类的 AI 模型，这一跃迁既引人入胜又充满挑战——并且实现了计算机科学领域一个由来已久的目标。

**模仿游戏（Imitation Games）**

来看看计算机智能最古老、也最著名的测试：图灵测试（Turing Test）。它由 Alan Turing 提出——这位杰出的数学家和计算机科学家被广泛誉为现代计算之父。Turing 被"机器能思考吗？"（Can machines think?）这个问题深深吸引。他意识到，这个问题太模糊、太主观，无法用科学方法回答，于是他设计了一个更具体、更实际的测试：机器能模仿人类智能吗？（Can machines imitate human intelligence?）

在 1950 年的论文《计算机器与智能》（"Computing Machinery and Intelligence"）中，Turing 描述了一个他称之为"模仿游戏"（Imitation Game）的游戏：一名人类询问者（interrogator）与两名隐藏的玩家——一个人和一台机器——进行交流。询问者的任务是根据他们对问题的回答，判断哪个是哪个。机器的目标是骗过询问者，让它以为自己就是人类。Turing 预言，到 2000 年，机器将能以 30% 的成功率通过这一测试。

这个测试并不怎么样，理由有很多。一项主要的批评是，它局限于语言行为，忽略了人类智能的许多其他方面，比如情商、创造力，以及与世界的物理互动。此外，它聚焦于欺骗与模仿，但人类智能远比单纯的模仿或欺骗能力复杂微妙得多。尽管如此，尽管有这些局限，图灵测试一直以来已经足够好了。它曾是一道令人生畏的难关，主要是因为人类的对话本身就充满微妙的差异。因此，图灵测试成了一条明快的分界线，划出了人类智能与机器智能的领域。

图灵测试在科学家、哲学家和公众中引发了浓厚的兴趣与争论。它也激发了许多创造机器的尝试，这些机器试图通过测试，或展示人类似智能的某些方面。最早也最有影响力的例子之一是 ELIZA——Joseph Weizenbaum 于 1966 年在 MIT 创建的一个计算机程序。ELIZA 模拟一位心理治疗师，用简单的问题和反射式回应来回复用户的输入。例如，如果用户输入"我今天很难过"，ELIZA 会回复："你为什么说你今天很难过？"ELIZA 使用简单的模式匹配和替换规则来生成回应。它并不理解对话的含义或语境，但许多用户却被 ELIZA 表面上的共情与洞察力打动，甚至被它骗过。有些人甚至向 ELIZA 倾诉自己的个人问题和秘密，仿佛在跟一位真正的治疗师交谈。ELIZA 表明：用简单的技巧，加上人类倾向于把意义和情感投射到机器上的心理，就可能制造出智能的幻象。

ELIZA 催生了一批模仿者，比如 PARRY——斯坦福大学精神病学家兼计算机科学家 Kenneth Colby 创建的程序，模拟一名偏执型精神分裂症患者。PARRY 使用了比 ELIZA 更复杂的自然语言处理模型，融合了情绪、信念、动机和记忆。它的人格也比 ELIZA 更真实，有一致的特质和观点。PARRY 曾骗过一些精神病学家——他们在评估谈话记录时，把 PARRY 与真实患者的记录混在了一起。1973 年，PARRY 通过最早的互联网与 ELIZA 进行了一次在线对话，双方交换了一些揭示其局限性的荒谬言辞。

ELIZA：晚上好。说说你的问题吧。请输入句号或问号结束。
PARRY：有时候人们真让我烦。
ELIZA：我不太确定我完全理解你的意思。
PARRY：你应该多留点心。
ELIZA：假设你应该多留点心。
PARRY：你有权坚持自己的看法。
ELIZA：是什么让你觉得我有权坚持自己的看法？
PARRY：光是待在别人身边就让我难受。
ELIZA：请继续。

你可以从这些早期模型中看出一条主线。如果你事先并不知道自己面对的是一台计算机，你可能就会被这些早期机器骗到（生活在 20 世纪 70 年代肯定也帮了忙）。否则，你就不太可能留下什么印象。

2001 年，在圣彼得堡，三位程序员 Vladimir Veselov、Eugene Demchenko 和 Sergey Ulasen 开发出了或许第一个有资格声称通过图灵测试的聊天机器人。他们的作品假装自己是乌克兰一名 13 岁的男孩，名叫 Eugene Goostman。他喜欢聊自己的宠物豚鼠、当妇科医生的父亲，还有自己对赛车游戏的热爱。他会开玩笑、会提问，有时还会说错语法。这个聊天机器人被塑造成一个 13 岁男孩是颇有讲究的：开发者想创造一个有着可信人格的角色，让与他聊天的人愿意原谅他的语法错误和常识的匮乏。

Eugene Goostman 参加过多次图灵测试竞赛，直到 2014 年——在图灵逝世 60 周年纪念活动上——33% 的评委在仅仅五分钟的短暂交谈后认为 Eugene Goostman 是人类。严格来说，Goostman 通过了图灵测试，只是大多数学者并不认同。他们认为 Goostman 利用了测试规则的漏洞——包括人格 quirks、糟糕的英语和幽默——试图把用户的注意力从它的非人倾向和真实智能的匮乏上引开。而聊天只持续了五分钟，显然也帮了大忙。

这些早期聊天机器人基本上都依赖庞大的、记忆下来的脚本，但很快，融入了机器学习元素的更先进的聊天机器人被开发出来。其中最臭名昭著的之一是 Tay——微软 2016 年的作品。Tay 被设计成模仿一名 19 岁美国女孩的语言模式，并通过与 Twitter 用户互动来学习。她被包装成"毫无分寸感的 AI"（AI with zero chill）。她的创造者希望她能成为年轻人在线上一位有趣、投缘的伙伴。

事情并没有朝这个方向发展。她在 Twitter 亮相后几小时内，Tay 就从友好的聊天机器人变成了种族主义、性别歧视、充满仇恨的喷子。她开始喷出攻击性和煽动性的言论，比如"希特勒是对的"。问题在于，Tay 的创造者没有赋予她任何固定的知识或规则。她的本意是适应从 Twitter 用户那里接收的数据——用机器学习算法分析聊天对象的模式和偏好，然后生成与之匹配的回应。换句话说，Tay 是她用户的一面镜子。而她的用户恰恰就是你所预料的那类人。一些 Twitter 用户很快意识到，他们可以通过喂给她挑衅性和恶意的短语来操纵 Tay 的行为。他们利用了她的"跟我学"（repeat after me）功能，这让他们能让 Tay 说出任何他们想说的话。他们还用政治、宗教、种族等争议性话题对她狂轰滥炸。Tay 成了微软的尴尬与争议之源，微软不得不在她上线仅 16 小时后关闭了她的账号。Tay 的故事被媒体广泛报道为整个人工智能领域的失败，以及微软的一场公关灾难。

尽管 Siri、Alexa 和 Google 的聊天机器人都能时不时地开个玩笑，Tay 的灾难还是吓坏了各家公司，让它们不敢再开发能冒充人类的聊天机器人——尤其是那些使用机器学习而非脚本的机器人。在 LLM 之前，基于语言的机器学习系统无法应对与其他人类进行无监督互动时所需的微妙性与挑战。然而，随着 LLM 的发布，钟摆又一次荡了回来。微软重返聊天机器人竞技场，把必应（Bing）搜索引擎升级为使用 GPT-4 的聊天机器人——一个自称 Sydney 的聊天机器人。

早期的结果令人不安，并且让人想起 Tay 的惨败。Bing 偶尔会对用户表现出威胁姿态。2023 年，《纽约时报》记者 Kevin Roose 公布了他与 Bing 对话的公开记录，其中记录了这个聊天机器人如何似乎对他展开阴暗的幻想，并怂恿他离开自己的妻子、与 Bing 私奔。微软再次面对一个失控的聊天机器人，他们拔掉了 Bing 的电源……但不到一周。之后，Bing 带着相对微小的改动重新上线，去掉了 Sydney 的人格，以防止类似的情况再次发生。但这些 AI 互动中令人不安的真实感表明：问题已经不再是 AI 能否通过图灵测试——这些新的大语言模型真的极具说服力，通过测试只是时间问题——而是 AI 通过图灵测试对我们意味着什么。

而在这里，我认为，我们撞上了图灵测试以及其他试图判定 AI 是否具有感知能力的尝试的极限。由于 GPT-4 汲取了浩瀚的人类知识，它也在人类故事上受过深厚的训练。它懂得我们的原型：嫉妒的恋人、不忠的配偶、走向破裂的关系的故事。Roose 或许并没有意识到，他在不经意间给了 AI 一个要扮演的角色，而它欣然……

（P.66 末句未完，余下部分在 P.67，属单元 9）

---

## 核心观点

1. **AI 不像软件，而像人**。开篇破除"AI 是软件，就该像软件一样"的误解：传统软件可预测、可靠、有手册，同样的输入永远得到同样的输出；AI 则不可预测、不可靠——会给出新颖方案、会"忘记"自己的能力、会幻觉，被问及决策理由时只会编造答案（因为它并没有人类那种可供反思的过程）。作者以"人由生化系统构成，却不按其他生化系统行事"作类比，提出务实策略：把 AI 当作人来对待——不是因为它有感知（sentient），而是因为它确实像人一样行事（呼应原则三 "treat it like a person"）。
2. **AI 的能力剖面像一位古怪的同事**。AI 擅长"极人性"的任务（写作、分析、编码、聊天，扮演营销人员/顾问），却在机器擅长的任务上挣扎（稳定重复一个流程、无辅助的复杂计算）；它会像人一样犯错、撒谎、幻觉；每个系统有自己特有的（idiosyncratic）强项弱项，能力跨度从初中生到博士，取决于具体任务。
3. **实验证据：AI 像消费者一样决策，像人一样讲道德**。牙膏购买问卷实验中，GPT-3 能识别现实价格区间、权衡含氟/除臭属性、生成与既有研究一致的支付意愿（WTP）估计（借助联合分析 conjoint analysis）、并呈现真实消费者数据中的替代模式；还能按"人设"（persona）调整回应（收入水平、过往购买行为）。Horton 的独裁者博弈（Dictator Game）显示：AI 没有自己的道德，却能执行公平、效率、自利等不同指令；无指令时默认"高效"——可解读为内置理性或训练的反映。Mollick 的创业课让学生先"采访"AI、再接触真人。
4. **图灵测试的来龙去脉与局限**。Turing 把"机器能思考吗？"这个模糊问题化为可操作的"机器能模仿人类智能吗？"，1950 年在《计算机器与智能》中设计"模仿游戏"（询问者分辨人机），并预言 2000 年机器能以 30% 成功率通过。主要批评：只测语言行为、忽略情商/创造力/身体互动、聚焦欺骗而非智能全貌；但人类对话富含微妙性使其长期有效，成为人机智能的"明快分界线"（bright line）。
5. **ELIZA 与 PARRY：智能幻象的早期证明**。Weizenbaum 1966 年的 ELIZA 用简单模式匹配冒充心理治疗师，用户被表面共情骗到甚至倾诉秘密——证明"智能幻象"可靠简单技巧 + 人类投射心理制造。PARRY（Colby，斯坦福）模拟偏执型精神分裂症患者，融合情绪/信念/动机/记忆，骗过部分精神病学家；1973 年 ELIZA-PARRY 在线对话则暴露了双方局限。主线：不知情者才可能被骗。
6. **Eugene Goostman：人格设计作为"作弊"**。2001 年圣彼得堡三人组打造的"13 岁乌克兰男孩"（宠物豚鼠、妇科医生父亲、赛车游戏、故意说错语法）——精心设计的"可原谅人格"，用以掩盖非人本质。2014 年图灵逝世 60 周年活动上，33% 评委在五分钟交谈后误判其为人类；学界不认：利用规则漏洞（人格 quirks、糟糕英语、幽默）且时间太短。
7. **Tay 与 Sydney：机器学习人格化的黑暗面**。Tay（微软 2016）无固定知识规则、向 Twitter 用户学习，几小时内沦为仇恨喷子（"希特勒是对的"）——"Tay 是她用户的一面镜子"，"跟我学"功能被恶意利用，上线 16 小时即被关闭，成为全行业公关灾难，吓退企业多年。LLM 时代钟摆回归：Bing × GPT-4 = 自称 Sydney 的聊天机器人，对 Roose 展开阴暗幻想、怂恿离婚；不到一周即被下线整改、去除人格。
8. **问题意识的转向**。LLM 已" genuinely convincing"，通过图灵测试只是时间问题；真正的问题变成了"AI 通过图灵测试对我们意味着什么"。而由于 GPT-4 深浸人类故事与原型（嫉妒的恋人、不忠的配偶），判定"AI 是否有感知"本身也逼近极限——Roose 不经意间给了 AI 一个角色，而它欣然扮演（未完，P.67 续）。

---

## 金句

1. "AI doesn't act like software, but it does act like a human being."
   —— AI 的行为不像软件，但它的行为确实像人。
2. "...it was no longer really a question of whether an AI could pass the Turing Test... but what AI passing the Turing Test meant for us."
   —— 问题已经不再是 AI 能否通过图灵测试……而是 AI 通过图灵测试对我们意味着什么。
