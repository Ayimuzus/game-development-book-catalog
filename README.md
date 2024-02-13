1. Computer Science（计算机科学）
	1. Structure and Interpretation of Computer Programs（计算机程序的构造和解释）
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
	2. Computer Systems A Programmer’s Perspective（深入理解计算机系统）
		1. 1
			1. A Tour of Computer Systems（计算机系统之旅）（38）
				1. Information Is Bits + Context（信息就是比特+上下文）（40）
				2. Programs Are Translated by Other Programs into Different Forms（程序被其他程序翻译成不同的形式）（41）
				3. It Pays to Understand How Compilation Systems Work（了解编译系统如何工作是值得的）（43）
				4. Processors Read and Interpret Instructions Stored in Memory（处理器读取并解释存储在内存中的指令）（44）
					1. Hardware Organization of a System（系统的硬件组织）（45）
						1. Buses（总线）（45）
						2. I/O Devices（输入/输出设备）（46）
						3. Main Memory（主内存）（46）
						4. Processor（处理器）（46）
					2. Running the hello Program（运行hello程序）（47）
				5. Caches Matter（缓存很重要）（48）
				6. Storage Devices Form a Hierarchy（存储设备形成层次结构）（51）
				7. The Operating System Manages the Hardware（操作系统管理硬件）（51）
					1. Processes（流程）（52）
					2. Threads（线程）（54）
					3. Virtual Memory（虚拟内存）（55）
					4. Files（文件）（56）
				8. Systems Communicate with Other Systems Using Networks（系统使用网络与其他系统通信）（56）
				9. Important Themes（重要主题）（59）
					1. Amdahl’s Law（阿姆达尔定律）（59）
					2. Concurrency and Parallelism（并发和并行）（61）
						1. Thread-Level Concurrency（线程级并发）（61）
						2. Instruction-Level Parallelism（指令级并行性）（63）
						3. Single-Instruction, Multiple-Data (SIMD) Parallelism（单指令、多数据  (SIMD)  并行）（63）
					3. The Importance of Abstractions in Computer Systems（计算机系统中抽象的重要性）（63）
		2. Program Structure and Execution（程序结构和执行）（66）
			1. Representing and Manipulating Information（表示和操纵信息）（68）
				1. Information Storage（信息存储）（71）
					1. Hexadecimal Notation（十六进制表示法）（73）
					2. Data Sizes（数据大小）（76）
					3. Addressing and Byte Ordering（寻址和字节顺序）（79）
					4. Representing Strings（表示字符串）（86）
					5. Representing Code（表示代码）（86）
					6. Introduction to Boolean Algebra（布尔代数简介）（87）
					7. Bit-Level Operations in C（C  中的位级操作）（91）
					8. Logical Operations in C（C  中的逻辑运算）（93）
					9. Shift Operations in C（C  中的移位运算）（94）
				2. Integer Representations（整数表示）（96）
					1. Integral Data Types（整数数据类型）（97）
					2. Unsigned Encodings（无符号编码）（99）
					3. Two’s-Complement Encodings（补码编码）（101）
					4. Conversions between Signed and Unsigned（有符号和无符号之间的转换）（107）
					5. Signed versus Unsigned in C（C  中的有符号与无符号）（111）
					6. Expanding the Bit Representation of a Number（扩展数字的位表示）（113）
					7. Truncating Numbers（截断数字）（118）
					8. Advice on Signed versus Unsigned（关于签名与未签名的建议）（120）
				3. Integer Arithmetic（整数运算）（121）
					1. Unsigned Addition（无符号加法）（121）
					2. Two’s-Complement Addition（补码加法）（127）
					3. Two’s-Complement Negation（补码否定）（132）
					4. Unsigned Multiplication（无符号乘法）（133）
					5. Two’s-Complement Multiplication（补码乘法）（134）
					6. Multiplying by Constants（乘以常数）（138）
					7. Dividing by Powers of 2（除以  2  的幂）（140）
					8. Final Thoughts on Integer Arithmetic（关于整数运算的最终思考）（144）
				4. Floating Point（浮点）（145）
					1. Fractional Binary Numbers（二进制小数）（146）
					2. IEEE Floating-Point Representation（IEEE  浮点表示）（149）
						1. Case 1: Normalized Values（案例  1：标准化值）（150）
						2. Case 2: Denormalized Values（案例  2：非规范化值）（151）
						3. Case 3: Special Values（案例  3：特殊值）（152）
					3. Example Numbers（数字示例）（152）
					4. Rounding（舍入）（157）
					5. Floating-Point Operations（浮点运算）（159）
					6. Floating Point in C（C  中的浮点）（161）
			2. Machine-Level Representation of Programs（程序的机器级表示）（200）
				1. A Historical Perspective（历史视角）（203）
				2. Program Encodings（程序编码）（206）
					1. Machine-Level Code（机器级代码）（207）
					2. Code Examples（代码示例）（209）
					3. Notes on Formatting（格式化注意事项）（212）
				3. Data Formats（数据格式）（214）
				4. Accessing Information（获取信息）（216）
					1. Operand Specifiers（操作数说明符）（217）
					2. Data Movement Instructions（数据移动指令）（219）
					3. Data Movement Example（数据移动示例）（223）
					4. Pushing and Popping Stack Data（堆栈数据的压入和弹出）（226）
				5. Arithmetic and Logical Operations（算术和逻辑运算）（228）
					1. Load Effective Address（加载有效地址）（228）
					2. Unary and Binary Operations（一元和二元运算）（231）
					3. Shift Operations（移位操作）（231）
					4. Discussion（讨论）（233）
					5. Special Arithmetic Operations（特殊算术运算）（234）
				6. Control（控制）（237）
					1. Condition Codes（条件代码）（238）
					2. Accessing the Condition Codes（访问条件代码）（239）
					3. Jump Instructions（跳转指令）（242）
					4. Jump Instruction Encodings（跳转指令编码）（244）
					5. Implementing Conditional Branches with Conditional Control（用条件控制实现条件分支）（246）
					6. Implementing Conditional Branches with Conditional Moves（通过条件移动实现条件分支）（251）
					7. Loops（循环）（257）
						1. Do-While Loops（Do‑While  循环）（257）
						2. While Loops（While  循环）（260）
						3. For Loops（For  循环）（265）
					8. Switch Statements（Switch语句）（269）
				7. Procedures（程序）（275）
					1. The Run-Time Stack（运行时堆栈）（276）
					2. Control Transfer（控制转移）（278）
					3. Data Transfer（数据传输）（282）
					4. Local Storage on the Stack（堆栈本地存储）（285）
					5. Local Storage in Registers（寄存器中的本地存储）（288）
					6. Recursive Procedures（递归过程）（290）
				8. Array Allocation and Access（数组分配和访问）（292）
					1. Basic Principles（基本原理）（292）
					2. Pointer Arithmetic（指针运算）（294）
					3. Nested Arrays（嵌套数组）（295）
					4. Fixed-Size Arrays（固定大小的数组）（297）
					5. Variable-Size Arrays（可变大小数组）（299）
				9. Heterogeneous Data Structures（异构数据结构）（302）
					1. Structures（结构）（302）
					2. Unions（工会）（306）
					3. Data Alignment（数据对齐）（310）
				10. Combining Control and Data in Machine-Level Programs（在机器级程序中结合控制和数据）（313）
					1. Understanding Pointers（理解指针）（314）
					2. Life in the Real World: Using the gdb Debugger（现实世界中的生活：使用gdb调试器）（316）
					3. Out-of-Bounds Memory References and Buffer Overflow（越界内存引用和缓冲区溢出）（316）
					4. Thwarting Buffer Overflow Attacks（阻止缓冲区溢出攻击）（321）
						1. Stack Randomization（堆栈随机化）（321）
						2. Stack Corruption Detection（堆栈损坏检测）（323）
						3. Limiting Executable Code Regions（限制可执行代码区域）（326）
					5. Supporting Variable-Size Stack Frames（支持可变大小的堆栈帧）（327）
				11. Floating-Point Code（浮点代码）（330）
					1. Floating-Point Movement and Conversion Operations（浮点移动和转换操作）（333）
					2. Floating-Point Code in Procedures（过程中的浮点代码）（338）
					3. Floating-Point Arithmetic Operations（浮点算术运算）（339）
					4. Defining and Using Floating-Point Constants（定义和使用浮点常量）（341）
					5. Using Bitwise Operations in Floating-Point Code（在浮点代码中使用按位运算）（342）
					6. Floating-Point Comparison Operations（浮点比较运算）（343）
					7. Observations about Floating-Point Code（关于浮点代码的观察）（346）
			3. Processor Architecture（处理器架构）（388）
				1. The Y86-64 Instruction Set Architecture（Y86‑64指令集架构）（392）
					1. Programmer-Visible State（程序员可见的状态）（392）
					2. Y86-64 Instructions（Y86‑64  使用说明）（393）
					3. Instruction Encoding（指令编码）（395）
					4. Y86-64 Exceptions（Y86‑64  例外情况）（400）
					5. Y86-64 Programs（Y86‑64  程序）（401）
					6. Some Y86-64 Instruction Details（一些Y86‑64指令细节）（407）
				2. Logic Design and the Hardware Control Language HCL（逻辑设计和硬件控制语言HCL）（409）
					1. Logic Gates（逻辑门）（410）
					2. Combinational Circuits and HCL Boolean Expressions（组合电路和HCL布尔表达式）（411）
					3. Word-Level Combinational Circuits and HCL Integer Expressions（字级组合电路和HCL整数表达式）（413）
					4. Set Membership（设置成员资格）（417）
					5. Memory and Clocking（内存和时钟）（418）
				3. Sequential Y86-64 Implementations（顺序  Y86‑64  实现）（421）
					1. Organizing Processing into Stages（将处理分为阶段）（421）
					2. SEQ Hardware Structure（SEQ  硬件结构）（433）
					3. SEQ Timing（SEQ  时序）（437）
					4. SEQ Stage Implementations（SEQ  阶段实现）（441）
						1. Fetch Stage（获取阶段）（442）
						2. Decode and Write-Back Stages（解码和回写阶段）（443）
						3. Execute Stage（执行阶段）（445）
						4. Memory Stage（记忆阶段）（446）
						5. PC Update Stage（PC  更新阶段）（448）
						6. Surveying SEQ（测量序列）（448）
				4. General Principles of Pipelining（流水线的一般原则）（449）
					1. Computational Pipelines（计算管道）（449）
					2. A Detailed Look at Pipeline Operation（管道操作的详细介绍）（451）
					3. Limitations of Pipelining（流水线的局限性）（453）
						1. Nonuniform Partitioning（非均匀划分）（453）
						2. Diminishing Returns of Deep Pipelining（深度流水线的回报递减）（455）
					4. Pipelining a System with Feedback（带反馈的流水线系统）（456）
				5. Pipelined Y86-64 Implementations（流水线  Y86‑64  实现）（458）
					1. SEQ+: Rearranging the Computation Stages（SEQ+：重新安排计算阶段）（458）
					2. Inserting Pipeline Registers（插入流水线寄存器）（459）
					3. Rearranging and Relabeling Signals（重新排列和重新标记信号）（463）
					4. Next PC Prediction（下一台PC预测）（464）
					5. Pipeline Hazards（管道危险）（466）
						1. Avoiding Data Hazards by Stalling（通过停止来避免数据危险）（470）
						2. Avoiding Data Hazards by Forwarding（通过转发避免数据危险）（473）
						3. Load/Use Data Hazards（加载/使用数据危险）（476）
						4. Avoiding Control Hazards（避免控制风险）（478）
					6. Exception Handling（异常处理）（481）
					7. PIPE Stage Implementations（PIPE  阶段实现）（484）
						1. PC Selection and Fetch Stage（PC  选择和获取阶段）（484）
						2. Decode and Write-Back Stages（解码和回写阶段）（486）
						3. Execute Stage（执行阶段）（490）
						4. Memory Stage（记忆阶段）（491）
					8. Pipeline Control Logic（流水线控制逻辑）（492）
						1. Desired Handling of Special Control Cases（特殊控制案例的期望处理）（492）
						2. Detecting Special Control Conditions（检测特殊控制条件）（494）
						3. Pipeline Control Mechanisms（管道控制机制）（496）
						4. Combinations of Control Conditions（控制条件的组合）（497）
						5. Control Logic Implementation（控制逻辑实现）（499）
					9. Performance Analysis（性能分析）（501）
					10. Unfinished Business（未完成的事情）（505）
						1. Multicycle Instructions（多周期指令）（505）
						2. Interfacing with the Memory System（与内存系统的接口）（506）
			4. Optimizing Program Performance（优化程序性能）（532）
				1. Capabilities and Limitations of Optimizing Compilers（优化编译器的功能和限制）（535）
				2. Expressing Program Performance（表达程序性能）（539）
				3. Program Example（程序示例）（541）
				4. Eliminating Loop Inefficiencies（消除循环效率低下）（545）
				5. Reducing Procedure Calls（减少过程调用）（549）
				6. Eliminating Unneeded Memory References（消除不需要的内存引用）（551）
				7. Understanding Modern Processors（理解现代处理器）（554）
					1. Overall Operation（整体运行情况）（555）
					2. Functional Unit Performance（功能单元性能）（560）
					3. An Abstract Model of Processor Operation（处理器操作的抽象模型）（562）
						1. From Machine-Level Code to Data-Flow Graphs（从机器级代码到数据流图）（562）
						2. Other Performance Factors（其他性能因素）（566）
				8. Loop Unrolling（循环展开）（568）
				9. Enhancing Parallelis（增强并行性）（573）
					1. Multiple Accumulators（多个累加器）（573）
					2. Reassociation Transformation（重关联变换）（578）
				10. Summary of Results for Optimizing Combining Code（优化组合代码结果总结）（584）
				11. Some Limiting Factors（一些限制因素）（585）
					1. Register Spilling（寄存器溢出）（585）
					2. Branch Prediction and Misprediction Penalties（分支预测和错误预测惩罚）（586）
						1. Do Not Be Overly Concerned about Predictable Branches（不要过度担心可预测的分支）（587）
						2. Write Code Suitable for Implementation with Conditional Moves（编写适合通过条件移动实现的代码）（588）
				12. Understanding Memory Performance（了解内存性能）（590）
					1. Load Performance（负载性能）（591）
					2. Store Performance（商店绩效）（592）
				13. Life in the Real World: Performance Improvement Techniques（现实世界中的生活：绩效改进技巧）（598）
				14. Identifying and Eliminating Performance Bottlenecks（识别和消除性能瓶颈）（599）
					1. Program Profiling（程序分析）（599）
					2. Using a Profiler to Guide Optimization（使用分析器指导优化）（602）
			5. The Memory Hierarchy（内存层次结构）（616）
				1. Storage Technologies（存储技术）（618）
					1. Random Access Memory（随机存取存储器）（618）
						1. Static RAM（静态内存）（618）
						2. Dynamic RAM（动态内存）（619）
						3. Conventional DRAMs（传统  DRAM）（619）
						4. Memory Modules（内存模块）（621）
						5. Enhanced DRAMs（增强型  DRAM）（622）
						6. Nonvolatile Memory（非易失性存储器）（623）
						7. Accessing Main Memory（访问主内存）（624）
					2. Disk Storage（磁盘存储）（626）
						1. Disk Geometry（磁盘几何结构）（627）
						2. Disk Capacity（磁盘容量）（628）
						3. Disk Operation（磁盘操作）（629）
						4. Logical Disk Blocks（逻辑磁盘块）（632）
						5. Connecting I/O Devices（连接  I/O  设备）（633）
						6. Accessing Disks（访问磁盘）（634）
					3. Solid State Disks（固态硬盘）（637）
					4. Storage Technology Trends（存储技术趋势）（639）
				2. Locality（局部性）（641）
					1. Locality of References to Program Data（程序数据引用的位置）（643）
					2. Locality of Instruction Fetches（指令获取的局部性）（644）
					3. Summary of Locality（局部性总结）（645）
				3. The Memory Hierarchy（内存层次结构）（646）
					1. Caching in the Memory Hierarchy（内存层次结构中的缓存）（647）
						1. Cache Hits（缓存命中）（649）
						2. Cache Misses（缓存未命中）（649）
						3. Kinds of Cache Misses（缓存未命中的类型）（649）
						4. Cache Management（缓存管理）（650）
					2. Summary of Memory Hierarchy Concepts（内存层次结构概念总结）（651）
				4. Cache Memories（高速缓冲存储器）（651）
					1. Generic Cache Memory Organization（通用高速缓冲存储器组织）（652）
					2. Direct-Mapped Caches（直接映射缓存）（654）
						1. Set Selection in Direct-Mapped Caches（在直接映射缓存中设置选择）（655）
						2. Line Matching in Direct-Mapped Caches（直接映射缓存中的行匹配）（655）
						3. Word Selection in Direct-Mapped Caches（直接映射缓存中的字选择）（656）
						4. Line Replacement on Misses in Direct-Mapped Caches（直接映射缓存中未命中时的行替换）（656）
						5. Putting It Together: A Direct-Mapped Cache in Action（放在一起：直接映射缓存的实际应用）（656）
						6. Conflict Misses in Direct-Mapped Caches（直接映射缓存中的冲突未命中）（659）
					3. Set Associative Caches（设置关联缓存）（661）
						1. Set Selection in Set Associative Caches（集关联缓存中的集选择）（662）
						2. Line Matching and Word Selection in Set Associative Caches（组关联高速缓存中的行匹配和字选择）（662）
						3. Line Replacement on Misses in Set Associative Caches（组关联高速缓存中未命中时的行替换）（663）
					4. Fully Associative Caches（全关联缓存）（663）
						1. Set Selection in Fully Associative Caches（在全关联缓存中设置选择）（664）
						2. Line Matching and Word Selection in Fully Associative Caches（全关联缓存中的行匹配和字选择）（664）
					5. Issues with Writes（写入问题）（667）
					6. Anatomy of a Real Cache Hierarchy（真实缓存层次结构剖析）（668）
					7. Performance Impact of Cache Parameters（缓存参数的性能影响）（668）
						1. Impact of Cache Size（缓存大小的影响）（669）
						2. Impact of Block Size（区块大小的影响）（670）
						3. Impact of Associativity（关联性的影响）（670）
						4. Impact of Write Strategy（写入策略的影响）（670）
				5. Writing Cache-Friendly Code（编写缓存友好的代码）（670）
				6. Putting It Together: The Impact of Caches on Program Performance（综合起来：缓存对程序性能的影响）（676）
					1. The Memory Mountain（记忆山）（676）
					2. Rearranging Loops to Increase Spatial Locality（重新排列循环以增加空间局部性）（680）
					3. Exploiting Locality in Your Programs（在程序中利用局部性）（684）
		3. Running Programs on a System（在系统上运行程序）（924）
			1. Linking（链接）（706）
				1. Compiler Drivers（编译驱动程序）（708）
				2. Static Linking（静态链接）（709）
				3. Object Files（目标文件）（710）
				4. Relocatable Object Files（可重定位目标文件）（711）
				5. Symbols and Symbol Tables（符号和符号表）（712）
				6. Symbol Resolution（符号解析）（716）
					1. How Linkers Resolve Duplicate Symbol Names（链接器如何解决重复的符号名称）（717）
					2. Linking with Static Libraries（与静态库链接）（721）
					3. How Linkers Use Static Libraries to Resolve References（链接器如何使用静态库来解析引用）（725）
				7. Relocation（搬迁）（726）
					1. Relocation Entries（重定位条目）（727）
					2. Relocating Symbol References（重新定位符号引用）（728）
						1. Relocating PC-Relative References（重新定位  PC  相关参考）（729）
						2. Relocating Absolute References（重新定位绝对引用）（730）
				8. Executable Object Files（可执行目标文件）（732）
				9. Loading Executable Object Files（加载可执行目标文件）（734）
				10. Dynamic Linking with Shared Libraries（与共享库的动态链接）（735）
				11. Loading and Linking Shared Libraries from Applications（从应用程序加载和链接共享库）（738）
				12. Position-Independent Code (PIC)（位置无关代码（PIC））（741）
					1. PIC Data References（PIC  数据参考）（741）
					2. PIC Function Calls（PIC  函数调用）（742）
				13. Library Interpositioning（库插入）（744）
					1. Compile-Time Interpositioning（编译时插入）（745）
					2. Link-Time Interpositioning（链接时插入）（745）
					3. Run-Time Interpositioning（运行时插入）（747）
				14. Tools for Manipulating Object Files（操作目标文件的工具）（750）
			2. Exceptional Control Flow（卓越的控制流程）（758）
				1. Exceptions（例外情况）（760）
					1. Exception Handling（异常处理）（761）
					2. Classes of Exceptions（异常类别）（763）
						1. Interrupts（中断）（763）
						2. Traps and System Calls（陷阱和系统调用）（764）
						3. Faults（故障）（765）
						4. Aborts（中止）（765）
					3. Exceptions in Linux/x86-64 Systems（Linux/x86‑64  系统中的异常）（766）
						1. Linux/x86-64 Faults and Aborts（Linux/x86‑64  故障和中止）（766）
						2. Linux/x86-64 System Calls（Linux/x86‑64  系统调用）（766）
				2. Processes（流程）（769）
					1. Logical Control Flow（逻辑控制流程）（769）
					2. Concurrent Flows（并发流）（770）
					3. Private Address Space（私有地址空间）（771）
					4. User and Kernel Modes（用户模式和内核模式）（771）
					5. Context Switches（上下文切换）（773）
				3. System Call Error Handling（系统调用错误处理）（774）
				4. Process Control（过程控制）（775）
					1. Obtaining Process IDs（获取进程ID）（776）
					2. Creating and Terminating Processes（创建和终止进程）（776）
					3. Reaping Child Processes（收割子进程）（780）
						1. Determining the Members of the Wait Set（确定等待集的成员）（781）
						2. Modifying the Default Behavior（修改默认行为）（781）
						3. Checking the Exit Status of a Reaped Child（检查收割子进程的退出状态）（782）
						4. Error Conditions（错误情况）（782）
						5. The wait Function（等待函数）（783）
						6. Examples of Using waitpid（使用waitpid）（783）
					4. Putting Processes to Sleep（让进程进入睡眠状态）（786）
					5. Loading and Running Programs（加载和运行程序）（787）
					6. Using fork and execve to Run Programs（使用fork和execve运行程序）（790）
				5. Signals（信号）（793）
					1. Signal Terminology（信号术语）（795）
					2. Sending Signals（发送信号）（796）
						1. Process Groups（进程组）（796）
						2. Sending Signals with the /bin/kill Program（使用/bin/kill程序）（797）
						3. Sending Signals from the Keyboard（从键盘发送信号）（797）
						4. Sending Signals with the kill Function（使用kill函数）（798）
						5. Sending Signals with the alarm Function（发送信号并具有报警功能）（799）
					3. Receiving Signals（接收信号）（799）
					4. Blocking and Unblocking Signals（阻塞和解除阻塞信号）（801）
					5. Writing Signal Handlers（编写信号处理程序）（803）
						1. Safe Signal Handling（安全信号处理）（803）
						2. Correct Signal Handling（正确的信号处理）（807）
						3. Portable Signal Handling（便携式信号处理）（811）
					6. Synchronizing Flows to Avoid Nasty Concurrency Bugs（同步流程以避免严重的并发错误）（813）
					7. Explicitly Waiting for Signals（显式等待信号）（815）
				6. Nonlocal Jumps（非局部跳转）（818）
				7. Tools for Manipulating Processes（操作流程的工具）（823）
			3. Virtual Memory（虚拟内存）（838）
				1. Physical and Virtual Addressing（物理和虚拟寻址）（840）
				2. Address Spaces（地址空间）（841）
				3. VM as a Tool for Caching（VM作为缓存工具）（842）
					1. DRAM Cache Organization（DRAM  缓存组织）（842）
					2. Page Tables（页表）（843）
					3. Page Hits（页面点击量）（845）
					4. Page Faults（页面错误）（845）
					5. Allocating Pages（分配页面）（847）
					6. Locality to the Rescue Again（局部性再次发挥作用）（847）
				4. VM as a Tool for Memory Management（VM作为内存管理工具）（849）
				5. VM as a Tool for Memory Protection（VM作为内存保护工具）（849）
				6. Address Translation（地址转换）（850）
					1. Integrating Caches and VM（集成缓存和VM）（854）
					2. Speeding Up Address Translation with a TLB（使用  TLB  加速地址转换）（854）
					3. Multi-Level Page Tables（多级页表）（856）
					4. Putting It Together: End-to-End Address Translation（综合起来：端到端地址转换）（858）
				7. Case Study: The Intel Core i7/Linux Memory System（案例研究：Intel  Core  i7/Linux  内存系统）（862）
					1. Core i7 Address Translation（酷睿  i7  地址转换）（863）
					2. Linux Virtual Memory System（Linux  虚拟内存系统）（865）
						1. Linux Virtual Memory Areas（Linux  虚拟内存区域）（867）
						2. Linux Page Fault Exception Handling（Linux  页面错误异常处理）（869）
				8. Memory Mapping（内存映射）（870）
					1. Shared Objects Revisited（重新审视共享对象）（870）
					2. The fork Function Revisited（回顾fork函数）（873）
					3. The execve Function Revisited（重温execve函数）（873）
					4. User-Level Memory Mapping with the mmap Function（使用mmap函数进行用户级内存映射）（874）
				9. Dynamic Memory Allocation（动态内存分配）（876）
					1. The malloc and free Functions（malloc和free函数）（877）
					2. Why Dynamic Memory Allocation?（为什么要动态内存分配？）（880）
					3. Allocator Requirements and Goals（分配器要求和目标）（881）
					4. Fragmentation（碎片化）（883）
					5. Implementation Issues（实施问题）（883）
					6. Implicit Free Lists（隐式空闲列表）（884）
					7. Placing Allocated Blocks（放置分配的块）（886）
					8. Splitting Free Blocks（分割空闲块）（886）
					9. Getting Additional Heap Memory（获取额外的堆内存）（887）
					10. Coalescing Free Blocks（合并空闲块）（887）
					11. Coalescing with Boundary Tags（与边界标签的合并）（888）
					12. Putting It Together: Implementing a Simple Allocator（组合起来：实现一个简单的分配器）（891）
						1. General Allocator Design（通用分配器设计）（891）
						2. Basic Constants and Macros for Manipulating the Free List（用于操作空闲列表的基本常量和宏）（893）
						3. Creating the Initial Free List（创建初始空闲列表）（894）
						4. Freeing and Coalescing Blocks（释放和合并块）（896）
						5. Allocating Blocks（分配块）（896）
					13. Explicit Free Lists（显式空闲列表）（899）
					14. Segregated Free Lists（隔离的空闲列表）（900）
						1. Simple Segregated Storage（简单的隔离存储）（901）
						2. Segregated Fits（隔离配合）（901）
						3. Buddy Systems（好友系统）（902）
				10. Garbage Collection（垃圾收集）（902）
					1. Garbage Collector Basics（垃圾收集器基础知识）（903）
					2. Mark&Sweep Garbage Collectors（标记和清除垃圾收集器）（904）
					3. Conservative Mark&Sweep for C Programs（C  程序的保守标记和清除）（906）
				11. Common Memory-Related Bugs in C Programs（C  程序中与内存相关的常见错误）（907）
					1. Dereferencing Bad Pointers（取消引用坏指针）（907）
					2. Reading Uninitialized Memory（读取未初始化的内存）（908）
					3. Allowing Stack Buffer Overflows（允许堆栈缓冲区溢出）（908）
					4. Assuming That Pointers and the Objects They Point to Are the Same Size（假设指针和它们指向的对象大小相同）（909）
					5. Making Off-by-One Errors（犯差一错误）（909）
					6. Referencing a Pointer Instead of the Object It Points To（引用指针而不是它指向的对象）（910）
					7. Misunderstanding Pointer Arithmetic（误解指针运算）（910）
					8. Referencing Nonexistent Variables（引用不存在的变量）（911）
					9. Referencing Data in Free Heap Blocks（引用空闲堆块中的数据）（911）
					10. Introducing Memory Leaks（引入内存泄漏）（912）
		4. Interaction and Communication between Programs（程序之间的交互和通信）（924）
			1. System-Level I/O（系统级  I/O）（926）
				1. Unix I/O（Unix  输入/输出）（927）
				2. Files（文件）（928）
				3. Opening and Closing Files（打开和关闭文件）（930）
				4. Reading and Writing Files（读写文件）（932）
				5. Robust Reading and Writing with the Rio Package（使用 Rio 包实现强大的读写能力）（934）
					1. Rio Unbuffered Input and Output Functions（Rio无缓冲输入和输出函数）（934）
					2. Rio Buffered Input Functions（Rio缓冲输入函数）（935）
				6. Reading File Metadata（读取文件元数据）（940）
				7. Reading Directory Contents（读取目录内容）（942）
				8. Sharing Files（共享文件）（943）
				9. I/O Redirection（I/O  重定向）（946）
				10. Standard I/O（标准输入/输出）（948）
				11. Putting It Together: Which I/O Functions Should I Use?（综合起来：我应该使用哪些  I/O  函数？）（948）
			2. Network Programming（网络编程）（954）
				1. The Client-Server Programming Model（客户端‑服务器编程模型）（955）
				2. Networks（网络）（956）
				3. The Global IP Internet（全球IP互联网）（961）
					1. IP Addresses（IP  地址）（962）
					2. Internet Domain Names（互联网域名）（964）
					3. Internet Connections（互联网连接）（966）
				4. The Sockets Interface（套接字接口）（969）
					1. Socket Address Structures（套接字地址结构）（970）
					2. The socket Function（套接字功能）（971）
					3. The connect Function（连接函数）（971）
					4. The bind Function（绑定函数）（972）
					5. The listen Function（监听函数）（972）
					6. The accept Function（接受函数）（973）
					7. Host and Service Conversion（主机和服务转换）（974）
						1. The getaddrinfo Function（getaddrinfo函数）（974）
						2. The getnameinfo Function（getnameinfo函数）（977）
					8. Helper Functions for the Sockets Interface（套接字接口的辅助函数）（979）
						1. The open_clientfd Function（open_clientfd函数）（979）
						2. The open_listenfd Function（open_listenfd函数）（981）
					9. Example Echo Client and Server（Echo  客户端和服务器示例）（981）
				5. Web Servers（网络服务器）（985）
					1. Web Basics（网络基础知识）（985）
					2. Web Content（网页内容）（986）
					3. HTTP Transactions（HTTP  事务）（987）
						1. HTTP Requests（HTTP  请求）（988）
						2. HTTP Responses（HTTP  响应）（989）
					4. Serving Dynamic Content（提供动态内容）（990）
						1. How Does the Client Pass Program Arguments to the Server?（客户端如何将程序参数传递给服务器？）（990）
						2. How Does the Server Pass Arguments to the Child?（服务器如何将参数传递给子进程？）（990）
						3. How Does the Server Pass Other Information to the Child?（服务器如何将其他信息传递给子进程？）（991）
						4. Where Does the Child Send Its Output?（子进程将其输出发送到哪里？）（991）
				6. Putting It Together: The Tiny Web Server（组合起来：微型Web  服务器）（993）
					1. The Tiny main Routine（微小的主例程）（993）
					2. The doit Function（doit函数）（993）
					3. The clienterror Function（客户端错误函数）（996）
					4. The read_requesthdrs Function（read_requesthdrs函数）（997）
					5. The parse_uri Function（parse_uri函数）（997）
					6. The serve_static Function（serve_static函数）（998）
					7. The serve_dynamic Function（serve_dynamic函数）（1000）
			3. Concurrent Programming（并发编程）（1008）
				1. Concurrent Programming with Processes（进程的并发编程）（1010）
					1. A Concurrent Server Based on Processes（基于进程的并发服务器）（1011）
					2. Pros and Cons of Processes（流程的优缺点）（1012）
				2. Concurrent Programming with I/O Multiplexing（使用  I/O  复用进行并发编程）（1014）
					1. A Concurrent Event-Driven Server Based on I/O Multiplexing（基于I/O复用的并发事件驱动服务器）（1017）
					2. Pros and Cons of I/O Multiplexing（I/O  复用的优点和缺点）（1022）
				3. Concurrent Programming with Threads（线程并发编程）（1022）
					1. Thread Execution Model（线程执行模型）（1023）
					2. Posix Threads（Posix  线程）（1024）
					3. Creating Threads（创建线程）（1025）
					4. Terminating Threads（终止线程）（1025）
					5. Reaping Terminated Threads（收获终止的线程）（1026）
					6. Detaching Threads（分离线程）（1026）
					7. Initializing Threads（初始化线程）（1027）
					8. A Concurrent Server Based on Threads（基于线程的并发服务器）（1028）
				4. Shared Variables in Threaded Programs（线程程序中的共享变量）（1029）
					1. Threads Memory Model（线程内存模型）（1030）
					2. Mapping Variables to Memory（将变量映射到内存）（1031）
					3. Shared Variables（共享变量）（1032）
				5. Synchronizing Threads with Semaphores（同步线程与信号量）（1032）
					1. Progress Graphs（进度图）（1036）
					2. Semaphores（信号量）（1038）
					3. Using Semaphores for Mutual Exclusion（使用信号量进行互斥）（1039）
					4. Using Semaphores to Schedule Shared Resources（使用信号量调度共享资源）（1041）
						1. Producer-Consumer Problem（生产者‑消费者问题）（1042）
						2. Readers-Writers Problem（读者‑作者问题）（1043）
					5. Putting It Together: A Concurrent Server Based on Prethreading（综合起来：基于预线程的并发服务器）（1045）
				6. Using Threads for Parallelism（使用线程实现并行性）（1050）
					1. Characterizing the Performance of Parallel Programs（表征并行程序的性能）（1055）
				7. Other Concurrency Issues（其他并发问题）（1057）
					1. Thread Safety（线程安全）（1057）
					2. Reentrancy（可重入）（1060）
					3. Using Existing Library Functions in Threaded Programs（在线程程序中使用现有的库函数）（1061）
					4. Races（比赛）（1062）
					5. Deadlocks（死锁）（1064）
	3. Algorithms Fourth Edition（算法第四版）
		1. Fundamentals（基础知识）（15）
			1. BASIC PROGRAMMING MODEL（基本编程模型）（21）
				1. Basic structure of a Java program（Java  程序的基本结构）（23）
				2. Primitive data types and expressions（原始数据类型和表达式）（24）
					1. Expressions（表达式）（26）
					2. Type conversion（类型转换）（26）
					3. Comparisons（比较）（26）
					4. Other primitive types（其他原始类型）（26）
				3. Statements（语句）（27）
					1. Declarations（声明）（27）
					2. Assignments（作业）（27）
					3. Conditionals（条件句）（28）
					4. Loops（循环）（28）
					5. Break and continue（打破并继续）（28）
				4. Shortcut notations（快捷符号）（29）
					1. Initializing declarations（初始化声明）（29）
					2. Implicit assignments（隐式分配）（29）
					3. Single-statement blocks（单语句块）（29）
					4. For notation（用于记号）（29）
				5. Arrays（数组）（31）
					1. Creating and initializing an array（创建并初始化数组）（31）
					2. Short form（简写）（31）
					3. Using an array（使用数组）（32）
					4. Aliasing（别名）（32）
					5. Two-dimensional arrays（二维数组）（32）
				6. Static methods（静态方法）（35）
					1. Defining a static method（定义静态方法）（35）
					2. Properties of methods（方法的属性）（37）
					3. Recursion（递归）（38）
					4. Basic programming model（基本编程模型）（39）
					5. Modular programming（模块化编程）（39）
					6. Unit testing（单元测试）（39）
					7. External libraries（外部库）（40）
				7. APIs（41）
					1. Example（例子）（41）
					2. Java libraries（Java  库）（42）
					3. Our standard libraries（我们的标准库）（43）
					4. Your own libraries（您自己的图书馆）（44）
				8. Strings（字符串）（47）
					1. Concatenation（级联）（47）
					2. Conversion（转换）（47）
					3. Automatic conversion（自动转换）（48）
					4. Command-line arguments（命令行参数）（48）
				9. Input and output（输入和输出）（49）
					1. Commands and arguments（命令和参数）（49）
					2. Standard output（标准输出）（50）
					3. Formatted output（格式化输出）（50）
					4. Standard input（标准输入）（52）
					5. Redirection and piping（重定向和管道）（53）
					6. Input and output from a file（文件的输入和输出）（54）
					7. Standard drawing (basic methods)（标准绘图（基本方法））（55）
					8. Standard drawing (control methods)（标准绘图（控制方法））（56）
				10. Binary search（二分搜索）（59）
					1. Binary search（二分查找）（59）
					2. Development client（开发客户端）（59）
					3. Whitelisting（白名单）（61）
					4. Performance（表现）（61）
				11. Perspective（观点）（63）
			2. DATA ABSTRACTION（数据抽象）（77）
				1. Using abstract data types（使用抽象数据类型）（78）
					1. API for an abstract data type（抽象数据类型的  API）（78）
					2. Inherited methods（继承的方法）（79）
					3. Client code（客户端代码）（79）
					4. Objects（对象）（80）
					5. Creating objects（创建对象）（80）
					6. Invoking instance method（调用实例方法）（81）
					7. Using objects（使用对象）（82）
					8. Assignment statements（赋值语句）（82）
					9. Objects as arguments（对象作为参数）（84）
					10. Objects as return values（对象作为返回值）（84）
					11. Arrays are objects（数组是对象）（85）
					12. Arrays of objects（对象数组）（85）
				2. Examples of abstract data types（抽象数据类型示例）（87）
					1. Geometric objects（几何对象）（89）
					2. Information processing（信息处理）（91）
					3. Strings（字符串）（93）
					4. Input and output revisited（重新审视输入和输出）（95）
				3. Implementing an abstract data type（实现抽象数据类型）（97）
					1. Instance variables（实例变量）（97）
					2. Constructors（构造函数）（97）
					3. Instance methods（实例方法）（99）
					4. Scope（范围）（100）
					5. API, clients, and implementations（API、客户端和实现）（101）
				4. More ADT implementations（更多  ADT  实现）（103）
					1. Date（日期）（103）
					2. Maintaining multiple implementations（维护多个实施）（103）
					3. Accumulator（累加器）（105）
					4. Visual accumulator（视觉累加器）（107）
				5. Data-type design（数据类型设计）（109）
					1. Encapsulation（封装）（109）
					2. Designing APIs（设计  API）（110）
					3. Algorithms and abstract data types（算法和抽象数据类型）（111）
					4. Interface inheritance（接口继承）（113）
					5. Implementation inheritance（实现继承）（114）
					6. String conversion（字符串转换）（115）
					7. Wrapper types（包装类型）（115）
					8. Equality（平等）（115）
					9. Memory management（内存管理）（117）
					10. Immutability（不变性）（118）
					11. Design by contract（按合同设计）（120）
					12. Exceptions and errors（异常和错误）（120）
					13. Assertions（断言）（120）
					14. Summary（概括）（121）
			3. BAGS, QUEUES, AND STACKS（包、队列和栈）（133）
				1. APIs（134）
					1. Generics（泛型）（135）
					2. Autoboxing（自动装箱）（135）
					3. Iterable collections（可迭代的集合）（136）
					4. Bags（包）（137）
					5. FIFO queues（先进先出队列）（139）
					6. Pushdown stacks（下推堆栈）（140）
					7. Arithmetic expression evaluation（算术表达式求值）（141）
				2. Implementing collections（实现集合）（145）
					1. Fixed-capacity stack（固定容量堆栈）（145）
					2. Generics（泛型）（147）
					3. Array resizing（数组大小调整）（149）
					4. Loitering（闲逛）（150）
					5. Iteration（迭代）（151）
				3. Linked lists（链接列表）（155）
					1. Node record（节点记录）（155）
					2. Building a linked list（建立一个链接列表）（156）
					3. Insert at the beginning（插入到开头）（157）
					4. Remove from the beginning（从头开始删除）（158）
					5. Insert at the end（插入到最后）（158）
					6. Insert/remove at other positions（在其他位置插入/删除）（158）
					7. Traversal（遍历）（159）
					8. Stack implementation（堆栈实现）（160）
					9. Queue implementation（队列实现）（163）
					10. Bag implementation（袋实施）（167）
				4. Overview（概述）（169）
					1. Data structures（数据结构）（169）
			4. ANALYSIS OF ALGORITHMS（算法分析）（185）
				1. Scientific method（科学方法）（185）
				2. Observations（观察）（186）
					1. Example（例子）（186）
					2. Stopwatch（跑表）（187）
					3. Analysis of experimental data（实验数据分析）（189）
				3. Mathematical models（数学模型）（191）
					1. Tilde approximations（波形符近似值）（191）
					2. Approximate running time（大约运行时间）（193）
					3. Order-of-growth hypothesis（增长顺序假设）（193）
					4. Analysis of algorithms（算法分析）（195）
					5. Cost model（成本模型）（195）
					6. Summary（概括）（197）
				4. Order-of-growth classifications（增长顺序分类）（199）
					1. Constant（持续的）（199）
					2. Logarithmic（对数）（199）
					3. Linear（线性）（199）
					4. Linearithmic（线性算术）（199）
					5. Quadratic（二次方）（199）
					6. Cubic（立方体）（199）
					7. Exponential（指数）（199）
				5. Designing faster algorithms（设计更快的算法）（202）
					1. Warmup: 2-sum（热身：2  总和）（202）
					2. Fast algorithm for 3-sum（3‑sum  的快速算法）（203）
					3. Lower bounds（下限）（203）
				6. Doubling ratio experiments（倍增率实验）（205）
					1. Estimating the feasibility of solving large problems（估计解决大问题的可行性）（206）
					2. Estimating the value of using a faster computer（估计使用更快的计算机的价值）（207）
				7. Caveats（注意事项）（208）
					1. Large constants（大常数）（208）
					2. Nondominant inner loop（非主导内循环）（208）
					3. Instruction time（指导时间）（208）
					4. System considerations（系统考虑）（208）
					5. Too close to call（距离太近，无法通话）（208）
					6. Strong dependence on inputs（对投入的依赖性强）（209）
					7. Multiple problem parameters（多个问题参数）（209）
				8. Coping with dependence on inputs（应对对输入的依赖）（210）
					1. Input models（输入模型）（210）
					2. Worst-case performance guarantees（最坏情况下的性能保证）（210）
					3. Randomized algorithms（随机算法）（211）
					4. Sequences of operations（操作顺序）（211）
					5. Amortized analysis（摊销分析）（211）
				9. Memory（内存）（213）
					1. Objects（对象）（214）
					2. Linked lists（链接列表）（214）
					3. Arrays（数组）（215）
					4. String objects（字符串对象）（215）
					5. String values and substrings（字符串值和子字符串）（215）
				10. Perspective（观点）（218）
			5. CASE STUDY: UNION-FIND（案例研究：UNION‑FIND）（229）
				1. Dynamic connectivity（动态连接）（229）
					1. Networks（网络）（230）
					2. Variable-name equivalence（变量名等效）（230）
					3. Mathematical sets（数学集）（230）
				2. Implementations（实现）（235）
					1. Quick-find（快速查找）（235）
					2. Quick-find analysis（快速查找分析）（236）
					3. Quick-union（快速联合）（237）
					4. Forest-of-trees representation（树森林表示）（238）
					5. Quick-union analysis（快速联合分析）（239）
					6. Weighted quick-union（加权快速接头）（240）
					7. Weighted quick-union analysis（加权快速联合分析）（240）
					8. Optimal algorithms（最优算法）（244）
					9. Amortized cost plots（摊余成本图）（245）
				3. Perspective（观点）（246）
		2. Sorting（排序）（255）
			1. ELEMENTARY SORTS（基本排序）（257）
				1. Rules of the game（游戏规则）（257）
					1. Certification（认证）（259）
					2. Running time（运行时间）（259）
					3. Extra memory（额外的内存）（259）
					4. Types of data（数据类型）（259）
				2. Selection sort（选择排序）（261）
					1. Running time is insensitive to input（运行时间对输入不敏感）（261）
					2. Data movement is minimal（数据移动最少）（261）
				3. Insertion sort（插入排序）（263）
				4. Visualizing sorting algorithms（可视化排序算法）（266）
				5. Comparing two sorting algorithms（比较两种排序算法）（267）
				6. Shellsort（希尔排序）（271）
			2. MERGESORT（归并排序）（283）
				1. Abstract in-place merge（抽象就地合并）（283）
				2. Top-down mergesort（自顶向下合并排序）（285）
					1. Use insertion sort for small subarrays（对于小子数组使用插入排序）（288）
					2. Test whether the array is already in order（测试数组是否已经有序）（288）
					3. Eliminate the copy to the auxiliary array（消除对辅助数组的复制）（288）
				3. Bottom-up mergesort（自下而上的归并排序）（290）
				4. The complexity of sorting（排序的复杂性）（292）
			3. QUICKSORT（快速排序）（301）
				1. The basic algorithm（基本算法）（301）
					1. Partitioning in place（分区到位）（305）
					2. Staying in bounds（保持在界限内）（305）
					3. Preserving randomness（保持随机性）（305）
					4. Terminating the loop（终止循环）（305）
					5. Handling items with keys equal to the partitioning item’s key（处理键与分区项的键相同的项）（305）
					6. Terminating the recursion（终止递归）（305）
				2. Performance characteristics（性能特征）（306）
				3. Algorithmic improvements（算法改进）（308）
					1. Cutoff to insertion sort（插入排序的截止）（309）
					2. Median-of-three partitioning（三中位数划分）（309）
					3. Entropy-optimal sorting（309）
			4. PRIORITY QUEUES（优先级队列）（321）
				1. API（322）
					1. A priority-queue client（优先队列客户端）（323）
				2. Elementary implementations（基本实现）（323）
					1. Array representation (unordered)（数组表示（无序））（323）
					2. Array representation (ordered)（数组表示（有序））（325）
					3. Linked-list representations（链表表示）（325）
				3. Heap definitions（堆定义）（326）
					1. Binary heap representation（二进制堆表示）（326）
				4. Algorithms on heaps（堆上的算法）（328）
					1. Bottom-up reheapify （swim)（自下而上重新堆放（游泳））（328）
					2. Top-down reheapify (sink)（自上而下重新堆放（下沉））（329）
						1. Insert（插入）（330）
						2. Remove the maximum（去掉最大值）（330）
					3. Multiway heaps（多路堆）（332）
					4. Array resizing（数组大小调整）（333）
					5. Immutability of keys（键的不变性）（333）
					6. Index priority queue（索引优先队列）（333）
					7. Index priority-queue client（索引优先级队列客户端）（334）
				5. Heapsort（堆排序）（336）
					1. Heap construction（堆构建）（336）
					2. Sortdown（排序）（339）
					3. Sink to the bottom, then swim（沉到水底，然后游泳）（340）
			5. APPLICATIONS（应用）（349）
				1. Sorting various types of data（对各种类型的数据进行排序）（350）
					1. Transaction example（交易示例）（350）
					2. Pointer sorting（指针排序）（351）
					3. Keys are immutable（密钥是不可变的）（351）
					4. Exchanges are inexpensive（交换很便宜）（351）
					5. Alternate orderings（替代订单）（351）
					6. Items with multiple keys（具有多个键的项目）（352）
					7. Priority queues with comparators（带比较器的优先级队列）（353）
					8. Stability（稳定）（354）
				2. Which sorting algorithm should I use?（我应该使用哪种排序算法？）（355）
					1. Sorting primitive types（对原始类型进行排序）（356）
					2. Java system sort（Java系统排序）（356）
				3. Reductions（归约）（357）
					1. Duplicates（重复）（357）
					2. Rankings（排名）（358）
					3. Priority-queue reductions（优先级队列减少）（358）
					4. Median and order statistics（中位数和顺序统计）（358）
				4. A brief survey of sorting applications（排序应用程序的简要概述）（361）
					1. Commercial computing（商业计算）（361）
					2. Search for information（搜索信息）（361）
					3. Operations research（行动调查）（362）
					4. Event-driven simulation（事件驱动的模拟）（362）
					5. Numerical computations（数值计算）（362）
					6. Combinatorial search（组合搜索）（363）
					7. Prim’s algorithm and Dijkstra’s algorithm（Prim  算法和  Dijkstra  算法）（363）
					8. Kruskal’s algorithm（克鲁斯卡尔算法）（363）
					9. Huffman compression（霍夫曼压缩）（363）
					10. String-processing（字符串处理）（364）
		3. Searching（搜寻中）（373）
			1. SYMBOL TABLES（符号表）（374）
				1. API（376）
					1. Generics（泛型）（376）
					2. Duplicate keys（重复的钥匙）（376）
					3. Null keys（空键）（377）
					4. Null values（空值）（377）
					5. Deletion（删除）（377）
					6. Shorthand methods（速记方法）（377）
					7. Iteration（迭代）（378）
					8. Key equality（关键平等）（378）
				2. Ordered symbol tables（有序符号表）（379）
					1. Minimum and maximum（最小值和最大值）（380）
					2. Floor and ceiling（地板和天花板）（380）
					3. Rank and selection（排名和选择）（380）
					4. Range queries（范围查询）（381）
					5. Exceptional cases（特殊情况）（381）
					6. Shorthand methods（速记方法）（381）
					7. Key equality (revisited)（关键平等（重新审视））（381）
					8. Cost model（成本模型）（382）
				3. Sample clients（示例客户端）（383）
					1. Test client（测试客户端）（383）
					2. Performance client（性能客户端）（384）
				4. Sequential search in an unordered linked list（无序链表中的顺序搜索）（387）
				5. Binary search in an ordered array（有序数组中的二分搜索）（391）
					1. Binary search（二分查找）（393）
					2. Other operations（其他操作）（393）
				6. Analysis of binary search（二分搜索的分析）（396）
				7. Preview（预览）（398）
			2. BINARY SEARCH TREES（二叉搜索树）（409）
				1. Basic implementation（基本实现）（410）
					1. Representation（表示）（410）
					2. Search（搜索）（410）
					3. Insert（插入）（413）
					4. Recursion（递归）（414）
				2. Analysis（分析）（416）
					1. Experiments（实验）（417）
				3. Order-based methods and deletion（基于顺序的方法和删除）（419）
					1. Minimum and maximum（最小值和最大值）（419）
					2. Floor and ceiling（地板和天花板）（419）
					3. Selection（选择）（419）
					4. Rank（排名）（421）
					5. Delete the minimum/maximum（删除最小值/最大值）（421）
					6. Delete（删除）（423）
					7. Range queries（范围查询）（425）
					8. Analysis（分析）（425）
			3. BALANCED SEARCH TREES（平衡搜索树）（437）
				1. 2-3 search trees（2‑3  搜索树）（437）
					1. Search（搜索）（438）
					2. Insert into a 2-node（插入  2  节点）（438）
					3. Insert into a tree consisting of a single 3-node（插入由单个  3  节点组成的树中）（439）
					4. Insert into a 3-node whose parent is a 2-node（插入到父节点是  2  节点的  3  节点中）（439）
					5. Insert into a 3-node whose parent is a 3-node（插入到父节点是  3  节点的  3  节点中）（440）
					6. Splitting the root（分裂根部）（440）
					7. Local transformations（局部改造）（440）
					8. Global properties（全球属性）（441）
				2. Red-black BSTs（红黑BSTs）（445）
					1. Encoding 3-nodes（编码  3  节点）（445）
					2. An equivalent definition（等效定义）（445）
					3. A 1-1 correspondence（1-1对应）（445）
					4. Color representation（颜色表示）（446）
					5. Rotations（旋转）（446）
					6. Resetting the link in the parent after a rotation（旋转后重置父级中的链接）（447）
					7. Insert into a single 2-node（插入单个  2  节点）（448）
					8. Insert into a 2-node at the bottom（插入底部的  2  节点）（448）
					9. Insert into a tree with two keys (in a 3-node)（插入到具有两个键的树中（在  3  节点中））（448）
					10. Flipping colors（翻转颜色）（449）
					11. Keeping the root black（保持根部黑色）（450）
					12. Insert into a 3-node at the bottom（插入底部的  3  节点）（450）
					13. Passing a red link up the tree（将红色链接传递到树上）（450）
				3. Implementation（实现）（451）
				4. Deletion（删除）（454）
					1. Top-down 2-3-4 trees（自上而下的  2‑3‑4  树）（454）
					2. Delete the minimum（删除最小值）（455）
					3. Delete（删除）（456）
				5. Properties of red-black BSTs（红黑  BST  的性质）（457）
					1. Analysis（分析）（457）
					2. Ordered symbol-table API（有序符号表  API）（459）
			4. HASH TABLES（哈希表）（471）
				1. Hash functions（哈希函数）（472）
					1. Typical example（典型例子）（472）
					2. Positive integers（正整数）（472）
					3. Floating-point numbers（浮点数字）（473）
					4. Strings（字符串）（473）
					5. Compound keys（复合键）（473）
					6. Java conventions（Java  约定）（474）
					7. Converting a hashCode() to an array index（将 hashCode() 转换为数组索引）（474）
					8. User-defined hashCode()（用户定义的hashCode()）（474）
					9. Software caching（软件缓存）（475）
				2. Hashing with separate chaining（使用单独链接进行散列）（477）
					1. Table size（表尺寸）（480）
					2. Deletion（删除）（481）
					3. Ordered operations（有序操作）（481）
				3. Hashing with linear probing（使用线性探测）（482）
					1. Deletion（删除）（484）
					2. Clustering（聚类）（485）
					3. Analysis of linear probing（线性探测分析）（486）
				4. Array resizing（数组调整大小）（487）
					1. Separate chaining（单独链接）（487）
					2. Amortized analysis（摊销分析）（488）
				5. Memory（内存）（489）
			5. APPLICATIONS（应用）（499）
				1. Which symbol-table implementation should I use?（我应该使用哪种符号表实现？）（500）
					1. Primitive types（原始类型）（501）
					2. Duplicate keys（重复的钥匙）（501）
					3. Java libraries（Java  库）（502）
				2. Set APIs（设置  API）（502）
					1. Dedup（重复数据删除）（503）
					2. Whitelist and blacklist（白名单和黑名单）（504）
				3. Dictionary clients（字典客户端）（505）
				4. Indexing clients（索引客户端）（509）
					1. Inverted index（倒排索引）（511）
				5. Sparse vectors（稀疏向量）（515）
		4. Graphs（图表）（527）
			1. UNDIRECTED GRAPHS（无向图）（531）
				1. Glossary（术语表）（532）
				2. Undirected graph data type（无向图数据类型）（535）
					1. Representation alternatives（代表替代方案）（537）
					2. Adjacency-lists data structure（邻接表数据结构）（538）
					3. Design pattern for graph processing（图形处理的设计模式）（541）
				3. Depth-first search（深度优先搜索）（543）
					1. Searching in a maze（在迷宫中寻找）（543）
					2. Warmup（暖身）（544）
					3. One-way passages（单向通道）（545）
					4. Tracing DFS（追踪DFS）（545）
					5. Detailed trace of depth-first search（深度优先搜索的详细跟踪）（546）
				4. Finding paths（寻找路径）（548）
					1. Implementation（执行）（548）
					2. Detailed trace（详细踪迹）（550）
				5. Breadth-first search（广度优先搜索）（551）
					1. Implementation（执行）（551）
				6. Connected components（连接组件）（556）
					1. Implementation（执行）（556）
					2. Union-find（联合查找）（559）
				7. Symbol graphs（符号图）（561）
					1. API（561）
					2. Test client（测试客户端）（563）
					3. Implementation（执行）（564）
					4. Degrees of separation（分离程度）（566）
				8. Summary（总结）（569）
			2. DIRECTED GRAPHS（有向图）（579）
				1. Glossary（术语表）（579）
				2. Digraph data type（有向图数据类型）（581）
					1. Representation（表示）（581）
					2. Input format（输入格式）（581）
					3. Reversing a digraph（反转有向图）（581）
					4. Symbolic names（象征性的名字）（581）
				3. Reachability in digraphs（有向图中的可达性）（583）
					1. Mark-and-sweep garbage collection（标记和清除垃圾收集）（586）
					2. Finding paths in digraphs（在有向图中查找路径）（586）
				4. Cycles and DAGs（循环和  DAG）（587）
					1. Scheduling problems（调度问题）（587）
					2. Cycles in digraphs（有向图中的循环）（589）
					3. Depth-first orders and topological sort（深度优先顺序和拓扑排序）（591）
				5. Strong connectivity in digraphs（有向图中的强连通性）（597）
					1. Strong components（强大的组件）（597）
					2. Examples of applications（应用示例）（598）
					3. Kosaraju’s algorithm（Kosaraju  算法）（599）
					4. Reachability revisited（重新审视可达性）（603）
				6. Summary（小结）（607）
			3. MINIMUM SPANNING TREES（最小生成树）（617）
				1. Underlying principles（基本原则）（619）
					1. Cut property（削减财产）（619）
					2. Greedy algorithm（贪心算法）（620）
				2. Edge-weighted graph data type（边加权图数据类型）（621）
					1. Comparing edges by weight（按重量比较边缘）（625）
					2. Parallel edges（平行边缘）（625）
					3. Self-loops（自循环）（625）
				3. MST API and test client（MST  API  和测试客户端）（626）
					1. Test client（测试客户端）（626）
					2. Test data（测试数据）（627）
				4. Prim’s algorithm（Prim  算法）（629）
					1. Data structures（数据结构）（629）
					2. Maintaining the set of crossing edges（维护交叉边集）（629）
					3. Implementation（执行）（631）
					4. Running time（运行时间）（631）
				5. Eager version of Prim’s algorithm（Prim算法的Eager版本）（633）
				6. Kruskal’s algorithm（Kruskal  算法）（637）
				7. Perspective（观点）（641）
					1. Historical notes（历史笔记）（641）
					2. A linear-time algorithm?（线性时间算法？）（642）
			4. SHORTEST PATHS（最短路径）（651）
				1. Properties of shortest paths（最短路径的属性）（652）
					1. Shortest-paths tree（最短路径树）（653）
				2. Edge-weighted digraph data types（边加权有向图数据类型）（654）
					1. Shortest-paths API（最短路径  API）（657）
					2. Test client（测试客户端）（658）
					3. Data structures for shortest paths（最短路径的数据结构）（659）
					4. Edge relaxation（边缘松弛）（659）
					5. Vertex relaxation（顶点松弛）（661）
					6. Client query methods（客户端查询方法）（662）
				3. Theoretical basis for shortest-paths algorithms（最短路径算法的理论基础）（663）
					1. Optimality conditions（最优条件）（663）
					2. Certification（认证）（664）
					3. Generic algorithm（通用算法）（664）
				4. Dijkstra’s algorithm（Dijkstra  算法）（665）
					1. Data structures（数据结构）（665）
					2. Alternative viewpoint（另类观点）（665）
					3. Variants（变体）（667）
				5. Acyclic edge-weighted digraphs（非循环边加权有向图）（671）
					1. Longest paths（最长的路径）（674）
					2. Parallel job scheduling（并行作业调度）（676）
					3. Parallel job scheduling with relative deadlines（具有相对期限的并行作业调度）（679）
				6. Shortest paths in general edge-weighted digraphs（一般边加权有向图中的最短路径）（681）
					1. Strawman I（681）
					2. Strawman II（681）
					3. Negative cycles（负循环）（681）
					4. Strawman III（683）
					5. Queue-based Bellman-Ford（基于队列的  Bellman‑Ford）（685）
					6. Implementation（执行）（685）
					7. Negative weights（负权重）（688）
					8. Negative cycle detection（负循环检测）（690）
					9. Arbitrage（套利）（692）
				7. Perspective（观点）（695）
					1. Historical notes（历史笔记）（695）
		5. Strings（字符串）
			1. STRING SORTS（字符串排序）（715）
				1. Key-indexed counting（键索引计数）（716）
					1. Compute frequency counts（计算频率计数）（716）
					2. Transform counts to indices（将计数转换为索引）（717）
					3. Distribute the data（分发数据）（717）
					4. Copy back（抄回来）（718）
				2. LSD string sort（LSD  字符串排序）（719）
				3. MSD string sort（MSD  字符串排序）（723）
					1. End-of-string convention（字符串结尾约定）（723）
					2. Specified alphabet（指定字母表）（724）
					3. Small subarrays（小子数组）（726）
					4. Equal keys（相等的键）（728）
					5. Extra space（额外的空间）（729）
					6. Random string model（随机串模型）（729）
					7. Performance（表现）（729）
				4. Three-way string quicksort（三路字符串快速排序）（732）
					1. Small subarrays（小子数组）（734）
					2. Restricted alphabet（受限制的字母表）（734）
					3. Randomization（随机化）（735）
					4. Performance（表现）（735）
					5. Example: web logs（示例：网络日志）（736）
				5. Which string-sorting algorithm should I use?（我应该使用哪种字符串排序算法？）（737）
			2. TRIES（尝试）（743）
				1. Tries（尝试）（745）
					1. Basic properties（基本属性）（745）
					2. Search in a trie（在字典树中搜索）（745）
					3. Insertion into a trie（插入到特里树中）（747）
					4. Node representation（节点表示）（747）
					5. Size（尺寸）（749）
					6. Collecting keys（收集钥匙）（751）
					7. Wildcard match（通配符匹配）（752）
					8. Longest prefix（最长的前缀）（752）
					9. Deletion（删除）（753）
					10. Alphabet（字母）（754）
				2. Properties of tries（尝试的属性）（755）
					1. Worst-case time bound for search and insert（搜索和插入的最坏情况时间限制）（755）
					2. Expected time bound for search miss（搜索失败的预期时间范围）（756）
					3. Space（空间）（757）
					4. One-way branching（单向分支）（757）
				3. Ternary search tries (TSTs)（三元搜索尝试  (TST)）（759）
					1. Search and insert（搜索并插入）（759）
				4. Properties of TSTs（TST  的属性）（762）
					1. Space（空间）（762）
					2. Search cost（搜寻成本）（762）
					3. Alphabet（字母）（763）
					4. Prefix match, collecting keys, and wildcard match（前缀匹配、收集键和通配符匹配）（763）
					5. Deletion（删除）（763）
					6. Hybrid TSTs（混合  TST）（763）
					7. One-way branching（单向分支）（764）
				5. Which string symbol-table implementation should I use?（我应该使用哪种字符串符号表实现？）（765）
			3. SUBSTRING SEARCH（子串搜索）（771）
				1. A short history（简史）（772）
				2. Brute-force substring search（暴力子字符串搜索）（773）
				3. Knuth-Morris-Pratt substring search（Knuth‑Morris‑Pratt  子串搜索）（775）
					1. Backing up the pattern pointer（备份模式指针）（776）
					2. KMP search method（KMP搜索方法）（776）
					3. DFA simulation（DFA  模拟）（777）
					4. Constructing the DFA（构建  DFA）（778）
				4. Boyer-Moore substring search（Boyer‑Moore  子字符串搜索）（783）
					1. Mismatched character heuristic（不匹配的字符启发式）（783）
					2. Starting point（初始点）（784）
					3. Substring search（子串搜索）（784）
				5. Rabin-Karp fingerprint search（Rabin‑Karp  指纹搜索）（787）
					1. Basic plan（基本计划）（787）
					2. Computing the hash function（计算哈希函数）（787）
					3. Key idea（关键想法）（788）
					4. Implementation（执行）（789）
					5. A trick: Monte Carlo correctness（技巧：蒙特卡罗正确性）（789）
				6. Summary（摘要）（792）
			4. REGULAR EXPRESSIONS（正则表达式）（801）
				1. Describing patterns with regular expressions（用正则表达式描述模式）（802）
					1. Concatenation（级联）（802）
					2. Or（或者）（802）
					3. Closure（关闭）（802）
					4. Parentheses（括号）（802）
				2. Shortcuts（快捷方式）（804）
					1. Set-of-characters descriptors（字符集描述符）（804）
					2. Closure shortcuts（关闭快捷方式）（804）
					3. Escape sequences（转义序列）（804）
				3. REs in applications（应用中的  RE）（805）
					1. Substring search（子串搜索）（805）
					2. Validity checking（有效性检查）（805）
					3. Programmer’s toolbox（程序员的工具箱）（806）
					4. Genomics（基因组学）（806）
					5. Search（搜索）（806）
					6. Possibilities（可能性）（806）
					7. Limitations（局限性）（806）
				4. Nondeterministic finite-state automata（非确定性有限状态自动机）（807）
				5. Simulating an NFA（模拟  NFA）（810）
					1. Representation（表示）（810）
					2. NFA simulation and reachability（NFA  模拟和可达性）（810）
				6. Building an NFA corresponding to an RE（构建与  RE  相对应的  NFA）（813）
					1. Concatenation（级联）（813）
					2. Parentheses（括号）（813）
					3. Closure（闭包）（813）
					4. Or expression（或者表达）（813）
			5. DATA COMPRESSION（数据压缩）（823）
				1. Rules of the game（游戏规则）（824）
					1. Basic model（基本模型）（824）
				2. Reading and writing binary data（读取和写入二进制数据）（824）
					1. Binary input and output（二进制输入和输出）（825）
					2. Example（例子）（826）
					3. Binary dumps（二进制转储）（826）
					4. ASCII encoding（ASCII  编码）（828）
				3. Limitations（限制）（829）
					1. Universal data compression（通用数据压缩）（829）
					2. Undecidability（不确定性）（830）
				4. Warmup: genomics（热身：基因组学）（832）
					1. Genomic data（基因组数据）（832）
					2. 2-bit code compression（2  位代码压缩）（832）
					3. 2-bit code expansion（2  位代码扩展）（832）
				5. Run-length encoding（游程编码）（835）
					1. Bitmaps（位图）（835）
					2. Implementation（执行）（836）
					3. Increasing resolution in bitmaps（提高位图的分辨率）（836）
				6. Huffman compression（霍夫曼压缩）（839）
					1. Variable-length prefix-free codes（可变长度无前缀代码）（839）
					2. Trie representation for prefix-free codes（无前缀代码的  Trie  表示）（840）
					3. Overview（概述）（840）
					4. Trie nodes（特里树节点）（841）
					5. Expansion for prefix-free codes（无前缀代码的扩展）（841）
					6. Compression for prefix-free codes（无前缀代码的压缩）（842）
					7. Trie construction（特里构造）（843）
					8. Optimality（最优性）（845）
					9. Writing and reading the trie（写入和读取  trie）（847）
					10. Huffman compression implementation（霍夫曼压缩实现）（848）
					11. LZW compression（LZW  压缩（852））
					12. LZW compression example（LZW  压缩示例）（853）
					13. LZW trie representation（LZW  trie  表示）（853）
					14. LZW expansion（LZW  扩展）（854）
					15. Tricky situation（情况很棘手）（856）
					16. Implementation（执行）（856）
	4. Computer Architecture（计算机体系结构）
		1. Fundamentals of Quantitative Design and Analysis（定量设计和分析基础知识）（33）
			1. Introduction（介绍）（34）
			2. Classes of Computers（计算机类别）（38）
				1. Internet of Things/Embedded Computers（物联网/嵌入式计算机）（38）
				2. Personal Mobile Device（个人移动设备）（39）
				3. Desktop Computing（桌面计算）（40）
				4. Servers（服务器）（40）
				5. Clusters/Warehouse-Scale Computers（集群/仓库规模计算机）（41）
				6. Classes of Parallelism and Parallel Architectures（并行性和并行架构的类别）（42）
			3. Defining Computer Architecture（定义计算机体系结构）（44）
				1. Instruction Set Architecture: The Myopic View of Computer Architecture（指令集架构：计算机架构的短视观点）（44）
				2. Genuine Computer Architecture: Designing the Organization and Hardware to Meet Goals and Functional Requirements（真正的计算机体系结构：设计组织和硬件以满足目标和功能要求）（49）
			4. Trends in Technology（技术趋势）（50）
				1. Performance Trends: Bandwidth Over Latency（性能趋势：带宽与延迟的关系）（52）
				2. Scaling of Transistor Performance and Wires（晶体管性能和电线的扩展）（53）
			5. Trends in Power and Energy in Integrated Circuits（集成电路功率和能量的趋势）（55）
				1. Power and Energy: A Systems Perspective（电力和能源：系统视角）（55）
				2. Energy and Power Within a Microprocessor（微处理器内的能量和功率）（57）
				3. The Shift in Computer Architecture Because of Limits of Energy（由于能源限制而导致的计算机架构的转变）（60）
			6. Trends in Cost（成本趋势）（61）
				1. The Impact of Time, Volume, and Commoditization（时间、数量和商品化的影响）（62）
				2. Cost of an Integrated Circuit（集成电路的成本）（63）
				3. Cost Versus Price（成本与价格）（67）
				4. Cost of Manufacturing Versus Cost of Operation（制造成本与运营成本）（68）
			7. Dependability（可靠性）（68）
			8. Measuring, Reporting, and Summarizing Performance（衡量、报告和总结绩效）（71）
				1. Benchmarks（基准测试）（72）
					1. Desktop Benchmarks（桌面基准测试）（73）
					2. Server Benchmarks（服务器基准测试）（78）
				2. Reporting Performance Results（报告绩效结果）（77）
				3. Summarizing Performance Results（总结绩效结果）（77）
			9. Quantitative Principles of Computer Design（计算机设计的定量原理）（80）
				1. Take Advantage of Parallelism（利用并行性）（80）
				2. Principle of Locality（局部性原理）（80）
				3. Focus on the Common Case（关注常见案例）（81）
				4. Amdahl’s Law（阿姆达尔定律）（81）
				5. The Processor Performance Equation（处理器性能方程）（84）
			10. Putting It All Together: Performance, Price, and Power（合起来：性能、价格和功耗）（87）
			11. Fallacies and Pitfalls（谬误和陷阱）（90）
			12. Concluding Remarks（结束语）（96）
			13. Historical Perspectives and References（历史观点和参考）（99）
			14. Case Studies and Exercises by Diana Franklin（戴安娜·富兰克林的案例研究和练习）（99）
				1. Case Study 1: Chip Fabrication Cost（案例研究  1：芯片制造成本）（99）
				2. Case Study 2: Power Consumption in Computer Systems（案例研究  2：计算机系统的功耗）（101）
		2. Memory Hierarchy Design（内存层次结构设计）（109）
			1. Introduction（介绍）（110）
				1. Basics of Memory Hierarchies: A Quick Review（内存层次结构基础知识：快速回顾）（113）
			2. Memory Technology and Optimizations（内存技术及优化）（116）
				1. SRAM Technology（静态随机存储器技术）（117）
				2. DRAM Technology（内存技术）（117）
				3. Improving Memory Performance Inside a DRAM Chip: SDRAMs（提高 DRAM 芯片内部的内存性能：SDRAM）（119）
					1. Reducing Power Consumption in SDRAMs（降低  SDRAM  的功耗）（121）
				4. Graphics Data RAMs（图形数据  RAM）（122）
				5. Packaging Innovation: Stacked or Embedded DRAMs（封装创新：堆叠式或嵌入式  DRAM）（123）
				6. Flash Memory（闪存）（124）
				7. Phase-Change Memory Technology（相变内存技术）（125）
				8. Enhancing Dependability in Memory Systems（增强内存系统的可靠性）（125）
			3. Ten Advanced Optimizations of Cache Performance（缓存性能的十大高级优化）（126）
				1. First Optimization: Small and Simple First-Level Caches to Reduce Hit Time and Power（首次优化：小型且简单的一级缓存可减少命中时间和功耗）（127）
				2. Second Optimization: Way Prediction to Reduce Hit Time（第二次优化：减少命中时间的方式预测）（130）
				3. Third Optimization: Pipelined Access and Multibanked Caches to Increase Bandwidth（第三次优化：流水线访问和多组缓存以增加带宽）（131）
				4. Fourth Optimization: Nonblocking Caches to Increase Cache Bandwidth（优化四：非阻塞缓存，提高缓存带宽）（132）
					1. Implementing a Nonblocking Cache（实现非阻塞缓存）（135）
				5. Fifth Optimization: Critical Word First and Early Restart to Reduce Miss Penalty（优化五：关键词优先，提前重启，减少漏判）（136）
				6. Sixth Optimization: Merging Write Buffer to Reduce Miss Penalty（优化六：合并写入缓冲区，减少Miss Penalty）（137）
				7. Seventh Optimization: Compiler Optimizations to Reduce Miss Rate（优化七：编译器优化，降低miss率）（139）
					1. Loop Interchange（环路交汇处）（139）
					2. Blocking（阻塞）（139）
				8. Eighth Optimization: Hardware Prefetching of Instructions and Data to Reduce Miss Penalty or Miss Rate（优化八：指令和数据的硬件预取，减少丢失惩罚或丢失率）（141）
				9. Ninth Optimization: Compiler-Controlled Prefetching to Reduce Miss Penalty or Miss Rate（第九个优化：编译器控制的预取以减少丢失惩罚或丢失率）（143）
				10. Tenth Optimization: Using HBM to Extend the Memory Hierarchy（优化十：利用HBM扩展内存层次）（146）
				11. Cache Optimization Summary（缓存优化总结）（149）
			4. Virtual Memory and Virtual Machines（虚拟内存和虚拟机）（150）
				1. Protection via Virtual Memory（通过虚拟内存进行保护）（151）
				2. Protection via Virtual Machines（通过虚拟机进行保护）（152）
				3. Requirements of a Virtual Machine Monitor（虚拟机监视器的要求）（154）
				4. Instruction Set Architecture Support for Virtual Machines（虚拟机指令集架构支持）（154）
				5. Impact of Virtual Machines on Virtual Memory and I/O（虚拟机对虚拟内存和  I/O  的影响）（155）
				6. Extending the Instruction Set for Efficient Virtualization and Better Security（扩展指令集以实现高效虚拟化和更好的安全性）（156）
				7. An Example VMM: The Xen Virtual Machine（VMM  示例：Xen  虚拟机）（158）
			5. Cross-Cutting Issues: The Design of Memory Hierarchies（交叉问题：内存层次结构的设计）（158）
				1. Protection, Virtualization, and Instruction Set Architecture（保护、虚拟化和指令集架构）（158）
				2. Autonomous Instruction Fetch Units（自主取指令单元）（159）
				3. Speculation and Memory Access（推测和内存访问）（159）
				4. Special Instruction Caches（特殊指令缓存）（160）
				5. Coherency of Cached Data（缓存数据的一致性）（160）
			6. Putting It All Together: Memory Hierarchies in the ARM Cortex-A53 and Intel Core i7 6700（综合起来：ARM Cortex-A53 和 Intel Core i7 6700 中的内存层次结构）（161）
				1. The ARM Cortex-A53（161）
				2. Performance of the Cortex-A53 Memory Hierarchy（Cortex‑A53  内存层次结构的性能）（164）
				3. The Intel Core i7 6700（英特尔酷睿  i7  6700）（165）
					1. Performance of the i7 memory system（i7内存系统的性能）（170）
			7. Fallacies and Pitfalls（谬误和陷阱）（174）
			8. Concluding Remarks: Looking Ahead（结束语：展望未来）（178）
			9. Historical Perspectives and References（历史观点和参考）（180）
			10. Case Studies and Exercises by Norman P. Jouppi, Rajeev Balasubramonian, Naveen Muralimanohar, and Sheng Li（Norman P. Jouppi、Rajeev Balasubramonian、Naveen Muralimanohar 和 Shen Li 的案例研究和练习）（180）
				1. Case Study 1: Optimizing Cache Performance via Advanced Techniques（案例研究 1：通过先进技术优化缓存性能）（180）
				2. Case Study 2: Putting It All Together: Highly Parallel Memory Systems（案例研究 2：综合起来：高度并行内存系统）（182）
				3. Case Study 3: Studying the Impact of Various Memory System Organizations（案例研究 3：研究各种内存系统组织的影响）（185）
		3. Instruction-Level Parallelism and Its Exploitation（指令级并行性及其利用）（199）
			1. Instruction-Level Parallelism: Concepts and Challenges（指令级并行性：概念和挑战）（200）
				1. What Is Instruction-Level Parallelism?（什么是指令级并行性？）（201）
				2. Data Dependences and Hazards（数据依赖性和危险）（202）
					1. Data Dependences（数据依赖性）（202）
					2. Name Dependences（名称依赖）（204）
					3. Data Hazards（数据危害）（205）
				3. Control Dependences（控制依赖）（206）
			2. Basic Compiler Techniques for Exposing ILP（公开  ILP  的基本编译器技术）（208）
				1. Basic Pipeline Scheduling and Loop Unrolling（基本管道调度和循环展开）（209）
				2. Summary of the Loop Unrolling and Scheduling（循环展开和调度总结）（213）
			3. Reducing Branch Costs With Advanced Branch Prediction（通过高级分支预测降低分支成本）（214）
				1. Correlating Branch Predictors（关联分支预测器）（214）
				2. Tournament Predictors: Adaptively Combining Local and Global Predictors（锦标赛预测器：自适应地结合本地和全局预测器）（216）
				3. Tagged Hybrid Predictors（标记混合预测器）（220）
				4. The Evolution of the Intel Core i7 Branch Predictor（英特尔酷睿  i7  分支预测器的演变）（222）
			4. Overcoming Data Hazards With Dynamic Scheduling（通过动态调度克服数据危险）（223）
				1. Dynamic Scheduling: The Idea（动态调度：想法）（225）
				2. Dynamic Scheduling Using Tomasulo’s Approach（使用  Tomasulo  方法的动态调度）（227）
			5. Dynamic Scheduling: Examples and the Algorithm（动态调度：例子和算法）（233）
				1. Tomasulo’s Algorithm: The Details（Tomasulo  算法：细节）（235）
				2. Tomasulo’s Algorithm: A Loop-Based Example（Tomasulo  算法：基于循环的示例）（236）
			6. Hardware-Based Speculation（基于硬件的推测）（240）
			7. Exploiting ILP Using Multiple Issue and Static Scheduling（使用多问题和静态调度来利用  ILP）（250）
				1. The Basic VLIW Approach（基本  VLIW  方法）（250）
			8. Exploiting ILP Using Dynamic Scheduling, Multiple Issue, and Speculation（使用动态调度、多重问题和推测来利用 ILP）（254）
			9. Advanced Techniques for Instruction Delivery and Speculation（指令传递和推测的先进技术）（260）
				1. Increasing Instruction Fetch Bandwidth（增加指令获取带宽）（260）
					1. Branch-Target Buffers（分支目标缓冲区）（260）
				2. Specialized Branch Predictors: Predicting Procedure Returns, Indirect Jumps, and Loop Branches（专用分支预测器：预测过程返回、间接跳转和循环分支）（264）
					1. Integrated Instruction Fetch Units（集成指令获取单元）（265）
				3. Speculation: Implementation Issues and Extensions（推测：实施问题和扩展）（266）
					1. Speculation Support: Register Renaming Versus Reorder Buffers（推测支持：寄存器重命名与重新排序缓冲区）（266）
					2. The Challenge of More Issues per Clock（每个时钟出现更多问题的挑战）（268）
					3. How Much to Speculate（推测多少）（269）
					4. Speculating Through Multiple Branches（通过多个分支进行推测）（270）
					5. Speculation and the Challenge of Energy Efficiency（能源效率的投机与挑战）（270）
					6. Address Aliasing Prediction（地址别名预测）（271）
			10. Cross-Cutting Issues（跨领域问题）（272）
				1. Hardware Versus Software Speculation（硬件与软件推测）（272）
				2. Speculative Execution and the Memory System（推测执行和内存系统）（273）
			11. Multithreading: Exploiting Thread-Level Parallelism to Improve Uniprocessor Throughput（多线程：利用线程级并行性提高单处理器吞吐量）（274）
				1. Effectiveness of Simultaneous Multithreading on Superscalar Processors（超标量处理器上同步多线程的有效性）（277）
			12. Putting It All Together: The Intel Core i7 6700 and ARM Cortex-A53（综合起来：Intel Core i7 6700 和 ARM Cortex-A53）（279）
				1. The ARM Cortex-A53（280）
					1. Performance of the A53 Pipeline（A53管道的性能）（282）
				2. The Intel Core i7（284）
					1. Performance of the i7（i7的性能）（287）
			13. Fallacies and Pitfalls（谬误和陷阱）（290）
			14. Concluding Remarks: What’s Ahead?（结束语：接下来会发生什么？）（296）
			15. Historical Perspective and References（历史视角和参考文献）（298）
			16. Case Studies and Exercises by Jason D. Bakos and Robert P. Colwell（Jason D. Bakos 和 Robert P. Colwell 的案例研究和练习）（298）
				1. Case Study: Exploring the Impact of Microarchitectural Techniques（案例研究：探索微架构技术的影响）（298）
		4. Data-Level Parallelism in Vector, SIMD, and GPU Architectures（矢量、SIMD 和 GPU 架构中的数据级并行性）（313）
			1. Introduction（介绍）（314）
			2. Vector Architecture（矢量架构）（315）
				1. RV64V Extension（RV64V  扩展）（315）
				2. How Vector Processors Work: An Example（矢量处理器如何工作：一个例子）（320）
				3. Vector Execution Time（向量执行时间）（322）
				4. Multiple Lanes: Beyond One Element per Clock Cycle（多通道：每个时钟周期超过一个元素）（325）
				5. Vector-Length Registers: Handling Loops Not Equal to 32（矢量长度寄存器：处理不等于  32  的循环）（326）
				6. Predicate Registers: Handling IF Statements in Vector Loops（谓词寄存器：处理向量循环中的  IF  语句）（328）
				7. Memory Banks: Supplying Bandwidth for Vector Load/Store Units（存储器组：为矢量加载/存储单元提供带宽）（330）
				8. Stride: Handling Multidimensional Arrays in Vector Architectures（Stride：处理向量架构中的多维数组）（331）
				9. Gather-Scatter: Handling Sparse Matrices in Vector Architectures（聚集-分散：处理向量架构中的稀疏矩阵）（333）
				10. Programming Vector Architectures（向量架构编程）（334）
			3. SIMD Instruction Set Extensions for Multimedia（多媒体的  SIMD  指令集扩展）（336）
				1. Programming Multimedia SIMD Architectures（多媒体  SIMD  架构编程）（339）
				2. The Roofline Visual Performance Model（Roofline  视觉表现模型）（339）
			4. Graphics Processing Units（图形处理单元）（342）
				1. Programming the GPU（GPU  编程）（342）
				2. NVIDIA GPU Computational Structures（NVIDIA  GPU  计算结构）（345）
				3. NVIDA GPU Instruction Set Architecture（NVIDA  GPU  指令集架构）（352）
				4. Conditional Branching in GPUs（GPU  中的条件分支）（355）
				5. NVIDIA GPU Memory Structures（NVIDIA  GPU  内存结构）（358）
				6. Innovations in the Pascal GPU Architecture（Pascal  GPU  架构的创新）（360）
				7. Similarities and Differences Between Vector Architectures and GPUs（矢量架构和 GPU 之间的异同）（363）
				8. Similarities and Differences Between Multimedia SIMD Computers and GPUs（多媒体 SIMD 计算机和 GPU 之间的异同）（367）
				9. Summary（概括）（368）
			5. Detecting and Enhancing Loop-Level Parallelism（检测和增强循环级并行性）（368）
				1. Finding Dependences（寻找依赖关系）（373）
				2. Eliminating Dependent Computations（消除相关计算）（376）
			6. Cross-Cutting Issues（跨领域问题）（377）
				1. Energy and DLP: Slow and Wide Versus Fast and Narrow（能源和  DLP：缓慢⽽宽广与快速且狭窄）（377）
				2. Banked Memory and Graphics Memory（存储内存和图形内存）（378）
				3. Strided Accesses and TLB Misses（跨步访问和  TLB  未命中）（378）
			7. Putting It All Together: Embedded Versus Server GPUs and Tesla Versus Core i7（综合起来：嵌入式与服务器 GPU 以及 Tesla 与 Core i7）（378）
			8. Comparison of a GPU and a MIMD With Multimedia SIMD（GPU  和  MIMD  与多媒体  SIMD  的比较）（379）
			9. Comparison Update（比较更新）（385）
			10. Fallacies and Pitfalls（谬误和陷阱）（385）
			11. Concluding Remarks（结束语）（389）
			12. Historical Perspective and References（历史视角和参考文献）（389）
			13. Case Study and Exercises by Jason D. Bakos（Jason  D.  Bakos  的案例研究和练习）（389）
				1. Case Study: Implementing a Vector Kernel on a Vector Processor and GPU（案例研究：在矢量处理器和 GPU 上实现矢量内核）（389）
		5. Thread-Level Parallelism（线程级并行性）（399）
			1. Introduction（介绍）（400）
				1. Multiprocessor Architecture: Issues and Approach（多处理器架构：问题和方法）（402）
				2. Challenges of Parallel Processing（并行处理的挑战）（405）
			2. Centralized Shared-Memory Architectures（集中式共享内存架构）（409）
				1. What Is Multiprocessor Cache Coherence?（什么是多处理器缓存一致性？）（409）
				2. Basic Schemes for Enforcing Coherence（加强一致性的基本方案）（411）
				3. Snooping Coherence Protocols（窥探一致性协议）（412）
				4. Basic Implementation Techniques（基本实施技术）（414）
				5. An Example Protocol（协议示例）（415）
				6. Extensions to the Basic Coherence Protocol（基本一致性协议的扩展）（420）
				7. Limitations in Symmetric Shared-Memory Multiprocessors and Snooping Protocols（对称共享内存多处理器和监听协议的限制）（421）
				8. Implementing Snooping Cache Coherence（实现监听缓存一致性）（424）
			3. Performance of Symmetric Shared-Memory Multiprocessors（对称共享内存多处理器的性能）（425）
				1. A Commercial Workload（商业工作负载）（426）
				2. A Multiprogramming and OS Workload（多道程序设计和操作系统工作负载）（431）
				3. Performance of the Multiprogramming and OS Workload（多道程序设计和操作系统工作负载的性能）（433）
			4. Distributed Shared-Memory and Directory-Based Coherence（分布式共享内存和基于目录的一致性）（436）
				1. Directory-Based Cache Coherence Protocols: The Basics（基于目录的缓存一致性协议：基础知识）（438）
				2. An Example Directory Protocol（目录协议示例）（440）
			5. Synchronization: The Basics（同步：基础知识）（444）
				1. Basic Hardware Primitives（基本硬件原语）（444）
				2. Implementing Locks Using Coherence（使用一致性实现锁）（446）
			6. Models of Memory Consistency: An Introduction（内存一致性模型：简介）（449）
				1. The Programmer’s View（程序员的观点）（450）
				2. Relaxed Consistency Models: The Basics and Release Consistency（宽松的一致性模型：基础知识和发布一致性）（451）
			7. Cross-Cutting Issues（跨领域问题）（454）
				1. Compiler Optimization and the Consistency Model（编译器优化和一致性模型）（454）
					1. Using Speculation to Hide Latency in Strict Consistency Models（使用推测来隐藏严格一致性模型中的延迟）（454）
					2. Inclusion and Its Implementation（包容性及其实施）（455）
					3. Performance Gains From Multiprocessing and Multithreading（多处理和多线程带来的性能提升）（456）
			8. Putting It All Together: Multicore Processors and Their Performance（综合起来：多核处理器及其性能）（458）
				1. Performance of Multicore-Based Multiprocessors on a Multiprogrammed Workload（基于多核的多处理器在多道程序工作负载上的性能）（458）
				2. Performance of Multicore-Based Multiprocessors on a Multiprogrammed Workload（基于多核的多处理器在多道程序工作负载上的性能）（461）
				3. Scalability in an Xeon MP With Different Workloads（具有不同工作负载的  Xeon  MP  的可扩展性）（465）
				4. Performance and Energy Efficiency of the Intel i7 920 Multicore（Intel i7 920 多核的性能和能效）（466）
					1. Putting Multicore and SMT Together（将多核和  SMT  结合在一起）（468）
			9. Fallacies and Pitfalls（谬误和陷阱）（470）
			10. The Future of Multicore Scaling（多核扩展的未来）（474）
			11. Concluding Remarks（结束语）（476）
			12. Historical Perspectives and References（历史观点和参考）（477）
			13. Case Studies and Exercises by Amr Zaky and David A. Wood（Amr Zaky 和 David A. Wood 的案例研究和练习）（478）
				1. Case Study 1: Single Chip Multicore Multiprocessor（案例研究  1：单芯片多核多处理器）（478）
				2. Case Study 2: Simple Directory-Based Coherence（案例研究  2：简单的基于目录的一致性）（483）
				3. Read/Write Notation（读/写符号）（484）
				4. Messages（留言）（485）
				5. Case Study 3: Memory Consistency（案例研究  3：内存一致性）（488）
		6. Warehouse-Scale Computers to Exploit Request-Level and Data-Level Parallelism（利用请求级和数据级并行性的仓库规模计算机）（497）
			1. Introduction（介绍）（498）
			2. Programming Models and Workloads for Warehouse-Scale Computers（仓库规模计算机的编程模型和工作负载）（503）
			3. Computer Architecture of Warehouse-Scale Computers（仓库规模计算机的计算机体系结构）（509）
				1. Storage（贮存）（510）
				2. WSC Memory Hierarchy（WSC  内存层次结构）（511）
			4. The Efficiency and Cost of Warehouse-Scale Computers（仓库规模计算机的效率和成本）（514）
				1. Measuring Efficiency of a WSC（测量  WSC  的效率）（515）
				2. Cost of a WSC（WSC  的费用）（518）
			5. Cloud Computing: The Return of Utility Computing（云计算：效用计算的回归）（522）
				1. Amazon Web Services（亚马逊网络服务）（523）
				2. How Big Is the AWS Cloud?（AWS  云有多大？）（529）
			6. Cross-Cutting Issues（跨领域问题）（533）
				1. Preventing the WSC Network From Being a Bottleneck（防止WSC网络成为瓶颈）（533）
				2. Using Energy Efficiently Inside the Server（在服务器内部有效利用能源）（535）
			7. Putting It All Together: A Google Warehouse-Scale Computer（将它们放在一起：Google 仓库规模的计算机）（535）
				1. Power Distribution in a Google WSC（Google  WSC  中的配电）（536）
				2. Cooling in a Google WSC（Google  WSC  中的冷却）（538）
				3. Racks of a Google WSC（Google  WSC  的机架）（541）
				4. Networking in a Google WSC（Google  WSC  中的网络）（542）
				5. Servers in a Google WSC（Google  WSC  中的服务器）（544）
				6. Conclusion（结论）（545）
			8. Fallacies and Pitfalls（谬误和陷阱）（546）
			9. Concluding Remarks（结束语）（550）
			10. Historical Perspectives and References（历史观点和参考）（551）
			11. Case Studies and Exercises by Parthasarathy Ranganathan（Parthasarathy Ranganathan 的案例研究和练习）（551）
				1. Case Study 1: Total Cost of Ownership Influencing Warehouse-Scale Computer Design Decisions（案例研究 1：影响仓库规模计算机设计决策的总拥有成本）（551）
				2. Case Study 2: Resource Allocation in WSCs and TCO（案例研究  2：WSC  和  TCO  中的资源分配）（553）
		7. Domain-Specific Architectures（特定领域的架构）（571）
			1. Introduction（介绍）（572）
			2. Guidelines for DSAs（DSA  指南）（575）
			3. Example Domain: Deep Neural Networks（示例领域：深度神经网络）（576）
				1. The Neurons of DNNs（DNN  的神经元）（578）
				2. Training Versus Inference（训练与推理）（579）
				3. Multilayer Perceptron（多层感知器）（581）
				4. Convolutional Neural Network（卷积神经网络）（582）
				5. Recurrent Neural Network（循环神经网络）（585）
				6. Batches（批次）（588）
				7. Quantization（量化）（588）
				8. Summary of DNNs（DNN  总结）（588）
			4. Google’s Tensor Processing Unit, an Inference Data Center Accelerator（谷歌的张量处理单元，推理数据中心加速器）（589）
				1. TPU Origin（TPU产地）（589）
				2. TPU Architecture（TPU架构）（589）
				3. TPU Instruction Set Architecture（TPU指令集架构）（591）
				4. TPU Microarchitecture（TPU微架构）（591）
				5. TPU Implementation（TPU实施）（592）
				6. TPU Software（TPU软件）（595）
				7. Improving the TPU（改进TPU）（596）
				8. Summary: How TPU Follows the Guidelines（摘要：TPU  如何遵循指南）（598）
			5. Microsoft Catapult, a Flexible Data Center Accelerator（Microsoft  Catapult，灵活的数据中心加速器）（599）
				1. Catapult Implementation and Architecture（弹射器实施和架构）（600）
				2. Catapult Software（弹射器软件）（601）
				3. CNNs on Catapult（Catapult  上的  CNN）（602）
				4. Search Acceleration on Catapult（Catapult  上的搜索加速）（605）
				5. Catapult Version 1 Deployment（弹射器版本  1  部署）（606）
				6. Catapult Version 2（弹射器版本  2）（607）
				7. Summary: How Catapult Follows the Guidelines（摘要：Catapult  如何遵循指南）（609）
			6. Intel Crest, a Data Center Accelerator for Training（Intel  Crest，用于培训的数据中心加速器）（611）
			7. Pixel Visual Core, a Personal Mobile Device Image Processing Unit（Pixel Visual Core，个人移动设备图像处理单元）（611）
				1. ISPs, the Hardwired Predecessors of IPUs（ISP，IPU  的硬连线前身）（612）
				2. Pixel Visual Core Software（Pixel  Visual  Core  软件）（614）
				3. Pixel Visual Core Architecture Philosophy（Pixel视觉核心架构理念）（615）
				4. The Pixel Visual Core Halo（像素视觉核心光环）（616）
				5. A Processor of the Pixel Visual Core（像素视觉核心处理器）（617）
				6. Pixel Visual Core Instruction Set Architecture（Pixel  Visual  Core指令集架构）（619）
				7. Pixel Visual Core Example（像素视觉核心示例）（620）
				8. Pixel Visual Core Processing Element（像素视觉核心处理元件）（620）
				9. Two-Dimensional Line Buffers and Their Controller（二维行缓冲器及其控制器）（621）
				10. Pixel Visual Core Implementation（像素视觉核心实现）（622）
				11. Summary: How Pixel Visual Core Follows the Guidelines（摘要：Pixel  Visual  Core  如何遵循指南）（623）
			8. Cross-Cutting Issues（跨领域问题）（624）
				1. Heterogeneity and System on a Chip (SOC)（异构性和片上系统  (SOC)）（624）
				2. An Open Instruction Set（开放指令集）（626）
			9. Putting It All Together: CPUs Versus GPUs Versus DNN Accelerators（综合起来：CPU 与 GPU 与 DNN 加速器）（627）
				1. Performance: Rooflines, Response Time, and Throughput（性能：屋顶线、响应时间和吞吐量）（628）
				2. Cost-Performance, TCO, and Performance/Watt（性价比、TCO  和性能功耗比）（632）
				3. Evaluating Catapult and Pixel Visual Core（评估弹射器和像素视觉核心）（633）
			10. Fallacies and Pitfalls（谬论和陷阱）（634）
			11. Concluding Remarks（结束语）（636）
				1. An Architecture Renaissance（建筑文艺复兴）（637）
			12. Historical Perspectives and References（历史观点和参考）（638）
			13. Case Studies and Exercises by Cliff Young（Cliff  Young  的案例研究和练习）（638）
				1. Case Study: Google’s Tensor Processing Unit and Acceleration of Deep Neural Networks（案例研究：谷歌的张量处理单元和深度神经网络加速）（638）
		8. Instruction Set Principles（指令集原则）（651）
			1. Introduction（介绍）（652）
			2. Classifying Instruction Set Architectures（指令集架构分类）（653）
				1. Summary: Classifying Instruction Set Architectures（摘要：指令集架构分类）（656）
			3. Memory Addressing（内存寻址）（657）
				1. Interpreting Memory Addresses（解释内存地址）（657）
				2. Addressing Modes（寻址模式）（658）
				3. Displacement Addressing Mode（位移寻址模式）（661）
				4. Immediate or Literal Addressing Mode（立即或文字寻址模式）（662）
				5. Summary: Memory Addressing（摘要：内存寻址）（662）
			4. Type and Size of Operands（操作数的类型和大小）（663）
			5. Operations in the Instruction Set（指令集中的操作）（665）
			6. Instructions for Control Flow（控制流程说明）（666）
				1. Addressing Modes for Control Flow Instructions（控制流指令的寻址模式）（667）
				2. Conditional Branch Options（条件分支选项）（668）
				3. Procedure Invocation Options（过程调用选项）（669）
				4. Summary: Instructions for Control Flow（摘要：控制流说明）（670）
			7. Encoding an Instruction Set（指令集编码）（671）
				1. Reduced Code Size in RISCs（减少  RISC  中的代码大小）（673）
				2. Summary: Encoding an Instruction Set（摘要：编码指令集）（674）
			8. Cross-Cutting Issues: The Role of Compilers（交叉问题：编译器的作用）（674）
				1. The Structure of Recent Compilers（最新编译器的结构）（675）
				2. Register Allocation（寄存器分配）（677）
				3. Impact of Optimizations on Performance（优化对性能的影响）（677）
				4. The Impact of Compiler Technology on the Architect’s Decisions（编译器技术对架构师决策的影响）（677）
				5. How the Architect Can Help the Compiler Writer（架构师如何帮助编译器编写者）（680）
				6. Compiler Support (or Lack Thereof) for Multimedia Instructions（多媒体指令的编译器支持（或缺乏））（681）
				7. Summary: The Role of Compilers（摘要：编译器的作用）（682）
			9. Putting It All Together: The RISC-V Architecture（整合在一起：RISC‑V  架构）（683）
				1. RISC-V Instruction Set Organization（RISC‑V指令集组织）（684）
				2. Registers for RISC-V（RISC‑V  寄存器）（684）
				3. Data Types for RISC-V（RISC‑V  的数据类型）（685）
				4. Addressing Modes for RISC-V Data Transfers（RISC‑V  数据传输的寻址模式）（686）
				5. RISC-V Instruction Format（RISC‑V指令格式）（686）
				6. RISC-V Operations（RISC‑V  操作）（687）
				7. RISC-V Control Flow Instructions（RISC‑V  控制流程指令）（689）
				8. RISC-V Floating-Point Operations（RISC‑V  浮点运算）（690）
				9. RISC-V Instruction Set Usage（RISC‑V指令集使用）（692）
			10. Fallacies and Pitfalls（谬论和陷阱）（692）
			11. Concluding Remarks（结束语）（696）
			12. Historical Perspective and References（历史视角和参考文献）（697）
			13. Exercises by Gregory D. Peterson（格雷戈里·D·彼得森的练习）（697）
		9. Review of Memory Hierarchy（内存层次结构回顾）（707）
			1. Introduction（介绍）（708）
				1. Cache Performance Review（缓存性能审查）（709）
				2. Four Memory Hierarchy Questions（四个内存层次结构问题）（712）
					1. Q1: Where Can a Block be Placed in a Cache?（Q1：块可以放在缓存中的什么位置？）（712）
					2. Q2: How Is a Block Found If It Is in the Cache?（Q2：如果一个块在缓存中，如何找到它？）（714）
					3. Q3: Which Block Should be Replaced on a Cache Miss?（Q3：缓存未命中时应替换哪个块？）（715）
					4. Q4: What Happens on a Write?（Q4：写⼊时会发生什么？）（716）
				3. An Example: The Opteron Data Cache（示例：Opteron  数据缓存）（718）
			2. Cache Performance（缓存性能）（721）
				1. Average Memory Access Time and Processor Performance（平均内存访问时间和处理器性能）（723）
				2. Miss Penalty and Out-of-Order Execution Processors（未命中处罚和乱序执行处理器）（726）
			3. Six Basic Cache Optimizations（六种基本缓存优化）（728）
				1. First Optimization: Larger Block Size to Reduce Miss Rate（第一个优化：更大的块大小以降低丢失率）（732）
				2. Second Optimization: Larger Caches to Reduce Miss Rate（优化二：加大缓存，降低丢失率）（734）
				3. Third Optimization: Higher Associativity to Reduce Miss Rate（第三次优化：更高的关联性，降低失误率）（734）
				4. Fourth Optimization: Multilevel Caches to Reduce Miss Penalty（优化四：多级缓存，减少丢失惩罚）（736）
				5. Fifth Optimization: Giving Priority to Read Misses over Writes to Reduce Miss Penalty（优化五：读缺失优先于写入，减少缺失惩罚）（741）
				6. Sixth Optimization: Avoiding Address Translation During Indexing of the Cache to Reduce Hit Time（优化六：在缓存索引期间避免地址转换以减少命中时间）（742）
				7. Summary of Basic Cache Optimization（基本缓存优化总结）（746）
			4. Virtual Memory（虚拟内存）（746）
				1. Four Memory Hierarchy Questions Revisited（重新审视四个内存层次结构问题）（750）
					1. Q1: Where Can a Block be Placed in Main Memory?（Q1：块可以放置在主存中的什么位置？）（750）
					2. Q2: How Is a Block Found If It Is in Main Memory?（Q2：如果块在主存中，如何找到它？）（750）
					3. Q3: Which Block Should be Replaced on a Virtual Memory Miss?（Q3：虚拟内存丢失时应该替换哪个块？）（751）
					4. Q4: What Happens on a Write?（Q4：写⼊时会发生什么？）（751）
				2. Techniques for Fast Address Translation（快速地址转换技术）（752）
				3. Selecting a Page Size（选择页面尺寸）（752）
				4. Summary of Virtual Memory and Caches（虚拟内存和缓存总结）（754）
			5. Protection and Examples of Virtual Memory（虚拟内存的保护和示例）（755）
				1. Protecting Processes（保护进程）（756）
				2. A Segmented Virtual Memory Example: Protection in the Intel Pentium（分段虚拟内存示例：Intel  Pentium  中的保护）（757）
					1. Adding Bounds Checking and Memory Mapping（添加边界检查和内存映射）（758）
					2. Adding Sharing and Protection（添加共享和保护）（758）
					3. Adding Safe Calls from User to OS Gates and Inheriting Protection Level for Parameters（添加用户对操作系统门的安全调用并继承参数的保护级别）（760）
				3. A Paged Virtual Memory Example: The 64-Bit Opteron Memory Management（分页虚拟内存示例：64 位 Opteron 内存管理）（760）
				4. Summary: Protection on the 32-Bit Intel Pentium Versus the 64-Bit AMD Opteron（摘要：32 位 Intel Pentium 与 64 位 AMD Opteron 的保护）（763）
			6. Fallacies and Pitfalls（谬误和陷阱）（763）
			7. Concluding Remarks（结束语）（765）
			8. Historical Perspective and References（历史视角和参考文献）（765）
			9. Exercises by Amr Zaky（Amr  Zaky  的练习）（766）
		10. Pipelining: Basic and Intermediate Concepts（管道：基本和中级概念）（775）
			1. Introduction（介绍）（776）
				1. What Is Pipelining?（什么是管道化？）（776）
				2. The Basics of the RISC V Instruction Set（RISC  V  指令集的基础知识）（777）
				3. A Simple Implementation of a RISC Instruction Set（RISC指令集的简单实现）（778）
				4. The Classic Five-Stage Pipeline for a RISC Processor（RISC  处理器的经典五级流水线）（780）
				5. Basic Performance Issues in Pipelining（流水线中的基本性能问题）（782）
			2. The Major Hurdle of Pipelining—Pipeline Hazards（管道输送的主要障碍——管道危险）（784）
				1. Performance of Pipelines With Stalls（带失速管道的性能）（785）
				2. Data Hazards（数据危害）（786）
					1. Minimizing Data Hazard Stalls by Forwarding（通过转发最大限度地减少数据危险停顿）（788）
					2. Data Hazards Requiring Stalls（需要暂停的数据危险）（790）
				3. Branch Hazards（分支危害）（792）
					1. Reducing Pipeline Branch Penalties（减少管道分支处罚）（793）
					2. Performance of Branch Schemes（分行计划的表现）（795）
				4. Reducing the Cost of Branches Through Prediction（通过预测降低分支机构成本）（796）
				5. Static Branch Prediction（静态分支预测）（796）
				6. Dynamic Branch Prediction and Branch-Prediction Buffers（动态分支预测和分支预测缓冲区）（797）
			3. How Is Pipelining Implemented?（流水线是如何实现的？）（800）
				1. A Simple Implementation of RISC V（RISC  V  的简单实现）（800）
				2. A Basic Pipeline for RISC V（RISC  V  的基本流程）（804）
				3. Implementing the Control for the RISC V Pipeline（实现  RISC  V  流水线的控制）（807）
				4. Dealing With Branches in the Pipeline（处理管道中的分支）（809）
			4. What Makes Pipelining Hard to Implement?（是什么使得流水线难以实施？）（811）
				1. Dealing With Exceptions（处理异常）（812）
					1. Types of Exceptions and Requirements（例外情况和要求的类型）（812）
					2. Stopping and Restarting Execution（停止和重新启动执行）（815）
					3. Exceptions in RISC V（RISC  V  中的例外）（816）
				2. Instruction Set Complications（指令集并发症）（817）
			5. Extending the RISC V Integer Pipeline to Handle Multicycle Operations（扩展 RISC V 整数管道以处理多周期操作）（819）
				1. Hazards and Forwarding in Longer Latency Pipelines（较长延迟管道中的危险和转发）（823）
				2. Maintaining Precise Exceptions（维护精确的异常）（827）
				3. Performance of a Simple RISC V FP Pipeline（简单  RISC  V  FP  流水线的性能）（829）
			6. Putting It All Together: The MIPS R4000 Pipeline（综合起来：MIPS  R4000  管道）（829）
				1. The Floating-Point Pipeline（浮点流水线）（834）
				2. Performance of the R4000 Pipeline（R4000  管道的性能）（835）
			7. Cross-Cutting Issues（跨领域问题）（839）
				1. RISC Instruction Sets and Efficiency of Pipelining（RISC  指令集和流水线效率）（839）
				2. Dynamically Scheduled Pipelines（动态调度管道）（839）
					1. Dynamic Scheduling With a Scoreboard（使用记分板进行动态调度）（840）
			8. Fallacies and Pitfalls（谬误和陷阱）（844）
			9. Concluding Remarks（结束语）（845）
			10. Historical Perspective and References（历史视角和参考文献）（845）
			11. Updated Exercises by Diana Franklin（戴安娜·富兰克林更新的练习）（845）
		11. Storage Systems（存储系统）（854）
			1. Introduction（介绍）（855）
			2. Advanced Topics in Disk Storage（磁盘存储的高级主题）（855）
				1. Disk Power（磁盘电源）（858）
				2. Advanced Topics in Disk Arrays（磁盘阵列的高级主题）（859）
					1. RAID 10 versus 01 (or 1 +0 versus RAID 0+1)（RAID  10  与  01（或  1+0  与  RAID  0+1））（861）
					2. RAID 6: Beyond a Single Disk Failure（RAID  6：超越单一磁盘故障）（861）
			3. Definition and Examples of Real Faults and Failures（实际故障和故障的定义和示例）（863）
				1. Berkeley’s Tertiary Disk（伯克利第三级磁盘）（865）
				2. Tandem（串联）（866）
				3. Other Studies of the Role of Operators in Dependability（关于操作员在可靠性中的作用的其他研究）（866）
			4. I/O Performance, Reliability Measures, and Benchmarks（I/O  性能、可靠性测量和基准）（868）
				1. Throughput versus Response Time（吞吐量与响应时间）（869）
				2. Transaction-Processing Benchmarks（事务处理基准）（871）
				3. SPEC System-Level File Server, Mail, and Web Benchmarks（SPEC  系统级文件服务器、邮件和  Web  基准测试）（873）
				4. Examples of Benchmarks of Dependability（可靠性基准示例）（874）
			5. A Little Queuing Theory（一点排队理论）（876）
				1. Poisson Distribution of Random Variables（随机变量的泊松分布）（879）
			6. Crosscutting Issues（横切问题）（887）
				1. Point-to-Point Links and Switches Replacing Buses（点对点链路和交换机取代总线）（887）
				2. Block Servers versus Filers（块服务器与文件管理器）（887）
				3. Asynchronous I/O and Operating Systems（异步  I/O  和操作系统）（888）
			7. Designing and Evaluating an I/O System—The Internet Archive Cluster（设计和评估 I/O 系统 - 互联网档案集群）（889）
				1. The Internet Archive Cluster（互联网档案集群）（890）
				2. Estimating Performance, Dependability, and Cost of the Internet Archive Cluster（估计 Internet Archive 集群的性能、可靠性和成本）（891）
				3. Calculating MTTF of the TB-80 Cluster（计算  TB‑80  集群的  MTTF）（894）
			8. Putting It All Together: NetApp FAS6000 Filer（综合起来：NetApp  FAS6000  文件管理器）（896）
			9. Fallacies and Pitfalls（谬误和陷阱）（896）
			10. Concluding Remarks（结束语）（900）
			11. Historical Perspective and References（历史视角和参考文献）（901）
			12. Case Studies with Exercises by Andrea C. Arpaci-Dusseau and Remzi H. Arpaci-Dusseau（Andrea C. Arpaci-Dusseau 和 Remzi H. Arpaci-Dusseau 的案例研究与练习）（901）
				1. Case Study 1: Deconstructing a Disk（案例研究  1：解构磁盘）（901）
				2. Case Study 2: Deconstructing a Disk Array（案例研究  2：解构磁盘阵列）（904）
				3. Case Study 3: RAID Reconstruction（案例3：RAID重构）（908）
				4. Case Study 4: Performance Prediction for RAIDs（案例研究  4：RAID  性能预测）（910）
				5. Case Study 5: I/O Subsystem Design（案例研究 5：I/O 子系统设计）（912）
				6. Case Study 6: Dirty Rotten Bits（案例研究  6：脏乱差）（914）
				7. Case Study 7: Sorting Things Out（案例研究  7：整理事情）（917）
		12. Embedded Systems（嵌入式系统）（922）
			1. Introduction（介绍）（923）
				1. Real-Time Processing（实时处理）（924）
			2. Signal Processing and Embedded Applications: The Digital Signal Processor（信号处理和嵌入式应用：数字信号处理器）（926）
				1. The TI 320C55（928）
				2. The TI 320C6x（929）
				3. Media Extensions（媒体扩展）（931）
			3. Embedded Benchmarks（嵌入式基准测试）（933）
				1. Power Consumption and Efficiency as the Metric（以功耗和效率为衡量标准）（934）
			4. Embedded Multiprocessors（嵌入式多处理器）（935）
			5. Case Study: The Emotion Engine of the Sony PlayStation 2（案例研究：Sony  PlayStation  2  的情感引擎）（936）
			6. Case Study: Sanyo VPC-SX500 Digital Camera（案例研究：三洋  VPC‑SX500  数码相机）（940）
			7. Case Study: Inside a Cell Phone（案例研究：手机内部）（941）
				1. Background on Wireless Networks（无线网络背景）（942）
				2. The Cell Phone（手机）（943）
				3. Cell Phone Standards and Evolution（手机标准和演变）（946）
			8. Concluding Remarks（结束语）（946）
		13. Interconnection Networks（互连网络）（949）
			1. Introduction（介绍）（950）
				1. Interconnection Network Domains（互联网络域）（951）
				2. Approach and Organization of This Appendix（本附录的方法和组织）（953）
			2. Interconnecting Two Devices（连接两个设备）（954）
				1. Network Interface Functions: Composing and Processing Messages（网络接口功能：编写和处理消息）（954）
				2. Basic Network Structure and Functions: Media and Form Factor, Packet Transport, Flow Control, and Error Handling（基本网络结构和功能：媒体和外形尺寸、数据包传输、流量控制和错误处理）（957）
				3. Characterizing Performance: Latency and Effective Bandwidth（表征性能：延迟和有效带宽）（961）
			3. Connecting More than Two Devices（连接两个以上设备）（968）
				1. Additional Network Structure and Functions: Topology, Routing, Arbitration, and Switching（附加网络结构和功能：拓扑、路由、仲裁和交换）（969）
				2. Shared-Media Networks（共享媒体网络）（971）
				3. Switched-Media Networks（交换媒体网络）（972）
				4. Comparison of Shared- and Switched-Media Networks（共享媒体网络和交换媒体网络的比较）（973）
				5. Characterizing Performance: Latency and Effective Bandwidth（表征性能：延迟和有效带宽）（973）
			4. Network Topology（网络拓扑）（978）
				1. Centralized Switched Networks（集中交换网络）（979）
				2. Distributed Switched Networks（分布式交换网络）（983）
				3. Effects of Topology on Network Performance（拓扑对网络性能的影响）（989）
			5. Network Routing, Arbitration, and Switching（网络路由、仲裁和交换）（992）
				1. Routing（路由）（993）
				2. Arbitration（仲裁）（997）
				3. Switching（交换）（999）
				4. Impact on Network Performance（对网络性能的影响）（1000）
			6. Switch Microarchitecture（开关微架构）（1004）
				1. Basic Switch Microarchitecture（基本开关微架构）（1004）
				2. Buffer Organizations（缓冲组织）（1007）
				3. Routing Algorithm Implementation（路由算法实现）（1009）
				4. Pipelining the Switch Microarchitecture（Switch  微架构的流水线化）（1012）
				5. Other Switch Microarchitecture Enhancements（其他  Switch  微架构增强功能）（1014）
			7. Practical Issues for Commercial Interconnection Networks（商业互联网络的实际问题）（1015）
				1. Connectivity（连接性）（1015）
				2. Standardization: Cross-Company Interoperability（标准化：跨公司互操作性）（1015）
				3. Congestion Management（拥塞管理）（1016）
				4. Fault Tolerance（容错能力）（1018）
			8. Examples of Interconnection Networks（互连网络示例）（1021）
				1. On-Chip Network: Intel Single-Chip Cloud Computer（片上网络：英特尔单芯片云计算机）（1022）
				2. System Area Network: IBM Blue Gene/L 3D Torus Network（系统局域网：IBM  Blue  Gene/L  3D  Torus  网络）（1024）
				3. System/Storage Area Network: InfiniBand（系统/存储区域网络：InfiniBand）（1025）
				4. Ethernet: The Local Area Network（以太网：局域网）（1030）
				5. Wide Area Network: ATM（广域网：ATM）（1032）
			9. Internetworking（网络互联）（1033）
			10. Crosscutting Issues for Interconnection Networks（互连网络的横切问题）（1037）
				1. Density-Optimized Processors versus SPEC-Optimized Processors（密度优化处理器与规格优化处理器）（1037）
				2. Smart Switches versus Smart Interface Cards（智能交换机与智能接口卡）（1038）
				3. Protection and User Access to the Network（保护和用户对网络的访问）（1039）
				4. Efficient Interface to the Memory Hierarchy versus the Network（内存层次结构与网络的高效接口）（1039）
				5. Compute-Optimized Processors versus Receiver Overhead（计算优化处理器与接收器开销）（1040）
			11. Fallacies and Pitfalls（谬误和陷阱）（1040）
			12. Concluding Remarks（结束语）（1048）
			13. Historical Perspective and References（历史视角和参考文献）（1049）
				1. Wide Area Networks（广域网）（1050）
				2. Local Area Networks（局域网）（1051）
				3. System Area Networks（系统区域网络）（1052）
				4. Storage Area Networks（存储区域网络）（1054）
				5. On-Chip Networks（片上网络）（1056）
		14. Vector Processors in More Depth（更深入的矢量处理器）（1068）
			1. Introduction（介绍）（1069）
			2. Vector Performance in More Depth（更深入的矢量性能）（1069）
				1. Pipelined Instruction Start-Up and Multiple Lanes（流水线指令启动和多通道）（1074）
			3. Vector Memory Systems in More Depth（更深入的向量存储系统）（1076）
			4. Enhancing Vector Performance（增强矢量性能）（1078）
				1. Chaining in More Depth（更深入的链接）（1078）
				2. Sparse Matrices in More Depth（更深入的稀疏矩阵）（1079）
			5. Effectiveness of Compiler Vectorization（编译器矢量化的有效性）（1081）
			6. Putting It All Together: Performance of Vector Processors（综合起来：矢量处理器的性能）（1082）
				1. Measures of Vector Performance（矢量性能的测量）（1082）
				2. The Peak Performance of VMIPS on DAXPY（VMIPS  在  DAXPY  上的峰值性能）（1084）
				3. Sustained Performance of VMIPS on the Linpack Benchmark（VMIPS  在  Linpack  基准测试中的持续性能）（1084）
				4. DAXPY Performance on an Enhanced VMIPS（增强型  VMIPS  上的  DAXPY  性能）（1086）
			7. A Modern Vector Supercomputer: The Cray X1（现代矢量超级计算机：Cray  X1）（1088）
				1. Multi-Streaming Processors（多流处理器）（1090）
				2. Cray X1E（1091）
			8. Concluding Remarks（结束语）（1092）
			9. Historical Perspective and References（历史视角和参考文献）（1093）
		15. Hardware and Software for VLIW and EPIC（VLIW 和 EPIC 的硬件和软件）（1103）
			1. Introduction: Exploiting Instruction-Level Parallelism Statically（简介：静态利用指令级并行性）（1104）
			2. Detecting and Enhancing Loop-Level Parallelism（检测和增强循环级并行性）（1104）
				1. Finding Dependences（寻找依赖关系）（1108）
				2. Eliminating Dependent Computations（消除相关计算）（1112）
			3. Scheduling and Structuring Code for Parallelism（并行性的调度和结构化代码）（1114）
				1. Software Pipelining: Symbolic Loop Unrolling（软件流水线：符号循环展开）（1114）
				2. Global Code Scheduling（全局代码调度）（1117）
					1. Trace Scheduling: Focusing on the Critical Path（跟踪调度：关注关键路径）（1121）
					2. Superblocks（超级街区）（1123）
			4. Hardware Support for Exposing Parallelism: Predicated Instructions（公开并行性的硬件支持：谓词指令）（1125）
			5. Hardware Support for Compiler Speculation（对编译器推测的硬件支持）（1129）
				1. Hardware Support for Preserving Exception Behavior（保留异常行为的硬件支持）（1130）
				2. Hardware Support for Memory Reference Speculation（对内存参考推测的硬件支持）（1134）
			6. The Intel IA-64 Architecture and Itanium Processor（Intel  IA‑64  架构和  Itanium  处理器）（1134）
				1. The Intel IA-64 Instruction Set Architecture（英特尔  IA‑64  指令集架构）（1134）
					1. The IA-64 Register Model（IA‑64  寄存器模型）（1135）
					2. Instruction Format and Support for Explicit Parallelism（指令格式和显式并行支持）（1136）
					3. Instruction Set Basics（指令集基础知识）（1140）
					4. Predication and Speculation Support（预测和推测支持）（1140）
				2. The Itanium 2 Processor（安腾  2  处理器）（1142）
					1. Functional Units and Instruction Issue（功能单元和指令问题）（1143）
					2. Itanium 2 Performance（安腾  2  性能）（1145）
			7. Concluding Remarks（结束语）（1145）
		16. Large-Scale Multiprocessors and Scientific Applications（大规模多处理器和科学应用）（1148）
			1. Introduction（介绍）（1149）
			2. Interprocessor Communication: The Critical Performance Issue（处理器间通信：关键的性能问题）（1150）
				1. Advantages of Different Communication Mechanisms（不同沟通机制的优点）（1151）
			3. Characteristics of Scientific Applications（科学应用的特点）（1153）
				1. Characteristics of Scientific Applications（科学应用的特点）（1153）
					1. The FFT Kernel（FFT  内核）（1154）
					2. The LU Kernel（LU  内核）（1155）
					3. The Barnes Application（巴恩斯申请）（1155）
					4. The Ocean Application（海洋应用）（1156）
					5. Computation/Communication for the Parallel Programs（并行程序的计算/通信）（1157）
			4. Synchronization: Scaling Up（同步：扩大规模）（1159）
				1. Synchronization Performance Challenges（同步性能挑战）（1159）
					1. Barrier Synchronization（屏障同步）（1160）
				2. Synchronization Mechanisms for Larger-Scale Multiprocessors（大规模多处理器的同步机制）（1164）
					1. Software Implementations（软件实施）（1164）
					2. Hardware Primitives（硬件原语）（1165）
			5. Performance of Scientific Applications on Shared-Memory Multiprocessors（共享内存多处理器上科学应用程序的性能）（1168）
				1. Performance of a Scientific Workload on a Symmetric Shared-Memory Multiprocessor（对称共享内存多处理器上科学工作负载的性能）（1168）
				2. Performance of a Scientific Workload on a Distributed-Memory Multiprocessor（分布式内存多处理器上科学工作负载的性能）（1173）
			6. Performance Measurement of Parallel Processors with Scientific Applications（并行处理器性能测量与科学应用）（1180）
			7. Implementing Cache Coherence（实现缓存一致性）（1181）
				1. Implementing Cache Coherence in a DSM Multiprocessor（在  DSM  多处理器中实现缓存一致性）（1183）
				2. Avoiding Deadlock from Limited Buffering（避免有限缓冲造成的死锁）（1185）
				3. Implementing the Directory Controller（实现目录控制器）（1187）
			8. The Custom Cluster Approach: Blue Gene/L（定制聚类方法：Blue  Gene/L）（1188）
				1. The Blue Gene/L Computing Node（蓝色基因/L计算节点）（1189）
			9. Concluding Remarks（结束语）（1191）
		17. Computer Arithmetic（计算机算术）（1196）
			1. Introduction（介绍）（1197）
			2. Basic Techniques of Integer Arithmetic（整数运算的基本技巧）（1197）
				1. Ripple-Carry Addition（纹波进位加法）（1197）
				2. Radix-2 Multiplication and Division（Radix‑2  乘法和除法）（1199）
				3. Signed Numbers（签名号码）（1202）
				4. Systems Issues（系统问题）（1205）
			3. Floating Point（浮点）（1208）
				1. Special Values and Denormals（特殊值和非正规值）（1209）
				2. .Representation of Floating-Point Numbers（浮点数的表示）（1210）
			4. Floating-Point Multiplication（浮点乘法）（1212）
				1. Denormals（非正规化）（1215）
				2. Precision of Multiplication（乘法精度）（1216）
			5. Floating-Point Addition（浮点加法）（1216）
				1. Speeding Up Addition（加速添加）（1220）
				2. Denormalized Numbers（非规范化数字）（1221）
			6. Division and Remainder（除法和余数）（1222）
				1. Iterative Division（迭代除法）（1222）
				2. Floating-Point Remainder（浮点余数）（1226）
			7. More on Floating-Point Arithmetic（有关浮点运算的更多信息）（1227）
				1. Fused Multiply-Add（乘加融合）（1227）
				2. Precisions（精度）（1228）
				3. Exceptions（例外情况）（1229）
				4. Underflow（下溢）（1231）
			8. Speeding Up Integer Addition（加速整数加法）（1232）
				1. Carry-Lookahead（先行进位）（1232）
				2. Carry-Skip Adders（跳进位加法器）（1236）
				3. Carry-Select Adder（进位选择加法器）（1238）
			9. Speeding Up Integer Multiplication and Division（加速整数乘法和除法）（1239）
				1. Shifting over Zeros（移过零）（1240）
				2. SRT Division（SRT  除法）（1240）
				3. Speeding Up Multiplication with a Single Adder（使用单个加法器加速乘法）（1242）
				4. Faster Multiplication with Many Adders（使用多个加法器进行更快的乘法）（1244）
				5. Faster Division with One Adder（使用一个加法器加快除法速度）（1249）
			10. Putting It All Together（综合起来）（1252）
			11. Fallacies and Pitfalls（谬误和陷阱）（1257）
			12. Historical Perspective and References（历史视角和参考文献）（1258）
		18. Survey of Instruction Set Architectures（指令集架构综述）（1270）
			1. Introduction（介绍）（1271）
			2. A Survey of RISC Architectures for Desktop, Server, and Embedded Computers（台式机、服务器和嵌入式计算机的 RISC 架构调查）（1272）
				1. Introductio（介绍）（1272）
				2. Addressing Modes and Instruction Formats（寻址模式和指令格式）（1275）
				3. Instructions（指示）（1278）
					1. RV64G Core Instructions（RV64G核心指令）（1280）
					2. Compare and Conditional Branch（⽐较和条件分支）（1280）
					3. RV64GC Core 16-bit Instructions（RV64GC  内核  16  位指令）（1285）
				4. Instructions: Common Extensions beyond RV64G（说明：RV64G  之外的常见扩展）（1287）
				5. Instructions Unique to MIPS64 R6（MIPS64  R6  特有的指令）（1288）
				6. Instructions Unique to SPARC v.9（SPARC  v.9  特有的指令）（1289）
					1. Register Windows（注册Windows）（1289）
					2. Fast Traps（快速陷阱）（1289）
					3. Support for LISP and Smalltalk（支持  LISP  和  Smalltalk）（1290）
				7. Instructions Unique to ARM（ARM  独有的指令）（1291）
				8. Instructions Unique to Power3（Power3  独有的指令）（1292）
					1. Branch Registers: Link and Counter（分支寄存器：链接和计数器）（1294）
				9. Instructions: Multimedia Extensions of the Desktop/Server RISCs（说明：桌面/服务器 RISC 的多媒体扩展）（1294）
				10. Instructions: Digital Signal-Processing Extensions of the Embedded RISCs（指令：嵌入式 RISC 的数字信号处理扩展）（1297）
				11. Concluding Remarks（结束语）（1298）
			3. The Intel 80x86（英特尔  80x86）（1299）
				1. Introduction（介绍）（1299）
				2. 80x86 Registers and Data Addressing Modes（80x86  寄存器和数据寻址模式）（1301）
				3. 80x86 Integer Operations（80x86  整数运算）（1304）
				4. 80x86 Floating-Point Operations（80x86  浮点运算）（1307）
				5. 80x86 Instruction Encoding（80x86指令编码）（1309）
				6. Putting It All Together: Measurements of Instruction Set Usage（综合起来：指令集使用的测量）（1313）
					1. Measurements of 80x86 Operand Addressing（80x86  操作数寻址的测量）（1313）
					2. Comparative Operation Measurements（⽐较操作测量）（1315）
				7. Concluding Remarks（结束语）（1318）
					1. Beauty is in the eye of the beholder.（美在旁观者的眼中）（1318）
			4. The VAX Architecture（VAX  架构）（1319）
				1. Introduction（介绍）（1320）
				2. VAX Operands and Addressing Modes（VAX  操作数和寻址模式）（1320）
				3. Encoding VAX Instructions（编码  VAX  指令）（1323）
				4. VAX Operations（VAX运营）（1324）
					1. Number of Operations（操作次数）（1325）
					2. Branches, Jumps, and Procedure Calls（分支、跳转和过程调用）（1326）
				5. An Example to Put It All Together: swap（将所有内容放在一起的示例：交换）（1326）
					1. Register Allocation for swap（登记交换分配）（1328）
					2. Code for the Body of the Procedure swap（程序交换主体代码）（1328）
					3. Preserving Registers across Procedure Invocation of swap（跨过程调用交换保留寄存器）（1329）
					4. The Full Procedure swap（完整程序交换）（1330）
				6. A Longer Example: sort（更长的例子：排序）（1331）
					1. Register Allocation for sort（排序的寄存器分配）（1331）
					2. Code for the Body of the sort Procedure（排序过程主体代码）（1331）
						1. The Outer Loop（外环）（1331）
						2. The Inner Loop（内循环）（1332）
						3. The Procedure Call（过程调用）（1333）
						4. Passing Parameters（传递参数）（1333）
					3. Preserving Registers across Procedure Invocation of sort（跨过程调用保留寄存器）（1334）
					4. The Full Procedure sort（完整程序排序）（1334）
				7. Fallacies and Pitfalls（谬误和陷阱）（1334）
				8. Concluding Remarks（结束语）（1336）
			5. The IBM 360/370 Architecture for Mainframe Computers（大型计算机的  IBM  360/370  架构）（1338）
				1. Introduction（介绍）（1338）
				2. System/360 Instruction Set（System/360指令集）（1339）
					1. Integer/Logical and Floating-Point R-R Instructions（整数/逻辑和浮点  RR  指令）（1339）
					2. Branches and Status Setting R-R Instructions（分支和状态设置  RR  指令）（1340）
					3. Branches/Logical and Floating-Point Instructions—RX Format（分支/逻辑和浮点指令  ‑  RX  格式）（1340）
					4. Branches and Special Loads and Stores—RX Format（分支和特殊加载和存储  ‑  RX  格式）（1341）
					5. RS and SI Format Instructions（RS  和  SI  格式指令）（1341）
					6. SS Format Instructions（SS  格式说明）（1342）
				3. 360 Detailed Measurements（360  度详细测量）（1342）
			6. Historical Perspective and References（历史视角和参考文献）（1344）
		19. Advanced Concepts on Address Translation（地址转换的高级概念）（1346）
		20. Historical Perspectives and References（历史观点和参考）（1348）
			1. Introduction（介绍）（1349）
			2. The Early Development of Computers (Chapter 1)（计算机的早期发展（第一章））（1349）
				1. The First General-Purpose Electronic Computers（第一台通用电子计算机）（1349）
				2. Important Special-Purpose Machines（重要专用机）（1351）
				3. Commercial Developments（商业发展）（1352）
				4. Development of Quantitative Performance Measures: Successes and Failures（定量绩效衡量标准的制定：成功与失败）（1353）
			3. The Development of Memory Hierarchy and Protection (Chapter 2 and Appendix B)（内存层次结构和保护的发展（第 2 章和附录 B））（1356）
			4. The Evolution of Instruction Sets (Appendices A, J, and K)（指令集的演变（附录  A、J  和  K））（1364）
				1. Stack Architectures（堆栈架构）（1364）
				2. Computer Architecture Defined（计算机体系结构定义）（1365）
				3. High-Level Language Computer Architecture（高级语言计算机体系结构）（1366）
				4. Reduced Instruction Set Computers（精简指令集计算机）（1367）
			5. The Development of Pipelining and Instruction-Level Parallelism (Chapter 3 and Appendices C and H)（流水线和指令级并行性的发展（第 3 章和附录 C 和 H））（1374）
				1. Early Pipelined CPUs（早期的流水线CPU）（1374）
				2. The Introduction of Dynamic Scheduling（动态调度简介）（1375）
				3. The IBM 360 Model 91: A Landmark Computer（IBM  360  Model  91：具有里程碑意义的计算机）（1376）
				4. Branch-Prediction Schemes（分支预测方案）（1376）
				5. The Development of Multiple-Issue Processors（多问题处理器的发展）（1376）
				6. Compiler Technology and Hardware Support for Scheduling（编译器技术和硬件对调度的支持）（1379）
				7. EPIC and the IA-64 Development（EPIC  和  IA‑64  开发）（1380）
				8. Studies of ILP and Ideas to Increase ILP（ILP研究及提高ILP的思路）（1380）
				9. Going Beyond the Data Flow Limit（超越数据流限制）（1381）
				10. Recent Advanced Microprocessors（最近的先进微处理器）（1382）
				11. Multithreading and Simultaneous Multithreading（多线程和同时多线程）（1382）
			6. The Development of SIMD Supercomputers, Vector Computers, Multimedia SIMD Instruction Extensions, and Graphical Processor Units (Chapter 4)（SIMD 超级计算机、矢量计算机、多媒体 SIMD 指令扩展和图形处理器单元的发展（第 4 章））（1392）
				1. SIMD Supercomputers（SIMD超级计算机）（1392）
				2. Vector Computers（矢量计算机）（1394）
				3. Multimedia SIMD Instruction Extensions（多媒体  SIMD  指令扩展）（1396）
				4. Graphical Processor Units（图形处理器单元）（1397）
				5. Scalable GPUs（可扩展  GPU）（1398）
				6. Graphics Pipelines（图形管道）（1398）
				7. GPGPU: An Intermediate Step（GPGPU：中间步骤）（1399）
				8. GPU Computing（GPU计算）（1399）
			7. The History of Multiprocessors and Parallel Processing (Chapter 5 and Appendices F, G, and I)（多处理器和并行处理的历史（第 5 章和附录 F、G 和 I））（1402）
				1. SIMD Computers: Attractive Idea, Many Attempts, No Lasting Successes（SIMD 计算机：有吸引力的想法，多次尝试，但没有持久的成功）（1402）
				2. Other Early Experiments（其他早期实验）（1404）
				3. Great Debates in Parallel Processing（并行处理中的大争论）（1404）
				4. More Recent Advances and Developments（最近的进展和发展）（1406）
					1. The Development of Bus-Based Coherent Multiprocessors（基于总线的相干多处理器的发展）（1406）
				5. Toward Large-Scale Multiprocessors（迈向大规模多处理器）（1407）
				6. Clusters（集群）（1409）
					1. Recent Trends in Large-Scale Multiprocessors（大规模多处理器的最新趋势）（1410）
					2. Developments in Synchronization and Consistency Models（同步和一致性模型的发展）（1411）
				7. Other References（其他参考资料）（1412）
			8. The Development of Clusters (Chapter 6)（集群的发展（第6  章））（1421）
				1. Clusters, the Forerunner of WSCs（集群，WSC的先驱）（1421）
				2. Utility Computing, the Forerunner of Cloud Computing（效用计算，云计算的先驱）（1422）
				3. Containers（集装箱）（1423）
			9. Historical Perspectives and References（历史观点和参考）（1426）
			10. The History of Magnetic Storage, RAID, and I/O Buses (Appendix D)（磁性存储、RAID 和 I/O 总线的历史（附录 D））（1431）
				1. Magnetic Storage（磁存储）（1432）
				2. RAID（1433）
				3. I/O Buses and Controllers（I/O  总线和控制器）（1435）
	5. MODERN OPERATING SYSTEMS（现代操作系统）
		1. INTRODUCTION（介绍）（33）
			1. WHAT IS AN OPERATING SYSTEM?（什么是操作系统？）（35）
				1. The Operating System as an Extended Machine（操作系统作为扩展机器）（36）
				2. The Operating System as a Resource Manager（操作系统作为资源管理器）（37）
			2. HISTORY OF OPERATING SYSTEMS（操作系统的历史）（38）
				1. The First Generation (1945–55): Vacuum Tubes（第一代（1945‑55）：真空管）（39）
				2. The Second Generation (1955–65): Transistors and Batch Systems（第二代（1955‑65）：晶体管和批处理系统）（40）
				3. The Third Generation (1965–1980): ICs and Multiprogramming（第三代（1965‑1980）：IC  和多道程序设计）（41）
				4. The Fourth Generation (1980–Present): Personal Computers（第四代（1980年至今）：个人计算机）（47）
				5. The Fifth Generation (1990–Present): Mobile Computers（第五代（1990年至今）：移动数据终端）（51）
			3. COMPUTER HARDWARE REVIEW（计算机硬件回顾）（52）
				1. Processors（处理器）（53）
					1. Multithreaded and Multicore Chips（多线程和多核芯片）（55）
				2. Memory（内存）（56）
				3. Disks（磁盘）（59）
				4. I/O Devices（输入/输出设备）（60）
				5. Buses（公交车）（64）
				6. Booting the Computer（启动计算机）（66）
			4. THE OPERATING SYSTEM ZOO（操作系统动物园）（67）
				1. Mainframe Operating Systems（大型机操作系统）（67）
				2. Server Operating Systems（服务器操作系统）（67）
				3. Multiprocessor Operating Systems（多处理器操作系统）（68）
				4. Personal Computer Operating Systems（个人计算机操作系统）（68）
				5. Handheld Computer Operating Systems（手持计算机操作系统）（68）
				6. Embedded Operating Systems（嵌入式操作系统）（69）
				7. Sensor-Node Operating Systems（传感器节点操作系统）（69）
				8. Real-Time Operating Systems（实时操作系统）（69）
				9. Smart Card Operating Systems（智能卡操作系统）（70）
			5. OPERATING SYSTEM CONCEPTS（操作系统概念）（70）
				1. Processes（流程）（71）
				2. Address Spaces（地址空间）（73）
				3. Files（文件）（73）
				4. Input/Output（输入/输出）（77）
				5. Protection（保护）（77）
				6. The Shell（外壳）（77）
				7. Ontogeny Recapitulates Phylogeny（个体发育概括系统发育）（79）
					1. Large Memories（丰富的回忆）（80）
					2. Protection Hardware（保护硬件）（80）
					3. Disks（磁盘）（81）
					4. Virtual Memory（虚拟内存）（82）
			6. SYSTEM CALLS（系统调用）（82）
				1. System Calls for Process Management（进程管理的系统调用）（85）
				2. System Calls for File Management（文件管理的系统调用）（88）
				3. System Calls for Directory Management（目录管理的系统调用）（89）
				4. Miscellaneous System Calls（各种系统调用）（91）
				5. The Windows Win32 API（92）
			7. OPERATING SYSTEM STRUCTURE（操作系统结构）（94）
				1. Monolithic Systems（单体系统）（95）
				2. Layered Systems（分层系统）（96）
				3. Microkernels（微内核）（97）
				4. Client-Server Model（客户端‑服务器模型）（100）
				5. Virtual Machines（虚拟机）（101）
					1. VM/370（101）
					2. Virtual Machines Rediscovered（重新发现虚拟机）（102）
					3. The Jav a Virtual Machine（Java  虚拟机）（104）
				6. Exokernels（外核）（105）
			8. THE WORLD ACCORDING TO C（C  的世界）（105）
				1. The C Language（C语言）（105）
				2. Header Files（头文件）（106）
				3. Large Programming Projects（大型编程项目）（107）
				4. The Model of Run Time（运行时模型）（108）
			9. RESEARCH ON OPERATING SYSTEMS（操作系统研究）（109）
			10. OUTLINE OF THE REST OF THIS BOOK（本书其余部分的概述）（110）
			11. METRIC UNITS（公制单位）（111）
			12. SUMMARY（总结）（112）
		2. PROCESSES AND THREADS（进程和线程）（117）
			1. PROCESSES（流程）（117）
				1. The Process Model（过程模型）（118）
				2. Process Creation（流程创建）（120）
				3. Process Termination（进程终止）（122）
				4. Process Hierarchies（流程层次结构）（123）
				5. Process States（进程状态）（124）
				6. Implementation of Processes（流程的实施）（126）
				7. Modeling Multiprogramming（多道程序设计建模）（127）
			2. THREADS（线程）（129）
				1. Thread Usage（线程使用）（129）
				2. The Classical Thread Model（经典线程模型）（134）
				3. POSIX Threads（POSIX  线程）（138）
				4. Implementing Threads in User Space（在用户空间实现线程）（140）
				5. Implementing Threads in the Kernel（在内核中实现线程）（143）
				6. Hybrid Implementations（混合实现）（144）
				7. Scheduler Activations（调度程序激活）（145）
				8. Pop-Up Threads（弹出线程）（146）
				9. Making Single-Threaded Code Multithreaded（将单线程代码变成多线程）（148）
			3. INTERPROCESS COMMUNICATION（进程间通信）（151）
				1. Race Conditions（竞争条件）（151）
				2. Critical Regions（关键区域）（153）
				3. Mutual Exclusion with Busy Waiting（忙等待互斥）（154）
					1. Disabling Interrupts（禁用中断）（154）
					2. Lock Variables（锁定变量）（155）
					3. Strict Alternation（严格交替）（155）
					4. Peterson’s Solution（彼得森的解决方案）（156）
					5. The TSL Instruction（TSL指令）（158）
				4. Sleep and Wakeup（睡眠和唤醒）（159）
					1. The Producer-Consumer Problem（生产者‑消费者问题）（160）
				5. Semaphores（信号量）（162）
					1. Solving the Producer-Consumer Problem Using Semaphores（使用信号量解决生产者‑消费者问题）（162）
				6. Mutexes（互斥体）（164）
					1. Futexes（166）
					2. Mutexes in Pthreads（Pthread  中的互斥体）（167）
				7. Monitors（监视器）（169）
				8. Message Passing（消息传递）（176）
					1. Design Issues for Message-Passing Systems（消息传递系统的设计问题）（176）
					2. The Producer-Consumer Problem with Message Passing（消息传递的生产者‑消费者问题）（177）
				9. Barriers（障碍）（178）
				10. Avoiding Locks: Read-Copy-Update（避免锁：读‑复制‑更新）（180）
			4. SCHEDULING（调度）（181）
				1. Introduction to Scheduling（调度简介）（182）
					1. Process Behavior（进程行为）（183）
					2. When to Schedule（何时安排）（184）
					3. Categories of Scheduling Algorithms（调度算法分类）（185）
					4. Scheduling Algorithm Goals（调度算法目标）（186）
				2. Scheduling in Batch Systems（批处理系统中的调度）（188）
					1. First-Come, First-Served（先到先得）（188）
					2. Shortest Job First（最短工作优先）（189）
					3. Shortest Remaining Time Next（下一个剩余时间最短）（190）
				3. Scheduling in Interactive Systems（交互式系统中的调度）（190）
					1. Round-Robin Scheduling（循环调度）（190）
					2. Priority Scheduling（优先级调度）（191）
					3. Multiple Queues（多个队列）（193）
					4. Shortest Process Next（最短流程  接下来）（194）
					5. Guaranteed Scheduling（保证调度）（194）
					6. Lottery Scheduling（彩票安排）（195）
					7. Fair-Share Scheduling（公平份额调度）（195）
				4. Scheduling in Real-Time Systems（实时系统中的调度）（196）
				5. Policy Versus Mechanism（政策与机制）（197）
				6. Thread Scheduling（线程调度）（198）
			5. CLASSICAL IPC PROBLEMS（经典IPC问题）（199）
				1. The Dining Philosophers Problem（哲学家就餐问题）（199）
				2. The Readers and Writers Problem（读者和作者问题）（203）
			6. RESEARCH ON PROCESSES AND THREADS（进程和线程的研究）（204）
			7. SUMMARY（总结）（205）
		3. MEMORY MANAGEMENT（内存管理）（213）
			1. NO MEMORY ABSTRACTION（无内存抽象）（214）
				1. Running Multiple Programs Without a Memory Abstraction（在没有内存抽象的情况下运行多个程序）（215）
			2. A MEMORY ABSTRACTION: ADDRESS SPACES（存储器抽象：地址空间）（217）
				1. The Notion of an Address Space（地址空间的概念）（218）
					1. Base and Limit Registers（基址和限制寄存器）（218）
				2. Swapping（交换）（219）
				3. Managing Free Memory（管理空闲内存）（222）
					1. Memory Management with Bitmaps（位图内存管理）（223）
					2. Memory Management with Linked Lists（使用链表进行内存管理）（224）
			3. VIRTUAL MEMORY（虚拟内存）（226）
				1. Paging（分页）（227）
				2. Page Tables（页表）（230）
					1. Structure of a Page Table Entry（页表项的结构）（231）
				3. Speeding Up Paging（加速分页）（233）
					1. Translation Lookaside Buffers（翻译后备缓冲区）（234）
					2. Software TLB Management（软件TLB管理）（235）
				4. Page Tables for Large Memories（大内存的页表）（237）
					1. Multilevel Page Tables（多级页表）（237）
					2. Inverted Page Tables（倒排页表）（239）
			4. PAGE REPLACEMENT ALGORITHMS（页面替换算法）（241）
				1. The Optimal Page Replacement Algorithm（最优页面替换算法）（241）
				2. The Not Recently Used Page Replacement Algorithm（最近未使用的页面替换算法）（242）
				3. The First-In, First-Out (FIFO) Page Replacement Algorithm（先进先出（FIFO）页面替换算法）（243）
				4. The Second-Chance Page Replacement Algorithm（第二次机会页面替换算法）（244）
				5. The Clock Page Replacement Algorithm（时钟页面替换算法）（244）
				6. The Least Recently Used (LRU) Page Replacement Algorithm（最近最少使用（LRU）页面替换算法）（245）
				7. Simulating LRU in Software（用软件模拟LRU）（246）
				8. The Working Set Page Replacement Algorithm（工作集页面替换算法）（247）
				9. The WSClock Page Replacement Algorithm（WSClock页面替换算法）（251）
				10. Summary of Page Replacement Algorithms（页面替换算法总结）（253）
			5. DESIGN ISSUES FOR PAGING SYSTEMS（寻呼系统的设计问题）（254）
				1. Local versus Global Allocation Policies（本地分配策略与全局分配策略）（254）
				2. Load Control（负载控制）（257）
				3. Page Size（页面大小）（257）
				4. Separate Instruction and Data Spaces（独立的指令和数据空间）（259）
				5. Shared Pages（共享页）（260）
				6. Shared Libraries（共享库）（261）
				7. Mapped Files（映射文件）（263）
				8. Cleaning Policy（清洁政策）（264） 
				9. Virtual Memory Interface（虚拟内存接口）（264）
			6. IMPLEMENTATION ISSUES（实施问题）（265）
				1. Operating System Involvement with Paging（操作系统与分页的关系）（265）
				2. Page Fault Handling（页面错误处理）（266）
				3. Instruction Backup（指令备份）（267）
				4. Locking Pages in Memory（锁定内存中的页面）（269）
				5. Backing Store（后备存储）（269）
				6. Separation of Policy and Mechanism（政策与机制分离）（271）
			7. SEGMENTATION（细分）（272）
				1. Implementation of Pure Segmentation（纯分割的实现）（275）
				2. Segmentation with Paging: MULTICS（分页分段：MULTICS）（275）
				3. Segmentation with Paging: The Intel x86（分段与分页：Intel  x86）（279）
			8. RESEARCH ON MEMORY MANAGEMENT（内存管理研究）（284）
			9. SUMMARY（总结）（285）
		4. FILE SYSTEMS（文件系统）（295）
			1. FILES（文件）（297）
				1. File Naming（文件命名）（297）
				2. File Structure（文件结构）（299）
				3. File Types（文件类型）（300）
				4. File Access（文件访问）（302）
				5. File Attributes（文件属性）（303）
				6. File Operations（文件操作）（304）
				7. An Example Program Using File-System Calls（使用文件系统调用的示例程序）（305）
			2. DIRECTORIES（目录）（308）
				1. Single-Level Directory Systems（单级目录系统）（308）
				2. Hierarchical Directory Systems（分层目录系统）（308）
				3. Path Names（路径名）（309）
				4. Directory Operations（目录操作）（312）
			3. FILE-SYSTEM IMPLEMENTATION（文件系统实现）（313）
				1. File-System Layout（文件系统布局）（313）
				2. Implementing Files（实现文件）（314）
					1. Contiguous Allocation（连续分配）（314）
					2. Linked-List Allocation（链表分配）（316）
					3. Linked-List Allocation Using a Table in Memory（使用内存中的表进行链表分配）（317）
					4. I-nodes（I节点）（318）
				3. Implementing Directories（实施目录）（320）
				4. Shared Files（共享文件）（322）
				5. Log-Structured File Systems（日志结构文件系统）（325）
				6. Journaling File Systems（日志文件系统）（327）
				7. Virtual File Systems（虚拟文件系统）（328）
			4. FILE-SYSTEM MANAGEMENT AND OPTIMIZATION（文件系统管理和优化）（331）
				1. Disk-Space Management（磁盘空间管理）（332）
					1. Block Size（块大小）（332）
					2. Keeping Track of Free Blocks（跟踪空闲块）（335）
					3. Disk Quotas（磁盘配额）（337）
				2. File-System Backups（文件系统备份）（338）
				3. File-System Consistency（文件系统一致性）（344）
				4. File-System Performance（文件系统性能）（346）
					1. Caching（缓存）（347）
					2. Block Read Ahead（块预读）（349）
					3. Reducing Disk-Arm Motion（减少磁盘臂运动）（350）
				5. Defragmenting Disks（磁盘碎片整理）（351）
			5. EXAMPLE FILE SYSTEMS（文件系统示例）（352）
				1. The MS-DOS File System（MS‑DOS  文件系统）（352）
				2. The UNIX V7 File System（UNIX  V7  文件系统）（355）
				3. CD-ROM File Systems（CD‑ROM  文件系统）（357）
					1. The ISO 9660 File System（ISO  9660  文件系统）（358）
					2. Rock Ridge Extensions（岩脊延伸）（361）
					3. Joliet Extensions（乔利埃特扩展）（362）
			6. RESEARCH ON FILE SYSTEMS（文件系统研究）（363）
			7. SUMMARY（总结）（364）
		5. INPUT/OUTPUT（输入输出）（369）
			1. PRINCIPLES OF I/O HARDWARE（I/O硬件原理）（369）
				1. I/O Devices（I/O  设备）（370）
				2. Device Controllers（设备控制器）（371）
				3. Memory-Mapped I/O（内存映射  I/O）（372）
				4. Direct Memory Access（直接内存访问）（376）
				5. Interrupts Revisited（回顾中断）（379）
					1. Precise and Imprecise Interrupts（精确和不精确中断）（381）
			2. PRINCIPLES OF I/O SOFTWARE（I/O  软件原理）（383）
				1. Goals of the I/O Software（I/O  软件的目标）（383）
				2. Programmed I/O（编程  I/O）（384）
				3. Interrupt-Driven I/O（中断驱动  I/O）（386）
				4. I/O Using DMA（使用  DMA  的  I/O）（387）
			3. I/O SOFTWARE LAYERS（I/O  软件层）（388）
				1. Interrupt Handlers（中断处理程序）（388）
				2. Device Drivers（设备驱动程序）（389）
				3. Device-Independent I/O Software（设备无关的  I/O  软件）（393）
					1. Uniform Interfacing for Device Drivers（设备驱动程序的统一接口）（394）
					2. Buffering（缓冲）（395）
					3. Error Reporting（错误报告）（398）
					4. Allocating and Releasing Dedicated Devices（分配和释放专用设备）（398）
					5. Device-Independent Block Size（与设备无关的块大小）（399）
				4. User-Space I/O Software（用户空间  I/O  软件）（399）
			4. DISKS（磁盘）（401）
				1. Disk Hardware（磁盘硬件）（401）
					1. Magnetic Disks（磁盘）（401）
					2. RAID（403）
				2. Disk Formatting（磁盘格式化）（407）
				3. Disk Arm Scheduling Algorithms（磁盘臂调度算法）（411）
				4. Error Handling（错误处理）（414）
				5. Stable Storage（稳定存储）（417）
			5. CLOCKS（时钟）（420）
				1. Clock Hardware（时钟硬件）（420）
				2. Clock Software（时钟软件）（422）
				3. Soft Timers（软定时器）（424）
			6. USER INTERFACES: KEYBOARD, MOUSE, MONITOR（用户界面：键盘、鼠标、显示器）（426）
				1. Input Software（输入软件）（426）
					1. Keyboard Software（键盘软件）（426）
					2. Mouse Software（鼠标软件）（430）
				2. Output Software（输出软件）（431）
					1. Text Windows（文本窗口）（431）
					2. The X Window System（X  窗口系统）（433）
					3. Graphical User Interfaces（图形用户界面）（437）
					4. Bitmaps（位图）（443）
					5. Fonts（字体）（445）
					6. Touch Screens（触摸屏）（446）
			7. THIN CLIENTS（瘦客户端）（448）
			8. POWER MANAGEMENT（电源管理）（449）
				1. Hardware Issues（硬件问题）（450）
				2. Operating System Issues（操作系统问题）（451）
					1. The Display（显示器）（452）
					2. The Hard Disk（硬盘）（452）
					3. The CPU（中央处理器）（453）
					4. The Memory（记忆）（455）
					5. Wireless Communication（无线通信）（455）
					6. Thermal Management（热管理）（456）
					7. Battery Management（电池管理）（456）
					8. Driver Interface（驱动接口）（457）
				3. Application Program Issues（应用程序问题）（457）
			9. RESEARCH ON INPUT/OUTPUT（输入/输出研究）（458）
			10. SUMMARY（总结）（460）
		6. DEADLOCKS（僵局）（467）
			1. RESOURCES（资源）（468）
				1. Preemptable and Nonpreemptable Resources（可抢占和不可抢占资源）（468）
				2. Resource Acquisition（资源获取）（469）
			2. INTRODUCTION TO DEADLOCKS（死锁简介）（471）
				1. Conditions for Resource Deadlocks（资源死锁的条件）（472）
				2. Deadlock Modeling（死锁建模）（472）
			3. THE OSTRICH ALGORITHM（鸵鸟算法）（475）
			4. DEADLOCK DETECTION AND RECOVERY（死锁检测和恢复）（475）
				1. Deadlock Detection with One Resource of Each Type（每种类型一个资源的死锁检测）（476）
				2. Deadlock Detection with Multiple Resources of Each Type（每种类型的多个资源的死锁检测）（478）
				3. Recovery from Deadlock（死锁恢复）（481）
					1. Recovery through Preemption（通过抢占恢复）（481）
					2. Recovery through Rollback（通过回滚恢复）（481）
					3. Recovery through Killing Processes（通过杀戮过程恢复）（482）
			5. DEADLOCK AV OIDANCE（避免死锁）（482）
				1. Resource Trajectories（资源轨迹）（482）
				2. Safe and Unsafe States（安全和不安全状态）（484）
				3. The Banker’s Algorithm for a Single Resource（单一资源的银行家算法）（485）
				4. The Banker’s Algorithm for Multiple Resources（多种资源的银行家算法）（486）
			6. DEADLOCK PREVENTION（死锁预防）（488）
				1. Attacking the Mutual-Exclusion Condition（攻击互斥条件）（488）
				2. Attacking the Hold-and-Wait Condition（攻击保持等待条件）（488）
				3. Attacking the No-Preemption Condition（攻击无抢占条件）（489）
				4. Attacking the Circular Wait Condition（攻击循环等待条件）（489）
			7. OTHER ISSUES（其他问题）（490）
				1. Two-Phase Locking（两相锁定）（491）
				2. Communication Deadlocks（通信死锁）（491）
				3. Livelock（活锁）（493）
				4. Starvation（饥饿）（495）
			8. RESEARCH ON DEADLOCKS（僵局研究）（496）
			9. SUMMARY（总结）（496）
		7. VIRTUALIZATION AND THE CLOUD（虚拟化和云）（503）
			1. HISTORY（历史）（505）
			2. REQUIREMENTS FOR VIRTUALIZATION（虚拟化要求）（506）
			3. TYPE 1 AND TYPE 2 HYPERVISORS（类型  1  和类型  2  管理程序）（509）
			4. TECHNIQUES FOR EFFICIENT VIRTUALIZATION（高效虚拟化技术）（510）
				1. Virtualizing the Unvirtualizable（虚拟化不可虚拟化）（511）
				2. The Cost of Virtualization（虚拟化的成本）（514）
			5. ARE HYPERVISORS MICROKERNELS DONE RIGHT?（管理程序微内核做得正确吗？）（515）
			6. MEMORY VIRTUALIZATION（内存虚拟化）（518）
				1. Hardware Support for Nested Page Tables（嵌套页表的硬件支持）（520）
				2. Reclaiming Memory（回收记忆）（520）
			7. I/O VIRTUALIZATION（I/O  虚拟化）（522）
				1. I/O MMUs（522）
				2. Device Domains（设备域）（524）
				3. Single Root I/O Virtualization（单根  I/O  虚拟化）（524）
			8. VIRTUAL APPLIANCES（虚拟设备）（525）
			9. VIRTUAL MACHINES ON MULTICORE CPUS（多核  CPU  上的虚拟机）（526）
			10. LICENSING ISSUES（许可问题）（526）
			11. CLOUDS（云）（527）
				1. Clouds as a Service（云即服务）（528）
				2. Virtual Machine Migration（虚拟机迁移）（528）
				3. Checkpointing（检查点）（529）
			12. CASE STUDY: VMWARE（案例研究：VMWARE）（530）
				1. The Early History of VMware（VMware  的早期历史）（530）
				2. VMware Workstation（VMware  工作站）（531）
				3. Challenges in Bringing Virtualization to the x86（将虚拟化引入  x86  的挑战）（532）
				4. VMware Workstation: Solution Overview（VMware  Workstation：解决方案概述）（534）
					1. Virtualizing the x86 Architecture（虚拟化  x86  架构）（534）
					2. A Guest Operating System Centric Strategy（以客户操作系统为中心的策略）（537）
					3. The Virtual Hardware Platform（虚拟硬件平台）（538）
					4. The Role of the Host Operating System（主机操作系统的作用）（540）
				5. The Evolution of VMware Workstation（VMware  Workstation  的演变）（543）
				6. ESX Server: VMware’s type 1 Hypervisor（ESX  Server：VMware  的  1  类虚拟机管理程序）（544）
			13. RESEARCH ON VIRTUALIZATION AND THE CLOUD（虚拟化和云研究）（546）
		8. MULTIPLE PROCESSOR SYSTEMS（多处理器系统）（549）
			1. MULTIPROCESSORS（多处理器）（552）
				1. Multiprocessor Hardware（多处理器硬件）（552）
					1. UMA Multiprocessors with Bus-Based Architectures（具有基于总线架构的  UMA  多处理器）（552）
					2. UMA Multiprocessors Using Crossbar Switches（使用交叉开关的  UMA  多处理器）（553）
					3. UMA Multiprocessors Using Multistage Switching Networks（使用多级交换网络的  UMA  多处理器）（555）
					4. NUMA Multiprocessors（NUMA  多处理器）（557）
					5. Multicore Chips（多核芯片）（559）
					6. Manycore Chips（众核芯片）（560）
					7. Heterogeneous Multicores（异构多核）（561）
					8. Programming with Multiple Cores（多核编程）（562）
				2. Multiprocessor Operating System Types（多处理器操作系统类型）（563）
					1. Each CPU Has Its Own Operating System（每个CPU都有自己的操作系统）（563）
					2. Master-Slave Multiprocessors（主从多处理器）（564）
					3. Symmetric Multiprocessors（对称多处理器）（565）
				3. Multiprocessor Synchronization（多处理器同步）（566）
					1. Spinning vs. Switching（旋转与切换）（569）
				4. Multiprocessor Scheduling（多处理器调度）（571）
					1. Time Sharing（分时）（572）
					2. Space Sharing（空间共享）（574）
					3. Gang Scheduling（帮派调度）（575）
			2. MULTICOMPUTERS（多计算机）（577）
				1. Multicomputer Hardware（多计算机硬件）（578）
					1. Interconnection Technology（互连技术）（578）
					2. Network Interfaces（网络接口）（580）
				2. Low-Level Communication Software（底层通信软件）（582）
					1. Node-to-Network Interface Communication（节点到网络接口通信）（583）
					2. Remote Direct Memory Access（远程直接内存访问）（584）
				3. User-Level Communication Software（用户级通信软件）（585）
					1. Send and Receive（发送和接收）（585）
					2. Blocking versus Nonblocking Calls（阻塞调用与非阻塞调用）（585）
				4. Remote Procedure Call（远程过程调用）（588）
					1. Implementation Issues（实施问题）（589）
				5. Distributed Shared Memory（分布式共享内存）（590）
					1. Replication（复制）（593）
					2. False Sharing（虚假分享）（593）
					3. Achieving Sequential Consistency（实现顺序一致性）（594）
				6. Multicomputer Scheduling（多机调度）（595）
				7. Load Balancing（负载均衡）（595）
					1. A Graph-Theoretic Deterministic Algorithm（图论确定性算法）（596）
					2. A Sender-Initiated Distributed Heuristic Algorithm（发送者发起的分布式启发式算法）（597）
					3. A Receiver-Initiated Distributed Heuristic Algorithm（接收者发起的分布式启发式算法）（598）
			3. DISTRIBUTED SYSTEMS（分布式系统）（598）
				1. Network Hardware（网络硬件）（600）
					1. Ethernet（以太网）（601）
					2. The Internet（互联网）（603）
				2. Network Services and Protocols（网络服务和协议）（604）
					1. Network Services（网络服务）（604）
					2. Network Protocols（网络协议）（606）
				3. Document-Based Middleware（基于文档的中间件）（608）
				4. File-System-Based Middleware（基于文件系统的中间件）（609）
					1. Transfer Model（转移模型）（609）
					2. The Directory Hierarchy（目录层次结构）（610）
					3. Naming Transparency（命名透明度）（611）
					4. Semantics of File Sharing（文件共享的语义）（612）
				5. Object-Based Middleware（基于对象的中间件）（614）
				6. Coordination-Based Middleware（基于协调的中间件）（616）
					1. Publish/Subscribe（发布/订阅）（618）
			4. RESEARCH ON MULTIPLE PROCESSOR SYSTEMS（多处理器系统的研究）（619）
			5. SUMMARY（总结）（620）
		9. SECURITY（安全）（625）
			1. THE SECURITY ENVIRONMENT（安全环境）（627）
				1. Threats（威胁）（628）
				2. Attackers（攻击者）（631）
			2. OPERATING SYSTEMS SECURITY（操作系统安全）（631）
				1. Can We Build Secure Systems?（我们可以构建安全的系统吗？）（632）
				2. Trusted Computing Base（可信计算库）（633）
			3. CONTROLLING ACCESS TO RESOURCES（控制对资源的访问）（634）
				1. Protection Domains（保护域）（635）
				2. Access Control Lists（访问控制列表）（637）
				3. Capabilities（能力）（640）
			4. FORMAL MODELS OF SECURE SYSTEMS（安全系统的形式模型）（643）
				1. Multilevel Security（多级安全）（644）
					1. The Bell-LaPadula Model（贝尔‑拉帕杜拉模型）（645）
					2. The Biba Model（比巴模型）（646）
				2. Covert Channels（隐蔽通道）（647）
					1. Steganography（隐写术）（649）
			5. BASICS OF CRYPTOGRAPHY（密码学基础）（651）
				1. Secret-Key Cryptography（秘密密钥密码术）（652）
				2. Public-Key Cryptography（公钥密码术）（653）
				3. One-Way Functions（单向函数）（654）
				4. Digital Signatures（数字签名）（655）
				5. Trusted Platform Modules（可信平台模块）（656）
			6. AUTHENTICATION（认证）（658）
				1. Weak Passwords（弱密码）（662）
				2. UNIX Password Security（UNIX  密码安全）（662）
				3. One-Time Passwords（一次性密码）（663）
				4. Challenge-Response Authentication（质询‑响应认证）（664）
				5. Authentication Using a Physical Object（使用物理对象进行身份验证）（665）
				6. Authentication Using Biometrics（使用生物识别技术进行身份验证）（668）
			7. EXPLOITING SOFTWARE（利用软件）（671）
				1. Buffer Overflow Attacks（缓冲区溢出攻击）（672）
					1. Stack Canaries（堆栈金丝雀）（674）
					2. Av oiding Stack Canaries（避免堆栈金丝雀）（675）
					3. Data Execution Prev ention（数据执行保护）（676）
					4. Code Reuse Attacks（代码重用攻击）（677）
					5. Address-Space Layout Randomization（地址空间布局随机化）（679）
					6. Bypassing ASLR（绕过ASLR）（679）
					7. Noncontrol-Flow Diverting Attacks（非控制流转移攻击）（680）
					8. Buffer Overflows—The Not So Final Word（缓冲区溢出）（681）
				2. Format String Attacks（格式化字符串攻击）（681）
				3. Dangling Pointers（悬空指针）（684）
				4. Null Pointer Dereference Attacks（空指针解引用攻击）（685）
				5. Integer Overflow Attacks（整数溢出攻击）（686）
				6. Command Injection Attacks（命令注入攻击）（687）
				7. Time of Check to Time of Use Attacks（检查时间到使用时间攻击）（688）
			8. INSIDER ATTA CKS（内部攻击）（689）
				1. Logic Bombs（逻辑炸弹）（689）
				2. Back Doors（后门）（690）
				3. Login Spoofing（登录欺骗）（691）
			9. MALWARE（恶意软件）（692）
				1. Trojan Horses（特洛伊木马）（695）
				2. Viruses（病毒）（696）
					1. How Viruses Work（病毒如何工作）（697）
					2. Companion Viruses（伴随病毒）（697）
					3. Executable Program Viruses（可执行程序病毒）（698）
					4. Memory-Resident Viruses（内存驻留病毒）（701）
					5. Boot Sector Viruses（引导扇区病毒）（701）
					6. Device Driver Viruses（设备驱动程序病毒）（703）
					7. Macro Viruses（宏病毒）（703）
					8. Source Code Viruses（源代码病毒）（704）
					9. How Viruses Spread（病毒如何传播）（704）
				3. Worms（蠕虫）（706）
				4. Spyware（间谍软件）（708）
					1. How Spyware Spreads（间谍软件如何传播）（709）
					2. Actions Taken by Spyware（间谍软件采取的行动）（711）
				5. Rootkits（712）
					1. Types of Rootkits（Rootkit  的类型）（712）
					2. Rootkit Detection（Rootkit检测）（713）
					3. The Sony Rootkit（索尼  Rootkit）（715）
			10. DEFENSES（防御）（716）
				1. Firewalls（防火墙）（717）
				2. Antivirus and Anti-Antivirus Techniques（防病毒和反防病毒技术）（719）
					1. Virus Scanners（病毒扫描仪）（719）
					2. Integrity Checkers（完整性检查器）（723）
					3. Behavioral Checkers（行为检查器）（723）
					4. Virus Avoidance（避免病毒）（724）
				3. Code Signing（代码签名）（725）
				4. Jailing（监禁）（726）
				5. Model-Based Intrusion Detection（基于模型的入侵检测）（727）
				6. Encapsulating Mobile Code（封装移动代码）（729）
					1. Sandboxing（沙盒）（730）
					2. Interpretation（解释）（732）
				7. Jav a Security（Java  安全）（733）
			11. RESEARCH ON SECURITY（安全研究）（735）
			12. SUMMARY（小结）（736）
		10. CASE STUDY 1: UNIX, LINUX, AND ANDROID（案例研究 1：UNIX、Linux 和 ANDROID）（745）
			1. HISTORY OF UNIX AND LINUX（UNIX  和  Linux  的历史）（746）
				1. UNICS（746）
				2. PDP-11 UNIX（747）
				3. Portable UNIX（便携式  UNIX）（748）
				4. Berkeley UNIX（伯克利UNIX）（749）
				5. Standard UNIX（标准  UNIX）（750）
				6. MINIX（751）
				7. Linux（752）
			2. OVERVIEW OF LINUX（Linux  概述）（755）
				1. Linux Goals（Linux  目标）（755）
				2. Interfaces to Linux（Linux  接口）（756）
				3. The Shell（外壳）（758）
				4. Linux Utility Programs（Linux  实用程序）（761）
				5. Kernel Structure（内核结构）（763）
			3. PROCESSES IN LINUX（Linux  中的进程）（765）
				1. Fundamental Concepts（基本概念）（765）
				2. Process-Management System Calls in Linux（Linux  中的进程管理系统调用）（768）
				3. Implementation of Processes and Threads in Linux（Linux中进程和线程的实现）（772）
					1. Threads in Linux（Linux  中的线程）（775）
				4. Scheduling in Linux（Linux  中的调度）（778）
					1. Synchronization in Linux（Linux  中的同步）（782）
				5. Booting Linux（引导  Linux）（783）
			4. MEMORY MANAGEMENT IN LINUX（Linux  中的内存管理）（785）
				1. Fundamental Concepts（基本概念）（786）
				2. Memory Management System Calls in Linux（Linux  中的内存管理系统调用）（788）
				3. Implementation of Memory Management in Linux（Linux内存管理的实现）（790）
					1. Physical Memory Management（物理内存管理）（790）
					2. Memory-Allocation Mechanisms（内存分配机制）（793）
					3. Virtual Address-Space Representation（虚拟地址空间表示）（795）
				4. Paging in Linux（Linux  中的分页）（796）
					1. The Page Replacement Algorithm（页面替换算法）（797）
			5. INPUT/OUTPUT IN LINUX（Linux  中的输入/输出）（799）
				1. Fundamental Concepts（基本概念）（799）
				2. Networking（网络）（801）
				3. Input/Output System Calls in Linux（Linux  中的输入/输出系统调用）（802）
				4. Implementation of Input/Output in Linux（Linux中输入/输出的实现）（803）
				5. Modules in Linux（Linux  中的模块）（806）
			6. THE LINUX FILE SYSTEM（Linux  文件系统）（807）
				1. Fundamental Concepts（基本概念）（807）
				2. File-System Calls in Linux（Linux  中的文件系统调用）（812）
				3. Implementation of the Linux File System（Linux文件系统的实现）（816）
					1. The Linux Virtual File System（Linux  虚拟文件系统）（816）
					2. The Linux Ext2 File System（Linux  Ext2  文件系统）（817）
					3. The Linux Ext4 File System（Linux  Ext4  文件系统）（822）
					4. The /proc File System（/proc  文件系统）（824）
				4. NFS: The Network File System（NFS：网络文件系统）（824）
					1. NFS Architecture（NFS架构）（824）
					2. NFS Protocols（NFS  协议）（826）
					3. NFS Implementation（NFS  实施）（827）
					4. NFS Version 4（NFS  版本  4）（830）
			7. SECURITY IN LINUX（Linux  中的安全性）（830）
				1. Fundamental Concepts（基本概念）（830）
				2. Security System Calls in Linu（Linux  中的安全系统调用）（833）
				3. Implementation of Security in Linux（Linux  中安全性的实现）（833）
			8. ANDROID（安卓）（834）
				1. Android and Google（Android  和谷歌）（835）
				2. History of Android（Android  的历史）（836）
					1. Early Development（早期发展）（836）
					2. Android 1.0（837）
					3. Continued Development（持续发展）（838）
				3. Design Goals（设计目标）（839）
				4. Android Architecture（Android  架构）（841）
				5. Linux Extensions（Linux  扩展）（842）
					1. Wake Locks（唤醒锁）（842）
					2. Out-Of-Memory Killer（内存不足杀手）（845）
				6. Dalvik（846）
				7. Binder IPC（847）
					1. Binder Kernel Module（Binder内核模块）（848）
					2. Binder User-Space API（Binder  用户空间  API）（853）
					3. Binder Interfaces and AIDL（Binder  接口和  AIDL）（854）
				8. Android Applications（Android  应用程序）（856）
					1. Activities（活动）（859）
					2. Services（服务）（863）
					3. Receivers（接收器）（865）
					4. Content Providers（内容提供商）（866）
				9. Intents（意图）（868）
				10. Application Sandboxes（应用程序沙箱）（870）
				11. Security（安全）（870）
				12. Process Model（过程模型）（876）
					1. Starting Processes（启动进程）（877）
					2. Process Lifecycle（流程生命周期）（878）
					3. Process Dependencies（流程依赖性）（879）
			9. SUMMARY（总结）（881）
		11. CASE STUDY 2: WINDOWS 8（案例研究  2：Windows  8）（889）
			1. HISTORY OF WINDOWS THROUGH WINDOWS 8.1（WINDOWS  8.1  的历史）（889）
				1. 1980s: MS-DOS（890）
				2. 1990s: MS-DOS-based Windows（891）
				3. 2000s: NT-based Windows（891）
				4. Windows Vista（894）
				5. 2010s: Modern Windows（2010年代：现代Windows）（895）
			2. PROGRAMMING WINDOWS（编程窗口）（896）
				1. The Native NT Application Programming Interface（本机  NT  应用程序编程接口）（900）
				2. The Win32 Application Programming Interface（Win32应用程序编程接口）（903）
				3. The Windows Registry（Windows  注册表）（907）
			3. SYSTEM STRUCTURE（系统结构）（909）
				1. Operating System Structure（操作系统结构）（909）
					1. The Hardware Abstraction Layer（硬件抽象层）（912）
					2. The Kernel Layer（内核层）（914）
					3. Deferred Procedure Calls（延迟过程调用）（915）
					4. Asynchronous Procedure Calls（异步过程调用）（917）
					5. Dispatcher Objects（调度程序对象）（918）
					6. The Executive Layer（执行层）（919）
					7. The Device Drivers（设备驱动程序）（923）
				2. Booting Windows（启动Windows）（925）
				3. Implementation of the Object Manager（对象管理器的实现）（926）
					1. Handles（手柄）（929）
					2. The Object Namespace（对象命名空间）（930）
				4. Subsystems, DLLs, and User-Mode Services（子系统、DLL  和用户模式服务）（937）
			4. PROCESSES AND THREADS IN WINDOWS（Windows  中的进程和线程）（940）
				1. Fundamental Concepts（基本概念）（940）
					1. Processes（流程）（941）
					2. Jobs and Fibers（工作和纤维）（941）
					3. Thread Pools and User-Mode Scheduling（线程池和用户模式调度）（943）
					4. Threads（线程数）（945）
				2. Job, Process, Thread, and Fiber Management API Calls（作业、进程、线程和纤程管理  API  调用）（946）
					1. Interprocess Communication（进程间通信）（948）
					2. Synchronization（同步）（949）
				3. Implementation of Processes and Threads（进程和线程的实现）（951）
					1. Scheduling（调度）（954）
			5. MEMORY MANAGEMENT（内存管理）（959）
				1. Fundamental Concepts（基本概念）（960）
					1. Virtual Address Allocation（虚拟地址分配）（961）
					2. Pagefiles（页面文件）（962）
				2. Memory-Management System Calls（内存管理系统调用）（963）
				3. Implementation of Memory Management（内存管理的实现）（965）
					1. Page-Fault Handling（页面错误处理）（966）
					2. The Page Replacement Algorithm（页面替换算法）（969）
					3. Physical Memory Management（物理内存管理）（971）
			6. CACHING IN WINDOWS（Windows  中的缓存）（974）
			7. INPUT/OUTPUT IN WINDOWS（窗口中的输入/输出）（975）
				1. Fundamental Concepts（基本概念）（976）
				2. Input/Output API Calls（输入/输出  API  调用）（977）
				3. Implementation of I/O（I/O  的实现）（980）
					1. Device Drivers（设备驱动程序）（980）
					2. I/O Request Packets（I/O  请求数据包）（982）
					3. Device Stacks（设备堆栈）（983）
			8. THE WINDOWS NT FILE SYSTEM（Windows  NT  文件系统）（984）
				1. Fundamental Concepts（基本概念）（985）
				2. Implementation of the NT File System（NT文件系统的实现）（986）
					1. File System Structure（文件系统结构）（986）
					2. Storage Allocation（存储分配）（990）
					3. File Compression（文件压缩）（994）
					4. Journaling（写日记）（995）
					5. File Encryption（文件加密）（995）
			9. WINDOWS POWER MANAGEMENT（Windows  电源管理）（996）
			10. SECURITY IN WINDOWS 8（Windows  8  中的安全性）（998）
				1. Fundamental Concepts（基本概念）（999）
				2. Security API Calls（安全  API  调用）（1001）
				3. Implementation of Security（安全实施）（1002）
				4. Security Mitigations（安全缓解措施）（1005）
			11. SUMMARY（小结）（1007）
		12. OPERATING SYSTEM DESIGN（操作系统设计）（1013）
			1. THE NATURE OF THE DESIGN PROBLEM（设计问题的本质）（1014）
				1. Goals（目标）（1014）
				2. Why Is It Hard to Design an Operating System?（为什么设计一个操作系统很难？）（1015）
			2. INTERFACE DESIGN（界面设计）（1017）
				1. Guiding Principles（指导原则）（1017）
					1. Principle 1: Simplicity（原则  1：简单性）（1017）
					2. Principle 2: Completeness（原则  2：完整性）（1018）
					3. Principle 3: Efficiency（原则  3：效率）（1019）
				2. Paradigms（范式）（1019）
					1. User-Interface Paradigms（用户界面范例）（1020）
					2. Execution Paradigms（执行范式）（1021）
					3. Data Paradigms（数据范式）（1021）
				3. The System-Call Interface（系统调用接口）（1023）
			3. IMPLEMENTATION（实施）（1025）
				1. System Structure（系统结构）（1025）
					1. Layered Systems（分层系统）（1025）
					2. Exokernels（外核）（1027）
					3. Microkernel-Based Client-Server Systems（基于微内核的客户端‑服务器系统）（1027）
					4. Extensible Systems（可扩展系）（1029）
					5. Kernel Threads（内核线程）（1029）
				2. Mechanism vs. Policy（机制与政策）（1029）
				3. Orthogonalit（正交性）（1030）
				4. Naming（命名）（1031）
				5. Binding Time（绑定时间）（1033）
				6. Static vs. Dynamic Structures（静态结构与动态结构）（1034）
				7. Top-Down vs. Bottom-Up Implementation（自上而下与自下而上的实施）（1035）
				8. Synchronous vs. Asynchronous Communication（同步与异步通信）（1036）
				9. Useful Techniques（有用的技术）（1037）
					1. Hiding the Hardware（隐藏硬件）（1037）
					2. Indirection（间接）（1039）
					3. Reusability（可重复使用性）（1040）
					4. Reentrancy（可重入性）（1041）
					5. Brute Force（暴力破解）（1041）
					6. Check for Errors First（首先检查错误）（1042）
			4. PERFORMANCE（性能）（1042）
				1. Why Are Operating Systems Slow?（为什么操作系统速度慢？）（1043）
				2. What Should Be Optimized?（应该优化什么？）（1043）
				3. Space-Time Trade-offs（时空权衡）（1044）
				4. Caching（缓存）（1047）
				5. Hints（提示）（1048）
				6. Exploiting Locality（利用局部性）（1049）
				7. Optimize the Common Case（优化常见案例）（1049）
			5. PROJECT MANAGEMENT（项目管理）（1050）
				1. The Mythical Man Month（人月神话）（1050）
				2. Team Structure（团队结构）（1051）
				3. The Role of Experience（经验的作用）（1053）
				4. No Silver Bullet（没有灵丹妙药）（1054）
			6. TRENDS IN OPERATING SYSTEM DESIGN（操作系统设计趋势）（1054）
				1. Virtualization and the Cloud（虚拟化和云）（1055）
				2. Manycore Chips（众核芯片）（1055）
				3. Large-Address-Space Operating Systems（大地址空间操作系统）（1056）
				4. Seamless Data Access（无缝数据访问）（1057）
				5. Battery-Powered Computers（电池供电的计算机）（1057）
				6. Embedded Systems（嵌入式系统）（1058）
			7. SUMMARY（总结）（1059）
		13. READING LIST AND BIBLIOGRAPHY（阅读清单和参考书目）（1063）
			1. SUGGESTIONS FOR FURTHER READING（进一步阅读的建议）（1063）
				1. Introduction（简介）（1064）
				2. Processes and Threads（进程和线程）（1064）
				3. Memory Management（内存管理）（1065）
				4. File Systems（文件系统）（1065）
				5. Input/Output（输入/输出）（1066）
				6. Deadlocks（死锁）（1067）
				7. Virtualization and the Cloud（虚拟化和云）（1067）
				8. Multiple Processor Systems（多处理器系统）（1068）
				9. Security（安全）（1069）
				10. Case Study 1: UNIX, Linux, and Android（案例研究  1：UNIX、Linux  和  Android）（1071）
				11. Case Study 2: Windows 8（案例研究  2：Windows  8）（1072）
				12. Operating System Design（操作系统设计）（1072）
			2. ALPHABETICAL BIBLIOGRAPHY（按字母顺序排列的参考书目）（1073）
	6. Introduction to Algorithms Third Edition（算法导论第3版）
		1. Foundations（基础）
			1. The Role of Algorithms in Computing（算法在计算中的作用）（26）
				1. Algorithms（算法）（26）
					1. What kinds of problems are solved by algorithms?（算法解决什么类型的问题？）（27）
					2. Data structures（数据结构）（30）
					3. Technique（技术）（30）
					4. Hard problems（难题）（30）
					5. Parallelism（并行性）（31）
				2. Algorithms as a technology（算法作为一种技术）（32）
					1. Efficiency（效率）（33）
					2. Algorithms and other technologies（算法和其他技术）（34）
			2. Getting Started（入门）（37）
				1. Insertion sort（插入排序）（37）
					1. Loop invariants and the correctness of insertion sort（循环不变量和插入排序的正确性）（39）
					2. Pseudocode conventions（伪代码约定）（41）
				2. Analyzing algorithms（分析算法）（44）
					1. Analysis of insertion sort（插入排序分析）（45）
					2. Worst-case and average-case analysis（最坏情况和平均情况分析）（48）
					3. Order of growth（增长顺序）（48）
				3. Designing algorithms（设计算法）（49）
					1. The divide-and-conquer approach（分而治之的方法）（50）
					2. Analyzing divide-and-conquer algorithms（分析分治算法）（55）
						1. Analysis of merge sort（归并排序分析）（56）
			3. Growth of Functions（功能的增长）（63）
				1. Asymptotic notation（渐近符号）（63）
					1. Asymptotic notation, functions, and running times（渐近符号、函数和运行时间）（64）
					2. Θ-notation（θ 表示法）（65）
					3. O-notation（O 表示法）（67）
					4. Ω-notation（Ω 表示法）（68）
					5. Theorem 3.1（定理3.1）（68）
					6. Asymptotic notation in equations and inequalities（方程和不等式中的渐近符号）（69）
					7. o-notation（o符号）（71）
					8. ω-notation（ω符号）（71）
					9. Comparing functions（功能比较）（71）
				2. Standard notations and common functions（标准符号和常用函数）（74）
					1. Monotonicity（单调性）（74）
					2. Floors and ceilings（地板和天花板）（74）
					3. Modular arithmetic（模运算）（74）
					4. Polynomials（多项式）（74）
					5. Exponentials（指数）（75）
					6. Logarithms（对数）（76）
					7. Factorials（阶乘）（78）
					8. Functional iteration（功能迭代）（78）
					9. The iterated logarithm function（迭代对数函数）（78）
					10. Fibonacci numbers（斐波那契数列）（79）
			4. Divide-and-Conquer（分而治之）（85）
				1. Recurrences（复发）（86）
				2. Technicalities in recurrences（重复的技术细节）（87）
				3. The maximum-subarray problem（最大子数组问题）（88）
					1. A brute-force solution（暴力解决方案）（89）
					2. A transformation（一次转变）（90）
					3. A solution using divide-and-conquer（使用分而治之的解决方案）（91）
					4. Analyzing the divide-and-conquer algorithm（分析分治算法）（94）
				4. Strassen’s algorithm for matrix multiplication（Strassen 矩阵乘法算法）（96）
					1. A simple divide-and-conquer algorithm（一个简单的分治算法）（97）
					2. Strassen’s method（施特拉森法）（99）
				5. The substitution method for solving recurrences（求解递推式的代入法）（103）
					1. Making a good guess（做出一个好的猜测）（105）
					2. Subtleties（微妙之处）（105）
					3. Avoiding pitfalls（避免陷阱）（106）
					4. Changing variables（改变变量）（106）
				6. The recursion-tree method for solving recurrences（求解递归的递归树方法）（108）
				7. The master method for solving recurrences（求解递推式的主要方法）（94）
					1. Using the master method（使用主方法）（116）
				8. Proof of the master theorem（主定理的证明）（118）
					1. The proof for exact powers（确切权力的证明）（118）
					2. Floors and ceilings（地板和天花板）（123）
			5. Probabilistic Analysis and Randomized Algorithms（概率分析和随机算法）（134）
				1. The hiring problem（招聘问题）（134）
					1. Worst-case analysis（最坏情况分析）（136）
					2. Probabilistic analysis（概率分析）（136）
					3. Randomized algorithms（随机算法）（137）
				2. Indicator random variables（指标随机变量）（138）
					1. Analysis of the hiring problem using indicator random variables（使用指标随机变量分析招聘问题）（140）
				3. Randomized algorithms（随机算法）（143）
					1. Randomly permuting arrays（随机排列数组）（144）
				4. Probabilistic analysis and further uses of indicator random variables（指标随机变量的概率分析和进一步使用）（150）
					1. The birthday paradox（生日悖论）（150）
						1. An analysis using indicator random variables（使用指标随机变量的分析）（152）
					2. Balls and bins（球和垃圾箱）（153）
					3. Streaks（条纹）（155）
					4. The on-line hiring problem（网上招聘问题）（160）
		2. Sorting and Order Statistics（排序和顺序统计）（166）
			1. Heapsort（堆排序）（171）
				1. Heaps（堆）（171）
				2. Maintaining the heap property（维护堆属性）（174）
				3. Building a heap（构建堆）（177）
				4. The heapsort algorithm（堆排序算法）（180）
				5. Priority queues（优先队列）（182）
			2. Quicksort（快速排序）（190）
				1. Description of quicksort（快速排序的描述）（190）
					1. Partitioning the array（对数组进行分区）（191）
				2. Performance of quicksort（快速排序的性能）（195）
					1. Worst-case partitioning（最坏情况分区）（195）
					2. Best-case partitioning（最佳情况分区）（195）
					3. Balanced partitioning（平衡分区）（195）
					4. Intuition for the average case（一般情况下的直觉）（197）
				3. A randomized version of quicksort（快速排序的随机版本）（199）
				4. Analysis of quicksort（快速排序分析）（200）
					1. Worst-case analysis（最坏情况分析）（195）
					2. Expected running time（预计运行时间）（201）
						1. Running time and comparisons（运行时间和比较）（201）
			3. Sorting in Linear Time（线性时间排序）（211）
				1. Lower bounds for sorting（排序的下限）（211）
					1. The decision-tree model（决策树模型）（212）
					2. A lower bound for the worst case（最坏情况的下限）（213）
				2. Counting sort（计数排序）（215）
				3. Radix sort（基数排序）（217）
				4. Bucket sort（桶排序）（221）
			4. Medians and Order Statistics（中位数和顺序统计）（233）
				1. Minimum and maximum（最小值和最大值）（234）
					1. Simultaneous minimum and maximum（同时最小值和最大值）（234）
				2. Selection in expected linear time（在预期线性时间内选择）（235）
				3. Selection in worst-case linear time（最坏情况线性时间的选择）（240）
		3. Data Structures（数据结构）（250）
			1. Elementary Data Structures（基本数据结构）（252）
				1. Stacks and queues（栈和队列）（252）
					1. Stacks（堆栈）（252）
					2. Queues（队列）（254）
				2. Linked lists（链接列表）（256）
					1. Searching a linked list（搜索链接列表）（257）
					2. Inserting into a linked list（插入到链表中）（257）
					3. Deleting from a linked list（从链接列表中删除）（258）
					4. Sentinels（哨兵）（258）
				3. Implementing pointers and objects（实现指针和对象）（261）
					1. A multiple-array representation of objects（对象的多数组表示）（261）
					2. A single-array representation of objects（对象的单数组表示）（262）
					3. Allocating and freeing objects（分配和释放对象）（263）
				4. Representing rooted trees（代表有根的树）（266）
					1. Binary trees（二叉树）（266）
					2. Rooted trees with unbounded branching（树有根，枝无边）（266）
					3. Other tree representations（其他树表示）（268）
			2. Hash Tables（哈希表）（273）
				1. Direct-address tables（直接地址表）（274）
				2. Hash tables（哈希表）（276）
					1. Collision resolution by chaining（通过链接解决碰撞）（277）
					2. Analysis of hashing with chaining（链式哈希分析）（278）
				3. Hash functions（哈希函数）（282）
					1. What makes a good hash function?（什么是好的哈希函数？）（282）
					2. Interpreting keys as natural numbers（将键解释为自然数）（283）
					3. The division method（划分方法）（283）
					4. The multiplication method（乘法）（283）
					5. Universal hashing（通用散列）（285）
					6. Designing a universal class of hash functions（设计通用类哈希函数）（287）
				4. Open addressing（开放寻址）（289）
					1. Linear probing（线性探测）（292）
					2. Quadratic probing（二次探测）（292）
					3. Double hashing（双重散列）（292）
					4. Analysis of open-address hashing（开放地址哈希分析）（294）
				5. Perfect hashing（完美哈希）（298）
			3. Binary Search Trees（二叉搜索树）
				1. What is a binary search tree?（什么是二叉搜索树？）（297）
				2. Querying a binary search tree（查询二叉搜索树）（310）
					1. Searching（搜索）（310）
					2. Minimum and maximum（最小值和最大值）（311）
					3. Successor and predecessor（继任者和前任）（311）
				3. Insertion and deletion（插入和删除）（314）
					1. Insertion（插入）（314）
					2. Deletion（删除）（315）
				4. Randomly built binary search trees（随机构建二叉搜索树）（320）
			4. Red-Black Trees（红黑树）（329）
				1. Properties of red-black trees（红黑树的性质）（329）
				2. Rotations（旋转次数）（333）
				3. Insertion（插入）（335）
					1. Analysis（分析）（342）
				4. Deletion（删除）（343）
			5. Augmenting Data Structures（增强数据结构）（359）
				1. Dynamic order statistics（动态订单统计）（360）
					1. Retrieving an element with a given rank（检索具有给定排名的元素）（361）
					2. Determining the rank of an element（确定元素的等级）（362）
					3. Maintaining subtree sizes（维护子树大小）（363）
				2. How to augment a data structure（如何扩充数据结构）（366）
					1. Augmenting red-black trees（增强红黑树）（367）
				3. Interval trees（区间树）（368）
					1. Step 1: Underlying data structure（第 1 步：底层数据结构）（369）
					2. Step 2: Additional information（第 2 步：附加信息）（369）
					3. Step 3: Maintaining the information（第三步：维护信息）（369）
					4. Step 4: Developing new operations（第四步：开发新业务）（371）
		4. Advanced Design and Analysis Techniques（先进的设计和分析技术）（376）
			1. Dynamic Programming（动态规划）（379）
				1. Rod cutting（棒材切割）（380）
					1. Recursive top-down implementation（自上而下的递归实现）（383）
					2. Using dynamic programming for optimal rod cutting（使用动态规划实现最佳棒材切割）（385）
					3. Subproblem graphs（子问题图）（387）
					4. Reconstructing a solution（重建解决方案）（389）
				2. Matrix-chain multiplication（矩阵链乘法）（391）
					1. Counting the number of parenthesizations（计算括号的数量）（392）
					2. Applying dynamic programming（应用动态规划）（392）
					3. Step 1: The structure of an optimal parenthesization（步骤 1：最佳括号的结构）（393）
					4. Step 2: A recursive solution（步骤 2：递归解决方案）（394）
					5. Step 3: Computing the optimal costs（步骤 3：计算最优成本）（395）
					6. Step 4: Constructing an optimal solution（第 4 步：构建最优解决方案）（397）
				3. Elements of dynamic programming（动态规划的要素）（399）
					1. Optimal substructure（最优子结构）（400）
					2. Subtleties（微妙之处）（402）
					3. Overlapping subproblems（重叠子问题）（404）
					4. Reconstructing an optimal solution（重建最优解）（407）
					5. Memoization（记忆化）（407）
				4. Longest common subsequence（最长公共子序列）（411）
					1. Step 1: Characterizing a longest common subsequence（步骤 1：表征最长公共子序列）（412）
					2. Step 2: A recursive solution（步骤 2：递归解决方案）（414）
					3. Step 3: Computing the length of an LCS（步骤 3：计算 LCS 的长度）（414）
					4. Step 4: Constructing an LCS（第四步：建造LCS）（415）
					5. Improving the code（改进代码）（416）
				5. Optimal binary search trees（最优二叉搜索树）（417）
					1. Step 1: The structure of an optimal binary search tree（步骤一：最优二叉搜索树的结构）（420）
					2. Step 2: A recursive solution（步骤 2：递归解决方案）（420）
					3. Step 3: Computing the expected search cost of an optimal binary search tree（步骤 3：计算最优二叉搜索树的预期搜索成本）（421）
			2. Greedy Algorithms（贪心算法）（434）
				1. An activity-selection problem（活动选择问题）（435）
					1. The optimal substructure of the activity-selection problem（活动选择问题的最优子结构）（436）
					2. Making the greedy choice（做出贪婪的选择）（437）
					3. A recursive greedy algorithm（递归贪心算法）（439）
					4. An iterative greedy algorithm（迭代贪心算法）（440）
				2. Elements of the greedy strategy（贪婪策略的要素）（443）
					1. Greedy-choice property（贪心选择性质）（444）
					2. Optimal substructure（最优子结构）（445）
					3. Greedy versus dynamic programming（贪心与动态规划）（446）
				3. Huffman codes（霍夫曼码）（449）
					1. Prefix codes（前缀码）（450）
					2. Constructing a Huffman code（构建霍夫曼代码）（451）
					3. Correctness of Huffman’s algorithm（霍夫曼算法的正确性）（453）
				4. Matroids and greedy methods（拟阵和贪心方法）（457）
					1. Matroids（拟阵）（457）
					2. Greedy algorithms on a weighted matroid（加权拟阵上的贪婪算法）（459）
				5. A task-scheduling problem as a matroid（作为拟阵的任务调度问题）（464）
			3. Amortized Analysis（摊销分析）
				1. Aggregate analysis（聚合分析）（472）
					1. Stack operations（堆栈操作）（472）
					2. Incrementing a binary counter（递增二进制计数器）（474）
				2. The accounting method（会计方法）（476）
					1. Stack operations（堆栈操作）（477）
					2. Incrementing a binary counter（递增二进制计数器）（478）
				3. The potential method（潜在方法）（480）
					1. Stack operations（堆栈操作）（480）
					2. Incrementing a binary counter（递增二进制计数器）（481）
				4. Dynamic tables（动态表）（483）
					1. Table expansion（表扩展）（484）
					2. Table expansion and contraction（表的扩展和收缩）（487）
		5. Advanced Data Structures（高级数据结构）（500）
			1. B-Trees（B树）（504）
				1. Data structures on secondary storage（二级存储上的数据结构）（504）
				2. Definition of B-trees（B树的定义）(508)
					1. The height of a B-tree（B树的高度）（509）
				3. Basic operations on B-trees（B 树的基本操作）（511）
					1. Searching a B-tree（搜索 B 树）（512）
					2. Creating an empty B-tree（创建一个空的 B 树）（513）
					3. Inserting a key into a B-tree（将键插入 B 树）（514）
					4. Splitting a node in a B-tree（分裂 B 树中的节点）（514）
					5. Inserting a key into a B-tree in a single pass down the tree（在树中单次遍历将键插入 B 树）（515）
				4. Deleting a key from a B-tree（从 B 树中删除键）（520）
			2. Fibonacci Heaps（斐波那契堆）（525）
				1. Mergeable heaps（可合并堆）（525）
				2. Fibonacci heaps in theory and practice（斐波那契理论与实践的结合）（526）
				3. Structure of Fibonacci heaps（斐波那契堆的结构）（528）
					1. Potential function（潜在功能）（529）
					2. Maximum degree（最大度数）（530）
				4. Mergeable-heap operations（可合并堆操作）（530）
					1. Creating a new Fibonacci heap（创建新的斐波那契堆）（530）
					2. Inserting a node（插入节点）（530）
					3. Finding the minimum node（寻找最小节点）（532）
					4. Uniting two Fibonacci heaps（合并两个斐波那契堆）（532）
					5. Extracting the minimum node（提取最小节点）（532）
				5. Decreasing a key and deleting a node（减少一个键并删除一个节点）（539）
					1. Decreasing a key（减少一个键）（540）
					2. Deleting a node（删除节点）（542）
				6. Bounding the maximum degree（限制最大度数）（543）
			3. van Emde Boas Trees（范恩德博阿斯树）（551）
				1. Preliminary approaches（初步方法）（552）
					1. Direct addressing（直接寻址）（552）
					2. Superimposing a binary tree structure（叠加二叉树结构）（553）
					3. Superimposing a tree of constant height（叠加一棵高度恒定的树）（555）
				2. A recursive structure（递归结构）（557）
					1. Proto van Emde Boas structures（原型范恩德博阿斯结构）（558）
					2. Operations on a proto van Emde Boas structure（对原型 van Emde Boas 结构进行操作）（561）
						1. Determining whether a value is in the set（判断一个值是否在集合中）（561）
						2. Finding the minimum element（寻找最小元素）（562）
						3. Finding the successor（寻找继任者）（563）
						4. Inserting an element（插入一个元素）（564）
						5. Deleting an element（删除元素）（564）
				3. The van Emde Boas tree（范·埃姆德·博阿斯树）（566）
					1. van Emde Boas trees（范·埃姆德·博阿斯树）（567）
					2. Operations on a van Emde Boas tree（van Emde Boas 树上的操作）（570）
						1. Finding the minimum and maximum elements（寻找最小和最大元素）（570）
						2. Determining whether a value is in the set（判断一个值是否在集合中）（570）
						3. Finding the successor and predecessor（寻找继任者和前任）（571）
						4. Inserting an element（插入一个元素）（573）
						5. Deleting an element（删除元素）（574）
			4. Data Structures for Disjoint Sets（不相交集的数据结构）（582）
				1. Disjoint-set operations（不相交集运算）（582）
					1. An application of disjoint-set data structures（不相交集数据结构的应用）（582）
				2. Linked-list representation of disjoint sets（不相交集合的链表表示）（585）
					1. A simple implementation of union（union 的简单实现）（585）
					2. A weighted-union heuristic（加权联合启发式）（586）
				3. Disjoint-set forests（不相交森林）（589）
					1. Heuristics to improve the running time（启发式改进运行时间）（590）
					2. Pseudocode for disjoint-set forests（不相交集森林的伪代码）（591）
					3. Effect of the heuristics on the running time（启发式对运行时间的影响）（592）
				4. Analysis of union by rank with path compression（通过路径压缩进行排名并集分析）（593）
					1. A very quickly growing function and its very slowly growing inverse（一个增长非常快的函数及其增长非常慢的逆函数）（593）
					2. Properties of ranks（等级的属性）（595）
					3. Proving the time bound（证明时间限制）（595）
					4. Potential function（潜在功能）（596）
					5. Potential changes and amortized costs of operations（潜在的变化和摊销运营成本）（598）
		6. Graph Algorithms（图算法）（607）
			1. Elementary Graph Algorithms（基本图算法）（609）
				1. Representations of graphs（图表的表示）（610）
					1. Representing attributes（代表属性）（612）
				2. Breadth-first search（广度优先搜索）（614）
					1. Breadth-first trees（广度优先树）（621）
				3. Depth-first search（深度优先搜索）（623）
					1. Properties of depth-first search（深度优先搜索的属性）（626）
					2. Classification of edges（边缘分类）（629）
				4. Topological sort（拓扑排序）（632）
				5. Strongly connected components（强连接组件）（635）
			2. Minimum Spanning Trees（最小生成树）（645）
				1. Growing a minimum spanning tree（生长最小生成树）（645）
				2. The algorithms of Kruskal and Prim（Kruskal和Prim算法）（651）
					1. Kruskal’s algorithm（克鲁斯卡尔算法）（651）
					2. Prim’s algorithm（Prim 算法）（654）
			3. Single-Source Shortest Paths（单源最短路径）（663）
				1. Variants（变体）（664）
				2. Optimal substructure of a shortest path（最短路径的最优子结构）（664）
				3. Negative-weight edges（负权重边）（666）
				4. Cycles（周期）（667）
				5. Representing shortest paths（表示最短路径）（668）
				6. Relaxation（松弛）（668）
				7. Properties of shortest paths and relaxation（最短路径和松弛的性质）（669）
				8. The Bellman-Ford algorithm（贝尔曼-福特算法）（671）
				9. Single-source shortest paths in directed acyclic graphs（有向无环图中的单源最短路径）（675）
				10. Dijkstra’s algorithm（Dijkstra 算法）（678）
				11. Difference constraints and shortest paths（差异约束和最短路径）（684）
					1. Linear programming（线性规划）（684）
					2. Systems of difference constraints（差异约束系统）（685）
					3. Constraint graphs（约束图）（687）
					4. Solving systems of difference constraints（688）
				12. Proofs of shortest-paths properties（最短路径属性的证明）（691）
					1. The triangle inequality（三角不等式）（691）
					2. Effects of relaxation on shortest-path estimates（松弛对最短路径估计的影响）（691）
					3. Relaxation and shortest-paths trees（松弛树和最短路径树）（694）
			4. All-Pairs Shortest Paths（全对最短路径）（704）
				1. Shortest paths and matrix multiplication（最短路径和矩阵乘法）（706）
					1. The structure of a shortest path（最短路径的结构）（707）
					2. A recursive solution to the all-pairs shortest-paths problem（全对最短路径问题的递归解决方案）（707）
					3. Computing the shortest-path weights bottom up（自下而上计算最短路径权重）（708）
					4. Improving the running time（改善运行时间）（710）
				2. The Floyd-Warshall algorithm（Floyd-Warshall 算法）（713）
					1. The structure of a shortest path（最短路径的结构）（713）
					2. A recursive solution to the all-pairs shortest-paths problem（全对最短路径问题的递归解决方案）（715）
					3. Computing the shortest-path weights bottom up（自下而上计算最短路径权重）（715）
					4. Constructing a shortest path（构建最短路径）（715）
					5. Transitive closure of a directed graph（有向图的传递闭包）（717）
				3. Johnson’s algorithm for sparse graphs（约翰逊稀疏图算法）（721）
					1. Preserving shortest paths by reweighting（通过重新加权保留最短路径）（721）
					2. Producing nonnegative weights by reweighting（通过重新加权生成非负权重）（722）
					3. Computing all-pairs shortest paths（计算所有对的最短路径）（722）
			5. Maximum Flow（最大流量）（728）
				1. Flow networks（流动网络）（729）
					1. Flow networks and flows（流量网络和流量）（729）
					2. An example of flow（流程示例）（731）
					3. Modeling problems with antiparallel edges（反平行边建模问题）（732）
					4. Networks with multiple sources and sinks（具有多个源和汇的网络）（732）
				2. The Ford-Fulkerson method（福特-富尔克森方法）（735）
					1. Residual networks（残差网络）（735）
					2. Augmenting paths（增强路径）（740）
					3. Cuts of flow networks（流量网络的切断）（741）
					4. The basic Ford-Fulkerson algorithm（基本的 Ford-Fulkerson 算法）（744）
					5. Analysis of Ford-Fulkerson（福特-福尔克森分析）（745）
					6. The Edmonds-Karp algorithm（Edmonds-Karp 算法）（748）
				3. Maximum bipartite matching（最大二分匹配）（752）
					1. The maximum-bipartite-matching problem（最大二分匹配问题）（752）
					2. Finding a maximum bipartite matching（寻找最大二分匹配）（753）
				4. Push-relabel algorithms（推送重新标记算法）（756）
					1. Intuition（直觉）（757）
					2. The basic operations（基本操作）（758）
					3. The push operation（推送操作）（758）
					4. The relabel operation（重新标记操作）（760）
					5. The generic algorithm（通用算法）（760）
					6. Correctness of the push-relabel method（Push-relabel方法的正确性）（761）
					7. Analysis of the push-relabel method（Push-relabel方法分析）（763）
				5. The relabel-to-front algorithm（重新标记到前面算法）（768）
					1. Admissible edges and networks（允许的边缘和网络）（769）
					2. Neighbor lists（邻居列表）（770）
					3. Discharging an overflowing vertex（释放溢出的顶点）（771）
					4. The relabel-to-front algorithm（重新标记到前面算法）（774）
					5. Analysis（分析）（778）
		7. Selected Topics（精选主题）（788）
			1. Multithreaded Algorithms（多线程算法）（793）
				1. Dynamic multithreaded programming（动态多线程编程）（794）
				2. The basics of dynamic multithreading（动态多线程的基础知识）（795）
					1. A model for multithreaded execution（多线程执行模型）（798）
					2. Performance measures（绩效衡量标准）（800）
					3. Scheduling（调度）（802）
					4. Analyzing multithreaded algorithms（分析多线程算法）（805）
					5. Parallel loops（并行循环）（806）
					6. Race conditions（比赛条件）（808）
					7. A chess lesson（一节国际象棋课）（811）
				3. Multithreaded matrix multiplication（多线程矩阵乘法）（813）
					1. Multithreaded matrix multiplication（多线程矩阵乘法）（813）
					2. A divide-and-conquer multithreaded algorithm for matrix multiplication（矩阵乘法的分而治之多线程算法）（814）
					3. Multithreading Strassen’s method（多线程施特拉森方法）（816）
				4. Multithreaded merge sort（多线程归并排序）（818）
					1. Analysis of multithreaded merging（多线程合并分析）（822）
					2. Multithreaded merge sort（多线程归并排序）（823）
					3. Analysis of multithreaded merge sort（多线程归并排序分析）（824）
			2. Matrix Operations（矩阵运算）（834）
				1. Solving systems of linear equations（求解线性方程组）（834）
					1. Overview of LUP decomposition（LUP分解概述）（836）
					2. Forward and back substitution（前向和后向替换）（837）
					3. Computing an LU decomposition（计算 LU 分解）（840）
					4. Computing an LUP decomposition（计算 LUP 分解）（844）
				2. Inverting matrices（矩阵求逆）（848）
					1. Computing a matrix inverse from an LUP decomposition（从 LUP 分解计算矩阵逆）（849）
					2. Matrix multiplication and matrix inversion（矩阵乘法和矩阵求逆）（849）
				3. Symmetric positive-definite matrices and least-squares approximation（对称正定矩阵和最小二乘近似）（853）
					1. Least-squares approximation（最小二乘近似）（856）
			3. Linear Programming（线性规划）（864）
				1. General linear programs（一般线性规划）（866）
				2. An overview of linear programming（线性规划概述）（867）
				3. Applications of linear programming（线性规划的应用）（870）
				4. Algorithms for linear programming（线性规划算法）（871）
				5. Standard and slack forms（标准形式和宽松形式）（871）
					1. Standard form（标准格式）（872）
					2. Converting linear programs into standard form（将线性程序转换为标准形式）（873）
					3. Converting linear programs into slack form（将线性程序转换为松弛形式）（875）
				6. Formulating problems as linear programs（将问题表述为线性规划）（880）
					1. Shortest paths（最短路径）（880）
					2. Maximum flow（最大流量）（881）
					3. Minimum-cost flow（最低成本流程）（882）
					4. Multicommodity flow（多商品流）（883）
				7. The simplex algorithm（单纯形算法）（885）
					1. An example of the simplex algorithm（单纯形算法的示例）（886）
					2. Pivoting（旋转）（890）
					3. The formal simplex algorithm（形式单纯形算法）（891）
					4. Termination（终止）（895）
				8. Duality（二元性）（900）
				9. The initial basic feasible solution（初始基本可行解）（907）
					1. Finding an initial solution（寻找初始解决方案）（907）
					2. Fundamental theorem of linear programming（线性规划基本定理）（912）
			4. Polynomials and the FFT（多项式和 FFT）（919）
				1. Polynomials（多项式）（919）
				2. Representing polynomials（表示多项式）（921）
					1. Coefficient representation（系数表示）（921）
					2. Point-value representation（点值表示）（922）
					3. Fast multiplication of polynomials in coefficient form（系数形式多项式的快速乘法）（924）
				3. The DFT and FFT（DFT 和 FFT）（927）
					1. Complex roots of unity（统一的复杂根源）（927）
						1. The DFT（密度泛函理论）（930）
						2. The FFT（快速傅里叶变换）（930）
						3. Interpolation at the complex roots of unity（单位复数根处的插值）（933）
					2. Efficient FFT implementations（高效的 FFT 实施）（936）
						1. An iterative FFT implementation（迭代 FFT 实现）（936）
						2. A parallel FFT circuit（并行FFT电路）（940）
			5. Number-Theoretic Algorithms（数论算法）（947）
				1. Size of inputs and cost of arithmetic computations（输入的大小和算术计算的成本）（947）
				2. Elementary number-theoretic notions（基本数论概念）（948）
					1. Divisibility and divisors（整除性和除数）（948）
					2. Prime and composite numbers（素数和合数）（949）
					3. The division theorem, remainders, and modular equivalence（除法定理、余数和模等价）（949）
					4. Common divisors and greatest common divisors（公约数和最大公约数）（950）
					5. Relatively prime integers（互质整数）（952）
					6. Unique factorization（独特的因式分解）（952）
				3. Greatest common divisor（最大公约数）（954）
					1. Euclid’s algorithm（欧几里得算法）（956）
					2. The running time of Euclid’s algorithm（欧几里得算法的运行时间）（956）
					3. The extended form of Euclid’s algorithm（欧几里得算法的扩展形式）（958）
				4. Modular arithmetic（模运算）（960）
					1. Finite groups（有限群）（960）
					2. The groups defined by modular addition and multiplication（由模加法和模乘法定义的群）（961）
					3. Subgroups（亚组）（964）
					4. Subgroups generated by an element（由元素生成的子组）（965）
				5. Solving modular linear equations（求解模线性方程）（967）
				6. The Chinese remainder theorem（中文剩余定理）（971）
				7. Powers of an element（元素的幂）（975）
					1. Raising to powers with repeated squaring（通过重复平方求幂）（977）
				8. The RSA public-key cryptosystem（Public-key cryptosystems）（980）
					1. The RSA cryptosystem（RSA 密码系统）（983）
				9. Primality testing（素性测试）（986）
					1. The density of prime numbers（素数的密度）（986）
					2. Pseudoprimality testing（伪素性测试）（987）
					3. The Miller-Rabin randomized primality test（Miller-Rabin 随机素性检验）（989）
					4. Error rate of the Miller-Rabin primality test（Miller-Rabin 素性测试的错误率）（992）
				10. Integer factorization（整数因式分解）（996）
					1. Pollard’s rho heuristic（波拉德的 rho 启发式）（996）
			6. String Matching（字符串匹配）（1007）
				1. Notation and terminology（符号和术语）（1007）
				2. The naive string-matching algorithm（简单的字符串匹配算法）（1009）
				3. The Rabin-Karp algorithm（Rabin-Karp 算法）（1011）
				4. String matching with finite automata（与有限自动机的字符串匹配）（1016）
					1. Finite automata（有限自动机）（1016）
					2. String-matching automata（字符串匹配自动机）（1017）
					3. Computing the transition function（计算转换函数）（1022）
				5. The Knuth-Morris-Pratt algorithm（计算转换函数）（1023）
					1. The prefix function for a pattern（模式的前缀函数）（1024）
					2. Running-time analysis（运行时分析）（1027）
					3. Correctness of the prefix-function computation（前缀函数计算的正确性）（1028）
					4. Correctness of the Knuth-Morris-Pratt algorithm（Knuth-Morris-Pratt 算法的正确性）（1030）
			7. Computational Geometry（计算几何）（1035）
				1. Line-segment properties（线段属性）（1036）
					1. Cross products（交叉产品）（1037）
					2. Determining whether consecutive segments turn left or right（确定连续线段是左转还是右转）（1038）
					3. Determining whether two line segments intersect（判断两条线段是否相交）（1038）
					4. Other applications of cross products（叉积的其他应用）（1041）
				2. Determining whether any pair of segments intersects（确定任意一对线段是否相交）（1043）
					1. Ordering segments（订购段）（1043）
					2. Moving the sweep line（移动扫描线）（1044）
					3. Segment-intersection pseudocode（线段交点伪代码）（1045）
					4. Correctness（正确性）（1047）
					5. Running time（运行时间）（1048）
				3. Finding the convex hull（寻找凸包）（1050）
					1. Graham’s scan（格雷厄姆扫描）（1051）
					2. Jarvis’s march（贾维斯的游行）（1058）
				4. Finding the closest pair of points（寻找最接近的点对）（1060）
					1. The divide-and-conquer algorithm（分治算法）（1061）
					2. Correctness（正确性）（1062）
					3. Implementation and running time（实施及运行时间）（1063）
			8. NP-Completeness（NP完备性）（1069）
				1. NP-completeness and the classes P and NP（NP 完备性以及 P 类和 NP 类）（1070）
				2. Overview of showing problems to be NP-complete（显示问题为 NP 完全问题的概述）（1071）
				3. Decision problems vs. optimization problems（决策问题与优化问题）（1071）
				4. Reductions（减少）（1072）
				5. A first NP-complete problem（第一个 NP 完全问题）（1074）
				6. Polynomial time（多项式时间）（1074）
					1. Abstract problems（抽象问题）（1075）
					2. Encodings（编码）（1076）
					3. A formal-language framework（形式语言框架）（1078）
				7. Polynomial-time verification（多项式时间验证）（1082）
					1. Hamiltonian cycles（哈密顿循环）（1082）
					2. Verification algorithms（验证算法）（1084）
					3. The complexity class NP（复杂度等级 NP）（1085）
				8. NP-completeness and reducibility（NP 完备性和可还原性）（1088）
					1. Reducibility（还原性）（1088）
					2. NP-completeness（NP 完备性）（1089）
					3. Circuit satisfiability（电路可满足性）（1091）
				9. NP-completeness proofs（1099）
					1. Formula satisfiability（公式可满足性）（1100）
					2. 3-CNF satisfiability（3-CNF 可满足性）（1103）
				10. NP-complete problems（NP 完全问题）（1107）
					1. The clique problem（派系问题）（1107）
					2. The vertex-cover problem（顶点覆盖问题）（1110）
					3. The hamiltonian-cycle problem（哈密顿循环问题）（1112）
					4. The traveling-salesman problem（旅行商问题）（1117）
					5. The subset-sum problem（子集和问题）（1118）
			9. Approximation Algorithms（近似算法）（1127）
				1. Performance ratios for approximation algorithms（近似算法的性能比）（1127）
				2. The vertex-cover problem（顶点覆盖问题）（1129）
				3. The traveling-salesman problem（旅行商问题）（1133）
					1. The traveling-salesman problem with the triangle inequality（三角不等式的旅行商问题）（1133）
					2. The general traveling-salesman problem（一般旅行商问题）（1136）
				4. The set-covering problem（集合覆盖问题）（1138）
					1. A greedy approximation algorithm（贪心近似算法）（1140）
					2. Analysis（分析）（1140）
				5. Randomization and linear programming（随机化和线性规划）（1144）
					1. A randomized approximation algorithm for MAX-3-CNF satisfiability（MAX-3-CNF 可满足性的随机近似算法）（1144）
					2. Approximating weighted vertex cover using linear programming（使用线性规划近似加权顶点覆盖）（1145）
				6. The subset-sum problem（子集和问题）（1149）
					1. An exponential-time exact algorithm（指数时间精确算法）（1149）
					2. A fully polynomial-time approximation scheme（完全多项式时间近似方案）（1150）
			10. Appendix: Mathematical Background（附录：数学背景）（1163）
				1. Summations（求和）（1166）
					1. Summation formulas and properties（求和公式及性质）（1167）
						1. Linearity（线性度）（1167）
						2. Arithmetic series（算术系列）（1167）
						3. Sums of squares and cubes（平方和和立方和）（1168）
						4. Geometric series（几何系列）（1168）
						5. Harmonic series（谐波系列）（1168）
						6. Integrating and differentiating series（积分与微分系列）（1169）
						7. Telescoping series（伸缩系列）（1169）
						8. Products（产品）（1169）
					2. Bounding summations（边界求和）（1170）
						1. Mathematical induction（数学归纳法）（1171）
						2. Bounding the terms（限制条款）（1171）
						3. Splitting summations（分割求和）（1173）
						4. Approximation by integrals（积分近似）（1175）
				2. Sets, Etc.（集合，等）（1179）
					1. Sets（集合）（1179）
					2. Relations（关系）（1184）
					3. Functions（函数）（1187）
					4. Graphs（图表）（1189）
					5. Trees（树）（1194）
						1. Free trees（自由树）（1194）
						2. Rooted and ordered trees（有根且有序的树）（1197）
						3. Binary and positional trees（二叉树和位置树）（1198）
				3. Counting and Probability（计数与概率）（1204）
					1. Counting（数数）（1204）
						1. Rules of sum and product（和与积的规则）（1204）
						2. Strings（字符串）（1205）
						3. Permutations（排列）（1205）
						4. Combinations（组合）（1206）
						5. Binomial coefficients（二项式系数）（1206）
						6. Binomial bounds（二项式界限）（1207）
					2. Probability（可能性）（1210）
						1. Axioms of probability（概率公理）（1211）
						2. Discrete probability distributions（离散概率分布）（1212）
						3. Continuous uniform probability distribution（连续均匀概率分布）（1212）
						4. Conditional probability and independence（条件概率和独立性）（1213）
						5. Bayes’s theorem（贝叶斯定理）（1215）
					3. Discrete random variables（离散随机变量）（1217）
						1. Expected value of a random variable（随机变量的期望值）（1218）
						2. Variance and standard deviation（方差和标准差）（1220）
					4. The geometric and binomial distributions（几何分布和二项分布）（1222）
						1. The geometric distribution（几何分布）（1223）
						2. The binomial distribution（二项式分布）（1224）
					5. The tails of the binomial distribution（二项式分布的尾部）（1229）
				4. Matrices（矩阵）（1238）
					1. Matrices and matrix operations（矩阵和矩阵运算）（1238）
						1. Matrices and vectors（矩阵和向量）（1238）
						2. Square matrices（方阵）（1239）
						3. Basic matrix operations（基本矩阵运算）（1241）
					2. Basic matrix properties（基本矩阵属性）（1243）
						1. Matrix inverses, ranks, and determinants（矩阵逆矩阵、秩和行列式）（1243）
						2. Positive-definite matrices（正定矩阵）（1246）
2. Programming Languages（编程语言）
	1. The C Programming Language（C程序设计语言）
		1. A Tutorial Introduction（教程简介）（9）
			1. Getting Started（入门）（9）
			2. Variables and Arithmetic Expressions（变量和算术表达式）（11）
			3. The for statement（for语句）（16）
			4. Symbolic Constants（符号常量）（17）
			5. Character Input and Output（字符输入与输出）（18）
				1. File Copying（文件复制）（18）
				2. Character Counting（字符计数）（20）
				3. Line Counting（行计数）（21）
				4. Word Counting（字数统计）（22）
			6. Arrays（数组）（23）
			7. Functions（功能）（25）
			8. Arguments - Call by Value（参数 - 按值调用）（28）
			9. Character Arrays（字符数组）（29）
			10. External Variables and Scope（外部变量和范围）（31）
		2. Types, Operators and Expressions（类型、运算符和表达式）（35）
			1. Variable Names（变量名称）（35）
			2. Data Types and Sizes（数据类型和大小）（35）
			3. Constants（常数）（36）
			4. Declarations（声明）（39）
			5. Arithmetic Operators（算术运算符）（40）
			6. Relational and Logical Operators（关系运算符和逻辑运算符）（40）
			7. Type Conversions（类型转换）（41）
			8. Increment and Decrement Operators（自增和自减运算符）（44）
			9. Bitwise Operators（位运算符）（46）
			10. Assignment Operators and Expressions（赋值运算符和表达式）（47）
			11. Conditional Expressions（条件表达式）（49）
			12. Precedence and Order of Evaluation（求值的优先级和顺序）（49）
		3. Control Flow（控制流）（52）
			1. Statements and Blocks（语句和块）（52）
			2. If-Else（52）
			3. Else-If（53）
			4. Switch（54）
			5. Loops - While and For（循环 - While 和 For）（56）
			6. Loops - Do-While（循环 - Do-While）（59）
			7. Break and Continue（59）
			8. Goto and labels（跳转和标签）（60）
		4. Functions and Program Structure（功能和程序结构）（62）
			1. Basics of Functions（功能和程序结构）（62）
			2. Functions Returning Non-integers（返回非整数的函数）（65）
			3. External Variables（外部变量）（67）
			4. Scope Rules（范围规则）（72）
			5. Header Files（头文件）（73）
			6. Static Variables（静态变量）（75）
			7. Register Variables（寄存器变量）（75）
			8. Block Structure（块结构）（76）
			9. Initialization（初始化）（76）
			10. Recursion（递归）（78）
			11. The C Preprocessor（C  预处理器）（79）
				1. File Inclusion（文件包含）（79）
				2. Macro Substitution（宏替换）（80）
				3. Conditional Inclusion（有条件包含）（82）
		5. Pointers and Arrays（指针和数组）（83）
			1. Pointers and Addresses（指针和地址）（83）
			2. Pointers and Function Arguments（指针和函数参数）（84）
			3. Pointers and Arrays（指针和数组）（87）
			4. Address Arithmetic（地址运算）（90）
			5. Character Pointers and Functions（字符指针和函数）（93）
			6. Pointer Arrays; Pointers to Pointers（指针数组；指针到指针）（96）
			7. Multi-dimensional Arrays（多维数组）（99）
			8. Initialization of Pointer Arrays（指针数组的初始化）（101）
			9. Pointers vs. Multi-dimensional Arrays（指针与多维数组）（101）
			10. Command-line Arguments（命令行参数）（102）
			11. Pointers to Functions（函数指针）（106）
			12. Complicated Declarations（复杂声明）（108）
		6. Structures（结构）（114）
			1. Basics of Structures（结构基础）（114）
			2. Structures and Functions（结构与功能）（116）
			3. Arrays of Structures（结构体数组）（118）
			4. Pointers to Structures（结构体指针）（122）
			5. Self-referential Structures（自指结构）（124）
			6. Table Lookup（查表）（127）
			7. Typedef（类型定义）（129）
			8. Unions（工会）（131）
			9. Bit-fields（位域）（132）
		7. Input and Output（输入和输出）（135）
			1. Standard Input and Output（标准输入输出）（135）
			2. Formatted Output - printf（格式化输出 - printf）（137）
			3. Variable-length Argument Lists（可变长度参数列表）（138）
			4. Formatted Input - Scanf（格式化输入‑Scanf）（140）
			5. File Access（文件访问）（142）
			6. Error Handling - Stderr and Exit（错误处理‑Stderr  和退出）（145）
			7. Line Input and Output（线路输入和输出）（146）
			8. Miscellaneous Functions（杂项功能）（147）
				1. String Operations（字符串操作）（147）
				2. Character Class Testing and Conversion（字符类测试和转换）（148）
				3. Ungetc（148）
				4. Command Execution（命令执行）（148）
				5. Storage Management（存储管理）（148）
				6. Mathematical Functions（数学函数）（149）
				7. Random Number generation（随机数生成）（149）
		8. The UNIX System Interface（UNIX  系统接口）（151）
			1. File Descriptors（文件描述符）（151）
			2. Low Level I/O - Read and Write（低级  I/O  ‑  读和写）（152）
			3. Open, Creat, Close, Unlink（打开、创建、关闭、取消链接）（153）
			4. Random Access - Lseek（随机访问‑Lseek）（155）
			5. Example - An implementation of Fopen and Getc（示例  ‑  Fopen  和  Getc  的实现）（156）
			6. Example - Listing Directories（示例  ‑  列出目录）（159）
			7. Example - A Storage Allocator（示例 - 存储分配器）（163）
	2. C++ Primer（C++ 入门）
		1. 0
			1. Getting Started（入门）（30）
				1. Writing a Simple C++ Program（编写一个简单的  C++  程序）（31）
					1. Compiling and Executing Our Program（编译并执行我们的程序）（32）
				2. A First Look at Input/Output（初步了解输入/输出）（34）
				3. A Word about Comments（关于评论的一句话）（38）
				4. Flow of Control（控制流程）（40）
					1. The while Statement（while  语句）（40）
					2. The for Statement（for  语句）（42）
					3. Reading an Unknown Number of Inputs（读取未知数量的输入）（43）
					4. The if Statement（if  语句）（46）
				5. Introducing Classes（介绍课程）（48）
					1. The Sales_item Class（Sales_item  类）（49）
					2. A First Look at Member Functions（会员功能初探）（52）
				6. The Bookstore Program（书店计划）（53）
				7. Chapter Summary（章节总结）（55）
				8. Defined Terms（术语定义）（55）
		2. The Basics（基础知识）（58）
			1. Variables and Basic Types（变量和基本类型）（60）
				1. Primitive Built-in Types（原始内置类型）（61）
					1. Arithmetic Types（算术类型）（61）
					2. Type Conversions（类型转换）（64）
					3. Literals（文字）（67）
				2. Variables（变量）（70）
					1. Variable Definitions（变量定义）（70）
					2. Variable Declarations and Definitions（变量声明和定义）（73）
					3. Identifiers（身份标识）（75）
					4. Scope of a Name（名称的范围）（77）
				3. Compound Types（复合类型）（79）
					1. References（引用）（79）
					2. Pointers（指针）（81）
					3. Understanding Compound Type Declarations（了解复合类型声明）（86）
				4. const Qualifier（常量限定符）（88）
					1. References to const（对  const  的引用）（90）
					2. Pointers and const（指针和常量）（91）
					3. Top-Level const（顶级常量）（92）
					4. constexpr and Constant Expressions（constexpr  和常量表达式）（94）
				5. Dealing with Types（处理类型）（96）
					1. Type Aliases（类型别名）（96）
					2. The auto Type Specifier（自动类型说明符）（97）
					3. The decltype Type Specifier（decltype  类型说明符）（99）
				6. Defining Our Own Data Structures（定义我们自己的数据结构）（定义我们自己的数据结构）（101）
					1. Defining the Sales_data Type（定义  Sales_data  类型）（101）
					2. Using the Sales_data Class（使用  Sales_data  类）（103）
					3. Writing Our Own Header Files（编写我们自己的头文件）（105）
				7. Chapter Summary（章节总结）（107）
				8. Defined Terms（术语定义）（107）
			2. Strings, Vectors, and Arrays（字符串、向量和数组）（110）
				1. Namespace using Declarations（使用声明的命名空间）（111）
				2. Library string Type（库字符串类型）（113）
					1. Defining and Initializing strings（定义和初始化字符串）（113）
					2. Operations on strings（字符串操作）（114）
					3. Dealing with the Characters in a string（处理字符串中的字符）（119）
				3. Library vector Type（库向量类型）（125）
					1. Defining and Initializing vectors（定义和初始化向量）（126）
					2. Adding Elements to a vector（将元素添加到向量）（129）
					3. Other vector Operations（其他向量运算）（131）
				4. Introducing Iterators（迭代器简介）（135）
					1. Using Iterators（使用迭代器）（135）
					2. Iterator Arithmetic（迭代器算法）（140）
				5. Arrays（数组）（142）
					1. Defining and Initializing Built-in Arrays（定义和初始化内置数组）（142）
					2. Accessing the Elements of an Array（访问数组的元素）（145）
					3. Pointers and Arrays（指针和数组）（146）
					4. C-Style Character Strings（C  风格字符串）（151）
					5. Interfacing to Older Code（与旧代码的接口）（153）
				6. Multidimensional Arrays（多维数组）（154）
				7. Chapter Summary（章节总结）（160）
				8. Defined Terms（术语定义）（160）
			3. Expressions（表达式）（162）
				1. Fundamentals（基础知识）（163）
					1. Basic Concepts（基本概念）（163）
					2. Precedence and Associativity（优先级和关联性）（165）
					3. Order of Evaluation（评估顺序）（166）
				2. Arithmetic Operators（算术运算符）（168）
				3. Logical and Relational Operators（逻辑和关系运算符）（170）
				4. Assignment Operators（赋值运算符）（173）
				5. Increment and Decrement Operators（自增和自减运算符）（176）
				6. The Member Access Operators（会员接入运营商）（179）
				7. The Conditional Operator（条件运算符）（180）
				8. The Bitwise Operators（按位运算符）（181）
				9. The sizeof Operator（运算符的大小）（185）
				10. Comma Operator（逗号运算符）（186）
				11. Type Conversions（类型转换）（188）
					1. The Arithmetic Conversions（算术转换）（188）
					2. Other Implicit Conversions（其他隐式转换）（190）
					3. Explicit Conversions（显式转换）（191）
				12. Operator Precedence Table（运算符优先级表）（195）
				13. Chapter Summary（章节总结）（197）
				14. Defined Terms（术语定义）（197）
			4. Statements（语句）（200）
				1. Simple Statements（简单的陈述）（201）
				2. Statement Scope（声明范围）（203）
				3. Conditional Statements（条件语句）（203）
					1. The if Statement（if  语句）（204）
					2. The switch Statement（switch  语句）（207）
				4. Iterative Statements（迭代语句）（212）
					1. The while Statement（while  语句）（212）
					2. Traditional for Statement（传统  for  语句）（214）
					3. Range for Statement（范围for语句）（216）
					4. The do while Statement（do  while  语句）（218）
				5. Jump Statements（跳转语句）（219）
					1. The break Statement（中断语句）（219）
					2. The continue Statement（继续语句）（220）
					3. The goto Statement（goto  语句）（221）
				6. try Blocks and Exception Handling（try块和异常处理）（222）
					1. A throw Expression（抛出表达式）（222）
					2. The try Block（尝试块）（223）
					3. Standard Exceptions（标准例外）（226）
				7. Chapter Summary（章节总结）（228）
				8. Defined Terms（术语定义）（228）
			5. Functions（函数）（230）
				1. Function Basics（函数基础知识）（231）
					1. Local Objects（本地对象）（233）
					2. Function Declarations（函数声明）（235）
					3. Separate Compilation（单独编译）（236）
				2. Argument Passing（参数传递）（237）
					1. Passing Arguments by Value（按值传递参数）（238）
					2. Passing Arguments by Reference（通过引用传递参数）（239）
					3. const Parameters and Arguments（const  参数和参数）（241）
					4. Array Parameters（数组参数）（243）
					5. main: Handling Command-Line Options（main：处理命令行选项）（247）
					6. Functions with Varying Parameters（具有不同参数的函数）（249）
				3. Return Types and the return Statement（返回类型和返回语句）（251）
					1. Functions with No Return Value（无返回值的函数）（252）
					2. Functions That Return a Value（返回值的函数）（252）
					3. Returning a Pointer to an Array（返回指向数组的指针）（257）
				4. Overloaded Functions（重载函数）（259）
					1. Overloading and Scope（重载和范围）（263）
				5. Features for Specialized Uses（特殊用途的功能）（265）
					1. Default Arguments（默认参数）（265）
					2. Inline and constexpr Functions（内联函数和  constexpr  函数）（267）
					3. Aids for Debugging（调试辅助工具）（269）
				6. Function Matching（功能匹配）（271）
					1. Argument Type Conversions（参数类型转换）（274）
				7. Pointers to Functions（函数指针）（276）
				8. Chapter Summary（章节总结）（280）
				9. Defined Terms（术语定义）（280）
			6. Classes（类）（282）
				1. Defining Abstract Data Types（定义抽象数据类型）（283）
					1. Designing the Sales_data Class（设计  Sales_data  类）（283）
					2. Defining the Revised Sales_data Class（定义修订后的  Sales_data  类）（285）
					3. Defining Nonmember Class-Related Functions（定义非成员类相关函数）（289）
					4. Constructors（构造函数）（291）
					5. Copy, Assignment, and Destruction（复制、分配和销毁）（296）
				2. Access Control and Encapsulation（访问控制和封装）（297）
					1. Friends（友元）（298）
				3. Additional Class Features（附加课程功能）（300）
					1. Class Members Revisited（重访班级成员）（300）
					2. Functions That Return *this（返回  *this  的函数）（304）
					3. Class Types（类类型）（306）
					4. Friendship Revisited（重温友谊）（308）
				4. Class Scope（类别范围）（311）
					1. Name Lookup and Class Scope（名称查找和类范围）（312）
				5. Constructors Revisited（重温构造函数）（317）
					1. Constructor Initializer List（构造函数初始化列表）（317）
					2. Delegating Constructors（委托构造函数）（320）
					3. The Role of the Default Constructor（默认构造函数的作用）（322）
					4. Implicit Class-Type Conversions（隐式类类型转换）（323）
					5. Aggregate Classes（聚合类）（327）
					6. Literal Classes（文字类）（328）
				6. static Class Members（静态类成员）（329）
				7. Chapter Summary（章节总结）（334）
				8. Defined Terms（术语定义）（334）
		3. The C++ Library（C++  库）（336）
			1. The IO Library（IO  库）（338）
				1. The IO Classes（IO  类）（339）
					1. No Copy or Assign for IO Objects（禁止复制或分配  IO  对象）（340）
					2. Condition States（条件状态）（341）
					3. Managing the Output Buffer（管理输出缓冲区）（343）
				2. File Input and Output（文件输入和输出）（345）
					1. Using File Stream Objects（使用文件流对象）（346）
					2. File Modes（文件模式）（348）
				3. string Streams（字符串流）（350）
					1. Using an istringstream（使用  istringstream）（350）
					2. Using ostringstreams（使用  ostringstreams）（352）
				4. Chapter Summary（章节总结）（353）
				5. Defined Terms（术语定义）（353）
			2. Sequential Containers（顺序容器）（354）
				1. Overview of the Sequential Containers（顺序容器概述）（355）
				2. Container Library Overview（容器库概述）（357）
					1. Iterators（迭代器）（360）
					2. Container Type Members（容器类型成员）（361）
					3. begin and end Members（开始和结束成员）（362）
					4. Defining and Initializing a Container（定义和初始化容器）（363）
					5. Assignment and swap（分配和交换）（366）
					6. Container Size Operations（集装箱尺寸操作）（369）
					7. Relational Operators（关系运算符）（369）
				3. Sequential Container Operations（顺序容器操作）（370）
					1. Adding Elements to a Sequential Container（将元素添加到顺序容器）（370）
					2. Accessing Elements（访问元素）（375）
					3. Erasing Elements（擦除元素）（377）
					4. Specialized forward_list Operations（专门的forward_list操作）（379）
					5. Resizing a Container（调整容器大小）（381）
					6. Container Operations May Invalidate Iterators（容器操作可能会使迭代器失效）（382）
				4. How a vector Grows（向量如何增长）（384）
				5. Additional string Operations（附加字符串操作）（389）
					1. Other Ways to Construct strings（构造字符串的其他方法）（389）
					2. Other Ways to Change a string（更改字符串的其他方法）（390）
					3. string Search Operations（字符串搜索操作）（393）
					4. The compare Functions（比较函数）（395）
					5. Numeric Conversions（数字转换）（396）
				6. Container Adapto（容器适配器）（397）
				7. Chapter Summary（章节总结）（401）
				8. Defined Terms（术语定义）（401）
			3. Generic Algorithms（通用算法）（404）
				1. Overview（概述）（405）
				2. A First Look at the Algorithms（算法初探）（407）
					1. Read-Only Algorithms（只读算法）（408）
					2. Algorithms That Write Container Elements（写入容器元素的算法）（409）
					3. Algorithms That Reorder Container Elements（重新排序容器元素的算法）（412）
				3. Customizing Operations（定制操作）（414）
					1. Passing a Function to an Algorithm（将函数传递给算法）（415）
					2. Lambda Expressions（拉姆达表达式）（416）
					3. Lambda Captures and Returns（Lambda  捕获并返回）（421）
					4. Binding Arguments（具有约束力的论据）（426）
				4. Revisiting Iterators（重温迭代器）（430）
					1. Insert Iterators（插入迭代器）（431）
					2. iostream Iterators（iostream  迭代器）（432）
					3. Reverse Iterators（反向迭代器）（436）
				5. Structure of Generic Algorithms（通用算法的结构）（439）
					1. The Five Iterator Categories（迭代器的五种类别）（439）
					2. Algorithm Parameter Patterns（算法参数模式）（441）
					3. Algorithm Naming Conventions（算法命名约定）（442）
				6. Container-Specific Algorithms（容器特定算法）（444）
				7. Chapter Summary（章节总结）（446）
				8. Defined Terms（术语定义）（446）
			4. Associative Containers（关联容器）（448）
				1. Using an Associative Container（使用关联容器）（449）
				2. Overview of the Associative Containers（关联容器概述）（452）
					1. Defining an Associative Container（定义关联容器）（452）
					2. Requirements on Key Type（密钥类型要求）（453）
					3. The pair Type（配对类型）（455）
				3. Operations on Associative Containers（关联容器上的操作）（457）
					1. Associative Container Iterators（关联容器迭代器）（458）
					2. Adding Elements（添加元素）（460）
					3. Erasing Elements（擦除元素）（463）
					4. Subscripting a map（订阅地图）（464）
					5. Accessing Elements（访问元素）（465）
					6. A Word Transformation Map（单词转换图）（469）
				4. The Unordered Containers（无序容器）（472）
				5. Chapter Summary（章节总结）（476）
				6. Defined Terms（术语定义）（476）
			5. Dynamic Memory（动态内存）（478）
				1. Dynamic Memory and Smart Pointers（动态内存和智能指针）（479）
					1. The shared_ptr Class（Shared_ptr  类）（479）
					2. Managing Memory Directly（直接管理内存）（487）
					3. Using shared_ptrs with new（将shared_ptr与new一起使用）（493）
					4. Smart Pointers and Exceptions（智能指针和异常）（496）
					5. unique_ptr（唯一指针）（499）
					6. weak_ptr（弱指针）（502）
				2. Dynamic Arrays（动态数组）（505）
					1. new and Arrays（新的和数组）（506）
					2. The allocator Class（分配器类）（501）
				3. Using the Library: A Text-Query Program（使用库：文本查询程序）（513）
					1. Design of the Query Program（查询程序的设计）（514）
					2. Defining the Query Program Classes（定义查询程序类）（516）
				4. Chapter Summary（章节总结）（520）
				5. Defined Terms（术语定义）（520）
		4. Tools for Class Authors（课程作者的工具）（522）
			1. Copy Control（复制控制）（524）
				1. Copy, Assign, and Destroy（复制、分配和销毁）（525）
					1. The Copy Constructo（复制构造函数）（525）
					2. The Copy-Assignment Operator（复制赋值运算符）（529）
					3. The Destructor（破坏者）（530）
					4. The Rule of Three/Five（三/五法则）（532）
					5. Using = default（535）
					6. Preventing Copies（防止复制）（536）
				2. Copy Control and Resource Management（复制控制和资源管理）（539）
					1. Classes That Act Like Values（行为类似于值的类）（540）
					2. Defining Classes That Act Like Pointers（定义行为类似于指针的类）（542）
				3. Swap（交换）（545）
				4. A Copy-Control Example（复制控制⽰例）（548）
				5. Classes That Manage Dynamic Memory（管理动态内存的类）（553）
				6. Moving Objects（移动物体）（560）
					1. Rvalue References（右值引用）（561）
					2. Move Constructor and Move Assignment（移动构造函数和移动赋值）（563）
					3. Rvalue References and Member Functions（右值引用和成员函数）（573）
				7. Chapter Summary（章节总结）（578）
				8. Defined Terms（术语定义）（578）
			2. Overloaded Operations and Conversions（重载操作和转换）（580）
				1. Basic Concepts（重载操作和转换）（581）
				2. Input and Output Operators（输入和输出运算符）（585）
					1. Overloading the Output Operator <<（重载输出运算符  <<）（586）
					2. Overloading the Input Operator >>（重载输入运算符>>）（587）
				3. Arithmetic and Relational Operators（算术和关系运算符）（589）
					1. Equality Operators（等式运算）（590）
					2. Relational Operators（关系运算符）（591）
				4. Assignment Operators（赋值运算符）（592）
				5. Subscript Operator（下标运算符）（593）
				6. Increment and Decrement Operators（自增和自减运算符）（595）
				7. Member Access Operators（会员接入运营商）（598）
				8. Function-Call Operator（函数调用运算符）（600）
					1. Lambdas Are Function Objects（Lambda  是函数对象）（601）
					2. Library-Defined Function Objects（库定义的函数对象）（603）
					3. Callable Objects and function（可调用对象和函数）（605）
				9. Overloading, Conversions, and Operators（重载、转换和运算符）（608）
					1. Conversion Operators（转换运算符）（609）
					2. Avoiding Ambiguous Conversions（避免不明确的转换）（612）
					3. Function Matching and Overloaded Operators（函数匹配和重载运算符）（616）
				10. Chapter Summary（章节总结）（619）
				11. Defined Terms（术语定义）（619）
			3. Object-Oriented Programming（面向对象编程）（620）
				1. OOP: An Overview（面向对象编程：概述）（621）
				2. Defining Base and Derived Classes（定义基类和派生类）（623）
					1. Defining a Base Class（定义基类）（623）
					2. Defining a Derived Class（定义派生类）（625）
					3. Conversions and Inheritance（转换和继承）（630）
				3. Virtual Functions（虚拟功能）（632）
				4. Abstract Base Classes（抽象基类）（637）
				5. Access Control and Inheritance（访问控制和继承）（640）
				6. Class Scope under Inheritance（继承下的类范围）（646）
				7. Constructors and Copy Control（构造函数和复制控制）（651）
					1. Virtual Destructors（虚拟析构函数）（651）
					2. Synthesized Copy Control and Inheritance（综合复制控制和继承）（652）
					3. Derived-Class Copy-Control Members（派生类复制控制成员）（654）
					4. Inherited Constructors（继承的构造函数）（657）
				8. Containers and Inheritance（容器和继承）（659）
					1. Writing a Basket Class（编写篮子类）（660）
				9. Text Queries Revisited（重新审视文本查询）（663）
					1. An Object-Oriented Solution（面向对象的解决方案）（665）
					2. The Query_base and Query Classes（Query_base  和  Query  类）（668）
					3. The Derived Classes（派生类）（671）
					4. The eval Functions（eval  函数）（674）
				10. Chapter Summary（章节总结）（678）
				11. Defined Terms（术语定义）（678）
			4. Templates and Generic Programming（模板和通用编程）（680）
				1. Defining a Template（定义模板）（681）
					1. Function Templates（函数模板）（681）
					2. Class Templates（类模板）（687）
					3. Template Parameters（模板参数）（697）
					4. Member Templates（会员模板）（701）
					5. Controlling Instantiations（控制实例化）（704）
					6. Efficiency and Flexibility（效率和灵活性）（705）
				2. Template Argument Deduction（模板参数推导）（707）
					1. Conversions and Template Type Parameters（转换和模板类型参数）（708）
					2. Function-Template Explicit Arguments（函数模板显式参数）（710）
					3. Trailing Return Types and Type Transformation（尾随返回类型和类型转换）（712）
					4. Function Pointers and Argument Deduction（函数指针和参数推导）（715）
					5. Template Argument Deduction and References（模板参数推导和参考）（716）
					6. Understanding std::move（理解  std::move）（719）
					7. Forwarding（转发）（721）
				3. Overloading and Templates（重载和模板）（723）
				4. Variadic Templates（可变参数模板）（728）
					1. Writing a Variadic Function Template（编写可变参数函数模板）（730）
					2. Pack Exp（包扩展）（731）
					3. Forwarding Parameter Packs（转发参数包）（733）
				5. Template Specializations（模板专业化）（735）
				6. Chapter Summary（章节总结）（742）
				7. Defined Terms（术语定义）（742）
		5. Advanced Topics（高级主题）（744）
			1. Specialized Library Facilities（专业图书馆设施）（746）
				1. The tuple Type（元组类型）（747）
					1. Defining and Initializing tuples（定义和初始化元组）（747）
					2. Using a tuple to Return Multiple Values（使用元组返回多个值）（750）
				2. The bitset Type（位集类型）（752）
					1. Defining and Initializing bitsets（定义和初始化位集）（752）
					2. Operations on bitsets（位集上的操作）（754）
				3. Regular Expressions（常用表达）（757）
					1. Using the Regular Expression Library（使用正则表达式库）（758）
					2. The Match and Regex Iterator Types（匹配和正则表达式迭代器类型）（763）
					3. Using Subexpressions（使用子表达式）（767）
					4. Using regex_replace（使用  regex_replace）（770）
				4. Random Numbers（随机数）（774）
					1. Random-Number Engines and Distribution（随机数引擎和分布）（774）
					2. Other Kinds of Distributions（其他类型的发行版）（778）
				5. The IO Library Revisited（IO  库重温）（781）
					1. Formatted Input and Output（格式化输入和输出）（782）
					2. Unformatted Input/Output Operations（未格式化的输入/输出操作）（790）
					3. Random Access to a Stream（随机访问流）（792）
				6. Chapter Summary（章节总结）（798）
				7. Defined Terms（术语定义）（798）
			2. Tools for Large Programs（大型程序的工具）（800）
				1. Exception Handling（异常处理）（801）
					1. Throwing an Exception（抛出异常）（801）
					2. Catching an Exception（捕获异常）（804）
					3. Function try Blocks and Constructors（函数  try  块和构造函数）（806）
					4. The noexcept Exception Specification（noexcept  异常规范）（808）
					5. Exception Class Hierarchies（异常类层次结构）（811）
				2. Namespaces（命名空间）（814）
					1. Namespace Definitions（命名空间定义）（814）
					2. Using Namespace Members（使用命名空间成员）（821）
					3. Classes, Namespaces, and Scope（类、命名空间和范围）（825）
					4. Overloading and Namespaces（重载和命名空间）（829）
				3. Multiple and Virtual Inheritance（多重继承和虚拟继承）（831）
					1. Multiple Inheritance（多重继承）（832）
					2. Conversions and Multiple Base Classes（转换和多个基类）（834）
					3. Class Scope under Multiple Inheritance（多重继承下的类作用域）（836）
					4. Virtual Inheritance（虚拟继承）（839）
					5. Constructors and Virtual Inheritance（构造函数和虚拟继承）（842）
				4. Chapter Summary（章节总结）（845）
				5. Defined Terms（术语定义）（845）
			3. Specialized Tools and Techniques（专业工具和技术）（848）
				1. Controlling Memory Allocation（控制内存分配）（849）
					1. Overloading new and delete（重载  new  和删除）（849）
					2. Placement new Expressions（放置新表达式）（852）
				2. Run-Time Type Identification（运行时类型识别）（854）
					1. The dynamic_cast Operator（dynamic_cast  运算符）（854）
					2. The typeid Operator（typeid  运算符）（855）
					3. Using RTTI（使用RTTI）（857）
					4. The type_info Class（type_info  类）（860）
				3. Enumerations（枚举）（861）
				4. Pointer to Class Member（指向类成员的指针）（864）
					1. Pointers to Data Members（指向数据成员的指针）（865）
					2. Pointers to Member Functions（指向成员函数的指针）（867）
					3. Using Member Functions as Callable Objects（使用成员函数作为可调用对象）（870）
				5. Nested Classes（嵌套类）（872）
				6. union: A Space-Saving Class（union：节省空间的类别）（876）
				7. Local Classes（本地类）（881）
				8. Inherently Nonportable Features（固有的不可移植特性）（883）
					1. Bit-fields（位域）（883）
					2. volatile Qualifier（不稳定的限定符）（885）
					3. Linkage Directives: extern "C"（链接指令：extern "C"）（886）
				9. Chapter Summary（章节总结）（891）
				10. Defined Terms（术语定义）（891）
	3. Effective C++（高效  C++）
		1. Accustoming Yourself to C++（习惯  C++）（36）
			1. Item 1: View C++ as a federation of languages（第  1  项：将  C++  视为语言联盟）（36）
			2. Item 2: Prefer consts, enums, and inlines to #defines（第 2 项：优先使用 const、枚举和内联而不是 #defines）（38）
			3. Item 3: Use const whenever possible（第 3 条：尽可能使用 const）（43）
				1. const Member Functions（const 成员函数）（46）
				2. Avoiding Duplication in const and Non-const Member Functions（避免 const 和非常量成员函数中的重复）（50）
			4. Item 4: Make sure that objects are initialized before they're used（第 4 项：确保对象在使用前已初始化）（53）
		2. Constructors, Destructors, and Assignment Operators（构造函数、析构函数和赋值运算符）（63）
			1. Item 5: Know what functions C++ silently writes and calls（第  5  项：了解  C++  默默编写和调用哪些函数）（63）
			2. Item 6: Explicitly disallow the use of compiler-generated functions you do not want（第 6 项：明确禁止使用您不想要的编译器生成的函数）（67）
			3. Item 7: Declare destructors virtual in polymorphic base classes（第  7  项：在多态基类中将析构函数声明为  virtual）（70）
			4. Item 8: Prevent exceptions from leaving destructors（第  8  项：防止异常离开析构函数）（75）
			5. Item 9: Never call virtual functions during construction or destruction（第  9  条：在构造或销毁期间切勿调用虚函数）（80）
			6. Item 10: Have assignment operators return a reference to *this（第 10 项：让赋值运算符返回对 *this 的引用）（84）
			7. Item 11: Handle assignment to self in operator=（第11 项：处理operator= 中对self 的赋值。）（86）
			8. Item 12: Copy all parts of an object（第  12  项：复制对象的所有部分）（90）
		3. Resource Management（资源管理）（95）
			1. Item 13: Use objects to manage resources（第  13  项：使用对象来管理资源）（95）
			2. Item 14: Think carefully about copying behavior in resource-managing classes（第 14 项：仔细考虑资源管理类中的复制行为）（101）
			3. Item 15: Provide access to raw resources in resource-managing classes（第 15 项：提供对资源管理类中原始资源的访问）（104）
			4. Item 16: Use the same form in corresponding uses of new and delete（第16条：在new和delete的相应使用中使用相同的形式）（109）
			5. Item 17: Store newed objects in smart pointers in standalone statements（第 17 项：将新对象存储在独立语句中的智能指针中）（112）
		4. Designs and Declarations（设计和声明）（115）
			1. Item 18: Make interfaces easy to use correctly and hard to use incorrectly（第 18 条：使界面易于正确使用且难以错误使用）（115）
			2. Item 19: Treat class design as type design（第  19  条：将类设计视为类型设计）（121）
			3. Item 20: Prefer pass-by-reference-to-const to pass-by-value（第 20 项：更喜欢通过引用传递常量而不是通过值传递）（124）
			4. Item 21: Don't try to return a reference when you must return an object（第 21 条：当必须返回对象时不要尝试返回引用）（129）
			5. Item 22: Declare data members private（第 22 项：将数据成员声明为私有）（134）
			6. Item 23: Prefer non-member non-friend functions to member functions（第 23 项：优先选择非成员非友元函数而不是成员函数）（138）
			7. Item 24: Declare non-member functions when type conversions should apply to all parameters（第 24 项：当类型转换应应用于所有参数时声明非成员函数）（142）
			8. Item 25: Consider support for a non-throwing swap（第 25 项：考虑支持非抛出交换）（147）
		5. Implementations（实施）（156）
			1. Item 26: Postpone variable definitions as long as possible（第  26  项：尽可能推迟变量定义）（156）
			2. Item 27: Minimize casting（第  27  条：尽量减少铸造）（159）
			3. Item 28: Avoid returning “handles” to object internals（第  28  条：避免将“句柄”返回到对象内部）（168）
			4. Item 29: Strive for exception-safe code（第  29  条：争取异常安全的代码）（172）
			5. Item 30: Understand the ins and outs of inlining（第  30  项：了解内联的来龙去脉）（180）
			6. Item 31: Minimize compilation dependencies between files（第  31  项：最小化文件之间的编译依赖关系）（187）
		6. Inheritance and Object-Oriented Design（继承和面向对象设计）（198）
			1. Item 32: Make sure public inheritance models “is-a.”（第  32  项：确保公共继承模型“is‑a”）（198）
			2. Item 33: Avoid hiding inherited names（第  33  项：避免隐藏继承的名称）（205）
			3. Item 34: Differentiate between inheritance of interface and inheritance of implementation（第34条：接口继承和实现继承的区别）（213）
			4. Item 35: Consider alternatives to virtual functions（第  35  项：考虑虚拟函数的替代方案）（222）
				1. The Template Method Pattern via the Non-Virtual Interface Idiom（通过非虚拟接口惯用法的模板方法模式）（223）
				2. The Strategy Pattern via Function Pointers（通过函数指针的策略模式）（225）
				3. The Strategy Pattern via tr1::function（通过 tr1::function 的策略模式）（227）
				4. The “Classic” Strategy Pattern（“经典”策略模式）（230）
				5. Summary（概括）（231）
			5. Item 36: Never redefine an inherited non-virtual function（第  36  条：永远不要重新定义继承的非虚函数）（232）
			6. Item 37: Never redefine a function's inherited default parameter value（第 37 条：永远不要重新定义函数继承的默认参数值）（235）
			7. Item 38: Model “has-a” or “is-implemented-in-terms-of” through composition（第 38 项：模型通过组合“has-a”或“is-implemented-in terms-of”）（239）
			8. Item 39: Use private inheritance judiciously（第  39  条：明智地使用私有继承）（243）
			9. Item 40: Use multiple inheritance judiciously（第 40 条：明智地使用多重继承）（249）
		7. Templates and Generic Programming（模板和通用编程）（258）
			1. Item 41: Understand implicit interfaces and compile-time polymorphism（第 41 项：理解隐式接口和编译时多态性）（258）
			2. Item 42: Understand the two meanings of typename（第 42 条：理解 typename 的两种含义）（262）
			3. Item 43: Know how to access names in templatized base classes（第 43 项：了解如何访问模板化基类中的名称）（267）
			4. Item 44: Factor parameter-independent code out of templates（第 44 项：从模板中提取与参数无关的代码）（273）
			5. Item 45: Use member function templates to accept “all compatible types.”（第 45 项：使用成员函数模板接受“所有兼容类型”。）（279）
			6. Item 46: Define non-member functions inside templates when type conversions are desired（第 46 项：当需要类型转换时，在模板内定义非成员函数）（284）
			7. Item 47: Use traits classes for information about types（第 47 项：使用特征类获取有关类型的信息）（289）
			8. Item 48: Be aware of template metaprogramming（第  48  项：注意模板元编程）（297）
		8. Customizing new and delete（自定义新建和删除）（304）
			1. Item 49: Understand the behavior of the new-handler（第  49  项：了解新处理程序的行为）（304）
			2. Item 50: Understand when it makes sense to replace new and delete（第 50 项：了解何时替换新的和删除有意义）（313）
			3. Item 51: Adhere to convention when writing new and delete（第51条：写入new和delete时遵守约定）（318）
			4. Item 52: Write placement delete if you write placement new（第 52 项：如果写入新的展示位置，则写入删除）（323）
		9. Miscellany（杂项）（331）
			1. Item 53: Pay attention to compiler warnings（第 53 条：注意编译器警告）（331）
			2. Item 54: Familiarize yourself with the standard library, including TR1（第 54 项：熟悉标准库，包括 TR1）（332）
			3. Item 55: Familiarize yourself with Boost（第 55 项：熟悉 Boost）（338）
	4. C++ Coding Standards（C++编程规范）
		1. Organizational and Policy Issues（组织和政策问题）（18）
			1. Don’t sweat the small stuff. (Or: Know what not to standardize.)（不要为小事而烦恼。 （或者：知道什么不应该标准化。））（19）
			2. Compile cleanly at high warning levels.（在高警告级别干净地编译。）（21）
			3. Use an automated build system.（使用自动构建系统。）（24）
			4. Use a version control system.（使用版本控制系统。）（25）
			5. Invest in code reviews.（投资于代码审查。）（26）
		2. Design Style（设计风格）（28）
			1. Give one entity one cohesive responsibility.（赋予一个实体一项凝聚力责任。）（29）
			2. Correctness, simplicity, and clarity come first.（正确、简单、清晰是第一位的。）（30）
			3. Know when and how to code for scalability.（了解何时以及如何编码以实现可扩展性。）（31）
			4. Don’t optimize prematurely.（不要过早优化。）（33）
			5. Don’t pessimize prematurely（不要过早悲观。）（35）
			6. Minimize global and shared data.（尽量减少全局和共享数据。）（36）
			7. Hide information.（隐藏信息。）（37）
			8. Know when and how to code for concurrency.（了解何时以及如何编写并发代码。）（38）
			9. Ensure resources are owned by objects. Use explicit RAII and smart pointers（确保资源归对象所有。 使用显式 RAII 和智能指针）（41）
		3. Coding Style（编码风格）（44）
			1. Prefer compile- and link-time errors to run-time errors.（与运行时错误相比，更喜欢编译时和链接时错误。）（45）
			2. Use const proactively.（主动使用const。）（47）
			3. Avoid macros.（避免宏。）（49）
			4. Avoid magic numbers.（避免使用幻数。）（51）
			5. Declare variables as locally as possible.（尽可能在本地声明变量。）（52）
			6. Always initialize variables.（始终初始化变量。）（53）
			7. Avoid long functions. Avoid deep nesting.（避免长函数。避免深层嵌套。）（55）
			8. Avoid initialization dependencies across compilation units.（避免跨编译单元的初始化依赖性。）（56）
			9. Minimize definitional dependencies. Avoid cyclic dependencies（最小化定义依赖性。 避免循环依赖）（57）
			10. Make header files self-sufficient.（使头文件自给自足。）（59）
			11. Always write internal #include guards. Never write external #include guards（始终编写内部#include 防护。 切勿编写外部#include 防护）（60）
		4. Functions and Operators（函数和运算符）（62）
			1. Take parameters appropriately by value, (smart) pointer, or reference.（通过值、（智能）指针或引用适当地获取参数。）（63）
			2. Preserve natural semantics for overloaded operators.（保留重载运算符的自然语义。）（64）
			3. Prefer the canonical forms of arithmetic and assignment operators（更喜欢算术和赋值运算符的规范形式）（65）
			4. Prefer the canonical form of ++ and --.Prefer calling the prefix forms.（更喜欢 ++ 和 -- 的规范形式。更喜欢调用前缀形式。）（67）
			5. Consider overloading to avoid implicit type conversions（考虑重载以避免隐式类型转换）（68）
			6. Avoid overloading &&, ||, or , (comma) .（避免重载  &&、||  或 ,（逗号）。）（69）
			7. Don’t write code that depends on the order of evaluation of function arguments（不要编写依赖于函数参数求值顺序的代码）（71）
		5. Class Design and Inheritance（类的设计与继承）（72）
			1. Be clear what kind of class you’re writing.（明确你正在写什么样的课程。）（73）
			2. Prefer minimal classes to monolithic classes.（优先选择最小类而不是整体类。）（74）
			3. Prefer composition to inheritance.（更喜欢组合而不是继承。）（75）
			4. Avoid inheriting from classes that were not designed to be base classes（避免从不是设计为基类的类继承）（77）
			5. Prefer providing abstract interfaces.（更喜欢提供抽象接口。）（79）
			6. Public inheritance is substitutability. Inherit, not to reuse, but to be reused.（公共继承是可替代性的。 继承，不是为了重用，而是为了被重用。）（81）
			7. Practice safe overriding.（练习安全覆盖。）（83）
			8. Consider making virtual functions nonpublic, and public functions nonvirtual.（考虑将虚拟函数设置为非公共函数，将公共函数设置为非虚拟函数。）（85）
			9. Avoid providing implicit conversions.（避免提供隐式转换。）（87）
			10. Make data members private, except in behaviorless aggregates (C-style structs)（将数据成员设置为私有，无行为聚合（C 风格结构）除外）（89）
			11. Don’t give away your internals.（不要泄露你的内心。）（91）
			12. Pimpl judiciously.（明智地粉刺。）（93）
			13. Prefer writing nonmember nonfriend functions（更喜欢编写非成员非友元函数）（96）
			14. Always provide new and delete together.（更喜欢编写非成员非友元函数。）（97）
			15. If you provide any class-specific new, provide all of the standard forms (plain, in-place, and nothrow)（如果您提供任何特定于类的新内容，请提供所有标准形式（普通、就地和无抛出））（99）
		6. Construction, Destruction, and Copying（构造、破坏和复制）（102）
			1. Define and initialize member variables in the same order.（以相同的顺序定义和初始化成员变量。）（103）
			2. Prefer initialization to assignment in constructors（在构造函数中优先进行初始化而不是赋值）（104）
			3. Avoid calling virtual functions in constructors and destructors（避免在构造函数和析构函数中调用虚函数）（105）
			4. Make base class destructors public and virtual, or protected and nonvirtual（使基类析构函数成为公共和虚拟的，或受保护的和非虚拟的）（107）
			5. Destructors, deallocation, and swap never fail（析构函数、释放和交换永远不会失败）（109）
			6. Copy and destroy consistently.（持续复制和销毁。）（111）
			7. Explicitly enable or disable copying.（明确启用或禁用复制。）（112）
			8. Avoid slicing. Consider Clone instead of copying in base classes.（避免切片。 考虑克隆而不是在基类中进行复制。）（113）
			9. Prefer the canonical form of assignment.（更喜欢规范的赋值形式。）（116）
			10. Whenever it makes sense, provide a no-fail swap (and provide it correctly).（只要有意义，就提供无失败交换（并正确提供）。）（117）
		7. Namespaces and Modules（命名空间和模块）（120）
			1. Keep a type and its nonmember function interface in the same namespace.（将类型及其非成员函数接口保留在同一命名空间中。）（121）
			2. Keep types and functions in separate name-spaces unless they’re specifically intended to work together.（将类型和函数保留在单独的名称空间中，除非它们专门打算一起工作。）（123）
			3. Don’t write namespace usings in a header file or before an #include（不要在头文件中或 #include 之前编写命名空间 using）（125）
			4.  Avoid allocating and deallocating memory in different modules.（避免在不同模块中分配和释放内存。）（128）
			5.  Don’t define entities with linkage in a header file（不要在头文件中定义具有链接的实体）（129）
			6. Don’t allow exceptions to propagate across module boundaries（不允许异常跨模块边界传播）（131）
			7. Use sufficiently portable types in a module’s interface（在模块的接口中使用足够可移植的类型）（133）
		8. Templates and Genericity（模板和通用性）（136）
			1. Blend static and dynamic polymorphism judiciously（明智地混合静态和动态多态性）（137）
			2. Customize intentionally and explicitly.（有意且明确地定制。）（139）
			3. Don’t specialize function templates.（不要专门化函数模板。）（143）
			4. Don’t write unintentionally nongeneric code.（不要无意中编写非泛型代码。）（不要无意中编写非泛型代码。）（145）
		9. Error Handling and Exceptions（错误处理和异常）（146）
			1. Assert liberally to document internal assumptions and invariants（Assert liberally to document internal assumptions and invariants）（147）
			2. Establish a rational error handling policy, and follow it strictly（建立合理的错误处理政策，并严格遵守）（149）
			3. Distinguish between errors and non-errors.（区分错误和非错误。）（151）
			4. Design and write error-safe code.（设计和编写防错代码。）（154）
			5. Prefer to use exceptions to report errors.（喜欢使用异常来报告错误。）（157）
			6. Throw by value, catch by reference.（按值抛出，按引用捕获。）（161）
			7. Report, handle, and translate errors appropriately（适当地报告、处理和翻译错误）（162）
			8. Avoid exception specifications.（避免异常规范。）（163）
		10. STL: Containers（STL：容器）（166）
			1. Use vector by default. Otherwise, choose an appropriate container.（默认使用矢量。 否则，请选择合适的容器。）（167）
			2. Use vector and string instead of arrays.（使用向量和字符串代替数组。）（169）
			3. Use vector (and string::c_str) to exchange data with non-C++ APIs.（使用向量（和 string::c_str）与非 C++ API 交换数据。）（170）
			4.  Store only values and smart pointers in containers.（仅将值和智能指针存储在容器中。）（171）
			5. Prefer push_back to other ways of expanding a sequence.（与其他扩展序列的方法相比，更喜欢使用 Push_back。）（172）
			6. Prefer range operations to single-element operations（优先选择范围操作而不是单元素操作）（173）
			7. Use the accepted idioms to really shrink capacity and really erase elements.（使用公认的习惯用法来真正缩小容量并真正删除元素。）（174）
		11. STL: Algorithms（STL：算法）（176）
			1. Use a checked STL implementation.（使用经过检查的  STL  实现。）（177）
			2. Prefer algorithm calls to handwritten loops.（更喜欢算法调用而不是手写循环。）（179）
			3. Use the right STL search algorithm.（使用正确的STL搜索算法。）（182）
			4. Use the right STL sort algorithm.（使用正确的STL排序算法。）（183）
			5. Make predicates pure functions.（将谓词设为纯函数。）（185）
			6. Prefer function objects over functions as algorithm and comparer arguments.（与函数相比，更喜欢将函数对象作为算法和比较器参数。）（187）
			7. Write function objects correctly.（正确编写函数对象。）（189）
		12. Type Safety（类型安全）（190）
			1. Avoid type switching; prefer polymorphism.（避免类型转换；更喜欢多态性。）（191）
			2. Rely on types, not on representations.（依靠类型，而不是表征。）（193）
			3. Avoid using reinterpret_cast.（避免使用reinterpret_cast。）（194）
			4. Avoid using static_cast on pointers.（避免在指针上使用  static_cast。）（195）
			5. Avoid casting away const.（避免抛弃  const。）（196）
			6. Don’t use C-style casts.（不要使用C  风格的强制转换。）（196）
			7. Don’t memcpy or memcmp non-PODs.（不要使用  memcpy  或  memcmp  非  POD。）（199）
			8. Don’t use unions to reinterpret representation.（不要使用联合来重新解释表示。）（200）
			9. Don’t use varargs (ellipsis).（不要使用可变参数（省略号）。）（201）
			10. Don’t use invalid objects. Don’t use unsafe functions.（不要使用无效的对象。 不要使用不安全的函数。）（202）
			11. Don’t treat arrays polymorphically.（不要以多态方式对待数组。）（203）
	5. The C++ Standard Library（C++标准库）
		1. About This Book（关于本书）（30）
			1. Why This Book（为什么选择这本书）（30）
			2. Before Reading This Book（阅读本书之前）（31）
			3. Style and Structure of the Book（本书的风格和结构）（31）
			4. How to Read This Book（如何阅读本书）（33）
			5. State of the Art（最新技术）（34）
			6. Example Code and Additional Information（示例代码和附加信息）（34）
			7. Feedback（反馈）（34）
		2. Introduction to C++ and the Standard Library（C++ 和标准库简介）（36）
			1. History of the C++ Standards（C++  标准的历史）（36）
				1. Common Questions about the C++11 Standard（有关  C++11  标准的常见问题）（37）
				2. Compatibility between C++98 and C++11（C++98  和  C++11  之间的兼容性）（38）
			2. Complexity and Big-O Notation（复杂性和大O表示法）（39）
		3. New Language Features（新的语言特性）（42）
			1. New C++11 Language Features（C++11  语言新特性）（42）
				1. Important Minor Syntax Cleanups（重要的次要语法清理）（42）
				2. Automatic Type Deduction with auto（使用  auto  进行自动类型推导）（43）
				3. Uniform Initialization and Initializer Lists（统一初始化和初始化器列表）（44）
				4. Range-Based for Loops（基于范围的  for  循环）（46）
				5. Move Semantics and Rvalue References（移动语义和右值引用）（48）
				6. New String Literals（新字符串文字）（52）
				7. Keyword noexcept（关键字noexcept）（53）
				8. Keyword constexpr（关键字  constexpr）（55）
				9. New Template Features（新模板功能）（55）
				10. Lambdas（Lambda  表达式）（57）
				11. Keyword decltype（关键字  decltype）（61）
				12. New Function Declaration Syntax（新函数声明语法）（61）
				13. Scoped Enumerations（作用域枚举）（61）
				14. New Fundamental Data Types（新的基本数据类型）（62）
			2. Old “New” Language Features（旧的“新”语言特征）（62）
				1. Explicit Initialization for Fundamental Types（基本类型的显式初始化）（66）
				2. Definition of main()（main()的定义）（66）
		4. General Concepts（一般概念）（68）
			1. Namespace std（命名空间标准）（68）
			2. Header Files（头文件）（69）
			3. Error and Exception Handling（错误和异常处理）（70）
				1. Standard Exception Classes（标准异常类）（70）
				2. Members of Exception Classes（异常类的成员）（73）
				3. Passing Exceptions with Class exception_ptr（使用类  exception_ptr  传递异常）（81）
				4. Throwing Standard Exceptions（抛出标准异常）（82）
				5. Deriving from Standard Exception Classes（从标准异常类派生）（83）
			4. Callable Objects（可调用对象）（83）
			5. Concurrency and Multithreading（并发和多线程）（84）
			6. Allocators（分配器）（86）
		5. Utilities（公用事业）（88）
			1. Pairs and Tuples（对和元组）（89）
				1. Pairs（配对）（89）
				2. Tuples（元组）（97）
				3. I/O for Tuples（元组的  I/O）（103）
				4. Conversions between tuples and pairs（元组和对之间的转换）（104）
			2. Smart Pointers（智能指针）（105）
				1. Class shared_ptr（类shared_ptr）（105）
				2. Class weak_ptr（类weak_ptr）（113）
				3. Misusing Shared Pointers（滥用共享指针）（118）
				4. Shared and Weak Pointers in Detail（共享指针和弱指针详细信息）（121）
				5. Class unique_ptr（类  unique_ptr）（127）
				6. Class unique_ptr in Detail（unique_ptr  类详细信息）（139）
				7. Class auto_ptr（类  auto_ptr）（142）
				8. Final Words on Smart Pointers（关于智能指针的最后一句话）（143）
			3. Numeric Limits（数值限制）（144）
			4. Type Traits and Type Utilities（类型特征和类型实用程序）（151）
				1. Purpose of Type Traits（类型特征的目的）（151）
				2. Type Traits in Detail（类型特征详细信息）（154）
				3. Reference Wrappers（参考包装器）（161）
				4. Function Type Wrappers（函数类型包装器）（162）
			5. Auxiliary Functions（辅助功能）（163）
				1. Processing the Minimum and Maximum（处理最小值和最大值）（163）
				2. Swapping Two Values（交换两个值）（165）
				3. Supplementary Comparison Operators（补充比较运算符）（167）
			6. Compile-Time Fractional Arithmetic with Class ratio<>（具有类比<>的编译时小数算术）（169）
			7. Clocks and Timers（时钟和定时器）（172）
				1. Overview of the Chrono Library（Chrono  库概述）（172）
				2. Durations（持续时间）（173）
				3. Clocks and Timepoints（时钟和时间点）（178）
				4. Date and Time Functions by C and POSIX（C  和  POSIX  的日期和时间函数）（186）
				5. Blocking with Timers（用定时器阻塞）（189）
			8. Header Files < cstddef>, < cstdlib>, and < cstring>（头文件 < cstddef>、< cstdlib> 和 < cstring>）（190）
				1. Definitions in < cstddef>（< cstddef>中的定义）（190）
				2. Definitions in < cstdlib>（< cstdlib>中的定义）（191）
				3. Definitions in < cstring>（< cstring>中的定义）（192）
		6. The Standard Template Library（标准模板库）（194）
			1. STL Components（STL组件）（194）
			2. Containers（容器）（196）
				1. Sequence Containers（序列容器）（198）
				2. Associative Containers（关联容器）（206）
				3. Unordered Containers（无序容器）（209）
				4. Associative Arrays（关联数组）（214）
				5. Other Containers（其他容器）（216）
				6. Container Adapters（容器适配器）（217）
			3. Iterators（迭代器）（217）
				1. Further Examples of Using Associative and Unordered Containers（使用关联和无序容器的更多示例）（222）
				2. Iterator Categories（迭代器类别）（227）
			4. Algorithms（算法）（228）
				1. Ranges（范围）（232）
				2. Handling Multiple Ranges（处理多个范围）（236）
			5. Iterator Adapters（迭代器适配器）（239）
				1. Insert Iterators（插入迭代器）（239）
				2. Stream Iterators（流迭代器）（241）
				3. Reverse Iterators（反向迭代器）（243）
				4. Move Iterators（移动迭代器）（245）
			6. User-Defined Generic Functions（用户定义的通用函数）（245）
			7. Manipulating Algorithms（操纵算法）（246）
				1. “Removing” Elements（“删除”元素）（247）
				2. Manipulating Associative and Unordered Containers（操作关联和无序容器）（250）
				3. Algorithms versus Member Functions（算法与成员函数）（252）
			8. Functions as Algorithm Arguments（函数作为算法参数）（253）
				1. Using Functions as Algorithm Arguments（使用函数作为算法参数）（253）
				2. Predicates（谓词）（255）
			9. Using Lambdas（使用  Lambda  表达式）（258）
			10. Function Objects（函数对象）（262）
				1. Definition of Function Objects（函数对象的定义）（262）
				2. Predefined Function Objects（预定义函数对象）（268）
				3. Binders（粘合剂）（270）
				4. Function Objects and Binders versus Lambdas（函数对象和绑定器与  Lambda）（272）
			11. Container Elements（容器元素）（273）
				1. Requirements for Container Elements（容器元素的要求）（273）
				2. Value Semantics or Reference Semantics（值语义或引用语义）（274）
			12. Errors and Exceptions inside the STL（STL内部的错误和异常）（274）
				1. Error Handling（错误处理）（275）
				2. Exception Handling（异常处理）（277）
			13. Extending the STL（扩展STL）（279）
				1. Integrating Additional Types（集成附加类型）（279）
				2. Deriving from STL Types（从  STL  类型派生）
		7. STL Containers（STL容器）（282）
			1. Common Container Abilities and Operations（常用容器能力及操作）（283）
				1. Container Abilities（容器能力）（283）
				2. Container Operations（容器操作）（283）
				3. Container Types（容器类型）（289）
			2. Arrays（数组）（290）
				1. Abilities of Arrays（数组的能力）（290）
				2. Array Operations（数组操作）（292）
				3. Using arrays as C-Style Arrays（将数组用作  C  样式数组）（296）
				4. Exception Handling（异常处理）（297）
				5. Tuple Interface（元组接口）（297）
				6. Examples of Using Arrays（使用数组的⽰例）（297）
			3. Vectors（向量）（299）
				1. Abilities of Vectors（向量的能力）（299）
				2. Vector Operations（向量运算）（302）
				3. Using Vectors as C-Style Arrays（将向量用作  C  样式数组）（307）
				4. Exception Handling（异常处理）（307）
				5. Examples of Using Vectors（使用向量的示例）（308）
				6. Class vector< bool>（类向量< bool>）（310）
			4. Deques（双端队列）（312）
				1. Abilities of Deques（双端队列的能力）（313）
				2. Deque Operations（双端队列操作）（314）
				3. Exception Handling（异常处理）（317）
				4. Examples of Using Deques（使用双端队列的示例）（317）
			5. Lists（列表）（319）
				1. Abilities of Lists（列表的能力）（319）
				2. List Operations（列表操作）（320）
				3. Exception Handling（异常处理）（325）
				4. Examples of Using Lists（使用列表的示例）（327）
			6. Forward Lists（转发列表）（329）
				1. Abilities of Forward Lists（转发列表的功能）（329）
				2. Forward List Operations（转发列表操作）（331）
				3. Exception Handling（异常处理）（340）
				4. Examples of Using Forward Lists（使用转发列表的示例）（341）
			7. Sets and Multisets（集合和多重集合）（343）
				1. Abilities of Sets and Multisets（集合和多重集合的能力）（344）
				2. Set and Multiset Operations（集合和多重集合操作）（345）
				3. Exception Handling（异常处理）（354）
				4. Examples of Using Sets and Multisets（使用集合和多重集合的示例）（354）
				5. Example of Specifying the Sorting Criterion at Runtime（在运行时指定排序标准的示例）（357）
			8. Maps and Multimaps（映射和多重映射）（360）
				1. Abilities of Maps and Multimaps（地图和多重地图的功能）（361）
				2. Map and Multimap Operations（映射和多重映射操作）（362）
				3. Using Maps as Associative Arrays（使用映射作为关联数组）（372）
				4. Exception Handling（异常处理）（374）
				5. Examples of Using Maps and Multimaps（使用映射和多重映射的示例）（374）
				6. Example with Maps, Strings, and Sorting Criterion at Runtime（运行时的映射、字符串和排序标准示例）（380）
			9. Unordered Containers（无序容器）（384）
				1. Abilities of Unordered Containers（无序容器的能力）（386）
				2. Creating and Controlling Unordered Containers（创建和控制无序容器）（388）
				3. Other Operations for Unordered Containers（无序容器的其他操作）（396）
				4. The Bucket Interface（桶接口）（403）
				5. Using Unordered Maps as Associative Arrays（使用无序映射作为关联数组）（403）
				6. Exception Handling（异常处理）（404）
				7. Examples of Using Unordered Containers（使用无序容器的示例）（404）
			10. Other STL Containers（其他STL容器）（414）
				1. Strings as STL Containers（字符串作为  STL  容器）（414）
				2. Ordinary C-Style Arrays as STL Containers（普通  C  风格数组作为  STL  容器）（415）
			11. Implementing Reference Semantics（实现参考语义）（417）
			12. When to Use Which Container（何时使用哪个容器）（421）
		8. STL Container Members in Detail（STL容器成员详细信息）（426）
			1. Type Definitions（类型定义）（426）
			2. Create, Copy, and Destroy Operations（创建、复制和销毁操作）（429）
			3. Nonmodifying Operations（⾮修改操作）（432）
				1. Size Operations（尺寸操作）（432）
				2. Comparison Operations（比较运算）（433）
				3. Nonmodifying Operations for Associative and Unordered Containers（关联容器和无序容器的非修改操作）（433）
			4. Assignments（作业）（435）
			5. Direct Element Access（直接元素访问）（437）
			6. Operations to Generate Iterators（生成迭代器的操作）（439）
			7. Inserting and Removing Elements（插入和删除元素）（440）
				1. Inserting Single Elements（插入单个元素）（440）
				2. Inserting Multiple Elements（插入多个元素）（445）
				3. Removing Elements（删除元素）（446）
				4. Resizing（调整大小）（449）
			8. Special Member Functions for Lists and Forward Lists（列表和转发列表的特殊成员函数）（449）
				1. Special Member Functions for Lists (and Forward Lists)（列表（和转发列表）的特殊成员函数）（449）
				2. Special Member Functions for Forward Lists Only（仅用于转发列表的特殊成员函数）（452）
			9. Container Policy Interfaces（容器策略接口）（456）
				1. Nonmodifying Policy Functions（不可修改的策略函数）（456）
				2. Modifying Policy Functions（修改策略函数）（457）
				3. Bucket Interface for Unordered Containers（无序容器的桶接口）（458）
			10. Allocator Support（分配器支持）（459）
				1. Fundamental Allocator Members（基本分配器成员）（459）
				2. Constructors with Optional Allocator Parameters（具有可选分配器参数的构造函数）（459）
		9. STL Iterators（STL迭代器）（462）
			1. Header Files for Iterators（迭代器的头文件）（462）
			2. Iterator Categories（迭代器类别）（462）
				1. Output Iterators（输出迭代器）（462）
				2. Input Iterators（输入迭代器）（464）
				3. Forward Iterators（前向迭代器）（465）
				4. Bidirectional Iterators（双向迭代器）（466）
				5. Random-Access Iterators（随机访问迭代器）（467）
				6. The Increment and Decrement Problem of Vector Iterators（向量迭代器的自增和自减问题）（469）
			3. Auxiliary Iterator Functions（辅助迭代器函数）（470）
				1. advance()（470）
				2. next() and prev()（472）
				3. distance()（474）
				4. iter_swap()（475）
			4. Iterator Adapters（迭代器适配器）（447）
				1. Reverse Iterators（反向迭代器）（477）
				2. Insert Iterators（插入迭代器）（483）
				3. Stream Iterators（流迭代器）（489）
				4. Move Iterators（移动迭代器）（495）
			5. Iterator Traits（迭代器特征）（495）
				1. Writing Generic Functions for Iterators（为迭代器编写泛型函数）（497）
			6. Writing User-Defined Iterators（编写用户定义的迭代器）（500）
		10. STL Function Objects and Using Lambdas（STL 函数对象和使用 Lambda）（504）
			1. The Concept of Function Objects（函数对象的概念）（504）
				1. Function Objects as Sorting Criteria（函数对象作为排序标准）（505）
				2. Function Objects with Internal State（具有内部状态的函数对象）（507）
				3. The Return Value of for_each()（for_each()的返回值）（511）
				4. Predicates versus Function Objects（谓词与函数对象）（512）
			2. Predefined Function Objects and Binders（预定义函数对象和绑定器）（515）
				1. Predefined Function Objects（预定义函数对象）（515）
				2. Function Adapters and Binders（函数适配器和绑定器）（516）
				3. User-Defined Function Objects for Function Adapters（函数适配器的用户定义函数对象）（524）
				4. Deprecated Function Adapters（已弃用的函数适配器）（526）
			3. Using Lambdas（使用  Lambda  表达式）（528）
				1. Lambdas versus Binders（Lambda  与  Binder）（528）
				2. Lambdas versus Stateful Function Objects（Lambda  与有状态函数对象）（529）
				3. Lambdas Calling Global and Member Functions（Lambda  调用全局函数和成员函数）（531）
				4. Lambdas as Hash Function, Sorting, or Equivalence Criterion（Lambda 作为哈希函数、排序或等价标准）（533）
		11. STL Algorithms（STL算法）（534）
			1. Algorithm Header Files（算法头文件）（534）
			2. Algorithm Overview（算法概述）（534）
				1. A Brief Introduction（简介）（535）
				2. Classification of Algorithms（算法分类）（535）
			3. Auxiliary Functions（辅助功能）（546）
			4. The for_each() Algorithm（for_each()算法）（548）
			5. Nonmodifying Algorithms（不可修改算法）（553）
				1. Counting Elements（计数元素）（553）
				2. Minimum and Maximum（最小值和最大值）（554）
				3. Searching Elements（搜索元素）（557）
				4. Comparing Ranges（比较范围）（571）
				5. Predicates for Ranges（范围谓词）（579）
			6. Modifying Algorithms（修改算法）（586）
				1. Copying Elements（复制元素）（586）
				2. Moving Elements（移动元素）（590）
				3. Transforming and Combining Elements（转换和组合元素）（592）
				4. Swapping Elements（交换元素）（595）
				5. Assigning New Values（分配新值）（597）
				6. Replacing Elements（替换元件）（600）
			7. Removing Algorithms（删除算法）（604）
				1. Removing Certain Values（删除某些值）（604）
				2. Removing Duplicates（删除重复项）（607）
			8. Mutating Algorithms（变异算法）（612）
				1. Reversing the Order of Elements（颠倒元素的顺序）（612）
				2. Rotating Elements（旋转元件）（613）
				3. Permuting Elements（排列元素）（616）
				4. Shuffling Elements（打乱元素）（618）
				5. Moving Elements to the Front（将元素移到前面）（621）
				6. Partition into Two Subranges（划分为两个子范围）（623）
			9. Sorting Algorithms（排序算法）（625）
				1. Sorting All Elements（对所有元素进行排序）（625）
				2. Partial Sorting（部分排序）（628）
				3. Sorting According to the nth Element（根据第n个元素排序）（631）
				4. Heap Algorithms（堆算法）（633）
			10. Sorted-Range Algorithms（排序范围算法）（637）
				1. Searching Elements（搜索元素）（637）
				2. Merging Elements（合并元素）（643）
			11. Numeric Algorithms（数值算法）（652）
				1. Processing Results（处理结果）（652）
				2. Converting Relative and Absolute Values（相对值和绝对值的转换）（656）
		12. Special Containers（特种集装箱）（660）
			1. Stacks（堆栈）（661）
				1. The Core Interface（核心接口）（662）
				2. Example of Using Stacks（使用堆栈的示例）（662）
				3. A User-Defined Stack Class（用户定义的堆栈类）（664）
				4. Class stack<> in Detail（类堆栈<>详细信息）（666）
			2. Queues（队列）（667）
				1. The Core Interface（核心接口）（668）
				2. Example of Using Queues（使用队列的示例）（669）
				3. A User-Defined Queue Class（用户定义的队列类）（670）
				4. Class queue<> in Detail（类队列<>详细信息）（670）
			3. Priority Queues（优先级队列）（670）
				1. The Core Interface（核心接口）（672）
				2. Example of Using Priority Queues（使用优先级队列的示例）（672）
				3. Class priority_queue<> in Detail（类priority_queue<>详细信息）（673）
			4. Container Adapters in Detail（容器适配器详细信息）（674）
				1. Type Definitions（类型定义）（674）
				2. Constructors（构造函数）（675）
				3. Supplementary Constructors for Priority Queues（优先级队列的补充构造函数）（675）
				4. Operations（操作）（676）
			5. Bitsets（位集）（679）
				1. Examples of Using Bitsets（使用位集的示例）（680）
				2. Class bitset in Detail（类位集详细信息）（682）
		13. Strings（弦乐）（684）
			1. Purpose of the String Classes（字符串类的用途）（685）
				1. A First Example: Extracting a Temporary Filename（第一个示例：提取临时文件名）（685）
				2. A Second Example: Extracting Words and Printing Them Backward（第二个例子：提取单词并向后打印）（689）
			2. Description of the String Classes（字符串类的描述）（692）
				1. String Types（字符串类型）（692）
				2. Operation Overview（操作概述）（695）
				3. Constructors and Destructor（构造函数和析构函数）（696）
				4. Strings and C-Strings（字符串和  C  字符串）（697）
				5. Size and Capacity（尺寸和容量）（698）
				6. Element Access（元素访问）（700）
				7. Comparisons（比较）（701）
				8. Modifiers（修饰符）（702）
				9. Substrings and String Concatenation（子字符串和字符串连接）（705）
				10. Input/Output Operators（输入/输出运算符）（706）
				11. Searching and Finding（搜索与查找）（707）
				12. The Value npos（价值非营利组织）（709）
				13. Numeric Conversions（数字转换）（710）
				14. Iterator Support for Strings（字符串的迭代器支持）（713）
				15. Internationalization（国际化）（718）
				16. Performance（性能）（721）
				17. Strings and Vectors（字符串和向量）（721）
			3. String Class in Detail（字符串类详细信息）（722）
				1. Type Definitions and Static Values（类型定义和静态值）（722）
				2. Create, Copy, and Destroy Operations（创建、复制和销毁操作）（723）
				3. Operations for Size and Capacity（大小和容量的操作）（725）
				4. Comparisons（比较）（726）
				5. Character Access（字符访问）（728）
				6. Generating C-Strings and Character Arrays（生成  C  字符串和字符数组）（729）
				7. Modifying Operations（修改操作）（729）
				8. Searching and Finding（搜索与查找）（737）
				9. Substrings and String Concatenation（子字符串和字符串连接）（740）
				10. Input/Output Functions（输入/输出功能）（741）
				11. Numeric Conversions（数字转换）（742）
				12. Generating Iterators（生成迭代器）（743）
				13. Allocator Support（分配器支持）（744）
		14. Regular Expressions（常用表达）（746）
			1. The Regex Match and Search Interface（正则表达式匹配和搜索界面）（746）
			2. Dealing with Subexpressions（处理子表达式）（749）
			3. Regex Iterators（正则表达式迭代器）（755）
			4. Regex Token Iterators（正则表达式令牌迭代器）（756）
			5. Replacing Regular Expressions（替换正则表达式）（759）
			6. Regex Flags（正则表达式标志）（761）
			7. Regex Exceptions（正则表达式异常）（764）
			8. The Regex ECMAScript Grammar（正则表达式  ECMAScript  语法）（767）
			9. Other Grammars（其他语法）（768）
			10. Basic Regex Signatures in Detail（基本正则表达式签名详细信息）（769）
		15. Input/Output Using Stream Classes（使用流类的输入/输出）（722）
			1. Common Background of I/O Streams（I/O流的常见背景）（773）
				1. Stream Objects（流对象）（773）
				2. Stream Classes（流类）（773）
				3. Global Stream Objects（全局流对象）（774）
				4. Stream Operators（流运算符）（774）
				5. Manipulators（操纵器）（775）
				6. A Simple Example（一个简单的例子）（775）
			2. Fundamental Stream Classes and Objects（基本流类和对象）（777）
				1. Classes and Class Hierarchy（类和类层次结构）（777）
				2. Global Stream Objects（全局流对象）（780）
				3. Header Files（头文件）（781）
			3. Standard Stream Operators << and >>（标准流运算符<<和>>）（782）
				1. Output Operator <<（输出运算符<<）（782）
				2. Input Operator >>（输入运算符>>）（783）
				3. Input/Output of Special Types（特殊类型的输入/输出）（784）
			4. State of Streams（流的状态）（787）
				1. Constants for the State of Streams（流状态常量）（787）
				2. Member Functions Accessing the State of Streams（访问流状态的成员函数）（788）
				3. Stream State and Boolean Conditions（流状态和布尔条件）（789）
				4. Stream State and Exceptions（流状态和异常）（791）
			5. Standard Input/Output Functions（标准输入/输出功能）（796）
				1. Member Functions for Input（输入成员函数）（797）
				2. Member Functions for Output（输出成员函数）（800）
				3. Example Uses（示例用途）（801）
				4. sentry Objects（哨兵对象）（801）
			6. Manipulators（操纵器）（803）
				1. Overview of All Manipulators（所有操纵器概述）（803）
				2. How Manipulators Work（操纵器如何工作）（805）
				3. User-Defined Manipulators（用户定义的操纵器）（806）
			7. Formatting（格式化）（808）
				1. Format Flags（格式标志）（808）
				2. Input/Output Format of Boolean Values（布尔值的输入/输出格式）（810）
				3. Field Width, Fill Character, and Adjustment（字段宽度、填充字符及调整）（810）
				4. Positive Sign and Uppercase Letters（正号和大写字母）（813）
				5. Numeric Base（数字基数）（814）
				6. Floating-Point Notation（浮点表示法）（816）
				7. General Formatting Definitions（通用格式定义）（818）
			8. Internationalization（国际化）（819）
			9. File Access（文件访问）（820）
				1. File Stream Classes（文件流类）（820）
				2. Rvalue and Move Semantics for File Streams（文件流的右值和移动语义）（824）
				3. File Flags（文件标志）（825）
				4. Random Access（随机访问）（828）
				5. Using File Descriptors（使用文件描述符）（830）
			10. Stream Classes for Strings（字符串的流类）（831）
				1. String Stream Classes（字符串流类）（831）
				2. Move Semantics for String Streams（字符串流的移动语义）（835）
				3. char* Stream Classes（char*  流类）（836）
			11. Input/Output Operators for User-Defined Types（用户定义类型的输入/输出运算符）（839）
				1. Implementing Output Operators（实现输出运算符）（839）
				2. Implementing Input Operators（实现输入运算符）（841）
				3. Input/Output Using Auxiliary Functions（使用辅助功能的输入/输出）（843）
				4. User-Defined Format Flags（用户定义的格式标志）（844）
				5. Conventions for User-Defined Input/Output Operators（用户定义的输入/输出运算符的约定）（847）
			12. Connecting Input and Output Streams（连接输入和输出流）（848）
				1. Loose Coupling Using tie()（使用tie()的松耦合）（848）
				2. Tight Coupling Using Stream Buffers（使用流缓冲区的紧耦合）（849）
				3. Redirecting Standard Streams（重定向标准流）（851）
				4. Streams for Reading and Writing（读写流）（853）
			13. The Stream Buffer Classes（流缓冲区类）（855）
				1. The Stream Buffer Interfaces（流缓冲区接口）（855）
				2. Stream Buffer Iterators（流缓冲区迭代器）（857）
				3. User-Defined Stream Buffers（用户定义的流缓冲区）（861）
			14. Performance Issues（性能问题）（873）
				1. Synchronization with C’s Standard Streams（与C标准流同步）（874）
				2. Buffering in Stream Buffers（流缓冲区中的缓冲）（874）
				3. Using Stream Buffers Directly（直接使用流缓冲区）（875）
		16. Internationalization（国际化）（878）
			1. Character Encodings and Character Sets（字符编码和字符集）（879）
				1. Multibyte and Wide-Character Text（多字节和宽字符文本）（879）
				2. Different Character Sets（不同的字符集）（880）
				3. Dealing with Character Sets in C++（在  C++  中处理字符集）（881）
				4. Character Traits（性格特征）（882）
				5. Internationalization of Special Characters（特殊字符的国际化）（886）
			2. The Concept of Locales（语言环境的概念）（886）
				1. Using Locales（使用语言环境）（887）
				2. Locale Facets（语言环境方面）（893）
			3. Locales in Detail（语言环境详细信息）（895）
			4. Facets in Detail（面详细信息）（898）
				1. Numeric Formatting（数字格式）（899）
				2. Monetary Formatting（货币格式）（903）
				3. Time and Date Formatting（时间和日期格式）（913）
				4. Character Classification and Conversion（字符分类与转换）（920）
				5. String Collation（字符串排序规则）（933）
				6. Internationalized Messages（国际化消息）（934）
		17. Numerics（数值）（936）
			1. Random Numbers and Distributions（随机数和分布）（936）
				1. A First Example（第一个例子）（937）
				2. Engines（引擎）（941）
				3. Engines in Detail（引擎详细信息）（944）
				4. Distributions（分布）（946）
				5. Distributions in Detail（分布详细信息）（950）
			2. Complex Numbers（复数）（954）
				1. Class complex<> in General（类complex<>概述）（954）
				2. Examples Using Class complex<>（使用类complex<>的示例）（955）
				3. Operations for Complex Numbers（复数运算）（957）
				4. Class complex<> in Detail（类complex<>详细信息）（964）
			3. Global Numeric Functions（全局数值函数）（970）
			4. Valarrays（972）
		18. Concurrency（并发性）（974）
			1. The High-Level Interface: async() and Futures（高级接口：async() 和 Futures）（975）
				1. A First Example Using async() and Futures（使用  async()  和  Future  的第一个示例）（975）
				2. An Example of Waiting for Two Tasks（等待两个任务的示例）（984）
				3. Shared Futures（共享期货）（989）
			2. The Low-LevelInterface: Threads and Promises（低级接口：线程和  Promise）（993）
				1. Class std::thread（993）
				2. Promises（承诺）（998）
				3. Class packaged_task<>（1001）
			3. Starting a Thread in Detail（启动线程的详细信息）（1002）
				1. async() in Detail（async()  详细信息）（1003）
				2. Futures in Detail（期货详细信息）（1004）
				3. Shared Futures in Detail（共享期货详细信息）（1005）
				4. Class std::promise in Detail（类  std::promise  详细信息）（1006）
				5. Class std::packaged_task in Detail（类  std::packaged_task  详细信息）（1006）
				6. Class std::thread in Detail（类  std::thread  详细信息）（1008）
				7. Namespace this_thread（命名空间  this_thread）（1010）
			4. Synchronizing Threads, or the Problem of Concurrency（同步线程，或者说并发问题）（1011）
				1. Beware of Concurrency!（注意并发！）（1011）
				2. The Reason for the Problem of Concurrent Data Access（并发数据访问问题的原因）（1012）
				3. What Exactly Can Go Wrong (the Extent of the Problem)（究竟会出现什么问题（问题的程度））（1012）
				4. The Features to Solve the Problems（解决问题的特点）（1016）
			5. Mutexes and Locks（互斥锁和锁）（1018）
				1. Using Mutexes and Locks（使用互斥锁和锁）（1018）
				2. Mutexes and Locks in Detail（互斥体和锁的详细信息）（1027）
				3. Calling Once for Multiple Threads（多线程调用一次）（1029）
			6. Condition Variables（条件变量）（1032）
				1. Purpose of Condition Variables（条件变量的用途）（1032）
				2. A First Complete Example for Condition Variables（条件变量的第一个完整示例）（1033）
				3. Using Condition Variables to Implement a Queue for Multiple Threads（使用条件变量实现多线程队列）（1035）
				4. Condition Variables in Detail（条件变量详细信息）（1038）
			7. Atomics（原子）（1041）
				1. Example of Using Atomics（使用原子的示例）（1041）
				2. Atomics and Their High-Level Interface in Detail（原子及其高级接口详细信息）（1045）
				3. The C-Style Interface of Atomics（原子的  C  风格接口）（1048）
				4. The Low-Level Interface of Atomics（原子的低级接口）（1048）
		19. Allocators（分配器）（1052）
			1. Using Allocators as an Application Programmer（作为应用程序程序员使用分配器）（1052）
			2. A User-Defined Allocator（用户定义的分配器）（1053）
			3. Using Allocators as a Library Programmer（使用分配器作为库程序员）（1055）
	6. Effective Modern C++（有效的现代  C++）
		1. Deducing Types（推导类型）（27）
			1. Item 1: Understand template type deduction（第  1  项：了解模板类型推导）（27）
				1. Case 1: ParamType is a Reference or Pointer, but not a Universal Reference（情况 1：ParamType 是引用或指针，但不是通用引用）（29）
				2. Case 2: ParamType is a Universal Reference（情况  2：  ParamType是通用引用）（31）
				3. Case 3: ParamType is Neither a Pointer nor a Reference（情况  3：  ParamType既不是指针也不是引用）（32）
				4. Array Arguments（数组参数这几乎涵盖了）（33）
				5. Function Arguments（函数参数）（35）
			2. Item 2: Understand auto type deduction（第  2  项：了解自动类型推导）（36）
			3. Item 3: Understand decltype（第  3  项：了解decltype）（41）
			4. Item 4: Know how to view deduced types（第  4  项：了解如何查看推导类型）（48）
				1. IDE Editors（IDE编辑器）（48）
				2. Compiler Diagnostics（编译器诊断）（49）
				3. Runtime Output（运行时输出）（49）
		2. auto（自动）（55）
			1. Item 5: Prefer auto to explicit type declarations（第  5  项：优先使用auto而不是显式类型声明）（55）
			2. Item 6: Use the explicitly typed initializer idiom when auto deduces undesired types（第 6 项：当自动推导不需要的类型时，使用显式类型初始化惯用法）（61）
		3. Moving to Modern C++（转向现代  C++）（67）
			1. Item 7: Distinguish between () and {} when creating objects（第7条：创建对象时区分()和{}）（67）
			2. Item 8: Prefer nullptr to 0 and NULL（第  8  项：优先使用nullptr ，而不是0和NULL）（76）
			3. Item 9: Prefer alias declarations to typedefs（第  9  项：优先使用别名声明而不是typedef）（81）
			4. Item 10: Prefer scoped enums to unscoped enums（第  10  项：与无作用域枚举相比，更喜欢有作用域枚举）（85）
			5. Item 11: Prefer deleted functions to private undefined ones（第 11 项：优先选择已删除的函数而不是私有未定义的函数）（92）
			6. Item 12: Declare overriding functions override（第  12  项：声明重写函数override）（97）
			7. Item 13: Prefer const_iterators to iterators（第  13  项：与迭代器相比，更喜欢const_iterators）（104）
			8. Item 14: Declare functions noexcept if they won’t emit exceptions（第 14 项：如果函数不会发出异常，则将其声明为 noexcept）（108）
			9. Item 15: Use constexpr whenever possible（第  15  项：尽可能使用constexpr）（115）
			10. Item 16: Make const member functions thread safe（第  16  项：使const成员函数成为线程安全的）（121）
			11. Item 17: Understand special member function generation（第 17 项：理解特殊成员函数的生成）（127）
		4. Smart Pointers（智能指针）（135）
			1. Item 18: Use std::unique_ptr for exclusive-ownership resource management（第 18 项：使用 std::unique_ptr 进行独占所有权资源管理）（136）
			2. Item 19: Use std::shared_ptr for shared-ownership resource management（第 19 项：使用 std::shared_ptr 进行共享所有权资源管理）（143）
			3. Item 20: Use std::weak_ptr for std::shared_ptr-like pointers that can dangle（第 20 项：将 std::weak_ptr 用于类似 std::shared_ptr 的可以悬挂的指针）（152）
			4. Item 21: Prefer std::make_unique and std::make_shared to direct use of new（第 21 项：优先使用 std::make_unique 和 std::make_shared 而不是直接使用 new）（157）
			5. Item 22:When using the Pimpl Idiom, define special member functions in the implementation file（第22项：使用Pimpl Idiom时，在实现文件中定义特殊成员函数）（165）
		5. Rvalue References, Move Semantics, and Perfect Forwarding（右值引用、移动语义和完美转发）（175）
			1. Item 23: Understand std::move and std::forward（第  23  项：理解std::move和std::forward）（176）
			2. Item 24: Distinguish universal references from rvalue references（第 24 项：区分通用引用和右值引用）（182）
			3. Item 25: Use std::move on rvalue references, std::forward on universal references（第 25 项：在右值引用上使用 std::move，在通用引用上使用 std::forward）（186）
			4. Item 26: Avoid overloading on universal references（第  26  条：避免通用引用重载）（195）
			5. Item 27:Familiarize yourself with alternatives to overloading on universal references（第 27 项：熟悉通用引用重载的替代方案）（202）
				1. Abandon overloading（放弃超载）（202）
				2. Pass by const T&（通过 const T& 传递）（202）
				3. Pass by value（按值传递）（202）
				4. Use Tag dispatch（使用标签调度）（203）
				5. Constraining templates that take universal references（约束采用通用引用的模板）（206）
				6. Trade-offs（权衡）（212）
			6. Item 28: Understand reference collapsing（第  28  项：了解引用折叠）（215）
			7. Item 29: Assume that move operations are not present, not cheap, and not used（第 29 项：假设移动操作不存在、不便宜且未使用）（221）
			8. Item 30:Familiarize yourself with perfect forwarding failure cases（第30条：熟悉完美转发失败案例）（225）
				1. Braced initializers（带支撑的初始化器）（226）
				2. 0 or NULL as null pointers（0 或 NULL 作为空指针）（227）
				3. Declaration-only integral static const data members（仅声明整型静态常量数据成员）（228）
				4. Overloaded function names and template names（重载的函数名称和模板名称）（229）
				5. Bitfields（位域）（231）
				6. Upshot（结果）（232）
		6. Lambda Expressions（拉姆达表达式）（233）
			1. Item 31: Avoid default capture modes（第  31  项：避免默认捕获模式）（234）
			2. Item 32: Use init capture to move objects into closures（第  32  项：使用  init  capture  将对象移动到闭包中）（242）
			3. Item 33: Use decltype on auto&& parameters to std::forward them（第 33 项：在 auto&& 参数上使用 decltype 来 std::forward 它们）（247）
			4. Item 34: Prefer lambdas to std::bind（第  34  项：与std::bind  相比，更喜欢  lambda）（250）
		7. The Concurrency API（并发  API）（259）
			1. Item 35: Prefer task-based programming to thread-based（第 35 条：优先选择基于任务的编程而不是基于线程的编程）（259）
			2. Item 36:Specify std::launch::async if asynchronicity is essential（第 36 项：如果异步性必不可少，请指定 std::launch::async）（263）
			3. Item 37: Make std::threads unjoinable on all paths（第  37  项：使std::threads在所有路径上不可连接）（268）
			4. Item 38: Be aware of varying thread handle destructor behavior（第 38 项：注意不同的线程句柄析构函数行为）（276）
			5. Item 39:Consider void futures for one-shot event communication（第 39 条：考虑一次性事件通信的无效期货）（280）
			6. Item 40: Use std::atomic for concurrency, volatile for special memory（第 40 项：使用 std::atomic 实现并发，使用 volatile 实现特殊内存）（289）
		8. Tweaks（调整）（299）
			1. Item 41:Consider pass by value for copyable parameters that are cheap to move and always copied（第 41 项：考虑按值传递可复制参数，这些参数移动成本低且始终复制）（299）
			2. Item 42:Consider emplacement instead of insertion（第  42  条：考虑安放而不是插入）（310）
	7. Programming in Lua Fourth Edition（Lua程序设计第4版）
		1. The Basics（基础）（15）
			1. Getting Started（入门）（18）
				1. Chunks（块）（18）
				2. Some Lexical Conventions（一些词汇约定）（20）
				3. Global Variables（全局变量）（21）
				4. Types and Values（类型和值）（21）
					1. Nil（空）（22）
					2. Booleans（布尔值）（22）
				5. The Stand-Alone Interpreter（独立的解释器）（23）
			2. Interlude: The Eight-Queen Puzzle（插曲：八皇后谜题）（26）
				1. The eight-queen program（八皇后计划）（27）
			3. Numbers（数字）（29）
				1. Numerals（数字）（29）
				2. Arithmetic Operators（算术运算符）（30）
				3. Relational Operators（关系运算符）（31）
				4. The Mathematical Library（数学图书馆）（31）
					1. Random-number generator（随机数生成器）（32）
					2. Rounding functions（舍入函数）（32）
				5. Representation Limits（代表限制）（33）
				6. Conversions（转换）（35）
				7. Precedence（优先级）（36）
				8. Lua Before Integers（整数之前的 Lua）（36）
			4. Strings（字符串）（38）
				1. Literal strings（文字字符串）（38）
				2. Long strings（长串）（40）
				3. Coercions（强制）（40）
				4. The String Library（字符串库）（41）
				5. Unicode（统一码）（44）
			5. Tables（表格）
				1. Table Indices（表索引）（47）
				2. Table Constructors（表构造函数）（49）
				3. Arrays, Lists, and Sequences（数组、列表和序列）（50）
				4. Table Traversal（表遍历）（52）
				5. Safe Navigation（安全导航）（52）
				6. The Table Library（表格库）（53）
			6. Functions（函数）
				1. Multiple Results（多个结果）（57）
				2. Variadic Functions（可变参数函数）（59）
				3. The function table.unpack（函数table.unpack）（61）
				4. Proper Tail Calls（正确的尾部调用）（62）
			7. The External World（外部世界）（64）
				1. The Simple I/O Model（简单 I/O 模型）（64）
					1. A program to sort a file（一个对文件进行排序的程序）（66）
				2. The Complete I/O Model（完整的 I/O 模型）（67）
				3. Other Operations on Files（对文件的其他操作）（68）
				4. Other System Calls（其他系统调用）（69）
					1. Running system commands（运行系统命令）（69）
			8. Filling some Gaps（填补一些空白）（71）
				1. Local Variables and Blocks（局部变量和块）（71）
				2. Control Structures（控制结构）（72）
					1. if then else（如果那么否则）（72）
					2. while（尽管）（73）
					3. repeat（重复）（73）
					4. Numerical for（数值为）（74）
					5. Generic for（泛型）（74）
				3. break, return, and goto（中断、返回和转到）（75）
					1. An example of a state machine with goto（带 goto 的状态机示例）（76）
					2. A maze game（迷宫游戏）（77）
				4. A strange (and invalid) use of a goto（goto 的奇怪（且无效）用法）（78）
		2. Real Programming（真实编程）（78）
			1. Closures（闭包）（82）
				1. Functions as First-Class Values（功能是一流的价值）（82）
				2. Non-Global Functions（非全局函数）（83）
				3. Lexical Scoping（词汇范围）（85）
				4. A Taste of Functional Programming（函数式编程的初体验）（88）
					1. Union, intersection, and difference of regions（区域的并集、交集和差异）（89）
					2. Drawing a region in a PBM fil（在 PBM 过滤器中绘制区域）（89）
			2. Pattern Matching（模式匹配）（91）
				1. The Pattern-Matching Functions（模式匹配函数）（91）
					1. The function string.find（函数 string.find）（91）
					2. The function string.match（函数 string.match）（92）
					3. The function string.gsub（函数 string.gsub）（92）
					4. The function string.gmatch（函数 string.gmatch）（92）
				2. Patterns（图案）（92）
				3. Captures（捕获）（95）
				4. Replacements（替换品）（97）
					1. URL encoding（URL编码）（98）
					2. Tab expansion（选项卡扩展）（100）
				5. Tricks of the Trade（交易技巧）（100）
			3. Interlude: Most Frequent Words（插曲：最常用的单词（104）
				1. Word-frequency program（词频程序）（104）
			4. Date and Time（日期和时间）（105）
				1. The Function os.time（函数 os.time）（106）
				2. The Function os.date（函数 os.date）（107）
					1. Directives for function os.date（os.date 函数的指令）（108）
				3. Date–Time Manipulation（日期时间操作）（109）
			5. Bits and Bytes（位和字节）（111）
				1. Bitwise Operators（按位运算符）（111）
				2. Unsigned Integers（无符号整数）（111）
					1. Unsigned division（无符号除法）（112）
				3. Packing and Unpacking Binary Data（打包和解包二进制数据）（113）
				4. Binary files（二进制文件）（115）
					1. Dumping the dump program（转储转储程序）（116）
			6. Data Structures（数据结构）（118）
				1. Arrays（数组）（118）
				2. Matrices and Multi-Dimensional Arrays（矩阵和多维数组）（118）
					1. Multiplication of sparse matrices（稀疏矩阵的乘法）（120）
				3. Linked Lists（链表）（121）
				4. Queues and Double-Ended Queues（队列和双端队列）（121）
					1. A double-ended queue（双端队列）（122）
				5. Reverse Tables（反转表）（122）
				6. Sets and Bags（套装和包袋）（123）
				7. String Buffers（字符串缓冲区）（124）
				8. Graphs（图表）（125）
					1. Reading a graph from a file（从文件中读取图表）（126）
					2. Finding a path between two nodes（寻找两个节点之间的路径）（126）
			7. Data Files and Serialization（数据文件和序列化）（128）
				1. Data Files（数据文件）（128）
				2. Serialization（序列化）（130）
					1. Quoting arbitrary literal string（引用任意文字字符串）（131）
					2. Saving tables without cycles（保存没有循环的表）（132）
						1. Serializing tables without cycles（不带循环的序列化表）（132）
					3. Saving tables with cycles（保存带有循环的表）（133）
						1. Saving tables with cycles（保存带有循环的表）（133）
			8. Compilation, Execution, and Errors（编译、执行和错误）（136）
				1. Compilation（汇编）（136）
				2. Precompiled Code（预编译代码）（139）
					1. Example of output from luac -l（luac -l 的输出示例）（139）
				3. Errors（错误）（140）
				4. Error Handling and Exceptions（错误处理和异常）（141）
				5. Error Messages and Tracebacks（错误消息和回溯）（142）
				6. String repetition（字符串重复）（143）
			9. Modules and Packages（模块和包）（145）
				1. The Function require（该功能要求）（146）
					1. Renaming a module（重命名模块）（147）
					2. Path searching（路径搜索）（147）
						1. A homemade package.searchpath（自制的package.searchpath）（148）
					3. Searchers（搜索者）（149）
				2. The Basic Approach for Writing Modules in Lua（Lua 编写模块的基本方法）（149）
					1. A simple module for complex numbers（一个简单的复数模块）（150）
					2. Module with export list（带有导出列表的模块）（151）
				3. Submodules and Packages（子模块和包）（151）
		3. Lua-isms（Lua主义）（153）
			1. Iterators and the Generic for（迭代器和泛型）（156）
				1. Iterators and Closures（迭代器和闭包）（156）
					1. Iterator to traverse all words from the standard input（迭代器遍历标准输入中的所有单词）（157）
				2. The Semantics of the Generic for（泛型的语义）（157）
				3. Stateless Iterators（无状态迭代器）（159）
				4. Traversing Tables in Order（按顺序遍历表）（160）
				5. True Iterators（真正的迭代器）（161）
			2. Interlude: Markov Chain Algorithm（插曲：马尔可夫链算法）（163）
				1. Auxiliary definitions for the Markov program（马尔可夫程序的辅助定义）（164）
				2. The Markov program（马尔可夫规划）（165）
			3. Metatables and Metamethods（元表和元方法）（166）
				1. Arithmetic Metamethods（算术元方法）（166）
					1. A simple module for sets（一个简单的集合模块）（166）
				2. Relational Metamethods（关系元方法）（169）
				3. Library-Defined Metamethods（库定义的元方法）（169）
				4. Table-Access Metamethods（表访问元方法）（170）
					1. The __index metamethod（__index 元方法）（170）
					2. The __newindex metamethod（__newindex 元方法）（171）
					3. Tables with default values（具有默认值的表）（172）
					4. Tracking table accesses（跟踪表访问）（173）
						1. Tracking table accesses（跟踪表访问）（173）
					5. Read-only tables（只读表）（174）
			4. Object-Oriented Programming（面向对象编程）（176）
				1. Classes（类）（177）
				2. Inheritance（继承）（179）
					1. the Account class（帐户类）（179）
				3. Multiple Inheritance（多重继承）（180）
					1. An implementation of multiple inheritance（多重继承的实现）（181）
				4. Privacy（隐私）（182）
				5. The Single-Method Approach（单一方法）（183）
				6. Dual Representation（双重代表）（184）
					1. Accounts using a dual representation（使用双重表示的账户）（185）
			5. The Environment（环境）（187）
				1. Global Variables with Dynamic Names（具有动态名称的全局变量）（187）
					1. The function setfield（函数setfield）（188）
				2. Global-Variable Declarations（全局变量声明）（188）
					1. Checking global-variable declaration（检查全局变量声明）（190）
				3. Non-Global Environments（非全局环境）（190）
				4. Using _ENV（使用_ENV）（191）
				5. Environments and Modules（环境和模块）（194）
				6. _ENV and load（_ENV 和负载）（195）
			6. Garbage（垃圾）（196）
				1. Weak Tables（弱表）（197）
				2. Memorize Functions（记住函数）（198）
				3. Object Attributes（对象属性）（199）
				4. Revisiting Tables with Default Values（重新访问具有默认值的表）（200）
				5. Ephemeron Tables（星历表）（201）
					1. Constant-function factory with memorization（带记忆功能的常量工厂）（201）
				6. Finalizers（终结器）（202）
					1. Running a function at every GC cycle（在每个 GC 周期运行一个函数）（204）
				7. The Garbage Collector（垃圾收集器）（204）
				8. Controlling the Pace of Collection（控制收集速度）（205）
				9. Finalizers and memory（终结器和内存）（206）
			7. Coroutines（协程）（208）
				1. Coroutine Basics（协程基础知识）（208）
				2. Who Is the Boss?（请问谁是老板？）（210）
					1. Producer–consumer with filters（带过滤器的生产者-消费者）（212）
				3. Coroutines as Iterators（协程作为迭代器）（212）
					1. A function to generate permutations（生成排列的函数）（213）
				4. Event-Driven Programming（事件驱动编程）（214）
					1. An ugly implementation of the asynchronous I/O library（异步 I/O 库的丑陋实现）（215）
					2. Reversing a file in event-driven fashion（以事件驱动的方式反转文件）（216）
					3. Running synchronous code on top of the asynchronous library（在异步库之上运行同步代码）（217）
			8. Reflection（反射）（219）
				1. Introspective Facilities（内省设施）（219）
					1. Accessing local variables（访问局部变量）（221）
					2. Accessing non-local variables（访问非局部变量）（221）
						1. Getting the value of a variable（获取变量的值）（222）
					3. Accessing other coroutines（访问其他协程）（223）
				2. Hooks（挂钩）（224）
				3. Profiles（型材）（225）
					1. Hook for counting number of calls（用于计算调用次数的钩子）（225）
					2. Getting the name of a function（获取函数的名称）（226）
				4. Sandboxing（沙盒）（226）
					1. A naive sandbox with hooks（带钩子的天真沙箱）（227）
					2. Controlling memory use（控制内存使用）（228）
					3. Using hooks to bar calls to unauthorized functions（使用钩子来阻止对未经授权的函数的调用）（228）
			9. Interlude: Multithreading with Coroutines（插曲：使用协程进行多线程处理）（231）
				1. Function to download a Web page（下载网页功能）（232）
				2. The dispatcher（调度员）（233）
				3. Dispatcher using select（使用 select 的调度程序）（234）
		4. The C API（C API）（235）
			1. An Overview of the C API（C API 概述）（237）
				1. A First Example（第一个例子）（238）
					1. A bare-bones stand-alone Lua interpreter（一个简单的独立 Lua 解释器）（238）
				2. The Stack（堆栈）（239）
					1. Pushing elements（推动元素）（240）
					2. Querying elements（查询元素）（241）
						1. Dumping the stack（转储堆栈）（243）
					3. Other stack operations（其他堆栈操作）（243）
						1. Example of stack manipulation（堆栈操作示例）（245）
				3. Error Handling with the C API（使用 C API 进行错误处理）（245）
					1. Error handling in application code（应用程序代码中的错误处理）（246）
					2. Error handling in library code（库代码中的错误处理）（246）
				4. Memory Allocation（内存分配）（247）
			2. Extending Your Application（扩展您的应用程序）（249）
				1. The Basics（基础）（250）
					1. Getting user information from a configuration file（250）
				2. Table Manipulation（表操作）（251）
					1. A particular getcolorfield implementation（特定的 getcolorfield 实现）（252）
					2. Colors as strings or tables（颜色作为字符串或表格）（254）
					3. Some short cuts（一些捷径）（254）
				3. Calling Lua Functions（调用Lua函数）（255）
					1. Calling a Lua function from C（从 C 调用 Lua 函数）（256）
				4. A Generic Call Function（通用调用函数）（256）
					1. A generic call function（通用调用函数）（257）
					2. Pushing arguments for the generic call function（推送通用调用函数的参数）（258）
					3. Retrieving results for the generic call function（检索通用调用函数的结果）（259）
			3. Calling C from Lua（从 Lua 调用 C）（261）
				1. C Functions（C 函数）（261）
					1. A function to read a directory（读取目录的函数）（263）
				2. Continuations（延续）（263）
					1. Implementation of pcall with continuations（带有延续的 pcall 的实现）（265）
				3. C Modules（C 语言模块）（265）
			4. Techniques for Writing C Functions（编写 C 函数的技术）（268）
				1. Array Manipulation（数组操作）（268）
					1. The function map in C（C中的函数映射）（269）
				2. String Manipulation（字符串操作）（269）
					1. Splitting a string（分割字符串）（270）
					2. The function string.upper（函数 string.upper）（271）
					3. A simplified implementation for table.concat（table.concat 的简化实现）（272）
				3. Storing State in C Functions（在 C 函数中存储状态）（272）
					1. The registry（注册表）（272）
					2. Upvalues（上调）（274）
						1. An implementation of tuples（元组的实现）（276）
					3. Shared upvalues（共享价值）（277）
			5. User-Defined Types in C（C 中的用户定义类型）（279）
				1. Userdata（用户数据）（279）
					1. Manipulating a Boolean array（操作布尔数组）（280）
					2. Extra code for the Boolean array library（布尔数组库的额外代码）（281）
				2. Metatables（元表）（282）
					1. New versions for setarray/getarray（setarray/getarray 的新版本）（283）
				3. Object-Oriented Access（面向对象的访问）（284）
				4. Array Access（数组访问）（285）
					1. New initialization code for the Bit Array library（位数组库的新初始化代码）（286）
				5. Light Userdata（轻用户数据）（286）
			6. Managing Resources（管理资源）（288）
				1. A Directory Iterator（目录迭代器）（288）
					1. The dir.open factory function（dir.open 工厂函数）（289）
					2. Other functions for the dir library（dir 库的其他函数）（290）
				2. An XML Parser（XML 解析器）（290）
					1. Function to create XML parser objects（创建 XML 解析器对象的函数）（294）
					2. Function to parse an XML fragment（解析 XML 片段的函数）（295）
					3. Handler for character data（字符数据处理程序）（296）
					4. Handler for end elements（结束元素的处理程序）（296）
					5. Handler for start elements（开始元素的处理程序）（297）
					6. Method to close an XML parser（关闭 XML 解析器的方法）（297）
					7. Initialization code for the lxp library（lxp库的初始化代码）（298）
			7. Threads and States（线程和状态）（300）
				1. Multiple Threads（多线程）（300）
				2. Lua States（Lua 状态）（303）
					1. Function to search for a process waiting for a channel（搜索等待通道的进程的函数）（305）
					2. Function to add a process to a waiting list（将进程添加到等待列表的功能）（305）
					3. Functions to send and receive messages（发送和接收消息的函数）（306）
					4. Function to create new processes（创建新进程的函数）（307）
					5. Body for new threads（新线程的主体）（308）
					6. Extra functions for the lproc module（lproc 模块的额外功能）（309）
					7. Registering libraries to be opened on demand（注册按需打开的库）（310）
	8. Lua Programming Gems（Lua 编程精粹）
		1. Programming Techniques（编程技巧）（14）
			1. Lua Per-Thread Library Context（Lua  每线程库上下文）（15）
				1. Implementation alternatives（实施方案）（17）
				2. Using LUA ENVIRONINDEX for library private storage（使用LUA  ENVIRONINDEX进行库私有存储）（17）
				3. Using library private storage to implement per-thread private storage（使用库私有存储实现每线程私有存储）（18）
				4. Using per-thread private storage for per-thread library context（对每线程库上下文使用每线程私有存储）（19）
				5. Caching per-thread library context（缓存每个线程库上下文）（21）
				6. Testing and performance measurement（测试和性能测量）（25）
				7. Conclusion（结论）（26）
			2. Lua Performance Tips（Lua  性能技巧）（27）
				1. Basic facts（基本事实）（29）
				2. About tables（关于表格）（31）
				3. About strings（关于字符串）（34）
				4. Reduce, reuse, recycle（减少回收再利用）（35）
				5. Final remarks（最后的评论）（39）
			3. Vardump: The Power of Seeing What’s Behind（Var_dump：了解背后的力量）（41）
				1. Implementation（执行）（42）
				2. Conclusion（结论）（42）
			4. Serialization with Pluto（与  Pluto  的序列化）（45）
				1. The complexities of serialization（序列化的复杂性）（46）
				2. Using Pluto（使用Pluto）（47）
				3. Custom serialization routines（自定义序列化例程）（48）
				4. Permanent objects（永久物体）（49）
				5. Limitations of Pluto（Pluto的局限性）（50）
				6. Other approaches to general-purpose serialization（通用序列化的其他方法）（50）
				7. LuaPickle（52）
				8. lper（52）
				9. Conclusion（53）
			5. Abstractions for LuaSQL（LuaSQL  的抽象）（54）
				1. Common uses（常见用途）（54）
				2. Defining a module（定义模块）（56）
				3. Error handling（错误处理）（56）
				4. Result set iterator（结果集迭代器）（57）
				5. SQL statement constructors（SQL  语句构造函数）（59）
				6. Infrastructure（基础设施）（59）
				7. Insert（插入）（59）
				8. Select revisited（选择重访）（61）
				9. Delete（删除）（62）
				10. Update（更新）（62）
				11. Extensions（扩展）（63）
				12. Complete result set（完整结果集）（63）
				13. Logging SQL execution（记录  SQL  执行情况）（64）
				14. Other ideas（其他想法）（64）
				15. Discussion（讨论）（65）
				16. Conclusion（结论）（66）
			6. Boostrapping a Forth in 40 Lines of Lua Code（引导 40 行 Lua 代码中的第四行）（67）
				1. Introduction（介绍）（68）
				2. Forth via examples（通过示例进行说明）（68）
				3. Bootstrapping miniforth（引导小型文件）（71）
				4. Modes（模式）（73）
				5. Virtual modes（虚拟模式）（74）
				6. A bytecode for polynomials（多项式的字节码）（75）
				7. A bytecode language for propositional calculus（用于命题演算的字节码语言）（76）
				8. (Meta)Lua on miniforth（Miniforth  上的（元）Lua）（77）
				9. Why Forth?（为什么是Forth）（78）
				10. Conclusion（结论）（80）
			7. Effecting Large-Scale Change (with little trauma) using Metatables（使用元表实现大规模变革（几乎没有创伤））（81）
				1. Introduction（介绍）（81）
				2. Metamethods and environments（元方法和环境）（82）
				3. Our sample problem（我们的样本问题）（82）
				4. Resolution through “Origins”（通过“起源”解决）（84）
				5. Setup（设置）（86）
				6. Quick setup（快速设置）（87）
				7. Runtime（运行）（87）
				8. Limitations（局限性）（88）
				9. Further development（进一步的发展）（89）
				10. Other uses for metatables（元表的其他用途）（89）
				11. Conclusion（结论）（91）
		2. Design Techniques（设计技巧）（92）
			1. MVC Web Development with Kepler（使用  Kepler  进行  MVC  Web 开发）（93）
				1. Introduction（介绍）（93）
				2. Request dispatching（请求调度）（94）
				3. Overview（概述）（94）
				4. Kepler setup（Kepler设置）（96）
				5. Example 1: mapping a sequence to a function and parameters（示例  1：将序列映射到函数和参数）（96）
				6. Example 2: mapping through Lua pattern matching（示例2：通过Lua模式匹配进行映射）（98）
				7. Example 3: delegating action selection to objects（示例  3：将操作选择委托给对象）（99）
				8. Content generation（内容生成）（101）
				9. Overview（概述）（101）
				10. Scripting（脚本编写）（101）
				11. Templating（模板化）（103）
				12. Conclusion（结论）（104）
			2. Filters, Sources, Sinks & Pumps or Functional programming for the rest of us（过滤器、源、水槽和泵或我们其他人的函数式编程）（105）
				1. Introduction（介绍）（105）
				2. A simple example（一个简单的例子）（106）
				3. The Lua part of the filter（过滤器的Lua部分）（107）
				4. The C part of the filter（过滤器C部分）（108）
				5. Filter chains（过滤链）（109）
				6. Sources, sinks, and pumps（源、汇和泵）（110）
				7. Sources（来源）（110）
				8. Filtered sources（过滤来源）（111）
				9. Sinks（水槽）（111）
				10. Pumps（泵）（112）
				11. Exploding filters（爆炸过滤器）（113）
				12. A complex example（一个复杂的例子）（114）
				13. Conclusion（结论）（115）
			3. Lua as a Protocol Language（Lua  作为协议语言）（116）
				1. Background（背景）（116）
				2. Choice of language（语言选择）（116）
				3. Protocol（协议）（117）
				4. Compression（压缩）（119）
				5. Encryption（加密）（120）
				6. Secured mode（安全模式）（120）
				7. Benchmark（基准）（120）
				8. Security（安全）（121）
				9. Library functions（库函数）（121）
				10. Buffer overrun（缓冲区溢出）（122）
				11. Denial of service（拒绝服务）（122）
				12. Conclusion（结论）（124）
			4. Lua Script Packaging（Lua脚本打包）（125）
				1. Why do we need to package script files together?（为什么我们需要将脚本文件打包在一起？）（125）
				2. First try: luac -o（第一次尝试：  luac  ‑o）（125）
				3. Mock require and dofile（模拟  require  和  dofile）（126）
				4. How does the standard require work?（标准要求如何发挥作用？）（126）
				5. Mock require（模拟需求）（126）
				6. Mock dofile（模拟文件）（129）
				7. From separate Lua files to packed .dat— How to organize?（从单独的  Lua  文件到打包的 .dat-如何组织？）（129）
				8. When to mock?（什么时候嘲笑？）（131）
				9. Choose a packaging algorithm/utility（选择打包算法/实用程序）（131）
				10. .dat format（.dat  格式）（132）
				11. Compiled vs plain .lua files（编译文件与普通 .lua  文件）（132）
				12. Patching（打补丁）（133）
				13. Conclusion（结论）（133）
			5. Objects, Lua-style（对象，Lua  风格）（134）
				1. The object model（对象模型）（134）
				2. A judicious justification（明智的理由）（135）
				3. A delightful detour（一次愉快的绕行）（136）
				4. Implementation（执行）（137）
				5. Weaknesses（弱点）（137）
				6. Inconclusion（综上所述）（138）
			6. Exceptions in Lua（Lua  中的异常）（139）
				1. What is an error?（什么是错误？）（140）
				2. A simple try–catch construct（一个简单的  try‑catch  结构）（141）
				3. Custom error objects（自定义错误对象）（142）
				4. Exception safety（异常安全）（145）
				5. A simple scope manager（一个简单的范围管理器）（147）
		3. Algorithms and Data Structures（算法和数据结构）（150）
			1. Word Ladders（字梯）（151）
				1. Undirected graphs（无向图）（151）
				2. Word Ladder game（文字天梯游戏）（154）
				3. Summary（概括）（154）
			2. Building Data Structures and Iterators in Lua（在 Lua 中构建数据结构和迭代器）（157）
				1. Introduction（介绍）（158）
				2. Queues（队列）（158）
				3. Heaps（堆）（159）
				4. Heapsort（堆排序）（162）
				5. Partition sets（分区集）（163）
				6. Graphs（图表）（165）
				7. Graph search（图搜索）（166）
				8. Minimum spanning trees（最小生成树）（169）
				9. Shortest paths（最短路径）（170）
				10. Conclusions（结论）（173）
			3. A Primer of Scientific Computing in Lua（Lua 科学计算入门）（174）
				1. Introduction（介绍）（175）
				2. Matrices（矩阵）（175）
				3. Metamethods（元方法）（178）
				4. Core methods（核心方法）（180）
				5. Functional facilities（功能设施）（182）
				6. External libraries（外部库）（184）
				7. Library setup（库设置）（186）
				8. Lua side（187）
				9. Applications（应用领域）（189）
				10. Basic operations（基本操作）（190）
				11. Lagrangian interpolation（拉格朗日插值）（193）
				12. Fast Fourier transforms（快速傅立叶变换）（196）
				13. Clenshaw–Curtis quadrature（克伦肖‑柯蒂斯求积）（197）
				14. Conclusions（结论）（201）
			4. Complex Structured Data Input（复杂的结构化数据输入）（202）
				1. The problem（问题）（202）
				2. The solution（解决方案）（204）
				3. Justification and explanation（理由和解释）（206）
				4. How to use（如何使用）（208）
				5. Weaknesses and suggested improvements（缺点和改进建议）（209）
				6. Conclusions（结论）（210）
			5. Lua Implementations of Common Data Structures（常用数据结构的Lua实现）（212）
				1. Code examples（代码示例）（212）
				2. Abstract data types and common functionality（抽象数据类型和通用功能）（213）
				3. Lua tables（Lua表）（214）
				4. Lua table implementation（Lua表实现）（214）
				5. Lists（列表）（214）
				6. Array lists（数组列表）（215）
				7. Node lists（节点列表）（216）
				8. Stacks, queues, and dequeues（栈、队列和出列）（218）
				9. Stacks（堆栈）（218）
				10. Queues and dequeues（队列和出队）（219）
				11. Trees（树）（221）
				12. Linked-node trees（链接节点树）（222）
				13. Array-based trees（基于数组的树）（224）
				14. Maps and dictionaries（地图和词典）（226）
				15. Sets（集合）（227）
				16. Multisets（多组）（230）
				17. Partitions（分区）（232）
				18. Graphs（图表）（233）
				19. Text processing（文本处理）（235）
				20. Augmented data structures（增强数据结构）（235）
				21. Homogeneous data structures（同构数据结构）（237）
				22. Working with Lua（使用  Lua）（238）
				23. Resources（资源）（238）
			6. Tic-Tac-Toe and the Minimax Decision Algorithm（井字游戏和极小极大决策算法）（240）
				1. Introduction（介绍）（240）
				2. Search problems（搜索问题）（241）
				3. Games（游戏）（241）
				4. The minimax algorithm（极小极大算法）（242）
				5. Case study（案例分析）（244）
				6. Conclusions（结论）（246）
		4. Game Programming（游戏编程）（247）
			1. Using Lua in Game and Tool Creation（在游戏和工具创建中使用 Lua）（248）
				1. Programmable access via Lua（通过  Lua  进行可编程访问）（248）
				2. IDE (debugger)（IDE（调试器））（249）
				3. Excessive flexibility of Lua（Lua过于灵活）（250）
				4. Performance issues（性能问题）（250）
				5. Lua–C++ data transferring（Lua–C++数据传输）（251）
				6. Lua and .NET（251）
				7. Conclusion（252）
			2. Leveraging Lua and C++ to Create a Dynamic and Flexible Event System for Script-Driven Games（利用 Lua 和 C++ 为脚本驱动游戏创建动态且灵活的事件系统）（258）
				1. The subscriber（订阅者）（258）
				2. Strategy（战略）（262）
				3. Extra credit（额外学分）（263）
				4. Closing（闭包）（266）
			3. Lua for Game Programming（Lua  游戏编程）（267）
				1. Example game（示例游戏）（268）
				2. Data representation（数据表示）（268）
				3. Dynamic challenges（动态挑战）（271）
				4. AI and state machines（人工智能和状态机）（273）
				5. Generic Lua function exposure（通用Lua函数暴露）（276）
				6. Conclusion（结论）（277）
			4. Designing an Efficient Lua Driven Game Scripting Engine（设计高效的 Lua 驱动的游戏脚本引擎）（278）
				1. The problem — motivation and statement（问题-动机和陈述）（278）
				2. The solution — description（解决方案——描述）（279）
				3. Use an object local solution（使用对象本地解决方案）（279）
				4. Use frame-by-frame execution（使用逐帧执行）（279）
				5. Allow different update rate for the AIModel instances（允许  AIModel  实例有不同的更新速率）（280）
				6. Use an automatic activation process（使用自动激活过程）（280）
				7. Use an event based communication schema between AIModel instances（在 AIModel 实例之间使用基于事件的通信模式）（280）
				8. Use high level function packages（使用高级函数包）（281）
				9. Use handles to exchange data structures between Lua and C/C++ runtime（使用句柄在 Lua 和 C/C++ 运行时之间交换数据结构）（282）
				10. Limit the use of complex types（限制复杂类型的使用）（283）
				11. Encourage the use of local variables（鼓励使用局部变量）（283）
				12. Use preallocated memory pools（使用预分配的内存池）（283）
				13. Explanation and justification（解释和理由）（284）
				14. Weaknesses and suggested improvements（缺点和改进建议）（284）
				15. Conclusion（结论）（284）
		5. Embedding and Extending（嵌入和扩展）（285）
			1. Enhanced Coroutines in Lua（Lua  中的增强型协程）（286）
				1. History（历史）（286）
				2. Multithreading models（多线程模型）（287）
				3. Lua collaborative threads with memory sharing（具有内存共享功能的  Lua  协作线程）（287）
				4. Preemptive threads in separate Lua states, sharing no memory（抢占式线程处于单独的  Lua  状态，不共享内存）（287）
				5. Preemptive threads associated with coroutines（与协程关联的抢占式线程）（287）
				6. Implementation（执行）（287）
				7. Coding（编码）（290）
				8. Wget user function（wget用户函数）（291）
				9. Error handling（错误处理）（292）
				10. Example of Lua code（Lua代码示例）（292）
				11. Scheduler（调度程序）（292）
				12. Interpreter（口译员）（293）
				13. Complete example（完整示例）（294）
			2. Using Lua in Pascal（在  Pascal  中使用  Lua）（295）
				1. Why Lua?（为什么是Lua）（295）
				2. The basic needs（基本需求）（295）
				3. The problem（问题）（296）
				4. Project foundations (setting up the project)（项目基础（建立项目））（296）
				5. Defining HAL 9000（定义  HAL  9000）（297）
				6. Building HAL 9000（建筑  HAL  9000）（297）
				7. Read and writing variables（读取和写入变量）（298）
				8. Writing（写作）（298）
				9. Reading（阅读）（299）
				10. More on methods（更多关于方法的内容）（299）
				11. Differences between Lua and Pascal（Lua  和  Pascal  之间的区别）（299）
				12. Surfacing a method（呈现方法）（300）
				13. Getting something back（拿回一些东西）（300）
				14. Calling Lua methods（调用Lua方法）（301）
				15. Using records and objects（使用记录和对象）（302）
				16. Metatables（元表）（302）
				17. Garbage collection and the Lua registry（垃圾收集和  Lua  注册表）（302）
				18. Finally introducing objects（最后引入对象）（303）
				19. Back to the registry（返回注册表）（303）
				20. Object properties（对象属性）（303）
				21. Object methods（对象方法）（304）
				22. And the object（还有对象）（304）
				23. Records（记录）（304）
				24. Calling within a loop（循环内调用）（304）
				25. Final words（最后的话）（305）
			3. Porting Lua to a Microcontroller（将  Lua  移植到微控制器）（306）
				1. The target processor – why use Lua to program LEGO?（目标处理器——为什么使用Lua来对乐高进行编程？）（306）
				2. Think before you get started（开始之前请三思）（307）
				3. Add the Lua kernel code to the build system（将Lua内核代码添加到构建系统）（308）
				4. Building a better run-time library（构建更好的运行时库）（310）
				5. Thread-safe considerations（线程安全注意事项）（310）
				6. The ANSI C library（ANSI  C  库）（310）
				7. Memory allocation library（内存分配库）（312）
				8. Lua garbage collection and the heap（Lua  垃圾收集和堆）（312）
				9. File IO routines for systems without files（无文件系统的文件  IO  例程）（313）
				10. A new kind of math using “flongs”（使用“flongs”的新型数学）（314）
				11. Trading speed for accuracy（交易速度换取准确性）（314）
				12. Using flongs with the C math library（将  flongs  与  C  数学库结合使用）（315）
				13. Choosing a single-precision float library（选择单精度浮点库）（316）
				14. Conclusion（结论）（316）
			4. Writing C/C++ Modules for Lua（为  Lua  编写  C/C++  模块）（318）
				1. Generic module layout（通用模块布局）（319）
				2. Objects（对象）（321）
				3. Boxing and packing（装箱和包装）（322）
				4. Packing modules into a single library（将模块打包到单个库中）（322）
				5. A libevent module（libevent  模块）（323）
				6. Example.lua（324）
				7. Event.lua（324）
				8. Event.c (compiled into C-Event.so)（Event.c（编译成C‑Event.so））（325）
			5. Interpreted C Modules（解释型  C  模块）（330）
				1. The Lua module system（Lua模块系统）（331）
				2. require, searchers, and loaders（require、搜索器和加载器）（331）
				3. TCC（332）
				4. Tiny C Compiler（小  C  编译器）（332）
				5. libtcc（332）
				6. TCC binding（TCC结合）（333）
				7. TCC searcher（TCC搜索器）（334）
				8. The module header（模块头）（334）
				9. The searcher function（搜索器功能）（335）
				10. Installing the searcher（安装搜索器）（338）
				11. Conclusion（结论）（338）
	9. Microsoft Visual C# Step by Step（Visual C#从入门到精通）
		1. Introducing Microsoft Visual C# and Microsoft Visual Studio 2022（Microsoft Visual C# 和 Microsoft Visual Studio 2022 简介）（45）
			1. Welcome to C#（欢迎使用 C#）（46）
				1. Writing your first C# program（编写您的第一个 C# 程序）（46）
				2. Beginning programming with the Visual Studio 2022 environment（开始使用 Visual Studio 2022 环境进行编程）（55）
				3. Writing your first program using Visual Studio 2022（使用 Visual Studio 2022 编写您的第一个程序）（62）
				4. Using namespaces（使用命名空间）（73）
				5. Namespaces and assemblies（命名空间和程序集）（75）
				6. Commenting code（评论代码）（76）
				7. Creating a graphical application（创建图形应用程序）（76）
					1. Examining the Universal Windows Platform app（检查通用 Windows 平台应用程序）（96）
					2. Adding code to the graphical application（将代码添加到图形应用程序）（100）
			2. Working with variables, operators, and expressions（使用变量、运算符和表达式）（107）
				1. Understanding statements（理解陈述）（108）
				2. Using identifiers（使用标识符）（109）
				3. Identifying keywords（识别关键词）（109）
				4. Using variables（使用变量）（111）
					1. Naming variables（命名变量）（111）
					2. Declaring variables（声明变量）（112）
					3. Specifying numeric values（指定数值）（113）
				5. Working with primitive data types（使用原始数据类型）（114）
					1. Unassigned local variables（未分配的局部变量）（115）
					2. Displaying primitive data type values（显示原始数据类型值）（116）
				6. Using arithmetic operators（使用算术运算符）（126）
					1. Operators and types（运算符和类型）（126）
					2. Examining arithmetic operators（检查算术运算符）（129）
					3. Controlling precedence（控制优先级）（137）
					4. Using associativity to evaluate expressions（使用结合性计算表达式）（138）
					5. Associativity and the assignment operator（结合性和赋值运算符）（139）
				7. Incrementing and decrementing variables（递增和递减变量）（140）
					1. Prefix and postfix（前缀和后缀）（141）
				8. Declaring implicitly typed local variables（声明隐式类型局部变量）（142）
			3. Writing methods and applying scope（书写方法及适用范围）（146）
				1. Creating methods（创建方法）（146）
					1. Declaring a method（声明一个方法）（147）
					2. Returning data from a method（从方法返回数据）（149）
					3. Using expression-bodied methods（使用表达体方法）（149）
				2. Calling methods（调用方法）（152）
					1. Specifying the method call syntax（指定方法调用语法）（152）
					2. Returning multiple values from a method（从一个方法返回多个值）（156）
				3. Applying scope（适用范围）（159）
					1. Defining local scope（定义本地范围）（160）
					2. Defining class scope（定义类范围）（161）
					3. Overloading methods（重载方法）（161）
					4. Writing methods（写作方法）（163）
				4. Using the Visual Studio Debugger to step through methods（使用 Visual Studio 调试器逐步执行方法）（170）
					1. Refactoring code（重构代码）（180）
					2. Nesting methods（嵌套方法）（181）
				5. Using optional parameters and named arguments（使用可选参数和命名参数）（185）
					1. Defining optional parameters（187）
					2. Passing named arguments（188）
					3. Resolving ambiguities with optional parameters and named arguments（使用可选参数和命名参数解决歧义）（189）
			4. Using decision statements（使用决策语句）（201）
				1. Declaring Boolean variables（声明布尔变量）（201）
				2. Using Boolean operators（使用布尔运算符）（202）
					1. Understanding equality and relational operators（了解相等和关系运算符）（202）
					2. Understanding conditional logical operators（了解条件逻辑运算符）（203）
					3. Short-circuiting（短路）（204）
					4. Summarizing operator precedence and associativity（总结运算符优先级和结合性）（205）
					5. Pattern matching（模式匹配）（207）
				3. Using if statements to make decisions（使用 if 语句做出决定）（208）
					1. Understanding if statement syntax（了解 if 语句语法）（208）
					2. Using blocks to group statements（使用块对语句进行分组）（210）
					3. Cascading if statements（级联 if 语句）（211）
				4. Using switch statements（使用 switch 语句）（219）
					1. Understanding switch statement syntax（了解 switch 语句语法）（220）
					2. Following the switch statement rules（遵循 switch 语句规则）（221）
				5. Using switch expressions with pattern matching（使用带有模式匹配的 switch 表达式）（226）
			5. Using compound assignment and iteration statements（使用复合赋值和迭代语句）（232）
				1. Using compound assignment operators（使用复合赋值运算符）（232）
				2. Writing while statements（编写 while 语句）（234）
				3. Writing for statements（编写 for 语句）（242）
				4. Writing do statements（编写 do 语句）（245）
			6. Managing errors and exceptions（管理错误和异常）（259）
				1. Trying code and catching exceptions（尝试代码并捕获异常）（260）
					1. Unhandled exceptions（未处理的异常）（261）
					2. Using multiple catch handlers（使用多个 catch 处理程序）（263）
					3. Catching multiple exceptions（捕获多个异常）（264）
					4. Filtering exceptions（过滤异常）（266）
					5. Propagating exceptions（传播异常）（272）
				2. Using checked and unchecked integer arithmetic（使用已检查和未检查的整数算术）（274）
					1. Writing checked statements（编写检查语句）（275）
					2. Writing checked expressions（编写检查表达式）（276）
				3. Throwing exceptions（抛出异常）（280）
					1. Using throw expressions（使用抛出表达式）（286）
				4. Using a finally block（使用finally块）（287）
		2. Understanding the C# object model（了解 C# 对象模型）（291）
			1. Creating and managing classes and objects（创建和管理类和对象）（292）
				1. Understanding classification（了解分类）（292）
				2. The purpose of encapsulation（封装的目的）（293）
				3. Defining and using a class（定义和使用类）（293）
				4. Controlling accessibility（控制可访问性）（296）
				5. Working with constructors（与构造函数一起工作）（298）
					1. Overloading constructors（重载构造函数）（300）
					2. Deconstructing an object（解构一个对象）（311）
				6. Understanding static methods and data（了解静态方法和数据）（312）
					1. Creating a shared field（创建共享字段）（314）
					2. Creating a static field by using the const keyword（使用 const 关键字创建静态字段）（315）
					3. Understanding static classes（了解静态类）（315）
					4. Static using statements（静态using语句）（316）
				7. Anonymous classes（匿名类）（319）
			2. Understanding values and references（了解值和引用）（324）
				1. Copying value type variables and classes（复制值类型变量和类）（324）
				2. Understanding null values and nullable types（了解 null 值和可为 null 的类型）（333）
					1. The null-conditional and null-coalescing operators（null 条件运算符和 null 合并运算符）（335）
					2. Using nullable types（使用可空类型）（337）
					3. Understanding the properties of nullable types（了解可为空类型的属性）（338）
				3. Using ref and out parameters（使用 ref 和 out 参数）（339）
					1. Creating ref parameters（创建参考参数）（340）
					2. Creating out parameters（创建输出参数）（341）
				4. How computer memory is organized（计算机内存是如何组织的）（345）
					1. Using the stack and the heap（使用栈和堆）（347）
					2. The System.Object class（System.Object 类）（348）
					3. Boxing（装箱）（349）
					4. Unboxing（拆箱）（350）
				5. Casting data safely（安全地投射数据）（352）
					1. The is operator（is 运算符）（353）
					2. The as operator（as 运算符）（354）
					3. The switch statement revisited（重新审视 switch 语句（354）
			3. Creating value types with enumerations and structures（使用枚举和结构创建值类型）（363）
				1. Working with enumerations（使用枚举）（363）
					1. Declaring an enumeration（声明一个枚举）（364）
					2. Using an enumeration（使用枚举）（364）
					3. Choosing enumeration literal values（选择枚举文字值）（365）
					4. Choosing an enumeration’s underlying type（选择枚举的基础类型）（367）
				2. Working with structures（使用结构）（370）
					1. Declaring a structure（声明一个结构体）（372）
					2. Understanding differences between structures and classes（了解结构和类之间的差异）（374）
					3. Declaring structure variables（声明结构变量）（377）
					4. Understanding structure initialization（了解结构初始化）（378）
					5. Copying structure variables（复制结构变量）（384）
			4. Using arrays（使用数组）（392）
				1. Declaring array variables（声明数组变量）（393）
				2. Creating an array instance（创建数组实例）（394）
				3. Populating and using an array（填充和使用数组）（395）
					1. Creating an implicitly typed array（创建隐式类型数组）（396）
					2. Accessing an individual array element（访问单个数组元素）（398）
					3. Accessing a series of array elements（访问一系列数组元素）（399）
					4. Iterating through an array（迭代数组）（399）
					5. Passing arrays as parameters or return values for a method（将数组作为方法的参数或返回值传递）（401）
				4. Copying arrays（复制数组）（404）
				5. Using multidimensional arrays（使用多维数组）（406）
					1. Creating jagged arrays（创建锯齿状数组）（407）
				6. Accessing arrays that contain value types（访问包含值类型的数组）（421）
			5. Understanding parameter arrays（了解参数数组）（429）
				1. Overloading: a recap（重载：回顾）（429）
				2. Using array arguments（使用数组参数）（431）
					1. Declaring a params array（声明一个 params 数组）（433）
					2. Using params object[ ]（使用参数对象[]）（436）
					3. Using a params array（使用参数数组）（438）
				3. Comparing parameter arrays and optional parameters（比较参数数组和可选参数）（442）
			6. Working with inheritance（使用继承）（447）
				1. What is inheritance?（什么是继承？）（447）
				2. Using inheritance（使用继承）（448）
					1. The System.Object class revisited（重新审视 System.Object 类）（451）
					2. Calling base-class constructors（调用基类构造函数）（451）
					3. Assigning classes（分配类）（453）
					4. Declaring new methods（声明新方法）（455）
					5. Declaring virtual methods（声明虚拟方法）（457）
					6. Declaring override methods（声明覆盖方法）（458）
					7. Understanding protected access（了解受保护的访问）（462）
				3. Creating extension methods（创建扩展方法）（470）
			7. Creating interfaces and defining abstract classes（创建接口并定义抽象类）（478）
				1. Understanding interfaces（了解接口）（478）
					1. Defining an interface（定义接口）（480）
					2. Implementing an interface（实现接口）（480）
					3. Referencing a class through its interface（通过类的接口引用类）（483）
					4. Working with multiple interfaces（使用多个接口）（484）
					5. Explicitly implementing an interface（显式实现接口）（484）
					6. Handling versioning with interfaces（使用接口处理版本控制）（487）
					7. Interface restrictions（接口限制）（490）
					8. Defining and using interfaces（定义和使用接口）（490）
				2. Abstract classes（抽象类）（502）
					1. Abstract methods（抽象方法）（504）
				3. Sealed classes（密封类）（505）
					1. Sealed methods（密封方法）（506）
					2. Implementing and using an abstract class（实现和使用抽象类）（506）
			8. Using garbage collection and resource management（使用垃圾收集和资源管理）（517）
				1. The life and times of an object（物体的生命和时间）（517）
					1. Writing finalizers（编写终结器）（519）
					2. Why use the garbage collector?（为什么要使用垃圾收集器？）（522）
					3. How does the garbage collector work?（垃圾收集器如何工作？）（525）
					4. Recommendations（建议）（526）
				2. Resource management（资源管理）（526）
					1. Disposal methods（处置方法）（527）
					2. Exception-safe disposal（异常安全处置）（527）
					3. The using statement and the IDisposable interface（using 语句和 IDisposable 接口）（528）
					4. Calling the Dispose method from a finalizer（从终结器调用 Dispose 方法）（531）
				3. Implementing exception-safe disposal（实施异常安全处置）（533）
				4. Handling asynchronous disposal（处理异步处置）（545）
		3. Understanding the C# object model（了解 C# 对象模型）（550）
			1. Implementing properties to access fields（实现属性来访问字段）（552）
				1. Implementing encapsulation by using methods（使用方法实现封装）（552）
				2. What are properties?（什么是属性？）（555）
					1. Using properties（使用属性）（558）
					2. Read-only properties（只读属性）（559）
					3. Write-only properties（只写属性）（560）
					4. Property accessibility（物业无障碍）（561）
				3. Understanding property restrictions（了解财产限制）（562）
				4. Declaring interface properties（声明接口属性）（564）
					1. Replacing methods with properties（用属性替换方法）（566）
					2. Pattern-matching with properties（与属性进行模式匹配）（571）
				5. Generating automatic properties（生成自动属性）（573）
				6. Initializing objects by using properties（使用属性初始化对象）（576）
					1. Automatic properties and immutability（自动属性和不变性）（579）
				7. Using records with properties to implement ightweight structures（使用具有属性的记录来实现轻量级结构）（582）
			2. Handling binary data and using indexers（处理二进制数据并使用索引器）（595）
				1. What is an indexer?（什么是索引器？）（595）
					1. Storing binary values（存储二进制值）（595）
					2. Displaying binary values（显示二进制值）（597）
					3. Manipulating binary values（操作二进制值）（597）
					4. Solving the same problems using indexers（使用索引器解决相同的问题）（600）
				2. Understanding indexer accessors（了解索引器访问器）（603）
				3. Comparing indexers and arrays（比较索引器和数组）（604）
				4. Indexers in interfaces（接口中的索引器）（607）
				5. Using indexers in a Windows application（在 Windows 应用程序中使用索引器）（608）
			3. Introducing generics（泛型介绍）（620）
				1. The problem: Issues with the object type（问题：对象类型问题）（620）
				2. The generics solution（泛型解决方案）（625）
					1. Generics vs. generalized classes（泛型与泛化类）（628）
					2. Generics and constraints（泛型和约束）（628）
				3. Creating a generic class（创建泛型类）（629）
					1. The theory of binary trees（二叉树理论）（629）
					2. Building a binary tree class by using generics（使用泛型构建二叉树类）（634）
				4. Creating a generic method（创建通用方法）（646）
					1. Defining a generic method to build a binary tree（定义构建二叉树的通用方法）（648）
				5. Variance and generic interfaces（变体和通用接口）（653）
					1. Covariant interfaces（协变接口）（656）
					2. Contravariant interfaces（逆变接口）（658）
			4. Using collections（使用集合）（664）
				1. What are collection classes?（什么是集合类？）（664）
					1. The List< T> collection class（List< T> 集合类）（666）
					2. The LinkedList< T> collection class（LinkedList< T> 集合类）（669）
					3. The Queue< T> collection class（Queue< T> 集合类）（672）
					4. The PriorityQueue<TElement, TPriority> collection class（PriorityQueue<TElement, TPriority> 集合类）（673）
					5. The Stack< T> collection class（Stack< T> 集合类）（674）
					6. The Dictionary<TKey, TValue> collection class（Dictionary<TKey, TValue> 集合类）（675）
					7. The SortedList<TKey, TValue> collection class（SortedList<TKey, TValue> 集合类）（677）
					8. The HashSet< T> collection class（HashSet< T> 集合类）（679）
				2. Using collection initializers（使用集合初始值设定项）（681）
				3. Find methods, predicates, and lambda expressions（查找方法、谓词和 lambda 表达式）（682）
					1. The forms of lambda expressions（lambda 表达式的形式）（685）
					2. Lambda expressions and anonymous methods（Lambda 表达式和匿名方法）（687）
				4. Comparing arrays and collections（比较数组和集合）（687）
			5. Enumerating collections（枚举集合）（697）
				1. Enumerating the elements in a collection（枚举集合中的元素）（697）
					1. Manually implementing an enumerator（手动实现枚举器）（699）
					2. Implementing the IEnumerable interface（实现 IEnumerable 接口）（706）
				2. Implementing an enumerator by using an iterator（使用迭代器实现枚举器）（710）
					1. A simple iterator（一个简单的迭代器）（710）
					2. Defining an enumerator for the Tree< TItem> class by using an iterator（使用迭代器为 Tree< TItem> 类定义枚举器）（713）
			6. Decoupling application logic and handling events（解耦应用程序逻辑和处理事件）（719）
				1. Understanding delegates（了解委托）（720）
				2. Examples of delegates in the .NET class library（.NET 类库中的委托示例）（721）
					1. The automated factory scenario（自动化工厂场景）（724）
					2. Implementing the factory control system without using delegates（在不使用委托的情况下实施工厂控制系统）（724）
					3. Implementing the factory by using a delegate（使用委托来实现工厂）（725）
					4. Declaring and using delegates（声明和使用委托）（729）
				3. Lambda expressions and delegates（Lambda 表达式和委托）（742）
				4. Enabling notifications by using events（使用事件启用通知）（743）
					1. Declaring an event（宣布一个事件）（744）
					2. Subscribing to an event（订阅活动）（745）
					3. Unsubscribing from an event（取消订阅活动）（746）
					4. Raising an event（发起一个事件）（746）
				5. Understanding user-interface events（了解用户界面事件）（747）
				6. Using events（使用事件）（749）
			7. Querying in-memory data by using query expressions（使用查询表达式查询内存数据）（763）
				1. What is LINQ?（什么是 LINQ？）（763）
				2. Using LINQ in a C# application（在 C# 应用程序中使用 LINQ）（764）
					1. Selecting data（选择数据）（767）
					2. Filtering data（过滤数据）（771）
					3. Ordering, grouping, and aggregating data（对数据进行排序、分组和聚合）（772）
					4. Joining data（加入数据）（776）
					5. Using query operators（使用查询运算符）（778）
					6. Querying data in Tree< TItem> objects（查询 Tree< TItem> 对象中的数据）（782）
				3. LINQ and deferred evaluation（LINQ 和延迟评估）（791）
			8. Operator overloading（运算符重载）（799）
				1. Understanding operators（了解运算符）（799）
					1. Operator constraints（操作员限制）（800）
					2. Overloaded operators（重载运算符）（801）
					3. Creating symmetric operators（创建对称运算符）（803）
					4. Understanding compound assignment evaluation（了解复合作业评估）（805）
				2. Declaring increment and decrement operators（声明自增和自减运算符）（805）
				3. Comparing operators in structures and classes（比较结构和类中的运算符）（807）
				4. Defining operator pairs（定义运算符对）（808）
				5. Implementing operators（实施运算符）（809）
				6. Overriding the equality operators（覆盖相等运算符）（814）
				7. Understanding conversion operators（了解转换运算符）（819）
					1. Providing built-in conversions（提供内置转换）（820）
					2. Implementing user-defined conversion operators（实现用户定义的转换运算符）（821）
					3. Creating symmetric operators, revisited（重新审视创建对称运算符）（822）
					4. Writing conversion operators（编写转换运算符）（823）
		4. Building Universal Windows Platform applications with C#（使用 C# 构建通用 Windows 平台应用程序）（829）
			1. Improving throughput by using tasks（通过使用任务提高吞吐量）（831）
				1. Why perform multitasking by using parallel processing?（为什么要使用并行处理来执行多任务处理？）（831）
				2. The rise of the multicore processor（多核处理器的兴起）（832）
				3. Implementing multitasking by using Microsoft .NET（使用 Microsoft .NET 实现多任务处理）（834）
					1. Tasks, threads, and the ThreadPool（任务、线程和线程池）（835）
					2. Creating, running, and controlling tasks（创建、运行和控制任务）（836）
					3. Using the Task class to implement parallelism（使用Task类实现并行性）（840）
					4. Abstracting tasks by using the Parallel class（使用 Parallel 类抽象任务）（842）
					5. When not to use the Parallel class（何时不使用 Parallel 类）（860）
				4. Canceling tasks and handling exceptions（取消任务和处理异常）（863）
					1. The mechanics of cooperative cancellation（合作取消的机制）（863）
					2. Handling task exceptions by using the AggregateException class（使用 AggregateException 类处理任务异常）（879）
					3. Using continuations with canceled and faulted tasks（对已取消和有错误的任务使用延续）（881）
			2. Improving response time by performing asynchronous operations（通过执行异步操作来缩短响应时间）（887）
				1. Implementing asynchronous methods（实现异步方法）（889）
					1. Defining asynchronous methods: the problem（定义异步方法：问题）（889）
					2. Defining asynchronous methods: the solution（定义异步方法：解决方案）（894）
					3. Defining asynchronous methods that return values（定义返回值的异步方法）（902）
					4. Asynchronous method pitfalls（异步方法的陷阱）（904）
					5. Asynchronous methods and the Windows Runtime APIs（异步方法和 Windows 运行时 API）（906）
					6. Tasks, memory allocation, and efficiency（任务、内存分配和效率）（909）
				2. Using PLINQ to parallelize declarative data access（使用 PLINQ 并行化声明性数据访问）（913）
					1. Using PLINQ to improve performance while iterating through a collection（使用 PLINQ 提高迭代集合时的性能）（914）
					2. Canceling a PLINQ query（取消 PLINQ 查询）（922）
				3. Synchronizing concurrent access to data（同步并发访问数据）（922）
					1. Locking data（锁定数据）（927）
					2. Synchronization primitives for coordinating tasks（用于协调任务的同步原语）（927）
					3. ManualResetEventSlim（928）
					4. SemaphoreSlim（928）
					5. CountdownEvent（929）
					6. ReaderWriterLockSlim（929）
					7. Barrier（障碍）（930）
					8. Canceling synchronization（取消同步）（931）
					9. The concurrent collection classes（并发集合类）（931）
					10. Using a concurrent collection and a lock to implement thread-safe data access（使用并发集合和锁实现线程安全的数据访问）（933）
			3. Implementing the user interface for a Universal Windows Platform app（实现通用 Windows 平台应用程序的用户界面）（953）
				1. Features of a Universal Windows Platform app（通用 Windows 平台应用程序的功能）（955）
				2. Using the Blank App template to build a Universal Windows Platform app（使用空白应用程序模板构建通用Windows平台应用程序）（959）
				3. Implementing a scalable user interface（实现可扩展的用户界面）（963）
					1. Implementing a tabular layout by using a Grid control（使用网格控件实现表格布局）（980）
					2. Adapting the layout by using the Visual State Manager（使用视觉状态管理器调整布局）（992）
				4. Applying styles to a UI（将样式应用到 UI）（1002）
			4. Displaying and searching for data in a Universal Windows Platform app（在通用 Windows 平台应用程序中显示和搜索数据）（1019）
				1. Implementing the Model-View-ViewModel pattern（实现模型-视图-视图模型模式）（1019）
				2. Displaying data by using data binding（使用数据绑定显示数据）（1021）
					1. Modifying data by using data binding（使用数据绑定修改数据）（1029）
					2. Using data binding with a ComboBox control（将数据绑定与 ComboBox 控件一起使用）（1036）
				3. Creating a ViewModel（创建视图模型）（1038）
				4. Adding commands to a ViewModel（向 ViewModel 添加命令）（1043）
			5. Accessing a remote database from a Universal Windows Platform app（从通用 Windows 平台应用程序访问远程数据库）（1059）
				1. Retrieving data from a database（从数据库检索数据）（1059）
					1. Creating an entity model（创建实体模型）（1075）
					2. Creating and using a REST web service（创建和使用 REST Web 服务）（1084）
				2. Updating the UWP application to use the web service（更新 UWP 应用程序以使用 Web 服务）（1107）
				3. Searching for data in the Customers app（在客户应用程序中搜索数据）（1120）
				4. Inserting, updating, and deleting data through a REST web service（通过 REST Web 服务插入、更新和删除数据）（1129）
	10. C# in Depth FOURTH EDITION（深入理解C#第四版）
		1. C# in context（上下文中的  C#）（30）
			1. Survival of the sharpest（最敏锐的人生存）（32）
				1. An evolving language（不断发展的语言）（32）
					1. A helpful type system at large and small scales（在大尺度和小尺度上都有帮助的类型系统）（33）
					2. Ever more concise code（代码更加简洁）（35）
						1. CONSTRUCTION AND INITIALIZATION（构造和初始化）（35）
						2. METHOD AND PROPERTY DECLARATIONS（方法和属性声明）（37）
						3. STRING HANDLING（字符串处理）（37）
					3. Simple data access with LINQ（使用  LINQ  进行简单的数据访问）（38）
					4. Asynchrony（异步）（39）
					5. Balancing efficiency and complexity（平衡效率和复杂性）（40）
					6. Evolution at speed: Using minor versions（快速演进：使用次要版本）（41）
				2. An evolving platform（不断发展的平台）（42）
				3. An evolving community（不断发展的社区）（43）
				4. An evolving book（一本不断发展的书）（44）
					1. Mixed-level coverage（混合层次覆盖）（45）
					2. Examples using Noda Time（使用野田时间的示例）（45）
					3. Terminology choices（术语选择）（46）
		2. C# 2–5（48）
			1. C# 2（50）
				1. Generics（泛型）（51）
					1. Introduction by example: Collections before generics（举例介绍：集合先于泛型）（51）
					2. Generics save the day（泛型拯救世界）（54）
						1. TYPE PARAMETERS AND TYPE ARGUMENTS（类型参数和类型自变量）（55）
						2. ARITY OF GENERIC TYPES AND METHODS（通用类型和方法的数量）（57）
					3. What can be generic?（什么可以是通用的？）（58）
					4. Type inference for type arguments to methods（方法的类型参数的类型推断）（59）
					5. Type constraints（类型约束）（61）
					6. The default and typeof operators（默认和typeof运算符）（63）
					7. Generic type initialization and state（泛型类型初始化和状态）（66）
				2. Nullable value types（可空值类型）（67）
					1. Aim: Expressing an absence of information（目的：表达信息缺失）（68）
					2. CLR and framework support: The Nullable< T> struct（CLR  和框架支持：Nullable< T>  结构）（69）
						1. BOXING BEHAVIOR（拳击行为）（71）
					3. Language support（语言支持）（72）
						1. THE ? TYPE SUFFIX（的？类型后缀）（72）
						2. THE NULL LITERAL（空文字）（73）
						3. CONVERSIONS（转换）（73）
						4. LIFTED OPERATORS（提升运算符）（74）
						5. NULLABLE LOGIC（可空逻辑）（75）
						6. THE AS OPERATOR AND NULLABLE VALUE TYPES（AS  运算符和可空值类型）（77）
						7. THE NULL-COALESCING ?? OPERATOR（空合并？操作员）（77）
				3. Simplified delegate creation（简化委托创建）（78）
					1. Method group conversions（方法组转换）（79）
					2. Anonymous methods（匿名方法）（79）
					3. Delegate compatibility（委托兼容性）（81）
				4. Iterators（迭代器）（82）
					1. Introduction to iterators（迭代器简介）（83）
					2. Lazy execution（惰性执行）（84）
					3. Evaluation of yield statements（收益率报表的评估）（85）
					4. The importance of being lazy（懒惰的重要性）（86）
					5. Evaluation of finally blocks（finally块的评估）（87）
					6. The importance of finally handling（最终处理的重要性）（90）
					7. Implementation sketch（实现示意图）（91）
				5. Minor features（小特征）（95）
					1. Partial types（部分类型）（96）
						1. PARTIAL METHODS (C# 3)（部分方法(C#  3)）（97）
					2. Static classes（静态类）（98）
					3. Separate getter/setter access for properties（属性的单独  getter/setter  访问）（98）
					4. Namespace aliases（命名空间别名）（99）
						1. NAMESPACE ALIAS QUALIFIER SYNTAX（命名空间别名限定符语法）（99）
						2. THE GLOBAL NAMESPACE ALIAS（全局命名空间别名）（100）
						3. EXTERN ALIASES（外部别名）（100）
					5. Pragma directives（杂注指令）（101）
					6. Fixed-size buffers（固定大小缓冲区）（102）
						1. IMPROVED ACCESS TO FIXED-SIZED BUFFERS IN FIELDS IN C# 7.3（改进了对C#  7.3中字段中固定大小缓冲区的访问）（102）
					7. InternalsVisibleTo（内部可见）（102）
			2. C# 3:LINQ and everything that comes with it（C# 3:LINQ 及其附带的所有内容）（104）
				1. Automatically implemented properties（自动实现的属性）（105）
				2. Implicit typing（隐式类型）（105）
					1. Typing terminology（键入术语）（106）
						1. STATIC AND DYNAMIC TYPING（静态和动态打字）（106）
						2. EXPLICIT AND IMPLICIT TYPING（显式和隐式类型）（106）
					2. Implicitly typed local variables (var)（隐式类型局部变量（var））（107）
					3. Implicitly typed arrays（隐式类型数组）（108）
				3. Object and collection initializers（对象和集合初始值设定项）（110）
					1. Introduction to object and collection initializers（对象和集合初始值设定项简介）（110）
					2. Object initializers（对象初始值设定项）（112）
					3. Collection initializers（集合初始值设定项）（113）
					4. The benefits of single expressions for initialization（单个表达式初始化的好处）（115）
				4. Anonymous types（匿名类型）（115）
					1. Syntax and basic behavior（语法和基本行为）（115）
					2. The compiler-generated type（编译器生成的类型）（118）
					3. Limitations（限制）（119）
				5. Lambda expressions（Lambda表达式）（120）
					1. Lambda expression syntax（Lambda  表达式语法）（121）
					2. Capturing variables（捕获变量）（123）
						1. IMPLEMENTING CAPTURED VARIABLES WITH A GENERATED CLASS（使用生成的类实现捕获的变量）（124）
						2. MULTIPLE INSTANTIATIONS OF LOCAL VARIABLES（局部变量的多个实例化）（126）
						3. CAPTURING VARIABLES FROM MULTIPLE SCOPES（从多个范围捕获变量）（128）
					3. Expression trees（表达式树）（130）
						1. LIMITATIONS OF CONVERSIONS TO EXPRESSION TREES（转换为表达式树的局限性）（131）
						2. COMPILING EXPRESSION TREES TO DELEGATES（将表达式树编译为委托）（131）
				6. Extension methods（扩展方法）（132）
					1. Declaring an extension method（声明扩展方法）（132）
					2. Invoking an extension method（调用扩展方法）（133）
					3. Chaining method calls（链接方法调用）（135）
				7. Query expressions（查询表达式）（136）
					1. Query expressions translate from C# to C#（查询表达式从  C#  转换为  C#）（137）
					2. Range variables and transparent identifiers（范围变量和透明标识符）（137）
					3. Deciding when to use which syntax for LINQ（决定何时使用  LINQ  的语法）（139）
				8. The end result: LINQ（最终结果：LINQ）（140）
			3.  C# 4:Improving interoperability（C# 4:提高互操作性）（142）
				1. Dynamic typing（动态类型）（143）
					1. Introduction to dynamic typing（动态类型简介）（143）
						1. WHAT IS THE DYNAMIC TYPE?（什么是动态类型？）（144）
						2. APPLYING DYNAMIC BINDING IN A VARIETY OF CONTEXTS（在各种上下文中应用动态绑定）（145）
						3. WHAT CAN THE COMPILER CHECK IN DYNAMICALLY BOUND CONTEXTS?（编译器可以在动态绑定上下文中检查什么？）（146）
						4. WHAT OPERATIONS INVOLVING DYNAMIC VALUES AREN’T DYNAMICALLY BOUND?（哪些涉及动态值的操作不受动态约束？）（147）
						5. WHAT OPERATIONS INVOLVING DYNAMIC VALUES STILL HAVE A STATIC TYPE?（哪些涉及动态值的操作仍然具有静态类型？）（147）
					2. Dynamic behavior beyond reflection（超越反射的动态行为）（148）
						1. IMAGINARY EXAMPLE OF DATABASE ACCESS（数据库访问的假想示例）（148）
						2. EXPANDOOBJECT: A DYNAMIC BAG OF DATA AND METHODS（EXPANDOOBJECT：动态数据包和方法）（149）
						3. THE DYNAMIC VIEW OF JSON.NET（JSON.NET的动态视图）（150）
						4. IMPLEMENTING DYNAMIC BEHAVIOR IN YOUR OWN CODE（在您自己的代码中实现动态行为）（150）
					3. A brief look behind the scenes（幕后简要介绍）（153）
						1. WHO DOES WHAT?（谁做了什么？）（153）
						2. THE IL GENERATED FOR DYNAMIC TYPING（为动态打字生成的IL）（154）
					4. Limitations and surprises in dynamic typing（动态类型的限制和意外）（156）
						1. THE DYNAMIC TYPE AND GENERICS（动态类型和泛型）（156）
						2. EXTENSION METHODS（扩展方法）（157）
						3. ANONYMOUS FUNCTIONS（匿名函数）（158）
						4. ANONYMOUS TYPES（匿名类型）（159）
						5. EXPLICIT INTERFACE IMPLEMENTATION（显式接口实现）（160）
					5. Usage suggestions（使用建议）（160）
						1. SIMPLER REFLECTION（更简单的反思）（161）
						2. COMMON MEMBERS WITHOUT A COMMON INTERFACE（没有通用接口的通用成员）（162）
						3. USING A LIBRARY BUILT FOR DYNAMIC TYPING（使用为动态打字而构建的库）（162）
				2. Optional parameters and named arguments（可选参数和命名参数）（162）
					1. Parameters with default values and arguments with names（带默认值的参数和带名称的参数）（163）
					2. Determining the meaning of a method call（确定方法调用的含义）（164）
					3. Impact on versioning（对版本控制的影响）（166）
						1. PARAMETER NAME CHANGES ARE BREAKING（参数名称更改造成破坏）（166）
						2. DEFAULT VALUE CHANGES ARE AT LEAST SURPRISING（默认值的变化至少令人惊讶）（166）
						3. ADDING OVERLOADS IS FIDDLY（添加过载非常繁琐）（167）
				3. COM interoperability improvements（COM  互操作性改进）（167）
					1. Linking primary interop assemblies（链接主互操作程序集）（168）
					2. Optional parameters in COM（COM  中的可选参数）（169）
					3. Named indexers（命名索引器）（171）
				4. Generic variance（通用方差）（172）
					1. Simple examples of variance in action（行动差异的简单例子）（172）
					2. Syntax for variance in interface and delegate declarations（接口和委托声明中差异的语法）（173）
					3. Restrictions on using variance（使用方差的限制）（174）
					4. Generic variance in practice（实践中的一般差异）（176）
			4. Writing asynchronous code（编写异步代码）（179）
				1. Introducing asynchronous functions（引入异步函数）（181）
					1. First encounters of the asynchronous kind（第一次遇到异步类型）（181）
					2. Breaking down the first example（分解第一个例子）（183）
				2. Thinking about asynchrony（异步的思考）（184）
					1. Fundamentals of asynchronous execution（异步执行的基础知识）（184）
					2. Synchronization contexts（同步上下文）（186）
					3. Modeling asynchronous methods（异步方法建模）（187）
				3. Async method declarations（异步方法声明）（189）
					1. Return types from async methods（异步方法的返回类型）（190）
					2. Parameters in async methods（异步方法中的参数）（191）
				4. Await expressions（Await  表达式）（191）
					1. The awaitable pattern（可等待模式）（192）
					2. Restrictions on await expressions（对await表达式的限制）（194）
				5. Wrapping of return values（返回值的包装）（195）
				6. Asynchronous method flow（异步方法流程）（197）
					1. What is awaited and when?（等待什么以及何时？）（197）
					2. Evaluation of await expressions（await表达式的求值）（198）
					3. The use of awaitable pattern members（可等待模式成员的使用）（202）
					4. Exception unwrapping（异常展开）（203）
					5. Method completion（方法完成）（205）
						1. RETURNING SUCCESSFULLY（顺利归来）（206）
						2. LAZY EXCEPTIONS AND ARGUMENT VALIDATION（惰性异常和参数验证）（206）
						3. HANDLING CANCELLATION（处理取消）（208）
				7. Asynchronous anonymous functions（异步匿名函数）（209）
				8. Custom task types in C# 7（C#  7  中的自定义任务类型）（211）
					1. The 99.9% case: ValueTask< TResult>（99.9%的情况：ValueTask< TResult>）（211）
					2. The 0.1% case: Building your own custom task type（0.1%  案例：构建您自己的自定义任务类型）（213）
				9. Async main methods in C# 7.1（C#  7.1  中的异步主要方法）（215）
				10. Usage tips（使用提示）（216）
					1. Avoid context capture by using ConfigureAwait (where appropriate)（使用ConfigureAwait（在适当的情况下）避免上下文捕获）（216）
					2. Enable parallelism by starting multiple independent tasks（通过启动多个独立任务来启用并行性）（218）
					3. Avoid mixing synchronous and asynchronous code（避免混合同步和异步代码）（219）
					4. Allow cancellation wherever possible（尽可能允许取消）（219）
					5. Testing asynchrony（测试异步）（220）
			5. Async implementation（异步实现）（222）
				1. Structure of the generated code（生成代码的结构）（224）
					1. The stub method: Preparation and taking the first step（存根方法：准备和采取第一步）（227）
					2. Structure of the state machine（状态机结构）（228）
					3. The MoveNext() method (high level)（MoveNext()  方法（高级））（231）
					4. The SetStateMachine method and the state machine boxing dance（SetStateMachine方法和状态机拳击舞）（233）
				2. A simple MoveNext() implementation（一个简单的  MoveNext()  实现）（234）
					1. A full concrete example（一个完整的具体例子）（234）
					2. MoveNext() method general structure（MoveNext()方法总体结构）（236）
					3. Zooming into an await expression（放大await表达式）（238）
				3. How control flow affects MoveNext()（控制流如何影响MoveNext()）（239）
					1. Control flow between await expressions is simple（await表达式之间的控制流很简单）（240）
					2. Awaiting within a loop（循环内等待）（241）
					3. Awaiting within a try/finally block（在  try/finally  块内等待）（242）
				4. Execution contexts and flow（执行上下文和流程）（245）
				5. Custom task types revisited（重新审视自定义任务类型）（247）
			6. C# 5 bonus features（C#  5  个额外功能）（249）
				1. Capturing variables in foreach loops（在foreach循环中捕获变量）（249）
				2. Caller information attributes（来电信息属性）（251）
					1. Basic behavior（基本行为）（251）
					2. Logging（日志记录）（253）
					3. Simplifying INotifyPropertyChanged implementations（简化  INotifyPropertyChanged  实现）（253）
					4. Corner cases of caller information attributes（呼叫者信息属性的极端情况）（255）
						1. DYNAMICALLY INVOKED MEMBERS（动态调用成员）（255）
						2. NON-OBVIOUS MEMBER NAMES（不明显的成员姓名）（257）
						3. IMPLICIT CONSTRUCTOR INVOCATIONS（隐式构造函数调用）（257）
						4. QUERY EXPRESSION INVOCATIONS（查询表达式调用）（258）
						5. ATTRIBUTES WITH CALLER INFORMATION ATTRIBUTES（具有呼叫者信息属性的属性）（259）
					5. Using caller information attributes with old versions of .NET（在旧版本的 .NET  中使用调用者信息属性）（261）
		3. C# 6（262）
			1. Super-sleek properties and expression-bodied members（超级时尚的属性和表情丰富的成员）（264）
				1. A brief history of properties（属性简史）（265）
				2. Upgrades to automatically implemented properties（升级到自动实现的属性）（267）
					1. Read-only automatically implemented properties（只读自动实现的属性）（267）
					2. Initializing automatically implemented properties（初始化自动实现的属性）（268）
					3. Automatically implemented properties in structs（结构体中自动实现的属性）（269）
				3. Expression-bodied members（表达式体成员）（271）
					1. Even simpler read-only computed properties（更简单的只读计算属性）（271）
						1. PASS-THROUGH OR DELEGATING PROPERTIES（传递或委托属性）（273）
						2. PERFORMING SIMPLE LOGIC ON ANOTHER PIECE OF STATE（对另一个状态执行简单的逻辑）（274）
					2. Expression-bodied methods, indexers, and operators（表达式体方法、索引器和运算符）（274）
					3. Restrictions on expression-bodied members in C# 6（C#  6  中表达式主体成员的限制）（276）
					4. Guidelines for using expression-bodied members（使用表达式主体成员的指南）（278）
			2. Stringy features（字符串特性）（281）
				1. A recap on string formatting in .NET（.NET  中字符串格式的回顾）（282）
					1. Simple string formatting（简单的字符串格式化）（282）
					2. Custom formatting with format strings（使用格式字符串自定义格式）（282）
					3. Localization（本地化）（284）
						1. FORMATTING WITH THE DEFAULT CULTURE（使用默认文化进行格式化）（286）
						2. FORMATTING FOR MACHINES（机器格式化）（286）
				2. Introducing interpolated string literals（引入内插字符串文字）（287）
					1. Simple interpolation（简单插值）（287）
					2. Format strings in interpolated string literals（格式化内插字符串文字中的字符串）（288）
					3. Interpolated verbatim string literals（内插的逐字字符串文字）（288）
					4. Compiler handling of interpolated string literals (part 1)（内插字符串文字的编译器处理（第  1  部分））（290）
				3. Localization using FormattableString（使用  FormattableString  进行本地化）（290）
					1. Compiler handling of interpolated string literals (part 2)（编译器处理内插字符串文字（第  2  部分））（291）
					2. Formatting a FormattableString in a specific culture（在特定区域性中格式化  FormattableString）（292）
						1. FORMATTING IN A NONINVARIANT CULTURE（非不变文化中的格式化）（294）
					3. Other uses for FormattableString（FormattableString  的其他用途）（294）
					4. Using FormattableString with older versions of .NET（在旧版本的 .NET  中使用  FormattableString）（297）
				4. Uses, guidelines, and limitations（用途、指南和限制）（299）
					1. Developers and machines, but maybe not end users（开发人员和机器，但可能不是最终用户）（299）
						1. MACHINE-READABLE STRINGS（机器可读字符串）（299）
						2. MESSAGES FOR OTHER DEVELOPERS（给其他开发者的信息）（300）
						3. MESSAGES FOR END USERS（给最终用户的信息）（300）
					2. Hard limitations of interpolated string literals（内插字符串文字的硬限制）（301）
						1. NO DYNAMIC FORMATTING（无动态格式）（301）
						2. NO EXPRESSION REEVALUATION（无需重新评估表达）（301）
						3. NO BARE COLONS（没有裸冒号）（302）
					3. When you can but really shouldn’t（当你可以但确实不应该时）（302）
						1. DEFER FORMATTING FOR STRINGS THAT MAY NOT BE USED（推迟可能不使用的字符串的格式化）（302）
						2. FORMAT FOR READABILITY（可读性格式）（303）
				5. Accessing identifiers with nameof（使用  nameof  访问标识符）（304）
					1. First examples of nameof（nameof  的第一个例子）（304）
					2. Common uses of nameof（nameof的常见用法）（306）
						1. ARGUMENT VALIDATION（参数验证）（306）
						2. PROPERTY CHANGE NOTIFICATION FOR COMPUTED PROPERTIES（计算属性的属性更改通知）（306）
						3. ATTRIBUTES（属性）（307）
					3. Tricks and traps when using nameof（使用  nameof  时的技巧和陷阱）（309）
						1. REFERRING TO MEMBERS OF OTHER TYPES（提及其他类型的成员）（309）
						2. GENERICS（泛型）（310）
						3. USING ALIASES（使用别名）（310）
						4. PREDEFINED ALIASES, ARRAYS AND NULLABLE VALUE TYPES（预定义别名、数组和可为空值类型）（311）
						5. THE NAME, THE SIMPLE NAME, AND ONLY THE NAME（名字，简单的名字，只有名字）（311）
						6. NAMESPACES（命名空间）（311）
			3. A smörgåsbord of features for concise code（简洁代码的一大堆功能）（313）
				1. Using static directives（使用静态指令）（313）
					1. Importing static members（导入静态成员）（314）
					2. Extension methods and using static（扩展方法和使用静态）（317）
				2. Object and collection initializer enhancements（对象和集合初始值设定项增强）（319）
					1. Indexers in object initializers（对象初始值设定项中的索引器）（320）
					2. Using extension methods in collection initializers（在集合初始值设定项中使用扩展方法）（323）
						1. CREATING OTHER GENERAL-PURPOSE ADD SIGNATURES（创建其他通用添加签名）（325）
						2. CREATING SPECIALIZED ADD SIGNATURES（创建专门的添加签名）（325）
						3. REEXPOSING EXISTING METHODS “HIDDEN” BY EXPLICIT INTERFACE IMPLEMENTATION（重新暴露通过显式接口实现“隐藏”的现有）（326）
					3. Test code vs. production code（测试代码与生产代码）（327）
				3. The null conditional operator（空条件运算符）（328）
					1. Simple and safe property dereferencing（简单安全的属性解除引用）（328）
					2. The null conditional operator in more detail（更详细的  null  条件运算符）（329）
					3. Handling Boolean comparisons（处理布尔比较）（330）
					4. Indexers and the null conditional operator（索引器和空条件运算符）（331）
					5. Working effectively with the null conditional operator（有效地使用空条件运算符）（332）
						1. SAFE AND CONVENIENT EVENT RAISING（安全便捷的活动举办）（332）
						2. MAKING THE MOST OF NULL-RETURNING APIS（充分利用返回  NULL的API）（333）
					6. Limitations of the null conditional operator（null  条件运算符的限制）（334）
				4. Exception filters（异常过滤器）（334）
					1. Syntax and semantics of exception filters（异常过滤器的语法和语义）（335）
						1. THE TWO-PASS EXCEPTION MODEL（两次异常模型）（336）
						2. CATCHING THE SAME EXCEPTION TYPE MULTIPLE TIMES（多次捕获相同的异常类型）（339）
					2. Retrying operations（重试操作）（340）
					3. Logging as a side effect（日志记录作为副作用）（341）
					4. Individual, case-specific exception filters（单独的、特定于案例的异常过滤器）（342）
					5. Why not just throw?（为什么不直接抛出呢？）（343）
		4. C# 7 and beyond（C#  7  及更高版本）（346）
			1. Composition using tuples（使用元组组合）（348）
				1. Introduction to tuples（元组简介）（349）
				2. Tuple literals and tuple types（元组文字和元组类型）（350）
					1. Syntax（语法）（350）
					2. Inferred element names for tuple literals (C# 7.1)（元组文字的推断元素名称  (C#  7.1)）（352）
					3. Tuples as bags of variables（元组作为变量袋）（353）
						1. ACCESSING ELEMENTS BY NAME AND POSITION（按名称和位置访问元素）（354）
						2. TREATING A TUPLE AS A SINGLE VALUE（将元组视为单个值）（355）
				3. Tuple types and conversions（元组类型和转换）（358）
					1. Types of tuple literals（元组文字的类型）（358）
					2. Conversions from tuple literals to tuple types（从元组文字到元组类型的转换）（359）
						1. IMPLICIT CONVERSIONS（隐式转换）（359）
						2. EXPLICIT CONVERSIONS（显式转换）（361）
						3. THE ROLE OF ELEMENT NAMES IN TUPLE LITERAL CONVERSIONS（元素名称在元组文字转换中的作用）（361）
					3. Conversions between tuple types（元组类型之间的转换）（363）
						1. TUPLE TYPE IDENTITY CONVERSIONS（元组类型身份转换）（364）
						2. LACK OF GENERIC VARIANCE CONVERSIONS（缺乏通用方差转换）（365）
					4. Uses of conversions（转换的使用）（365）
					5. Element name checking in inheritance（继承中的元素名称检查）（365）
					6. Equality and inequality operators (C# 7.3)（等式和不等式运算符  (C#  7.3)）（366）
				4. Tuples in the CLR（CLR  中的元组）（367）
					1. Introducing System.ValueTuple<. . .>（介绍System.ValueTuple<。 。 .>）（367）
					2. Element name handling（元素名称处理）（368）
						1. ELEMENT NAMES IN METADATA（元数据中的元素名称）（369）
						2. NO ELEMENT NAMES AT EXECUTION TIME（执行时没有元素名称）（369）
					3. Tuple conversion implementations（元组转换实现）（370）
					4. String representations of tuples（元组的字符串表示）（370）
					5. Regular equality and ordering comparisons（常规相等和排序比较）（371）
					6. Structural equality and ordering comparisons（结构相等和顺序比较）（372）
					7. Womples and large tuples（Womples和大元组）（374）
					8. The nongeneric ValueTuple struct（非泛型  ValueTuple  结构）（375）
					9. Extension methods（扩展方法）（375）
				5. Alternatives to tuples（元组的替代方案）（375）
					1. System.Tuple<. . .>（系统.元组<. 。 .>）（376）
					2. Anonymous types（匿名类型）（376）
					3. Named types（命名类型）（377）
				6. Uses and recommendations（用途和建议）（377）
					1. Nonpublic APIs and easily changed code（非公共  API  和易于更改的代码）（377）
					2. Local variables（局部变量）（378）
					3. Fields（字段）（379）
					4. Tuples and dynamic don’t play together nicely（元组和动态不能很好地协同工作）（380）
						1. THE DYNAMIC BINDER DOESN’T KNOW ABOUT ELEMENT NAMES（动态活页夹不知道元素名称）（380）
						2. THE DYNAMIC BINDER DOESN’T (CURRENTLY) KNOW ABOUT HIGH ELEMENT NUMBERS（动态绑定器（当前）不知道高元素编号）（381）
			2. Deconstruction and pattern matching（解构与模式匹配）（382）
				1. Deconstruction of tuples（元组的解构）（383）
					1. Deconstruction to new variables（解构为新变量）（384）
						1. A SPECIAL IDENTIFIER: _ DISCARDS（特殊标识符：_ 丢弃）（386）
					2. Deconstruction assignments to existing variables and properties（对现有变量和属性的解构赋值）（386）
					3. Details of tuple literal deconstruction（元组文字解构细节）（390）
				2. Deconstruction of nontuple types（非元组类型的解构）（390）
					1. Instance deconstruction methods（实例解构方法）（391）
					2. Extension deconstruction methods and overloading（扩展解构方法和重载）（392）
					3. Compiler handling of Deconstruct calls（编译器对解构调用的处理）（393）
				3. Introduction to pattern matching（模式匹配简介）（394）
				4. Patterns available in C# 7.0（C#  7.0  中可用的模式）（396）
					1. Constant patterns（恒定模式）（396）
					2. Type patterns（类型模式）（397）
					3. The var pattern（var  模式）（400）
				5. Using patterns with the is operator（将模式与  is  运算符一起使用）（401）
				6. Using patterns with switch statements（使用具有  switch  语句的模式）（403）
					1. Guard clauses（保护条款）（404）
					2. Pattern variable scope for case labels（case  标签的模式变量范围）（405）
					3. Evaluation order of pattern-based switch statements（基于模式的  switch  语句的评估顺序）（406）
				7. Thoughts on usage（使用思考）（408）
					1. Spotting deconstruction opportunities（发现解构机会）（408）
					2. Spotting pattern matching opportunities（发现模式匹配机会）（409）
			3. Improving efficiency with more pass by reference（通过更多引用传递提高效率）（410）
				1. Recap: What do you know about ref?（回顾：你对  ref  了解多少？）（411）
				2. Ref locals and ref returns（引用局部变量和引用返回）（414）
					1. Ref locals（引用局部变量）（414）
						1. INITIALIZATION: ONCE, ONLY ONCE, AND AT DECLARATION (BEFORE C# 7.3)（初始化：一次，仅一次，且在声明时（C#  7.3  之前））（417）
						2. NO REF FIELDS, OR LOCAL VARIABLES THAT WOULD LIVE BEYOND THE METHOD CALL（没有超出方法调用范围的引用字段或局部变量）（418）
						3. NO REFERENCES TO READ-ONLY VARIABLES（没有对只读变量的引用）（418）
						4. TYPES: ONLY IDENTITY CONVERSIONS ARE PERMITTED（类型：仅允许身份转换）（419）
					2. Ref returns（参考返回）（419）
					3. The conditional ?: operator and ref values (C# 7.2)（条件 ?:  运算符和  ref  值  (C#  7.2)）（421）
					4. Ref readonly (C# 7.2)（引用只读  (C#  7.2)）（422）
				3. in parameters (C# 7.2)（参数（C#  7.2））（424）
					1. Compatibility considerations（兼容性考虑）（425）
					2. The surprising mutability of in parameters: External changes（参数令人惊讶的可变性：外部变化）（426）
					3. Overloading with in parameters（in  参数重载）（427）
					4. Guidance for in parameters（in  参数指南）（428）
				4. Declaring structs as readonly (C# 7.2)（将结构声明为只读  (C#  7.2)）（430）
					1. Background: Implicit copying with read-only variables（背景：使用只读变量进行隐式复制）（430）
					2. The readonly modifier for structs（结构体的  readonly  修饰符）（432）
					3. XML serialization is implicitly read-write（XML序列化是隐式读写的）（433）
				5. Extension methods with ref or in parameters (C# 7.2)（带  ref  或  in  参数的扩展方法  (C#  7.2)）（434）
					1. Using ref/in parameters in extension methods to avoid copying（在扩展方法中使用  ref/in  参数以避免复制）（434）
					2. Restrictions on ref and in extension methods（对  ref  和扩展方法的限制）（436）
				6. Ref-like structs (C# 7.2)（类引用结构  (C#  7.2)）（437）
					1. Rules for ref-like structs（类引用结构的规则）（438）
					2. Span< T> and stackalloc（439）
						1. STACKALLOC WITH INITIALIZERS (C# 7.3)（带初始化器的  STACKALLOC  (C#  7.3)）（442）
						2. PATTERN-BASED FIXED STATEMENTS (C# 7.3)（基于模式的固定语句(C#  7.3)）（442）
					3. IL representation of ref-like structs（类引用结构的  IL  表示）（443）
			4. Concise code in C# 7（C#  7  中的简洁代码）（444）
				1. Local methods（局部方法）（444）
					1. Variable access within local methods（本地方法内的变量访问）（446）
						1. A LOCAL METHOD CAN CAPTURE ONLY VARIABLES THAT ARE IN SCOPE（局部方法只能捕获作用域内的变量）（446）
						2. A LOCAL METHOD MUST BE DECLARED AFTER THE DECLARATION OF ANY VARIABLES IT CAPTURES（必须在声明它捕获的任何变量之后声明本地方法）（446）
						3. A LOCAL METHOD CAN’T CAPTURE REF PARAMETERS OF THE ENCLOSING METHOD（本地方法无法捕获封闭方法的引用参数）（447）
						4. LOCAL METHODS INTERACT WITH DEFINITE ASSIGNMENT（本地方法与明确的分配交互）（448）
						5. LOCAL METHODS CAN’T ASSIGN READ-ONLY FIELDS（本地方法无法分配只读字段）（448）
					2. Local method implementations（本地方法实现）（449）
						1. CAPTURING VARIABLES IN MULTIPLE SCOPES（捕获多个范围内的变量）（451）
						2. PRISON BREAK! HOW LOCAL METHODS CAN ESCAPE THEIR CONTAINING CODE（越狱！本地方法如何转义其包含的代码）（452）
					3. Usage guidelines（使用指南）（454）
						1. ITERATOR/ASYNC ARGUMENT VALIDATION AND LOCAL METHOD OPTIMIZATION（迭代器/异步参数验证和本地方法优化）（455）
						2. READABILITY SUGGESTIONS（可读性建议）（456）
				2. Out variables（输出变量）（456）
					1. Inline variable declarations for out parameters（输出参数的内联变量声明）（456）
					2. Restrictions lifted in C# 7.3 for out variables and pattern variables（C#  7.3  中取消了对  out  变量和模式变量的限制）（457）
				3. Improvements to numeric literals（对数字文字的改进）（458）
					1. Binary integer literals（二进制整数字面量）（458）
					2. Underscore separators（下划线分隔符）（459）
				4. Throw expressions（抛出表达式）（460）
				5. Default literals (C# 7.1)（默认文字  (C#  7.1)）（461）
				6. Nontrailing named arguments (C# 7.2)（非尾随命名参数  (C#  7.2)）（462）
				7. Private protected access (C# 7.2)（私有受保护访问  (C#  7.2)）（464）
				8. Minor improvements in C# 7.3（C#  7.3  中的小改进）（464）
					1. Generic type constraints（泛型类型约束）（464）
					2. Overload resolution improvements（重载分辨率改进）（465）
					3. Attributes for fields backing automatically implemented properties（支持自动实现的属性的字段属性）（466）
			5. C# 8 and beyond（C#  8  及更高版本）（468）
				1. Nullable reference types（可空引用类型）（469）
					1. What problem do nullable reference types solve?（可空引用类型解决什么问题？）（469）
					2. Changing the meaning when using reference types（使用引用类型时更改含义）（470）
					3. Enter nullable reference types（输入可为空的引用类型）（471）
					4. Nullable reference types at compile time and execution time（编译时和执行时的可为空引用类型）（472）
					5. The damn it or bang operator（该死的  it  或  bang  运算符）（474）
					6. Experiences of nullable reference type migration（可空引用类型迁移的经验）（476）
						1. USING ATTRIBUTES TO EXPRESS NULLABLE INTENT BEFORE C# 8（C#  8之前使用属性表达可空意图）（476）
						2. ITERATION IS NATURAL（迭代是自然的）（477）
						3. BEST PRACTICES FOR USING THE BANG OPERATOR（使用  Bang  运算符的最佳实践）（477）
						4. NULL-INCONSISTENT GENERICS（空不一致的泛型）（478）
						5. THE END RESULT（最终结果）（478）
					7. Future improvements（未来的改进）（478）
						1. PROVIDING THE COMPILER WITH MORE SEMANTIC INFORMATION（为编译器提供更多语义信息）（479）
						2. DEEPER THINKING ABOUT GENERICS（关于泛型的深入思考）（480）
						3. OPT-IN PARAMETER VALIDATION（选择加入参数验证）（480）
						4. ENABLING NULLABILITY CHECKING（启用可空性检查）（481）
				2. Switch expressions（Switch  表达式）（482）
				3. Recursive pattern matching（递归模式匹配）（484）
					1. Matching properties in patterns（匹配模式中的属性）（484）
					2. Deconstruction patterns（解构模式）（485）
					3. Omitting types from patterns（从模式中省略类型）（486）
				4. Indexes and ranges（索引和范围）（487）
					1. Index and Range types and literals（索引和范围类型和文字）（487）
					2. Applying indexes and ranges（应用索引和范围）（488）
				5. More async integration（更多异步集成）（490）
					1. Asynchronous resource disposal with using await（使用await  进行异步资源处置）（490）
					2. Asynchronous iteration with foreach await（使用  foreach  wait  进行异步迭代）（491）
					3. Asynchronous iterators（异步迭代器）（494）
				6. Features not yet in preview（尚未预览的功能）（495）
					1. Default interface methods（默认接口方法）（495）
					2. Record types（记录类型）（497）
					3. Even more features in brief（更多功能简介）（498）
						1. TYPE CLASSES (AKA CONCEPTS, SHAPES, OR STRUCTURAL GENERIC CONSTRAINTS)（类型类（又名概念、形状或结构通用约束））（498）
						2. EXTENSION EVERYTHING（扩展一切）（498）
						3. TARGET-TYPED NEW（目标型新）（499）
				7. Getting involved（参与）（499）
3. Software Development（软件开发）
	1. The Mythical Man-Month（人月神话）
		1. The Tar Pit（焦油坑）（17）
			1. The Programming Systems Product（编程系统产品）（21）
			2. The Joys of the Craft（工艺的乐趣）（23）
			3. The Woes of the Craft（工艺的困境）（25）
		2. The Mythical Man-Month（神话般的人月）（27）
			1. Optimism（乐观）（31）
			2. The Man-Month（人月）（33）
			3. Systems Test（系统测试）（37）
			4. Gutless Estimating（盲目估计）（39）
			5. Regenerative Schedule Disaster（再生计划灾难）（40）
		3. The Surgical Team（手术团队）（45）
			1. The Problem（问题）（49）
			2. Mills's Proposal（米尔斯的提议）（51）
			3. How It Works（怎么运行的）（54）
		4. Aristocracy, Democracy, and System Design（贵族制、民主制与制度设计）（55）
			1. Conceptual Integrity（概念完整性）（58）
			2. Achieving Conceptual Integrity（实现概念完整性）（60）
			3. Aristocracy and Democracy（贵族制与民主制）（62）
			4. What Does the Implementer Do While Waiting?（等待期间实施者会做什么？）（65）
		5. The Second-System Effect（第二系统效应）（68）
			1. Interactive Discipline for the Architect（建筑师的互动纪律）（72）
			2. Self-Discipline—The Second-System Effect（自律——第二系统效应）（74）
		6. Passing the Word（传递话语）（77）
			1. Written Specifications—the Manual（书面规格——手册）（81）
			2. Formal Definitions（正式定义）（83）
			3. Direct Incorporation（直接合并）（86）
			4. Conferences and Courts（会议和法院）（87）
			5. Multiple Implementations（多种实施方式）（89）
			6. The Telephone Log（电话记录）（90）
			7. Product Test（产品测试）（91）
		7. Why Did the Tower of Babel Fail?（巴别塔为何失败？）（92）
			1. A Management Audit of the Babel Project（Babel  项目的管理审计）（95）
			2. Communication in the Large Programming Project（大型编程项目中的沟通）（96）
			3. The Project Workbook（项目工作手册）（97）
			4. Organization in the Large Programming Project（大型编程项目中的组织）（100）
		8. Calling the Shot（发号施令）（105）
			1. Portman's Data（波特曼的数据）（110）
			2. Aron's Data（阿伦的数据）（111）
			3. Harr's Data（哈尔的数据）（112）
			4. OS/360 Data（OS/360  数据）（114）
			5. Corbato's Data（科巴托的数据）（115）
		9. Ten Pounds in a Five-Pound Sack（五磅重的袋子里有十磅重）（116）
			1. Program Space as Cost（项目空间成本）（119）
			2. Size Control（尺寸控制）（120）
			3. Space Techniques（空间技术）（122）
			4. Representation Is the Essence of Programming（表示是编程的本质）（124）
		10. The Documentary Hypothesis（纪录片假说）（125）
			1. Documents for a Computer Product（计算机产品的文档）（129）
			2. Documents for a University Department（大学部门的文件）（131）
			3. Documents for a Software Project（软件项目的文档）（132）
			4. Why Have Formal Documents?（为什么要有正式文件？）（133）
		11. Plan to Throw One Away（计划扔掉一个）（134）
			1. Pilot Plants and Scaling Up（试点工厂和扩大规模）（137）
			2. The Only Constancy Is Change Itself（唯一不变的就是改变本身）（138）
			3. Plan the System for Change（规划系统变革）（139）
			4. Plan the Organization for Change（规划组织变革）（140）
			5. One Step Forward and One Step Back（一进一退）（143）
		12. Sharp Tools（锋利的工具）（144）
			1. Target Machines（目标机器）（148）
			2. Vehicle Machines and Data Services（车辆机器和数据服务）（151）
		13. The Whole and the Parts（整体与部分）（156）
			1. Designing the Bugs Out（设计消除错误）（160）
			2. Component Debugging（组件调试）（163）
			3. System Debugging（系统调试）（166）
		14. Hatching a Catastrophe（酝酿一场灾难）（169）
			1. Milestones or Millstones?（里程碑还是磨石？）（173）
			2. "The Other Piece Is Late, Anyway"（“无论如何，另一首曲子迟到了”）（175）
			3. Under the Rug（地毯下）（177）
		15. The Other Face（另一张脸）（181）
			1. What Documentation Is Required?（需要什么文件？）（185）
			2. The Flow-Chart Curse（流程图诅咒）（188）
			3. Self-Documenting Programs（自记录程序）（191）
		16. No Silver Bullet-Essence and Accident in Software Engineering（软件工程中没有灵丹妙药——本质和意外）（198）
			1. Abstract（抽象的）（201）
			2. Introduction（介绍）（202）
			3. Does It Have to Be Hard?—Essential Difficulties（它一定很困难吗？——本质上的困难）（203）
			4. Past Breakthroughs Solved Accidental Difficulties（过去的突破解决了意外的困难）（207）
			5. Hopes for the Silver（对银牌的希望）（209）
			6. Promising Attacks on the Conceptual Essence（对概念本质的有希望的攻击）（217）
		17. "No Silver Bullet" Refired（“没有银弹”重炮）（224）
			1. On Werewolves and Other Legendary Terrors（关于狼人和其他传说中的恐怖分子）（227）
			2. There is Too a Silver Bullet—AND HERE IT IS!（太有灵丹妙药了——它就在这里！）（228）
			3. Obscure Writing Will Be Misunderstood（晦涩的文字会被误解）（229）
			4. Harel's Analysis（哈雷尔的分析）（232）
			5. Jones's Point—Productivity Follows Quality（琼斯的观点——生产力追随质量）（237）
			6. So What Has Happened to Productivity?（那么生产力发生了什么变化？）（238）
			7. Object-Oriented Programming—Will a Brass Bullet Do?（面向对象编程——黄铜子弹可以吗？）（240）
			8. What About Reuse?（重用怎么样？）（243）
			9. Learning Large Vocabularies—A Predictable but Unpredicted Problem for Software Reuse（学习大量词汇——软件重用的一个可预测但不可预测的问题）（246）
			10. Net on Bullets—Position Unchanged（子弹网——位置不变）（248）
		18. Propositions of Mythical Man-Month: True or False?（神话人月命题：对还是错？）（249）
			1. Chapter 1. The Tar Pit（第一章  焦油坑）（253）
			2. Chapter 2. The Mythical Man-Month（第  2  章  神话般的人月）（255）
			3. Chapter 3. The Surgical Team（第  3  章  手术团队）（256）
			4. Chapter 4. Aristocracy, Democracy, and System Design（第四章贵族制、民主制和制度设计）（257）
			5. Chapter 5. The Second-System Effect（第  5  章第二系统效应）（258）
			6. Chapter 6. Passing the Word（第  6  章  传递话语）（259）
			7. Chapter 7. Why Did the Tower of Babel Fail?（第7章 巴别塔为何失败？）（260）
			8. Chapter 8. Calling the Shot（第  8  章  发号施令）（262）
			9. Chapter 9. Ten Pounds in a Five-Pound Sack（第9章五磅重的袋子里有十磅重）（263）
			10. Chapter 10. The Documentary Hypothesis（第  10  章  文献假说）（265）
			11. Chapter 11. Plan to Throw One Away（第11章  计划扔掉一个）（267）
			12. Chapter 12. Sharp Tools（第12章  利器）（270）
			13. Chapter 13. The Whole and the Parts（第13章整体与部分）（272）
			14. Chapter 14. Hatching a Catastrophe（第14章  酝酿一场灾难）（274）
			15. Chapter 15. The Other Face（第15章  另一张脸）（276）
			16. Original Epilogue（原尾声）（278）
		19. The Mythical Man-Month after 20 Years（20年后的神话人月）（279）
			1. Why Is There a Twentieth Anniversary Edition?（为什么会有二十周年纪念版？）（282）
			2. The Central Argument: Conceptual Integrity and the Architect（中心论点：概念完整性和架构师）（284）
			3. The Second-System Effect: Featuritis and Frequency-Guessing（第二系统效应：功能炎和频率猜测）（286）
			4. The Triumph of the WIMP Interface（WIMP  接口的胜利）（289）
			5. Don't Build One to Throw Away—The Waterfall Model Is Wrong!（不要建造一个就扔掉——瀑布模型是错误的！）（293）
			6. An Incremental-Build Model Is Better—Progressive Refinement（渐进式构建模型更好——渐进式细化）（296）
			7. Parnas Was Right, and I Was Wrong about Information Hiding（关于信息隐藏，帕纳斯是对的，我错了）（301）
			8. How Mythical Is the Man-Month? Boehm's Model and Data（人月有多神秘？ 伯姆的模型和数据）（303）
			9. People Are Everything (Well, Almost Everything)（人就是一切（嗯，几乎一切））（306）
			10. The Power of Giving Up Power（放弃权力的力量）（308）
			11. What's the Biggest New Surprise? Millions of Computers（最大的新惊喜是什么？ 数百万台计算机）（311）
			12. Whole New Software Industry Shrink Wrapped Software（全新软件行业收缩包装软件）（314）
			13. Buy and Build—Shrink-Wrapped Packages As Components（购买并构建——收缩包装封装作为组件）（317）
			14. The State and Future of Software Engineering（软件工程的现状和未来）（320）
		20. Fifty Years of Wonder, Excitement, and Joy（五十年的奇迹、兴奋和欢乐）（322）
	2. The Practice of Programming（程序设计实践）
		1. Style（风格）（12）
			1. Names（名称）（14）
			2. Expressions and Statements（表达式和陈述）（17）
			3. Consistency and Idioms（一致性和习语）（21）
			4. Function Macros（函数宏）（28）
			5. Magic Numbers（魔法数字）（30）
			6. Comments（评论）（34）
			7. Why Bother?（为什么要麻烦？）（38）
		2. Algorithms and Data Structures（算法和数据结构）（40）
			1. Searching（搜索）（41）
			2. Sorting（排序）（43）
			3. Libraries（库）（45）
			4. A Java Quicksort（Java快速排序）（48）
			5. O-Notation（O 表示法）（51）
			6. Growing Arrays（增长数组）（52）
			7. Lists（列表）（55）
			8. Trees（树）（61）
			9. Hash Tables（哈希表）（66）
			10. Summary（总结）（69）
		3. Design and Implementation（设计与实现）（71）
			1. The Markov Chain Algorithm（马尔可夫链算法）（72）
			2. Data Structure Alternatives（数据结构替代方案）（74）
			3. Building the Data Structure in C（用C语言构建数据结构）（75）
			4. Generating Output（生成输出）（79）
			5. Java（81）
			6. C++（86）
			7. Awk and Perl（awk和Perl）（88）
			8. Performance（性能）（90）
			9. Lessons（教训）（92）
		4. Interfaces（接口）（95）
			1. Comma-Separated Values（逗号分隔值）（96）
			2. A Prototype Library（原型库）（97）
			3. A Library for Others（为他人而设的图书馆）（101）
			4. A C++ Implementation（C  ++实现）（109）
			5. Interface Principles（接口原理）（113）
			6. Resource Management（资源管理）（116）
			7. Abort, Retry, Fail?（中止、重试、失败？）（119）
			8. User Interfaces（用户界面）（123）
		5. Debugging（调试）（126）
			1. Debuggers（调试器）（127）
			2. Good Clues, Easy Bugs（好的线索，容易的错误）（128）
			3. No Clues, Hard Bugs（没有线索，硬错误）（132）
			4. Last Resorts（最后的手段）（136）
			5. Non-reproducible Bugs（不可重现的错误）（139）
			6. Debugging Tools（调试工具）（140）
			7. Other People's Bugs（其他人的错误）（144）
			8. Summary（总结）（145）
		6. Testing（测试）（147）
			1. Test as You Write the Code（在编写代码时进行测试）（148）
			2. Systematic Testing（系统测试）（153）
			3. Test Automation（测试自动化）（157）
			4. Test Scaffolds（测试脚手架）（159）
			5. Stress Tests（压力测试）（163）
			6. Tips for Testing（测试技巧）（166）
			7. Who Does the Testing?（谁进行测试？）（167）
			8. Testing the Markov Program（测试马尔可夫程序）（168）
			9. Summary（总结）（170）
		7. Performance（表现）（172）
			1. A Bottleneck（瓶颈）（173）
			2. Timing and Profiling（计时和分析）（178）
			3. Strategies for Speed（速度策略）（182）
			4. Tuning the Code（调整代码）（185）
			5. Space Efficiency（空间效率）（189）
			6. Estimation（估计）（191）
			7. Summary（总结）（194）
		8. Portability（可移植性）（196）
			1. Language（语言）（197）
			2. Headers and Libraries（头文件和库）（203）
			3. Program Organization（程序组织）（205）
			4. Isolation（隔离）（209）
			5. Data Exchange（数据交换）（210）
			6. Byte Order（字节顺序）（211）
			7. Portability and Upgrade（移植与升级）（214）
			8. Internationalization（国际化）（216）
			9. Summary（总结）（219）
		9. Notation（符号）（221）
			1. Formatting Data（格式化数据）（222）
			2. Regular Expressions（正则表达式）（228）
			3. Programmable Tools（可编程工具）（234）
			4. Interpreters, Compilers, and Virtual Machines（解释器、编译器和虚拟机）（237）
			5. Programs that Write Programs（编写程序的程序）（243）
			6. Using Macros to Generate Code（使用宏生成代码）（246）
			7. Compiling on the Fly（即时编译）（247）
	3. Refactoring（重构）
		1. Refactoring: A First Example（重构：第一个例子）（23）
			1. The Starting Point（起点）（23）
			2. Comments on the Starting Program（对启动计划的评论）（26）
			3. The First Step in Refactoring（重构的第一步）（27）
			4. Decomposing the statement Function（分解语句函数）（28）
				1. Removing the play Variable（删除播放变量）（32）
				2. Extracting Volume Credits（提取积分）（36）
				3. Removing the format Variable（删除格式变量）（38）
				4. Removing Total Volume Credits（删除总容量积分）（40）
			5. Status: Lots of Nested Functions（状态：大量嵌套函数）（44）
			6. Splitting the Phases of Calculation and Formatting（分割计算和格式化阶段）（46）
			7. Status: Separated into Two Files (and Phases)（状态：分为两个文件（和阶段））（53）
			8. Reorganizing the Calculations by Type（按类型重新组织计算）（56）
				1. Creating a Performance Calculator（创建性能计算器）（58）
				2. Moving Functions into the Calculator（将函数移入计算器）（59）
				3. Making the Performance Calculator Polymorphic（使性能计算器具有多态性）（60）
			9. Status: Creating the Data with the Polymorphic Calculator（状态：使用多态计算器创建数据）（63）
			10. Final Thoughts（最后的想法）（65）
		2. Principles in Refactoring（重构原则）（67）
			1. Defining Refactoring（定义重构）（67）
			2. The Two Hats（两顶帽子）（68）
			3. Why Should We Refactor?（我们为什么要重构？）（69）
				1. Refactoring Improves the Design of Software（重构改进软件设计）（69）
				2. Refactoring Makes Software Easier to Understand（重构使软件更容易理解）（69）
				3. Refactoring Helps Me Find Bugs（重构帮助我发现错误）（70）
				4. Refactoring Helps Me Program Faster（重构帮助我更快地编程）（70）
			4. When Should We Refactor?（我们什么时候应该重构？）（72）
				1. Preparatory Refactoring—Making It Easier to Add a Feature（预备重构——让添加功能变得更容易）（72）
				2. Comprehension Refactoring: Making Code Easier to Understand（理解式重构：让代码更容易理解）（73）
				3. Litter-Pickup Refactoring（垃圾收集重构）（74）
				4. Planned and Opportunistic Refactoring（有计划的和机会性的重构）（74）
				5. Long-Term Refactoring（长期重构）（75）
				6. Refactoring in a Code Review（代码审查中的重构）（76）
				7. What Do I Tell My Manager?（我该告诉我的经理什么？）（76）
				8. When Should I Not Refactor?（我什么时候不应该重构？）（77）
			5. Problems with Refactoring（重构问题）（77）
				1. Slowing Down New Features（放慢新功能的速度）（78）
				2. Code Ownership（代码所有权）（79）
				3. Branches（分支机构）（80）
				4. Testing（测试）（81）
				5. Legacy Code（遗留代码）（82）
				6. Databases（数据库）（83）
			6. Refactoring, Architecture, and Yagni（重构、架构和  Yagni）（84）
			7. Refactoring and the Wider Software Development Process（重构和更广泛的软件开发过程）（85）
			8. Refactoring and Performance（重构和性能）（86）
			9. Where Did Refactoring Come From?（重构从何而来？）（89）
			10. Automated Refactorings（自动重构）（90）
			11. Going Further（更进一步）（92）
		3. Bad Smells in Code（代码中的难闻气味）（93）
			1. Mysterious Name（神秘的名字）（94）
			2. Duplicated Code（重复的代码）（94）
			3. Long Function（长函数）（95）
			4. Long Parameter List（长参数列表）（96）
			5. Global Data（全球数据）（96）
			6. Mutable Data（可变数据）（97）
			7. Divergent Change（发散性变化）（98）
			8. Shotgun Surgery（霰弹枪手术）（98）
			9. Feature Envy（功能羡慕）（99）
			10. Data Clumps（数据块）（100）
			11. Primitive Obsession（原始的痴迷）（100）
			12. Repeated Switches（重复开关）（101）
			13. Loops（循环）（101）
			14. Lazy Element（惰性元素）（102）
			15. Speculative Generality（推测的普遍性）（102）
			16. Temporary Field（临时场地）（102）
			17. Message Chains（消息链）（103）
			18. Middle Man（中间人）（103）
			19. Insider Trading（内幕交易）（104）
			20. Large Class（大类）（104）
			21. Alternative Classes with Different Interfaces（具有不同接口的替代类）（105）
			22. Data Class（数据类）（105）
			23. Refused Bequest（拒绝遗赠）（105）
			24. Comments（评论）（106）
		4. Building Tests（构建测试）（107）
			1. The Value of Self-Testing Code（自测试代码的价值）（107）
			2. Sample Code to Test（要测试的示例代码）（109）
			3. A First Test（第一次测试）（112）
			4. Add Another Test（添加另一个测试）（115）
			5. Modifying the Fixture（修改夹具）（117）
			6. Probing the Boundaries（探索边界）（118）
			7. Much More Than This（远不止于此）（121）
		5. Introducing the Catalog（目录介绍）（123）
			1. Format of the Refactorings（重构的格式）（123）
			2. The Choice of Refactorings（重构的选择）（124）
		6. A First Set of Refactorings（第一组重构）（127）
			1. Extract Function（提取功能）（128）
				3. Example: No Variables Out of Scope（示例：没有超出范围的变量）（131）
				4. Example: Using Local Variables（示例：使用局部变量）（132）
				5. Example: Reassigning a Local Variable（示例：重新分配局部变量）（134）
			2. Inline Function（内联函数）（137）
			3. Extract Variable（提取变量）（141）
				4. Example: With a Class（示例：有一个类）（143）
			4. Inline Variable（内联变量）（145）
			5. Change Function Declaration（更改函数声明）（146）
				3. Example: Renaming a Function (Simple Mechanics)（示例：重命名函数（简单机制））（149）
				4. Example: Renaming a Function (Migration Mechanics)（示例：重命名函数（迁移机制））（149）
				5. Example: Adding a Parameter（示例：添加参数）（150）
				6. Example: Changing a Parameter to One of Its Properties（示例：将参数更改为其属性之一）（151）
			6. Encapsulate Variable（封装变量）（154）
			7. Rename Variable（重命名变量）（159）
			8. Introduce Parameter Object（引入参数对象）（162）
			9. Combine Functions into Class（将函数合并到类中）（166）
			10. Combine Functions into Transform（将函数组合成变换）（171）
			11. Split Phase（分相）（176）
		7. Encapsulation（封装）（183）
			1. Encapsulate Record（封装记录）（184）
			2. Encapsulate Collection（封装集合）（192）
			3. Replace Primitive with Object（用对象替换原语）（196）
			4. Replace Temp with Query（将  Temp  替换为查询）（200）
			5. Extract Class（提取类）（204）
			6. Inline Class（内联类）（208）
			7. Hide Delegate（隐藏委托）（211）
			8. Remove Middle Man（删除中间人）（214）
			9. Substitute Algorithm（替代算法）（217）
		8. Moving Features（移动功能）（220）
			1. Move Function（移动功能）（220）
				1. Example: Moving a Nested Function to Top Level（示例：将嵌套函数移动到顶层）（222）
				2. Example: Moving between Classes（示例：在班级之间移动）（226）
			2. Move Field（移动字段）（229）
				1. Example: Moving to a Shared Object（示例：移动到共享对象）（233）
			3. Move Statements into Function（将语句移至函数中）（235）
			4. Move Statements to Callers（将语句移至调用者）（239）
			5. Replace Inline Code with Function Call（用函数调用替换内联代码）（244）
			6. Slide Statements（幻灯片陈述）（245）
				1. Example: Sliding with Conditionals（示例：带条件滑动）（248）
			7. Split Loop（分割循环）（248）
			8. Replace Loop with Pipeline（用管道替换循环）（253）
			9. Remove Dead Code（删除死代码）（259）
		9. Organizing Data（组织数据）（261）
			1. Split Variable（分割变量）（262）
				1. Example: Assigning to an Input Parameter（示例：分配给输入参数）（264）
			2. Rename Field（重命名字段）（266）
				1. Example: Renaming a Field（示例：重命名字段）（267）
			3. Replace Derived Variable with Query（用查询替换派生变量）（270）
				1. Example: More Than One Source（示例：多个来源）（272）
			4. Change Reference to Value（更改对值的引用）（274）
			5. Change Value to Reference（将值更改为参考值）（278）
		10. Simplifying Conditional Logic（简化条件逻辑）（281）
			1. Decompose Conditional（条件分解）（282）
			2. Consolidate Conditional Expression（巩固条件表达式）（285）
				1. Example: Using ands（示例：使用and）（287）
			3. Replace Nested Conditional with Guard Clauses（用保护子句替换嵌套条件）（288）
				1. Example: Reversing the Conditions（示例：反转条件）（291）
			4. Replace Conditional with Polymorphism（用多态性代替条件式）（294）
				1. Example: Using Polymorphism for Variation（示例：使用多态性进行变异）（300）
			5. Introduce Special Case（介绍特殊案例）（311）
				1. Example: Using an Object Literal（示例：使用对象文字）（317）
				2. Example: Using a Transform（示例：使用转换）（319）
			6. Introduce Assertion（引入断言）（324）
		11. Refactoring APIs（重构API）（327）
			1. Separate Query from Modifier（将查询与修饰符分开）（328）
			2. Parameterize Function（参数化函数）（332）
			3. Remove Flag Argument（删除标志参数）（336）
			4. Preserve Whole Object（保留整个对象）（341）
				1. Example: A Variation to Create the New Function（示例：创建新函数的变体）（344）
			5. Replace Parameter with Query（用查询替换参数）（346）
			6. Replace Query with Parameter（用参数替换查询）（349）
			7. Remove Setting Method（删除设置方法）（353）
			8. Replace Constructor with Factory Function（用工厂函数替换构造函数）（356）
			9. Replace Function with Command（用命令替换函数）（359）
			10. Replace Command with Function（用函数替换命令）（366）
		12. Dealing with Inheritance（处理继承）（371）
			1. Pull Up Method（上拉法）（372）
			2. Pull Up Field（拉起场）（375）
			3. Pull Up Constructor Body（拉起构造函数主体）（377）
			4. Push Down Method（下推法）（381）
			5. Push Down Field（下推场）（383）
			6. Replace Type Code with Subclasses（用子类替换类型代码）（384）
				1. Example: Using Indirect Inheritance（示例：使用间接继承）（388）
			7. Remove Subclass（删除子类）（391）
			8. Extract Superclass（提取超类）（397）
			9. Collapse Hierarchy（折叠层次结构）（402）
			10. Replace Subclass with Delegate（用委托替换子类）（403）
				1. Example: Replacing a Hierarchy（示例：替换层次结构）（411）
			11. Replace Superclass with Delegate（用委托替换超类）（421）
	4. Head First Design Patterns（Head First设计模式）
		1. intro to Design Patterns Welcome to Design Patterns（设计模式简介 欢迎来到设计模式）（39）
			1. It started with a simple SimUDuck app（它从一个简单的 SimUDuck 应用程序开始）（40）
			2. But now we need the ducks to FLY（但现在我们需要鸭子飞翔）（41）
			3. But something went horribly wrong...（但发生了可怕的错误......）（42）
			4. Joe thinks about inheritance（乔考虑继承问题）（43）
			5. How about an interface?（接口怎么样？）（44）
			6. What would you do if you were Joe?（如果你是乔你会怎么做？）（45）
			7. The one constant in software development（软件开发中的一个常数）（46）
			8. Zeroing in on the problem（聚焦问题）（47）
			9. Separating what changes from what stays the same（将变化的内容与保持不变的内容分开）（48）
			10. Designing the Duck Behaviors（设计鸭子的行为）（49）
			11. Implementing the Duck Behaviors（实施鸭子行为）（51）
			12. Integrating the Duck Behaviors（整合鸭子行为）（53）
			13. More integration...（更多整合...）（54）
			14. Testing the Duck code（测试鸭子代码）（56）
			15. Setting behavior dynamically（动态设置行为）（58）
			16. The Big Picture on encapsulated behaviors（封装行为的大局观）（60）
			17. HAS-A can be better than IS-A（HAS-A 可能比 IS-A 更好）（61）
			18. Speaking of Design Patterns...（说到设计模式...）（62）
			19. Overheard at the local diner...（在当地的小餐馆里无意中听到的……）（64）
			20. Overheard in the next cubicle...（隔壁小隔间里无意中听到的……）（65）
			21. The power of a shared pattern vocabulary（共享模式词汇的力量）（66）
			22. How do I use Design Patterns?（如何使用设计模式？）（67）
			23. Skeptical Developer（持怀疑态度的开发者）（68）
			24. Friendly Patterns Guru（友好模式大师）（68）
			25. Tools for your Design Toolbox（设计工具箱中的工具）（70）
		2. the Observer Pattern Keeping your Objects in the Know（观察者模式让你的对象了解情况）（75）
			1. The Weather Monitoring application overview（天气监测应用概述）（77）
			2. Unpacking the WeatherData class（解压 WeatherData 类）（78）
			3. Our Goal（我们的目标）（79）
			4. Taking a first, misguided implementation of the Weather Station（第一次错误地实施气象站）（80）
			5. What’s wrong with our implementation anyway?（我们的实施到底出了什么问题？）（81）
			6. Meet the Observer Pattern（认识观察者模式）（82）
			7. Publishers + Subscribers = Observer Pattern（发布者 + 订阅者 = 观察者模式）（83）
			8. A day in the life of the Observer Pattern（观察者模式生活中的一天）（84）
			9. Five-minute drama: a subject for observation（五分钟戏剧：观察的主题）（86）
			10. Two weeks later...（两个星期后...）（88）
			11. The Observer Pattern defined（观察者模式的定义）（89）
			12. The Observer Pattern: the Class Diagram（观察者模式：类图）（90）
			13. The Power of Loose Coupling（松耦合的力量）（92）
			14. Cubicle conversation（隔间谈话）（94）
			15. Designing the Weather Station（设计气象站）（95）
			16. Implementing the Weather Station（实施气象站）（96）
			17. Implementing the Subject interface in WeatherData（在WeatherData中实现Subject接口）（97）
			18. Now, let’s build those display elements（现在，让我们构建这些显示元素）（98）
			19. Power up the Weather Station（启动气象站）（99）
			20. Looking for the Observer Pattern in the Wild（在野外寻找观察者模式）（103）
			21. Coding the life-changing application（编写改变生活的应用程序）（104）
			22. Meanwhile, back at Weather-O-Rama（与此同时，回到Weather-O-Rama）（107）
			23. Test Drive the new code（测试新代码）（109）
			24. Tools for your Design Toolbox（设计工具箱中的工具）（110）
		3. the Decorator Pattern Decorating Objects（装饰者模式装饰对象）（117）
			1. Welcome to Starbuzz Coffee（欢迎来到星巴兹咖啡）（118）
			2. The Open-Closed Principle（开闭原则）（124）
			3. Meet the Decorator Pattern（认识装饰者模式）（126）
			4. Constructing a drink order with Decorators（使用装饰器构建饮料订单）（127）
			5. The Decorator Pattern defined（装饰模式的定义）（129）
			6. Decorating our Beverages（装饰我们的饮料）（129）
			7. Cubicle Conversation（隔间对话）（130）
			8. New barista training（新咖啡师培训）（132）
			9. Writing the Starbuzz code（编写 Starbuzz 代码）（133）
			10. Coding beverages（饮料编码）（134）
			11. Coding condiments（调味品编码）（135）
			12. Serving some coffees（供应一些咖啡）（136）
			13. Real-World Decorators: Java I/O（现实世界的装饰器：Java I/O）（138）
			14. Decorating the java.io classes（装饰 java.io 类）（138）
			15. Writing your own Java I/O Decorator（编写您自己的 Java I/O 装饰器）（140）
			16. Test out your new Java I/O Decorator（测试您的新 Java I/O 装饰器）（141）
			17. Tools for your Design Toolbox（设计工具箱中的工具）（143）
		4. the Factory Pattern Baking with OO Goodness（工厂模式烘焙与 OO 的优点）（147）
			1. Identifying the aspects that vary（识别不同的方面）（150）
			2. But the pressure is on to add more pizza types（151）
			3. Encapsulating object creation（封装对象创建）（152）
			4. Building a simple pizza factory（建造一个简单的披萨工厂）（153）
			5. Reworking the PizzaStore class（重新设计 PizzaStore 类）（154）
			6. The Simple Factory defined（简单工厂定义）（155）
			7. Franchising the pizza store（披萨店特许经营）（156）
			8. We’ve seen one approach...（我们已经看到了一种方法......）（157）
			9. But you’d like a little more quality control...（但您想要更多的质量控制......）（157）
			10. A framework for the pizza store（披萨店的框架）（158）
			11. Allowing the subclasses to decide（允许子类决定）（159）
			12. Let’s make a Pizza Store（让我们开一家披萨店）（161）
			13. Declaring a factory method（声明工厂方法）（163）
			14. Let’s see how it works: ordering pizzas with the pizza factory method（让我们看看它是如何工作的：使用披萨工厂方法订购披萨）（164）
			15. So how do they order?（那么他们如何订购呢？）（164）
			16. Let’s check out how these pizzas are really made to order...（让我们看看这些披萨是如何真正按订单制作的......）（164）
			17. We’re just missing one thing: Pizzas!（我们只是缺少一件事：披萨！）（166）
			18. You’ve waited long enough. Time for some pizzas!（你已经等得够久了。 是时候吃一些披萨了！）（167）
			19. It’s finally time to meet the Factory Method Pattern（终于到了工厂方法模式的时候了）（169）
			20. View Creators and Products in Parallel（并行查看创作者和产品）（170）
			21. Factory Method Pattern defined（工厂方法模式定义）（172）
			22. Looking at object dependencies（查看对象依赖关系）（176）
			23. The Dependency Inversion Principle（依赖倒置原则）（177）
			24. Applying the Principle（应用原则）（178）
			25. Inverting your thinking...（颠覆你的思维...）（180）
			26. A few guidelines to help you follow the Principle...（一些指导方针可以帮助您遵循该原则...）（181）
			27. Meanwhile, back at the Pizza Store...（与此同时，回到披萨店……）（182）
			28. Ensuring consistency in your ingredients（确保成分的一致性）（182）
			29. Families of ingredients...（成分家族...）（183）
			30. Building the ingredient factories（建设原料工厂）（184）
			31. Building the New York ingredient factory（建造纽约配料工厂）（185）
			32. Reworking the pizzas...（重新加工披萨...）（187）
			33. Revisiting our pizza stores（重访我们的披萨店）（189）
			34. What have we done?（我们做了什么？）（191）
			35. More pizza for Ethan and Joel...（给伊森和乔尔更多的披萨......）（192）
			36. Abstract Factory Pattern defined（抽象工厂模式定义）（194）
			37. Factory Method and Abstract Factory compared（工厂方法和抽象工厂的比较）（198）
			38. Tools for your Design Toolbox（设计工具箱中的工具）（200）
		5. the Singleton Pattern One-of-a-Kind Objects（单例模式独一无二的对象）（207）
			1. The Little Singleton（小单身汉）（209）
			2. Dissecting the classic Singleton Pattern implementation（剖析经典的单例模式实现）（211）
			3. The Chocolate Factory（巧克力工厂）（213）
			4. Singleton Pattern defined（单例模式定义）（215）
			5. Hershey, PA, we have a problem...（宾夕法尼亚州赫尔希，我们有一个问题......）（216）
			6. Dealing with multithreading（处理多线程）（218）
			7. Can we improve multithreading?（我们可以改进多线程吗？）（219）
			8. Meanwhile, back at the Chocolate Factory...（与此同时，回到巧克力工厂……）（221）
			9. Congratulations!（恭喜！）（222）（设计工具箱中的工具）（224）
			10. Tools for your Design Toolbox（设计工具箱中的工具）（224）
		6. the Command Pattern Encapsulating Invocation（命令模式封装调用）（229）
			1. Free hardware! Let’s check out the Remote Control...（免费硬件！ 我们来看看远程控制...）（231）
			2. Taking a look at the vendor classes（查看供应商类别）（232）
			3. Cubicle Conversation（隔间对话）（233）
			4. Meanwhile, back at the Diner..., or, A brief introduction to the Command Pattern（与此同时，回到餐厅......，或者，命令模式的简要介绍）（235）
			5. Let’s study the interaction in a little more detail...（让我们更详细地研究一下交互作用......）（235）
			6. The Objectville Diner roles and responsibilities（Objectville Diner 的角色和职责）（237）
			7. From the Diner to the Command Pattern（从餐厅到指挥模式）（239）
			8. Our first command object（我们的第一个命令对象）（241）
			9. Using the command object（使用命令对象）（242）
			10. Creating a simple test to use the Remote Control（创建一个简单的测试来使用远程控制）（242）
			11. The Command Pattern defined（命令模式定义）（244）
			12. Assigning Commands to slots（将命令分配给插槽）（247）
			13. Implementing the Remote Control（实施远程控制）（248）
			14. Implementing the Commands（执行命令）（249）
			15. Putting the Remote Control through its paces（检验遥控器的性能）（250）
			16. Time to write that documentation...（是时候编写该文档了...）（253）
			17. The updated code, using lambda expressions:（更新后的代码，使用 lambda 表达式：）（254）
			18. What are we doing?（我们在做什么？）（255）
			19. Time to QA that Undo button!（是时候对撤消按钮进行质量检查了！）（258）
			20. Using state to implement Undo（使用状态来实现Undo）（259）
			21. Adding Undo to the Ceiling Fan commands（将撤消添加到吊扇命令）（260）
			22. Get ready to test the ceiling fan（准备好测试吊扇）（261）
			23. Testing the ceiling fan...（测试吊扇...）（262）
			24. Every remote needs a Party Mode!（每个遥控器都需要派对模式！）（263）
			25. Using a macro command（使用宏命令）（264）
			26. More uses of the Command Pattern: queuing requests（命令模式的更多用途：排队请求）（267）
			27. More uses of the Command Pattern: logging requests（命令模式的更多用途：记录请求）（672）
			28. Command Pattern in the Real World（现实世界中的命令模式）（269）
			29. Tools for your Design Toolbox（设计工具箱中的工具）（271）
		7. the Adapter and Facade Patterns Being Adaptive（适配器和外观模式是自适应的）（275）
			1. Adapters all around us（我们身边的适配器）（275）
			2. Object-oriented adapters（面向对象的适配器）（277）
			3. If it walks like a duck and quacks like a duck, then it might be a turkey wrapped with a duck adapter...（如果它像鸭子一样行走并且像鸭子一样嘎嘎叫，那么它可能是一只用鸭子适配器包裹的火鸡......）（278）
			4. Test drive the adapter（测试驱动适配器）（280）
			5. The Adapter Pattern explained（适配器模式解释）（281）
			6. Adapter Pattern defined（适配器模式定义）（283）
			7. Object and class adapters（对象和类适配器）（284）
			8. Real-world adapters（现实世界的适配器）（288）
			9. Adapting an Enumeration to an Iterator（使枚举适应迭代器）（289）
			10. Designing the Adapter（设计适配器）（289）
			11. Dealing with the remove() method（处理remove()方法）（290）
			12. Writing the EnumerationIterator adapter（编写枚举迭代器适配器）（290）
			13. And now for something different...（现在换一些不同的东西......）（294）
			14. Home Sweet Home Theater（甜蜜之家家庭影院）（295）
			15. Watching a movie (the hard way)（看电影（艰难的方式））（296）
			16. Lights, Camera, Facade!（灯光、相机、立面！）（297）
			17. Constructing your home theater facade（建造您的家庭影院立面）（301）
			18. Implementing the simplified interface（实现简化的接口）（302）
			19. Time to watch a movie (the easy way)（是时候看电影了（最简单的方法））（303）
			20. Facade Pattern defined（外观模式定义）（304）
			21. The Principle of Least Knowledge（最少知识原则）（304）
			22. How NOT to Win Friends and Influence Objects（如何不赢得朋友和影响对象）（306）
			23. Keeping your method calls in bounds...（让你的方法调用保持在界限之内......）（307）
			24. The Facade Pattern and the Principle of Least Knowledge（外观模式和最少知识原则）（309）
			25. Tools for your Design Toolbox（设计工具箱中的工具）（310）
		8. the Template Method Pattern Encapsulating Algorithms（模板方法模式封装算法）（315）
			1. It’s time for some more caffeine（是时候补充一些咖啡因了）（316）
			2. Whipping up some coffee and tea classes (in Java)（开设一些咖啡和茶课程（Java））（317）
			3. And now the Tea...（现在茶...）（318）
			4. Let’s abstract that Coffee and Tea（让我们抽象一下咖啡和茶）（320）
			5. Taking the design further...（进一步深化设计...）（321）
			6. Abstracting prepareRecipe()（抽象prepareRecipe()）（322）
			7. What have we done?（我们做了什么？）（325）
			8. Meet the Template Method（认识模板方法）（326）
			9. Let’s make some tea...（我们来泡杯茶吧……）（327）
			10. What did the Template Method get us?（模板方法给我们带来了什么？）（328）
			11. Template Method Pattern defined（模板方法模式定义）（329）
			12. Hooked on Template Method...（迷上了模板方法......）（332）
			13. Using the hook（使用钩子）（333）
			14. Let’s run the Test Drive（让我们运行试驾）（334）
			15. The Hollywood Principle（好莱坞原则）（336）
			16. The Hollywood Principle and Template Method（好莱坞原则和模板方法）（337）
			17. Template Methods in the Wild（野外模板方法）（339）
			18. Sorting with Template Method（使用模板方法排序）（340）
			19. We’ve got some ducks to sort...（我们有一些鸭子要分类...）（341）
			20. What is compareTo()?（什么是compareTo()？）（341）
			21. Comparing Ducks and Ducks（鸭子和鸭子的比较）（342）
			22. Let’s sort some Ducks（让我们对一些鸭子进行排序）（343）
			23. The making of the sorting duck machine（分拣鸭机的制作）（344）
			24. Swingin’ with Frames（与框架一起摇摆）（346）
			25. Custom Lists with AbstractList（带有 AbstractList 的自定义列表）（347）
			26. Tools for your Design Toolbox（设计工具箱中的工具）（351）
		9. the Iterator and Composite Patterns Well-Managed Collections（迭代器和复合模式管理良好的集合）（355）
			1. Breaking News: Objectville Diner and Objectville Pancake House Merge（突发新闻：Objectville Diner 和 Objectville Pancake House 合并）（356）
			2. Check out the Menu Items（查看菜单项）（357）
			3. Lou and Mel’s Menu implementations（Lou 和 Mel 的菜单实现）（358）
			4. What’s the problem with having two different menu representations?（有两种不同的菜单表示有什么问题？）（360）
			5. Implementing the spec: our first attempt（实施规范：我们的第一次尝试）（361）
			6. What now?（现在怎么办？）（362）
			7. Can we encapsulate the iteration?（我们可以封装迭代吗？）（363）
			8. Meet the Iterator Pattern（认识迭代器模式）（365）
			9. Adding an Iterator to DinerMenu（将迭代器添加到 DinerMenu）（366）
			10. Reworking the DinerMenu with Iterator（使用 Iterator 重新设计 DinerMenu）（367）
			11. Fixing up the Waitress code（修复 Waitress 代码）（368）
			12. Testing our code（测试我们的代码）（369）
			13. Here’s the test run...（这是测试运行...）（369）
			14. What have we done so far?（到目前为止我们做了什么？）（370）
			15. Reviewing our current design...（回顾我们当前的设计...）（371）
			16. Making some improvements...（进行一些改进...）（372）
			17. Cleaning things up with java.util.Iterator（使用 java.util.Iterator 进行清理）（373）
			18. We are almost there...（我们就快到了...）（374）
			19. What does this get us?（这给我们带来什么？）（375）
			20. Iterator Pattern defined（迭代器模式定义）（376）
			21. The Iterator Pattern Structure（迭代器模式结构）（377）
			22. The Single Responsibility Principle（单一责任原则）（378）
			23. Meet Java’s Iterable interface（认识 Java 的 Iterable 接口）（381）
			24. Java’s enhanced for loop（Java 的增强 for 循环）（382）
			25. Not so fast; Arrays are not Iterables（没那么快； 数组不是可迭代的）（383）
			26. Taking a look at the Café Menu（看看咖啡馆的菜单）（385）
			27. Reworking the Café Menu code（重新设计咖啡馆菜单代码）（386）
			28. Adding the Cafe Menu to the Waitress（将咖啡馆菜单添加到女服务员）（387）
			29. Breakfast, lunch, AND dinner（早餐午餐和晚餐）（388）
			30. What did we do?（我们做了什么？）（389）
			31. Code Magnets（代码磁铁）（392）
			32. Is the Waitress ready for prime time?（女服务员准备好迎接黄金时段了吗？）（393）
			33. Just when we thought it was safe...（就在我们以为安全了的时候……）（395）
			34. What do we need?（我们需要什么？）（396）
			35. The Composite Pattern defined（复合模式定义）（398）
			36. Designing Menus with Composite（使用 Composite 设计菜单）（401）
			37. Implementing MenuComponent（实现菜单组件）（402）
			38. Implementing the MenuItem（实现菜单项）（403）
			39. Implementing the Composite Menu（实现复合菜单）（404）
			40. Fixing the print() method（修复 print() 方法）（405）
			41. Getting ready for a test drive...（准备试驾...）（406）
			42. Now for the test drive...（现在进行试驾...）（407）
			43. Getting ready for a test drive...（准备试驾...）（408）
			44. Tools for your Design Toolbox（设计工具箱中的工具）（414）
		10. the State Pattern The State of Things（状态模式 事物的状态）（419）
			1. Java Breakers（Java 破坏者）（420）
			2. Cubicle Conversation（隔间对话）（421）
			3. State machines 101（状态机101）（422）
			4. Writing the code（编写代码）（424）
			5. In-house testing（内部测试）（426）
			6. You knew it was coming...a change request!（您知道它即将到来...变更请求！）（428）
			7. The messy STATE of things...（事情的混乱状态......）（430）
			8. The new design（新设计）（432）
			9. Defining the State interfaces and classes（定义 State 接口和类）（433）
			10. Implementing our State classes（实施我们的状态类）（435）
			11. Reworking the Gumball Machine（改造口香糖机）（436）
			12. Now, let’s look at the complete GumballMachine class...（现在，让我们看看完整的 GumballMachine 类......）（437）
			13. Implementing more states（实施更多状态）（438）
			14. Let’s take a look at what we’ve done so far...（让我们看看到目前为止我们做了什么......）（441）
			15. The State Pattern defined（状态模式定义）（444）
			16. We still need to finish the Gumball 1 in 10 game（我们还需要在十场比赛中完成冈布奥一役）（447）
			17. Finishing the game（完成游戏）（448）
			18. Demo for the CEO of Mighty Gumball, Inc.（为 Mighty Gumball, Inc. 的首席执行官进行演示）（449）
			19. Sanity check...（完整性检查...）（451）
			20. We almost forgot!（我们差点忘了！）（454）
			21. Tools for your Design Toolbox（设计工具箱中的工具）（457）
		11. the Proxy Pattern Controlling Object Access（控制对象访问的代理模式）（463）
			1. Coding the Monitor（监视器编码）（465）
			2. Testing the Monitor（测试显示器）（564）
			3. The role of the ‘remote proxy’（“远程代理”的作用）（468）
			4. Adding a remote proxy to the Gumball Machine monitoring code（添加远程代理到Gumball Machine监控代码）（470）
			5. Remote methods 101（远程方法 101）（471）
			6. Walking through the design（浏览设计）（471）
			7. How the method call happens（方法调用是如何发生的）（472）
			8. Java RMI, the Big Picture（Java RMI，大局观）（474）
			9. Making the Remote service（制作远程服务）（475）
			10. Step one: make a Remote interface（第一步：制作远程接口）（476）
			11. Step two: make a Remote implementation（第二步：进行远程实施）（477）
			12. Step three: run rmiregistry（第三步：运行rmiregistry）（478）
			13. Step four: start the service（第四步：启动服务）（478）
			14. Complete code for the server side（服务器端完整代码）（479）
			15. Complete code for the client side（客户端完整代码）（482）
			16. Back to our GumballMachine remote proxy（回到我们的 GumballMachine 远程代理）（483）
			17. Getting the GumballMachine ready to be a remote service（让 GumballMachine 准备好成为远程服务）（484）
			18. Registering with the RMI registry...（正在向 RMI 注册表注册...）（485）
			19. Now for the GumballMonitor client...（现在对于 GumballMonitor 客户端...）（487）
			20. Writing the Monitor test drive（编写监视器测试驱动）（488）
			21. Another demo for the CEO of Mighty Gumball...（Mighty Gumball 首席执行官的另一个演示......）（489）
			22. The Proxy Pattern defined（代理模式定义）（493）
			23. Get ready for the Virtual Proxy（为虚拟代理做好准备）（495）
			24. Displaying Album covers（显示专辑封面）（496）
			25. Designing the Album Cover Virtual Proxy（设计专辑封面虚拟代理）（497）
			26. Writing the Image Proxy（编写图像代理）（498）
			27. Testing the Album Cover Viewer（测试专辑封面查看器）（502）
			28. What did we do?（我们做了什么？）（503）
			29. Using the Java API’s Proxy to create a protection proxy（使用Java API的Proxy创建保护代理）（507）
			30. Geeky Matchmaking in Objectville（Objectville 的极客对接会）（508）
			31. The Person implementation（人员实施）（509）
			32. Five-minute drama: protecting subjects（五分钟戏剧：保护主体）（511）
			33. Big Picture: creating a Dynamic Proxy for the Person（大局：为人员创建动态代理）（512）
			34. Step one: creating Invocation Handlers（第一步：创建调用处理程序）（513）
			35. Step two: creating the Proxy class and instantiating the Proxy object（第二步：创建Proxy类并实例化Proxy对象）（515）
			36. Testing the matchmaking service（测试匹配服务）（517）
			37. Running the code...（运行代码...）（518）
			38. The Proxy Zoo（代理动物园）（520）
			39. Tools for your Design Toolbox（设计工具箱中的工具）（523）
			40. The code for the Album Cover Viewer（专辑封面查看器的代码）（527）
		12. compound patterns Patterns of Patterns（复合模式 模式的模式）（531）
			1. Working together（一起工作）（532）
			2. Duck reunion（鸭子团圆）（533）
			3. Safety versus transparency（安全与透明度）（547）
			4. What did we do?（我们做了什么？）（555）
			5. A duck’s-eye view: the class diagram（鸭眼视图：类图）（556）
			6. The King of Compound Patterns（复合模式之王）（558）
			7. Meet Model-View-Controller（认识模型-视图-控制器）（561）
			8. A closer look...（仔细一看...）（562）
			9. Understanding MVC as a set of Patterns（将 MVC 理解为一组模式）（564）
			10. Using MVC to control the beat...（使用MVC来控制节拍...）（566）
			11. Putting the pieces together（将各个部分组合在一起）（568）
			12. Building the pieces（构建碎片）（569）
			13. Now let’s have a look at the concrete BeatModel class（现在让我们看一下具体的 BeatModel 类）（570）
			14. The View（风景）（571）
			15. Implementing the View（实现视图）（572）
			16. Now for the Controller（现在是控制器）（574）
			17. And here’s the implementation of the controller:（这是控制器的实现：）（575）
			18. Putting it all together...（把它们放在一起......）（576）
			19. Exploring Strategy（探索策略）（577）
			20. Adapting the Model（调整模型）（578）
			21. And now for a test run...（现在进行测试运行...）（580）
			22. Tools for your Design Toolbox（设计工具箱中的工具）（583）
		13. better living with patterns Patterns in the Real World（现实世界中的模式）（601）
			1. Design Pattern defined（设计模式定义）（603）
			2. Looking more closely at the Design Pattern definition（更仔细地查看设计模式定义）（605）
			3. May the force be with you（愿原力与你同在）（606）
			4. So you wanna be a Design Patterns writer（所以你想成为一名设计模式作家）（611）
			5. Organizing Design Patterns（组织设计模式）（613）
			6. Thinking in Patterns（模式思考）（618）
			7. Your Mind on Patterns（你对模式的看法）（621）
			8. Don’t forget the power of the shared vocabulary（不要忘记共享词汇的力量）（522）
			9. Cruisin’ Objectville with the Gang of Four（与四人帮一起巡游奥博维尔）（625）
			10. Your journey has just begun...（你的旅程才刚刚开始……）（626）
			11. The Patterns Zoo（图案动物园）（628）
			12. Annihilating evil with Anti-Patterns（用反模式消灭邪恶）（630）
			13. Tools for your Design Toolbox（设计工具箱中的工具）（632）
			14. Leaving Objectville...（离开奥布塞维尔...）（633）
		14. Appendix Leftover Patterns（附录 剩余模式）（635）
			1. Bridge（桥接模式）（636）
			2. Builder（建造者模式）（638）
			3. Chain of Responsibility（责任链模式）（640）
			4. Flyweight（享元模式）（642）
			5. Interpreter（解释器模式）（644）
			6. Mediator（中介者模式）（646）
			7. Memento（备忘录模式）（648）
			8. Prototype（原型模式）（650）
			9. Visitor（访问者模式）（652）
	5. Code Complete（代码大全）
		1. Laying the Foundation（奠定基础）（46）
			1. Welcome to Software Construction（欢迎来到软件构建）（47）
				1. What Is Software Construction?（什么是软件构建？）（48）
				2. Why Is Software Construction Important?（为什么软件建设很重要？）（52）
				3. How to Read This Book（如何阅读本书）（54）
			2. Metaphors for a Richer Understanding of Software Development（更丰富地理解软件开发的隐喻）（56）
				1. The Importance of Metaphors（隐喻的重要性）（57）
				2. How to Use Software Metaphors（如何使用软件隐喻）（60）
				3. Common Software Metaphors（常见软件隐喻）（62）
					1. Software Penmanship: Writing Code（软件书法：编写代码）（63）
					2. Software Farming: Growing a System（软件耕种：种植系统）（65）
					3. Software Oyster Farming: System Accretion（软件牡蛎养殖：系统增殖）（66）
					4. Software Construction: Building Software（软件构建：构建软件）（69）
					5. Applying Software Techniques: The Intellectual Toolbox（应用软件技术：智能工具箱）（74）
					6. Combining Metaphors（结合隐喻）（75）
			3. Measure Twice, Cut Once: Upstream Prerequisites（测量两次，切割一次：上游先决条件）（78）
				1. Importance of Prerequisites（先决条件的重要性）（80）
					1. Do Prerequisites Apply to Modern Software Projects?（先决条件适用于现代软件项目吗？）（82）
					2. Causes of Incomplete Preparation（准备不充分的原因）（83）
					3. Utterly Compelling and Foolproof Argument for Doing Prerequisites Before Construction（在施工前做好先决条件的完全令人信服且万无一失的论点）（86）
				2. Determine the Kind of Software You're Working On（确定您正在开发的软件类型）（91）
					1. Iterative Approaches' Effect on Prerequisites（迭代方法对先决条件的影响）（94）
					2. Choosing Between Iterative and Sequential Approaches（在迭代方法和顺序方法之间进行选择）（97）
				3. Problem-Definition Prerequisite（问题定义先决条件）（100）
				4. Requirements Prerequisite（要求先决条件）（103）
					1. Why Have Official Requirements?（为什么有官方要求？）（104）
					2. The Myth of Stable Requirements（稳定需求的神话）（106）
					3. Handling Requirements Changes During Construction（处理施工期间的需求变化）（108）
				5. Architecture Prerequisite（架构先决条件）（112）
					1. Typical Architectural Components（典型的架构组件）（114）
				6. Amount of Time to Spend on Upstream Prerequisites（花在上游先决条件上的时间量）（129）
			4. Key Construction Decisions（关键建设决策）（138）
				1. Choice of Programming Language（编程语言的选择）（139）
					1. Language Descriptions（语言描述）（142）
				2. Programming Conventions（编程约定）（146）
				3. Your Location on the Technology Wave（您在科技浪潮中的位置）（148）
					1. Example of Programming into a Language（语言编程示例）（150）
				4. Selection of Major Construction Practices（主要施工实践的选择）（152）
		2. Creating High-Quality Code（创建高质量代码）（155）
			1. Design in Construction（施工中的设计）（156）
				1. Design Challenges（设计挑战）（158）
					1. Design Is a Wicked Problem（设计是一个棘手的问题）（159）
					2. Design Is a Sloppy Process (Even If it Produces a Tidy Result)（设计是一个马虎的过程（即使它产生了整洁的结果））（161）
					3. Design Is About Tradeoffs and Priorities（设计是关于权衡和优先级的）（162）
					4. Design Involves Restrictions（设计涉及限制）（163）
					5. Design Is Nondeterministic（设计是不确定的）（164）
					6. Design Is a Heuristic Process（设计是一个启发式的过程）（165）
					7. Design Is Emergent（设计是自然而然的）（166）
				2. Key Design Concepts（关键设计概念）（167）
					1. Software's Primary Technical Imperative: Managing Complexity（软件的主要技术要求：管理复杂性）（168）
					2. Desirable Characteristics of a Design（设计的理想特征）（173）
					3. Levels of Design（设计水平）（176）
				3. Design Building Blocks: Heuristics（设计构建模块：启发式）（184）
					1. Find Real-World Objects（寻找现实世界的物体）（184）
					2. Form Consistent Abstractions（形成一致的抽象）（188）
					3. Encapsulate Implementation Details（封装实现细节）（190）
					4. Inherit—When Inheritance Simplifies the Design（继承——当继承简化设计时）（191）
					5. Hide Secrets (Information Hiding)（隐藏秘密（信息隐藏））（193）
					6. Identify Areas Likely to Change（确定可能发生变化的领域）（202）
					7. Keep Coupling Loose（保持联轴器松动）（206）
					8. Look for Common Design Patterns（寻找常见的设计模式）（210）
					9. Other Heuristics（其他启发法）（214）
					10. Summary of Design Heuristics（设计启发法总结）（219）
					11. Guidelines for Using Heuristics（使用启发法的指南）（220）
				4. Design Practices（设计实践）（222）
					1. Iterate（迭代）（223）
					2. Divide and Conquer（分而治之）（225）
					3. Top-Down and Bottom-Up Design Approaches（自上而下和自下而上的设计方法）（226）
					4. Experimental Prototyping（实验原型制作）（230）
					5. Collaborative Design（协同设计）（232）
					6. How Much Design Is Enough?（多少设计就足够了？）（233）
					7. Capturing Your Design Work（捕捉您的设计作品）（236）
				5. Comments on Popular Methodologies（对流行方法论的评论）（239）
			2. Working Classes（工人阶级）（250）
				1. Class Foundations: Abstract Data Types (ADTs)（类基础：抽象数据类型  (ADT)）（252）
					1. Example of the Need for an ADT（需要  ADT  的示例）（253）
					2. Benefits of Using ADTs（使用  ADT  的好处）（255）
					3. More Examples of ADTs（更多  ADT  示例）（258）
					4. Handling Multiple Instances of Data with ADTs in Non-Object-Oriented Environments（在非面向对象环境中使用 ADT 处理多个数据实例）（262）
					5. ADTs and Classes（ADT  和类）（264）
				2. Good Class Interfaces（良好的类接口）（265）
					1. Good Abstraction（良好的抽象）（266）
					2. Good Encapsulation（良好的封装性）（274）
				3. Design and Implementation Issues（设计和实施问题）（280）
					1. Containment ("has a" Relationships)（遏制（“有”关系））（281）
					2. Inheritance ("is a" Relationships)（继承（“是”关系））（282）
					3. Member Functions and Data（会员功能及数据）（290）
					4. Constructors（构造函数）（292）
				4. Reasons to Create a Class（创建班级的原因）（294）
					1. Classes to Avoid（要避免的课程）（299）
					2. Summary of Reasons to Create a Class（创建班级的原因总结）（300）
				5. Language-Specific Issues（特定于语言的问题）（301）
				6. Beyond Classes: Packages（超越类：包）（302）
			3. High-Quality Routines（高质量例程）（311）
				1. Valid Reasons to Create a Routine（创建例程的正当理由）（315）
					1. Operations That Seem Too Simple to Put Into Routines（看起来太简单而无法放入例程中的操作）（318）
					2. Summary of Reasons to Create a Routine（创建例程的原因摘要）（320）
				2. Design at the Routine Level（日常设计）（321）
				3. Good Routine Names（好的例程名称）（326）
				4. How Long Can a Routine Be?（例行公事可以持续多长时间？）（330）
				5. How to Use Routine Parameters（如何使用常规参数）（332）
				6. Special Considerations in the Use of Functions（使用函数时的特殊注意事项）（340）
					1. When to Use a Function and When to Use a Procedure（何时使用函数以及何时使用过程）（341）
					2. Setting the Function's Return Value（设置函数的返回值）（342）
				7. Macro Routines and Inline Routines（宏例程和内联例程）（344）
					1. Limitations on the Use of Macro Routines（宏例程的使用限制）（347）
					2. Inline Routines（内联例程）（348）
			4. Defensive Programming（防御性编程）（351）
				1. Protecting Your Program from Invalid Inputs（保护您的程序免受无效输入的影响）（353）
				2. Assertions（断言）（355）
					1. Building Your Own Assertion Mechanism（构建您自己的断言机制）（357）
					2. Guidelines for Using Assertions（使用断言的指南）（258）
				3. Error-Handling Techniques（错误处理技术）（362）
					1. Robustness vs. Correctness（稳健性与正确性）（366）
					2. High-Level Design Implications of Error Processing（错误处理的高级设计含义）（367）
				4. Exceptions（例外情况）（368）
				5. Barricade Your Program to Contain the Damage Caused by Errors（阻止您的程序以遏制错误造成的损害）（376）
					1. Relationship Between Barricades and Assertions（路障和断言之间的关系）（378）
				6. Debugging Aids（调试辅助工具）（379）
					1. Don't Automatically Apply Production Constraints to the Development Version（不要自动将生产约束应用于开发版本）（380）
					2. Introduce Debugging Aids Early（尽早引入调试辅助工具）（381）
					3. Use Offensive Programming（使用攻击性编程）（382）
					4. Plan to Remove Debugging Aids（计划删除调试辅助工具）（384）
				7. Determining How Much Defensive Programming to Leave in Production Code（确定在生产代码中保留多少防御性编程）（388）
				8. Being Defensive About Defensive Programming（对防御性编程持防御态度）（390）
			5. The Pseudocode Programming Process（伪代码编程过程）（397）
				1. Summary of Steps in Building Classes and Routines（构建类和例程的步骤摘要）（398）
					1. Steps in Creating a Class（创建类的步骤）（399）
					2. Steps in Building a Routine（建立例程的步骤）（400）
				2. Pseudocode for Pros（专业人士的伪代码）（402）
				3. Constructing Routines by Using the PPP（使用PPP构建例程）（406）
					1. Design the Routine（设计例程）（407）
					2. Code the Routine（编写例程代码）（414）
					3. Check the Code（检查代码）（420）
					4. Clean Up Leftovers（清理剩菜）（424）
					5. Repeat Steps as Needed（根据需要重复步骤）（425）
				4. Alternatives to the PPP（PPP  的替代方案）（426）
		3. Variables（变量）（429）
			1. General Issues in Using Variables（使用变量的一般问题）（430）
				1. Data Literacy（数据素养）（432）
					1. The Data Literacy Test（数据素养测试）（433）
					2. Additional Resources on Data Types（有关数据类型的其他资源）（435）
				2. Making Variable Declarations Easy（使变量声明变得简单）（436）
					1. Implicit Declarations（隐式声明）（437）
				3. Guidelines for Initializing Variables（初始化变量的指南）（439）
				4. Scope（范围）（445）
					1. Localize References to Variables（本地化对变量的引用）（446）
					2. Keep Variables "Live" for as Short a Time as Possible（保持变量“活动”的时间尽可能短）（448）
					3. General Guidelines for Minimizing Scope（最小化范围的一般准则）（452）
					4. Comments on Minimizing Scope（对最小化范围的评论）（455）
				5. Persistence（坚持）（457）
				6. Binding Time（结合时间）（459）
				7. Relationship Between Data Types and Control Structures（数据类型和控制结构之间的关系）（461）
				8. Using Each Variable for Exactly One Purpose（将每个变量仅用于一个目的）（464）
			2. The Power of Variable Names（变量名称的力量）（469）
				1. Considerations in Choosing Good Names（选择好名字的注意事项）（470）
					1. The Most Important Naming Consideration（最重要的命名考虑因素）（472）
					2. Problem Orientation（问题导向）（474）
					3. Optimum Name Length（最佳名称长度）（474）
					4. The Effect of Scope on Variable Names（范围对变量名的影响）（477）
					5. Computed-Value Qualifiers in Variable Names（变量名称中的计算值限定符）(479)
					6. Common Opposites in Variable Names（变量名称中常见的反义词）（480）
				2. Naming Specific Types of Data（命名特定类型的数据）（481）
					1. Naming Loop Indexes（命名循环索引）（482）
					2. Naming Status Variables（命名状态变量）（484）
					3. Naming Temporary Variables（命名临时变量）（486）
					4. Naming Boolean Variables（命名布尔变量）（487）
					5. Naming Enumerated Types（命名枚举类型）（489）
					6. Naming Constants（命名常量）（491）
				3. The Power of Naming Conventions（命名约定的力量）（491）
					1. Why Have Conventions?（为什么要有约定？）（493）
					2. When You Should Have a Naming Convention（什么时候应该有命名约定）（495）
					3. Degrees of Formality（正式程度）（496）
				4. Informal Naming Conventions（非正式命名约定）（497）
					1. Guidelines for a Language-Independent Convention（独立于语言的约定指南）（498）
					2. Guidelines for Language-Specific Conventions（特定语言约定指南）（502）
					3. Mixed-Language Programming Considerations（混合语言编程注意事项）（504）
					4. Sample Naming Conventions（示例命名约定）（506）
				5. Standardized Prefixes（标准化前缀）（510）
					1. User-Defined Type Abbreviations（用户定义类型缩写）（511）
					2. Semantic Prefixes（语义前缀）（513）
					3. Advantages of Standardized Prefixes（标准化前缀的优点）（515）
				6. Creating Short Names That Are Readable（创建可读的短名称）（516）
					1. General Abbreviation Guidelines（一般缩写指南）（517）
					2. Phonetic Abbreviations（音标缩略语）（518）
					3. Comments on Abbreviations（对缩写的评论）（519）
				7. Kinds of Names to Avoid（应避免使用的名称类型）（522）
			3. Fundamental Data Types（基本数据类型）（528）
				1. Numbers in General（一般数字）（530）
				2. Integers（整数）（533）
				3. Floating-Point Numbers（浮点数字）（536）
				4. Characters and Strings（字符和字符串）（540）
					1. Strings in C（C  中的字符串）（543）
				5. Boolean Variables（布尔变量）（546）
				6. Enumerated Types（枚举类型）（549）
					1. If Your Language Doesn't Have Enumerated Types（如果您的语言没有枚举类型）（554）
				7. Named Constants（命名常量）（555）
				8. Arrays（数组）（559）
				9. Creating Your Own Types (Type Aliasing)（创建您自己的类型（类型别名））（562）
					1. Why Are the Examples of Creating Your Own Types in Pascal and Ada?（为什么 Pascal 和 Ada 中有创建您自己的类型的示例？）（566）
					2. Guidelines for Creating Your Own Types（创建您自己的类型的指南）（567）
			4. Unusual Data Types（异常数据类型）（572）
				1. Structures（结构）（573）
				2. Pointers（指针）（578）
					1. Paradigm for Understanding Pointers（理解指针的范例）（579）
					2. General Tips on Pointers（关于指针的一般提示）（581）
					3. C++-Pointer Pointers（C++-指针 指针）（592）
					4. C-Pointer Pointers（C 指针 指针）（594）
				3. Global Data（全球数据）（596）
					1. Common Problems with Global Data（全局数据的常见问题）（597）
					2. Reasons to Use Global Data（使用全球数据的原因）（601）
					3. Use Global Data Only as a Last Resort（仅将全局数据用作最后的手段）（603）
					4. Using Access Routines Instead of Global Data（使用访问例程而不是全局数据）（604）
					5. How to Reduce the Risks of Using Global Data（如何降低使用全球数据的风险）（610）
		4. Statements（声明）（616）
			1. Organizing Straight-Line Code（组织直线代码）（616）
				1. Statements That Must Be in a Specific Order（必须按特定顺序的语句）（617）
				2. Statements Whose Order Doesn't Matter（顺序无关紧要的语句）（622）
					1. Making Code Read from Top to Bottom（使代码从上到下阅读）（623）
					2. Grouping Related Statements（对相关语句进行分组）（625）
			2. Using Conditionals（使用条件）（628）
				1. if Statements（if语句）（629）
					1. Plain if-then Statements（简单的if‑then语句）（630）
					2. Chains of if-then-else Statements（if‑then‑else语句链）（635）
				2. case Statements（case语句）（638）
					1. Choosing the Most Effective Ordering of Cases（选择最有效的案例排序）（639）
					2. Tips for Using case Statements（使用case语句的技巧）（640）
			3. Controlling Loops（控制循环）（647）
				1. Selecting the Kind of Loop（选择循环类型）（648）
					1. When to Use a while Loop（何时使用while循环）（650）
					2. When to Use a Loop-With-Exit Loop（何时使用带退出的循环）（651）
					3. When to Use a for Loop（何时使用for循环）（655）
					4. When to Use a foreach Loop（何时使用foreach循环）（656）
				2. Controlling the Loop（控制循环）（657）
					1. Entering the Loop（进入循环）（658）
					2. Processing the Middle of the Loop（处理循环的中间部分）（661）
					3. Exiting the Loop（退出循环）（663）
					4. Checking Endpoints（检查端点）（669）
					5. Using Loop Variables（使用循环变量）（670）
					6. How Long Should a Loop Be?（循环应该多长？）（674）
				3. Creating Loops Easily—From the Inside Out（轻松创建循环——从内到外）（675）
				4. Correspondence Between Loops and Arrays（循环与数组的对应关系）（678）
			4. Unusual Control Structures（不寻常的控制结构）（681）
				1. Multiple Returns from a Routine（例程的多次返回）（682）
				2. Recursion（递归）（685）
					1. Example of Recursion（递归示例）（686）
					2. Tips for Using Recursion（使用递归的技巧）（688）
				3. goto(691)
					1. The Argument Against gotos（反对goto  的争论）（691）
					2. The Argument for gotos（goto的论证）（694）
					3. The Phony goto Debate（虚假的转到辩论）（696）
					4. Error Processing and gotos（错误处理和跳转）（698）
					5. gotos and Sharing Code in an else Clause（goto和在else子句中共享代码）（704）
					6. Summary of Guidelines for Using gotos（goto使用指南摘要）（706）
				4. Perspective on Unusual Control Structures（对不寻常控制结构的看法）（708）
			5. Table-Driven Methods（表驱动方法）（715）
				1. General Considerations in Using Table-Driven Methods（使用表驱动方法的一般注意事项）（716）
					1. Two Issues in Using Table-Driven Methods（使用表驱动方法的两个问题）（717）
				2. Direct Access Tables（直接访问表）（718）
					1. Days-in-Month Example（一个月中的天数示例）（719）
					2. Insurance Rates Example（保险费率示例）（721）
					3. Flexible-Message-Format Example（灵活消息格式示例）（724）
					4. Logic-Based Approach（基于逻辑的方法）（726）
					5. Object-Oriented Approach（面向对象的方法）（727）
					6. Table-Driven Approach（表驱动方法）（729）
					7. Fudging Lookup Keys（伪造查找键）（734）
				3. Indexed Access Tables（索引访问表）（736）
				4. Stair-Step Access Tables（阶梯通道表）（739）
				5. Other Examples of Table Lookups（表查找的其他示例）（743）
			6. General Control Issues（一般控制问题）（745）
				1. Boolean Expressions（布尔表达式）（746）
					1. Using true and false for Boolean Tests（使用true和false进行布尔测试）（747）
					2. Making Complicated Expressions Simple（使复杂的表达式变得简单）（750）
					3. Forming Boolean Expressions Positively（正向构造布尔表达式）（753）
					4. Using Parentheses to Clarify Boolean Expressions（使用括号来阐明布尔表达式）（756）
					5. Knowing How Boolean Expressions Are Evaluated（了解如何评估布尔表达式）（758）
					6. Writing Numeric Expressions in Number-Line Order（按数轴顺序编写数值表达式）（761）
					7. Guidelines for Comparisons to 0（与0比较的指南）（762）
					8. Common Problems with Boolean Expressions（布尔表达式的常见问题）（764）
				2. Compound Statements (Blocks)（复合语句（块））（765）
				3. Null Statements（空语句）（768）
				4. Taming Dangerously Deep Nesting（驯服危险的深层嵌套）（770）
					1. Summary of Techniques for Reducing Deep Nesting（减少深度嵌套的技术总结）（780）
				5. A Programming Foundation: Structured Programming（编程基础：结构化编程）（781）
					1. The Three Components of Structured Programming（结构化编程的三个组成部分）（782）
				6. Control Structures and Complexity（控制结构和复杂性）（785）
					1. How Important Is Complexity?（复杂性有多重要？）（786）
					2. General Guidelines for Reducing Complexity（降低复杂性的一般准则）（787）
					3. Other Kinds of Complexity（其他类型的复杂性）（789）
		5. Code Improvements（代码改进）（791）
			1. The Software-Quality Landscape（软件质量格局）（792）
				1. Characteristics of Software Quality（软件质量的特点）（793）
				2. Techniques for Improving Software Quality（提高软件质量的技术）（797）
					1. Development Process（开发流程）（800）
					2. Setting Objectives（设定目标）（802）
				3. Relative Effectiveness of Quality Techniques（质量技术的相对有效性）（804）
					1. Percentage of Defects Detected（检测到的缺陷百分比）（805）
					2. Cost of Finding Defects（发现缺陷的成本）（809）
					3. Cost of Fixing Defects（修复缺陷的成本）（810）
				4. When to Do Quality Assurance（何时进行质量保证）（812）
				5. The General Principle of Software Quality（软件质量的一般原则）（813）
			2. Collaborative Construction（协同建设）（820）
				1. Overview of Collaborative Development Practices（协作开发实践概述）（822）
					1. Collaborative Construction Complements Other Quality-Assurance Techniques（协同施工补充了其他质量保证技术）（823）
					2. Collaborative Construction Provides Mentoring in Corporate Culture and Programming Expertise（协作构建提供企业文化和编程专业知识方面的指导）（826）
					3. Collective Ownership Applies to All Forms of Collaborative Construction（集体所有制适用于各种形式的协同建设）（827）
					4. Collaboration Applies As Much Before Construction As After（施工前和施工后的协作同样适用）（828）
				2. Pair Programming（结对编程）（829）
					1. Keys to Success with Pair Programming（结对编程成功的关键）（830）
					2. Benefits of Pair Programming（结对编程的好处）（832）
				3. Formal Inspections（正式检查）（833）
					1. What Results Can You Expect from Inspections?（您可以从检查中得到什么结果？）（834）
					2. Roles During an Inspection（检查期间的角色）（835）
					3. General Procedure for an Inspection（检查的一般程序）（837）
					4. Egos in Inspections（检查中的自我意识）（841）
					5. Inspections and Code Complete（检查和代码完成）（842）
					6. Inspection Summary（检查总结）（843）
				4. Other Kinds of Collaborative Development Practices（其他类型的协作开发实践）（845）
					1. Walk-Throughs（演练）（846）
					2. Code Reading（代码阅读）（849）
					3. Dog-and-Pony Shows（狗和小马表演）（851）
				5. Comparison of Collaborative Construction Techniques（协同施工技术比较）（852）
			3. Developer Testing（开发人员测试）（858）
				1. Role of Developer Testing in Software Quality（开发人员测试在软件质量中的作用）（861）
					1. Testing During Construction（施工期间测试）（864）
				2. Recommended Approach to Developer Testing（推荐的开发人员测试方法）（865）
					1. Test First or Test Last?（先测试还是最后测试？）（866）
					2. Limitations of Developer Testing（开发人员测试的局限性）（867）
				3. Bag of Testing Tricks（测试技巧包）（868）
					1. Incomplete Testing（测试不完整）（869）
					2. Structured Basis Testing（结构化基础测试）（870）
					3. Data-Flow Testing（数据流测试）（875）
					4. Equivalence Partitioning（等价划分）（880）
					5. Error Guessing（错误猜测）（881）
					6. Boundary Analysis（边界分析）（882）
					7. Classes of Bad Data（不良数据的类别）（884）
					8. Classes of Good Data（好数据的类别）（885）
					9. Use Test Cases That Make Hand-Checks Convenient（使用方便手动检查的测试用例）（887）
				4. Typical Errors（典型错误）（888）
					1. Which Classes Contain the Most Errors?（哪些类包含最多错误？）（889）
					2. Errors by Classification（错误分类）（891）
					3. Proportion of Errors Resulting from Faulty Construction（因施工错误而导致的错误比例）（894）
					4. How Many Errors Should You Expect to Find?（您应该期望发现多少错误？）（896）
					5. Errors in Testing Itself（测试本身的错误）（898）
				5. Test-Support Tools（测试支持工具）（900）
					1. Building Scaffolding to Test Individual Classes（构建脚手架来测试各个类）（901）
					2. Diff Tools（差异工具）（904）
					3. Test-Data Generators（测试数据生成器）（905）
					4. Coverage Monitors（覆盖范围监视器）（907）
					5. Data Recorder/Logging（数据记录器/记录）（908）
					6. Symbolic Debuggers（符号调试器）（909）
					7. System Perturbers（系统扰动者）（910）
					8. Error Databases（错误数据库）（911）
				6. Improving Your Testing（改进您的测试）（912）
					1. Planning to Test（计划测试）（913）
					2. Retesting (Regression Testing)（重新测试（回归测试））（914）
					3. Automated Testing（自动化测试）（915）
				7. Keeping Test Records（保存测试记录）（917）
					1. Personal Test Records（个人测试记录）（918）
					2. Additional Resources（其他资源）（919）
					3. Testing（测试）（920）
					4. Test Scaffolding（测试脚手架）（922）
					5. Test First Development（测试优先开发）（923）
					6. Relevant Standards（相关标准）（924）
			4. Debugging（调试）（926）
				1. Overview of Debugging Issues（调试问题概述）（927）
					1. Role of Debugging in Software Quality（调试在软件质量中的作用）（929）
					2. Variations in Debugging Performance（调试性能的变化）（930）
					3. Defects as Opportunities（缺陷即机遇）（932）
					4. An Ineffective Approach（无效的方法）（934）
				2. Finding a Defect（寻找缺陷）（936）
					1. The Scientific Method of Debugging（科学的调试方法）（937）
					2. Tips for Finding Defects（查找缺陷的技巧）（942）
					3. Syntax Errors（语法错误）（950）
				3. Fixing a Defect（修复缺陷）（952）
				4. Psychological Considerations in Debugging（调试中的心理考虑）（958）
					1. How "Psychological Set" Contributes to Debugging Blindness（“心理设定”如何导致调试失明）（959）
					2. How "Psychological Distance" Can Help（“心理距离”有何帮助）（961）
				5. Debugging Tools—Obvious and Not-So-Obvious（调试工具——显而易见的和不那么显而易见的）（961）
					1. Source-Code Comparators（源代码比较器）（963）
					2. Compiler Warning Messages（编译器警告消息）（964）
					3. Extended Syntax and Logic Checking（扩展语法和逻辑检查）（966）
					4. Execution Profilers（执行分析器）（967）
					5. Test Frameworks/Scaffolding（测试框架/脚手架）（968）
					6. Debuggers（调试器）（969）
			5. Refactoring（重构）（975）
				1. Kinds of Software Evolution（软件演化的种类）（977）
					1. Philosophy of Software Evolution（软件演化哲学）（978）
				2. Introduction to Refactoring（重构简介）（979）
					1. Reasons to Refactor（重构的原因）（980）
					2. Reasons Not to Refactor（不重构的原因）（987）
				3. Specific Refactorings（具体重构）（988）
					1. Data-Level Refactorings（数据级重构）（989）
					2. Statement-Level Refactorings（语句级重构）（991）
					3. Routine-Level Refactorings（例程级重构）（993）
					4. Class Implementation Refactorings（类实现重构）（995）
					5. Class Interface Refactorings（类接口重构）（996）
					6. System-Level Refactorings（系统级重构）（998）
				4. Refactoring Safely（安全重构）（1001）
					1. Bad Times to Refactor（重构的糟糕时机）（1004）
				5. Refactoring Strategies（重构策略）（1005）
			6. Code-Tuning Strategies（代码调整策略）（1010）
				1. Performance Overview（性能概览）（1012）
					1. Quality Characteristics and Performance（质量特性及性能）（1013）
					2. Performance and Code Tuning（性能和代码调优）（1015）
				2. Introduction to Code Tuning（代码调优简介）（1020）
					1. The Pareto Principle（帕累托法则）（1021）
					2. Old Wives' Tales（老妇人的故事）（1023）
					3. When to Tune（何时调整）（1028）
					4. Compiler Optimizations（编译器优化）（1029）
				3. Kinds of Fat and Molasses（脂肪和糖蜜的种类）（1031）
					1. Common Sources of Inefficiency（低效率的常见根源）（1032）
					2. Relative Performance Costs of Common Operations（常见操作的相对性能成本）（1037）
				4. Measurement（测量）（1041）
					1. Measurements Need to Be Precise（测量需要精确）（1043）
				5. Iteration（迭代）（1044）
				6. Summary of the Approach to Code Tuning（代码调优方法总结）（1046）
			7. Code-Tuning Techniques（代码调整技术）（1052）
				1. Logic（逻辑）（1054）
					1. Stop Testing When You Know the Answer（当您知道答案时停止测试）（1055）
					2. Order Tests by Frequency（按频率排序测试）（1057）
					3. Compare Performance of Similar Logic Structures（比较类似逻辑结构的性能）（1060）
					4. Substitute Table Lookups for Complicated Expressions（用表查找替换复杂的表达式）（1061）
					5. Use Lazy Evaluation（使用惰性求值）（1063）
				2. Loops（循环）（1064）
					1. Unswitching（取消切换）（1065）
					2. Jamming（干扰）（1067）
					3. Unrolling（展开）（1069）
					4. Minimizing the Work Inside Loops（最小化循环内的工作）（1072）
					5. Sentinel Values（哨兵价值观）（1074）
					6. Putting the Busiest Loop on the Inside（将最繁忙的循环放在内部）（1077）
					7. Strength Reduction（强度降低）（1078）
				3. Data Transformations（数据转换）（1080）
					1. Use Integers Rather Than Floating-Point Numbers（使用整数而不是浮点数）（1081）
					2. Use the Fewest Array Dimensions Possible（使用尽可能少的数组维度）（1083）
					3. Minimize Array References（最小化数组引用）（1085）
					4. Use Supplementary Indexes（使用补充索引）（1086）
					5. Use Caching（使用缓存）（1087）
				4. Expressions（表达式）（1089）
					1. Exploit Algebraic Identities（利用代数恒等式）（1090）
					2. Use Strength Reduction（使用强度降低）（1091）
					3. Initialize at Compile Time（编译时初始化）（1094）
					4. Be Wary of System Routines（警惕系统例程）（1096）
					5. Use the Correct Type of Constants（使用正确类型的常量）（1098）
					6. Precompute Results（预先计算结果）（1099）
					7. Eliminate Common Subexpressions（消除公共子表达式）（1103）
				5. Routines（例程）（1104）
					1. Rewrite Routines Inline（内联重写例程）（1105）
				6. Recoding in a Low-Level Language（用低级语言重新编码）（1106）
				7. The More Things Change, the More They Stay the Same（事物变化越多，它们就越保持不变）（1110）
		6. System Considerations（系统注意事项）（1115）
			1. How Program Size Affects Construction（程序大小如何影响构造）（1116）
				1. Communication and Size（沟通和规模）（1118）
				2. Range of Project Sizes（项目规模范围）（1120）
				3. Effect of Project Size on Errors（项目规模对错误的影响）（1122）
				4. Effect of Project Size on Productivity（项目规模对生产力的影响）（1125）
				5. Effect of Project Size on Development Activities（项目规模对开发活动的影响）（1127）
					1. Activity Proportions and Size（活动比例及规模）（1128）
					2. Programs, Products, Systems, and System Products（程序、产品、系统和系统产品）（1131）
					3. Methodology and Size（方法论和规模）（1133）
			2. Managing Construction（管理施工）（1138）
				1. Encouraging Good Coding（鼓励良好的编码）（1140）
					1. Considerations in Setting Standards（制定标准时的考虑因素）（1141）
					2. Techniques for Encouraging Good Coding（鼓励良好编码的技术）（1142）
					3. The Role of This Book（本书的作用）（1145）
				2. Configuration Management（配置管理）（1146）
					1. What Is Configuration Management?（什么是配置管理？）（1147）
					2. Requirements and Design Changes（要求和设计变更）（1149）
					3. Software Code Changes（软件代码变更）（1152）
					4. Tool Versions（工具版本）（1154）
					5. Machine Configurations（机器配置）（1155）
					6. Backup Plan（后备方案）（1156）
					7. Additional Resources on Configuration Management（有关配置管理的其他资源）（1158）
				3. Estimating a Construction Schedule（估算施工进度）（1159）
					1. Estimation Approaches（估计方法）（1160）
					2. Estimating the Amount of Construction（估算施工量）（1164）
					3. Influences on Schedule（对日程的影响）（1165）
					4. Estimation vs. Control（估计与控制）（1168）
					5. What to Do If You're Behind（如果你落后了怎么办）（1169）
					6. Additional Resources on Software Estimation（有关软件估算的其他资源）（1171）
				4. Measurement（测量）（1172）
					1. Additional Resources on Software Measurement（有关软件测量的其他资源）（1176）
				5. Treating Programmers as People（把程序员当人对待）（1178）
					1. How Do Programmers Spend Their Time?（程序员如何度过他们的时间？）（1179）
					2. Variation in Performance and Quality（性能和质量的变化）（1181）
					3. Religious Issues（宗教问题）（1184）
					4. Physical Environment（物理环境）（1186）
					5. Additional Resources on Programmers as Human Beings（有关程序员作为人类的其他资源）（1188）
				6. Managing Your Manager（管理你的经理）（1190）
					1. Additional Resources on Managing Construction（有关管理施工的其他资源）（1191）
					2. Relevant Standards（相关标准）（1192）
			3. Integration（整合）（1194）
				1. Importance of the Integration Approach（整合方法的重要性）（1195）
				2. Integration Frequency—Phased or Incremental?（积分频率——分阶段还是增量？）（1197）
					1. Phased Integration（分阶段整合）（1198）
					2. Incremental Integration（增量集成）（1200）
					3. Benefits of Incremental Integration（增量集成的好处）（1202）
				3. Incremental Integration Strategies（增量集成策略）（1204）.
					1. Top-Down Integration（自上而下的整合）（1205）
					2. Bottom-Up Integration（自下而上的整合）（1208）
					3. Sandwich Integration（三明治整合）（1210）
					4. Risk-Oriented Integration（以风险为导向的整合）（1211）
					5. Feature-Oriented Integration（面向功能的集成）（1212）
					6. T-Shaped Integration（T型整合）（1214）
					7. Summary of Integration Approaches（集成方法总结）（1215）
				4. Daily Build and Smoke Test（每日构建和冒烟测试）（1216）
					1. What Kinds of Projects Can Use the Daily Build Process?（哪些类型的项目可以使用日常构建流程？）（1222）
					2. Continuous Integration（持续集成）（1223）
			4. Programming Tools（编程工具）（1229）
				1. Design Tools（设计工具）（1231）
				2. Source-Code Tools（源代码工具）（1232）
					1. Editing（编辑）（1233）
					2. Analyzing Code Quality（分析代码质量）（1238）
					3. Refactoring Source Code（重构源代码）（1240）
					4. Version Control（版本控制）（1242）
					5. Data Dictionaries（数据字典）（1243）
				3. Executable-Code Tools（可执行代码工具）（1244）
					1. Code Creation（代码创建）（1245）
					2. Debugging（调试）（1249）
					3. Testing（测试）（1250）
					4. Code Tuning（代码调优）（1251）
				4. Tool-Oriented Environments（面向工具的环境）（1252）
				5. Building Your Own Programming Tools（构建您自己的编程工具）（1253）
					1. Project-Specific Tools（项目特定工具）（1254）
					2. Scripts（脚本）（1255）
				6. Tool Fantasyland（工具幻想世界）（1256）
		7. Software Craftsmanship（软件工艺）（1261）
			1. Layout and Style（布局和风格）（1262）
				1. Layout Fundamentals（布局基础知识）（1264）
					1. Layout Extremes（极端布局）（1265）
					2. The Fundamental Theorem of Formatting（格式化的基本定理）（1268）
					3. Human and Computer Interpretations of a Program（程序的人类和计算机解释）（1269）
					4. How Much Is Good Layout Worth?（好的布局值多少钱？）（1270）
					5. Layout as Religion（作为宗教的布局）（1273）
					6. Objectives of Good Layout（良好布局的目标）（1275）
				2. Layout Techniques（布局技巧）（1277）
					1. White Space（空白）（1278）
					2. Parentheses（括号）（1281）
				3. Layout Styles（布局样式）（1282）
					1. Pure Blocks（纯块）（1283）
					2. Emulating Pure Blocks（模拟纯块）（1285）
					3. Using begin-end Pairs (Braces) to Designate Block Boundaries（使用开始‑结束对（大括号）来指定块边界）（1287）
					4. Endline Layout（端线布局）（1289）
					5. Which Style Is Best?（哪种风格最好？）（1292）
				4. Laying Out Control Structures（布置控制结构）（1293）
					1. Fine Points of Formatting Control-Structure Blocks（格式化控制结构块的要点）（1294）
					2. Other Considerations（其他考虑因素）（1297）
				5. Laying Out Individual Statements（制定个人陈述）（1304）
					1. Statement Length（语句长度）（1305）
					2. Using Spaces for Clarity（使用空格来提高清晰度）（1306）
					3. Formatting Continuation Lines（设置连续行的格式）（1307）
					4. Using Only One Statement Per Line（每行仅使用一个语句）（1313）
					5. Laying Out Data Declarations（布置数据声明）（1317）
				6. Laying Out Comments（发表评论）（1321）
				7. Laying Out Routines（安排日常事务）（1324）
				8. Laying Out Classes（布置类）（1327）
					1. Laying Out Class Interfaces（布局类接口）（1328）
					2. Laying Out Class Implementations（布局类实现）（1329）
					3. Laying Out Files and Programs（布置文件和程序）（1333）
			2. Self-Documenting Code（自记录代码）（1339）
				1. External Documentation（外部文档）（1340）
				2. Programming Style as Documentation（作为文档的编程风格）（1342）
				3. To Comment or Not to Comment（注释或不注释）（1346）
				4. Keys to Effective Comments（有效注释的关键）（1351）
					1. Kinds of Comments（注释种类）（1353）
					2. Commenting Efficiently（高效注释）（1356）
					3. Optimum Number of Comments（最佳注释数）（1361）
				5. Commenting Techniques（注释技巧）（1362）
					1. Commenting Individual Lines（注释单行）（1363）
					2. Commenting Paragraphs of Code（注释代码段落）（1367）
					3. Commenting Data Declarations（注释数据声明）（1376）
					4. Commenting Control Structures（注释控制结构）（1379）
					5. Commenting Routines（注释例程）（1381）
					6. Commenting Classes, Files, and Programs（注释类、文件和程序）（1388）
				6. IEEE Standards（IEEE  标准）（1393）
					1. Software-Development Standards（软件开发标准）（1394）
					2. Software Quality-Assurance Standards（软件质量保证标准）（1395）
					3. Management Standards（管理标准）（1396）
					4. Overview of Standards（标准概述）（1397）
			3. Personal Character（个人品格）（1402）
				1. Isn't Personal Character Off the Topic?（个人性格不是题外话吗？）（1404）
				2. Intelligence and Humility（智慧与谦逊）（1405）
				3. Curiosity（好奇心）（1407）
				4. Intellectual Honesty（知识诚实）（1413）
				5. Communication and Cooperation（交流合作）（1417）
				6. Creativity and Discipline（创造力与纪律）（1418）
				7. Laziness（懒惰）（1420）
				8. Characteristics That Don't Matter As Much As You Might Think（特征并不像您想象的那么重要）（1422）
					1. Persistence（坚持）（1423）
					2. Experience（经验）（1424）
					3. Gonzo Programming（奇闻趣事编程）（1426）
				9. Habits（习惯）（1427）
			4. Themes in Software Craftsmanship（软件工艺的主题）（1432）
				1. Conquer Complexity（征服复杂性）（1433）
				2. Pick Your Process（选择您的流程）（1436）
				3. Write Programs for People First, Computers Second（首先为人编写程序，其次为计算机编写程序）（1439）
				4. Program into Your Language, Not in It（用你的语言编程，而不是用它）（1442）
				5. Focus Your Attention with the Help of Conventions（在惯例的帮助下集中你的注意力）（1444）
				6. Program in Terms of the Problem Domain（根据问题域进行规划）（1446）
					1. Separating a Program into Levels of Abstraction（将程序分为多个抽象级别）（1447）
					2. Low-Level Techniques for Working in the Problem Domain（在问题领域工作的低级技术）（1450）
				7. Watch for Falling Rocks（留意落石）（1451）
				8. Iterate, Repeatedly, Again and Again（迭代，反复，一次又一次）（1454）
				9. Thou Shalt Rend Software and Religion Asunder（你应该分裂软件和宗教）（1456）
					1. Software Oracles（软件预言机）（1457）
					2. Eclecticism（折衷主义）（1458）
					3. Experimentation（实验）（1460）
			5. Where to Find More Information（哪里可以找到更多信息）（1462）
				1. Information About Software Construction（软件建设信息）（1464）
				2. Topics Beyond Construction（建筑之外的主题）（1466）
					1. Overview Material（概述材料）（1467）
					2. Software-Engineering Overviews（软件工程概述）（1469）
					3. Other Annotated Bibliographies（其他带注释的参考书目）（1470）
				3. Periodicals（期刊）（1471）
					1. Lowbrow Programmer Magazines（低俗程序员杂志）（1472）
					2. Highbrow Programmer Journals（高雅程序员期刊）（1473）
					3. Special-Interest Publications（特别兴趣出版物）（1474）
				4. A Software Developer's Reading Plan（软件开发人员的阅读计划）（1475）
					1. Introductory Level（入门级）（1476）
					2. Practitioner Level（从业者级别）（1477）
					3. Professional Level（专业水平）（1478）
				5. Joining a Professional Organization（加入专业组织）（1479）
	6. Working Effectively with Legacy Code（修改代码的艺术）
		1. The Mechanics of Change（变革的机制）（24）
			1. Changing Software（改变软件）（26）
				1. Four Reasons to Change Software（更换软件的四个理由）（26）
					1. Adding Features and Fixing Bugs（添加功能并修复错误）（26）
					2. Improving Design（改进设计）（28）
					3. Optimization（优化）（29）
					4. Putting It All Together（把它们放在一起）（29）
				2. Risky Change（危险的改变）（30）
			2. Working with Feedback（处理反馈）（32）
				1. What Is Unit Testing?（什么是单元测试？）（35）
				2. Higher-Level Testing（更高级别的测试）（37）
				3. Test Coverings（测试覆盖物）（37）
				4. The Legacy Code Change Algorithm（遗留代码更改算法）（41）
					1. Identify Change Points（识别变化点）（41）
					2. Find Test Points（寻找测试点）（42）
					3. Break Dependencies（打破依赖关系）（42）
					4. Write Tests（编写测试）（42）
					5. Make Changes and Refactor（进行更改和重构）（43）
					6. The Rest of This Book（本书的其余部分）（43）
			3. Sensing and Separation（传感与分离）（46）
				1. Faking Collaborators（伪造合作者）（46）
					1. Fake Objects（假物体）（46）
					2. The Two Sides of a Fake Object（假物体的两侧）（49）
					3. Fakes Distilled（假货蒸馏）（50）
					4. Mock Objects（模拟对象）（50）
			4. The Seam Model（接缝模型）（52）
				1. A Huge Sheet of Text（一大页文字）（52）
				2. Seams（接缝）（53）
				3. Seam Types（接缝类型）（56）
					1. Preprocessing Seams（预处理接缝）（56）
					2. Link Seams（连接缝）（59）
					3. Object Seams（对象接缝）（63）
			5. Tools（工具）（68）
				1. Automated Refactoring Tools（自动重构工具）（68）
				2. Mock Objects（模拟对象）（70）
				3. Unit-Testing Harnesses（单元测试工具）（71）
					1. JUnit（72）
					2. CppUnitLite（73）
					3. NUnit（75）
					4. Other xUnit Frameworks（其他  xUnit  框架）（75）
				4. General Test Harnesses（通用测试工具）（76）
					1. Framework for Integrated Tests (FIT)（集成测试框架（FIT））（76）
					2. Fitnesse（健康）（76）
		2. 3Changing Software（改变软件）（78）
			1. I Don’t Have Much Time and I Have to Change It（我没有太多时间，我必须改变它）（80）
				1. Sprout Method（发芽法）（82）
					1. Advantages and Disadvantages（优点和缺点）（85）
				2. Sprout Class（萌芽类）
					1. Advantages and Disadvantages（优点和缺点）（90）
				3. Wrap Method（包裹法）（90）
					1. Advantages and Disadvantages（优点和缺点）（93）
				4. Wrap Class（包裹类）（94）
				5. Summary（概括）（99）
			2. It Takes Forever to Make a Change（改变需要永远）（100）
				1. Understanding（理解）（100）
				2. Lag Time（找时间）（101）
				3. Breaking Dependencies（打破依赖）（102）
					1. Build Dependencies（构建依赖关系）（103）
				4. Summary（概括）（108）
			3. How Do I Add a Feature?（如何添加功能？）（110）
				1. Test-Driven Development (TDD)（测试驱动开发  (TDD)）（111）
					1. Write a Failing Test Case（编写失败的测试用例）（111）
					2. Get It to Compile（让它编译）（111）
					3. Make It Pass（让它通过）（112）
					4. Remove Duplication（删除重复项）（112）
					5. Write a Failing Test Case（编写失败的测试用例）（112）
					6. Get It to Compile（让它编译）（113）
					7. Make It Pass（让它通过）（113）
					8. Remove Duplication（删除重复项）（113）
					9. Write a Failing Test Case（编写失败的测试用例）（114）
					10. Get It to Compile（让它编译）（114）
					11. Make It Pass（让它通过）（115）
					12. Remove Duplication（删除重复项）（116）
				2. Programming by Difference（差异编程）（117）
				3. Summary（概括）（127）
			4. I Can’t Get This Class into a Test Harness（我无法将此类放入测试工具中）（128）
				1. The Case of the Irritating Parameter（令人恼火的参数的情况）（129）
				2. The Case of the Hidden Dependency（隐藏依赖的案例）（136）
				3. The Case of the Construction Blob（建筑斑点的案例）（139）
				4. The Case of the Irritating Global Dependency（令人恼火的全球依赖性案例）（141）
				5. The Case of the Horrible Include Dependencies（可怕的依赖关系案例）（150）
				6. The Case of the Onion Parameter（洋葱参数的案例）（153）
				7. The Case of the Aliased Parameter（别名参数的情况）（156）
			5. I Can’t Run This Method in a Test Harness（我无法在测试工具中运行此方法）（160）
				1. The Case of the Hidden Method（隐藏方法的案例）（161）
				2. The Case of the “Helpful” Language Feature（“有用”语言功能的案例）（164）
				3. The Case of the Undetectable Side Effect（无法检测到的副作用的案例）（167）
			6. I Need to Make a Change. What Methods Should I Test?（我需要做出改变。 我应该测试什么方法？）（174）
				1. Reasoning About Effects（关于效果的推理）（174）
				2. Reasoning Forward（向前推理）（180）
				3. Effect Propagation（效果传播）（186）
				4. Tools for Effect Reasoning（效果推理工具）（188）
				5. Learning from Effect Analysis（从效果分析中学习）（190）
				6. Simplifying Effect Sketches（简化效果草图）（191）
			7. I Need to Make Many Changes in One Area. Do I Have to Break Dependencies for All the Classes Involved?（我需要在一个领域做出许多改变。 我是否必须打破所有涉及的类的依赖关系？）（196）
				1. Interception Points（拦截点）（197）
					1. The Simple Case（简单的案例）（197）
					2. Higher-Level Interception Points（更高级别的拦截点）（201）
				2. Judging Design with Pinch Points（用夹点来判断设计）（205）
				3. Pinch Point Traps（夹点陷阱）（207）
			8. I Need to Make a Change, but I Don’t Know What Tests to Write（我需要做出改变，但我不知道要编写什么测试）（208）
				1. Characterization Tests（特性测试）（209）
				2. Characterizing Classes（表征类）（212）
				3. Targeted Testing（有针对性的测试）（213）
				4. A Heuristic for Writing Characterization Tests（编写表征测试的启发式方法）（218）
			9. Dependencies on Libraries Are Killing Me（对库的依赖正在杀死我）（220）
			10. My Application Is All API Calls（我的应用程序都是 API 调用）（222）
			11. I Don’t Understand the Code Well Enough to Change It（我对代码的理解不够深入，无法更改它）（232）
				1. Notes/Sketching（笔记/素描）（233）
				2. Listing Markup（列表标记）（234）
					1. Separating Responsibilities（职责分离）（234）
					2. Understanding Method Structure（了解方法结构）（234）
					3. Extract Methods（提取方法）（235）
					4. Understand the Effects of a Change（了解变革的影响）（235）
				3. Scratch Refactoring（从头开始重构）（235）
				4. Delete Unused Code（删除未使用的代码）（236）
			12. My Application Has No Structure（我的应用程序没有结构）（238）
				1. Telling the Story of the System（讲述系统的故事）（239）
				2. Naked CRC（裸CRC）（243）
				3. Conversation Scrutiny（对话审查）（247）
			13. My Test Code Is in the Way（我的测试代码妨碍了）（250）
				1. Class Naming Conventions（类命名约定）（250）
				2. Test Location（测试地点）（251）
			14. My Project Is Not Object Oriented. How Do I Make Safe Changes?（我的项目不是面向对象的。 如何进行安全的更改？）（254）
				1. An Easy Case（一个简单的案例）（255）
				2. A Hard Case（硬盒）（255）
				3. Adding New Behavior（添加新行为）（259）
				4. Taking Advantage of Object Orientation（利用面向对象）（262）
				5. It’s All Object Oriented（一切都是面向对象的）（265）
			15. This Class Is Too Big and I Don’t Want It to Get Any Bigger（这个类太大了，我不想让它变得更大）（268）
				1. Seeing Responsibilities（看到责任）（272）
				2. Other Techniques（其他技术）（288）
				3. Moving Forward（向前进）（288）
					1. Strategy（战略）（288）
					2. Tactic（策略）（289）
				4. After Extract Class（提取类之后）（291）
			16. I’m Changing the Same Code All Over the Place（我正在到处更改相同的代码）（292）
				1. First Steps（第一步）（295）
			17. I Need to Change a Monster Method and I Can’t Write Tests for It（我需要更改一个怪物方法，但无法为其编写测试）（312）
				1. Varieties of Monsters（各种怪物）（313）
					1. Bulleted Methods（项目符号方法）（313）
					2. Snarled Methods（咆哮的方法）（315）
				2. Tackling Monsters with Automated Refactoring Support（通过自动重构支持应对怪物）（317）
				3. The Manual Refactoring Challenge（手动重构的挑战）（320）
					1. Introduce Sensing Variable（引入传感变量）（321）
					2. Extract What You Know（提取你所知道的）（324）
					3. Gleaning Dependencies（收集依赖关系）（326）
					4. Break Out a Method Object（分解方法对象）（327）
				4. Strategy（战略）（327）
					1. Skeletonize Methods（骨架化方法）（327）
					2. Find Sequences（查找序列）（328）
					3. Extract to the Current Class First（首先提取到当前类）（329）
					4. Extract Small Pieces（提取小块）（329）
					5. Be Prepared to Redo Extractions（准备好重新提取）（330）
			18. How Do I Know That I’m Not Breaking Anything?（我怎么知道我没有破坏任何东西？）（332）
				1. Hyperaware Editing（超意识编辑）（333）
				2. Single-Goal Editing（单目标编辑）（334）
				3. Preserve Signatures（保留签名）（335）
				4. Lean on the Compiler（依靠编译器）（338）
					1. Pair Programming（结对编程）（339）
			19. We Feel Overwhelmed.It Isn’t Going to Get Any Better（我们感到不知所措，情况不会好转）（342）
		3. Dependency-Breaking Techniques（打破依赖的技术）（346）
			1. Dependency-Breaking Techniques（打破依赖的技术）（348）
				1. Adapt Parameter（适配参数）（349）
				2. Break Out Method Object（突破方法对象）（353）
				3. Definition Completion（定义完成）（360）
				4. Encapsulate Global References（封装全局引用）（362）
				5. Expose Static Method（暴露静态方法）（368）
				6. Extract and Override Call（提取并覆盖调用）（371）
				7. Extract and Override Factory Method（提取并覆盖工厂方法）（373）
				8. Extract and Override Getter（提取并覆盖  Getter）（375）
				9. Extract Implementer（提取实施者）（379）
					1. A More Complex Example（一个更复杂的例子）（382）
				10. Extract Interface（提取接口）（385）
				11. Introduce Instance Delegator（引入实例委托者）（392）
				12. Introduce Static Setter（引入静电设置器）（395）
				13. Link Substitution（链接替换）（400）
				14. Parameterize Constructor（参数化构造函数）（402）
				15. Parameterize Method（参数化方法）（406）
				16. Primitivize Parameter（参数原始化）（408）
				17. Pull Up Feature（上拉功能）（411）
				18. Push Down Dependency（下推依赖）（415）
				19. Replace Function with Function Pointer（用函数指针替换函数）（419）
				20. Replace Global Reference with Getter（用  Getter  替换全局引用）（422）
				21. Subclass and Override Method（子类和重写方法）（424）
				22. Supersede Instance Variable（取代实例变量）（427）
				23. Template Redefinition（模板重新定义）（431）
				24. Text Redefinition（文本重新定义）（435）
	7. Clean Code（编码整洁之道）
		1. Clean Code（干净的代码）（35）
			1. There Will Be Code（会有代码）（37）
			2. Bad Code（错误代码）（39）
			3. The Total Cost of Owning a Mess（拥有一团糟的总成本）（42）
				1. The Grand Redesign in the Sky（空中的宏伟重新设计）（43）
				2. Attitude（态度）（44）
				3. The Primal Conundrum（原始难题）（45）
				4. The Art of Clean Code?（干净代码的艺术？）（45）
				5. What Is Clean Code?（什么是干净代码？）（46）
			4. Schools of Thought（思想流派）（56）
			5. We Are Authors（我们是作者）（59）
			6. The Boy Scout Rule（童子军规则）（61）
			7. Prequel and Principles（前传和原理）（62）
			8. Conclusion（结论）（63）
		2. Meaningful Names（有意义的名字）（65）
			1. Introduction（介绍）（66）
			2. Use Intention-Revealing Names（使用透露意图的名称）（67）
			3. Avoid Disinformation（避免虚假信息）（70）
			4. Make Meaningful Distinctions（做出有意义的区分）（72）
			5. Use Pronounceable Names（使用容易发音的名字）（74）
			6. Use Searchable Names（使用可搜索的名称）（76）
			7. Avoid Encodings（避免编码）（78）
				1. Hungarian Notation（匈牙利表示法）（78）
				2. Member Prefixes（会员前缀）（79）
				3. Interfaces and Implementations（接口和实现）（79）
			8. Avoid Mental Mapping（避免心理映射）（81）
			9. Class Names（类名）（82）
			10. Method Names（方法名称）（83）
			11. Don’t Be Cute（别可爱）（84）
			12. Pick One Word per Concept（每个概念选择一个单词）（85）
			13. Don’t Pun（不要双关语）（86）
			14. Use Solution Domain Names（使用解决方案域名）（87）
			15. Use Problem Domain Names（使用有问题的域名）（88）
			16. Add Meaningful Context（添加有意义的上下文）（89）
			17. Don’t Add Gratuitous Context（不要添加无端的上下文）（92）
			18. Final Words（最后的话）（93）
		3. Functions（函数）（94）
			1. Small!（小的！）（98）
				1. Blocks and Indenting（块和缩进）（99）
			2. Do One Thing（做一件事）（100）
				1. Sections within Functions（函数内的部分）（102）
			3. One Level of Abstraction per Function（每个函数一个抽象级别）（103）
				1. Reading Code from Top to Bottom: The Stepdown Rule（从上到下阅读代码：递减规则）（103）
			4. Switch Statements（Switch  语句）（105）
			5. Use Descriptive Names（使用描述性名称）（108）
			6. Function Arguments（函数参数）（110）
				1. Common Monadic Forms（常见的一元形式）（111）
				2. Flag Arguments（标记参数）（112）
				3. Dyadic Functions（二元函数）（112）
				4. Triads（三合会）（113）
				5. Argument Objects（参数对象）（114）
				6. Argument Lists（参数列表）（114）
				7. Verbs and Keywords（动词和关键词）（115）
			7. Have No Side Effects（无副作用）（116）
				1. Output Arguments（输出参数）（117）
			8. Command Query Separation（命令查询分离）（119）
			9. Prefer Exceptions to Returning Error Codes（优先选择异常而不是返回错误代码）（120）
				1. Extract Try/Catch Blocks（提取  Try/Catch  块）（121）
				2. Error Handling Is One Thing（错误处理是一回事）（122）
				3. The Error.java Dependency Magnet（Error.java依赖磁石）（122）
			10. Don’t Repeat Yourself（不要重复自己的话）（124）
			11. Structured Programming（结构化编程）（125）
			12. How Do You Write Functions Like This?（你如何编写这样的函数？）（126）
			13. Conclusion（结论）（127）
			14. SetupTeardownIncluder（安装程序拆卸包含程序）（128）
		4. Comments（注释）（133）
			1. Comments Do Not Make Up for Bad Code（注释并不能弥补糟糕的代码）（136）
			2. Explain Yourself in Code（用代码解释自己）（137）
			3. Good Comments（好的注释）（138）
				1. Legal Comments（法律注释）（138）
				2. Informative Comments（内容丰富的注释）（138）
				3. Explanation of Intent（意图解释）（139）
				4. Clarification（澄清）（140）
				5. Warning of Consequences（后果警告）（141）
				6. TODO Comments（待办事项注释）
				7. Amplification（放大）（143）
				8. Javadocs in Public APIs（公共  API  中的  Javadoc）（144）
			4. Bad Comments（坏的注释）
				1. Mumbling（咕哝着）（145）
				2. Redundant Comments（多余的注释）（146）
				3. Misleading Comments（误导性注释）（150）
				4. Mandated Comments（强制注释）（150）
				5. Journal Comments（期刊注释）（151）
				6. Noise Comments（噪音注释）（152）
				7. Scary Noise（可怕的噪音）（155）
				8. Don’t Use a Comment When You Can Use a Function or a Variable（当可以使用函数或变量时不要使用注释）（155）
				9. Position Markers（位置标记）（156）
				10. Closing Brace Comments（右大括号注释）（156）
				11. Attributions and Bylines（归属和署名）（157）
				12. Commented-Out Code（注释掉的代码）（158）
				13. HTML Comments（HTML  注释）（159）
				14. Nonlocal Information（非本地信息）（160）
				15. Too Much Information（太多信息）（160）
				16. Inobvious Connection（不明显的联系）（161）
				17. Function Headers（函数头）（162）
				18. Javadocs in Nonpublic Code（非公共代码中的  Javadoc）（162）
				19. Example（例子）（162）
		5. Formatting（格式化）（169）
			1. The Purpose of Formatting（格式化的目的）（170）
			2. Vertical Formatting（垂直格式）（171）
				1. The Newspaper Metaphor（报纸的隐喻）（172）
				2. Vertical Openness Between Concepts（概念之间的垂直开放性）（173）
				3. Vertical Density（垂直密度）（175）
				4. Vertical Distance（垂直距离）（176）
				5. Vertical Ordering（垂直排序）（183）
			3. Horizontal Formatting（水平格式）（184）
				1. Horizontal Openness and Density（水平开放度和密度）（185）
				2. Horizontal Alignment（水平对齐）（186）
				3. Indentation（缩进）（188）
				4. Dummy Scopes（虚拟瞄准镜）（191）
			4. Team Rules（团队规则）（192）
			5. Uncle Bob’s Formatting Rules（鲍勃叔叔的格式规则）（193）
		6. Objects and Data Structures（对象和数据结构）（196）
			1. Data Abstraction（数据抽象）（196）
			2. Data/Object Anti-Symmetry（数据/对象反对称）（199）
			3. The Law of Demeter（得墨忒尔法则）（203）
				1. Train Wrecks（火车残骸）（203）
				2. Hybrids（杂交种）（205）
				3. Hiding Structure（隐藏结构）（205）
			4. Data Transfer Objects（数据传输对象）（207）
				1. Active Record（活动记录）（208）
			5. Conclusion（结论）（209）
		7. Error Handling（错误处理）（211）
			1. Use Exceptions Rather Than Return Codes（使用异常而不是返回代码）（213）
			2. Write Your Try-Catch-Finally Statement First（写你的尝试‑捕获‑最终首先声明）（216）
			3. Use Unchecked Exceptions（使用未经检查的异常）（218）
			4. Provide Context with Exceptions（提供带有异常的上下文）（220）
			5. Define Exception Classes in Terms of a Caller’s Needs（根据调用者的需求定义异常类）（221）
			6. Define the Normal Flow（定义正常流程）（224）
			7. Don’t Return Null（不要返回空值）（226）
			8. Don’t Pass Null（不要传递空值）（228）
			9. Conclusion（结论）（230）
		8. Boundaries（边界）（232）
			1. Using Third-Party Code（使用第三方代码）（233）
			2. Exploring and Learning Boundaries（探索和学习边界）（236）
			3. Learning log4j（学习log4j）（237）
			4. Learning Tests Are Better Than Free（学习测试比免费更好）（240）
			5. Using Code That Does Not Yet Exist（使用尚不存在的代码）（241）
			6. Clean Boundaries（清晰的边界）（243）
		9. Unit Tests（单元测试）（245）
			1. The Three Laws of TDD（TDD  三大定律）（248）
			2. Keeping Tests Clean（保持测试干净）（249）
				1. Tests Enable the -ilities（测试启用功能）（250）
			3. Clean Tests（清洁测试）（252）
				1. Domain-Specific Testing Language（特定领域的测试语言）（256）
				2. A Dual Standard（双重标准）（256）
			4. One Assert per Test（每个测试一个断言）（260）
				1. Single Concept per Test（每次测试单一概念）（261）
			5. F.I.R.S.T.（264）
			6. Conclusion（结论）（266）
		10. Classes（类）
			1. Class Organization（类组织）（270）
				1. Encapsulation（封装）（270）
			2. Classes Should Be Small!（类应该是小类）（271）
				1. The Single Responsibility Principle（单一责任原则）（274）
				2. Cohesion（凝聚）（276）
				3. Maintaining Cohesion Results in Many Small Classes（在许多小类中保持凝聚力）（277）
			3. Organizing for Change（组织变革）（287）
				1. Isolating from Change（远离变化）（290）
		11. Systems（系统）（294）
			1. How Would You Build a City?（你会如何建造一座城市？）（296）
			2. Separate Constructing a System from Using It（将构建系统与使用系统分开）（297）
				1. Separation of Main（主分离）（298）
				2. Factories（工厂）（299）
				3. Dependency Injection（依赖注入）（300）
			3. Scaling Up（扩大）（303）
				1. Cross-Cutting Concerns（307）
			4. Java Proxies（Java代理）（309）
			5. Pure Java AOP Frameworks（纯  Java  AOP  框架）（312）
			6. AspectJ Aspects（AspectJ  方面）（317）
			7. Test Drive the System Architecture（测试系统架构）（318）
			8. Optimize Decision Making（优化决策）（320）
			9. Use Standards Wisely, When They Add Demonstrable Value（当标准增加可证明的价值时，明智地使用标准）（321）
			10. Systems Need Domain-Specific Languages（系统需要特定领域的语言）（322）
			11. Conclusion（结论）（323）
		12. Emergence（紧急情况）（327）
			1. Getting Clean via Emergent Design（通过紧急设计实现清洁）（372）
			2. Simple Design Rule 1: Runs All the Tests（简单设计规则  1：运行所有测试）（328）
			3. Simple Design Rules 2–4: Refactoring（简单设计规则  2‑4：重构）（329）
			4. No Duplication（无重复）（330）
			5. Expressive（富有表现力）（334）
			6. Minimal Classes and Methods（最少的类和方法）（336）
			7. Conclusion（结论）（337）
		13. Concurrency（并发性）（339）
			1. Why Concurrency?（为什么要并发？）（341）
				1. Myths and Misconceptions（神话和误解）（342）
			2. Challenges（挑战）（344）
			3. Concurrency Defense Principles（并发防御原则）（346）
				1. Single Responsibility Principle（单一责任原则）（346）
				2. Corollary: Limit the Scope of Data（推论：限制数据范围）（347）
				3. Corollary: Use Copies of Data（推论：使用数据副本）（347）
				4. Corollary: Threads Should Be as Independent as Possible（推论：线程应该尽可能独立）（347）
			4. Know Your Library（了解你的图书馆）（349）
				1. Thread-Safe Collections（线程安全集合）（349）
			5. Know Your Execution Models（了解你的执行模型）（351）
				1. Producer-Consumer（生产者‑消费者）（351）
				2. Readers-Writers（读取器-写入器）（352）
				3. Dining Philosophers（哲学家用餐）（352）
			6. Beware Dependencies Between Synchronized Methods（注意同步方法之间的依赖关系）（354）
			7. Keep Synchronized Sections Small（保持同步部分较小）（355）
			8. Writing Correct Shut-Down Code Is Hard（编写正确的关闭代码很困难）（356）
			9. Testing Threaded Code（测试线程代码）（357）
				1. Treat Spurious Failures as Candidate Threading Issues（将虚假故障视为候选线程问题）（357）
				2. Get Your Nonthreaded Code Working First（首先让您的非线程代码正常工作）（358）
				3. Make Your Threaded Code Pluggable（使您的线程代码可插入）（358）
				4. Make Your Threaded Code Tunable（使您的线程代码可调）（359）
				5. Run with More Threads Than Processors（使用比处理器更多的线程运行）（259）
				6. Run on Different Platforms（在不同平台上运行）（359）
				7. Instrument Your Code to Try and Force Failures（检测您的代码以尝试并强制失败）（360）
				8. Hand-Coded（手工编码）（361）
				9. Automated（自动化）（362）
			10. Conclusion（结论）（364）
		14. Successive Refinement（精益求精）（370）
			1. Args Implementation（参数实现）（376）
				1. How Did I Do This?（我是怎么做到的？）（378）
			2. Args: The Rough Draft（参数：草稿）（380）
				1. So I Stopped（所以我停了下来）（397）
				2. On Incrementalism（论渐进主义）（397）
			3. String Arguments（字符串参数）（401）
			4. Conclusion（结论）（456）
		15. JUnit Internals（JUnit  内部结构）（457）
			1. The JUnit Framework（JUnit  框架）（458）
			2. Conclusion（结论）（478）
		16. Refactoring SerialDate（重构序列日期）（479）
			1. First, Make It Work（首先，让它发挥作用）（481）
			2. Then Make It Right（然后改正）（484）
			3. Conclusion（结论）（505）
		17. Smells and Heuristics（气味和启发法）（507）
			1. Comments（注释）（508）
				1. C1: Inappropriate Information（C1：不当信息）（508）
				2. C2: Obsolete Comment（C2：过时的注释）（508）
				3. C3: Redundant Comment（C3：多余的注释）（508）
				4. C4: Poorly Written Comment（C4：注释写得不好）（509）
				5. C5: Commented-Out Code（C5：注释掉的代码）（509）
			2. Environment（环境）（511）
				1. E1: Build Requires More Than One Step（E1：构建需要多个步骤）（511）
				2. E2: Tests Require More Than One Step（E2：测试需要多个步骤）（511）
			3. Functions（函数）（512）
				1. F1: Too Many Arguments（F1：参数太多）（512）
				2. F2: Output Arguments（F2：输出参数）（512）
				3. F3: Flag Arguments（F3：标记参数）（512）
				4. F4: Dead Function（F4：死函数）（512）
			4. General（一般的）（513）
				1. G1: Multiple Languages in One Source File（G1：一个源文件中的多种语言）（513）
				2. G2: Obvious Behavior Is Unimplemented（G2：明显的行为未实现）（513）
				3. G3: Incorrect Behavior at the Boundaries（G3：边界处的不正确行为）（514）
				4. G4: Overridden Safeties（G4：超越安全性）（514）
				5. G5: Duplication（G5：复制）（515）
				6. G6: Code at Wrong Level of Abstraction（G6：抽象级别错误的代码）（516）
				7. G7: Base Classes Depending on Their Derivatives（G7：基类取决于其派生类）（517）
				8. G8: Too Much Information（G8：信息太多）（518）
				9. G9: Dead Code（G9：死代码）（518）
				10. G10: Vertical Separation（G10：垂直分离）（519）
				11. G11: Inconsistency（G11：不一致）（519）
				12. G12: Clutter（G12：杂乱）（520）
				13. G13: Artificial Coupling（G13：人工耦合）（520）
				14. G14: Feature Envy（G14：功能羡慕）（520）
				15. G15: Selector Arguments（G15：选择器参数）（522）
				16. G16: Obscured Intent（G16：模糊的意图）（523）
				17. G17: Misplaced Responsibility（G17：错误的责任）（524）
				18. G18: Inappropriate Static（G18：不适当的静电）（524）
				19. G19: Use Explanatory Variables（G19：使用解释变量）（525）
				20. G20: Function Names Should Say What They Do（G20：函数名称应该说明它们的作用）（526）
				21. G21: Understand the Algorithm（G21：理解算法）（526）
				22. G22: Make Logical Dependencies Physical（G22：使逻辑依赖成为物理依赖）（527）
				23. G23: Prefer Polymorphism to If/Else or Switch/Case（G23：比起  If/Else  或  Switch/Case  更喜欢多态）（529）
				24. G24: Follow Standard Conventions（G24：遵循标准约定）（530）
				25. G25: Replace Magic Numbers with Named Constants（G25：用命名常量替换幻数）（530）
				26. G26: Be Precise（G26：精确）（532）
				27. G27: Structure over Convention（G27：结构优于惯例）（533）
				28. G28: Encapsulate Conditionals（G28：封装条件）（533）
				29. G29: Avoid Negative Conditionals（G29：避免否定条件）（533）
				30. G30: Functions Should Do One Thing（G30：函数应该做一件事）（534）
				31. G31: Hidden Temporal Couplings（G31：隐藏的时间耦合）（535）
				32. G32: Don’t Be Arbitrary（G32：不要武断）（536）
				33. G33: Encapsulate Boundary Conditions（G33：封装边界条件）（537）
				34. G34: Functions Should Descend Only One Level of Abstraction（G34：函数应该仅下降一层抽象）（538）
				35. G35: Keep Configurable Data at High Levels（G35：将可配置数据保持在高水平）（540）
				36. G36: Avoid Transitive Navigation（G36：避免传递导航）（541）
			5. Java（542）
				1. J1: Avoid Long Import Lists by Using Wildcards（J1：使用通配符避免长导入列表）（542）
				2. J2: Don’t Inherit Constants（J2：不要继承常量）（543）
				3. J3: Constants versus Enums（J3：常量与枚举）（544）
			6. Names（名称）（546）
				1. N1: Choose Descriptive Names（N1：选择描述性名称）（546）
				2. N2: Choose Names at the Appropriate Level of Abstraction（N2：在适当的抽象级别选择名称）（548）
				3. N3: Use Standard Nomenclature Where Possible（N3：尽可能使用标准术语）（549）
				4. N4: Unambiguous Names（N4：明确的名称）（549）
				5. N5: Use Long Names for Long Scopes（N5：为长范围使用长名称）（550）
				6. N6: Avoid Encodings（N6：避免编码）（551）
				7. N7: Names Should Describe Side-Effects（N7：名称应描述副作用）（551）
			7. Tests（测试）（552）
				1. T1: Insufficient Tests（T1：测试不充分）（552）
				2. T2: Use a Coverage Tool!（T2：使用覆盖工具！）（552）
				3. T3: Don’t Skip Trivial Tests（T3：不要跳过琐碎的测试）（552）
				4. T4: An Ignored Test Is a Question about an Ambiguity（T4：被忽略的测试是一个关于歧义的问题）（552）
				5. T5: Test Boundary Conditions（T5：测试边界条件）（553）
				6. T6: Exhaustively Test Near Bugs（T6：彻底测试附近的错误）（553）
				7. T7: Patterns of Failure Are Revealing（T7：失败模式正在显现）（553）
				8. T8: Test Coverage Patterns Can Be Revealing（T8：测试覆盖率模式具有启发性）（553）
				9. T9: Tests Should Be Fast（T9：测试应该很快）（554）
			8. Conclusion（结论）（555）
		18. Appendix A Concurrency II（附录 A 并发 II）（557）
			1. Client/Server Example（客户端/服务器示例）（558）
				1. The Server（服务器）（558）
				2. Adding Threading（添加线程）（560）
				3. Server Observations（服务器观察）（561）
				4. Conclusion（结论）（564）
			2. Possible Paths of Execution（可能的执行路径）（564）
				1. Number of Paths（路径数）（566）
				2. Digging Deeper（深层发掘）（568）
				3. Conclusion（结论）（571）
			3. Knowing Your Library（了解你的图书馆）（573）
				1. Executor Framework（执行器框架）（573）
				2. Nonblocking Solutions（非阻塞解决方案）（574）
				3. Nonthread-Safe Classes（非线程安全类）（576）
			4. Dependencies Between Methods Can Break Concurrent Code（方法之间的依赖关系可能会破坏并发代码）（578）
				1. Tolerate the Failure（容忍失败）（579）
				2. Client-Based Locking（基于客户端的锁定）（579）
				3. Server-Based Locking（基于服务器的锁定）（582）
			5. Increasing Throughput（提高吞吐量）（585）
				1. Single-Thread Calculation of Throughput（单线程吞吐量计算）（586）
				2. Multithread Calculation of Throughput（多线程吞吐量计算）（587）
			6. Deadlock（死锁）
				1. Mutual Exclusion（相互排斥）（590）
				2. Lock & Wait（锁定并等待）（591）
				3. No Preemption（无抢占）（591）
				4. Circular Wait（循环等待）（591）
				5. Breaking Mutual Exclusion（打破相互排斥）（592）
				6. Breaking Lock & Wait（打破锁定并等待）（592）
				7. Breaking Preemption（打破抢占）（593）
				8. Breaking Circular Wait（打破循环等待）（593）
			7. Testing Multithreaded Code（测试多线程代码）（595）
			8. Tool Support for Testing Thread-Based Code（用于测试基于线程的代码的工具支持）（599）
			9. Conclusion（结论）（600）
			10. Tutorial: Full Code Examples（教程：完整代码示例）（601）
				1. Client/Server Nonthreaded（客户端/服务器非线程）（601）
				2. Client/Server Using Threads（使用线程的客户端/服务器）（606）
	8. Agile Software Development（敏捷软件开发）
		1. Agile Development（敏捷开发）（8）
			1. Agile Practices（敏捷实践）（10）
				1. The Agile Alliance（敏捷联盟）（11）
				2. Principles（原则）（13）
			2. Overview of Extreme Programming（极限编程概述）（18）
				1. The Practices of Extreme Programming（极限编程的实践）（18）
			3. Planning（规划）（26）
				1. Initial Exploration（初步探索）（27）
				2. Release Planning（发布计划）（27）
				3. Iteration Planning（迭代计划）（28）
				4. Task Planning（任务规划）（28）
				5. Iterating（迭代）（29）
			4. Testing（测试）（30）
				1. Test Driven Development（测试驱动开发）（30）
				2. Acceptance Tests（验收测试）（34）
			5. Refactoring（重构）（38）
				1. Generating Primes: A Simple Example of Refactoring（生成素数：重构的简单示例）（39）
			6. A Programming Episode（节目编排）（50）
				1. The Bowling Game（保龄球游戏）（51）
		2. Agile Design（敏捷设计）（92）
			1. What Is Agile Design?（什么是敏捷设计？）（94）
				1. What Goes Wrong with Software?（软件出了什么问题？）（94）
				2. Design Smells—The Odors of Rotting Software（设计气味——腐烂软件的气味）（95）
				3. The “Copy” Program（“复制”计划）（97）
				4. Keeping the Design As Good As It Can Be（保持设计尽可能好）（101）
			2. SRP: The Single-Responsibility Principle（SRP：单一职责原则）（102）
			3. OCP: The Open–Closed Principle（OCP：开闭原则）（106）
				1. Description（描述）（107）
				2. Abstraction Is the Key（抽象是关键）（107）
				3. The Shape Application（形状应用）（108）
			4. LSP: The Liskov Substitution Principle（LSP：里氏替换原则）（118）
				1. A Simple Example of a Violation of the LSP（违反 LSP 的简单示例）（119）
				2. Square and Rectangle, a More Subtle Violation（正方形和长方形，一种更微妙的违反）（120）
				3. A Real Example（一个真实的例子）（124）
				4. Factoring instead of Deriving（因式分解而不是推导）（128）
				5. Heuristics and Conventions（启发式和约定）（131）
			5. DIP: The Dependency-Inversion Principle（DIP：依赖倒置原则）（134）
				1. Layering（分层）（135）
				2. A Simple Example（一个简单的示例）（137）
				3. The Furnace Example（熔炉示例）（139）
			6. ISP: The Interface-Segregation Principle（ISP：接口隔离原则）（142）
				1. Interface Pollution（界面污染）（142）
				2. Separate Clients Mean Separate Interfaces（单独的客户端意味着单独的接口）（144）
				3. ISP: The Interface-Segregation Principle（ISP：接口隔离原则）（144）
				4. Class Interfaces v. Object Interfaces（类接口与对象接口）（145）
				5. The ATM User Interface Example（ATM 用户界面示例）（146）
		3. The Payroll Case Study（薪资案例研究）（154）
			1. COMMAND and ACTIVE OBJECT（命令和活动对象）（158）
				1. Simple Commands（简单命令）（159）
				2. Transactions（交易）（160）
				3. ACTIVE OBJECT（主动对象）（162）
			2. TEMPLATE METHOD & STRATEGY: Inheritance vs. Delegation（模板方法和策略：继承与委托）（168）
				1. TEMPLATE METHOD（模板法）（169）
				2. STRATEGY（战略）（175）
			3. FACADE and MEDIATOR（外观和中介）（180）
				1. FACADE（正面）（180）
				2. MEDIATOR（调解员）（181）
			4. SINGLETON and MONOSTATE（单例和单态）（184）
				1. SINGLETON（单例）（185）
				2. MONOSTATE（单态）（187）
			5. NULL OBJECT（空对象）（196）
			6. The Payroll Case Study: Iteration One Begins（薪资案例研究：第一轮迭代开始）（200）
				1. Introduction（介绍）（200）
				2. Analysis by Use Cases（按用例分析）（201）
				3. Reflection: What Have We Learned?（反思：我们学到了什么？）（208）
				4. Finding the Underlying Abstractions（寻找底层抽象）（208）
			7. The Payroll Case Study: Implementation（薪资案例研究：实施）（212）
				1. Adding Employees（添加员工）（213）
				2. Deleting Employees（删除员工）（219）
				3. Time Cards, Sales Receipts, and Service Charges（考勤卡、销售收据和服务费）（221）
				4. Changing Employees（更换员工）（227）
				5. Paying Employees（支付员工工资）（240）
				6. Main Program（主程序）（255）
				7. The Database（数据库）（255）
				8. Summary of Payroll Design（薪资设计概要）（256）
		4. Packaging the Payroll System（打包薪资系统）（258）
			1. Principles of Package Design（包装设计原则）（260）
				1. Designing with Packages?（使用包进行设计？）（260）
				2. Granularity: The Principles of Package Cohesion（粒度：包内聚性的原则）（261）
				3. Stability: The Principles of Package Coupling（稳定性：封装耦合的原理）（263）
				4. Top-Down Design（自上而下的设计）（267）
				5. The Stable-Dependencies Principle (SDP)（稳定依赖原则  (SDP)）（268）
				6. The Stable-Abstractions Principle (SAP)（稳定抽象原则  (SAP)）（271）
			2. FACTORY（工厂）（276）
				1. A Dependency Cycle（依赖循环）（278）
				2. Substitutable Factories（可替代工厂）（279）
				3. Using Factories for Test Fixtures（使用工厂作为测试夹具）（280）
				4. How Important Is It to Use Factories?（使用工厂有多重要？）（281）
			3. The Payroll Case Study (Part 2)（薪资案例研究（第  2  部分））（282）
				1. Package Structure and Notation（包结构和符号）（283）
				2. Applying the Common-Closure Principle (CCP)（应用公共闭合原则  (CCP)）（284）
				3. Applying the Reuse–Release Equivalency Principle (REP)（应用重用‑发布等效原则  (REP)）（285）
				4. Coupling and Encapsulation（耦合与封装）（286）
				5. Metrics（指标）（288）
				6. Applying the Metrics to the Payroll Application（将指标应用于薪资应用程序）（289）
				7. The Final Package Structure（最终的封装结构）（294）
		5. The Weather Station Case Study（气象站案例研究）（298）
			1. COMPOSITE（合成的）（300）
				1. Example: Composite Commands（示例：复合命令）（301）
				2. Multiplicity or Not Multiplicity（多重性或非多重性）（302）
			2. OBSERVER—Backing into a Pattern（观察者——回归模式）（304）
				1. The Digital Clock（数字时钟）（304）
				2. Conclusion（结论）（321）
				3. The OBSERVER Pattern（观察者模式）（322）
			3. ABSTRACT SERVER, ADAPTER, and BRIDGE（抽象服务器、适配器和网桥）（324）
				1. ABSTRACT SERVER（抽象服务器）（325）
				2. Adapter（适配器）（326）
				3. BRIDGE（桥）（329）
			4. PROXY and STAIRWAY TO HEAVEN: Managing Third Party APIs（代理和天堂的阶梯：管理第三方 API）（334）
				1. PROXY（代理人）（334）
				2. STAIRWAY TO HEAVEN（天堂的阶梯）（354）
				3. Other Patterns That Can Be Used with Databases（可与数据库一起使用的其他模式）（360）
			5. Case Study: Weather Station（案例研究：气象站）（362）
				1. The Cloud Company（云公司）（362）
				2. Nimbus-LC Software Design（Nimbus-LC 软件设计）（364）
				3. Nimbus-LC Requirements Overview（Nimbus-LC 要求概述）（386）
				4. Nimbus-LC Use Cases（Nimbus‑LC  用例）（387）
				5. Nimbus-LC Release Plan（Nimbus‑LC  发布计划）（388）
		6. The ETS Case Study（ETS  案例研究）（392）
			1. VISITOR（游客）（394）
				1. The VISITOR Family of Design Patterns（VISITOR 设计模式系列）（395）
				2. VISITOR（访客）（395）
				3. ACYCLIC VISITOR（非循环访问者）（398）
				4. DECORATOR（装饰器）（410）
				5. EXTENSION OBJECT（扩展对象）（415）
			2. STATE（状态）（426）
				1. Overview of Finite State Automata（有限状态自动机概述）（426）
				2. Implementation Techniques（实施技术）（428）
				3. The STATE Pattern（状态模式）（433）
				4. Where Should State Machines Be Used?（状态机应该用在哪里？）（439）
				5. High-Level Application Policies for GUIs（GUI 的高级应用程序策略）（439）
				6. Conclusion（结论）（441）
				7. Listings（列表）（441）
			3. The ETS Framework（ETS框架）（450）
				1. Introduction（介绍）（450）
				2. Framework!（框架！）（453）
				3. Framework Design（框架设计）（455）
				4. A Case for TEMPLATE METHOD（模板方法案例）（460）
	9. Design Patterns（设计模式）
		1. Introduction（简介）（19）
			1. What Is a Design Pattern?（什么是设计模式？）（20）
			2. Design Patterns in Smalltalk MVC（Smalltalk  MVC  中的设计模式）（22）
			3. Describing Design Patterns（描述设计模式）（24）
				1. Pattern Name and Classification（模式名称及分类）（24）
				2. Intent（意图）（24）
				3. Also Known As（也称为）（24）
				4. Motivation（动机）（25）
				5. Applicability（适用性）（25）
				6. Structure（结构）（25）
				7. Participants（参加者）（25）
				8. Collaborations（合作）（25）
				9. Consequences（结果）（25）
				10. Implementation（执行）（25）
				11. Sample Code（示例代码）（26）
				12. Known Uses（已知用途）（26）
				13. Related Patterns（相关模式）（26）
			4. The Catalog of Design Patterns（设计模式目录）（26）
			5. Organizing the Catalog（组织目录）（28）
			6. How Design Patterns Solve Design Problems（设计模式如何解决设计问题）（30）
				1. Finding Appropriate Objects（寻找合适的对象）（30）
				2. Determining Object Granularity（确定对象粒度）（31）
				3. Specifying Object Interfaces（指定对象接口）（32）
				4. Specifying Object Implementations（指定对象实现）（33）
				5. Class versus Interface Inheritance（类继承与接口继承）（35）
				6. Programming to an Interface, not an Implementation（针对接口而非实现进行编程）（36）
				7. Putting Reuse Mechanisms to Work（让重用机制发挥作用）（37）
				8. Inheritance versus Composition（继承与组合）（38）
				9. Delegation（代表团）（39）
				10. Inheritance versus Parameterized Types（继承与参数化类型）（41）
				11. Relating Run-Time and Compile-Time Structures（关联运行时和编译时结构）（42）
				12. Designing for Change（为变革而设计）（43）
				13. Application Programs（应用程序）（45）
				14. Toolkits（工具包）（46）
				15. Frameworks（构架）（46）
			7. How to Select a Design Pattern（如何选择设计模式）（48）
			8. How to Use a Design Pattern（如何使用设计模式）（50）
		2. A Case Study: Designing a Document Editor（案例研究：设计文档编辑器）（52）
			1. Design Problems（设计问题）（53）
			2. Document Structure（文档结构）（54）
				1. Recursive Composition（递归组合）（55）
				2. Glyphs（字形）（57）
				3. Composite Pattern（复合图案）（58）
			3. Formatting（格式化）（58）
				1. Encapsulating the Formatting Algorithm（封装格式化算法）（59）
				2. Compositor and Composition（合成器和合成）（60）
				3. Strategy Pattern（策略）（61）
			4. Embellishing the User Interface（美化用户界面）（62）
				1. Transparent Enclosure（透明外壳）（62）
				2. Monoglyph（独字形）（63）
				3. Decorator Pattern（装饰模式）（65）
			5. Supporting Multiple Look-and-Feel Standards（支持多种外观标准）（65）
				1. Abstracting Object Creation（抽象对象创建）（66）
				2. Factories and Product Classes（工厂和产品类别）（66）
				3. Abstract Factory Pattern（抽象工厂模式）（69）
			6. Supporting Multiple Window Systems（支持多窗口系统）（69）
				1. Can We Use an Abstract Factory?（69）
				2. Encapsulating Implementation Dependencies（封装实现依赖关系）（70）
				3. Window and WindowImp（窗口和WindowImp）（72）
				4. WindowImp Subclasses（WindowImp  子类）（73）
				5. Configuring Windows with WindowImps（使用  WindowImps  配置  Windows）（75）
				6. Bridge Pattern（桥梁图案）（76）
			8. User Operations（用户操作）（76）
				1. Encapsulating a Request（封装请求）（77）
				2. Command Class and Subclasses（命令类和子类）（78）
				3. Undoability（可撤销性）（79）
				4. Command History（命令历史）（80）
				5. Command Pattern（命令模式）（81）
			9. Spelling Checking and Hyphenation（拼写检查和连字符）（82）
				1. Accessing Scattered Information（访问分散的信息）（82）
				2. Encapsulating Access and Traversal（封装访问和遍历）（82）
				3. Iterator Class and Subclasses（迭代器类和子类）（84）
				4. Iterator Pattern（迭代器模式）（87）
				5. Traversal versus Traversal Actions（遍历与遍历动作）（87）
				6. Encapsulating the Analysis（封装分析）（88）
				7. Visitor Class and Subclasses（访客类别和子类别）（91）
				8. Visitor Pattern（访客模式）（93）
			10. Summary（总结）（93）
		3. Creational Patterns（创作模式）（96）
			1. Object Creational: Abstract Factory（对象创建：抽象工厂）（100）
			2. Object Creational: Builder（对象创建：生成器）（109）
			3. Class Creational: Factory Method（类创建：工厂方法）（118）
			4. Object Creational: Prototype（对象创建：原型）（129）
			5. Object Creational: Singleton（对象创建：单例）（138）
			6. Discussion of Creational Patterns（创作模式探讨）（146）
		4. Structural Patterns（结构模式）（148）
			1. Class, Object Structural: Adapter（类、对象结构：适配器）（149）
			2. Object Structural: Bridge（对象结构：桥接）（160）
			3. Object Structural: Composite（对象结构：组合）（170）
			4. Object Structural: Decorator（对象结构：装饰器）（182）
			5. Object Structural: Facade（对象结构：外观）（192）
			6. Object Structural: Flyweight（对象结构：享元）（201）
			7. Object Structural: Proxy（对象结构：代理）（212）
			8. Discussion of Structural Patterns（结构模式的讨论）（223）
				1. Adapter versus Bridge（适配器与桥接器）（223）
				2. Composite versus Decorator versus Proxy（组合、装饰器、代理）（224）
		5. Behavioral Patterns（行为模式）（226）
			1. Object Behavioral: Chain of Responsibility（对象行为：责任链）（227）
			2. Object Behavioral: Command（对象行为：命令）（237）
			3. Class Behavioral: Interpreter（类行为：口译员）（247）
			4. Object Behavioral: Iterator（对象行为：迭代器）（260）
			5. Object Behavioral: Mediator（对象行为：中介者）（275）
			6. Object Behavioral: Memento（对象行为：备忘录）（285）
			7. Object Behavioral: Observer（对象行为：观察者）（294）
			8. Object Behavioral: State（对象行为：状态）（305）
			9. Object Behavioral: Strategy（对象行为：策略）（314）
			10. Class Behavioral: Template Method（类行为：模板方法）（323）
			11. Object Behavioral: Visitor（对象行为：访问者）（329）
			12. Discussion of Behavioral Patterns（行为模式的讨论）（343）
				1. Encapsulating Variation（封装变化）（343）
				2. Objects as Arguments（对象作为参数）（344）
				3. Should Communication be Encapsulated or Distributed?（通信应该封装还是分布式？）（344）
				4. Decoupling Senders and Receivers（发送者和接收者的解耦）（345）
				5. Summary（概括）（347）
		6. Conclusion（结论）（149）
			1. What to Expect from Design Patterns（对设计模式的期望）（349）
				1. A Common Design Vocabulary（通用设计词汇）（349）
				2. A Documentation and Learning Aid（文档和学习辅助工具）（350）
				3. An Adjunct to Existing Methods（现有方法的补充）（350）
				4. A Target for Refactoring（重构的目标）（351）
			2. A Brief History（简史）（353）
			3. The Pattern Community（模式社区）（354）
				1. Alexander’s Pattern Languages（亚历山大的模式语言）（354）
				2. Patterns in Software（软件中的模式）（355）
			4. An Invitation（邀请）（356）
			5. A Parting Thought（临别思考）（356）
4. Mathematics for Game Programming（游戏程序员的数学课）
	1. Mathematics for 3D Game Programming and Computer Graphics（3D游戏与计算机图形学中的数学方法）
		1. The Rendering Pipeline（渲染管线）（20）
			1. Graphics Processors（图形处理器）（20）
			2. Vertex Transformation（顶点变换）（23）
			3. Rasterization and Fragment Operations（光栅化和片段操作）（26）
		2. Vectors（向量）（30）
			1. Vector Properties（向量属性）（30）
			2. The Dot Product（点积）（34）
			3. The Cross Product（叉积）（38）
			4. Vector Spaces（向量空间）（45）
			5. Chapter 2 Summary（第二章小结）（48）
		3. Matrices（矩阵）（50）
			1. Matrix Properties（矩阵性质）（50）
			2. Linear Systems（线性系统）（53）
			3. Matrix Inverses（矩阵逆）（59）
			4. Determinants（决定因素）（66）
			5. Eigenvalues and Eigenvectors（特征值和特征向量）（73）
			6. Diagonalization（对角化）（77）
			7. Chapter 3 Summary（第三章小结）（81）
		4. Transforms（变换）（86）
			1. Linear Transformations（线性变换）（86）
				1. Orthogonal Matrices（正交矩阵）（87）
				2. Handedness（惯用手）（89）
			2. Scaling Transforms（缩放变换）（89）
			3. Rotation Transforms（旋转变换）（90）
				1. Rotation About an Arbitrary Axis（绕任意轴旋转）（93）
			4. Homogeneous Coordinates（齐次坐标）（94）
				1. Four-Dimensional Transforms（四维变换）（95）
				2. Points and Directions（点和方向）（97）
				3. Geometrical Interpretation of the w Coordinate（w坐标）（97）
			5. Transforming Normal Vectors（变换法向量）（97）
			6. Quaternions（四元数）（99）
				1. Quaternion Mathematics（四元数数学）（99）
				2. Rotations with Quaternions（四元数旋转）（101）
				3. Spherical Linear Interpolation（球面线性插值）（105）
			7. Chapter 4 Summary（第四章总结）（108）
		5. Geometry for 3D Engines（3D  引擎的⼏何结构）（112）
			1. Lines in 3D Space（3D空间中的线）（112）
				1. Distance Between a Point and a Line（点与线之间的距离）（112）
				2. Distance Between Two Lines（两条线之间的距离）（113）
			2. Planes in 3D Space（3D空间中的平面）（116）
				1. Intersection of a Line and a Plane（直线与平面的交点）（117）
				2. Intersection of Three Planes（三个平面的交点）（118）
				3. Transforming Planes（变换平面）（120）
			3. The View Frustum（视锥体）（121）
				1. Field of View（视野）（122）
				2. Frustum Planes（截锥体平面）（125）
			4. Perspective-Correct Interpolation（透视校正插值）（126）
				1. Depth Interpolation（深度插值）（127）
				2. Vertex Attribute Interpolation（顶点属性插值）（129）
			5. Projections（预测）（130）
				1. Perspective Projections（透视投影）（131）
				2. Orthographic Projections（正交投影）（135）
				3. Extracting Frustum Planes（提取截锥体平面）（137）
			6. Reflections and Oblique Clipping（反射和倾斜裁剪）（139）
			7. Chapter 5 Summary（第五章总结）（145）
		6. Ray Tracing（光线追踪）（150）
			1. Root Finding（求根）（150）
				1. Quadratic Polynomials（二次多项式）（151）
				2. Cubic Polynomials（三次多项式）（151）
				3. Quartic Polynomials（四次多项式）（154）
				4. Newton’s Method（牛顿法）（155）
				5. Refinement of Reciprocals and Square Roots（倒数和平方根的细化）（158）
			2. Surface Intersections（曲面相交）（159）
				1. Intersection of a Ray and a Triangle（射线与三角形的交点）（160）
				2. Intersection of a Ray and a Box（射线与盒子的交集）（162）
				3. Intersection of a Ray and a Sphere（射线与球体的交集）（163）
				4. Intersection of a Ray and a Cylinder（射线与圆柱的交点）（164）
				5. Intersection of a Ray and a Torus（射线和环面的交点）（166）
			3. Normal Vector Calculation（法向量计算）（167）
			4. Reflection and Refraction Vectors（反射和折射矢量）（168）
				1. Reflection Vector Calculation（反射矢量计算）（169）
				2. Refraction Vector Calculation（折射矢量计算）（170）
			5. Chapter 6 Summary（第六章总结）（172）
		7. Lighting and Shading（照明和阴影）（176）
			1. RGB Color（RGB颜色）（176）
			2. Light Sources（光源）（177）
				1. Ambient Light（环境光）（177）
				2. Directional Light Sources（定向光源）（178）
				3. Point Light Sources（点光源）（178）
				4. Spot Light Sources（聚光光源）（179）
			3. Diffuse Reflection（漫反射）（180）
			4. Specular Reflection（镜面反射）（181）
			5. Texture Mapping（纹理映射）（183）
				1. Standard Texture Maps（标准纹理贴图）（185）
				2. Projective Texture Maps（投影纹理贴图）（186）
				3. Cube Texture Maps（立方体纹理贴图）（188）
				4. Filtering and Mipmaps（过滤和  Mipmap）（190）
			6. Emission（排放）（193）
			7. Shading Models（着色模型）（194）
				1. Calculating Normal Vectors（计算法向量）（194）
				2. Gouraud Shading（高洛着色）（195）
				3. Blinn-Phong Shading（Blinn‑Phong  着色）（196）
			8. Bump Mapping（凹凸贴图）（197）
				1. Bump Map Construction（凹凸贴图构建）（197）
				2. Tangent Space（切线空间）（199）
				3. Calculating Tangent Vectors（计算切向量）（199）
				4. Implementation（实施）（204）
			9. A Physical Reflection Model（物理反射模型）（206）
				1. Bidirectional Reflectance Distribution Functions（双向反射率分布函数）（206）
				2. Cook-Torrance Illumination（库克‑托伦斯照明）（210）
				3. The Fresnel Factor（菲涅耳因子）（211）
				4. The Microfacet Distribution Function（微面分布函数）（214）
				5. The Geometrical Attenuation Factor（几何衰减因子）（217）
				6. Implementation（实施）（219）
			10. Chapter 7 Summary（第7章总结）（224）
		8. Visibility Determination（能见度测定）（230）
			1. Bounding Volume Construction（包围体构造）（230）
				1. Principal Component Analysis（主成分分析）（231）
				2. Bounding Box Construction（边界框构造）（234）
				3. Bounding Sphere Construction（边界球构造）（236）
				4. Bounding Ellipsoid Construction（边界椭球构造）（237）
				5. Bounding Cylinder Construction（边界圆柱体构造）（239）
			2. Bounding Volume Tests（包围体测试）（240）
				1. Bounding Sphere Test（边界球测试）（240）
				2. Bounding Ellipsoid Test（边界椭球测试）（241）
				3. Bounding Cylinder Test（包围圆柱测试）（245）
				4. Bounding Box Test（边界框测试）（247）
			3. Spatial Partitioning（空间分区）（249）
				1. Octrees（八叉树）（249）
				2. Binary Space Partitioning Trees（二元空间划分树）（251）
			4. Portal Systems（门户系统）（254）
				1. Portal Clipping（入口裁剪）（255）
				2. Reduced View Frustums（缩小视锥体）（257）
			5. Chapter 8 Summary（第8章总结）（259）
		9. Polygonal Techniques（多边形技术）（264）
			1. Depth Value Offset（深度值偏移）（264）
				1. Projection Matrix Modification（投影矩阵修改）（265）
				2. Offset Value Selection（偏置值选择）（266）
				3. Implementation（实施）（267）
			2. Decal Application（贴花应用）（268）
				1. Decal Mesh Construction（贴花网格结构）（269）
				2. Polygon Clipping（多边形裁剪）（271）
			3. Billboarding（广告牌）（273）
				1. Unconstrained Quads（无约束四边形）（273）
				2. Constrained Quads（约束四边形）（276）
				3. Polyboards（聚板）（277）
			4. Polygon Reduction（多边形缩减）（279）
			5. T-Junction Elimination（T形连接消除）（283）
			6. Triangulation（三角测量）（286）
			7. Chapter 9 Summary（第9章总结）（293）
		10. Shadows（阴影）（298）
			1. Shadow Casting Set（阴影投射设置）（298）
			2. Shadow Mapping（阴影贴图）（300）
				1. Rendering the Shadow Map（渲染阴影贴图）（300）
				2. Rendering the Main Scene（渲染主场景）（303）
				3. Self-Shadowing（自阴影）（303）
			3. Stencil Shadows（模板阴影）（305）
				1. Algorithm Overview（算法概述）（305）
				2. Infinite View Frustums（无限视锥体）（310）
				3. Silhouette Determination（轮廓确定）（314）
				4. Shadow Volume Construction（阴影体构建）（318）
				5. Determining Cap Necessity（确定上限必要性）（322）
				6. Rendering Shadow Volumes（渲染阴影体积）（326）
				7. Scissor Optimization（剪刀优化）（328）
			4. Chapter 10 Summary（第10章总结）（333）
		11. Curves and Surfaces（曲线和曲面）（336）
			1. Cubic Curves（三次曲线）（336）
			2. Hermite Curves（埃尔米特曲线）（339）
			3. Bézier Curves（贝塞尔曲线）（341）
				1. Cubic Bézier Curves（三次贝塞尔曲线）（341）
				2. Bézier Curve Truncation（贝塞尔曲线截断）（345）
				3. The de Casteljau Algorithm（de  Casteljau算法）（346）
			4. Catmull-Rom Splines（Catmull‑Rom  样条线）（348）
			5. Cubic Splines（三次样条）（350）
			6. B-Splines（B样条）（353）
				1. Uniform B-Splines（均匀  B  样条）（354）
				2. B-Spline Globalization（B样条全球化）（359）
				3. Nonuniform B-Splines（非均匀  B  样条）（361）
				4. NURBS（364）
			7. Bicubic Surfaces（双三次曲面）（367）
			8. Curvature and Torsion（曲率和扭转）（369）
			9. Chapter 11 Summary（第11章总结）（374）
		12. Collision Detection（碰撞检测）（380）
			1. Plane Collisions（平面碰撞）（380）
				1. Collision of a Sphere and a Plane（球体与平面的碰撞）（381）
				2. Collision of a Box and a Plane（盒子与平面的碰撞）（383）
				3. Spatial Partitioning（空间分区）（385）
			2. General Sphere Collisions（一般球体碰撞）（385）
			3. Sliding（滑动）（390）
			4. Collision of Two Spheres（两个球体的碰撞）（391）
			5. Chapter 12 Summary（第十二章总结）（395）
		13. Linear Physics（线性物理）（398）
			1. Position Functions（位置功能）（398）
			2. Second-Order Differential Equations（二阶微分方程）（400）
				1. Homogeneous Equations（齐次方程）（400）
				2. Nonhomogeneous Equations（非齐次方程）（404）
				3. Initial Conditions（初始条件）（407）
			3. Projectile Motion（抛射运动）（409）
			4. Resisted Motion（阻力运动）（413）
			5. Friction（摩擦力）（416）
			6. Chapter 13 Summary（第13章总结）（419）
		14. Rotational Physics（旋转物理学）（424）
			1. Rotating Environments（旋转环境）（424）
				1. Angular Velocity（角速度）（424）
				2. The Centrifugal Force（离心力）（426）
				3. The Coriolis Force（科里奥利力）（427）
			2. Rigid Body Motion（刚体运动）（429）
				1. Center of Mass（质心）（429）
				2. Angular Momentum and Torque（角动量和扭矩）（432）
				3. The Inertia Tensor（惯性张量）（433）
				4. Principal Axes of Inertia（惯性主轴）（441）
				5. Transforming the Inertia Tensor（变换惯性张量）（445）
			3. Oscillatory Motion（振荡运动）（449）
				1. Spring Motion（弹簧运动）（449）
				2. Pendulum Motion（摆运动）（453）
			4. Chapter 14 Summary（第14章总结）（455）
		15. Fluid and Cloth Simulation（流体和布料模拟）（462）
			1. Fluid Simulation（流体模拟）（462）
				1. The Wave Equation（波动方程）（462）
				2. Approximating Derivatives（近似导数）（466）
				3. Evaluating Surface Displacemen（评估表面位移）（469）
				4. Implementation（实施）（472）
			2. Cloth Simulation（布料模拟）（476）
				1. The Spring System（弹簧系统）（476）
				2. External Forces（外力）（478）
				3. Implementation（实施）（479）
			3. Chapter 15 Summary（第15章总结）（480）
		16. Numerical Methods（数值方法）（482）
			1. Trigonometric Functions（三角函数）（482）
			2. Linear Systems（线性系统）（484）
				1. Triangular Systems（三角系统）（484）
				2. Gaussian Elimination（高斯消去法）（486）
				3. LU Decomposition（LU分解）（489）
				4. Error Reduction（误差减少）（496）
				5. Tridiagonal Systems（三对角系）（498）
			3. Eigenvalues and Eigenvectors（特征值和特征向量）（502）
			4. Ordinary Differential Equations（常微分方程）（509）
				1. Euler’s Method（欧拉方法）（509）
				2. Taylor Series Method（泰勒级数法）（511）
				3. Runge-Kutta Method（龙格‑库塔法）（512）
				4. Higher-Order Differential Equations（高阶微分方程）（514）
			5. Chapter 16 Summary（第十六章总结）（515）
	2. Geometric Tools for Computer Graphics（计算机图形学几何工具算法详解）
		1. Introduction（介绍）（48）
			1. How to Use This Book（如何使用本书）（48）
			2. Issues of Numerical Computation（数值计算问题）（49）
				1. Low-Level Issues（低级问题）（49）
				2. High-Level Issues（高层问题）（51）
			3. A Summary of the Chapters（章节总结）（53）
		2. Matrices and Linear Systems（矩阵和线性系统）（56）
			1. Introduction（简介）（56）
				1. Motivation（动机）（56）
				2. Organization（组织机构）（60）
				3. Notational Conventions（符号约定）（61）
			2. Tuples（元组）（61）
				1. Definition（定义）（62）
				2. Arithmetic Operations（算术运算）（63）
			3. Matrices（矩阵）（63）
				1. Notation and Terminology（符号和术语）（64）
				2. Transposition（换位）（64）
				3. Arithmetic Operations（算术运算）（65）
				4. Matrix Multiplication（矩阵乘法）（67）
			4. Linear Systems（线性系统）（71）
				1. Linear Equations（线性方程）（71）
				2. Linear Systems in Two Unknowns（两个未知数的线性系统）（73）
				3. General Linear Systems（一般线性系统）（76）
				4. Row Reductions, Echelon Form, and Rank（行约简、梯队形式和等级）（77）
			5. Square Matrices（方阵）（79）
				1. Diagonal Matrices（对角矩阵）（79）
				2. Triangular Matrices（角矩阵）（81）
				3. The Determinant（行列式）（81）
				4. Inverse（逆）（85）
			6. Linear Spaces（线性空间）（88）
				1. Fields（字段）（88）
				2. Definition and Properties（定义和属性）（89）
				3. Subspaces（子空间）（90）
				4. Linear Combinations and Span（线性组合和跨度）（90）
				5. Linear Independence, Dimension, and Basis（线性无关性、维数和基础）（91）
			7. Linear Mappings（线性映射）（92）
				1. Mappings in General（一般映射）（92）
				2. Linear Mappings（线性映射）（94）
				3. Matrix Representation of Linear Mappings（线性映射的矩阵表示）（96）
				4. Cramer’s Rule（克莱默法则）（97）
			8. Eigenvalues and Eigenvectors（特征值和特征向量）（99）
			9. Euclidean Space（欧几里得空间）（101）
				1. Inner Product Spaces（内积空间）（101）
				2. Orthogonality and Orthonormal Sets（正交性和正交集）（102）
			10. Least Squares（最小二乘法）（103）
		3. Vector Algebra（向量代数）（110）
			1. Vector Basics（向量基础知识）（110）
				1. Vector Equivalence（向量等价）（110）
				2. Vector Addition（向量加法）（111）
				3. Vector Subtraction（向量减法）（112）
				4. Vector Scaling（矢量缩放）（112）
				5. Properties of Vector Addition and Scalar Multiplication（矢量加法和标量乘法的性质）（113）
			2. Vector Space（向量空间）（116）
				1. Span（跨度）（117）
				2. Linear Independence（线性无关性）（118）
				3. Basis, Subspaces, and Dimension（基础、子空间和维数）（118）
				4. Orientation（方向）（120）
				5. Change of Basis（基础变更）（122）
				6. Linear Transformations（线性变换）（123）
			3. Affine Spaces（仿射空间）（127）
				1. Euclidean Geometry（欧几里得几何）（131）
				2. Volume, the Determinant, and the Scalar Triple Product（体积、行列式和标量三重积）（141）
				3. Frames（框架）（143）
			4. Affine Transformations（仿射变换）（145）
				1. Types of Affine Maps（仿射图的类型）（150）
				2. Composition of Affine Maps（仿射图的构成）（150）
			5. Barycentric Coordinates and Simplexes（重心坐标和单纯形）（151）
				1. Barycentric Coordinates and Subspaces（重心坐标和子空间）（153）
				2. Affine Independence（仿射独立性）（153）
		4. Matrices, Vector Algebra, and Transformations（矩阵、向量代数和变换）（156）
			1. Introduction（简介）（156）
			2. Matrix Representation of Points and Vectors（点和向量的矩阵表示）（157）
			3. Addition, Subtraction, and Multiplication（加法、减法和乘法）（160）
				1. Vector Addition and Subtraction（向量加法和减法）（160）
				2. Point and Vector Addition and Subtraction（点与向量加减法）（161）
				3. Subtraction of Points（积分减法）（162）
				4. Scalar Multiplication（标量乘法）（162）
			4. Products of Vectors（向量的乘积）（162）
				1. Dot Product（点积）（163）
				2. Cross Product（叉积）（164）
				3. Tensor Product（张量积）（167）
				4. The “Perp” Operator and the “Perp” Dot Product（Perp”运算符和“Perp”点积）（168）
			5. Matrix Representation of Affine Transformations（仿射变换的矩阵表示）（173）
			6. Change-of-Basis/Frame/Coordinate System（改变基准/框架/坐标系）（175）
			7. Vector Geometry of Affine Transformations（仿射变换的向量几何）（179）
				1. Notation（符号）（180）
				2. Translation（平移）（181）
				3. Rotation（旋转）（183）
				4. Scaling（缩放）（189）
				5. Reflection（反射）（195）
				6. Shearing（剪切）（200）
			8. Projections（预测）（205）
				1. Orthographic（正交）（206）
				2. Oblique（倾斜）（207）
				3. Perspective（视角）（210）
			9. Transforming Normal Vectors（变换法向量）（212）
		5. Geometric Primitives in 2D（二维几何基元）（218）
			1. Linear Components（线性元件）（218）
				1. Implicit Form（隐式形式）（219）
				2. Parametric Form（参数化形式）（220）
				3. Converting between Representations（表示形式之间的转换）（221）
			2. Triangles（三角形）（222）
			3. Rectangles（矩形）（224）
			4. Polylines and Polygons（折线和多边形）（224）
			5. Quadratic Curves（二次曲线）（228）
				1. Circles（圆圈）（230）
				2. Ellipses（椭圆）（230）
			6. Polynomial Curves（多项式曲线）（232）
				1. B´ezier Curves（贝塞尔曲线）（233）
				2. B-Spline Curves（B 样条曲线）（233）
				3. NURBS Curves（NURBS  曲线）（235）
		6. Distance in 2D（二维距离）（236）
			1. Point to Linear Component（点到线性分量）（237）
				1. Point to Line（点到线）（237）
				2. Point to Ray（点到射线）（238）
				3. Point to Segment（点到段）（239）
			2. Point to Polyline（点到折线）（241）
			3. Point to Polygon（点到多边形）（243）
				1. Point to Triangle（点到三角形）（243）
				2. Point to Rectangle（点到矩形）（258）
				3. Point to Orthogonal Frustum（指向正交平截头体）（260）
				4. Point to Convex Polygon（点到凸多边形）（263）
			4. Point to Quadratic Curve（点到二次曲线）（264）
			5. Point to Polynomial Curve（点到多项式曲线）（266）
			6. Linear Components（线性元件）（268）
				1. Line to Line（线对线）（268）
				2. Line to Ray（线到射线）（269）
				3. Line to Segment（线到段）（270）
				4. Ray to Ray（射线到射线）（271）
				5. Ray to Segment（射线到线段）（273）
				6. Segment to Segment（段到段）（275）
			7. Linear Component to Polyline or Polygon（线性分量到折线或多边形）（276）
			8. Linear Component to Quadratic Curve（线性分量到二次曲线）（277）
			9. Linear Component to Polynomial Curve（线性分量到多项式曲线）（280）
			10. GJK Algorithm（GJK算法）（280）
				1. Set Operations（设置操作）（281）
				2. Overview of the Algorithm（算法概述）（282）
				3. Alternatives to GJK（GJK  的替代方案）（285）
		7. Intersection in 2D（二维交集）（288）
			1. Linear Components（线性元件）（288）
			2. Linear Components and Polylines（线性分量和折线）（293）
			3. Linear Components and Quadratic Curves（线性分量和二次曲线）（293）
				1. Linear Components and General Quadratic Curves（线性分量和一般二次曲线）（294）
				2. Linear Components and Circular Components（线性元件和圆形元件）（294）
			4. Linear Components and Polynomial Curves（线性分量和多项式曲线）（295）
				1. Algebraic Method（代数法）（295）
				2. Polyline Approximation（折线近似）（297）
				3. Hierarchical Bounding（层次边界）（298）
				4. Monotone Decomposition（单调分解）（299）
				5. Rasterization（光栅化）（300）
			5. Quadratic Curves（二次曲线）（302）
				1. General Quadratic Curves（一般二次曲线）（302）
				2. Circular Components（圆形元件）（304）
				3. Ellipses（椭圆）（305）
			6. Polynomial Curves（多项式曲线）（309）
				1. Algebraic Method（代数方法）（309）
				2. Polyline Approximation（折线近似）（309）
				3. Hierarchical Bounding（层次边界）（310）
				4. Rasterization（光栅化）（310）
			7. The Method of Separating Axes（分离轴的方法）（312）
				1. Separation by Projection onto a Line（通过投影到直线上的分离）（312）
				2. Separation of Stationary Convex Polygons（静止凸多边形的分离）（313）
				3. Separation of Moving Convex Polygons（移动凸多边形的分离）（320）
				4. Intersection Set for Stationary Convex Polygons（静止凸多边形的交集）（324）
				5. Contact Set for Moving Convex Polygons（移动凸多边形的接触集）（324）
		8. Miscellaneous 2D Problems（各种二维问题）（332）
			1. Circle through Three Points（过三点的圆）（332）
			2. Circle Tangent to Three Lines（与三条线相切的圆）（332）
			3. Line Tangent to a Circle at a Given Point（与圆在给定点相切的直线）（334）
			4. Line Tangent to a Circle through a Given Point（通过给定点与圆相切的线）（335）
			5. Lines Tangent to Two Circles（与两个圆相切的直线）（338）
			6. Circle through Two Points with a Given Radius（以给定半径绕两点画圆）（344）
			7. Circle through a Point and Tangent to a Line with a Given Radius（通过点并与给定半径的线相切的圆）（345）
			8. Circles Tangent to Two Lines with a Given Radius（与给定半径的两条线相切的圆）（349）
			9. Circles through a Point and Tangent to a Circle with a Given Radius（通过一点并与给定半径的圆相切的圆）（352）
			10. Circles Tangent to a Line and a Circle with a Given Radius（与直线和给定半径的圆相切的圆）（356）
			11. Circles Tangent to Two Circles with a Given Radius（与给定半径的两个圆相切的圆）（361）
			12. Line Perpendicular to a Given Line through a Given Point（与通过给定点的给定线垂直的线）（363）
			13. Line between and Equidistant to Two Points（两点之间且等距的直线）（364）
			14. Line Parallel to a Given Line at a Given Distance（与给定距离处的给定线平行的线）（365）
			15. Line Parallel to a Given Line at a Given Vertical (Horizontal) Distance（在给定垂直（水平）距离处与给定线平行的线）（367）
			16. Lines Tangent to a Given Circle and Normal to a Given Line（与给定圆相切并垂直于给定线的线）（369）
		9. Geometric Primitives in 3D（3D 几何基元）（372）
			1. Linear Components（线性元件）（372）
			2. Planar Components（平面元件）（373）
				1. Planes（平面）（373）
				2. Coordinate System Relative to a Plane（相对于平面的坐标系）（377）
				3. 2D Objects in a Plane（平面中的二维物体）（378）
			3. Polymeshes, Polyhedra, and Polytopes（多网格、多面体和多面体）（380）
				1. Vertex-Edge-Face Tables（点‑边‑面表）（384）
				2. Connected Meshes（连接网格）（387）
				3. Manifold Meshes（流形网格）（389）
				4. Closed Meshes（封闭网格）（389）
				5. Consistent Ordering（一致的顺序）（390）
				6. Platonic Solids（柏拉图固体）（393）
			4. Quadric Surfaces（二次曲面）（398）
				1. Three Nonzero Eigenvalues（三个非零特征值）（398）
				2. Two Nonzero Eigenvalues（两个非零特征值）（399）
				3. One Nonzero Eigenvalue（一个非零特征值）（399）
			5. Torus（环面）（402）
			6. Polynomial Curves（多项式曲线）（403）
				1. B´ezier Curves（贝塞尔曲线）（404）
				2. B-Spline Curves（B样条曲线）（404）
				3. NURBS Curves（NURBS  曲线）（405）
			7. Polynomial Surfaces（多项式曲面）（406）
				1. B´ezier Surfaces（贝兹曲面）（407）
				2. B-Spline Surfaces（B 样条曲面）（409）
				3. NURBS Surfaces（NURBS  曲面）（411）
		10. Distance in 3D（3D 距离）（412）
			1. Introduction（简介）（412）
			2. Point to Linear Component（点到线性分量）（412）
				1. Point to Ray or Line Segment（点到射线或线段）（414）
				2. Point to Polyline（点到折线）（416）
			3. Point to Planar Component（点到平面组件）（421）
				1. Point to Plane（点到平面）（421）
				2. Point to Triangle（点到三角形）（423）
				3. Point to Rectangle（点到矩形）（429）
				4. Point to Polygon（点到多边形）（432）
				5. Point to Circle or Disk（指向圆或圆盘）（435）
			4. Point to Polyhedron（点到多面体）（438）
				1. General Problem（一般问题）（438）
				2. Point to Oriented Bounding Box（指向定向边界框）（441）
				3. Point to Orthogonal Frustum（指向正交平截头体）（444）
			5. Point to Quadric Surface（点到二次曲面）（448）
				1. Point to General Quadric Surface（点到一般二次曲面）（448）
				2. Point to Ellipsoid（指向椭球体）（450）
			6. Point to Polynomial Curve（点到多项式曲线）（452）
			7. Point to Polynomial Surface（点到多项式曲面）（454）
			8. Linear Components（线性元件）（456）
				1. Lines and Lines（线与线）（456）
				2. Segment/Segment, Line/Ray, Line/Segment, Ray/Ray, Ray/Segment（线段/线段、线/射线、线/线段、射线/射线、射线/线段）（459）
				3. Segment to Segment, Alternative Approach（分段到分段，替代方法）（473）
			9. Linear Component to Triangle, Rectangle, Tetrahedron, Oriented Box（线性分量到三角形、矩形、四面体、定向盒子）（480）
				1. Linear Component to Triangle（线性分量到三角形）（480）
				2. Linear Component to Rectangle（线性分量到矩形）（488）
				3. Linear Component to Tetrahedron（四面体的线性分量）（494）
				4. Linear Component to Oriented Bounding Box（线性分量到定向边界框）（497）
			10. Line to Quadric Surface（直线到二次曲面）（512）
			11. Line to Polynomial Surface（直线到多项式曲面）（514）
			12. GJK Algorithm（GJK算法）（515）
			13. Miscellaneous（其他）（516）
				1. Distance between Line and Planar Curve（直线与平面曲线之间的距离）（516）
				2. Distance between Line and Planar Solid Object（线与平面实体之间的距离）（518）
				3. Distance between Planar Curves（平面曲线之间的距离）（519）
				4. Geodesic Distance on Surfaces（曲面上的测地距离）（524）
		11. Intersection in 3D（3D 交集）（528）
			1. Linear Components and Planar Components（线性分量和平面分量）（528）
				1. Linear Components and Planes（线性分量和平面）（529）
				2. Linear Components and Triangles（线性分量和三角形）（532）
				3. Linear Components and Polygons（线性分量和多边形）（535）
				4. Linear Component and Disk（线性元件和圆盘）（538）
			2. Linear Components and Polyhedra（线性分量和多面体）（540）
			3. Linear Components and Quadric Surfaces（线性分量和二次曲面）（545）
				1. General Quadric Surfaces（一般二次曲面）（546）
				2. Linear Components and a Sphere（线性分量和球体）（548）
				3. Linear Components and an Ellipsoid（线性分量和椭球体）（551）
				4. Linear Components and Cylinders（线性元件和圆柱体）（554）
				5. Linear Components and a Cone（线性分量和锥体）（560）
			4. Linear Components and Polynomial Surfaces（线性分量和多项式曲面）（566）
				1. Algebraic Surfaces（线性分量和多项式）（567）
				2. Free-Form Surfaces（自由曲面）（568）
			5. Planar Components（平面组件）（576）
				1. Two Planes（两个平面）（576）
				2. Three Planes（三个平面）（579）
				3. Triangle and Plane（三角形和平面）（581）
				4. Triangle and Triangle（三角形和三角形）（586）
			6. Planar Components and Polyhedra（平面组件和多面体）（590）
				1. Trimeshes（修剪网格）（590）
				2. General Polyhedra（一般多面体）（591）
			7. Planar Components and Quadric Surfaces（平面分量和二次曲面）（594）
				1. Plane and General Quadric Surface（平面和一般二次曲面）（594）
				2. Plane and Sphere（平面和球面）（595）
				3. Plane and Cylinder（平面和圆柱）（598）
				4. Plane and Cone（平面和圆锥）（610）
				5. Triangle and Cone（三角形和圆锥）（630）
			8. Planar Components and Polynomial Surfaces（平面组件和多项式曲面）（634）
				1. Hermite Curves（埃尔米特曲线）（635）
				2. Geometry Definitions（几何定义）（637）
				3. Computing the Curves（计算曲线）（638）
				4. The Algorithm（算法）（639）
				5. Implementation Notes（实施注意事项）（642）
			9. Quadric Surfaces（二次曲面）（642）
				1. General Intersection（一般交叉点）（643）
				2. Ellipsoids（椭球）（651）
			10. Polynomial Surfaces（多项式曲面）（655）
				1. Subdivision Methods（细分方法）（655）
				2. Lattice Evaluation（点阵评估）（656）
				3. Analytic Methods（分析方法）（657）
				4. Marching Methods（行进方法）（657）
			11. The Method of Separating Axes（分离轴的方法）（658）
				1. Separation of Stationary Convex Polyhedra（静止凸多面体的分离）（658）
				2. Separation of Moving Convex Polyhedra（动凸多面体的分离）（662）
				3. Intersection Set for Stationary Convex Polyhedra（静止凸多面体的交集）（663）
				4. Contact Set for Moving Convex Polyhedra（动凸多面体的接触集）（663）
			12. Miscellaneous（其他）（671）
				1. Oriented Bounding Box and Orthogonal Frustum（定向边界框和正交平截头体）（671）
				2. Linear Component and Axis-Aligned Bounding Box（线性分量和轴对齐边界框）（673）
				3. Linear Component and Oriented Bounding Box（线性分量和定向边界框）（677）
				4. Plane and Axis-Aligned Bounding Box（平面和轴对齐的边界框）（681）
				5. Plane and Oriented Bounding Box（平面和定向边界框）（682）
				6. Axis-Aligned Bounding Boxes（轴对齐边界框）（684）
				7. Oriented Bounding Boxes（定向边界框）（686）
				8. Sphere and Axis-Aligned Bounding Box（球体和轴对齐边界框）（691）
				9. Cylinders（气缸）（693）
				10. Linear Component and Torus（线性分量和环面）（706）
		12. Miscellaneous 3D Problems（其他 3D 问题）（710）
			1. Projection of a Point onto a Plane（点在平面上的投影）（710）
			2. Projection of a Vector onto a Plane（矢量到平面的投影）（712）
			3. Angle between a Line and a Plane（直线与平面之间的角度）（713）
			4. Angle between Two Planes（两个平面之间的角度）（714）
			5. Plane Normal to a Line and through a Given Point（垂直于直线并通过给定点的平面）（714）
			6. Plane through Three Points（通过三点的平面）（716）
			7. Angle between Two Lines（两条线之间的角度）（717）
		13. Computational Geometry Topics（计算几何主题）（720）
			1. Binary Space-Partitioning Trees in 2D（二维二元空间划分树）（720）
				1. BSP Tree Representation of a Polygon（多边形的BSP树表示）（721）
				2. Minimum Splits versus Balanced Trees（最小分裂与平衡树）（727）
				3. Point in Polygon Using BSP Trees（使用BSP树的多边形中的点）（730）
				4. Partitioning a Line Segment by a BSP Tree（用BSP树划分线段）（731）
			2. Binary Space-Partitioning Trees in 3D（3D  中的二元空间划分树）（734）
				1. BSP Tree Representation of a Polyhedron（多面体的BSP树表示）（735）
				2. Minimum Splits versus Balanced Trees（最小分裂与平衡树）（737）
				3. Point in Polyhedron Using BSP Trees（使用BSP树的多面体中的点）（738）
				4. Partitioning a Line Segment by a BSP Tree（用BSP树划分线段）（739）
				5. Partitioning a Convex Polygon by a BSP Tree（用BSP树划分凸多边形）（741）
			3. Point in Polygon（多边形内的点）（742）
				1. Point in Triangle（三角形中的点）（742）
				2. Point in Convex Polygon（凸多边形中的点）（744）
				3. Point in General Polygon（一般多边形中的点）（747）
				4. Faster Point in General Polygon（一般多边形中的更快点）（753）
				5. A Grid Method（网格法）（754）
			4. Point in Polyhedron（多面体中的点）（755）
				1. Point in Tetrahedron（四面体中的点）（755）
				2. Point in Convex Polyhedron（凸多面体中的点）（756）
				3. Point in General Polyhedron（一般多面体中的点）（758）
			5. Boolean Operations on Polygons（多边形的布尔运算）（761）
				1. The Abstract Operations（抽象操作）（762）
				2. The Two Primitive Operations（两个原始操作）（764）
				3. Boolean Operations Using BSP Trees（使用BSP树的布尔运算）（766）
				4. Other Algorithms（其他算法）（771）
			6. Boolean Operations on Polyhedra（多面体的布尔运算）（773）
				1. Abstract Operations（抽象操作）（773）
				2. Boolean Operations Using BSP Trees（使用BSP树的布尔运算）（774）
			7. Convex Hulls（凸包）（776）
				1. Convex Hulls in 2D（二维凸包）（776）
				2. Convex Hulls in 3D（凸包）（791）
				3. Convex Hulls in Higher Dimensions（高维凸包）（797）
			8. Delaunay Triangulation（德劳内三角剖分）（803）
				1. Incremental Construction in 2D（二维增量构建）（804）
				2. Incremental Construction in General Dimensions（一般尺寸增量施工）（808）
				3. Construction by Convex Hull（凸包构造）（813）
			9. Polygon Partitioning（多边形划分）（814）
				1. Visibility Graph of a Simple Polygon（简单多边形的可见性图）（814）
				2. Triangulation（三角测量）（818）
				3. Triangulation by Horizontal Decomposition（水平分解三角测量）（822）
				4. Convex Partitioning（凸划分）（836）
			10. Circumscribed and Inscribed Balls（外接球和内切球）（845）
				1. Circumscribed Ball（外接球）（846）
				2. Inscribed Ball（内接球）（848）
			11. Minimum Bounds for Point Sets（点集的最小界限）（850）
				1. Minimum-Area Rectangle（最小面积矩形）（850）
				2. Minimum-Volume Box（最小容量盒）（853）
				3. Minimum-Area Circle（最小面积圆）（854）
				4. Minimum-Volume Sphere（最小体积球体）（858）
				5. Miscellaneous（其他）（860）
			12. Area and Volume Measurements（面积和体积测量）（863）
				1. Area of a 2D Polygon（二维多边形的面积）（863）
				2. Area of a 3D Polygon（3D多边形的面积）（867）
				3. Volume of a Polyhedron（多面体的体积）（871）
		14. Numerical Methods（数值方法）（874）
			1. Solving Linear Systems（求解线性系统）（874）
				1. Special Case: Solving a Triangular System（特殊情况：求解三角系统）（875）
				2. Gaussian Elimination（高斯消去法）（876）
			2. Systems of Polynomials（多项式系统）（879）
				1. Linear Equations in One Formal Variable（一个形式变量的线性方程）（880）
				2. Any-Degree Equations in One Formal Variable（一个形式变量中的任意次方程）（882）
				3. Any-Degree Equations in Any Formal Variables（任意形式变量中的任意次方程）（884）
			3. Matrix Decompositions（矩阵分解）（894）
				1. Euler Angle Factorization（欧拉角分解）（894）
				2. QR Decomposition（QR  分解）（899）
				3. Eigendecomposition（特征分解）（900）
				4. Polar Decomposition（极分解）（901）
				5. Singular Value Decomposition（奇异值分解）（904）
			4. Representations of 3D Rotations（3D  旋转的表示）（904）
				1. Matrix Representation（矩阵表示）（904）
				2. Axis-Angle Representation（轴角表示）（905）
				3. Quaternion Representation（四元数表示）（907）
				4. Performance Issues（性能问题）（908）
			5. Root Finding（求根）（916）
				1. Methods in One Dimension（一维方法）（916）
				2. Methods in Many Dimensions（多维度方法）（921）
				3. Stable Solution to Quadratic Equations（二次方程的稳定解）（922）
			6. Minimization（最小化）（923）
				1. Methods in One Dimension（一维方法）（923）
				2. Methods in Many Dimensions（多维度方法）（924）
				3. Minimizing a Quadratic Form（最小化二次形式）（927）
				4. Minimizing a Restricted Quadratic Form（最小化受限二次形式）（927）
			7. Least Squares Fitting（最小二乘拟合）（929）
				1. Linear Fitting of Points (x, f (x))（点(x,  f  (x))的线性拟合）（929）
				2. Linear Fitting of Points Using Orthogonal Regression（使用正交回归对点进行线性拟合）（929）
				3. Planar Fitting of Points (x, y, f (x, y))（点(x,  y,  f  (x,  y))的平面拟合）（931）
				4. Hyperplanar Fitting of Points Using Orthogonal Regression（使用正交回归对点进行超平面拟合）（931）
				5. Fitting a Circle to 2D Points（将圆拟合到  2D  点）（933）
				6. Fitting a Sphere to 3D Points（将球体拟合到  3D  点）（934）
				7. Fitting a Quadratic Curve to 2D Points（将二次曲线拟合到二维点）（935）
				8. Fitting a Quadric Surface to 3D Points（将二次曲面拟合到  3D  点）（936）
			8. Subdivision of Curves（曲线细分）（936）
				1. Subdivision by Uniform Sampling（均匀采样细分）（936）
				2. Subdivision by Arc Length（按弧长细分）（937）
				3. Subdivision by Midpoint Distance（按中点距离细分）（938）
				4. Subdivision by Variation（按变体细分）（939）
			9. Topics from Calculus（微积分主题）（941）
				1. Level Sets（水平集）（941）
				2. Minima and Maxima of Functions（函数的最小值和最大值）（945）
				3. Lagrange Multipliers（拉格朗日乘子）（957）
		15. Trigonometry（三角学）（970）
			1. Introduction（简介）（970）
				1. Terminology（术语）（970）
				2. Angles（角度）（970）
				3. Conversion Examples（转换示例）（972）
			2. Trigonometric Functions（三角函数）（973）
				1. Definitions in Terms of Exponentials（指数的定义）（977）
				2. Domains and Ranges（域和值域）（978）
				3. Graphs of Trigonometric Functions（三角函数图）（978）
				4. Derivatives of Trigonometric Functions（三角函数的导数）（978）
				5. Integration（整合）（981）
			3. Trigonometric Identities and Laws（三角恒等式和定律）（981）
				1. Periodicity（周期性）（982）
				2. Laws（法则）（983）
				3. Formulas（公式）（987）
			4. Inverse Trigonometric Functions（反三角函数）（992）
				1. Defining arcsin and arccos in Terms of arctan（用反正切定义  arcsin  和  arccos）（992）
				2. Domains and Ranges（域和值域）（992）
				3. Graphs（图表）（993）
				4. Derivatives（衍生品）（993）
				5. Integration（集成）（995）
			5. Further Reading（进一步阅读）（995）
		16. Basic Formulas for Geometric Primitives（几何基元的基本公式）（996）
			1. Introduction（简介）（996）
			2. Triangles（三角形）（996）
				1. Symbols（符号）（996）
				2. Definitions（定义）（997）
				3. Right Triangles（直角三角形）（999）
			3. Quadrilaterals（四边形）（1001）
				1. Square（正方）（1001）
				2. Rectangle（矩形）（1001）
				3. Parallelogram（平行四边形）（1001）
				4. Rhombus（菱形）（1002）
				5. Trapezoid（梯形）（1002）
				6. General Quadrilateral（一般四边形）（1002）
			4. Circles（圆圈）（1003）
				1. Symbols（符号）（1003）
				2. Full Circle（全圆）（1003）
				3. Sector of a Circle（圆的扇区）（1003）
				4. Segment of a Circle（圆的线段）（1004）
			5. Polyhedra（多面体）（1004）
				1. Symbols（符号）（1004）
				2. Box（盒子）（1004）
				3. Prism（棱镜）（1005）
				4. Pyramid（金字塔）（1005）
			6. Cylinder（圆柱）（1005）
			7. Cone（锥体）（1006）
			8. Spheres（球体）（1006）
				1. Segments（段）（1006）
				2. Sector（扇区）（1007）
			9. Torus（环面）（1008）
	3. Computational Geometry（计算几何）
		1. Computational Geometry（计算几何）（12）
			1. An Example: Convex Hulls（例子：凸包）（13）
			2. Degeneracies and Robustness（简并性和鲁棒性）（19）
			3. Application Domains（应用领域）（21）
			4. Notes and Comments（注释和评论）（24）
		2. Line Segment Intersection（线段交点）（29）
			1. Line Segment Intersection（线段交点）（30）
			2. The Doubly-Connected Edge List（双连通边列表）（39）
			3. Computing the Overlay of Two Subdivisions（计算两个细分的重叠）（43）
			4. Boolean Operations（布尔运算）（49）
			5. Notes and Comments（注释和评论）（50）
		3. Polygon Triangulation（多边形三角剖分）（54）
			1. Guarding and Triangulations（防护和三角测量）（55）
			2. Partitioning a Polygon into Monotone Pieces（将多边形分割成单调块）（58）
			3. Triangulating a Monotone Polygon（对单调多边形进行三角剖分）（64）
			4. Notes and Comments（注释和评论）（68）
		4. Linear Programming（线性规划）（71）
			1. The Geometry of Casting（铸件的几何形状）（72）
			2. Half-Plane Intersection（半平面交线）（74）
			3. Incremental Linear Programming（增量线性规划）（79）
			4. Randomized Linear Programming（随机线性规划）（84）
			5. Unbounded Linear Programs（无界线性规划）（87）
			6. Linear Programming in Higher Dimensions（高维线性规划）（90）
			7. Smallest Enclosing Discs（最小封闭光盘）（94）
			8. Notes and Comments（注释和评论）（97）
		5. Orthogonal Range Searching（正交范围搜索）（102）
			1. 1-Dimensional Range Searching（一维范围搜索）（103）
			2. Kd-Trees（Kd树）（106）
			3. Range Trees（范围树）（112）
			4. Higher-Dimensional Range Trees（高维范围树）（116）
			5. General Sets of Points（一般点集）（117）
			6. Fractional Cascading（分数级联）（118）
			7. Notes and Comments（注释和评论）（122）
		6. Point Location（点位置）（128）
			1. Point Location and Trapezoidal Maps（点位置和梯形图）（129）
			2. A Randomized Incremental Algorithm（随机增量算法）（135）
			3. Dealing with Degenerate Cases（处理退化案例）（144）
			4. A Tail Estimate（尾部估计）（147）
			5. Notes and Comments（注释和评论）（150）
		7. Voronoi Diagrams（维诺图）（154）
			1. Definition and Basic Properties（定义和基本属性）（155）
			2. Computing the Voronoi Diagram（计算  Voronoi  图）（158）
			3. Voronoi Diagrams of Line Segments（线段Voronoi图）（167）
			4. Farthest-Point Voronoi Diagrams（最远点  Voronoi  图）（170）
			5. Notes and Comments（注释和评论）（174）
		8. Arrangements and Duality（安排和二元性）（179）
			1. Computing the Discrepancy（计算差异）（181）
			2. Duality（对偶性）（183）
			3. Arrangements of Lines（线路布置）（185）
			4. Levels and Discrepancy（水平和差异）（191）
			5. Notes and Comments（注释和评论）（192）
		9. Delaunay Triangulations（德劳内三角剖分）（197）
			1. Triangulations of Planar Point Sets（平面点集的三角剖分）（199）
			2. The Delaunay Triangulation（德劳内三角剖分）（202）
			3. Computing the Delaunay Triangulation（计算Delaunay三角剖分）（205）
			4. The Analysis（分析）（211）
			5. A Framework for Randomized Algorithms（随机算法框架）（214）
			6. Notes and Comments（注释和评论）（220）
		10. More Geometric Data Structures（更多几何数据结构）（225）
			1. Interval Trees（区间树）（226）
			2. Priority Search Trees（优先级搜索树）（232）
			3. Segment Trees（线段树）（237）
			4. Notes and Comments（注释和评论）（243）
		11. Convex Hulls（凸包）（248）
			1. The Complexity of Convex Hulls in 3-Space（3‑空间中凸包的复杂性）（249）
			2. Computing Convex Hulls in 3-Space（计算3‑空间中的凸包）（251）
			3. The Analysis（分析）（255）
			4. Convex Hulls and Half-Space Intersection（凸包和半空间交集）（258）
			5. Voronoi Diagrams Revisited（沃罗诺伊图重温）（259）
			6. Notes and Comments（注释和评论）（261）
		12. Binary Space Partitions（二进制空间分区）（264）
			1. The Definition of BSP Trees（BSP树的定义）（266）
			2. BSP Trees and the Painter’s Algorithm（BSP树和Painter算法）（268）
			3. Constructing a BSP Tree（构建BSP树）（269）
			4. The Size of BSP Trees in 3-Space（3 空间中 BSP 树的大小）（273）
			5. BSP Trees for Low-Density Scenes（低密度场景的BSP树）（276）
			6. Notes and Comments（注释和评论）（283）
		13. Robot Motion Planning（机器人运动规划）（287）
			1. Work Space and Configuration Space（工作空间和配置空间）（288）
			2. A Point Robot（点机器人）（290）
			3. Minkowski Sums（闵可夫斯基和）（294）
			4. Translational Motion Planning（平移运动规划）（301）
			5. Motion Planning with Rotations（带旋转的运动规划）（303）
			6. Notes and Comments（注释和评论）（307）
		14. Quadtrees（四叉树）（311）
			1. Uniform and Non-Uniform Meshes（均匀和非均匀网格）（313）
			2. Quadtrees for Point Sets（点集的四叉树）（313）
			3. From Quadtrees to Meshes（从四叉树到网格）（319）
			4. Notes and Comments（注释和评论）（322）
		15. Visibility Graphs（可见性图表）（327）
			1. Shortest Paths for a Point Robot（点机器人的最短路径）（328）
			2. Computing the Visibility Graph（计算可见性图）（330）
			3. Shortest Paths for a Translating Polygonal Robot（多边形平移机器人的最短路径）（334）
			4. Notes and Comments（注释和评论）（335）
		16. Simplex Range Searching（单纯形范围搜索）（338）
			1. Partition Trees（划分树）（339）
			2. Multi-Level Partition Trees（多级划分树）（346）
			3. Cutting Trees（砍伐树木）（349）
			4. Notes and Comments（注释和评论）（355）
5. Game Programming（游戏编程）
	1. Game Programming Patterns（游戏编程模式）
		1. Introduction（介绍）（7）
			1. What’s in Store（商店里有什么）（10）
			2. How it Relates to Design Patterns（它与设计模式有何关系）（11）
			3. How to Read the Book（如何阅读这本书）（13）
			4. About the Sample Code（关于示例代码）（15）
			5. Where to Go From Here（从这往哪儿走）（17）
			6. Architecture, Performance, and Games（建筑、性能和游戏）（18）
				1. What is Software Architecture?（什么是软件架构？）（19）
					1. What is good software architecture?（什么是好的软件架构？（19））
					2. How do you make a change?（你如何做出改变？）（20）
					3. How can decoupling help?（脱钩有何帮助？）（21）
				2. At What Cost?（代价是什么？）（23）
				3. Performance and Speed（性能和速度）（25）
				4. The Good in Bad Code（坏代码中的好处）（27）
				5. Striking a Balance（取得平衡）（29）
				6. Simplicity（简单）（31）
				7. Get On With It, Already（已经开始了）（33）
		2. Design Patterns Revisited（重新审视设计模式）（34）
			1. Command（命令）（36）
				1. Configuring Input（配置输入）（38）
				2. Directions for Actors（演员指导）（41）
				3. Undo and Redo（撤消和重做）（44）
				4. Classy and Dysfunctional?（优雅又功能失调？）（48）
				5. See Also（也可以看看）（50）
			2. Flyweight（享元）（51）
				1. Forest for the Trees（以树还林）（52）
				2. A Thousand Instances（一千个实例）（55）
				3. The Flyweight Pattern（享元模式）（56）
				4. A Place To Put Down Roots（扎根的地方）（57）
				5. What About Performance?（性能怎么样？）（62）
				6. See Also（也可以看看）（63）
			3. Observer（观察者）（64）
				1. Achievement Unlocked（解锁成就）（65）
				2. How it Works（怎么运行的）（67）
					1. The observer（观察者）（67）
					2. The subject（主题）（68）
					3. Observable physics（可观测物理）（69）
				3. “It’s Too Slow”（“太慢了”）（72）
					1. It’s too fast?（太快了？）（72）
				4. “It Does Too Much Dynamic Allocation”（“它的动态分配太多了”）（74）
					1. Linked observers（链接观察者）（74）
					2. A pool of list nodes（列表节点池）（78）
				5. Remaining Problems（遗留问题）（80）
					1. Destroying subjects and observers（摧毁主体和观察者）（80）
					2. Don’t worry, I’ve got a GC（别担心，我有GC）（81）
					3. What’s going on?（这是怎么回事？）（82）
				6. Observers Today（今日观察家）（84）
				7. Observers Tomorrow（明天观察家）（86）
			4. Prototype（原型）（88）
				1. The Prototype Design Pattern（原型设计模式）（89）
					1. How well does it work?（效果如何？）（92）
					2. Spawn functions（生成函数）（93）
					3. Templates（模板）（94）
					4. First-class types（一流类型）（94）
				2. The Prototype Language Paradigm（原型语言范式）（96）
					1. Self（自己）（96）
					2. How did it go?（进展如何？）（99）
					3. What about JavaScript?（JavaScript  呢？）（100）
				3. Prototypes for Data Modeling（数据建模原型）（103）
			5. Singleton（单例）（107）
				1. The Singleton Pattern（单例模式）（108）
					1. Restricting a class to one instance（将一个类限制为一个实例）（108）
					2. Providing a global point of access（提供全球访问点）（108）
				2. Why We Use It（我们为什么使用它）（111）
				3. Why We Regret Using It（为什么我们后悔使用它）（114）
					1. It’s a global variable（这是一个全局变量）（114）
					2. It solves two problems even when you just have one（即使您只有一个问题，它也能解决两个问题）（116）
					3. Lazy initialization takes control away from you（延迟初始化夺走了您的控制权）（117）
				4. What We Can Do Instead（我们可以做什么）（119）
					1. See if you need the class at all（看看你是否需要这门课）（119）
				5. To limit a class to a single instance（将类限制为单个实例）（121）
					1. To provide convenient access to an instance（提供对实例的便捷访问）（122）
				6. What’s Left for Singleton（Singleton还剩下什么）（126）
			6. State（状态）（127）
				1. We’ve All Been There（我们都去过那里）（128）
				2. Finite State Machines to the Rescue（有限状态机的救援）（131）
				3. Enums and Switches（枚举和开关）（133）
				4. The State Pattern（状态模式）（136）
					1. A state interface（状态接口）（136）
					2. Classes for each state（每个状态的类）（136）
					3. Delegate to the state（委托状态）（137）
				5. Where Are the State Objects?（状态对象在哪里？）（139）
					1. Static states（静态状态）（139）
					2. Instantiated states（实例化状态）（140）
				6. Enter and Exit Actions（进入和退出操作）（142）
				7. What’s the Catch?（有什么问题？）（144）
				8. Concurrent State Machines（并发状态机）（145）
				9. Hierarchical State Machines（分层状态机）（147）
				10. Pushdown Automata（下推自动机）（148）
				11. So How Useful Are They?（那么它们有多有用呢？）（151）
		3. Sequencing Patterns（测序模式）（152）
			1. Double Buffer（双缓冲器）（154）
				1. Intent（意图）（154）
				2. Motivation（动机）（155）
					1. How computer graphics work (briefly)（计算机图形学的工作原理（简要））（155）
					2. Act 1, Scene 1（第一幕，场景  1）（157）
					3. Back to the graphics（回到图形）（158）
				3. The Pattern（模式）（159）
				4. When to Use It（何时使用它）（160）
				5. Keep in Mind（记住）（161）
					1. The swap itself takes time（交换本身需要时间）（161）
					2. We have to have two buffers（我们必须有两个缓冲区）（161）
				6. Sample Code（示例代码）（162）
					1. Not just for graphics（不仅仅是图形）（165）
					2. Artificial unintelligence（人工无智能）（165）
					3. Buffered slaps（缓冲拍打）（170）
				7. Design Decisions（设计决策）（172）
					1. How are the buffers swapped?（缓冲区是如何交换的？）（172）
					2. What is the granularity of the buffer?（缓冲区的粒度是多少？）（174）
				8. See Also（也可以看看）（176）
			2. Game Loop（游戏循环）（177）
				1. Intent（意图）（177）
				2. Motivation（动机）（178）
					1. Interview with a CPU（采访CPU）（178）
					2. Event loops（事件循环）（179）
					3. A world out of time（一个不合时宜的世界）（180）
					4. Seconds per second（每秒秒数）（181）
				3. The Pattern（模式）（182）
				4. When to Use It（何时使用它）（183）
				5. Keep in Mind（记住）（184）
					1. You may need to coordinate with the platform’s event loop（您可能需要与平台的事件循环协调）（184）
				6. Sample Code（示例代码）（185）
					1. Run, run as fast as you can（跑，尽可能快地跑）（185）
					2. Take a little nap（小睡一会儿）（185）
					3. One small step, one giant step（一小步，一大步）（186）
					4. Play catch up（玩追赶游戏）（189）
					5. Stuck in the middle（卡在中间）（190）
				8. Design Decisions（设计决策）（193）
					1. Do you own the game loop, or does the platform?（你拥有游戏循环，还是平台拥有？）（193）
					2. How do you manage power consumption?（您如何管理功耗？）（194）
					3. How do you control gameplay speed?（你如何控制游戏速度？）（195）
				9. See Also（也可以看看）（198）
			3. Update Method（更新方法）（199）
				1. Intent（意图）（199）
				2. Motivation（动机）（200）
				3. The Pattern（模式）（204）
				4. When to Use It（何时使用它）（205）
				5. Keep in Mind（记住）（206）
					1. Splitting code into single frame slices makes it more complex（将代码拆分为单帧切片会使代码变得更加复杂）（206）
					2. You have to store state to resume where you left off each frame（你必须存储状态才能从每一帧停止的地方恢复）（206）
					3. Objects all simulate each frame but are not truly concurrent（对象全部模拟每一帧，但并不是真正并发的）（207）
					4. Be careful modifying the object list while updating（更新时要小心修改对象列表）（208）
				6. Sample Code（示例代码）（210）
					1. Subclassing entities?!（子类化实体？！）（211）
					2. Defining entities（定义实体）（212）
					3. Passing time（消磨时间）（214）
				7. Design Decisions（设计决策）（216）
					1. What class does the update method live on?（update  方法位于哪个类上？）（216）
					2. How are dormant objects handled?（如何处理休眠对象？）（217）
				8. See Also（也可以看看）（219）
		4. Behavioral Patterns（行为模式）（220）
			1. Bytecode（字节码）（222）
				1. Intent（意图）（222）
				2. Motivation（动机）（223）
					1. Spell fight!（咒语战斗！）（223）
					2. Data > code（数据  >  代码）（224）
					3. The Interpreter pattern（解释器模式）（224）
					4. Machine code, virtually（机器代码，实际上）（228）
				3. The Pattern（模式）（230）
				4. When to Use It（何时使用它）（231）
				5. Keep in Mind（记住）（232）
					1. You’ll need a front-end（你需要一个前端）（232）
					2. You’ll miss your debugger（你会想念你的调试器）（233）
				6. Sample Code（示例代码）（234）
					1. A magical API（神奇的API）（234）
					2. A magical instruction set（神奇的指令集）（234）
					3. A stack machine（一台堆垛机）（236）
					4. Behavior = composition（行为=组合）（240）
					5. A virtual machine（虚拟机）（242）
					6. Spellcasting tools（施法工具）（243）
				7. Design Decisions（设计决策）（247）
					1. How do instructions access the stack?（指令如何访问堆栈？）（247）
					2. What instructions do you have?（您有什么指示？）（248）
					3. How are values represented?（价值观如何体现？）（249）
					4. How is the bytecode generated?（字节码是如何生成的？）（253）
				8. See Also（也可以看看）（256）
			2. Subclass Sandbox（子类沙箱）（257）
				1. Intent（意图）（257）
				2. Motivation（动机）（258）
				3. The Pattern（模式）（261）
				4. When to Use It（何时使用它）（262）
				5. Keep in Mind（记住）（263）
				6. Sample Code（示例代码）（264）
				7. Design Decisions（设计决策）（268）
					1. What operations should be provided?（应该提供哪些操作？）（268）
					2. Should methods be provided directly, or through objects that contain them?（方法应该直接提供，还是通过包含它们的对象提供？）（270）
					3. How does the base class get the state that it needs?（基类如何获得它需要的状态？）（271）
				8. See Also（也可以看看）（275）
			3. Type Object（类型对象）（276）
				1. Intent（意图）（276）
				2. Motivation（动机）（277）
					1. The typical OOP answer（典型的  OOP  答案）（277）
					2. A class for a class（279）
				3. The Pattern（模式）（283）
				4. When to Use It（何时使用它）（284）
				5. Keep in Mind（记住）（285）
					1. The type objects have to be tracked manually（必须手动跟踪类型对象）（285）
					2. It’s harder to define behavior for each type（定义每种类型的行为更加困难）（286）
				6. Sample Code（示例代码）（288）
					1. Making type objects more like types: constructors（让类型对象更像类型：构造函数）（289）
					2. Sharing data through inheritance（通过继承共享数据）（290）
				7. Design Decisions（设计决策）（294）
					1. Is the type object encapsulated or exposed?（类型对象是封装的还是暴露的？）（294）
					2. How are typed objects created?（类型对象是如何创建的？）（296）
					3. Can the type change?（类型可以改变吗？）（296）
					4. What kind of inheritance is supported?（支持什么样的继承？）（297）
				8. See Also（也可以看看）（300）
		5. Decoupling Patterns（解耦模式）（301）
			1. Component（成分）（303）
				1. Intent（意图）（303）
				2. Motivation（动机）（304）
					1. The Gordian knot（棘手的结）（304）
					2. Cutting the knot（剪断结）（305）
					3. Loose ends（未解决的问题）（306）
					4. Tying back together（重新绑在一起）（306）
				3. The Pattern（模式）（309）
				4. When to Use It（何时使用它）（310）
				5. Keep in Mind（记住）（311）
				6. Sample Code（示例代码）（312）
					1. A monolithic class（单一类）（312）
					2. Splitting out a domain（拆分域）（315）
					3. Splitting out the rest（把剩下的分开）（317）
					4. Robo-Bjørn（机器人比约恩）（319）
					5. No Bjørn at all?（根本没有比约恩吗？）（322）
				7. Design Decisions（设计决策）（326）
					1. How does the object get its components?（对象如何获取其组件？）（326）
					2. How do components communicate with each other?（组件之间如何通信？）（327）
				8. See Also（也可以看看）（332）
			2. Event Queue（事件队列）（333）
				1. Intent（意图）（333）
				2. Motivation（动机）（334）
					1. GUI event loops（GUI  事件循环）（334）
					2. Central event bus（中央活动巴士）（335）
					3. Say what?（说什么？）（336）
				3. The Pattern（模式）（340）
				4. When to Use It（何时使用它）（341）
				5. Keep in Mind（记住）（342）
					1. A central event queue is a global variable（中央事件队列是一个全局变量）（342）
					2. The state of the world can change under you（世界的状况可以在你的领导下改变）（342）
					3. You can get stuck in feedback loops（你可能会陷入反馈循环）（343）
				6. Sample Code（示例代码）（344）
					1. A ring buffer（环形缓冲区）（346）
					2. Aggregating requests（聚合请求）（350）
					3. Spanning threads（跨接线程）（351）
				7. Design Decisions（设计决策）（353）
					1. What goes in the queue?（队列里有什么？）（353）
					2. Who can read from the queue?（谁可以从队列中读取？）（354）
					3. Who can write to the queue?（谁可以写入队列？）（356）
					4. What is the lifetime of the objects in the queue?（队列中对象的生命周期是多少？）（357）
				8. See Also（也可以看看）（358）
			3. Service Locator（服务定位器）（360）
				1. Intent（意图）（360）
				2. Motivation（动机）（361）
				3. The Pattern（模式）（363）
				4. When to Use It（何时使用它）（364）
				5. Keep in Mind（记住）（365）
					1. The service actually has to be located（该服务实际上必须位于）（365）
					2. The service doesn’t know who is locating it（该服务不知道是谁找到了它）（365）
				6. Sample Code（示例代码）（366）
					1. The service（服务）（366）
					2. The service provider（服务提供者）（366）
					3. A simple locator（一个简单的定位器）（367）
					4. A null service（空服务）（368）
					5. Logging decorator（记录装饰器）（370）
				7. Design Decisions（设计决策）（372）
					1. How is the service located?（该服务如何定位？）（372）
					2. What happens if the service can’t be located?（如果找不到该服务会怎样？）（375）
					3. What is the scope of the service?（服务范围是什么？）（378）
				8. See Also（也可以看看）（380）
			4. Optimization Patterns（优化模式）（381）
				1. Data Locality（数据局部性）（383）
					1. Intent（意图）（383）
					2. Motivation（动机）（384）
						1. A data warehouse（数据仓库）（385）
						2. A pallet for your CPU（适用于您的  CPU  的托盘）（386）
						3. Wait, data is performance?（等等，数据就是性能？）（388）
					3. The Pattern（模式）（391）
					4. When to Use It（何时使用它）（392）
					5. Keep in Mind（记住）（393）
					6. Sample Code（示例代码）（394）
						1. Contiguous arrays（连续数组）（394）
						2. Packed data（打包数据）（399）
						3. Hot/cold splitting（热/冷分裂）（403）
					7. Design Decisions（设计决策）（406）
						1. How do you handle polymorphism?（你如何处理多态性？）（406）
						2. How are game entities defined?（游戏实体是如何定义的？）（408）
					8. See Also（也可以看看）（412）
				2. Dirty Flag（脏标记）（413）
					1. Intent（意图）（413）
					2. Motivation（动机）（414）
						1. Local and world transforms（地方和世界的转变）（415）
						2. Cached world transforms（缓存的世界变换）（416）
						3. Deferred recalculation（推迟重新计算）（418）
					3. The Pattern（模式）（420）
					4. When to Use It（何时使用它）（421）
					5. Keep in Mind（记住）（423）
						1. There is a cost to deferring for too long（推迟太久是要付出代价的）（423）
						2. You have to make sure to set the flag every time the state changes（您必须确保每次状态更改时都设置标志）（424）
						3. You have to keep the previous derived data in memory（你必须将之前导出的数据保存在内存中）（425）
					6. Sample Code（示例代码）（426）
						1. An unoptimized traversal（未优化的遍历）（427）
						2. Let’s get dirty（让我们变脏吧）（428）
					7. Design Decisions（设计决策）（431）
						1. When is the dirty flag cleaned?（脏标记什么时候清理？）
						2. How fine-grained is your dirty tracking?（您的脏跟踪的细粒度如何？）（432）
					8. See Also（也可以看看）（433）
				3. Object Pool（对象池）（435）
					1. Intent（意图）（435）
					2. Motivation（动机）（436）
						1. The curse of fragmentation（碎片化的诅咒）（436）
						2. The best of both worlds（两全其美的）（437）
					3. The Pattern（模式）（439）
					4. When to Use It（何时使用它）（440）
					5. Keep in Mind（记住）（441）
						1. The pool may waste memory on unneeded objects（池可能会在不需要的对象上浪费内存）（441）
						2. Only a fixed number of objects can be active at any one time（任何一次只能有固定数量的对象处于活动状态）（441）
						3. Memory size for each object is fixed（每个对象的内存大小是固定的）（442）
						4. Reused objects aren’t automatically cleared（重复使用的对象不会自动清除）（443）
						5. Unused objects will remain in memory（未使用的对象将保留在内存中）（444）
					6. Sample Code（示例代码）（445）
						1. A free list（空闲列表）（447）
					7. Design Decisions（设计决策）（451）
						1. Are objects coupled to the pool?（对象是否与池耦合？）（451）
						2. What is responsible for initializing the reused objects?（什么负责初始化重用对象？）（453）
					8. See Also（也可以看看）（457）
				4. Spatial Partition（空间分区）（458）
					1. Intent（意图）（458）
					2. Motivation（动机）（459）
						1. Units on the field of battle（战场上的单位）（459）
						2. Drawing battle lines（绘制战线）（460）
					3. The Pattern（模式）（462）
					4. When to Use It（何时使用它）（463）
					5. Keep in Mind（记住）（464）
					6. Sample Code（示例代码）（465）
						1. A sheet of graph paper（一张方格纸）（465）
						2. A grid of linked units（链接单元的网格）（466）
						3. Entering the field of battle（进入战场）（467）
						4. A clash of swords（刀剑的碰撞）（468）
						5. Charging forward（向前冲锋）（469）
						6. At arm’s length（一臂长）（471）
					7. Design Decisions（设计决策）（475）
						1. Is the partition hierarchical or flat?（分区是分层的还是平面的？）（475）
						2. Does the partitioning depend on the set of objects?（分区是否取决于对象集？）（476）
						3. Are objects only stored in the partition?（对象只存储在分区中吗？）（479）
					8. See Also（也可以看看）（481）
	2. Game Coding Complete（游戏编程权威指南）
		1. What Is Game Programming Really Like?（游戏编程到底是什么样的？）（46）
			1. The Good（好的）（47）
				1. The Job（工作）（47）
				2. The Gamers（游戏玩家）（48）
				3. Your Coworkers（你的同事）（49）
				4. The Tools—Software Development Kits (SDKs)（工具-软件开发套件  (SDK)）（52）
				5. The Hardware（硬件）（53）
				6. The Platforms（平台）（53）
				7. The Show（演出）（58）
			2. The Hard Work（艰苦的工作）（59）
				1. Game Programming Is Freaking Hard（游戏编程太难了）（59）
				2. Bits and Pieces（点点滴滴）（60）
				3. That’s Not a Bug—That’s a Feature（这不是一个错误-这是一个功能）
				4. The Tools（工具）（62）
			3. The Dark Side（黑暗面）（62）
				1. Hitting a Moving Target（实现移动目标）（63）
				2. Crunch Mode (and Crunch Meals)（紧缩模式（和紧缩餐））（64）
				3. Bah Humbug（65）
				4. Operating System Hell（操作系统地狱）（66）
				5. Fluid Nature of Employment（就业的流动性）（67）
			4. It’s All Worth It, Right?（这一切都是值得的，对吧？）（68）
		2. What’s in a Game?（游戏中有什么？）（70）
			1. Game Architecture（游戏架构）（71）
			2. Applying the Game Architecture（应用游戏架构）（73）
			3. Application Layer（应用层）（76）
				1. Reading Input（读取输入）（76）
				2. File Systems and Resource Caching（文件系统和资源缓存）（76）
				3. Managing Memory（管理内存）（78）
				4. Initialization, the Main Loop, and Shutdown（初始化、主循环和关闭）（78）
				5. Other Application Layer Code（其他应用层代码）（79）
			4. Game Logic（游戏逻辑）（80）
				1. Game State and Data Structures（游戏状态和数据结构）（81）
				2. Physics and Collision（物理和碰撞）（82）
				3. Events（活动）（38）
				4. Process Manager（流程经理）（84）
				5. Command Interpreter（命令解释器）（85）
			5. Game View for the Human Player（人类玩家的游戏视图）（86）
				1. Graphics Display（图形显示器）（86）
				2. Audio（声音）（88）
				3. User Interface Presentation（用户界面演示）（89）
				4. Process Manager（流程经理）（89）
				5. Options（选项）（90）
				6. Multiplayer Games（多人游戏）（90）
			6. Game Views for AI Agents（AI  代理的游戏视图）（90）
			7. Networked Game Architecture（网络游戏架构）（91）
				1. Remote Game View（远程游戏视图）（92）
				2. Remote Game Logic（远程游戏逻辑）（92）
			8. Do I Have to Use DirectX?（我必须使用  DirectX  吗？）（94）
				1. Design Philosophy of DirectX（DirectX  的设计理念）（94）
				2. Direct3D or OpenGL（Direct3D  或  OpenGL）（95）
				3. DirectSound or What?（DirectSound  还是什么？）（95）
				4. DirectInput or Roll Your Own（DirectInput  或  Roll  Your  Own）（96）
			9. Other Bits and Pieces（其他零碎的东西）（96）
			10. Further Reading（进一步阅读）（97）
		3. Coding Tidbits and Style That Saved Me（拯救我的编码花絮和风格）（98）
			1. General Coding Styles（通用编码风格）（99）
				1. Bracing（支撑）（99）
				2. Consistency（一致性）（101）
			2. Smart Code Design Practices（智能代码设计实践）（103）
				1. Avoiding Hidden Code and Nontrivial Operations（避免隐藏代码和重要操作）（104）
				2. Class Hierarchies: Keep Them Flat（类层次结构：保持平坦）（105）
				3. Inheritance Versus Composition（继承与组合）（106）
				4. Virtual Functions Gone Bad（虚拟功能变坏了）（106）
				5. Use Interface Classes（使用接口类）（109）
				6. Consider Using Factories（考虑使用工厂）（110）
				7. Encapsulate Components That Change（封装变化的组件）（111）
				8. Use Streams to Initialize Objects（使用流来初始化对象）（112）
			3. Smart Pointers and Naked Pointers（智能指针和裸指针）（113）
				1. Reference Counting（引用计数）（114）
				2. C++’s shared_ptr（116）
			4. Using Memory Correctly（正确使用内存）（120）
				1. Understanding the Different Kinds of Memory（了解不同类型的内存）（120）
					1. System RAM（系统  RAM）（120）
					2. Video Memory (VRAM)（视频内存  (VRAM)）（123）
				2. Optimizing Memory Access（优化内存访问）（123）
				3. Memory Alignment（内存对齐）（125）
				4. Virtual Memory（虚拟内存）（126）
				5. Writing Your Own Memory Manager（编写自己的内存管理器）（127）
			5. Grab Bag of Useful Stuff（抓起一袋有用的东西）（129）
				1. An Excellent Random Number Generator（优秀的随机数生成器）（130）
				2. Pseudo-Random Traversal of a Set（集合的伪随机遍历）（132）
				3. Memory Pools（内存池）（133）
			6. Developing the Style That’s Right for You（发展适合您的风格）（140）
			7. Further Reading（进一步阅读）（140）
		4. Building Your Game（构建你的游戏）（142）
			1. A Little Motivation（一点动力）（143）
			2. Creating a Project（创建项目）（144）
				1. Build Configurations（构建配置）（144）
				2. Create a Bullet-Proof Directory Structure（创建防弹目录结构）（145）
				3. Where to Put Your Game Engine and Tools（将游戏引擎和工具放在哪里）（148）
				4. Setting Visual Studio Build Options（设置  Visual  Studio  生成选项）（149）
				5. Multiplatform Projects（多平台项目）（153）
			3. Source Code Repositories and Version Control（源代码存储库和版本控制）（155）
				1. A Little History—Visual SourceSafe from Microsoft（历史回顾  ‑  Microsoft  的  Visual  SourceSafe）（156）
				2. Subversion and TortoiseSVN（Subversion  和  TortoiseSVN）（157）
				3. Perforce by Perforce Software（Perforce  软件公司的  Perforce在这一类别）（158）
				4. AlienBrain from Avid（Avid  的  AlienBrain）（159）
				5. Using Source Control Branches（使用源代码控制分支）（160）
			4. Building the Game: A Black Art?（构建游戏：黑色艺术？）（163）
				1. Automate Your Builds（自动化您的构建）（165）
				2. The Build Machine（构建机器）（165）
				3. Automated Build Scripts（自动构建脚本）（166）
			5. Creating Build Scripts（创建构建脚本）（167）
				1. Normal Build（正常构建）（168）
				2. Milestone Build（里程碑构建）（169）
			6. Multiple Projects and Shared Code（多个项目和共享代码）（172）
			7. Some Parting Advice（一些离别建议）（173）
		5. Game Initialization and Shutdown（游戏初始化和关闭）（174）
			1. Initialization 101（初始化101）（175）
			2. Some C++ Initialization Pitfalls（一些  C++  初始化陷阱）（175）
			3. The Game’s Application Layer（游戏的应用层）（178）
				1. WinMain: The Windows Entry Point（WinMain：  Windows  入口点）（178）
				2. The Application Layer: GameCodeApp（应用程序层：  GameCodeApp游戏的应用程序层处）（180）
				3. InitInstance(): Checking System Resources（InitInstance()：检查系统资源）（181）
				4. Checking for Multiple Instances of Your Game（检查游戏的多个实例）（182）
				5. Checking Hard Drive Space（检查硬盘空间）（183）
				6. Checking Memory（检查内存）（184）
				7. Calculating CPU Speed（计算CPU速度）（185）
				8. Do You Have a Dirtbag on Your Hands?（你手上有脏袋吗？）（186）
				9. Initialize Your Resource Cache（初始化您的资源缓存）（186）
				10. Loading Text Strings（加载文本字符串）（187）
				11. Your Script Manager and the Events System（您的脚本管理器和事件系统）（189）
				12. Initialize DirectX and Create Your Window（初始化  DirectX  并创建您的窗口）（190）
				13. Create Your Game Logic and Game View（创建游戏逻辑和游戏视图游戏）（190）
				14. Set Your Save Game Directory（设置保存游戏目录）（191）
				15. Preload Selected Resources from the Cache（从缓存中预加载选定的资源）（192）
			4. Stick the Landing: A Nice Clean Exit（坚持着陆：干净利落的出口）（192）
				1. How Do I Get Out of Here?（我怎样才能离开这里？）（193）
				2. Forcing Modal Dialog Boxes to Close（强制关闭模态对话框）（195）
				3. Shutting Down the Game（关闭游戏）（196）
				4. What About Consoles?（控制台怎么样？）（197）
			5. Getting In and Getting Out（进出）（198）
		6. Game Actors and Component Architecture（游戏参与者和组件架构）（200）
			1. A First Attempt at Building Game Actors（构建游戏演员的首次尝试）（200）
			2. Component Architecture（组件架构）（204）
			3. Creating Actors and Components（创建  Actor  和组件）（205）
			4. Defining Actors and Components（定义参与者和组件）（210）
			5. Storing and Accessing Actors（存储和访问  Actor）（213）
			6. Putting It All Together（把它们放在一起）（215）
			7. Data Sharing（数据共享）（216）
				1. Direct Access（直接访问）（217）
				2. Events（活动）（218）
				3. The Best of Both Worlds（两全其美的）（218）
		7. Controlling the Main Loop（控制主循环）（220）
			1. Organizing the Main Loop（组织主循环）（220）
				1. Hard-Coded Updates（硬编码更新）（221）
				2. Multithreaded Main Loops（多线程主循环）（221）
				3. A Hybrid Technique（混合技术）（223）
				4. A Simple Cooperative Multitasker（简单的协作多任务）（225）
				5. Very Simple Process Example: DelayProcess（非常简单的过程示例：  DelayProcess）（231）
				6. More Uses of Process Derivatives（过程导数的更多用途）（232）
			2. Playing Nicely with the OS（与操作系统完美配合）（233）
			3. Using the DirectX 11 Framework（使用  DirectX  11  框架）（234）
				1. Rendering and Presenting the Display（渲染和呈现显示）（235）
				2. Your Callback Functions for Updating and Rendering（用于更新和渲染的回调函数）（236）
			4. Can I Make a Game Yet?（我还可以制作游戏吗？）（238）
		8. Loading and Caching Game Data（加载和缓存游戏数据）（240）
			1. Game Resources: Formats and Storage Requirements（游戏资源：格式和存储要求）（242）
				1. 3D Object Meshes and Environments（3D  对象网格和环境）（242）
				2. Animation Data（动画数据）（245）
				3. Map/Level Data（地图/关卡数据）（247）
				4. Texture Data（纹理数据）（247）
				5. Bitmap Color Depth（位图颜色深度）（247）
					1. Which Is Better: 24-, 16-, or 8-Bit Art?（哪个更好：24  位、16  位或  8  位艺术？）（248）
					2. Using Lossy Compression（使用有损压缩）（249）
					3. Data Sizes for Textures（纹理的数据大小）（249）
				6. Sound and Music Data（声音和音乐数据）（250）
				7. Video and Prerendered Cinematics（视频和预渲染过场动画）（251）
			2. Resource Files（资源文件）（254）
				1. Packaging Resources into a Single File（将资源打包到单个文件）（256）
				2. Other Benefits of Packaging Resources（打包资源的其他好处）（256）
				3. Data Compression and Performance（数据压缩和性能）（257）
				4. Zlib: Open Source Compression（Zlib：开源压缩）（258）
			3. The Resource Cache（资源缓存）（263）
				1. IResourceFile Interface（IResourceFile接口）（267）
				2. ResHandle: Tracking Loaded Resources（ResHandle：跟踪加载的资源）（267）
				3. IResourceLoader Interface and the DefaultResourceLoader（IResourceLoader接口和DefaultResourceLoader）（269）
				4. ResCache: A Simple Resource Cache（ResCache：一个简单的资源缓存）（270）
				5. Caching Resources into DirectX et al（将资源缓存到  DirectX  等中）（278）
				6. World Design and Cache Prediction（世界设计和缓存预测）（278）
			4. I’m Out of Cache（我的缓存已满）（282）
		9. Programming Input Devices（输入设备编程）（284）
			1. Getting the Device State（获取设备状态）（285）
			2. Using XInput or DirectInput（使用  XInput  或  DirectInput）（288）
			3. A Few Safety Tips（一些安全提示）（290）
			4. Working with Two-Axis Controls（使用两轴控件）（294）
				1. Capturing the Mouse on Desktops（捕获桌面上的鼠标）（294）
				2. Making a Mouse Drag Work（让鼠标拖动发挥作用）（297）
			5. Working with a Game Controller（使用游戏控制器）（300）
				1. Dead Zones（死区）（301）
				2. Normalizing Input（标准化输入）（304）
				3. One Stick, Two Stick, Red Stick, Blue Stick（一棒、两棒、红棒、蓝棒）（306）
				4. Ramping Control Values（斜坡控制值）（306）
			6. Working with the Keyboard（使用键盘）（307）
				1. Mike’s Keyboard Snooper（307）
				2. GetAsyncKeyState() and Other Evils（GetAsyncKeyState()和其他弊端）（312）
				3. Handling the Alt Key Under Windows（在  Windows  下处理  Alt  键）（312）
			7. What, No Dance Pad?（什么，没有舞蹈垫？）（312）
		10. User Interface Programming（用户界面编程）（314）
			1. DirectX’s Text Helper and Dialog Resource Manager（DirectX 的文本助手和对话框资源管理器）（315）
			2. The Human’s Game View（人类的游戏观）（316）
			3. A WASD Movement Controller（WASD  运动控制器）（326）
			4. Screen Elements（屏幕元素）（328）
			5. A Custom MessageBox Dialog（自定义消息框对话框）（331）
			6. Modal Dialog Boxes（模态对话框）（337）
			7. Controls（控制）（342）
			8. Control Identification（控制识别）（343）
			9. Hit Testing and Focus Order（命中测试和焦点顺序）（345）
			10. Control State（控制状态）（346）
			11. More Control Properties（更多控制属性）（347）
				1. Hot Keys（热键）（347）
				2. Tooltips（工具提示）（348）
				3. Context-Sensitive Help（上下文相关帮助）（349）
				4. Dragging（拖动控件）（349）
				5. Sounds and Animation（声音和动画）（349）
			12. Some Final User Interface Tips（一些最终的用户界面提示）（349）
		11. Game Event Management（游戏活动管理）（352）
			1. Game Events（游戏活动）（353）
				1. Events and Event Data（事件和事件数据）（354）
				2. The Event Listener Delegates（事件侦听器委托）（358）
				3. The Event Manager（事件管理器）（359）
				4. Example: Bringing It All Together（示例：将所有内容整合在一起）（368）
			2. What Game Events Are Important?（哪些游戏事件很重要？）（369）
			3. Distinguishing Events from Processes（区分事件和进程）（371）
			4. Further Reading（进一步阅读）（372）
		12. Scripting with Lua（使用  Lua  编写脚本）（374）
			1. A Brief History of Game Programming Languages（游戏编程语言简史）（375）
				1. Assembly Language（汇编语言）（376）
				2. C/C++（C/C++）（376）
				3. Scripting Languages（脚本语言）（379）
			2. Using a Scripting Language（使用脚本语言）（379）
				1. Rapid Prototyping（快速原型制作）（379）
				2. Design Focused（以设计为中心）（380）
				3. Speed and Memory Costs（速度和内存成本）（381）
				4. Where’s the Line?（线路在哪里？）（381）
			3. Scripting Language Integration Strategies（脚本语言集成策略）（382）
				1. Writing Your Own（自己写）（382）
				2. Using an Existing Language（使用现有语言）（382）
				3. Choosing a Scripting Language（选择脚本语言游戏）（383）
				4. Python（383）
				5. Lua（384）
			4. A Crash Course in Lua（Lua  速成班）（385）
				1. Comments（注释）（385）
				2. Variables（变量）（385）
				3. Functions（功能）（386）
				4. Tables（表格）（388）
				5. Flow Control（流量控制）（391）
				6. Operators（运算符）（393）
				7. What’s Next?（下一步是什么？）（394）
			5. Object-Oriented Programming in Lua（Lua  中的面向对象编程）（934）
				1. Metatables（元表）（396）
				2. Creating a Simple Class Abstraction（创建简单的类抽象）（398）
			6. Memory Management（内存管理）（401）
			7. Binding Lua to C++（将  Lua  绑定到  C++）（401）
				1. The Lua C API（401）
				2. tolua++（402）
				3. luabind（402）
				4. LuaPlus（402）
			8. A Crash Course in LuaPlus（LuaPlus  速成课程）（403）
				1. LuaState（403）
				2. LuaObject（403）
				3. Tables（405）
				4. Globals（406）
				5. Functions（408）
				6. Calling C++ Functions from Lua（从  Lua  调用  C++  函数从  Lua  调）（408）
			9. Bringing It All Together（将一切整合在一起）（411）
				1. Managing the Lua State（管理  Lua  状态）（411）
				2. Script Exports（脚本导出）（413）
				3. Process System（处理系统）（415）
				4. Event System（事件系统）（425）
				5. Script Component（脚本组件）（432）
			10. Lua Development and Debugging（Lua开发与调试）（434）
			11. Final Thoughts（最后的想法）（434）
			12. Further Reading（进一步阅读）（435）
		13. Game Audio（游戏音频）（436）
			1. How Sound Works（声音的工作原理）（437）
				1. Digital Recording and Reproduction（数字录音和复制）（438）
				2. Sound Files（声音文件）（440）
				3. A Quick Word About Threads and Synchronization（关于线程和同步的简短说明）（441）
			2. Game Sound System Architecture（游戏音响系统架构）（443）
				1. Sound Resources and Handles（声音资源和句柄）（443）
					1. Loading the WAV Format with WaveResourceLoader（使用WaveResourceLoader加载  WAV  格式）（446）
					2. Loading the OGG Format（加载  OGG  格式）（448）
				2. IAudioBuffer Interface and AudioBuffer Class（IAudioBuffer接口和AudioBuffer类）（454）
				3. IAudio Interface and Audio Class（IAudio接口和音频类）（456）
				4. DirectSound Implementations（DirectSound  实现）（459）
				5. Sound Processes（完善的流程）（471）
				6. Launching Sound Effects（启动音效）（476）
			3. Other Technical Hurdles（其他技术障碍）（477）
				1. Sounds and Game Objects（声音和游戏对象）（477）
				2. Timing and Synchronization（定时和同步）（477）
				3. Mixing Issues（混合问题）（479）
			4. Some Random Notes（一些随机笔记）（482）
				1. Data-Driven Sound Settings（数据驱动的声音设置）（482）
				2. Background Ambient Sounds and Music（背景环境声音和音乐）（483）
				3. Speech（语音游戏）（484）
					1. Random Barks（随机吠叫）（484）
					2. Game Fiction（游戏小说）（485）
					3. Lip Synching（口型同步）（485）
					4. Recording Speech（录音语音）（486）
			5. The Last Dance（最后的舞蹈）（486）
		14. 3D Graphics Basics（3D  图形基础知识）（488）
			1. 3D Graphics Pipeline（3D图形管线）（489）
			2. 3D Math 101（3D  数学  101）（490）
				1. Coordinates and Coordinate Systems（坐标和坐标系）（491）
				2. Vector Mathematics（矢量数学）（494）
			3. C++ Math Classes（C++  数学课程）（501）
				1. Vector Classes（向量类）（501）
				2. Matrix Mathematics（矩阵数学）（503）
					1. The Mat4 × 4 Transform Matrix Class（Mat4  ×  4变换矩阵类）（511）
				3. Quaternion Mathematics（四元数数学）（514）
					1. The Plane Class（飞机类）（518）
					2. The Frustum Class（截锥体类）（519）
				4. Transformations（转换）（523）
					1. World Transform（世界转变）（524）
					2. View Transform（视图变换）（524）
					3. Projection Transform（投影变换）（525）
				5. Geometry（几何）（526）
				6. Lighting, Normals, and Color（光照、法线和颜色）（527）
				7. Materials（材质）（529）
				8. Textured Vertices（纹理顶点）（532）
				9. Texturing（纹理）（532）
				10. Subsampling（子采样）（533）
				11. Mip-Mapping（Mip  映射）（535）
				12. Introducing ID3D11Device and ID3D11DeviceContext（ID3D11Device和ID3D11DeviceContext简介）（536）
				13. Loading Textures in D3D11（在  D3D11  中加载纹理）（536）
				14. Triangle Meshes（三角形网格）（539）
			4. Still with Me?（还在我这儿？）（542）
		15. 3D Vertex and Pixel Shaders（3D  顶点和像素着色器）（544）
			1. The Vertex Shader and Shader Syntax（顶点着色器和着色器语法）（546）
			2. Compiling the Vertex Shader（编译顶点着色器）（550）
			3. C++ Helper Class for the Vertex Shader（顶点着色器的  C++  辅助类）（552）
			4. The Pixel Shader（像素着色器）（560）
			5. C++ Helper Class for the Pixel Shader（像素着色器的  C++  辅助类）（561）
			6. Rendering with the Shader Helper Classes（使用着色器辅助类进行渲染）（565）
			7. Shaders— It’s Just the Beginning（着色器-这只是开始）（566）
			8. Further Reading（进一步阅读）（566）
		16. 3D Scenes（3D场景）（568）
			1. Scene Graph Basics（场景图基础知识）（568）
				1. ISceneNode Interface Class（ISceneNode接口类）（569）
				2. SceneNodeProperties and RenderPass（SceneNodeProperties和RenderPass）（571）
				3. SceneNode—It All Starts Here（SceneNode-一切从这里开始）（574）
				4. The Scene Class（581）
			2. Special Scene Graph Nodes（特殊场景图节点）（590）
				1. Implementing Separate Render Passes（实现单独的渲染通道）（590）
				2. A Simple Camera（一个简单的相机）（593）
				3. Putting Lights in Your Scene（将灯光放入场景）（596）
				4. Rendering the Sky（渲染天空）（599）
				5. Using Meshes in Your Scene（在场景中使用网格）（605）
			3. What’s Missing?（少了什么东西？）（610）
			4. Still Hungry?（还是饿着？）（610）
			5. Further Reading（进一步阅读）（610）
		17. Collision and Simple Physics（碰撞和简单物理）（614）
			1. Mathematics for Physics Refresher（物理复习数学）（614）
				1. Meters, Feet, Cubits, or Kellicams?（米、英尺、肘或凯利卡姆？）（614）
				2. Distance, Velocity, and Acceleration（距离、速度和加速度）（614）
				3. Mass, Acceleration, and Force（质量、加速度和力量）（616）
				4. Rotational Inertia, Angular Velocity, and Torque（转动惯量、角速度和扭矩）（619）
				5. Distance Calculations and Intersections（距离计算和交叉点）（620）
			2. Choosing a Physics SDK（选择物理  SDK）（621）
			3. Object Properties（对象属性）（623）
			4. Collision Hulls（碰撞船体）（625）
				1. Requirements of Good Collision Geometry（良好碰撞几何体的要求）（626）
				2. Visible Geometry Versus Collision Geometry（可见几何与碰撞几何）（627）
				3. Collision Hulls for Human Characters（人类角色的碰撞外壳）（628）
				4. Special Objects: Stairs, Doorways, and Trees（特殊对象：楼梯、门口和树木）（630）
			5. Using a Collision System（使用碰撞系统）（631）
			6. Integrating a Physics SDK（集成物理  SDK）（633）
				1. Components of the Bullet SDK（Bullet  SDK  的组件）（638）
				2. Initialization（初始化）（639）
				3. Shutdown（关闭）（640）
				4. Updating the Physics System（更新物理系统）（641）
				5. Creating a Simple Physics Object（创建一个简单的物理对象）（644）
				6. Creating a Convex Mesh（创建凸面网格）（646）
				7. Creating a Trigger（创建触发器）（647）
				8. Applying Force and Torque（应用力和扭矩）（648）
				9. The Physics Debug Renderer（物理调试渲染器）（649）
				10. Receiving Collision Events（接收碰撞事件）（651）
				11. A Final Word on Integrating Physics SDKs（关于集成物理  SDK  的最后一句话）（654）
			7. But Wait, There’s So Much More（但是等等，还有更多）（655）
		18. An Introduction to Game AI（游戏人工智能简介）（656）
			1. AI Techniques（人工智能技术）（657）
				1. Hard-Coded AI（硬编码人工智能）（657）
				2. Randomization（随机化）（659）
				3. Weighted Randoms（加权随机）（661）
			2. Finite State Machines（有限状态机）（661）
			3. Decision Trees（决策树）（667）
			4. Fuzzy Logic（模糊逻辑）（672）
			5. Utility Theory（效用理论）（675）
			6. Goal-Oriented Action Planning（以目标为导向的行动计划）（680）
			7. PathFinding（寻找路径）（683）
				1. A* (A-Star)（683）
				2. Dynamic Avoidance（动态回避）（685）
			8. Further Reading（进一步阅读）（686）
		19. Network Programming for Multiplayer Games（多人游戏的网络编程）（688）
			1. How the Internet Works（互联网如何运作）（689）
				1. Winsock or Berkeley?（温索克还是伯克利？）（690）
				2. Internet Addresses（互联网地址）（691）
				3. The Domain Name System（域名系统）（693）
				4. Useful Programs and Files（有用的程序和文件）（694）
			2. Sockets API（套接字API）（695）
				1. Sockets Utility Functions（套接字实用函数）（696）
				2. Domain Name Service (DNS) Functions（域名服务  (DNS)  功能）（698）
				3. Sockets Initialization and Shutdown（套接字初始化和关闭）（699）
				4. Creating Sockets and Setting Socket Options（创建套接字并设置套接字选项）（700）
					1. Connecting Sockets to a Server and Understanding Ports（将套接字连接到服务器并了解端口）（703）
				5. Server Functions（服务器功能）（705）
				6. Socket Reading and Writing（套接字读取和写入）（708）
			3. Making a Multiplayer Game with Sockets（使用套接字制作多人游戏）（708）
				1. Packet Classes（数据包类别）（710）
				2. Core Socket Classes（核心套接字类）（711）
				3. A Socket Class for Listening（用于监听的  Socket  类）（718）
				4. A Socket Manager Class（套接字管理器类）（720）
			4. Core Client-Side Classes（核心客户端类）（728）
			5. Core Server-Side Classes（核心服务器端类）（729）
			6. Wiring Sockets into the Event System（将套接字连接到事件系统）（731）
			7. Gosh, if It’s That Easy（天哪，如果有那么容易的话）（737）
		20. Introduction to Multiprogramming（多道程序设计简介）（738）
			1. What Multiprogramming Does（多道程序设计有什么作用）（738）
			2. Creating Threads（创建线程）（741）
			3. Process Synchronization（进程同步）（743）
				1. Test and Set, the Semaphore, and the Mutex（测试和设置、信号量和互斥信号量）（745）
				2. The Windows Critical Section（Windows  临界区）（745）
			4. Interesting Threading Problems（有趣的线程问题）（747）
			5. Thread Safety（线程安全）（749）
			6. Multithreading Classes in GameCode4（GameCode4  中的多线程类）（749）
				1. The RealtimeProcess Class（RealtimeProcess类）（750）
				2. Sending Events from Real-Time Processes（从实时进程发送事件）（753）
				3. Receiving Events in Real-Time Processes（在实时进程中接收事件）（756）
			7. Background Decompression of a Zip File（Zip  文件的后台解压）（758）
			8. Further Work（进一步的工作）（760）
			9. About the Hardware（关于硬件）（762）
			10. About the Future（关于未来）（763）
			11. Further Reading（进一步阅读）（763）
		21. A Game of Teapot Wars!（茶壶大战游戏！）（764）
			1. Making a Game（制作游戏）（765）
			2. Creating the Core Classes（创建核心类）（767）
				1. The Teapot Wars Application Layer（Teapot  Wars应用程序层）（767）
				2. The Game Logic（游戏逻辑）（768）
				3. The Game View for a Human Player（人类玩家的游戏视图）（778）
			3. Game Events（游戏活动）（782）
			4. Gameplay（游戏玩法）（782）
				1. Loading the Level（加载关卡）（783）
				2. The Actor Manager（演员管理器）（784）
				3. Sending and Receiving Events（发送和接收事件）（786）
				4. Processes（流程）（788）
			5. An Exercise Left to the Reader（留给读者的练习）（790）
		22. A Simple Game Editor in C#（一个简单的  C#  游戏编辑器）（792）
			1. Why C#?（为什么是  C#？）（792）
			2. How the Editor Is Put Together（编辑器是如何组合在一起的）（793）
			3. The Editor Architecture（编辑器架构）（793）
				1. The Application Layer（应用层）（794）
				2. The Editor’s Logic Class（编辑器的逻辑类）（795）
				3. The Editor View（编辑器视图）（796）
				4. Functions to Access the Game Engine（访问游戏引擎的函数）（798）
					1. Editor Framework Functions（编辑器框架函数）（798）
					2. Actor Accessor Functions（Actor  访问器函数）（801）
					3. Actor Modification Functions（Actor  修改功能）（806）
				5. Creating the DLL（创建  DLL）（808）
				6. Wrapping Up the Editor Architecture（总结编辑器架构）（809）
			4. The C# Editor Application（C#  编辑器应用程序）（801）
				1. Differences Between Managed Code and Unmanaged Code（托管代码和非托管代码之间的差异）（811）
				2. NativeMethods Class（NativeMethods类）（812）
				3. Program Class（Program类）（813）
				4. MessageHandler Class（MessageHandler类）（814）
			5. The C# Editor User Interface（C#  编辑器用户界面）（817）
				1. The EditorForm Class（EditorForm类）（817）
					1. The Asset Tree（资产树）（820）
					2. Actors List（演员列表）（822）
					3. The Menu Bar（菜单栏）（825）
				2. The ActorComponentEditor Class（ActorComponentEditor类）（829）
					1. Data Members and Initialization（数据成员和初始化）（831）
					2. A Quick XPath Tutorial（快速  XPath  教程）（832）
					3. Showing Actor Components（显示  Actor  组件）（834）
					4. Editing Actor Components（编辑  Actor  组件）（837）
			6. Future Work（未来的工作）（840）
			7. Further Reading（进一步阅读）（841）
		23. Debugging and Profiling Your Game（调试和分析您的游戏）（842）
			1. The Art of Handling Failure（处理失败的艺术）（843）
			2. Debugging Basics（调试基础知识）（845）
				1. Using the Debugger（使用调试器）（848）
				2. Installing Windows Symbol Files（安装  Windows  符号文件）（850）
				3. Debugging Full-Screen Games（调试全屏游戏）（852）
				4. Remote Debugging（远程调试）（853）
				5. Debugging Minidumps（调试小型转储）（855）
			3. Graphics and Shader Debugging（图形和着色器调试）（857）
			4. Debugging Techniques（调试技术）（858）
				1. Debugging Is an Experiment（调试是一项实验）（858）
				2. Reproducing the Bug（重现错误）（862）
				3. Eliminating Complexity（消除复杂性）（862）
				4. Setting the Next Statement（设置下一条语句）（863）
				5. Assembly Level Debugging（汇编级调试）（865）
				6. Peppering the Code（填充代码）（867）
				7. Draw Debug Information（绘制调试信息）（868）
				8. Lint and Other Code Analyzers（Lint  和其他代码分析器）（869）
				9. Nu-Mega’s BoundsChecker and Runtime Analyzers（Nu‑Mega  的  BoundsChecker  和运行时分析器）（870）
				10. Disappearing Bugs（消失的虫子）（870）
				11. Tweaking Values（调整值）（870）
				12. Caveman Debugging（Caveman  调试）（871）
				13. When All Else Fails（当一切都失败时）（872）
			5. Building an Error Logging System（构建错误记录系统）（873）
			6. Different Kinds of Bugs（不同种类的错误）（880）
				1. Memory Leaks and Heap Corruption（内存泄漏和堆损坏）（880）
				2. Game Data Corruption（游戏数据损坏）（884）
				3. Stack Corruption（堆栈损坏）（886）
				4. Cut and Paste Bugs（剪切和粘贴错误）（887）
				5. Running Out of Space（空间不足）（887）
				6. Release Mode-only Bugs（仅限发布模式的错误）（888）
				7. Multithreading Gone Bad（多线程变得糟糕）（888）
				8. Weird Ones（奇怪的人）（890）
			7. Profiling（分析）（891）
				1. Measuring Performance（测量性能）（891）
				2. Optimizing Code（优化代码）（892）
				3. Tradeoffs（权衡）（893）
				4. Over-Optimization（过度优化）（894）
			8. Parting Thoughts（离别的思念）（894）
			9. Further Reading（进一步阅读）（895）
		24. Driving to the Finish（驾驶至终点）（896）
			1. Finishing Issues（整理问题）（897）
				1. Quality（质量）（897）
				2. Code（代码）（902）
				3. Content（内容）（907）
			2. Dealing with Big Trouble（处理大麻烦）（910）
				1. Projects Seriously Behind Schedule（严重落后于计划的项目）（910）
					1. The Dreaded Crunch Mode—Working More Hours（可怕的加班模式——加班加点）（910）
					2. Pixel Fodder—Throw Warm Bodies at the Problem（像素饲料——用温暖的身体来解决问题）（913）
					3. Slipping the Schedule（推迟进度）（914）
					4. Cutting Features and Postponing Bugs（削减功能并推迟错误）（916）
				2. Personnel-Related Problems（人事相关问题）（917）
					1. Exhaustion（精疲力尽）（917）
					2. Morale（士气团）（918）
					3. Other Stuff（其他事情）（919）
				3. Your Competition Beats You to the Punch（你的竞争对手击败了你）（919）
				4. There’s No Way Out—or Is There?（没有出路——还是有出路？）（920）
				5. One Last Word—Don’t Panic（最后一句话——不要惊慌）（924）
			3. The Light—It’s Not a Train After All（光——它毕竟不是火车）（921）
				1. Test the Archive（测试存档）（922）
				2. The Patch Build or the Product Demo（补丁构建或产品演示）（923）
				3. The Postmortem（事后剖析）（923）
				4. What to Do with Your Time（怎样利用你的时间）（924）
	3. Game Programming Algorithms and Techniques（游戏编程算法和技巧）
		1. GAME PROGRAMMING OVERVIEW（游戏编程概述）（22）
			1. Evolution of Video Game Programming（视频游戏编程的演变）（23）
				1. Atari Era (1977–1985)（雅达利时代  (1977–1985)）（23）
				2. NES and SNES Era (1985–1995)（NES  和  SNES  时代  (1985–1995)）（24）
				3. Playstation/Playstation 2 Era (1995–2005)（Playstation/Playstation  2  时代（1995–2005））（24）
				4. Xbox 360, PS3, and Wii Era (2005–2013)（Xbox  360、PS3  和  Wii  时代（2005–2013））（25）
				5. The Future（未来）（25）
			2. The Game Loop（游戏循环）（26）
				1. Traditional Game Loop（传统游戏循环）（26）
				2. Multithreaded Game Loops（多线程游戏循环）（28）
			3. Time and Games（时间和游戏）（30）
				1. Real Time and Game Time（实时和游戏时间）（31）
				2. Logic as a Function of Delta Time（逻辑作为  Delta  时间的函数）（31）
			4. Game Objects（游戏对象）（34）
				1. Types of Game Objects（游戏对象的类型）（34）
				2. Game Objects in the Game Loop（游戏循环中的游戏对象）（34）
		2. 2D GRAPHICS（2D  图形）（40）
			1. 2D Rendering Foundations（2D  渲染基础）（41）
				1. CRT Monitor Basics（CRT  显示器基础知识）（41）
				2. Color Buffers and Vertical Sync（颜色缓冲区和垂直同步）（42）
			2. Sprites（精灵）（43）
				1. Drawing Sprites（绘制精灵）（44）
				2. Animating Sprites（动画精灵）（46）
				3. Sprite Sheets（精灵表）（49）
			3. Scrolling（滚动）（51）
				1. Single-Axis Scrolling（单轴滚动）（51）
				2. Infinite Scrolling（无限滚动）（53）
				3. Parallax Scrolling（视差滚动）（53）
				4. Four-Way Scrolling（四向滚动）（55）
			4. Tile Maps（平铺地图）（56）
				1. Simple Tile Maps（简单的平铺地图）（57）
				2. Isometric Tile Maps（等距瓷砖地图）（59）
		3. LINEAR ALGEBRA OR GAMES（线性代数或游戏）（62）
			1. Vectors（向量）（63）
				1. Addition（加法）（64）
				2. Subtraction（减法）（65）
				3. Length, Unit Vectors, and Normalization（长度、单位向量和归一化）（66）
				4. Scalar Multiplication（标量乘法）（68）
				5. Dot Product（点积）（69）
				6. Sample Problem: Vector Reflection（示例问题：矢量反射）（71）
				7. Cross Product（叉积）（72）
				8. Sample Problem: Rotating a 2D Character（示例问题：旋转  2D  角色）（75）
				9. Linear Interpolation（线性插值）（76）
				10. Coordinate Systems（坐标系）（77）
			2. Matrices（矩阵）（79）
				1. Addition/Subtraction（加法/减法）（79）
				2. Scalar Multiplication（标量乘法）（79）
				3. Multiplication（乘法）（80）
				4. Inverse（逆）（81）
				5. Transpose（转置）（81）
				6. Transforming 3D Vectors by Matrices（通过矩阵转换  3D  矢量）（81）
		4. 3D GRAPHICS（3D图形）（86）
			1. Basics（基本）（87）
				1. Polygons（多边形）（87）
			2. Coordinate Spaces（坐标空间）（88）
				1. Model Space（模型空间）（88）
				2. World Space（世界空间）（89）
					1. Homogenous Coordinates（齐次坐标）（89）
					2. Transforming 4D Vectors by Matrices（通过矩阵变换  4D  矢量）（90）
					3. Transform Matrices（变换矩阵）（90）
				3. View/Camera Space（视图/相机空间）（93）
				4. Projection Space（投影空间）（95）
			3. Lighting and Shading（照明和阴影）（97）
				1. Color（颜色）（97）
				2. Vertex Attributes（顶点属性）（98）
				3. Lights（灯）（100）
					1. Ambient Light（环境光）（101）
					2. Directional Light（定向光）（102）
					3. Point Light（点光源）（102）
					4. Spotlight（聚光灯）（102）
				4. Phong Reflection Model（Phong  反射模型）（103）
				5. Shading（阴影）（104）
					1. Gouraud Shading（Gouraud  着色）（104）
					2. Phong Shading（Phong  着色）（105）
			4. Visibility（能见度）（106）
				1. Painter’s Algorithm, Revisited（重温画家算法）（106）
				2. Z-Buffering（107）
			5. World Transform, Revisited（重温世界变革）（109）
				1. Quaternions（四元数）（110）
				2. 3D Game Object Representation（3D  游戏对象表示）（112）
		5. INPUT（输入）（114）
			1. Input Devices（输入设备）（115）
				1. Digital Input（数字输入）（116）
				2. Analog Input（模拟输入）（118）
			2. Event-Based Input Systems（基于事件的输入系统）（120）
				1. A Basic Event System（基本事件系统）（121）
				2. A More Complex System（更复杂的系统）（123）
			3. Mobile Input（移动输入）（126）
				1. Touch Screens and Gestures（触摸屏和手势）（126）
				2. Accelerometer and Gyroscope（加速度计和陀螺仪）（127）
				3. Other Mobile Input（其他移动输入）（129）
		6. SOUND（声音）（132）
			1. Basic Sound（基本声音）（133）
				1. Source Data（源数据）（133）
				2. Sound Cues（声音提示）（133）
			2. 3D Sound（3D音效）（136）
				1. Listeners and Emitters（听众和发射者）（137）
				2. Falloff（衰减）（139）
				3. Surround Sound（环绕声）（139）
			3. Digital Signal Processing（数字信号处理）（140）
				1. Common DSP Effects（常见的  DSP  效果）（141）
				2. Marking Regions（标记区域）（142）
			4. Other Sound Topics（其他声音主题）（143）
				1. Doppler Effect（多普勒效应）（143）
				2. Sound Occlusion and Obstruction（声音遮挡和阻碍）（144）
		7. PHYSICS（物理）（148）
			1. Planes, Rays, and Line Segments（平面、射线和线段）（149）
				1. Planes（平面）（149）
				2. Rays and Line Segments（射线和线段）（150）
			2. Collision Geometry（碰撞几何）（151）
				1. Bounding Sphere（包围球）（152）
				2. Axis-Aligned Bounding Box（轴对齐边界框）（153）
				3. Oriented Bounding Box（定向边界框）（153）
				4. Capsule（胶囊）（154）
				5. Convex Polygons（凸多边形）（154）
				6. List of Collision Geometries（碰撞几何形状列表）（155）
			3. Collision Detection（碰撞检测）（155）
				1. Sphere versus Sphere Intersection（球体与球体相交）（155）
				2. AABB versus AABB Intersection（AABB  与  AABB  交点）（156）
				3. Line Segment versus Plane Intersection（线段与平面相交）（157）
				4. Line Segment versus Triangle Intersection（线段与三角形交点）（159）
				5. Sphere versus Plane Intersection（球体与平面的交点）（161）
				6. Swept Sphere Intersection（扫掠球体交点）（162）
				7. Collision Response（碰撞响应）（167）
				8. Optimizing Collisions（优化碰撞）（168）
			4. Physics-Based Movement（基于物理的运动）（169）
				1. Linear Mechanics Overview（线性力学概述）（170）
				2. Issues with Variable Time Steps（可变时间步长的问题）（171）
				3. Calculating the Force（计算力）（172）
				4. Euler and Semi-Implicit Euler Integration（欧拉和半隐式欧拉积分）（172）
				5. Velocity Verlet Integration（速度  Verlet积分）（173）
				6. Other Integration Methods（其他积分方法）（174）
				7. Angular Mechanics（角度力学）（174）
			5. Physics Middleware（物理中间件）（174）
		8. CAMERAS（相机）（178）
			1. Types of Cameras（相机类型）（179）
				1. Fixed and Non-Player Controlled Cameras（固定和非玩家控制的摄像机）（179）
				2. First-person Camera（第一人称相机）（180）
				3. Follow Cameras（跟随摄像机）（181）
				4. Cutscene Cameras（过场动画摄像机）（182）
			2. Perspective Projections（透视投影）（182）
				1. Field of View（视野）（182）
				2. Aspect Ratio（纵横比）（184）
			3. Camera Implementations（相机实现）（185）
				1. Basic Follow Camera（基本跟随相机）（185）
				2. Spring Follow Camera（弹簧跟随相机）（186）
				3. Orbit Camera（轨道相机）（189）
				4. First-person Camera（第一人称相机）（191）
				5. Spline Camera（样条相机）（193）
			4. Camera Support Algorithms（相机支持算法）（196）
				1. Camera Collision（相机碰撞）（196）
				2. Picking（采摘）（197）
		9. ARTIFICIAL INTELLIGENCE（人工智能）（200）
			1. “Real” AI versus Game AI（“真实”人工智能与游戏人工智能）（201）
			2. Pathfinding（寻找路径）（201）
				1. Representing the Search Space（表示搜索空间）（202）
				2. Admissible Heuristics（可接受的启发法）（205）
				3. Greedy Best-First Algorithm（贪心最佳优先算法）（206）
				4. A* Pathfinding（A*  寻路）（210）
				5. Dijkstra’s Algorithm（迪杰斯特拉算法）（213）
			3. State-Based Behaviors（基于状态的行为）（213）
				1. State Machines for AI（AI  状态机）（214）
				2. Basic State Machine Implementation（基本状态机实现）（216）
				3. State Design Pattern（状态设计模式）（217）
			4. Strategy and Planning（策略与规划）（219）
				1. Strategy（战略）（219）
				2. Planning（规划）（220）
		10. USER INTERFACES（用户界面）（224）
			1. Menu Systems（菜单系统）（225）
				1. Menu Stack（菜单堆栈）（225）
				2. Buttons（纽扣）（226）
				3. Typing（打字）（227）
			2. HUD Elements（平视显示器元素）（228）
				1. Waypoint Arrow（航点箭头）（229）
				2. Aiming Reticule（瞄准标线）（232）
				3. Radar（雷达）（233）
			3. Other UI Considerations（其他用户界面注意事项）（238）
				1. Supporting Multiple Resolutions（支持多种分辨率）（239）
				2. Localization（本土化）（240）
				3. UI Middleware（用户界面中间件）（242）
				4. User Experience（用户体验）（242）
		11. SCRIPTING LANGUAGES AND DATA FORMATS（脚本语言和数据格式）（244）
			1. Scripting Languages（脚本语言）（245）
				1. Tradeoffs（权衡）（245）
				2. Types of Scripting Languages（脚本语言的类型）（246）
				3. Lua（248）
				4. UnrealScript（248）
				5. Visual Scripting Systems（可视化脚本系统）（250）
			2. Implementing a Scripting Language（实现脚本语言）（250）
				1. Tokenization（代币化）（251）
				2. Regular Expressions（正则表达式）（252）
				3. Syntax Analysis（语法分析）（253）
				4. Code Execution or Generation（代码执行或生成）（254）
			3. Data Formats（数据格式）（256）
				1. Tradeoffs（权衡）（256）
				2. Binary Formats（二进制格式）（257）
				3. INI（257）
				4. XML（258）
				5. JSON（259）
			4. Case Study: UI Mods in World of Warcraft（案例研究：《魔兽世界》中的 UI Mod）（260）
				1. Layout and Events（布局和事件）（260）
				2. Behavior（行为）（261）
				3. Issue: Player Automation（问题：玩家自动化）（261）
				4. Issue: The UI Breaking（问题：UI  破坏）（261）
				5. Conclusion（结论）（262）
		12. NETWORKED GAMES（联网游戏）（264）
			1. Protocols（协议）（265）
				1. IP（265）
				2. ICMP（266）
				3. TCP（267）
				4. UDP（270）
			2. Network Topology（网络拓扑结构）（271）
				1. Server/Client（服务器/客户端）（271）
				2. Peer-to-Peer（点对点）（274）
			3. Cheating（作弊）（276）
				1. Information Cheats（信息秘籍）（276）
				2. Game State Cheats（游戏状态秘籍）（277）
				3. Man-in-the-Middle Attack（中间人攻击）（277）
		13. SAMPLE GAME: SIDE-SCROLLER FOR IOS（示例游戏：适用于 IOS 的横向卷轴游戏）（280）
			1. Overview（概述）（281）
				1. Objective-C（282）
				2. cocos2d（283）
			2. Code Analysis（代码分析）（283）
				1. AppDelegate（应用程序代理）（284）
				2. MainMenuLayer（主菜单层）（284）
				3. GameplayScene（游戏场景）（284）
				4. ScrollingLayer（284）
				5. Ship（船）（286）
				6. Projectiles（射弹）（286）
				7. Enemy（敌人）（286）
				8. ObjectLayer（对象层）（287）
			3. Exercises（练习）（288）
		14. SAMPLE GAME: TOWER DEFENSE FOR PC/MAC（示例游戏：PC/MAC 版塔防）（290）
			1. Overview（概述）（291）
				1. C#（291）
				2. XNA（293）
				3. MonoGame（单机游戏）（294）
			2. Code Analysis（代码分析）（294）
				1. Settings（设置）（294）
				2. Singleton（单例）（295）
				3. Game Class（游戏类）（295）
				4. Game State（游戏状态）（296）
				5. Game Objects（游戏对象）（297）
				6. Level（等级）（298）
				7. Timer（定时器）（298）
				8. Pathfinding（寻路）（299）
				9. Camera and Projection（摄像头和投影）（300）
				10. Input（输入）（301）
				11. Physics（物理）（301）
				12. Localization（本土化）（301）
				13. Graphics（图形）（302）
				14. Sound（声音）（303）
				15. User Interface（用户界面）（303）
			3. Exercises（练习）（305）
	4. CROSS-PLATFORM GAME PROGRAMMING（跨平台游戏编程）
		1. Introduction（简介）（22）
			1. BACKGROUND OF CROSS-PLATFORM PROGRAMMING（跨平台编程的背景）（22）
				1. History（历史）（23）
				2. The Importance of Cross-Platform Development（跨平台开发的重要性）（25）
			2. OVERVIEW OF CROSS-PLATFORM COMPONENTS（跨平台组件概述）（28）
				1. The Lead Platform（领先平台）（30）
				2. Cross-Generation, Cross-Platform Game Programming（跨世代、跨平台的游戏编程）（30）
				3. The Theoretical Process（理论过程）（31）
			3. THE DEVELOPMENT PROCESS（开发过程）（33）
				1. Code Is Code（代码就是代码）（33）
				2. Console Limitations（控制台限制）（35）
				3. Libraries（图书馆）（36）
			4. ABOUT THE BOOK（关于本书）（38）
				1. Coding Style（编码风格）（38）
			5. NON-DISCLOSURE AGREEMENTS（保密协议）（39）
			6. NOTES TO THE READER（读者须知）（39）
		2. Top Ten Tips（十大秘诀）（42）
			1. THE BASIC ISSUES（基本问题）（42）
			2. ABSTRACTION（抽象）（43）
			3. COMMONALITY（共性）（45）
			4. LIMITATIONS（局限性）（45）
				1. Language Limitations（语言限制）（45）
				2. Library Limitations（库的限制）（48）
				3. Compiler Limitations（编译器限制）（48）
				4. Platform Limitations（平台限制）（52）
			5. MODULARIZATION（模块化）（54）
			6. RESOURCE CREATION PATH（资源创建路径）（56）
				1. Resource Detail（资源详情）（56）
			7. GRANULARITY（粒度）（59）
				1. Basic Datatypes（基本数据类型）（60）
				2. Memory Management（内存管理）（60）
				3. Audio Code（音频代码）（60）
			8. SEPARATION AND ISOLATION（分离和隔离）（61）
				1. Obvious Isolation（明显的隔离）（61）
				2. Singletons（单例）（62）
				3. Class Structures（类结构）（64）
				4. Divorcing Code（离婚法）（65）
				5. Separation by Purpose（按目的分离）（67）
				6. Separation by Memory（记忆分离）（70）
				7. Separation for the Present（目前的分离）（70）
				8. Separation for the Future（为了未来的分离）（71）
				9. Succession（演替）（73）
				10. The pImpl Idiom（pImpl  习语）（74）
			9. DEBUGGING AND PROFILING（调试和分析）（74）
				1. Programming-Based Bugs（基于编程的错误）（74）
				2. Compiler-Based Bugs（基于编译器的错误）（75）
				3. Execution-Based Bugs（基于执行的错误）（76）
				4. Profiling（分析）（80）
			10. PREDICTABILITY（可预测性）（81）
				1. Randomness（随机性）（81）
				2. Trigonometry（三角学）（82）
				3. Input Stimuli（输入刺激）（82）
			11. TURN-AROUND（回转）（83）
		3. Memory（内存）（88）
			1. THE SPECIFICATION（规格）（88）
			2. SIMPLE MEMORY（简单的内存）（92）
				1. The Issues—Datatypes（问题——数据类型）（92）
				2. The Issues—A Safety File（问题——安全文件）（95）
				3. The Issues—The Report（问题——报告）（97）
			3. OUR OWN MEMORY MANAGER—DESIGN（我们自己的内存管理器——设计）（102）
			4. HARDWARE PROPERTIES（硬件特性）（102）
				1. Endian（字节序）（102）
				2. Alignment（结盟）（106）
				3. Access（使用权）（108）
			5. SOFTWARE PROPERTIES（软件特性）（108）
				1. Fragmentation（碎片化）（108）
				2. The Standard Library（标准库）（110）
			6. OUR OWN MEMORY MANAGER—IMPLEMENTATION（我们自己的内存管理器——实现）（111）
				1. Conceptual Design（概念设计）（112）
				2. Allocating Memory（分配内存）（115）
				3. Garbage Collection（垃圾收集）（118）
				4. Releasing Memory（释放内存）（119）
			7. DEBUGGING MEMORY（调试内存）（120）
				1. Profiling Memory Usage（分析内存使用情况）（123）
				2. Allocation Wrappers（分配包装器）（123）
			8. HIGH-LEVEL MEMORY USAGE（高级内存使用）（123）
				1. Application Memory Usage（应用程序内存使用情况）（125）
			9. Using Allocation Within Subsystems（在子系统内使用分配）（136）
				1. Global versus Game（全球与游戏）（138）
			10. OTHER GUIDELINES（其他指南）（139）
				1. The Stack（堆栈）（139）
				2. Local Variables（局部变量）（141）
				3. Intelligent Buffer Usage（智能缓冲区使用）（142）
				4. Minimize Dynamic Memory（最小化动态内存）（142）
		4. The CPU（144）
			1. THE CPU（144）
				1. Timer Resolution（定时器分辨率）（145）
				2. Processor Yield（处理器产量）（147）
				3. Programming the Clock（时钟编程）（148）
				4. Programming Timers（定时器编程）（151）
				5. Programming Profilers（编程分析器）（151）
			2. TIME SLICING（时间切片）（153）
			3. CPU SCALABILITY（CPU可扩展性）（159）
				1. Lowest Common Denominator（最小公分母）（159）
				2. Scale Back（缩减）（160）
				3. Level of Detail (LOD)（细节层次  (LOD)）（160）
				4. Extra Burn（额外燃烧）（161）
			4. PARALLEL PROCESSING（并行处理）（162）
				1. Parallel Determination（平行测定）（162）
				2. Parallel Distribution（并行分布）（164）
				3. Parallel Implementation（并行实施）（170）
				4. Task Scheduling（任务调度）（181）
			5. AVOIDING THE WHOLE PROBLEM（避免整个问题）（183）
		5. Storage（存储）（186）
			1. THE FOUR CORNERS OF STORAGE（存储的四个角落）（186）
			2. THE PROBLEMS（问题）（187）
			3. THE DATA CONVERSION PROCESS（数据转换过程）（191）
				1. Serialization（序列化）（194）
				2. Endian Issues（字节序问题）（199）
				3. Extensibility and Future-Proofing（可扩展性和面向未来）（205）
				4. Introducing Platform-Specific Data（引入特定于平台的数据）（209）
				5. Introducing Platform-Specific Resources（引入特定于平台的资源）（217）
				6. Serializing Class Hierarchies（序列化类层次结构）（218）
				7. Object Creation（对象创建）（220）
				8. Interdependent Objects（相互依赖的对象）（221）
				9. Patching Pointers（修补指针）（222）
			4. DESIGNING A FILESYSTEM（设计文件系统）（226）
				1. Disc Size（光盘尺寸）（229）
				2. Layout（布局）（230）
			5. FILESYSTEM IMPLEMENTATION（文件系统实现）（233）
				1. Filesystem Devices（文件系统设备）（235）
				2. File Handling（文件处理）（241）
				3. Filesystem Shortcuts（文件系统快捷方式）（245）
				4. Filesystem Additions（文件系统添加）（246）
			6. HANDLING PHYSICAL DEVICES（处理物理设备）（246）
				1. Asynchronous Loading（异步加载）（247）
				2. Synchronous Loading（同步加载）（252）
				3. Block Sizes and Caching（块大小和缓存）（254）
				4. The General Case（一般情况）（257）
			7. CREATING BACK DOORS（创建后门）（257）
				1. Going Around the Problem（解决问题）（258）
				2. Knowing the Device（了解设备）（258）
				3. A ZIP Warning（邮政编码警告）（258）
		6. Debugging（调试）（262）
			1. BASIC REQUIREMENTS（基本要求）（262）
			2. DEBUGGING METHODS（调试方法）（263）
				1. Coding Style（编码风格）（263）
				2. Debugging Methodologies（调试方法）（269）
			3. IMPLEMENTING DEBUGGING CODE（实现调试代码）（271）
				1. Trace Messages（跟踪消息）（272）
				2. Trace Levels（痕量水平）（273）
				3. Handling Errors（处理错误）（282）
				4. Assertions（断言）（283）
				5. Memory（内存）（286）
			4. OUTPUT TARGETS（产出目标）（292）
				1. Time Delay（延时）（293）
				2. Flushes（冲水）（293）
				3. Sending to Host（发送至主机）（293）
				4. Bugs in the Compiler（编译器中的错误）（293）
				5. Bugs in the Debugging Code（调试代码中的错误）（294）
				6. Reproduction Bugs（繁殖错误）（294）
				7. Hardware Problems（硬件问题）（294）
				8. Screen（屏幕）（294）
				9. Second Sight（第二次看见）（295）
				10. File（文件）（295）
				11. Serial Port（串行端口）（296）
			5. MAKING DATA READABLE（使数据可读）（296）
				1. Multithreaded Output（多线程输出）（297）
			6. MAINTAINING CONSISTENCY（保持一致性）（299）
				1. Isolating System Calls（隔离系统调用）（299）
				2. Tabulating Trigonometry（三角学制表）（303）
				3. Random Numbers（随机数）（308）
				4. Code Checking（代码检查）（313）
		7. System I/O（系统输入/输出）（316）
			1. ABSTRACTING BASICS（抽象基础知识）（316）
			2. THE NULL DRIVER（空司机）（317）
				1. Prepared Singleton（准备单例）（317）
				2. Double Chance Functions（双机会函数）（319）
			3. INPUT DEVICES（输入设备）（320）
				1. General Implementation（一般实施）（321）
				2. Input Logging（输入记录）（332）
			4. Gameplay Abstractions（游戏玩法抽象）（336）
				1. The Bottom Line（底线）（339）
		8. The Audio System（音频系统）（342）
			1. HIGH-LEVEL PARAMETERS（高级参数）（342）
			2. PLAYING MUSIC（玩音乐）（343）
				1. CD Audio（CD音频）（344）
				2. MP3 and Ogg Vorbis（MP3  和  Ogg  Vorbis）（344）
				3. MIDI（345）
				4. Customized Formats（定制格式）（346）
			3. PLAYING SOUNDS（播放声音）（347）
				1. Raw Data（原始数据）（347）
				2. Compressed Data（压缩数据）（347）
				3. Metadat（元数据）（348）
				4. Looped Sounds（循环声音）（348）
			4. RESOURCING DATA（资源数据）（348）
				1. In Memory（在内存中）（349）
				2. From a Stream（来自流）（349）
				3. Asynchronous Loading（异步加载）（351）
			5. MIXER CONTROL（混音器控制）（351）
				1. UDE（352）
				2. The Gameplay Mixer（游戏混合器）（355）
				3. The Technology Mixer（技术混合器）（359）
				4. The User Mixer（用户混合器）（360）
			6. VIDEO PLAYBACK INTERACTION（视频播放互动）（362）
		9. The Graphics Engine（图形引擎）（364）
			1. HISTORY（历史）（364）
				1. Common Code（通用代码）（365）
			2. TECHNIQUES（技巧）（367）
				1. Static Texture Changes（静态纹理变化）（367）
				2. Dynamic Texture Changes（动态纹理变化）（370）
				3. Translucent Textures（半透明纹理）（373）
				4. State Changes（状态变化）（374）
				5. Mode Changes（模式变化）（377）
				6. Special Cases（特别案例）（379）
				7. Textures（纹理）（380）
				8. Meshes（网格）（383）
			3. ENGINE FEATURES（引擎特点）（384）
				1. Camera（相机）（384）
				2. Viewports（视口）（385）
				3. Lights（灯）（386）
				4. The Scene（现场）（387）
				5. Abstracted Features（抽象特征）（388）
				6. Texture Handling（纹理处理）（389）
				7. Meshes（网格）（390）
				8. Sprites（精灵）（393）
				9. Fonts and 2D Overlays（字体和  2D  叠加）（394）
			4. ABSTRACTING SPECIAL EFFECTS（抽象特殊效果）（395）
				1. Engine Effects（引擎效果）（395）
				2. Game Effects（游戏效果）（395）
				3. Special Effects（特殊效果）（395）
			5. GRAPHICS ON TELEVISION（电视图像）（396）
				1. Text（文本）（396）
				2. Contrasting Colors（对比色）（397）
				3. Image Sizes（图像尺寸）（397）
				4. Balancing Colors（平衡颜色）（398）
				5. Physical Testing（物理测试）（398）
		10. Network Programming（网络编程）（400）
			1. PACKET PROGRAMMING（数据包编程）（400）
			2. NETWORKING BACKGROUND（网络背景）（401）
			3. THE PHYSICAL NETWORK（物理网络）（403）
				1. The Conceptual Network Driver（概念网络驱动程序）（403）
			4. THE NULL NETWORK（空网络）（412）
				1. Network Latency（网络延迟）（413）
				2. Dropped Packets（丢弃的数据包）（414）
				3. The Two Modes（两种模式）（415）
			5. CROSS-NETWORK PROGRAMMING（跨网络编程）（416）
		11. The Bits We Forget About（我们忘记的那些事）（418）
			1. THE DEVELOPMENT PROCESS（开发过程）（418）
				1. The Environment（环境）（418）
				2. Source Code（源代码）（422）
			2. PRESENTATION ISSUES（演示问题）（424）
				1. PAL and NTSC（PAL  和  NTSC）（424）
				2. Frontend Screens（前端屏幕）（426）
				3. Foreign Language Versions（外语版本）（427）
			3. OPERATING SYSTEM CONSIDERATIONS（操作系统注意事项）（430）
				1. The Size of size_t（size_t  的大小）（430）
				2. Code Overlays（代码叠加）（430）
				3. Initializing the OS（初始化操作系统）（431）
				4. Title Screens（标题画面）（434）
				5. Attract Mode（吸引模式）（435）
				6. Reset Buttons（重置按钮）（435）
				7. Memory Cards（存储卡）（436）
				8. Disc Covers（光盘盖）（440）
			4. ARTIFACTS OF （代码工件）（441）
				1. The Consequence of STL（STL的后果）（441）
				2. Exceptions（例外情况）（443）
				3. Game Configuration（游戏配置）（445）
				4. Hacking It（破解它）（445）
	5. Android NDK Game Development Cookbook（Android NDK 游戏开发指南）
		1. Establishing a Build Environment（建立构建环境）（24）
			1. Introduction（介绍）（25）
			2. Installing Android development tools on Windows（在Windows上安装Android开发工具）（25）
			3. Installing Android development tools on Linux（在Linux上安装Android开发工具）（29）
			4. Creating an application template manually（手动创建应用程序模板）（30）
			5. Adding native C++ code to your application（将本机  C++  代码添加到您的应用程序）（34）
			6. Switching NDK toolchains（切换  NDK  工具链）（37）
			7. Supporting multiple CPU architectures（支持多种CPU架构）（38）
			8. Basic rendering with OpenGL ES（使用  OpenGL  ES  进行基本渲染）（39）
			9. Going cross platform（跨平台）（42）
			10. Unifying the cross-platform code（统一跨平台代码）（48）
			11. Linking and source code organization（链接和源代码组织）（50）
			12. Signing release Android applications（签署发布Android应用程序）（50）
		2. Porting Common Libraries（移植通用库）（54）
			1. Introduction（介绍）（55）
			2. Compiling the native static libraries for Windows（编译 Windows 的本机静态库）（55）
			3. Compiling the native static libraries for Android（编译 Android 原生静态库）（57）
			4. Compiling the libcurl networking library（编译  libcurl  网络库）（59）
			5. Compiling the OpenAL library（编译  OpenAL  库）（60）
			6. Compiling libvorbis, libmodplug, and libtheora（编译 libvorbis、libmodplug 和 libtheora）（61）
			7. Using the FreeImage graphics library（使用  FreeImage  图形库）（62）
			8. Using the FreeType library for text rendering（使用  FreeType  库进行文本渲染）（65）
			9. Implementing timing in physics（在物理学中实现计时）（71）
			10. Rendering graphics in 2D（以  2D  形式渲染图形）（74）
			11. Setting up Box2D simulations（设置  Box2D  模拟）（76）
			12. Building the ODE physical library（构建ODE物理库）（78）
		3. Networking（联网）（80）
			1. Introduction（介绍）（80）
			2. Fetching list of photos from Flickr and Picasa（从 Flickr 和 Picasa 获取照片列表）（81）
			3. Downloading images from Flickr and Picasa（从 Flickr 和 Picasa 下载图像）（85）
			4. Performing cross-platform multithreading（从  Flickr  和  Picasa  下载图像）（89）
			5. Synchronizing native cross-platform threads（同步本机跨平台线程）（91）
			6. Managing memory using reference counting（使用引用计数管理内存）（93）
			7. Implementing asynchronous task queues（实现异步任务队列）（98）
			8. Handling asynchronous callbacks invocation（处理异步回调调用）（100）
			9. Working with the network asynchronously（异步使用网络）（103）
			10. Detecting a network address（检测网络地址）（106）
			11. Writing the HTTP server（编写  HTTP  服务器）（108）
		4. Organizing a Virtual Filesystem（组织虚拟文件系统）（112）
			1. Introduction（介绍）（113）
			2. Abstracting file streams（抽象文件流）（113）
			3. Implementing portable memory-mapped files（实现便携式内存映射文件）（117）
			4. Implementing file writers（实现文件编写器）（119）
			5. Working with in-memory files（处理内存中的文件）（124）
			6. Implementing mount points（实施挂载点）（125）
			7. Enumerating files in the .zip archives（枚举 .zip  存档中的文件）（129）
			8. Decompressing files from the .zip archives（从 .zip  存档中解压文件）（134）
			9. Loading resources asynchronously（异步加载资源）（136）
			10. Storing application data（存储应用程序数据）（140）
		5. Cross-platform Audio Streaming（跨平台音频流）（144）
			1. Introduction（介绍）（144）
			2. Initializing OpenAL and playing the .wav files（初始化  OpenAL  并播放 .wav  文件）（145）
			3. Abstracting basic audio components（抽象基本音频组件）（149）
			4. Streaming sounds（流媒体声音）（161）
			5. Decoding Ogg Vorbis files（解码Ogg  Vorbis文件）（164）
			6. Decoding tracker music using ModPlug（使用  ModPlug  解码跟踪器音乐）（170）
		6. Unifying OpenGL ES 3 and OpenGL 3（统一 OpenGL ES 3 和 OpenGL 3）（172）
			1. Introduction（介绍）（172）
			2. Unifying the OpenGL 3 core profile and OpenGL ES 2（统一 OpenGL 3 核心配置文件和 OpenGL ES 2）（173）
			3. Initializing the OpenGL 3 core profile on Windows（在 Windows 上初始化 OpenGL 3 核心配置文件）（177）
			4. Initializing OpenGL ES 2 on Android（在  Android  上初始化  OpenGL  ES  2）（182）
			5. Unifying the GLSL 3 and GLSL ES 2 shaders（统一  GLSL  3  和  GLSL  ES  2  着色器）（187）
			6. Manipulating geometry（操纵几何图形）（193）
			7. Unifying vertex arrays（统一顶点数组）（196）
			8. Creating a wrapper for textures（创建纹理的包装器）（200）
			9. Creating a canvas for immediate rendering（创建用于立即渲染的画布）（203）
		7. Cross-platform UI and Input Systems（跨平台 UI 和输入系统）（208）
			1. Introduction（介绍）（208）
			2. Processing multi-touch events on Android（Android  上的多点触摸事件处理）（209）
			3. Setting up multi-touch emulation on Windows（在 Windows 上设置多点触控模拟）（212）
			4. Handling multi-touch events on Windows（在  Windows  上处理多点触摸事件）（213）
			5. Recognizing gestures（识别手势）（219）
			6. Implementing an on-screen joypad（实现屏幕游戏手柄）（227）
			7. Using FreeType for text rendering（使用  FreeType  进行文本渲染）（233）
			8. Localization of in-game strings（游戏内字符串的本地化）（244）
		8. Writing a Match-3 Game（编写三消游戏）（248）
			1. Introduction（介绍）（248）
			2. Handling asynchronous multi-touch input（处理异步多点触控输入）（249）
			3. Improving the audio playback mechanism（改进音频播放机制）（251）
			4. Shutting down the application（关闭应用程序）（254）
			5. Implementing the main loop（实现主循环）（256）
			6. Creating a multiplatform gaming engine（创建多平台游戏引擎）（258）
			7. Writing the match-3 game（编写三消游戏）（261）
			8. Managing shapes（管理形状）（271）
			9. Managing the game field logic（管理游戏字段逻辑）（274）
			10. Implementing user interaction within a game loop（在游戏循环中实现用户交互）（276）
		9. Writing a Picture Puzzle Game（编写一个图片益智游戏）（282）
			1. Introduction（介绍）（282）
			2. Implementing picture puzzle game logic（实现图片拼图游戏逻辑）（283）
			3. Implementing the animated 3D image selector（实现动画 3D 图像选择器）（289）
			4. Page-based user interface（基于页面的用户界面）（298）
			5. Image gallery with Picasa downloader（带  Picasa  下载器的图片库）（303）
			6. Implementing the complete picture-puzzle game（实现完整的图片拼图游戏）（307）
	6. Game Programming Gems 2（游戏编程精粹2）
		1. 1
			1. Optimization for C++ Games（C++ 游戏优化）（3）
				1. Object Construction and Destruction（对象构造和销毁）（3）
				2. Memory Management（内存管理）（7）
				3. Virtual Functions（虚函数）（7）
				4. Code Size（代码大小）（9）
				5. The Standard Template Library（标准模板库）（10）
				6. Advanced Features（高级功能）（12）
			2. Inline Functions Versus Macros（内联函数与宏）（14）
				1. Advantages of Inline Functions（内联函数的优点）（14）
				2. When to Use Inline Functions（何时使用内联函数）（16）
				3. When to Use Macros（何时使用宏）（16）
				4. Microsoft Specifics（微软细节）（17）
			3. Programming with Abstract Interfaces（使用抽象接口编程）（18）
				1. Abstract Interfaces（抽象接口）（18）
				2. Adding a Factory（添加工厂）（20）
				3. Abstract Interfaces as Traits（作为特征的抽象接口）（21）
				4. Everything Has a Cost（一切都有成本）（24）
				5. Conclusion（结论）（25）
			4. Exporting C++ Classes from DLLs（从  DLL  导出  C++  类）（26）
				1. Exporting a Function（导出函数）（26）
				2. Exporting a Class（导出类）（26）
				3. Exporting Class Member Functions（导出类成员函数）（28）
				4. Exporting Virtual Class Member Functions（导出虚拟类成员函数）（29）
				5. Summary（概括）（30）
			5. Protect Yourself from DLL Hell and Missing OS Functions（保护自己免受 DLL Hell 和缺失操作系统功能的影响）（31）
				1. Implicit vs. Explicit Linking（隐式链接与显式链接）（31）
				2. LoadLibrary and GetProcAddress（LoadLibrary  和  GetProcAddress）（32）
				3. Guarding Against DirectX（防范  DirectX）（32）
				4. Using OS-Specific Features（使用特定于操作系统的功能）（34）
				5. Summary（概括）（35）
			6. Dynamic Type Information（动态类型信息）（36）
				1. Introducing the Dynamic Type Information Class（动态类型信息类简介）（36）
				2. Exposing and Querying the DTI（公开和查询  DTI）（37）
				3. Inheritance Means "IsA"（继承的意思是“IsA”）（38）
				4. Handling Generic Objects（处理通用对象）（39）
				5. Implementing Persistent Type Information（实现持久类型信息）（41）
				6. Applying Persistent Type Information to a Game Save Database（将持久类型信息应用到游戏保存数据库）（42）
				7. Conclusion（结论）（43）
			7. A Property Class for Generic C++ Member Access（用于通用 C++ 成员访问的属性类）（44）
				1. The Code（代码）（44）
				2. Additional Uses（额外用途）（47）
				3. Additional Reading（补充阅读）（48）
			8. A Game Entity Factory（游戏实体工厂）（49）
				1. Components（成分）（49）
				2. Flyweight, Behavior, and Exported Classes（Flyweight、行为和导出类）（50）
				3. Flyweight Objects（享元对象）（50）
				4. SAMMy, Where Are You?（萨米，你在哪里？）（50）
				5. Behavioral Class Hierarchy（行为类层次结构）（52）
				6. Using the Template Method Pattern for Behavior Assignment（使用模板方法模式进行行为分配）（53）
				7. Exported Classes（导出类）（53）
				8. The Entity Factory（实体工厂）（55）
				9. Selecting Strategies at Runtime（在运行时选择策略）（56）
				10. Final Notes（最后的注释）（58）
			9. Adding Deprecation Facilities to C++（向C++添加弃用工具）（60）
				1. Possible Solutions（可能的解决方案）（60）
				2. The Ideal Solution（理想的解决方案）（61）
				3. Using and Assigning Deprecated Functions（使用和分配已弃用的函数）（61）
				4. Implementing Deprecation in C++（在  C++  中实现弃用）（62）
				5. What Could Be Improved?（有什么可以改进的地方？）（63）
			10. A Drop-in Debug Memory Manager（嵌入式调试内存管理器）（64）
				1. Getting Started（入门）（64）
				2. Memory Manager Logging（内存管理器日志记录）（66）
				3. Reporting the Information（报告信息）（68）
				4. Things to Keep in Mind（要记住的事情）（69）
				5. Further Enhancements（进一步增强）（71）
			11. A Built-in Game Profiling Module（内置游戏分析模块）（72）
				1. Profiling Basics（分析基础知识）（72）
				2. Commercially Available Tools（市售工具）（73）
				3. Why Roll Our Own?（为什么要自己推出？）（73）
				4. Profile Module Requirements（配置文件模块要求）（74）
				5. Architecture and Implementation（架构与实施）（74）
				6. Implementation Details（实施细节）（76）
				7. Data Analysis（数据分析）（76）
				8. Implementation Notes（实施说明）（76）
			12. Linear Programming Model for Windows-based Games（基于 Windows 的游戏的线性规划模型）（77）
				1. Updating the World（更新世界）（78）
				2. The Solution: Multithreading（解决方案：多线程）（79）
			13. Stack Winding（叠绕）（83）
				1. Simple TempRet（简单的TempRet）（83）
				2. Listing 1.13.1 The TempRet routine（清单  1.13.1  TempRet  例程）（83）
				3. TempRet Chains（TempRet  链）（84）
				4. Listing 1.13.2 Winding multiple routines onto the stack（清单1.13.2将多个例程缠绕到堆栈上）（85）
				5. Thunking（沉思）（86）
				6. Listing 1.13.3 Visual C++ example using TempRet（清单  1.13.3  使用  TempRet  的  Visual  C++  示例）（86）
				7. Recursion（递归）（87）
				8. Listing 1.13.4 The SafeEnter and SafeExit functions that aid recursion（清单  1.13.4  辅助递归的  SafeEnter  和  SafeExit  函数）（87）
				9. Listing 1.13.5 Recursive example using SafeEnter and SafeExit（清单  1.13.5  使用  SafeEnter  和  SafeExit  的递归示例）（88）
			14. Self-Modifying Code（自修改代码）（89）
				1. The Principles of RAM-Code（RAM  代码的原理）（89）
				2. A Fast Bit Blitter（快速位碎块）（90）
			15. File Management Using Resource Files（使用资源文件进行文件管理）（98）
				1. What Is a Resource File?（什么是资源文件？）（98）
				2. Listing 1.15.1 Resource file structure.（清单  1.15.1  资源文件结构。）（98）
				3. Listing 1.15.2 File lump structure.（清单  1.15.2  文件块结构。）（99）
				4. Design（设计）（99）
				5. Implementation（执行）（100）
				6. Last Words about the Implementation（关于实施的最后一句话）（102）
				7. Conclusion（结论）（102）
			16. Game Input Recording and Playback（游戏输入录制和回放）（103）
				1. What Exactly Is Input Recording Useful For?（输入记录到底有什么用？）（103）
				2. What Does ItJTake?（需要什么？）（105）
				3. Testing Your Input Recording（测试您的输入录音）（108）
				4. Conclusion（结论）（108）
			17. A Flexible Text Parsing System（灵活的文本解析系统）（110）
				1. The Parsing System（解析系统）（110）
				2. Macros, Headers, and Preprocessing Magic（宏、标头和预处理魔法）（111）
				3. The Parsing System Explained（解析系统解释）（112）
				4. Wrapping Up（包起来）（116）
			18. A Generic Tweaker（通用调整器）（116）
				1. Requirements Analysis（需求分析）（116）
				2. Implementation（实现）（116）
				3. Usage（用法）（121）
				4. Graphical User Interface（图形用户界面）（122）
				5. Note（笔记）（123）
				6. Acknowledgment（致谢）（124）
			19. Genuine Random Number Generation（真正的随机数生成）（125）
				1. Pseudo-Randomness（伪随机性）（125）
				2. Genuine Randomness（真正的随机性）（125）
				3. Random Input Sources（随机输入源）（126）
				4. Hardware Sources（硬件资源）（127）
				5. Mixing Function（混合功能）（127）
				6. Limitations（局限性）（127）
				7. Implementation（执行）（128）
				8. How Random Is GenRand?（GenRand  的随机性如何？）（129）
			20. Using Bloom Filters to Improve Computational Performance（使用布隆过滤器提高计算性能）（131）
				1. Bloom's Way（布鲁姆之路）（131）
				2. Possible Scenarios（可能的情况）（131）
				3. How It Works（怎么运行的）（132）
				4. Definitions（定义）（132）
				5. Example 1（实施例1）（133）
				6. Example 2（实施例2）（137）
				7. Final Notes（最后的注释）（137）
				8. Conclusion（结论）（138）
			21. 3ds max Skin Exporter and Animation Toolkit（3ds max 皮肤导出器和动画工具包）（139）
				1. Exporting（出口）（140）
				2. Listing 1.21.1: Exporting the Mesh to a File（清单1.21.1：将网格导出到文件）（147）
				3. Listing 1.21.2: Reading Bone Assignments（清单  1.21.2：读取骨骼分配）（148）
			22. Using Web Cameras in Video Games（在视频游戏中使用网络摄像头）（151）
				1. Initializing the Web Cam Capture Window（初始化网络摄像头捕获窗口）（151）
				2. Manipulating Web Cam Data（操作网络摄像头数据）（156）
				3. Conclusion（结论）（160）
		2. 2
			1. Floating-Point Tricks: Improving Performance with IEEE Floating Point（浮点技巧：利用 IEEE 浮点提高性能）（161）
				1. Overview（概述）（161）
				2. IEEE Floating-Point Format（IEEE  浮点格式）（162）
				3. Floating-Point Tricks（浮点技巧）（163）
				4. Linear Lookup Tables for Sine and Cosine（正弦和余弦线性查找表）（168）
				5. Logarithmic Optimization of Square Root（平方根的对数优化）（170）
				6. Optimization of Arbitrary Functions（任意函数的优化）（171）
				7. Performance Measurement（绩效衡量）（174）
				8. Conclusions（结论）（175）
			2. Vector and Plane Tricks（矢量和平面技巧）（176）
				1. Altitude Relative to the Collision Plane（相对于碰撞平面的高度）（176）
				2. Pinning Down the Collision Point（确定碰撞点）（177）
				3. Distance to the Collision Point（到碰撞点的距离）（178）
				4. Reflecting Off the Collision Plane（从碰撞平面反射）（179）
				5. Collisions with Damping（与阻尼碰撞）（182）
			3. Fast, Robust Intersection of 3D Line Segments（3D 线段的快速、稳健的交集）（185）
				1. What Makes This Algorithm Robust?（是什么让这个算法如此强大？）（185）
				2. The Problem Statement（问题陈述）（185）
				3. Derivation of Closed-Form Solution Equations（闭式解方程的推导）（188）
				4. Dealing with Finite Line Segments（处理有限线段）（194）
				5. Implementation Description（实施说明）（196）
				6. Opportunities to Optimize（优化的机会）（197）
				7. Conclusions（结论）（198）
			4. Inverse Trajectory Determination（逆轨迹确定）（199）
				1. A Special Case:Both Points at the Same Elevation（特殊情况：两个点处于同一高程）（201）
				2. Optimizing Implementation（优化实施）（207）
				3. Summary（概括）（208）
			5. The Parallel Transport Frame（并行传输框架）（209）
				1. The Technique（技术）（209）
				2. Conclusion（结论）（213）
			6. Smooth C2 Quaternion-based Flythrough Paths（基于 C2 四元数的平滑飞行路径）（241）
				1. Introduction（介绍）（214）
				2. Position Interpolation（位置插补）（214）
				3. Orientation Interpolation（方向插补）（216）
				4. Direction of Rotation and Selective Negation（旋转方向和选择性否定）（217）
				5. Spline Interpolation for Quaternions（四元数的样条插值）（218）
				6. Singularity in the Rational Mapping（有理映射中的奇异性）（219）
				7. Camera Cuts（镜头剪辑）（220）
				8. Code（代码）（220）
			7. Recursive Dimensional Clustering: A Fast Algorithm for Collision Detection（递归维度聚类：碰撞检测的快速算法）（222）
				1. Listing 2.7.1 Brute-force comparison algorithm（清单2.7.1 暴力比较算法）（222）
				2. Other Applications（其他应用）（223）
				3. Listing 2.7.2 Algorithm for finding groups along one dimension（清单  2.7.2  沿一维查找群的算法）（224）
				4. A Flaw in the Algorithm（算法中的一个缺陷）（227）
				5. Finding Pairs in Collision（寻找碰撞对）（228）
				6. Listing 2.7.3 RDC algorithm (pseudocode)（清单2.7.3  RDC算法（伪代码））（229）
				7. Time Complexity（时间复杂度）（230）
				8. Conclusion（结论）（231）
			8. Programming Fractals（分形编程）（233）
				1. The Plasma Fractal（等离子体分形）（234）
				2. The Fault Fractal（断层分形）（234）
				3. Fractal Brownian Motion（分形布朗运动）（235）
				4. Implementation（执行）（236）
				5. Using FBM（使用FBM）（239）
		3. 3
			1. Strategies for Optimizing Al（优化人工智能的策略）（241）
				1. Strategy f 1: Use Event-Driven Behavior Rather than Polling（策略  f  1：使用事件驱动的行为而不是轮询）（241）
				2. Strategy #2: Reduce Redundant Calculations（策略#2：减少冗余计算）（242）
				3. Strategy #3: Centralize Cooperation with Managers（策略#3：集中与管理者的合作）（242）
				4. Strategy #4: Run the Al Less Often（策略#4：减少运行  Al  的频率）（243）
				5. Strategy #5: Distribute the Processing over Several Frames（策略#5：将处理分布到多个帧上）（243）
				6. Strategy #6: Employ Level-of-Detail AI（策略#6：采用详细级别的人工智能）（244）
				7. Strategy #7: Solve Only Part of the Problem（策略#7：只解决部分问题）（244）
				8. Strategy #8^ Do the Hard Work Offline（策略  #8^  离线完成艰苦工作）（245）
				9. Strategy #9: Use Emergent Behavior to Avoid Scripting（策略#9：使用紧急行为来避免脚本）（245）
				10. Strategy #10: Amortize Query Costs with Continuous Bookkeeping（策略#10：通过连续记账来摊销查询成本）（245）
				11. Strategy #11; Rethink the Problem（策略#11；重新思考问题）（246）
				12. Conclusion（结论）（247）
			2. Micro-Threads for Game Object Al（游戏对象 AI 的微线程）（248）
				1. A Simpler Method（更简单的方法）（249）
				2. Micro-Threads（微线程）（250）
				3. Stack Management（堆栈管理）（252）
				4. Complications（并发症）（253）
				5. Conclusion（结论）（254）
			3. Managing Al with Micro-Threads（使用微线程管理人工智能）（255）
				1. Piece by Piece（一点一点）（255）
				2. Good Behavior（好的行为）（256）
				3. It's All in the Mind（一切尽在心中）（257）
				4. Complications（并发症）（259）
				5. Conclusion（结论）（261）
			4. An Architecture for RTS Command Queuing（RTS 命令队列架构）（263）
				1. RTS Commands（RTS命令）（263）
				2. Command Queuing（命令排队）（264）
				3. Cyclic Commands（循环命令）（265）
				4. Conclusion（结论）（268）
			5. A High-Performance Tile-based Line-of Sight and Search System（高性能基于平铺的视线和搜索系统）（269）
				1. Overview（概述）（269）
				2. Definitions（定义）（270）
				3. Component #1: Individual Player Visibility Maps（组件#1：单个玩家可见性地图）（270）
				4. Component #2: LOS Templates（组件#2：LOS  模板）（271）
				5. Component #3: The Combined Visibility Map（组件#3：组合可见性图）（273）
				6. Improved Searching（改进的搜索）（274）
				7. Conclusion（结论）（276）
			6. Influence Mapping（影响力图）（277）
				1. Influence Maps（影响力地图）（277）
				2. A Simple Influence Map（简单的影响力图）（278）
				3. Influence Map Cell Data（影响图单元格数据）（279）
				4. Computing Desirability Values（计算意愿值）（280）
				5. Determining Optimal Cell Size（确定最佳单元尺寸）（282）
				6. Influence Propagation（影响力传播）（282）
				7. Accounting for Terrain（考虑地形）（283）
				8. Special Considerations（特别注意事项）（285）
				9. Refreshing the Influence Map（刷新影响力地图）（285）
				10. Influence Maps in 3D Environments（3D  环境中的影响力地图）（286）
			7. Strategic Assessment Techniques（战略评估技术）（288）
				1. The Resource Allocation Tree（资源分配树）（288）
				2. Calculating Desired Allocation（计算所需的分配）（290）
				3. Determining Current Allocation（确定当前分配）（290）
				4. Strategic Decision-Making（战略决策）（291）
				5. Measuring Value（测量值）（292）
				6. The Dependency Graph（依赖图）（292）
				7. Dependency Graph Nodes（依赖图节点）（293）
				8. Economic Planning（经济规划）（294）
				9. Finding Vulnerable Dependencies（查找易受攻击的依赖项）（294）
				10. Strategic Inference（策略推理）（295）
				11. Player Personality（玩家个性）（296）
				12. Putting It All Together（把它们放在一起）（296）
			8. Terrain Reasoning for 3D Action Games（3D 动作游戏的地形推理）（297）
				1. Representing Terrain to Reason About It（代表地形来推理它）（297）
				2. Waypoints（航点）（298）
				3. Example Terrain and AI Needs（地形和  AI  需求示例）（298）
				4. Tactical Analysis（战术分析）（299）
				5. From Tactical Values to Waypoint Properties（从战术价值到航点属性）（300）
				6. Computing Way point Properties（计算路点属性）（301）
				7. Learning from Gameplay Experience（从游戏体验中学习）（304）
				8. Putting Terrain Reasoning in the Game（将地形推理融⼊游戏中）（304）
				9. Other Applications（其他应用）（305）
				10. Conclusion（结论）（305）
			9. Expanded Geometry for Points-of-Visibility Pathfinding（用于可视点寻路的扩展几何形状）（307）
				1. Defining a Collision Model（定义碰撞模型）（308）
				2. Polygonal Pathfinding（多边形寻路）（308）
				3. Expand and Conquer（扩张和征服）（308）
				4. Minkowski Sum of Convex Polygons（凸多边形的闵可夫斯基和）（309）
				5. Expanding Nonconvex Geometry（扩展非凸几何）（311）
				6. Choosing a Collision Shape（选择碰撞形状）（312）
				7. Conclusion（结论）（313）
			10. Optimizing Points-of-Visibility Pathfinding（优化可视点寻路）（314）
				1. Points-of-Visibility Pathfinding（可视点寻路）（314）
				2. Storing the Shortest Path to Each Point（存储到每个点的最短路径）（315）
				3. Connecting the Corners（连接角落）（315）
				4. Silhouette Zones（剪影区）（317）
				5. Using Silhouette Zones with Spatial Partitioning（使用轮廓区域进行空间分区）（319）
				6. Conclusion（结论）（319）
			11. Flocking with Teeth: Predators and Prey（长满牙齿：掠食者和猎物）（320）
				1. A Whole New World（一个全新的世界）（321）
				2. Flocking with Teeth（带齿植绒）（324）
				3. Limitations and Potential Improvements（局限性和潜在改进）（324）
			12. A Generic Fuzzy State Machine in C++（C++ 中的通用模糊状态机）（327）
				1. Why Use a FuSM In a Game?（为什么在游戏中使用  FuSM？）（328）
				2. How To Use FuSMs in a Game（如何在游戏中使用  FuSM）（329）
				3. Review of Game Programming Gems' Generic Finite State Machine in C++（游戏编程 Gems 的 C++ 通用有限状态机回顾）（329）
				4. Adapting the Generic FSM in C++ to FuSM in C++（将  C++  中的通用  FSM  适配为  C++  中的  FuSM）（330）
				5. Now Fuzzy Up Your Games!（现在模糊你的游戏！）（331）
			13. Imploding Combinatorial Explosion in a Fuzzy System（模糊系统中的内爆组合爆炸）（332）
				1. The Problem（问题）（332）
				2. The Solution（解决方案）（333）
				3. Concrete Example（具体例子）（335）
				4. Conclusion（结论）（340）
			14. Using a Neural Network in a Game: A Concrete Example（在游戏中使用神经网络：具体示例）（341）
				1. The Game（游戏）（341）
				2. The Multilayer Perceptron（多层感知器）（341）
				3. Input Selection（输⼊选择）（343）
				4. Collecting Data（收集数据）（344）
				5. Training the MLP（训练  MLP）（345）
				6. Results（结果）（347）
				7. Conclusion（结论）（347）
		4. 4
			1. Comparison of VIPM Methods（VIPM  方法的比较）（348）
				1. Considerations（注意事项）（348）
				2. Vanilla VIPM（350）
				3. Skip Strips（跳过条）（353）
				4. Multilevel Skip Strips（多层跳跃带）（354）
				5. Mixed-Mode VIPM（混合模式  VIPM）（355）
				6. Mixed-Mode Skip Strips（混合模式跳过条）（357）
				7. Sliding Window（滑动窗口）（357）
				8. Summary（概括）（360）
			2. Simplified Terrain Using Interlocking Tiles（使用互锁瓷砖简化地形）（362）
				1. Tiles Revisited（重新审视瓷砖）（343）
				2. Map Making（地图制作）（364）
				3. Tile Templates（平铺模板）（365）
				4. Ugly, Ugl* Ugly（365）
				5. Better, Faster, Stronger（更好、更快、更强）（367）
				6. Conclusion（结论）（367）
			3. Sphere Ttees for Fast Visibility Culling, Ray Tracing, and Range Searching（用于快速可见性剔除、光线追踪和范围搜索的球体 T 恤）（369）
				1. Bounding Spheres（边界球）（369）
				2. Using Sphere Trees（使用球体树）（370）
				3. Demonstration Application（示范应用）（370）
			4. Compressed Axis-Aligned Bounding Box Trees（压缩轴对齐边界框树）（373）
				1. A Brief Survey of Hierarchical Sorting Methods（层次排序方法简述）（373）
				2. AABB Trees（AABB  树）（374）
				3. Building AABB Trees（构建  AABB  树）（375）
				4. Compressing AABB Trees（压缩  AABB  树）（375）
				5. Approximating Extents（近似范围）（376）
				6. Exploiting Redundancy（利用冗余）（377）
				7. Runtime Efficiency（运行时效率）（378）
				8. Future Work（未来的工作）（378）
			5. Direct Access Quadtree Lookup（直接访问四叉树查找）（379）
				1. Where the Performance Goes（性能走向何方）（379）
				2. Eliminating the Middlemen（消除中间商）（380）
				3. Conditions and Requirements（条件和要求）（380）
				4. Determining the Tree Level（确定树级别）（381）
				5. Mapping to the Situation（映射到情况）（383）
				6. Determining the Location（确定位置）（384）
				7. Traversing the Quadtree（遍历四叉树）（384）
				8. Tuning the Quadtree（调整四叉树）（384）
				9. Listing 4.5.1 Simple implementation of quadtree search（清单4.5.1  四叉树搜索的简单实现）（385）
				10. Listing 4.5.2 Code to determine the level of the target quadnode（清单4.5.2  确定目标四节点级别的代码）（386）
				11. Listing 4.5.3 Code to determine the level of the target quadnode（清单  4.5.3  确定目标四元节点的级别的代码QuadNode*）（386）
			6. Approximating Fish Tank Refractions（近似鱼缸折射）（387）
				1. Fish Tank Observations（鱼缸观察）（387）
				2. Improving the Reality（改善现实）（390）
				3. Conclusion（结论）（390）
			7. Rendering Print Resolution Screenshots（渲染打印分辨率屏幕截图）（391）
				1. Basic Algorithm（基本算法）（391）
				2. Caveats and Concerns（注意事项和疑虑）（394）
				3. Conclusion（结论）（395）
			8. Applying Decals to Arbitrary Surfaces（将贴花应用于任意表面）（396）
				1. The Algorithm（算法）（396）
				2. Triangle Clipping（三角形剪裁）（398）
				3. Implementation（执行）（399）
			9. Rendering Distant Scenery with Skyboxes（使用天空盒渲染远处的风景）（401）
				1. Basic Technique（基本技术）（401）
				2. Skybox Resolution（天空盒分辨率）（401）
				3. Skybox Size（天空盒尺寸）（403）
				4. Rendering the Scene（渲染场景）（403）
				5. Cube Environment Mapping（立方体环境映射）（404）
				6. Generating Skybox Textures（生成天空盒纹理）（404）
				7. Conclusion（结论）（405）
				8. Source Code（源代码）（405）
			10. Self-Shadowing Characters（自我阴影角色）（406）
				1. Previous Work（之前的工作）（406）
				2. Segmenting Character Geometry（分割角色几何形状）（406）
				3. Rendering the Texture（渲染纹理）（407）
				4. Rendering the Character（渲染角色）（408）
				5. Conclusion（结论）（408）
			11. Classic Super Mario 64 Third-Person Control and Animation（经典《超级马里奥 64》第三人称控制和动画）（410）
				1. The Setup（设置）（410）
				2. Converting the Controller Input（转换控制器输入）（410）
				3. Rotating the Character（旋转角色）（412）
				4. Translating the Character（平移角色）（413）
				5. Animating the Character（动画角色）（414）
				6. Super Mario 64 Animation Analyzed（《超级马里奥  64》动画分析）（416）
				7. Conclusion（结论）（417）
		5. 5
			1. Cartoon Rendering: Real-time Silhouette Edge Detection and Rendering（卡通渲染：实时轮廓边缘检测与渲染）（418）
				1. Inker（墨客）（418）
				2. Important Edges（重要的优势）（419）
				3. Silhouette Edge Detection Techniques（轮廓边缘检测技术）（420）
				4. Edge-based Inking（基于边缘的墨迹）（420）
				5. Listing 5.1.1 Edge-based silhouette edge detection（Listing  5.1.1  基于边缘的轮廓边缘检测）（421）
				6. Programmable Vertex Shader Inking（可编程顶点着色器墨迹）（422）
				7. Listing 5.1.2 Silhouette shader for DirectX 8.0 vertex programmable shading（清单 5.1.2 DirectX 8.0 顶点可编程着色的轮廓着色器）（423）
				8. Inking with Advanced Texture Features（使用高级纹理功能上墨）（424）
				9. Conclusion（结论）（425）
			2. Cartoon Rendering Using Texture Mapping and Programmable Vertex Shaders（使用纹理映射和可编程顶点着色器进行卡通渲染）（426）
				1. Cartoon Shading（卡通底纹）（426）
				2. Painting（绘画）（426）
				3. Listing 5.2.1 Function for computing Toon texture coordinates（清单  5.2.1  计算  Toon  纹理坐标的函数）（428）
				4. Programmable Vertex Shaders（可编程顶点着色器）（430）
				5. Listing 5.2.2 DirectX 8.0 cartoon programmable vertex shader（清单 5.2.2 DirectX 8.0 卡通可编程顶点着色器）（431）
				6. Conclusion（结论）（432）
			3. Dynamic Per-Pixel Lighting Techniques（动态每像素照明技术）（434）
				1. 3D Textures for Dynamic Lightmapping（用于动态光照贴图的  3D  纹理）（434）
				2. Listing 5.3.1 Code to generate 3D lightmap with quadratic falloff（清单  5.3.1  生成具有二次衰减的  3D  光照贴图的代码）（435）
				3. Dot3 Bump Mapping（Dot3  凹凸贴图）（438）
				4. Cubemap Normalizer（立方体贴图标准化器）（441）
				5. Per-Pixel Spotlights（每像素聚光灯）（442）
			4. Generating Procedural Clouds Using 3D Hardware（使用 3D 硬件生成程序云）（445）
				1. Properties of Clouds（云的属性）（445）
				2. Random Number Generation（随机数生成）（446）
				3. Listing 5.4.1 A simple pseudo-random number generator（清单  5.4.1  一个简单的伪随机数生成器）（447）
				4. Animating an Octave of Noise（制作八度噪声的动画）（448）
				5. Listing 5.4.2 Noise octave composition（清单  5.4.2  噪声倍频程组成）（449）
				6. Mapping It to the Sky Geometry（将其映射到天空几何形状）（451）
				7. Feature Creep（特征蠕变）（452）
				8. Hardware Limitations（硬件限制）（453）
				9. Making It Scale（使其规模化）（453）
				10. Conclusion（结论）（454）
			5. Texture Masking for Faster Lens Flare（纹理遮罩可实现更快的镜头光晕）（456）
				1. Lens Flare Occlusion（镜头光晕遮挡）（456）
				2. Hardware Issues（硬件问题）（457）
				3. Texture Masking（纹理遮蔽）（459）
				4. Performance Considerations（性能考虑因素）（461）
				5. Improvements（改进）（461）
				6. Sample Code（示例代码）（462）
				7. Alternative Approaches（替代方法）（462）
			6. Practical Priority Buffer Shadows（实用的优先级缓冲区阴影）（463）
				1. Comparing Priority Buffers to Depth Buffers（比较优先级缓冲区与深度缓冲区）（465）
				2. Resolving Aliasing Problems（解决别名问题）（466）
				3. Hybrid Approaches（混合方法）（468）
				4. Summary（概括）（469）
			7. Impostors: Adding Clutter（冒名顶替者：增加混乱）（470）
				1. The Whole Process（整个过程）（470）
				2. Rendering the Impostor（渲染冒名顶替者）（471）
				3. Update Heuristics（更新启发式）（475）
				4. Efficiency（效率）（476）
				5. Prediction（预言）（477）
				6. Summary（概括）（477）
			8. Operations for Hardware Accelerated Procedural Texture Animation（硬件加速程序纹理动画的操作）（479）
				1. Hardware Operations（硬件操作）（479）
				2. Listing 5.8.1. Code and vertex program for sampling each texel's neighbors（清单 5.8.1。 用于对每个纹素的邻居进行采样的代码和顶点程序）（481）
				3. Listing 5.8.2 Code for RGB normal map creation in hardware from a grayscale height texture. The grayscale image is selected into all four texture stages, and offsets A from Listing 5.8.1 are used.（清单 5.8.2 在硬件中从灰度高度纹理创建 RGB 法线贴图的代码。 灰度图像被选择到所有四个纹理阶段，并使用清单 5.8.1 中的偏移量 A。）（486）
				4. Future Work（未来的工作）（490）
				5. Code Samples（代码示例）（491）
		6. 6
			1. Game Audio Design Patterns（游戏音频设计模式）（492）
				1. Bridge（桥）（492）
				2. Facade（正面）（493）
				3. Composite（合成的）（493）
				4. Proxy（代理人）（494）
				5. Decorator（装饰者）（495）
				6. Command（命令）（495）
				7. Memento（纪念）（496）
				8. Observer（观察者）（496）
				9. Big Ball Of Mud (also known as Spaghetti Code)（大泥球（也称为意大利面条代码））（496）
				10. Conclusion（结论）（498）
			2. A Technique to Instantaneously Reuse Voices in a Sample-based Synthesizer（在基于样本的合成器中即时重用声音的技术）（499）
				1. The Problem（问题）（499）
				2. An Idea for a Solution（解决方案的想法）（500）
				3. The Solution（解决方案）（501）
				4. Conclusion（结论）（502）
			3. Software-based DSP Effects（基于软件的  DSP  效果）（503）
				1. Filtering（过滤）（503）
				2. Convolution（卷积）（504）
				3. Delay（延迟）（505）
				4. Interpolation（插值法）（506）
			4. Interactive Processing Pipeline for Digital Audio（数字音频交互式处理管道）（507）
				1. Discussion（讨论）（509）
				2. The Code（代码）（512）
				3. Extra Commentary（额外评论）（515）
				4. Conclusion（结论）（516）
			5. A Basic Music Sequencer for Games（游戏的基本音乐音序器）（517）
				1. Streaming vs. Sequencing（流式传输与排序）（517）
				2. Core Computer Music Concepts（核心计算机音乐概念）（518）
				3. Computer Music Sequencer Implementation（计算机音乐音序器的实现）（521）
				4. Listing 6.5.1 Music sequencer data structures（清单  6.5.1  音乐音序器数据结构）（523）
				5. Listing 6.5.2 Event type data structures（清单  6.5.2  事件类型数据结构）（524）
				6. Listing 6.5.3 The audio frame（清单  6.5.3  音频帧）（526）
				7. Listing 6.5.4 Time step calculation（清单6.5.4  时间步计算）（527）
				8. Audio Synthesis Control（音频合成控制）（527）
				9. The Code（代码）（528）
				10. Conclusions（结论）（528）
			6. An Interactive Music Sequencer for Games（游戏的交互式音乐音序器）（529）
				1. Musical Associations（音乐协会）（529）
				2. Musical Meaning（音乐意义）（530）
				3. Transitions（过渡）（531）
				4. Transition Types（过渡类型）（531）
				5. Control Granularity（控制粒度）（532）
				6. Target Control（目标控制）（533）
				7. Listing 6.6.1 Sequencer data structures with target control（清单  6.6.1  具有目标控制的定序器数据结构）（533）
				8. Design Examples（设计实例）（534）
				9. The Code（代码）（536）
				10. Conclusion（结论）（536）
			7. A Low-Level Sound API（低级声音  API）（537）
				1. Core Classes（核心课程）（537）
	7. Game Programming Gems 7（游戏编程精粹7）
		1. GENERAL PROGRAMMING（一般的编程）（34）
			1. Efficient Cache Replacement Using the Age and Cost Metrics（使用寿命和成本指标进行高效缓存替换）（38）
				1. Overview（概述）（38）
				2. Cache-Replacement Algorithms（缓存替换算法）（39）
				3. Age and Cost Metrics（年龄和成本指标）（41）
				4. Conclusion（结论）（46）
			2. High Performance Heap Allocator（高性能堆分配器）（48）
				1. Introduction（介绍）（48）
				2. Related Works（相关作品）（48）
				3. Our Solution（我们的解决方案）（49）
				4. On the CD（光盘上）（56）
			3. Optical Flow for Video Games Played with Webcams（使用网络摄像头玩视频游戏的光流）（58）
				1. Introduction（介绍）（58）
				2. OpenCV Code（OpenCV  代码）（59）
				3. First Method: Image Differences（第一种方法：图像差异）（60）
				4. Second Method: Motion History（第二种方法：运动历史记录）（61）
				5. Third Method: Lucas and Kanade Algorithm（第三种方法：Lucas和Kanade算法）（62）
				6. Optical Flow Game（光流游戏）（63）
			4. Design and Implementation of a Multi-Platform Threading Engine（多平台线程引擎的设计与实现）（68）
				1. Threads（线程数）（71）
				2. Thread Allocation Strategies（线程分配策略）（74）
				3. Object Threading（对象线程）（75）
				4. Thread Safety, Reentrancy, Object Synchronicity,  and Data Access（线程安全、重入、对象同步和数据访问）（76）
				5. Dancing the Line (or Cache Coherency)（跳舞（或缓存一致性））（76）
				6. How to Use the GLRThreading Library（如何使用  GLRThreading  库）（77）
				7. Conclusion（结论）（78）
			5. For Bees and Gamers: How to Handle Hexagonal Tiles（对于蜜蜂和游戏玩家：如何处理六角形瓷砖）（80）
				1. Introduction（介绍）（80）
				2. Mastering the Hexagonal Grid（掌握六角形网格）（84）
				3. Implementation Tips（实施技巧）（87）
				4. Applications（应用领域）（88）
				5. Conclusion（结论）（90）
			6. A Sketch-Based Interface to Real-Time Strategy Games Based on a Cellular Automaton（基于元胞自动机的实时策略游戏的草图界面）（92）
				1. Focus-Context Control Level（焦点‑上下文控制级别）（94）
				2. Implementation Details（实施细节）（95）
				3. Conclusion（结论）（99）
			7. Foot Navigation Technique for First-Person Shooting Games（第一人称射击游戏的足部导航技术）（102）
				1. Introduction（介绍）（102）
				2. Navigating with the Foot（用脚导航）（103）
				3. A Sample Game（示例游戏）（108）
				4. Tests with Real Users（与真实用户进行测试）（110）
				5. Conclusion（结论）（111）
				6. Future Work（未来的工作）（111）
			8. Deferred Function Call Invocation System（延迟函数调用调用系统）（114）
				1. A Matter of Time（时间的问题）（114）
				2. Case Studies（实例探究）（115）
				3. Categorizing a Function Call（对函数调用进行分类）（116）
				4. A Look at the System（系统概览）（117）
				5. Conclusion（结论）（118）
			9. Multithread Job and Dependency System（多线程作业和依赖系统）（120）
				1. Introduction（介绍）（120）
				2. The Job System（职位系统）（121）
				3. The Dependency Manager（依赖管理器）（124）
				4. Future Work（未来的工作）（127）
				5. Conclusion（结论）（128）
			10. Advanced Debugging Techniques（先进的调试技术）（130）
				1. Application Crashes（应用程序崩溃）（130）
				2. Memory Leaks（内存泄漏）（133）
				3. Windows Error Reporting (WER)（Windows  错误报告  (WER)）（135）
				4. The Framework（框架）（136）
				5. Conclusion（结论）（137）
		2. MATH AND PHYSICS（数学和物理）（140）
			1. Random Number Generation（随机数生成）（146）
				1. Background: Random Number Generation（背景：随机数生成）（146）
				2. Non-Cryptographic RNG Methods（非加密  RNG  方法）（149）
				3. Cryptographic RNG Methods（加密  RNG  方法）（154）
				4. Common Mistakes in Creating Random Number Generators（创建随机数生成器的常见错误）（155）
				5. Code（代码）（157）
				6. Conclusion（结论）（157）
			2. Fast Generic Ray Queries for Games（游戏的快速通用射线查询）（160）
				1. Introduction to Ray Tracing（光线追踪简介）（160）
				2. kD-Tree Concepts and Storage Considerations（kD  树概念和存储注意事项）（162）
				3. Dynamic Objects（动态对象）（172）
				4. Demo Application（演示应用程序）（172）
				5. Conclusion（结论）（173）
			3. Fast Rigid-Body Collision Detection Using Farthest Feature Maps（使用最远特征图进行快速刚体碰撞检测）（176）
				1. Background（背景）（177）
				2. Preprocessing（预处理）（177）
				3. Runtime Queries（运行时查询）（181）
				4. Performance Analysis and Concluding Remarks（绩效分析及总结）（183）
			4. Using Projective Space to Improve Precision of Geometric Computations（利用射影空间提高几何计算的精度）（186）
				1. Projective Space（投影空间）（187）
				2. Basic Objects in R2（188）
				3. Points and Directed Lines in RP2（RP2  中的点和有向线）（188）
				4. Basic Operations in RP2（RP2  中的基本操作）（190）
				5. Precise Geometrical Computations in RP2 Using Integer Coordinates（使用整数坐标在 RP2 中进行精确几何计算）（191）
				6. Number Range Limits in Geometrical Computations in RP2（RP2  中几何计算的数值范围限制）（191）
				7. Example Application of Operations in RP2（RP2  中运算的示例应用）（194）
				8. Extension into the Third Dimension（延伸至第三维度）（197）
				9. Conclusion（结论）（197）
			5. XenoCollide: Complex Collision Made Simple（XenoCollide：复杂碰撞变得简单）（198）
				1. Introduction（介绍）（198）
				2. Representing Shapes with Support Mappings（用支撑映射表示形状）（199）
				3. Simplifying Collision Detection Using Minkowski Differences（使用  Minkowski  差异简化碰撞检测）（203）
				4. Detecting Collision Using Minkowski Portal Refinement（使用  Minkowski  Portal  细化检测碰撞）（204）
				5. Using MPR for Contact Information（使用  MPR  获取联系信息）（209）
				6. Conclusion（结论）（211）
			6. Efficient Collision Detection Using Transformation Semantics（使用转换语义进行高效碰撞检测）（212）
				1. Affine Transforms and Games（仿射变换和博弈）（213）
				2. Extracting Semantics from Matrices（从矩阵中提取语义）（214）
				3. Using Semantics for Collision Detection Tasks（使用语义进行碰撞检测任务）（217）
				4. Conclusion（结论）（221）
			7. Trigonometric Splines（三角样条）（224）
				1. Background（背景）（225）
				2. Discussion（讨论）（228）
				3. Conclusion（结论）（229）
			8. Using Gaussian Randomness to Realistically Vary Projectile Paths（使用高斯随机性来真实地改变射弹路径）（232）
				1. Gaussian Distribution（高斯分布）（232）
				2. Generating Gaussian Randomness（生成高斯随机性）（233）
				3. Additional Applications（附加应用）（236）
				4. Gaussian Distributions in Nature（自然界中的高斯分布）（236）
				5. Conclusion（结论）（237）
		3. AI（238）
			1. Creating Interesting Agents with Behavior Cloning（通过行为克隆创建有趣的代理）（242）
				1. Example: The Demo Game（示例：演示游戏）（243）
				2. Conclusion（结论）（249）
			2. Designing a Realistic and Unified Agent-Sensing Model（设计现实且统一的代理感知模型）（250）
				1. The Basic Vision Model（基本视觉模型）（250）
				2. The Basic Hearing Model（基本听力模型）（252）
				3. Augmenting the Vision Model Toolbox with Ellipses（使用椭圆增强视觉模型工具箱）（252）
				4. Modeling Human Vision with Certainty（准确地模拟人类视觉）（255）
				5. Modeling Human Hearing with Certainty（准确地模拟人类听力）（257）
				6. Unified Sensing Model（统一感知模型）（259）
				7. Adding Memory to the Unified Sensing Model（为统一感知模型添加内存）（260）
				8. Conclusion（结论）（261）
			3. Managing AI Algorithmic Complexity: Generic Programming Approach（管理人工智能算法复杂性：通用编程方法）（262）
				1. Introduction（介绍）（262）
				2. Action Choosing Workflow（操作选择工作流程）（263）
				3. Implementation（执行）（271）
				4. Conclusion（结论）（280）
			4. All About Attitude:  Building Blocks for Opinion, Reputation, and NPC Personalities（态度决定一切：意见、声誉和 NPC 个性的基石）（282）
				1. Introduction（介绍）（282）
				2. Attitude（态度）（283）
				3. What’s in an Attitude?（态度是什么？）（285）
				4. Complex Attitude Objects（复杂的态度对象）（289）
				5. Attitude and Behavior（态度和行为）（291）
				6. Persuasion and Influence（说服力和影响力）（292）
				7. Social Exchanges of Attitudes（社会态度交流）（293）
				8. Another Example（另一个例子）（294）
				9. Cautions and Conclusion（注意事项和结论）（295）
			5. Understanding Intelligence in Games Using Player Traces and Interactive Player Graphs（使用玩家轨迹和交互式玩家图了解游戏中的智能）（298）
				1. Introduction（介绍）（298）
				2. The Value of Information（信息的价值）（299）
				3. Interactive Player Graphs（交互式玩家图表）（306）
				4. A Deeper Understanding of Behavior（对行为的更深入理解）（311）
				5. Conclusion（结论）（312）
			6. Goal-Oriented Plan Merging（目标导向的计划合并）（314）
				1. Review of Goal-Oriented Planning Systems（以目标为导向的规划系统的审查）（314）
				2. Plan Merging for Goal-Oriented Plans（以目标为导向的计划的计划合并）（316）
				3. Conclusion（结论）（319）
			7. Beyond A*: IDA* and Fringe Search（超越 A*：IDA* 和边缘搜索）（322）
				1. A* and Dijkstra（A*  和迪杰斯特拉）（323）
				2. The Iterative Deepening A* (IDA*)（迭代深化  A*  (IDA*)）（325）
				3. The Fringe Search Algorithm（边缘搜索算法）（326）
				4. Conclusion（结论）（327）
		4. AUDIO（声音的）（328）
			1. Audio Signal Processing Using Programmable Graphics Hardware（使用可编程图形硬件进行音频信号处理）（332）
				1. GPGPU Programming Overview（GPGPU  编程概述）（333）
				2. Audio Effects（音频效果）（334）
				3. Room Acoustics（室内声学）（335）
				4. Conclusion（结论）（336）
			2. MultiStream—The Art of Writing a Next-Gen Audio Engine（MultiStream——编写下一代音频引擎的艺术）（338）
				1. How It All Began（一切是如何开始的）（339）
				2. Understanding “Next-Gen” Audio（了解“下一代”音频）（339）
				3. Surround Sound（环绕声）（348）
				4. Routing（路由）（351）
				5. Conclusion（结论）（352）
			3. Listen Carefully, You Probably Won’t Hear This Again（仔细听，你可能不会再听到这个）（354）
				1. How It Works; Thinking Differently（怎么运行的;换个角度思考）（355）
				2. Going Bang!（爆炸！）（355）
				3. The Old and the New（新与旧）（357）
				4. New Tools for a New Approach（新方法新工具）（359）
				5. Micromanagement（微观管理）（361）
				6. Why Are We Doing This Again?（我们为什么要再次这样做？）（361）
				7. Going Further（更进一步）（362）
				8. Conclusion（结论）（363）
			4. Real-Time Audio Effects Applied（应用实时音频效果）（364）
				1. Overview of a Sound System（音响系统概述）（365）
				2. Sound Buffers（声音缓冲器）（366）
				3. Rank Buffers（排名缓冲区）（367）
				4. Effects and Filters（效果和滤镜）（369）
				5. Compression and Streaming（压缩和流媒体）（370）
				6. Conclusion（结论）（371）
			5. Context-Driven, Layered Mixing（上下文驱动的分层混合）（374）
				1. Overview（概述）（374）
				2. Implementation（执行）（375）
				3. Extending the Concept with Live Tuning（通过实时调音扩展概念）（378）
				4. Performance（表现）（379）
				5. Sample Program（示例程序）（380）
				6. Conclusion（结论）（380）
		5. GRAPHICS（图形）（382）
			1. Advanced Particle Deposition（先进的粒子沉积）（386）
				1. Why Particles?（为什么是粒子？）（386）
				2. Particle Deposition（粒子沉积）（386）
				3. Conclusion（结论）（397）
			2. Reducing Cumulative Errors in Skeletal Animations（减少骨骼动画中的累积误差）（398）
				1. A Quick Tour of Game Animation Systems（游戏动画系统快速浏览）（398）
				2. Cumulative Error（累计误差）（399）
				3. Conclusion（结论）（403）
			3. An Alternative Model for Shading of Diffuse Light for Rough Materials（粗糙材料漫射光着色的替代模型）（406）
				1. Introduction（介绍）（406）
				2. The Flattening Effect（扁平化效应）（408）
				3. Backscattering（后向散射）（410）
				4. Conclusion（结论）（412）
			4. High-Performance Subdivision Surfaces（高性能细分曲面）（414）
				1. Introduction to Subdivision Schemes（细分方案简介）（414）
				2. Loop Subdivision Features and Options（循环细分功能和选项）（416）
				3. Subdivision Data Structure（细分数据结构）（423）
				4. Subdivision Algorithm Details（细分算法详细信息）（425）
				5. Performance Issues（性能问题）（429）
				6. Conclusion（结论）（432）
			5. Animating Relief Impostors Using Radial Basis Functions Textures（使用径向基函数纹理对浮雕冒名顶替者进行动画处理）（434）
				1. Introduction（介绍）（435）
				2. Image Warping（图像变形）（436）
				3. Radial Basis Functions（径向基函数）（437）
				4. Interpolating the Warping Functions（插值扭曲函数）（437）
				5. Evaluating the Warping Function Using Shaders（使用着色器评估扭曲函数）（438）
				6. Animating Relief Maps（地形图动画）（440）
				7. Animating Relief Impostors（动画救济冒名顶替者）（440）
				8. Results（结果）（442）
				9. Conclusion（结论）（443）
			6. Clipmapping on SM1.1 and Higher（SM1.1 及更高版本上的剪辑贴图）（446）
				1. Basic Concepts of Clipmaps（剪贴图的基本概念）（446）
				2. Implementation of Clipmaps（剪贴图的实现）（447）
				3. If You Want To Save Some Time...（如果您想节省一些时间...）（454）
			7. An Advanced Decal System Joris Mans（先进的贴花系统 Joris Mans）（456）
				1. Requirements（要求）（456）
				2. Normal Decals Method（普通贴花法）（457）
				3. Advanced Decals Method（高级贴花方法）（457）
				4. Advantages of This Advanced Decal System（这种先进贴花系统的优点）（461）
				5. Performance and Experimental Results（性能与实验结果）（463）
				6. Demo（演示）（466）
				7. Conclusion（结论）（466）
			8. Mapping Large Textures for Outdoor Terrain Rendering（映射大型纹理以进行室外地形渲染）（468）
				1. Introduction（介绍）（468）
				2. Structure（结构）（470）
				3. Updating the Contents of the Cache（更新缓存的内容）（473）
				4. Rendering Issues（渲染问题）（475）
				5. Results（结果）（477）
				6. Conclusion（结论）（478）
			9. Art-Based Rendering with Graftal Imposters（使用移植冒名顶替者进行基于艺术的渲染）（480）
				1. Assets（资产）（480）
				2. Runtime（运行）（483）
				3. Acknowledgements（致谢）（486）
				4. Conclusion and Future Work（结论和未来的工作）（486）
			10. Cheap Talk: Dynamic Real-Time Lipsync（廉价谈话：动态实时口型同步）（488）
				1. Requirements（要求）（488）
				2. General Procedure（一般程序）（490）
				3. Conclusion（结论）（494）
		6. NETWORKING AND MULTIPLAYER（网络和多人游戏）（496）
			1. High-Level Abstraction of Game World Synchronization（游戏世界同步的高级抽象）（500）
				1. HLA Usage（HLA用途）（501）
				2. Anatomy of Game World Synchronization（游戏世界同步剖析）（501）
				3. HLA Components（HLA  成分）（503）
				4. Viewports in HLA Runtime（HLA  运行时中的视口）（509）
				5. Further Issues（进一步的问题）（511）
				6. Conclusion（结论）（512）
			2. Authentication for Online Games（网络游戏认证）（514）
				1. Introduction（介绍）（514）
				2. Securing Game Logins（保护游戏登录安全）（514）
				3. Securing Game Sessions（确保游戏会话安全）（518）
				4. Conclusion（结论）（520）
			3. Game Network Debugging with Smart Packet Sniffers（使用智能数据包嗅探器进行游戏网络调试）（524）
				1. The Smart Packet Sniffer Concept（智能数据包嗅探器概念）（524）
				2. An Example（一个例子）（524）
				3. Gotchas with Traditional Debugging Techniques（传统调试技术的陷阱）（525）
				4. Implementation（执行）（526）
				5. Using the WinPcap Library（使用  WinPcap  库）（527）
				6. Security Risk Reduction（降低安全风险）（528）
				7. An Alternative（替代）（529）
				8. Sample Code（示例代码）（529）
				9. Conclusion（结论）（530）
		7. SCRIPTING AND DATA-DRIVEN SYSTEMS（脚本和数据驱动系统）（532）
			1. Automatic Lua Binding System（自动Lua绑定系统）（536）
				1. Introduction（介绍）（536）
				2. Binding of C Functions（C  函数的绑定）（537）
				3. Object-Oriented in Lua（Lua  中的面向对象）（537）
				4. Binding C++ Objects in Lua（在  Lua  中绑定  C++  对象）（538）
				5. Extending the Binding System（扩展绑定系统）（543）
				6. Summary（概括）（546）
				7. Future Work（未来的工作）（546）
				8. Demo（演示）（549）
				9. Conclusion（结论）（549）
			2. Serializing C++ Objects into a Database Using Introspection（使用内省将 C++ 对象序列化到数据库中）（550）
				1. Metadata（元数据）（550）
				2. Arrays（数组）（551）
				3. Serializing in Text（在文本中序列化）（551）
				4. The Database System（数据库系统）（552）
				5. The Demo（演示）（565）
				6. Issues and Future Improvements（问题和未来的改进）（565）
				7. Conclusion（结论）（566）
			3. Dataports（数据端口）（568）
				1. Conceptual Overview（概念概述）（568）
				2. Type Safety（类型安全）（570）
				3. Reference Counting（引用计数）（570）
				4. Practical Examples（实际例子）（571）
				5. Problems（问题）（572）
				6. Conclusion（结论）（573）
			4. Support Your Local Artist: Adding Shaders to Your Engine（支持您的本地艺术家：将着色器添加到您的引擎中）（574）
				1. Shader Terminology（着色器术语）（574）
				2. Programs and Parameters and Managers, Oh My!（程序、参数和管理器，天哪！）（575）
				3. Flexibility Is Key（灵活性是关键）（576）
				4. Prototypes（原型）（577）
				5. Shader Parameters（着色器参数）（579）
				6. Use Case—The Blimp Target（用例——飞艇目标）（582）
				7. Advanced Techniques（先进技术）（584）
				8. Future Work（未来的工作）（586）
				9. Conclusion（结论）（586）
			5. Dance with Python’s AST（与 Python 的 AST 共舞）（588）
				1. Introduction（介绍）（588）
				2. Background（背景）（588）
				3. Solution（解决方案）（589）
				4. Conclusion（结论）（592）
	8. Game Programming Gems 8（游戏编程精粹8）
		1. GRAPHICS（图形）（16）
			1. Fast Font Rendering with Instancing（通过实例快速渲染字体）（18）
				1. Text-Rendering Basics（文本渲染基础知识）（18）
				2. Improving Performance（提高绩效）（20）
				3. Instancing Quad Geometry（实例化四边形几何体）（22）
				4. Constant Array Instancing（常量数组实例化）（22）
				5. Additional Considerations（其他注意事项）（24）
				6. Future Work（未来的工作）（25）
				7. Demo（演示）（26）
				8. Conclusion（结论）（26）
			2. Principles and Practice of Screen Space Ambient Occlusion（屏幕空间环境光遮挡的原理与实践）（27）
				1. Screen Space Ambient Occlusion（屏幕空间环境光遮挡）（29）
				2. Generating the Source Data（生成源数据）（30）
				3. Sampling Process（取样流程）（32）
				4. Sampling Randomization（随机抽样）（36）
				5. Ambient Occlusion Post-Processing（环境光遮挡后处理）（39）
				6. Handling Edge Cases（处理边缘情况）（41）
				7. Optimizing Performance（优化性能）（42）
				8. Fake Global Illumination and Artistic Styling（假全局照明和艺术造型）（42）
				9. Transparency（透明度）（44）
				10. Final Results（最终结果）（45）
				11. Conclusion（结论）（45）
			3. Multi-Resolution Deferred Shading（多分辨率延迟着色）（47）
				1. Deferred Shading（延迟着色）（48）
				2. Multi-Resolution Deferred Shading（多分辨率延迟着色）（49）
				3. Conclusion and Future Work（结论和未来的工作）（53）
			4. View Frustum Culling of Catmull-Clark Patches in DirectX 11（查看 DirectX 11 中 Catmull-Clark 补丁的视锥体剔除）（54）
				1. Background（背景）（54）
				2. Culling（剔除）（58）
				3. Pre-Processing Step（预处理步骤）（58）
				4. Run-Time Step（运行时步骤）（59）
				5. Performance（表现）（61）
				6. Conclusion（结论）（64）
			5. Ambient Occlusion Using DirectX Compute Shader（使用 DirectX 计算着色器的环境光遮挡）（65）
				1. The Compute Shader（计算着色器）（66）
				2. Screen Space Ambient Occlusion（屏幕空间环境光遮挡）（70）
				3. Compute Shader Implementation Details（计算着色器实现细节）（79）
				4. Results（结果）（85）
				5. Conclusion and Future Work（结论和未来的工作）（87）
			6. Eye-View Pixel Anti-Aliasing for Irregular Shadow Mapping（用于不规则阴影映射的眼视像素抗锯齿）（89）
				1. Background and Problem: Shadow Edge Aliasing（背景和问题：阴影边缘锯齿）（90）
				2. Solution: Adaptive Multi-Sampling of Irregular Shadows（解决方案：不规则阴影的自适应多重采样）（94）
				3. Results and Discussion（结果与讨论）（100）
				4. Conclusion（结论）（103）
			7. Overlapped Execution on Programmable Graphics Hardware（可编程图形硬件上的重叠执行）（105）
				1. Introduction to Irregular Z-Buffer Shadows（不规则  Z  缓冲区阴影简介）（105）
				2. Overview of Programmable Graphics Hardware（可编程图形硬件概述）（108）
				3. Overview of Task-Based Parallelism（基于任务的并行性概述）（109）
				4. Combining Render Graphs and Task Graphs（组合渲染图和任务图）（110）
				5. Combined Dependency Graph（组合依赖图）（112）
				6. Idle-Free Irregular Z-Buffer Shadows（无空闲不规则  Z  缓冲区阴影）（113）
				7. Conclusion（结论）（114）
			8. Techniques for Effective Vertex and Fragment Shading on the SPUs（SPU 上有效顶点和片段着色的技术）（116）
				1. The CBE as Part of a Real-World System（CBE  作为现实世界系统的一部分）（116）
				2. The SPEs（117）
				3. Data Management（数据管理）（120）
				4. Vertex/Geometry Shading（顶点/几何着色）（123）
				5. Fragment Shading（片段着色）（127）
				6. Further Work（进一步的工作）（130）
				7. Conclusion（结论）（131）
		2. PHYSICS AND ANIMATION（物理和动画）（134）
			1. A Versatile and Interactive Anatomical Human Face Model（多功能交互式解剖人脸模型）（136）
				1. Overview（概述）（137）
				2. Numerical Simulation（数值模拟）（137）
				3. Building the Anatomical Model（建立解剖模型）（140）
				4. Conclusion（结论）（146）
			2. Curved Paths for Seamless Character Animation（无缝角色动画的曲线路径）（147）
				1. Related Work（相关工作）（147）
				2. Finding a Path（寻找路径）（148）
				3. Smoothing the Path（平滑路径）（150）
				4. Animation Selection（动画选择）（152）
				5. Conclusion（结论）（154）
			3. Non-Iterative, Closed-Form, Inverse Kinematic Chain Solver (NCF IK) （非迭代、闭式、逆运动链求解器 (NCF IK)）（156）
				1. Context（语境）（157）
				2. Bone Definition（骨骼定义）（157）
				3. IK Goal Position（IK  目标位置）（157）
				4. Handling Extreme Deformation（处理极端变形）（163）
				5. Additional Details（额外细节）（164）
				6. Future Work（未来的工作）（165）
				7. Conclusion（结论）（166）
			4. Particle Swarm Optimization for Game Programming（游戏编程的粒子群优化）（167）
				1. A Few Words on Optimization（关于优化的几句话）（167）
				2. The PSO Paradigm and Its Canonical Formulation（PSO  范式及其规范表述）（168）
				3. Add-Ons to the Classical Formulation（经典配方的附加成分）（173）
				4. A Note on Randomness（关于随机性的注释）（176）
				5. Case Study 1: Typical Benchmarking Functions（案例研究  1：典型的基准测试功能）（177）
				6. Case Study 2:  Optimization of Physical Parameters  for In-Game Vehicle Simulation（案例研究2：游戏中车辆模拟的物理参数优化）（177）
				7. Case Study 3: Physics-Based Animation of Mechanical Systems（案例研究  3：基于物理的机械系统动画）（179）
				8. Conclusion（结论）（181）
			5. Imp roved Numerical Integration with Analytical Techniques（通过分析技术改进数值积分）（183）
				1. Classifying Errors（错误分类）（184）
				2. Kinematics of Constant Acceleration（恒定加速度的运动学）（184）
				3. The Kinematic Integrator（运动学积分器）（185）
				4. Integral Contributions Due to a Spring Force（弹簧力的整体贡献）（187）
				5. Multiple Forces（多重力量）（188）
				6. Integral Contributions of a Pulse（脉冲的积分贡献）（190）
				7. Integral Contributions of Collision Forces（碰撞力的积分贡献）（191）
				8. Integral Contributions of Viscous Forces（粘性力的积分贡献）（193）
				9. Integral Contributions of Constraint Forces（约束力的积分贡献）（194）
				10. Summary（概括）（195）
				11. Conclusion（结论）（197）
			6. What a Drag: Modeling Realistic Three-Dimensional Air and Fluid Resistance（阻力多大：模拟真实的三维空气和流体阻力）（198）
				1. Physics（物理）（199）
				2. Solution of the Three-Dimensional Linear Case（三维线性情况的求解）（203）
				3. Solution of the Three-Dimensional Quadratic Case（三维二次案例的解）（204）
				4. Pseudocode（伪代码）（207）
				5. Comparison of Linear versus Quadratic Solutions（线性解与二次解的比较）（207）
				6. Conclusion（结论）（208）
			7. Application of Quasi-Fluid Dynamics for Arbitrary Closed Meshes（准流体动力学在任意封闭网格中的应用）（209）
				1. Requirements for the Mesh Representing the Object（对表示对象的网格的要求）（209）
				2. Physical Rudiments（身体基础）（210）
				3. Pre-Computation Based on a Triangle Mesh（基于三角形网格的预计算）（211）
				4. Calculation of the Pressure on the Triangle Surface（三角形表面压力的计算）（214）
				5. Simple Correction of Dynamic Pressure（动压的简单修正）（215）
				6. Conclusion（结论）（215）
			8. Approximate Convex Decomposition for Real-Time Collision Detection（用于实时碰撞检测的近似凸分解）（217）
				1. Approximate Convex Decomposition（近似凸分解）（218）
				2. Hierarchical Approximate Convex Decomposition（层次近似凸分解）（220）
				3. Experimental Results（实验结果）（223）
				4. Conclusion（结论）（225）
		3. AI（人工智能）（226）
			1. AI Level of Detail for Really Large Worlds （真正大世界的人工智能细节水平）（228）
				1. Gradual LOD Example（渐变  LOD  示例）（229）
				2. Graphical LOD versus LOD AI（图形  LOD  与  LOD  AI）（230）
				3. Simulation at the Full Detail（全面细节模拟）（231）
				4. Toward LOD AI: Hierarchical Behavior（迈向  LOD  AI：分层行为）（232）
				5. Space Representation（空间表示）（238）
				6. Positions of Objects and NPCs（物体和  NPC  的位置）（240）
				7. Reshaping the Membrane（重塑膜）（243）
				8. Creating the Structure of the World（创造世界的结构）（244）
				9. Source Code Summary（源代码摘要）（245）
				10. Conclusion（结论）（245）
			2. A Pattern-Based Approach to Modular AI for Games（基于模式的游戏模块化人工智能方法）（247）
				1. A Real-World Example: Apartment Shopping（现实世界的例子：公寓购物）（248）
				2. Boolean Decisions（布尔决策）（249）
				3. Float-Based Decisions（基于流动资金的决策）（256）
				4. Conclusion（结论）（258）
			3. Automated Navigation Mesh Generation Using Advanced Growth-Based Techniques（使用先进的基于增长的技术自动生成导航网格）（259）
				1. The Algorithms（算法）（260）
				2. Post-Processing（后期处理）（268）
				3. Conclusion（结论）（268）
			4. A Practical Spatial Architecture for Animal  and Agent Navigation（用于动物和代理导航的实用空间架构）（271）
				1. Fundamental Components of the Spatial Representation System（空间表示系统的基本组成部分）（272）
				2. Navigation System Architecture（导航系统架构）（274）
				3. Navrep Continuity and Stitching（Navrep  连续性和缝合）（275）
				4. Handling Locomotion and Turning（处理运动和转弯）（276）
				5. Conclusion（结论）（278）
			5. Applying Control Theory to Game AI and Physics（将控制理论应用于游戏人工智能和物理）（279）
				1. Conclusion（结论）（293）
			6. Adaptive Tactic Selection in First-Person Shooter (FPS) Games（第一人称射击 (FPS) 游戏中的自适应策略选择）（294）
				1. A Dynamic Approach to Adaptive Tactic Selection（自适应策略选择的动态方法）（294）
				2. Overview of the Adaptive Tactic Selection Architecture（自适应策略选择架构概述）（295）
				3. Fitness and Weight-Update Functions（健身和体重更新功能）（297）
				4. Adapting Tactic Selection（调整策略选择）（299）
				5. Conclusion（结论）（302）
			7. Embracing Chaos Theory: Generating Apparent Unpredictability through Deterministic Systems（拥抱混沌理论：通过确定性系统产生明显的不可预测性）（303）
				1. The Need for Predictability（对可预测性的需求）（303）
				2. Shaking Things Up（改变现状）（304）
				3. A Brief History of Chaos（混沌简史）（304）
				4. Exploring Cellular Automata（探索元胞自动机）（307）
				5. Leveraging Chaos Theory in Games（在游戏中利用混沌理论）（310）
				6. Conclusion（结论）（316）
			8. Needs-Based AI（基于需求的人工智能）（317）
				1. Background（背景）（317）
				2. Needs-Based AI Overview（基于需求的人工智能概述）（318）
				3. Advertisements and Action Selection（广告和动作选择）（319）
				4. Action Performance（动作表现）（323）
				5. Design Consequences of Needs-Based AI（基于需求的人工智能的设计后果）（325）
				6. Conclusion（结论）（325）
			9. A Framework for  Emotional Digital Actors（情感数字演员的框架）（327）
				1. Models of Emotion, Mood, and Personality（情感、情绪和人格模型）（327）
				2. The Emotional Framework（情感框架）（329）
				3. Conclusion（结论）（336）
			10. Scalable Dialog Authoring（可扩展的对话框创作）（338）
				1. Conversational Agents Today（当今的会话代理）（338）
				2. Overview（概述）（342）
				3. Intention Modeling（意图建模）（343）
				4. Cultural Wrappers（文化包装）（345）
				5. Creating Unique Individuals（创造独特的个体）（348）
				6. Conclusion（结论）（349）
			11. Graph-Based Data Mining for Player Trace Analysis in MMORPGs（MMORPG 中基于图的数据挖掘玩家轨迹分析）（350）
				1. Data Logging and Preprocessing（数据记录和预处理）（350）
				2. Advertisement Placement in MMORPGs（MMORPG  中的广告投放）（353）
				3. Building Player Profiles with Clustering（通过聚类构建玩家档案）（359）
				4. Detecting Bots and Gold Farmers with Classification Models（使用分类模型检测机器人和金农）（364）
				5. Conclusion（结论）（366）
		4. GENERAL PROGRAMMING（通用编程）（368）
			1. Fast-IsA（快速IsA）（370）
				1. Problem Definition（问题定义）（370）
				2. Balanced Class Hierarchies（平衡的类层次结构）（371）
				3. Eliminating the Tree Traversal（消除树遍历）（373）
				4. Building a Balanced Tree（构建平衡树）（375）
				5. Conclusion（结论）（376）
			2. Registered Variables（注册变量）（378）
				1. Getting Started（入门）（378）
				2. Assumptions（假设）（379）
				3. The Base Class: RegisteredVar（基类：RegisteredVar）（379）
				4. Single Variable Values versus Array Variable Values（单变量值与数组变量值）（381）
				5. Type-Specific Registered Variable（特定类型的注册变量）（383）
				6. Setting a Registered Variable Directly（直接设置注册变量）（383）
				7. IsA Functionality（IsA  功能）（384）
				8. Setting a Registered Variable Indirectly（间接设置注册变量）（385）
				9. Conclusion（结论）（387）
			3. Efficient and Scalable Multi-Core Programming（高效且可扩展的多核编程）（388）
				1. Efficient Multi-Threaded Programming（高效的多线程编程）（388）
				2. Scalable Multi-Threaded Programming（可扩展的多线程编程）（394）
				3. Future Work（未来的工作）（397）
				4. Optimizations（优化）（397）
				5. Conclusion（结论）（398）
			4. Game Optimization through the Lens of Memory and Data Access（通过内存和数据访问的视角优化游戏）（400）
				1. Understand the Cache（了解缓存）（400）
				2. Pinpoint Problem Areas（查明问题领域）（402）
				3. Avoid Waste（避免浪费）（402）
				4. Shrink the Data（缩小数据）（403）
				5. Organize the Data（整理数据）（405）
				6. Manipulate the Cache（操纵缓存）（406）
				7. Conclusion（结论）（407）
			5. Stack Allocation（堆栈分配）（408）
				1. Overview（概述）（408）
				2. Example Implementation（实施示例）（409）
				3. Index-Based Implementation（基于索引的实施）（410）
				4. POD Types（吊舱类型）（413）
				5. Known Issues（已知的问题）（414）
				6. Advantages and Disadvantages（优点和缺点）（415）
				7. Conclusion（结论）（416）
			6. Design and Implementation of an In-Game Memory Profiler（游戏内存分析器的设计与实现）（417）
				1. Introduction（介绍）（417）
				2. Memory Profiling Basics（内存分析基础知识）（418）
				3. Function Hooking（函数挂钩）（419）
				4. Call-Stack Generation（调用堆栈生成）（420）
				5. Collecting Statistics（收集统计数据）（421）
				6. Multi-Thread Issues（多线程问题）（422）
				7. The Source Code（源代码）（423）
				8. Conclusion（结论）（423）
			7. A More Informative Error Log Generator（信息更丰富的错误日志生成器）（424）
				1. Definition of RTSI（RTSI的定义）（424）
				2. Potential Uses（潜在用途）（425）
				3. Setting Up the Code（设置代码）（426）
				4. Error Logs Redundancy Problem versus Using RTSI（错误日志冗余问题与使用  RTSI）（428）
				5. Conclusion（结论）（430）
			8. Code Coverage for QA（质量检查的代码覆盖率）（431）
				1. Common Approaches（常见方法）（431）
				2. An Analogy: Breakpoint Testing（类比：断点测试）（432）
				3. Code Coverage（代码覆盖率）（432）
				4. Implementation（执行）（433）
				5. QA Interface and Workflow（QA  界面和工作流程）（436）
				6. Collecting Results（收集结果）（439）
				7. Possible Expansions（可能的扩展）（440）
				8. A Post-Mortem（验尸）（441）
				9. Conclusion（结论）（442）
			9. Domain-Specific Languages in Game Engines （游戏引擎中的特定领域语言）（443）
				1. Domain-Specific Languages in Depth（深入了解特定领域的语言）（443）
				2. Creating a DSL（创建  DSL）（447）
				3. Multi-Language Game Engine Development（多语言游戏引擎开发）（452）
				4. Integrating DSLs into the Pipeline（将  DSL  集成到管道中）（454）
				5. Conclusion（结论）（456）
			10. A Flexible User Interface Layout System for Divergent Environments（适用于不同环境的灵活用户界面布局系统）（457）
				1. The Problem（问题）（457）
				2. Some Cheap Solutions（一些廉价的解决方案）（458）
				3. A More Flexible Solution（更灵活的解决方案）（460）
				4. Concatenate Conditional Modifiers and Conditions（连接条件修饰符和条件）（461）
				5. Implementation Details of the CM System（CM系统实施细则）（462）
				6. Conditional Modifier Condition References（条件修饰符条件参考）（463）
				7. Widget Templates（小部件模板）（464）
				8. Proxy Assets（代理资产）（465）
				9. Performance（表现）（466）
				10. Problems（问题）（467）
				11. Conclusion（结论）（467）
			11. Road Creation for Projectable Terrain Meshes（可投影地形网格物体的道路创建）（468）
				1. Roads as Geodesic Curves（道路作为测地曲线）（468）
				2. Road Grading Techniques for The Sims 3 Worlds（《The  Sims  3  Worlds》的道路平整技术）（472）
				3. Conclusion（结论）（476）
			12. Developing for Digital Drawing Tablets（数字绘图板的开发）（477）
				1. Background（背景）（477）
				2. Tablet Theory（平板电脑理论）（479）
				3. Tablet Programming（平板电脑编程）（483）
				4. Conclusion（结论）（487）
			13. Creating a Multi-Threaded Actor-Based Architecture Using Intel® Threading Building Blocks（使用英特尔® 线程构建模块创建基于多线程 Actor 的架构）（488）
				1. Introduction（介绍）（488）
				2. Actor-Based Programming（基于角色的编程）（490）
				3. Implementing an Actor Engine（实现  Actor  引擎）（491）
				4. Message-Passing Patterns（消息传递模式）（497）
				5. Conclusion（结论）（498）
		5. NETWORKING AND MULTIPLAYER（网络和多人游戏）（500）
			1. Secure Channel Communication（安全通道通信）（502）
				1. Architecture（建筑学）（502）
				2. Network Security（网络安全）（504）
				3. Attacks（攻击）（507）
				4. Responses（回应）（509）
				5. Disciplinary Measures（纪律措施）（510）
				6. Examples（例子）（511）
				7. Conclusion（结论）（511）
			2. Social Networks in Games: Playing with Your Facebook Friends（游戏中的社交网络：与 Facebook 好友一起玩）（513）
				1. RESTful Web Services（RESTful  Web  服务）（513）
				2. The Facebook API（脸书  API）（516）
				3. Conclusion（结论）（520）
			3. Asynchronous I/O for Scalable Game Servers（可扩展游戏服务器的异步 I/O）（521）
				1. Background（背景）（521）
				2. Asynchronous I/O APIs（异步  I/O  API）（524）
				3. Results and Analysis（结果与分析）（526）
				4. Conclusion（结论）（528）
			4. Introduction to 3D Streaming Technology in Massively Multiplayer Online Games（大型多人在线游戏中的3D流媒体技术简介）（529）
				1. The Problem（问题）（530）
				2. The Solution（解决方案）（530）
				3. The World（世界）（531）
				4. The Rendering（渲染图）（536）
				5. The Transport（交通）（540）
				6. Predictive Loading（预测加载）（547）
				7. 3DStreamer: Putting Everything Together（3DStreamer：将一切整合在一起）（552）
				8. Conclusion（结论）（553）
		6. AUDIO（声音的）（554）
			1. A Practical DSP Radio Effect（实用的 DSP 收音机效果器）（557）
				1. The Effect（效果）（558）
				2. Automatic Gain Control（自动增益控制）（564）
				3. Adding Static（添加静态）（565）
				4. Putting It All Together（把它们放在一起）（566）
				5. Parameter Animation（参数动画）（567）
				6. Conclusion（结论）（567）
			2. Empowering Your Audio Team with a Great Engine（为您的音频团队提供强大的引擎）（568）
				1. Audio Code Building Blocks（音频代码构建块）（568）
				2. Sound Parameterization（声音参数化）（570）
				3. Mixing（混合）（574）
				4. Post-Production（后期制作）（576）
				5. Conclusion（结论）（576）
			3. Real-Time Sound Synthesis for Rigid Bodies（刚体的实时声音合成）（578）
				1. Modal Analysis and Impulse Responses（模态分析和脉冲响应）（579）
				2. From Physics Engine to Contact Sounds（从物理引擎到接触声音）（582）
				3. Putting It Together（把它放在一起）（586）
				4. Conclusion（结论）（586）
		7. GENERAL PURPOSE COMPUTING ON GPUS（GPU 上的通用计算）（588）
			1. Using Heterogeneous Parallel Architectures with OpenCL（将异构并行架构与 OpenCL 结合使用）（590）
				1. OpenCL Primer（OpenCL  入门）（591）
				2. Tips for Optimizing OpenCL C Kernels（优化  OpenCL  C  内核的技巧）（593）
				3. Optimizing Memory-Bound OpenCL Kernels（优化受内存限制的  OpenCL  内核）（597）
				4. OpenCL Command Profiling（OpenCL  命令分析）（603）
				5. Conclusion（结论）（604）
			2. PhysX GPU Rigid Bodies in Batman: Arkham Asylum（《蝙蝠侠：阿卡姆疯人院》中的 PhysX GPU 刚体）（605）
				1. Requirements（要求）（606）
				2. Shape Representation（形状表示）（607）
				3. Dynamics Algorithm（动力学算法）（607）
				4. Pipeline（管道）（608）
				5. Transform Spheres into World Space（将球体转换为世界空间）（608）
				6. Sphere-Sphere Collision Detection（球体碰撞检测）（608）
				7. Sphere-Mesh Collision Detection（球体‑网格碰撞检测）（609）
				8. Evaluate Force Fields（评估力场）（609）
				9. Calculate Unconstrained Velocities（计算无约束速度）（609）
				10. Generate Constraints（生成约束）（610）
				11. Solver（求解器）（610）
				12. Update Positions（更新职位）（612）
				13. GPU Implementation（GPU实现）（612）
				14. CUDA Voxelizer（CUDA  体素化器）（613）
				15. Spatial Data Structures（空间数据结构）（614）
				16. Solver（求解器）（614）
				17. Conclusion（结论）（615）
			3. Fast GPU Fluid Simulation in PhysX（PhysX 中的快速 GPU 流体模拟）（617）
				1. Particle Systems（粒子系统）（618）
				2. Fluids（流体）（618）
				3. Robust Particle Collisions（鲁棒粒子碰撞）（619）
				4. Fluid Simulation with Smoothed Particle Hydrodynamics（使用平滑粒子流体动力学进行流体模拟）（621）
				5. Fluid Simulation Algorithm（流体模拟算法）（622）
				6. Fluid Rendering（流体渲染）（628）
				7. Performance（表现）（629）
6. Game Engine Development（游戏引擎开发）
	1. Game Engine Architecture（游戏引擎架构）
		1. Foundations（基础）（20）
			1. Introduction（介绍）（22）
				1. Structure of a Typical Game Team（典型游戏团队的结构）（24）
					1. Engineers（工程师）（24）
					2. Artists（艺术家）（25）
					3. Game Designers（游戏设计师）（26）
					4. Producers（制片人）（26）
					5. Other Staff（其他员工）（27）
					6. Publishers and Studios（出版商和工作室）（27）
				2. What Is a Game?（什么是游戏？）（27）
					1. Video Games as Soft Real-Time Simulations（作为软实时模拟的视频游戏）（28）
				3. What Is a Game Engine?（什么是游戏引擎？）（30）
				4. Engine Differences across Genres（不同类型的引擎差异）（32）
					1. First-Person Shooters (FPS)（第一人称射击游戏 (FPS)）（33）
					2. Platformers and Other Third-Person Games（平台游戏和其他第三人称游戏）（34）
					3. Fighting Games（格斗游戏）（36）
					4. Racing Games（赛车游戏）（38）
					5. Strategy Games（策略游戏）（40）
					6. Massively Multiplayer Online Games (MMOG)（大型多人在线游戏 (MMOG)）（42）
					7. Player-Authored Content（玩家创作的内容）（44）
					8. Virtual, Augmented and Mixed Reality（虚拟、增强和混合现实）（46）
						1. Virtual Reality（虚拟现实）（46）
						2. Augmented and Mixed Reality（增强现实和混合现实）（46）
						3. VR/AR/MR Games（VR/AR/MR 游戏）（47）
						4. VR Game Engines（VR游戏引擎）（48）
						5. Location-Based Entertainment（基于位置的娱乐）（49）
					9.  Other Genres（其他流派）（50）
				5.  Game Engine Survey（游戏引擎调查）（50）
					1. The Quake Family of Engines（Quake 系列引擎）（50）
					2. Unreal Engine（虚幻引擎）（51）
					3. The Half-Life Source Engine（半条命起源引擎）（52）
					4. DICE’s Frostbite（DICE 的寒霜）（52）
					5. Rockstar Advanced Game Engine (RAGE)（Rockstar 高级游戏引擎 (RAGE)）（52）
					6. CRYENGINE（53）
					7. Sony’s PhyreEngine（53）
					8. Microsoft’s XNA Game Studio（微软的 XNA 游戏工作室）（53）
					9. Unity（54）
					10. Other Commercial Game Engines（其他商业游戏引擎）（54）
					11. Proprietary In-House Engines（专有的内部引擎）（54）
					12. Open Source Engines（开源引擎）（55）
					13. 2D Game Engines for Non-programmers（适合非程序员的 2D 游戏引擎）（56）
				6. Runtime Engine Architecture（运行时引擎架构）（57）
					1. Target Hardware（目标硬件）（57）
					2. Device Drivers（设备驱动程序）（57）
					3. Operating System（操作系统）（59）
					4. Third-Party SDKs and Middleware（第三方 SDK 和中间件）（59）
						1. Data Structures and Algorithms（数据结构和算法）（59）
						2. Graphics（图形）（60）
						3. Collision and Physics（碰撞和物理）（61）
						4. Character Animation（角色动画）（61）
						5. Biomechanical Character Models（生物力学角色模型）（62）
					5. Platform Independence Layer（平台独立层）（62）
					6. Core Systems（核心系统）（63）
					7. Resource Manager（资源管理器）（64）
					8. Rendering Engine（渲染引擎）（64）
						1. Low-Level Renderer（低级渲染器）（65）
						2. Scene Graph/Culling Optimizations（场景图/剔除优化）（66）
						3. Visual Effects（视觉效果）（67）
						4. Front End（前端）（68）
					9. Profiling and Debugging Tools（分析和调试工具）（69）
					10. Collision and Physics（碰撞和物理）（70）
					11. Animation（动画片）（71）
					12. Human Interface Devices (HID)（人机接口设备 (HID)）（72）
					13. Audio（声音的）（73）
					14. Online Multiplayer/Networking（在线多人游戏/网络）（74）
					15. Gameplay Foundation Systems（游戏基础系统）（74）
						1. Game Worlds and Object Models（游戏世界和对象模型）（75）
						2. Event System（事件系统）（76）
						3. Scripting System（脚本系统）（77）
						4. Artificial Intelligence Foundations（人工智能基础）（77）
					16. Game-Specific Subsystems（游戏特定子系统）（77）
				7. Tools and the Asset Pipeline（工具和资产管道）（78）
					1. Digital Content Creation Tools（数字内容创建工具）（78）
					2. The Asset Conditioning Pipeline（资产调整管道）（80）
						1. 3D Model/Mesh Data（3D模型/网格数据）（80）
						2. Skeletal Animation Data（骨骼动画数据）（81）
						3. Audio Data（音频数据）（82）
						4. Particle Systems Data（粒子系统数据）（83）
					3. The World Editor（世界编辑）（83）
					4. The Resource Database（资源数据库）（83）
					5. Some Approaches to Tool Architecture（工具架构的一些方法）（84）
						1. Web-Based User Interfaces（基于网络的用户界面）（86）
			2. Tools of the Trade（贸易工具）（88）
				1. Version Control（版本控制）（88）
					1. Why Use Version Control?（为什么要使用版本控制？）（89）
					2. Common Version Control Systems（89）
					3. Overview of Subversion and TortoiseSVN（Subversion 和 TortoiseSVN 概述）（91）
					4. Setting up a Code Repository（设置代码存储库）（91）
					5. Installing TortoiseSVN（安装 TortoiseSVN）（92）
					6. File Versions, Updating and Committing（文件版本、更新和提交）（93）
					7. Multiple Check-Out, Branching and Merging（多重检出、分支和合并）（95）
					8. Deleting Files（删除文件）（97）
				2. Compilers, Linkers and IDEs（编译器、链接器和 IDE）（97）
					1. Source Files, Headers and Translation Units（源文件、标题和翻译单元）（98）
					2. Libraries, Executables and Dynamic Link Libraries（库、可执行文件和动态链接库）（98）
					3. Projects and Solutions（项目与解决方案）（99）
					4. Build Configurations（构建配置）（100）
						1. Common Build Options（通用构建选项）（101）
						2. Local and Global Optimizations（局部和全局优化）（103）
						3. Typical Build Configurations（典型的构建配置）（105）
						4. Project Configuration Tutorial（项目配置教程）（107）
					5. Debugging Your Code（调试你的代码）（110）
						1. The Start-Up Project（启动项目）（111）
						2. Breakpoints（断点）（111）
						3. Stepping through Your Code（单步执行您的代码）（111）
						4. The Call Stack（调用堆栈）（112）
						5. The Watch Window（观察窗）（112）
						6. Data Breakpoints（数据断点）（114）
						7. Conditional Breakpoints（条件断点）（115）
						8. Debugging Optimized Builds（调试优化构建）（116）
				3. Profiling Tools（分析工具）（118）
					1. List of Profilers（分析器列表）（120）
				4. Memory Leak and Corruption Detection（内存泄漏和损坏检测）（120）
				5. Other Tools（其他工具）（121）
			3. Fundamentals of Software Engineering for Games（游戏软件工程基础知识）（124）
				1. C++ Review and Best Practices（C++ 回顾和最佳实践）（124）
					1. Brief Review of Object-Oriented Programming（面向对象编程简述）（125）
						1. Classes and Objects（类和对象）（125）
						2. Encapsulation（封装）（125）
						3. Inheritance（继承）（125）
						4. Polymorphism（多态性）（128）
						5. Composition and Aggregation（组合和聚合）（130）
						6. Design Patterns（设计模式）（130）
					2. C++ Language Standardization（C++ 语言标准化）（132）
						1. Further Reading（进一步阅读）（134）
						2. Which Language Features to Use?（使用哪些语言功能？）（135）
						3. Coding Standards: Why and How Much?（编码标准：为什么以及多少？）（137）
				2. Catching and Handling Errors（捕获和处理错误）（138）
					1. Types of Errors（错误类型）（138）
					2. Handling Errors（处理错误）（139）
						1. Handling Player Errors（处理玩家错误）（139）
						2. Handling Developer Errors（处理开发者错误）（140）
						3. Handling Programmer Errors（处理程序员错误）（141）
					3. Implementation of Error Detection and Handling（错误检测和处理的实现）（141）
						1. Error Return Codes（错误返回码）（141）
						2. Exceptions（例外情况）（142）
						3. Assertions（断言）（144）
				3. Data, Code and Memory Layout（数据、代码和内存布局）（150）
					1. Numeric Representations（数字表示）（150）
						1. Numeric Bases（数字基数）（150）
						2. Signed and Unsigned Integers（有符号和无符号整数）（151）
						3. Fixed-Point Notation（定点表示法）（152）
						4. Floating-Point Notation（浮点表示法）（152）
					2. Primitive Data Types（原始数据类型）（156）
						1. Multibyte Values and Endianness（多字节值和字节顺序）（159）
					3. Kilobytes versus Kibibytes（162）
					4. Declarations, Definitions and Linkage（声明、定义和链接）（163）
						1. Translation Units Revisited（重新审视翻译单元）（163）
						2. Declaration versus Definition（声明与定义）（165）
						3. Linkage（连锁）（168）
					5. Memory Layout of a C/C++ Program（C/C++ 程序的内存布局）（170）
						1. Executable Image（可执行映像）（170）
						2. Program Stack（程序栈）（172）
						3. Dynamic Allocation Heap（动态分配堆）（174）
					6. Member Variables（成员变量）（175）
						1. Class-Static Members（类静态成员）（176）
					7. Object Layout in Memory（内存中的对象布局）（177）
						1. Alignment and Packing（对齐和包装）（178）
						2. Memory Layout of C++ Classes（C++ 类的内存布局）（180）
				4. Computer Hardware Fundamentals（计算机硬件基础知识）（183）
					1. Learning from the Simpler Computers of Yesteryear（向过去的简单计算机学习）（184）
					2. Anatomy of a Computer（计算机剖析）（185）
					3. CPU（185）
						1. ALU（186）
						2. VPU（187）
						3. Registers（寄存器）（187）
						4. Control Unit（控制单元）（190）
					4. Clock（时钟）（190）
						1. Clock Speed versus Processing Power（时钟速度与处理能力）（191）
					5. Memory（内存）（191）
					6. Buses（巴士）（192）
						1. Bus Widths（总线宽度）（193）
						2. Words（字）（194）
						3. n-Bit Computers（n 位计算机）（194）
					7. Machine and Assembly Language（机器和汇编语言）（194）
						1. Instruction Set Architecture (ISA)（指令集架构 (ISA)）（195）
						2. Machine Language（机器语言）（196）
						3. Assembly Language（汇编语言）（198）
						4. Addressing Modes（寻址模式）（190）
						5. Further Reading on Assembly Language（汇编语言进一步阅读）（200）
				5. Memory Architectures（内存架构）（200）
					1. Memory Mapping（内存映射）（201）
						1. Memory-Mapped I/O（内存映射 I/O）（201）
						2. Video RAM（视频内存）（202）
						3. Case Study: The Apple II Memory Map（案例研究：Apple II 内存映射）（202）
					2. Virtual Memory（虚拟内存）（203）
						1. Virtual Memory Pages（虚拟内存页）（203）
						2. Virtual to Physical Address Translation（虚拟地址到物理地址的转换）（204）
						3. Handling Page Faults（处理页面错误）（205）
						4. The Translation Lookaside Buffer (TLB)（转换后备缓冲区 (TLB)）（206）
						5. Further Reading on Virtual Memory（进一步阅读虚拟内存）（206）
					3. Memory Architectures for Latency Reduction（用于减少延迟的内存架构）（207）
						1. The Memory Gap（内存差距）（208）
						2. Register Files（注册文件）（209）
					4. Memory Cache Hierarchies（内存缓存层次结构）（210）
						1. Cache Lines（缓存行）（210）
						2. Mapping Cache Lines to Main RAM Addresses（将缓存行映射到主 RAM 地址）（211）
						3. Addressing the Cache（寻址缓存）（211）
						4. Set Associativity and Replacement Policy（设置关联性和替换策略）（213）
						5. Multilevel Caches（多级缓存）（214）
						6. Instruction Cache and Data Cache（指令缓存和数据缓存）（215）
						7. Write Policy（写政策）（215）
						8. Cache Coherency: MESI, MOESI and MESIF（缓存一致性：MESI、MOESI 和 MESIF）（215）
						9. Avoiding Cache Misses（避免缓存未命中）（216）
					5. Nonuniform Memory Access (NUMA)（非一致内存访问 (NUMA)）（217）
						1. SPU Local Stores on the PS3（PS3 上的 SPU 本地商店）（218）
						2. PS2 Scratchpad (SPR)（PS2 便签本 (SPR)）（218）
			4. Parallelism and Concurrent Programming（并行性和并发编程）（222）
				1. Defining Concurrency and Parallelism（定义并发和并行性）（223）
					1. Concurrency（并发性）（223）
					2. Parallelism（并行性）（224）
						1. Implicit versus Explicit Parallelism（隐式并行与显式并行）（225）
					3. Task versus Data Parallelism（任务并行与数据并行）（226）
					4. Flynn’s Taxonomy（弗林的分类法）（226）
						1. Single versus Multiple Data（单个数据与多个数据）（227）
						2. GPU Parallelism: SIMT（GPU 并行性：SIMT）（228）
					5. Orthogonality of Concurrency and Parallelism（并发和并行的正交性）（230）
					6. Roadmap of the Chapter（本章路线图）（230）
				2. Implicit Parallelism（隐式并行性）（230）
					1. Pipelining（流水线）（231）
					2. Latency versus Throughput（延迟与吞吐量）（233）
					3. Pipeline Depths（管道深度）（233）
					4. Stalls（摊位）（234）
					5. Data Dependencies（数据依赖性）（234）
						1. Instruction Reordering（指令重新排序）（235）
						2. Out-of-Order Execution（乱序执行）（236）
					6. Branch Dependencies（分支依赖关系）（236）
						1. Speculative Execution（推测执行）（237）
						2. Predication（预测）（238）
					7. Superscalar CPUs（超标量 CPU）（240）
						1. Complexity of Superscalar Designs（超标量设计的复杂性）（241）
						2. Superscalar and RISC（超标量和 RISC）（242）
					8. Very Long Instruction Word (VLIW)（超长指令字 (VLIW)）（242）
				3. Explicit Parallelism（显式并行性）（244）
					1. Hyperthreading（超线程）（244）
					2. Multicore CPUs（多核CPU）（245）
					3. Symmetric versus Asymmetric Multiprocessing（对称与非对称多处理）（246）
					4. Distributed Computing（分布式计算）（248）
				4. Operating System Fundamentals（操作系统基础知识）（249）
					1. The Kernel（内核）（249）
						1. Kernel Mode versus User Mode（内核模式与用户模式）（249）
						2. Kernel Mode Privileges（内核模式权限）（250）
					2. Interrupts（中断）（251）
					3. Kernel Calls（内核调用）（252）
					4. Preemptive Multitasking（抢占式多任务处理）（252）
					5. Processes（流程）（254）
						1. Anatomy of a Process（流程剖析）（254）
						2. Virtual Memory Map of a Process（进程的虚拟内存映射）（255）
					6. Threads（线程数）（260）
						1. Thread Libraries（线程库）（260）
						2. Thread Creation and Termination（线程的创建和终止）（261）
						3. Joining Threads（加入线程）（262）
						4. Polling, Blocking and Yielding（轮询、阻止和让步）（263）
						5. Context Switching（上下文切换）（266）
						6. Thread Priorities and Affinity（线程优先级和关联性）（267）
						7. Thread Local Storage（线程本地存储）（268）
						8. Thread Debugging（线程调试）（269）
					7. Fibers（纤维）（269）
						1. Fiber Creation and Destruction（纤维的产生和破坏）（270）
						2. Fiber States（纤维状态）（270）
						3. Fiber Migration（纤维迁移）（271）
						4. Debugging with Fibers（使用光纤进行调试）（271）
						5. Further Reading on Fibers（关于纤维的进一步阅读）（271）
					8. User-Level Threads and Coroutines（用户级线程和协程）（272）
						1. Coroutines（协程）（272）
						2. Kernel Threads versus User Threads（内核线程与用户线程）（274）
					9. Further Reading on Processes and Threads（关于进程和线程的进一步阅读）（274）
				5. Introduction to Concurrent Programming（并发编程简介）（275）
					1. Why Write Concurrent Software?（为什么要编写并发软件？）（276）
					2. Concurrent Programming Models（并发编程模型）（276）
					3. Race Conditions（竞赛条件）（277）
						1. Critical Races（关键比赛）（277）
						2. Data Races（数据竞争）（278）
					4. Critical Operations and Atomicity（关键操作和原子性）（280）
						1. Invocation and Response（调用和响应）（281）
						2. Atomicity Defined（原子性定义）（283）
						3. Making an Operation Atomic（使操作原子化）（283）
						4. Atomicity as Serialization（作为序列化的原子性）（284）
						5. Data-Centric Consistency Models（以数据为中心的一致性模型）（285）
				6. Thread Synchronization Primitives（线程同步原语）（286）
					1. Mutexes（互斥体）（286）
						1. POSIX（287）
						2. C++ Standard Library（C++ 标准库）（288）
						3. Windows（288）
					2. Critical Sections（关键部分）（289）
					3. Condition Variables（条件变量）（290）
					4. Semaphores（信号量）（294）
						1. Mutex versus Binary Semaphore（互斥量与二进制信号量）（295）
						2. Implementing a Semaphore（实现信号量）（297）
					5. Windows Events（窗口事件）（298）
				7. Problems with Lock-Based Concurrency（基于锁的并发问题）（300）
					1. Deadlock（死锁）（300）
					2. Livelock（活锁）（302）
					3. Starvation（饥饿）（303）
					4. Priority Inversion（优先级反转）（303）
					5. The Dining Philosophers（用餐哲学家）（304）
				8. Some Rules of Thumb for Concurrency（并发的一些经验规则）（305）
					1. Global Ordering Rules（全球订购规则）（305）
					2. Transaction-Based Algorithms（基于交易的算法）（306）
					3. Minimizing Contention（最小化争用）（306）
					4. Thread Safety（线程安全）（307）
				9. Lock-Free Concurrency（无锁并发）（308）
					1. Causes of Data Race Bugs（数据竞争错误的原因）（310）
					2. Implementing Atomicity（实现原子性）（311）
						1. Atomicity by Disabling Interrupts（通过禁用中断实现原子性）（311）
						2. Atomic Instructions（原子指令）（311）
						3. Atomic Reads and Writes（原子读写）（312）
						4. Atomic Read-Modify-Write（原子读-修改-写）（312）
						5. Test and Set（测试和设置）（313）
						6. Exchange（交换）（314）
						7. Compare and Swap（比较和交换）（314）
						8. ABA Problem（应用行为分析问题）（316）
						9. Load Linked/Store Conditional（加载链接/条件存储）（317）
						10. Advantages of LL/SC over CAS（LL/SC 相对于 CAS 的优势）（318）
						11. Strong and Weak Compare-Exchange（强弱比较交换）（318）
						12. Relative Strength of Atomic RMW Instructions（原子 RMW 指令的相对强度）（319）
					3. Barriers（障碍）（319）
						1. How Instruction Reordering Causes Concurrency Bugs（指令重新排序如何导致并发错误）（320）
						2. Volatile in C/C++ (and Why It Doesn’t Help Us)（C/C++ 中的易失性（以及为什么它对我们没有帮助））（321）
						3. Compiler Barriers（编译器障碍）（322）
					4. Memory Ordering Semantics（内存排序语义）（323）
						1. Memory Caching Revisited（重新审视内存缓存）（324）
						2. Multicore Cache Coherency Protocols（多核缓存一致性协议）（325）
						3. The MESI Protocol（MESI协议）（327）
						4. How MESI Can Go Wrong（MESI 为何会出错）（328）
						5. Memory Fences（内存栅栏）（329）
						6. Acquire and Release Semantics（获取和释放语义）（330）
						7. When to Use Acquire and Release Semantics（何时使用获取和释放语义）（331）
						8. CPU Memory Models（CPU 内存型号）（332）
						9. Fence Instructions on Real CPUs（真实 CPU 上的围栏指令）（332）
					5. Atomic Variables（原子变量）（333）
						1. C++ Memory Order（C++ 内存顺序）（334）
					6. Concurrency in Interpreted Programming Languages（解释性编程语言中的并发）（336）
					7. Spin Locks（自旋锁）（337）
						1. Basic Spin Lock（基本自旋锁）（338）
						2. Scoped Locks（作用域锁）（339）
						3. Reentrant Locks（可重入锁）（340）
						4. Readers-Writer Locks（读写锁）（343）
						5. Lock-Not-Needed Assertions（不需要锁的断言）（344）
					8. Lock-Free Transactions（无锁交易）（346）
					9. A Lock-Free Linked List（无锁链表）（347）
					10. Further Reading on Lock-Free Programming（关于无锁编程的进一步阅读）（349）
				10. SIMD/Vector Processing（SIMD/矢量处理）（350）
					1. The SSE Instruction Set and Its Registers（SSE指令集及其寄存器）（351）
						1. The __m128 Data Type（__m128 数据类型）（351）
						2. Alignment of SSE Data（上交所数据对齐）（352）
						3. SSE Compiler Intrinsics（SSE 编译器内部函数）（352）
						4. Some Useful SSE Intrinsics（一些有用的 SSE 内在函数）（353）
					2. AltiVec vector Types（AltiVec 向量类型）（355）
					3. Using SSE to Vectorize a Loop（使用 SSE 向量化循环）（355）
						1. A First Attempt (That’s Slow)（第一次尝试（很慢））（357）
						2. A Better Approach（更好的方法）（358）
						3. Transpose as We Go（随走随移）（359）
						4. Shuffle and Transpose（随机播放和移调）（360）
					4. Vector-Matrix Multiplication with SSE（使用 SSE 进行向量矩阵乘法）（361）
					5. Matrix-Matrix Multiplication with SSE（使用 SSE 进行矩阵-矩阵乘法）（362）
					6. Generalized Vectorizaton（广义矢量化）（362）
					7. Vector Predication（向量预测）（363）
				11. Introduction to GPGPU Programming（GPGPU编程简介）（367）
					1. Data-Parallel Computations（数据并行计算）（367）
					2. Compute Kernels（计算内核）（369）
					3. Executing a Kernel（执行内核）（371）
					4. GPU Threads and Thread Groups（GPU 线程和线程组）（372）
						1. From SIMD to SIMT（从SIMD到SIMT）（374）
					5. Further Reading（进一步阅读）（376）
			5. 3D Math for Games（游戏 3D 数学）（378）
				1. Solving 3D Problems in 2D（在 2D 中解决 3D 问题）（378）
				2. Points and Vectors（点和向量）（379）
					1. Points and Cartesian Coordinates（点和笛卡尔坐标）（379）
					2. Left-Handed versus Right-Handed Coordinate Systems（左手坐标系与右手坐标系）（380）
					3. Vectors（向量）（381）
						1. Cartesian Basis Vectors（笛卡尔基向量）（382）
					4. Vector Operations（向量运算）（382）
						1. Multiplication by a Scalar（乘以标量）（383）
						2. Addition and Subtraction（加减）（383）
						3. Magnitude（震级）（384）
						4. Vector Operations in Action（向量运算的实际应用）（385）
						5. Normalization and Unit Vectors（归一化和单位向量）（386）
						6. Normal Vectors（法向量）（386）
						7. Dot Product and Projection（点积和投影）（386）
						8. Cross Product（叉积）（389）
						9. Pseudovectors and Exterior Algebra（伪向量和外代数）（392）
					5. Linear Interpolation of Points and Vectors（点和向量的线性插值）（394）
				3. Matrices（矩阵）（395）
					1. Matrix Multiplication（矩阵乘法）（395）
					2. Representing Points and Vectors as Matrices（将点和向量表示为矩阵）（396）
					3. The Identity Matrix（单位矩阵）（397）
					4. Matrix Inversion（矩阵求逆）（397）
					5. Transposition（换位）（398）
					6. Homogeneous Coordinates（齐次坐标）（398）
						1. Transforming Direction Vectors（变换方向向量）（400）
					7. Atomic Transformation Matrices（原子变换矩阵）（400）
						1. Translation（平移）（401）
						2. Rotation（旋转）（401）
						3. Scale（缩放）（402）
					8. 4 × 3 Matrices（4 × 3 矩阵）（403）
					9. Coordinate Spaces（坐标空间）（403）
						1. Model Space（模型空间）（404）
						2. World Space（世界空间）（405）
						3. View Space（视图空间）（406）
					10. Change of Basis（基础变更）（407）
						1. Coordinate Space Hierarchies（坐标空间层次结构）（407）
						2. Building a Change of Basis Matrix（构建基矩阵的变化）（407）
						3. Extracting Unit Basis Vectors from a Matrix（从矩阵中提取单位基向量）（409）
						4. Transforming Coordinate Systems versus Vectors（变换坐标系与向量）（409）
					11. Transforming Normal Vectors（变换法线向量）（411）
					12. Storing Matrices in Memory（在内存中存储矩阵）（411）
				4. Quaternions（四元数）（413）
					1. Unit Quaternions as 3D Rotations（单位四元数作为 3D 旋转）（414）
					2. Quaternion Operations（四元数运算）（415）
						1. Quaternion Multiplication（四元数乘法）（415）
						2. Conjugate and Inverse（共轭和逆）（415）
					3. Rotating Vectors with Quaternions（用四元数旋转向量）（416）
						1. Quaternion Concatenation（四元数串联）（417）
					4. Quaternion-Matrix Equivalence（四元数矩阵等价）（418）
					5. Rotational Linear Interpolation（旋转线性插补）（419）
						1. Spherical Linear Interpolation（球面线性插值）（420）
						2. To SLERP or Not to SLERP (That’s Still the Question)（SLERP 还是不 SLERP（这仍然是个问题））（421）
				5. Comparison of Rotational Representations（旋转表示的比较）（422）
					1. Euler Angles（欧拉角）（422）
					2. 3 × 3 Matrices（3 × 3 矩阵）（423）
					3. Axis + Angle（轴+角度）（423）
					4. Quaternions（四元数）（424）
					5. SRT Transformations（SRT 转换）（424）
					6. Dual Quaternions（对偶四元数）（425）
					7. Rotations and Degrees of Freedom（旋转和自由度）（425）
				6. Other Useful Mathematical Objects（其他有用的数学对象）（426）
					1. Lines, Rays and Line Segments（直线、射线和线段）（427）
					2. Spheres（球体）（427）
					3. Planes（平面）（427）
					4. Axis-Aligned Bounding Boxes (AABB)（轴对齐边界框 (AABB)）（430）
					5. Oriented Bounding Boxes (OBB)（定向边界框 (OBB)）（430）
					6. Frusta（430）
					7. Convex Polyhedral Regions（凸多面体区域）（430）
				7. Random Number Generation（随机数生成）（731）
					1. Linear Congruential Generators（线性同余发生器）（431）
					2. Mersenne Twister（432）
					3. Mother-of-All, Xorshift and KISS99（万物之母、Xorshift 和 KISS99）（432）
					4. PCG
		2. Low-Level Engine Systems（低级引擎系统）（434）
			1. Engine Support Systems（引擎支持系统）（436）
				1. Subsystem Start-Up and Shut-Down（子系统启动和关闭）（436）
					1. C++ Static Initialization Order (or Lack Thereof)（C++  静态初始化顺序（或缺乏）)（437）
						1. Construct On Demand（按需构建）（438）
					2. A Simple Approach That Works（一种有效的简单方法）（439）
					3. Some Examples from Real Engines（真实引擎的一些例子）（441）
						1. OGRE（441）
						2. Naughty Dog’s Uncharted and The Last of Us Series（顽皮狗《神秘海域》和《最后生还者》系列）（443）
				2.  Memory Management（内存管理）（445）
					1. Optimizing Dynamic Memory Allocation（优化动态内存分配）（445）
						1. Stack-Based Allocators（基于堆栈的分配器）（446）
						2. Pool Allocators（池分配器）（449）
						3. Aligned Allocations（对齐分配）（450）
						4. Single-Frame and Double-Buffered Memory Allocators（单帧和双缓冲内存分配器）（453）
					2. Memory Fragmentation（内存碎片）（456）
						1. Avoiding Fragmentation with Stack and Pool Allocators（使用堆栈和池分配器避免碎片）（457）
						2. Defragmentation and Relocation（碎片整理和重定位）（458）
				3. Containers（容器）（460）
					1. Container Operations（容器操作）（462）
					2. Iterators（迭代器）（463）
						1. Preincrement versus Postincrement（前增量与后增量）（464）
					3. Algorithmic Complexity（算法复杂度）（464）
					4. Building Custom Container Classes（构建自定义容器类）（466）
					5. Dynamic Arrays and Chunky Allocation（动态数组和块分配）（470）
					6. Dictionaries and Hash Tables（字典和哈希表）（471）
						1. Collisions: Open and Closed Hash Tables（冲突：开放哈希表和封闭哈希表）（471）
						2. Hashing（散列）（472）
						3. Implementing a Closed Hash Table（实现封闭哈希表）（474）
						4. Robin Hood Hashing（罗宾汉哈希）（475）
				4. Strings（字符串）（475）
					1. The Problem with Strings（字符串问题）（475）
					2. String Classes（字符串类）（476）
					3. Unique Identifiers（唯一标识符）（477）
						1. Hashed String Ids（散列字符串  ID）（478）
						2. Some Implementation Ideas（一些实现思路）（478）
					4. Localization（本地化）（481）
						1. Unicode（统一码）（481）
						2. char versus wchar_t（char  与  wchar_t）（483）
						3. Unicode under Windows（Windows  下的  Unicode）（484）
						4. Unicode on Consoles（控制台上的  Unicode）（485）
						5. Other Localization Concerns（其他本地化问题）（485）
						6. Case Study: Naughty Dog’s Localization Tool（案例分析：顽皮狗的本地化工具）（487）
				5.  Engine Configuration（引擎配置）（489）
					1. Loading and Saving Options（加载和保存选项）（490）
					2. Per-User Options（每个用户选项）（493）
					3. Configuration Management in Some Real Engines（部分实机中的配置管理）（493）
						1. Example: Quake’s Cvars（示例：Quake  的  Cvar）（493）
						2. Example: OGRE（示例：OGRE）（494）
						3. Example: The Uncharted and The Last of Us Series（示例：《神秘海域》和《最后生还者》系列）（494）
			2. Resources and the File System（资源和文件系统）（500）
				1. File System（文件系统）（501）
					1. File Names and Paths（文件名和路径）（501）
						1. Differences across Operating Systems（操作系统之间的差异）（502）
						2. Absolute and Relative Paths（绝对路径和相对路径）（503）
						3. Search Paths（搜索路径）（504）
						4. Path APIs（路径  API）（505）
					2. Basic File I/O（基本文件  I/O）（505）
						1. To Wrap or Not to Wrap（缠绕或不缠绕）（506）
						2. Synchronous File I/O（同步文件  I/O）（507）
					3. Asynchronous File I/O（异步文件I/O）（508）
						1. Priorities（优先级）（511）
						2. How Asynchronous File I/O Works（异步文件  I/O  的工作原理）（511）
				2. The Resource Manager（资源管理器）（512）
					1. Offline Resource Management and the Tool Chain（离线资源管理及工具链）（512）
						1. Revision Control for Assets（资产的修订控制）（512）
						2. The Resource Database（资源数据库）（513）
						3. Some Successful Resource Database Designs（一些成功的资源数据库设计）（515）
						4. The Asset Conditioning Pipeline（资产调节管道）（520）
					2. Runtime Resource Management（运行时资源管理）（522）
						1. Responsibilities of the Runtime Resource Manager（运行时资源管理器的职责）（522）
						2. Resource File and Directory Organization（资源文件和目录组织）（523）
						3. Resource File Formats（资源文件格式）（526）
						4. Resource GUIDs（资源  GUID）（526）
						5. The Resource Registry（资源注册表）（527）
						6. Resource Lifetime（资源生命周期）（528）
						7. Memory Management for Resources（资源的内存管理）（530）
						8. Composite Resources and Referential Integrity（复合资源和引用完整性）（535）
						9. Handling Cross-References between Resources（处理资源之间的交叉引用）（536）
						10. Post-Load Initialization（加载后初始化）（540）
			3. The Game Loop and Real-Time Simulation（游戏循环和实时模拟）（544）
				1. The Rendering Loop（渲染循环）（544）
				2. The Game Loop（游戏循环）（545）
					1. A Simple Example: Pong（一个简单的例子：Pong）（546）
				3. Game Loop Architectural Styles（游戏循环架构风格）（548）
					1. Windows Message Pumps（Windows  消息泵）（548）
					2. Callback-Driven Frameworks（回调驱动的框架）（548）
					3. Event-Based Updating（基于事件的更新）（550）
				4.  Abstract Timelines（抽象时间线）（551）
					1. Real Time（实时）（551）
					2. Game Time（游戏时间）（551）
					3. Local and Global Timelines（本地和全球时间表）（552）
				5. Measuring and Dealing with Time（测量和处理时间）（553）
					1. Frame Rate and Time Deltas（帧速率和时间增量）（553）
					2. From Frame Rate to Speed（从帧率到速度）（554）
						1. Old-School CPU-Dependent Games（老式的  CPU  相关游戏）（554）
						2. Updating Based on Elapsed Time（根据经过的时间更新）（555）
						3. Using a Running Average（使用移动平均值）（556）
						4. Governing the Frame Rate（控制帧速率）（556）
						5. Screen Tearing and V-Sync（屏幕撕裂和垂直同步）（557）
					3. Measuring Real Time with a High-Resolution Timer（使用高分辨率计时器进行实时测量）（558）
						1. High-Resolution Clock Drift（高分辨率时钟漂移）（559）
					4. Time Units and Clock Variables（时间单位和时钟变量）（559）
						1. 64-Bit Integer Clocks（64  位整数时钟）（559）
						2. 32-Bit Integer Clocks（32  位整数时钟）（560）
						3. 32-Bit Floating-Point Clocks（32  位浮点时钟）（560）
						4. Limitations of Floating-Point Clocks（浮点时钟的限制）（561）
						5. Other Time Units（其他时间单位）（561）
					5. Dealing with Breakpoints（处理断点）（562）
				6.  Multiprocessor Game Loops（多处理器游戏循环）（563）
					1. Task Decomposition（任务分解）（563）
					2. One Thread per Subsystem（每个子系统一个线程）（564）
					3. Scatter/Gather（分散/聚集）（565）
						1. Scatter/Gather in the Game Loop（游戏循环中的分散/聚集）（566）
						2. SIMD for Scatter/Gather（用于分散/聚集的  SIMD）（567）
						3. Making Scatter/Gather More Efficient（使分散/聚集更加高效）（567）
					4. Job Systems（工作系统）（568）
						1. Typical Job System Interface（典型作业系统界面）（568）
						2. A Simple Job System Based on a Thread Pool（一个基于线程池的简单作业系统）（570）
						3. A Limitation of Thread-Based Jobs（基于线程的作业的限制）（571）
						4. Jobs as Coroutines（作为协程的作业）（573）
						5. Jobs as Fibers（作业作为纤维）（573）
						6. Job Counters（作业计数器）（573）
						7. Job Synchronization Primitives（作业同步原语）（574）
						8. Job Visualization and Profiling Tools（作业可视化和分析工具）（575）
						9. The Naughty Dog Job System（顽皮狗工作系统）（576）
			4.  Human Interface Devices（人机接口设备）（578）
				1. Types of Human Interface Devices（人机接口设备的类型）（578）
				2. Interfacing with a HID（与  HID  接口）（580）
					1. Polling（轮询）（580）
					2. Interrupts（中断）（581）
					3. Wireless Devices（无线设备）（581）
				3. Types of Inputs（输入类型）（582）
					1. Digital Buttons（数字按钮）（582）
					2. Analog Axes and Buttons（模拟轴和按钮）（583）
					3. Relative Axes（相对轴）（585）
					4. Accelerometers（加速度计）（585）
					5. 3D Orientation with the Wiimote or DualShock（使用  Wiimote  或  DualShock  进行  3D  定向）（585）
					6. Cameras（相机）（586）
				4.   Types of Outputs（输出类型）（588）
					1. Rumble（588）
					2. Force-Feedback（力反馈）（589）
					3. Audio（音频）（589）
					4. Other Inputs and Outputs（其他输入和输出）（589）
				5. Game Engine HID Systems（游戏引擎HID系统）（589）
					1. Typical Requirements（典型要求）（590）
					2. Dead Zone（死区）（590）
					3. Analog Signal Filtering（模拟信号滤波）（591）
					4. Detecting Input Events（检测输入事件）（593）
						1. Button Up and Button Down（按钮向上和按钮向下）（593）
						2. Chords（594）
						3. Sequences and Gesture Detection（序列和手势检测）（596）
					5. Managing Multiple HIDs for Multiple Players（管理多个玩家的多个  HID）（601）
					6. Cross-Platform HID Systems（跨平台  HID  系统）（601）
					7. Input Remapping（输入重新映射）（603）
					8. Context-Sensitive Controls（上下文相关控件）（605）
					9. Disabling Inputs（禁用输入）（605）
				6. Human Interface Devices in Practice（实践中的人机接口设备）（606）
			5. Tools for Debugging and Development（调试和开发工具）（608）
				1. Logging and Tracing（记录和跟踪）（608）
					1. Formatted Output with OutputDebugString()（使用  OutputDebugString()  格式化输出）（609）
					2. Verbosity（冗长）（610）
					3. Channels（通道）（611）
						1. Using Redis to Manage TTY Channels（使用Redis管理TTY通道）（612）
					4. Mirroring Output to a File（将输出镜像到文件）（612）
					5. Crash Reports（崩溃报告）（613）
				2.  Debug Drawing Facilities（调试绘图工具）（613）
					1. Debug Drawing API（调试绘图API）（616）
				3. In-Game Menus（游戏内菜单）（620）
				4. In-Game Console（游戏内控制台）（623）
				5. Debug Cameras and Pausing the Game（调试相机和暂停游戏）（624）
				6. Cheats（秘籍）（625）
				7. Screenshots and Movie Capture（屏幕截图和视频捕捉）（625）
				8.  In-Game Profiling（游戏内分析）（627）
					1. Hierarchical Profiling（分层分析）（628）
					2. Exporting to Exce（导出到  Excel）（633）
				9.  In-Game Memory Stats and Leak Detection（游戏内存统计和泄漏检测）（634）
		3. Graphics, Motion and Sound（图形、动作和声音）（638）
			1. The Rendering Engine（渲染引擎）（640）
				1. Foundations of Depth-Buffered Triangle Rasterization（深度缓冲的基础三角形光栅化）（641）
					1. Describing a Scene（描述场景）（642）
						1. Representations Used by High-End Rendering Packages（高端渲染包使用的表示）（643）
						2. Triangle Meshes（三角形网格）（644）
						3. Constructing a Triangle Mesh（构建三角形网格）（646）
						4. Model Space（模型空间）（649）
						5. World Space and Mesh Instancing（世界空间和网格实例化）（650）
					2. Describing the Visual Properties of a Surface（描述表面的视觉属性）（651）
						1. Introduction to Light and Color（光和颜色简介）（652）
						2. Vertex Attributes（顶点属性）（654）
						3. Vertex Formats（顶点格式）（655）
						4. Attribute Interpolation（属性插值）（656）
						5. Textures（纹理）（658）
						6. Materials（材料）（665）
					3. Lighting Basics（照明基础知识）（666）
						1. Local and Global Illumination Models（局部和全局照明模型）（666）
						2. The Phong Lighting Mode（Phong  光照模型）（668）
						3. Modeling Light Sources（光源建模）（672）
					4. The Virtual Camera（虚拟相机）（674）
						1. View Space（视图空间）（675）
						2. Projections（预测）（676）
						3. The View Volume and the Frustum（视体积和视锥体）（677）
						4. Projection and Homogeneous Clip Space（投影和均匀裁剪空间）（678）
						5. Screen Space and Aspect Ratios（屏幕空间和长宽比）（682）
						6. The Frame Buffer（帧缓冲区）（682）
						7. Triangle Rasterization and Fragments（三角形光栅化和片段）（683）
						8. Occlusion and the Depth Buffer（遮挡和深度缓冲区）（683）
				2. The Rendering Pipeline（渲染管线）（686）
					1. Overview of the Rendering Pipeline（渲染管线概述）（687）
						1. How the Rendering Pipeline Transforms Data（渲染管线如何转换数据）（688）
						2. Implementation of the Pipeline（管道的实施）（688）
					2. The Tools Stage（工具阶段）（688）
					3. The Asset Conditioning Stage（资产调整阶段）（690）
					4. The GPU Pipeline（GPU  管线）（691）
						1. Vertex Shader（顶点着色器）（692）
						2. Geometry Shader（几何着色器）（693）
						3. Stream Output（流输出）（693）
						4. Clipping（剪裁）（693）
						5. Screen Mapping（屏幕映射）（694）
						6. Triangle Set-up（三角形设置）（694）
						7. Triangle Traversal（三角形遍历）（694）
						8. Early z-Test（早期  z  测试）（694）
						9. Pixel Shader（像素着色器）（694）
						10. Merging / Raster Operations Stage（合并/光栅操作阶段）（695）
					5. Programmable Shaders（可编程着色器）（696）
						1. Accessing Memory（访问内存）（697）
						2. Introduction to High-Level Shader Language Syntax（高级着色器语言语法简介）（699）
						3. Effect Files（效果文件）（701）
						4. Further Reading（进一步阅读）（701）
					6. Antialiasing（抗锯齿）（702）
						1. Full-Screen Antialiasing (FSAA)（全屏抗锯齿  (FSAA)）（703）
						2. Multisampled Antialiasing (MSAA)（多重采样抗锯齿  (MSAA)）（703）
						3. Coverage Sample Antialiasing (CSAA)（覆盖样本抗锯齿  (CSAA)）（704）
						4. Morphological Antialiasing (MLAA)（形态抗锯齿  (MLAA)）（704）
						5. Subpixel Morphological Antialiasing (SMAA)（子像素形态抗锯齿  (SMAA)）（706）
					7. The Application Stage（申请阶段）（706）
						1. Visibility Determination（能见度测定）（706）
						2. Primitive Submission（原始提交）（710）
						3. Geometry Sorting（几何排序）（711）
						4. Scene Graphs（场景图）（712）
						5. Choosing a Scene Graph（选择场景图）（716）
				3. Advanced Lighting and Global Illumination（高级光照和全局照明）（716）
					1. Image-Based Lighting（基于图像的照明）（716）
						1. Normal Mapping（法线贴图）（717）
						2. Heightmaps: Bump, Parallax and Displacement Mapping（高度图：凹凸、视差和位移贴图）（717）
						3. Specular/Gloss Maps（镜面/光泽贴图）（718）
						4. Environment Mapping（环境映射）（719）
						5. Three-Dimensional Textures（三维纹理）（720）
					2. High Dynamic Range Lighting（高动态范围照明）（721）
					3. Global Illumination（全局照明）（721）
						1. Shadow Rendering（阴影渲染）（722）
						2. Ambient Occlusion（环境遮挡）（724）
						3. Reflections（反射）（725）
						4. Caustics（焦散）（725）
						5. Subsurface Scattering（次表面散射）（726）
						6. Precomputed Radiance Transfer (PRT)（预计算辐射传输  (PRT)）（727）
					4. Deferred Rendering（延迟渲染）（728）
					5. Physically Based Shading（基于物理的着色）（728）
				4.  Visual Effects and Overlays（视觉效果和叠加）（729）
					1. Particle Effects（粒子效应）（730）
					2. Decals（贴花）（731）
					3. Environmental Effects（环境影响）（732）
						1. Skies（天空）（732）
						2. Terrain（地形）（733）
						3. Water（水）（734）
					4. Overlays（叠加）（735）
						1. Text and Fonts（文本和字体）（735）
					5. Gamma Correction（伽马校正）（737）
					6. Full-Screen Post Effects（全屏后期效果）（738）
				5. Further Reading（进一步阅读）（738）
			2. Animation Systems（动画系统）（740）
				1. Types of Character Animation（角色动画的类型）（740）
					1. Cel Animation（赛璐珞动画）（741）
					2. Rigid Hierarchical Animation（刚性分层动画）（742）
					3. Per-Vertex Animation and Morph Targets（每顶点动画和变形目标）（743）
					4. Skinned Animation（蒙皮动画）（744）
					5. Animation Methods as Data Compression Techniques（作为数据压缩技术的动画方法）（744）
				2. Skeletons（骨架）（746）
					1. The Skeleal Hierarchy（骨架层次结构）（747）
					2. Representing a Skeleton in Memory（在内存中表示骨架）（747）
				3. Poses（姿势）（748）
					1. Bind Pose（绑定姿势）（748）
					2. Local Poses（局部位姿）（749）
						1. Joint Scale（关节尺度）（750）
						2. Representing a Joint Pose in Memory（表示记忆中的关节姿势）（751）
						3. The Joint Pose as a Change of Basis（关节姿势作为基础的改变）（751）
					3. Global Poses（全局位姿）（752）
						1. Representing a Global Pose in Memory（在内存中表示全局位姿）（752）
				4. Clips（剪辑）（753）
					1. The Local Timeline（本地时间线）（754）
						1. Pose Interpolation and Continuous Time（位姿插值和连续时间）（755）
						2. Time Units（时间单位）（756）
						3. Frame versus Sample（框架与样本）（756）
						4. Frames, Samples and Looping Clips（帧、样本和循环剪辑）（757）
						5. Normalized Time (Phase)（归一化时间（相位））（757）
					2. The Global Timeline（全球时间线）（758）
					3. Comparison of Local and Global Clocks（本地时钟和全局时钟的比较动画系统必须跟踪当）（760）
						1. Synchronizing Animations with a Local Clock（将动画与本地时钟同步）（761）
						2. Synchronizing Animations with a Global Clock（将动画与全局时钟同步）（762）
					4. A Simple Animation Data Format（简单的动画数据格式）（763）
					5. Continuous Channel Functions（连续通道功能）（764）
					6. Metachannels（元通道）（765）
					7. Relationship between Meshes, Skeletons and Clips（网格、骨架和剪辑之间的关系）（767）
						1. Animation Retargeting（动画重定向）（767）
				5. Skinning and Matrix Palette Generation（蒙皮和矩阵调色板生成）（769）
					1. Per-Vertex Skinning Information（每顶点蒙皮信息）（769）
					2. The Mathematics of Skinning（蒙皮的数学原理）（770）
						1. Simple Example: One-Jointed Skeleton（简单示例：单关节骨骼）（770）
						2. Extension to Multijointed Skeletons（扩展到多关节骨骼）（772）
						3. Incorporating the Model-to-World Transform（合并模型到世界的变换）（773）
						4. Skinning a Vertex to Multiple Joints（将顶点蒙皮到多个关节（773））
				6. Animation Blending（动画混合）（774）
					1. LERP Blending（LERP  混合）（774）
					2. Applications of LERP Blending（LERP混合的应用）（776）
						1. Temporal Interpolation（时间插值）（776）
						2. Motion Continuity: Cross-Fading（运动连续性：交叉淡入淡出）（777）
						3. Directional Locomotion（定向运动）（780）
					3. Complex LERP Blends（复杂的  LERP  混合）（782）
						1. Generalized One-Dimensional LERP Blending（广义一维  LERP  混合）（782）
						2. Simple Two-Dimensional LERP Blending（简单的二维  LERP  混合）（782）
						3. Triangular Two-Dimensional LERP Blending（三角形二维LERP混合）（784）
						4. Generalized Two-Dimensional LERP Blending（广义二维  LERP  混合）（785）
					4. Partial-Skeleton Blending（部分骨架混合）（786）
					5. Additive Blending（添加剂混合）（788）
						1. Mathematical Formulation（数学公式）（788）
						2. Additive Blending versus Partial Blending（加法混合与部分混合）（790）
						3. Limitations of Additive Blending（添加剂混合的局限性）（790）
					6. Applications of Additive Blending（添加剂混合的应用）（791）
						1. Stance Variation（姿态变化）（791）
						2. Locomotion Noise（运动噪声）（792）
						3. Aim and Look-At（瞄准和观察）（792）
						4. Overloading the Time Axis（重载时间轴）（793）
				7. Post-Processing（后处理）（793）
					1. Procedural Animations（程序动画）（794）
					2. Inverse Kinematics（逆运动学）（794）
					3. Rag Dolls（布娃娃）（796）
				8. Compression Techniques（压缩技术）（796）
					1. Channel Omission（通道省略）（797）
					2. Quantization（量化）（797）
					3. Sampling Frequency and Key Omission（采样频率和关键省略）（801）
					4. Curve-Based Compression（基于曲线的压缩）（802）
					5. Wavelet Compression（小波压缩）（802）
					6. Selective Loading and Streaming（选择性加载和流式传输）（803）
				9. The Animation Pipeline（动画管道）（803）
				10. Action State Machines（动作状态机）（805）
					1. The Flat Weighted Average Approach（统一加权平均法）（807）
						1. Example: OGRE（示例：OGRE）（808）
						2. Example: Granny（示例：Granny）（809）
						3. Cross-Fades with a Flat Weighted Average（具有平坦加权平均值的交叉淡入淡出）（809）
					2. Blend Trees（混合树）（811）
						1. Binary LERP Blend Trees（二元  LERP  混合树）（811）
						2. Generalized One-Dimensional Blend Trees（广义一维混合树）（811）
						3. Two-Dimensional LERP Blend Trees（二维  LERP  混合树）（812）
						4. Additive Blend Trees（加法混合树）（812）
						5. Layered Blend Trees（分层混合树）（813）
						6. Cross-Fades with Blend Trees（使用混合树进行交叉淡入淡出）（814）
					3. State and Blend Tree Specifications（状态和混合树规范）（815）
						1. Example: The Naughty Dog Engine（示例：顽皮狗引擎）（816）
						2. Example: Unreal Engine 4（示例：虚幻引擎  4）（819）
					4. Transitions（转换）（819）
						1. Kinds of Transitions（转换类型）（820）
						2. Transition Parameters（转换参数）（820）
						3. The Transition Matrix（转移矩阵）（821）
						4. Implementing a Transition Matrix（实现转移矩阵）（821）
					5. Control Parameters（控制参数）（824）
				11. Constraints（约束）（825）
					1. Attachments（附件）（826）
					2. Interobject Registration（对象间注册）（827）
						1. Reference Locators（参考定位器）（828）
						2. Finding the World-Space Reference Location（查找世界空间参考位置）（829）
					3. Grabbing and Hand IK（抓取和手  IK）（830）
					4. Motion Extraction and Foot IK（运动提取和足部  IK）（832）
						1. Motion Extraction（运动提取）（832）
						2. Foot IK（脚  IK）（834）
					5. Other Kinds of Constraints（其他类型的约束）（835）
			3. Collision and Rigid Body Dynamics（碰撞和刚性身体动力学）（836）
				1. Do You Want Physics in Your Game?（你想在游戏中加入物理吗？）（837）
					1. Things You Can Do with a Physics System（物理系统可以做的事情）（837）
					2. Is Physics Fun?（物理有趣吗？）（838）
						1. Simulations (Sims)（模拟  (Sims)）（838）
						2. Physics Puzzle Games（物理益智游戏）（839）
						3. Sandbox Games（沙盒游戏）（839）
						4. Goal-Based and Story-Driven Games（基于目标和故事驱动的游戏）（839）
					3. Impact of Physics on a Game（物理对游戏的影响）（840）
						1. Design Impacts（设计影响）（840）
						2. Engineering Impacts（工程影响）（840）
						3. Art Impacts（艺术影响）（841）
						4. Other Impacts（其他影响）（842）
				2. Collision/Physics Middleware（碰撞/物理中间件）（842）
					1. ODE（842）
					2. Bullet（项目符号）（843）
					3. TrueAxis（真轴）（843）
					4. PhysX（物理X）（843）
					5. Havok（冲击波）（843）
					6. Physics Abstraction Layer (PAL)（物理抽象层（PAL））
					7. Digital Molecular Matter (DMM)（数字分子物质（DMM））
				3. The Collision Detection System（碰撞检测系统）（844）
					1. Collidable Entities（可碰撞实体）（845）
					2. The Collision/Physics World（碰撞/物理世界）（847）
						1. The Physics World（物理世界）（847）
					3. Shape Concepts（形状概念）（848）
						1. Intersection（交叉点）（848）
						2. Contact（联系方式）（849）
						3. Convexity（凸性）（849）
					4. Collision Primitives（碰撞原语）（849）
						1. Spheres（球体）（849）
						2. Capsules（胶囊）（850）
						3. Axis-Aligned Bounding Boxes（轴对齐边界框）（850）
						4. Oriented Bounding Boxes（定向边界框）（851）
						5. Discrete Oriented Polytopes (DOP)（离散定向多面体  (DOP)（851）
						6. Arbitrary Convex Volumes（任意凸体积）（852）
						7. Poly Soup（聚汤）（853）
						8. Compound Shapes（复合形状）（854）
					5. Collision Testing and Analytical Geometry（碰撞测试和解析几何）（855）
						1. Point versus Sphere（点与球体  我们可以通）（855）
						2. Sphere versus Sphere（球体与球体  确定两个球体）（855）
						3. The Separating Axis Theorem（分离轴定理）（856）
						4. AABB versus AABB（AABB  与  AABB）（857）
						5. Detecting Convex Collisions: The GJK Algorithm（检测凸碰撞：GJK  算法）（858）
						6. Other Shape-Shape Combinations（其他形状‑形状组合）（861）
						7. Detecting Collisions between Moving Bodies（检测移动体之间的碰撞）（862）
					6. Performance Optimizations（性能优化）（864）
						1. Temporal Coherency（时间一致性）（865）
						2. Spatial Partitioning（空间分区）（865）
						3. Broad Phase, Midphase and Narrow Phase（宽相、中相和窄相）（866）
					7. Collision Queries（碰撞查询）（866）
						1. Ray Casting（光线投射）（867）
						2. Shape Casting（形状铸造）（868）
						3. Phantoms（幻象）（871）
						4. Other Types of Queries（其他类型的查询）（871）
					8. Collision Filtering（冲突过滤）（871）
						1. Collision Masking and Layers（碰撞掩蔽和层）（872）
						2. Collision Callbacks（碰撞回调）（872）
						3. Game-Specific Collision Materials（游戏特定的碰撞材质）（872）
				4. Rigid Body Dynamics（刚体动力学）（873）
					1. Some Foundations（一些基础）（875）
						1. Units（单位）（875）
						2. Separability of Linear and Angular Dynamics（线性和角动力学的可分离性）（875）
						3. Center of Mass（质心）（876）
					2. Linear Dynamics（线性动力学）（877）
						1. Linear Velocity and Acceleration（线速度和加速度）（877）
						2. Force and Momentum（力和动量）（878）
					3. Solving the Equations of Motion（求解运动方程）（879）
						1. Force as a Function（力作为函数）（879）
						2. Ordinary Differential Equations（常微分方程）（879）
						3. Analytical Solutions（分析解）（880）
					4. Numerical Integration（数值积分）（880）
						1. Explicit Euler（显式欧拉）（881）
						2. Properties of Numerical Methods（数值方法的性质）（882）
						3. Alternatives to Explicit Euler（显式欧拉的替代方案）（883）
						4. Verlet Integration（Verlet  集成）（884）
						5. Velocity Verlet（速度韦尔莱）（885）
					5. Angular Dynamics in Two Dimensions（二维角动力学）（885）
						1. Orientation and Angular Speed（方向和角速度）（885）
						2. Angular Speed and Acceleration（角速度和加速度）（886）
						3. Moment of Inertia（转动惯量）（886）
						4. Torque（扭矩）（886）
						5. Solving the Angular Equations of Motion in Two Dimensions（求解二维运动角方程）（888）
					6. Angular Dynamics in Three Dimensions（三维角动力学）（889）
						1. The Inertia Tensor（惯性张量）（889）
						2. Orientation in Three Dimensions（三维方向）（890）
						3. Angular Velocity and Momentum in Three Dimensions（三维角速度和动量）（890）
						4. Torque in Three Dimensions（三维扭矩）（892）
						5. Solving the Equations of Angular Motion in Three Dimensions（求解三维角运动方程）（892）
					7. Collision Response（碰撞响应）（894）
						1. Energy（能源）（894）
						2. Impulsive Collision Response（脉冲碰撞响应）（895）
						3. Penalty Forces（处罚力量）（898）
						4. Using Constraints to Resolve Collisions（使用约束来解决冲突）（898）
						5. Friction（摩擦力）（899）
						6. Welding（焊接）（900）
						7. Coming to Rest, Islands and Sleeping（休息、离岛和睡觉）（900）
					8. Constraints（约束）（902）
						1. Point-to-Point Constraints（点对点约束）（903）
						2. Stiff Springs（硬弹簧）（903）
						3. Hinge Constraints（铰链约束）（903）
						4. Prismatic Constraints（棱柱约束）（904）
						5. Other Common Constraint Types（其他常见约束类型）（904）
						6. Constraint Chains（约束链）（904）
						7. Rag Dolls（布娃娃）（905）
						8. Powered Constraints（动力约束）（906）
					9. Controlling the Motions of Rigid Bodies（控制刚体运动）（907）
						1. Gravity（重力）（907）
						2. Applying Forces（施加力）（907）
						3. Applying Torques（施加扭矩）（908）
						4. Applying Impulses（施加脉冲）（908）
					10. The Collision/Physics Step（碰撞/物理步骤）（908）
						1. The Constraint Solver（约束求解器）（909）
						2. Variations between Engines（引擎之间的差异）（910）
				5. Integrating a Physics Engine into Your Game（将物理引擎集成到游戏中）（911）
					1. Linking Game Objects and Rigid Bodies（连接游戏对象和刚体）（911）
						1. Physics-Driven Bodies（物理驱动体）（913）
						2. Game-Driven Bodies（游戏驱动体）（914）
						3. Fixed Bodies（固定体）（915）
						4. Havok’s Motion Type（Havok  的运动类型）（915）
					2. Updating the Simulation（更新模拟）（916）
						1. Timing Collision Queries（时序冲突查询）（917）
						2. Single-Threaded Updating（单线程更新）（918）
					3. Example Uses of Collision and Physics in a Game（游戏中碰撞和物理的使用示例）（919）
						1. Simple Rigid Body Game Objects（简单刚体游戏对象）（919）
						2. Bullet Traces（子弹轨迹）（919）
						3. Grenades（手榴弹）（921）
						4. Explosions（爆炸）（921）
						5. Destructible Objects（可破坏的物体）（922）
						6. Character Mechanics（角色机制）（923）
						7. Camera Collision（相机碰撞）（924）
						8. Rag Doll Integration（布娃娃集成）（926）
				6. Advanced Physics Features（高级物理特性）（928）
			4. Aduio（声音的）（930）
				1. The Physics of Sound（声音物理学）（931）
					1. Properties of Sound Waves（声波的性质）（932）
					2. Perceived Loudness and the Decibel（感知响度和分贝）（933）
						1. Equal-Loudness Contours（等响度轮廓）（935）
						2. The Audible Frequency Band（听觉频段）（936）
					3. Sound Wave Propagation（声波传播）（936）
						1. Fall-Off with Distance（随距离的衰减）（936）
						2. Atmospheric Absorption（大气吸收）（937）
						3. Phase Shift and Interference（相移和干扰）（938）
						4. Reverb and Echo（混响和回声）（939）
						5. Sound in Motion: The Doppler Effect（运动中的声音：多普勒效应）（941）
					4. Perception of Position（位置感知）（942）
				2. The Mathematics of Sound（声音的数学）（943）
					1. Signals（信号）（943）
						1. Be Discrete, Continuously（离散、连续）（944）
					2. Manipulating Signals（操纵信号）（944）
					3. Linear Time-Invariant (LTI) Systems（线性时不变（LTI）系统）（945）
					4. Impulse Response of an LTI System（LTI系统的脉冲响应）（947）
						1. The Unit Impulse（单位冲量）（947）
						2. Using an Impulse Train to Represent a Signal（使用脉冲序列表示信号）（948）
						3. Convolution（卷积）（949）
						4. Visualizing Convolution（可视化卷积）（951）
						5. Some Properties of Convolution（卷积的一些性质）（952）
					5. The Frequency Domain and the Fourier Transform（频域和傅立叶变换）（952）
						1. The Sinusoidal Signal（正弦信号）（952）
						2. The Complex Exponential Signal（复指数信号）（953）
						3. The Fourier Series（傅立叶级数）（957）
						4. The Fourier Transform（傅立叶变换）（957）
						5. Bode Plots（波特图）（958）
						6. The Fast Fourier Transform (FFT)（快速傅里叶变换（FFT））（958）
						7. Fourier Transforms and Convolution（傅里叶变换和卷积）（959）
						8. Filtering（过滤）（959）
				3. The Technology of Sound（声音技术）（960）
					1. Analog Audio Technology（模拟音频技术）（960）
						1. Microphones（麦克风）（961）
						2. Speakers（发言者）（962）
						3. Speaker Layouts: Stereo（扬声器布局：立体声）（963）
						4. Speaker Layouts: Surround Sound（扬声器布局：环绕声）（963）
						5. Analog Signal Levels（模拟信号电平）（964）
						6. Amplifiers（放大器）（965）
						7. Volume/Gain Controls（音量/增益控制）（965）
						8. Analog Wiring and Connectors（模拟接线和连接器）（966）
					2. Digital Audio Technology（数字音频技术）（967）
						1. Analog-to-Digital Conversion: Pulse-Code Modulation（模数转换：脉冲编码调制）（967）
						2. Digital-to-Analog Conversion: Demodulation（数模转换：解调）（970）
						3. Digital Audio Formats and Codecs（数字音频格式和编解码器）（970）
						4. Parallel and Interleaved Audio Data（并行和交错音频数据）（972）
						5. Digital Wiring and Connectors（数字接线和连接器）（973）
				4.  Rendering Audio in 3D（以  3D  方式渲染音频）（974）
					1. Overview of 3D Sound Rendering（3D声音渲染概述）（975）
					2. Modeling the Audio World（音频世界建模）（975）
					3. Distance-Based Attenuation（基于距离的衰减）（976）
						1. Fall-Off Min and Max（衰减最小值和最大值）（976）
						2. Blending to Zero（混合至零）（976）
						3. Bending the Rules（违反规则）（977）
						4. Atmospheric Attenuation（大气衰减）（977）
					4. Pan（平移）（978）
						1. Constant Gain Panning（恒定增益平移）（980）
						2. The Constant Power Pan Law（恒功率平移定律）（980）
						3. Headroom（净空）（981）
						4. To Center or Not to Center?（居中还是不居中？）（981）
						5. Focus（焦点）（982）
						6. Dealing with Verticality（处理垂直度）（983）
						7. Further Reading on Pan（关于  Pan  的进一步阅读）（984）
					5. Propagation, Reverb and Acoustics（传播、混响和声学）（984）
						1. Modeling Propagation Effects with an LTI System（使用  LTI  系统对传播效应进行建模）（985）
						2. Reverb Regions（混响区域）（986）
						3. Obstruction, Occlusion and Exclusion（阻碍、遮挡和排除）（987）
						4. Sound Portals in The Last of Us（《最后生还者》中的声音入口）（991）
						5. Further Reading on Environmental Acoustics（环境声学进一步阅读）（992）
						6. Doppler Shift（多普勒频移）（992）
				5. Audio Engine Architecture（音频引擎架构）（993）
					1. The Audio Processing Pipeline（音频处理管道）（994）
					2. Concepts and Terminology（概念和术语）（996）
						1. Voices（声音）（996）
						2. Buses（总线）（997）
					3. The Voice Bus（语音总线）（997）
						1. Sound Synthesis: Codecs（声音合成：编解码器）（997）
						2. Gain Control（增益控制）（998）
						3. Aux Sends（辅助发送）（998）
						4. Reverb （混响）（998）
						5. Pre-Send Filter（预发送过滤器）（999）
						6. Post-Send Filter（发送后过滤器）（999）
						7. Pan Pots（999）
					4. Master Mixer（主混音器）（999）
						1. Analog Mixing（模拟混合）（1000）
						2. Digital Mixing（数字混音）（1000）
						3. Sample Depth Conversion（样本深度转换）（1000）
						4. Sample Rate Conversion（采样率转换）（1000）
					5. The Master Output Bus（主输出总线）（1001）
					6. Implementing a Bus（实现总线）（1002）
						1. Analog Buses（模拟总线）（1002）
						2. Digital Buses（数字总线）（1002）
						3. Bus Latency（总线延迟）（1003）
					7. Asset Management（资产管理）（1004）
						1. Audio Clips（音频剪辑）（1004）
						2. Sound Cues（声音提示）（1005）
						3. Sound Banks（声音库）（1006）
						4. Streaming Sounds（流声音）（1007）
					8. Mixing Your Game（混合你的游戏）（1007）
						1. Groups（组）（1008）
						2. Ducking（闪避）（1008）
						3. Bus Presets and Mix Snapshots（1009）
						4. Instance Limiting（实例限制）（1009）
						5. Mixing In-Game Cinematics（混合游戏内动画）（1010）
					9. Audio Engine Survey（音频引擎调查）（1011）
						1. Windows: The Universal Audio Architecture（Windows：通用音频架构）（1011）
						2. XAudio2（1012）
						3. Scream and BoomRangBuss（Scream  和  BoomRangBuss）（1012）
						4. Multiplatform 3D Audio Engines（多平台  3D  音频引擎）（1013）
				6. Game-Specific Audio Features（游戏特定的音频特性）（1015）
					1. Supporting Split-Screen（支持分屏）（1016）
					2. Character Dialog（角色对话框）（1016）
						1. Giving a Character a Voice（赋予角色声音）（1017）
						2. Defining a Line of Dialog（定义一行对话）（1017）
						3. Playing a Line of Dialog（播放一行对话）（1019）
						4. Priority and Interruption（优先级和中断）（1020）
						5. Conversations（对话）（1021）
						6. Interrupting Conversations（中断对话）（1022）
						7. Exclusivity（排他性）（1023）
						8. Choices and Branching Conversations（选择和分支对话）（1023）
						9. Context-Sensitive Dialog（上下文相关对话框）（1028）
						10. Dialog Actions（对话框操作）（1028）
					3. Music（音乐）（1029）
		4. Gameplay（游戏玩法）（1032）
			1. Introduction to Gameplay Systems（简介游戏系统）（1034）
				1. Anatomy of a Game World（游戏世界剖析）（1035）
					1. World Elements（世界元素）（1035）
						1. Static Geometry（静态几何）（1037）
					2. World Chunks（世界块）（1038）
					3. High-Level Game Flow（高级游戏流程）（1038）
				2. Implementing Dynamic Elements: Game Objects（实现动态元素：游戏对象）（1040）
					1. Game Object Models（游戏对象模型）（1041）
					2. Tool-Side Design versus Runtime Design（工具端设计与运行时设计）（1042）
				3.  Data-Driven Game Engines（数据驱动的游戏引擎）（1043）
				4. The Game World Editor（游戏世界编辑器）（1044）
					1. Typical Features of a Game World Editor（游戏世界编辑器的典型特征）（1048）
						1. World Chunk Creation and Management（世界块创建和管理）（1048）
						2. Game World Visualization（游戏世界可视化）（1048）
						3. Navigation（导航）（1049）
						4. Selection（选择）（1049）
						5. Layers（层）（1050）
						6. Property Grid（属性网格）（1050）
						7. Object Placement and Alignment Aids（对象放置和对齐辅助）（1052）
						8. Special Object Types（特殊对象类型）（1052）
						9. Saving and Loading World Chunks（保存和加载世界块）（1054）
						10. Rapid Iteration（快速迭代）（1054）
					2. Integrated Asset Management Tools（综合资产管理工具）（1054）
						1. Data Processing Costs（数据处理成本）（1055）
			2. Runtime Gameplay Foundation Systems（运行时游戏基础系统）（1058）
				1. Components of the Gameplay Foundation System（游戏基础系统的组成）
				2. Runtime Object Model Architectures（运行时对象模型架构）（1062）
					1. Object-Centric Architectures（以对象为中心的架构）（1063）
						1. A Simple Object-Based Model in C: Hydro Thunder（C  语言中的简单的基于对象的模型：Hydro  Thunder）（1063）
						2. Monolithic Class Hierarchies（整体类层次结构）（1065）
						3. Problems with Deep, Wide Hierarchies（深、宽层次结构的问题）（1047）
						4. Using Composition to Simplify the Hierarchy（使用组合来简化层次结构）（1070）
						5. Generic Components（通用组件）（1074）
						6. Pure Component Models（纯组件模型）（1075）
					2. Property-Centric Architectures（以属性为中心的架构）（1076）
						1. Implementing Behavior via Property Classes（通过属性类实现行为）（1078）
						2. Implementing Behavior via Script（通过脚本实现行为）（1078）
						3. Properties versus Components（属性与组件）（1078）
						4. Pros and Cons of Property-Centric Designs（以属性为中心的设计的优缺点）（1079）
						5. Further Reading（进一步阅读）（1080）
				3. World Chunk Data Formats（世界块数据格式）（1081）
					1. Binary Object Images（二进制对象图像）（1082）
					2. Serialized Game Object Descriptions（序列化游戏对象描述）（1082）
					3. Spawners and Type Schemas（生成器和类型模式）（1084）
						1. Object Type Schemas（对象类型模式）（1085）
						2. Default Attribute Values（默认属性值）（1087）
						3. Some Beneifts of Spawners and Type Schemas（Spawners  和类型模式的一些好处）（1088）
				4. Loading and Streaming Game Worlds（加载和流式传输游戏世界）（1088）
					1. Simple Level Loading（简单关卡加载）（1089）
					2. Toward Seamless Loading: Air Locks（实现无缝装载：气闸）（1089）
					3. Game World Streaming（游戏世界流媒体）（1091）
						1. Determining Which Resources to Load（确定要加载的资源）（1092）
						2. PlayGo on the PlayStation 4（PlayStation  4  上的  PlayGo）（1093）
					4. Memory Management for Object Spawning（对象生成的内存管理）（1093）
						1. OffLine Memory Allocation for Object Spawning（对象生成的离线内存分配）（1093）
						2. Dynamic Memory Management for Object Spawning（对象生成的动态内存管理）（1094）
					5. Saved Games（Saved Games）（1096）
						1. Checkpoints（检查点）（1097）
						2. Save Anywhere（保存在任何地方）（1097）
				5.  Object References and World Queries（对象引用和世界查询）（1098）
					1. Pointers（指针）（1098）
					2. Smart Pointers（智能指针）（1099）
					3. Handles（句柄）（1101）
					4. Game Object Queries（游戏对象查询）（1104）
				6. Updating Game Objects in Real Time（实时更新游戏对象）（1105）
					1. A Simple Approach (That Doesn’t Work)（一个简单的方法（不起作用））（1107）
						1. Maintaining a Collection of Active Game Objects（维护活动游戏对象的集合）（1108）
						2. Responsibilities of the Update() Function（Update()函数的职责）（1108）
					2. Performance Constraints and Batched Updates（性能约束和批量更新）（1109）
					3. Object and Subsystem Interdependencies（对象和子系统的相互依赖性）（1112）
						1. Phased Updates（分阶段更新）（1112）
						2. Bucketed Updates（分桶更新）（1114）
						3. Object State Inconsistencies and One-Frame-Off Lag（对象状态不一致和一帧关闭延迟）（1117）
						4. Object State Caching（对象状态缓存）（1119）
						5. Time-Stamping（时间戳）（1120）
				7. Applying Concurrency to Game Object Updates()（将并发应用于游戏对象更新）（1120）
					1. Concurrent Engine Subsystems（并发引擎子系统）（1120）
					2. Asynchronous Program Design（异步程序设计）（1121）
						1. When to Make Asynchronous Requests（何时发出异步请求）（1124）
					3. Job Dependencies and Degree of Parallelism（作业依赖性和并行度）（1124）
					4. Parallelizing the Game Object Model Itself（并行化游戏对象模型本身）（1126）
						1. Game Object Updates as Jobs（游戏对象更新为作业）（1127）
						2. Asynchronous Game Object Updates（异步游戏对象更新）（1129）
						3. Locking During Game Object Updates（游戏对象更新期间的锁定）（1130）
						4. Object Snapshots（对象快照）（1131）
						5. Handling Inter-Object Mutation（处理对象间突变）（1132）
						6. Future Improvements（未来的改进）（1132）
				8. Events and Message-Passing（事件和消息传递）（1133）
					1. The Problem with Statically Typed Function Binding（静态类型函数绑定的问题）（1133）
					2. Encapsulating an Event in an Object（将事件封装在对象中）（1135）
					3. Event Types（事件类型）（1136）
					4. Event Arguments（事件参数）（1137）
						1. Event Arguments as Key-Value Pairs（作为键值对的事件参数）（1138）
					5. Event Handlers（事件处理程序）（1139）
					6. Unpacking an Event’s Arguments（解压事件的参数）（1140）
					7. Chains of Responsibility（责任链）（1140）
					8. Registering Interest in Events（注册对事件的兴趣）（1142）
					9. To Queue or Not to Queue（排队或不排队）（1143）
						1. Some Benefits of Event Queuing（事件队列的一些好处）（1143）
						2. Some Problems with Event Queuing（事件队列的一些问题）（1145）
					10. Some Problems with Immediate Event Sending（立即事件发送的一些问题）（1149）
					11. Data-Driven Event/Message-Passing Systems（数据驱动的事件/消息传递系统）（1150）
						1. Data Pathway Communication Systems（数据通路通信系统）（1151）
						2. Some Pros and Cons of GUI-Based Programming（基于  GUI  编程的一些优点和缺点）（1153）
				9. Scripting（脚本编写）（1153）
					1. Runtime versus Data Definition（运行时与数据定义）（1154）
					2. Programming Language Characteristics（编程语言特性）（1154）
						1. Typical Characteristics of Game Scripting Languages（游戏脚本语言的典型特征）（1156）
					3. Some Common Game Scripting Languages（一些常见的游戏脚本语言）（1157）
						1. QuakeC（1157）
						2. UnrealScript（1157）
						3. Lua（1158）
						4. Python（1159）
						5. Pawn/Small/Small-C（1160）
					4. Architectures for Scripting（脚本架构）（1161）
					5. Features of a Runtime Game Scripting Language（运行时游戏脚本语言的特性）（1162）
						1. Interface with the Native Programming Language（与本机编程语言的接口）（1163）
						2. Game Object References（游戏对象引用）（1169）
						3. Receiving and Handling Events in Script（在脚本中接收和处理事件）（1170）
						4. Sending Events（发送事件）（1171）
						5. Object-Oriented Scripting Languages（面向对象的脚本语言）（1171）
						6. Scripted Finite State Machines（脚本化有限状态机）（1173）
						7. Multithreaded Scripts（多线程脚本）（1173）
				10. High-Level Game Flow（高级游戏流程）（1176）
		5. Conclusion（结论）（1178）
			1. You Mean There’s More?（你的意思是还有更多？）（1180）
				1. Some Engine Systems We Didn’t Cover（一些我们没有讨论的引擎系统）（1180）
					1. Movie Player（电影播放器）（1180）
					2. Multiplayer Networking（多人网络）（1181）
				2. Gameplay Systems（游戏系统）（1181）
					1. Player Mechanics（玩家机制）（1181）
					2. Cameras（相机）（1182）
					3. Artificial Intelligence（人工智能）（1183）
					4. Other Gameplay Systems（其他游戏系统）（1183）
7. Computer Graphics (CG)（计算机图形学（CG））
	1. Fundamentals of Computer Graphics（计算机图形学基础）
		1. Introduction（介绍）（19）
			1. Graphics Areas（图形区域）（20）
			2. Major Applications（主要应用）（21）
			3. Graphics APIs（图形API）（22）
			4. Graphics Pipeline（图形管线）（23）
			5. Numerical Issues（数值问题）（23）
			6. Efficiency（效率）（26）
			7. Designing and Coding Graphics Programs（图形程序的设计和编码）（27）
				1. Class Design（类设计）（28）
				2. Float vs. Double（浮点型与双精度型）（29）
				3. Debugging Graphics Programs（调试图形程序）（29）
					1. The Scientific Method（科学方法）（30）
					2. Images as Coded Debugging Output（图像作为编码调试输出）（30）
					3. Using a Debugger（使用调试器）（31）
					4. Data Visualization for Debugging（用于调试的数据可视化）（32）
		2. Miscellaneous Math（杂项数学）（33）
			1. Sets and Mappings（集合和映射）（33）
				1. Inverse Mappings（逆映射）（34）
				2. Intervals（间隔）（35）
				3. Logarithms（对数）（36）
			2. Solving Quadratic Equations（求解二次方程）（38）
			3. Trigonometry（三角学）（39）
				1. Angles（角度）（39）
				2. Trigonometric Functions（三角函数）（40）
				3. Useful Identities（有用的身份）（42）
				4. Solid Angles and Spherical Trigonometry（立体角和球面三角学）（44）
			4. Vectors（向量）（44）
				1. Vector Operations（向量运算）（45）
				2. Cartesian Coordinates of a Vector（向量的笛卡尔坐标）（46）
				3. Dot Product（点积）（48）
				4. Cross Product（叉积）（49）
				5. Orthonormal Bases and Coordinate Frames（正交基和坐标系）（51）
				6. Constructing a Basis from a Single Vector（从单个向量构建基础）（53）
				7. Constructing a Basis from Two Vectors（从两个向量构建基础）（54）
				8. Squaring Up a Basis（求基数的平方）（55）
			5. Integration（集成）（55）
				1. Averages and weighted averages（平均值和加权平均值）（56）
				2. Integrals over solid angle（立体角积分）（57）
			6. Density Functions（密度函数）（57）
			7. Curves and Surfaces（曲线和曲面）（59）
				1. 2D Implicit Curves（2D  隐式曲线）（59）
				2. The 2D Gradient（二维梯度）（61）
					1. Implicit 2D Lines（隐式二维线）（64）
					2. Implicit Quadric Curves（隐式二次曲线）（68）
				3. 3D Implicit Surfaces（3D隐式曲面）（69）
				4. Surface Normal to an Implicit Surface（垂直于隐式曲面的曲面）（69）
				5. Implicit Planes（隐式平面）（59）
					1. 3D Quadric Surfaces（3D  二次曲面）（71）
					2. 3D Curves from Implicit Surfaces（隐式曲面的  3D  曲线）（71）
				6. 2D Parametric Curves（2D  参数曲线）（71）
					1. 2D Parametric Lines（2D  参数线）（72）
					2. 2D Parametric Circles（2D  参数化圆）（73）
				7. 3D Parametric Curves（3D参数曲线）（73）
					1. 3D Parametric Lines（3D  参数线）（74）
				8. 3D Parametric Surfaces（3D参数化曲面）（74）
				9. Summary of Curves and Surfaces（曲线和曲面总结）（76）
			8. Linear Interpolation（线性插值）（77）
			9. Triangles（三角形）（77）
				1. 2D Triangles（二维三角形）（77）
				2. 3D Triangles（3D  三角形）（81）
			10. Discrete probability（离散概率）（83）
			11. Continuous probability（连续概率）（85）
			12. Monte Carlo Integration（蒙特卡罗积分）（85）
				1. Importance Sampling（重要性采样）（86）
			13. Frequently Asked Questions（经常问的问题）（88）
		3. Raster Images（光栅图像）（90）
			1. Raster Devices（光栅设备）（92）
				1. Displays（显示）（92）
				2. Hardcopy Devices（硬拷贝设备）（95）
				3. Input Devices（输入设备）（97）
			2. Images, Pixels, and Geometry（图像、像素和几何）（100）
				1. Pixel Values（像素值）（103）
				2. Monitor Intensities and Gamma（监控强度和伽玛）（105）
			3. RGB Color（RGB颜色）（107）
			4. Alpha Compositing（Alpha  合成）（110）
				1. Image Storage（图片存储）（112）
			5. Frequently Asked Questions（经常问的问题）（112）
		4. Ray Tracing（光线追踪）（114）
			1. The Basic Ray-Tracing Algorithm（基本光线追踪算法）（114）
			2. Perspective（视角）（116）
			3. Computing Viewing Rays（计算观察光线）（119）
				1. Orthographic Views（正交视图）（122）
				2. Perspective Views（透视图）（124）
			4. Ray-Object Intersection（光线与物体相交）（125）
				1. Ray-Sphere Intersection（射线‑球体相交）（125）
				2. Ray-Triangle Intersection（射线‑三角形相交）（127）
				3. Ray intersection in software（软件中的射线相交）（130）
				4. Intersecting a Group of Objects（一组对象相交）（131）
			5. Shading（阴影）（132）
				1. Light Sources（光源）（133）
				2. Shading in software（软件中的着色）（133）
				3. Shadows（阴影）（136）
				4. Mirror Reflection（镜面反射）（137）
			6. Historical Notes（历史注释）（139）
			7. Frequently Asked Questions（经常问的问题）（139）
		5. Surface Shading（表面着色）（142）
			1. Point-like light sources（点状光源）（142）
				1. Point source illumination（点光源照明）（142）
				2. Directional illumination（定向照明）（145）
			2. Basic reflection models（基本反射模型）（146）
				1. Lambertian reflection（朗伯反射）（147）
				2. Specular reflection（镜面反射）（148）
				3. Calculating shading（计算阴影）（150）
			3. Ambient illumination（环境照明）（152）
			4. Frequently Asked Questions（经常问的问题）（154）
		6. Linear Algebra（线性代数）（155）
			1. Determinants（决定因素）（156）
			2. Matrices（矩阵）（159）
				1. Matrix Arithmetic（矩阵运算）（159）
				2. Operations on Matrices（矩阵运算）（161）
				3. Vector Operations in Matrix Form（矩阵形式的向量运算）（162）
				4. Special Types of Matrices（特殊类型的矩阵）（164）
			3. Computing with Matrices and Determinants（矩阵和行列式的计算）（165）
				1. Computing Inverses（计算逆）（169）
				2. Linear Systems（线性系统）（171）
			4. Eigenvalues and Matrix Diagonalization（特征值和矩阵对角化）（172）
				1. Singular Value Decomposition（奇异值分解）（174）
			5. Frequently Asked Questions（经常问的问题）（176）
		7. Transformation Matrices（变换矩阵）（179）
			1. 2D Linear Transformations（二维线性变换）（179）
				1. Scaling（缩放）（179）
				2. Shearing（剪切）（181）
				3. Rotation（旋转）（182）
				4. Reflection（反射）（184）
				5. Composition and Decomposition of Transformations（变换的组合与分解）（185）
				6. Decomposition of Transformations（变换的分解）（188）
					1. Symmetric Eigenvalue Decomposition（对称特征值分解）（188）
					2. Singular Value Decomposition（奇异值分解）（190）
					3. Paeth Decomposition of Rotations（旋转的  Paeth  分解）（192）
			2. 3D Linear Transformations（3D线性变换）（193）
				1. Arbitrary 3D Rotations（任意  3D  旋转）（194）
				2. Transforming Normal Vectors（变换法向量）（196）
			3. Translation and Affine Transformations（平移和仿射变换）（198）
			4. Inverses of Transformation Matrices（变换矩阵的逆）（202）
			5. Coordinate Transformations（坐标变换）（203）
			6. Frequently Asked Questions（经常问的问题）（206）
		8. Viewing（视野）（209）
			1. Viewing Transformations（查看变换）（210）
				1. The Viewport Transformation（视口变换）（212）
				2. The Orthographic Projection Transformation（正交投影变换）（213）
				3. The Camera Transformation（相机变换）（216）
			2. Projective Transformations（投影变换）（218）
			3. Perspective Projection（透视投影）（223）
			4. Some Properties of the Perspective Transform（透视变换的一些性质）（228）
			5. Field-of-View（视野）（229）
			6. Frequently Asked Questions（经常问的问题）（230）
		9. The Graphics Pipeline（图形管道）（234）
			1. Rasterization（光栅化）（235）
				1. Line Drawing（画线）（236）
					1. Line Drawing Using Implicit Line Equations（使用隐式直线方程绘制线条）（236）
				2. Triangle Rasterization（三角形光栅化）（241）
					1. Dealing with Pixels on Triangle Edges（处理三角形边缘上的像素）（244）
				3. Perspective Correct Interpolation（透视校正插值）（246）
				4. Clipping（裁剪）（251）
					1. Clipping Before the Transform (Option 1)（变换前剪裁（选项  1））（154）
					2. Clipping in Homogeneous Coordinates (Option 2)（在齐次坐标中裁剪（选项  2））（255）
					3. Clipping against a Plane（相对于平面进行剪裁）（255）
			2. Operations Before and After Rasterization（光栅化前后的操作）（256）
				1. Simple 2D Drawing（简单的二维绘图）（257）
				2. A Minimal 3D Pipeline（最小  3D  管道）（257）
				3. Using a z-Buffer for Hidden Surfaces（对隐藏表面使用  z  缓冲区）（259）
					1. Precision Issues（精度问题）（261）
				4. Per-vertex Shading（每顶点着色）（263）
				5. Per-fragment Shading（每片段着色）（264）
				6. Texture Mapping（纹理映射）（265）
				7. Shading Frequency（遮光频率）（266）
			3. Simple Antialiasing（简单的抗锯齿）（266）
			4. Culling Primitives for Efficiency（剔除原语以提高效率）（268）
				1. View Volume Culling（视图卷剔除）（269）
				2. Backface Culling（背面剔除）（269）
			5. Frequently Asked Questions（经常问的问题）（270）
		10. Signal Processing（信号处理）（272）
			1. Digital Audio: Sampling in 1D（数字音频：一维采样）（273）
				1. Sampling Artifacts and Aliasing（采样伪影和混叠）（275）
			2. Convolution（卷积）（276）
				1. Moving Averages（移动平均线）（277）
				2. Discrete Convolution（离散卷积）（278）
					1. Convolution Filters（卷积滤波器）（280）
					2. Properties of Convolution（卷积的性质）（282）
				3. Convolution as a Sum of Shifted Filters（卷积作为移位滤波器的总和）（283）
				4. Convolution with Continuous Functions（连续函数的卷积）（285）
					1. The Dirac Delta Function（狄拉克  Delta  函数）（287）
				5. Discrete-Continuous Convolution（离散连续卷积）（289）
				6. Convolution in More Than One Dimension（多维卷积）（291）
			3. Convolution Filters（卷积滤波器）（294）
				1. A Gallery of Convolution Filters（卷积滤波器图库）（294）
					1. The Box Filter（箱式过滤器）（294）
					2. The Tent Filter（帐篷过滤器）（295）
					3. The Gaussian Filter（高斯滤波器）（296）
					4. The B-Spline Cubic Filter（B  样条三次滤波器）（296）
					5. The Catmull–Rom Cubic Filter（Catmull–Rom  立方滤波器）（297）
					6. The Mitchell–Netravali Cubic Filter（Mitchell‑Netravali  立方滤波器）（298）
				2. Properties of Filters（过滤器的属性）（298）
					1. Separable Filters（可分离过滤器）（300）
			4. Signal Processing for Images（图像信号处理）（304）
				1. Image Filtering Using Discrete Filters（使用离散滤波器进行图像滤波）（304）
				2. Antialiasing in Image Sampling（图像采样中的抗锯齿）（306）
				3. Reconstruction and Resampling（重建和重采样）（308）
			5. Sampling Theory（抽样理论）（314）
				1. The Fourier Transform（傅立叶变换）（315）
				2. Convolution and the Fourier Transform（卷积和傅立叶变换）（319）
				3. A Gallery of Fourier Transforms（傅立叶变换图库）（320）
				4. Dirac Impulses in Sampling Theory（抽样理论中的狄拉克脉冲）（321）
				5. Sampling and Aliasing（采样和混叠）（322）
					1. Preventing Aliasing in Sampling（防止采样中的混叠）（324）
					2. Preventing Aliasing in Reconstruction（防止重建中的锯齿）（327）
					3. Preventing Aliasing in Resampling（防止重采样中的混叠）（329）
				6. Ideal Filters vs. Useful Filters（理想滤波器与有用滤波器）（329）
		11. Texture Mapping（纹理映射）（332）
			1. Looking Up Texture Values（查找纹理值）（333）
			2. Texture Coordinate Functions（纹理坐标函数）（337）
				1. Geometrically Determined Coordinates（几何确定的坐标）（338）
					1. Planar Projection（平面投影）（339）
					2. Spherical Coordinates（球坐标）（342）
					3. Cylindrical Coordinates（圆柱坐标）（343）
					4. Cubemaps（立方体贴图）（343）
				2. Interpolated Texture Coordinates（插值纹理坐标）（345）
				3. Tiling, Wrapping Modes, and Texture Transformations（平铺、环绕模式和纹理变换）（348）
				4. Continuity and Seams（连续性和接缝）（351）
				5. Texture coordinates in rendering systems（渲染系统中的纹理坐标）（352）
			3. Antialiasing Texture Lookups（抗锯齿纹理查找）（353）
				1. The Footprint of a Pixel（像素的足迹）（354）
				2. Reconstruction（重建）（358）
				3. Mipmapping（纹理贴图）（360）
				4. Basic Texture Filtering with Mipmaps（使用  Mipmap  进行基本纹理过滤）（361）
				5. Anisotropic Filtering（各向异性过滤）（362）
			4. Applications of Texture Mapping（纹理映射的应用）（363）
				1. Controlling Shading Parameters（控制着色参数）（363）
				2. Normal Maps and Bump Maps（法线贴图和凹凸贴图）（364）
				3. Displacement Maps（位移图）（367）
				4. Shadow Maps（阴影贴图）（369）
				5. Environment Maps（环境贴图）（370）
			5. Procedural 3D Textures（程序3D纹理）（372）
				1. 3D Stripe Textures（3D  条纹纹理）（373）
				2. Solid Noise（固体噪声）（375）
				3. Turbulence（湍流）（378）
			6. Frequently Asked Questions（经常问的问题）（380）
		12. Data Structures for Graphics（图形数据结构）（382）
			1. Triangle Meshes（三角形网格）（383）
				1. Mesh Topology（网状拓扑）（383）
				2. Indexed Mesh Storage（索引网格存储）（387）
				3. Triangle Strips and Fans（三角条和扇形）（390）
				4. Data Structures for Mesh Connectivity（网状连接的数据结构）（392）
					1. The Triangle-Neighbor Structure（三角邻接结构）（394）
					2. The Winged-Edge Structure（翼缘结构）（398）
					3. The Half-Edge Structure（半边结构）（401）
			2. Scene Graphs（场景图）（404）
				1. In rasterization（光栅化中）（407）
				2. In ray tracing（光线追踪中）（408）
			3. Spatial Data Structures（空间数据结构）（411）
				1. Bounding Boxes（边界框）（412）
				2. Hierarchical Bounding Boxes（分层边界框）（417）
				3. Uniform Spatial Subdivision（统一空间细分）（422）
				4. Axis-Aligned Binary Space Partitioning（轴对⻬二元空间划分）（425）
			4. BSP Trees for Visibility（可见性的  BSP  树）（427）
				1. Overview of BSP Tree Algorithm（BSP树算法概述）（428）
				2. Building the Tree（构建树）（434）
				3. Cutting Triangles（切割三角形）（437）
				4. Optimizing the Tree（优化树）（439）
			5. Tiling Multidimensional Arrays（平铺多维数组）（440）
				1. One-Level Tiling for 2D Arrays（2D  数组的一级平铺）（442）
				2. Example: Two-Level Tiling for 3D Arrays（示例：3D  数组的两级平铺）（444）
			6. Frequently Asked Questions（经常问的问题）（446）
		13. Sampling（采样）（448）
			1. Integration（集成）（448）
				1. Measures and Averages（测量和平均值）（450）
				2. Example: Measures on the Lines in the 2D Plane（示例：2D  平面中直线上的测量）（451）
				3. Example: Measure of Lines in 3D（示例：3D  线的测量）（455）
			2. Continuous Probability（连续概率）（456）
				1. One-Dimensional Continuous Probability Density Functions（一维连续概率密度函数）（456）
				2. One-Dimensional Expected Value（一维期望值）（457）
				3. Multidimensional Random Variables（多维随机变量）（458）
				4. Variance（方差）（459）
				5. Estimated Means（估计平均值）（460）
			3. Monte Carlo Integration（蒙特卡罗积分）（460）
				1. Quasi–Monte Carlo Integration（准蒙特卡罗积分）（462）
			4. Choosing Random Points（选择随机点）（463）
				1. Function Inversion（函数反演）（464）
				2. Rejection（拒绝）（468）
				3. Metropolis（大都会）（469）
				4. Example: Choosing Random Lines in the Square（示例：在正方形中选择随机线）（471）
			5. Frequently Asked Questions（经常问的问题）（475）
		14. Physics-Based Rendering（基于物理的渲染）（477）
			1. Photons（光子）（477）
			2. Smooth Metals（光滑金属）（478）
			3. Smooth Dielectrics（光滑电介质）（479）
				1. Reflectivity of a Dielectric（电介质的反射率）（479）
				2. Refraction and Beer’s Law（折射和比尔定律）（480）
			4. Dielectrics with Subsurface Scattering（具有次表面散射的电介质）（484）
			5. A Brute Force Photon Tracer（强力光子追踪器）（485）
				1. Sensor（传感器）（485）
				2. Photon Tracer（光子追踪器）（486）
				3. Motion and Defocus Blur（运动和散焦模糊）（487）
				4. Reversing Time（倒转时间）（488）
			6. Radiometry（辐射测量）（488）
				1. Spectral Energy（光谱能量）（489）
				2. Power（电源）（491）
				3. Irradiance（辐照度）（492）
				4. Radiance（辐射率）（492）
					1. Other Radiometric Quantities in Terms of Radiance（以辐射率表示的其他辐射量）（495）
			7. Radiometry of Scattering（散射辐射测量）（497）
				1. BRDF（双向反射分布函数）（497）
					1. Directional Hemispherical Reflectance（定向半球反射率）（499）
					2. Ideal Diffuse BRDF（理想漫反射  BRDF）（500）
			8. Transport Equation（输运方程）（501）
			9. Materials in Practice（实践材料）（503）
			10. Monte Carlo Ray Tracing（蒙特卡罗光线追踪）（505）
			11. Frequently Asked Questions（经常问的问题）（507）
		15. Curves（曲线）（511）
			1. Curves（曲线）（511）
				1. Parameterizations and Reparameterizations（参数化和重新参数化）（513）
				2. Piecewise Parametric Representations（分段参数表示）（514）
				3. Splines（样条曲线）（516）
			2. Curve Properties（曲线属性）（516）
				1. Continuity（连续性）（517）
			3. Polynomial Pieces（多项式部分）（518）
				1. Polynomial Notation（多项式符号）（518）
				2. A Line Segment（线段）（519）
				3. Beyond Line Segments（线段之外）（521）
				4. Basis Matrices for Cubics（三次方的基矩阵）（523）
				5. Blending Functions（混合函数）（524）
				6. Interpolating Polynomials（插值多项式）（524）
			4. Putting Pieces Together（将各个部分放在一起）（525）
				1. Knots（525）
				2. Using Independent Pieces（使用独立片段）（526）
				3. Putting Segments Together（将段放在一起）（526）
			5. Cubics（立方）（528）
				1. Natural Cubics（自然立方）（530）
				2. Hermite Cubics（厄米立方）（531）
				3. Cardinal Cubics（基数三次）（531）
			6. Approximating Curves（近似曲线）（534）
				1. Bézier Curves（贝塞尔曲线）（534）
					1. Geometric Intuition for Bézier Curves（贝塞尔曲线的几何直觉）（538）
					2. The de Casteljau Algorithm（de  Casteljau  算法）（539）
				2. B-Splines（B  样条）（541）
					1. Uniform Linear B-Splines（均匀线性  B  样条）（542）
					2. Uniform Quadratic B-Splines（均匀二次  B  样条）（543）
					3. Uniform Cubic B-Splines（均匀三次  B  样条）（544）
				3. Nonuniform B-Splines（非均匀  B  样条）（546）
					1. Repeated Knots and B-Spline Interpolation（重复结和  B  样条插值）（547）
				4. NURBS（549）
		16. Computer Animation（电脑动画）（552）
			1. Principles of Animation（动画原理）（553）
				1. Timing（时序）（553）
				2. Action Layout（动作布局）（554）
				3. Animation Techniques（动画技术）（555）
				4. Animator Control vs. Automatic Methods（动画器控制与自动方法）（557）
			2. Keyframing（关键帧）（557）
				1. Motion Controls（运动控制）（561）
				2. Interpolating Rotation（插值旋转）（564）
			3. Deformations（变形）（567）
			4. Character Animation（角色动画）（569）
				1. Facial Animation（面部动画）（574）
				2. Motion Capture（动作捕捉）（575）
			5. Physics-Based Animation（基于物理的动画）（577）
			6. Procedural Techniques（程序技术）（580）
			7. Groups of Objects（对象组）（583）
		17. Using Graphics Hardware（使用图形硬件）（588）
			1. Hardware Overview（硬件概述）（588）
			2. What Is Graphics Hardware（什么是图形硬件）（588）
			3. Heterogeneous Multiprocessing（异构多重处理）（591）
				1. Programming with OpenGL（使用  OpenGL  编程）（593）
			4. Graphics Hardware Programming: Buffers, State, and Shaders（图形硬件编程：缓冲区、状态和着色器）（594）
				1. Buffers（缓冲区）（594）
				2. Display Buffer（显示缓冲区）（594）
				3. Cycle of Refresh（刷新周期）（595）
			5. State Machine（状态机）（596）
			6. Basic OpenGL Application Layout（基本OpenGL应用程序布局）（597）
			7. Geometry（几何）（598）
				1. Describing Geometry for the Hardware（描述硬件的几何形状）（599）
			8. A First Look at Shaders（着色器初探）（600）
				1. Vertex Shader Example（顶点着色器示例）（601）
				2. Fragment Shader Example（片段着色器示例）（603）
				3. Loading, Compiling, and Using Shaders（加载、编译和使用着色器）（603）
			9. Vertex Buffer Objects（顶点缓冲区对象）（604）
			10. Vertex Array Objects（顶点数组对象）（607）
			11. Transformation Matrices（变换矩阵）（610）
				1. GLM（610）
				2. Using an Orthographic Projection（使用正交投影）（611）
			12. Shading with Per-Vertex Attributes（使用每顶点属性进行着色）（613）
				1. Structs of Vertex Data（顶点数据的结构）（616）
			13. Shading in the Fragment Processor（片段处理器中的着色）（617）
				1. Blinn-Phong Shader Program: Vertex Shader（Blinn‑Phong着色器程序：顶点着色器）（619）
				2. Blinn-Phong Shader Program: Fragment Shader（Blinn‑Phong着色器程序：片段着色器）（622）
				3. A Normal Shader（普通着色器）（624）
			14. Meshes and Instancing（网格和实例化）（625）
				1. Instancing Models（实例化模型）（627）
			15. Texture Objects（纹理对象）（628）
				1. Texture Lookup in Shaders（着色器中的纹理查找）（633）
			16. Object-Oriented Design for Graphics Hardware Programming（图形硬件编程的面向对象设计）（635）
			17. Continued Learning（继续学习）（637）
			18. Frequently Asked Questions（经常问的问题）（638）
		18. Color（颜色）（641）
			1. Colorimetry（比色法）（643）
				1. Grassmann’s Laws（格拉斯曼定律）（644）
				2. Cone Responses（视锥反应）（645）
				3. Color Matching Experiments（配色实验）（646）
				4. Standard Observers（标准观察员）（647）
				5. Chromaticity Coordinates（色度坐标）（650）
			2. Color Spaces（色彩空间）（654）
				1. Constructing a Matrix Transform（构造矩阵变换）（654）
				2. Device-Dependent RGB Spaces（设备相关的  RGB  空间）（656）
				3. LMS Cone Space（LMS锥空间）（658）
				4. CIE 1976 L* a* b*（659）
			3. Chromatic Adaptation（色彩适应）（661）
			4. Color Appearance（颜色外观）（664）
		19. Visual Perception（视觉感知）（666）
			1. Vision Science（视觉科学）（667）
			2. Visual Sensitivity（视觉灵敏度）（668）
				1. Brightness and Contrast（亮度和对比度）（669）
				2. Color（颜色）（677）
				3. Dynamic Range（动态范围）（682）
				4. Field-of-View and Acuity（视野和敏锐度）（684）
				5. Motion（运动）（688）
			3. Spatial Vision（空间视觉）（692）
				1. Frames of Reference and Measurement Scales（参考系和测量尺度）（693）
				2. Ocularmotor Cues（动眼线索）（694）
				3. Binocular Disparity（双眼视差）（697）
				4. Motion Cues（动作提示）（699）
				5. Pictorial Cues（图形提示）（701）
			4. Objects, Locations, and Events（对象、位置和事件）（709）
				1. Object Recognition（物体识别）（710）
				2. Size and Distance（尺寸和距离）（713）
				3. Events（事件）（716）
			5. Picture Perception（图像感知）（720）
		20. Tone Reproduction（音调再现）（724）
			1. Classification（分类）（728）
			2. Dynamic Range（动态范围）（729）
			3. Color（颜色）（732）
			4. Image Formation（图像形成）（735）
			5. Frequency-Based Operators（基于频率的运算符）（736）
			6. Gradient-Domain Operators（梯度域算子）（737）
			7. Spatial Operators（空间运算符）（739）
			8. Division（除法）（742）
			9. Sigmoids（743）
			10. Other Approaches（其他方法）（750）
			11. Night Tonemapping（夜间色调映射）（752）
			12. Discussion（讨论）（754）
		21. Implicit Modeling（隐式建模）（756）
			1. Implicit Functions, Skeletal Primitives, and Summation Blending（隐式函数、骨架基元和求和混合）（758）
				1. C 1 Continuity and the Gradient（C 连续性和梯度）（761）
				2. Distance Fields, R-Functions, and F-Reps（距离场、R  函数和  F  表示）（762）
				3. Level Sets（水平集）（763）
				4. Variational Implicit Surfaces（变分隐式曲面）（764）
				5. Convolution Surfaces（卷积曲面）（765）
				6. Defining Skeletal Primitives（定义骨骼基元）（766）
			2. Rendering（渲染）（769）
			3. Space Partitioning（空间划分）（770）
				1. Exhaustive Search（穷举搜索）（770）
				2. Algorithm Description（算法描述）（771）
					1. Data Structures（数据结构）（775）
				3. Polygonization Algorithm（多边形化算法）（775）
					1. Finding Cube-Surface Intersections（寻找立方体表面交点）（776）
				4. Sampling Problems（抽样问题）（778）
					1. Subdividing a Cube（细分立方体）（779）
				5. Cell Polygonization（细胞多边形化）（780）
			4. More on Blending（更多关于混合的内容）（780）
			5. Constructive Solid Geometry（构造立体几何）（782）
			6. Warping（变形）（784）
				1. Twist（扭转）（786）
				2. Taper（锥度）（786）
				3. Bend（弯曲）（787）
			7. Precise Contact Modeling（精确接触建模）（788）
			8. The BlobTree（Blob树）（791）
				1. Traversing the BlobTree（遍历BlobTree）（791）
			9. Interactive Implicit Modeling Systems（交互式隐式建模系统）（793）
		22. Computer Graphics in Games（游戏中的计算机图形学）（798）
			1. Platforms（平台）（798）
			2. Limited Resources（有限资源）（801）
				1. Processing Time（处理时间）（801）
				2. Storage（存储）（802）
				3. Development Resources（开发资源）（804）
			3. Optimization Techniques（优化技术）（805）
			4. Game Types（游戏类型）（806）
			5. The Game Production Process（游戏制作流程）（811）
				1. Asset Creation（资产创建）（812）
					1. Initial Modeling（初始建模）（813）
					2. Texturing（纹理化）（814）
					3. Shading（阴影）（822）
					4. Lighting（灯光）（823）
					5. Animation（动画片）（823）
		23. Visualization（可视化）（826）
			1. Background（背景）（828）
				1. History（历史）（828）
				2. Resource Limitations（资源限制）（829）
			2. Data Types（数据类型）（830）
				1. Dimension and Item Count（尺寸和项目计数）（931）
				2. Data Transformation and Derived Dimensions（数据转换和派生维度）（831）
			3. Human-Centered Design Process（以人为本的设计过程）（832）
				1. Task Characterization（任务表征）（832）
				2. Abstraction（抽象）（833）
				3. Technique and Algorithm Design（技术和算法设计）（833）
				4. Validation（验证）（833）
			4. Visual Encoding Principles（视觉编码原理）（934）
				1. Visual Channel Characteristics（视觉通道特性）（836）
				2. Color（颜色）（839）
				3. 2D vs. 3D Spatial Layouts（2D  与  3D  空间布局）（841）
				4. Text Labels（文本标签）（844）
			5. Interaction Principles（交互原则）（844）
				1. Overview First, Zoom and Filter, Details on Demand（概览先行，缩放过滤，细节按需）（845）
				2. Interactivity Costs（交互成本）（845）
				3. Animation（动画）（846）
			6. Composite and Adjacent Views（复合视图和相邻视图）（846）
				1. Single Drawing（单图）（847）
				2. Superimposing and Layering（叠加和分层）（848）
				3. Glyphs（字形）（849）
				4. Multiple Views（多视图）（852）
			7. Data Reduction（数据缩减）（854）
				1. Overviews and Aggregation（概述和聚合）（855）
				2. Filtering and Navigation（过滤和导航）（855）
				3. Focus+Context（焦点+上下文）（856）
				4. Dimensionality Reduction（降维）（858）
			8. Examples（例子）（860）
				1. Tables（表格）（860）
				2. Graphs（图表）（862）
				3. Trees（树）（865）
				4. Geographic（地理）（867）
				5. Spatial Fields（空间场）（868）
			9. Frequently Asked Questions（经常问的问题）（868）
	2. Real-Time Rendering Fourth Edition（实时渲染第四版）
		1. Introduction（介绍）（22）
			1. Contents Overview（内容概述）（24）
			2. Notation and Definitions（符号和定义）（26）
				1. Mathematical Notation（数学符号）（26）
				2. Geometrical Definitions（几何定义）（29）
				3. Shading（阴影）（30）
			3. Further Reading and Resources（进一步阅读和资源）（30）
		2. The Graphics Rendering Pipeline（图形渲染管线）（32）
			1. Architecture（架构）（33）
			2. The Application Stage（申请阶段）（34）
			3. Geometry Processing（几何处理）（35）
				1. Vertex Shading（顶点着色）（36）
				2. Optional Vertex Processing（可选的顶点处理）（39）
				3. Clipping（裁剪）（40）
				4. Screen Mapping（屏幕映射）（41）
			4. Rasterization（光栅化）（42）
				1. Triangle Setup（三角形设置）（43）
				2. Triangle Traversal（三角形遍历）（43）
			5. Pixel Processing（像素处理）（43）
				1. Pixel Shading（像素着色）（44）
				2. Merging（合并）（45）
			6. Through the Pipeline（通过管道）（46）
				1. Application（应用程序）（46）
				2. Geometry Processing（几何处理）（47）
				3. Rasterization（光栅化）（47）
				4. Pixel Processing（像素处理）（47）
			7. Conclusion（结论）（48）
			8. Further Reading and Resources（进一步阅读和资源）（48）
		3. The Graphics Processing Unit（图形处理单元）（50）
			1. Data-Parallel Architectures（数据并行架构）（51）
			2. GPU Pipeline Overview（GPU管线概述）（55）
			3. The Programmable Shader Stage（可编程着色器阶段）（56）
			4. The Evolution of Programmable Shading and APIs（可编程着色和  API  的演变）（58）
			5. The Vertex Shader（顶点着色器）（63）
			6. The Tessellation Stage（曲面细分阶段）（65）
			7. The Geometry Shader（几何着色器）（68）
				1. Stream Output（流输出）（69）
			8. The Pixel Shader（像素着色器）（70）
			9. The Merging Stage（合并阶段）（74）
			10. The Compute Shader（计算着色器）（75）
			11. Further Reading and Resources（进一步阅读和资源）（76）
		4. Transforms（变换）（78）
			1. Basic Transforms（基本变换）（79）
				1. Translation（平移）（80）
				2. Rotation（旋转）（81）
				3. Scaling（缩放）（83）
				4. Shearing（剪切）（84）
				5. Concatenation of Transforms（变换的串联）（86）
				6. The Rigid-Body Transform（刚体变换）（87）
				7. Normal Transform（法线变换）（89）
				8. Computation of Inverses（逆的计算）（90）
			2. Special Matrix Transforms and Operations（特殊矩阵变换和运算）（91）
				1. The Euler Transform（欧拉变换）（91）
				2. Extracting Parameters from the Euler Transform（从欧拉变换中提取参数）（93）
				3. Matrix Decomposition（矩阵分解）（94）
				4. Rotation about an Arbitrary Axis（绕任意轴旋转）（95）
			3. Quaternions（四元数）（97）
				1. Mathematical Background（数学背景）（97）
				2. Quaternion Transforms（四元数变换）（100）
					1. Matrix Conversion（矩阵转换）（100）
					2. Spherical Linear Interpolation（球面线性插值）（102）
					3. Rotation from One Vector to Another（从一个向量到另一个向量的旋转）（104）
			4. Vertex Blending（顶点混合）（105）
			5. Morphing（变形）（108）
			6. Geometry Cache Playback（几何缓存回放）（113）
			7. Projections（预测）（113）
				1. Orthographic Projection（正交投影）（114）
				2. Perspective Projection（透视投影）（117）
			8. Further Reading and Resources（进一步阅读和资源）（123）
		5. Shading Basics（着色基础知识）（124）
			1. Shading Models（着色模型）（124）
			2. Light Sources（光源）（127）
				1. Directional Lights（定向光）（130）
				2. Punctual Lights（正点灯）（131）
					1. Point/Omni Lights（点光源/泛光灯）（132）
					2. Spotlights（聚光灯）（135）
					3. Other Punctual Lights（其他守时灯）（137）
				3. Other Light Types（其他灯光类型）（137）
			3. Implementing Shading Models（实现着色模型）（138）
				1. Frequency of Evaluation（评估频率）（138）
				2. Implementation Example（实现示例）（141）
				3. Material Systems（材质系统）（146）
			4. Aliasing and Antialiasing（锯齿和抗锯齿）（151）
				1. Sampling and Filtering Theory（采样和过滤理论）（151）
					1. Reconstruction（重构）（154）
					2. Resampling（重采样）（157）
				2. Screen-Based Antialiasing（基于屏幕的抗锯齿）（158）
					1. Sampling Patterns（采样模式）（166）
					2. Morphological Methods（形态学方法）（167）
			5. Transparency, Alpha, and Compositing（透明度、Alpha  和合成）（169）
				1. Blending Order（混合顺序）（171）
				2. Order-Independent Transparency（与顺序无关的透明度）（175）
				3. Premultiplied Alphas and Compositing（预乘  Alpha  和合成）（180）
			6. Display Encoding（显示编码）（181）
			7. Further Reading and Resources（进一步阅读和资源）（186）
		6. Texturing（纹理化）（188）
			1. The Texturing Pipeline（纹理管道）（190）
				1. The Projector Function（投影仪功能）（191）
				2. The Corresponder Function（通讯员功能）（195）
				3. Texture Values（纹理值）（196）
			2. Image Texturing（图像纹理）（197）
				1. Magnification（放大倍数）（199）
				2. Minification（缩小）（203）
					1. Mipmapping（204）
					2. Summed-Area Table（求和面积表）（207）
					3. Unconstrained Anisotropic Filtering（无约束各向异性过滤）（209）
				3. Volume Textures（体积纹理）（210）
				4. Cube Maps（立方体贴图）（211）
				5. Texture Representation（纹理表示）（211）
				6. Texture Compression（纹理压缩）（213）
			3. Procedural Texturing（程序纹理）（219）
			4. Texture Animation（纹理动画）（221）
			5. Material Mapping（材质贴图）（222）
			6. Alpha Mapping（阿尔法映射）（223）
			7. Bump Mapping（凹凸贴图）（229）
				1. Blinn’s Methods（布林方法）（232）
				2. Normal Mapping（法线贴图）（232）
			8. Parallax Mapping（视差映射）（235）
				1. Parallax Occlusion Mapping（视差遮挡贴图）（237）
			9. Textured Lights（纹理灯）（242）
			10. Further Reading and Resources（进一步阅读和资源）（243）
		7. Shadows（阴影）（244）
			1. Planar Shadows（平面阴影）（246）
				1. Projection Shadows（投影阴影）（246）
				2. Soft Shadows（软阴影）（249）
			2. Shadows on Curved Surfaces（曲面上的阴影）（250）
			3. Shadow Volumes（阴影体积）（251）
			4. Shadow Maps（阴影贴图）（255）
				1. Resolution Enhancement（分辨率增强）（260）
			5. Percentage-Closer Filtering（百分比接近过滤）（268）
			6. Percentage-Closer Soft Shadows（百分比接近的软阴影）（271）
			7. Filtered Shadow Maps（过滤阴影贴图）（273）
			8. Volumetric Shadow Techniques（体积阴影技术）（278）
			9. Irregular Z-Buffer Shadows（不规则的  Z  缓冲区阴影）（280）
			10. Other Applications（其他应用）（283）
			11. Further Reading and Resources（进一步阅读和资源）（286）
		8. Light and Color（光与色）（288）
			1. Light Quantities（光量）（288）
				1. Radiometry（辐射测量）（288）
				2. Photometry（光度测定）（292）
				3. Colorimetry（比色法）（293）
				4. Rendering with RGB Colors（使用  RGB  颜色渲染）（300）
			2. Scene to Screen（场景到屏幕）（302）
				1. High Dynamic Range Display Encoding（高动态范围显示编码）（302）
				2. Tone Mapping（色调映射）（304）
					1. Tone Reproduction Transform（色调再现变换）（307）
					2. Exposure（曝光计算）（309）
				3. Color Grading（颜色分级）（310）
			3. Further Reading and Resources（进一步阅读和资源）（312）
		9. Physically Based Shading（基于物理的着色）（314）
			1. Physics of Light（光物理）（314）
				1. Particles（粒子）（318）
				2. Media（媒体）（319）
				3. Surfaces（表面）（321）
				4. Subsurface Scattering（次表面散射）（326）
			2. The Camera（相机）（328）
			3. The BRDF（双向反射分布函数）（329）
			4. Illumination（照明）（336）
			5. Fresnel Reflectance（菲涅耳反射率）（337）
				1. External Reflection（外部反射）（338）
				2. Typical Fresnel Reflectance Values（典型菲涅尔反射率值）（342）
					1. Fresnel Reflectance Values for Dielectrics（电介质的菲涅尔反射率值）（342）
					2. Fresnel Reflectance Values for Metals（金属的菲涅尔反射率值）（344）
					3. Fresnel Reflectance Values for Semiconductors（半导体的菲涅尔反射率值）（345）
					4. Fresnel Reflectance Values in Water（水中的菲涅耳反射率值）（345）
					5. Parameterizing Fresnel Values（参数化菲涅尔值）（345）
				3. Internal Reflection（内部反射）（346）
			6. Microgeometry（微观几何）（348）
			7. Microfacet Theory（微面理论）（352）
			8. BRDF Models for Surface Reflection（表面反射的BRDF模型）（357）
				1. Normal Distribution Functions（正态分布函数）（358）
					1. Isotropic Normal Distribution Functions（各向同性正态分布函数）（259）
					2. Anisotropic Normal Distribution Functions（各向异性正态分布函数）（364）
				2. Multiple-Bounce Surface Reflection（多次反射表面反射）（367）
			9. BRDF Models for Subsurface Scattering（次表面散射的BRDF模型）（368）
				1. Subsurface Albedo（地下反照率）（369）
				2. Scale of Subsurface Scattering and Roughness（次表面散射和粗糙度的尺度）（370）
				3. Smooth-Surface Subsurface Models（光滑表面地下模型）（371）
				4. Rough-Surface Subsurface Models（粗糙表面次表面模型）（374）
			10. BRDF Models for Cloth（布料的  BRDF  模型）（377）
				1. Empirical Cloth Models（经验布料模型）（378）
				2. Microfacet Cloth Models（微面布料模型）（378）
				3. Micro-Cylinder Cloth Models（微圆筒布料模型）（379）
			11. Wave Optics BRDF Models（波动光学BRDF模型）（380）
				1. Diffraction Models（衍射模型）（381）
				2. Models for Thin-Film Interference（薄膜干涉模型）（382）
			12. Layered Materials（分层材料）（384）
			13. Blending and Filtering Materials（混合和过滤材料）（386）
				1. Filtering Normals and Normal Distributions（过滤法线和正态分布）（388）
			14. Further Reading and Resources（进一步阅读和资源）（393）
		10. Local Illumination（局部照明）（396）
			1. Area Light Sources（面光源）（398）
				1. Glossy Materials（光泽材质）（403）
				2. General Light Shapes（一般光形状）（407）
			2. Environment Lighting（环境照明）（412）
			3. Spherical and Hemispherical Functions（球函数和半球函数）（413）
				1. Simple Tabulated Forms（简单表格形式）（414）
				2. Spherical Bases（球形底座）（416）
					1. Spherical Radial Basis Functions（球面径向基函数）（417）
					2. Spherical Gaussians（球状高斯分布）（418）
					3. Spherical Harmonics（球谐函数）（419）
					4. Other Spherical Representations（其他球面表示）（422）
				3. Hemispherical Bases（半球形底座）（423）
					1. Ambient/Highlight/Direction（环境/高光/方向）（423）
					2. Radiosity Normal Mapping/Half-Life 2 Basis（光能传递法线贴图/半条命  2  基础）（423）
					3. Hemispherical Harmonics/H-Basis（半球谐波/H  基）（425）
			4. Environment Mapping（环境映射）（425）
				1. Latitude-Longitude Mapping（经纬度映射）（427）
				2. Sphere Mapping（球体映射）（429）
				3. Cube Mapping（立方体贴图）（431）
				4. Other Projections（其他预测）（434）
			5. Specular Image-Based Lighting（基于镜面图像的照明）（435）
				1. Prefiltered Environment Mapping（预过滤环境映射）（436）
					1. Convolving the Environment Map（对环境贴图进行卷积）（439）
				2. Split-Integral Approximation for Microfacet BRDFs（微面BRDF的分裂积分近似）（441）
				3. Asymmetric and Anisotropic Lobes（不对称和各向异性波瓣）（443）
			6. Irradiance Environment Mapping（辐照度环境映射）（445）
				1. Spherical Harmonics Irradiance（球谐波辐照度）（448）
				2. Other Representations（其他表示）（452）
			7. Sources of Error（误差源）（454）
			8. Further Reading and Resources（进一步阅读和资源）（456）
		11. Global Illumination（全局照明）（458）
			1. The Rendering Equation（渲染方程）（458）
			2. General Global Illumination（一般全局照明）（462）
				1. Radiosity（光能传递）（463）
				2. Ray Tracing（光线追踪）（464）
			3. Ambient Occlusion（环境光遮挡）（467）
				1. Ambient Occlusion Theory（环境遮挡理论）（467）
				2. Visibility and Obscurance（可见性和遮蔽性）（469）
				3. Accounting for Interreflections（考虑相互反射）（471）
				4. Precomputed Ambient Occlusion（预先计算的环境光遮挡）（472）
				5. Dynamic Computation of Ambient Occlusion（环境遮挡的动态计算）（474）
				6. Screen-Space Methods（屏幕空间方法）（478）
				7. Shading with Ambient Occlusion（使用环境光遮挡进行着色）（484）
			4. Directional Occlusion（定向遮挡）（486）
				1. Precomputed Directional Occlusion（预先计算的方向遮挡）（487）
				2. Dynamic Computation of Directional Occlusion（定向遮挡的动态计算）（488）
				3. Shading with Directional Occlusion（定向遮挡着色）（489）
			5. Diffuse Global Illumination（漫反射全局照明）（493）
				1. Surface Prelighting（表面预照明）（494）
				2. Directional Surface Prelighting（定向表面预照明）（496）
				3. Precomputed Transfer（预计算传输）（499）
				4. Storage Methods（存储方法）（505）
				5. Dynamic Diffuse Global Illumination（动态漫反射全局照明）（512）
				6. Light Propagation Volumes（光传播体积）（514）
				7. Voxel-Based Methods（基于体素的方法）（515）
				8. Screen-Space Methods（屏幕空间方法）（517）
				9. Other Methods（其他方法）（518）
			6. Specular Global Illumination（镜面全局照明）（518）
				1. Localized Environment Maps（本地化环境贴图）（519）
				2. Dynamic Update of Environment Maps（环境贴图的动态更新）（523）
				3. Voxel-Based Methods（基于体素的方法）（524）
				4. Planar Reflections（平面反射）（525）
				5. Screen-Space Methods（屏幕空间方法）（526）
			7. Unified Approaches（统一方法）（530）
			8. Further Reading and Resources（进一步阅读和资源）（533）
		12. Image-Space Effects（图像空间效应）（534）
			1. Image Processing（图像处理）（534）
				1. Bilateral Filtering（双边过滤）（539）
			2. Reprojection Techniques（重投影技术）（543）
			3. Lens Flare and Bloom（镜头光晕和光晕）（545）
			4. Depth of Field（景深）（548）
			5. Motion Blur（运动模糊）（557）
			6. Further Reading and Resources（进一步阅读和资源）（564）
		13. Beyond Polygons（超越多边形）（566）
			1. The Rendering Spectrum（渲染谱）（566）
			2. Fixed-View Effects（固定视图效果）（567）
			3. Skyboxes（天空盒）（568）
			4. Light Field Rendering（光场渲染）（570）
			5. Sprites and Layers（精灵和图层）（571）
			6. Billboarding（广告牌）（572）
				1. Screen-Aligned Billboard（屏幕对齐广告牌）（574）
				2. World-Oriented Billboard（面向世界的广告牌）（575）
				3. Axial Billboard（轴向广告牌）（580）
				4. Impostors（冒名顶替者）（582）
				5. Billboard Representation（广告牌表示）（584）
			7. Displacement Techniques（位移技术）（585）
			8. Particle Systems（粒子系统）（588）
				1. Shading Particles（着色粒子）（590）
				2. Particle Simulation（粒子模拟）（592）
			9. Point Rendering（点渲染）（593）
			10. Voxels（体素）（599）
				1. Applications（应用）（599）
				2. Voxel Storage（体素存储）（600）
				3. Generation of Voxels（体素的生成）（601）
				4. Rendering（渲染）（603）
				5. Other Topics（其他主题）（607）
			11. Further Reading and Resources（进一步阅读和资源）（608）
		14. Volumetric and Translucency Rendering（体积和半透明度渲染）（610）
			1. Light Scattering Theory（光散射理论）（610）
				1. Participating Media Material（参与媒体材料）（611）
				2. Transmittance（透射率）（614）
				3. Scattering Events（散射事件）（614）
				4. Phase Functions（相位函数）（616）
					1. Rayleigh Scattering（瑞利散射）（617）
					2. Mie Scattering（米氏散射）（618）
					3. Geometric Scattering（几何散射）（620）
			2. Specialized Volumetric Rendering（专门的体积渲染）（210）
				1. Large-Scale Fog（大范围雾）（621）
				2. Simple Volumetric Lighting（简单体积照明）（423）
			3. General Volumetric Rendering（一般体积渲染）（626）
				1. Volume Data Visualization（体数据可视化）（626）
				2. Participating Media Rendering（参与媒体渲染）（628）
			4. Sky Rendering（天空渲染）（634）
				1. Sky and Aerial Perspective（天空和空中透视）（634）
				2. Clouds（云）（637）
					1. Clouds as Particles（云作为粒子）（638）
					2. Clouds as Participating Media（云作为参与媒体）（639）
					3. Multiple Scattering Approximation（多次散射近似）（642）
					4. Clouds and Atmosphere Interactions（云和大气相互作用）（643）
			5. Translucent Surfaces（半透明表面）（644）
				1. Coverage and Transmittance（覆盖范围和透射率）（644）
				2. Refraction（折射）（647）
				3. Caustics and Shadows（焦散和阴影）（651）
			6. Subsurface Scattering（次表面散射）（653）
				1. Wrap Lighting（环绕照明）（654）
				2. Normal Blurring（法线模糊）（655）
				3. Pre-Integrated Skin Shading（预集成皮肤着色）（655）
				4. Texture-Space Diffusion（纹理空间扩散）（656）
				5. Screen-Space Diffusion（屏幕空间扩散）（657）
				6. Depth-Map Techniques（深度图技术）（659）
			7. Hair and Fur（头发和毛皮）（661）
				1. Geometry and Alpha（几何和阿尔法）（662）
				2. Hair（头发）（663）
				3. Fur（毛皮）（667）
			8. Unified Approaches（统一方法）（669）
			9. Further Reading and Resources（进一步阅读和资源）（669）
		15. Non-Photorealistic Rendering（非真实感渲染）（672）
			1. Toon Shading（卡通着色）（673）
			2. Outline Rendering（轮廓渲染）（675）
				1. Shading Normal Contour Edges（法线轮廓边缘着色）（677）
				2. Procedural Geometry Silhouetting（程序几何轮廓）（678）
				3. Edge Detection by Image Processing（图像处理的边缘检测）（681）
				4. Geometric Contour Edge Detection（几何轮廓边缘检测）（686）
				5. Hidden Line Removal（隐藏线去除）（689）
			3. Stroke Surface Stylization（笔画表面风格化）（690）
			4. Lines（线条）（694）
				1. Triangle Edge Rendering（三角形边缘渲染）（694）
				2. Rendering Obscured Lines（渲染模糊线）（695）
				3. Haloing（光晕）（696）
			5. Text Rendering（文本渲染）（696）
			6. Further Reading and Resources（进一步阅读和资源）（699）
		16. Polygonal Techniques（多边形技术）（702）
			1. Sources of Three-Dimensional Data（三维数据来源）（703）
			2. Tessellation and Triangulation（曲面细分和三角测量）（704）
				1. Shading Problems（阴影问题）（707）
				2. Edge Cracking and T-Vertices（边裂纹和  T  形顶点）（710）
			3. Consolidation（合并）（711）
				1. Merging（合并）（712）
				2. Orientation（方向）（712）
				3. Solidity（坚固性）（714）
				4. Normal Smoothing and Crease Edges（正常平滑和折痕边缘）（715）
			4. Triangle Fans, Strips, and Meshes（三角形扇形、条带和网格）（717）
				1. Fans（扇形）（717）
				2. Strips（条带）（718）
				3. Triangle Meshes（三角形网格）（720）
				4. Cache-Oblivious Mesh Layouts（忽略缓存的网格布局）（721）
				5. Vertex and Index Buffers/Arrays（顶点和索引缓冲区/数组）（722）
			5. Simplification（简化）（727）
				1. Dynamic Simplification（动态简化）（727）
			6. Compression and Precision（压缩和精度）（733）
			7. Further Reading and Resources（进一步阅读和资源）（737）
		17. Curves and Curved Surfaces（曲线和曲面）（738）
			1. Parametric Curves（参数曲线）（739）
				1. B´ezier Curves（B´ezier  曲线）（741）
					1. B´ezier Curves Using Bernstein Polynomials（使用伯恩斯坦多项式的贝塞尔曲线）（743）
					2. Rational B´ezier Curves（有理贝塞尔曲线）（746）
				2. Bounded B´ezier Curves on the GPU（GPU  上的有界  B´ezier  曲线）（746）
				3. Continuity and Piecewise B´ezier Curves（连续性和分段贝塞尔曲线）（747）
				4. Cubic Hermite Interpolation（三次Hermite插值）（750）
				5. Kochanek-Bartels Curves（Kochanek‑Bartels曲线）（751）
				6. B-Splines（B样条）（753）
			2. Parametric Curved Surfaces（参数化曲面）（755）
				1. B´ezier Patches（B´ezier  补丁）（756）
					1. Rational B´ezier Patches（有理贝塞尔面片）（759）
				2. B´ezier Triangles（B´ezier三角形）（761）
				3. Continuity（连续性）（762）
				4. PN Triangles（PN三角形）（765）
				5. Phong Tessellation（Phong  镶嵌）（769）
				6. B-Spline Surfaces（B样条曲面）（770）
			3. Implicit Surfaces（隐式曲面）（770）
			4. Subdivision Curves（细分曲线）（774）
			5. Subdivision Surfaces（细分曲面）（777）
				1. Loop Subdivision（循环细分）（779）
				2. Catmull-Clark Subdivision（卡特莫尔‑克拉克细分）（782）
				3. Piecewise Smooth Subdivision（分段平滑细分）（784）
				4. Displaced Subdivision（位移细分）（786）
				5. Normal, Texture, and Color Interpolation（法线、纹理和颜色插值）（788）
			6. Efficient Tessellation（高效曲面细分）（788）
				1. Fractional Tessellation（分数镶嵌）（789）
				2. Adaptive Tessellation（自适应曲面细分）（791）
					1. Terminating Adaptive Tessellation（终止自适应曲面细分）（792）
					2. Split and Dice Methods（分割和骰子方法）（795）
				3. Fast Catmull-Clark Tessellation（快速Catmull‑Clark曲面细分）（796）
					1. Approximating Approaches（近似方法）（796）
					2. Feature Adaptive Subdivision and OpenSubdiv（特征自适应细分和  OpenSubdiv）（798）
					3. Adaptive Quadtrees（自适应四叉树）（800）
			7. Further Reading and Resources（进一步阅读和资源）（802）
		18. Pipeline Optimization（管道优化）（805）
			1. Profiling and Debugging Tools（分析和调试工具）（805）
			2. Locating the Bottleneck（定位瓶颈）（807）
				1. Testing the Application Stage（测试应用阶段）（807）
				2. Testing the Geometry Processing Stage（测试几何处理阶段）（808）
				3. Testing the Rasterization Stage（测试光栅化阶段）（808）
				4. Testing the Pixel Processing Stage（测试像素处理阶段）（809）
				5. Testing the Merging Stage（测试合并阶段）（809）
			3. Performance Measurements（性能测量）（809）
			4. Optimization（优化）（811）
				1. Application Stage（申请阶段）（811）
					1. Memory Issues（内存问题）（812）
				2. API Calls（API调用）（814）
					1. State Changes（状态更改）（815）
					2. Consolidating and Instancing（整合和实例化）（819）
				3. Geometry Stage（几何阶段）（819）
				4. Rasterization Stage（光栅化阶段）（821）
				5. Pixel Processing Stage（像素处理阶段）（821）
				6. Framebuffer Techniques（帧缓冲技术）（825）
				7. Merging Stage（合并阶段）（826）
			5. Multiprocessing（多重处理）（826）
				1. Multiprocessor Pipelining（多处理器流水线）（827）
				2. Parallel Processing（并行处理）（830）
				3. Task-Based Multiprocessing（基于任务的多重处理）（832）
				4. Graphics API Multiprocessing Support（图形  API  多处理支持）（833）
			6. Further Reading and Resources（进一步阅读和资源）（835）
		19. Acceleration Algorithms（加速算法）（838）
			1. Spatial Data Structures（空间数据结构）（839）
				1. Bounding Volume Hierarchies（包围体层次结构）（840）
				2. BSP Trees（BSP树）（843）
					1. Axis-Aligned BSP Trees (k-D Trees)（轴对齐  BSP  树（kD  树））（843）
					2. Polygon-Aligned BSP Trees（多边形对齐  BSP  树）（844）
				3. Octrees（八叉树）（845）
				4. Cache-Oblivious and Cache-Aware Representations（缓存忽略和缓存感知陈述）（848）
				5. Scene Graphs（场景图）（848）
			2. Culling Techniques（剔除技术）（851）
			3. Backface Culling（背面剔除）（852）
			4. View Frustum Culling（视锥体剔除）（856）
			5. Portal Culling（门户剔除）（858）
			6. Detail and Small Triangle Culling（细节和小三角形剔除）（860）
			7. Occlusion Culling（遮挡剔除）（861）
				1. Occlusion Queries（遮挡查询）（865）
				2. Hierarchical Z-Buffering（分层Z  缓冲）（867）
			8. Culling Systems（剔除系统）（871）
			9. Level of Detail（详细程度）（873）
				1. LOD Switching（LOD切换）（875）
					1. Discrete Geometry LODs（离散几何  LOD）（875）
					2. Blend LODs（混合  LOD）（877）
					3. Alpha LODs（Alpha  LOD）（878）
					4. CLODs and Geomorph LODs（CLOD  和  Geomorph  LOD）（880）
				2. LOD Selection（LOD  选择）（881）
					1. Range-Based（基于范围）（881）
					2. Projected Area-Based（基于投影面积）（882）
					3. Other Selection Methods（其他选择方法）（885）
				3. Time-Critical LOD Rendering（时间关键的  LOD  渲染）（886）
			10. Rendering Large Scenes（渲染大场景）（888）
				1. Virtual Texturing and Streaming（虚拟纹理和流）（888）
				2. Texture Transcoding（纹理转码）（891）
				3. General Streaming（通用流媒体）（892）
				4. Terrain Rendering（地形渲染）（893）
			11. rther Reading and Resources（进一步阅读和资源）（900）
		20. Efficient Shading（高效遮阳）（904）
			1. Deferred Shading（延迟着色）（909）
			2. Decal Rendering（贴花渲染）（909）
			3. Tiled Shading（平铺着色）（913）
			4. Clustered Shading（簇状着色）（919）
			5. Deferred Texturing（延迟纹理）（926）
			6. Object- and Texture-Space Shading（对象空间和纹理空间着色）（929）
			7. Further Reading and Resources（进一步阅读和资源）（934）
		21. Virtual and Augmented Reality（虚拟和增强现实）（936）
			1. Equipment and Systems Overview（设备和系统概述）（937）
			2. Physical Elements（物理元素）（940）
				1. Latency（延迟）（941）
				2. Optics（光学）（942）
				3. Stereopsis（立体视觉）（943）
			3. APIs and Hardware（API和硬件）（945）
				1. Stereo Rendering（立体渲染）（948）
				2. Foveated Rendering（焦点渲染）（952）
			4. Rendering Techniques（渲染技术）（953）
				1. Judder（颤动）（956）
				2. Timing（时序）（959）
			5. Further Reading and Resources（进一步阅读和资源）（960）
		22. Intersection Test Methods（相交测试方法）（963）
			1. GPU-Accelerated Picking（GPU加速拣选）（963）
			2. Definitions and Tools（定义和工具）（964）
			3. Bounding Volume Creation（包围体创建）（969）
				1. AABB and k-DOP Creation（AABB  和k‑DOP  创建）（970）
				2. Sphere Creation（球体创建）（970）
				3. Convex Polyhedron Creation（凸多面体创建）（971）
				4. OBB Creation（OBB  创建）（972）
			4. Geometric Probability（几何概率）（974）
			5. Rules of Thumb（经验法则）（975）
			6. Ray/Sphere Intersection（射线/球体相交）（976）
				1. Mathematical Solution（数学解）（977）
				2. Optimized Solution（优化解）（978）
			7. Ray/Box Intersection（射线/盒子交集）（980）
				1. Slabs Method（板法）（980）
				2. Ray Slope Method（射线斜率法）（982）
			8. Ray/Triangle Intersection（射线/三角形相交）（983）
				1. Intersection Algorithm（交集算法）（984）
				2. Implementation（实施）（986）
			9. Ray/Polygon Intersection（射线/多边形相交）（987）
				1. The Crossings Test（交叉测试）（988）
			10. Plane/Box Intersection（平面/盒子相交）（991）
				1. AABB（991）
				2. OBB（993）
			11. Triangle/Triangle Intersection（三角形/三角形相交）（993）
			12. Triangle/Box Intersection（三角形/盒子的交点）（995）
			13. Bounding-Volume/Bounding-Volume Intersection（边界体积/边界体积交集）（997）
				1. Sphere/Sphere Intersection（球体/球体相交）（997）
				2. Sphere/Box Intersection（球体/长方体相交）（998）
				3. AABB/AABB Intersection（AABB/AABB  交点）（999）
				4. k-DOP/k-DOP Intersection（k‑DOP/k‑DOP交集）（1000）
				5. OBB/OBB Intersection（OBB/OBB  交叉点）（1001）
			14. View Frustum Intersection（视图截锥体交点）（1002）
				1. Frustum Plane Extraction（截锥体平面提取）（1004）
				2. Frustum/Sphere Intersection（平截头体/球体相交）（1005）
				3. Frustum/Box Intersection（平截头体/长方体相交）（1007）
			15. Line/Line Intersection（线/线交点）（1008）
				1. Two Dimensions（二维）（1008）
					1. First Method（第一种方法）（1008）
					2. Second Method（第二种方法）（1009）
				2. Three Dimensions（三个维度）（1010）
			16. Intersection between Three Planes（三个平面的交线）（1011）
			17. Further Reading and Resources（进一步阅读和资源）（1011）
		23. Graphics Hardware（图形硬件）（1014）
			1. Rasterization（光栅化）（1014）
				1. Interpolation（插值）（1019）
				2. Conservative Rasterization（保守光栅化）（1022）
			2. Massive Compute and Scheduling（海量计算与调度）（2023）
			3. Latency and Occupancy（延迟和占用）（1025）
			4. Memory Architecture and Buses（内存架构和总线）（1027）
			5. Caching and Compression（缓存和压缩）（1028）
			6. Color Buffering（颜色缓冲）（1030）
				1. Video Display Controller（视频显示控制器）（1032）
				2. Single, Double, and Triple Buffering（单缓冲、双缓冲和三缓冲）（1032）
			7. Depth Culling, Testing, and Buffering（深度剔除、测试和缓冲）（1035）
			8. Texturing（纹理）（1038）
			9. Architecture（架构）（1040）
			10. Case Studies（案例研究）（1045）
				1. Case Study: ARM Mali G71 Bifrost（案例研究：ARM  Mali  G71  Bifrost）（1045）
				2. Case Study: NVIDIA Pascal（案例研究：NVIDIA  Pascal）（1050）
				3. Case Study: AMD GCN Vega（案例研究：AMD  GCN  Vega）（1056）
			11. Ray Tracing Architectures（光线追踪架构）（1060）
			12. Further Reading and Resources（进一步阅读和资源）（1061）
		24. The Future（未来）（1062）
			1. Everything Else（其他一切）（1063）
			2. You（你）（1067）
	3. Physically Based Rendering（基于物理的渲染）
		1. INTRODUCTION（简介）（18）
			1. LITERATE PROGRAMMING（文学编程）（18）
				1. INDEXING AND CROSS-REFERENCING（索引和交叉引用）（20）
			2. PHOTOREALISTIC RENDERING AND THE RAY-TRACING ALGORITHM（真实感渲染和光线追踪算法）（21）
				1. CAMERAS（相机）（22）
				2. RAY–OBJECT INTERSECTIONS（射线‑物体相交）（24）
				3. LIGHT DISTRIBUTION（光分布）（25）
				4. VISIBILITY（能见度）（27）
				5. SURFACE SCATTERING（表面散射）（27）
				6. INDIRECT LIGHT TRANSPORT（间接光传输）（28）
				7. RAY PROPAGATION（射线传播）（30）
			3. pbrt: SYSTEM OVERVIEW（pbrt：系统概述）（32）
				1. PHASES OF EXECUTION（执行阶段）（34）
				2. SCENE REPRESENTATION（场景表示）（36）
				3. INTEGRATOR INTERFACE AND SamplerIntegrator（积分器接口和  SamplerIntegrator）（41）
				4. THE MAIN RENDERING LOOP（主渲染循环）（43）
				5. AN INTEGRATOR FOR WHITTED RAY TRACING（白射线追踪积分器）（49）
			4. PARALLELIZATION OF pbrt（pbrt的并行化）（55）
				1. DATA RACES AND COORDINATION（数据竞争和协调）（56）
				2. CONVENTIONS IN pbrt（pbrt中的约定）（59）
				3. THREAD SAFETY EXPECTATIONS IN pbrt（pbrt中的线程安全期望）（60）
			5. HOW TO PROCEED THROUGH THIS BOOK（如何继续阅读本书）（61）
				1. THE EXERCISES（练习）（62）
			6. USING AND UNDERSTANDING THE CODE（使用和理解代码）（62）
				1. POINTER OR REFERENCE?（指针还是引用）（62）
				2. ABSTRACTION VERSUS EFFICIENCY（抽象与效率）（63）
				3. CODE OPTIMIZATION（代码优化）（63）
				4. THE BOOK WEB SITE（本书网站）（64）
				5. EXTENDING THE SYSTEM（扩展系统）（64）
				6. BUGS（错误）（64）
			7. A BRIEF HISTORY OF PHYSICALLY BASED RENDERING（基于物理的渲染简史）（65）
				1. RESEARCH（研究）（65）
				2. PRODUCTION（生产）（67）
		2. GEOMETRY AND TRANSFORMATIONS（几何与变换）（73）
			1. COORDINATE SYSTEMS（坐标系）（73）
				1. COORDINATE SYSTEM HANDEDNESS（坐标系惯用手）（74）
			2. VECTORS（向量）（75）
				1. DOT AND CROSS PRODUCT（点积和叉积）（79）
				2. NORMALIZATION（标准化）（81）
				3. MISCELLANEOUS OPERATIONS（杂项操作）（82）
				4. COORDINATE SYSTEM FROM A VECTOR（向量坐标系）（83）
			3. POINTS（积分）（83）
			4. NORMALS（法线）（87）
			5. RAYS（射线）（88）
				1. RAY DIFFERENTIALS（光线微分）（90）
			6. BOUNDING BOXES（边界框）（91）
			7. TRANSFORMATIONS（转换）（97）
				1. HOMOGENEOUS COORDINATES（齐次坐标）（98）
				2. BASIC OPERATIONS（基本操作）（100）
				3. TRANSLATIONS（101）
				4. SCALING（缩放）（103）
				5. x, y, AND z AXIS ROTATIONS（x、  y  和z轴旋转）（104）
				6. ROTATION AROUND AN ARBITRARY AXIS（绕任意轴旋转）（105）
				7. THE LOOK-AT TRANSFORMATION（观察变换）（107）
			8. APPLYING TRANSFORMATIONS（应用变换）（109）
				1. POINTS（积分）（109）
				2. VECTORS（向量）（109）
				3. NORMALS（法线）（109）
				4. RAYS（射线）（111）
				5. BOUNDING BOXES（边界框）（111）
				6. COMPOSITION OF TRANSFORMATIONS（变换的组合）（112）
				7. TRANSFORMATIONS AND COORDINATE SYSTEM HANDEDNESS（变换和坐标系惯用手）（112）
			9. ANIMATING TRANSFORMATIONS（动画变换）（113）
				1. QUATERNIONS（四元数）（115）
				2. QUATERNION INTERPOLATION（四元数插值）（117）
				3. AnimatedTransform IMPLEMENTATION（AnimatedTransform  实现）（119）
				4. BOUNDING MOVING BOUNDING BOXES（边界移动边界框）（123）
			10. INTERACTIONS（互动）（130）
				1. SURFACE INTERACTION（表面相互作用）（132）
		3. SHAPES（形状）（138）
			1. BASIC SHAPE INTERFACE（基本形状界面）（138）
				1. BOUNDING（边界）（139）
				2. RAY–BOUNDS INTERSECTIONS（光线边界交点）（140）
				3. INTERSECTION TESTS（交叉口测试）（144）
				4. SURFACE AREA（表面积）（145）
				5. SIDEDNESS（侧面）（146）
			2. SPHERES（球体）（146）
				1. BOUNDING（边界）（148）
				2. INTERSECTION TESTS（交叉口测试）（149）
				3. PARTIAL DERIVATIVES OF NORMAL VECTORS（正规向量的偏导数）（153）
				4. SurfaceInteraction INITIALIZATION（表面交互初始化）（155）
				5. SURFACE AREA（表面积）（156）
			3. CYLINDERS（气缸）（157）
				1. BOUNDING（边界）（158）
				2. INTERSECTION TESTS（交叉口测试）（159）
				3. SURFACE AREA（表面积）（161）
			4. DISKS（磁盘）（161）
				1. BOUNDING（边界）（163）
				2. INTERSECTION TESTS（交叉口测试）（163）
				3. SURFACE AREA（表面积）（165）
			5. OTHER QUADRICS（其他二次方程）（165）
				1. CONES（锥体）（165）
				2. PARABOLOIDS（抛物面）（166）
				3. HYPERBOLOIDS（双曲面）（167）
			6. TRIANGLE MESHES（三角形网格）（167）
				1. TRIANGLE（三角形）（170）
				2. TRIANGLE INTERSECTION（三角形相交）（172）
				3. SHADING GEOMETRY（阴影几何形状）（181）
				4. SURFACE AREA（表面积）（182）
			7. CURVES（曲线）（184）
			8. SUBDIVISION SURFACES（细分曲面）（196）
				1. MESH REPRESENTATION（网格表示）（199）
				2. SUBDIVISON（细分）（207）
					1. Computing New Vertex Positions（计算新的顶点位置）（209）
					2. Updating Mesh Topology（更新网格拓扑）（215）
					3. To the Limit Surface and Output（限制曲面和输出）（218）
			9. MANAGING ROUNDING ERROR（管理舍入误差）（221）
				1. FLOATING-POINT ARITHMETIC（浮点运算）（223）
					1. Floating-Point Representation（浮点表示）（223）
					2. Utility Routines（实用例程）（226）
					3. Arithmetic Operations（算术运算）（228）
					4. Error Propagation（误差传播）（229）
					5. Running Error Analysis（运行误差分析）（233）
				2. CONSERVATIVE RAY–BOUNDS INTERSECTIONS（保守光线边界交点）（235）
				3. ROBUST TRIANGLE INTERSECTIONS（稳健三角形交点）（236）
				4. BOUNDING INTERSECTION POINT ERROR（边界交点误差）（237）
					1. Reprojection: Quadrics（重投影：二次曲面）（238）
					2. Parametric Evaluation: Triangles（参数评估：三角形）（240）
					3. Other Shapes（其他形状）（242）
					4. Effect of Transformations（转换的效果）（242）
				5. ROBUST SPAWNED RAY ORIGINS（稳健的射线生成源）（245）
				6. AVOIDING INTERSECTIONS BEHIND RAY ORIGINS（避免射线原点后面的相交）（248）
				7. DISCUSSION（讨论）（250）
		4. PRIMITIVES AND NTERSECTION ACCELERATION（基元和交集加速）（260）
			1. PRIMITIVE INTERFACE AND GEOMETRIC PRIMITIVES（基元接口和几何基元）（261）
				1. GEOMETRIC PRIMITIVES（几何原语）（几何基元）（263）
				2. TransformedPrimitive: OBJECT INSTANCING AND ANIMATED PRIMITIVES（TransformedPrimitive：对象实例和动画基元）（264）
			2. AGGREGATES（聚合）（267）
			3. BOUNDING VOLUME HIERARCHIES（边界体层次结构）（268）
				1. BVH CONSTRUCTION（BVH  建设）（270）
				2. THE SURFACE AREA HEURISTIC（表面积启发法）（276）
				3. LINEAR BOUNDING VOLUME HIERARCHIES（线性边界体层次结构）（281）
				4. COMPACT BVH FOR TRAVERSAL（用于遍历的紧凑  BVH）（293）
				5. TRAVERSAL（遍历）（295）
			4. KD-TREE ACCELERATOR（KD树加速器）（297）
				1. TREE REPRESENTATION（树的表示）（299）
				2. TREE CONSTRUCTION（树的构造）（301）
				3. TRAVERSA（遍历）（310）
		5. COLOR AND RADIOMETRY（颜色和辐射度）（324）
			1. SPECTRAL REPRESENTATION（光谱表示）（324）
				1. THE Spectrum TYPE（频谱类型）（326）
				2. CoefficientSpectrum IMPLEMENTATION（CoefficientSpectrum  实现）（326）
			2. THE SampledSpectrum CLASS（采样频谱类）（329）
				1. XYZ COLOR（XYZ  颜色）（333）
				2. RGB COLOR（RGB  颜色）（336）
			3. RGBSpectrum IMPLEMENTATION（RGBSpectrum  实现）（342）
			4. RADIOMETRY（辐射测量）（345）
				1. BASIC QUANTITIES（基本数量）（346）
					1. Energy（能量）（346）
					2. Flux（通量）（346）
					3. Irradiance and Radiant Exitance（辐照度和辐射出射度）（347）
					4. Solid Angle and Intensity（立体角和强度）（348）
					5. Radiance（辐射度）（350）
				2. INCIDENT AND EXITANT RADIANCE FUNCTIONS（入射和出射辐射函数）（350）
				3. LUMINANCE AND PHOTOMETRY（亮度和光度测量）（352）
			5. WORKING WITH RADIOMETRIC INTEGRALS（使用辐射积分）（354）
				1. INTEGRALS OVER PROJECTED SOLID ANGLE（投影立体角上的积分）（354）
				2. INTEGRALS OVER SPHERICAL COORDINATES（球坐标上的积分）（355）
				3. INTEGRALS OVER AREA（面积积分）（358）
			6. SURFACE REFLECTION（表面反射）（359）
				1. THE BRDF（360）
				2. THE BSSRDF（362）
		6. CAMERA MODELS（相机型号）（365）
			1. CAMERA MODEL（相机型号）（366）
				1. CAMERA COORDINATE SPACES（相机坐标空间）（368）
			2. PROJECTIVE CAMERA MODELS（投影相机模型）（368）
				1. ORTHOGRAPHIC CAMERA（正交相机）（371）
				2. PERSPECTIVE CAMERA（透视相机）（375）
				3. THE THIN LENS MODEL AND DEPTH OF FIELD（薄透镜模型和景深）（378）
			3. ENVIRONMENT CAMERA（环境相机）（385）
			4. REALISTIC CAMERAS（真实的相机）（387）
				1. LENS SYSTEM REPRESENTATION（镜头系统表示）（389）
				2. TRACING RAYS THROUGH LENSES（通过透镜追踪光线）（392）
				3. THE THICK LENS APPROXIMATION（厚透镜近似）（396）
				4. FOCUSING（聚焦）（398）
				5. THE EXIT PUPIL（出瞳）（399）
				6. GENERATING RAYS（生成射线）（404）
				7. THE CAMERA MEASUREMENT EQUATION（相机测量方程）（405）
		7. SAMPLING AND RECONSTRUCTION（采样和重建）（410）
			1. SAMPLING THEORY（抽样理论）（411）
				1. THE FREQUENCY DOMAIN AND THE FOURIER TRANSFORM（频域和傅立叶变换）（412）
				2. IDEAL SAMPLING AND RECONSTRUCTION（理想采样和重建）（414）
				3. ALIASING（别名）（418）
				4. ANTIALIASING TECHNIQUES（抗锯齿技术）（419）
					1. Nonuniform Sampling（非均匀采样）（420）
					2. Adaptive Sampling（自适应采样）（421）
					3. Prefiltering（预滤波）（421）
				5. APPLICATION TO IMAGE SYNTHESIS（在图像合成中的应用）（422）
				6. SOURCES OF ALIASING IN RENDERING（渲染中锯齿的来源）（423）
				7. UNDERSTANDING PIXELS（理解像素）（424）
			2. SAMPLING INTERFACE（采样接口）（425）
				1. EVALUATING SAMPLE PATTERNS: DISCREPANCY（评估样本模式：差异）（426）
				2. BASIC SAMPLER INTERFACE（基本采样器接口）（430）
				3. SAMPLER IMPLEMENTATION（采样器实现）（434）
				4. PIXEL SAMPLER（像素采样器）（436）
				5. GLOBAL SAMPLER（全局采样器）（437）
			3. STRATIFIED SAMPLING（分层抽样）（441）
			4. THE HALTON SAMPLER（Halton  采样器）（450）
				1. HAMMERSLEY AND HALTON SEQUENCES（Hammersley  和  Halton  序列）（452）
				2. HALTON SAMPLER IMPLEMENTATION（HALTON  采样器实现）（459）
			5. (0, 2)-SEQUENCE SAMPLER（(0,  2)‑序列采样器）（463）
				1. SAMPLING WITH GENERATOR MATRICES（使用生成矩阵进行采样）（464）
				2. SAMPLER IMPLEMENTATION（采样器实现）（471）
			6. MAXIMIZED MINIMAL DISTANCE SAMPLER（最大最小距离采样器）（474）
			7. SOBOL’ SAMPLER（索博尔采样器）（476）
			8. IMAGE RECONSTRUCTION（图像重建）（481）
				1. FILTER FUNCTIONS（过滤器功能）（483）
					1. Box Filter（盒式过滤器）（484）
					2. Triangle Filter（三角形过滤器）（486）
					3. Gaussian Filter（高斯滤波器与盒式滤）（486）
					4. Mitchell Filter（米切尔滤波器滤波）（488）
					5. Windowed Sinc Filter（窗口  Sinc  滤波器）（490）
			9. FILM AND THE IMAGING PIPELINE（胶片和成像流程）（492）
				1. THE FILM CLASS（电影类）（497）
				2. SUPPLYING PIXEL VALUES TO THE FILM（为影片提供像素值）（497）
				3. IMAGE OUTPUT（图像输出）（503）
		8. REFLECTION MODELS（反射模型）（514）
			1. BASIC INTERFACE（基本界面）（519）
				1. REFLECTANCE（反射率）（521）
				2. BxDF SCALING ADAPTER（BxDF  缩放适配器）（522）
			2. SPECULAR REFLECTION AND TRANSMISSION（镜面反射和透射）（523）
				1. FRESNEL REFLECTANCE（菲涅耳反射率）（523）
					1. Fresnel Conductors（529）
					2. Fresnel Dielectrics（529）
					3. A Special Fresnel Interface（特殊的菲涅尔接口）（530）
				2. SPECULAR REFLECTION（镜面反射）（530）
				3. SPECULAR TRANSMISSION（镜面透射）（533）
				4. FRESNEL-MODULATED SPECULAR REFLECTION AND TRANSMISSION（菲涅耳调制镜面反射和透射）（538）
			3. LAMBERTIAN REFLECTION（朗伯反射）（539）
			4. MICROFACET MODELS（微面模型）（540）
				1. OREN–NAYAR DIFFUSE REFLECTION（奥伦‑纳亚尔漫反射）（541）
				2. MICROFACET DISTRIBUTION FUNCTIONS（微面分布函数）（544）
				3. MASKING AND SHADOWING（掩蔽和阴影）（548）
				4. THE TORRANCE–SPARROW MODEL（托伦斯‑斯帕罗模型）（551）
			5. FRESNEL INCIDENCE EFFECTS（菲涅耳入射效应）（556）
			6. FOURIER BASIS BSDFs（傅里叶基  BSDF）（559）
				1. SPLINE INTERPOLATION（样条插值）（567）
		9. MATERIALS（材质）（576）
			1. BSDFs（576）
				1. BSDF MEMORY MANAGEMENTO（BSDF  内存管理）（581）
			2. MATERIAL INTERFACE AND IMPLEMENTATIONS（材质接口和实现）（582）
				1. MATTE MATERIAL（哑光材质）（583）
				2. PLASTIC MATERIAL（塑料材料）（584）
				3. MIX MATERIAL（混合材料）（586）
				4. FOURIER MATERIAL（傅立叶材料）（588）
				5. ADDITIONAL MATERIALS（附加材料）（589）
			3. BUMP MAPPING（凹凸贴图）（589）
		10. TEXTURE（纹理）（600）
			1. SAMPLING AND ANTIALIASING（采样和抗锯齿）（601）
				1. FINDING THE TEXTURE SAMPLING RATE（求纹理采样率）（602）
				2. FILTERING TEXTURE FUNCTIONS（过滤纹理函数）（607）
				3. RAY DIFFERENTIALS FOR SPECULAR REFLECTION AND TRANSMISSION（镜面反射和透射的光线微分）（608）
			2. TEXTURE COORDINATE GENERATION（纹理坐标生成）（611）
				1. 2D (u, v) MAPPING（2D  (u,  v)映射）（613）
				2. SPHERICAL MAPPING（球面映射）（614）
				3. CYLINDRICAL MAPPING（圆柱映射）（615）
				4. PLANAR MAPPING（平面映射）（616）
				5. 3D MAPPING（3D  映射）（616）
			3. TEXTURE INTERFACE AND BASIC TEXTURES（纹理接口和基本纹理）（617）
				1. CONSTANT TEXTURE（恒定纹理）（618）
				2. SCALE TEXTURE（鳞片纹理）（618）
				3. MIX TEXTURES（混合纹理）（619）
				4. BILINEAR INTERPOLATION（双线性插值）（620）
			4. IMAGE TEXTURE（图像纹理）（621）
				1. TEXTURE MEMORY MANAGEMENT（纹理内存管理）（623）
				2. ImageTexture EVALUATION（图像纹理评估）（625）
				3. MIP MAPS（MIP  映射）（626）
				4. ISOTROPIC TRIANGLE FILTER（各向同性三角形滤波器）（635）
				5. ELLIPTICALLY WEIGHTED AVERAGE（椭圆加权平均）（637）
			5. SOLID AND PROCEDURAL TEXTURING（实体和程序纹理）（643）
				1. UV TEXTURE（紫外线纹理）（644）
				2. CHECKERBOARD（棋盘）（645）
				3. SOLID CHECKERBOARD（实体棋盘）（649）
			6. NOISE（噪声）（651）
				1. PERLIN NOISE（柏林噪声）（652）
				2. RANDOM POLKA DOTS（随机圆点）（656）
				3. NOISE IDIOMS AND SPECTRAL SYNTHESIS（噪声习语和谱合成）（658）
				4. BUMPY AND WRINKLED TEXTURES（凹凸不平和皱纹纹理）（663）
				5. WINDY WAVES（风浪）（665）
				6. MARBLE（大理石）（666）
		11. VOLUME SCATTERING（体散射）（673）
			1. VOLUME SCATTERING PROCESSES（体散射过程）（674）
				1. ABSORPTION（吸收）（675）
				2. EMISSION（排放）（676）
				3. OUT-SCATTERING AND ATTENUATION（外散射和衰减）（678）
				4. IN-SCATTERING（内散射）（680）
			2. PHASE FUNCTIONS（相函数）（682）
			3. MEDIA（媒体）（686）
				1. MEDIUM INTERACTIONS（中等交互）（689）
				2. HOMOGENEOUS MEDIUM（均质介质）（691）
				3. 3D GRIDS（3D  网格）（692）
			4. THE BSSRDF（694）
				1. SEPARABLE BSSRDFS（可分离的  BSSRDFS）（695）
				2. TABULATED BSSRDF（表格化  BSSRDF）（698）
				3. SUBSURFACE SCATTERING MATERIALS（地下散射材料）（702）
		12. LIGHT SOURCES（光源）（707）
			1. LIGHT EMISSION（光发射）（708）
				1. BLACKBODY EMITTERS（黑体发射器）（709）
				2. STANDARD ILLUMINANTS（标准光源）（712）
			2. LIGHT INTERFACE（灯光接口）（714）
				1. VISIBILITY TESTING（能见度测试）（717）
			3. POINT LIGHTS（点光源）（719）
				1. SPOTLIGHTS（亮点）（721）
				2. TEXTURE PROJECTION LIGHTS（纹理投影灯）（724）
				3. GONIOPHOTOMETRIC DIAGRAM LIGHTS（测角光度图灯）（728）
			4. DISTANT LIGHTS（远距离灯光）（731）
			5. AREA LIGHTS（区域灯）（733）
			6. INFINITE AREA LIGHTS（无限区域灯）（737）
		13. MONTE CARLO INTEGRATION（蒙特卡罗积分）（746）
			1. BACKGROUND AND PROBABILITY REVIEW（背景和可能性回顾）（747）
				1. CONTINUOUS RANDOM VARIABLES（连续随机变量）（748）
				2. EXPECTED VALUES AND VARIANCE（期望值和方差）（749）
			2. THE MONTE CARLO ESTIMATOR（蒙特卡洛估计器）（750）
			3. SAMPLING RANDOM VARIABLES（随机变量采样）（752）
				1. THE INVERSION METHOD（反演方法）（752）
					1. Example: Power Distribution（⽰例：功率分布）（754）
					2. Example: Exponential Distribution（⽰例：指数分布）（755）
					3. Example: Piecewise-Constant 1D Functions（⽰例：分段常数一维函数）（756）
				2. THE REJECTION METHOD（拒绝方法）（759）
					1. Example: Rejection Sampling a Unit Circle（⽰例：对单位圆进行拒绝采样）（760）
			4. METROPOLIS SAMPLING（大都市采样）（761）
				1. BASIC ALGORITHM（基本算法）（762）
				2. CHOOSING MUTATION STRATEGIES（选择突变策略）（763）
				3. START-UP BIAS（启动偏差）（765）
				4. 1D SETTING（一维设置）（765）
				5. ESTIMATING INTEGRALS WITH METROPOLIS SAMPLING（使用  METROPOLIS  采样估计积分）（770）
			5. TRANSFORMING BETWEEN DISTRIBUTIONS（发行版之间的转换）（770）
				1. TRANSFORMATION IN MULTIPLE DIMENSIONS（多维度转型）（771）
				2. POLAR COORDINATES（极坐标）（771）
				3. SPHERICAL COORDINATES（球坐标）（772）
			6. 2D SAMPLING WITH MULTIDIMENSIONAL TRANSFORMATIONS（具有多维变换的 2D 采样）（772）
				1. UNIFORMLY SAMPLING A HEMISPHERE（半球均匀采样）（773）
				2. SAMPLING A UNIT DISK（对单位圆盘进行采样）（775）
				3. COSINE-WEIGHTED HEMISPHERE SAMPLING（余弦加权半球采样）(778)
				4. SAMPLING A CONE（圆锥体采样）（780）
				5. SAMPLING A TRIANGLE（三角形采样）（780）
				6. SAMPLING CAMERAS（采样相机）（782）
				7. PIECEWISE-CONSTANT 2D DISTRIBUTIONS（分段常数二维分布）（783）
			7. RUSSIAN ROULETTE AND SPLITTING（俄罗斯轮盘赌和分裂）（786）
				1. SPLITTING（分裂）（787）
			8. CAREFUL SAMPLE PLACEMENT（小心放置样品）（788）
				1. STRATIFIED SAMPLING（分层抽样）（788）
				2. QUASI MONTE CARLO（准蒙特卡罗）（791）
				3. WARPING SAMPLES AND DISTORTION（样本变形和畸变）（791）
			9. BIAS（偏差）(792)
			10. IMPORTANCE SAMPLING（重要性抽样）（793）
				1. MULTIPLE IMPORTANCE SAMPLING（多重重要性抽样）（796）
		14. LIGHT TRANSPORT I: SURFACE REFLECTION（光传输 I：表面反射）（802）
			1. SAMPLING REFLECTION FUNCTIONS（采样反射函数）（803）
				1. MICROFACET BxDFS（微面  BxDFS）（804）
				2. FresnelBlend（菲涅耳混合）（811）
				3. SPECULAR REFLECTION AND TRANSMISSION（镜面反射和透射）（812）
				4. FOURIER BSDF（傅里叶BSDF）（814）
					1. Sampling 1D Spline Interpolants（一维样条插值采样）（818）
					2. Sampling 2D Spline Interpolants（采样  2D  样条插值）（821）
					3. Sampling Fourier Expansions（采样傅里叶展开）（825）
				5. APPLICATION: ESTIMATING REFLECTANCE（应用：估计反射率）（827）
				6. SAMPLING BSDFs（BSDF  采样）（829）
			2. SAMPLING LIGHT SOURCES（光源采样）（832）
				1. LIGHTS WITH SINGULARITIES（具有奇点的光）（833）
				2. SAMPLING SHAPES（采样形状）（833）
					1. Sampling Disks（圆盘采样）（835）
					2. Sampling Cylinders（气瓶采样）（836）
					3. Sampling Triangles（采样三角形）（836）
					4. Sampling Spheres（球体采样）（837）
				3. AREA LIGHTS（区域灯）（842）
				4. INFINITE AREA LIGHTS（无限区域灯）（842）
			3. DIRECT LIGHTING（直接照明）（848）
				1. ESTIMATING THE DIRECT LIGHTING INTEGRAL（估计直接照明积分）（853）
			4. THE LIGHT TRANSPORT EQUATION（光传输方程）（858）
				1. BASIC DERIVATION（基本推导）（859）
				2. ANALYTIC SOLUTIONS TO THE LTE（LTE  分析解）（860）
				3. THE SURFACE FORM OF THE LTE（LTE的表面形态）（862）
				4. INTEGRAL OVER PATHS（路径积分）（863）
				5. DELTA DISTRIBUTIONS IN THE INTEGRAND（积分中的  Delta  分布）（865）
				6. PARTITIONING THE INTEGRAND（被积的划分）（866）
			5. PATH TRACING（路径追踪）（867）
				1. OVERVIEW（概述）（869）
				2. PATH SAMPLING（路径采样）（870）
				3. INCREMENTAL PATH CONSTRUCTION（增量路径构建）（871）
				4. IMPLEMENTATION（实施）（872）
		15. LIGHT TRANSPORT II: VOLUME RENDERING（光传输 II：体积渲染）（883）
			1. THE EQUATION OF TRANSFER（传递方程）（884）
				1. GENERALIZED PATH SPACE（广义路径空间）（886）
			2. SAMPLING VOLUME SCATTERING（体积散射采样）（887）
				1. HOMOGENEOUS MEDIUM（均质介质）（889）
				2. HETEROGENEOUS MEDIUM（异质介质）（890）
				3. SAMPLING PHASE FUNCTIONS（采样阶段函数）（894）
			3. VOLUMETRIC LIGHT TRANSPORT（体积光传输）（895）
				1. PATH TRACING（路径追踪）（896）
			4. SAMPLING SUBSURFACE REFLECTION FUNCTIONS（采样地下反射函数）（899）
				1. SAMPLING THE SeparableBSSRDF（对  SeparableBSSRDF  进行采样）（901）
				2. SAMPLING THE TabulatedBSSRDF（对  TabulatedBSSRDF  进行采样）（909）
				3. SUBSURFACE SCATTERING IN THE PATH TRACER（路径追踪器中的次表面散射）（911）
			5. SUBSURFACE SCATTERING USING THE DIFFUSION EQUATION（使用扩散方程的次表面散射）（912）
				1. PRINCIPLE OF SIMILARITY（相似原则）（913）
				2. DIFFUSION THEORY（扩散理论）（914）
				3. MONOPOLE SOLUTION（单极子解决方案）（919）
				4. NON-CLASSICAL DIFFUSION（非经典扩散）（920）
				5. DIPOLE SOLUTION（偶极子解）（921）
					1. Boundary Conditions（边界条件）（922）
					2. Radiant Exitance（辐射出射度）（922）
				6. BEAM SOLUTION（梁解）（924）
				7. SINGLE SCATTERING TERM（单散射项）（926）
				8. FILLING THE BSSRDFTable（填充  BSSRDF  表）（930）
				9. SETTING SCATTERING PROPERTIES（设置散射属性）（934）
		16. LIGHT TRANSPORT III: BIDIRECTIONAL METHODS（光传输 III：双向方法）（942）
			1. THE PATH-SPACE MEASUREMENT EQUATION（路径空间测量方程）（943）
				1. SAMPLING CAMERAS（采样相机）（944）
				2. SAMPLING LIGHT RAYS（光线采样）（950）
					1. Point Lights（点光源）（950）
					2. Spotlights（聚光灯）（951）
					3. Area Lights（区域光）（952）
					4. Distant Lights（远光）（952）
					5. Infinite Area Lights（无限区域光）（954）
				3. NON-SYMMETRIC SCATTERING（非对称散射）（955）
					1. Non-symmetry Due to Refraction（折射导致的非对称性）（956）
					2. Non-symmetry Due to Shading Normals（由于着色法线导致的不对称）（957）
			2. STOCHASTIC PROGRESSIVE PHOTON MAPPING（随机渐进光子映射）（958）
				1. THEORETICAL BASIS FOR PARTICLE TRACING（粒子追踪的理论基础）（958）
				2. PHOTON MAPPING（光子映射）（961）
					1. Progressive Photon Mapping（渐进光子映射）（965）
					2. Stochastic Progressive Photon Mapping（随机渐进光子映射）（966）
				3. SPPMIntegrator（SPPM积分器）（967）
				4. ACCUMULATING VISIBLE POINTS（累积可见点）（970）
				5. VISIBLE POINT GRID CONSTRUCTION（可见点网格构建）（974）
				6. ACCUMULATING PHOTON CONTRIBUTIONS（累积光子贡献）（978）
			3. BIDIRECTIONAL PATH TRACING（双向路径追踪）（985）
				1. VERTEX ABSTRACTION LAYER（顶点抽象层）（990）
					1. Probability Densities（概率密度）（995）
				2. GENERATING THE CAMERA AND LIGHT SUBPATHS（生成相机和灯光子路径）（998）
				3. SUBPATH CONNECTIONS（子路径连接）（1003）
				4. MULTIPLE IMPORTANCE SAMPLING（多重重要性采样）（1007）
				5. INFINITE AREA LIGHTS AND BDPT（无限区域灯和  BDPT）（1014）
			4. METROPOLIS LIGHT TRANSPORT（大都市光传输）（1017）
				1. PRIMARY SAMPLE SPACE MLT（主样本空间MLT）（1018）
				2. MULTIPLEXED MLT（复用  MLT）（1020）
				3. APPLICATION TO RENDERING（渲染应用）（1020）
				4. PRIMARY SAMPLE SPACE SAMPLER（主样本空间采样器）（1023）
				5. MLT INTEGRATOR（MLT  积分器）（1030）
					1. Main Rendering Loop（主渲染循环）（1032）
		17. RETROSPECTIVE AND THE FUTURE（回顾与未来）（1045）
			1. DESIGN RETROSPECTIVE（设计回顾）（1045）
				1. TRIANGLES ONLY（仅三角形）（1046）
				2. INCREASED SCENE COMPLEXITY（增加场景复杂性）（1047）
				3. PRODUCTION RENDERING（生产渲染）（1048）
				4. SPECIALIZED COMPILATION（专门编译）（1048）
			2. ALTERNATIVE HARDWARE ARCHITECTURES（替代硬件架构）（1049）
				1. GPU RAY TRACING（GPU  光线追踪）（1050）
				2. PACKET TRACING（数据包跟踪）（1051）
				3. RAY-TRACING HARDWARE（光线追踪硬件）（1053）
				4. THE FUTURE（未来）（1053）
			3. CONCLUSION（结论）（1054）
8. Game Artificial Intelligence（游戏人工智能（AI））
	1. Artificial Intelligence For Games（游戏人工智能）
		1. AI and Games（人工智能与游戏）（40）
			1. INTRODUCTION（介绍）（42）
				1. WHAT IS AI?（什么是人工智能？）（43）
					1. ACADEMIC AI（学术人工智能）（44）
						1. The Early Days（早期）（44）
						2. The Symbolic Era（象征时代）（44）
						3. The Natural Era（自然时代）（45）
						4. Engineering（工程）（46）
					2. GAME AI（游戏人工智能）（47）
				2. MY MODEL OF GAME AI（我的游戏人工智能模型）（48）
					1. MOVEMENT（运动）（49）
					2. DECISION MAKING（决策）（49）
					3. STRATEGY（策略）（50）
					4. INFRASTRUCTURE（基础设施）（50）
					5. AGENT-BASED AI（基于代理的人工智能）（51）
					6. IN THE BOOK（书中）（51）
				3. ALGORITHMS, DATA STRUCTURES, AND REPRESENTATIONS（算法、数据结构和表示）（52）
					1. ALGORITHMS（算法）（52）
						1. Performance Characteristics（性能特点）（53）
						2. Pseudo-Code（伪代码）（53）
					2. REPRESENTATIONS（表述）（55）
				4. ON THE CD（光盘上）（56）
					1. PROGRAMS（程序）（56）
					2. Optimizations（优化）（57）
					3. Rendering and Maths（渲染和数学）（57）
					4. Getting the Latest Code（获取最新代码）（57）
				5. LAYOUT OF THE BOOK（本书的版式）（58）
			2. GAME AI（游戏人工智能）（60）
				1. THE COMPLEXITY FALLACY（复杂性谬误）（60）
					1. WHEN SIMPLE THINGS LOOK GOOD（当简单的事情看起来不错时）（60）
					2. WHEN COMPLEX THINGS LOOK BAD（当复杂的事情看起来很糟糕时）（61）
					3. THE PERCEPTION WINDOW（感知窗口）（62）
					4. CHANGES OF BEHAVIOR（行为改变）（62）
				2. THE KIND OF AI IN GAMES（游戏中的人工智能类型）（63）
					1. HACKS（黑客攻击）（63）
					2. HEURISTICS（启发式）（64）
						1. Common Heuristics（常见启发法）（65）
					3. ALGORITHMS（算法）（66）
				3. SPEED AND MEMORY（速度和内存）（66）
					1. PROCESSOR ISSUES（处理器问题）（67）
						1. SIMD（单指令多数据流）（67）
						2. Multi-Core Processing and Hyper-Threading（多核处理和超线程）（68）
						3. Virtual Functions/Indirection（虚函数/间接）（69）
					2. MEMORY CONCERNS（内存问题）（70）
						1. Cache（缓存）（70） 
					3. PC CONSTRAINTS（PC限制）（71）
					4. CONSOLE CONSTRAINTS（控制台限制）（71）
						1. Working with Rendering Hardware（使用渲染硬件）（72）
						2. Handheld Consoles（手持控制台）（73）
				4. THE AI ENGINE（人工智能引擎）（74）
					1. STRUCTURE OF AN AI ENGINE（人工智能引擎的结构）（74）
					2. TOOLCHAIN CONCERNS（工具链问题）（76）
					3. PUTTING IT ALL TOGETHER（综合起来_）（77）
		2. Techniques（技巧）（78）
			1. MOVEMENT（移动）（80）
				1. THE BASICS OF MOVEMENT ALGORITHMS（运动算法的基础）（81）
					1. TWO-DIMENSIONAL MOVEMENT（二维运动）（82）
						1. Characters as Points（字符作为点）（82）
					2. STATICS（统计数据）（83）
						1. 2½ Dimensions（2½ 方面）（84）
						2. Math（数学）（85）
					3. KINEMATICS（运动学）（86）
						1. Independent Facing（独立面向）（87）
						2. Updating Position and Orientation（更新位置和方向）（88）
						3. Variable Frame Rates（可变帧率）（89）
						4. Forces and Actuation（力和驱动）（89）
				2. KINEMATIC MOVEMENT ALGORITHMS（运动算法）（90）
					1. SEEK（寻找）（91）
						1. Data Structures and Interfaces（数据结构和接口）（92）
						2. Performance（表现）（92）
						3. Flee（逃跑）（92）
						4. Arriving（到达）（93）
					2. WANDERING（徘徊）（94）
						1. Pseudo-Code（伪代码）（95）
						2. Data Structure（数据结构）（96）
						3. Implementation Notes（实施说明）（96）
					3. ON THE CD（光盘上）（96）
				3. STEERING BEHAVIORS（转向行为）（96）
					1. STEERING BASICS（转向基础知识）（97）
					2. VARIABLE MATCHING（变量匹配）（97）
					3. SEEK AND FLEE（寻找并逃跑）（98）
						1. Pseudo-Code（伪代码）（99）
						2. Data Structures and Interfaces（数据结构和接口）（101）
						3. Performance（表现）（101）
						4. Flee（逃跑）（101）
					4. ARRIVE（到达）（101）
						1. Pseudo-Code（伪代码）（103）
						2. Performance（表现）（104）
						3. Implementation Notes（实施说明）（104）
						4. Leave（离开）（104）
					5. ALIGN（对齐）（105）
						1. Pseudo-Code（伪代码）（106）
						2. Implementation Notes（实施说明）（107）
						3. Performance（表现）（108）
						4. The Opposite（相反）（108）
					6. VELOCITY MATCHING（速度匹配）（108）
						1. Pseudo-Code（伪代码）（108）
						2. Performance（表现）（109）
					7. DELEGATED BEHAVIORS（委托行为）（109）
					8. PURSUE AND EVADE（追击与躲避）（110）
						1. Pseudo-Code（伪代码）（111）
						2. Implementation Notes（实施说明）（113）
						3. Performance（表现）（113）
						4. Evade（逃避）（113）
						5. Overshooting（超调）（113）
					9. FACE（人脸）（113）
						1. Pseudo-Code（伪代码）（114）
					10. LOOKING WHERE YOU’RE GOING（看看你要去哪里）（114）
						1. Pseudo-Code（伪代码）（115）
						2. Implementation Notes（实施说明）（115）
						3. Performance（表现）（115）
					11. WANDER（徘徊）（115）
						1. Pseudo-Code（伪代码）（117）
						2. Data Structures and Interfaces（数据结构和接口）（118）
						3. Performance（表现）（118）
					12. PATH FOLLOWING（路径跟踪）（118）
						1. Pseudo-Code（伪代码）（121）
						2. Data Structures and Interfaces（数据结构和接口）（122）
						3. Performance（表现）（124）
					13. SEPARATION（分离）（124）
						1. Pseudo-Code（伪代码）（125）
						2. Implementation Notes（实施说明）（126）
						3. Performance（表现）（127）
						4. Attraction（景点）（127）
						5. Independence（独立）（127）
					14. COLLISION AVOIDANCE（避免碰撞）（127）
						1. Pseudo-Code（伪代码）（130）
						2. Performance（表现）（132）
					15. OBSTACLE AND WALL AVOIDANCE（障碍物和墙壁躲避）（133）
						1. Pseudo-Code（伪代码）（133）
						2. Data Structures and Interfaces（数据结构和接口）（134）
						3. Performance（表现）（135）
						4. Collision Detection Problems（碰撞检测问题）（135）
					16. SUMMARY（总结）（139）
				4. COMBINING STEERING BEHAVIORS（组合转向行为）（139）
					1. BLENDING AND ARBITRATION（混合和仲裁）（139）
					2. WEIGHTED BLENDING（加权混合）（140）
						1. The Algorithm（算法）（140）
						2. Pseudo-Code（伪代码）（141）
						3. Data Structures（数据结构）（141）
						4. Performance（表现）（142）
						5. Flocking and Swarming（蜂拥而至）（142）
						6. On the CD（光盘上）（143）
						7. Problems（问题）（143）
					3. PRIORITIES（优先事项）（146）
						1. The Algorithm（算法）（147）
						2. Pseudo-Code（伪代码）（147）
						3. Data Structures and Interfaces（数据结构和接口）（148）
						4. Implementation Notes（实施说明）（148）
						5. On the CD（光盘上）（148）
						6. Performance（表现）（149）
						7. Equilibria Fallback（均衡回退）（149）
						8. Weaknesses（弱点）（149）
						9. Variable Priorities（可变优先级）（150）
					4. COOPERATIVE ARBITRATION（合作仲裁）（150）
					5. STEERING PIPELINE（转向管路）（152）
						1. Algorithm（算法）（153）
						2. Pseudo-Code（伪代码）（157）
						3. Data Structures and Interfaces（数据结构和接口）（158）
						4. Performance（表现）（160）
						5. On the CD（光盘上）（161）
						6. Example Components（示例组件）（161）
						7. Conclusion（结论）（165）
				5. PREDICTING PHYSICS（预测物理学）（165）
					1. AIMING AND SHOOTING（瞄准和射击）（165）
					2. PROJECTILE TRAJECTORY（弹丸轨迹）（166）
						1. Predicting a Landing Spot（预测着陆点）（167）
					3. THE FIRING SOLUTION（点火解决方案）（168）
					4. PROJECTILES WITH DRAG（具有阻力的射弹）（171）
						1. Rotating and Lift（旋转和提升）（173）
					5. ITERATIVE TARGETING（迭代定位）（173）
						1. The Problem（问题）（173）
						2. The Algorithm（算法）（174）
						3. Pseudo-Code（伪代码）（175）
						4. Data Structures and Interfaces（数据结构和接口）（177）
						5. Performance（表现）（178）
						6. Iterative Targeting without Motion Equations（无需运动方程的迭代定位）（178）
						7. Other Uses of Prediction（预测的其他用途）（179）
				6. JUMPING（跳跃）（179）
					1. JUMP POINTS（跳转点）（180）
						1. Achieving the Jump（实现跳跃）（182）
						2. Weaknesses（弱点）（183）
					2. LANDING PADS（停机坪）（184）
						1. The Trajectory Calculation（轨迹计算）（184）
						2. Pseudo-Code（伪代码）（185）
						3. Data Structures and Interfaces（数据结构和接口）（187）
						4. Implementation Notes（实施说明）（188）
						5. Performance（表现）（188）
						6. Jump Links（跳转链接）（188）
					3. HOLE FILLERS（孔填充剂）（188）
				7. COORDINATED MOVEMENT（协调运动）（190）
					1. FIXED FORMATIONS（固定阵型）（190）
					2. SCALABLE FORMATIONS（可扩展的阵型）（192）
					3. EMERGENT FORMATIONS（紧急阵型）（192）
					4. TWO-LEVEL FORMATION STEERING（两级编队操舵）（194）
						1. Removing the Leader（移除领导者）（195）
						2. Moderating the Formation Movement（缓和队形运动）（195）
						3. Drift（漂移）（196）
					5. IMPLEMENTATION（实施）（197）
						1. Data Structures and Interfaces（数据结构和接口）（200）
						2. Implementation Caveats（实施注意事项）（201）
						3. Performance（表现）（201）
						4. Sample Formation Pattern（样本形成模式）（202）
					6. EXTENDING TO MORE THAN TWO LEVELS（扩展到两个以上级别）（204）
					7. SLOT ROLES AND BETTER ASSIGNMENT（槽位角色和更好的分配）（206）
						1. Hard and Soft Roles（硬角色和软角色）（206）
					8. SLOT ASSIGNMENT（时隙分配）（208）
						1. Generalized Slot Costs（广义时隙成本）（210）
						2. Implementation（执行）（210）
						3. Data Structures and Interfaces（数据结构和接口）（212）
						4. Performance（表现）（213）
					9. DYNAMIC SLOTS AND PLAYS（动态老虎机和玩法）（213）
					10. TACTICAL MOVEMENT（战术移动）（216）
						1. Tactical Motion and Anchor Point Moderation（战术动作和锚点调节）（218）
				8. MOTOR CONTROL（电机控制）（219）
					1. OUTPUT FILTERING（输出滤波）（220）
					2. CAPABILITY-SENSITIVE STEERING（能力敏感转向）（222）
						1. Coping with Combined Steering Behaviors（应对组合转向行为）（222）
					3. COMMON ACTUATION PROPERTIES（常见驱动属性）（223）
						1. Human Characters（人物角色）（223）
						2. Cars and Motorbikes（汽车和摩托车）（224）
						3. Tracked Vehicles (Tanks)（履带式车辆（坦克））（226）
				9. MOVEMENT IN THE THIRD DIMENSION（第三维度的运动）（226）
					1. ROTATION IN THREE DIMENSIONS（三维旋转）（227）
					2. CONVERTING STEERING BEHAVIORS TO THREE DIMENSIONS（将转向行为转换为三维）（228）
						1. Linear Steering Behaviors in Three Dimensions（三维线性转向行为）（228）
						2. Angular Steering Behaviors in Three Dimensions（三维角度转向行为）（228）
					3. ALIGN（对齐）（229）
					4. ALIGN TO VECTOR（与向量对齐）（230）
					5. FACE（人脸）（231）
					6. LOOK WHERE YOU’RE GOING（看看你要去哪里）（234）
					7. WANDER（漫游）（234）
					8. FAKING ROTATION AXES（伪造旋转轴）（237）
						1. The Algorithm（算法）（238）
						2. Pseudo-Code（伪代码）（239）
						3. Data Structures and Interfaces（数据结构和接口）（240）
						4. Implementation Notes（实施说明）（241）
						5. Performance（表现）（241）
			2. PATHFINDING（寻找路径）（242）
				1. THE PATHFINDING GRAPH（寻路图）（243）
					1. GRAPHS（图表）（244）
					2. WEIGHTED GRAPHS（加权图）（245）
						1. Representative Points in a Region（区域内的代表点）（246）
						2. The Non-Negative Constraint（非负约束）（246）
					3. DIRECTED WEIGHTED GRAPHS（有向加权图）（247）
					4. TERMINOLOGY（术语）（248）
					5. REPRESENTATION（表示）（249）
				2. DIJKSTRA（250）
					1. THE PROBLEM（问题）（250）
					2. THE ALGORITHM（算法）（251）
						1. Processing the Current Node（处理当前节点）（251）
						2. The Node Lists（节点列表）（253）
						3. Calculating Cost-So-Far for Open and Closed Nodes（计算开放节点和封闭节点的迄今为止成本）（253）
						4. Terminating the Algorithm（终止算法）（254）
						5. Retrieving the Path（检索路径）（255）
					3. PSEUDO-CODE（伪代码）（255）
						1. Other Functions（其他功能）（258）
					4. DATA STRUCTURES AND INTERFACES（数据结构和接口）（258）
						1. Simple List（简单列表）（258）
						2. Pathfinding List（寻路列表）（258）
						3. Graph（图形）（259）
					5. PERFORMANCE OF DIJKSTRA（Dijkstra的性能）（259）
					6. WEAKNESSES（弱点）（260）
				3. A*（262）
					1. THE PROBLEM（问题）（262）
					2. THE ALGORITHM（算法）（262）
						1. Processing the Current Node（处理当前节点）（262）
						2. The Node Lists（节点列表）（263）
						3. Calculating Cost-So-Far for Open and Closed Nodes（计算开放节点和封闭节点的迄今为止成本）（264）
						4. Terminating the Algorithm（终止算法）（264）
						5. Retrieving the Path（检索路径）（266）
					3. PSEUDO-CODE（伪代码）（266）
						1. Changes from Dijkstra（迪杰斯特拉的变化）（269）
					4. DATA STRUCTURES AND INTERFACES（数据结构和接口）（270）
						1. Pathfinding List（寻路列表）（270）
						2. Heuristic Functio（启发式函数）（273）
					5. IMPLEMENTATION NOTES（实施说明）（274）
					6. ALGORITHM PERFORMANCE（算法性能）（275）
					7. NODE ARRAY A*（节点数组A*）（275）
						1. Keeping a Node Array（保留节点数组）（276）
						2. Checking if a Node Is in Open or Closed（检查节点是否处于打开或关闭状态）（276）
						3. The Open List Implementation（开放列表实施）（277）
						4. A Variation for Large Graphs（大图的变体）（278）
					8. CHOOSING A HEURISTIC（选择启发式）（278）
						1. Underestimating Heuristics（低估启发法）（278）
						2. Overestimating Heuristics（高估启发法）（279）
						3. Euclidean Distance（欧氏距离）（279）
						4. Cluster Heuristic（聚类启发式）（281）
						5. Fill Patterns in A*（在  A*  中填充图案）（283）
						6. Quality of Heuristics（启发式的质量）（284）
						7. Dijkstra Is A*（迪杰斯特拉是  A*）（285）
				4. WORLD REPRESENTATIONS（世界代表）（285）
					1. Quantization and Localization（量化和定位）（285）
					2. Generation（一代）（286）
					3. Validity（有效性）（286）
					4. TILE GRAPHS（平铺图）（287）
						1. Division Scheme（划分方案）（287）
						2. Quantization and Localization（量化和定位）（287）
						3. Generation（一代）（288）
						4. Validity（有效性）（288）
						5. Usefulness（用处）（288）
					5. DIRICHLET DOMAINS（狄利克雷域）（290）
						1. Division Scheme（划分方案）（290）
						2. Quantization and Localization（量化和定位）（291）
						3. Validity（有效性）（291）
						4. Usefulness（用处）（292）
					6. POINTS OF VISIBILITY（可见点）（292）
						1. Division Scheme（划分方案）（292）
						2. Quantization, Localization, and Validity（量化、定位和有效性）（293）
						3. Usefulness（用处）（294）
					7. POLYGONAL MESHES（多边形网格）（294）
						1. Division Scheme（划分方案）（295）
						2. Quantization and Localization（量化和定位）（296）
						3. Validity（有效性）（297）
						4. Usefulness（用处）（297）
						5. Edges as Nodes（边作为节点）（298）
					8. NON-TRANSLATIONAL PROBLEMS（非翻译问题）（299）
					9. COST FUNCTIONS（成本函数）（300）
					10. PATH SMOOTHING（路径平滑）（301）
						1. The Algorithm（算法）（301）
						2. Pseudo-Code（伪代码）（302）
						3. Data Structures and Interfaces（数据结构和接口）（303）
						4. Performance（表现）（303）
				5. IMPROVING ON A*（改进A*）（303）
				6. HIERARCHICAL PATHFINDING（分层寻路）（304）
					1. THE HIERARCHICAL PATHFINDING GRAPH（分层寻路图）（304）
						1. Nodes（节点）（304）
						2. Connections（连接）（305）
						3. Connection Costs（连接费用）（305）
					2. PATHFINDING ON THE HIERARCHICAL GRAPH（层次图上的寻路）（308）
						1. Algorithm（算法）（308）
						2. Pseudo-Code（伪代码）（309）
						3. Data Structures and Interfaces（数据结构和接口）（309）
						4. Performance（表现）（310）
					3. HIERARCHICAL PATHFINDING ON EXCLUSIONS（排除的分层寻路）（311）
					4. STRANGE EFFECTS OF HIERARCHIES ON PATHFINDING（层次结构对寻路的奇怪影响）（311）
					5. INSTANCED GEOMETRY（实例几何）（314）
						1. Algorithm（算法）（314）
						2. Pseudo-Code（伪代码）（317）
						3. Data Structures and Interfaces（数据结构和接口）（319）
						4. Implementation Nodes（实施节点）（319）
						5. Performance（表现）（319）
						6. Weaknesses（弱点）（320）
						7. Setting Node Offsets（设置节点偏移）（320）
				7. OTHER IDEAS IN PATHFINDING（寻路的其他想法）（320）
					1. OPEN GOAL PATHFINDING（开放目标寻路）（320）
					2. DYNAMIC PATHFINDING（动态寻路）（321）
					3. OTHER KINDS OF INFORMATION REUSE（其他类型的信息重用）（322）
					4. LOW MEMORY ALGORITHMS（低内存算法）（322）
						1. IDA*—Iterative Deepening A*（IDA*-迭代深化A*）（322）
						2. SMA*—Simplified Memory-Bounded A*（SMA*-简化的内存限制  A*）（323）
					5. INTERRUPTIBLE PATHFINDING（可中断寻路）（324）
					6. POOLING PLANNERS（池化规划器）（324）
				8. CONTINUOUS TIME PATHFINDING（连续时间寻路）（325）
					1. THE PROBLEM（问题）（325）
					2. THE ALGORITHM（算法）（327）
						1. Nodes as States（节点作为状态）（327）
						2. The Size of the Graph（图表的大小）（328）
						3. How the Graph Is Created（图表是如何创建的）（329）
						4. Which Pathfinder（哪个探路者）（331）
					3. IMPLEMENTATION NOTES（实施说明）（331）
					4. PERFORMANCE（性能）（331）
					5. WEAKNESSES（弱点）（332）
				9. MOVEMENT PLANNING（运动计划）（332）
					1. ANIMATIONS（动画）（332）
					2. MOVEMENT PLANNING（运动计划）（334）
						1. The Planning Graph（规划图）（334）
						2. Planning（规划）（335）
						3. Infinite Graphs（无限图）（335）
						4. Implementation Issues（实施问题）（336）
					3. EXAMPLE（示例）（336）
					4. FOOTFALLS（脚步声）（337）
			3. DECISION MAKING（决策）（340）
				1. OVERVIEW OF DECISION MAKING（决策概述）（340）
				2. DECISION TREES（决策树）（342）
					1. THE PROBLEM（问题）（342）
					2. THE ALGORITHM（算法）（343）
						1. Decisions（决定）（344）
						2. Combinations of Decisions（决策组合）（345）
						3. Decision Complexity（决策复杂性）（346）
						4. Branching（分枝）（346）
					3. PSEUDO-CODE（伪代码）（348）
						1. Multiple Branches（多个分支机构）（349）
					4. ON THE CD（光盘上）（350）
					5. KNOWLEDGE REPRESENTATION（知识表示）（350）
					6. IMPLEMENTATION NODES（实现节点）（351）
					7. PERFORMANCE OF DECISION TREES（决策树的性能）（351）
					8. BALANCING THE TREE（平衡树）（351）
					9. BEYOND THE TREE（树之外）（353）
					10. RANDOM DECISION TREES（随机决策树）（354）
						1. Pseudo-Code（伪代码）（355）
						2. Timing Out（超时）（355）
						3. On the CD（光盘上）（256）
						4. Using Random Decision Trees（使用随机决策树）（357）
				3. STATE MACHINES（状态机）（357）
					1. A Basic State Machin（基本状态机）（357）
					2. Finite State Machines（有限状态机）（358）
					3. The Game FSM（游戏  FSM）（358）
					4. THE PROBLEM（问题）（359）
					5. THE ALGORITHM（算法）（359）
					6. PSEUDO-CODE（伪代码）（359）
					7. DATA STRUCTURES AND INTERFACES（数据结构和接口）（360）
						1. Transition Implementation（过渡实施）（361）
					8. ON THE CD（光盘上）（363）
					9. PERFORMANCE（性能）（364）
					10. IMPLEMENTATION NOTES（实施说明）（364）
					11. HARD-CODED FSM（硬编码FSM）（364）
						1. Pseudo-Code（伪代码）（364）
						2. Performance（表现）（366）
						3. Weaknesses（弱点）（366）
					12. HIERARCHICAL STATE MACHINES（分层状态机）（366）
						1. The Problem（问题）（370）
						2. The Algorithm（算法）（370）
						3. Pseudo-Code（伪代码）（374）
						4. Implementation Notes（实施说明）（379）
						5. Performance（表现）（379）
						6. On the CD（光盘上）（379）
					13. COMBINING DECISION TREES AND STATE MACHINES（结合决策树和状态机）（379）
						1. Pseudo-Code（伪代码）（381）
						2. Implementation（执行）（382）
				4. FUZZY LOGIC（模糊逻辑）（383）
					1. INTRODUCTION TO FUZZY LOGIC（模糊逻辑简介）（383）
						1. Fuzzy Sets（模糊集）（383）
						2. Membership of Multiple Sets（多个集合的成员资格）（384）
						3. Fuzzification（模糊化）（385）
						4. Defuzzification（去模糊化）（386）
						5. Combining Facts（结合事实）（390）
						6. Fuzzy Rules（模糊规则）（392）
					2. FUZZY LOGIC DECISION MAKING（模糊逻辑决策）（393）
						1. The Problem（问题）（393）
						2. The Algorithm（算法）（394）
						3. Pseudo-Code（伪代码）（397）
						4. Data Structures and Interfaces（数据结构和接口）（398）
						5. Implementation Notes（实施说明）（399）
						6. Performance（表现）（399）
						7. Weaknesses（弱点）（400）
						8. Combs Method（梳⼦法）（400）
					3. FUZZY STATE MACHINES（模糊状态机）（403）
						1. The Problem（问题）（403）
						2. The Algorithm（算法）（404）
						3. Pseudo-Code（伪代码）（405）
						4. Data Structures and Interfaces（数据结构和接口）（406）
						5. Implementation Notes（实施说明）（407）
						6. Performance（表现）（407）
						7. Multiple Degrees of Transition（多重过渡）（408）
						8. On the CD（光盘上）（408）
				5. MARKOV SYSTEMS（马尔可夫系统）（408）
					1. MARKOV PROCESSES（马尔可夫过程）（409）
						1. Conservative Markov Processes（保守马尔可夫过程）（410）
						2. Iterated Processes（迭代过程）（410）
						3. Markov Processes in Math and Science（数学和科学中的马尔可夫过程）（411）
					2. MARKOV STATE MACHINE（马尔可夫状态机）（412）
						1. The Algorithm（算法）（412）
						2. Pseudo-Code（伪代码）（413）
						3. Data Structures and Interfaces（数据结构和接口）（414）
						4. On the CD（光盘上）（414）
				6. GOAL-ORIENTED BEHAVIOR（以目标为导向的行为）（414）
					1. GOAL-ORIENTED BEHAVIOR（以目标为导向的行为）（416）
						1. Goals（目标）（416）
						2. Actions（行动）（417）
					2. SIMPLE SELECTION（简单选择）（417）
						1. Pseudo-Code（伪代码）（418）
						2. Data Structures and Interfaces（数据结构和接口）（419）
						3. Performance（表现）（419）
						4. Weaknesses（弱点）（419）
					3. OVERALL UTILITY（整体效用）（419）
						1. Pseudo-Code（伪代码）（421）
						2. Data Structures and Interfaces（数据结构和接口）（422）
						3. Performance（表现）（422）
					4. TIMING（时序）（422）
						1. Utility Involving Time（涉及时间的效用）（423）
						2. Pseudo-Code（伪代码）（424）
						3. Data Structures and Interfaces（数据结构和接口）（424）
						4. Performance（表现）（425）
						5. Calculating the Goal Change over Time（计算目标随时间的变化）（425）
						6. The Need for Planning（规划的必要性）（426）
					5. OVERALL UTILITY GOAP（总体效用目标）（427）
						1. The Algorithm（算法）（428）
						2. Pseudo-Code（伪代码）（429）
						3. Data Structures and Interfaces（数据结构和接口）（431）
						4. Implementation Notes（实施说明）（431）
						5. Performance（表现）（432）
						6. Weaknesses（弱点）（432）
					6. GOAP WITH IDA*（GOAP与IDA*）（433）
						1. IDA*（433）
						2. The Heuristic（启发式）（434）
						3. The Algorithm（算法）（434）
						4. Pseudo-Code（伪代码）（435）
						5. Data Structures and Interfaces（数据结构和接口）（438）
						6. Implementation Notes（实施说明）（440）
						7. Performance（440）
					7. SMELLY GOB（440）
						1. Compound Actions（复合动作）（441）
				7. RULE-BASED SYSTEMS（基于规则的系统）（442）
					1. THE PROBLEM（问题）（443）
						1. Database Matching（数据库匹配）（443）
						2. Condition–Action Rules（条件‑动作规则）（445）
						3. Database Rewriting Rules（数据库重写规则）（445）
						4. Forward and Backward Chaining（前向和后向链接）（446）
						5. Format of Data in the Database（数据库中数据的格式）（447）
					2. THE ALGORITHM（算法）（448）
					3. PSEUDO-CODE（伪代码）（449）
					4. DATA STRUCTURES AND INTERFACES（数据结构和接口）（450）
						1. The Database（数据库）（450）
						2. Rules（规则）（450）
						3. IF-Clauses（IF  ⼦句）（451）
						4. Item Matching（物品搭配）（452）
						5. Summary（概括）（455）
					5. IMPLEMENTATION NOTES（实施说明）（455）
					6. RULE ARBITRATION（规则仲裁）（457）
						1. First Applicable（第一个适用）（457）
						2. Least Recently Used（最近最少使用）（457）
						3. Random Rule（随机规则）（458）
						4. Most Specific Conditions（最具体的条件）（458）
						5. Dynamic Priority Arbitration（动态优先仲裁）（458）
					7. UNIFICATION（统一）（459）
						1. Performance（表现）（460）
					8. RETE（461）
						1. The Algorithm（算法）（462）
						2. On the CD（光盘上）（470）
						3. Performance（表现）（471）
					9. EXTENSIONS（扩展）（472）
						1. Managing Large Rule Sets（管理大型规则集）（472）
						2. Justification in Expert Systems（专家系统的论证）（474）
					10. WHERE NEXT（下一步）（475）
				8. BLACKBOARD ARCHITECTURES（黑板架构）（475）
					1. THE PROBLEM（问题）（476）
					2. THE ALGORITHM（算法）（476）
						1. Extracting an Action（提取动作）（478）
					3. PSEUDO-CODE（伪代码）（478）
					4. DATA STRUCTURES AND INTERFACES（数据结构和接口）（479）
						1. The Blackboard Language（黑板语言）（480）
					5. PERFORMANCE（性能）（481）
					6. OTHER THINGS ARE BLACKBOARD SYSTEMS（其他都是黑板系统）（482）
						1. Rule-Based Systems（基于规则的系统）（482）
						2. Finite State Machines（有限状态机）（482）
				9. SCRIPTING（脚本编写）（483）
					1. LANGUAGE FACILITIES（语言设施）（484）
						1. Speed（速度）（484）
						2. Compilation and Interpretation（编译与解释）（484）
						3. Extensibility and Integration（可扩展性和集成性）（485）
						4. Re-Entrancy（重新进入）（485）
					2. EMBEDDING（嵌入）（485）
					3. CHOOSING A LANGUAGE（选择语言）（486）
						1. Advantages（优点）（486）
						2. Disadvantages（缺点）（486）
						3. Open Source Languages（开源语言）（487）
					4. A LANGUAGE SELECTION（语言选择）（488）
						1. Lua（488）
						2. Scheme and Variations（489）
						3. Python（490）
						4. Other Options（其他选项）（491）
					5. ROLLING YOUR OWN（自己动手）（492）
						1. The Stages of Language Processing（语言处理的阶段）（493）
						2. Tools: A Quick Look at Lex and Yacc（工具：Lex  和  Yacc  快速浏览）（497）
					6. SCRIPTING LANGUAGES AND OTHER AI（脚本语言和其他人工智能）（498）
				10. ACTION EXECUTION（动作执行）（498）
					1. TYPES OF ACTION（行动类型）（499）
						1. A Single Action（单一动作）（499）
						2. Interrupting Actions（打断行动）（501）
						3. Compound Actions（复合动作）（501）
						4. Scripted Actions（脚本化动作）（502）
					2. THE ALGORITHM（算法）（503）
					3. PSEUDO-CODE（伪代码）（504）
					4. DATA STRUCTURES AND INTERFACES（数据结构和接口）（506）
					5. IMPLEMENTATION NOTES（实施说明）（508）
						1. Debugging（调试）（509）
					6. PERFORMANCE（性能）（509）
					7. PUTTING IT ALL TOGETHER（综合起来）（509）
						1. On the CD（光盘上）（510）
			4. TACTICAL AND STRATEGIC AI（战术和战略人工智能）（512）
				1. WAYPOINT TACTICS（航路点策略）（512）
					1. TACTICAL LOCATIONS（战术位置）（513）
						1. A Set of Locations（一组地点）（514）
						2. Primitive and Compound Tactics（原始策略和复合策略）（515）
						3. Waypoint Graphs and Topological Analysis（航点图和拓扑分析）（517）
						4. Continuous Tactics（连续战术）（518）
						5. Context Sensitivity（上下文敏感性）（520）
						6. Putting It Together（把它放在一起）（522）
					2. USING TACTICAL LOCATIONS（使用战术位置）（522）
						1. Simple Tactical Movement（简单的战术动作）（523）
						2. Using Tactical Information like Any Other Data（像使用任何其他数据一样使用战术信息）（524）
						3. Tactical Information in Fuzzy Logic Decision Making（模糊逻辑决策中的战术信息）（525）
						4. Generating Nearby Waypoints（生成附近的航点）（526）
						5. Tactical Pathfinding（战术寻路）（527）
					3. GENERATING THE TACTICAL PROPERTIES OF A WAYPOINT（生成航路点的战术属性）（527）
						1. Cover Points（覆盖点）（528）
						2. Visibility Points（可见度点）（530）
						3. Shadow Points（阴影点）（531）
						4. Compound Tactics（复合战术）（532）
						5. Generating Tactical Properties and Tactical Analysis（生成战术属性和战术分析）（532）
					4. AUTOMATICALLY GENERATING THE WAYPOINTS（自动生成航点）（533）
						1. Watching Human Players（观看人类玩家）（533）
						2. Condensing a Waypoint Grid（压缩航点网格）（533）
					5. THE CONDENSATION ALGORITHM（压缩算法）（534）
						1. Pseudo-Code（伪代码）（535）
						2. Data Structures and Interfaces（数据结构和接口）（537）
						3. The Trade-Off（权衡）（537）
				2. TACTICAL ANALYSES（战术分析）（538）
					1. REPRESENTING THE GAME LEVEL（代表游戏等级）（539）
					2. SIMPLE INFLUENCE MAPS（简单影响力图）（539）
						1. Simple Influence（简单的影响）（540）
						2. Calculating the Influence（计算影响力）（541）
						3. Applications（应用领域）（544）
						4. Dealing with Unknowns（处理未知数）（544）
					3. TERRAIN ANALYSIS（地形分析）（547）
						1. Terrain Difficulty（地形难度）（547）
						2. Visibility Map（能见度地图）（548）
					4. LEARNING WITH TACTICAL ANALYSES（通过战术分析进行学习）（549）
					5. A STRUCTURE FOR TACTICAL ANALYSES（战术分析结构）（551）
						1. Multi-Layer Analyses（多层分析）（553）
						2. When to Combine Things（何时组合事物）（555）
						3. Building a Tactical Analysis Server（构建战术分析服务器）（555）
					6. MAP FLOODING（地图泛洪）（556）
						1. The Algorithm（算法）（556）
						2. Pseudo-Code（伪代码）（557）
						3. Data Structures and Interfaces（数据结构和接口）（559）
						4. Performance（表现）（560）
					7. CONVOLUTION FILTERS（卷积滤波器）（560）
						1. The Algorithm（算法）（561）
						2. Boundaries（边界（562））
						3. Pseudo-Code（伪代码）（563）
						4. Data Structures and Interfaces（数据结构和接口）（565）
						5. Implementation Notes（实施说明）（565）
						6. Performance（565）
						7. Filters（过滤器）（565）
						8. Gaussian Blur（高斯模糊）（566）
						9. Separable Filters（可分离过滤器）（567）
						10. The Sharpening Filter（锐化滤镜）（570）
					8. CELLULAR AUTOMATA（元胞自动机）（572）
						1. Cellular Automata Rules（元胞自动机规则）（573）
						2. Running a Cellular Automaton（运行元胞自动机）（574）
						3. The Complexity of Cellular Automata（元胞自动机的复杂性）（575）
						4. Applications and Rules（申请及规则）（575）
				3. TACTICAL PATHFINDING（战术寻路）（577）
					1. THE COST FUNCTION（成本函数）（577）
					2. TACTIC WEIGHTS AND CONCERN BLENDING（策略权重和关注点混合）（577）
					3. MODIFYING THE PATHFINDING HEURISTIC（修改寻路启发式）（580）
					4. TACTICAL GRAPHS FOR PATHFINDING（寻路战术图）（581）
					5. USING TACTICAL WAYPOINTS（使用战术航路点）（581）
				4. COORDINATED ACTION（协调行动）（582）
					1. MULTI-TIER AI（多层人工智能）（583）
						1. Group Decisions（集体决策）（584）
						2. Group Movement（团体运动）（585）
						3. Group Pathfinding（团体寻路）（585）
						4. Including the Player（包括玩家）（586）
						5. Explicit Player Orders（明确的玩家命令）（588）
						6. Structuring Multi-Tier AI（构建多层人工智能）（589）
					2. EMERGENT COOPERATION（紧急合作）（590）
						1. Scalability（可扩展性）（591）
						2. Predictability（可预测性）（592）
					3. SCRIPTING GROUP ACTIONS（脚本组操作）（593）
						1. Pseudo-Code（伪代码）（595）
						2. Data Structures and Interfaces（数据结构和接口）（596）
						3. Implementation Notes（实施说明）（597）
						4. Performance（表现）（597）
						5. Creating Scripts（创建脚本）（597）
					4. MILITARY TACTICS（军事策略）（598）
						1. Case Study: A Fire Team Takes a House（案例研究：消防队占领一所房屋）（598）
			5. LEARNING（学习）（602）
				1. LEARNING BASICS（学习基础知识）（602）
					1. ONLINE OR OFFLINE LEARNING（在线或离线学习）（602）
					2. INTRA-BEHAVIOR LEARNING（行为内学习）（603）
					3. INTER-BEHAVIOR LEARNING（行为间学习）（604）
					4. A WARNING（警告）（604）
					5. OVER-LEARNING（过度学习）（605）
					6. THE ZOO OF LEARNING ALGORITHMS（学习算法的动物园）（605）
					7. THE BALANCE OF EFFORT（努力的平衡）（606）
				2. PARAMETER MODIFICATION（参数修改）（606）
					1. THE PARAMETER LANDSCAPE（参数概况）（606）
						1. Energy and Fitness Values（能量和健身值）（607）
					2. HILL CLIMBING（爬山）（608）
						1. Pseudo-Code（伪代码）（609）
						2. Data Structures and Interfaces（数据结构和接口）（611）
						3. Implementation Notes（实施说明）（611）
						4. Performance（表现）（611）
					3. EXTENSIONS TO BASIC HILL CLIMBING（基本爬坡的扩展）（611）
						1. Momentum（势头）（613）
						2. Adaptive Resolution（自适应分辨率）（613）
						3. Multiple Trials（多次试验）（614）
						4. Finding the Global Optimum（寻找全局最优值）（614）
					4. ANNEALING（退火）（615）
						1. Direct Method（直接法）（615）
						2. Boltzmann Probabilities（玻尔兹曼概率）（617）
						3. Optimizations（优化）（619）
				3. ACTION PREDICTION（动作预测）（619）
					1. LEFT OR RIGHT（左或右）（620）
					2. RAW PROBABILITY（原始概率）（620）
					3. STRING MATCHING（字符串匹配）（621）
					4. N-GRAMS（621）
						1. N-Grams in Computer Science（计算机科学中的  N  元语法）（622）
						2. Pseudo-Code（伪代码）（622）
						3. Data Structures and Interfaces（数据结构和接口）（624）
						4. Implementation Notes（实施说明）（624）
						5. Performance（表现）（624）
					5. WINDOW SIZE（窗口大小）（625）
						1. Memory Concerns（内存问题）（626）
						2. Sequence Length（序列长度）（626）
					6. HIERARCHICAL N-GRAMS（分层N  元语法）（627）
						1. Pseudo-Code（伪代码）（627）
						2. Data Structures and Implementation（数据结构和实现）（629）
						3. Performance（表现）（629）
						4. Confidence（信心）（629）
					7. APPLICATION IN COMBAT（战斗中的应用）（630）
				4. DECISION LEARNING（决策学习）（630）
					1. STRUCTURE OF DECISION LEARNING（决策学习的结构）（631）
						1. Weak or Strong Supervision（弱监管还是强监管）（631）
					2. WHAT SHOULD YOU LEARN?（你应该学什么？）（631）
					3. THREE TECHNIQUES（三种技术）（632）
				5. DECISION TREE LEARNING（决策树学习）（632）
					1. ID3（633）
						1. Algorithm（算法）（633）
						2. Entropy and Information Gain（熵和信息增益）（634）
						3. More than Two Actions（两个以上的动作）（635）
						4. Non-Binary Discrete Attributes（非二进制离散属性）（636）
						5. Pseudo-Code（伪代码）（637）
						6. Data Structures and Interfaces（数据结构和接口）（641）
						7. Starting the Algorithm（启动算法）（641）
						8. Performance（表现）（641）
					2. ID3 WITH CONTINUOUS ATTRIBUTES（具有连续属性的  ID3）（641）
						1. Single Splits（单分裂）（642）
						2. Pseudo-Code（伪代码）（643）
						3. Data Structures and Interfaces（数据结构和接口）（645）
						4. Performance（表现）（645）
						5. On the CD（光盘上）（645）
						6. Multiple Categories（多类别）（645）
					3. INCREMENTAL DECISION TREE LEARNING（增量决策树学习）（646）
						1. The Algorithm（算法）（647）
						2. Walk Through（走过）（649）
						3. Problems with ID4（ID4  的问题）（650）
						4. Heuristic Algorithms（启发式算法）（651）
				6. REINFORCEMENT LEARNING（强化学习）（651）
					1. THE PROBLEM（问题）（652）
					2. THE ALGORITHM（算法）（652）
						1. Q-Learning’s Representation of the World（Q‑Learning  对世界的表述）（652）
						2. Doing Learning（做学习）（654）
						3. How It Works（怎么运行的）（654）
						4. Exploration Strategy（勘探策略）（655）
						5. Convergence and Ending（收敛与结束）（655）
						6. On the CD（光盘上）（655）
					3. PSEUDO-CODE（伪代码）（656）
					4. DATA STRUCTURES AND INTERFACES（数据结构和接口）（657）
					5. IMPLEMENTATION NOTES（实施说明）（658）
					6. PERFORMANCE（性能）（658）
					7. TAILORING PARAMETERS（定制参数）（658）
						1. Alpha: The Learning Rate（Alpha：学习率）（659）
						2. Gamma: The Discount Rate（伽玛：折扣率）（659）
						3. Rho: Randomness for Exploration（Rho：探索的随机性）（659）
						4. Nu: The Length of Walk（Nu：步行的长度）（660）
						5. Choosing Rewards（选择奖励）（661）
					8. WEAKNESSES AND REALISTIC APPLICATIONS（弱点和实际应用）（662）
						1. Limits of the Algorithm（算法的局限性）（663）
						2. Applications（应用领域）（664）
						3. Case Study: Choosing Tactical Defense Locations（案例研究：选择战术防御地点）（664）
					9. OTHER IDEAS IN REINFORCEMENT LEARNING（强化学习的其他想法）（665）
						1. TD（665）
						2. Neural Networks for Storage（用于存储的神经网络）（666）
						3. Actor–Critic（667）
				7. ARTIFICIAL NEURAL NETWORKS（人工神经网络）（667）
					1. Neural Network Zoology（神经网络动物学）（668）
					2. OVERVIEW（概述）（668）
						1. Architecture（建筑学）（668）
						2. Feedforward and Recurrence（前馈和递归）（669）
						3. Neuron Algorithm（神经元算法）（669）
						4. Learning Rule（学习规则）（670）
					3. THE PROBLEM（问题）（671）
						1. What about Decision Tree Learning?（决策树学习怎么样？）（671）
					4. THE ALGORITHM（算法）（672）
						1. Initial Setup and Framework（初始设置和框架）（672）
						2. Feedforward（前馈）（673）
						3. Backpropagation（反向传播）（674）
					5. PSEUDO-CODE（伪代码）（675）
					6. DATA STRUCTURES AND INTERFACES（数据结构和接口）（677）
					7. IMPLEMENTATION CAVEATS（实施注意事项）（679）
						1. On the CD（光盘上）（680）
					8. PERFORMANCE（性能）（680）
					9. OTHER APPROACHES（其他方法）（680）
						1. Radial Basis Function（径向基函数）（680）
						2. Weakly Supervised Learning（弱监督学习）（682）
						3. Hebbian Learning（赫布学习）（683）
			6. BOARD GAMES（棋盘游戏）（686）
				1. GAME THEORY（博弈论）（687）
					1. TYPES OF GAMES（游戏类型）（687）
						1. Number of Players（玩家数量）（687）
						2. The Goal of the Game（游戏的目标）（687）
						3. Information（信息）（688）
						4. Applying Algorithms（应用算法）（688）
					2. THE GAME TREE（游戏树）（689）
						1. Branching Factor and Depth（分支因子和深度）（689）
						2. Transposition（换位）（690）
				2. MINIMAXING（极小化）（691）
					1. THE STATIC EVALUATION FUNCTION（静态评估功能）（691）
						1. Range of the Function（功能范围）（692）
						2. Combining Scoring Functions（组合评分函数）（692）
						3. Simple Move Choice（简单的移动选择）（693）
					2. MINIMAXING（极小化）（693）
					3. THE MINIMAXING ALGORITHM（极小化算法）（695）
						1. Pseudo-Code（伪代码）（695）
						2. Data Structures and Interfaces（数据结构和接口）（696）
						3. More than Two Players（两名以上玩家）（697）
						4. Performance（表现）（697）
					4. NEGAMAXING（负最大）（698）
						1. Negamax and the Static Evaluation Function（Negamax  和静态评估函数）（698）
						2. Pseudo-Code（伪代码）（699）
						3. Data Structures and Interfaces（数据结构和接口）（699）
						4. Performance（表现）（700）
						5. Implementation Notes（实施说明）（700）
					5. AB PRUNING（AB剪枝）（700）
						1. Alpha Pruning（阿尔法剪枝）（700）
						2. Beta Pruning（贝塔剪枝）（701）
						3. AB Negamax（702）
						4. Pseudo-Code（伪代码）（702）
						5. Data Structures and Interfaces（数据结构和接口）（703）
						6. Performance（表现）（703）
					6. THE AB SEARCH WINDOW（AB搜索窗口）（704）
						1. Move Order（移动顺序）（704）
						2. Aspiration Search（愿望搜索）（705）
					7. NEGASCOUT（负侦察兵）（705）
						1. Pseudo-Code（伪代码）（706）
						2. Data Structures and Interfaces（数据结构和接口）（708）
						3. Performance（表现）（708）
						4. Move Ordering and Negascout（移动排序和  Negascout）（708）
						5. Principal Variation Search（主要变异搜索）（709）
				3. TRANSPOSITION TABLES AND MEMORY（换位表和存储器）（709）
					1. HASHING GAME STATES（哈希游戏状态）（709）
						1. Zobrist Keys（710）
						2. Hash Implementation（哈希实现）（710）
						3. Incremental Zobrist Hashing（增量  Zobrist  哈希）（711）
						4. The Game Class, Revisited（重新审视游戏类）（712）
					2. WHAT TO STORE IN THE TABLE（表中存储的内容）（712）
					3. HASH TABLE IMPLEMENTATION（哈希表实现）（713）
					4. REPLACEMENT STRATEGIES（替换策略）（715）
					5. A COMPLETE TRANSPOSITION TABLE（完整的换位表）（715）
						1. Performance（表现）（716）
						2. Implementation Notes（实施说明）（716）
					6. TRANSPOSITION TABLE ISSUES（换位表问题）（716）
						1. Path Dependency（路径依赖）（716）
						2. Instability（不稳定）（716）
					7. USING OPPONENT’S THINKING TIME（利用对手的思考时间）（717）
				4. MEMORY-ENHANCED TEST ALGORITHMS（内存增强测试算法）（717）
					1. IMPLEMENTING TEST（实施测试）（717）
						1. Pseudo-Code（伪代码）（718）
						2. Transposition Table（换位表）（719）
					2. THE MTD ALGORITHM（MTD算法）（720）
						1. MTD Variations（MTD  变化）（721）
						2. Memory Size（内存大小）（721）
					3. PSEUDO-CODE（伪代码）（721）
						1. Performance（表现）（722）
				5. OPENING BOOKS AND OTHER SET PLAYS（开局和其他比赛）（722）
					1. IMPLEMENTING AN OPENING BOOK（实施开盘簿）（723）
						1. Opening Book in the Evaluation Function（在评估功能中打开书本）（723）
					2. LEARNING FOR OPENING BOOKS（开卷学习）（723）
					3. SET PLAY BOOKS（设置游戏书）（724）
						1. Ending Database（结束数据库（724））
				6. FURTHER OPTIMIZATIONS（进一步优化）（724）
					1. ITERATIVE DEEPENING（迭代深化）（725）
						1. MTD Implementation（MTD  实施）（725）
						2. History Heuristic（历史启发法）（726）
					2. VARIABLE DEPTH APPROACHES（可变深度方法）（726）
						1. Extensions（扩展）（726）
						2. Quiescence Pruning（静止修剪）（727）
				7. TURN-BASED STRATEGY GAMES（回合制策略游戏）（727）
					1. IMPOSSIBLE TREE SIZE（不可能的树大小）（728）
						1. Divide and Conquer（分而治之）（728）
						2. Heuristics（启发式）（729）
					2. REAL-TIME AI IN A TURN-BASED GAME（回合制游戏中的实时人工智能）（729）
		3. Supporting Technologies（配套技术）（730）
			1. EXECUTION MANAGEMENT（执行管理）（732）
				1. SCHEDULING（日程安排）（733）
					1. THE SCHEDULER（调度程序）（733）
						1. Frequencies（频率）（734）
						2. Phase（阶段）（735）
						3. Pseudo-Code（伪代码）（735）
						4. Implementation Notes（实施说明）（736）
						5. Performance（表现）（737）
						6. Direct Access（直接访问）（737）
						7. Pseudo-Code（伪代码）（737）
						8. Phase Quality（相位质量）（739）
						9. Automatic Phasing（自动定相）（739）
						10. Single Task Spikes（单一任务峰值）（741）
					2. INTERRUPTIBLE PROCESSES（可中断进程）（741）
						1. Threads（线程数）（741）
						2. Software Threads（软件线程）（742）
						3. Micro-Threads（微线程）（742）
						4. Hyper-Threads and Multiple Cores（超线程和多核）（742）
						5. Quality of Service（服务质量）（743）
					3. LOAD-BALANCING SCHEDULER（负载平衡调度器）（744）
						1. Pseudo-Code（伪代码）（744）
						2. Data Structures（数据结构）（745）
						3. Performance（表现）（746）
					4. HIERARCHICAL SCHEDULING（分层调度）（746）
						1. Data Structures and Interfaces（数据结构和接口）（747）
						2. Behavior Selection（行为选择）（747）
					5. PRIORITY SCHEDULING（优先级调度）（748）
						1. Pseudo-Code（伪代码）（748）
						2. Performance（表现）（750）
						3. Other Policies（其他政策）（750）
						4. Priority Problems（优先问题）（750）
				2. ANYTIME ALGORITHMS（随时算法）（751）
				3. LEVEL OF DETAIL（细节层次）（751）
					1. GRAPHICS LEVEL OF DETAIL（图形细节层次）（752）
					2. AI LOD（人工智能细节层次）（752）
						1. Importance Values（重要性值）（753）
					3. SCHEDULING LOD（调度LOD）（753）
						1. Frequency Schedulers（频率调度器）（754）
						2. Priority Schedulers（优先级调度程序）（754）
						3. Combined Scheduling（组合调度）（754）
					4. BEHAVIORAL LOD（行为LOD）（754）
						1. Entry and Exit Processing（进入和退出处理）（755）
						2. Behavior Compression（行为压缩）（755）
						3. Hysteresis（迟滞）（756）
						4. Pseudo-Code（伪代码）（757）
						5. Data Structures and Interfaces（数据结构和接口）（758）
						6. Implementation Notes（实施说明）（759）
						7. Performance（表现）（760）
					5. GROUP LOD（组LOD）（760）
						1. Probability Distributions（概率分布）（761）
					6. IN SUMMARY（总结）（763）
			2. WORLD INTERFACING（世界界面）（766）
				1. COMMUNICATION（通讯）（766）
				2. GETTING KNOWLEDGE EFFICIENTLY（高效获取知识）（767）
					1. POLLING（轮询）（767）
						1. Polling Stations（投票站）（767）
					2. EVENTS（事件）（768）
						1. Event Managers（活动经理）（768）
					3. DETERMINING WHAT APPROACH TO USE（确定使用什么方法）（769）
				3. EVENT MANAGERS（活动经理）（769）
					1. IMPLEMENTATION（实施）（772）
						1. Pseudo-Code（伪代码）（772）
						2. Data Structures and Interfaces（数据结构和接口）（773）
						3. Performance（表现）（774）
						4. Implementation Notes（实施说明）（774）
					2. EVENT CASTING（事件铸造）（775）
						1. Broadcasting（广播）（775）
						2. Narrowcasting（窄播）（776）
						3. Compromising（妥协）（777）
					3. INTER-AGENT COMMUNICATION（代理间通信）（777）
				4. POLLING STATIONS（投票站）（778）
					1. PSEUDO-CODE（伪代码）（778）
					2. PERFORMANCE（性能）（779）
					3. IMPLEMENTATION NOTES（实施说明）（779）
					4. ABSTRACT POLLING（抽象轮询）（780）
				5. SENSE MANAGEMENT（感知管理）（781）
					1. FAKING IT（伪造）（782）
					2. WHAT DO I KNOW?（我知道什么？）（782）
						1. Polling and Notification Revisited（重新审视投票和通知）（783）
					3. SENSORY MODALITIES（感觉方式）（783）
						1. Sight（视线）（783）
						2. Hearing（听力）（787）
						3. Touch（触碰）（788）
						4. Smell（闻）（788）
						5. Fantasy Modalities（幻想形态）（789）
					4. REGION SENSE MANAGER（区域感知管理器）（789）
						1. The Algorithm（算法）（789）
						2. Pseudo-Code（伪代码）（791）
						3. Data Structures and Interfaces（数据结构和接口）（793）
						4. Performance（表现）（795）
						5. Camouflage and Shadows（伪装和阴影）（795）
						6. Weaknesses（弱点）（795）
					5. FINITE ELEMENT MODEL SENSE MANAGER（有限元模型传感管理器）（797）
						1. Finite Element Models（有限元模型）（798）
						2. The Sense Graph（感知图）（798）
						3. The Algorithm（算法）（802）
						4. On the CD（光盘上）（805）
						5. Implementation Notes（实施说明）（806）
						6. Weaknesses（弱点）（806）
			3. TOOLS AND CONTENT CREATION（工具和内容创作）
				1. TOOLCHAINS LIMIT AI（工具链限制人工智能）（809）
				2. WHERE AI KNOWLEDGE COMES FROM（人工智能知识从何而来）（809）
				3. KNOWLEDGE FOR PATHFINDING AND WAYPOINT TACTICS（寻路和航路点策略知识）（809）
					1. MANUALLY CREATING REGION DATA（手动创建区域数据）（810）
						1. Tile Graphs（平铺图）（810）
						2. Dirichlet Domains（狄利克雷域）（811）
						3. Polygonal Meshes（多边形网格）（812）
						4. Bounded Regions（有界区域）（812）
					2. AUTOMATIC GRAPH CREATION（自动图形创建）（813）
					3. GEOMETRIC ANALYSIS（几何分析）（813）
						1. Calculating Costs（计算成本）（813）
						2. Calculating Connections（计算连接）（813）
						3. Calculating Nodes（计算节点）（816）
					4. DATA MINING（数据挖掘）（817）
						1. Calculating Nodes（计算节点）（817）
						2. Calculating Connections（计算连接）（817）
						3. Character Movement（角色动作）（818）
						4. Limitations（局限性）（818）
						5. Other Representations（其他代表）（819）
				4. KNOWLEDGE FOR MOVEMENT（运动知识）（819）
					1. OBSTACLES（障碍）（819）
						1. Walls（墙壁）（819）
						2. Obstacle Representation（障碍物表示）（820）
					2. HIGH-LEVEL STAGING（高级阶段）（821）
				5. KNOWLEDGE FOR DECISION MAKING（决策知识）（822）
					1. OBJECT TYPES（对象类型）（822）
					2. CONCRETE ACTIONS（具体行动）（822）
				6. THE TOOLCHAIN（工具链）（823）
					1. DATA-DRIVEN EDITORS（数据驱动的编辑器）（823）
					2. AI DESIGN TOOLS（人工智能设计工具）（824）
						1. Scripting Tools（脚本工具）（824）
						2. State Machine Designers（状态机设计者）（824）
					3. REMOTE DEBUGGING（远程调试）（825）
					4. PLUG-INS（插件）（826）
		4. Designing Game AI（设计游戏人工智能）（828）
			1. DESIGNING GAME AI（设计游戏人工智能）（830）
				1. THE DESIGN（设计）（830）
					1. EXAMPLE（示例）（831）
					2. EVALUATING THE BEHAVIORS（评估行为）（832）
						1. Example（例子）（834）
					3. SELECTING TECHNIQUES（选择技术）（835）
						1. Example（例子）（835）
					4. THE SCOPE OF ONE GAME（一场比赛的范围）（837）
				2. SHOOTERS（射手）（837）
					1. MOVEMENT AND FIRING（移动和射击）（838）
					2. DECISION MAKING（决策）（840）
					3. PERCEPTION（感知）（841）
					4. PATHFINDING AND TACTICAL AI（寻路和战术人工智能）（841）
					5. SHOOTER-LIKE GAMES（射击类游戏）（842）
						1. Platform and Adventure Games（平台和冒险游戏）（843）
						2. MMOG（大型多人在线游戏）（843）
				3. DRIVING（驾驶）（844）
					1. MOVEMENT（运动）（844）
					2. PATHFINDING AND TACTICAL AI（寻路和战术人工智能）（847）
					3. DRIVING-LIKE GAMES（驾驶类游戏）（847）
				4. REAL-TIME STRATEGY（实时策略）（848）
					1. PATHFINDING（寻路）（849）
					2. GROUP MOVEMENT（群体运动）（849）
					3. TACTICAL AND STRATEGIC AI（战术和战略人工智能）（850）
					4. DECISION MAKING（决策）（850）
				5. SPORTS（运动）（851）
					1. PHYSICS PREDICTION（物理预测）（852）
					2. PLAYBOOKS AND CONTENT CREATION（剧本和内容创建）（853）
				6. TURN-BASED STRATEGY GAMES（回合制策略游戏）（853）
					1. TIMING（时序）（854）
					2. HELPING THE PLAYER（帮助玩家）（855）
			2. AI-BASED GAME GENRES（基于人工智能的游戏类型）（856）
				1. TEACHING CHARACTERS（教学人物）（856）
					1. REPRESENTING ACTIONS（表示动作）（857）
					2. REPRESENTING THE WORLD（代表世界）（857）
					3. LEARNING MECHANISM（学习机制）（858）
						1. Neural Network Architecture（神经网络架构）（858）
						2. Observational Learning（观察学习）（859）
						3. Mind-Reading for Observational Learning（观察学习的读心术）（859）
						4. Feedback Learning（反馈学习）（860）
					4. PREDICTABLE MENTAL MODELS AND PATHOLOGICAL STATES（可预测的心理模型和病理状态）（860）
						1. Instincts（本能）（861）
						2. The Brain Death of a Character（一个角色的脑死亡）（861）
				2. FLOCKING AND HERDING GAMES（聚集和放牧游戏）（862）
					1. MAKING THE CREATURES（制作生物）（862）
					2. TUNING STEERING FOR INTERACTIVITY（调整转向以实现交互性）（862）
					3. STEERING BEHAVIOR STABILITY（转向行为稳定性）（864）
					4. ECOSYSTEM DESIGN（生态系统设计）（864）
						1. Size of the Food Chain（食物链的规模）（865）
						2. Behavior Complexity（行为复杂性）（865）
						3. Sensory Limits（感官限制）（866）
						4. Movement Range（移动范围）（866）
						5. Putting It All Together（把它们放在一起）（866）
	2. Artificial Intelligence A Modern Approach（人工智能一种现代方法）
		1. Artificial intelligence（人工智能）（20）
			1. INTRODUCTION（介绍）（20）
				1. What Is AI?（什么是人工智能？）（20）
					1. Acting humanly: The Turing test approach（人性化：图灵测试方法）（21）
					2. Thinking humanly: The cognitive modeling approach（人性化思考：认知建模方法）（21）
					3. Thinking rationally: The “laws of thought” approach（理性思考：“思维法则”方法）（22）
					4. Acting rationally: The rational agent approach（理性行动：理性代理人方法）（22）
					5. Beneficial machines（受益机器）（23）
				2. The Foundations of Artificial Intelligence（人工智能的基础）（24）
					1. Philosophy（理念）（25）
					2. Mathematics（数学）（27）
					3. Economics（经济学）（28）
					4. Neuroscience（神经科学）（30）
					5. Psychology（心理学）（31）
					6. Computer engineering（计算机工程）（33）
					7. Control theory and cybernetics（控制理论和控制论）（34）
					8. Linguistics（语言学）（35）
				3. The History of Artificial Intelligence（人工智能的历史）（36）
					1. The inception of artificial intelligence (1943–1956)（人工智能的起源（1943‑1956））（36）
					2. Early enthusiasm, great expectations (1952–1969)（早期的热情，远大的期望（1952‑1969））（37）
					3. A dose of reality (1966–1973)（现实的剂量（1966‑1973））（40）
					4. Expert systems (1969–1986)（专家系统（1969‑1986））（41）
					5. The return of neural networks (1986–present)（神经网络的回归（1986  年至今））（43）
					6. Probabilistic reasoning and machine learning (1987–present)（概率推理和机器学习（1987年至今））（43）
					7. Big data (2001–present)（大数据（2001年至今））（45）
					8. Deep learning (2011–present)（深度学习（2011年至今））（45）
				4. The State of the Art（最新技术）（46）
				5. Risks and Benefits of AI（人工智能的风险和收益）（50）
			2. INTELLIGENT AGENTS（智能代理）（55）
				1. Agents and Environments（代理和环境）（55）
				2. Good Behavior: The Concept of Rationality（良好行为：理性的概念）（58）
					1. Performance measures（绩效衡量）（58）
					2. Rationality（合理性）（59）
					3. Omniscience, learning, and autonomy（全知、学习和自主）（59）
				3. The Nature of Environments（环境的本质）（61）
					1. Specifying the task environment（指定任务环境）（61）
					2. Properties of task environments（任务环境的属性）（62）
				4. The Structure of Agents（代理的结构）（66）
					1. Agent programs（代理程序）（67）
					2. Simple reflex agents（简单反射代理）（68）
					3. Model-based reflex agents（基于模型的反射代理）（70）
					4. Goal-based agents（基于目标的代理）（72）
					5. Utility-based agents（基于实用程序的代理）（93）
					6. Learning agents（学习代理）（75）
					7. How the components of agent programs work（代理程序的组件如何工作）（77）
		2. Problem-solving（解决问题）（82）
			1. SOLVING PROBLEMS BY SEARCHING（通过搜索解决问题）（82）
				1. Problem-Solving Agents（问题解决代理）（82）
					1. Search problems and solutions（搜索问题及解决方案）（84）
					2. Formulating problems（制定问题）（85）
				2. Example Problems（示例问题）（85）
					1. Standardized problems（标准化问题）（85）
					2. Real-world problems（现实问题）（88）
				3. Search Algorithms（搜索算法）（90）
					1. Best-first search（最佳优先搜索）（92）
					2. Search data structures（搜索数据结构）（92）
					3. Redundant paths（冗余路径）（93）
					4. Measuring problem-solving performance（衡量解决问题的能力）（94）
				4. Uninformed Search Strategies（不知情的搜索策略）（95）
					1. Breadth-first search（广度优先搜索）（95）
					2. Dijkstra’s algorithm or uniform-cost search（Dijkstra算法或统一成本搜索）（96）
					3. Depth-first search and the problem of memory（深度优先搜索和内存问题）（97）
					4. Depth-limited and iterative deepening search（深度有限和迭代深化搜索）（99）
					5. Bidirectional search（双向搜索）（101）
					6. Comparing uninformed search algorithms（比较无信息搜索算法）（103）
				5. Informed (Heuristic) Search Strategies（知情（启发式）搜索策略）（103）
					1. Greedy best-first search（贪婪最佳优先搜索）（104）
					2. A∗ search（A*搜索）（104）
					3. Search contours（搜索轮廓）（108）
					4. Satisficing search: Inadmissible heuristics and weighted A∗（令人满意的搜索：不允许的启发法和加权A*）（109）
					5. Memory-bounded search（内存限制搜索）（111）
					6. Bidirectional heuristic search（双向启发式搜索）（115）
				6. Heuristic Functions（启发式函数）（116）
					1. The effect of heuristic accuracy on performance（启发式准确性对性能的影响）（117）
					2. Generating heuristics from relaxed problems（从宽松的问题中生成启发式）（118）
					3. Generating heuristics from subproblems: Pattern databases（从子问题生成启发式：模式数据库）（119）
					4. Generating heuristics with landmarks（用地标生成启发式）（121）
					5. Learning to search better（学会更好地搜索）（122）
					6. Learning heuristics from experience（从经验中学习启发式方法）（123）
			2. SEARCH IN COMPLEX ENVIRONMENTS（在复杂环境中搜索）（129）
				1. Local Search and Optimization Problems（本地搜索和优化问题）（129）
					1. Hill-climbing search（爬山搜索）（130）
					2. Simulated annealing（模拟退火）（133）
					3. Local beam search（局部波束搜索）（134）
					4. Evolutionary algorithms（进化算法）（134）
				2. Local Search in Continuous Spaces（连续空间中的局部搜索）（138）
				3. Search with Nondeterministic Actions（使用非确定性动作进行搜索）（141）
					1. The erratic vacuum world（不稳定的真空世界）（141）
					2. AND–OR search trees（AND–OR搜索树）（142）
					3. Try, try again（尝试，再尝试）（144）
				4. Search in Partially Observable Environments（部分可观测环境中的搜索）（145）
					1. Searching with no observation（不观察的搜索）（145）
					2. Searching in partially observable environments（在部分可观察环境中搜索）（149）
					3. Solving partially observable problems（解决部分可观察问题）（141）
					4. An agent for partially observable environments（部分可观察环境的代理）（151）
				5. Online Search Agents and Unknown Environments（在线搜索代理和未知环境）（153）
					1. Online search problems（在线搜索问题）（154）
					2. Online search agents（在线搜索代理）（156）
					3. Online local search（在线本地搜索）（157）
					4. Learning in online search（在线搜索学习）（159）
			3. CONSTRAINT SATISFACTION PROBLEMS（约束满足问题）（165）
				1. Defining Constraint Satisfaction Problems（定义约束满足问题）（165）
					1. Example problem: Map coloring（示例问题：地图着色）（166）
					2. Example problem: Job-shop scheduling（示例问题：作业车间调度）（167）
					3. Variations on the CSP formalism（CSP  形式主义的变体）（168）
				2. Constraint Propagation: Inference in CSPs（约束传播：CSP  中的推理）（170）
					1. Node consistency（节点一致性）（171）
					2. Arc consistency（弧一致性）（171）
					3. Path consistency（路径一致性）（172）
					4. K-consistency（K‑一致性）（173）
					5. Global constraints（全局约束）（173）
					6. Sudoku（数独）（174）
				3. Backtracking Search for CSPs（CSP  的回溯搜索）（176）
					1. Variable and value ordering（变量和值排序）（178）
					2. Interleaving search and inference（交错搜索和推理）（179）
					3. Intelligent backtracking: Looking backward（智能回溯：向后看）（180）
					4. Constraint learning（约束学习）（181）
				4. Local Search for CSPs（本地搜索  CSP）（182）
				5. The Structure of Problems（问题的结构）（184）
					1. Cutset conditioning（割集调节）（185）
					2. Tree decomposition（树分解）（186）
					3. Value symmetry（价值对称性）（188）
			4. ADVERSARIAL SEARCH AND GAMES（对抗性搜索和游戏）（193）
				1. Game Theory（博弈论）（193）
					1. Two-player zero-sum games（两人零和博弈）（194）
				2. Optimal Decisions in Games（博弈中的最优决策）（195）
					1. The minimax search algorithm（极小极大搜索算法）（196）
					2. Optimal decisions in multiplayer games（多人游戏中的最优决策）（198）
					3. Alpha–Beta Pruning（Alpha‑Beta剪枝）（199）
					4. Move ordering（移动顺序）（200）
				3. Heuristic Alpha–Beta Tree Search（启发式α‑β树搜索）（203）
					1. Evaluation functions（评价函数）（203）
					2. Cutting off search（切断搜索）（205）
					3. Forward pruning（前向剪枝）（206）
					4. Search versus lookup（搜索与查找）（207）
				4. Monte Carlo Tree Search（蒙特卡罗树搜索）（208）
				5. Stochastic Games（随机博弈）（211）
					1. Evaluation functions for games of chance（机会游戏的评估函数）（213）
				6. Partially Observable Games（部分可观察博弈）（215）
					1. Kriegspiel: Partially observable chess（Kriegspiel：部分可观察的国际象棋）（215）
					2. Card games（纸牌游戏）（218）
				7. Limitations of Game Search Algorithms（游戏搜索算法的局限性）（220）
		3. Knowledge, reasoning, and planning（知识、推理和计划）（227）
			1. LOGICAL AGENTS（逻辑代理）（227）
				1. Knowledge-Based Agents（基于知识的代理）（228）
				2. The Wumpus World（Wumpus  世界）（229）
				3. Logic（逻辑）（233）
				4. Propositional Logic: A Very Simple Logic（命题逻辑：一个非常简单的逻辑）（236）
					1. Syntax（语法）（236）
					2. Semantics（语义）（237）
					3. A simple knowledge base（简单的知识库）（239）
					4. A simple inference procedure（一个简单的推理过程）（239）
				5. Propositional Theorem Proving（命题定理证明）（241）
					1. Inference and proofs（推论与证明）（242）
					2. Proof by resolution（分辨率证明）（244）
						1. Conjunctive normal form（连词范式）（245）
						2. A resolution algorithm（解析算法）（246）
						3. Completeness of resolution（决议的完整性）（247）
					3. Horn clauses and definite clauses（喇叭从句和定语从句）（248）
					4. Forward and backward chaining（前向和后向链接）（249）
				6. Effective Propositional Model Checking（有效命题模型检验）（251）
					1. A complete backtracking algorithm（完整的回溯算法）（252）
					2. Local search algorithms（本地搜索算法）（254）
					3. The landscape of random SAT problems（随机  SAT  问题的概况）（255）
				7. Agents Based on Propositional Logic（基于命题逻辑的代理）（256）
					1. The current state of the world（世界现状）（256）
					2. A hybrid agent（混合代理）（260）
					3. Logical state estimation（逻辑状态估计）（260）
					4. Making plans by propositional inference（通过命题推理制定计划）（263）
			2. FIRST-ORDER LOGIC（一阶逻辑）（270）
				1. Representation Revisited（重新审视表示法）（270）
					1. The language of thought（思想语言）（271）
					2. Combining the best of formal and natural languages（结合形式语言和自然语言的精华）（273）
				2. Syntax and Semantics of First-Order Logic（一阶逻辑的语法和语义）（275）
					1. Models for first-order logic（一阶逻辑模型）（275）
					2. Symbols and interpretations（符号和解释）（276）
					3. Terms（术语）（278）
					4. Atomic sentences（原子句）（279）
					5. Complex sentences（复杂句子）（279）
					6. Quantifiers（量词）（279）
						1. Universal quantification (∀)（通用量化(∀)）（279）
						2. Existential quantification (∃)（存在量化(∃)）（281）
						3. Nested quantifiers（嵌套量词）（282）
						4. Connections between ∀ and ∃（∀和∃之间的连接）（282）
					7. Equality（平等）（283）
					8. Database semantics（数据库语义）（283）
				3. Using First-Order Logic（使用一阶逻辑）（284）
					1. Assertions and queries in first-order logic（一阶逻辑中的断言和查询）（284）
					2. The kinship domain（亲属关系域）（285）
					3. Numbers, sets, and lists（数字、集合和列表）（287）
					4. The wumpus world（wumpus  世界）（289）
				4. Knowledge Engineering in First-Order Logic（一阶逻辑中的知识工程）（290）
					1. The knowledge engineering process（知识工程过程）（290）
					2. The electronic circuits domain（电子电路领域）（292）
						1. Identify the questions（确定问题）（292）
						2. Assemble the relevant knowledge（整理相关知识）（292）
						3. Decide on a vocabulary（决定词汇）（293）
						4. Encode general knowledge of the domain（编码该领域的一般知识）（294）
						5. Encode the specific problem instance（对特定问题实例进行编码）（295）
						6. Pose queries to the inference procedure（对推理过程提出查询）（295）
						7. Debug the knowledge base（调试知识库）（296）
			3. INFERENCE IN FIRST-ORDER LOGIC（一阶逻辑推理）（299）
				1. Propositional vs. First-Order Inference（命题与一阶推理）（299）
					1. Reduction to propositional inference（还原为命题推理）（300）
				2. Unification and First-Order Inference（统一和一阶推理）（301）
					1. Unification（统一）（302）
					2. Storage and retrieval（存储和检索）（303）
				3. Forward Chaining（前向链接）（305）
					1. First-order definite clauses（一阶定语从句）（305）
					2. A simple forward-chaining algorithm（一个简单的前向链接算法）（306）
					3. Efficient forward chaining（高效的前向链接）（308）
						1. Matching rules against known facts（根据已知事实匹配规则）（308）
						2. Incremental forward chaining（增量前向链接）（310）
						3. Irrelevant facts（不相关的事实）（311）
				4. Backward Chaining（反向链接）（312）
					1. A backward-chaining algorithm（后向链接算法）（312）
					2. Logic programming（逻辑编程）（313）
					3. Redundant inference and infinite loops（冗余推理和无限循环）（314）
					4. Database semantics of Prolog（Prolog的数据库语义）（316）
					5. Constraint logic programming（约束逻辑编程）（317）
				5. Resolution（分辨率）（317）
					1. Conjunctive normal form for first-order logic（一阶逻辑的合取范式）（317）
					2. The resolution inference rule（分辨率推断规则）（319）
					3. Example proofs（示例证明）（320）
					4. Completeness of resolution（决议的完整性）（322）
					5. Equality（平等）（325）
					6. Resolution strategies（解决策略）（326）
						1. Practical uses of resolution theorem provers（解析定理证明器的实际应用）（328）
			4. KNOWLEDGE REPRESENTATION（知识表示）（333）
				1. Ontological Engineering（本体工程）（333）
				2. Categories and Objects（类别和对象）（336）
					1. Physical composition（物理成分）（337）
					2. Measurements（测量）（338）
					3. Objects: Things and stuff（对象：事物和物质）（340）
				3. Events（事件）（341）
					1. Time（时间）（343）
					2. Fluents and objects（流体和对象）（344）
				4. Mental Objects and Modal Logic（心理对象和模态逻辑）（345）
					1. Other modal logics（其他模态逻辑）（347）
				5. Reasoning Systems for Categories（类别推理系统）（348）
					1. Semantic networks（语义网络）（348）
					2. Description logics（描述逻辑）（350）
				6. Reasoning with Default Information（用默认信息进行推理）（352）
					1. Circumscription and default logic（限制和默认逻辑）（352）
					2. Truth maintenance systems（真相维护系统）（354）
			5. AUTOMATED PLANNING（自动化规划）（363）
				1. Definition of Classical Planning（经典规划的定义）（363）
					1. Example domain: Air cargo transport（示例领域：航空货物运输）（364）
					2. Example domain: The spare tire problem（示例域：备胎问题）（365）
					3. Example domain: The blocks world（示例域：积木世界）（365）
				2. Algorithms for Classical Planning（经典规划算法）（367）
					1. Forward state-space search for planning（用于规划的正向状态空间搜索）（367）
					2. Backward search for planning（向后搜索规划）（369）
					3. Planning as Boolean satisfiability（作为布尔可满足性的规划）（370）
					4. Other classical planning approaches（其他经典规划方法）（371）
				3. Heuristics for Planning（规划启发法）（372）
					1. Domain-independent pruning（与域无关的剪枝）（373）
					2. State abstraction in planning（规划中的状态抽象）（374）
				4. Hierarchical Planning（分层规划）（375）
					1. High-level actions（高层行动）（376）
					2. Searching for primitive solutions（搜索原解）（377）
					3. Searching for abstract solutions（搜索抽象解决方案）（379）
				5. Planning and Acting in Nondeterministic Domains（非确定性领域中的规划和行动）（384）
					1. Sensorless planning（无传感器规划）（386）
					2. Contingent planning（应急计划）（389）
					3. Online planning（在线规划）（390）
				6. Time, Schedules, and Resources（时间、日程和资源）（393）
					1. Representing temporal and resource constraints（表示时间和资源约束）（394）
					2. Solving scheduling problems（解决调度问题）（395）
				7. Analysis of Planning Approaches（规划方法分析）（397）
		4. Uncertain knowledge and reasoning（不确定的知识和推理）（404）
			1. QUANTIFYING UNCERTAINTY（量化不确定性）（404）
				1. Acting under Uncertainty（不确定性下的行动）（404）
					1. Summarizing uncertainty（总结不确定性）（405）
					2. Uncertainty and rational decisions（不确定性与理性决策）（406）
				2. Basic Probability Notation（基本概率符号）（407）
					1. What probabilities are about（概率是什么意思）（407）
					2. The language of propositions in probability assertions（概率断言中的命题语言）（409）
					3. Probability axioms and their reasonableness（概率公理及其合理性）（412）
				3. Inference Using Full Joint Distributions（使用完全联合分布进行推理）（414）
				4. Independence（独立性）（416）
				5. Bayes’ Rule and Its Use（贝叶斯规则及其应用）（418）
					1. Applying Bayes’ rule: The simple case（应用贝叶斯规则：简单情况）（418）
					2. Using Bayes’ rule: Combining evidence（使用贝叶斯规则：结合证据）（419）
				6. Naive Bayes Models（朴素贝叶斯模型）（421）
					1. Text classification with naive Bayes（使用朴素贝叶斯进行文本分类）（422）
				7. The Wumpus World Revisited（重温  Wumpus  世界）（423）
			2. PROBABILISTIC REASONING（概率推理）（431）
				1. Representing Knowledge in an Uncertain Domain（表示不确定领域的知识）（431）
				2. The Semantics of Bayesian Networks（贝叶斯网络的语义）（434）
					1. A method for constructing Bayesian networks（一种构建贝叶斯网络的方法）（434）
					2. Compactness and node ordering（紧凑性和节点排序）（436）
					3. Conditional independence relations in Bayesian networks（贝叶斯网络中的条件独立关系）（437）
					4. Efficient Representation of Conditional Distributions（条件分布的有效表示）（439）
					5. Bayesian nets with continuous variables（具有连续变量的贝叶斯网络）（440）
					6. Case study: Car insurance（案例研究：汽车保险）（443）
				3. Exact Inference in Bayesian Networks（贝叶斯网络中的精确推理）（446）
					1. Inference by enumeration（枚举推理）（446）
					2. The variable elimination algorithm（变量消除算法）（449）
						1. Operations on factors（对因子的操作）（450）
						2. Variable ordering and variable relevance（变量排序和变量相关性）（451）
					3. The complexity of exact inference（精确推理的复杂性）（452）
					4. Clustering algorithms（聚类算法）（453）
				4. Approximate Inference for Bayesian Networks（贝叶斯网络的近似推理）（454）
					1. Direct sampling methods（直接取样方法）（455）
						1. Rejection sampling in Bayesian networks（贝叶斯网络中的拒绝采样）（456）
						2. Importance sampling（重要性抽样）（458）
					2. Inference by Markov chain simulation（通过马尔可夫链模拟进行推理）（460）
						1. Gibbs sampling in Bayesian networks（贝叶斯网络中的吉布斯采样）（461）
						2. Analysis of Markov chains（马尔可夫链分析）（462）
						3. Why Gibbs sampling works（为什么吉布斯抽样有效）（464）
						4. Complexity of Gibbs sampling（吉布斯采样的复杂性）（465）
						5. Metropolis–Hastings sampling（大都会‑黑斯廷斯抽样）（466）
					3. Compiling approximate inference（编译近似推理）（467）
				5. Causal Networks（因果网络）（468）
					1. Representing actions: The do-operator（表示动作：  do  运算符）（470）
					2. The back-door criterion（后门标准）（472）
			3. PROBABILISTIC REASONING OVER TIME（随时间推移的概率推理）（480）
				1. Time and Uncertainty（时间和不确定性）（480）
					1. States and observations（状态和观察）（481）
					2. Transition and sensor models（转换和传感器模型）（482）
				2. Inference in Temporal Models（时间模型中的推理）（484）
					1. Filtering and prediction（过滤和预测）（485）
					2. Smoothing（平滑）（487）
					3. Finding the most likely sequence（寻找最可能的序列）（490）
				3. Hidden Markov Models（隐马尔可夫模型）（492）
					1. Simplified matrix algorithms（简化的矩阵算法）（493）
					2. Hidden Markov model example: Localization（隐马尔可夫模型示例：定位）（495）
				4. Kalman Filters（卡尔曼滤波器）（498）
					1. Updating Gaussian distributions（更新高斯分布）（499）
					2. A simple one-dimensional example（一个简单的一维例子）（499）
					3. The general case（一般情况）（501）
					4. Applicability of Kalman filtering（卡尔曼滤波的适用性）（502）
				5. Dynamic Bayesian Networks（动态贝叶斯网络）（504）
					1. Constructing DBNs（构建DBN）（505）
					2. Exact inference in DBNs（DBN中的精确推理）（508）
					3. Approximate inference in DBNs（DBN中的近似推理）（510）
			4. MAKING SIMPLE DECISIONS（做出简单的决定）（519）
				1. Combining Beliefs and Desires under Uncertainty（不确定性下信念与欲望的结合）（519）
				2. The Basis of Utility Theory（效用理论基础）（520）
					1. Constraints on rational preferences（理性偏好的约束）（521）
					2. Rational preferences lead to utility（理性偏好导致效用）（522）
				3. Utility Functions（实用函数）（523）
					1. Utility assessment and utility scales（效用评估和效用量表）（524）
					2. The utility of money（货币的效用）（525）
					3. Expected utility and post-decision disappointment（预期效用和决策后失望）（527）
					4. Human judgment and irrationality（人类判断和非理性）（529）
				4. Multiattribute Utility Functions（多属性效用函数）（531）
					1. Dominance（统治地位）（531）
					2. Preference structure and multiattribute utility（偏好结构和多属性效用）（534）
						1. Preferences without uncertainty（没有不确定性的偏好）（534）
						2. Preferences with uncertainty（具有不确定性的偏好）（535）
				5. Decision Networks（决策网络）（535）
					1. Representing a decision problem with a decision network（用决策网络表示决策问题）（536）
					2. Evaluating decision networks（评估决策网络）（537）
				6. The Value of Information（信息的价值）（538）
					1. A simple example（一个简单的例子）（538）
					2. A general formula for perfect information（完美信息的通用公式）（539）
					3. Properties of the value of information（信息价值的属性）（540）
					4. Implementation of an information-gathering agent（信息收集代理的实现）（541）
					5. Nonmyopic information gathering（非近视信息收集）（542）
					6. Sensitivity analysis and robust decisions（敏感性分析和稳健决策）（543）
				7. Unknown Preferences（未知的偏好）（544）
					1. Uncertainty about one’s own preferences（对自己偏好的不确定性）（544）
					2. Deference to humans（尊重人类）（545）
			5. MAKING COMPLEX DECISIONS（做出复杂的决定）（553）
				1. Sequential Decision Problems（顺序决策问题）（553）
					1. Utilities over time（随时间变化的效用）（555）
					2. Optimal policies and the utilities of states（最优政策和国家效用）（558）
					3. Reward scales（奖励等级）（560）
					4. Representing MDPs（代表  MDP）（561）
				2. Algorithms for MDPs（MDP算法）（563）
					1. Value Iteration（值迭代）（563）
						1. Convergence of value iteration（价值迭代的收敛性）（565）
					2. Policy iteration（策略迭代）（567）
					3. Linear programming（线性规划）（569）
					4. Online algorithms for MDPs（MDP  的在线算法）（569）
				3. Bandit Problems（强盗问题）（572）
					1. Calculating the Gittins index（计算Gittins指数）（574）
					2. The Bernoulli bandit（伯努利老虎机）（575）
					3. Approximately optimal bandit policies（近似最优老虎机策略）（576）
					4. Non-indexable variants（不可转位的变型）（577）
				4. Partially Observable MDPs（部分可观测的MDP）（579）
					1. Definition of POMDPs（POMDP  的定义）（579）
				5. Algorithms for Solving POMDPs（求解POMDP的算法）（581）
					1. Value iteration for POMDPs（POMDP  的值迭代）（581）
					2. Online algorithms for POMDPs（POMDP  的在线算法）（584）
			6. MULTIAGENT DECISION MAKING（多主体决策）（590）
				1. Properties of Multiagent Environments（多主体环境的属性）（590）
					1. One decision maker（一名决策者）（590）
					2. Multiple decision makers（多个决策者）（591）
					3. Multiagent planning（多智能体规划）（592）
					4. Planning with multiple agents: Cooperation and coordination（多主体规划：合作与协调）（595）
				2. Non-Cooperative Game Theory（非合作博弈论）（596）
					1. Games with a single move: Normal form games（单步博弈：正常形式博弈）（596）
					2. Social welfare（社会福利）（600）
						1. Computing equilibria（计算平衡）（601）
					3. Repeated games（重复博弈）（605）
					4. Sequential games: The extensive form（序列博弈：扩展形式）（608）
						1. Chance and simultaneous moves（机会和同时移动）（610）
						2. Capturing imperfect information（捕捉不完美的信息）（610）
					5. Uncertain payoffs and assistance games（不确定的收益和援助博弈）（614）
				3. Cooperative Game Theory（合作博弈论）（617）
					1. Coalition structures and outcomes（联盟结构和结果）（617）
					2. Strategy in cooperative games（合作博弈中的策略）（618）
					3. Computation in cooperative games（合作博弈中的计算）（621）
						1. Marginal contribution nets（边际贡献净值）（621）
						2. Coalition structures for maximum social welfare（实现社会福利最大化的联盟结构）（622）
					4. Making Collective Decisions（做出集体决策）（623）
						1. Allocating tasks with the contract net（通过合约网分配任务）（623）
						2. Allocating scarce resources with auctions（通过拍卖分配稀缺资源）（625）
							1. Common goods（普通商品）（628）
						3. Voting（投票）（629）
							1. Strategic manipulation（战略操纵）（632）
						4. Bargaining（讨价还价）（632）
							1. Bargaining with the alternating offers protocol（使用交替报价协议进行讨价还价）（632）
							2. Impatient agents（不耐烦的代理人）（633）
							3. Negotiation in task-oriented domains（面向任务领域的谈判）（634）
							4. The monotonic concession protocol（单调让步协议）（635）
							5. The Zeuthen strategy（泽森战略）（635）
			7. PROBABILISTIC PROGRAMMING（概率编程）（642）
				1. Relational Probability Models（关系概率模型）（643）
					1. Syntax and semantics（语法和语义）（644）
					2. Example: Rating player skill levels（示例：对玩家技能水平进行评级）（647）
					3. Inference in relational probability models（关系概率模型中的推理）（648）
				2. Open-Universe Probability Models（开放宇宙概率模型）（649）
					1. Syntax and semantics（语法和语义）（650）
					2. Inference in open-universe probability models（开放宇宙概率模型中的推理）（652）
					3. Examples（示例）（653）
						1. Citation matching（引文匹配）（653）
						2. Nuclear treaty monitoring（核条约监测）（654）
				3. Keeping Track of a Complex World（跟踪复杂的世界）（656）
					1. Example: Multitarget tracking（示例：多目标跟踪）（657）
					2. Example: Traffic monitoring（示例：流量监控）（660）
				4. Programs as Probability Models（作为概率模型的程序）（661）
					1. Example: Reading text（示例：读取文本）（661）
					2. Syntax and semantics（语法和语义）（662）
					3. Inference results（推理结果）（664）
					4. Improving the generative program to incorporate a Markov model（改进生成程序以纳入马尔可夫模型）（664）
					5. Inference in generative programs（生成程序中的推理）（664）
		5. Machine Learning（机器学习）（670） 
			1. LEARNING FROM EXAMPLES（从例子中学习）（670）
				1. Forms of Learning（学习形式）
				2. Supervised Learning（监督学习）（672）
					1. Example problem: Restaurant waiting（示例问题：餐厅等待）（675）
				3. Learning Decision Trees（学习决策树）（676）
					1. Expressiveness of decision trees（决策树的表达能力）（676）
					2. Learning decision trees from examples（从例子中学习决策树）（677）
					3. Choosing attribute tests（选择属性测试）（680）
					4. Generalization and overfitting（泛化和过拟合）（682）
					5. Broadening the applicability of decision trees（扩大决策树的适用范围）（683）
				4. Model Selection and Optimization（模型选择与优化）（684）
					1. Model selection（型号选择）（686）
					2. From error rates to loss（从错误率到损失）（688）
					3. Regularization（正则化）（690）
					4. Hyperparameter tuning（超参数调整）（690）
				5. The Theory of Learning（学习理论）（691）
					1. PAC learning example: Learning decision lists（PAC学习示例：学习决策列表）（693）
				6. Linear Regression and Classification（线性回归和分类）（695）
					1. Univariate linear regression（单变量线性回归）（695）
					2. Gradient descent（梯度下降）（696）
					3. Multivariable linear regression（多元线性回归）（698）
					4. Linear classifiers with a hard threshold（具有硬阈值的线性分类器）（701）
					5. Linear classification with logistic regression（使用逻辑回归进行线性分类）（703）
				7. Nonparametric Models（非参数模型）（705）
					1. Nearest-neighbor models（最近邻模型）（706）
					2. Finding nearest neighbors with k-d trees（kd树寻找最近邻居）（707）
					3. Locality-sensitive hashing（局部敏感散列）（708）
					4. Nonparametric regression（非参数回归）（710）
					5. Support vector machines（支持向量机）（711）
					6. The kernel trick（内核技巧）（714）
				8. Ensemble Learning（集成学习）（715）
					1. Bagging（装袋）（716）
					2. Random forests（随机森林）（716）
					3. Stacking（堆叠）（718）
					4. Boosting（提升）（718）
					5. Gradient boosting（梯度提升）（720）
					6. Online learning（在线学习）（721）
				9. Developing Machine Learning Systems（开发机器学习系统）（723）
					1. Problem formulation（问题表述）（723）
					2. Data collection, assessment, and management（数据收集、评估和管理）（724）
						1. Feature engineering（特征工程）（726）
						2. Exploratory data analysis and visualization（探索性数据分析和可视化）（727）
					3. Model selection and training（模型选择与训练）（728）
					4. Trust, interpretability, and explainability（信任、可解释性和可说明性）（729）
					5. Operation, monitoring, and maintenance（操作、监控和维护）（731）
			2. KNOWLEDGE IN LEARNING（学习中的知识）（740）
				1. A Logical Formulation of Learning（学习的逻辑表述）（740）
					1. Examples and hypotheses（例子和假设）（740）
					2. Current-best-hypothesis search（当前最佳假设搜索）（742）
					3. Least-commitment search（最少承诺搜索）（745）
				2. Knowledge in Learning（学习中的知识）（748）
					1. Some simple examples（一些简单的例子）（749）
					2. Some general schemes（一些通用方案）（750）
				3. Explanation-Based Learning（基于解释的学习）（751）
					1. Extracting general rules from examples（从示例中提取一般规则）（752）
					2. Improving efficiency（提高效率）（753）
				4. Learning Using Relevance Information（使用相关信息进行学习）（755）
					1. Determining the hypothesis space（确定假设空间）（756）
					2. Learning and using relevance information（学习和使用相关信息）（756）
				5. Inductive Logic Programming（归纳逻辑编程）（759）
					1. An example（一个例子）（759）
					2. Top-down inductive learning methods（自上而下的归纳学习方法）（762）
					3. Inductive learning with inverse deduction（逆向演绎的归纳学习）（764）
					4. Making discoveries with inductive logic programming（用归纳逻辑编程进行发现）（766）
			3. LEARNING PROBABILISTIC MODELS（学习概率模型）（773）
				1. Statistical Learning（统计学习）（773）
				2. Learning with Complete Data（利用完整数据学习）（776）
					1. Maximum-likelihood parameter learning: Discrete models（最大似然参数学习：离散模型）（777）
					2. Naive Bayes models（朴素贝叶斯模型）（779）
					3. Generative and discriminative models（生成模型和判别模型）（779）
					4. Maximum-likelihood parameter learning: Continuous models（最大似然参数学习：连续模型）（780）
					5. Bayesian parameter learning（贝叶斯参数学习）（782）
					6. Bayesian linear regression（贝叶斯线性回归）（784）
					7. Learning Bayes net structures（学习贝叶斯网络结构）（786）
					8. Density estimation with nonparametric models（非参数模型的密度估计）（788）
				3. Learning with Hidden Variables: The EM Algorithm（隐变量学习：EM算法）（789）
					1. Unsupervised clustering: Learning mixtures of Gaussians（无监督聚类：学习高斯混合）（790）
					2. Learning Bayes net parameter values for hidden variables（学习隐藏变量的贝叶斯网络参数值）（793）
					3. Learning hidden Markov models（学习隐马尔可夫模型）（796）
					4. The general form of the EM algorithm（EM算法的一般形式）（796）
					5. Learning Bayes net structures with hidden variables（学习带有隐藏变量的贝叶斯网络结构）（797）
			4. DEEP LEARNING（深度学习）（802）
				1. Simple Feedforward Networks（简单的前馈网络）（803）
					1. Networks as complex functions（作为复杂函数的网络）（803）
					2. Gradients and learning（梯度和学习）（806）
				2. Computation Graphs for Deep Learning（深度学习的计算图）（808）
					1. Input encoding（输入编码）（808）
					2. Output layers and loss functions（输出层和损失函数）（809）
					3. Hidden layers（隐藏层）（811）
				3. Convolutional Networks（卷积网络）（812）
					1. Pooling and downsampling（池化和下采样）（814）
					2. Tensor operations in CNNs（CNN  中的张量运算）（815）
					3. Residual networks（残差网络）（816）
				4. Learning Algorithms（学习算法）（817）
					1. Computing gradients in computation graphs（计算计算图中的梯度）（818）
					2. Batch normalization（批量归一化）（820）
				5. Generalization（概括）（820）
					1. Choosing a network architecture（选择网络架构）（820）
					2. Neural architecture search（神经架构搜索）（822）
					3. Weight decay（权重衰减）（823）
					4. Dropout（Dropout）（824）
				6. Recurrent Neural Networks（循环神经网络）（824）
					1. Training a basic RNN（训练基本  RNN）（825）
					2. Long short-term memory RNNs（长短期记忆RNN）（827）
				7. Unsupervised Learning and Transfer Learning（无监督学习和迁移学习）（827）
					1. Unsupervised learning（无监督学习）（828）
						1. Probabilistic PCA: A simple generative model（概率  PCA：一个简单的生成模型）（828）
						2. Autoencoders（自动编码器）（830）
						3. Deep autoregressive models（深度自回归模型）（831）
						4. Generative adversarial networks（生成对抗网络）（832）
						5. Unsupervised translation（无监督翻译）（832）
					2. Transfer learning and multitask learning（迁移学习和多任务学习）（833）
				8. Applications（应用）（834）
					1. Vision（愿景）（834）
					2. Natural language processing（自然语言处理）（835）
					3. Reinforcement learning（强化学习）（835）
			5. REINFORCEMENT LEARNING（强化学习）（841）
				1. Learning from Rewards（从奖励中学习）（841）
				2. Passive Reinforcement Learning（被动强化学习）（843）
					1. Direct utility estimation（直接效用估计）（844）
					2. Adaptive dynamic programming（自适应动态规划）（845）
					3. Temporal-difference learning（时间差异学习）（845）
				3. Active Reinforcement Learning（主动强化学习）（849）
					1. Exploration（探索）（849）
					2. Safe exploration（安全探索）（851）
					3. Temporal-difference Q-learning（时间差分Q学习）（853）
				4. Generalization in Reinforcement Learning（强化学习的泛化）（855）
					1. Approximating direct utility estimation（近似直接效用估计）（856）
					2. Approximating temporal-difference learning（近似时间差分学习）（857）
					3. Deep reinforcement learning（深度强化学习）（858）
					4. Reward shaping（奖励塑造）（859）
					5. Hierarchical reinforcement learning（分层强化学习）（859）
				5. Policy Search（策略搜索）（862）
				6. Apprenticeship and Inverse Reinforcement Learning（学徒期和逆强化学习）（864）
				7. Applications of Reinforcement Learning（强化学习的应用）（867）
					1. Applications in game playing（游戏中的应用）（867）
					2. Application to robot control（在机器人控制中的应用）（868）
		6. Communicating, perceiving, and acting（沟通、感知和行动）（875）
			1. NATURAL LANGUAGE PROCESSING（自然语言处理）（875）
				1. Language Models（语言模型）（875）
					1. The bag-of-words model（词袋模型）（876）
					2. N-gram word models（N‑gram单词模型）（878）
					3. Other n-gram models（其他n‑gram  模型）（878）
					4. Smoothing n-gram models（平滑n‑gram模型）（879）
					5. Word representations（词表示）（880）
					6. Part-of-speech (POS) tagging（词性（POS）标记）（881）
					7. Comparing language models（比较语言模型）（884）
				2. Grammar（语法）（885）
					1. The lexicon of E0（E0的词典）（887）
				3. Parsing（解析）（887）
					1. Dependency parsing（依存解析）（891）
					2. Learning a parser from examples（从例子中学习解析器）（891）
				4. Augmented Grammars（增强语法）（892）
					1. Semantic interpretation（语义解释）（895）
					2. Learning semantic grammars（学习语义语法）（897）
				5. Complications of Real Natural Language（真实自然语言的复杂性）（897）
				6. Natural Language Tasks（自然语言任务）（901）
			2. DEEP LEARNING FOR NATURAL LANGUAGE PROCESSING（自然语言处理的深度学习）（908）
				1. Word Embeddings（词嵌入）（908）
				2. Recurrent Neural Networks for NLP（NLP  的循环神经网络）（912）
					1. Language models with recurrent neural networks（具有循环神经网络的语言模型）（912）
					2. Classification with recurrent neural networks（使用循环神经网络进行分类）（914）
					3. LSTMs for NLP tasks（用于  NLP  任务的  LSTM）（915）
				3. Sequence-to-Sequence Models（序列到序列模型）（916）
					1. Attention（注意）（917）
					2. Decoding（解码）（919）
				4. The Transformer Architecture（变压器架构）（920）
					1. Self-attention（自注意力）（920）
					2. From self-attention to transformer（从  self‑attention  到  Transformer）（921）
				5. Pretraining and Transfer Learning（预训练和迁移学习）（923）
					1. Pretrained word embeddings（预训练词嵌入）（923）
					2. Pretrained contextual representations（预训练的上下文表示）（925）
					3. Masked language models（屏蔽语言模型）（925）
				6. State of the art（最新技术水平）（927）
			3. ROBOTICS（机器人技术）（933）
				1. Robots（机器人）（933）
				2. Robot Hardware（机器人硬件）（934）
					1. Types of robots from the hardware perspective（从硬件角度看机器人的类型）（934）
					2. Sensing the world（感知世界）（935）
					3. Producing motion（产生运动）（937）
				3. What kind of problem is robotics solving?（机器人技术正在解决什么样的问题？）（938）
				4. Robotic Perception（机器人感知）（939）
					1. Localization and mapping（定位和绘图）（940）
					2. Other types of perception（其他类型的感知）（943）
					3. Supervised and unsupervised learning in robot perception（机器人感知中的监督和无监督学习）（945）
				5. Planning and Control（规划与控制）（946）
					1. Configuration space（配置空间）（947）
					2. Motion planning（运动规划）（950）
						1. Visibility graphs（可见性图表）（951）
						2. Voronoi diagrams（维诺图）（951）
						3. Cell decomposition（细胞分解）（953）
						4. Randomized motion planning（随机运动规划）（954）
						5. Rapidly-exploring random trees（快速探索随机树）（955）
						6. Trajectory optimization for kinematic planning（运动规划的轨迹优化）（956）
					3. Trajectory tracking control（轨迹跟踪控制）（958）
						1. Plans versus policies（计划与政策）（962）
					4. Optimal control（最优控制）（962）
				6. Planning Uncertain Movements（规划不确定的运动）（964）
				7. Reinforcement Learning in Robotics（机器人技术中的强化学习）（966）
					1. Exploiting models（利用模型）（967）
					2. Exploiting other information（利用其他信息）（968）
				8. Humans and Robots（人类和机器人）（968）
					1. Coordination（协调）（969）
						1. Humans as approximately rational agents（人类作为近似理性的主体）（969）
						2. Predicting human action（预测人类行为）（970）
						3. Human predictions about the robot（人类对机器人的预测）（972）
						4. Humans as black box agents（人类作为黑匣子特工）（973）
					2. Learning to do what humans want（学习做人类想做的事）（973）
						1. Preference learning: Learning cost functions（偏好学习：学习成本函数）（973）
						2. Learning policies directly via imitation（直接通过模仿学习政策）（974）
				9. Alternative Robotic Frameworks（替代机器人框架）（976）
					1. Reactive controllers（反应控制器）（976）
					2. Subsumption architectures（包含架构）（977）
				10. Application Domains（应用领域）（979）
			4. COMPUTER VISION（计算机视觉）（989）
				1. Introduction（简介）（989）
				2. Image Formation（图像形成）（990）
					1. Images without lenses: The pinhole camera（没有镜头的图像：针孔相机）（990）
					2. Lens systems（透镜系统）（992）
					3. Scaled orthographic projection（缩放正投影）（993）
					4. Light and shading（光照和阴影）（994）
					5. Color（颜色）（996）
				3. Simple Image Features（简单图像特征）（996）
					1. Edges（边）（997）
					2. Texture（纹理）（1000）
					3. Optical flow（光流）（1001）
					4. Segmentation of natural images（自然图像的分割）（1002）
				4. Classifying Images（图像分类）（1003）
					1. Image classification with convolutional neural networks（使用卷积神经网络进行图像分类）（1004）
					2. Why convolutional neural networks classify images well（为什么卷积神经网络能够很好地分类图像）（1005）
				5. Detecting Objects（检测物体）（1007）
				6. The 3D World（3D世界）（1009）
					1. 3D cues from multiple views（来自多个视图的  3D  线索）（1009）
					2. Binocular stereopsis（双眼立体视觉）（1010）
					3. 3D cues from a moving camera（来自移动摄像机的  3D  提示）（1012）
					4. 3D cues from one view（单一视图的  3D  提示）（1013）
				7. Using Computer Vision（使用计算机视觉）（1014）
					1. Understanding what people are doing（了解人们在做什么）（1014）
					2. Linking pictures and words（连接图片和文字）（1017）
					3. Reconstruction from many views（从多个视图重建）（1019）
					4. Geometry from a single view（单一视图中的几何图形）（1019）
					5. Making pictures（制作图片）（1021）
					6. Controlling movement with vision（用视觉控制运动）（1025）
		7. Conclusions（结论）（1033）
			1. PHILOSOPHY, ETHICS, AND SAFETY OF AI（人工智能的哲学、伦理和安全）（1033）
				1. The Limits of AI（人工智能的局限性）（1033）
					1. The argument from informality（来自非正规性的论证）（1033）
					2. The argument from disability（来自残疾的论证）（1034）
					3. The mathematical objection（数学上的反对意见）（1035）
					4. Measuring AI（测量人工智能）（1036）
				2. Can Machines Really Think?（机器真的能思考吗？）（1036）
					1. The Chinese room（中文房间）（1037）
					2. Consciousness and qualia（意识和感受性）（1037）
				3. The Ethics of AI（人工智能的伦理）（1038）
					1. Lethal autonomous weapons（致命性自主武器）（1039）
					2. Surveillance, security, and privacy（监视、安全和隐私）（1042）
					3. Fairness and bias（公平与偏见）（1044）
					4. Trust and transparency（信任和透明度）（1048）
					5. The future of work（工作的未来）（1050）
					6. Robot rights（机器人权利）(1052)
					7. AI Safety（人工智能安全）（1053）
			2. THE FUTURE OF AI（人工智能的未来）（1064）
				1. AI Components（人工智能组件）（1064）
					1. Sensors and actuators（传感器和执行器）（1064）
					2. Representing the state of the world（代表世界现状）（1065）
					3. Selecting actions（选择动作）（1066）
					4. Deciding what we want（决定我们想要什么）（1066）
					5. Learning（学习）（1067）
					6. Resources（资源）（1069）
				2. AI Architectures（人工智能架构）（1070）
					1. General AI（通用人工智能）（1072）
					2. AI engineering（人工智能工程）（1073）
					3. The future（未来）（1074）
9. Multiplayer Game Programming（多人游戏编程）
	1. Multiplayer Game Programming Architecting Networked Games（多人游戏编程构建网络游戏）
		1. Overview of Networked Games（网络游戏概述）（21）
			1. A Brief History of Multiplayer Games（多人游戏简史）（21）
				1. Local Multiplayer Games（本地多人游戏）（21）
				2. Early Networked Multiplayer Games（早期的网络多人游戏）（22）
				3. Multi-User Dungeons（多用户地下城）（23）
				4. Local Area Network Games（局域网游戏）（23）
				5. Online Games（线上游戏）（24）
				6. Massively Multiplayer Online Games（大型多人在线游戏）（25）
				7. Mobile Networked Games（手机网络游戏）（26）
			2. Starsiege: Tribes（《星际围城：部落》）（27）
				1. Platform Packet Module（平台包模块）（29）
				2. Connection Manager（连接管理器）（30）
				3. Stream Manager（流管理器）（30）
				4. Event Manager（事件管理器）（31）
				5. Ghost Manager（幽灵管理器）（32）
				6. Move Manager（移动管理器）（33）
				7. Other Systems（其他系统）（33）
			3. Age of Empires（帝国时代）（34）
				1. Turn Timers（转动定时器）（35）
				2. Synchronization（同步）（37）
		2. The Internet（互联网）（41）
			1. Origins: Packet Switching（起源：数据包交换）（41）
			2. The TCP/IP Layer Cake（TCP/IP  层蛋糕）（43）
			3. The Physical Layer（物理层）（45）
			4. The Link Layer（链路层）（45）
				1. Ethernet/802.3（48）
			5. The Network Layer（网络层）（51）
				1. IPv4（52）
					1. IP Address and Packet Structure（IP  地址和数据包结构）（53）
					2. Direct Routing and Address Resolution Protocol（直接路由和地址解析协议）（55）
					3. Subnets and Indirect Routing（子网和间接路由）（59）
					4. Fragmentation（分段）（67）
				2. IPv6（72）
			6. The Transport Layer（传输层）（74）
				1. UDP（76）
				2. TCP（76）
					1. Reliability（可靠性）（78）
					2. Three-Way Handshake（三向握手）（80）
					3. Data Transmission（数据传输）（82）
					4. Disconnecting（断开连接）（89）
			7. The Application Layer（应用层）（89）
				1. DHCP（动态主机配置协议）（90）
				2. DNS（域名系统）（90）
			8. NAT（网络地址转换）（91）
				1. NAT Traversal（NAT穿越）（96）
		3. Berkeley Sockets（Berkeley  套接字）（105）
			1. Creating Sockets（创建套接字）（105）
			2. API Operating System Differences（API  操作系统差异）（108）
			3. Socket Address（套接字地址）（111）
				1. Type Safety（类型安全由）（115）
				2. Initializing sockaddr from a String（从字符串初始化  sockaddr）（116）
				3. Binding a Socket（绑定套接字）（120）
			4. UDP Sockets（UDP  套接字）（122）
				1. Type-Safe UDP Sockets（类型安全的  UDP  套接字）（124）
			5. TCP Sockets（TCP  套接字）（127）
				1. Sending and Receiving via Connected Sockets（通过连接的套接字发送和接收）（129）
				2. Type-Safe TCP Sockets（类型安全的  TCP  套接字）（130）
			6. Blocking and Non-Blocking I/O（阻塞和非阻塞  I/O）（133）
				1. Multithreading（多线程）（133）
				2. Non-Blocking I/O（非阻塞  I/O默）（135）
				3. Select（选择）（137）
			7. Additional Socket Options（其他套接字选项）（142）
		4. Object Serialization（对象序列化）（147）
			1. The Need for Serialization（序列化的必要性）（147）
			2. Streams（流）（151）
				1. Memory Streams（内存流）（152）
				2. Endian Compatibility（Endian  兼容性）（157）
				3. Bit Streams（比特流）（162）
			3. Referenced Data（参考数据）（168）
				1. Inlining or Embedding（内联或嵌入）（169）
				2. Linking（链接）（171）
			4. Compression（压缩）（173）
				1. Sparse Array Compression（稀疏数组压缩）（174）
				2. Entropy Encoding（熵编码）（175）
				3. Fixed Point（固定点）（178）
				4. Geometry Compression（几何压缩）（180）
			5. Maintainability（可维护性）（182）
				1. Abstracting Serialization Direction（抽象序列化方向）（182）
				2. Data-Driven Serialization（数据驱动的序列化）（184）
		5. Object Replication（对象复制）（190）
			1. The State of the World（世界现状）（190）
			2. Replicating an Object（复制对象）（190）
				1. Object Creation Registry（对象创建注册表）（195）
				2. Multiple Objects per Packet（每个数据包多个对象）（200）
			3. Naïve World State Replication（简单的世界状态复制）（201）
			4. Changes in World State（世界状态的变化）（206）
				1. Partial Object State Replication（部分对象状态复制）（211）
			5. RPCs as Serialized Objects（作为序列化对象的  RPC）（214）
			6. Custom Solutions（定制解决方案）（218）
		6. Network Topologies and Sample Games（网络拓扑和示例游戏）（221）
			1. Network Topologies（网络拓扑）（221）
				1. Client-Server（客户端服务器）（221）
				2. Peer-to-Peer（点对点）（225）
			2. Implementing Client-Server（实现客户端‑服务器）（227）
				1. Separating Server and Client Code（分离服务器和客户端代码）（228）
				2. Network Manager and Welcoming New Clients（网络管理器和欢迎新客户端）（230）
				3. Input Sharing and Client Proxies（输入共享和客户端代理）（235）
			3. Implementing Peer-to-Peer（实现点对点）（242）
				1. Welcoming New Peers and Game Start（欢迎新玩家和游戏开始）（243）
				2. Command Sharing and Lockstep Turns（命令共享和锁步转向）（246）
				3. Maintaining Synchronization（保持同步）（253）
					1. Synchronizing Pseudo-Random Number Generators（同步伪随机数生成器）（253）
					2. Verifying Game Synchronization（验证游戏同步）（257）
		7. Latency, Jitter, and Reliability（延迟、抖动和可靠性）（262）
			1. Latency（延迟）（262）
				1. Non-Network Latency（非网络延迟）（263）
				2. Network Latency（网络延迟）（266）
			2. Jitter（抖动）（269）
			3. Packet Loss（数据包丢失）（270）
			4. Reliability: TCP or UDP?（可靠性：TCP  还是  UDP？）（272）
			5. Packet Delivery Notification（数据包传送通知）（276）
				1. Tagging Outgoing Packets（标记传出数据包）（277）
				2. Receiving Packets and Sending Acknowledgments（接收数据包和发送确认）（278）
				3. Receiving Acknowledgments and Delivering Status（接收确认和传送状态）（284）
			6. Object Replication Reliability（对象复制可靠性）（290）
				1. Optimizing from In-Flight Packets（从飞行中的数据包进行优化）（297）
			7. Simulating Real-World Conditions（模拟现实世界条件）（299）
		8. Improved Latency Handling（改进的延迟处理）（305）
			1. The Dumb Terminal Client（愚蠢的终端客户端）（305）
			2. Client Side Interpolation（客户端插值）（308）
			3. Client Side Prediction（客户端预测）（310）
				1. Dead Reckoning（航位推算）（313）
				2. Client Move Prediction and Replay（客户端移动预测和重播）（316）
				3. Hiding Latency through Tricks and Optimism（通过技巧和乐观隐藏延迟）（322）
			4. Server Side Rewind（服务器端倒回）（323）
		9. Scalability（可扩展性）（328）
			1. Object Scope and Relevancy（对象范围和相关性）（328）
				1. Static Zones（静态区域）（331）
				2. Using the View Frustum（使用视锥体）（332）
				3. Other Visibility Techniques（其他可见性技术）（335）
				4. Relevancy When Not Visible（不可见时的相关性）（337）
			2. Server Partitioning（服务器分区）（337）
			3. Instancing（实例化）（340）
			4. Prioritization and Frequency（优先级和频率）（341）
		10. Security（安全）（344）
			1. Packet Sniffing（数据包嗅探）（344）
				1. Man-in-the-Middle Attack（中间人攻击）（345）
				2. Packet Sniffing on a Host Machine（主机上的数据包嗅探）（349）
			2. Input Validation（输入验证）（350）
			3. Software Cheat Detection（软件作弊检测）（352）
				1. Valve Anti-Cheat（354）
				2. Warden（355）
			4. Securing the Server（确保服务器安全）（355）
				1. Distributed Denial-of-Service Attack（分布式拒绝服务攻击）（356）
				2. Bad Data（不良数据）（356）
				3. Timing Attacks（计时攻击）（357）
				4. Intrusions（入侵）（358）
		11. Real-World Engines（现实世界的引擎）（362）
			1. Unreal Engine 4（虚幻引擎）（362）
				1. Sockets and Basic Networking（套接字和基本网络）（363）
				2. Game Objects and Topology（游戏对象和拓扑）（364）
				3. Actor Replication（Actor  复制）（365）
				4. Remote Procedure Calls（远程过程调用）（367）
			2. Unity（368）
				1. Transport Layer API（传输层  API）（369）
				2. Game Objects and Topology（游戏对象和拓扑）（370）
				3. Spawning Objects and Replication（生成对象和复制）（371）
				4. Remote Procedure Calls（远程过程调用）（372）
				5. Matchmaking（372）
		12. Gamer Services（玩家服务）（375）
			1. Choosing a Gamer Service（选择玩家服务）（375）
			2. Basic Setup（基本设置）（376）
				1. Initialization, Running, and Shutdown（初始化、运行和关闭Steamworks）（378）
				2. User IDs and Names（用户  ID  和名称）（380）
			3. Lobbies and Matchmaking（大厅和配对）（381）
			4. Networking（网络）（386）
			5. Player Statistics（玩家统计数据）（389）
			6. Player Achievements（玩家成就）（395）
			7. Leaderboards（排行榜）（397）
			8. Other Services（其他服务）（399）
		13. Cloud Hosting Dedicated Servers（云托管专用服务器）（402）
			1. To Host or Not To Host（主持或不主持）（402）
			2. Tools of the Trade（贸易工具）（404）
				1. REST（405）
				2. JSON（406）
				3. Node.JS（JSON）（406）
			3. Overview and Terminology（概述和术语）（407）
				1. Server Game Instance（服务器游戏实例）（408）
				2. Game Server Process（游戏服务器进程）（408）
				3. Game Server Machine（游戏服务器）（410）
				4. Hardware（硬件）（410）
			4. Local Server Process Manager（本地服务器进程管理器）（411）
				1. Process Monitoring（流程监控）（416）
			5. Virtual Machine Manager（虚拟机管理器）（419）
				1. Virtual Machine Monitoring（虚拟机监控）（426）
		14. Appendix A. A Modern C++ Primer（附录  A.  现代  C++  入门）（433）
			1. C++11（433）
				1. auto（433）
				2. nullptr（434）
			2. References（引用）（435）
				1. Const References（常量引用）（435）
				2. Const Member Functions（常量成员函数）（436）
			3. Templates（模板）（437）
				1. Template Specialization（模板专业化）（438）
				2. Static Assertions and Type Traits（静态断言和类型特征）（438）
			4. Smart Pointers（智能指针）（440）
				1. Shared Pointers（共享指针）（442）
				2. Unique Pointer（唯一指针）（444）
				3. Weak Pointer（弱指针）（444）
				4. Caveats（注意事项）（445）
			5. STL Containers（STL容器）（445）
				1. array（数组）（445）
				2. vector（向量）（446）
				3. list（列表）（447）
				4. forward_list（447）
				5. map（447）
				6. set（集合）（447）
				7. unordered_map（448）
			6. Iterators（迭代器）（448）
				1. Range-Based For Loop（基于范围的  For  循环）（449）
				2. Other Uses of Iterators（迭代器的其他用途）（450）
10. Unity
	1. Unity 2017 Game AI Programming（Unity 2017 游戏AI编程）
		1. The Basics of AI in Games（游戏中人工智能的基础知识）（16）
			1. Creating the illusion of life（创造生活的幻象）（17）
			2. Neural Networks（神经网络）（18）
			3. Leveling up your game with AI（利用人工智能提升你的游戏水平）（20）
			4. Using AI in Unity（在  Unity  中使用  AI）（21）
			5. Defining the agent（定义代理）（21）
			6. Finite State Machines（有限状态机）（21）
			7. Seeing the world through our agent's eyes（通过我们代理的眼睛看世界）（23）
			8. Path following and steering（路径跟随和转向）（24）
				1. Dijkstra's algorithm（迪杰斯特拉算法）（24）
				2. Using A* Pathfinding（使用  A*  寻路）（25）
					1. IDA* Pathfinding（IDA*  探路IDA*  星号代表迭代）（27）
				3. Using Navigation Mesh（使用导航网格）（27）
			9. Flocking and crowd dynamics（聚集和人群动态）（30）
			10. Behavior trees（行为树）（30）
			11. Thinking with fuzzy logic（用模糊逻辑思考）（32）
		2. Finite State Machines and You（有限状态机和你）（34）
			1. Finding uses for FSMs（寻找  FSM  的用途）（35）
			2. Creating state machine behaviors（创建状态机行为）（36）
				1. Creating the AnimationController asset（创建  AnimationController  资源）（37）
				2. Layers and parameters（图层和参数）（39）
				3. The animation controller inspector（动画控制器检查器）（41）
				4. Bringing behaviors into the picture（将行为纳入画面）（41）
				5. Creating our very first state（创建我们的第一个状态）（42）
				6. Transitioning between states（状态之间的转换）（43）
			3. Setting up our player tank（设置我们的玩家坦克）（43）
			4. Creating the enemy tank（创建敌方坦克）（43）
				1. Choosing transitions（选择过渡）（44）
				2. Making the cogs turn（让齿轮转动）（45）
					1. Setting conditions（设置条件我们需要为敌方坦克提供）（48）
					2. Driving parameters via code（通过代码驱动参数在继续之前，我们需要从本章前面导入的资源）（50）
					3. Making our enemy tank move（让我们的敌方坦克移动您可能已经注意到，除了我们）（54）
					4. Testing（测试）（56）
		3. Implementing Sensors（实施传感器）（58）
			1. Basic sensory systems（基本感觉系统）（59）
				1. Cone of sight（视锥体）（59）
				2. Hearing, feeling, and smelling using spheres（使用球体进行听觉、感觉和嗅觉）（60）
				3. Expanding AI through omniscience（通过全知扩展人工智能）（61）
				4. Getting creative with sensing（通过感知发挥创意）（62）
			2. Setting up the scene（设置场景）（62）
			3. Setting up the player tank and aspect（设置玩家坦克和方面）（64）
				1. Implementing the player tank（实施玩家坦克）（65）
				2. Implementing the Aspect class（实现  Aspect  类）（67）
			4. Creating an AI character（创建  AI  角色）（68）
			5. Using the Sense class（使用  Sense  类）（69）
			6. Giving a little perspective（提供一点观点）（70）
			7. Touching is believing（感动就是相信）（72）
			8. Testing the results（测试结果）（75）
		4. Finding Your Way（找到你的路）（77）
			1. Following a path（遵循一条路径）（77）
				1. The path script（路径脚本）（79）
				2. Using the path follower（使用路径跟随器）（81）
				3. Avoiding obstacles（避开障碍物）（84）
				4. Adding a custom layer（添加自定义图层）（86）
				5. Obstacle avoidance（避障）（88）
			2. A* Pathfinding（A*  寻路）（93）
				1. Revisiting the A* algorithm（重温  A*  算法）（94）
				2. Implementation（执行）（95）
					1. The Node class（节点类）（95）
					2. Establishing the priority queue（建立优先级队列我）（97）
					3. Setting up our grid manager（设置网格管理器）（98）
					4. Diving into our A* implementation（深入了解我们的  A*  实施）（101）
					5. Implementing a TestCode class（实现  TestCode  类现在我们已经通过AStar类）（107）
					6. Testing it in the sample scene（在示例场景中进行测试）（109）
					7. Testing all the components（测试所有组件）（111）
				3. A* vs IDA*（112）
			3. Navigation mesh（导航网格）（112）
				1. Inspecting our map（检查我们的地图）（113）
				2. Navigation Static（导航静态）（114）
				3. Baking the navigation mesh（烘焙导航网格）（114）
				4. Using the NavMesh agent（使用  NavMesh  代理）（120）
				5. Setting a destination（设定目的地）（121）
				6. Making sense of Off Mesh Links（理解离网链接）（124）
		5. Flocks and Crowds（成群结队）（128）
			1. Learning the origins of flocks（了解羊群的起源）（128）
			2. Understanding the concepts behind flocks and crowds（了解羊群和人群背后的概念）（129）
			3. Using the Reynolds algorithm（使用雷诺算法）（131）
				1. Implementing the FlockController（实现  FlockController）（132）
				2. The flock target（羊群目标）（136）
				3. The scene layout（场景布置）（138）
			4. Using crowds（利用人群）（142）
				1. Implementing a simple crowd simulation（实现简单的人群模拟）（143）
				2. Using the CrowdAgent component（使用  CrowdAgent  组件）（145）
				3. Adding some fun obstacles（添加一些有趣的障碍）（147）
		6. Behavior Trees（行为树）（151）
			1. Learning the basics of behavior trees（学习行为树的基础知识）（152）
				1. Understanding different node types（了解不同的节点类型）（152）
					1. Defining composite nodes（定义复合节点）（153）
					2. Understanding decorator nodes（了解装饰器节点）（154）
					3. Describing the leaf node（描述叶节点）（155）
			2. Evaluating the existing solutions（评估现有解决方案）（155）
			3. Implementing a basic behavior tree framework（实现基本的行为树框架）（156）
				1. Implementing a base Node class（实现  Node  基类）（156）
				2. Extending nodes to selectors（将节点扩展到选择器）（157）
				3. Moving on to sequences（继续序列）（158）
				4. Implementing a decorator as an inverter（将装饰器实现为逆变器）（160）
				5. Creating a generic action node（创建通用操作节点）（161）
			4. Testing our framework（测试我们的框架）（162）
				1. Planning ahead（提前计划）（163）
				2. Examining our scene setup（检查我们的场景设置）（164）
				3. Exploring the MathTree code（探索  MathTree  代码）（165）
				4. Executing the test（执行测试）（169）
			5. HomeRock card game example（HomeRock  卡牌游戏示例）（172）
				1. The scene setup（场景设置）（172）
				2. The enemy state machine（敌方国家机器）（180）
				3. Testing the game（测试游戏）（184）
		7. Using Fuzzy Logic to Make Your AI Seem Alive（使用模糊逻辑来制作你的人工智能看起来还活着）（186）
			1. Defining fuzzy logic（定义模糊逻辑）（186）
				1. Picking fuzzy systems over binary systems（选择模糊系统而不是二元系统）（188）
			2. Using fuzzy logic（使用模糊逻辑）（188）
				1. Implementing a simple fuzzy logic system（实现一个简单的模糊逻辑系统）（189）
				2. Expanding the sets（扩展集合）（198）
				3. Defuzzifying the data（数据去模糊化）（198）
			3. Using the resulting crisp data（使用生成的清晰数据）（199）
				1. Using a simpler approach（使用更简单的方法）（201）
			4. The morality meter example（道德量表示例）（202）
				1. The question and answer classes（问答类）
				2. Managing the conversation（管理对话）（203）
					1. Loading up the questions（加载问题）（205）
					2. Handling user input（处理用户输入）（205）
					3. Calculating the results（计算结果）（206）
				3. Scene setup（场景设置）（208）
				4. Testing the example（测试示例）（211）
			5. Finding other uses for fuzzy logic（寻找模糊逻辑的其他用途）（211）
				1. Merging with other concepts（与其他概念合并）（211）
				2. Creating a truly unique experience（创造真正独特的体验）（212）
		8. How It All Comes Together（这一切是如何结合在一起的）（214）
			1. Setting up the rules（制定规则）（215）
			2. Creating the towers（创建塔）（215）
				1. Making the towers shoot（让塔射击）（223）
			3. Setting up the tank（设置坦克）
				1. Bonus tank abilities（坦克能力奖励）（231）
			4. Setting up the environment（设置环境）（232）
			5. Testing the example（测试示例）（233）
	2. Unity in Action Multiplatform game development in C#（Unity 实践使用 C# 进行多平台游戏开发）
		1. First steps（第一步）（31）
			1. Getting to know Unity（了解 Unity）（33）
				1. Why is Unity so great?（为什么Unity如此伟大？）（34）
					1. Unity’s strengths and advantages（Unity的优势）（34）
					2. Downsides to be aware of（需要注意的缺点）（36）
					3. Example games built with Unity（使用 Unity 构建的示例游戏）（37）
				2. How to use Unity（如何使用Unity）（40）
					1. Scene view, Game view, and the Toolbar（场景视图、游戏视图和工具栏）（42）
					2. The mouse and keyboard（鼠标和键盘）（44）
					3. The Hierarchy view and the Inspector panel（层次结构视图和检查器面板）（45）
					4. The Project and Console tabs（项目和控制台选项卡）（46）
				3. Getting up and running with Unity programming（启动并运行 Unity 编程）（46）
					1. Running code in Unity: Script components（在 Unity 中运行代码：脚本组件）（47）
					2. Using Visual Studio, the included IDE（使用 Visual Studio（附带的 IDE））（48）
					3. Printing to the console: Hello World!（打印到控制台：Hello World！）（49）
			2. Building a demo that puts you in 3D space（构建一个让您置身于 3D 空间的演示）（53）
				1. Before you start . . .（在你开始之前 。 。 。）（54）
					1. Planning the project（规划项目）（54）
					2. Understanding 3D coordinate space（了解 3D 坐标空间）（55）
				2. Begin the project: Place objects in the scene（开始项目：将对象放置在场景中）（57）
					1. The scenery: Floor, outer walls, and inner walls（风景：地板、外墙、内墙）（58）
					2. Lights and cameras（灯光和相机）（60）
					3. The player’s collider and viewpoint（玩家的碰撞器和视点）（62）
				3. Make things move: A script that applies transforms（让事物动起来：应用变换的脚本）（63）
					1. Visualizing how movement is programmed（可视化运动的编程方式）（63）
					2. Writing code to implement the diagram（编写代码来实现该图）（64）
					3. Understanding local vs. global coordinate space（了解局部坐标空间与全局坐标空间）（65）
				4. Script component for looking around: MouseLook（用于四处查看的脚本组件：MouseLook）（67）
					1. Horizontal rotation that tracks mouse movement（跟踪鼠标移动的水平旋转）（68）
					2. Vertical rotation with limits（垂直旋转有限制）（69）
					3. Horizontal and vertical rotation at the same time（水平和垂直同时旋转）（71）
				5. Keyboard input component: First-person controls（键盘输入组件：第一人称控件）（74）
					1. Responding to keypresses（响应按键）（74）
					2. Setting a rate of movement independent of the computer’s speed（设置独立于计算机速度的移动速率）（75）
					3. Moving the CharacterController for collision detection（移动CharacterController以进行碰撞检测）（76）
					4. Adjusting components for walking instead of flying（调整组件以步行而不是飞行）（77）
			3. Adding enemies and projectiles to the 3D game（将敌人和射弹添加到 3D 游戏中）（80）
				1. Shooting via raycasts（通过光线投射进行拍摄）（81）
					1. What is raycasting?（什么是光线投射？）（82）
					2. Using the ScreenPointToRay command for shooting（使用ScreenPointToRay命令进行拍摄）（82）
					3. Adding visual indicators for aiming and hits（添加瞄准和命中的视觉指示器）（84）
				2. Scripting reactive targets（编写反应性目标脚本）（87）
					1. Determining what was hit（确定被击中的对象）（87）
					2. Alerting the target that it was hit（提醒目标已被击中）（88）
				3. Basic wandering AI（基本的漫游AI）（90）
					1. Diagramming how basic AI works（绘制基本人工智能的工作原理图）（90）
					2. “Seeing” obstacles with a raycast（通过光线投射“看到”障碍物）（91）
					3. Tracking the character’s state（追踪角色的状态）（92）
				4. Spawning enemy prefabs（生成敌方预制件）（94）
					1. What is a prefab?（什么是预制件？）（94）
					2. Creating the enemy prefab（创建敌人预制件）（95）
					3. Instantiating from an invisible SceneController（从不可见的 SceneController 实例化）（95）
				5. Shooting by instantiating objects（通过实例化物体进行拍摄）（98）
					1. Creating the projectile prefab（创建射弹预制件）（98）
					2. Shooting the projectile and colliding with a target（发射弹丸并与目标碰撞）（100）
					3. Damaging the player（对玩家造成伤害）（103）
			4. Developing graphics for your game（为您的游戏开发图形）（105）
				1. Understanding art assets（了解艺术资产）（106）
				2. Building basic 3D scenery: Whiteboxing（构建基本 3D 场景：白盒化）（108）
					1. Whiteboxing explained（白盒解释）（108）
					2. Drawing a floor plan for the level（绘制该层的平面图）（109）
					3. Laying out primitives according to the plan（根据计划布置图元）（110）
				3. Texturing the scene with 2D images（使用 2D 图像对场景进行纹理化）（112）
					1. Choosing a file format（选择文件格式）（112）
					2. Importing an image file（导入图像文件）（114）
					3. Applying the image（应用图像）（115）
				4. Generating sky visuals by using texture images（使用纹理图像生成天空视觉效果）（418）
					1. What is a skybox?（什么是天空盒？）（117）
					2. Creating a new skybox material（创建新的天空盒材质）（118）
				5. Working with custom 3D models（使用自定义 3D 模型）（120）
					1. Which file format to choose?（选择哪种文件格式？）（121）
					2. Exporting and importing the model（导出和导入模型）（122）
				6. Creating effects by using particle systems（使用粒子系统创建效果）（125）
					1. Adjusting parameters on the default effect（调整默认效果的参数）（126）
					2. Applying a new texture for fire（应用新的火焰纹理）（128）
					3. Attaching particle effects to 3D objects（129）
		2. Getting comfortable（变得舒适）（131）
			1. Building a Memory game using Unity’s 2D functionality（使用 Unity 的 2D 功能构建记忆游戏）（133）
				1. Setting up everything for 2D graphics（设置 2D 图形的所有内容）（134）
					1. Preparing the project（准备项目）（135）
					2. Displaying 2D images (aka sprites)（显示 2D 图像（又名精灵））（137）
					3. Switching the camera to 2D mode（将相机切换至 2D 模式）（138）
				2. Building a card object and making it react to clicks（构建卡片对象并使其对点击做出反应）（140）
					1. Building the object out of sprites（用精灵构建对象）（140）
					2. Mouse input code（鼠标输入代码）（141）
					3. Revealing the card on a click（单击即可显示卡片）（142）
				3. Displaying the various card images（显示各种卡片图像）（143）
					1. Loading images programmatically（以编程方式加载图像）（143）
					2. Setting the image from an invisible SceneController（从不可见的 SceneController 设置图像）（144）
					3. Instantiating a grid of cards（实例化卡片网格）（146）
					4. Shuffling the cards（洗牌）（148）
				4. Making and scoring matches（组织比赛并得分）（149）
					1. Storing and comparing revealed cards（存储和比较翻出的牌）（150）
					2. Hiding mismatched cards（隐藏不匹配的卡片）（150）
					3. Text display for the score（分数的文本显示）（151）
				5. Restart button（重启按钮）（153）
					1. Programming a UIButton component by using SendMessage（使用 SendMessage 编写 UIButton 组件）（154）
					2. Calling LoadScene from SceneController（从 SceneController 调用 LoadScene）（156）
			2. Creating a basic 2D platformer（创建基本的 2D 平台游戏）（158）
				1. Setting up the graphics（设置图形）（159）
					1. Placing the scenery（放置风景）（159）
					2. Importing sprite sheets（导入精灵表）（160）
				2. Moving the player left and right（左右移动玩家）（162）
					1. Writing keyboard controls（编写键盘控件）（163）
					2. Colliding with the block（与方块碰撞）（164）
				3. Playing the sprite’s animation（播放精灵的动画）（164）
					1. Explaining the Mecanim animation system（解释 Mecanim 动画系统）（164）
					2. Triggering animations from code（从代码触发动画）（166）
				4. Adding the ability to jump（增加跳跃能力）（167）
					1. Falling from gravity（因重力而坠落）（167）
					2. Applying an upward impulse（施加向上的推动力）（168）
					3. Detecting the ground（检测地面）（169）
				5. Additional features for a platform game（平台游戏的附加功能）（170）
					1. Unusual floors: Slopes and one-way platforms（不寻常的楼层：斜坡和单向平台）（170）
					2. Implementing moving platforms（实施移动平台）（172）
					3. Camera control（相机控制）（175）
			3. Putting a GUI onto a game（将 GUI 放入游戏中）（177）
				1. Before you start writing code . . .（在开始编写代码之前。 。 。）（179）
					1. Immediate mode GUI or advanced 2D interface?（立即模式 GUI 还是高级 2D 界面？）（179）
					2. Planning the layout（规划布局）（180）
					3. Importing UI images（导入用户界面图像）（181）
				2. Setting up the GUI display（设置 GUI 显示）（181）
					1. Creating a canvas for the interface（为界面创建画布）（181）
					2. Buttons, images, and text labels（按钮、图像和文本标签）（183）
					3. Controlling the position of UI elements（控制 UI 元素的位置）（186）
				3. Programming interactivity in the UI（UI 中的交互编程）（187）
					1. Programming an invisible UIController（编写一个不可见的 UIController）（188）
					2. Creating a pop-up window（创建弹出窗口）（190）
					3. Setting values using sliders and input fields（使用滑块和输入字段设置值）（193）
				4. Updating the game by responding to events（使用滑块和输入字段设置值）（196）
					1. Integrating an event system（集成事件系统）（196）
					2. Broadcasting and listening for events from the scene（广播和监听现场事件）（197）
					3. Broadcasting and listening for events from the HUD（广播和监听来自 HUD 的事件）（198）
			4. Creating a third-person 3D game: Player movement and animation（创建第三人称 3D 游戏：玩家运动和动画）（201）
				1. Adjusting the camera view for third-person（调整第三人称视角）（203）
					1. Importing a character to look at（导入一个角色来查看）（204）
					2. Adding shadows to the scene（向场景添加阴影）（205）
					3. Orbiting the camera around the player character（让摄像机围绕玩家角色旋转）（207）
				2. Programming camera-relative movement controls（对摄像机相关的运动控制进行编程）（210）
					1. Rotating the character to face movement direction（旋转角色以面向移动方向）（210）
					2. Moving forward in that direction（朝着那个方向前进）（213）
				3. Implementing the jump action（实现跳跃动作）（214）
					1. Applying vertical speed and acceleration（应用垂直速度和加速度）（215）
					2. Modifying the ground detection to handle edges and slopes（修改地面检测以处理边缘和斜坡）（216）
				4. Setting up animations on the player character（在玩家角色上设置动画）（220）
					1. Defining animation clips in the imported model（在导入的模型中定义动画剪辑）（222）
					2. Creating the animator controller for these animations（为这些动画创建动画控制器）（224）
					3. Writing code that operates the animator（编写操作动画器的代码）（227）
			5. Adding interactive devices and items within the game（在游戏中添加互动设备和物品）（230）
				1. Creating doors and other devices（创建门和其他设备）（231）
					1. Doors that open and close on a keypress（通过按键打开和关闭的门）（231）
					2. Checking distance and facing before opening the door（开门前检查距离和朝向）（233）
					3. Operating a color-changing monitor（操作变色显示器）（235）
				2. Interacting with objects by bumping into them（通过碰撞物体与物体进行交互）（236）
					1. Colliding with physics-enabled obstacles（与物理支持的障碍物碰撞）（236）
					2. Operating the door with a trigger object（使用触发对象操作门）（237）
					3. Collecting items scattered around the level（收集散布在关卡各处的物品）（240）
				3. Managing inventory data and game state（管理库存数据和游戏状态）（242）
					1. Setting up player and inventory managers（设置玩家和库存管理器）（242）
					2. Programming the game managers（游戏管理器编程）（244）
					3. Storing inventory in a collection object: List vs. Dictionary（在集合对象中存储库存：列表与字典）（247）
				4. Inventory UI for using and equipping items（用于使用和装备物品的库存 UI）（250）
					1. Displaying inventory items in the UI（在 UI 中显示库存项目）（250）
					2. Equipping a key to use on locked doors（配备钥匙以用于上锁的门）（253）
					3. Restoring the player’s health by consuming health packs（通过消耗生命包来恢复玩家的生命值）（254）
		3. Strong finish（坚固的表面处理）
			1. Connecting your game to the internet（将您的游戏连接到互联网）（259）
				1. Creating an outdoor scene（创建室外场景）（261）
					1. Generating sky visuals by using a skybox（使用天空盒生成天空视觉效果）（261）
					2. Setting up an atmosphere that’s controlled by code（营造一种由代码控制的氛围）（262）
				2. Downloading weather data from an internet service（从互联网服务下载天气数据）（265）
					1. Requesting HTTP data using coroutines（使用协程请求 HTTP 数据）（268）
					2. Parsing XML（解析XML）（272）
					3. Parsing JSON（解析 JSON）（273）
					4. Affecting the scene based on weather data（根据天气数据影响场景）（276）
				3. Adding a networked billboard（添加网络广告牌）（277）
					1. Loading images from the internet（从互联网加载图像）（277）
					2. Displaying images on the billboard（在广告牌上显示图像）（280）
					3. Caching the downloaded image for reuse（缓存下载的图像以供重复使用）（281）
				4. Posting data to a web server（将数据发布到网络服务器）（283）
					1. Tracking current weather: Sending post requests（跟踪当前天气：发送帖子请求）（284）
					2. Server-side code in PHP（PHP 中的服务器端代码）（285）
			2. Playing audio: Sound effects and music（播放音频：音效和音乐）（287）
				1. Importing sound effects（导入音效）（288）
					1. Supported file formats（支持的文件格式）（288）
					2. Importing audio files（导入音频文件）（290）
				2. Playing sound effects（播放音效）（291）
					1. Explaining what’s involved: Audio clip vs. source vs. listener（解释所涉及的内容：音频剪辑与源与听众）（291）
					2. Assigning a looping sound（分配循环声音）（293）
					3. Triggering sound effects from code（从代码触发音效）（294）
				3. Using the audio control interface（使用音频控制接口）（295）
					1. Setting up the central AudioManager（设置中央 AudioManager）（295）
					2. Volume control UI（音量控制界面）（297）
					3. Playing UI sounds（播放用户界面声音）（301）
				4. Adding background music（添加背景音乐）（301）
					1. Playing music loops（循环播放音乐）（302）
					2. Controlling music volume separately（单独控制音乐音量）（306）
					3. Fading between songs（歌曲之间的淡入淡出）（308）
			3. Putting the parts together into a complete game（将各个部分组合成一个完整的游戏）（312）
				1. Building an action RPG by repurposing projects（通过重新利用项目来构建动作角色扮演游戏）（313）
					1. Assembling assets and code from multiple projects（组装多个项目的资产和代码）（314）
					2. Programming point-and-click controls: Movement and devices（对点击式控件进行编程：移动和设备）（317）
					3. Replacing the old GUI with a new interface（用新界面替换旧 GUI）（323）
				2. Developing the overarching game structure（开发总体游戏结构）（329）
					1. Controlling mission flow and multiple levels（控制任务流程和多个级别）（329）
					2. Completing a level by reaching the exit（到达出口即可完成关卡）（333）
					3. Losing the level when caught by enemies（被敌人抓住时失去等级）（335）
				3. Handling the player’s progression through the game（处理玩家在游戏中的进展）（337）
					1. Saving and loading the player’s progress（保存和加载玩家的进度）（337）
					2. Beating the game by completing three levels（通过完成三个级别来击败游戏）（341）
			4. Deploying your game to players’ devices（将您的游戏部署到玩家的设备上）（344）
				1. Start by building for the desktop: Windows, Mac, and Linux（首先针对桌面进行构建：Windows、Mac 和 Linux）（347）
					1. Building the application（构建应用程序）（347）
					2. Adjusting player settings: Setting the game’s name and icon（调整玩家设置：设置游戏名称和图标）（348）
					3. Platform-dependent compilation（平台相关编译）（349）
				2. Building for the web（为网络构建）（351）
					1. Building the game embedded in a web page（构建嵌入网页的游戏）（351）
					2. Communicating with JavaScript in the browser（在浏览器中与 JavaScript 通信）（352）
				3. Building for mobile: iOS and Android（为移动设备构建：iOS 和 Android）（355）
					1. Setting up the build tools（设置构建工具）（356）
					2. Texture compression（纹理压缩）（361）
					3. Developing plugins（开发插件）（362）
				4. Developing XR (both VR and AR)（开发 XR（VR 和 AR））（371）
					1. Supporting virtual reality headsets（支持虚拟现实耳机）（371）
					2. AR Foundation for mobile Augmented Reality（移动增强现实 AR 基金会）（372）
	3. Unity Game Optimization Third Edition（Unity游戏优化第三版）
		1. Base Scripting Optimization（基本脚本优化）（23）
			1. Evaluating Performance Problems（评估绩效问题）（24）
				1. Gathering profiling data using the Unity Profiler（使用  Unity  收集分析数据分析器）（25）
					1. Launching the Profiler（启动分析器）（27）
						1. Editor or standalone instances（编辑器或独立实例）（28）
						2. Connecting to a WebGL instance（连接到  WebGL  实例）（29）
						3. Remote connection to an iOS device（远程连接到  iOS  设备）（30）
						4. Remote connection to an Android device（远程连接到  Android  设备）（30）
						5. Editor profiling（编辑器分析）（31）
					2. The Profiler window（探查器窗口）（32）
						1. Profiler controls（分析器控件）（33）
							1. Add Profiler（添加分析器）（33）
							2. Playmode（33）
							3. Record（记录）（34）
							4. Deep Profile（34）
							5. Allocation Callstack（分配调用栈）（35）
							6. Clear（清除）（36）
							7. Load（加载）（36）
							8. Save（节省）（36）
							9. Frame Selection（框架选择）（36）
						2. Timeline View（时间轴视图）（37）
						3. Breakdown View Controls（细分视图控件）（38）
						4. Breakdown View（细分视图）（38）
							1. The CPU Usage area（CPU  使用率区域）（38）
							2. The GPU Usage area（GPU  使用率区域）（40）
							3. The Rendering area（渲染区域）（41）
							4. The Memory area（内存区域）（41）
							5. The Audio area（音频区）（42）
							6. The Physics 3D and Physics 2D areas（物理  3D  和物理  2D  区域）（43）
							7. The network messages and network operations areas（网络消息和网络操作区域）（43）
							8. The Video area（视频区）（43）
							9. The UI and UI Details areas（UI  和  UI  详细信息区域）（44）
							10. The Global Illumination area（全局照明区域）（44）
				2. Best approaches to performance analysis（性能分析的最佳方法）（44）
					1. Verifying script presence（验证脚本是否存在）（45）
					2. Verifying script count（验证脚本计数）（46）
					3. Verifying the order of events（验证事件的顺序）（47）
					4. Minimizing ongoing code changes（最大限度地减少正在进行的代码更改）（48）
					5. Minimizing internal distractions（尽量减少内部干扰）（49）
					6. Minimizing external distractions（最大限度地减少外部干扰）（51）
					7. Targeted profiling of code segments（有针对性的代码段分析）（51）
						1. Profiler script control（Profiler  脚本控制）（52）
						2. Custom CPU profiling（自定义  CPU  分析）（53）
				3. Final thoughts on profiling and analysis（关于剖析和分析的最终想法）（57）
					1. Understanding the Profiler（了解探查器）（58）
					2. Reducing noise（降低噪音）（58）
					3. Focusing on the issue（聚焦问题）（59）
			2. Scripting Strategies（脚本策略）（61）
				1. Obtaining components using the fastest method（使用最快的方法获取组件）（62）
				2. Removing empty callback definitions（删除空回调定义）（63）
				3. Caching component references（缓存组件引用）（57）
				4. Sharing calculation output（共享计算输出）（59）
				5. Update, coroutines, and InvokeRepeating（更新、协程和  InvokeRepeating）（70）
				6. Faster GameObject null reference checks（更快的游戏对象空引用检查）（74）
				7. Avoid retrieving string properties from GameObjects（避免从以下位置检索字符串属性游戏对象）（75）
				8. Using appropriate data structures（使用适当的数据结构）（77）
				9. Avoiding re-parenting transforms at runtime（避免在运行时重新设置父子关系转换）（78）
				10. Considering caching transform changes（考虑缓存转换更改）（79）
				11. Avoiding Find() and SendMessage() at runtime（在运行时避免  Find()  和  SendMessage()）（81）
					1. Assigning references to pre-existing objects（分配对预先存在的对象的引用）（85）
					2. Static classes（静态类）（87）
					3. Singleton components（单例组件）（90）
					4. A global messaging system（全球消息系统）（94）
						1. A globally accessible object（全局可访问的对象）（95）
						2. Registration（注册）（96）
						3. Message processing（消息处理）（97）
						4. Implementing the messaging system（实现消息系统）（97）
						5. Message queuing and processing（消息队列和处理）（98）
						6. Implementing custom messages（实现自定义消息）（101）
						7. Message sending（消息发送）（102）
						8. Message registration（留言登记）（102）
						9. Message cleanup（消息清理）（105）
						10. Wrapping up the messaging system（结束消息传递系统）（106）
				12. Disabling unused scripts and objects（禁用未使用的脚本和对象）（107）
					1. Disabling objects by visibility（通过可见性禁用对象）（108）
					2. Disabling objects by distance（按距离禁用对象）（109）
				13. Using distance-squared over distance（使用距离平方除以距离）（110）
				14. Minimizing deserialization behavior（最小化反序列化行为）（111）
					1. Reducing serialized object size（减少序列化对象的大小）（112）
					2. Loading serialized objects asynchronously（异步加载序列化对象）（112）
					3. Keeping previously loaded serialized objects in memory（将先前加载的序列化对象保留在内存中）（113）
					4. Moving common data into ScriptableObjects（将通用数据移动到  ScriptableObjects  中）（113）
				15. Loading scenes additively and asynchronously（添加和异步加载场景）（113）
				16. Creating a custom Update() layer（创建自定义  Update()  层）（115）
		2. Graphical Optimizations（图形优化）（121）
			1. The Benefits of Batching（批处理的好处）（122）
				1. Draw calls（绘制调用）（123）
				2. Materials and shaders（材质和着色器）（126）
				3. The Frame Debugger（帧调试器）（129）
				4. Dynamic batching（动态批处理）（130）
					1. Vertex attributes（顶点属性）（132）
					2. Mesh scaling（网格缩放）（134）
					3. Dynamic batching summary（动态批处理总结）（135）
				5. Static batching（静态批处理）（137）
					1. The Static flag（静态标志）（137）
					2. Memory requirements（内存要求）（138）
					3. Material references（材质引用）（138）
					4. Static batching caveats（静态批处理注意事项）（139）
						1. Edit Mode debugging of static batching（静态批处理的编辑模式调试）（139）
						2. Instantiating static meshes at runtime（在运行时实例化静态网格物体）（139）
					5. Static batching summary（静态批处理总结）（140）
			2. Optimizing Your Art Assets（优化您的艺术资产）（142）
				1. Audio（声音）（142）
					1. Importing audio files（导入音频文件）（143）
					2. Loading audio files（加载音频文件）（144）
					3. Encoding formats and quality levels（编码格式和质量级别）（148）
					4. Audio performance enhancements（音频性能增强）（149）
						1. Minimizing active audio source count（最小化活动音频源数量）（150）
						2. Enabling Force to Mono for 3D sounds（为  3D  声音启用强制为单声道）（150）
						3. Resampling to lower frequencies（重新采样到较低频率）（151）
						4. Considering all compression formats（考虑所有压缩格式）（151）
						5. Being cautious of streaming（对流式传输保持谨慎）（151）
						6. Applying filter effects through mixer groups to reduce duplication（通过混音器组应用滤镜效果以减少重复）（152）
						7. Using remote content streaming responsibly（负责任地使用远程内容流）（152）
						8. Consider using audio module files for background music（考虑使用音频模块文件作为背景音乐）（153）
				2. Texture files（纹理文件）（153）
					1. Texture compression formats（纹理压缩格式）（154）
					2. Texture performance enhancements（纹理性能增强）（157）
						1. Reducing texture file size（减少纹理文件大小）（157）
						2. Using mipmaps wisely（明智地使用  mipmap）（158）
						3. Managing resolution downscaling externally（管理外部分辨率缩小）（160）
						4. Adjusting anisotropic filtering levels（调整各向异性过滤级别）（160）
						5. Consider atlasing（考虑图集）（161）
						6. Adjusting compression rates for nonsquare textures（调整非方形纹理的压缩率）（164）
						7. Sparse textures（稀疏纹理）（164）
						8. Procedural materials（程序材质）（166）
						9. Asynchronous texture uploading（异步纹理上传）（166）
				3. Mesh and animation files（网格和动画文件）（167）
					1. Reducing the polygon count（减少多边形数量）（167）
					2. Tweaking mesh compression（调整网格压缩）（168）
					3. Using Read-Write Enabled appropriately（适当使用读写启用）（169）
					4. Considering baked animations（考虑烘焙动画）（170）
					5. Combining meshes（组合网格）（170）
				4. Asset bundles and resources（资产包和资源）（171）
			3. Faster Physics（更快的物理）（173）
				1. Understanding the physics engine（了解物理引擎）（174）
					1. Physics and time（物理与时间）（175）
						1. Maximum Allowed Timestep（最大允许时间步长）（177）
						2. Physics updates and runtime changes（物理更新和运行时更改）（177）
					2. Static colliders and dynamic colliders（静态碰撞器和动态碰撞器）（179）
					3. Collision detection（碰撞检测）（179）
					4. Collider types（对撞机类型）（181）
					5. The Collision Matrix（碰撞矩阵）（183）
					6. Rigidbody active and sleeping states（刚体活动和睡眠状态）（184）
					7. Ray and object casting（光线和物体投射）（185）
					8. Debugging physics（调试物理）（185）
				2. Physics performance optimizations（物理性能优化）（187）
					1. Scene setup（场景设置）（187）
						1. Scaling（缩放比例）（188）
						2. Positioning（定位）（188）
						3. Mass（189）
					2. Using static colliders appropriately（适当使用静态碰撞器）（190）
					3. Using trigger volumes responsibly（负责任地使用触发量）（191）
					4. Optimizing the Collision Matrix（优化碰撞矩阵）（192）
					5. Preferring discrete collision detection（首选离散碰撞检测）（193）
					6. Modifying the fixed update frequency（修改固定更新频率）（194）
					7. Adjusting the Maximum Allowed Timestep（调整最大允许时间步长）（196）
					8. Minimizing raycasting and bounding-volume checks（最小化光线投射和包围体检查）（196）
					9. Avoiding complex Mesh Colliders（避免复杂的网格碰撞器）（198）
						1. Using simpler primitives（使用更简单的基元）（199）
						2. Using simpler Mesh Colliders（使用更简单的网格碰撞器）（200）
					10. Avoiding complex physics components（避免复杂的物理组件）（201）
					11. Letting physics objects sleep（让物理对象休眠）（202）
					12. Modifying the solver iteration count（修改求解器迭代计数）（203）
					13. Optimizing ragdolls（优化布娃娃）（205）
						1. Reducing joints and colliders（减少关节和碰撞）（205）
						2. Avoiding inter-ragdoll collisions（避免布娃娃之间的碰撞）（206）
						3. Replacing, deactivating, or removing inactive ragdolls（替换、停用或删除不活动的布娃娃）（206）
					14. Knowing when to use physics（知道何时使用物理）（207）
			4. Dynamic Graphics（动态图形）（209）
				1. Exploring the Rendering Pipeline（探索渲染管线）（210）
					1. The GPU frontend（GPU  前端）（212）
					2. The GPU backend（GPU  后端）（212）
						1. Fill Rate（填充率）（213）
							1. Overdraw（214）
						2. Memory bandwidth（内存带宽）（216）
					3. Lighting and shadowing（照明和阴影）（217）
						1. Forward Rendering（前向渲染）（219）
						2. Deferred Shading（延迟着色）（219）
						3. Vertex-Lit shading (legacy)（顶点光照着色（旧版））（220）
						4. Global Illumination（全局照明）（220）
					4. Multithreaded Rendering（多线程渲染）（222）
					5. Low-level rendering APIs（低级渲染  API）（223）
				2. Detecting performance issues（检测性能问题）（223）
					1. Profiling rendering issues（分析渲染问题）（224）
					2. Brute force testing（暴力测试）（226）
				3. Rendering performance enhancements（渲染性能增强）（228）
					1. Enabling/disabling GPU skinning（启用/禁用  GPU  换肤）（228）
					2. Reducing geometric complexity（降低几何复杂性）（228）
					3. Reducing tessellation（减少镶嵌）（229）
					4. Employing GPU instancing（使用GPU实例化）（229）
					5. Using mesh-based LOD（使用基于网格的  LOD）（230）
						1. Culling groups（剔除组）（232）
					6. Making use of Occlusion Culling（利用遮挡剔除）（232）
					7. Optimizing Particle Systems（优化粒子系统）（234）
						1. Making use of Particle System culling（利用粒子系统剔除）（234）
						2. Avoiding recursive Particle System calls（避免递归粒子系统调用）（235）
					8. Optimizing Unity UI（优化Unity  UI）（236）
						1. Using more Canvases（使用更多Canvas）（236）
						2. Separating objects between static and dynamic Canvases（分离静态和动态画布之间的对象）（237）
						3. Disabling Raycast Target for non-interactive elements（禁用非交互式元素的  Raycast  Target）（238）
						4. Hiding UI elements by disabling the parent Canvas component（通过禁用父  Canvas  组件来隐藏  UI  元素）（238）
						5. Avoiding Animator components（避免  Animator  组件）（239）
						6. Explicitly defining the event camera for World Space Canvases（明确定义世界空间画布的事件相机）（239）
						7. Don't use alpha to hide UI elements（不要使用  alpha  来隐藏  UI  元素）（240）
						8. Optimizing ScrollRects（优化  ScrollRect）（240）
							1. Make sure to use a RectMask2D（确保使用  RectMask2D）（240）
							2. Disable Pixel Perfect for ScrollRects（禁用  ScrollRect  的  Pixel  Perfect）（224）
							3. Manually stop ScrollRect motion（手动停止  ScrollRect  运动）（241）
						9. Using empty UIText elements for full-screen interaction（使用空的  UIText  元素进行全屏交互）（241）
						10. Checking the Unity UI source code（检查  Unity  UI  源代码）（241）
						11. Checking the documentation（检查文档）（242）
					9. Shader optimization（着色器优化）（242）
						1. Consider using shaders intended for mobile platforms（考虑使用适用于移动平台的着色器）（243）
						2. Using small data types（使用⼩数据类型）（243）
						3. Avoiding changing precision while swizzling（避免在调配时改变精度）（244）
						4. Using GPU-optimized helper functions（使用  GPU  优化的辅助函数）（245）
						5. Disabling unnecessary features（禁用不必要的功能）（246）
						6. Removing unnecessary input data（删除不必要的输入数据）（246）
						7. Exposing only necessary variables（仅公开必要的变量）（246）
						8. Reducing mathematical complexity（降低数学复杂性）（246）
						9. Reducing texture sampling（减少纹理采样）（247）
						10. Avoiding conditional statements（避免条件语句）（248）
						11. Reducing data dependencies（减少数据依赖性编）（249）
						12. Surface Shaders（表面着色器）（250）
						13. Use shader-based LOD（使用基于着色器的  LOD）（250）
					10. Using less texture data（使用更少的纹理数据）（251）
					11. Testing different GPU texture compression formats（测试不同的GPU纹理压缩格式）（251）
					12. Minimizing texture swapping（最⼩化纹理交换）（252）
					13. VRAM limits（显存限制）（253）
						1. Preloading textures with hidden GameObjects（使用隐藏的游戏对象预加载纹理）（253）
						2. Avoid texture thrashing（避免纹理抖动）（253）
					14. Lighting optimization（照明优化）（254）
						1. Using real-time shadows responsibly（负责任地使用实时阴影）（254）
						2. Using culling masks（使用剔除蒙版）（256）
						3. Using baked lightmaps（使用烘焙光照贴图）（256）
					15. Optimizing rendering performance for mobile devices（优化移动设备的渲染性能）（257）
						1. Avoiding alpha testing（避免  alpha  测试）（257）
						2. Minimizing draw calls（最大限度地减少绘制调用）（257）
						3. Minimizing Material count（最大限度地减少材料数量）（258）
						4. Minimizing texture size（最⼩化纹理大⼩）（258）
						5. Making textures square and the power-of-two（使纹理平方和  2  的幂）（259）
						6. Using the lowest possible precision formats in shaders（在着色器中使用尽可能低的精度格式）（259）
		3. Advance Optimizations（高级优化）（260）
			1. Optimizations for Virtual and Augmented Reality（虚拟和增强现实的优化）（261）
				1. Overview of XR technology（XR技术概述）（262）
				2. Developing XR products（开发XR产品）（263）
					1. User comfort（用户舒适度）（265）
				3. Performance enhancements in XR（XR  的性能增强）（258）
					1. The kitchen sink（268）
					2. Single Pass versus Multi Pass Stereo rendering（单通道与多通道立体渲染）（269）
					3. Applying antialiasing（应用抗锯齿）（271）
					4. Using forward rendering（使用前向渲染）（271）
					5. Applying image effects in VR（在  VR  中应用图像效果）（272）
					6. Backface culling（背面剔除）（272）
					7. Spatialized audio（空间化音频）（273）
					8. Avoiding camera physics collisions（避免相机物理碰撞）（273）
					9. Avoiding Euler angles（避免欧拉角）（258）
					10. Exercise restraint（保持克制）（275）
					11. Keeping up to date with the latest developments（及时了解最新动态）（275）
			2. Masterful Memory Management（精湛的内存管理）（276）
				1. The Mono platform（单声道平台）（277）
					1. Memory domains（内存域）（280）
						1. The stack（堆栈）（281）
						2. The heap（堆）（281）
					2. Garbage collection（垃圾收集）（282）
						1. Memory fragmentation（内存碎片）（283）
						2. Garbage collection at runtime（运行时垃圾收集）（285）
						3. Threaded garbage collection（线程垃圾收集）（286）
				2. Code compilation（代码编译）（287）
					1. IL2CPP（288）
				3. Profiling memory（分析内存）（290）
					1. Profiling memory consumption（分析内存消耗）（290）
					2. Profiling memory efficiency（分析内存效率）（291）
				4. Memory management performance enhancements（内存管理性能增强）（292）
					1. Garbage collection tactics（垃圾收集策略）（292）
					2. Manual JIT compilation（手动JIT编译）（293）
					3. Value types and reference types（值类型和引用类型）（294）
						1. Pass by value and by reference（按值传递和按引用传递）（297）
						2. Structs are value types（结构是值类型）（299）
						3. Arrays are reference types（数组是引用类型）（301）
						4. Strings are immutable reference types（字符串是不可变的引用类型）（302）
					4. String concatenation（字符串连接）（304）
						1. StringBuilder（306）
						2. String formatting（字符串格式化）（306）
					5. Boxing（307）
					6. The importance of data layout（数据布局的重要性）（309）
					7. Arrays from the Unity API（来自  Unity  API  的数组）（310）
					8. Using InstanceIDs for dictionary keys（使用  InstanceID  作为字典键）（311）
					9. foreach loops（foreach  循环）（312）
					10. Coroutines（协程）（313）
					11. Closures（闭包）（313）
					12. The .NET library functions（.NET  库函数）（314）
					13. Temporary work buffers（临时工作缓冲区）（315）
					14. Object pooling（对象池）（315）
					15. Prefab pooling（预制池）（318）
						1. Poolable components（可共用组件）（322）
						2. The Prefab pooling system（预制池系统）（325）
						3. Prefab pools（预制件池）（328）
						4. Object spawning（对象生成）（329）
						5. Instance prespawning（实例预生成）（330）
						6. Object despawning（对象消失）（331）
						7. Prefab pool testing（预制池测试）（332）
						8. Prefab pooling and scene loading（预制件池和场景加载）（333）
						9. Prefab pooling summary（预制池总结）（334）
					16. IL2CPP optimizations（IL2CPP  优化）（335）
					17. WebGL optimizations（WebGL  优化）（335）
			3. The Data-Oriented Technology Stack（面向数据的技术堆栈）（337）
				1. The problem of multithreading（多线程的问题）（338）
					1. A small example（一个⼩例子）（339）
				2. The Unity Job System（Unity工作系统）（343）
					1. A basic job（一份基本工作）（343）
					2. A more complex example（一个更复杂的例子）（346）
				3. The new ECS（新的ECS）（351）
					1. Mixing ECS and jobs（混合  ECS  和作业）（352）
				4. The burst compiler（突发编译器）（359）
			4. Tactical Tips and Tricks（战术提示和技巧）（361）
				1. Editor hotkey tips（编辑器热键提示）（362）
					1. Working with GameObjects（使用游戏对象）（362）
					2. Scene window（场景窗口）（363）
					3. Arrays（数组）（364）
					4. Interface（界面）（365）
					5. In-editor documentation（编辑器内文档）（366）
				2. Editor UI tips（编辑器  UI  提示）（366）
					1. Script Execution Order（脚本执行顺序）（367）
					2. Editor files（编辑器文件）（367）
					3. The Inspector window（检查器窗口）（369）
					4. The Project window（项目窗口）（371）
					5. The Hierarchy window（层次结构窗口）（372）
					6. The Scene and Game windows（场景和游戏窗口）（372）
					7. Playmode（游戏模式）（374）
				3. Scripting tips（脚本编写技巧）（375）
					1. General（一般的）（375）
					2. Attributes（属性）（375）
						1. Variable attributes（可变属性）（376）
						2. Class attributes（类属性）（376）
					3. Logging（记录）（377）
					4. Useful links（有用的链接）（377）
				4. Custom Editor scripts and menu tips（自定义编辑器脚本和菜单提示）（378）
				5. External tips（外部提示）（379）
				6. Other tips（其他提示）（380）
	4. Building an FPS Game with Unity（使用  Unity  构建  FPS  游戏）
		1. Getting Started on an FPS（FPS  入门）（24）
			1. Prerequisites（先决条件）（25）
			2. Project creation（项目创建）（27）
			3. Getting started with the Asset Store（开始使用资源商店）（29）
				1. Installing UFPS（安装  UFPS）（32）
			4. Installing Prototype（安装原型）（35）
			5. File organization（文件组织）（38）
			6. Customizing Unity's layout（自定义  Unity  的布局（39））
		2. Building Custom Weapons（建造定制武器）（42）
			1. Prerequisites（先决条件）（43）
			2. Setting up a testbed（设置测试平台）（43）
			3. Getting models/sounds for weapons（获取武器的模型/声音）（45）
			4. Building our weapon – the mesh（建造我们的武器-网格）（47）
			5. Creating a UnitBank（创建单位银行）（52）
			6. Creating the weapon（创造武器）（53）
			7. Customizing our weapon's properties（定制我们的武器属性）（57）
		3. Prototyping Levels with Prototype（使用 Prototype 制作原型级别）（64）
			1. Prerequisites（先决条件）（65）
				1. Level design 101 – planning（关卡设计101-计划）（65）
				2. Creating the architectural overview（创建架构概述）（67）
					1. 3D modeling software（3D建模软件）（67）
					2. Constructing geometry with brushes（用画笔构建几何体）（67）
					3. Modular tilesets（模块化图块集）（68）
					4. Mix and match（连连看）（68）
			2. Creating geometry（创建几何图形）（69）
			3. Building a doorway（建造一个门道）（83）
			4. Duplicating rooms / creating a hallway（复制房间/创建走廊）（91）
			5. Preventing falls - collision（预防跌倒‑碰撞）（96）
			6. Adding stairways（添加楼梯）（99）
			7. Coloring your world（为你的世界增添色彩）（107）
		4. Creating Exterior Environments（创造外部环境）（110）
			1. Prerequisites（先决条件）（110）
			2. Introduction to Terrain（地形简介）（111）
				1. Height maps（高度图）（111）
				2. Hand sculpting（手工雕刻）（113）
			3. Creating the Terrain（创建地形）（114）
			4. Adding color to our Terrain – textures（为我们的地形添加颜色  ‑  纹理）（120）
			5. Adding water（加水）（129）
			6. Adding trees（添加树木）（131）
			7. Adding details – grass（添加细节-草）（135）
			8. Building the atmosphere – Skyboxes and Fog（营造氛围——天空盒和雾）（137）
		5. Building Encounters（建筑邂逅）（144）
			1. Prerequisites（先决条件）（144）
			2. Adding a simple turret enemy（添加一个简单的炮塔敌人）（145）
			3. Integrating an AI system – RAIN（集成人工智能系统-RAIN）（152）
			4. Integrating an AI system – Shooter AI（集成AI系统——Shooter AI）（176）
			5. Spawning enemies with the help of a trigger（在扳机的帮助下生成敌人）（187）
			6. Spawning multiple enemies at once（一次生成多个敌人）（202）
			7. Cleaning up dead AI（清理死掉的AI）（207）
			8. Placing healthpacks/ammo（放置医疗包/弹药）（209）
		6. Breathing Life into Levels（为关卡注入生命力）（212）
			1. Prerequisites（先决条件）（212）
			2. Building an explosive barrel（建造一个炸药桶）（213）
			3. Using triggers for doors（使用门触发器）（221）
			4. Creating an elevator（231）（创建电梯）（231）
		7. Adding Polish with ProBuilder（使用  ProBuilder  添加抛光效果）（238）
			1. Prerequisites（先决条件）（238）
			2. Upgrading from Prototype to ProBuilder（从  Prototype  升级到  ProBuilder）（239）
			3. Creating material（创建材质）（246）
			4. Working with ProBuilder – placing materials（使用  ProBuilder  –  放置材质）（250）
			5. Meshing your levels（网格化你的关卡）（272）
		8. Creating a Custom GUI（创建自定义  GUI）（278）
			1. Prerequisites（先决条件）（278）
			2. Creating a main menu: part 1 – adding text（创建主菜单：第 1 部分 – 添加文本）（279）
			3. Creating a main menu: part 2 – adding buttons（创建主菜单：第 2 部分 – 添加按钮）（284）
			4. Creating a main menu: part 3 – button functionality（创建主菜单：第 3 部分 – 按钮功能）（288）
			5. Replacing the default UFPS HUD（替换默认的  UFPS  HUD）（293）
		9. Finalizing Our Project（完成我们的项目）（302）
			1. Prerequisites（先决条件）（302）
			2. Building the game in Unity（在  Unity  中构建游戏）（302）
			3. Building an installer for Windows（构建  Windows  安装程序）（306）
			4. Building an installer for Windows（构建  Windows  安装程序）（314）
	5. Building an RPG with Unity 2018 Second Edition（使用 Unity 2018 构建 RPG 第二版）
		1. What is an RPG?（什么是角色扮演游戏？）（39）
			1. A brief history of the genre（该流派简史）（40）
			2. Characteristics of an RPG（角色扮演游戏的特点）（42）
				1. Story and setting（故事和设定）（43）
					1. A glimpse of a cRPG story（cRPG  故事一瞥）（44）
				2. Exploration and quests（探索和任务）（45）
					1. A glimpse at our exploration and quests（一睹我们的探索和追求）（47）
				3. Inventory system（库存系统）（48）
				4. Character attributes and actions（角色属性和动作）（52）
				5. Experience and leveling（经验和练级）（55）
				6. Combat system（战斗系统）（57）
				7. User interaction and graphics（用户交互和图形）（59）
			3. Existing or upcoming RPG games（现有或即将推出的  RPG  游戏）（63）
				1. MU Legend（64）
				2. Titan Siege（神话纪元）（66）
				3. Citadel: Forged with Fire（68）
				4. Cyberpunk 2077（赛博朋克2077）（70）
			4. Patterns in RPG（RPG  中的模式）（72）
				1. Terminology（术语）（74）
				2. Contest tree（竞赛树）（77）
				3. Last Man Standing（最后一个站着的人）（79）
				4. Negotiated Contest（谈判竞赛）（80）
		2. Planning the Game（规划游戏）（83）
			1. Building our RPG（构建我们的角色扮演游戏）（84）
			2. The story of the Zazar dynasty（扎扎尔王朝的故事）（85）
				1. Backstory（背景故事）（86）
				2. Exploration and quests（探索和任务）（87）
					1. Awakening（唤醒）（88）
					2. The village（村庄）（90）
					3. Broken forest – the horizon（破碎的森林——地平线）（92）
					4. The kingdom（王国）（94）
			3. Asset inventory（资产盘点）（96）
				1. Environment assets（环境资产）（97）
					1. Medieval Environment Pack（中世纪环境包）（99）
					2. Terrain Toolkit 2017（地形工具包  2017）（101）
					3. Nature Starter Kit 2（自然入门套件  2）（102）
				2. Character assets（角色资产）（103）
					1. Barbarians（野蛮人）（104）
					2. Orcs（兽人）（105）
					3. Villagers（村民）（106）
					4. Free Assets（自由资产）（107）
			4. Level design（关卡设计）（108）
				1. Setting the stage（搭建舞台）（110）
				2. Terrain toolkit in a nutshell（简而言之，地形工具包）（114）
				3. The Awakening（觉醒）（116）
					1. Using the terrain model（使用地形模型）（119）
					2. Using a custom toolkit（使用自定义工具包）（121）
					3. Skybox（天空盒）（130）
			5. Testing the level（测试关卡）（131）
			6. Creating the main menu（创建主菜单）（133）
			7. Creating the GameMaster script（创建  GameMaster  脚本）（135）
		3. RPG Character Design（角色扮演游戏角色设计）（140）
			1. Character definitions（角色定义）（141）
				1. Character assets（角色资产）（142）
			2. Base character class attributes（基本角色类属性）
			3. Character states（角色状态）（145）
			4. Character model（角色模型）（148）
				1. Default character models（默认角色模型）（149）
					1. Barbarian（野蛮人）（149）
					2. Villager（村民）（151）
					3. Orc（兽人）（152）
				2. Let's get started（让我们开始吧）（153）
					1. Rigging your model（操纵你的模型）（155）
			5. Character motion（角色动作）（157）
				1. Animator Controller（动画控制器）（158）
					1. Animation states（动画状态）（160）
				2. Character controller（角色控制器）（165）
					1. Modification to animations（动画修改）（170）
			6. Inverse Kinematics（逆运动学）（174）
				1. Setting the animation curve（设置动画曲线）（179）
		4. The Game Mechanics（游戏机制）（182）
			1. Customizing the player character（自定义玩家角色）（183）
				1. Customizable parts（可定制零件）（186）
					1. User interface（用户界面）（188）
					2. The code for character customization（角色定制代码）（191）
					3. Preserving our character state（保持我们的性格状态）（195）
				2. Recap（回顾）（197）
			2. Non-player characters（非玩家角色）（198）
				1. Non-player character basics（非玩家角色基础知识）（200）
					1. Setting up the non-player character（设置非玩家角色）（201）
					2. NPC Animator Controller（NPC  动画控制器）（207）
					3. NPC Attack（NPC攻击）（211）
				2. NPC AI（NPC人工智能）（214）
			3. PC and NPC interaction（PC与NPC互动）（222）
		5. GameMaster and Game Mechanics（游戏大师和游戏机制）（232）
			1. GameMaster（游戏大师）（233）
				1. Managing game settings and audio（管理游戏设置和音频）（237）
				2. Managing scenes（管理场景）（241）
			2. Improving GameMaster（改进游戏大师）（245）
				1. Level controller（关卡控制器）
				2. Audio controller（音频控制器）（248）
			3. Player data management（玩家数据管理）（252）
				1. PC class enhancements（PC类增强）（253）
				2. Character customization class update（角色定制类更新）（256）
			4. Changes to the game level controller（游戏关卡控制器的更改）（263）
			5. Testing（测试）（264）
		6. Inventory System（库存系统）（268）
			1. Designing an inventory system（设计库存系统）（270）
				1. Weighted inventory（加权库存）（271）
				2. Determining item types（确定项目类型）（273）
			2. Creating an inventory item（创建库存项目）（280）
				1. Creating the prefab（创建预制件）（282）
				2. Adding an inventory item agent（添加库存项目代理）（284）
				3. Inventory items defined as prefabs（定义为预制件的库存项目）（288）
			3. Designing an inventory interface（设计库存界面）（290）
				1. Creating the inventory UI framework（创建库存 UI 框架）（292）
				2. Designing a dynamic item viewer（设计动态项目查看器）（296）
					1. Adding a scroll view（添加滚动视图）（297）
					2. Adding elements to PanelItem and Scroll View（将元素添加到PanelItem 和Scroll View）（301）
					3. Adding txtItemElement dynamically（动态添加txtItemElement）（303）
				3. Building the final inventory item UI（构建最终库存项目  UI）（305）
			4. Integrating the UI with the actual inventory system（将UI与实际库存系统集成）（308）
				1. Hooking the category buttons and displaying the data（挂钩类别按钮并显示数据）（309）
				2. Testing the inventory system（测试库存系统）（313）
			5. Inventory items and the player character（库存物品和玩家角色）（319）
				1. Applying inventory items（应用库存项目）（320）
				2. How it looks（看起来怎么样）（333）
		7. User Interface and System Feedback（用户界面和系统反馈）（337）
			1. Designing a heads-up display（设计平视显示器）(339)
				1. HUD basics（平视显示器基础知识）（340）
				2. Our design（我们的设计）（341）
				3. HUD framework（平视显示器框架）（342）
			2. Completing our HUD design（完成我们的  HUD  设计）（345）
				1. Character info panel（角色信息面板）（346）
				2. Active inventory items panel（活动库存物品面板）（351）
				3. Special items panel（特殊物品面板）（356）
			3. Integrating the code（集成代码）（358）
			4. Enemy stats in the HUD（HUD  中的敌人统计数据）（371）
				1. NPC stats user interface（NPC统计用户界面）（372）
				2. Creating the NPC canvas（创建  NPC  画布）（373）
				3. NPC taking a hit（NPC受到打击）（377）
			5. Enhancing the code（增强代码）（382）
		8. Multiplayer Setup（多人游戏设置）（389）
			1. Challenges of a multiplayer game（多人游戏的挑战）（390）
			2. Initial multiplayer game（初始多人游戏）（392）
				1. Fundamental networking components（基本网络组件）（393）
				2. My tank networking project（我的坦克网络项目）（395）
				3. Adding a player character（添加玩家角色）（397）
					1. Variable synchronization（变量同步）（401）
					2. Network callbacks（网络回调）（402）
					3. Sending commands（发送命令）（403）
					4. Client RPC calls（客户端  RPC  调用）（404）
					5. Creating the cannonball for the tank（为坦克制作炮弹）（407）
					6. Creating the tank prefab and configuring the network lobby manager（创建坦克预制件并配置网络大厅管理器）（409）
				4. Adding the enemy tank（添加敌方坦克）（413）
				5. Building and testing（构建和测试）（418）
			3. Network-enabling RPG characters（支持网络的  RPG  角色）（421）
				1. Creating a scene for our RPG（为我们的  RPG  创建场景）（422）
				2. Networked player character（网络玩家角色）（424）
				3. Networked non-player character（联网的非玩家角色）（430）
				4. Synchronizing player customization and items（同步玩家自定义和物品）（439）
				5. Spawning NPCs and other items（生成  NPC  和其他物品）（441）
			4. Testing our network-enabled PC and NPC（测试我们的联网  PC  和  NPC）（443）
			5. What's next?（下一步是什么？）（450）
	6. Introduction to Game Design, Prototyping, and Development From Concept to Playable Game with Unity and C# （使用 Unity 和 C# 介绍从概念到可玩游戏的游戏设计、原型设计和开发）（71）
		1. Game Design and Paper Prototyping（游戏设计和纸质原型）（71）
			1. Thinking Like a Designer（像设计师一样思考）（72）
				1. You Are a Game Designer（你是一名游戏设计师）（72）
				2. Bartok: A Game Design Exercise（Bartok：游戏设计练习）（73）
					1. Objective（客观的）（74）
					2. Getting Started（入门）（74）
					3. Playtesting（游戏测试）（76）
					4. Analysis: Asking the Right Questions（分析：提出正确的问题）（77）
					5. Modifying the Rules（修改规则）（78）
					6. Analysis: Comparing the Rounds（分析：回合比较）（79）
					7. Designing for the Game Feel That You Want（为您想要的游戏感觉进行设计）（81）
				3. The Definition of Game（游戏的定义）（82）
					1. Bernard Suits’ Definition（伯纳德西装的定义）（83）
					2. Sid Meier’s Definition（席德·梅尔的定义）（85）
					3. Tracy Fullerton’s Definition（特雷西·富勒顿的定义）（86）
					4. Jesse Schell’s Definition（杰西·谢尔的定义）（87）
					5. Keith Burgun’s Definition（基思·布尔根的定义）（88）
					6. Why Care About the Definition of Game?（为什么要关心游戏的定义？）（89）
					7. The Nebulous Nature of Definitions（定义的模糊性）（91）
			2. Game Analysis Frameworks（游戏分析框架）（95）
				1. Common Frameworks for Ludology（Ludology  的通用框架）（95）
				2. MDA: Mechanics, Dynamics, and Aesthetics（MDA：力学、动力学和美学）（96）
					1. Definitions of Mechanics, Dynamics, and Aesthetics（力学、动力学和美学的定义）（96）
					2. Designer and Player Views of a Game（游戏的设计师和玩家视图）（97）
					3. Design from Aesthetics to Dynamics to Mechanics（设计从美学到动力学再到力学）（98）
				3. Formal, Dramatic, and Dynamic Elements（正式、戏剧性和动态元素）（101）
					1. Formal Elements（形式要素）（102）
					2. Dramatic Elements（戏剧元素）（103）
					3. Dynamic Elements（动态元素）（105）
				4. The Elemental Tetrad（元素四分体）（106）
			3. The Layered Tetrad（层状四分体）（110）
				1. The Inscribed Layer（铭刻层）（111）
				2. The Dynamic Layer（动态层）（112）
				3. The Cultural Layer（文化层）（114）
				4. The Responsibility of the Designer（设计师的责任）（117）
			4. The Inscribed Layer（铭刻层）（120）
				1. Inscribed Mechanics（铭刻力学）（120）
					1. Objectives（目标）（122）
					2. Player Relationships（玩家关系）（125）
					3. Rules（规则）（128）
					4. Boundaries（边界）（129）
					5. Resources（资源）（130）
					6. Spaces（空间）（131）
					7. Tables（表格）（132）
				2. Inscribed Aesthetics（铭刻美学）（133）
					1. The Five Aesthetic Senses（五种审美感官）（133）
					2. Aesthetic Goals（审美目标）（136）
				3. Inscribed Narrative（铭刻叙事）（137）
					1. Components of Inscribed Narrative（铭刻叙事的组成部分）（137）
					2. Traditional Dramatics（传统戏剧）（138）
					3. Differences Between Interactive and Linear Narrative（互动叙事和线性叙事之间的差异）（144）
					4. Purposes for Inscribed Dramatics（铭刻戏剧的目的）（150）
				4. Inscribed Technology（铭刻技术）（152）
					1. Inscribed Paper Game Technology（刻纸游戏技术）（152）
					2. Inscribed Digital Game Technology（铭刻数字游戏技术）（153）
			5. The Dynamic Layer（动态层）（154）
				1. The Role of the Player（玩家的角色）（154）
				2. Emergence（紧急情况）（156）
					1. Unexpected Mechanical Emergence（意外的机械出现）（156）
				3. Dynamic Mechanics（动态力学）（157）
					1. Procedures（程序）（157）
					2. Meaningful Play（有意义的游戏）（158）
					3. Strategy（战略）（159）
					4. House Rules（家庭规则）（161）
					5. Player Intent: Bartle’s Types, Cheaters, Spoilsports（玩家意图：巴图类型、作弊者、破坏运动）（162）
					6. Outcome（结果）（164）
				4. Dynamic Aesthetics（动态美学）（166）
					1. Procedural Aesthetics（程序美学）（166）
					2. Environmental Aesthetics（环境美学）（173）
				5. Dynamic Narrative（动态叙事）（176）
					1. Interactive Narrative Incunabula（互动叙事摇篮）（177）
					2. Emergent Narrative（涌现叙事）（179）
				6. Dynamic Technology（动态技术）（180）
			6. The Cultural Layer（文化层）（182）
				1. Beyond Play（超越游戏）（182）
				2. Cultural Mechanics（文化机制）（184）
				3. Cultural Aesthetics（文化美学）（186）
				4. Cultural Narrative（文化叙事）（187）
				5. Cultural Technology（文化科技）（189）
				6. Authorized Transmedia Are Not Part of the Cultural Layer（授权的跨媒体不属于文化层）（190）
				7. The Cultural Impact of a Game（游戏的文化影响）（192）
					1. Manipulative Game Design（操控性游戏设计）（193）
					2. The Messages that Our Games—and Fans—Send（我们的游戏和粉丝传递的信息）（194）
			7. Acting Like a Designer（像设计师一样行事）（198）
				1. Iterative Design（迭代设计）（198）
					1. Analysis（分析）（200）
					2. Design（设计）（203）
					3. Implementation（执行）（206）
					4. Testing（测试）（208）
					5. Iterate, Iterate, Iterate, Iterate, Iterate, Iterate, Iterate!（迭代，迭代，迭代，迭代，迭代，迭代，迭代！）（209）
				2. Innovation（创新）（209）
				3. Brainstorming and Ideation（头脑风暴和构思）（211）
					1. Step 1: Expansion Phase（第  1  步：扩张阶段）（211）
					2. Step 2: Collection Phase（第  2  步：收集阶段）（213）
					3. Step 3: Collision Phase（第三步：碰撞阶段）（214）
					4. Step 4: Rating Phase（第四步：评级阶段）（215）
					5. Step 5: Discussion（第五步：讨论）（215）
				4. Changing Your Mind（改变你的想法）（216）
					1. As the Project Progresses, You’re More Locked In（随着项目的进展，你会更加锁定）（217）
				5. Scoping!（范围界定！）（220）
					1. Scope Management via Preproduction Deliverables（通过预生产可交付成果进行范围管理）（221）
			8. Design Goals（设计目标）（229）
				1. Design Goals: An Incomplete List（设计目标：不完整的列表）（229）
					1. Designer-Centric Goals（以设计师为中心的目标）（229）
					2. Player-Centric Goals（以玩家为中心的目标）（230）
				2. Designer-Centric Goals（以设计师为中心的目标）（231）
					1. Fortune（财富）（231）
					2. Fame（名气）（231）
					3. Community（社区）（233）
					4. Personal Expression and Communication（个人表达与沟通）（233）
					5. Greater Good（更大的善）（233）
					6. Becoming a Better Designer（成为更好的设计师）（234）
				3. Player-Centric Goals（以玩家为中心的目标）（235）
					1. Fun（乐趣）（235）
					2. Lusory Attitude（华丽的态度）（237）
					3. Flow（流动）（240）
					4. Structured Conflict（结构性冲突）（243）
					5. Empowerment（赋权）（245）
					6. Attention and Involvement（关注和参与）（248）
					7. Interesting Decisions（有趣的决定）（251）
					8. Experiential Understanding（体验式理解）（254）
			9. Paper Prototyping（纸质原型）（257）
				1. The Benefits of Paper Prototyping（纸质原型的好处）（257）
				2. Paper Prototyping Tools（纸质原型工具）（259）
				3. Paper Prototyping for Interfaces（界面纸质原型）（263）
				4. A Paper Prototype Example（纸质原型示例）（264）
					1. Game Concept — 2D Adventure Game Level（游戏概念——2D冒险游戏关卡）（264）
					2. Prototyping New Traversal Mechanics（制作新的遍历机制原型）（267）
					3. Playtesting（游戏测试）（270）
				5. Best Uses for Paper Prototyping（纸质原型的最佳用途）（271）
				6. Poor Uses for Paper Prototyping（纸质原型的不良用途）（273）
			10. Game Testing（游戏测试）（275）
				1. Why Playtest?（为什么要进行游戏测试？）（275）
				2. Being a Great Playtester Yourself（成为一名出色的游戏测试员）（276）
				3. The Circles of Playtesters（游戏测试者圈子）（277）
					1. The First Circle: You（第一圈：你）（278）
					2. The Second Circle: Trusted Friends（第二圈：值得信赖的朋友）（278）
					3. The Third Circle: Acquaintances and Others（第三圈：熟人及其他）（280）
					4. The Fourth Circle: The Internet（第四圈：互联网）（281）
				4. Methods of Playtesting（游戏测试方法）（281）
					1. Informal Individual Testing（非正式的个人测试）（281）
					2. Formal Group Testing（正式团体测试）（285）
					3. Formal Individual Testing（正式个人测试）（287）
					4. Online Playtesting（在线游戏测试）（292）
				5. Other Important Types of Testing（其他重要的测试类型）（295）
					1. Focus Testing（焦点测试）（295）
					2. Interest Polling（兴趣投票）（296）
					3. Usability Testing（可用性测试）（296）
					4. Quality Assurance (QA) Testing（质量保证  (QA)  测试）（296）
					5. Automated Testing（自动化测试）（297）
			11. Math and Game Balance（数学和游戏平衡）（299）
				1. The Meaning of Game Balance（游戏平衡的意义）（299）
				2. The Importance of Spreadsheets（电子表格的重要性）（300）
					1. The Choice of Google Sheets for This Book（本书选择的  Google  表格）（301）
				3. Examining Dice Probability with Sheets（用床单检查骰子概率）（303）
					1. Getting Started in Google Sheets（Google  表格入门）（303）
					2. Getting Started with Sheets（开始使用表格）（305）
					3. Naming the Document（命名文档）（307）
					4. Creating a Row of Numbers from 1 to 36（创建一行从  1  到  36  的数字）（308）
					5. Making the Row for Die A（为骰子  A  排好队）（310）
					6. Making the Row for Die B（为  Die  B  排好队）（312）
					7. Adding Clarity with Labels（使用标签增加清晰度）（314）
					8. Color Scale Conditional Formatting（色阶条件格式）（315）
					9. Summing the Results of the Two Dice（将两个骰子的结果相加）（317）
					10. Counting the Sums of Die Rolls（计算骰子的总数）（317）
					11. Counting All Possible Rolls（计算所有可能的卷数）（318）
					12. Conditional Formatting（条件格式）（320）
					13. Charting the Results（绘制结果图表）（320）
					14. Wrapping Up Our Intro to Sheets（总结我们对表格的介绍）（324）
				4. The Math of Probability（概率数学）（324）
				5. Randomizer Technologies in Paper Games（纸质游戏中的随机发生器技术）（331）
					1. Dice（骰子）（331）
					2. Spinners（纺纱机）（331）
					3. Decks of Cards（牌组）（333）
				6. Weighted Distributions（加权分布）（336）
				7. Weighted Probability in Google Sheets（Google  表格中的加权概率）（337）
				8. Permutations（排列）（339）
					1. Permutations with Repeating Elements（重复元素的排列）（340）
					2. Permutations with No Repeating Elements（没有重复元素的排列）（341）
				9. Using Sheets to Balance Weapons（使用床单来平衡武器）（341）
					1. Determining the Percent Chance for Each Shot（确定每次射击的百分比机会）（342）
					2. Calculating Average Damage（计算平均伤害）（344）
					3. Charting the Average Damage（绘制平均伤害图表）（346）
					4. Showing Overall Damage（显示整体损坏）（348）
					5. Duplicating the Weapon Data（复制武器数据）（349）
					6. Rebalancing the Weapons（重新平衡武器）（350）
					7. One Example of Balanced Values（平衡价值观的一个例子）（351）
				10. Positive and Negative Feedback（正反馈和负反馈）（353）
			12. Guiding the Player（引导玩家）（355）
				1. Direct Guidance（直接指导）（355）
					1. Methods of Direct Guidance（直接指导方法）（357）
				2. Indirect Guidance（间接指导）（359）
					1. Constraints（约束条件）（359）
					2. Goals（目标）（359）
					3. Physical Interface（物理接口）（360）
					4. Visual Design（视觉设计）（361）
					5. Audio Design（音频设计）（366）
					6. Player Avatar（玩家头像）（367）
					7. Non-Player Characters（非玩家角色）（367）
				3. Teaching New Skills and Concepts（教授新技能和概念）（369）
					1. Sequencing（测序）（370）
					2. Integration（一体化）（373）
			13. Puzzle Design（拼图设计）（375）
				1. Scott Kim on Puzzle Design（斯科特·金  (Scott  Kim)  谈拼图设计）（375）
					1. Defining Puzzle（定义谜题）（376）
					2. Genres of Puzzles（谜题类型）（378）
					3. The Four Major Reasons that People Play Puzzles（人们玩拼图的四个主要原因）（380）
					4. Modes of Thought Required by Puzzles（谜题所需的思维模式）（381）
					5. Kim’s Eight Steps of Digital Puzzle Design（Kim  的数字拼图设计八步）（384）
					6. Seven Goals of Effective Puzzle Design（有效谜题设计的七个目标）（386）
				2. The Steps of Solving a Puzzle（解决谜题的步骤）（387）
					1. Understanding the Goal（了解目标）（388）
					2. Exploration（勘探）（389）
					3. Insight（洞察力）（389）
					4. Attempt（试图）（389）
					5. Mastery（精通）（390）
				3. Puzzle Examples in Action Games（动作游戏中的谜题示例）（391）
					1. Sliding Blocks / Position Puzzles（滑块/位置拼图）（391）
					2. Physics Puzzles（物理谜题）（392）
					3. Chain Reaction（连锁反应）（392）
					4. Traversal（遍历）（392）
					5. Stealth（隐身）（393）
					6. Boss Fights（Boss战）（393）
					7. Dexterity and Timing（敏捷性和时机）（394）
				4. Designing and Developing Puzzle Games（设计和开发益智游戏）（395）
			14. The Agile Mentality（敏捷心态）（398）
				1. The Manifesto for Agile Software Development（敏捷软件开发宣言）（398）
				2. Scrum Methodology（Scrum  方法论）（400）
					1. The Scrum Team（Scrum  团队）（401）
					2. Product Backlog / Task List（产品待办事项/任务列表）（402）
					3. The Burndown Chart（燃尽图）（402）
					4. Daily Scrum Meetings（每日  Scrum  会议）（403）
					5. Releases and Sprints（发布和冲刺）（404）
				3. Burndown Chart Example（燃尽图示例）（405）
					1. Burndown Chart Example: Worksheets（燃尽图示例：工作表）（406）
					2. Worksheet—Main（工作表—主要）（408）
					3. Worksheet—Task Rank Chart（工作表—任务排名图）（417）
					4. Worksheet—Person Chart（工作表—人员图表）（419）
					5. Worksheet—Daily Scrum（工作表——每日 Scrum）（420）
				4. Creating Your Own Burndown Charts（创建您自己的燃尽图）（423）
			15. The Digital Game Industry（数字游戏产业）（425）
				1. About the Game Industry（关于游戏产业）（425）
					1. Entertainment Software Association Essential Facts（娱乐软件协会基本事实）（426）
					2. Conditions in the Industry（行业状况）（427）
				2. Game Education（游戏教育）（437）
					1. Should I Enroll in a Game Education Program?（我应该参加游戏教育计划吗？）（437）
					2. Which Game Education Program Should I Choose?（我应该选择哪个游戏教育项目？）（438）
				3. Getting Into the Industry（进入行业）（441）
					1. Meeting People in the Industry（会见业内人士）（441）
					2. Following Up（跟进）（444）
					3. Interviewing（面试）（445）
				4. Don’t Wait to Start Making Games!（不要等待开始制作游戏！）（449）
					1. Join a Project（加入项目）（449）
					2. Start Your Own Project（开始你自己的项目）（449）
		2. Programming C# in Unity（在  Unity  中进行  C#  编程）（455）
			1. Thinking in Digital Systems（数字系统思维）（456）
				1. Systems Thinking in Board Games（棋盘游戏中的系统思维）（456）
				2. An Exercise in Simple Instructions（简单说明的练习）（458）
					1. What This Means to Digital Programming（这对数字节目意味着什么）（459）
				3. Game Analysis: Apple Picker（游戏分析：苹果拾取器）（462）
					1. Apple Picker Basic Gameplay（苹果选择器基本游戏）（463）
					2. Apple Picker GameObjects（Apple  Picker游戏对象）（463）
					3. Apple Picker GameObject Action Lists（Apple  Picker游戏对象操作列表）（465）
					4. Apple Picker GameObject Flowcharts（Apple  Picker游戏对象流程图）（466）
			2. Introducing Unity HUB and The Unity Editor（Unity HUB 和 Unity 编辑器简介）（471）
				1. Downloading Unity（下载Unity）（471）
					1. Downloading and Installing Unity Hub（下载并安装  Unity  Hub）（472）
					2. Installing Unity 2020.3 LTS（安装  Unity  2020.3  LTS）（474）
				2. Introducing Our Development Environment（介绍我们的开发环境）（476）
					1. Why Choose Unity?（为什么选择Unity？）（478）
					2. Why Choose C#?（为什么选择  C#？）（480）
					3. On the Daunting Nature of Learning a Language（论学习语言的艰巨性）（480）
				3. Creating a Unity Account（创建  Unity  帐户）（485）
				4. Checking Out a Sample Project（查看示例项目）（485）
				5. Creating Your First Unity Project（创建您的第一个  Unity  项目）（486）
				6. Learning Your Way Around Unity（学习  Unity  的方法）（490）
				7. Setting Up the Unity Window Layout（设置  Unity  窗口布局）（492）
					1. Downloading the IGDPD Layout from the Website（从网站下载 IGDPD 布局）（492）
					2. Manually Arranging the IGDPD Layout（手动排列  IGDPD  布局）（493）
			3. Introducing Our Language: C#（介绍我们的语言：C#）（500）
				1. Understanding the Features of C#（了解  C#  的特性）（500）
					1. C# Is a Compiled Language（C#  是一种编译语言）（501）
					2. C# Is Managed Code（C#  是托管代码）（504）
					3. C# Is Statically Typed（C#  是静态类型的）（505）
					4. C# Is Function-Based（C#  是基于函数的）（506）
					5. C# Is Object-Oriented（C#  是面向对象的）（507）
					6. C# Can Be Data-Oriented（C#  可以是面向数据的）（509）
				2. Reading and Understanding C# Syntax（阅读和理解  C#  语法）（509）
			4. Hello World: Your First Program（你好世界：你的第一个程序）（514）
				1. Creating a New Project（创建一个新项目）（514）
				2. Making a New C# Script（制作新的  C#  脚本）（518）
					1. Start() Versus Update()（Start()  与  Update()）（526）
				3. Making Things More Interesting（让事情变得更有趣）（529）
					1. Making a Prefab（制作预制件）（532）
					2. Creating an Environment for the Cubes（为立方体创建环境）（539）
					3. Adding a Little Color（添加一点颜色）（543）
			5. Variables and Components（变量和组件）（546）
				1. Introducing Variables（引入变量）（546）
				2. Statically Typed Variables in C#（C# 中的静态类型变量）（547）
					1. Declaring and Defining Variables in C#（在  C#  中声明和定义变量）（548）
					2. Declaration Before Definition（先声明后定义）（548）
				3. Important C# Variable Types（重要的  C#  变量类型）（549）
					1. bool: A 1-bit True or False Value（bool：  1  位  True  或  False  值）（549）
					2. int: A 32-bit Integer（int：  32  位整数）（549）
					3. float: A 32-bit Decimal Number（float：  32  位十进制数）（550）
					4. char: A 16-bit Single Character（char：  16  位单个字符）（551）
					5. string: A Series of 16-bit Characters（string：一系列  16  位字符）（551）
					6. class: The Definition of a New Variable Type（class：新变量类型的定义）（553）
				4. The Scope of Variables（变量的范围）（553）
				5. Naming Conventions（命名约定）（553）
				6. Important Unity Variable Types（重要的  Unity  变量类型）（554）
					1. Vector3: A Collection of Three Floats（Vector3：三个浮点的集合）（558）
					2. Color: A Color with Transparency Information（颜色：带有透明度信息的颜色）（559）
					3. Quaternion: Rotation Information（四元数：旋转信息）（561）
					4. Mathf: A Library of Mathematical Functions（Mathf：数学函数库）（563）
					5. Screen: Information about the Display（屏幕：有关显示屏的信息）（564）
					6. Application: Information about the Unity context（应用程序：有关  Unity  上下文的信息）（564）
					7. SystemInfo: Information about the Device（SystemInfo：有关设备的信息）（565）
					8. GameObject: The Type of Any Object in the Scene（GameObject：场景中任何对象的类型）（566）
				7. Unity GameObjects and Components（Unity  游戏对象和组件）（567）
					1. Transform: Position, Rotation, and Scale（变换：位置、旋转和缩放）（568）
					2. MeshFilter: The Model That Is Rendered（MeshFilter：渲染的模型）（569）
					3. Renderer: Draws the Model on the Screen（渲染器：在屏幕上绘制模型）（569）
					4. Collider: The Physical Presence of the GameObject（对撞机：游戏对象的物理存在）（569）
					5. Rigidbody: The Physics Simulation（Rigidbody：物理模拟）（571）
					6. Script: The C# Scripts That You Write（脚本：您编写的  C#  脚本）（571）
			6. Boolean Operations and Conditionals（布尔运算和条件）（573）
				1. Booleans（布尔值）（573）
					1. Boolean Operations（布尔运算）（574）
					2. Combination of Boolean Operations（布尔运算的组合）（578）
					3. Logical Equivalence of Boolean Operations（布尔运算的逻辑等价）（579）
				2. Comparison Operators（比较运算符）（580）
					1. == (Is Equal To)（==（等于））（580）
					2. != (Not Equal To)（!=（不等于））（585）
					3. > (Greater Than) and < (Less Than)（>（大于）和  <（小于））（585）
					4. >= (Greater Than or Equal To) and <= (Less Than or Equal To)（>=（大于或等于）和 <=（小于或等于））（586）
				3. Conditional Statements（条件语句）（587）
					1. if Statements（if语句）（587）
					4. switch Statements（switch语句）（592）
			7. Loops（循环）（596）
				1. Types of Loops（循环的类型）（596）
				2. Set Up a Project（建立一个项目）（597）
				3. while Loops（while  循环）（598）
					1. The Danger of Infinite Loops（无限循环的危险）（598）
					2. A More Useful while Loop（更有用的while循环）（601）
				4. do…while Loops（do...while  循环）（604）
				5. for Loops（for  循环）（605）
					1. Using the Decrement Operator in an Iteration Clause（在迭代子句中使用减量运算符）（608）
					2. Any of the Three for Clauses Can Be Empty（三个  for  子句中的任何一个都可以为空）（609）
				6. foreach Loops（foreach  循环）（610）
				7. Jump Statements within Loops（循环内的跳转语句）（611）
					1. Using break Statements to Exit Any Kind of Loop（使用break语句退出任何类型的循环）（612）
					2. Skipping the Rest of an Iteration with continue（使用continue跳过剩余的迭代）（617）
			8. Collections in C#（C#  中的集合）（620）
				1. C# Collections（C#  集合）（620）
					1. Commonly Used Collections（常用集合）（621）
				2. Using Generic Collections（使用通用集合）（626）
				3. List< T>（列表< T>）（627）
				4. Dictionary<Tkey, TValue>（字典<Tkey,  TValue>）（632）
				5. Array（数组）（637）
					1. Empty Elements in the Middle of an Array（数组中间的空元素）（639）
					2. Skipping null Array Elements with foreach（使用foreach跳过空数组元素）（640）
				6. Multidimensional Arrays（多维数组）（643）
				7. Jagged Arrays（锯⻮状阵列）（649）
					1. Using for Loops Instead of foreach for Jagged Arrays（使用 for 循环代替 foreach 来处理锯齿状数组）（652）
				8. Jagged List< T>s（锯⻮状列表< T>）（653）
				9. Choosing Whether to Use an Array or List（选择使用数组还是列表）（655）
			9. Functions and parameters（功能及参数）（661）
				1. Setting Up the Function Examples Project（设置函数示例项目）（661）
				2. Definition of a Function（函数的定义）（662）
				3. What Happens When You Call a Function?（调用函数时会发生什么？）（665）
				4. Function Parameters and Arguments（函数参数和参数）（667）
				5. Returning Values（返回值）（670）
				6. Returning void（返回无效）（671）
				7. Function Naming Conventions（函数命名约定）（672）
				8. Why Use Functions?（为什么使用函数？）（673）
				9. Function Overloading（函数重载）（676）
				10. Optional Parameters（可选参数）（678）
				11. The params Keyword（参数关键字）（679）
				12. Recursive Functions（递归函数）（682）
			10. Debugging（调试）（686）
				1. Getting Started with Debugging（调试入门）（686）
					1. Compile-Time Bugs（编译时错误）（688）
					2. Attaching and Removing Scripts（添加和删除脚本）（695）
					3. Runtime Errors（运行时错误）（698）
					4. Unity Errors (That Aren’t Your Fault)（Unity  错误（那不是你的错））（702）
				2. Stepping Through Code with the Debugger（使用调试器单步执行代码）（702）
					1. Enabling Debugging in Unity 2020（在  Unity  2020  中启用调试）（707）
					2. Attaching the Debugger to Unity（将调试器附加到  Unity）（708）
					3. Using the Debugger to Examine code（使用调试器检查代码）（713）
			11. Classes（类）（722）
				1. Understanding Classes（了解类）（722）
					1. The Anatomy of a Class (and of Most C# Scripts)（类（以及大多数  C#  脚本）的剖析）（723）
					2. Setting Up the Enemy Class Sample Project（设置敌人类示例项目）（725）
					3. Creating Properties—Methods That Work Like Fields（创建属性——像字段一样工作的方法）（728）
					4. MonoBehaviour Subclasses Are GameObject Components（MonoBehaviour 子类是 GameObject 组件）（733）
				2. Class Inheritance（类继承）（738）
					1. Implementing the Enemy Class on a GameObject（在游戏对象上实现敌人类）（739）
					2. Understanding Superclasses and Subclasses（了解超类和子类）（741）
			12. Object-Oriented Thinking（面向对象的思维）（746）
				1. The Object-Oriented Metaphor（面向对象的隐喻）（746）
					1. Simulating a Flock of Birds in a Monolithic Way（以整体方式模拟一群鸟）（746）
					2. Simulating a Flock of Birds Using OOP and Boids（使用  OOP  和  Boids  模拟鸟群）（748）
				2. An Object-Oriented Boids Implementation（面向对象的  Boids  实现）（749）
					1. Making a Simple Boid Model（制作一个简单的身体模型）（750）
					2. Attractor GameObject（吸引子游戏对象）（756）
					3. The C# Scripts（C#  脚本）（758）
			13. Data-Oriented Design（面向数据的设计）（783）
				1. The Theory of Data-Oriented Design（面向数据的设计理论）（783）
					1. Realities of Modern Computer Hardware（现代计算机硬件的现实）（784）
					2. Data Locality and Access Speed（数据局部性和访问速度）（786）
					3. Cache Lines（缓存线）（787）
					4. The Issues with Object-Oriented Programming（面向对象编程的问题）（788）
					5. Unity’s Data-Oriented Tech Stack（Unity  面向数据的技术堆栈）（790）
				2. DOTS Tutorial and Example（DOTS  教程和示例）（791）
					1. Setting Up the Unity Project（设置  Unity  项目）（792）
						1. Setting the Scene（设置场景）（795）
						2. Object-Oriented Image Creation（面向对象的图像创建）（797）
						3. Data-Oriented Image Creation（面向数据的图像创建）（807）
						4. Turning Noise into an Archipelago（将噪音变成群岛）（819）
						5. Entity Component Systems (ECS)（实体组件系统  (ECS)）（831）
					2. The Future of Unity DOTS（Unity  DOTS  的未来）（837）
		3. Game Prototype Tutorials（游戏原型教程）（840）
			1. Apple Picker（苹果采摘器）（841）
				1. What You Will Learn（你将学到什么）（841）
				2. The Apple Picker Prototype（苹果采摘器原型）（841）
				3. The Purpose of a Digital Prototype（数字原型的目的）（842）
				4. Preparing（准备中）（843）
					1. Getting Started: Art Assets（入门：艺术资产）（844）
					2. Camera Setup（相机设置）（853）
					3. Game Panel Settings（游戏面板设置）（856）
				5. Coding the Apple Picker Prototype（编写Apple  Picker原型）（857）
					1. Applying AppleTree Instance Overrides to the AppleTree Prefab（将 AppleTree 实例覆盖应用于 AppleTree 预制件）（862）
					2. Basic Movement（基本动作）（863）
					3. Changing Direction（改变方向）（866）
					4. Changing Direction Randomly（随机改变方向）（867）
					5. Dropping Apples（掉落苹果）（869）
					6. Setting Physics Layers（设置物理层）（871）
					7. Stopping Apples If They Fall Too Far（如果苹果掉得太远就阻止它们）（874）
					8. Instantiating the Baskets（实例化篮子）（876）
					9. Moving the Baskets with the Mouse（用鼠标移动篮子）（877）
					10. Catching Apples（摘苹果）（879）
					11. Tuning AppleTree (Script) Variables（调整  AppleTree（脚本）变量）（880）
				6. GUI and Game Management（GUI  和游戏管理）（882）
					1. HighScore and ScoreCounter Texts（HighScore  和  ScoreCounter  文本）（882）
					2. Accumulating Points for Each Caught Apple（每抓到一个苹果即可累积积分）（885）
					3. Notifying ApplePicker That an Apple Was Missed（通知  ApplePicker  丢失了一个苹果）（889）
					4. Adding a High Score（添加高分）（893）
			2. Mission Demolition（任务拆除）（901）
				1. What You Will Learn（你将学到什么）（901）
				2. The Mission Demolition Prototype（任务拆除原型）（902）
				3. Getting Started: Mission Demolition（入门：任务拆除）（902）
				4. Game Prototype Concept（游戏原型概念）（903）
				5. Art Assets（艺术资产）（904）
					1. Ground（地面）（904）
					2. Directional Light（定向光）（904）
					3. Camera Settings（相机设置）（904）
					4. The Slingshot（弹弓）（906）
					5. Projectile（弹丸）（909）
				6. Coding the Prototype（编写原型代码）（910）
					1. Creating the Slingshot Class（创建  Slingshot  类）（910）
					2. Making a Follow Camera（制作跟随相机）（922）
					3. Providing Vection and a Sense of Speed（提供矢量和速度感）（930）
					4. Organizing the Project Pane（组织项目窗格）（935）
					5. Building the Castle（建造城堡）（936）
					6. Fixing Rigidbody’s Insomnia（修复  Rigidbody  的失眠问题）（944）
					7. Adding a ProjectileLine Trail（添加  ProjectileLine  轨迹）（947）
					8. Hitting the Goal（击中目标）（953）
				7. From Prototype to First Playable（从原型到首次可玩）（955）
					1. Adding More Castles（添加更多城堡）（955）
					2. Adding UI to the Scene（将  UI  添加到场景中）（956）
					3. Adding More Game Management（添加更多游戏管理）（958）
					4. Showing Different Views of the Level（显示关卡的不同视图）（965）
			3. Space SHMUP – Part 1（太空  SHMUP  –  第  1  部分）（973）
				1. What You Will Learn（你将学到什么）（973）
				2. Getting Started: Space SHMUP（入门：太空  SHMUP）（973）
					1. Importing a Unity Asset Package（导入Unity资源包）（975）
				3. Setting the Scene（设置场景）（976）
				4. Making the Hero Ship（制作英雄船）（977）
					1. The Hero Update() Method（Hero  Update()  方法）（979）
					2. The Hero Shield（英雄之盾）（983）
					3. Keeping _Hero on Screen（将  _Hero  保留在屏幕上）（985）
				5. Adding Some Enemies（添加一些敌人）（990）
					1. The Enemy C# Script（敌人的  C#  脚本）（991）
				6. Spawning Enemies at Random（随机生成敌人）（1005）
				7. Setting Tags, Layers, and Physics（设置标签、图层和物理）（1008）
					1. Assigning the Proper Layers to GameObjects（为游戏对象分配适当的层）（1010）
				8. Making the Enemies Damage the Player（让敌人伤害玩家）（1011）
				9. Restarting the Game（重新开始游戏）（1015）
				10. Shooting (Finally)（射击（最后））（1018）
					1. ProjectileHero, the Hero’s Bullet（ProjectileHero，英雄的子弹）（1018）
					2. Giving _Hero the Ability to Shoot（赋予  _Hero  射击能力）（1020）
					3. Scripting the ProjectileHero（编写  ProjectileHero  脚本）（1021）
					4. Allowing Projectiles to Destroy Enemies（允许射弹摧毁敌人）（1021）
			4. Space SHMUP – Part 2（太空  SHMUP  –  第  2  部分）（1023）
				1. What You Will Learn（你将学到什么）（1023）
				2. Getting Started: Space SHMUP – Part 2（入门：  Space  SHMUP  –  第  2  部分）（1024）
				3. Enemy to Enemy_0（敌人对敌人_0）（1025）
				4. Programming Other Enemies（对其他敌人进行编程）（1027）
					1. Enemy_1（敌人_1）（1027）
					2. When Is BoundsCheck bndCheck Being private a Problem?（BoundsCheck bndCheck 私有化何时会出现问题？）（1031）
					3. Preparing for the Other Enemies（为其他敌人做好准备）（1034）
					4. Enemy_2（敌人_2）（1034）
					5. Enemy_3（敌人_3）（1041）
					6. Saving Enemy_4 for Later（保存  Enemy_4  供以后使用）（1047）
				5. Shooting Revisited（重温拍摄）（1047）
					1. The eWeaponType Enum（eWeaponType  枚举）（1048）
					2. The Serializable WeaponDefinition Class（可序列化的  WeaponDefinition  类）（1049）
					3. A Generic Dictionary for WeaponDefinitions（武器定义通用词典）（1053）
					4. Using a Delegate Event to Fire（使用委托事件来触发）（1057）
					5. Creating a Weapon GameObject to Fire Projectiles（创建武器游戏对象来发射射弹）（1059）
					6. Revising the Enemy OnCollisionEnter Method（修改  Enemy  OnCollisionEnter  方法）（1066）
				6. Showing Enemy Damage（显示敌人伤害）（1068）
					1. Adding GetAllMaterials to the Utils Script（将  GetAllMaterials  添加到  Utils  脚本）（1068）
					2. Using GetAllMaterials to Make the Enemy Blink Red（使用  GetAllMaterials  让敌人闪烁红光）（1069）
				7. Adding PowerUps and Boosting Weapons（添加  PowerUps  和增强武器）（1072）
					1. Artwork for the PowerUp GameObject（PowerUp  游戏对象的艺术作品）（1073）
					2. PowerUp Code（通电代码）（1075）
				8. Race Conditions & Script Execution Order（竞争条件和脚本执行顺序）（1084）
				9. Making Enemies Drop PowerUps（让敌人掉落能量）（1087）
				10. Enemy_4 — A More Complex Enemy（Enemy_4 — 更复杂的敌人）（1091）
					1. Enemy_4 Prefab Modifications（Enemy_4  预制件修改）（1091）
					2. Creating the EnemyShield Script（创建  EnemyShield  脚本）（1093）
					3. Coding Enemy_4 to Use EnemyShield（对  Enemy_4  进行编码以使用  EnemyShield）（1097）
					4. Movement of Enemy_4（敌人的移动_4）（1101）
				11. Tuning Settings for the Game Entities（调整游戏实体的设置）（1103）
				12. Adding a Scrolling Starfield Background（添加滚动星空背景）（1106）
			5. Prospector Solitaire – Part 1（探矿者纸牌  –  第  1  部分）（1111）
				1. What You Will Learn（你将学到什么）（1111）
				2. The Prospector Game（勘探者游戏）（1111）
					1. Prospector Initial Layout（探矿者初始布局）（1112）
					2. Prospector Rules（探矿者规则）（1113）
					3. Example of Play（游戏示例）（1113）
				3. Getting Started: Prospector Solitaire（入门：探矿者纸牌）（1114）
				4. Build Settings（构建设置）（1115）
					1. Installing the WebGL Module（安装WebGL模块）（1116）
					2. Switching to the WebGL Build Platform（切换到  WebGL  构建平台）（1117）
					3. Including __Prospector_Scene_0 in Any Builds（在任何构建中包含 __Prospector_Scene_0）（1119）
				5. Setting Up the Unity Window Layout（设置  Unity  窗口布局）（1119）
				6. Setting Up the Camera and Game Pane（设置相机和游戏面板）（1119）
				7. Importing Images as Sprites（将图像导入为精灵）（1121）
					1. Slicing the Rank Image into Multiple Sprites（将排名图像分割成多个精灵）（1123）
				8. Constructing Cards from Sprites（从精灵构建卡片）（1125）
					1. Making Use of JSON Through Code（通过代码使用  JSON）（1127）
					2. Gathering References to the Deck Sprites（收集对牌组精灵的引用）（1132）
					3. Creating Prefab GameObjects for Sprites and Cards（为精灵和卡片创建预制游戏对象）（1134）
					4. Building the Cards Through Code（通过代码构建卡片）（1136）
					5. Building the Cards from Sprites（从精灵构建卡片）（1145）
					6. Shuffling the Cards（洗牌）（1153）
				9. Implementing Prospector in Code（在代码中实施Prospector）（1154）
					1. Parsing the Mine Tableau Layout from JSON（从  JSON  解析  Mine  Tableau  布局）（1154）
					2. The Prospector Class (Finally!)（勘探者级（最后！））（1162）
				10. Implementing Game Logic（实现游戏逻辑）（1176）
					1. Making Cards Clickable（使卡片可点击）（1176）
					2. Matching Cards from the Mine（矿井中的匹配卡）（1178）
			6. Prospector Solitaire – Part 2（探矿者纸牌–  第  2  部分）（1184）
				1. What You Will Learn（你将学到什么）（1184）
				2. Getting Started: Prospector – Part 2（入门：探矿者‑  第  2  部分）（1185）
				3. Additional Prospector Game Elements（额外的勘探者游戏元素）（1186）
					1. Managing Prospector Rounds（管理探矿者回合）（1187）
					2. Adding Scoring to Prospector（为Prospector添加评分）（1190）
					3. The Prospector Background Image（探矿者背景图片）（1199）
				4. Adding GUI Elements to Display the Score（添加  GUI  元素来显示分数）（1202）
					1. The BézierMover Class（BézierMover  类）（1203）
					2. The FloatingScore Game Object and Canvas（FloatingScore  游戏对象和画布）（1208）
					3. Creating the ScoreBoard Class and GameObject（创建记分板类和游戏对象）（1218）
					4. Updating ScoreManager（更新分数管理器）（1220）
					5. Adding a Pause Between Rounds（在回合之间添加暂停）（1226）
					6. Giving the Player Feedback on Their Score（向玩家提供分数反馈）（1227）
				5. Building and Running Your WebGL Build（构建并运行您的  WebGL  构建）（1234）
			7. Dungeon Delver – Part 1（地牢探索者–  第  1  部分）（1241）
				1. What You Will Learn（你将学到什么）（1241）
				2. The Dungeon Delver Game（地牢探索者游戏）（1241）
					1. Component-Based Design（基于组件的设计）（1242）
				3. Getting Started: Dungeon Delver（入门：地下城探索者）（1243）
				4. Setting Up the Cameras（设置相机）（1244）
					1. Game Pane（游戏面板）（1245）
					2. Main Camera（主摄像头）（1246）
					3. GUI Camera（图形化相机）（1246）
				5. Understanding the Dungeon Data（了解地下城数据）（1247）
					1. Preparing DelverTiles（准备  DelverTiles）（1247）
					2. The DelverLevel_Eagle Text File（DelverLevel_Eagle  文本文件）（1249）
				6. Showing the Map with a Unity Tilemap（使用  Unity  Tilemap  显示地图）（1252）
					1. Setting Up Tiles and the Tilemap_Visual（设置图块和 Tilemap_Visual）（1252）
					2. Generating a Tilemap from Data（从数据生成瓦片地图）（1253）
				7. Adding the Hero（添加英雄）（1263）
					1. The Dray Sprite Naming Convention（Dray  Sprite  命名约定）（1263）
					2. Your First Animation（你的第一部动画）（1264）
					3. Tweaking the Dray_Walk_0 Animation（调整  Dray_Walk_0  动画）（1269）
					4. Adding Additional Dray Animation（添加额外的拖曳动画）（1269）
					5. Moving Dray（移动板车）（1270）
					6. A More Interesting Movement Approach（更有趣的运动方式）（1271）
					7. A Better Way to Handle Input Keys（处理输入键的更好方法）（1272）
					8. Animating Dray for Walking（步行动画拖车）（1274）
				8. Giving Dray an Attack Animation（为德雷提供攻击动画）（1275）
					1. Generating the Attack Pose Animations（生成攻击姿势动画）（1275）
					2. Coding the Attack Pose Animations（编写攻击姿势动画）（1275）
				9. Dray’s Sword（德雷之剑）（1278）
				10. Programmatic Collision in Unity Tilemap（Unity  Tilemap  中的编程碰撞）（1280）
					1. Understanding the CollisionTiles Sprites（了解  CollisionTiles  精灵）（1281）
					2. Setting Up Collision Tiles and the Tilemap_Collision（设置碰撞图块和  Tilemap_Collision）（1282）
					3. Programmatically Filling the Tilemap_Collision（以编程方式填充  Tilemap_Collision）（1284）
					4. Adding a Collider to Dray（将碰撞器添加到  Dray）（1288）
				11. The InRoom Script（室内脚本）（1288）
				12. Enemy: Skeletos（敌人：骷髅）（1290）
					1. Skeletos Animation（骷髅动画）（1290）
					2. The Enemy Base Class（敌人基类）（1291）
					3. The Skeletos Subclass of Enemy（敌人的骷髅子类）（1292）
				13. Keeping GameObjects in the Room（将游戏对象保留在房间中）（1293）
				14. Aligning to the Grid（与网格对齐）（1296）
					1. The IFacingMover Interface（IFaceingMover  界面）（1297）
					2. The GridMove Script（网格移动脚本）（1302）
				15. Moving from Room to Room（从一个房间移动到另一个房间）（1304）
				16. Making the Camera Follow Dray（让相机跟随拖车）（1308）
			8. Dungeon Delver – Part 2（地牢探索者–  第  2  部分）（1312）
				1. What You Will Learn（你将学到什么）（1312）
				2. Getting Started: Dungeon Delver — Part 2（入门：地下城探索者 — 第 2 部分）（1312）
				3. Dungeon Delver — Part 2 Overview（地下城探索者 — 第 2 部分概述）（1313）
				4. Implementing TileSwaps（实施  TileSwaps）（1314）
					1. The TileSwapManager Script（TileSwapManager  脚本）（1315）
					2. Setting Up TileSwaps for Doors（为门设置  TileSwaps）（1318）
				5. Swapping in LockedDoor GameObjects（交换  LockedDoor  游戏对象）（1321）
					1. The ISwappable Interface（可交换接口）（1323）
					2. Making Skeletos and LockedDoor Prefabs（制作骨架和  LockedDoor  预制件）（1325）
					3. Using ISwappable.Init()（使用  ISwappable.Init()）（1325）
				6. Implementing Keys and Unlocking Doors（使用钥匙和开门）（1327）
					1. The IKeyMaster（钥匙大师）（1327）
					2. Locked Doors That Require Keys（锁着的门需要钥匙）（1329）
				7. Adding GUI to Track Key Count and Health（添加  GUI  来跟踪按键计数和运行状况）（1335）
					1. Adding Health to Dray（为拖车添加生命值）（1337）
					2. Connecting the GUI to Dray（将  GUI  连接到  Dray）（1338）
				8. Enabling Enemies to Damage Dray（使敌人能够损坏战车）（1341）
					1. Implementing DamageEffect（实施伤害效果）（1341）
					2. Modifying the Dray Class to Take Damage（修改  Dray  类以承受伤害）（1342）
				9. Making Dray’s Attack Damage Enemies（让德雷的攻击伤害敌人）（1346）
				10. Modifying Enemy to Take Damage（修改敌人以承受伤害）（1347）
				11. Picking Up Items（拾取物品）（1351）
				12. Enemies Dropping Items on Death（敌人死亡时会掉落物品）（1354）
					1. Dropping Keys（掉落钥匙）（1354）
					2. Dropping Randomized Items（丢弃随机物品）（1356）
				13. Implementing a New Dungeon — The Hat（实施一个新的地下城——帽子）（1359）
					1. Preparing the Scene（准备场景）（1359）
					2. Setting Up TileSwaps for Enemies and Items（为敌人和物品设置  TileSwaps）（1359）
				14. Implementing a Grappler（实施抓斗器）（1363）
					1. The IGadget Interface（IGadget  界面）（1363）
					2. Understanding How Dray Works with IGadgets（了解  Dray  如何与  IGadgets  配合使用）（1365）
					3. Enabling Dray to Use IGadgets（启用  Dray  使用  IGadgets）（1365）
					4. Building the Grappler（建造抓斗者）（1370）
					5. Starting with Secondary Grappler Abilities（从次要格斗者能力开始）（1375）
					6. Adding Tilemap_GrapTiles for Grappler Collisions（为  Grappler  碰撞添加  Tilemap_GrapTiles）（1384）
					7. Enabling the Grappler to Pull Dray to It（使抓斗能够将拖车拉向它）（1388）
					8. Testing the Grappler（测试抓斗）（1395）
					9. Implementing the Grappler PickUp（实施  Grappler  PickUp）（1396）
		4. Next Steps（下一步）（1401）
			1. Coding Challenges（编码挑战）（1402）
				1. What Is a Coding Challenge?（什么是编码挑战？）（1402）
				2. Getting Started on a Coding Challenge（开始编码挑战）（1404）
				3. Filling in the Blanks（填空）（1406）
				4. How to Approach Each Challenge（如何应对每项挑战）（1409）
			2. Beyond this Book（超越本书）（1412）
				1. Continue to Learn Unity Development（继续学习Unity开发）（1412）
				2. Build a Classic Game（打造经典游戏）（1413）
				3. Start a Small Game Project or Prototype（启动一个小型游戏项目或原型）（1414）
				4. Make Games for Lifelong Enrichment（制作让终生受益的游戏）（1415）
				5. Consider Going to School for GameDev（考虑去游戏开发学校）（1415）
				6. Explore Advanced Game Design（探索高级游戏设计）（1416）
				7. Finally, Drop Me a Line（最后，给我留言）（1417）
	7. Building a Game with Unity and Blender（使用 Unity 和 Blender 构建游戏）
		1. Creating Your Game Concept（创建你的游戏概念）（20）
			1. Job roles in game development（游戏开发中的工作角色）（20）
			2. Gameplay design（游戏玩法设计）（21）
				1. Starting point（初始点）（22）
				2. Choosing a game genre（选择游戏类型）（22）
				3. Game mechanics（游戏机制）（23）
				4. Level design（关卡设计）（25）
				5. Rapid prototyping（快速原型制作）（26）
			3. Writing the game's story（编写游戏故事）（26）
			4. Choosing a visual style（选择视觉风格）（27）
			5. The characters concept（人物概念）（27）
			6. The environment concept（环境理念）（31）
			7. Summary（概括）（32）
		2. Creating Characters（创建角色）（34）
			1. Downloading Blender（下载Blender）（34）
				1. A brief history of Blender（Blender  简史）（35）
				2. The basic user interface of Blender（Blender  的基本用户界面）（35）
			2. Creating the monster's 3D model（创建怪物的  3D  模型）（40）
			3. Unwrapping the monster's UV map（打开怪物的  UV  贴图）（56）
			4. Creating the monster's texture（创建怪物的纹理）（62）
			5. Creating the player character's 3D model（创建玩家角色的  3D  模型）（67）
			6. Unwrapping the player character's UV map（展开玩家角色的  UV  贴图）（80）
			7. Summary（概括）（83）
		3. Animating Your Characters（为你的角色制作动画）（84）
			1. What is character rigging?（什么是角色绑定？）（65）
			2. Creating a monster's armature（创建怪物的骨架）（85）
			3. Creating the player character's armature（创建玩家角色的骨架）（90）
			4. Weight painting（重量画）（96）
			5. Animating characters（动画角色）（99）
			6. The 12 basic principles of animation（动画的12条基本原则）（103）
			7. Summary（概括）（105）
		4. Creating the Environment（创造环境）（106）
			1. Building terrain and wall models（构建地形和墙体模型）（106）
			2. Building rock models（建造岩石模型）（113）
			3. Creating rock and wall textures（创建岩石和墙壁纹理）（115）
			4. Building grass models（建立草地模型）（117）
			5. Creating the grass texture（创建草纹理）（119）
			6. Summary（概括）（121）
		5. Integrating Your Assets into the Game（将您的资产整合到游戏中）（122）
			1. Basic user interface of Unity（Unity的基本用户界面）（123）
			2. Importing environment assets（导入环境资产）（124）
				1. Introducing prefabs（预制件简介）（127）
				2. Setting up the terrain（设置地形）（127）
				3. Setting up water surfaces（设置水面）（130）
				4. Setting up foliage（设置树叶）（132）
				5. Setting up environment lighting（设置环境照明）（134）
				6. Optimizing the scene with Occlusion Culling（使用遮挡剔除优化场景）（137）
			3. Importing character assets（导入角色资源）（139）
			4. Summary（概括）（146）
		6. Developing the Game Structure（开发游戏结构）（148）
			1. Introduction to game structure design（游戏结构设计简介）（148）
			2. Planning the game flow（规划游戏流程）（149）
			3. Designing the user interface structure（设计用户界面结构）（156）
			4. Player inputs and character movements（玩家输入和角色动作）（167）
			5. Creating basic artificial intelligence（创建基础人工智能）（183）
			6. Summary（概括）（189）
		7. Creating Levels and Game Progression（创建关卡和游戏进程）（190）
			1. Creating character attributes（创建角色属性）（190）
			2. Adding in-game items and power-ups（添加游戏内物品和能量提升）（192）
			3. Improving enemy AI（改善敌人AI）（197）
			4. Adding save points（添加保存点）（199）
			5. Summary（概括）（208）
		8. Post-Production and Visual FX（后期制作和视觉效果）（210）
			1. A basic particle system（基本粒子系统）（210）
			2. Mist particles（雾粒）（217）
			3. Torch fire（火炬火）（220）
			4. Image FX（图像特效）（223）
			5. Quality settings（质量设置）（227）
			6. Summary（概括）（230）
		9. Deploying the Game（部署游戏）（232）
			1. Build settings（构建设置）（232）
				1. Shared settings（共享设置）（234）
				2. The webplayer（网络播放器）（234）
				3. PC, Mac, and Linux standalone（PC、Mac  和  Linux  独立版）（235）
				4. iOS（235）
				5. Android（235）
				6. WebGL（235）
					1. Optimization level（优化级别）（236）
			2. Player Settings（播放器设置）（238）
				1. Cursor hotspot（光标热点）（240）
			3. Summary（概括）（241）
11. UnrealEngine
	1. Learning Unreal Engine Game Development（学习虚幻引擎游戏开发）
		1. An Overview of Unreal Engine（虚幻引擎概述）（22）
			1. What goes into a game?（游戏中有什么内容？）（22）
			2. What is a game engine?（什么是游戏引擎？）（23）
			3. The history of Unreal Engine（虚幻引擎的历史）（23）
			4. Game development（游戏开发）（25）
				1. Artists（艺术家）（25）
				2. Cinematic creators（电影创作者）（25）
				3. Sound designers（声音设计师）（25）
				4. Game designers（游戏设计师）（26）
				5. Programmers（程序员）（26）
			5. The components of Unreal Engine 4（虚幻引擎 4 的组件）（26）
				1. The sound engine（声音引擎）（26）
				2. The physics engine（物理引擎）（27）
				3. The graphics engine（图形引擎）（27）
				4. Input and the Gameplay framework（输入和游戏框架）（27）
				5. Light and shadow（光与阴影）（28）
				6. Post-process effects（后期处理效果）（29）
				7. Artificial intelligence（人工智能）（29）
				8. Online and multiplatform capabilities（在线和多平台功能）（30）
			6. Unreal Engine and its powerful editors（虚幻引擎及其强大的编辑器）（30）
				1. Unreal Editor（虚幻编辑器）（30）
				2. Material Editor（材质编辑器）（31）
					1. The Cascade particle system（级联粒子系统）（31）
					2. The Persona skeletal mesh animation（Persona 骨骼网格动画）（32）
					3. Landscape – building large outdoor worlds and foliage（景观——建造大型户外世界和树叶）（33）
				3. Sound Cue Editor（声音提示编辑器）（33）
				4. Matinee Editor（日场编辑）（33）
				5. The Blueprint visual scripting system（Blueprint 可视化脚本系统）（34）
			7. Unreal programming（虚幻编程）（35）
				1. Unreal objects（虚幻的物体）（36）
			8. A beginner's guide to the Unreal Editor（虚幻编辑器初学者指南）（36）
				1. The start menu（开始菜单）（36）
				2. Project Browser（项目浏览器）（37）
				3. Content Browser（内容浏览器）（37）
				4. Toolbar（工具栏）（38）
				5. Viewport（视口）（39）
				6. Scene Outliner（场景大纲）（39）
				7. Modes（模式）（40）
		2. Creating Your First Level（创建你的第一个关卡）（42）
			1. Exploring preconfigured levels（探索预先配置的级别）（42）
			2. Creating a new project（创建一个新项目）（43）
			3. Navigating the viewport（浏览视口）（45）
				1. Views（意见）（45）
				2. Control keys（控制键）（46）
			4. Creating a level from a new blank map（从新的空白地图创建关卡）（48）
			5. Creating the ground using the BSP Box brush（使用 BSP Box 笔刷创建地面）（50）
				1. Useful tip – selecting an object easily（有用的提示 – 轻松选择对象）（54）
				2. Useful tip – changing View Mode to aid visuals（有用的提示 - 更改视图模式以辅助视觉效果）（55）
			6. Adding light to a level（向关卡添加光线）（55）
				1. Useful tip – positioning objects in a level（有用的提示 - 在关卡中放置对象）（57）
			7. Adding the sky to a level（将天空添加到关卡中）（57）
			8. Adding Player Start（添加玩家开始）（57）
				1. Useful tip – rotating objects in a level（有用的提示 - 在关卡中旋转对象）（60）
			9. Viewing a level that's been created（查看已创建的关卡）（61）
			10. Saving a level（保存一个关卡）（62）
			11. Configuring a map as a start level（将地图配置为起始关卡）（63）
			12. Adding material to the ground（向地面添加材料）（63）
			13. Adding a wall（添加一堵墙）（64）
			14. Duplicating a wall（复制一面墙）（65）
			15. Creating an opening for a door（为门创建一个开口）（67）
			16. Adding materials to the walls（向墙壁添加材料）（70）
			17. Sealing a room（密封一个房间）（71）
			18. Adding props or a static mesh to the room（向房间添加道具或静态网格物体）（72）
			19. Adding Lightmass Importance Volume（添加光质量重要性体积）（74）
			20. Applying finishing touches to a room（对房间进行最后的修饰）（76）
				1. Useful tip – using the drag snap grid（有用的提示 – 使用拖动捕捉网格）（77）
		3. Game Objects – More and Move（游戏对象 – 更多和移动）（80）
			1. BSP Brush（BSP刷）（80）
				1. Background（背景）（81）
				2. Brush type（刷式）（81）
				3. Brush solidity（刷子坚固度）（81）
			2. Static Mesh（静态网格体）（82）
			3. BSP Brush versus Static Mesh（BSP 画笔与静态网格物体）（82）
			4. Making Static Mesh movable（使静态网格物体可移动）（83）
			5. Materials（材料）（84）
				1. Creating a Material in Unreal（在虚幻中创建材质）（85）
				2. Materials versus Textures（材质与纹理）（86）
				3. Texture/UV mapping（纹理/UV 映射）（87）
					1. How to create and use a Texture Map（如何创建和使用纹理贴图）（87）
					2. Multitexturing（多重纹理）（88）
					3. A special form of texture maps – Normal Maps（纹理贴图的一种特殊形式——法线贴图）（55）
			6. Level of detail（详细程度）（89）
			7. Collisions（碰撞）（89）
				1. Collision configuration properties（碰撞配置属性）（90）
					1. Simulation Generates Hit Events（模拟生成命中事件）（91）
					2. Generate Overlap Events（生成重叠事件）（91）
					3. Collision Presets（碰撞预设）（91）
					4. Collision Enabled（碰撞启用）（91）
					5. Object Type（对象类型）（91）
					6. Collision Responses（碰撞响应）（91）
						1. Trace Responses（跟踪响应）（91）
						2. Object Responses（对象响应）（91）
					7. Collision hulls（碰撞船体）（92）
				2. Interactions（互动）（93）
			8. Static Mesh creation pipeline（静态网格体创建管道）（94）
			9. Introducing volumes（介绍量）（94）
				1. Blocking Volume（阻塞量）（94）
				2. Camera Blocking Volume（相机遮挡量）（95）
				3. Trigger Volume（触发量）（96）
				4. Nav Mesh Bounds Volume（导航网格边界体积）（96）
				5. Physics Volume（物理量）
					1. Pain Causing Volume（引起疼痛的量）（97）
					2. Kill Z Volume（杀死 Z 量）
					3. Level Streaming Volume（级别 流媒体音量）（99）
					4. Cull Distance Volume（剔除距离体积）（100）
					5. Audio Volume（音频音量）（101）
					6. PostProcess Volume（后处理体积）（101）
					7. Lightmass Importance Volume（光质量 重要性 体积）（101）
			10. Introducing Blueprint（介绍蓝图）（101）
				1. Level Blueprint（关卡蓝图）（103）
			11. Using the Trigger Volume to turn on/off light（使用触发音量打开/关闭灯）（103）
			12. Using Trigger Volume to toggle light on/ off (optional)（使用触发音量来打开/关闭灯光（可选））（115）
		4. Material and Light（材质与光线）（118）
			1. Materials（材质）（118）
			2. The Material Editor（材质编辑器）（119）
				1. The rendering system（渲染系统）（119）
				2. Physical Based Shading Model（基于物理的着色模型）（119）
				3. High Level Shading Language（高级着色语言）（120）
				4. Getting started（入门）（120）
				5. Creating a simple custom material（创建简单的自定义材质）（120）
				6. Creating custom material using simple textures（使用简单纹理创建自定义材质）（128）
				7. Using custom materials to transform the level（使用自定义材质来变换关卡）（130）
			3. Rendering pipeline（渲染管线）（131）
			4. Shaders（着色器）（132）
			5. APIs – DirectX and OpenGL（API – DirectX 和 OpenGL）（136）
				1. DirectX（136）
					1. DirectX12（136）
						1. Pipeline state representation（管道状态表示）（137）
						2. Work submission（工作提交）（139）
						3. Resource access（资源获取）（139）
			6. Lights（灯）（139）
				1. Configuring a Point Light with more settings（使用更多设置配置点光源）（140）
					1. Attenuation Radius（衰减半径）（141）
					2. Intensity（强度）（142）
						1. Use Inverse Squared Falloff（使用平方反比衰减）（142）
					3. Color（颜色）（143）
				2. Adding and configuring a Spot Light（添加和配置聚光灯）（143）
					1. Inner cone and outer cone angle（内锥角和外锥角）（143）
				3. Using the IES Profile（使用 IES 配置文件）（144）
					1. Downloading IES Light Profiles（下载 IES 灯光配置文件）（145）
					2. Importing IES Profiles into the Unreal Engine Editor（将 IES 配置文件导入虚幻引擎编辑器）（145）
					3. Using IES Profiles（使用 IES 配置文件）（146）
				4. Adding and configuring a Directional Light（添加和配置定向光）（147）
					1. Example – adding and configuring a Sky light（示例 - 添加和配置天光）（148）
				5. Static, stationary, or movable lights（静态、固定或可移动的灯）（149）
					1. Common light/shadow definitions（常见的光/阴影定义）（150）
					2. Static Light（静态光）（151）
					3. Stationary Light（固定灯）（151）
					4. Movable Light（移动灯）（151）
				6. Exercise – extending your game level (optional)（练习 – 提高你的游戏水平（可选））（151）
					1. Useful tips（有用的提示）（152）
					2. Guidelines（指南）（152）
						1. Area expansion（面积扩大）（152）
						2. Creating windows and doors（创建门窗）（154）
						3. Creating basic furniture（创建基本家具）（157）
		5. Animation and AI（动画与人工智能）（160）
			1. What is animation?（什么是动画？）（161）
			2. Understanding how to animate a 3D model（了解如何制作 3D 模型动画）（161）
				1. Preparing before animation（动画制作前的准备工作）（162）
				2. How is animation created?（动画是如何创作的？）（163）
			3. What Unreal Engine 4 offers for animation in games（虚幻引擎 4 为游戏动画提供了什么）（164）
				1. Importing animation from Maya/3ds Max（从 Maya/3ds Max 导入动画）（164）
					1. Tutorial – importing the animation pack from Marketplace（教程 - 从 Marketplace 导入动画包）（164）
				2. What can you do with Persona?（你可以用角色做什么？）（166）
					1. Tutorial – assigning existing animation to a Pawn（教程 - 将现有动画分配给 Pawn）（166）
				3. Why do we need to blend animations?（为什么我们需要混合动画？）（168）
					1. Tutorial – creating a Blend Animation（教程 – 创建混合动画）（169）
					2. Tutorial – setting up the Animation Blueprint to use a Blend Animation（教程 - 设置动画蓝图以使用混合动画）（172）
						1. AnimGraph（动画图）（175）
						2. EventGraph（事件图）（179）
			4. Artificial intelligence（人工智能）（183）
				1. Understanding a Behavior Tree（理解行为树）（183）
				2. Exercise – designing the logic of a Behavior Tree（练习——设计行为树的逻辑）（185）
				3. Example – creating a simple Behavior Tree（示例 – 创建一个简单的行为树）（185）
				4. How to implement a Behavior Tree in Unreal Engine 4（如何在虚幻引擎 4 中实现行为树）（188）
				5. Navigation Mesh（导航网格）（188）
					1. Tutorial – creating a Navigation Mesh（教程 – 创建导航网格）（189）
				6. Tutorial – setting up AI logic（教程 – 设置 AI 逻辑）（190）
					1. Creating the Blueprint AIController（创建蓝图 AIController）（191）
					2. Creating the Blueprint character（创建蓝图角色）（192）
					3. Adding and configuring Mesh to a Character Blueprint（向角色蓝图添加和配置网格）（192）
					4. Linking AIController to the Character Blueprint（将 AIController 链接到角色蓝图）（195）
					5. Adding basic animation（添加基本动画）（196）
					6. Configuring AIController（配置AI控制器）（196）
						1. Nodes to add in EventGraph（要在 EventGraph 中添加的节点）（196）
					7. Adjusting movement speed（调整移动速度）（198）
					8. Creating the BlackBoardData（创建 BlackBoardData）（199）
						1. Adding a variable into BlackBoardData（将变量添加到 BlackBoardData 中）（200）
					9. Creating a Behavior Tree（创建行为树）（200）
					10. Creating a simple BT using a Wait task（使用等待任务创建简单的 BT）（201）
					11. Using the Behavior Tree（使用行为树）（203）
					12. Creating a custom task for the Behavior Tree（为行为树创建自定义任务）（203）
					13. Using the PickTargetLocation custom task in BT（在 BT 中使用 PickTargetLocation 自定义任务）（206）
					14. Replacing the Wait task with Move To（用“移至”替换“等待”任务）（207）
				7. Implementing AI in games（在游戏中实施人工智能）（208）
		6. A Particle System and Sound（粒子系统和声音）（210）
			1. What is a particle system?（什么是粒子系统？）（210）
			2. Exploring an existing particle system（探索现有的粒子系统）（211）
			3. The main components of a particle system（粒子系统的主要组成部分）（212）
				1. Modules（模块）（212）
			4. The design principles of a particle system（粒子系统的设计原理）（213）
				1. Research（研究）（213）
				2. The iterative creative process（迭代的创作过程）（213）
			5. Example – creating a fireplace particle system（示例 - 创建壁炉粒子系统）（214）
				1. Crafting P_Fireplace（制作 P_Fireplace）（218）
					1. Observing the solo emitters of the system（观察系统的单独发射器）（218）
					2. Deleting non-essential emitters（删除非必要的发射器）（218）
					3. Focusing on editing the Flame emitter（专注于编辑火焰发射器）（219）
					4. Looking at the complete particle system（查看完整的粒子系统）（219）
			6. Sound and music（声音和音乐）（219）
			7. How do we produce sound and music for games?（我们如何为游戏制作声音和音乐？）（220）
			8. Audio quality（音频质量）（221）
			9. How are sounds recorded?（声音是如何录制的？）（221）
			10. The Unreal audio system（虚幻音频系统）（222）
			11. Getting audio into Unreal（将音频导入 Unreal）（222）
				1. The audio format（音频格式）（222）
				2. The sampling rate（采样率）（222）
				3. Bit depth（位深度）（222）
				4. Supported sound channels（支持的声道）（223）
			12. Unreal sound formats and terminologies（虚幻的声音格式和术语）（225）
			13. The Sound Cue Editor（声音提示编辑器）（225）
				1. How to open the Sound Cue Editor（如何打开声音提示编辑器）（225）
			14. Exercise – importing a sound into the Unreal Editor（练习 – 将声音导入虚幻编辑器）（227）
			15. Exercise – adding custom sounds to a level（练习 – 将自定义声音添加到关卡中）（230）
			16. Configuring the Sound Cue Editor（配置声音提示编辑器）（232）
		7. Terrain and Cinematics（地形和电影）（236）
			1. Introducing terrain manipulation（介绍地形操纵）（236）
				1. Exercise – creating hills using the Landscape tool（练习 – 使用地形工具创建山丘）（237）
				2. Landscape creation options（景观创建选项）（244）
					1. Multiple landscapes（多重风景）（245）
					2. Using custom material（245）
					3. Importing height maps and layers（导入高度图和图层）（245）
					4. Scale（缩放）（245）
					5. The number of components（元件数量）（245）
					6. Section Size（断面尺寸）（246）
			2. Introducing cinematics（介绍动画）（246）
			3. Why do we need cut scenes?（为什么我们需要过场动画？）（247）
			4. Cinematic techniques（电影技巧）（248）
				1. Adjusted camera functions（调整相机功能）（248）
					1. Zoom（飞涨）（248）
					2. Field of view（视野）（248）
					3. Depth of field（景深）（249）
				2. Camera movement（相机移动）（250）
					1. Tilt（俯仰）（251）
					2. Pan（偏航）（251）
					3. Dolly/track/truck（移动车/轨道/卡车）（252）
					4. Pedestal（253）
				3. Capturing a scene（捕捉场景）（253）
					1. Lighting（灯光）（253）
					2. Framing（取景）（253）
						1. Some framing rules（一些取景规则）（254）
						2. Shot types（镜头类型）（254）
					3. Shot plan（拍摄计划）（254）
			5. Getting familiar with the Unreal Matinee Editor（熟悉 Unreal Matinee 编辑器）（255）
			6. Exercise – creating a simple matinee sequence（练习 – 创建一个简单的日场序列）（255）