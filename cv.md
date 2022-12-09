# **Loshkarov Denis**
# **Contact**
* **Email** loshkarov55@gmail.com
# ***About ME***

*Maintenance engineer with experience in the service industry, computer, mobile and office equipment repair, cartridge refilling. Working with documents, 1c, setting up a digital signature (keys). Communication with clients. Experience in creating and managing a repair company, from repair to solving all company issues, creating and developing websites.*
=============================
# ***Work experience 9 years 2 months***
* **АО «АКГ «РБС»**
    + ***APCS department worker***
        - Reading and reporting LND documents 
        - Remote assistance in setting up a PC and software 
        - Installing EDS keys 
        - Renewing and installing certification.
* **OОO «КартриджТехплюс»**
    + ***Electronics, Tool Engineering***
        - Organization and creation of an equipment repair company
        - Search and communication with customers,participation in tenders.
        - Repair, firmware, diagnostics of office peripherals
        - Repair and setup of stationary computers and laptops
        - Repair of mobile equipment
        - Refueling, diagnostics of cartridges and maintenance of office equipment.Work with accounting 1c
        - Hiring and training new employees
* **ТУП «АСБК»**
    + ***Service Engineer***
        - Service maintenance of Apple equipment

# ***Professional development***    
* **Oki Corporation Technical Course**
     + ***Oki Corporation, Oki's Technical Service engineer***
* **Kyocera Technical Course**
     + ***Kyocera company, Kyocera Service enginee***     
* **Mikrotik programming course**
     + ***Mikrotik, Mikrotik programmer***      
* **Epson Technical course**
     + ***Epson, Service engineer***   

# ***Languages***
* **Russian — Native**
* **English — B1 — Intermediate**

# ***Code example***
* **Exemples**
    
       zipWith( Math.pow, [10,10,10,10], [0,1,2,3] )      =>  [1,10,100,1000]
       zipWith( Math.max, [1,4,7,1,4,7], [4,7,1,4,7,   1] )  =>  [4,7,7,4,7,7]
       
       zipWith( function(a,b) { return a+b; }, [0,1,2,3], [0,1,2,3] )  =>  [0,2,4,6]  Both forms are valid.
       zipWith( (a,b) => a+b,                  [0,1,2,3], [0,1,2,3] )  =>  [0,2,4,6]  Both are functions.
* **Solution**
      
      function zipWith(fn,a0,a1) 
      {let arr = [];   
      const short = Math.min(a0.length, a1.length);
      for (let i=0;i<short;i++){arr.push(fn(a0[i],a1[i]))}   return arr }