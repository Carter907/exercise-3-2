```
BEGIN
	CLASS Program
		Main METHOD
			DOUBLE speed = (CONVERT TO DOUBLE) PROMPT USER("Please enter the windspeed of the Hurricane")

        		IF speed >= 157 THEN

				PRINT
				- "Category Five Hurricane"

		        ELSE IF speed >= 130 THEN
		        
				PRINT
				- "Category Four Hurricane"
		
			ELSE IF speed >= 111 THEN

				PRINT
				- "Category Four Hurricane"
		
			ELSE IF speed >= 96 THEN
		        
				PRINT
				- "Category Four Hurricane"
		
			ELSE IF speed >= 74 THEN
		        
				PRINT
				- "Category Four Hurricane"
		
		        ELSE
				PRINT
				- "Not a Hurricane"

		END Main
	END Program
END
```
