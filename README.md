# plantuml-functions


Including files works as follows:

```
!include https://raw.githubusercontent.com/Cloud-Team-Eagle/plantuml-functions/main/public-holidays-bw-2021.iuml 
!include https://raw.githubusercontent.com/Cloud-Team-Eagle/plantuml-functions/main/functions.iuml
```


![your-UML-diagram-name](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/Cloud-Team-Eagle/plantuml-functions/main/demo.iuml)



```plantuml
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response
   
Alice -> Bob: Another authentication Request
Alice <-- Bob: Another authentication Response
```
