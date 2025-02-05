
## Objective
The goal is to understand what factors make a car more or less expensive. As a result of the analysis, one should provide clear recommendations to a client—a used car dealership—as to what consumers value in a used car.

## Dataset Description

The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure the speed of processing.
It contains fields:
-	id              
- region          
- price           
- year            
- manufacturer    
- model           
- condition       
- cylinders       
- fuel            
- odometer        
- title_status    
- transmission    
- VIN             
- drive           
- size            
- type            
- paint_color     
- state           

## Findings
- Price column has outliers with prices ranging from $0 to $3024942282 (3 Million).
- Abnormalities such as missing values (NaNs) in several columns needed to be fixed through preprocessing.
- Inventory contains 83% of gas powered cars.
- Large percentage of null values in dataset for columsn - size (72%), cylinders (42%), condition (41%), VIN (38%), drive (31%), paint_color (31%) and type (22%).
- Ford car models are popular.
- Old cars with low odometer values have a potential to be sold quickly.
- Gathering more comprehensive and diverse data on used cars, including additional features such as maintenance history,market demand, could enrich the prediction model.


## Contact

For any questions or concerns, please contact [priyadarsheeni@gmal.com].

