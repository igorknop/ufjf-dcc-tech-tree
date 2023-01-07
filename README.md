# 2022-1

```mermaid
flowchart BT

flowchart BT

    DCC013[DCC013\nEst. Dados I]
    DCC013 ==> DCC198
    DCC013 -.-> CPP

    DCC012[DCC012\nEst. Dados II]
    DCC012 ==> DCC013
    DCC012 -.-> CPP


    DCC025[DCC025\nOrientação\na Objetos]
    DCC025 ==> DCC013
    DCC025 -.-> Java([Java])

    DCC121[DCC121\nLP WebSites]
    DCC121 -.-> JS([JavaScript])
    DCC121 -.-> HTML([HTML])
    DCC121 -.-> CSS([CSS])
    
    DCC138[DCC138\nTópicos LP]
    DCC138 -.-> JS
    
    
    DCC192[DCC192\nLP Sist. Web I]
    DCC192==> DCC121
    DCC192==> DCC025
    DCC192 -.-> Java
    DCC192 -.-> JSP([JSP])
    DCC192 -.-> HTML
    DCC192 -.-> CSS

    DCC193[DCC193\nLP Sist. Web II]
    DCC193 ==> DCC192
    DCC193 -.-> Java([Java])
    DCC193 -.-> SpringBoot([SpringBoot])

    DCC195[DCC195\nLP Tendências]
    DCC195 -.-> JS
    DCC195 -.-> NodeJS([NodeJS])

    DCC196[DCC196\nLP Disp. Móveis]
    DCC196 ==> DCC121
    DCC196 ==> DCC025 
    DCC196 -.-> Java

    DCC199[DCC199\nAlgoritmos]
    DCC199 -.->C

    DCC198[DCC198\nAlgoritmos II]
    DCC198 ==> DCC199
    DCC198 -.->CPP(C++)

    classDef tech fill:#cfc,stroke:#333,stroke-width:1px
    class C,CPP,HTML,CSS,JS,NodeJS,Java,JSP,SpringBoot tech;
```

