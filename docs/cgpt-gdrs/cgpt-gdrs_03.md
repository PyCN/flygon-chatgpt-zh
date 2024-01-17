# 四、使用 ChatGPT 的提示工程技巧

提示工程是设计和优化人工智能语言模型（如 GPT-4）的提示的过程。用于训练这些模型的提示的质量和有效性可以显著影响它们的性能和生成准确和有用输出的能力。

在提示工程中，目标是创建有效传达模型所需输入和输出的提示，同时最小化歧义、噪音和其他可能降低模型准确性或有效性的因素。这涉及选择适当的输入格式，定义预期的输出格式，并考虑可能影响模型性能的任何约束或限制。

提示工程还涉及持续优化和改进提示，以随着时间的推移提高模型的准确性和有效性。它涉及根据在模型训练和测试过程中生成的反馈和性能指标调整提示的语言、结构或内容。

总的来说，提示工程对于开发和训练有效的人工智能语言模型至关重要，并需要在自然语言处理、机器学习和相关领域中进行仔细考虑和专业知识。

提示工程的几个优点包括：

1.  改进模型性能：通过精心设计和优化提示，生成的语言模型可以更准确、有效和高效。这是因为提示提供了清晰和相关的输入和输出期望，这可以帮助模型更好地理解和解释数据。

1.  增加模型的灵活性：设计良好的提示可以帮助语言模型更容易地适应新任务和数据源，因为它们为处理和生成输出提供了一个结构化的框架。这可以帮助减少从头开始重新训练模型的需求，节省时间和资源。

1.  增强模型的泛化能力：有效的提示还可以帮助语言模型更好地泛化到新的和多样化的数据，提供一致和明确定义的框架来解释输入和生成输出。这可以提高模型处理语言、上下文和其他影响准确性和有效性的因素的能力。

1.  更好的模型可解释性：通过理解提示是如何制定和优化的，可以更容易地解释和解释语言模型生成的决策和输出。这可以建立与利益相关者和最终用户的信任和理解，并促进人工智能技术的更广泛采用。

训练像 GPT-4 这样的人工智能语言模型专门从事提示工程是一个复杂的过程，需要在自然语言处理、机器学习和相关领域中具有专业知识。然而，以下是一些可以帮助指导训练过程的一般步骤和考虑因素：

+   收集多样化和相关的数据集：训练语言模型的第一步是收集与提示工程相关的文本的多样化和相关的数据集。这可能包括研究论文、博客文章、在线讨论和其他信息来源。

+   预处理和清理数据集：一旦您有了数据集，您需要对其进行预处理和清理，以删除任何不相关或多余的信息，标准化格式和语法，并确保数据的一致性。

+   训练 GPT-4 模型：在预处理数据之后，您可以使用您收集的数据集训练 GPT-4 模型。这通常涉及使用转移学习等技术对现有的 GPT-4 架构进行针对您特定任务和数据的微调。

+   评估模型性能：一旦模型训练完成，您需要评估其在单独的测试数据集上的性能，以衡量其准确性、精确度、召回率和其他相关指标。这可以帮助确定模型性能不佳或过拟合的领域，并指导进一步的优化。

+   不断完善和优化模型：最后，随着您收集更多数据并对模型的性能有更多了解，您可以不断完善和优化模型，以提高其准确性、泛化性和有效性。这可能涉及调整超参数，添加额外的层或节点，或尝试不同的输入或输出格式。

虽然这些步骤提供了培训过程的高层概述，但重要的是要注意，提示工程是一个复杂且持续的领域，需要持续学习和适应。因此，重要的是要及时了解这一领域的最新研究和最佳实践，并不断评估和完善您的方法，以最大化 AI 语言模型的有效性。

具体点

要在提示工程中具体化，您需要清楚地了解您要解决的任务或问题，以及您正在处理的数据和模型。这涉及定义输入和输出格式，识别任何约束或要求，并优化提示的语言和结构，以最大化模型的准确性和有效性。

以下是您可以如何使用 chatGPT 进行提示工程的一些示例：

1.  为情感分析制定提示：如果您正在进行情感分析，您可以使用 chatGPT 帮助您制定有效的提示，准确捕捉给定文本的情感。例如，您可以提示模型识别特定文本的情感，如产品评论，并提供一个表示情感是积极的、消极的还是中性的数值分数或标签。

