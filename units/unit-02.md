# 单元 02｜第1章 创造外星思维（上）

> **书籍**：Co-Intelligence — Living and Working with AI（Ethan Mollick）
> **单元**：2/31 ｜ **页码范围**：P.12–21（10 页）｜ **完成日期**：2026-10-17

---

## 本单元讲了什么

本单元从历史一路讲到当下，回答一个问题：让我们兴奋的 AI，究竟是怎么来的？开篇先破除名词混乱——从 1770 年骗过拿破仑的"土耳其行棋傀儡"，到 1950 年香农的机械鼠忒修斯与图灵的"模仿游戏"，再到 1956 年"人工智能"正式命名后的多轮炒作与"AI 寒冬"。2010 年代，监督学习让预测式 AI 在大机构落地（亚马逊供应链是巅峰），但它不懂语言、普通人无感。真正的分水岭是 2017 年谷歌的 Transformer 论文《Attention Is All You Need》——注意力机制让机器第一次"知道句子里哪个词重要"。在此基础上，大语言模型（LLM）诞生：本质上仍是预测，但预测的是下一个词元，技术上是"超级自动补全"；它通过无监督预训练从数十亿词汇中自学出上千亿个权重，再经 RLHF 等微调长出行为与伦理边界。单元末尾把视野扩展到 LLM 之外：扩散模型生成图像，多模态 LLM 正在同时获得"看"与"画"的能力。一句话：本单元给出了全书的"技术底座"——后文所有关于共创、伦理、岗位、教育的讨论，都建立在这些机制之上。

---

## 英文原文

**1 — CREATING ALIEN MINDS**

Talking about AI can be confusing, in part because AI has meant so many different things and they all tend to get muddled together. Siri telling you a joke on command. The Terminator crushing a skull. Algorithms predicting credit scores.

We've long had a fascination with machines that can think. In 1770, the invention of the first mechanical chess computer stunned those who saw it—a chessboard set upon an elaborate cabinet, with its chess pieces manipulated by a robot dressed as an Ottoman wizard. It toured the world from 1770 to 1838. The machine, also known as the Mechanical Turk, beat Ben Franklin and Napoleon in chess matches and led Edgar Allan Poe to speculate on the possibility of artificial intelligence upon seeing it in the 1830s. It was all a lie, of course—the machine cleverly hid a real chess master inside its fake gears, but our ability to believe that machines might be able to think fooled many of the best minds in the world for three quarters of a century.

Fast-forward to 1950, when a toy and a thought experiment, each developed by a different genius of the still-developing field of computer science, led to a new conception of artificial intelligence. The toy was a jury-rigged mechanical mouse called Theseus, developed by Claude Shannon, an inventor, prankster, and the greatest information theorist of the twentieth century. In a 1950 film, he revealed that Theseus, powered by repurposed telephone switches, could navigate through a complex maze—the first real example of machine learning. The thought experiment was the imitation game, where computer pioneer Alan Turing first laid out the theories about how a machine could develop a level of functionality sufficient to mimic a person. While computers were a very new invention, Turing's influential paper helped kick off the nascent field of artificial intelligence.

Theories alone were not enough, and a handful of early computer scientists started working on programs that pushed the boundaries of what was soon called artificial intelligence, a term invented in 1956 by John McCarthy of MIT. Progress was initially rapid as computers were programmed to solve logic problems and play checkers—leading researchers expected an AI to beat grandmasters in chess within a decade. But hype cycles have always plagued AI, and as these promises went unfulfilled, disillusionment set in, one of many "AI winters" in which AI progress stalls and funding dries up. Other boom-and-bust cycles followed, each boom accompanied by major technological advances, such as artificial neural networks that mimicked the human brain, followed by collapse as AI could not deliver on expected goals.

The latest AI boom started in the 2010s with the promise of using machine learning techniques for data analysis and prediction. Many of these applications used a technique called supervised learning, which means these forms of AI needed labeled data to learn from. Labeled data is data that has been annotated with the correct answers or outputs for a given task. For example, if you want to train an AI system to recognize faces, you need to provide it with images of faces that have been labeled with the names or identities of the people in them. This phase of AI was the domain of larger organizations that had vast amounts of data. They used these tools as powerful prediction systems, whether optimizing shipping logistics or guessing what kind of content to show you based on your browsing history. You might have heard the buzzwords big data or algorithmic decision-making describing these kinds of uses. Consumers mostly saw the benefits of machine learning when these techniques were integrated into tools such as voice recognition systems or translation apps. AI was a poor (albeit marketing-friendly) label for what this sort of software did, since there was very little about these systems that actually seemed intelligent or clever, at least in the ways humans are intelligent and clever.

