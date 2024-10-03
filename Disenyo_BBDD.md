EMPLEADO (DATOS PERSONALES)

'id_empleado' PK 

'age'
'education'
'educationfield'
'gender'
'datebirth'
'yearsatcompany'
'maritalstatus'
'totalworkingyears' 
'distancefromhome' 
'numcompaniesworked'
'employeenumber'  
'attrition' 



-----------------------------------------------

PUESTO

'id_puesto' PK
'id_empleado' FK    

'joblevel'
'jobrole'
'roledepartament'  
'department'   
'businesstravel'
'overtime'
'remotework'
'yearssincelastpromotion'
'yearswithcurrmanager'
'trainingtimeslastyear'
'standardhours' 


-----------------------------------------------

COSTES

(( id_empleado PK 
id_puesto PK )) 

'dailyrate'
'hourlyrate'
'monthlyrate'
'yearincome'
'monthlyincome'
'stockoptionlevel'


-----------------------------------------------

VALORACIONES

(( id_empleado PK 
id_puesto PK )) 

'relationshipsatisfaction'
'percentsalaryhike'
'worklifebalance'
'jobinvolvement'
'jobsatisfaction'
'environmentsatisfaction'
'performancerating'


-----------------------------------------------








