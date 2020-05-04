# java-notes

Mutability & Immutability

- Risks of mutation : passing mutable values, returning mutable values, 

- Defensive copying   // return new Date(groundhogAnswer.getTime());
- In both of these examples — the List<Integer> and the Date — the problems would have been completely avoided if the list and the date had been immutable types. The bugs would have been impossible by design.

- In fact, you should never use Date! Use one of the classes from package java.time: LocalDateTime, Instant, etc. All guarantee in their specifications that they are immutable.

- The array is aliased //  pointing to the same char array.
- immutable object (like a String) and an immutable reference (like a final variable).
- using immutable objects and immutable references as much as possible

src : https://web.mit.edu/6.005/www/fa15/classes/09-immutability/


