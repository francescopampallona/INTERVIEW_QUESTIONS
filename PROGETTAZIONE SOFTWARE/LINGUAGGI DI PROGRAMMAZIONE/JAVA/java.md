# JAVA

## 1. INTRODUZIONE A JAVA
### Cos'è Java?
### Perché Java è indipendente dalla piattaforma?
### Cos'è il bytecode?
### Differenza tra JDK, JRE e JVM
### Come funziona il processo di compilazione ed esecuzione
### Cos'è la JVM e quale ruolo ha a runtime?
### Cos'è il class loader?

---

## 2. TIPI DI DATI, VARIABILI E OPERATORI
### Differenza tra tipi primitivi e reference type
### Quali sono i tipi primitivi in Java?
### Casting implicito ed esplicito
### Differenza tra variabili locali, di istanza e di classe
### Scope di una variabile
### Differenza tra passaggio per valore e per riferimento (in Java)
### Autoboxing e unboxing

---

## 3. CLASSI, OGGETTI E METODI
### Cos'è una classe? Cos'è un oggetto?
### Cos'è un metodo?
### Cos'è un costruttore?
### Differenza tra costruttore di default e costruttore definito
### Uso di this() e super()
### Ordine di inizializzazione
### Cos'è la garbage collection?
### Perché finalize() è deprecato/sconsigliato?
### Cos'è l'information hiding?
### Cos'è l'incapsulamento?
### Differenza tra metodo statico e metodo di istanza
### Differenza tra shallow copy e deep copy

---

## 4. CONFRONTO TRA OGGETTI
### Differenza tra == ed equals()
### Come funziona il metodo equals()
### Perché bisogna override anche hashCode()
### Cos'è hashCode e a cosa serve?

---

## 5. CLASSE OBJECT
### Quali sono i metodi principali della classe Object?
### A cosa servono:
#### toString()
#### equals()
#### hashCode()
#### clone()
#### getClass()
#### wait(), notify(), notifyAll()

---

## 6. STRINGHE E IMMUTABILITÀ
### Cos'è una String?
### Perché String è immutable?
### Cos'è lo string pool?
### Differenza tra String, StringBuilder e StringBuffer
### Differenza tra == ed equals() con le stringhe
### Quando usare StringBuilder rispetto a String

---

## 7. WRAPPER, BOXING E UNBOXING
### Cos'è una classe wrapper?
### Differenza tra tipi primitivi e wrapper
### Cos'è autoboxing e unboxing (Java 5)
### Problemi di performance legati al boxing

---

## 8. ARRAY
### Come funzionano gli array in Java?
### Differenza tra array di primitivi e oggetti
### Differenza tra array e collection
### Cos'è ArrayIndexOutOfBoundsException?
### Come si copia un array?

---

## 9. MODIFICATORI E PAROLE CHIAVE
### Significato di final (variabile, metodo, classe)
### Differenza tra final, finally, finalize()
### Uso di this e super
### Uso di instanceof
### Significato di:
#### static
#### synchronized
#### volatile
#### transient
#### native

---

## 10. OVERLOADING
### Cos'è l’overloading?
### Regole dell’overloading
### Overloading e tipo di ritorno

---

## 11. EREDITARIETÀ
### Cos'è l’ereditarietà (relazione is-a)?
### Differenza tra is-a e has-a
### Perché Java non supporta ereditarietà multipla tra classi

---

## 12. OVERRIDING
### Cos'è l’overriding?
### Regole dell’overriding
### Uso di @Override
### Overloading vs overriding

---

## 13. POLIMORFISMO
### Cos'è il polimorfismo?
### Cos'è il binding dinamico
### Differenza tra binding statico e dinamico

---

## 14. CLASSI ASTRATTE E INTERFACCE
### Cos'è una classe astratta?
### Cos'è un'interfaccia?
### Si può estendere un’interfaccia?
### Si possono implementare più interfacce?
### Differenza tra interfaccia e classe astratta (Java 8+)
### Cosa sono i metodi default e static nelle interfacce
### Cos'è una functional interface

---

## 15. PACKAGE E VISIBILITÀ
### Cos'è un package?
### Modificatori di accesso:
#### private
#### default
#### protected
#### public
### Differenza tra visibilità a livello di classe e di membro

---

## 16. ECCEZIONI
### Cos'è un’eccezione?
### Differenza tra checked e unchecked exception
### Differenza tra Error ed Exception
### Uso di try, catch, finally
### Differenza tra throw e throws
### Cos'è il multicatch (Java 7)
### Cos'è il try-with-resources
### Cosa succede se un'eccezione non viene gestita?

---

