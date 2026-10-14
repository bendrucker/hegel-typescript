RELEASE_TYPE: patch

Allow an interface as the type argument of `gs.record`, as in `gs.record<Person>({...})`, which previously failed with TS2344.

Fix the getting-started examples, which passed the result of `hegel.test(...)` to `test` instead of a function. They now use `test("name", () => hegel.test(...))`.