To see one example of how this sort of AI works, picture a hotel attempting to forecast its demand for the upcoming year, armed with nothing but existing data and a simple Excel spreadsheet. Before predictive AI, hotel owners would often be left playing a guessing game, trying to predict demand while grappling with inefficiencies and wasted resources. With this form of AI, they could instead input a wealth of data—weather patterns, local events, and competitor pricing—and generate far more accurate predictions. The results were a more efficient operation and, ultimately, a more profitable business. Before machine learning and natural language processing became mainstream, organizations focused on being correct on average—a rather rudimentary approach by today's standards. With the introduction of AI algorithms, the focus shifted to statistical analysis and minimizing variance. Instead of being right on average, they could be right for each specific instance, leading to more accurate predictions that revolutionized many back-office functions, from managing customer service to helping run supply chains.

These predictive AI technologies may have found their ultimate expression at the retail giant Amazon, which deeply embraced this form of AI in the 2010s. At the heart of Amazon's logistical prowess lies its AI algorithms, silently orchestrating every stage of the supply chain. Amazon integrated AI into forecasting demand, optimizing its warehouse layouts, and delivering its goods. It also intelligently organizes and rearranges shelves based on real-time demand data, ensuring that popular products are easily accessible for quick shipping. AI also powered Amazon's Kiva robots, which transported shelves of products to warehouse workers, making the packing and shipping process more efficient. The robots themselves rely on other AI advances, including those in computer vision and automated driving.

However, these types of AI systems were not without limitations. For instance, they struggled with predicting "unknown unknowns," or situations that humans intuitively understand but machines do not. Additionally, they had difficulty with data they had not yet encountered through supervised learning, which posed challenges to their adaptability. And, most important, most AI models were also limited in their ability to understand and generate text in a coherent and context-aware manner. Thus, while these uses of AI are still important today, they were not something most people directly saw or noticed in their daily lives.

But among the many papers on different forms of AI being published by industry and academic experts, one stood out, a paper with the catchy title "Attention Is All You Need." Published by Google researchers in 2017, this paper introduced a significant shift in the world of AI, particularly in how computers understand and process human language. This paper proposed a new architecture, called the Transformer, that could be used to help a computer better process how humans communicate. Before the Transformer, other methods were used to teach computers to understand language, but they had limitations that severely curtailed their usefulness. The Transformer solved these issues by utilizing an "attention mechanism." This technique allows the AI to concentrate on the most relevant parts of a text, making it easier for the AI to understand and work with language in a way that seemed more human.

When reading, we know that the last word we read in a sentence is not always the most important one, but machines struggled with this concept. The result was awkward-sounding sentences that were clearly computer generated. TALKING ABOUT HOW ALGORITHMS SILENTLY ORCHESTRATING EVERY ITEM is how a Markov chain generator, an early form of text generation AI, wanted to continue this paragraph. Early text generators relied on selecting words according to basic rules, rather than reading context clues, which is why the iPhone keyboard would show so many bad autocomplete suggestions. Solving the problem of understanding language was very complex, as there were many words that could be combined in many ways, making a formulaic statistical approach impossible. The attention mechanism helps solve this problem by allowing the AI model to weigh the importance of different words or phrases in a block of text. By focusing on the most relevant parts of the text, Transformers can produce more context-aware and coherent writing compared to earlier predictive AIs. Building on the strides of the Transformer architecture, we now find ourselves in an era when AI, like me, can generate contextually rich content, showcasing the remarkable evolution of machine comprehension and expression. (And, yes, that last sentence was AI-produced text—a big difference from the Markov chain!)

These new types of AI, called Large Language Models (LLMs), are still doing prediction, but rather than predicting the demand for an Amazon order, they are analyzing a piece of text and predicting the next token, which is simply a word or part of a word. Ultimately, that is all ChatGPT does technically—act as a very elaborate autocomplete like you have on your phone. You give it some initial text, and it keeps writing text based on what it statistically calculates as the most likely next token in the sequence. If you type "Finish this sentence: I think, therefore I...," the AI will predict the next word will be am every time, because it is incredibly probable that this is the case. If you type something weirder, like "The Martian ate the banana because," you will get different answers every time: "it was the only familiar food available in the spacecraft's pantry," "it was a new and interesting food that he had never tried before and he wanted to experience the taste and texture of this Earthly fruit," or "it was part of an experiment to test the suitability of Earth's food for consumption on Mars." This is because there are many more possible answers for the second half of the sentence, and most LLMs add a little randomness to their answers, which ensures slightly different results each time you ask them a question.

