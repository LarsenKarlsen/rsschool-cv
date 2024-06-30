## Andrei Pratasevich  
***
### Contacts
Location: Brest, Belarus  
Email: a.protasevich93@gmail.com  
Github: https://github.com/LarsenKarlsen
***
### About Me
Hello I'am Andrei and I will become software engineer. Big fan of AI, space, Warhammer and LOTR.  I'am an enthusiastic, self-motivated, reliable, responsible and hard working person. I am a mature team worker and adaptable to all challenging situations. I am able to work well both in a team environment as well as using own initiative.
***
### Languages
* Russian - Native
* English - A2-B1
***
### Work Experience
*  __RUE "Brestenergo" 09.2023 - now__  
__Deputy Head of Energy Sales Service__  
I am currently working in the energy sales service. My duties include leading a department with 14 subordinates. Nearly 600 people work in the company's branches in the direction of sales of electricity and heat energy. The energy sales direction intersects many production issues, such as legal, economic, technical, and others. To solve tasks, business process automation is actively introduced for both internal (billing for calculations with consumers, services for tracking meter devices, etc.) and external processes (personal accounts of household subscribers and legal entities, and several services for interaction with consumers).  
*  __RUE "Brestenergo" 10.2020 - 09.2023__  
__Engineer of the Production-Technical Department__  
I work with a large amount of data related to the operation of power plants, including one of the largest in the Republic of Belarus -  [Berezovskaya GRES](https://ru.wikipedia.org/wiki/%D0%91%D0%B5%D1%80%D1%91%D0%B7%D0%BE%D0%B2%D1%81%D0%BA%D0%B0%D1%8F_%D0%93%D0%A0%D0%AD%D0%A1_(%D0%91%D0%B5%D0%BB%D0%BE%D1%80%D1%83%D1%81%D1%81%D0%B8%D1%8F)). I am actively working on automation and digitalization of my work. 
I have drafted a technical specification for the development of software to automate business processes at my workplace. I am overseeing the development of this software.  
* __"Brest heating grid" 09.2016-10.2020__  
Created a model for forecasting the supply of thermal energy for the needs of the city of Brest using the methods of machine learning and neural networks(Xgb, Sklearn, pandas, TensorFlow).
***
### Education
- __Belarusian National Technical University 2016-2018__  
Specialty Power engineer
- __Brest State Technical Univercity at 2010-2015__  
Bachelor's Degree Civil Engineer (Faculty of Engineering Systems and Networks)
- __Courses:__
    - [Golang](https://stepik.org/cert/1641778)
    - [Rolling Scopes School ml-intro-2022Q1](https://app.rs.school/certificate/83h8ci71)
    - [FreeCodeCamp Python, ML](https://www.freecodecamp.org/certification/fcc26f24a5e-8ee4-41bd-8108-0723699c5895/machine-learning-with-python-v7)
    - [TheOdinProject (JS, CSS, HTML, React)](https://www.theodinproject.com/)
### Skills
* Python(django, pandas, matplotlib, sklearn, tensorflow etc)
* GIT
* JS (React), CSS, HTML
* SQL  
***
### Code Examples
* [ML Ready repository](https://github.com/LarsenKarlsen/eval-selection-9) to Kaggle competition [Forest Cover Type Prediction](https://www.kaggle.com/competitions/forest-cover-type-prediction)  

_JavaScript(Node) code example_
```
const sum = (a,b) => {
    return a+b
}

console.log(sum(1,2)) // 3
```
_Python code example_
```
def even_odd(arr: list[int]) -> float:
    """
    The function returns the ratio of the sum of even array elements to the sum of odd ones.
    Example:
    even_odd([1, 2, 3, 4, 5]) == 0.8889
    """
    sums = [0,0]
    for num in arr:
        if num%2==0:
            sums[0]+=num
        else:
            sums[1]+=num
    return  sums[0]/sums[1] if sums[1]>0 else 0
```
_Go code example_  
Given a number N, print out all integer values of a power of two not exceeding N, in ascending order.
```
package main
import ("fmt";"math")
        
func main() {
    var n float64
    fmt.Scanln(&n)
    
    for {
        for i:=0.;math.Pow(2,i)<=n;i++ {
            fmt.Print(math.Pow(2,i), " ")
        }
        break
    }
}
```