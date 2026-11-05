# 单元 11｜第5章 作为创造者的AI：开篇

> **书籍**：Co-Intelligence — Living and Working with AI（Ethan Mollick）
> **单元**：11/31 ｜ **页码范围**：P.79–82（4 页）｜ **完成日期**：2026-10-27

---

## 本单元讲了什么

本单元是第 5 章"作为创造者的 AI"的开篇。作者先接上原则一"永远邀请 AI 上桌"的追问——AI 像哪种人、擅长什么——然后话锋一转：要谈擅长，先谈它极不擅长的东西，即"幻觉"（hallucination）。作者剖析了幻觉的机理：LLM 靠预测最可能的下一个词元生成文本，不在乎真假与原创，只求让你满意；模型不存储文本而只存储词元共现模式，所以它并不"知道"什么，答案是现编的；为避免过拟合（overfitting）而加入的随机性又进一步推高了幻觉概率——"限制"与"长处"由此同源。训练素材的偏见、矛盾与错误同样会流入模型，而模型分不清虚构与现实：数据科学家 Colin Fraser 发现的"42 梗"（ChatGPT 被问随机数时 10% 回答"42"，皆因《银河系漫游指南》中 42 是"生命、宇宙以及一切的终极问题"之答案）是典型案例。引文是"生成"而非"检索"：名句（"八十七年前……"）因见过太多次能续对，冷门生平则被貌似合理地编造（GPT-4 坚称作者有计算机科学本科学位）；追问 AI"为什么"也得不了真相，因为它对自己的过程并无意识，只会信心十足地给出答案。随后作者讲了 2023 年律师 Schwartz 用 ChatGPT 编造六个假判例、被法院罚款五千美元的著名案例，并当场自证：他请联网版 GPT-4 复述案情，"几乎全对"却有多处小错——小幻觉最难防，因为它们完全貌似合理。最后给出审慎的乐观：随着模型进步，幻觉率在下降（研究发现 GPT-3.5 引注出错率 98%，GPT-4 仅 20%），"退格键"等技术也在提升准确性；问题或永不消失但会改善，别忘了原则四"假设这是你将使用的最差的 AI"。（句子在 P.82 页尾中断，续至单元 12）

---

## 英文原文

**AI as a Creative**

Our first principle of working with AI is to always invite it to the table. We have discussed how interacting with AI can resemble talking to and working with people. But what kind of people? What skills does an AI have? What is it good at? To talk about that, we first need to confront what AI is very bad at.

The biggest issue limiting AI is also one of its strengths: its notorious ability to make stuff up, to hallucinate. Remember that LLMs work by predicting the most likely words to follow the prompt you gave it based on the statistical patterns in its training data. It does not care if the words are true, meaningful, or original. It just wants to produce a coherent and plausible text that makes you happy.

Hallucinations sound likely and contextually appropriate enough to make it hard to tell lies from the truth.

There is no definitive answer to why LLMs hallucinate, and the contributing factors may differ among models. Different LLMs may have different architectures, training data, and objectives. But in many ways, hallucinations are a deep part of how LLMs work. They don't store text directly; rather, they store patterns about which tokens are more likely to follow others. That means the AI doesn't actually "know" anything. It makes up its answers on the fly. Plus, if it sticks too closely to the patterns in its training data, the model is said to be overfitted to that training data. Overfitted LLMs may fail to generalize to new or unseen inputs and generate irrelevant or inconsistent text—in short, their results are always similar and uninspired. To avoid this, most AIs add extra randomness in their answers, which correspondingly raises the likelihood of hallucination.

Beyond the technical, hallucinations can also come from the source material of the AI, which can be biased, incomplete, contradictory, or even wrong in ways that we discussed in chapter 2. The model has no way of distinguishing opinion or creative fictional work from fact, figurative language from literal, or unreliable sources from reliable ones. The model may inherit the biases and prejudices of the data creators, curators, and fine-tuners.