To teach AI how to understand and generate humanlike writing, it is trained on a massive amount of text from various sources, such as websites, books, and other digital documents. This is called pretraining, and unlike earlier forms of AI, it is unsupervised, which means the AI doesn't need carefully labeled data. Instead, by analyzing these examples, AI learns to recognize patterns, structures, and context in human language. Remarkably, with a vast number of adjustable parameters (called weights), LLMs can create a model that emulates how humans communicate through written text. Weights are complex mathematical transformations that LLMs learn from reading those billions of words, and they tell the AI how likely different words or parts of words are to appear together or in a certain order. The original ChatGPT had 175 billion weights, encoding the connection between words and parts of words. No one programmed these weights; instead, they are learned by the AI itself during its training.

Imagine an LLM as a diligent apprentice chef who aspires to become a master chef. To learn the culinary arts, the apprentice starts by reading and studying a vast collection of recipes from around the world. Each recipe represents a piece of text, with various ingredients symbolizing words and phrases. The apprentice's goal is to understand how to combine different ingredients (words) to create a delicious dish (coherent text).

The apprentice chef begins with a chaotic, disorganized pantry, representing the 175 billion weights. Initially, these weights have random values and do not yet contain any useful information about how words are related. To build their knowledge and refine the spice rack, the apprentice chef goes through a process of trial and error, learning from the recipes they have studied. It finds that certain flavors are more common and go better together—like apples and cinnamon—and certain flavors are rare because they should be avoided—like apples and cumin. During training, the apprentice chef attempts to re-create the dishes from the recipes using their current pantry. After each attempt, the apprentice compares their creation to the original recipe and identifies any mistakes or discrepancies. The apprentice then reconsiders the ingredients in the pantry, refining the connections between flavors to better understand how likely they are to be used together or in a particular sequence.

Over time, and through countless iterations, the apprentice chef's pantry becomes more organized and accurate. The weights now reflect meaningful connections between words and phrases, and the apprentice has transformed into a master chef. When given a prompt, the master chef artfully selects the right ingredients from their vast repertoire and consults their refined spice rack to ensure the perfect balance of flavors. In an analogous way, AI creates humanlike written text that is engaging, informative, and relevant to the topic at hand.

Training an AI to do this is an iterative process, and requires powerful computers to handle the immense calculations involved in learning from billions of words. This pretraining phase is one of the main reasons AIs are so expensive to build. The need for fast computers, with very expensive chips, to run for months in pretraining is largely responsible for the fact that more advanced LLMs cost over $100 million to train, using large amounts of energy in the process.

Many of the AI companies keep the source text they train from, called training corpuses, secret, but a typical example of training data largely consists of text pulled from the internet, public domain books and research articles, and assorted other free sources of content that researchers can find. Actually looking into these sources in detail reveals some odd material. For example, the entire email database of Enron, shut down for corporate fraud, is used as part of the training material for many AIs, simply because it was made freely available to AI researchers. Similarly, there is a tremendous amount of amateur romance novels included in training data, as the internet is full of amateur novelists. The search for high-quality content for training material has become a major topic in AI development, since information-hungry AI companies are running out of good, free sources.

As a result, it is also likely that most AI training data contains copyrighted information, like books used without permission, whether by accident or on purpose. The legal implications of this are still unclear. Since the data is used to create weights, and not directly copied into the AI systems, some experts consider it to be outside standard copyright law. In the coming years, these issues are likely to be resolved by courts and legal systems, but they create a cloud of uncertainty, both ethically and legally, over this early stage of AI training. In the meantime, AI companies are searching for more data to use for training (one estimate suggests that high-quality data, like online books and academic articles, will be exhausted by 2026), and continue to use lower-quality data as well. There is also active research into understanding whether AI can pretrain on its own content. This is what chess-playing AIs already do, learning by playing games against themselves, but it is not yet clear whether it will work for LLMs.

