# Reading Notes for Day 28 of 401:

### effects hook

- What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?
It lets you perform side effects in function components.


### When using the useEffect Hook:

- What does useEffect do?
It allows you to run some additional code after React has updated the DOM.

- Why is useEffect called inside a component?
Runing it inside the component lets us access the count state variable (or any props) right from the effect.

- Explain the importance of properly implementing effects with Cleanup
If you don't properly clean up after some effects, you can introduce bugs because of the behavior of the leftover code.

### Reflection
- What are your learning goals after reading and reviewing the class README?
My goal at this point is just to try to make my code work.


### Things I want to know more about:

[back to Table of Contents](./README.md)