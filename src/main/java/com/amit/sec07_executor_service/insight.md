Executor Service do thread pooling to reuse platform thread , as they are very expensive.

Thread Per Task Executor :: Creates new thread per task on demand (from java 21)

ExecutorService now extends the AutoCloseable

Virtual Thread are not supposed to pooled according to oracle docs.