Because of the variety of data sources used, learning is not always a good thing. AI can also learn biases, errors, and falsehoods from the data it sees. Just out of pretraining, the AI also doesn't necessarily produce the sorts of outcomes that people would expect in response to a prompt. And, potentially worse, it has no ethical boundaries and would be happy to give advice on how to embezzle money, commit murder, or stalk someone online. LLMs in this pretrained mode just reflect back whatever they were trained on, like a mirror, without applying any judgment. So, after learning from all the text examples in pretraining, many LLMs undergo further improvement in a second stage, called fine-tuning.

One important fine-tuning approach is to bring humans into the process, which had previously been mostly automated. AI companies hire workers, some highly paid experts, others low-paid contract workers in English-speaking nations like Kenya, to read AI answers and judge them on various characteristics. In some cases, that might be rating results for accuracy, in others it might be to screen out violent or pornographic answers. That feedback is then used to do additional training, fine-tuning the AI's performance to fit the preferences of the human, providing additional learning that reinforces good answers and reduces bad answers, which is why the process is called Reinforcement Learning from Human Feedback (RLHF).

After an AI has gone through this initial phase of reinforcement learning, they can continue to be fine-tuned and adjusted. This type of fine-tuning is usually done by providing more specific examples to create a new tweaked model. That information can be provided by a specific customer trying to fit the model to its use case, for example a company feeding it examples of customer support transcripts along with good responses. Or the information could come from watching which kinds of answers get a "thumbs-up" or "thumbs-down" from users. This additional fine-tuning can make the responses of the model more specific to a particular need.

When we discuss AI in this book, we will mostly be discussing Large Language Models built in this way, but they are not the only kind of "generative AI" that are causing transformation and change. In the same year that ChatGPT had its breakthrough moment, a separate set of AIs, those designed to create images, also appeared on the market with names like Midjourney and DALL-E. These AI tools can create high-quality images based on prompts from users, either aping the style of famous artists ("draw Mickey Mouse in the style of Van Gogh") or creating ultrarealistic photographs that are indistinguishable from real ones.

Just like LLMs, these tools had been in development for years, though only recently did the technology allow for them to become truly useful. Rather than learning from text, these models are trained by analyzing lots of images paired with relevant text captions describing what's in each picture. The model learns to associate words with visual concepts. They then start with a randomized background image that looks like old-fashioned television static, and use a process called diffusion to turn random noise into a clear image by gradually refining it over multiple steps. Each step removes a bit more noise based on the text description, until a realistic image emerges. Once trained, diffusion models can take just a text prompt and generate a unique image matching that description. Unlike language models that produce text, diffusion models specialize in visual outputs, inventing pictures from scratch based on the words provided.

But LLMs are learning to work with images as well, gaining the ability to both "see" and make pictures. These multimodal LLMs combine the powers of language models and image generators. They employ Transformer architectures to process text but also use extra components to work with images. This allows an LLM to link visual concepts with text and to gain an understanding of the visual world around them. Give a multimodal LLM a terrible hand-drawn picture of an airplane surrounded by hearts (as I just did), and it says, "I think it's a cute drawing of an airplane with hearts around it. It looks like you are fond of flying or someone who flies. Maybe you are a pilot or have a loved one who is a pilot. Or maybe you just like to travel and explore new places." It can then use its much better drawing skills to provide an even better version of the picture, which it also did. Most large LLMs are gaining multimodal capability, which will allow them to learn about the world in new and unpredictable ways.

---

## 中文翻译

**第 1 章 创造外星思维**

谈 AI 容易让人糊涂，部分原因是"AI"这个词承载了太多不同的含义，而它们又总是被混为一谈：Siri 应声讲个笑话，《终结者》捏碎一个骷髅，算法预测信用评分。

我们着迷于"会思考的机器"已久。1770 年，第一台机械弈棋机的发明震惊了所有见过它的人——一副棋盘架在一座精致的柜子上，棋子的移动由一个装扮成奥斯曼巫师的机器人完成。它从 1770 年到 1838 年周游世界。这台机器又名"土耳其行棋傀儡"（Mechanical Turk），在对局中击败了本杰明·富兰克林和拿破仑，还引得埃德加·爱伦·坡在 19 世纪 30 年代见过它之后，开始思索人工智能的可能性。当然，这一切都是个骗局——机器在假齿轮背后巧妙地藏着一位真正的象棋大师——但我们愿意相信"机器也许会思考"的倾向，骗过了世上最优秀的一批头脑，长达四分之三个世纪。

