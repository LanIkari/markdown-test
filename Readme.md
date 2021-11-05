<!-- Tiltle --> 

# Mi titulo 
## Mi titulo H2
### Mi titutlo h3
#### Mi titutlo h4
##### Mi titutlo h5

<!-- Italic --> 
this is am *Italic* text
<!-- Strong --> 
this is an **Strong** text
<!-- strikethrough --> 
this is an ~~strikethrough~~ text

<!-- UL --> 
* apple
  * Apple_2
* orange
  * Orange_2
* etc.

1. Apple
2. Orange
3. etc.

<!-- UR --> 

LinkedIn: [BRANDON AVENDAÑO VILLEGAS](https://www.linkedin.com/in/brandon-avenda%C3%B1o-villegas-58b0291b4/ "Custom title")

<!-- Separadores --> 

> this is a quote

---
___

<!-- Code --> 

~~~java
public  Graph(int n){
        this.n = n;
        numberOfEdges=0;
        Vertax = new ArrayList<>(n);
        edges  = new int[n][n];
        isVisited = new boolean[n+1];
        distance = new double[n];
        for (int i = 0; i <n ; i++) {
            distance[i] = Double.POSITIVE_INFINITY;
        }

        path = new String[n];
        for (int i = 0; i <n ; i++) {
            path[i] = "";
        }
    }
~~~

<!-- Tables --> 

|Impuestos|importe|Total|
|---------|-------|-----|
|3%       |2%     |$580 |

<!-- Imagenes --> 


![Visual Studio Code Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/2048px-Visual_Studio_Code_1.35_icon.svg.png)

![Visual Studio Code Logo](Visual_Studio_Code_1.35_icon.svg.png "VSCode logo")

<!-- GITHUB MARKDOWN -->

* [X] Task 1
* [X] Task 2
* [X] Task 3
* [X] Task 4
