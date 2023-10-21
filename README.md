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
3. Game Programming（游戏编程）
	1. Unity in Action Multiplatform game development in C#（Unity 实践使用 C# 进行多平台游戏开发）
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