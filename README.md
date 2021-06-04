# Firenet
Firestore orm for .net applications. A simple to manipulate firestore database in an easy way keeping the same domain driven developer.


## Installation
Download by dotnet cli:  

```   
  Install-Package Firenet  
```

## How to use

Put the data annotations in the class model and properties:
![image](https://user-images.githubusercontent.com/30809620/120727373-bda61b00-c4b0-11eb-8586-37573b936c20.png)

Create a class the implement 'FireContext', and write the jsonCredential with the path and create the fireCollections that represents the models that you want:
![image](https://user-images.githubusercontent.com/30809620/120727771-c519f400-c4b1-11eb-9685-58c2743cbdbc.png)

Add on startup configureServices:
![image](https://user-images.githubusercontent.com/30809620/120727866-feeafa80-c4b1-11eb-8e81-b4feab63224f.png)

Or in console application, instance:
![image](https://user-images.githubusercontent.com/30809620/120727951-33f74d00-c4b2-11eb-840e-c560ebcf68b2.png)
