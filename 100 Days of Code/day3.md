# Day 3
## Number of Problems Solved: 4

### Problem #1 Football Cup
#### [Problem Statement](https://www.codechef.com/MAY221D/problems/FOOTCUP/)

#### Related Topics:
Math
#### Code:
```java


import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.lang.Math;
import java.util.*;
import java.io.*;
import java.util.*;
import java.util.StringTokenizer;

import javax.lang.model.element.Element;

public class Main {
    static class FastReader {
        BufferedReader br;
        StringTokenizer st;

        public FastReader() {
            br = new BufferedReader(new InputStreamReader(System.in));
        }

        String next() {
            while (st == null || !st.hasMoreElements()) {
                try {
                    st = new StringTokenizer(br.readLine());
                } catch (IOException e) {
                    e.printStackTrace();
                }
            }
            return st.nextToken();
        }

        int nextInt() {
            return Integer.parseInt(next());
        }

        long nextLong() {
            return Long.parseLong(next());
        }

        double nextDouble() {
            return Double.parseDouble(next());
        }

        String nextLine() {
            String str = "";
            try {
                str = br.readLine();
            } catch (IOException e) {
                e.printStackTrace();
            }
            return str;
        }
    }

    public static void main(String[] args) throws Exception {
        // TODO Auto-generated method stub
        FastReader sc = new FastReader();
        BufferedWriter ou = new BufferedWriter(new OutputStreamWriter(System.out));
        // Start coding
        int tc = sc.nextInt();
        for (int o = 0; o < tc; o++) {
            int x = sc.nextInt();
            int y = sc.nextInt();

            if (x == y && x > 0 && y > 0) {
                ou.write("YES \n");
            } else {
                ou.write("NO \n");
            }
        }
        ou.flush();
    }
}

```
#### Time Taken: 1 min

### Problem #2 Miami GP 
#### [Problem Statement](https://www.codechef.com/MAY221D/problems/F1RULE)

#### Related Topics:

Math

#### Code:
```java
import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.lang.Math;
import java.util.*;
import java.io.*;
import java.util.*;
import java.util.StringTokenizer;

import javax.lang.model.element.Element;

public class Main {
    static class FastReader {
        BufferedReader br;
        StringTokenizer st;

        public FastReader() {
            br = new BufferedReader(new InputStreamReader(System.in));
        }

        String next() {
            while (st == null || !st.hasMoreElements()) {
                try {
                    st = new StringTokenizer(br.readLine());
                } catch (IOException e) {
                    e.printStackTrace();
                }
            }
            return st.nextToken();
        }

        int nextInt() {
            return Integer.parseInt(next());
        }

        long nextLong() {
            return Long.parseLong(next());
        }

        double nextDouble() {
            return Double.parseDouble(next());
        }

        String nextLine() {
            String str = "";
            try {
                str = br.readLine();
            } catch (IOException e) {
                e.printStackTrace();
            }
            return str;
        }
    }

    public static void main(String[] args) throws Exception {
        // TODO Auto-generated method stub
        FastReader sc = new FastReader();
        BufferedWriter ou = new BufferedWriter(new OutputStreamWriter(System.out));
        // Start coding
        int tc = sc.nextInt();
        for (int o = 0; o < tc; o++) {
            double x = sc.nextInt();
            double y = sc.nextInt();

            if (y <= (x * 107) / 100) {
                ou.write("YES \n");

            } else {
                ou.write("NO \n");
            }
        }
        ou.flush();
    }
}
```
#### Time Taken: 2 min

### Problem #3 Sugarcane Juice Business 
#### [Problem Statement](https://www.codechef.com/MAY221D/problems/SUGARCANE)
#### Related Topics:

Math

#### Code:
```java
import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.lang.Math;
import java.util.*;
import java.io.*;
import java.util.*;
import java.util.StringTokenizer;

import javax.lang.model.element.Element;

public class Main {
    static class FastReader {
        BufferedReader br;
        StringTokenizer st;

        public FastReader() {
            br = new BufferedReader(new InputStreamReader(System.in));
        }

        String next() {
            while (st == null || !st.hasMoreElements()) {
                try {
                    st = new StringTokenizer(br.readLine());
                } catch (IOException e) {
                    e.printStackTrace();
                }
            }
            return st.nextToken();
        }

        int nextInt() {
            return Integer.parseInt(next());
        }

        long nextLong() {
            return Long.parseLong(next());
        }

        double nextDouble() {
            return Double.parseDouble(next());
        }

        String nextLine() {
            String str = "";
            try {
                str = br.readLine();
            } catch (IOException e) {
                e.printStackTrace();
            }
            return str;
        }
    }

    public static void main(String[] args) throws Exception {
        // TODO Auto-generated method stub
        FastReader sc = new FastReader();
        BufferedWriter ou = new BufferedWriter(new OutputStreamWriter(System.out));
        // Start coding
        int tc = sc.nextInt();
        for (int o = 0; o < tc; o++) {
            int x = sc.nextInt();

            int ti = x * 50;

            int p = (ti * 30) / 100;
            ou.write(p + "\n");
        }
        ou.flush();
    }
}
```
### Time Taken: 3 mins

### Problem #4 The Attack of Queen  
#### [Problem Statement](https://www.codechef.com/MAY221D/problems/QUEENATTACK)
#### Related Topics:

Math

#### Code:
```java
import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
import java.lang.Math;
import java.util.*;
import java.io.*;
import java.util.*;
import java.util.StringTokenizer;

import javax.lang.model.element.Element;

public class Main {
   static class FastReader {
      BufferedReader br;
      StringTokenizer st;

      public FastReader() {
         br = new BufferedReader(new InputStreamReader(System.in));
      }

      String next() {
         while (st == null || !st.hasMoreElements()) {
            try {
               st = new StringTokenizer(br.readLine());
            } catch (IOException e) {
               e.printStackTrace();
            }
         }
         return st.nextToken();
      }

      int nextInt() {
         return Integer.parseInt(next());
      }

      long nextLong() {
         return Long.parseLong(next());
      }

      double nextDouble() {
         return Double.parseDouble(next());
      }

      String nextLine() {
         String str = "";
         try {
            str = br.readLine();
         } catch (IOException e) {
            e.printStackTrace();
         }
         return str;
      }
   }

   public static void main(String[] args) throws Exception {
      // TODO Auto-generated method stub
      FastReader sc = new FastReader();
      BufferedWriter ou = new BufferedWriter(new OutputStreamWriter(System.out));
      // Start coding
      int tc = sc.nextInt();
      for (int o = 0; o < tc; o++) {
         int n = sc.nextInt();
         int X = sc.nextInt();
         int Y = sc.nextInt();

         int a1 = Math.min(Math.abs(X - 1), Math.abs(Y - 1));
         int a2 = Math.min(Math.abs(X - 1), Math.abs(n - Y));
         int a3 = Math.min(Math.abs(n - X), Math.abs(Y - 1));
         int a4 = Math.min(Math.abs(n - X), Math.abs(n - Y));

         int a5 = (n - 1) * 2;

         int ans = a1 + a2 + a3 + a4 + a5;

         ou.write(ans + "\n");

      }
      ou.flush();
   }
}
```
### Time Taken: 10 min