## 17. ENUMERAZIONI (Java 5)
### Cos'è un enum?
### Quando usarlo
### Un enum può avere metodi e costruttori?

---

## 18. ANNOTAZIONI (Java 5)
### Cos'è un'annotazione?
### Esempi: @Override, @Deprecated, @FunctionalInterface
### Differenza tra annotazioni built-in e custom
### Cos'è la reflection in relazione alle annotazioni?

---

## 19. GENERIC (Java 5)
### Cosa sono i generic?
### Vantaggi dei generic
### Type erasure
### Uso del wildcard ?:
#### ? extends
#### ? super
### Cosa succede se non si usano i generic?

---

## 20. COLLECTION FRAMEWORK
### Differenza tra List, Set, Map, Queue
### Differenza tra:
#### ArrayList vs LinkedList
#### HashSet vs TreeSet
#### HashMap vs TreeMap
### Come funziona una HashMap (concettualmente)?
### Cos'è Comparable?
### Cos'è Comparator?
### Cos'è un Iterator?
### Differenza tra Iterator e ListIterator
### ConcurrentModificationException

---

## 21. INNER CLASS
### Cosa sono le inner class?
### Tipi:
#### static nested class
#### inner class
#### local class
#### anonymous class

---

## 22. INPUT/OUTPUT E FILE
### Differenza tra byte stream e character stream
### InputStream/OutputStream vs Reader/Writer
### Cos'è il buffering
### Come leggere/scrivere file
### Differenza tra I/O e NIO
### Cos'è il try-with-resources nel contesto I/O

---

## 23. SERIALIZZAZIONE
### Cos'è la serializzazione?
### Interfaccia Serializable
### Cos'è serialVersionUID
### Uso di transient
### Problemi di sicurezza legati alla serializzazione

---

## 24. JVM E MEMORIA
### Cos'è la JVM?
### Stack vs Heap
### Cos'è il class loader
### Come funziona la garbage collection
### Cos'è un memory leak in Java
### Differenza tra memoria stack e heap in termini pratici

---

## 25. MULTITHREADING
### Differenza tra processo e thread
### Creazione thread:
#### Thread
#### Runnable
### Differenza tra start() e run()
### Cos'è la race condition
### Cos'è il deadlock
### Cos'è la starvation
### Cos'è la livelock
### Uso di synchronized
### Differenza tra wait() e sleep()
### Cos'è il monitor di un oggetto

---

## 26. CONCURRENCY UTILITIES (Java 5)
### Cos'è ExecutorService
### Cos'è un thread pool
### Differenza tra Runnable e Callable
### Cos'è Future
### Cos'è CompletableFuture
### Strumenti:
#### CountDownLatch
#### CyclicBarrier
#### Semaphore
### Concurrent collections (es. ConcurrentHashMap)
### Differenza tra HashMap e ConcurrentHashMap
### Atomic variables (es. AtomicInteger)
### Quando usare classi atomiche invece di synchronized

---

## 27. PROGRAMMAZIONE FUNZIONALE (Java 8+)
### Cos'è una lambda expression
### Cos'è una functional interface
### Cos'è @FunctionalInterface
### Cos'è uno Stream
### Operazioni intermedie e terminali
### Differenza tra map() e filter()
### Cos'è Optional
### Quando usare Optional e quando evitarlo

---

## 28. JDBC
### Cos'è JDBC
### Componenti:
#### Connection
#### Statement
#### PreparedStatement
#### ResultSet
### Differenza tra Statement e PreparedStatement
### Cos'è SQL Injection
### Perché PreparedStatement previene SQL Injection

---

## 29. MODULI (Java 9)
### Cos'è il sistema a moduli
### Cos'è module-info.java
### Differenza tra package e modulo

---

## 30. NOVITÀ JAVA MODERNO
### var (Java 10)
### switch expressions
### text blocks
### record (Java 16)
### sealed classes (Java 17)
### pattern matching for instanceof

---

## 31. SICUREZZA E BEST PRACTICES
### Differenza tra shallow copy e deep copy
### Privacy leak con oggetti mutabili nei getter
### Defensive copy
### Immutabilità degli oggetti
### Buone pratiche OOP in Java
### Principi SOLID (a livello concettuale)

---

## 32. DOMANDE TRASVERSALI IMPORTANTI
### Differenza tra == ed equals()
### Differenza tra equals() e hashCode()
### Differenza tra final, finally, finalize()
### Perché String è immutable
### Perché Java non supporta ereditarietà multipla
### Differenza tra ArrayList e LinkedList
### Differenza tra HashMap e TreeMap
### Differenza tra Runnable e Callable
### Differenza tra start() e run()
