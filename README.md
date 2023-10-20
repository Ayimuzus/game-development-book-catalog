1. Computer Science（计算机科学）
	1. Structure and Interpretation of Computer Programs（计算机程序的结构和解释）
		1. Building Abstractions with Procedures（用过程构建抽象）（19）
			1. The Elements of Programming（编程的要素）（22）
				1. Expressions（表达式）（22）
				2. Naming and the Environment（命名与环境）（24）
				3. Evaluating Combinations（评估组合）（25）
				4. Compound Procedures（复合程序）（27）
				5. The Substitution Model for Procedure Application（程序申请的替代模型）（28）
					1. Applicative order versus normal order（应用顺序与正常顺序）（30）
				6. Conditional Expressions and Predicates（条件表达式和谓词）（31）
				7. Example: Square Roots by Newton's Method（示例：牛顿法求平方根）（35）
				8. Procedures as Black-Box Abstractions（作为黑盒抽象的过程）（38）
					1. Local names（当地名称）（39）
					2. Internal definitions and block structure（内部定义和块结构）（41）
			2. Procedures and the Processes They Generate（程序及其生成的过程）（45）
				1. Linear Recursion and Iteration（线性递归和迭代）（45）
				2. Tree Recursion（树递归）（49）
					1. Example: Counting change（示例：计算变化）（52）
				3. Orders of Growth（增长订单）（54）
				4. Exponentiation（求幂）（55）
				5. Greatest Common Divisors（最大公约数）（58）
				6. Example: Testing for Primality（示例：素性测试）（59）
					1. Searching for divisors（寻找除数）（59）
					2. The Fermat test（费马测试）（60）
					3. Probabilistic methods（概率方法）（61）
			3. Formulating Abstractions with Higher-Order Procedures（用高阶过程制定抽象）（67）
				1. Procedures as Arguments（作为参数的过程）（67）
				2. Constructing Procedures Using Lambda（使用 Lambda 构建过程）（71）
					1. Using let to create local variables（使用let创建局部变量）（73）
				3. Procedures as General Methods（作为一般方法的程序）（76）
					1. Finding roots of equations by the half-interval method（用半区间法求方程根）（76）
					2. Finding fixed points of functions（寻找函数的不动点）（78）
				4. Procedures as Returned Values（作为返回值的过程）（80）
					1. Newton's method（牛顿法）（81）
					2. Abstractions and first-class procedures（抽象和一流的程序）（83）
		2. Building Abstractions with Data（用数据构建抽象）（88）
			1. Introduction to Data Abstraction（数据抽象简介）（91）
				1. Example: Arithmetic Operations for Rational Numbers（示例：有理数的算术运算）（91）
					1. Pairs（对）（92）
					2. Representing rational numbers（表示有理数）（93）
				2. Abstraction Barriers（抽象障碍）（94）
				3. What Is Meant by Data?（数据是什么意思？）（96）
				4. Extended Exercise: Interval Arithmetic（扩展练习：区间算术）（99）
			2. Hierarchical Data and the Closure Property（分层数据和闭包属性）（104）
				1. Representing Sequences（表示序列）（105）
					1. List operations（列表操作）（106）
					2. Mapping over lists（映射列表）（109）
				2. Hierarchical Structures（层次结构）
					1. Mapping over trees（在树上绘制地图）（116）
				3. Sequences as Conventional Interfaces（作为传统接口的序列）（117）
					1. Sequence Operations（顺序操作）（119）
					2. Nested Mappings（嵌套映射）（124）
				4. Example: A Picture Language（示例：图像语言）（128）
					1. The picture language（画面语言）（129）
					2. Higher-order operations（高阶运算）（134）
					3. Frames（镜框）（135）
					4. Painters（画家）（136）
					5. Transforming and combining painters（画家的改造与结合）（137）
					6. Levels of language for robust design（稳健设计的语言级别）（138）
			3. Symbolic Data（符号数据）（144）
				1. Quotation（引述）（144）
				2. Example: Symbolic Differentiation（示例：符号微分）（146）
					1. The differentiation program with abstract data（抽象数据的微分程序）（147）
					2. Representing algebraic expressions（表示代数表达式）（148）
				3.  Example: Representing Sets（示例：表示集合）（151）
					1. Sets as unordered lists（设置为无序列表）（152）
					2. Sets as ordered lists（设置为有序列表）（153）
					3. Sets as binary trees（集合为二叉树）（154）
					4. Sets and information retrieval（集合和信息检索）（158）
				4. Example: Huffman Encoding Trees（示例：霍夫曼编码树）（159）
					1. Generating Huffman trees（生成霍夫曼树）（161）
					2. Representing Huffman trees（代表霍夫曼树）（162）
					3. The decoding procedure（解码过程）（163）
					4. Sets of weighted elements（加权元素集）（164）
			4. Multiple Representations for Abstract Data（抽象数据的多重表示）（168）
				1. Representations for Complex Numbers（复数的表示）（169）
				2. Tagged data（标记数据）（172）
				3. Data-Directed Programming and Additivity（数据导向编程和可加性）（175）
					1. Message passing（消息传递）（181）
			5. Systems with Generic Operations（具有通用操作的系统）（183）
				1. Generic Arithmetic Operations（通用算术运算）（183）
				2. Combining Data of Different Types（组合不同类型的数据）（188）
					1. Coercion（强迫）（188）
					2. Hierarchies of types（类型的层次结构）（190）
					3. Inadequacies of hierarchies（等级制度的不足之处）（192）
				3. Example: Symbolic Algebra（示例：符号代数）（194）
					1. Arithmetic on polynomials（多项式算术）（194）
					2. Representing term lists（表示术语列表）（198）
					3. Hierarchies of types in symbolic algebra（符号代数中类型的层次结构）（200）
					4. Extended exercise: Rational functions（扩展练习：有理函数）
		3. Modularity, Objects, and State（模块化、对象和状态）（207）
			1. Assignment and Local State（分配和本地状态）（209）
				1. Local State Variables（局部状态变量）（209）
				2. The Benefits of Introducing Assignment（引入作业的好处）（214）
				3. The Costs of Introducing Assignment（引入作业的成本）（217）
					1. Sameness and change（相同与变化）（219）
					2. Pitfalls of imperative programming（命令式编程的陷阱）（221）
			2. The Environment Model of Evaluation（评价环境模型）（224）
				1. The Rules for Evaluation（评审规则）（225）
				2. Applying Simple Procedures（应用简单的程序）（227）
				3. Frames as the Repository of Local State（框架作为本地状态的存储库）（230）
				4. Internal Definitions（内部定义）（235）
			3. Modeling with Mutable Data（使用可变数据建模）（238）
				1. Mutable List Structure（可变列表结构）（238）
					1. Sharing and identity（共享和身份）（243）
					2. Mutation is just assignment（变异只是赋值）（246）
				2. Representing Queues（代表队列）（247）
				3. Representing Tables（代表表格）（251）
					1. Two-dimensional tables（二维表）（253）
					2. Creating local tables（创建本地表）（254）
				4. A Simulator for Digital Circuits（数字电路模拟器）（257）
					1. Primitive function boxes（原始函数框）（259）
					2. Representing wires（代表电线）（261）
					3. The agenda（议程）（262）
					4. A sample simulation（模拟示例）（263）
					5. Implementing the agenda（落实议程）（265）
				5. Propagation of Constraints（约束的传播）（267）
					1. Using the constraint system（使用约束系统）（268）
					2. Implementing the constraint system（落实约束制度）（270）
					3. Representing connectors（代表连接器）（273）
			4. Concurrency: Time Is of the Essence（并发：时间至关重要）（279）
				1. The Nature of Time in Concurrent Systems（并发系统中时间的本质）（280）
					1. Correct behavior of concurrent programs（并发程序的正确行为）（281）
				2. Mechanisms for Controlling Concurrency（并发控制机制）（283）
					1. Serializing access to shared state（串行访问共享状态）（284）
					2. Serializers in Scheme（方案中的序列化器）（284）
					3. Complexity of using multiple shared resources（使用多个共享资源的复杂性）（287）
					4. Implementing serializers（实现序列化器）（290）
					5. Deadlock（僵局）（292）
					6. Concurrency, time, and communication（并发、时间和通信）（292）
			5. Streams（流）（296）
				1. Streams Are Delayed Lists（流是延迟列表）（296）
					1. The stream implementation in action（实际的流实现）（299）
					2. Implementing delay and force（实施延迟和强制）（301）
				2. Infinite Streams（无限流）（303）
					1. Defining streams implicitly（隐式定义流）（305）
				3. Exploiting the Stream Paradigm（利用流范式）（310）
					1. Formulating iterations as stream processes（将迭代表述为流过程）（310）
					2. Infinite streams of pairs（无限对流）（314）
					3. Streams as signals（流作为信号）（317）
				4. Streams and Delayed Evaluation（流和延迟评估）（320）
					1. Normal-order evaluation（正态顺序评估）（324）
				5. Modularity of Functional Programs and Modularity of Objects（功能程序的模块化和对象的模块化）（325）
					1. A functional-programming view of time（函数式编程的时间观）（326）
		4. Metalinguistic Abstraction（元语言抽象）（332）
			1. The Metacircular Evaluator（元循环评估器）（335）
				1. The Core of the Evaluator（评估器的核心）（335）
					1. Eval（评估）（336）
					2. Primitive expressions（原始表达式）（336）
					3. Special forms（特殊形式）（336）
					4. Combinations（组合）（337）
					5. Apply（申请）（337）
					6. Procedure arguments（过程参数）（338）
					7. Conditionals（条件句）（338）
					8. Sequences（序列）（339）
					9. Assignments and definitions（作业和定义）（339）
				2. Representing Expressions（表示表达式）（340）
					1. Derived expressions（派生表达式）（343）
				3. Evaluator Data Structures（评估器数据结构）（346）
					1. Testing of predicates（谓词测试）（346）
					2. Representing procedures（代表程序）（346）
					3. Operations on Environments（环境运营）（347）
				4. Running the Evaluator as a Program（将评估器作为程序运行）（350）
				5. Data as Programs（数据即程序）（352）
				6. Internal Definitions（内部定义）（354）
				7. Separating Syntactic Analysis from Execution（将语法分析与执行分离）（359）
			2. Variations on a Scheme -- Lazy Evaluation（方案的变体——惰性求值）（367）
				1. Normal Order and Applicative Order（正常顺序和适用顺序）（367）
				2. An Interpreter with Lazy Evaluation（具有惰性求值的解释器）（368）
					1. Modifying the evaluator（修改评估器）（369）
					2. Representing thunks（代表 thunk）（371）
				3. Streams as Lazy Lists（作为惰性列表的流）（375）
			3. Variations on a Scheme -- Nondeterministic Computing（方案的变体——非确定性计算）（379）
				1. Amb and Search（安布和搜索）（380）
					1. Driver loop（驱动循环）（381）
				2. Examples of Nondeterministic Programs（非确定性程序的示例）（383）
					1. Logic Puzzles（逻辑谜题）（383）
					2. Parsing natural language（解析自然语言）（385）
				3. Implementing the Amb Evaluator（实施 Amb 评估器）（389）
					1. Execution procedures and continuations（执行程序和延续）（389）
					2. Structure of the evaluator（评估器的结构）（391）
					3. Simple expressions（简单的表达）（392）
					4. Conditionals and sequences（条件和序列）（392）
					5. Definitions and assignments（定义和任务）（393）
					6. Procedure applications（程序申请）（394）
					7. Evaluating amb expressions（评估 amb 表达式）（396）
					8. Driver loop（驱动循环）（396）
			4. Logic Programming（逻辑编程）（401）
				1. Deductive Information Retrieval（演绎信息检索）（402）
					1. A sample data base（示例数据库）（403）
					2. Simple queries（简单查询）（404）
					3. Compound queries（复合查询）（407）
					4. Rules（规则）（409）
					5. Logic as programs（逻辑作为程序）（411）
				2. How the Query System Works（查询系统如何工作）（413）
					1. Pattern matching（模式匹配）（414）
					2. Streams of frames（帧流）（414）
					3. Compound queries（复合查询）（415）
					4. Unification（统一）（417）
					5. Applying rules（应用规则）（418）
					6. Simple queries（简单查询）（419）
					7. The query evaluator and the driver loop（查询评估器和驱动程序循环）（420）
				3. Is Logic Programming Mathematical Logic?（逻辑编程是数学逻辑吗？）（420）
					1. Infinite loops（无限循环）（421）
					2. Problems with not（问题不）（422）
				4. Implementing the Query System（实施查询系统）（425）
					1. The Driver Loop and Instantiation（驱动程序循环和实例化）（425）
					2. The Evaluator（评估者）（426）
						1. Simple queries（简单查询）（426）
						2. Compound queries（复合查询）（427）
						3. Filters（过滤器）（428）
					3. Finding Assertions by Pattern Matching（通过模式匹配查找断言）（429）
						1. Patterns with dotted tails（带有点尾的图案）（430）
					4. Rules and Unification（规则与统一）（431）
					5. Maintaining the Data Base（维护数据库）（434）
					6. Stream Operations（流操作）（436）
					7. Query Syntax Procedures（查询语法过程）（437）
					8. Frames and Bindings（框架和装订）（439）
		5. Computing with Register Machines（使用寄存器机进行计算）（446）
			1. Designing Register Machines（设计套准机）（448）
				1. A Language for Describing Register Machines（一种描述寄存器机的语言）（450）
					1. Actions（行动）（453）
				2. Abstraction in Machine Design（机械设计中的抽象）（454）
				3. Subroutines（子程序）（456）
				4. Using a Stack to Implement Recursion（使用堆栈实现递归）（460）
					1. A double recursion（双重递归）（462）
				5. Instruction Summary（指令摘要）（464）
			2. A Register-Machine Simulator（寄存器机模拟器）（466）
				1. The Machine Model（机器模型）（467）
					1. Registers（寄存器）（468）
					2. The stack（堆栈）（468）
					3. The basic machine（基本机器）（469）
				2. The Assembler（组装者）（471）
				3. Generating Execution Procedures for Instructions（生成指令执行程序）（473）
					1. Assign instructions（分配指令）（474）
					2. Test, branch, and goto instructions（测试、分支和跳转指令）（475）
					3. Other instructions（其他说明）（476）
					4. Execution procedures for subexpressions（子表达式的执行过程）（477）
				4. Monitoring Machine Performance（监控机器性能）（480）
			3. Storage Allocation and Garbage Collection（存储分配和垃圾收集）（484）
				1. Memory as Vectors（内存作为向量）（484）
					1. Representing Lisp data（表示 Lisp 数据）（485）
					2. Implementing the primitive list operations（实现原始列表操作）（486）
					3. Implementing stacks（实现堆栈）（487）
				2. Maintaining the Illusion of Infinite Memory（维持无限内存的幻觉）（489）
					1. Implementation of a stop-and-copy garbage collector（停止并复制垃圾收集器的实现）（489）
			4. The Explicit-Control Evaluator（显式控制评估器）（495）
				1. The Core of the Explicit-Control Evaluator（显式控制评估器的核心）（496）
					1. Evaluating simple expressions （评估简单表达式）（497）
					2. Evaluating procedure applications（评估程序应用）（498）
					3. Procedure application（程序申请）（500）
				2. Sequence Evaluation and Tail Recursion（序列评估和尾递归）（501）
					1. Tail recursion（尾递归）（502）
				3. Conditionals, Assignments, and Definitions（条件、赋值和定义）（503）
					1. Assignments and definitions（作业和定义）（504）
				4. Running the Evaluator（运行评估器）（505）
					1. Monitoring the performance of the evaluator（监控评估者的表现）（507）
			5. Compilation（汇编）（512）
				1. Structure of the Compiler（编译器的结构）（514）
					1. Targets and linkages（目标和联系）（514）
					2. Instruction sequences and stack usage（指令序列和堆栈使用）（515）
				2. Compiling Expressions（编译表达式）（517）
					1. Compiling linkage code（编译链接代码）（517）
					2. Compiling simple expressions（编译简单表达式）（518）
					3. Compiling conditional expressions（编译条件表达式）（519）
					4. Compiling sequences（编译序列）（520）
					5. Compiling lambda expressions（编译 lambda 表达式）（521）
				3. Compiling Combinations（编译组合）（522）
					1. Applying procedures（申请程序）（524）
					2. Applying compiled procedures（应用已编译的程序）（525）
				4. Combining Instruction Sequences（组合指令序列）（527）
				5. An Example of Compiled Code（编译代码示例）（529）
			6. Lexical Addressing（词法寻址）（537）
			7. Interfacing Compiled Code to the Evaluator（将编译代码连接到评估器）（540）
				1. Interpretation and compilation（解释与编译）（542）