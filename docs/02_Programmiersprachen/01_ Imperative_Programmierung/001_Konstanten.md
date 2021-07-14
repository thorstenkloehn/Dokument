## Konstanten

### C

```
#include <stdio.h>
void main() {
    const int zahl = 100;
    printf("%d",zahl);
}
```

### C++

```
#include <iostream>

int main() {
    const int zahl = 100;
    std::cout << "Hallo " << zahl;
    return 0;
}

```

### Go 

```
package main

import "fmt"

func main() {
	const zahl int = 100

	fmt.Println(zahl)
}

```

### Java 

```

public class main {

    public static void main(String args[]) {

        final int zahl = 100;
        System.out.println("Hallo Leute"+zahl);

    }
}




```

### Rust

```

fn main() {

    const AUSGABE: i8 = 100;
    println!("Hello, world! {}",AUSGABE);
}



```