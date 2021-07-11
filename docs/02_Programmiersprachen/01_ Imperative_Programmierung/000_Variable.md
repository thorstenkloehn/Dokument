## C

```

char zeichen = 't';
int intvariable = 1ß;
double doublevariable = 10.56;

```
## C++
```

int main() {
    char zeichen = 't';
    int intVariable = 10;
    double kommazahl = 1.50;
    bool wahr = true;

}
```
## Go

```
package main

import "fmt"



func main()  {
	var zahl1 int8
	var zahl = 100
	ausgabe := 200
	fmt.Println(zahl)
	fmt.Println(zahl1)
    fmt.Println(ausgabe)
}

```

## Rust

```

fn main() {
    let zahl = 100; // unveränderlich Variable
    let mut ausgabe = 200; // veränderlich Variable
    ausgabe = 300;
    println!("Zahl ausgabe {} {}", zahl, ausgabe);
}



```

## Javascript


```
"use strict";
let zahl = 100;
console.log (" Zahl ausgeben" , zahl)

```

## Python 

```

zahl = 100
print (zahl)


```

## Java

```

public class main {

    public static void main (String[] args) {
        int zahl = 100;
        System.out.println("Ergebnis Ausgeben "+zahl);
    }
}

```

## C#

```

using System;

namespace _01_Lektion
{
    class Program
    {
        static void Main(string[] args)
        {

            //Ganzezahlen
            byte wbyte = 200;
            System.Console.WriteLine(wbyte);
            short wshort = 3000;
            System.Console.WriteLine(wshort);
            //Kommazahlen
            float wfloat = 3.4f;
            double wdouble = 3.14;
            
            System.Console.WriteLine(wfloat);
            System.Console.WriteLine(wdouble);
        }
    }
}


```