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
	2. Introduction to Algorithms Third Edition（算法导论第3版）
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
	1. Programming in Lua Fourth Edition（Lua程序设计第4版）
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
	2. Microsoft Visual C# Step by Step（Visual C#从入门到精通）
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
3. Software Development（软件开发）
	1. Head First Design Patterns（Head First设计模式）
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
	2. Clean Code（编码整洁之道）
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
4. Game Programming（游戏编程）
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
5. Game Engine Development（游戏引擎开发）
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
6. Computer Graphics (CG)（计算机图形学（CG））
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
7. Game Artificial Intelligence（游戏人工智能（AI））
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
8. Multiplayer Game Programming（多人游戏编程）
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
9. Unity
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
10. UnrealEngine
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