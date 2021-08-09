### Reading a file line by line

```rust 
use std::io;
use std::io::{BufRead, BufReader};
use std::fs::File;

fn main() -> io::Result<()> {
    // ...
    //
    let f = File::open(filename)?;
    let mut reader = BufReader::new(f);
    let mut buffer = String::new();
    while let Ok(count) = reader.read_line(&mut buffer) {
        if count == 0 {
            break;
        }
        // process line
        // ...
        buffer.clear();
    }
    Ok(())
}
```
