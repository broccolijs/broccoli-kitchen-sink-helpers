# master

* Add `copyRecursivelySync` & `copyPreserveSync`

* Change `linkRecursivelySync` & `linkAndOverwrite` to use
  `copyRecursivelySync` & `copyPreserveTime` respectively. We now refuse
  to overwrite in either of those functions, despite the `linkAndOverwrite`
  name.

# 0.1.1

* In `linkRecursivelySync`, link (broken) symlinks correctly

# 0.1.0

* Initial release
