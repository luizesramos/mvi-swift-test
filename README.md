README.md

MVI

The key is the View has an immutable state (Model) defined as a struct/class/enum. A user's Intent triggers business logic (Reducer + Middleware) that generates a new state to replace the previous state. The View observes the ViewModel (or binds to a Presenter) who owns and publishes the state. The view updates itself based on the new state.

The business logic may be comprised of "pure" and/or "non-pure" functions. A pure function (1) produces the same output for a same input; and (2) has no side effects. Side effects include reads/writes to global variables, reads from input stream (e.g., keyboard, network), committing to a persistent data source, operations that may fail or be retried.



https://betterprogramming.pub/mvi-architecture-for-swiftui-apps-cff44428394

https://jsonplaceholder.typicode.com/guide/

https://dummyjson.com/
https://gorest.co.in/