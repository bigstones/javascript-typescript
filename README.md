# javascript

자바스크립트 공부하면서 설정하면 좋을 것 코드 작성중입니다

## filter

    
    class Animal{
    constructor(name, age) {
    this.name = name;
    this.age = age;
    }
    }
    
    const animals = [
    new Animal('dog', 1)
    new Animal('cat', 2)
    ]
    
    const name_result = animals.filter((animal) => animal.name);
    const age_result = animals.filter((animal) => animal.age);
    

## map

    class Animal{
    constructor(name, age) {
    this.name = name;
    this.age = age;
    }
    }
    
    const animals = [
    new Animal('dog', 1)
    new Animal('cat', 2)
    ]
    
    const result = students.map((student)=> student.age);


## reduce

    class Animal{
    constructor(name, age) {
    this.name = name;
    this.age = age;
    }
    }
    
    const animals = [
    new Animal('dog', 1)
    new Animal('cat', 2)
    ]
    
    const result = students.reduce((prev, curr)=> {return prev + curr.age}, 0);


## some


## every


## join

    const test = ['a', 'b', 'c']
    const testjoin = test.join('')

    console.log(testjoin)
    // 'abc'

## string
문자 길이

    value.toString().length;
    
[if문](https://github.com/bigstones/javascript-typescript/blob/main/if.js)
    
    if(조건) {
    
    } else if {
    
    }

## 연산자

    || #or
    && #and
    ! #not


# typescript

## decorator

## type inference

    interface Person {
        name: string;
        sex: number;
    }

    interface Car {
        brand: string;
        model: string;
    }

    function isPerson(arg: any): arg is Person {
        return arg.name !== undefined;
    }

    function hello(arg: Person | Car) {
        if (isPerson(arg)) {
            console.log(arg.name);
        } else {
            console.log(arg.brand)
        }
    }
    