It can be funny when the AI fails to distinguish when fiction bleeds into reality. For example, Colin Fraser, a data scientist, noted that when asked for a random number between 1 and 100, ChatGPT answered "42" 10 percent of the time. If it were truly choosing a number randomly, it should answer "42" only 1 percent of the time. The science fiction nerds among my readers have probably already guessed why 42 pops up so much more often. In Douglas Adams's classic comedy The Hitchhiker's Guide to the Galaxy, 42 is the answer to the "ultimate question of life, the universe, and everything" (leaving open a bigger issue: What was the question?), and the number has become a shorthand joke on the internet. Thus, Fraser speculates that there are a lot more 42s for the AI to see than other numbers, which, in turn, increases the likelihood that AI will output that number—while hallucinating that it is giving you a random answer.

These technical issues are compounded because they rely on patterns, rather than a storehouse of data, to create answers. If you ask an AI to give you a citation or a quote, it is going to generate that quote or citation based on the connections between the data it learned, not retrieve it from memory. If the quote is famous, like "Four score and seven years ago," the AI will finish it properly: ". . . our fathers brought forth on this continent, a new nation, conceived in Liberty, and dedicated to the proposition that all men are created equal." The AI has seen those connections enough times to figure out the next word. If it is more obscure, like my biography, it will fill in the details with plausible hallucinations, like GPT-4 insisting that I have a computer science undergraduate degree. Anything that requires exact recall is likely to result in a hallucination, though giving AI the ability to use outside resources, like web searches, might change this equation.

And you can't figure out why an AI is generating a hallucination by asking it. It is not conscious of its own processes. So if you ask it to explain itself, the AI will appear to give you the right answer, but it will have nothing to do with the process that generated the original result. The system has no way of explaining its decisions, or even knowing what those decisions were. Instead, it is (you guessed it) merely generating text that it thinks will make you happy in response to your query. LLMs are not generally optimized to say "I don't know" when they don't have enough information. Instead, they will give you an answer, expressing confidence.

One of the most notorious early examples of hallucination in LLMs occurred in 2023, when a lawyer named Steven A. Schwartz used ChatGPT to prepare a legal brief for a personal injury lawsuit against an airline. Schwartz used ChatGPT to research court filings; the AI cited six fake cases. He then presented these cases to the court as real precedents, without verifying their authenticity or accuracy. The fake cases were discovered by the defense lawyers, who could not find any records of them in the legal databases. They then alerted the judge, who ordered Schwartz to explain his sources. Schwartz then admitted that he had used ChatGPT to generate the cases and that he had no intention to deceive the court or act in bad faith. He claimed that he was unaware of the nature and limitations of ChatGPT, and that he had learned about it from his college-age children.

The judge, P. Kevin Castel, was not convinced by Schwartz's explanation. He ruled that Schwartz had acted in bad faith and had misled the court by submitting false and unsupported information. He also found that Schwartz had ignored several red flags that should have alerted him to the fact that the cases were fake, such as their nonsensical names, dates, and citations. He imposed a joint $5,000 fine on Schwartz and his co-counsel, Peter LoDuca, who had taken over the case when it moved to a different jurisdiction. He also ordered them to reach out to the judges mentioned in the fake cases with information about the situation.

Those previous three paragraphs, by the way, were written by a version of GPT-4 with an internet connection. And they are almost right. According to news reports, there were more than six fake cases; LoDuca did not take over the case but merely covered for Schwartz; and part of the reason for the fine was that the lawyers doubled down on the fake cases, far beyond their initial mistake.

These small hallucinations are hard to catch because they are completely plausible. I was able to notice the issues only after an extremely close reading and research on every fact and sentence in the output. I may still have missed something (sorry, whoever fact-checks this chapter). But this is what makes hallucinations so perilous: it isn't the big issues you catch but the small ones you don't notice that can cause problems.

