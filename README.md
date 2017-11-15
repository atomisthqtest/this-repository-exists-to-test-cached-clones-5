# this is used in a specific test.

It is in automation-client-ts.

It is called CachedGitCloneTest, at the moment.

If any other tests use it at the same time (on the same box) they will conflict and get flaky. So don't.

It's public so that people can clone it if the tests are running under their own GitHub token.
That will prevent some irritating failures.
