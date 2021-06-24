# Node Ecosystem, TDD, CI/CD
## Array.map()  
Array.map() is an array method the loops over the elements of the array it take an arrow function as an argument and does some work on the values and return the result of the work.    

## Array.filter()  
Array.filter() is an array method the loops over the elements of the array it take an arrow function as an argument and returns the elment if it satisfies a condition.    

## Array.reduce()  
Array.reduce() is an array method the loops over the elements of the array it take an arrow function and an acculmator as arguments and does some work on the values and return one value as a result.  
  
## superagent code snippets  
with .then():  
`superagent.get(apiLink).then(result=>{/*do some work*/}).catch(e){/*do some thing with the error if there is an error*/}`  
with async and await:  
`async function getData(){  let result = await superagent.get(api_link); /*do some work with result*/}; getData();`