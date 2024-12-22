This repository demonstrates a common error in Rust: a data race caused by multiple mutable references to the same variable without proper synchronization. The file `bug.rs` contains the buggy code.  The solution is provided in `bugSolution.rs` and involves using techniques to avoid the data race, such as mutexes or other synchronization primitives.