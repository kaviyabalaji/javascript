# 1
```
let age=30;
const name="Alice";
 name="bob";
 console.log(name)
```
# 2
```
const add=(a,b)=>{
    console.log(a+b) ;
}
add(9,11);


```
# 3
```
let name="Alice";
let age=30;
let txt=`Hello,${name} Your age is ${age}.`;
console.log(txt);
```
# 4
```
const person={
    firstName: "Alice", 
    lastName: "Johnson"
}
const{firstName,lastName}=person;
console.log(firstName);
console.log(lastName)
```
# 5
```
const numbers = [1, 2, 3, 4, 5];

const [first, second] = numbers;

console.log(first);  
console.log(second);
```
# 6
```
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];

const combined = [...arr1, ...arr2];

console.log(combined);
```
# 7
```
const sum = (...numbers) => numbers.reduce((acc, current) => acc + current, 0);

console.log(sum(1, 2, 3, 4, 5)); 
console.log(sum(50, 40));        
console.log(sum());
```
# 8
```
const greet = (name, greeting = "Hello") => `${greeting}, ${name}!`;

console.log(greet("Alice"));          
console.log(greet("Bob", "Hi"));      
console.log(greet("Charlie", "Hey"));
```
# 9
```

class Animal {
    constructor(name) {
      this.name = name;
    }
  }
  
  class Dog extends Animal {
    bark() {
      return `Woof! My name is ${this.name}`;
    }
  }
  
  const myDog = new Dog('Julie');
  console.log(myDog.bark());

```
# 10
```
const waitAndReturn = () => 
    new Promise(resolve => setTimeout(() => resolve("Done"), 2000));
  
  async function run() {
    const result = await waitAndReturn();
    console.log(result); 
  }
  
  run();
```
# output
![image](https://github.com/kaviyabalaji/javascript/blob/main/Screenshot%202024-07-08%20110517.png)
![image](https://github.com/kaviyabalaji/javascript/blob/main/Screenshot%202024-07-08%20110525.png)
![image](https://github.com/kaviyabalaji/javascript/blob/main/Screenshot%202024-07-08%20110532.png)
![image](https://github.com/kaviyabalaji/javascript/blob/main/Screenshot%202024-07-08%20110537.png)
![image](https://github.com/kaviyabalaji/javascript/blob/main/Screenshot%202024-07-08%20110543.png)
![image](https://github.com/kaviyabalaji/javascript/blob/main/Screenshot%202024-07-08%20110548.png)
![image](https://github.com/kaviyabalaji/javascript/blob/main/Screenshot%202024-07-08%20110632.png)
![image](https://github.com/kaviyabalaji/javascript/blob/main/Screenshot%202024-07-08%20110632.png)
![image](https://github.com/kaviyabalaji/javascript/blob/main/Screenshot%202024-07-08%20110638.png)
![image](https://github.com/kaviyabalaji/javascript/blob/main/Screenshot%202024-07-08%20110646.png)
