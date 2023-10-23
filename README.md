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
4. Game Programming（游戏编程）
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
	2. Learning Unreal Engine Game Development（学习虚幻引擎游戏开发）
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
				1. Subsystem Start-Up and Shut-Down（ 子系统启动和关闭）（436）
					1. C++ Static Initialization Order (or Lack Thereof)（ C++  静态初始化顺序（或缺乏）)（437）
						1. Construct On Demand（按需构建）（438）
					2. A Simple Approach That Works（ 一种有效的简单方法）（439）
					3. Some Examples from Real Engines（真实引擎的一些例子）（441）
						1. OGRE（441）
						2. Naughty Dog’s Uncharted and The Last of Us Series（ 顽皮狗《神秘海域》和《最后生还者》系列）（443）
				2.  Memory Management（ 内存管理）（445）
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
						2. Hashing（ 散列）（472）
						3. Implementing a Closed Hash Table（ 实现封闭哈希表）（474）
						4. Robin Hood Hashing（ 罗宾汉哈希）（475）
				4. Strings（字符串）（475）
					1. The Problem with Strings（字符串问题）（475）
					2. String Classes（ 字符串类）（476）
					3. Unique Identifiers（唯一标识符）（477）
						1. Hashed String Ids（散列字符串  ID）（478）
						2. Some Implementation Ideas（ 一些实现思路）（478）
					4. Localization（ 本地化）（481）
						1. Unicode（统一码）（481）
						2. char versus wchar_t（char  与  wchar_t）（483）
						3. Unicode under Windows（Windows  下的  Unicode）（484）
						4. Unicode on Consoles（控制台上的  Unicode）（485）
						5. Other Localization Concerns（其他本地化问题）（485）
						6. Case Study: Naughty Dog’s Localization Tool（ 案例分析：顽皮狗的本地化工具）（487）
				5.  Engine Configuration（引擎配置）（489）
					1. Loading and Saving Options（加载和保存选项）（490）
					2. Per-User Options（每个用户选项）（493）
					3. Configuration Management in Some Real Engines（ 部分实机中的配置管理）（493）
						1. Example: Quake’s Cvars（示例：Quake  的  Cvar）（493）
						2. Example: OGRE（  示例：OGRE）（494）
						3. Example: The Uncharted and The Last of Us Series（示例：《神秘海域》和《最后生还者》系列）（494）
			2. Resources and the File System（资源和文件系统）（500）
				1. File System（文件系统）（501）
					1. File Names and Paths（文件名和路径）（501）
						1. Differences across Operating Systems（操作系统之间的差异）（502）
						2. Absolute and Relative Paths（绝对路径和相对路径）（503）
						3. Search Paths（ 搜索路径）（504）
						4. Path APIs（路径  API）（505）
					2. Basic File I/O（  基本文件  I/O）（505）
						1. To Wrap or Not to Wrap（ 缠绕或不缠绕）（506）
						2. Synchronous File I/O（同步文件  I/O）（507）
					3. Asynchronous File I/O（异步文件I/O）（508）
						1. Priorities（  优先级）（511）
						2. How Asynchronous File I/O Works（ 异步文件  I/O  的工作原理）（511）
				2. The Resource Manager（资源管理器）（512）
					1. Offline Resource Management and the Tool Chain（离线资源管理及工具链）（512）
						1. Revision Control for Assets（ 资产的修订控制）（512）
						2. The Resource Database（资源数据库）（513）
						3. Some Successful Resource Database Designs（ 一些成功的资源数据库设计）（515）
						4. The Asset Conditioning Pipeline（ 资产调节管道）（520）
					2. Runtime Resource Management（ 运行时资源管理）（522）
						1. Responsibilities of the Runtime Resource Manager（运行时资源管理器的职责）（522）
						2. Resource File and Directory Organization（ 资源文件和目录组织）（523）
						3. Resource File Formats（资源文件格式）（526）
						4. Resource GUIDs（资源  GUID）（526）
						5. The Resource Registry（ 资源注册表）（527）
						6. Resource Lifetime（资源生命周期）（528）
						7. Memory Management for Resources（资源的内存管理）（530）
						8. Composite Resources and Referential Integrity（复合资源和引用完整性）（535）
						9. Handling Cross-References between Resources（处理资源之间的交叉引用）（536）
						10. Post-Load Initialization（ 加载后初始化）（540）
			3. The Game Loop and Real-Time Simulation（游戏循环和实时模拟）（544）
				1. The Rendering Loop（渲染循环）（544）
				2. The Game Loop（游戏循环）（545）
					1. A Simple Example: Pong（ 一个简单的例子：Pong）（546）
				3. Game Loop Architectural Styles（游戏循环架构风格）（548）
					1. Windows Message Pumps（  Windows  消息泵）（548）
					2. Callback-Driven Frameworks（  回调驱动的框架）（548）
					3. Event-Based Updating（ 基于事件的更新）（550）
				4.  Abstract Timelines（抽象时间线）（551）
					1. Real Time（  实时）（551）
					2. Game Time（游戏时间）（551）
					3. Local and Global Timelines（本地和全球时间表）（552）
				5. Measuring and Dealing with Time（测量和处理时间）（553）
					1. Frame Rate and Time Deltas（帧速率和时间增量）（553）
					2. From Frame Rate to Speed（ 从帧率到速度）（554）
						1. Old-School CPU-Dependent Games（ 老式的  CPU  相关游戏）（554）
						2. Updating Based on Elapsed Time（ 根据经过的时间更新）（555）
						3. Using a Running Average（使用移动平均值）（556）
						4. Governing the Frame Rate（ 控制帧速率）（556）
						5. Screen Tearing and V-Sync（屏幕撕裂和垂直同步）（557）
					3. Measuring Real Time with a High-Resolution Timer（ 使用高分辨率计时器进行实时测量）（558）
						1. High-Resolution Clock Drift（高分辨率时钟漂移）（559）
					4. Time Units and Clock Variables（ 时间单位和时钟变量）（559）
						1. 64-Bit Integer Clocks（ 64  位整数时钟）（559）
						2. 32-Bit Integer Clocks（ 32  位整数时钟）（560）
						3. 32-Bit Floating-Point Clocks（  32  位浮点时钟）（560）
						4. Limitations of Floating-Point Clocks（浮点时钟的限制）（561）
						5. Other Time Units（其他时间单位）（561）
					5. Dealing with Breakpoints（ 处理断点）（562）
				6.  Multiprocessor Game Loops（多处理器游戏循环）（563）
					1. Task Decomposition（任务分解）（563）
					2. One Thread per Subsystem（  每个子系统一个线程）（564）
					3. Scatter/Gather（分散/聚集）（565）
						1. Scatter/Gather in the Game Loop（游戏循环中的分散/聚集）（566）
						2. SIMD for Scatter/Gather（用于分散/聚集的  SIMD）（567）
						3. Making Scatter/Gather More Efficient（使分散/聚集更加高效）（567）
					4. Job Systems（ 工作系统）（568）
						1. Typical Job System Interface（典型作业系统界面）（568）
						2. A Simple Job System Based on a Thread Pool（ 一个基于线程池的简单作业系统）（570）
						3. A Limitation of Thread-Based Jobs（  基于线程的作业的限制）（571）
						4. Jobs as Coroutines（ 作为协程的作业）（573）
						5. Jobs as Fibers（作业作为纤维）（573）
						6. Job Counters（作业计数器）（573）
						7. Job Synchronization Primitives（作业同步原语）（574）
						8. Job Visualization and Profiling Tools（  作业可视化和分析工具）（575）
						9. The Naughty Dog Job System（ 顽皮狗工作系统）（576）
			4.  Human Interface Devices（人机接口设备）（578）
				1. Types of Human Interface Devices（人机接口设备的类型）（578）
				2. Interfacing with a HID（与  HID  接口）（580）
					1. Polling（轮询）（580）
					2. Interrupts（  中断）（581）
					3. Wireless Devices（无线设备）（581）
				3. Types of Inputs（输入类型）（582）
					1. Digital Buttons（数字按钮）（582）
					2. Analog Axes and Buttons（模拟轴和按钮）（583）
					3. Relative Axes（相对轴）（585）
					4. Accelerometers（加速度计）（585）
					5. 3D Orientation with the Wiimote or DualShock（使用  Wiimote  或  DualShock  进行  3D  定向）（585）
					6. Cameras（  相机）（586）
				4.   Types of Outputs（输出类型）（588）
					1. Rumble（588）
					2. Force-Feedback（力反馈）（589）
					3. Audio（  音频）（589）
					4. Other Inputs and Outputs（其他输入和输出）（589）
				5. Game Engine HID Systems（游戏引擎HID系统）（589）
					1. Typical Requirements（典型要求）（590）
					2. Dead Zone（死区）（590）
					3. Analog Signal Filtering（模拟信号滤波）（591）
					4. Detecting Input Events（  检测输入事件）（593）
						1. Button Up and Button Down（按钮向上和按钮向下）（593）
						2. Chords（594）
						3. Sequences and Gesture Detection（ 序列和手势检测）（596）
					5. Managing Multiple HIDs for Multiple Players（管理多个玩家的多个  HID）（601）
					6. Cross-Platform HID Systems（跨平台  HID  系统）（601）
					7. Input Remapping（输入重新映射）（603）
					8. Context-Sensitive Controls（上下文相关控件）（605）
					9. Disabling Inputs（禁用输入）（605）
				6. Human Interface Devices in Practice（实践中的人机接口设备）（606）
			5. Tools for Debugging and Development（调试和开发工具）（608）
				1. Logging and Tracing（ 记录和跟踪）（608）
					1. Formatted Output with OutputDebugString()（ 使用  OutputDebugString()  格式化输出）（609）
					2. Verbosity（冗长）（610）
					3. Channels（通道）（611）
						1. Using Redis to Manage TTY Channels（使用Redis管理TTY通道）（612）
					4. Mirroring Output to a File（将输出镜像到文件）（612）
					5. Crash Reports（ 崩溃报告）（613）
				2.  Debug Drawing Facilities（调试绘图工具）（613）
					1. Debug Drawing API（调试绘图API）（616）
				3. In-Game Menus（  游戏内菜单）（620）
				4. In-Game Console（游戏内控制台）（623）
				5. Debug Cameras and Pausing the Game（调试相机和暂停游戏）（624）
				6. Cheats（秘籍）（625）
				7. Screenshots and Movie Capture（  屏幕截图和视频捕捉）（625）
				8.  In-Game Profiling（ 游戏内分析）（627）
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
						5. World Space and Mesh Instancing（ 世界空间和网格实例化）（650）
					2. Describing the Visual Properties of a Surface（描述表面的视觉属性）（651）
						1. Introduction to Light and Color（光和颜色简介）（652）
						2. Vertex Attributes（顶点属性）（654）
						3. Vertex Formats（ 顶点格式）（655）
						4. Attribute Interpolation（属性插值）（656）
						5. Textures（ 纹理）（658）
						6. Materials（材料）（665）
					3. Lighting Basics（照明基础知识）（666）
						1. Local and Global Illumination Models（局部和全局照明模型）（666）
						2. The Phong Lighting Mode（ Phong  光照模型）（668）
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
						1. Vertex Shader（ 顶点着色器）（692）
						2. Geometry Shader（ 几何着色器）（693）
						3. Stream Output（ 流输出）（693）
						4. Clipping（剪裁）（693）
						5. Screen Mapping（屏幕映射）（694）
						6. Triangle Set-up（ 三角形设置）（694）
						7. Triangle Traversal（ 三角形遍历）（694）
						8. Early z-Test（ 早期  z  测试）（694）
						9. Pixel Shader（像素着色器）（694）
						10. Merging / Raster Operations Stage（合并/光栅操作阶段）（695）
					5. Programmable Shaders（可编程着色器）（696）
						1. Accessing Memory（访问内存）（697）
						2. Introduction to High-Level Shader Language Syntax（高级着色器语言语法简介）（699）
						3. Effect Files（效果文件）（701）
						4. Further Reading（ 进一步阅读）（701）
					6. Antialiasing（抗锯齿）（702）
						1. Full-Screen Antialiasing (FSAA)（ 全屏抗锯齿  (FSAA)）（703）
						2. Multisampled Antialiasing (MSAA)（多重采样抗锯齿  (MSAA)）（703）
						3. Coverage Sample Antialiasing (CSAA)（ 覆盖样本抗锯齿  (CSAA)）（704）
						4. Morphological Antialiasing (MLAA)（ 形态抗锯齿  (MLAA)）（704）
						5. Subpixel Morphological Antialiasing (SMAA)（  子像素形态抗锯齿  (SMAA)）（706）
					7. The Application Stage（ 申请阶段）（706）
						1. Visibility Determination（ 能见度测定）（706）
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
						4. Caustics（ 焦散）（725）
						5. Subsurface Scattering（ 次表面散射）（726）
						6. Precomputed Radiance Transfer (PRT)（ 预计算辐射传输  (PRT)）（727）
					4. Deferred Rendering（ 延迟渲染）（728）
					5. Physically Based Shading（ 基于物理的着色）（728）
				4.  Visual Effects and Overlays（ 视觉效果和叠加）（729）
					1. Particle Effects（粒子效应）（730）
					2. Decals（贴花）（731）
					3. Environmental Effects（环境影响）（732）
						1. Skies（天空）（732）
						2. Terrain（地形）（733）
						3. Water（ 水）（734）
					4. Overlays（ 叠加）（735）
						1. Text and Fonts（文本和字体）（735）
					5. Gamma Correction（伽马校正）（737）
					6. Full-Screen Post Effects（全屏后期效果）（738）
				5. Further Reading（进一步阅读）（738）
			2. Animation Systems（动画系统）（740）
				1. Types of Character Animation（角色动画的类型）（740）
					1. Cel Animation（赛璐珞动画）（741）
					2. Rigid Hierarchical Animation（ 刚性分层动画）（742）
					3. Per-Vertex Animation and Morph Targets（每顶点动画和变形目标）（743）
					4. Skinned Animation（蒙皮动画）（744）
					5. Animation Methods as Data Compression Techniques（作为数据压缩技术的动画方法）（744）
				2. Skeletons（骨架）（746）
					1. The Skeleal Hierarchy（骨架层次结构）（747）
					2. Representing a Skeleton in Memory（在内存中表示骨架）（747）
				3. Poses（姿势）（748）
					1. Bind Pose（绑定姿势）（748）
					2. Local Poses（局部位姿）（749）
						1. Joint Scale（ 关节尺度）（750）
						2. Representing a Joint Pose in Memory（表示记忆中的关节姿势）（751）
						3. The Joint Pose as a Change of Basis（关节姿势作为基础的改变）（751）
					3. Global Poses（全局位姿）（752）
						1. Representing a Global Pose in Memory（  在内存中表示全局位姿）（752）
				4. Clips（剪辑）（753）
					1. The Local Timeline（本地时间线）（754）
						1. Pose Interpolation and Continuous Time（位姿插值和连续时间）（755）
						2. Time Units（  时间单位）（756）
						3. Frame versus Sample（ 框架与样本）（756）
						4. Frames, Samples and Looping Clips（  帧、样本和循环剪辑）（757）
						5. Normalized Time (Phase)（归一化时间（相位））（757）
					2. The Global Timeline（ 全球时间线）（758）
					3. Comparison of Local and Global Clocks（本地时钟和全局时钟的比较动画系统必须跟踪当）（760）
						1. Synchronizing Animations with a Local Clock（将动画与本地时钟同步）（761）
						2. Synchronizing Animations with a Global Clock（将动画与全局时钟同步）（762）
					4. A Simple Animation Data Format（ 简单的动画数据格式）（763）
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
				6. Animation Blending（ 动画混合）（774）
					1. LERP Blending（ LERP  混合）（774）
					2. Applications of LERP Blending（LERP混合的应用）（776）
						1. Temporal Interpolation（时间插值）（776）
						2. Motion Continuity: Cross-Fading（ 运动连续性：交叉淡入淡出）（777）
						3. Directional Locomotion（  定向运动）（780）
					3. Complex LERP Blends（复杂的  LERP  混合）（782）
						1. Generalized One-Dimensional LERP Blending（广义一维  LERP  混合）（782）
						2. Simple Two-Dimensional LERP Blending（简单的二维  LERP  混合）（782）
						3. Triangular Two-Dimensional LERP Blending（三角形二维LERP混合）（784）
						4. Generalized Two-Dimensional LERP Blending（广义二维  LERP  混合）（785）
					4. Partial-Skeleton Blending（部分骨架混合）（786）
					5. Additive Blending（添加剂混合）（788）
						1. Mathematical Formulation（ 数学公式）（788）
						2. Additive Blending versus Partial Blending（加法混合与部分混合）（790）
						3. Limitations of Additive Blending（ 添加剂混合的局限性）（790）
					6. Applications of Additive Blending（添加剂混合的应用）（791）
						1. Stance Variation（ 姿态变化）（791）
						2. Locomotion Noise（运动噪声）（792）
						3. Aim and Look-At（瞄准和观察）（792）
						4. Overloading the Time Axis（重载时间轴）（793）
				7. Post-Processing（ 后处理）（793）
					1. Procedural Animations（ 程序动画）（794）
					2. Inverse Kinematics（逆运动学）（794）
					3. Rag Dolls（布娃娃）（796）
				8. Compression Techniques（压缩技术）（796）
					1. Channel Omission（通道省略）（797）
					2. Quantization（量化）（797）
					3. Sampling Frequency and Key Omission（采样频率和关键省略）（801）
					4. Curve-Based Compression（ 基于曲线的压缩）（802）
					5. Wavelet Compression（  小波压缩）（802）
					6. Selective Loading and Streaming（ 选择性加载和流式传输）（803）
				9. The Animation Pipeline（ 动画管道）（803）
				10. Action State Machines（ 动作状态机）（805）
					1. The Flat Weighted Average Approach（统一加权平均法）（807）
						1. Example: OGRE（ 示例：OGRE）（808）
						2. Example: Granny（示例：Granny）（809）
						3. Cross-Fades with a Flat Weighted Average（具有平坦加权平均值的交叉淡入淡出）（809）
					2. Blend Trees（  混合树）（811）
						1. Binary LERP Blend Trees（二元  LERP  混合树）（811）
						2. Generalized One-Dimensional Blend Trees（ 广义一维混合树）（811）
						3. Two-Dimensional LERP Blend Trees（二维  LERP  混合树）（812）
						4. Additive Blend Trees（加法混合树）（812）
						5. Layered Blend Trees（分层混合树）（813）
						6. Cross-Fades with Blend Trees（使用混合树进行交叉淡入淡出）（814）
					3. State and Blend Tree Specifications（状态和混合树规范）（815）
						1. Example: The Naughty Dog Engine（示例：顽皮狗引擎）（816）
						2. Example: Unreal Engine 4（  示例：虚幻引擎  4）（819）
					4. Transitions（ 转换）（819）
						1. Kinds of Transitions（ 转换类型）（820）
						2. Transition Parameters（  转换参数）（820）
						3. The Transition Matrix（转移矩阵）（821）
						4. Implementing a Transition Matrix（实现转移矩阵）（821）
					5. Control Parameters（ 控制参数）（824）
				11. Constraints（约束）（825）
					1. Attachments（附件）（826）
					2. Interobject Registration（对象间注册）（827）
						1. Reference Locators（  参考定位器）（828）
						2. Finding the World-Space Reference Location（ 查找世界空间参考位置）（829）
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
						2. Physics Puzzle Games（ 物理益智游戏）（839）
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
					3. TrueAxis（ 真轴）（843）
					4. PhysX（物理X）（843）
					5. Havok（ 冲击波）（843）
					6. Physics Abstraction Layer (PAL)（物理抽象层（PAL））
					7. Digital Molecular Matter (DMM)（数字分子物质（DMM））
				3. The Collision Detection System（碰撞检测系统）（844）
					1. Collidable Entities（可碰撞实体）（845）
					2. The Collision/Physics World（  碰撞/物理世界）（847）
						1. The Physics World（  物理世界）（847）
					3. Shape Concepts（形状概念）（848）
						1. Intersection（ 交叉点）（848）
						2. Contact（ 联系方式）（849）
						3. Convexity（凸性）（849）
					4. Collision Primitives（ 碰撞原语）（849）
						1. Spheres（球体）（849）
						2. Capsules（ 胶囊）（850）
						3. Axis-Aligned Bounding Boxes（轴对齐边界框）（850）
						4. Oriented Bounding Boxes（定向边界框）（851）
						5. Discrete Oriented Polytopes (DOP)（离散定向多面体  (DOP)（851）
						6. Arbitrary Convex Volumes（任意凸体积）（852）
						7. Poly Soup（聚汤）（853）
						8. Compound Shapes（复合形状）（854）
					5. Collision Testing and Analytical Geometry（ 碰撞测试和解析几何）（855）
						1. Point versus Sphere（点与球体  我们可以通）（855）
						2. Sphere versus Sphere（球体与球体  确定两个球体）（855）
						3. The Separating Axis Theorem（分离轴定理）（856）
						4. AABB versus AABB（ AABB  与  AABB）（857）
						5. Detecting Convex Collisions: The GJK Algorithm（检测凸碰撞：GJK  算法）（858）
						6. Other Shape-Shape Combinations（其他形状‑形状组合）（861）
						7. Detecting Collisions between Moving Bodies（  检测移动体之间的碰撞）（862）
					6. Performance Optimizations（性能优化）（864）
						1. Temporal Coherency（时间一致性）（865）
						2. Spatial Partitioning（空间分区）（865）
						3. Broad Phase, Midphase and Narrow Phase（ 宽相、中相和窄相）（866）
					7. Collision Queries（ 碰撞查询）（866）
						1. Ray Casting（光线投射）（867）
						2. Shape Casting（形状铸造）（868）
						3. Phantoms（ 幻象）（871）
						4. Other Types of Queries（其他类型的查询）（871）
					8. Collision Filtering（冲突过滤）（871）
						1. Collision Masking and Layers（碰撞掩蔽和层）（872）
						2. Collision Callbacks（碰撞回调）（872）
						3. Game-Specific Collision Materials（游戏特定的碰撞材质）（872）
				4. Rigid Body Dynamics（刚体动力学）（873）
					1. Some Foundations（ 一些基础）（875）
						1. Units（单位）（875）
						2. Separability of Linear and Angular Dynamics（线性和角动力学的可分离性）（875）
						3. Center of Mass（质心）（876）
					2. Linear Dynamics（线性动力学）（877）
						1. Linear Velocity and Acceleration（线速度和加速度）（877）
						2. Force and Momentum（ 力和动量）（878）
					3. Solving the Equations of Motion（求解运动方程）（879）
						1. Force as a Function（力作为函数）（879）
						2. Ordinary Differential Equations（常微分方程）（879）
						3. Analytical Solutions（分析解）（880）
					4. Numerical Integration（  数值积分）（880）
						1. Explicit Euler（显式欧拉）（881）
						2. Properties of Numerical Methods（数值方法的性质）（882）
						3. Alternatives to Explicit Euler（显式欧拉的替代方案）（883）
						4. Verlet Integration（Verlet  集成）（884）
						5. Velocity Verlet（ 速度韦尔莱）（885）
					5. Angular Dynamics in Two Dimensions（ 二维角动力学）（885）
						1. Orientation and Angular Speed（方向和角速度）（885）
						2. Angular Speed and Acceleration（角速度和加速度）（886）
						3. Moment of Inertia（转动惯量）（886）
						4. Torque（扭矩）（886）
						5. Solving the Angular Equations of Motion in Two Dimensions（  求解二维运动角方程）（888）
					6. Angular Dynamics in Three Dimensions（三维角动力学）（889）
						1. The Inertia Tensor（惯性张量）（889）
						2. Orientation in Three Dimensions（三维方向）（890）
						3. Angular Velocity and Momentum in Three Dimensions（三维角速度和动量）（890）
						4. Torque in Three Dimensions（三维扭矩）（892）
						5. Solving the Equations of Angular Motion in Three Dimensions（求解三维角运动方程）（892）
					7. Collision Response（碰撞响应）（894）
						1. Energy（能源）（894）
						2. Impulsive Collision Response（ 脉冲碰撞响应）（895）
						3. Penalty Forces（处罚力量）（898）
						4. Using Constraints to Resolve Collisions（使用约束来解决冲突）（898）
						5. Friction（摩擦力）（899）
						6. Welding（焊接）（900）
						7. Coming to Rest, Islands and Sleeping（休息、离岛和睡觉）（900）
					8. Constraints（约束）（902）
						1. Point-to-Point Constraints（ 点对点约束）（903）
						2. Stiff Springs（硬弹簧）（903）
						3. Hinge Constraints（ 铰链约束）（903）
						4. Prismatic Constraints（棱柱约束）（904）
						5. Other Common Constraint Types（  其他常见约束类型）（904）
						6. Constraint Chains（约束链）（904）
						7. Rag Dolls（布娃娃）（905）
						8. Powered Constraints（动力约束）（906）
					9. Controlling the Motions of Rigid Bodies（控制刚体运动）（907）
						1. Gravity（重力）（907）
						2. Applying Forces（施加力）（907）
						3. Applying Torques（  施加扭矩）（908）
						4. Applying Impulses（ 施加脉冲）（908）
					10. The Collision/Physics Step（碰撞/物理步骤）（908）
						1. The Constraint Solver（ 约束求解器）（909）
						2. Variations between Engines（引擎之间的差异）（910）
				5. Integrating a Physics Engine into Your Game（将物理引擎集成到游戏中）（911）
					1. Linking Game Objects and Rigid Bodies（连接游戏对象和刚体）（911）
						1. Physics-Driven Bodies（物理驱动体）（913）
						2. Game-Driven Bodies（游戏驱动体）（914）
						3. Fixed Bodies（ 固定体）（915）
						4. Havok’s Motion Type（Havok  的运动类型）（915）
					2. Updating the Simulation（更新模拟）（916）
						1. Timing Collision Queries（ 时序冲突查询）（917）
						2. Single-Threaded Updating（ 单线程更新）（918）
					3. Example Uses of Collision and Physics in a Game（ 游戏中碰撞和物理的使用示例）（919）
						1. Simple Rigid Body Game Objects（简单刚体游戏对象）（919）
						2. Bullet Traces（ 子弹轨迹）（919）
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
						1. Equal-Loudness Contours（ 等响度轮廓）（935）
						2. The Audible Frequency Band（听觉频段）（936）
					3. Sound Wave Propagation（声波传播）（936）
						1. Fall-Off with Distance（随距离的衰减）（936）
						2. Atmospheric Absorption（大气吸收）（937）
						3. Phase Shift and Interference（相移和干扰）（938）
						4. Reverb and Echo（混响和回声）（939）
						5. Sound in Motion: The Doppler Effect（运动中的声音：多普勒效应）（941）
					4. Perception of Position（位置感知）（942）
				2. The Mathematics of Sound（ 声音的数学）（943）
					1. Signals（ 信号）（943）
						1. Be Discrete, Continuously（离散、连续）（944）
					2. Manipulating Signals（操纵信号）（944）
					3. Linear Time-Invariant (LTI) Systems（线性时不变（LTI）系统）（945）
					4. Impulse Response of an LTI System（ LTI系统的脉冲响应）（947）
						1. The Unit Impulse（单位冲量）（947）
						2. Using an Impulse Train to Represent a Signal（使用脉冲序列表示信号）（948）
						3. Convolution（卷积）（949）
						4. Visualizing Convolution（可视化卷积）（951）
						5. Some Properties of Convolution（卷积的一些性质）（952）
					5. The Frequency Domain and the Fourier Transform（频域和傅立叶变换）（952）
						1. The Sinusoidal Signal（正弦信号）（952）
						2. The Complex Exponential Signal（复指数信号）（953）
						3. The Fourier Series（ 傅立叶级数）（957）
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
						5. Analog Signal Levels（ 模拟信号电平）（964）
						6. Amplifiers（放大器）（965）
						7. Volume/Gain Controls（ 音量/增益控制）（965）
						8. Analog Wiring and Connectors（模拟接线和连接器）（966）
					2. Digital Audio Technology（数字音频技术）（967）
						1. Analog-to-Digital Conversion: Pulse-Code Modulation（模数转换：脉冲编码调制）（967）
						2. Digital-to-Analog Conversion: Demodulation（ 数模转换：解调）（970）
						3. Digital Audio Formats and Codecs（数字音频格式和编解码器）（970）
						4. Parallel and Interleaved Audio Data（并行和交错音频数据）（972）
						5. Digital Wiring and Connectors（ 数字接线和连接器）（973）
				4.  Rendering Audio in 3D（以  3D  方式渲染音频）（974）
					1. Overview of 3D Sound Rendering（3D声音渲染概述）（975）
					2. Modeling the Audio World（音频世界建模）（975）
					3. Distance-Based Attenuation（基于距离的衰减）（976）
						1. Fall-Off Min and Max（ 衰减最小值和最大值）（976）
						2. Blending to Zero（ 混合至零）（976）
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
						2. Reverb Regions（ 混响区域）（986）
						3. Obstruction, Occlusion and Exclusion（阻碍、遮挡和排除）（987）
						4. Sound Portals in The Last of Us（《最后生还者》中的声音入口）（991）
						5. Further Reading on Environmental Acoustics（  环境声学进一步阅读）（992）
						6. Doppler Shift（多普勒频移）（992）
				5. Audio Engine Architecture（音频引擎架构）（993）
					1. The Audio Processing Pipeline（音频处理管道）（994）
					2. Concepts and Terminology（概念和术语）（996）
						1. Voices（ 声音）（996）
						2. Buses（ 总线）（997）
					3. The Voice Bus（语音总线）（997）
						1. Sound Synthesis: Codecs（ 声音合成：编解码器）（997）
						2. Gain Control（增益控制）（998）
						3. Aux Sends（辅助发送）（998）
						4. Reverb （混响）（998）
						5. Pre-Send Filter（预发送过滤器）（999）
						6. Post-Send Filter（发送后过滤器）（999）
						7. Pan Pots（999）
					4. Master Mixer（ 主混音器）（999）
						1. Analog Mixing（模拟混合）（1000）
						2. Digital Mixing（数字混音）（1000）
						3. Sample Depth Conversion（样本深度转换）（1000）
						4. Sample Rate Conversion（ 采样率转换）（1000）
					5. The Master Output Bus（主输出总线）（1001）
					6. Implementing a Bus（实现总线）（1002）
						1. Analog Buses（模拟总线）（1002）
						2. Digital Buses（数字总线）（1002）
						3. Bus Latency（总线延迟）（1003）
					7. Asset Management（资产管理）（1004）
						1. Audio Clips（ 音频剪辑）（1004）
						2. Sound Cues（ 声音提示）（1005）
						3. Sound Banks（声音库）（1006）
						4. Streaming Sounds（流声音）（1007）
					8. Mixing Your Game（混合你的游戏）（1007）
						1. Groups（组）（1008）
						2. Ducking（闪避）（1008）
						3. Bus Presets and Mix Snapshots（1009）
						4. Instance Limiting（实例限制）（1009）
						5. Mixing In-Game Cinematics（混合游戏内动画）（1010）
					9. Audio Engine Survey（音频引擎调查）（1011）
						1. Windows: The Universal Audio Architecture（  Windows：通用音频架构）（1011）
						2. XAudio2（1012）
						3. Scream and BoomRangBuss（ Scream  和  BoomRangBuss）（1012）
						4. Multiplatform 3D Audio Engines（多平台  3D  音频引擎）（1013）
				6. Game-Specific Audio Features（游戏特定的音频特性）（1015）
					1. Supporting Split-Screen（支持分屏）（1016）
					2. Character Dialog（角色对话框）（1016）
						1. Giving a Character a Voice（赋予角色声音）（1017）
						2. Defining a Line of Dialog（定义一行对话）（1017）
						3. Playing a Line of Dialog（播放一行对话）（1019）
						4. Priority and Interruption（优先级和中断）（1020）
						5. Conversations（ 对话）（1021）
						6. Interrupting Conversations（中断对话）（1022）
						7. Exclusivity（排他性）（1023）
						8. Choices and Branching Conversations（选择和分支对话）（1023）
						9. Context-Sensitive Dialog（ 上下文相关对话框）（1028）
						10. Dialog Actions（对话框操作）（1028）
					3. Music（音乐）（1029）
		4. Gameplay（游戏玩法）（1032）
			1. Introduction to Gameplay Systems（简介游戏系统）（1034）
				1. Anatomy of a Game World（游戏世界剖析）（1035）
					1. World Elements（ 世界元素）（1035）
						1. Static Geometry（ 静态几何）（1037）
					2. World Chunks（世界块）（1038）
					3. High-Level Game Flow（高级游戏流程）（1038）
				2. Implementing Dynamic Elements: Game Objects（实现动态元素：游戏对象）（1040）
					1. Game Object Models（游戏对象模型）（1041）
					2. Tool-Side Design versus Runtime Design（ 工具端设计与运行时设计）（1042）
				3.  Data-Driven Game Engines（数据驱动的游戏引擎）（1043）
				4. The Game World Editor（ 游戏世界编辑器）（1044）
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
						1. A Simple Object-Based Model in C: Hydro Thunder（ C  语言中的简单的基于对象的模型：Hydro  Thunder）（1063）
						2. Monolithic Class Hierarchies（整体类层次结构）（1065）
						3. Problems with Deep, Wide Hierarchies（ 深、宽层次结构的问题）（1047）
						4. Using Composition to Simplify the Hierarchy（使用组合来简化层次结构）（1070）
						5. Generic Components（通用组件）（1074）
						6. Pure Component Models（纯组件模型）（1075）
					2. Property-Centric Architectures（以属性为中心的架构）（1076）
						1. Implementing Behavior via Property Classes（通过属性类实现行为）（1078）
						2. Implementing Behavior via Script（通过脚本实现行为）（1078）
						3. Properties versus Components（属性与组件）（1078）
						4. Pros and Cons of Property-Centric Designs（以属性为中心的设计的优缺点）（1079）
						5. Further Reading（ 进一步阅读）（1080）
				3. World Chunk Data Formats（世界块数据格式）（1081）
					1. Binary Object Images（二进制对象图像）（1082）
					2. Serialized Game Object Descriptions（序列化游戏对象描述）（1082）
					3. Spawners and Type Schemas（生成器和类型模式）（1084）
						1. Object Type Schemas（ 对象类型模式）（1085）
						2. Default Attribute Values（默认属性值）（1087）
						3. Some Beneifts of Spawners and Type Schemas（Spawners  和类型模式的一些好处）（1088）
				4. Loading and Streaming Game Worlds（加载和流式传输游戏世界）（1088）
					1. Simple Level Loading（简单关卡加载）（1089）
					2. Toward Seamless Loading: Air Locks（实现无缝装载：气闸）（1089）
					3. Game World Streaming（游戏世界流媒体）（1091）
						1. Determining Which Resources to Load（确定要加载的资源）（1092）
						2. PlayGo on the PlayStation 4（ PlayStation  4  上的  PlayGo）（1093）
					4. Memory Management for Object Spawning（对象生成的内存管理）（1093）
						1. OffLine Memory Allocation for Object Spawning（对象生成的离线内存分配）（1093）
						2. Dynamic Memory Management for Object Spawning（ 对象生成的动态内存管理）（1094）
					5. Saved Games（Saved Games）（1096）
						1. Checkpoints（检查点）（1097）
						2. Save Anywhere（ 保存在任何地方）（1097）
				5.  Object References and World Queries（对象引用和世界查询）（1098）
					1. Pointers（指针）（1098）
					2. Smart Pointers（ 智能指针）（1099）
					3. Handles（句柄）（1101）
					4. Game Object Queries（游戏对象查询）（1104）
				6. Updating Game Objects in Real Time（ 实时更新游戏对象）（1105）
					1. A Simple Approach (That Doesn’t Work)（一个简单的方法（不起作用））（1107）
						1. Maintaining a Collection of Active Game Objects（维护活动游戏对象的集合）（1108）
						2. Responsibilities of the Update() Function（Update()函数的职责）（1108）
					2. Performance Constraints and Batched Updates（性能约束和批量更新）（1109）
					3. Object and Subsystem Interdependencies（对象和子系统的相互依赖性）（1112）
						1. Phased Updates（分阶段更新）（1112）
						2. Bucketed Updates（ 分桶更新）（1114）
						3. Object State Inconsistencies and One-Frame-Off Lag（对象状态不一致和一帧关闭延迟）（1117）
						4. Object State Caching（对象状态缓存）（1119）
						5. Time-Stamping（时间戳）（1120）
				7. Applying Concurrency to Game Object Updates()（将并发应用于游戏对象更新）（1120）
					1. Concurrent Engine Subsystems（并发引擎子系统）（1120）
					2. Asynchronous Program Design（异步程序设计）（1121）
						1. When to Make Asynchronous Requests（何时发出异步请求）（1124）
					3. Job Dependencies and Degree of Parallelism（ 作业依赖性和并行度）（1124）
					4. Parallelizing the Game Object Model Itself（并行化游戏对象模型本身）（1126）
						1. Game Object Updates as Jobs（游戏对象更新为作业）（1127）
						2. Asynchronous Game Object Updates（异步游戏对象更新）（1129）
						3. Locking During Game Object Updates（游戏对象更新期间的锁定）（1130）
						4. Object Snapshots（对象快照）（1131）
						5. Handling Inter-Object Mutation（处理对象间突变）（1132）
						6. Future Improvements（未来的改进）（1132）
				8. Events and Message-Passing（事件和消息传递）（1133）
					1. The Problem with Statically Typed Function Binding（静态类型函数绑定的问题）（1133）
					2. Encapsulating an Event in an Object（ 将事件封装在对象中）（1135）
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
						1. Typical Characteristics of Game Scripting Languages（ 游戏脚本语言的典型特征）（1156）
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
						3. Receiving and Handling Events in Script（ 在脚本中接收和处理事件）（1170）
						4. Sending Events（发送事件）（1171）
						5. Object-Oriented Scripting Languages（面向对象的脚本语言）（1171）
						6. Scripted Finite State Machines（脚本化有限状态机）（1173）
						7. Multithreaded Scripts（多线程脚本）（1173）
				10. High-Level Game Flow（高级游戏流程）（1176）
		5. Conclusion（结论）（1178）
			1. You Mean There’s More?（你的意思是还有更多？）（1180）
				1. Some Engine Systems We Didn’t Cover（ 一些我们没有讨论的引擎系统）（1180）
					1. Movie Player（电影播放器）（1180）
					2. Multiplayer Networking（多人网络）（1181）
				2. Gameplay Systems（游戏系统）（1181）
					1. Player Mechanics（玩家机制）（1181）
					2. Cameras（相机）（1182）
					3. Artificial Intelligence（人工智能）（1183）
					4. Other Gameplay Systems（其他游戏系统）（1183）