快进到 1950 年：一个玩具和一场思想实验——分别出自仍在发展中的计算机科学领域的两位天才之手——催生了人工智能的新概念。那个玩具是一只临时拼凑的机械鼠，名叫忒修斯（Theseus），由克劳德·香农发明——他是发明家、爱搞恶作剧的人，也是二十世纪最伟大的信息论学者。在 1950 年的一部影片中，他展示了忒修斯如何依靠改装的电话交换机驱动，在复杂的迷宫中穿行——这是机器学习的第一个真实案例。而那场思想实验，则是"模仿游戏"（imitation game）：计算机先驱艾伦·图灵在其中首次系统阐述了一台机器如何才能发展出足以模仿人的功能水平。当时计算机还是极新的发明，图灵那篇影响深远的论文，帮助开启了人工智能这一新生领域。

仅有理论还不够，少数早期计算机科学家开始编写程序，去挑战不久后被命名为"人工智能"（artificial intelligence）的边界——这个词由麻省理工学院的约翰·麦卡锡在 1956 年造出。进展最初很迅猛：计算机被编程来解逻辑题、下跳棋，领军研究者曾预期 AI 将在十年内击败象棋特级大师。但炒作周期从来都是 AI 的痼疾；随着承诺落空，幻灭感降临——这是多次"AI 寒冬"（AI winter）中的一次，AI 进展停滞、资金枯竭。此后又有若干轮兴衰循环：每一轮繁荣都伴随着重大技术进步，比如模仿人脑的人工神经网络；每一轮又都因 AI 无法兑现预期目标而崩塌。

最新一轮 AI 繁荣始于 21 世纪 10 年代，承诺用机器学习技术做数据分析和预测。这些应用中许多使用一种叫"监督学习"（supervised learning）的技术，意味着这类 AI 需要带标注的数据来学习。标注数据（labeled data）指已被标注了给定任务正确答案或输出的数据。比如，你想训练一个识别人脸的 AI 系统，就需要提供人脸图片，并标注图中人物的姓名或身份。这一阶段的 AI 是拥有海量数据的大机构的地盘。它们把这些工具当作强大的预测系统——无论是优化航运物流，还是根据你的浏览历史猜测该给你推送什么内容。你或许听过"大数据"（big data）、"算法决策"（algorithmic decision-making）这类热词，描述的就是这类用途。消费者大多是在这些技术被集成进语音识别系统或翻译 App 等工具时，才感受到机器学习的好处。"AI"这个词用来形容这类软件其实是拙劣的（尽管利于营销），因为这些系统里几乎没有什么东西，真正称得上人类意义上的聪明。

要举例说明这类 AI 如何工作，不妨设想一家酒店试图预测来年的需求，手里只有现有数据和一张简单的 Excel 表格。在预测式 AI 出现之前，酒店老板常常只能猜谜，一边试图预测需求，一边应付低效与资源浪费。有了这种 AI，他们可以输入海量数据——天气模式、本地活动、竞争对手定价——生成远为准确的预测。结果是运营更高效，生意更赚钱。在机器学习和自然语言处理成为主流之前，组织的目标是"平均而言正确"——以今天的标准看是相当粗糙的做法。随着 AI 算法的引入，重点转向统计分析和最小化方差：不再是平均正确，而是对每一个具体实例都正确，从而带来更准确的预测，彻底改变了许多后台职能，从管理客服到支撑供应链。

这类预测式 AI 技术，或许在零售巨头亚马逊身上找到了终极表达——亚马逊在 21 世纪 10 年代深度拥抱了这种 AI。亚马逊物流能力的核心，是它的 AI 算法，静默地编排着供应链的每一个环节。亚马逊把 AI 用于需求预测、优化仓库布局、配送商品。它还根据实时需求数据智能地组织和重排货架，确保热门商品触手可及、快速发货。AI 还为亚马逊的 Kiva 机器人提供动力——它们把整架整架的商品运送给仓库工人，让分拣和发货流程更高效。这些机器人本身又依赖其他 AI 进展，包括计算机视觉和自动驾驶方面的突破。

然而，这类 AI 系统并非没有局限。例如，它们难以预测"未知的未知"（unknown unknowns）——即人类凭直觉能理解、机器却无法理解的情形。此外，面对监督学习尚未接触过的数据，它们也力不从心，这给它们的适应性带来了挑战。而最重要的是，大多数 AI 模型理解和生成连贯、有上下文意识的文本的能力都很有限。因此，尽管 AI 的这些用途今天依然重要，大多数人在日常生活中并不能直接看到或注意到它们。