AI researchers have mixed opinions as to when, or even if, these problems will be solved. There is some reason to hope. As models advance, hallucination rates are dropping over time. For example, a study examining the number of hallucinations and errors in citations given by AI found that GPT-3.5 made mistakes in 98 percent of the cites, but GPT-4 hallucinated only 20 percent of the time. Additionally, technical tricks, like giving the AI a "backspace" key so it can correct and delete its own errors, seem to improve accuracy. So, while it may never go away, this problem will likely improve. Remember Principle 4: "Assume this is the worst AI you will ever use." Even today, with some experience, users can learn how to avoid forcing the AI into hallucinations and when careful fact-checking is necessary. And more discussion of this issue will prevent users like Schwartz from

（注：本句在 P.82 页尾中断，续于单元 12 开头。）

---

## 中文翻译

**作为创造者的 AI（AI as a Creative）**

我们与 AI 合作的第一条原则，是永远邀请它上桌。我们此前讨论过，与 AI 互动何以酷似与人交谈和共事。但那是哪种人？AI 身怀何种技能？它擅长什么？要谈这些，我们首先需要直面 AI 极不擅长的一面。

限制 AI 的最大问题，同时也是它的长处之一：它那出了名的"无中生有"的本事——幻觉（hallucination）。请记住，LLM 的工作方式是：基于训练数据中的统计模式，预测接在你给出的提示词（prompt）之后最可能出现的词。它不在乎这些词是真是假、有无意义、是否原创。它只想产出连贯而貌似合理的文本，让你满意。

幻觉听起来合乎情理、贴合语境，足以让人难以分辨谎言与真相。

关于 LLM 为何会产生幻觉，并没有确定的答案，不同模型的诱因也可能各异。不同的 LLM 可能有不同的架构（architectures）、训练数据（training data）和目标（objectives）。但在很多方面，幻觉是 LLM 工作方式的深层组成部分。它们并不直接存储文本；相反，它们存储的是"哪些词元（tokens）更可能跟在另一些词元之后"的模式。这意味着 AI 其实并不"知道"任何东西——它的答案是现编的。此外，如果模型过于紧贴训练数据中的模式，就被称为对训练数据过拟合（overfitted）。过拟合的 LLM 可能无法泛化（generalize）到新的或未见过的输入，生成不相关或不连贯的文本——简言之，它们的结果总是千篇一律、了无新意。为避免这一点，大多数 AI 会在回答中加入额外的随机性，而这相应地也提高了幻觉出现的概率。

除技术层面之外，幻觉也可能源自 AI 的原始素材——正如我们在第 2 章讨论过的，这些素材可能有偏见、不完整、自相矛盾，甚至根本就是错的。模型无从区分观点或虚构创作与事实、比喻义与字面义、不可靠来源与可靠来源。它还可能继承数据创建者、整理者和微调者（fine-tuners）的偏见与成见。

当 AI 分不清虚构何时渗入现实时，事情可能变得有趣。例如，数据科学家 Colin Fraser 注意到，当被要求给一个 1 到 100 之间的随机数时，ChatGPT 有 10% 的次数回答"42"。如果它真的是在随机选数，回答"42"的概率应该只有 1%。我读者中的科幻迷大概已经猜到"42"为何出现得如此频繁。在道格拉斯·亚当斯（Douglas Adams）的经典喜剧《银河系漫游指南》（The Hitchhiker's Guide to the Galaxy）中，42 是"关于生命、宇宙以及一切的终极问题"的答案（这留下了一个更大的问题：问题是什么？），而这个数字也成了互联网上的一个梗。因此，Fraser 推测，AI 在训练数据里看到的"42"远多于其他数字，这反过来增加了 AI 输出这个数字的概率——同时幻觉般地以为自己在随机回答你。

