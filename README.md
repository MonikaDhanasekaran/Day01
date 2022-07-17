1.Write a blog on Difference between HTTP1.1 vs HTTP2:

          * HTTP2 is much faster and more reliable than HTTP1. 
          
          * HTTP1 loads a single request for every TCP connection, while HTTP2 avoids network delay by using multiplexing. 
          
          * HTTP is a network delay sensitive protocol in the sense that if there is less network delay, then the page loads faster.
          
          * These are the high-level differences between HTTP1 and HTTP2: 
          
                          1. HTTP2 is binary, instead of textual. 
          
                          2. HTTP2 is fully multiplexed, instead of ordered and blocking. 
                          
                          3. HTTP2 can, therefore, use one connection for parallelism.
                          
           * The first usable version of HTTP was created in 1997. Because it went through several stages of development, this first version of HTTP was called                      HTTP/1.1.            
           
           * This version is still in use on the web. In 2015, a new version of HTTP called HTTP/2 was created.

           * HTTP/2 solves several problems that the creators of HTTP/1.1 did not anticipate. In particular, HTTP/2 is much faster and more efficient than HTTP/1.1. 
           
           * One of the ways in which HTTP/2 is faster is in how it prioritizes content during the loading process.
           
2.Write a blog about objects and its internal representation in javascript:

           * Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript. These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).

          * Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types. An object, is a reference data type. Variables that are assigned a reference value are given a reference or a pointer to that value. That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.

          * Loosely speaking, objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.

          * For Eg. If your object is a student, it will have properties like name, age, address, id, etc and methods like updateAddress, updateNam, etc.
          
          * Creating Objects in JavaScript:

                    1.By object literal

                    2.By creating instance of Object directly (using new keyword)
            
           * By object literal:

                    1.The syntax of creating object using object literal is given below:

                              object = {property:value1,property2:value2,...,propertyN:valueN}

                    2.Property and value is separated by colon(:).

              Example:

                    var person ={
                    fname:"xxx",
                    lname:"yyy",
                    age:25,
                    }

           * By creating instance of Object directly (using new keyword):

                   1.The syntax of creating object directly is given below:

                             var objectname=new Object();

                   Here, new keyword is used to create object.

              Example:

                    var emp = new Object();
                    emp.id=101;
                    emp.name="xxx";
                    emp.salary=50000;

           * Accessing JavaScript Objects:

                   1.The syntax for accessing the property of an object is:

                             objectName.property

                                    (or)

                             objectName[“property”]

           * Accessing ‘fname’ from example 1 using dot operator,

                            person.fname
    
           * Accessing ‘name’ form example 2 using [],

                            emp["name"]