1.  优化语言建模的提示：如果您正在进行语言建模，可以使用 chatGPT 来优化您的提示，以提高模型性能。例如，您可以尝试不同的输入格式，如添加额外的上下文或修改输入序列的结构，并评估这些变化对模型准确性和有效性的影响。

1.  为数据增强生成新的提示：如果您正在进行数据增强，您可以使用 chatGPT 生成新的提示或现有提示的变体，以帮助改善训练数据的多样性和质量。例如，您可以提示模型生成类似于现有提示但在语言或结构上略有变化的新句子或短语。

1.  评估提示质量：如果您正在进行提示评估，您可以使用 chatGPT 分析现有提示的质量，并提供反馈，以改进它们以提高模型性能。例如，您可以提示模型基于现有提示生成输出，并评估这些输出的准确性和相关性，以确定可以改进提示的任何领域。

以下是 chatGPT 生成的提示示例：

输入：我希望你成为一个提示生成器。首先，我会告诉你一个故事类型，然后你会为学生生成一个继续的短篇故事的提示。

输出：当然，我可以基于给定的故事类型生成提示。请告诉我您心中的故事类型，我会尽力生成一个合适的提示。

输入：这是故事类型：惊悚

输出：太好了，这是一个惊悚短篇故事的提示：

提示："当艾米莉深夜独自走回家时，她注意到有人在跟踪她。她加快了步伐，但她身后的脚步声只变得更响。就在她准备跑开时，她感到有人在她肩膀上拍了一下，并有声音在她耳边低语道：“不要尖叫，但我需要你的帮助……”

在这个提示中，学生被要求从艾米莉被一个需要她帮助的陌生人接触的地方继续故事。学生可以探索陌生人身份的神秘之处，他们为什么需要艾米莉的帮助以及卷入陌生人问题的危险和风险。

提示提供了一个明确而具体的情景，旨在产生紧张和悬念，并给学生足够的空间来探索不同的情节转折和角色动机。

ChatGPT 生成的提示的一个更具体的例子是：

输入：我希望你成为一个提示生成器。首先，我会给你一个书名，然后你给我提供一本书的潜在情节。情节应该包括主要角色以及背景。故事还应包括适合 10 到 12 岁儿童的良好道德。

输出：当然，我可以尝试根据给定的书名生成情节。请告诉我你心中的书名，我会尽力生成一个包括主要角色、背景和适合 10 到 12 岁儿童的良好道德的合适情节。

输入：书名：王子和被遗忘的城堡

输出：很好，以下是《王子和被遗忘的城堡》的一个潜在情节：

在一个遥远的王国，一个叫亚历山大的年轻王子发现了一个隐藏在森林深处的被遗忘的城堡。这座城堡已经被废弃多年了，亚历山大对它神秘的过去感到好奇。当他探索城堡时，他遇到了一位名叫威廉的智者，威廉告诉他这座城堡曾经是一个美丽和快乐的地方，直到一个邪恶的巫师诅咒了它，并导致所有的居民都忘记了他们的过去。

决心打破诅咒，恢复城堡的昔日荣耀，亚历山大踏上了寻找巫师并请求解除诅咒的探险。在这个过程中，他遇到了一群忠诚的同伴，包括一位勇敢的骑士乔治爵士和一个善良的女孩艾米莉。他们一起面对许多挑战和障碍，包括险恶的森林、危险的野兽和巫师的手下。

当他们接近巫师的巢穴时，亚历山大学到了关于勇气、决心和友谊重要性的重要教训。他意识到真正的力量来自内心，当我们共同努力并相信自己时，甚至最大的障碍也能够克服。最终，亚历山大的探险是成功的，诅咒从城堡上解除了。曾经忘记过去的人们终于可以记起他们的历史并夺回他们的家园。

故事的寓意是，凭借决心、毅力和忠诚的朋友的帮助，甚至最大的挑战也能够克服。因此，孩子们可以学会友谊的价值、决心的重要性，以及保留历史和传统的重要性。

尝试使用提示

Priming 是自然语言处理和机器学习中使用的一种技术，通过提供上下文或提示给模型，以改善文本生成的质量和相关性。例如，在 GPT（生成式预训练变换器）语言模型的情况下，priming 是提供一系列文本或关键词来引导生成后续文本的过程。

