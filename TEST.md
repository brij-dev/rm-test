### Question 1 
Write a function that takes input as param and returns ourput given below
Input: 
    
     [
      {
        student_data:{
          name:'A',
          id: 123,
          marks:[{'hi':11,'mt':22,'en':20}]
        }
      },
      {
        student_data:{
          name:'B',
          id: 124,
          marks:[{'hi':12,'mt':20,'en':10}]
        }
      },
      {
        student_data:{
          name:'C',
          id: 125,
          marks:[{'hi':12,'mt':22,'en':23}]
        }
      }
    ];
Output


    {
      '123': {
        name: 'A',
        total_marks: 52
      },
      '124': {
        name: 'B',
        total_marks: 56
      },
      '125': {
        name: 'C',
        total_marks: 57
      }
    }
    
### Question 2 
Create a function that returns which chapter is nearest to the page you're on. If two chapters are equidistant, return the chapter with the higher page number.

Example
```nearestChapter({
  "Chapter 1" : 1,
  "Chapter 2" : 15,
  "Chapter 3" : 37
}, 10) ➞ "Chapter 2"
```

* Note - Please use only Javascript to write programs 



  
