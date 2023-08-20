
# eecs-resume-gpt_prompt

**使用**: 你需要复制如下的prompt part_1 到你的GPT中（API/Web entrance均可），根据指令输入【职位职责】，然后复制prompt part_2，根据指令输入【我的经历】。请注意，【职位职责】应该是你目标岗位招聘信息上的内容，而【我的经历】则是一段你描述自己经历的段落文字。（注：亲测GPT-4的使用效果显著优于GPT-3.5-trubo/text-davinci-002-render-sha)

**Acknowledge**：本文参考了@gaogaotiantian在 https://www.eecsresume.com/example 提供的简历修改tips。

**Useage**: You need to copy the following prompt part_1 into your GPT (API/Web entrance is fine), then enter [Position Responsibilities], then copy the prompt part_2, and then enter [My Experience] according to the instruction. Please note that [job responsibilities] should be the content of your target job posting, and [my experience] is a paragraph of text that you describe your experience. (Note: The use of GPT-4 has been personally tested to be significantly better than GPT-3.5-trubo/text-davinci-002-render-sha)

**Acknowledgement**: this article draws on resume revision tips provided by @gaogaotiantian at https://www.eecsresume.com/example .

**Part_1**
> 我将为你提供一段【职位职责】的描述，希望你能根据以下四个方面进行总结，每一方面只需列出相关名词，不需要额外解释：
> 1. **要求掌握的工具或技能**：请列出使用计算机的特定技能软件或平台、专业语言、或特定专业技能，例如：会计中的财务报表、工程专业的3D建模、文书工作中使用的Word或Markdown等实践性的内容。
> 2. **建议有的经历或者经验**：请列出与该【岗位职责】最匹配的一些其他岗位经验，例如：同样要求数据分析工作经验的其他工作等。
> 3. **岗位要求的背景知识**：请列出在学校中学习的相关专业或科目，例如：特定学科如经济学、金融、计算机科学、生物、物理、化学等，或科目如计算机编程、宏观经济学、微观经济学、高等数学、线性代数、运筹学、统计分析等理论性的知识。
> 4. **岗位需求的职责特性**：请列出符合该【岗位职责】的一些个人性格特征，例如：积极主动、擅长与人交流、富有好奇精神、学习能力强、承压能力强等特性。
>
> 请确保上述四个方面的内容彼此独立，互不重复。如果你已明白，请回复：我已明白，请你提供【岗位职责】。

**Part_2**
> 现在，请根据你刚才总结的【要求掌握的工具或技能】、【建议有的经历或者经验】、【岗位要求的背景知识】、【岗位需求的职责特性】，按照以下指令改写我将提供的【我的经历】。
指令：
> 1. **整理经历**：请按照【建议有的经历或者经验】对【我的经历】进行整理，将符合【建议有的经历或者经验】的内容归纳为2-3点。例如：如果我的经历中有数据处理工作，并与当前岗位的数据处理经验要求相匹配，则保留；若有与岗位无关的文书工作经历，则删除。
> 2. **描述经历**：将保留下的每一点按照“使用某工具+完成某工作内容+达到某效果/结果”的结构写为连贯的句子。在描述中，“使用某工具”需符合【要求掌握的工具或技能】，“完成某工作内容”需符合【建议有的经历或者经验】，“达到某效果/结果”需体现熟练使用【要求掌握的工具或技能】、符合【岗位需求的职责特性】或证明掌握【岗位要求的背景知识】。
> 3. **合理用词**：在细节描述中，请注意用词的真实性，不要夸大其词。酌情使用像“擅长”、“熟练掌握”、“了解”等词汇。
> 4. **数据支撑**：在成果展示的部分，务必提供数据支撑，避免空泛的描述。例如，不要使用“对某领域有极大贡献”，而应使用具体指标如“减少了50%的成本”、“提高了30%的效率”等。
> 5. **信息缺失**：如果【我的经历】中缺失了对应的信息，请留下相应的位置，以便我之后进行修改和补充。
> 
> 综合例子：
>- 软件开发工程师
  （1）使用Flask开发了一个新功能，使客户能保存以前的订单，并通过一次点击重新订购。
  （2）与两名工程师使用React.js重构了用户界面，使客户购买产品的时间平均减少了48%。
  （3）完善了招聘网站的购买流程，使之易于使用，从而将用户满意率从73%提高到84%。