GPT 模型中的 Priming 通过向模型提供上下文或种子来工作，这使得它生成的文本更符合上下文。上下文可以是一些词、一个句子，甚至是一个段落，可以用来指定要生成的文本的主题、类型、风格或情绪。

GPT priming 的基本思想是利用 GPT 模型的预训练知识和能力，根据给定的上下文生成相关和连贯的文本。通过提供提示或种子文本，GPT 模型可以被微调或调节，以生成更具体的与上下文相关的文本。

GPT priming 的过程包括以下步骤：

1.  选择上下文：GPT priming 的第一步是选择将指导后续文本生成的上下文或种子文本。上下文可以是一些词、一个句子或一个段落，应与要生成的文本的主题或主题相关。

1.  编码上下文：一旦选择了上下文，就必须将其编码成 GPT 模型可以处理的格式。这涉及将文本转换为数字表示，如标记 ID 或嵌入，以便 GPT 模型能够理解。

1.  生成文本：在上下文被编码后，它被输入到 GPT 模型中，同时还有任何额外的参数或约束。然后，模型使用其预训练的知识和语言生成能力生成与上下文一致的文本。

1.  评估输出：生成文本后，需要评估以确保其连贯、相关，并符合所需标准。可以使用困惑度、连贯性、可读性或人工评估指标来进行评估。

1.  微调模型：如果输出不理想，可以通过调整参数、上下文或训练数据来微调 GPT 模型。这涉及在额外数据上重新训练模型，修改架构或更改超参数。

GPT 启动可以用于各种应用，包括创意写作、聊天机器人、推荐系统和内容生成。例如，GPT 启动可以为创意写作中生成故事、诗歌或对话提供起点或提示。在聊天机器人中，GPT 启动可以用于提供对话的背景或话题，提高回复的相关性和连贯性。此外，在推荐系统中，GPT 启动可以根据用户偏好或先前互动生成个性化推荐。

一些 GPT 启动的最佳实践包括：

1.  使用相关和具体的上下文：提供给 GPT 启动的上下文应与要生成的文本的主题或主题相关，并且应该足够具体，以有效地引导生成过程。

1.  改变上下文的长度和复杂性：根据应用和目标，提供给 GPT 启动的上下文的长度和复杂性可以有很大的变化。一般来说，较短和较简单的上下文更容易让模型处理，但可能导致输出不够具体或多样化。

1.  使用高质量和多样化的训练数据：用于预训练 GPT 模型的训练数据的质量和多样性可以显著影响生成文本的质量和相关性。因此，使用高质量和多样化的训练数据对于确保 GPT 模型能够学习自然语言的微妙和复杂性至关重要。这包括各种来源，如书籍、文章和来自不同领域和流派的其他文本数据。

1.  在选择训练数据时，重要的是要确保它具有多样性，并且代表了模型打算为其生成文本的语言和主题。这有助于防止模型产生偏见或在为某些主题或领域生成文本的能力上受到限制。

1.  此外，确保数据具有高质量且没有错误或不一致也至关重要。这包括清理数据，删除重复项，并确保数据格式正确和结构良好。

1.  除了训练数据的质量和多样性之外，其他因素，如数据集的大小和训练方法，也可能影响启动过程的有效性。因此，在为启动训练 GPT 模型时，重要的是要仔细考虑这些因素。

通过以下步骤在 ChatGPT 中尝试提示：

1.  访问一个平台或工具，允许您使用 ChatGPT 生成提示，例如 OpenAI 的 GPT-4 Playground 或 Hugging Face 的 Transformers 库。

1.  定义要生成的提示类型，例如创意写作提示、研究问题或对话提示。

1.  根据您的需求和目标指定提示的长度和复杂度。例如，您可以生成一个只需要几句回答的简短提示，或者需要详细的短文或故事的长提示。

1.  提供 ChatGPT 模型可以用来生成提示的相关上下文或关键词。这可以包括特定的主题、主题、流派或风格。

1.  尝试不同的提示变体，并观察 ChatGPT 模型的响应。您可以修改提示的长度、复杂度和上下文，以及生成的响应的创造性、连贯性和相关性的程度。

