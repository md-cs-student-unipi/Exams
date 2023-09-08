# Exams | MSc in Computer Science @ Unipi
Collection of oral questions and exam material

**Template**
<details>
  <summary>:us: 2019-20</summary>

- Your questions here... (leave don't remove spaces for a correct visualization)

</details>


## ADVANCED DATABASES
<details>
  
  <summary>:it: 2020-21</summary>
  
  - Perché un indice multidimensionale è più efficiente di un indice combinato su 2 dimensioni per query spaziali?
  
  - Che cosa sono gli istogrammi e a che cosa servono nei RDBMS?
  
  - Quali vantaggi e svantaggi ha l'organizzazione sequenziale?
  
  - Parlare di 2-Phase Commit: come viene gestita dal coordinatore la mancata ricezione di un messaggio? Cosa presume? Qual è il problema principale di questo protocollo? (Se il coordinatore fallisce dopo aver ricevuto un ready da parte di un partecipante)
  
  - Descrivere l'indice combinato (multi-attributo)
  
  - Parlare di 2-Phase Lock
  
  - Che cos'è una phantom lock?
  
  - Perché nel G-tree uno dei 2 alberi non è memorizzato su disco?
  
  - A che cosa serve avere lock multigranularità?
  
  - Parlare delle tecniche di hashing dinamico. Qual è il problema del linear hash?
  
  - Perché la nozione di "riconciliazione" di un valore è propria dei sistemi NoSQL e non dei DBMS tradizionali?
  
  - In quali situazioni ha senso usare un sistema NoSQL?
  
  - Qual è la differenza tra la progettazione dello schema concettuale di un database e quello di una data warehouse?
  
  - In un database distribuito, come posso gestire la consistenza distribuita?
  
  - In un columnar database, come sono memorizzate le colonne su disco? Il modo di memorizzare i dati su una singola pagina è rilevante a questi fini?
  
  - Quali similitudini e differenze ci sono tra un sistema parallelo con architettura shared-nothing e un sistema distribuito?
  
  - Perché si usa la formula di Cardenas? Quando ha senso approssimarla con il minimo?
  
  - Qual è il momento critico del protocollo 2-Phase Commit? Se il coordinatore muore proprio in questo momento, i partecipanti si scambiano messaggi tra di loro: cosa possono fare? nel caso in cui dovessero eleggere un nuovo coordinatore, che problema si può verificare? (Che il vecchio coordinatore torni online durante l'elezione di quello nuovo)
  
  - Nella progettazione di un database distribuito, cos'è la progettazione della distribuzione dei dati? E la progettazione dell'allocazione dei dati?
  
  - Perchè la scelta di default per la creazione di tabelle è heap file + indici?
</details>

<details>
  <summary>:us: 2020-21</summary>
  
  - Why a multidimensional index is more efficient than a combined index on the 2 dimensions?
  
  - What are histograms and why are they needed in RDBMS?
  
  - What are advantages and disadvantages of the sequential organization?
  
  - Explain 2-Phase Commit: how the coordinator handles a failure receiving a message? What does it assume? What is the main issue with this protocol?
  
  - Describe the combined (multi-attribute) index
  
  - Explain the 2-Phase Lock protocol
  
  - What's a Phantom Lock?
  
  - Why one of the two trees used in the G-tree is not stored on disk?
  
  - Why RDBMS use multi-granularity locks?
  
  - Talk about dynamic hashing. What's the main problem with linear hash?
  
  - Why the notion of "reconciliation" is associated to NoSQL systems and not RDBMSs?
  
  - In what scenarios we may choose a NoSQL system?
  
  - What's the difference between conceptual schema planning in a traditional database and in a data warehouse?
  
  - In a distributed database, how can we manage distributed consistency?
  
  - In columnar databases, how the columns are actually stored on disk? The way in wich we store the values inside the columns is actually important? Why? What we try to optimize with columnar DBs?
  
  - What are the similarities and differences between shared-nothing parallel architectuure and distributed architecture?
  
  - Why do we introduced the Cardenas formula? When can we simply approximate it with min?
  
  - What's the critical phase of 2-Phase Commit? If the coordinator dies exactly during this phase, how the participants can interact each other to try and continue? If they try and elect a new coordinator, what are the problems? (The old coordinator may restart during the election of the new one)
  
  - In distributed databases, what's data distribution design? And what's data allocation design?
  
  - Why the default choice for database tables is the heap organization?
</details>

## ADVANCED PROGRAMMING
<details>
  <summary>:us: 2018-19</summary>

Topic chosen by the student: Python (almost all, excluding GIL)

Questions on the assignments
- Given a bean, how can we tell what is its public API?
- Question about complexity of some haskell function. What are the problems between arrays and generics in Java? What happens with generic at runtime/after compilation?
- Is Python more OO or more functional, according to your opinion?

Questions on the syllabus
- Explain the concept (with written example) of covariance and contravariance in a language with universal polymorphism and explain in what cases their use is safe
- Explain inversion of control and dependecy injection
- What is lazy evalutaion in haskell and explain the spirit of IO Monads

------------------------------

Topic chosen by the student: lambda expressions in Java

Questions on Java
- What are streams in java?
- Example of lambdas in a context different from streams
- What are functional interfaces?
- How the java compiler manges lambdas?
- Differences between component, packages and classes
- Talk about the lifecycle of a sw component
- How can we interact with java beans?
- How can Netbeans (or another builder tool) provides "live interaction" with a bean?
- What kind of properties a bean can have?

Questions on Haskell
- What is "Functor" in haskell?
- What relationships there are between functor and maybe type class?
- Lazyness in haskell

Question on Python
- What are python decorator?
- How can we write functions with a variable number of arguments

Other questions
- Describe the different kind of parameter passing strategies
- What is memoization?

------------------------------

Topic chosen by the student: JVM internals and JVM instruction set.  
_For this exam, most of the questions were asked during the presentation of the topic chosen by the student._

Questions on Java
- Memory management
- How are lambda expressions implemented?
- Talk about streams

Question on Python
- What is GIL?
- Talk about decorators and higher order functions in general
- Namespaces and scopes
- What does the "@staticmethod" decorator do?

Other questions
- Differences between "reduce" in functional programming and "collect" in the Java Stream API
- Give an example of list comprehension and write a function using a functional language that does the same thing, using combinators such as filter, foldr, map ecc

</details>


## ADVANCED SOFTWARE ENGINEERING
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## ALGORITHM DESIGN
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## ALGORITHM ENGINEERING
<details>
  <summary>:it: Jan 2021</summary>
  
+ mi sa parlare del bloom filter? qual'è l'errore ottimo che si fa quando si considerano le funzioni? 
+ cos'è un ternary search tree?
+ dimostrazione lower bound permuting
+ cooko-hasing: celle vuote + piene : c'è un modo per compattare in maniera efficiente per usare i vetori binari rank and select?

---

+ cos'è una classe di funzioni hash universali? dove ci serve?
+ algoritmo che fa un campionamento da uno stream di un elemento su n elementi. idea della dimostrazione per il caso di m elementi invece che 1
+ three-way partition: vantaggio rispetto ai classici metodi che usano le partizioni in due
+ definizione di minimal order perfect hashing
+ huffman: lunghezza in media di un codeword e in quale range, entropia
+ se ho un vettore ordinato di key e voglio estrarre la chiave k-esima accedo a k, e se non è ordinato come faccio ad accedere alla k-esima?

---

+ definisci il bloom filter
+ example of universal hash function + dimostrazione that it is an UHF
+ instead of using arithm. coding., how can i improve the extra bit of huffman?
+ define the treap. how do you search for a key in a treap?

---

+ treap: how do you solve split and merge operations? build a treap of logarithmic height: the way to build the treap balanced. prove that in this way the average height is logarithmic
+ what is a suffix array?
+ do you know elias-fano?

---

+ come venivano trovate le copie più lunghe di elias-fano?
+ lz77
+ p-for-delta

</details>
  
## ARTIFICIAL INTELLIGENCE FUNDAMENTALS

<details>
  <summary>:us: 2021-22</summary>

  - Talk about KR&R in general and its connection with classical logic. What is the problem of classical logic? (monotonicity)

  - Talk about the CWA, definition. Is it always consistent? (Generalized CWA)

  - What is a random variable?

  - Given a set of random variables, write down the formula for the full joint distribution.

  - Joint distribution of two variables. What is the probability when the two random variables are independent?
  
  - Talk about non monotonic reasoning

  - Which problems does it cause? Define it in a formal way (written). Is ordinary logic monotonic?

  - What about default logic?

  - Definition of CWA.

  - How is it used for defaults?

  - Talk about the main limits of FOL?

  - Example of contradiction induced by non monotonic representations.

  - Example of non monotonic reasoning.

  - What is the fundamental tradeoff of KR?

  - Compare FOL and description logic.

  - Can all FOL formulas be translated into Horn Clauses?

  - Definition of Horn Clause.

  - Is description logic decidable?

  - Il PDDL a restriction of FOL?

  - Fast Thinking and slow thinking

  - Advantages of using KR wrt to Machine Learning

  - Problem in representing propositional attitudes in classical logic.

  - Special semantics available in modal logic.

  - How does it handle non monotonic reasoning issues?

  - Different dimensions of complexity to be  considered(wrt to agents). What can affect complexity?

  - Extremes of the fundamental tradeoff of KR.

  - Differences in expressivity between different logics. Limits in FOL.

  - What is a semantic network?

  - Typical inference of a semantic network.

  - Is the inheritance mechanism modeled is any kind of logic?

  - What is a computational agent?

  - What are CSPs? (Formal definition)

  - What is the problem induction technique?

  - General complexity of CSP solution search.

  - Topology of CSP graphs? How to enforce properties to achieve efficiency? (DAC etc..)

  - Frame Systems.

  - Satisfiability of a FOL KR. Is this problem decidable?

  - Local search algorithms.

  - Specificities of description logic.

  - What are concepts? What are roules?

  - Typical problem of description logic.

  - How to model uncertainty in AI? What tool can we use?

  - Why is a specific language needed to "do" planning?

  - What is a random variable in probability theory? Make an example.

  - Definition of product rule with an example with two variables (written).

  - What if the two variables were independent?

  - Compare Forward reasoning and backward reasoning.

  - What is PROLOG? What is it used for?

  - Describe the usage of the !CUT operator.

  - Definition of full joint probability.

  - What are belief networks? What is represented by nodes and edges?

  - Given a problem, are there many ways to represent it, or just once?

  - How to choose the best one? Are there any complexity tradeoffs?

  - Definition of PDDL.

  - Example (instance) of problem solvable using it.

  - Bayes Theorem

  - Viterbi Algorithm

  - Why do we need to model uncertainty?

  - Decision Theory vs Probability Theory

  - Variable Elimination Algorithm

  - Where is it used?

  - Differences between prediction, filtering and smoothing.

  - Basic axiom of probability (Kolgmogorv).

  - What is a random variable? Make an example.

  - Tradeoff between representation power and complexity of bayesian networks.

  - How can topology impact complexity?

  - What is PDDL, how does it work?

  - What is a definite horn clause?

  - Why do we need to “limit” to the usage of them?

  - What is the probability full joint distribution? What is its usage?

  - Why do we need more sophisticated algorithms?

  - Graph planning algorithm. 

  - What is prolog. Describe its main properties
</details>
<details>
<summary>:it: Feb 2022</summary>
  
  - Perché l’autoepistemic Logic va contro la logica monotonica?
  
  - default logic
  
  - dpll 
  
  - ragionare sul frame problem
  
  - Differenza tra FOL e Description Logic
  
  - Cosa non può essere definito nella Description Logic mentre nella FOL si?
  
  - Come vengono definite le semantic network?
  
  - Cosa decide la complessità per un agente?
  
  - Cosa rende complesso un linguaggio rispetto un altro?
  
  - Le Logiche descrittive sono meno espressive della FOL, parlane
  
  -  Cosa possiamo dire con FOL e non in DL sì
  
  -  Quali sono i problemi decisionali tipici delle logiche descrittive
  
  -  Algoritmo sulla propagazione dei vincoli
  
  -    Consistenza di concetto
  
  -    Sussunzione
  
  -  L’ambito più importante delle logiche descrittive 
  
  -  Limiti espressivi della logica classica nel fare un qualsiasi ragionamento non monotono 
  
  - Vantaggi dei sistemi Rule Based e Logica Classica

  - Che garanzie ci sono usando le clausole di Horn?

  - Teorema di Bayes, che significa che ha un senso “diagnostico”?
  
  - Algoritmo di Viterbi, me lo puoi descrivere brevemente?

  - Applicazione pratica del Viterbi Algo
  
  - Come si definisce una variabile randomica?

  - Cos'è il PDDL?

  - Quali altre tipologie di sistemi abbiamo visionato oltre CLIPS e Prolog riguardando i Ruled Based Systems?
  
  - Definizione di Polytree, in che contesto l’abbiamo introdotto
  
  - Perché è importante che la nostra rete sia un polytree

  - Cosa intendiamo per Marginalizzazione

  - Smoothing

  - Graph Plan Algorithm
  
  - Prolog in livello dichiarativo e procedurale
  
  - CUT Operator
  
  - prob. condizionale e sulla product rule
  
  - Smoothing VS Prediction
  
  - Belief Network, cosa sono?
  
  - Dimostrazione del teorema di bayes a partire dalla product rule
  
  - Satplan cos’è? Perchè abbiamo bisogno di altri algoritmi se abbiamo già questo?
  
  - come è fatta una Bayesian Network
  
  - euristiche nel planning
  
  - Cos’è un production system? + esempio (CLIPS)

</details>


## BIOINFORMATICS
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## COMPETITIVE PROGRAMMING AND CONTESTS
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## COMPUTATIONAL MATHEMATICS FOR LEARNING AND DATA ANALYSIS
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## COMPUTATIONAL MODELS FOR COMPLEX SYSTEMS
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## COMPUTATIONAL NEUROSCIENCE
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## DATA MINING

<details>
  <summary>:us: Before 2020</summary>

-  Differences between Apriori and FP-Grow. Hierarchical Transactional clustering  -> Rock and differences with classic hierarchical clustering. MLE: expectation phase and maximization Phase, comparison with the same phases in KMeans

- two questions about FP-Grow.

- fp-growth; the difference between different kinds of clustering algorithms.

</details>



## FOUNDATION OF COMPUTING
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## HUMAN LANGUAGE TECHNOLOGIES
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## ICT INFRASTRUCTURES
<details>
<summary>:us: 2020-21 - From various oral exams</summary>
  
  
   - Cooling system of a physical DC affect the service catalog and SLA defined by the private cloud that runs on the physical infrastructure ?
   - What can we say about the service catalog?
   - How can service catalog be affected by physical constraints? Example of service that you can run with 15 kwatts per rack of power?
   - What's a Full Fat Tree
   - What's Spine and Leaf architecture? Is there a limit of leaf in a network? What can i do if i finish the spine's ports?
   - What's thin provisioning?
   - What happen when you do a snapshot of a VM? How is the drive snapshoted?
   - What is the main problem of SAN architecture in storage? (Bandwith)
   - Why we use virtualization in servers?
   - How does live migration works? What are its physical constraints?
   - What's Capacity management/planning? How CAPEX and OPEX are related to it?
   - What's RAID?
   - What is the Pizza Model? (asked different times) (the explanation of pizza analogy is very important)
   - Cooling and energy management. Definition of PUE.
   - What is NvME?
   - What's a Hyperconvergent infrastructure?
   - We want to implement a storage service with hundred thousand users how do you think about the infrastructure? Tell me about storage, servers and cooling.
   - What's a LUN.
   - How is possible in an hypervisor to overbook the memory? How can you guarantee that a VM does not go in space memory of another VM.
   - Why Monitoring is important?
   - What are the strategy to build a HA system?
</details>


## ICT RISK ASSESSMENT
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## INFORMATION RETRIEVAL

<details>
  <summary>:us: 2021-22</summary>
  
  - Talk about the web graph: explain the "bow tie" picture, and the three properties of a web graph
  - How do we map urls to integers to represent the uncompressed adjacency list?
  - Where and how we exploit locality and similarity properties in the uncompressed adjacency list representation of the web graph?
  - Explain how we can simplify cosine similarity when comparing two vectors
  - Where and how we use the Karp Rabin fingerprint in the min-hashing technique
  <summary>:us: 2020-21</summary>

  - Compression of WebGraph, meaning of "near pages", how to optimize the saving of the "extra nodes"
  - Karp-Rabin fingerprints, properties, proof
  - Pearson's Chi-Square test. Meaning of the tables used in this test
  - Zsynch (exercise like in written exams, but explaining your thoughts while writing)
  - Delta compression (zdelta)
    - Delta compression for groups of files (the one with the graph)
</details>


## INTELLIGENT SYSTEMS FOR PATTERN RECOGNITION
<details>
  <summary>:en: 2022-23</summary>
  - Markov random fields.
  - Given a MRF, is the factorisation in its equivalent directed counterpart unique? And given a directed model, is the factorisation in MRF unique?
  - RNN, gradient vanishing and gradient explosion.
  - LSTMs with residual connections
  - Diffusion models
  - GANs
  - Manifold Assumption in autoencoders
  - Variational learning with proof of ELBO and KL divergence
  - LDA
  - HMMs, viterbi and smoothing problem with alpha/beta recursion
  - Smoothing problem for second order HMMs

</details>
<details>
  <summary>:it: 2021-22</summary>

- Markov Random Fields
- Hidden Markov Models
- Hmm vs crf differenze
- Probabilità condizionata
- Q-learning cos’è e su cosa si basa 
- Ancestral sampling cos’è?
- HMM vs CRF differenze
- come faccio il training in CRF 
- Bootstraping vs monte carlo 
- Le reti neurali hanno un problema, quale? (Gradient descent!)
- Com’è fatta una LSTM in particolare la parte ricorrente 
- Bellman expectation e Bellman optimality differenza 
- ELBO 
- SIFT
- ARMA
- Batch normalization 
- Approcci value based vs policy based pro contro
- Attention come si usa e come funziona
- Attention vs Self-Attention
- Bolzman machine 
- d-separation
- Neural turing machine
- MSER maximally stable extremal regions
- LDA

</details>
<details>
  <summary>2020-21</summary>

- Markov Random Fields
- Hidden Markov Models

</details>


## LABORATORY FOR INNOVATIVE SOFTWARE
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## LANGUAGES, COMPILERS AND INTERPRETERS
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## MACHINE LEARNING

<details>
  <summary>:us: 2022-23</summary>

  - What is the linear basis expansion (phi) and where it appears
  - Write the formula of the LBE for a Neural Network (the phi are learned)
  - Covariance in cascade correlation
  - What is dropout
  - Where the regularization appears during the course 

</details>

<details>
  <summary>:us: 2020-21</summary>

  - List all the differences between SVM and NN (without actually explaining _what_ they are)
  - Explain why SOMs are better than K-Means
  - RBF kernel (especially from the point of view of the LBE)
  - Approximation theorem of NNs

</details>
<details>
  <summary>:us: 2019-20</summary>

- Write the loss for a linear model in form of ridge regression (with Tikhonov regularization)
- Write (and briefly comment on) the most important factors ruling the flexibility of the SVM and of the NN approaches
Compute dE/do_i for a NN (the same seen in class) showing the single steps of the derivation for the dE/do_i (assuming to have already delta for the units of the other layers indexed by h and k. Finally, write delta_k, delta_t, delta_i
- Define the VC-dim. Does the VC-dim in Phi_1 increase or decrease if the value of the regularization parameter increases? Explain.
------------------------------
1.
- Write the net_t(x) of a preceptron with inputs i in [1, ..., k]  
- Write the radial basis function kernel

2. Answer true or false to the following and motivate your answer  
- In a SVM can the alpha values help to select the best features? False (they only select some input patterns and not the components)  
- To estimate the (future) predictive capability of your model is it a good practice to consider the result and accuracy obtained by the model selection phase without looking to the training results? False (only the test result cares to estimate the (future) predictive capability)
- Increasing the VC-dim, th VC-bound on the risk R (according to SLT) increases. True

3. Write the derivation of the bias-variance decomposition (assuming without proving the variance lemma)

4. Show a picture of:  
- undercomplete autoencoder  
- overcomplete autoencoder

5. Equation of the RBF Kernel. Equation of the Loss for Ridge regression + comments on the role of lambda.

6. Equations used for SOM. Why is the Neural Network able to approximate every function? Why do we use deep learning if one layer is enough?

</details>


## MOBILE AND CYBER-PHYSICAL SYSTEMS
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## PARALLEL AND DISTRIBUTED SYSTEMS: PARADIGMS AND MODELS
:it: _La maggior parte dell'orale verte sul progetto e molte delle domande di teoria sono collegate._

<details>
  <summary>:en: 2022-2023</summary>
  - CAP theorem and CAP theorem with latency. How is latency related to consistency?
  - Refactoring rules
  - Model the speedup of a farm whose workers have a part of work to be executed in mutual exclusion and a part which is fully parallel.
</details>

<details>
  <summary>:it: 2020-21</summary>
  
    - Map fusion, differenze tra regola di equivalenza `comp(map(f), map(g)) == map(comp(f, g))` e `pipe(map(f), map(g)) == map(comp(f, g))`. Quante risorse si impiegano in ciascun caso?

    - Che cos'è la vettorizzazione e com'è implementata a livello hardware?

    - A quali condizioni posso implementare la vettorizzazione? Se ho una chiamata di libreria all'interno del corpo del for e forzo la vettorizzazione (es. con un `pragma`) cosa succede? (Dipende dalla funzione) E se ho iterazioni dipendenti e forzo la vettorizzazione? (Errore)

    - Autonomic management della farm. Come si può implementare autonomic management in FastFlow? Posso implementare `farmout(pipe(s1, s2, s3))` a runtime in FastFlow? (No) Cambierebbe qualcosa se la libreria non fosse header-based ma fosse in un file `.so`? (No perché dipende dalle API di FastFlow)

    - Parlami del workspan model. Come lo implementeresti con la threadpool di async e future? (Un susseguirsi di chiamate .get() in base alle dipendenze di codice)

    - Cos'è il cache coherency protocol e come si evita un sovra utilizzo (padding)

    - Costruisci una pipeline con tre stadi e mostrami due pipeline equivalenti utilizzando le regole di riscrittura. Come cambiano le varie metriche nei casi mostrati?

  </details>

<details>
    <summary>:it: 2019-20</summary>

  - Macro Data Flow con esempio

  - Buildin blocks per streming e data.

  - Point to point e collective comunication in fast flow. Qunado serve collective comunication.

  - Service time, latency, efficiency più esempi su quando voglio ottimizzare cosa

</details>

<details>
  <summary>:it: 2018-19</summary>

- Perchè non hai usato un manager e hai fatto fare tutto all’emitter? Con il manager hai dei movimenti di dati in più? L’emitter ha qualche guadagno se c’è il manager?
- Perchè parti subito con un numero fissato di worker? Non sarebbe stato meglio farlo lavorare uno e poi capire quanti worker servono dinamicamente?
- Sarebbe stato giusto fare un’analisi del tempo che ci metto per fare uno switch del numero di worker in modo da capire ogni quanto cambiare
- Se ho due map quali ottimizzazioni posso fare? Se faccio la map fusion poi ho un guadagno? Ce l’ho sempre?
- Se metto una map dentro ad una farm che guadagno ho se aumento il numero di worker della map o se aumento il numero di worker della farm?
Se tolgo la map e lascio la farm aumentando i worker cambia qualcosa? L’efficiency come cambia? Se tolgo tutto e lascio solo un nodo sequenziale cambia qualcosa? L’efficiency come varia (diventa 1)?
- Differenza tra work span model e amdahl law, voleva sapere che i nodi devono avere lo stesso tempo di esecuzione
------------------------------
- Come si calcola lo speedup?
- Amdahl Law (con limite)
- Cosa devo aggiungere ad un farm che tenga in conto sia il tempo che il consumo energetico (considerando che entrambi dipendono dal nw)? Devo tenere conto di grado di parallelismo e frequenza del processore. Nel collector posso calcolare il service time Ts. Posso variare il numero di worker e vedere all'aumentare del nw come varia l'energia. Più worker = meno tempo di uso di CPU con più consumo. Posso fermarmi quando diventa sconveniente aumentare il nw per l'overhead.
- Tipi di pattern
- Vettorizzazione del codice

</details>

<details>
  <summary>:it: 2017-18</summary>

- Hamdal law
- Macro data flow, con un esempio di conversione fra  "farm(pipe(f1,f2))", chiedendo di disegnare il grafico

</details>


:us: _Most of the oral exam focuses on the project and many of the theory questions are related._

<details>
  <summary>:us: 2020-21</summary>
    
  - Map fusion, difference between equivalence rules `comp(map(f), map(g)) == map(comp(f, g))` and `pipe(map(f), map(g)) == map(comp(f, g))`. How many resources are needed for each of those cases?
    
  - What's vectorization and how is it implemented?
    
  - Under what conditions can I implement vectorization? If I have a library call inside the for body and force vectorization (e.g. with a `pragma`) what happens? What if I have dependent iterations and force vectorization?
    
  - Autonomic farm management. How can I implement autonomic management in FastFlow? Can I implement `farmout(pipe(s1, s2, s3))` at runtime in FastFlow? (No) Would it change anything if the library was not header-based but was in a `.so` file? (No because it depends on the FastFlow API)
 
</details>

<details>
    <summary>:us: 2019-20</summary>

  - Macro Data Flow with examples

  - Buildin blocks for streming and data.

  - Point to point and collective comunication in fast flow. When to use collective comunication.

  - Service time, latency, efficiency and example where to use what metrics.

</details>

<details>
  <summary>:us: 2018-19</summary>

- Why didn't you use a manager and have the emitter do everything? Do you have more data movements with the manager? Does the emitter have any earnings if there is a manager?
- Why do you start immediately with a fixed number of workers? Wouldn't it have been better to have him work one and then figure out how many workers they need dynamically?
- It would have been right to do an analysis of the time it takes to make a switch of the number of workers in order to understand how often to change
- If I have two maps, which optimizations can I do? If I do map fusion then do I have a profit? Do I always have it?
- If I put a map inside a farm, what profit do I have if I increase the number of workers on the map or if I increase the number of workers in the farm?
If I remove the map and leave the farm increasing the workers does something change? How does efficiency change? If I remove everything and leave only a sequential node, does something change? How does the efficiency vary (becomes 1)?
- Difference between work span model and amdahl law, he wanted to know that nodes must have the same execution time
------------------------------
- How is the speedup calculated?
- Amdahl Law (with limit)
- What should I add to a farm that takes into account both time and energy consumption (considering that both depend on the nw)? I have to take into account the degree of parallelism and the frequency of the processor. In the collector I can calculate the service time Ts. I can vary the number of workers and see how the energy changes as the nw increases. More worker = less CPU usage time with more consumption. I can stop when it becomes inconvenient to increase the nw for overhead.
- Types of patterns
- Vectorization of the code

</details>

<details>
  <summary>:us: 2017-18</summary>

- Hamdal law
- Macro data flow works, with an example of conversion between "farm(pipe(f1, f2))", asking to draw the graph

</details>


## PEER TO PEER SYSTEMS AND BLOCKCHAINS
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## PRINCIPLES FOR SOFTWARE COMPOSITION
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## ROBOTICS
- Architectures for robot behavior described by the three primitive functions
- Motion control with gravity compensation (robot control)
- Potential fields (robot navigation)
- Histograms of an image (robot vision)
- ZMP components (bipedal locomotion)


## SCIENTIFIC AND LARGE DATA VISUALIZATION
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## SECURITY METHODS AND VERIFICATION
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## SEMANTIC WEB
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## SMART APPLICATIONS
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## SOCIAL AND ETHICAL ISSUES IN INFORMATION TECHNOLOGY
- Be the first to contribute, open a pull request with your oral questions or other relevant material!


## SOFTWARE VALIDATION AND VERIFICATION
- Be the first to contribute, open a pull request with your oral questions or other relevant material!
