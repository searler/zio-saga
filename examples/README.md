This is the example that extends one provided in the parent REAMDE file.

This projects shows one of the implementation variants of Saga Executor Coordinator
that also writes transaction log to database and knows how to recover from failures. 

TODO:
- pack project to docker image
- what if coordinator fails after saga fails (we don't want to repeat the failed request)