# [第25章ChatGPT与Excel](contents.xhtml#ch25a)

[介绍](contents.xhtml#sc2_360a)

在本章中，我们将探讨如何将ChatGPT与Excel集成。Excel是一个强大的数据组织和分析工具，而ChatGPT是一个可以在各种Excel相关任务中提供帮助的AI语言模型。通过结合这些工具，您可以利用两者的功能来增强您的Excel体验。

[结构](contents.xhtml#sc2_361a)

在本章中，我们将讨论以下主题：

+   使用ChatGPT与Excel

[目标](contents.xhtml#sc2_362a)

通过本章结束时，读者将学会如何将ChatGPT与Excel集成，以实现各种目的，进一步发挥Excel的功能，并提高在数据分析、公式故障排除和格式设置等任务中的效率。

[使用ChatGPT与Excel](contents.xhtml#sc2_363a)

Excel是一个强大的组织和分析数据的工具，另一方面，ChatGPT是一个可以在包括Excel在内的各个领域提供帮助的AI语言模型。以下是您可以一起使用Excel和ChatGPT的一些方式：

+   请求Excel函数和公式的帮助：您可以向ChatGPT请求帮助解决您遇到困难的特定Excel函数或公式。只需描述问题或提供示例，ChatGPT可以提供解决方案或提供逐步指南，如[图25.1](#fig25-1)所示：

    ![](images/Figure_25.1.png)

    图25.1：向ChatGPT请求Excel函数和公式的帮助

+   获取使用Excel的技巧和窍门：ChatGPT可以为更有效地使用Excel提供技巧和窍门。例如，您可以要求快捷方式、格式设置技巧或自动化任务的方法，如[图25.2](#fig25-2)所示：

    ![](images/Figure_25.2.png)

    图25.2：向ChatGPT询问如何使用Excel的技巧和窍门

+   从数据分析中获取见解：Excel可用于分析数据并生成见解，如[图25.3](#fig25-3)所示。ChatGPT可以帮助您解释分析结果或建议新的查看数据的方式，如[图25.4](#fig25-4)所示：

    ![](images/Figure_25.3.png)

    图25.3：Excel上的数据

转到ChatGPT，在聊天中写下如何分析这些数据。回应如[图25.4](#fig25-4)所示：

![](images/Figure_25.4.png)

图25.4：ChatGPT如何分析这些数据

+   在Excel电子表格上进行协作：您可以使用ChatGPT与他人在Excel电子表格上进行协作。例如，您可以要求ChatGPT建议对电子表格进行更改或改进，或者就数据的特定方面提供反馈。[图25.5](#fig25-5)展示了一个带有数据的电子表格：

    ![](images/Figure_25.5.png)

    图25.5：带有数据的电子表格

请求ChatGPT对[图25.5](#fig25-5)中显示的数据透视表提供反馈，生成以下回应：

![](images/Figure_25.6.png)

图25.6：ChatGPT的回应

+   对于在Excel中编码：您可以使用ChatGPT生成任何代码；例如，使用VBA在Excel中将数字转换为单词。

要在Excel中使用VBA将单词转换为卢比数字，您可以创建一个自定义函数，该函数使用Microsoft Speech对象库将文本转换为语音，然后从所说的文本中提取数字。以下是您可以执行此操作的示例：

1.  打开一个新的Excel工作簿，按Alt + F11打开VBA编辑器。

1.  在编辑器中，转到插入 | 模块，创建一个新模块。

1.  在新模块中，复制并粘贴[图25.7](#fig25-7)中显示的代码：

    ![](images/Figure_25.7.png)

    图25.7：要复制到新模块的代码

1.  保存模块并返回到您的Excel工作表。

1.  在您想要将单词转换为卢比数字的单元格中，输入以下公式：

    =WordsToNumbers(“仅两千五百卢比五十派仅”)

1.  按Enter键计算结果。

1.  此公式将单词“仅两千五百卢比五十派仅”转换为数字2500.50。您可以将示例文本替换为您要转换的实际文本。

总的来说，Excel和ChatGPT的结合可以帮助您更高效、更有效地处理数据，并为您的工作提供新的见解和视角。假设您有一张包含公司销售数据的电子表格。您想要计算每个月的总销售额，并创建一个图表来可视化数据。为此，您需要按照以下步骤操作：

1.  首先，您可以使用Excel创建一个新列，并使用MONTH函数从销售数据中提取日期的月份。

1.  然后，您可以使用SUMIFS函数计算每个月的总销售额。您需要为函数指定条件，以便对每个月的销售数据进行求和。

1.  一旦您有了总数，您可以创建一个图表来可视化数据。选择您的数据，转到插入选项卡，并选择您想要创建的图表类型。

1.  如果您不确定要使用哪种图表类型或如何格式化图表，可以向ChatGPT寻求建议。例如，您可以询问“用于按月可视化销售数据的最佳图表类型是什么？”或“如何使我的图表更具视觉吸引力？”

1.  ChatGPT可以根据最佳实践和设计原则提供建议。如果您不确定如何使用Excel中的特定功能或设置，也可以向ChatGPT询问。参考[图25.8](#fig25-8)作为示例：

    ![](images/Figure_25.8.png)

    图25.8：向ChatGPT寻求有关Excel中特定功能或设置的帮助

总的来说，使用Excel和ChatGPT一起可以帮助您更高效、更有效地处理数据，并为您的工作提供新的见解和视角。

[结论](contents.xhtml#sc2_364a)

总之，将ChatGPT与Excel集成为用户提供了有价值的帮助和指导。通过利用Excel函数和公式的强大功能，再加上ChatGPT的能力，用户可以提高在数据分析、公式故障排除和格式设置等任务中的效率。ChatGPT还可以提供有关更有效使用Excel的技巧、窍门和见解。此外，与ChatGPT合作在电子表格上进行协作并从ChatGPT获取反馈，可以增强使用Excel的整体体验。通过结合这些工具，用户可以优化其数据管理和分析工作流程，从而提高生产力和做出更好的决策。

[练习](contents.xhtml#sc2_365a)

1.  打开Microsoft Excel并创建一个新工作簿。

1.  在工作表中输入以下示例销售数据

    | 日期 | 销售额 |
    | --- | --- |
    | 01-01-2023 | $500 |
    | 05-01-2023 | $300 |
    | 10-02-2023 | $750 |
    | 15-02-2023 | $600 |
    | 03-03-2023 | $900 |
    | 07-03-2023 | $400 |

表25.1：示例销售数据

创建一个执行以下任务的VBA宏：

1.  计算每个月的总销售额。

1.  确定销售额最高的月份。

1.  在消息框中显示计算出的总额和销售额最高的月份。

加入我们书籍的Discord空间

加入该书的Discord工作区，获取最新更新、优惠、全球科技动态、新发布内容以及与作者的交流：

**[https://discord.bpbonline.com](https://discord.bpbonline.com)**

![](images/fm1.png)