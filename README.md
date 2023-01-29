# Understanding TypeScript

Aim: 
- What TypeScript really is about and how it works
- Know how to combine TypeScript with ReactJS or NodeJS / Express
- Know TypeScript both in theory as well as applied to real use-cases and projects


## Getting Started 
![image](https://user-images.githubusercontent.com/104793540/215285561-ac73233e-a0c7-4f1f-a47a-ea637616becf.png)
![image](https://user-images.githubusercontent.com/104793540/215285658-dfe30563-26e6-4898-baba-2cb3d5b9b97e.png)

- https://www.typescriptlang.org/download
- check if i have node with `node --version` and i do already
- `npm install -g typescript`

```
const button = document.querySelector("button");
const input1 = document.getElementById("num1")! as HTMLInputElement;
const input2 = document.getElementById("num2")! as HTMLInputElement;

function add(num1: number, num2: number) {
  return num1 + num2;
}

button.addEventListener("click", function() {
  console.log(add(input1.value, input2.value));
});

```
-  `tsc using-ts.ts` in ide where ts file is
![image](https://user-images.githubusercontent.com/104793540/215287188-a6e44a0a-9450-4ec7-b0c1-e68a8292142e.png)
- fixed errors then ran  `tsc using-ts.ts`

TypeScript Advantages:

![image](https://user-images.githubusercontent.com/104793540/215287659-5541e30d-c1e2-49c5-aade-b3f3046e5b69.png)

### Plan

![image](https://user-images.githubusercontent.com/104793540/215287730-62d64ac2-974f-43db-8f4d-ac0c32f92514.png)

## TypeScript Basics & Basic Types

### Basic Types 
https://www.typescriptlang.org/docs/handbook/basic-types.html

- number 1,5.3, -10 all numbers, no diff between integers or floats
- string "hi", 'hi' all text values 
- boolean true, false  just these two, no "truthy" or "falsy" values
- array number [] = [1, 2, 3];
- tuple lets you express an array with a fixed number of elements whose types are known

let x: [string, number];

x = ["hello", 10]; 

- `npm start`

![image](https://user-images.githubusercontent.com/104793540/215333704-962b78a3-1823-45ef-8836-c7640c354d29.png)

## The TypeScript Compiler (and it's config)



## Next gen JavaScript & TypeScript
## Classes & Interfaces
## Advanced Types
## Generics 
## Decorators 
## Building Drag and Drop project 
## Modules & Namespaces 
## Using Webpack with TypeScript
## 3rd Party Libraries & TypeScript
## Building Select and Share a Place app (incl google maps)
## React.js & TypeScript
## Node.js + Express & TypeScript