这些技术问题之所以更加棘手，是因为它们靠模式而非数据仓库来生成答案。如果你让 AI 给出一段引文或出处，它会基于学到的数据之间的关联来生成这段引文或出处，而不是从记忆中检索。如果引文很有名，比如"Four score and seven years ago"（八十七年前），AI 会正确地续完："……我们的先辈在这片大陆上创立了一个新国家，它孕育于自由之中，奉行人人生而平等的主张。"AI 见过足够多的这类关联，足以推想出下一个词。如果引文较为冷门——比如我的生平简介——它就会用貌似合理的幻觉来填补细节，比如 GPT-4 坚称我有计算机科学本科学位。任何需要精确回忆的内容都可能引发幻觉，尽管赋予 AI 使用外部资源（比如网页搜索）的能力，或许会改变这个等式。

而且，你没法通过问 AI 来弄清它为何产生幻觉——它对自己的处理过程并无意识。所以如果你让它解释自己，AI 会显得给出了正确答案，但那与其生成原始结果的过程毫无关系。这个系统无法解释它的决策，甚至不知道那些决策是什么。相反，它（你猜对了）只是在生成它认为会让你满意的文本，用来回应你的提问。LLM 通常并没有被优化成"在信息不足时说'我不知道'"；相反，它们会给你一个答案，并显得信心十足。

LLM 早期最臭名昭著的幻觉案例之一发生在 2023 年：一位名叫 Steven A. Schwartz 的律师用 ChatGPT 为一桩针对航空公司的个人伤害诉讼准备法律简报。Schwartz 用 ChatGPT 检索法庭案卷；AI 引用了六个虚构的判例。他随后将这些判例当作真实的先例（precedents）提交给法庭，没有核验其真实性或准确性。这些假判例被辩方律师发现——他们在法律数据库中找不到任何相关记录。他们随即将此事告知法官，法官命令 Schwartz 说明其来源。Schwartz 随后承认，这些判例是他用 ChatGPT 生成的，他无意欺骗法庭，也没有恶意。他声称自己当时不了解 ChatGPT 的性质和局限，而且是从他大学年纪的孩子那里听说它的。

法官 P. Kevin Castel 并不信服 Schwartz 的解释。他裁定 Schwartz 存在恶意，通过提交虚假且无依据的信息误导了法庭。他还认定，Schwartz 忽视了几个本应让他警觉到判例是假的红旗信号（red flags），比如那些判例在名称、日期和引注上的荒谬之处。他对 Schwartz 和他的联席律师（co-counsel）Peter LoDuca 处以合计 5000 美元的罚款——后者在这起案件移送到另一司法辖区时接手。法官还命令他们联系假判例中提及的各位法官，说明相关情况。

顺便说一句，前面这三段是一个联网版 GPT-4 写的。而它们几乎是对的。据新闻报道，假判例其实不止六个；LoDuca 并没有接手案件，只是替 Schwartz 顶班；罚款的部分原因还在于这两位律师在假判例上变本加厉，远远超出了最初的错误。

这些小型幻觉难以察觉，因为它们完全貌似合理。我只有在极度仔细地阅读、并对输出中的每一个事实和句子做了研究之后，才注意到了这些问题。我可能还是漏掉了什么（对不起，本章的事实核查员）。但这正是幻觉如此危险的原因：造成麻烦的不是你抓住的大问题，而是你没注意到的小问题。

AI 研究人员对于这些问题何时——甚至是否——能够解决，意见不一。但仍有希望的理由：随着模型进步，幻觉率（hallucination rates）随时间下降。例如，一项考察 AI 给出的引注（cites）中幻觉与错误数量的研究发现，GPT-3.5 在 98% 的引注中出错，而 GPT-4 幻觉的比例只有 20%。此外，一些技术手段——比如给 AI 一个"退格键"（backspace），让它能改正和删除自己的错误——似乎也能提升准确性。所以，尽管这个问题可能永远不会消失，它很可能会改善。请记住原则四："假设这是你将使用的最差的 AI（Assume this is the worst AI you will ever use）。"即便是今天，只要有些经验，用户就能学会如何避免逼 AI 产生幻觉，以及何时需要仔细的事实核查。而对这个问题的更多讨论，将防止像 Schwartz 这样的用户……

