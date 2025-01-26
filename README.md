# Uninitialized Variable in Go

This repository demonstrates a common but easily missed bug in Go: the use of uninitialized variables.  Go automatically initializes variables to their zero values, but relying on this without explicit checking can lead to unexpected behavior and program errors.

The `bug.go` file contains code that demonstrates this issue. The `bugSolution.go` file shows a corrected version.  This repository is intended for educational purposes to help developers understand and avoid this type of error.