但在产业界和学术界专家发表的众多 AI 论文中，有一篇脱颖而出——它的标题很抓人：《你需要的只是注意力》（"Attention Is All You Need"）。这篇论文由谷歌研究者于 2017 年发表，在 AI 世界、尤其是计算机理解和处理人类语言的方式上，带来了重大转变。论文提出了一种名为 Transformer 的新架构，可以帮助计算机更好地处理人类的交流方式。在 Transformer 之前，人们也用其他方法教计算机理解语言，但那些方法的局限严重限制了它们的用处。Transformer 利用一种"注意力机制"（attention mechanism）解决了这些问题。这项技术让 AI 能够聚焦于文本中最相关的部分，使它更容易以一种更接近人的方式理解和处理语言。

阅读时我们都知道，一个句子里最后一个词未必是最重要的词，但机器很难理解这一点。其结果就是那些明显由计算机生成的、听起来彆扭的句子。"谈论算法如何静默地编排每一个条目"——这就是一个马尔可夫链生成器（Markov chain generator，早期的一种文本生成 AI）想续写本段的方式。早期的文本生成器依赖基本规则选词，而不是阅读上下文线索，这就是为什么 iPhone 键盘会给出那么多糟糕的自动补全建议。理解语言这个问题非常复杂，因为词可以有许多组合方式，让公式化的统计方法无路可走。注意力机制有助于解决这个问题：它让 AI 模型能够衡量一段文本中不同词或短语的重要性。通过聚焦于文本最相关的部分，Transformer 能比早期的预测式 AI 生成更懂上下文、更连贯的文字。站在 Transformer 架构的肩膀上，我们如今进入了一个 AI——比如我——能够生成上下文丰富内容的时代，展示了机器理解与表达能力的惊人进化。（没错，最后一句话就是 AI 生成的文字——和马尔可夫链相比真是天壤之别！）

这类新型 AI 被称为大语言模型（Large Language Models, LLM）。它们依然在做预测，但预测的不再是亚马逊订单的需求，而是分析一段文本、预测下一个词元（token）——简单说就是一个词或词的一部分。归根结底，ChatGPT 技术上所做的全部事情，就是这个——一个像你手机里那样的超级精致的自动补全。你给它一些初始文本，它就根据统计上算出的"序列中最可能的下一个词元"不断续写。如果你输入"补全这个句子：我思，故我……"，AI 每次都会预测下一个词是"在"，因为这种情况的概率高得惊人。如果你输入更古怪的句子，比如"火星人吃掉了香蕉，因为"，你每次会得到不同的答案："它是航天器食品柜里唯一熟悉的食物""这是一种他从未尝过的新奇食物，他想体验这种地球水果的味道和口感"或者"这是为了检验地球食物是否适合在火星上食用而做的一项实验"。因为句子后半部分有更多可能的答案，而大多数 LLM 会在输出中加入一点点随机性，这确保了你每次提问都会得到略有不同的结果。

要教会 AI 理解和生成类人的文字，需要让它接受海量文本的训练，来源包括网站、书籍和其他数字文档。这叫做预训练（pretraining）；与早期的 AI 不同，它是无监督的（unsupervised）——AI 不需要精心标注的数据。相反，通过分析这些样本，AI 学会识别人类语言中的模式、结构和上下文。了不起的是，凭借海量可调参数（称为权重，weights），LLM 能够建立一个模型，模拟人类如何通过书面文字交流。权重是 LLM 从阅读数十亿词汇中学到的复杂数学变换，它们告诉 AI 不同的词或词的部分以多大概率一起出现或以某种顺序出现。最初的 ChatGPT 有 1750 亿个权重，编码了词与词的部分之间的关联。这些权重没有经人编程；相反，它们是 AI 在训练过程中自己学到的。

把 LLM 想象成一个立志成为大厨的勤勉学徒。为了学习烹饪技艺，学徒先阅读和研究来自世界各地的海量菜谱。每份菜谱代表一段文本，各种食材象征词和短语。学徒的目标是理解如何把不同的食材（词）组合成一道美味佳肴（连贯的文本）。