1.  根据您的标准和目标评估生成的提示的质量和有用性。例如，您可以使用可读性、连贯性、相关性、独创性或参与度等指标来评估提示的有效性。

1.  根据实验获得的反馈和见解，完善和迭代提示生成过程。您可以调整提示生成的参数、上下文和目标，以及所选和评估的生成提示，以优化结果。

以下是在 ChatGPT 中尝试提示时要记住的一些要点：

1.  从明确的目标开始：在尝试提示之前定义您的目标和目标。这将帮助您选择生成和评估提示的正确参数、上下文和标准。

1.  使用相关的上下文和关键词：提供与您的主题、主题或流派相关的上下文和关键词。这将帮助 ChatGPT 模型生成连贯、相关和引人入胜的提示。

1.  具体而简洁：在提示中使用具体而简洁的语言。这将帮助 ChatGPT 模型专注于您想要探索的关键思想和概念。

1.  尝试不同长度和复杂度的实验：尝试生成不同长度和复杂度的提示，并根据您的标准和目标评估其质量和有用性。

1.  批判性评估生成的提示：使用可读性、连贯性、相关性、独创性或参与度等指标来评估生成提示的有效性。在评估中要批判和客观，并根据获得的反馈和见解完善提示生成过程。

1.  迭代和完善提示生成过程：根据实验获得的反馈和见解，完善和迭代提示生成过程。调整提示生成的参数、上下文和目标，以及所选和评估的生成提示，以优化结果。

审查和编辑

审查和编辑提示是提示工程过程中的重要步骤。它有助于确保生成的文本与预期的用例相关、连贯且合适。

在审查提示时，重要的是要考虑诸如内容的准确性、语言的语气和风格以及与任务或领域的相关性等因素。这涉及仔细阅读提示并检查文本中的任何错误或不一致之处。

一旦发现任何问题，就可以编辑提示以提高其质量和相关性。这可能涉及重新措辞句子、添加或删除信息，或调整语言的语气或风格。

在编辑提示时，考虑受众的意图也很重要。例如，面向儿童的提示可能需要更简单的语言和更多的视觉线索来帮助他们理解任务或提示。

此外，有多个审阅者或编辑提供反馈，并确保提示从不同角度准确和相关是有帮助的。这可以帮助识别可能被忽视的任何偏见或假设。

审查和编辑提示是提示工程过程中的关键步骤，以确保生成的文本质量高、相关且适用于预期的用例。

几个指标可以帮助您确定您的提示是否有效：

1.  完成率：如果您的提示的完成率很高，那么提示很可能是有效的。完成率是指成功完成提示中概述的任务或活动的用户的百分比。高完成率表明提示对用户来说足够清晰和具体，以便理解和遵循。

1.  响应质量：如果对提示的响应质量很高，那么提示很可能是有效的。响应质量可以通过准确性，相关性，创造性和复杂性等标准来衡量。如果大多数响应符合这些标准，这表明提示有效地引发了用户的高质量输出。

1.  用户反馈：用户反馈可以为提示的有效性提供宝贵的见解。您可以通过调查，访谈或焦点小组收集反馈。用户可以就清晰度，相关性，兴趣和难度等因素提供反馈。如果用户持续提供积极的反馈，提示很可能是有效的。

1.  完成时间：如果用户能够在合理的时间内完成提示，那么提示很可能是有效的。完成时间是指用户完成提示中概述的任务或活动所需的时间。如果提示需要太长时间才能完成，用户可能会感到沮丧或失去兴趣。

1.  学习目标的实现：如果提示用于教育目的，您可以通过衡量学习目标的实现来评估其有效性。学习目标是指用户通过提示预期获得的具体技能或知识。如果用户能够成功实现这些目标，这表明提示在促进学习方面是有效的。

通过考虑这些指标，您可以评估提示的有效性，并根据需要进行调整，以提高其质量和用户的相关性。

章节附录：提示商店/市场出售/购买提示

ChatGPT 还可以通过出售提示帮助用户赚钱的另一种方式。

是的，您可以在线出售提示。有各种在线市场可以出售您的提示，如 Teachers Pay Teachers，Udemy 和 Skillshare。这些平台允许您创建和出售教育资源，包括提示，面向全球受众。您还可以在您的网站，博客或社交媒体渠道上出售提示。

