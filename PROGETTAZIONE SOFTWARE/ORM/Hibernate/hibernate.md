# GESTIONE DELLA PERSISTENZA (JPA / HIBERNATE)

## BASI DI HIBERNATE
Cos’è Hibernate?
Qual è la differenza tra JPA e Hibernate?
Cos’è un ORM e quali problemi risolve?
Quali sono i vantaggi e gli svantaggi dell’uso di un ORM?

## ENTITY E MAPPING
Cos’è una Entity?
Quali annotazioni principali usi per mappare una Entity?
Differenza tra @Entity e @Table?
Come si definisce una chiave primaria?
Differenza tra @GeneratedValue strategie (AUTO, IDENTITY, SEQUENCE, TABLE)?
Come si mappano colonne custom con @Column?

## RELAZIONI TRA ENTITY
Differenza tra @OneToOne, @OneToMany, @ManyToOne, @ManyToMany?
Cos’è il lato owning di una relazione?
Cosa fa mappedBy?
Differenza tra unidirezionale e bidirezionale?
Come gestisci una relazione ManyToMany?
Come eviti problemi di serializzazione JSON nelle relazioni bidirezionali?

## FETCHING E PERFORMANCE
Differenza tra FetchType.LAZY e FetchType.EAGER?
Quando usare Lazy e quando Eager?
Cos’è il problema N+1?
Come lo risolvi?
Cos’è una fetch join?
Cos’è una DTO projection e quando usarla?

## ENTITY MANAGER E CICLO DI VITA
Cos’è l’EntityManager?
Quali sono gli stati di una Entity? (transient, managed, detached, removed)
Cosa succede quando fai persist?
Differenza tra persist e merge?
Cos’è il persistence context?

## TRANSAZIONI
Cos’è una transazione?
Cosa significa ACID?
Come gestisci le transazioni in Quarkus?
Cosa succede in caso di errore?
Differenza tra commit e rollback?

## QUERY
Differenza tra JPQL e SQL?
Cos’è una query JPQL?
Come esegui query dinamiche?
Cosa sono le named query?
Quando useresti query native?
Differenza tra getSingleResult e getResultList?

## CACHE
Cos’è la first-level cache?
Cos’è la second-level cache?
Quando ha senso usare la cache?
Quali problemi può introdurre?

## CONCURRENCY E LOCKING
Cos’è l’optimistic locking?
Cos’è il pessimistic locking?
Quando useresti uno o l’altro?
A cosa serve @Version?

## STRATEGIE DI EREDITARIETÀ
Parlami delle principali strategie di mapping con ereditarietà con i loro relativi vantaggi e svantaggi
Quali sono le differenze tra SINGLE_TABLE, JOINED e TABLE_PER_CLASS?
Quando useresti SINGLE_TABLE?
Quando preferiresti JOINED?
Perché TABLE_PER_CLASS è poco utilizzata?

## BEST PRACTICES
Quali sono le best practice nell’uso di Hibernate?
Perché evitare FetchType.EAGER di default?
Perché evitare di esporre direttamente le Entity nelle API REST?
Quando usare DTO invece delle Entity?
Come gestire correttamente le transazioni in un’applicazione enterprise?

## DOMANDE DA COLLOQUIO AVANZATE
Come ottimizzeresti le performance di un sistema basato su Hibernate?
Come gestisci grandi volumi di dati?
Come debugghi un problema di performance legato a Hibernate?
Hai mai avuto problemi con LazyInitializationException? Come li hai risolti?