学徒厨师从一个混乱无序的食品储藏室开始，它代表那 1750 亿个权重。最初，这些权重是随机值，还不包含任何关于词如何关联的有用信息。为了积累知识、调好香料架，学徒厨师经历反复试错，从研习过的菜谱中学习。他发现某些味道更常见、更搭——比如苹果配肉桂；某些味道罕见，因为本该避开——比如苹果配孜然。训练期间，学徒厨师尝试用当前的储藏室复现菜谱中的菜品。每次尝试后，他把作品与原菜谱对比，找出错误和出入。然后他重新思考储藏室里的食材，细化味道之间的关联，以更好地理解它们以多大概率被组合使用或以何种顺序出现。

随着时间推移和无数次迭代，学徒厨师的储藏室变得更有条理、更准确。权重如今反映了词与短语之间有意义的关联，学徒也已蜕变为大厨。接到提示词时，大厨从庞大的技艺库中娴熟地选取恰当的食材，并参考调好的香料架，确保味道完美平衡。类似地，AI 创造出引人入胜、信息丰富、切题的人类化文字。

训练 AI 做到这一点是一个迭代过程，需要强大的计算机来处理从数十亿词汇中学习所涉及的巨大计算量。这个预训练阶段是 AI 造价高昂的主要原因之一。需要配备昂贵芯片的高速计算机连续运转数月做预训练，这在很大程度上导致了更先进的 LLM 训练成本超过 1 亿美元，过程中还消耗大量能源。

许多 AI 公司把它们训练所用的源文本——称为训练语料库（training corpuses）——保密，但典型的训练数据主要由从互联网抓取的文本、公版书和研究文章，以及研究者能找到的其他免费内容构成。真正细看这些来源，会发现一些古怪材料。例如，因公司欺诈而倒闭的安然公司（Enron）的整个邮件数据库，就被用作许多 AI 的训练材料，只因为它被免费提供给了 AI 研究者。类似地，训练数据中还海量收录了业余爱情小说，因为互联网上到处都是业余小说家。为训练材料寻找高质量内容，已成为 AI 开发的一大课题，因为如饥似渴的 AI 公司正在耗尽优质的免费来源。

因此，大多数 AI 训练数据中很可能也包含受版权保护的信息，比如未经许可使用的书籍——无论偶然还是故意。其法律含义至今不明。由于数据被用于生成权重，而不是被直接复制进 AI 系统，一些专家认为这超出了标准版权法的管辖范围。未来几年，这些问题很可能由法院和法律体系裁决，但它们给 AI 训练的早期阶段蒙上了伦理和法律上的不确定性阴云。与此同时，AI 公司正在搜寻更多训练数据（一项估计认为，像网络书籍和学术文章这样的高质量数据将在 2026 年被耗尽），并继续使用质量较低的数据。也有活跃的研究在探讨 AI 能否在自己的内容上预训练。国际象棋 AI 已经这么做了——通过与自己博弈来学习——但这是否适用于 LLM 尚不清楚。

因为数据来源多样，学习并不总是好事。AI 也会从数据中学到偏见、错误和虚假信息。刚从预训练出来的 AI，也未必会给出人们对提示词所预期的那类回应。而潜在更糟的是，它没有伦理边界，会很乐意给出如何贪污公款、杀人或网上跟踪别人的建议。处于预训练模式的 LLM 就像一面镜子，只是反射它被训练的内容，不作任何判断。因此，在从预训练的所有文本样本中学完之后，许多 LLM 会进入第二阶段进一步改进，称为微调（fine-tuning）。

一种重要的微调方法是把人类纳入流程——此前的流程大多是自动化的。AI 公司雇佣员工，有些是高薪专家，有些是肯尼亚等英语国家的低薪合同工，来阅读 AI 的回答，并按各种特征给它们打分。有时是给结果的准确性评分，有时是筛掉暴力或色情回答。这些反馈随后被用于额外训练，微调 AI 的表现以契合人类偏好，提供强化好答案、减少坏答案的额外学习——这个过程因此被称为"基于人类反馈的强化学习"（Reinforcement Learning from Human Feedback, RLHF）。

AI 经过这一初始强化学习阶段后，还可以继续被微调和调整。这类微调通常通过提供更具体的样本来造出一个新的调校过的模型。这些信息可以来自某个想把模型适配到自身用例的客户，比如一家公司喂给它客服对话记录和好的回应范例；也可以来自观察用户对哪些回答点"赞"或点"踩"。这种额外微调能让模型的回应更贴合特定需求。

