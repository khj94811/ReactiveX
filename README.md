# Reactive X Study

- ReactiveX is a library for composing asynchronous and event-based programs by using observable sequences.
- It extends the observer pattern to support sequences of data and/or events and adds operators that allow you to compose sequences together declaratively while abstracting away concerns about things like low-level threading, synchronization, thread-safety, concurrent data structures, and non-blocking I/O.
- References: http://reactivex.io/intro.html

### Why Use Observables?

- Observables Are Composable
- Observables Are Flexible
- Observables Are Less Opinionated

### Why Rx?

- Users expect real time data. They want their tweets now. Their order confirmed now. They need prices accurate as of now. Their online games need to be responsive. As a developer, you demand fire-and-forget messaging. You don't want to be blocked waiting for a result.
- You want to have the result pushed to you when it is ready. Even better, when working with result sets, you want to receive individual results as they are ready. You do not want to wait for the entire set to be processed before you see the first row.

### Observable

- In ReactiveX an observer subscribes to an Observable. Then that observer reacts to whatever item or sequence of items the Observable emits. 
- This pattern facilitates concurrent operations because it does not need to block while waiting for the Observable to emit objects, but instead it creates a sentry in the form of an observer that stands ready to react appropriately at whatever future time the Observable does so.
- ![Observable](http://reactivex.io/assets/operators/legend.png)
