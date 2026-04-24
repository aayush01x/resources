# Intern prep resources

## SWE/SDE 
1. Leetcode (and/or) Interviewbit, Interviewbit already has structured roadmap kind of thing of topics and lot of leetcode sheets are also pretty easily available on the internet.
2. Give codeforces/atcoder contests, now companies have started to increase difficulty of the problems they ask, so better to practice some non-conventional algo problems.
3. CSES is also a great resource to practice topic wise problems. If you are somewhot comfortable with Leetcode/Interviewbit, better to practice this. 
4. Coming to topics, OAs and interviews wont ask anything ahead of Graphs and DP. There might be 1 or 2 outliers though which may get into Segtree etc. 
5. You may learn C++ but thats pretty optional.
----
## Quant Dev
1. DSA/CP - see SWE section.
2. Learn C++ in depth, OAs and interviews both ask questions related to it. 
3. Learn CS fundamentals if time permits. 

### C++
#### Important topics in C++
1. OOPs - Inheritance, Polymorphism, Encapsulation, Abstraction, Constructors, Destructors, Rule of 5, Virtual functions, Copy semantics, etc.
2. Templates
3. STL - Vectors, Maps, Sets, Algorithms, etc.
4. Smart Pointers
5. RAII
6. Move Semantics
7. Concurrency - Threads, Mutexes, Semaphores

#### Resources for C++
1. [learncpp.com](https://www.learncpp.com/)
2. Cherno's C++ series, Jason Turner's series.
3. bequant.dev roadmap
4. Some relevant CPPCon talks
5. Nice collection of notes and resources - https://github.com/Shivam5022/Knowledgebase-SV (see C++ section)

#### Practice and Implementation
- Implement basic data structures in C++ (e.g., circular queue, `unique_ptr`, `shared_ptr`).
- Analyze tradeoffs between different implementation strategies as these will be asked in interviews with good firms.
- Understand memory allocation: identify which parts of a data structure are on the stack versus the heap.
- Look into internal implementations of common STL data structures, what things do they store, what algos they use etc.

### CS Fundamentals
These mostly don't appear in depth much with oncampus companies. But its good to have some knowledge if you have time. 

#### OS
Processes, Threads, Concurrency, Synchronization, Deadlocks, Scheduling, Memory Management, File Systems, Virtual Memory, etc.
Resource - OSTEP, Lectures from CS330 - [Link](https://iitk-my.sharepoint.com/personal/bsingh23_iitk_ac_in/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fbsingh23%5Fiitk%5Fac%5Fin%2FDocuments%2FCS330&ga=1) 

#### DBMS
Relational Algebra, SQL, Normalization, Transactions, ACID Properties, Concurrency Control, Indexing, etc.

#### Networking
OSI Model, TCP/IP Model, HTTP, DNS, Sockets, etc.

### Firm wise expectations/experiences
1. Optiver - SWE OA round had some fast mcq type questions on algos, and very basic CS fundamentals - OS, DBMS, Networking. Apart from that, there was one coding problem which wasn't very tough, just had a very long story and had to think what data structure is best to use. GD round was quant like only, no swe questions.
2. IMC - OA round had 2/3 problems, very implementation based. They shortlist lot of people for GD round. In GD round, they give a code snippet and ask you to find bugs, optimize it etc. The code was in C++, related to processing of orders in trading, and used knowledge of concurrency - threads etc. Also knowledge of algos used in Scheduling in Operating system would have helped.
3. Graviton - 2-3 1500-1900 type CF questions were given in pen-paper format.
4. Atlas - Pretty hard 4 cp questions in the OA Round. In interview, was asked to implement some data structure in C++, move semantics, Networking(DHCP, congestion control etc), garbage collector.
5. Alphagrep - OA had easy-medium problems, ig interview round was based a bit on C++ knowledge and some DSA.
6. Jump - OA has Implementation problems. For interview, should be pretty thorough with CS fundamentals and C++.
7. Quantbox - Had lot of C++, CS fundamentals knowledge problems in OA, but everyone pretty much everyone gpted them.
----
## Quant Trader/Researcher
1. Practice fast maths - Zetamac pretty much does the job. Although, no test would directly be testing this. 
2. Practice probability, combinatorics, expectation problems and puzzles.
3. Look at market making, bid-ask spread, arbitrage etc.

#### Resources
1. Xinfeng Zhou's A Practical Guide to Quantitative Finance Interviews (Ch 1,2,3,4,5)
2. 50 Challenging Problems in Probability
3. Brainstellar
4. Puzzledquant - although has mostly repeated problems from other sources, still have some new problems, and also really nice to learn about new approaches through comments sometimes. This sheet contains all problems(even the locked ones) - [Link](https://docs.google.com/spreadsheets/d/10oZ7wG2qD2xRxd6ksAYYDCHBDZu8DTTr/edit?usp=sharing&ouid=105948000423544987246&rtpof=true&sd=true).
5. Market making - [1](https://www.tradermath.org/knowledge-base/make-me-a-market-guide), [2](https://github.com/mikinty/Trading-Interview-Questions/blob/master/chapters%2Fmarket.md), [3](https://www.janestreet.com/probability-markets/)
Optional - 
6. quantguide.io
7. Gurmeet's Puzzles
8. Dice Problems: https://www.karlin.mff.cuni.cz/~nagy/NMSA202/dice1.pdf
9. https://www.math.lsu.edu/~smolinsk/Quant_Interview_Prep.pdf 

**General Recommendations**: 
1. While practicing, sort problems into some categories into your mind and try to make a generic framework. After a point, every problem would start to look like some variant of a problem you've already solved.
2. While solving a new problem, try to look for other solutions on internet, like on mathstackexchange or puzzlestackexchange. Lot of times you will get faster, and very nicer solutions than the conventional ones. 
3. Maintaining notes while solving problems would be helpful in the end. 

----
## Applying Offcampus
1. Make a nice resume, mentioning all your achievements, projects, internships etc. Keep it to 1 page and relevant to the job description. 
2. Look for openings here - https://github.com/northwesternfintech/2027QuantInternships . These repo only includes link for US/UK openings mostly, but try looking for any openings in general of the mentioned firms. Apply anyway, even if you think getting OA/interview is not possible.