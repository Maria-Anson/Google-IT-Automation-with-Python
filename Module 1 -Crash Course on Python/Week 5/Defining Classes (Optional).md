# Defining Classes (Optional)
> 
> * * *
> 
> We can create and define our classes in Python similar to how we define functions. We start with the **class** keyword, followed by the name of our class and a colon. Python style guidelines recommend class names to start with a capital letter. After the class definition line is the class body, indented to the right. Inside the class body, we can define attributes for the class.
> 
> Let's take our Apple class example:
> 
> <pre contenteditable="false" data-language="python" tabindex="0" style="opacity: 1;">
> 
> 1
> 
> 2
> 
> 3
> 
> 4
> 
> >>> class Apple:
> 
> ...     color = ""
> 
> ...     flavor = ""
> 
> ... 
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> We can create a new instance of our new class by assigning it to a variable. This is done by calling the class name as if it were a function. We can set the attributes of our class instance by accessing them using dot notation. Dot notation can be used to set or retrieve object attributes, as well as call methods associated with the class.
> 
> <pre contenteditable="false" data-language="python" tabindex="0" style="opacity: 1;">
> 
> 1
> 
> 2
> 
> 3
> 
> >>> jonagold = Apple()
> 
> >>> jonagold.color = "red"
> 
> >>> jonagold.flavor = "sweet"
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> We created an Apple instance called jonagold, and set the color and flavor attributes for this Apple object. We can create another instance of an Apple and set different attributes to differentiate between two different varieties of apples.
> 
> <pre contenteditable="false" data-language="python" tabindex="0" style="opacity: 1;">
> 
> 1
> 
> 2
> 
> 3
> 
> >>> golden = Apple()
> 
> >>> golden.color = "Yellow"
> 
> >>> golden.flavor = "Soft"
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> We now have another Apple object called golden that also has color and flavor attributes. But these attributes have different values.
>
> -- https://www.coursera.org/learn/python-crash-course/supplement/gri8d/defining-classes-optional#main
