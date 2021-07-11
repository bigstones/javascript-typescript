# javascript

자바스크립트 공부하면서 설정하면 좋을 것 코드 작성중입니다


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
    
