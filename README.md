# Java_DSA


## Patterns in JAVA 

1. Star pattern in Java

```java
    public class Pattern {
    public static void main(String[] args) {
      for (int i = 1; i<=5 ; i++) {
            System.out.println();
            for (int j=1; j<=i; j++) {
                System.out.print("*");
            }
        }
     }
 }

```

output:

        *
        **
        ***
        ****
        *****  
        
2. Reverse Star pattern in Java
```java

    public class Pattern {
    public static void main(String[] args) {
        for(int i=5;i>=1;i--){
            System.out.println();
            for(int j=1;j<=i;j++){
                System.out.print("*");
            }
        }
     }
}

```

 output:

        *****
        ****
        ***
        **
        *   

3. Another Pattern in Java
   ```java

   public class Pattern {
   public static void main(String[] args) {
   for (int i = 1; i <= 5; i++) {
            System.out.println();

            for (int j = 5; j >= 1; j--) {
                if (j != i) {
                    System.out.print(j);
                } else {
                    System.out.print("*");
                    }
                }
            }
       }
   }

```
output:
        5432*
        543*1
        54*21
        5*321
        *4321
