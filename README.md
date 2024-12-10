This repository demonstrates a common error in Rust: using a raw pointer to access a vector after it has been modified. This can lead to undefined behavior, crashes, or unexpected results.

The `bug.rs` file contains the buggy code. The `bugSolution.rs` file provides a corrected version that avoids the use of raw pointers and uses safe Rust techniques instead.

This is a good example of the importance of careful memory management in Rust.