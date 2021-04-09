# This project is about Model Refactoring in ATL transformation languages (Model Driven Engineering)
### Sometimes in models, there are conditions that we have to use Model Refactoring, these conditions are as follows 

- [x] we have **two classes** that have same **one or more common property**, this two classes have **same parent class** in our model, /_see figure below_/  (this is **issue 1**) 
<img src="https://drive.google.com/file/d/1BkZ18p8xAfZDCP6rOgpG5MVkqT0ACB_H/view?usp=sharing" width="180">

- [x] we have **many classes** that **two classes of them** have same **one or more common property**, all of the classes have **same parent class** in our model, /_see figure below_/   (this is **issue 2**)
<img src="https://panikoweb.ir/Me&MrShams/2-i.jpg" width="350">

- [x] we have **many root classes** that **two classes of them** have same **one or more common property**, /_see figure below_/ (this is **issue 3**)
<img src="https://panikoweb.ir/Me&MrShams/3-i.jpg" width="350">

See this [article](https://www.sciencedirect.com/science/article/pii/S0167642313001871) for more information
### So you've got to know the story so far / what's the solution?
- [x] **solution for issue 1**: at first, search and find those **same properties** of **both classes**, then move these **same properties** to **same parent class**, /_see figure below_/ (this is **Rule 1**) 
-*maybe we have more than two classes!(another senario)
<img src="https://panikoweb.ir/Me&MrShams/1-sol.jpg" width="350">

- [x] **soultion for issue 2**: at first, find **classes** that have **common properties**, create **one middle class** for **each classes that ever have one or more common properties**, this properties must move to **middle class** /_see figure below_/ (this is **Rule 2**)  
-*Generalisation link must be created carefully
<img src="https://panikoweb.ir/Me&MrShams/2-sol.jpg" width="710">

- [x] **solution for issue 3**: af first, find **classes** that have **common properties**, create **one root class** for all of **these**, then move properies must be done. /_see figure below_/ (this is **Rule 3**)
-*Generalisation link must be created.
<img src="https://panikoweb.ir/Me&MrShams/3-sol.jpg" width="700">


## How to Use?
1. Download git and then extract it in eclipse-workspace
1. See **metamodel** from metamodel folder (Ecore file)
1. See **class-to-class.atl** from transform folder (**comment** is good thing for better understanding, see those)
1. Running is easy, just click at **launch file**, (before that, make sure that **target model** is deleted)
1. Click **run** (each launch file that you like)
1. See target model from your source model in model folder (Open each model with **sample reflective ecore model editor**)

## need help/more?
download this [pdf](https://panikoweb.ir/Me&MrShams/Model-Refactoring-ATL.pdf), and take a quite look!

@ModelRefactoring 2020 :100: by [@Mr-talebi]() and [@Mr-Shams]()
> [University of isfahan](https://ui2.ui.ac.ir/)

> Thank's to [Dr.Shekoufeh Kolahdouz-Rahimi](https://mdse.ui.ac.ir/member/shekoufeh-kolahdouz-rahimi/)


