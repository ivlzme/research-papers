**A chronologically ordered collection of papers on software analysis with a focus on concurrency, race detection, and partial ordering techniques.** (Original List from Paper list: Fundamentals of Software Analysis, Jeff Huang, Spring 2018, [https://parasol.tamu.edu/~jeff/course/689\_spring2018/papers.html](https://parasol.tamu.edu/~jeff/course/689_spring2018/papers.html))

## Partial Ordering
- _(DC analysis + Vindicator)_ [High-Coverage, Unbounded Sound Predictive Race Detection](http://web.cse.ohio-state.edu/~bond.213/vindicator-pldi-2018.pdf). Jake Roemer, Kaan Genç, Michael D. Bond. (PLDI 2018)
- _(Schedulable Happens-Before)_[What Happens-After the First Race? Enhancing the Predictive Power of Happens-Before Based Dynamic Race Detection](http://umathur3.web.engr.illinois.edu/papers/shb-oopsla2018.pdf). Dileep Kini, Umang Mathur, Mahesh Viswanathan. (OOPSLA 2018)
- _(Weak Causally Precedes)_ [Dynamic Race Prediction in Linear Time](https://arxiv.org/pdf/1704.02432.pdf). Dileep Kini, Umang Mathur, Mahesh Viswanathan. (PLDI 2017)
- _(CP-sub polynomial time)_ [An Online Dynamic Analysis for Sound Predictive Data Race Detection](http://web.cse.ohio-state.edu/~bond.213/raptor-tr.pdf). Jake Roemer, Michael D. Bond. (Technical Report OSU-CISRC-11/16-TR05, 2016)
- _(Maximal Causality)_ [Stateless Model Checking Concurrent Programs with Maximal Causality Reduction](https://parasol.tamu.edu/~jeff/academic/mcr.pdf). Jeff Huang. (PLDI 2015)
- _(Causally Precedes)_ [Sound Predictive Race Detection in Polynomial Time](https://users.soe.ucsc.edu/~cormac/papers/popl12a.pdf). Yannis Smaragdakis, Jacob M. Evans, Caitlin Sadowski, Jaeheon Yi, Cormac Flanagan. (POPL 2012)
- _(Lockset discipline)_ [Eraser: A Dynamic Data Race Detector for Multithreaded Programs](http://www.cs.washington.edu/homes/tom/pubs/eraser.pdf). Stefan Savage et al. (TOCS 1997)
- _(Happens-Before)_ [Time, Clocks, and the Ordering of Events in a Distributed System](https://lamport.azurewebsites.net/pubs/time-clocks.pdf). Leslie Lamport. (1978)

## Static Analysis
- [FlowDroid: Precise Context, Flow, Field, Object-sensitive and Lifecycle-aware Taint Analysis for Android Apps](http://www.bodden.de/pubs/far+14flowdroid.pdf). S. Arzt et al. (PLDI 2014)
- [Pick Your Contexts Well: Understanding Object-Sensitivity](http://plg.uwaterloo.ca/~olhotak/pubs/popl11b.pdf). Yannis Smaragdakis, Martin Bravenboer, and Ondrej Lhotak. (POPL 2011)
- [A few Billion Lines of code Later using static Analysis to find Bugs in the Real World](http://www.cs.columbia.edu/~junfeng/reliable-software/papers/coverity.pdf). Dawson Engler et al. (CACM 2010)
- [Effective Static Race Detection for Java](https://a4bf0b58-a-62cb3a1a-s-sites.googlegroups.com/site/gatechpag/pubs/pldi06.pdf?attachauth=ANoY7cpH-dDoODhsSnVk1EhxWVSVrh3vPd86prrxbqhXFWJ29KzQsDSSCRiezFtJst2pslOVHnUz_8QPyAya0QZqSKK2ot1iJBdVGv6AdpCXDzPzFnAHFTUK6XkjhrGfLyOmimlTcBVX0Y6tnKL6Cq7Ll7HOZ9tU0XYcK3OgBsJkCnorj4jZoL7vaY6-3DNatRragzngIF8qw2tbq17BWzAx_r9Br2A3FA%3D%3D&amp;attredirects=0). Mayur Naik, Alex Aiken, and John Whaley. (PLDI 2006)
- [Cloning-based context-sensitive pointer alias analysis using binary decision diagrams](http://www.cs.ucla.edu/~palsberg/course/cs232/papers/Whaley-pldi04.pdf). John Whaley and Monica S. Lam. (PLDI 2004)
- [A Type and Effect System for Atomicity](http://users.soe.ucsc.edu/~cormac/papers/pldi03.pdf). Cormac Flanagan and Shaz Qadeer. (PLDI 2003)
- [A Static Analyzer for Large Safety-Critical Software](http://dl.acm.org/citation.cfm?doid=781131.781153). Bruno Blanchet et al. (PLDI 2003)
- [Scalable Propagation-Based Call Graph Construction Algorithms](http://www.cs.ucla.edu/~palsberg/paper/oopsla00.pdf). Frank Tip and Jens Palsberg. (OOPSLA 2000)
- [Type-Based Race Detection for Java](http://users.soe.ucsc.edu/~cormac/papers/pldi03.pdf). Cormac Flanagan and Stephen N. Freund. (PLDI 2000)
- [Program Analysis via Graph Reachability](http://research.cs.wisc.edu/wpis/papers/tr1386.pdf). Thomas Reps. (ISLP 1997)

## Dynamic Analysis
- [EffectiveSan: Type and Memory Error Detection Using Dynamically Typed C/C++](https://arxiv.org/pdf/1710.06125.pdf). Gregory J. Duck, Roland H. C. Yap. (PLDI 2018)
- [AddressSanitizer: A Fast Address Sanity Checker](https://www.usenix.org/system/files/conference/atc12/atc12-final39.pdf). Konstantin Serebryany, Derek Bruening, Alexander Potapenko, Dmitry Vyukov. (USENIX ATC 2012)
- [All You Ever Wanted to Know About Dynamic Taint Analysis and Forward Symbolic Execution](https://edmcman.github.io/papers/oakland10.pdf). Edward J. Schwartz, Thanassis Avgerinos, and David Brumley. (OAKLAND 2010)
- [ThreadSanitizer -- data race detection in practice](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/35604.pdf). Konstantin Serebryany, Timur Iskhodzhanov. (WBIA 2009)
- [How to Shadow Every Byte of Memory Used by a Program](http://valgrind.org/docs/shadow-memory2007.pdf). N. Nethercote and J. Seward (VEE 2007)
- [Whole Execution Traces](http://dl.acm.org/citation.cfm?id=1038935). X. Zhang and R. Gupta. (MICRO 2004)
- [Static and Dynamic Analysis: Synergy and Duality](https://homes.cs.washington.edu/~mernst/pubs/staticdynamic-woda2003.pdf). Michael D. Ernst. (WODA 2003)
- [Precise Dynamic Slicing Algorithms](http://dl.acm.org/citation.cfm?id=776816.776855). X. Zhang and R. Gupta. (ICSE 2003)
- [Dynamically Discovering Likely Program Invariants to Support Program Evolution](http://www.cs.washington.edu/homes/mernst/pubs/invariants-tse2001.pdf). M. D. Ernst, J. Cockrell, W. G. Griswold, and D. Notkin. (TSE 2001)
- [Whole Program Paths](http://dl.acm.org/citation.cfm?id=301678). J. Larus. (PLDI 1999)
- [Efficient Path Profiling](http://dl.acm.org/citation.cfm?id=243857). T. Ball and J. Larus. (MICRO 1996)

## Symbolic Execution and Testing
- [A Survey of Symbolic Execution Techniques](https://arxiv.org/pdf/1610.00502.pdf). Roberto Baldoni, Emilio Coppa, Daniele Cono DÕElia, Camil Demetrescu, and Irene Finocchi. (arXiv last update: 2017)
- [Enhancing Symbolic Execution with Veritesting](http://research.microsoft.com/en-us/um/people/pg/public_psfiles/pldi2005.pdf). Thanassis Avgerinos, Alexandre Rebert, Sang Kil Cha, and David Brumley. (ICSE 2014)
- [Jalangi: A Selective Record-Replay and Dynamic Analysis Framework for JavaScript](http://srl.cs.berkeley.edu/~ksen/papers/jalangi.pdf). K. Sen, S. Kalasapur, T. Brutch, and S. Gibbs (FSE 2013)
- [Symbolic PathFinder: Symbolic Execution of Java Bytecode](https://ti.arc.nasa.gov/m/groups/rse/papers/p179-pasareanu.pdf). C. S. Pasareanu and N. Rungta. (ASE 2010)
- [Execution Synthesis: A Technique for Automated Software Debugging](http://dslab.epfl.ch/pubs/esd.pdf). Cristian Zamfir and George Candea. (EUROSYS 2010)
- [KLEE: Unassisted and Automatic Generation of High-Coverage Tests for Complex Systems Programs](http://www.stanford.edu/~engler/klee-osdi-2008.pdf). C. Cadar, D. Dunbar, and D. Engler. (OSDI 2008)
- [DART: Directed Automated Random Testing](http://research.microsoft.com/en-us/um/people/pg/public_psfiles/pldi2005.pdf). Patrice Godefroid, Nils Klarlund, and Koushik Sen. (PLDI 2005)

## Debugging and Bug Finding
- [Compiler Validation via Equivalence Modulo Inputs](http://vuminhle.com/pdf/pldi14-emi.pdf). Vu Le, Mehrdad Afshari, and Zhendong Su. (PLDI 2014)
- [Precise Memory Leak Detection for Java Software using Container Profiling](http://www.ics.uci.edu/~guoqingx/papers/xu-icse08.pdf). G. Xu and A. Rountev. (ICSE 2008)
- [Scalable Statistical Bug Isolation](http://dl.acm.org/citation.cfm?id=1065014). B. Liblit, M. Naik, A. X. Zheng, A. Aiken, and M. I. Jordan. (PLDI 2005)
- [Finding Bugs is Easy](http://www.cs.nyu.edu/~lharris/papers/findbugsPaper.pdf). David Hovemeyer and William Pugh. (SIGPLAN NOTICES 2004)
- [CP-Miner: A Tool for Finding Copy-paste and Related Bugs in Operating System Code](http://pages.cs.wisc.edu/~shanlu/paper/OSDI04-CPMiner.pdf). Z. Li, S. Lu, S. Myagmar, and Y. Y. Zhou. (OSDI 2004)
- [Simplifying and Isolating Failure-Inducing Input](https://www.st.cs.uni-saarland.de/publications/files/zeller-esec-1999.pdf). A. Zeller and R. Hildebrandt. (TSE 2002)
- [The SLAM Project: Debugging System Software via Static Analysis](https://www.ursuletz.com/~weimer/2011-6610/reading/p1-ball.pdf). Thomas Ball and Sriram K. Rajamani. (POPL 2002)

## Security
- [Meltdown](https://meltdownattack.com/meltdown.pdf). Moritz Lipp et al. (2018)
- [Spectre Attacks: Exploiting Speculative Execution](https://spectreattack.com/spectre.pdf). Paul Kocher et al. (2018)
- [Cimplifier: Automatically Debloating Containers](https://www.cs.colostate.edu/~ldecarli/docs/papers/fse17-cimplifier.pdf). Vaibhav Rastogi, Drew Davidson, Lorenzo De Carli, Somesh Jha, Patrick McDaniel (FSE 2017)
- [Code-Pointer Integrity](https://www.doc.ic.ac.uk/~cristic/papers/wit-sp-ieee-08.pdf). Volodymyr Kuznetsov, Laszl o Szekeres, Mathias Payer, George Candea, R. Sekar, Dawn Song (OSDI 2014)
- [Automatic exploit generation](http://security.ece.cmu.edu/aeg/aeg-current.pdf). T Avgerinos, SK Cha, A Rebert, EJ Schwartz, M Woo, D Brumley (CACM 2014)
- [Control-Flow Integrity Principles, Implementations, and Applications](https://users.soe.ucsc.edu/~abadi/Papers/cfi-tissec-revised.pdf). Martin Abadi, Mihai Budiu, òlfar Erlingsson, Jay Ligatti (TISSEC 2009)
- [Preventing memory error exploits with WIT](https://www.doc.ic.ac.uk/~cristic/papers/wit-sp-ieee-08.pdf). Periklis Akritidis, Cristian Cadar, Costin Raiciu, Manuel Costa, Miguel Castro (IEEE S&amp;P 2008)
- [Securing software by enforcing data-flow integrity](https://timharris.uk/papers/2006-osdi.pdf). Miguel Castro, Manuel Costa, Tim Harris (OSDI 2006)
- [Remote timing attacks are practical](https://crypto.stanford.edu/~dabo/pubs/papers/ssl-timing.pdf). David Brumley, Dan Boneh (USENIX SECURITY 2003)

## Program Analysis Frameworks
- [Angr -- The Next Generation of Binary Analysis](https://github.com/angr/angr). Fish Wang, Yan Shoshitaishvili (IEEE S&amp;P 2016)
- [BAP: A binary analysis platform](https://github.com/BinaryAnalysisPlatform/bap). David Brumley, Ivan Jager, Thanassis Avgerinos, Edward J Schwartz (CAV 2011)
- [Soot: The Soot framework for Java program analysis: a retrospective](http://www.bodden.de/pubs/lblh11soot.pdf). Patrick Lam, Eric Bodden, Ondrej Lhotak, and Laurie Hendren (CETUS 2011)
- [WALA: Static and Dynamic Program Analysis using WALA](http://wala.sourceforge.net/files/PLDI_WALA_Tutorial.pdf). Julian Dolby and Manu Sridharan. (PLDI Tutorial 2010)
- [RoadRunner: The RoadRunner Dynamic Analysis Framework for Concurrent Programs](http://slang.soe.ucsc.edu/cormac/papers/paste10.pdf). Cormac Flanagan and Stephen N. Freund. (PASTE 2010)
- [CalFuzzer: An Extensible Active Testing Framework for Concurrent Programs](http://srl.cs.berkeley.edu/~ksen/calfuzzer/). P. Joshi, M. Naik, C.-S. Park, and K. Sen. (CAV 2009)
- [Valgrind: A Framework for Heavyweight Dynamic Binary Instrumentation](http://valgrind.org/docs/valgrind2007.pdf). N. Nethercote and J. Seward. (PLDI 2007)
- [Pin: Building Customized Program Analysis Tools with Dynamic Instrumentation](http://www.cs.ucr.edu/~heng/teaching/cs260-winter2017/luk05pin.pdf). C. K. Luk et al. (PLDI 2005)
- [Jikes RVM: The Jikes Research Virtual Machine project: Building an open-source research community](http://people.cs.umass.edu/~moss/papers/ibm-systems-2005-jikes-rvm-open-source.pdf). B. Alpern et al. (IBM Systems Journal 2005)
- [LLVM: A Compilation Framework for Lifelong Program Analysis &amp; Transformation ](http://llvm.org/pubs/2004-01-30-CGO-LLVM.html). Chris Lattner and Vikram Adve. (CGO 2004)
- [Java PathFinder: Test Input Generation with Java PathFinder](https://users.ece.utexas.edu/~khurshid/papers/JPF-issta04.pdf). W. Visser, C. S. Pasareanu, and S. Khurshid. (ISSTA 2004)

## Concurrency in Practice
- [Java concurrency bug patterns for multicore systems](http://www.ibm.com/developerworks/library/j-concurrencybugpatterns/j-concurrencybugpatterns-pdf.pdf). Zhi Da Luo, Yarden Nir-Buchbinder, and Raja Das. (IBM 2010)
- [Learning from Mistakes - A Comprehensive Study on Real World Concurrency Bug Characteristics](http://dl.acm.org/citation.cfm?id=1346323). S. Lu, S. Park, E. S. and Y. Y. Zhou. (ASPLOS 2008)
- [Java Concurrency in Practice](http://www.periodicooficial.oaxaca.gob.mx/files/2011/05/EXT02-2011-05-19.pdf). Brian Goetz, Tim Peierls, Joshua Bloch, Joseph Bowbeer, David Holmes, and Doug Lea. (BOOK 2006)
- [Concurrent Bug Patterns and How to Test Them](https://ieeexplore.ieee.org/document/1213511). Eitan Farchi, Yarden Nir, Shmuel Ur. (IPDPS 2003)

## Data Races
- [RacerD: Compositional Static Race Detection](https://ilyasergey.net/papers/racerd-oopsla18-preprint.pdf). Sam Blackshear, Nikos Gorogiannis, Peter W. O&#39;Hearn, Ilya Sergey. (OOPLSA 2018)
- [ECHO: Instantaneous In Situ Race Detection in the IDE](https://parasol.tamu.edu/~jeff/academic/echo.pdf).  Sheng Zhan, Jeff Huang. (FSE 2016)
- [What&#39;s the Optimal Performance of Precise Dynamic Race Detection?--A Redundancy Perspective](https://parasol.tamu.edu/~jeff/academic/rex.pdf). Jeff Huang, Arun K. Rajagopalan. (ECOOP 2015)
- [Commutativity Race Detection](http://www.srl.inf.ethz.ch/papers/pldi14-commutativity.pdf). Dimitar Dimitrov, Veselin Raychev, Martin Vechev, and Eric Koskinen. (PLDI 2014)
- [Maximal Sound Predictive Race Detection With Control Flow Abstraction](http://fsl.cs.illinois.edu/FSL/papers/2014/huang-meredith-rosu-2014-pldi/huang-meredith-rosu-2014-pldi-public.pdf). Jeff Huang, Patrick Meredith, and Grigore Rosu. (PLDI 2014)
- [Practical Static Race Detection for Java Parallel Loops](http://dig.cs.illinois.edu/papers/Iterace.pdf). Cosmin Radoi, Danny Dig. (ISSTA 2013)
- [Data Races vs. Data Race Bugs: Telling the Difference with Portend](http://dslab.epfl.ch/pubs/portend.pdf). Baris Kasikci, Cristian ZamÞr, and George Candea. (ASPLOS 2012)
- [Detecting and Surviving Data Races using Complementary Schedules](http://web.eecs.umich.edu/~nsatish/papers/SOSP-11-Frost.pdf). K. Veeraraghavan, P. M. Chen, J. Flinn, S. Narayanasamy. (SOSP 2011)
- [Locksmith: Practical Static Race Detection for C](http://www.cs.umd.edu/~mwh/papers/locksmith-journal.pdf). Polyvios Pratikakis, Jeffrey S. Foster, Michael Hicks. (ACM Transactions on Programming Languages and Systems 2011)
- [Effective Data-Race Detection for the Kernel](http://research.microsoft.com/pubs/139266/DataCollider%20-%20OSDI2010.pdf). John Erickson, Madanlal Musuvathi, Sebastian Burckhardt, Kirk Olynyk. (OSDI 2010)
- [Pacer: Proportional Detection of Data Races](http://www.cse.ohio-state.edu/~mikebond/pacer-pldi-2010.pdf). Michael D. Bond, Katherine E. Coons, Kathryn S. McKinley. (PLDI 2010)
- [FastTrack: Efficient and Precise Dynamic Race Detection](http://slang.soe.ucsc.edu/cormac/papers/pldi09.pdf). Cormac Flanagan, Stephen N. Freund. (PLDI 2009)
- [LiteRace: Effective Sampling for Lightweight Data-Race Detection](http://www.cs.columbia.edu/~junfeng/reliable-software/papers/literace.pdf). Daniel Marino, Madanlal Musuvathi, Satish Narayanasamy. (PLDI 2009)
- [Race Directed Random Testing of Concurrent Programs](http://dl.acm.org/citation.cfm?id=1375584). Koushik Sen. (PLDI 2008)
- [RELAY: Static Race Detection on Millions of Lines of Code](https://cseweb.ucsd.edu/~lerner/papers/relay.pdf). Jan Wen Voung, Ranjit Jhala, Sorin Lerner. (FSE 2007)
- [Goldilocks: A Race and Transaction-Aware Java Runtime](https://www.cs.purdue.edu/homes/xyzhang/fall07/Papers/goldilock.pdf). Tayfun Elmas, Shaz Qadeer, Serdar Tasiran. (PLDI 2007)
- [RacerX: effective, static detection of race conditions and deadlocks](https://web.stanford.edu/~engler/racerx-sosp03.pdf). Dawson Engler, Ken Ashcraft. (SOSP 2003)
- [Hybrid Dynamic Data Race Detection](http://web5.cs.columbia.edu/~junfeng/09fa-e6998/papers/hybrid.pdf). Robert O&#39;Callahan and Jong-Deok Choi. (PPOPP 2003)
- [Efficient on-the-fly data race detection in multithreaded C++ programs](https://dl.acm.org/citation.cfm?id=781529). Eli Pozniansky, Technion, Assaf Schuster. (PPoPP 2003)
- [Eraser: A Dynamic Data Race Detector for Multithreaded Programs](http://www.cs.washington.edu/homes/tom/pubs/eraser.pdf). Stefan Savage et al. (TOCS 1997)
- [What are Race Conditions: Some Issues and Formalizations](ftp://ftp.cs.wisc.edu/paradyn/papers/what-are-races.pdf). Robert Netzer and Barton Miller. (LOPLAS 1992)

## Atomicity, Serializability, and Linearizability
- [Detecting Atomic-Set Serializability Violations in Multithreaded Programs through Active Randomized Testing](http://www.cs.cityu.edu.hk/~wkchan/papers/icse10-lai+cheung+chan.pdf). Zhifeng Lai et al. (ICSE 2010)
- [Line-Up: A Complete and Automatic Linearizability Checker](http://research.microsoft.com/en-us/projects/chess/pldi015-burckhardt.pdf). Sebastian Burckhardt, Chris Dern, Madanlal Musuvathi, Roy Tan. (PLDI 2010)
- [CTrigger: Exposing Atomicity Violation Bugs from Their Hiding Places](http://www.stanford.edu/class/cs240/readings/asplos092-zhou.pdf). Soyeon Park, Shan Lu, and Yuanyuan Zhou. (ASPLOS 2009)
- [Velodrome: A Sound and Complete Dynamic Atomicity Checker for Multithreaded Programs](http://slang.soe.ucsc.edu/cormac/papers/pldi08.pdf). C. Flanagan, S. N. Freund, J. Yi. (PLDI 2008)
- [Atomizer: A Dynamic Atomicity Checker for Multithreaded Programs](http://slang.soe.ucsc.edu/cormac/papers/scp08.pdf). Cormac Flanagan, Stephen N. Freund. (POPL 2004)

## Deadlocks
- [ConLock: A Constraint-Based Approach to Dynamic Checking on Deadlocks in Multithreaded Programs](http://www.cs.cityu.edu.hk/~wkchan/papers/icse2014-cai+wu+chan.pdf). Yan Cai et al. (ICSE 2014)
- [A Randomized Dynamic Program Analysis Technique for Detecting Real Deadlocks](http://dl.acm.org/citation.cfm?id=1542489). Pallavi Joshi, Chang-Seo Park, Koushik Sen, Mayur Naik. (PLDI 2009)
- [Effective Static Deadlock Detection](https://a4bf0b58-a-62cb3a1a-s-sites.googlegroups.com/site/gatechpag/pubs/icse09.pdf?attachauth=ANoY7cpkTq5s4jfWE1eSi9fJhSJO8_bEieSj5wMP0f3l8UtpjCMYvm90bxLkLfm8JRnNcs7gmrO7f8LnR_THz_lua3abIuBTfStwg_wcCwzbS1dLOH3vYtfJsTZUzufna5NldRpC1yvi3WNnCbOBgaWnjv6yylClzaapD1Y7N2xe27u7oJMht1Gx_jnpXIILrXVybcb2Ruq6puhBw7KWDQiMUiixEmYycQ%3D%3D&amp;attredirects=0). Mayur Naik, Chang-Seo Park, Koushik Sen, and David Gay. (ICSE 2009)
- [Gadara: Dynamic Deadlock Avoidance for Multithreaded Programs](http://www.usenix.org/events/osdi08/tech/full_papers/wang/wang.pdf). Yin Wang et al. (OSDI 2008)

## Partial Order Reduction
- [Stateless Model Checking Concurrent Programs with Maximal Causality Reduction](https://parasol.tamu.edu/~jeff/academic/mcr.pdf). Jeff Huang. (PLDI 2015)
- [Dynamic partial-order reduction for model checking software](https://users.soe.ucsc.edu/~cormac/papers/popl05.pdf). C. Flanagan and P. Godefroid. (POPL 2005)
- [State Space Reduction using Partial Order Techniques](https://link.springer.com/article/10.1007/s100090050035). E.M. Clarke, O. Grumberg, M. Minea, D. Peled. (STTT 1998)
- [Partial-Order Methods for the Verification of Concurrent Systems: An Approach to the State-Explosion Problem](https://pdfs.semanticscholar.org/acaf/9c18e5711d4fd63144953292d43fb3fdac92.pdf). P Godefroid. (PhD thesis, University of LiÃ´lge., 1996)

## Testing, Isolation, and Repairing
- [Maple: A Coverage-Driven Testing Tool for Multithreaded Programs](http://web.eecs.umich.edu/~nsatish/papers/OOPSLA-12-Maple.pdf). Jie Yu, Satish Narayanasamy, Cristiano Pereira, and Gilles Pokam. (OOPSLA 2012)
- [Automated Concurrency-Bug Fixing](https://www.usenix.org/system/files/conference/osdi12/osdi12-final-103.pdf). Guoliang Jin, Wei Zhang, Dongdong Deng, Ben Liblit, and Shan Lu. (OSDI 2012)
- [AXIS: Automatically Fixing Atomicity Violations Through Solving Control Constraints](http://dl.acm.org/citation.cfm?id=2337259). Peng Liu and Charles Zhang. (ICSE 2012)
- [Laws of Order: Expensive Synchronization in Concurrent Algorithms Cannot be Eliminated](http://infoscience.epfl.ch/record/161286/files/popl168gf-attiya.pdf). Hagit Attiya et al. (POPL 2011)
- [ISOLATOR: Dynamically Ensuring Isolation in Concurrent Programs](http://research.microsoft.com/pubs/72307/Isolator%20-%20Dynamically%20Ensuring%20Isolation%20in%20Concurrent%20Programs.pdf). Sriram Rajamani et al. (ASPLOS 2009)
- [Finding and Reproducing Heisenbugs in Concurrent Programs](http://research.microsoft.com/pubs/77961/osdi2008-CHESS.pdf). Madanlal Musuvathi et al. (OSDI 2008)
- [Iterative Context Bounding for Systematic Testing of Multithreaded Programs](http://research.microsoft.com/en-us/projects/chess/pldi07-iterativecontextbounding.pdf). Madan Musuvathi and Shaz Qadeer. (PLDI 2007)

## Memory Consistency Models
- [End-To-End Sequential Consistency](http://www.cs.ucla.edu/~todd/research/isca12.pdf). Abhayendra Singh, Satish Narayanasamy, Daniel Marino, Todd Millstein, and Madanlal Musuvathi. (ISCA 2012)
- [A Case for an SC-Preserving Compiler](http://web.eecs.umich.edu/~nsatish/papers/PLDI-11-SC-Preservation.pdf). Daniel Marino, Abhayendra Singh, Todd Millstein, Madanlal Musuvathi, and Satish Narayanasamy. (PLDI 2011)
- [A Primer on Memory Consistency and Cache Coherence](http://dl.acm.org/citation.cfm?id=2028905). Daniel J. Sorin, Mark D. Hill, and David A. Wood. (BOOK 2011)
- [Memory Models: A Case for Rethinking Parallel Languages and Hardware](http://cacm.acm.org/magazines/2010/8/96610-memory-models-a-case-for-rethinking-parallel-languages-and-hardware/pdf). Sarita V. Adve, Hans-J. Boehm. (CACM 2010)
- [Adversarial Memory For Detecting Destructive Races](http://slang.soe.ucsc.edu/cormac/papers/pldi10.pdf). Cormac Flanagan, Stephen N. Freund. (PLDI 2010)
- [DRFx: A Simple and Efficient Memory Model for Concurrent Programming Languages](http://www.eecs.umich.edu/~nsatish/papers/PLDI-10-DRFx.pdf). Daniel Marino et al. (PLDI 2010)
- [MemSAT: Checking Axiomatic SpeciÞcations of Memory Models](http://people.csail.mit.edu/emina/pubs/memsat.pldi10.pdf). Emina Torlak, Mandana Vaziri, and Julian Dolby. (PLDI 2010)
- [The Java Memory Model](http://rsim.cs.illinois.edu/Pubs/popl05.pdf). Jeremy Manson, William Pugh, Sarita V. Adve. (POPL 2005)

## Multithreaded Record and Replay
- [CLAP: Recording Local Executions to Reproduce Concurrency Failures](http://0391b35.netsolhost.com/academic/clap.pdf). Jeff Huang, Charles Zhang, and Julian Dolby. (PLDI 2013)
- [DDOS: Taming Nondeterminism in Distributed Systems](http://homes.cs.washington.edu/~luisceze/publications/asplos021-hunt.pdf). Nicholas Hunt, Tom Bergan, Luis Ceze, Steven D. Gribble. (ASPLOS 2013)
- [DoublePlay: Parallelizing Sequential Logging and Replay](http://web.eecs.umich.edu/~nsatish/papers/ASPLOS-11-DoublePlay.pdf). Kaushik Veeraraghavan et al. (ASPLOS 2011)
- [LEAP: Lightweight Deterministic Multi-processor Replay of Concurrent Java Programs](http://www.cs.ust.hk/~charlesz/academic/leap.pdf). Jeff Huang, Peng Liu, and Charles Zhang. (FSE 2010)
- [PinPlay: A Framework for Deterministic Replay and Reproducible Analysis of Parallel Programs](http://dl.acm.org/citation.cfm?id=1772958). Harish Patil et al. (CGO 2010)
- [PRES: Probabilistic Replay with Execution Sketching on Multiprocessors](http://opera.ucsd.edu/paper/pres-sosp09.pdf). Soyeon Park et al. (SOSP 2009)

## Deterministic Multithreading
- [Dthreads: Efficient Deterministic Multithreading](http://people.cs.umass.edu/~emery/pubs/dthreads-sosp11.pdf). Tongping Liu, Charlie Curtsinger, Emery D. Berger. (SOSP 2011)
- [PARROT: A Practical Runtime for Deterministic, Stable, and Reliable Threads](http://www.cs.columbia.edu/~junfeng/papers/parrot-sosp13.pdf). Heming Cui et al. (ASPLOS 2010)
- [CoreDet: A Compiler and Runtime System for Deterministic Multithreaded Execution](http://www.cs.washington.edu/homes/tbergan/papers/asplos10-coredet.pdf). Tom Bergan et al. (ASPLOS 2010)
- [Kendo: Efficient Deterministic Multithreading in Software](http://people.csail.mit.edu/mareko/asplos073-olszewski.pdf). Marek Olszewski, Jason Ansel, Saman Amarasinghe. (ASPLOS 2009)
- [DMP: Deterministic Shared Memory Multiprocessing](http://www.cs.washington.edu/homes/luisceze/publications/asplos004-devietti.pdf). Joseph Devietti, Brandon Lucia, Luis Ceze, Mark Oskin. (ASPLOS 2009)

## Concurrency Programming Models
- [Grace: Safe Multithreaded Programming for C/C++](http://www.cs.umass.edu/~emery/pubs/grace-oopsla09.pdf). Emery D. Berger, Ting Yang, Tongping Liu, Gene Novark. (OOPSLA 2009)
- [Parallel Programming Must Be Deterministic by Default](https://www.usenix.org/legacy/event/hotpar09/tech/full_papers/bocchino/bocchino.pdf). Robert L. Bocchino Jr., Vikram S. Adve, Sarita V. Adve, Marc Snir. (HotPar 2009)
- [Associating Synchronization Constraints with Data in an Object-Oriented Language](https://cs.uwaterloo.ca/~ftip/pubs/popl2006.pdf). Mandana Vaziri, Frank Tip, and Julian Dolby. (POPL 2006)

## Transactional Memory
- [Using Hardware Memory Protection to Build a High-Performance, Strongly Atomic Hybrid Transactional Memory](http://www.cs.illinois.edu/~zilles/papers/ufo_hybridTM.isca2008.pdf). L. Baugh et al. (ISCA 2008)
- [Enforcing Isolation and Ordering in STM](https://homes.cs.washington.edu/~djg/papers/tm_pldi07.pdf). Tatiana Shpeisman et al. (PLDI 2007)
- [LogTM: Log-based Transactional Memory](http://research.cs.wisc.edu/multifacet/papers/hpca06_logtm.pdf). Kevin E. Moore, Jayaram Bobba, Michelle J. Moravan, Mark D. Hill, and David A. Wood. (HPCA 2006)
- [Hybrid Transactional Memory](http://pages.cs.wisc.edu/~david/courses/cs758/Fall2009/papers/damron_hytm_asplos2006.pdf). Peter Damron, Alexandra Fedorova, Yossi Lev, Victor Luchangco, Mark Moir, and Daniel Nussbaum. (ASPLOS 2006)