>
>如果你已经明白了我的要求，请回复：我已经明白，请您提供【我的经历】。

**Part_1**
> I will provide you with a one-paragraph description of the [Position Responsibilities], which I would like you to summarize based on the following four areas, each of which should be listed with only the relevant terms and no additional explanation:
> 1. **Tools or Skills Required**: please list skill-specific software or platforms that use computers, specialized languages, or specific professional skills, e.g., financial statements in accounting, 3D modeling in engineering, hands-on use of Word or Markdown in clerical work, etc.
> 2. **Recommended experience or experience**: please list some other job experience that best matches this [job role], e.g., other jobs that also require data analytics experience, etc.
> 3. **Background Knowledge Required for the Position**: Please list relevant majors or subjects studied in school, e.g., specific disciplines such as Economics, Finance, Computer Science, Biology, Physics, Chemistry, etc., or subjects such as Computer Programming, Macroeconomics, Microeconomics, Higher Mathematics, Linear Algebra, Operations Research, Statistical Analysis, and other theoretical knowledge.
> 4. **Duty Characteristics Required for the Position**: Please list some personal character traits that match this [Job Duties], e.g., characteristics such as being proactive, good at communicating with others, curious, a strong learner, and a strong stress-bearer.
>
> Please make sure that the above four areas are independent of each other and do not repeat each other. If you have understood, please reply: I have understood, please provide [job responsibilities]."

**Part_2**
> Now, please rewrite the [my experience] that I will provide based on the [tools or skills required], [suggested experience or experience], [background knowledge required for the position], and [duty characteristics required for the position] that you have just summarized, according to the following instructions.
Instructions:
> 1. **Organize experience**: Please organize [my experience] according to [suggested experience or experience], and summarize what meets [suggested experience or experience] into 2-3 points. For example, if there is data processing work in my experience and it matches the data processing experience requirement of the current position, keep it; if there is paperwork experience that is not related to the position, delete it.
> 2. **Describe the experience**: Write each of the retained points in a coherent sentence following the structure of "using a tool + accomplishing a task + achieving an effect/result". In the description, "using a tool" should be in line with [tools or skills to be mastered], "accomplishing a task" should be in line with [experience or experience recommended], "achieving an effect/result" should reflect proficiency in the use of [tools or skills to be mastered], and "achieving an effect/result" should reflect proficiency in the use of [tools or skills to be mastered]. "Achieving a certain effect/result" should reflect proficiency in the use of [required tools or skills], conformity with the [required duty characteristics of the job], or demonstration of mastery of [required background knowledge of the job].
> 3. **Reasonable use of words**: In the detailed description, please pay attention to the truthfulness of the words used and do not exaggerate. Use words such as "good at", "proficient in", "understand", etc. as appropriate.
> 4. **Data support**: In the section on results presentation, be sure to provide data support and avoid vague descriptions. For example, instead of using the phrase "made a significant contribution to a particular area", use specific indicators such as "reduced costs by 50%", "increased efficiency by 30%", etc.
> 5. **Missing information**: If there is any missing information in [My Experience], please leave the corresponding location so that I can make corrections and additions later.
> 
> Comprehensive examples:
>- Software Development Engineer
  (1) Developed a new feature using Flask that allows customers to save previous orders and reorder them with a single click.
  (2) Worked with two engineers to refactor the user interface using React.js, which reduced the time it took customers to purchase products by an average of 48%.
  (3) Improved the job board's buying process to make it easy to use, resulting in an increase in user satisfaction from 73% to 84%.
>
>If you have understood my request, please reply: i have understood, please provide [my experience].
