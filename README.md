```
@startuml
officer -> Bob: get orderinfo()
officer <- Bob: display result()
@enduml
```
http://www.plantuml.com/plantuml/png/oqzBoqnEBLBGjLDmoa-oKaXFBL78Bqf9BShCIylNqEJAXyhRw4BaKpAB2t8IAnMAKejBSqeqD040



```
@startuml
Noon->Noon: love
@enduml
```
http://www.plantuml.com/plantuml/png/yylFpzErymEILWev-MMf0000



```
@startuml
noon -[#red]> new : i love you
new -[#000000]>noon : i hate you
@enduml
```
http://www.plantuml.com/plantuml/png/oylFprFGZLOkIas9jLF8IorNi5B8LCZ9BqjLgCmlvG8906KDm23MBW-a6gGW8x44h000



```
@startuml
box "Internal Service" #LightBlue
participant aCilent
	participant aDirector
end box
participant aConcreteBuilder

aCilent -> aDirector : new director
aDirector -> aConcreteBuilder : BuildpartA
@enduml
```

http://www.plantuml.com/plantuml/png/NOv12i9G34JNvXIXhhs02y7MZU3E4wJ_3nhuv9UGQe-l5OlKxSoyn_HrukPi0JSfV8K_DA7XxKLlzsZB21h4GvCEOi7IQO45RLRXIHqfgXCiSr-dFwHQSWJQKKk64tqbl3kmB2ZlsV3al9X-nRpgreht-2ERJnnV



```
@startuml
hide footbox

User -> system: Login
system --> User: Hello (User)
@enduml
```
http://www.plantuml.com/plantuml/png/oyXCILL8oyylISgluE8ABKujKj2rKoYkB2v9pRLIyCbFpypZWl0KT84I80LM2XwfEJdv2XeWZYO0





# OOAD-WEEK10
Sequence Diagram


README.md 
md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```

ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
 