您可以使用的另一个平台是 Prompt Base。

Promptbase 是一个基于 Web 的平台，为生成，测试和完善用于机器学习应用的提示提供了一系列工具和资源，包括自然语言处理（NLP）和文本生成。该平台包括一个大型的预先构建提示和模板数据库，以及用于定制和测试提示以满足特定需求的工具。

Promptbase 的核心功能包括以下内容：

1.  提示库：Promptbase 包括一个预先构建的提示库，用于各种用例，包括聊天机器人，语言翻译，情感分析等。用户可以浏览库以找到满足其需求的提示，并根据需要进行定制。

1.  提示构建器：该平台还包括一个提示构建工具，允许用户为其特定用例创建自定义提示。构建器提供一系列定制选项，包括用于收集用户输入，生成文本输出等提示。

1.  提示测试：Promptbase 包括一个测试功能，允许用户实时测试他们的提示，以评估其有效性并根据需要进行调整。测试功能提供一系列指标和见解，如用户参与度，响应时间和准确性。

1.  数据管理：该平台提供了管理和将数据与机器学习模型集成的工具。用户可以上传和管理数据集，训练机器学习模型，并访问各种分析和报告工具。

1.  合作：Promptbase 还提供协作功能，允许用户共同处理提示并与他人分享。用户可以共同处理提示，分享反馈和见解，并共同努力随着时间的推移完善和改进提示。

Promptbase 可用于各种应用，包括：

1.  聊天机器人：Promptbase 可用于创建和完善聊天机器人的提示，包括用于收集用户输入和生成文本输出的提示。该平台可用于创建客户服务、营销和其他用例的聊天机器人。

1.  情感分析：Promptbase 可用于创建和完善情感分析的提示，包括用于将文本分类为积极、消极或中性的提示。这可以用于社交媒体监控、客户反馈分析和更多应用。

1.  语言翻译：Promptbase 可用于创建和完善语言翻译的提示，包括用于将文本从一种语言翻译成另一种语言的提示。这可以用于语言学习、旅行和更多应用。

1.  文本生成：Promptbase 可用于创建和完善生成文本的提示，包括用于生成产品描述、新闻文章等的提示。这可以用于内容营销、新闻业等应用。

总的来说，Promptbase 为生成、测试和完善机器学习应用的提示提供了强大的工具和资源。无论您是数据科学家、开发人员还是业主，Promptbase 都可以帮助您创建有效、引人入胜的提示，从而产生结果。

在线销售提示时，确保它们与目标受众高度相关是很重要的。这将帮助您建立作为可靠和值得信赖的教育资源提供者的声誉。您可能还希望考虑向潜在客户提供免费样品或试用您的提示，以帮助建立兴趣并促进销售。

此外，确保您具有在线销售提示所需的必要权限和许可是很重要的。例如，如果您的提示是基于受版权保护的材料，您可能需要从版权持有人那里获得许可或购买使用该材料的许可证。您还应该了解与在您的司法管辖区内销售教育材料相关的任何法律要求。

确定提示是否值得销售时需要考虑几个因素：

1.  质量：高质量的提示应该引人入胜、发人深省，并与目标受众相关。它还应该写得好，没有语法错误或其他可能影响用户体验的问题。

1.  独创性：您的提示应该是独特的，而不是其他地方容易获得的。如果与其他广泛可用的提示相似，可能不太吸引潜在买家。

1.  目标受众：考虑您的提示面向的受众群体，以及该领域是否存在对提示的需求。如果您的提示太小众，可能无法吸引足够广泛的受众来进行销售。

1.  市场研究：进行研究，以确定您选择的领域是否存在提示市场。寻找与该主题相关的在线论坛或群体，看看是否对提示感兴趣。

1.  竞争：评估竞争，并确定您的提示是否提供了独特的东西或填补了市场上的空白。如果已经有许多类似的提示可用，要脱颖而出并进行销售可能会很困难。

1.  反馈：从潜在客户那里收集反馈，看看他们是否认为您的提示有用且引人入胜。考虑提供免费试用或样品以在投入时间和资源之前获得反馈。

最终，一个提示的成功将取决于它的质量、原创性和吸引目标受众的程度。进行彻底的研究和收集反馈可以帮助你决定一个提示是否值得销售。