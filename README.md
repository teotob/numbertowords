# numbertowords
This simple application is used to convert input number into words.

Specification:
- ASP .NET 4.0
- IDE VS2010
- Web Application

How to run:
- Download the source code
- Extract the zip file. Run the solution "TobingTeofils.sln"

Default.aspx is to display a list of name in a repeater.
Exercise_2.aspx is to display words from inputed number.

Logic description: 
- Default.aspx: there is a class named People has two properties: FirstName and LastName and a constructor accept two parameters. This class will be loaded into a generic collection of type. In the aspx page there is a repeater to display the result. The datasource for repeater comes from the generic collection.
Don't try to change the class People to a static class. It will be error because static class is a parameterless constructor.

- Exercise_2.aspx: A method NumberToWord(string input), this method is a recursive method. It validates every input number and converts the numbers into words.
