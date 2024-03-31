# [第14章在VBA中创建和记录宏](contents.xhtml#ch14a)

[简介](contents.xhtml#sc2_185a)

在本章中，我们探索了VBA宏的世界及其在Microsoft Excel中自动化重复任务中的作用。VBA代表Visual Basic for Applications，是嵌入在Excel中的强大编程语言。宏是一系列命令，允许我们自动化操作并简化工作流程。无论您是初学者还是有经验，本章都提供了创建和记录宏的全面指南。您将学习VBA的基础知识，宏的好处，以及如何通过编写代码或记录操作来创建宏。准备好通过VBA宏的力量提高在Excel中的生产力和效率。

[结构](contents.xhtml#sc2_186a)

在本章中，我们将讨论以下主题：

+   VBA简介

+   宏简介

+   创建宏

+   记录宏

+   定义宏

+   停止录制

+   相对引用宏

+   运行您的宏

+   按名称运行宏

[目标](contents.xhtml#sc2_187a)

通过本章，我们的目标是介绍VBA和宏，解释创建和记录宏的过程，定义宏及其属性，演示如何运行宏，并提供创建宏以自动化Excel任务的实际示例。

[VBA简介](contents.xhtml#sc2_188a)

VBA代表Visual Basic for Applications。它是包含在所有Microsoft Office应用程序中的编程语言，如Excel、Word、PowerPoint等。它也是Excel宏所编写的语言。VBA是Microsoft Visual Basic的一个子集。

[VBA的用途](contents.xhtml#sc3_189a)

VBA的一些用途如下：

+   驱动整个应用程序。

+   将多个操作组合为一个宏。

+   编写您自己的函数。

[宏简介](contents.xhtml#sc2_190a)

宏是按逻辑顺序编写的一系列命令，以自动化任何重复任务。它存储在Microsoft Visual Basic模块中。它可以分配给“加载项”选项卡或“快速访问工具栏”上的按钮。

一些制作宏的示例包括：

+   在按下按钮时自动向任何电子表格添加标准公司页眉。

+   将来自总账系统的文本文件格式化为更易用的格式。

+   从工作簿内打印出特定的工作表，而不是逐个工作表打印。

[创建宏](contents.xhtml#sc2_191a)

创建宏有两种方法：

+   编写：使用VBA语言为宏中的操作编写代码。

+   记录：使用宏记录器在Excel中记录您的操作。Excel具有宏记录器，可以记录操作并为宏编写代码。

创建宏的最佳方法是按照以下步骤进行：

1.  确定用户想要宏实现的确切问题和最终结果。

1.  计划宏的步骤以成功获得最终结果。

1.  创建宏时可以选择录制、编写或两者结合。

注意：记录您在 Excel 中执行的操作，否则请写下来。

[在功能区添加开发者选项卡](contents.xhtml#sc3_192a)

要在功能区上添加开发者选项卡，请按照以下步骤进行：

1.  单击“文件”按钮。

1.  点击“选项…”按钮。

1.  在“自定义功能区”选项卡上，选择在功能区中显示“开发者”选项卡，如[图 14.1](#fig14-1)所示：

    ![](images/Figure_14.1.png)

    图 14.1：在功能区添加开发者选项卡

[录制宏](contents.xhtml#sc2_193a)

要录制宏，请按照以下步骤进行：

1.  单击“开发者”选项卡。

1.  在“代码”组中，单击“录制宏”按钮，如[图 14.2](#fig14-2)所示：

    ![](images/Figure_14.2.png)

    图 14.2：录制宏

[定义宏](contents.xhtml#sc2_194a)

要定义宏，请按照以下步骤进行：

![](images/Figure_14.3.png)

图 14.3：定义宏

在为宏分配名称时，请遵循以下规则：

+   宏名称可以由字母和数字组成。

+   宏名称不应以数字开头。

+   宏名称不应包含除下划线(_)之外的任何特殊符号。

+   最多可有 255 个字符。

+   不要使用既是宏名称又是单元格引用的名称。

[宏存储](contents.xhtml#sc3_195a)

不同的宏存储方式如下：

+   个人宏工作簿：录制将在当前工作簿上执行，而宏将存储在名为 Personal.xls 的文件中。这是一个隐藏文件（位于 XLSTART 文件夹内），每当 Excel 应用程序打开时都会打开。

+   此工作簿：录制将在当前工作簿上执行，而宏将存储在当前文件中。

+   新工作簿：录制将在当前工作簿上执行，而宏将存储在新文件中。

注意：只有打开存储宏的文件才能使用宏。如果希望在使用 Excel 时始终可用宏，请选择“个人宏工作簿”选项。

[宏快捷键](contents.xhtml#sc3_196a)

您可以使用 Ctrl+字母（小写字母）或 Ctrl+Shift+字母（大写字母）的组合键，其中字母是键盘上的任何字母键。您使用的快捷键字母不能是数字或特殊字符，如 @ 或 #。快捷键将在包含宏的工作簿打开时覆盖任何等效的默认 Microsoft Excel 快捷键。

[宏描述](contents.xhtml#sc3_197a)

描述用于写入有关宏的详细信息，例如此宏的目的等。这有助于后续维护。

[停止录制](contents.xhtml#sc2_198a)

要停止录制宏，请按照以下步骤进行：

1.  执行宏需要执行的操作。

1.  停止录制，可以通过在开发者选项卡的“代码”组中单击“停止录制”按钮或在底部状态栏上单击停止录制来实现。

参考以下[图 14.4](#fig14-4)：

![](images/Figure_14.4.png)

图 14.4：停止录制宏

[相对引用宏](contents.xhtml#sc2_199a)

如果您希望宏相对于活动单元格的位置运行，请使用相对单元引用进行记录。在开发者选项卡上，单击使用相对引用，以便选择它。Excel将继续使用相对引用记录宏，直到您退出Excel或再次单击使用相对引用，以便取消选择。

参考[图14.5](#fig14-5)：

![](images/Figure_14.5.png)

图14.5：停止录制宏

注意：使用相对引用按钮是一个切换按钮。请注意，开始录制之前，请检查是否已选择。

[场景1](contents.xhtml#sc3_200a)

创建一个宏，自动将公司名称以特定格式添加到任何电子表格的第一行。

为此，请参考Training File1.xls并按照给定步骤进行：

1.  开始录制。

1.  给名称为Company_name。

1.  将快捷键设置为Ctrl + Shift + C。

1.  执行以下步骤：

    1.  选择第一个单元格（因为名称应该出现在第一行）。

    1.  输入你公司的名称。

    1.  应用格式：字体大小20，加粗，蓝色字体，白色背景。

    1.  选择A1到H1单元格。

    1.  点击合并工具。

1.  停止录制：

    1.  转到工具菜单，然后宏 | 停止录制。

参考以下[图14.6](#fig14-6)：

![](images/Figure_14.6.png)

图14.6：场景1

[运行你的宏](contents.xhtml#sc2_201a)

宏可以通过

+   快捷键（在定义宏时分配的）

+   名称

+   快速访问工具栏上的按钮

+   工作表上的按钮

[按名称运行宏](contents.xhtml#sc2_202a)

要按名称运行您的宏，请按照给定步骤进行：

1.  转到开发者选项卡。

1.  选择宏，（快照1）

1.  选择要运行的宏，（快照2）

1.  点击运行按钮。

参考以下[图14.7](#fig14-7)：

![](images/Figure_14.7.png)

图14.7：按名称运行宏

[场景2](contents.xhtml#sc3_203a)

创建一个宏来显示一个产品表，其中包含表头，产品名称，数量，价格，总计和净额。表必须始终从第二行第一列开始显示。Excel不应接受任何负值作为价格和数量。此宏将始终从第二行第一列（A1引用）产生结果。

执行以下步骤（参考Training File1.xls）：

1.  开始录制（命名为Product_Table，快捷键Ctrl + Shift + P）

1.  选择单元格A2（表必须始终从第二行第一列开始显示）。

1.  根据[图14.8](#fig14-8)创建一个表：

1.  编写总计和净额的公式。

1.  格式化它。

1.  对数量和价格单元格进行验证（限制负值）。

1.  停止录制。

参考以下[图14.8](#fig14-8)：

![](images/Figure_14.8.png)

图14.8：场景2

[场景3](contents.xhtml#sc3_204a)

创建一个宏来显示相同的产品表（场景2），但这次它应该出现在用户想要的任何地方（使用相对引用）。此宏取决于用户的选择。

执行以下步骤：

1.  开始录制（命名为Product_Table_Relative并设置快捷键）。

1.  在停止录制工具栏上打开相对引用按钮。

1.  根据[图14.9](#fig14-9)从当前单元格创建表格。

    注意：从表格中的任何位置开始输入；在创建相对引用宏时不要不必要地点击表格。

1.  编写总和和净总额的公式。

1.  格式化它。

1.  对数量和价格单元格进行验证（限制负值）。

1.  关闭相对引用按钮。

1.  停止录制。

参考以下[图14.9](#fig14-9)：

![](images/Figure_14.9.png)

图14.9：场景3

[结论](contents.xhtml#sc2_205a)

总结一下，本章介绍了VBA宏的基础知识以及它们在Excel中自动化任务中的重要性。通过创建和记录宏，用户可以简化重复操作并提高生产效率。无论是通过手动编码还是录制功能，宏都为定制和优化Excel功能提供了强大的工具。通过利用宏，用户可以节省时间，减少错误，并提高效率。

[练习](contents.xhtml#sc2_206a)

1.  创建一个名为“CalculateAverage”的宏，用于计算Excel中一系列数字的平均值。

1.  创建一个名为“FormatData”的宏，将特定格式应用于Excel中一系列单元格。

1.  创建一个名为“GenerateReport”的宏，用于自动化在Excel中生成报告的过程。

加入我们书籍的Discord空间

加入书籍的Discord工作区，获取最新更新、优惠、全球技术动态、新发布和与作者的交流：

**[https://discord.bpbonline.com](https://discord.bpbonline.com)**

![](images/fm1.png)