# PANACHE

## BASI PANACHE

- Cos’è Hibernate Panache?
- Quale problema risolve Panache?
- Differenza tra Active Record e Repository Pattern?
- Quando useresti PanacheEntity?
- Quando useresti PanacheRepository?
- Quali vantaggi offre Panache rispetto a JPA standard?
- Cos’è PanacheEntityBase?
- Perché PanacheEntity ha già il campo id?

---

## ENTITY E REPOSITORY

- Come definisci una entity con PanacheEntity?
- Come definisci una repository con PanacheRepository?
- Scrivimi una repository Panache per User.
- Come inietti una repository?
- Come esegui CRUD con Panache?
- Come salvi un’entità?
- Differenza tra persist() e persistAndFlush()?
- Come elimini un record?
- Come aggiorni un’entità?
- Come controlli se un’entità esiste?

---

## QUERY CON PANACHE

- Come funziona find() in Panache?
- Come esegui query parametrizzate?
- Differenza tra list() e stream()?
- Come recuperi un solo record?
- Differenza tra firstResult() e singleResult()?
- Come ordini risultati con Sort?
- Come fai paginazione con Panache?
- Come esegui query custom JPQL?
- Come fai count() dei record?
- Come esegui delete() bulk?
- Come fai update() bulk?
- Come scriveresti una query per trovare utenti per email?
- Come recuperi dati usando named query?
- Come useresti Parameters.with()?

---

## PAGINATION E SORTING

- Come funziona PanacheQuery?
- Come implementi paginazione server-side?
- Differenza tra page() e range()?
- Come ottieni il numero totale di pagine?
- Come ordini per più campi?
- Come implementeresti una ricerca con filtri dinamici?

---

## TRANSAZIONI E PERFORMANCE

- Come funziona @Transactional con Panache?
- Cosa succede se dimentichi @Transactional?
- Panache è thread-safe?
- Come gestisci LazyInitializationException?
- Come eviti il problema N+1 con Panache?
- Come ottimizzeresti una query Panache lenta?
- Come useresti fetch join con Panache?
- Quando usare stream() può essere pericoloso?

---

## PANACHE REACTIVE

- Cos’è Hibernate Reactive Panache?
- Differenza tra Panache classico e Reactive Panache?
- Quando useresti Reactive Panache?
- Cos’è Uni?
- Cos’è Multi?
- Come esegui query reactive?
- Come gestisci transazioni reactive?
- Differenza tra Uni<List<User>> e List<User>?
- Perché il modello reactive evita thread blocking?

---

## DOMANDE PRATICHE PANACHE

- Scrivimi una entity Panache per User con id, nome ed email.
- Scrivimi una repository Panache con un metodo findByEmail().
- Come implementeresti soft delete con Panache?
- Come implementeresti auditing (createdAt, updatedAt)?
- Come mapperesti DTO con Panache?
- Come implementeresti una ricerca paginata con filtri dinamici?
- Come gestiresti transazioni concorrenti?
- Come testeresti repository Panache?