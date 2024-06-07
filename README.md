```
BEGIN
	CLASS Program
		Main METHOD
          DOUBLE speed = (CONVERT TO DOUBLE) PROMPT USER("Please enter the windspeed of the Hurricane")

        if (speed >= 157)
        {
            Console.WriteLine("Category Five Hurricane");


        }
        else if (speed >= 130)
        {
            Console.WriteLine("Category Four Hurricane");


        }
        else if (speed >= 111)
        {
            Console.WriteLine("Category Three Hurricane");

        }
        else if (speed >= 96)
        {

            Console.WriteLine("Category Two Hurricane");

        }
        else if (speed >= 74)
        {

            Console.WriteLine("Category One Hurricane");

        }
        else
        {

            Console.WriteLine("Not a Hurricane");
        }
		END Main
	END Program
END
```