本书讨论 AI 时，将主要讨论以这种方式构建的大语言模型，但它们并非唯一在引发变革的"生成式 AI"。在 ChatGPT 取得突破的同一年，另一组 AI——那些设计来生成图像的 AI——也携 Midjourney 和 DALL-E 等名字登陆市场。这些 AI 工具能根据用户提示生成高质量图像，既可以模仿著名艺术家的风格（"以梵高的风格画米老鼠"），也能创造出与真实照片无法区分的超现实影像。

与 LLM 一样，这些工具也已研发多年，只是直到最近，技术才让它们真正变得有用。这些模型不学文本，而是通过分析大量配有相关文字说明的图片来训练。模型学会把词与视觉概念关联起来。然后它们从一张像老式电视雪花的随机背景图开始，用一个叫扩散（diffusion）的过程，在多个步骤中逐步精炼，把随机噪声变成清晰图像。每一步都根据文字描述去掉一点噪声，直到一幅逼真的图像浮现。一旦训练完成，扩散模型只需一段文字提示，就能生成与该描述匹配的独特图像。与产出文本的语言模型不同，扩散模型专攻视觉输出，依据提供的词语从零发明图像。

但 LLM 也在学习处理图像，同时获得"看"图和作图的能力。这些多模态 LLM（multimodal LLMs）结合了语言模型和图像生成器的力量。它们用 Transformer 架构处理文本，同时也用额外组件处理图像。这让 LLM 能把视觉概念与文本关联起来，并获得对周围视觉世界的理解。给一个多模态 LLM 一张手画的、画得很糟的飞机图，周围画满爱心（我刚这么干了），它会说："我觉得这是一幅可爱的飞机画，周围都是爱心。看起来您很喜欢飞行，或者您认识飞行员。也许您是飞行员，或者您爱的人里有飞行员。又或者您只是喜欢旅行和探索新地方。"然后它能以自己好得多的绘画技巧，给出这幅画的更好版本——它也真的这么做了。大多数大型 LLM 都在获得多模态能力，这将让它们以新的、不可预测的方式了解世界。

---

## 核心观点

1. **"AI"是个被用滥的词**：从下棋傀儡到信用评分算法，历史上的"AI"与今天的 LLM 是不同物种——本书聚焦 LLM。
2. **两次认知起点**：1950 年香农的机械鼠忒修斯（机器学习的第一个真实案例）和图灵的模仿游戏（思想实验），分别在"能做"和"能装"两条线上开启了 AI。
3. **AI 的兴衰律**：1956 年命名后经历多轮"AI 寒冬"；2010 年代监督学习让预测式 AI 在大机构中落地（亚马逊供应链是巅峰），但它不懂语言、普通人无感。
4. **Transformer 是分水岭**：2017 年《Attention Is All You Need》提出注意力机制，让机器第一次"知道句子里哪个词重要"——LLM 由此诞生。
5. **LLM 的本质是"超级自动补全"**：技术上就是预测下一个词元；训练分两阶段——无监督预训练（学权重，1750 亿参数，成本过亿美元）和微调（RLHF 用人类反馈塑造行为）。
6. **镜子与边界**：预训练模型像镜子一样反射训练数据中的偏见与黑暗（连贪污杀人都乐于指导），伦理边界靠 RLHF 后天建立。
7. **生成式 AI 不止 LLM**：扩散模型生成图像；多模态 LLM 正在同时获得"看"与"画"的能力。

---

## 金句

> "It was all a lie, of course—the machine cleverly hid a real chess master inside its fake gears, but our ability to believe that machines might be able to think fooled many of the best minds in the world for three quarters of a century."
> 当然，这一切都是个骗局——机器在假齿轮背后巧妙地藏着一位真正的象棋大师——但我们愿意相信"机器也许会思考"的倾向，骗过了世上最优秀的一批头脑，长达四分之三个世纪。

> "Ultimately, that is all ChatGPT does technically—act as a very elaborate autocomplete like you have on your phone."
> 归根结底，ChatGPT 技术上所做的全部事情，就是这个——一个像你手机里那样的超级精致的自动补全。

> "LLMs in this pretrained mode just reflect back whatever they were trained on, like a mirror, without applying any judgment."
> 处于预训练模式的 LLM 就像一面镜子，只是反射它被训练的内容，不作任何判断。