---

## 核心观点

1. **幻觉是 AI 最大的短板，也是创造力的影子**：限制 AI 的最大问题同时也是其长处之一——"无中生有"（make stuff up）的能力。LLM 只预测最可能的后续词元，"不在乎真假、意义、原创"，只想产出让你满意的连贯文本；幻觉听上去合情合理、贴合语境，让人难辨真伪。
2. **幻觉机理深植于 LLM 的工作方式**：为何幻觉没有确定答案（架构、数据、目标各异），但深层原因是模型不存储文本、只存储"哪些 token 更可能跟随哪些 token"的模式——AI 并不"知道"什么，答案是现编的。过拟合（overfitting）会让输出千篇一律，为免于此而加入的随机性又进一步推高幻觉概率——这是"限制"与"长处"同源的深层原因。
3. **数据源头也会"投毒"**：除技术因素外，训练素材的偏见、不完整、矛盾、错误（第 2 章已讨论）都会流入模型；模型分不清观点/虚构与事实、比喻与字面、可靠与不可靠来源，会继承数据创建者、整理者、微调者（fine-tuners）的偏见。
4. **"42 梗"：虚构渗入现实的幽默案例**：数据科学家 Colin Fraser 发现 ChatGPT 被问 1–100 随机数时 10% 回答"42"（真随机应约 1%），因为《银河系漫游指南》中 42 是"生命、宇宙以及一切的终极问题"之答案、已成网络梗——AI 见到更多 42 于是更可能输出它，同时幻觉地以为自己在随机作答。
5. **引用是"生成"而非"检索"**：模型靠数据之间的关联生成引文——名句（"八十七年前……"）因见过太多次能续对；冷门内容（如作者生平）则被貌似合理地编造（GPT-4 坚称作者有计算机科学本科学位）。凡需精确回忆（exact recall）处皆易幻觉；联网等外部资源可能改变这个等式。
6. **问 AI"为什么"得不到真相**：AI 对自己的处理过程无意识，追问只能得到"显得正确"却与真实过程无关的解释；系统无法解释、甚至不知道自己的决策。LLM 未被优化为说"我不知道"，只会信心十足地给出答案。
7. **Schwartz 假判例案**：2023 年律师用 ChatGPT 检索案卷，AI 编造六个假判例，未核验即提交法庭；被辩方揭穿后，法官认定其忽视名称、日期、引注荒谬等红旗信号（red flags），与联席律师合计罚款 5000 美元，并令其联系假判例所涉法官。
8. **作者的自证：请 GPT-4 写案情回顾，"几乎对"但有小错**：联网版 GPT-4 的三段复述看似准确，实则假判例数量、LoDuca 角色、罚款加重原因均有出入——小幻觉最难防，因为它们完全貌似合理；造成麻烦的不是你抓住的大错，而是你没注意到的小错。
9. **审慎的乐观：幻觉率在下降，原则四依然适用**：研究人员意见不一但有理由抱有希望——GPT-3.5 引注出错率 98%，GPT-4 仅 20%；"退格键"（backspace）等技术手段提升准确性。问题或永不消失但会改善；记住原则四"假设这是你将使用的最差的 AI"，用户可学会避免逼 AI 幻觉、知道何时需要仔细核查。（未完，续于单元 12）

---

## 金句

1. "The biggest issue limiting AI is also one of its strengths: its notorious ability to make stuff up, to hallucinate."
   —— 限制 AI 的最大问题，同时也是它的长处之一：它那出了名的"无中生有"的本事——幻觉。
2. "But this is what makes hallucinations so perilous: it isn't the big issues you catch but the small ones you don't notice that can cause problems."
   —— 但这正是幻觉如此危险的原因：造成麻烦的不是你抓住的大问题，而是你没注意到的小问题。
