# Reading Notes for Day 4 of 301:

## Readings: React and Forms

### Reading [React Docs - Forms](https://reactjs.org/docs/forms.html)

- What is a ‘Controlled Component’?

An element whose native responses overwritten by React instructions. Kind of like mind control but with programming.

- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

With a controlled component we update state with every keystroke, this allows us to update in real time, and pass data to other UI elements and event handlers. As to whether or not we should, that's kind of a meaningless judgement, but personally I think all this rush to capture data is kind of creepy. 

- How do we target what the user is entering if we have an event handler on an input field?

We use the value captured in this.state.value.

### [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

- Why would we use a ternary operator?

We want to evaluate code that equates to true/false and make decisions based on the result, and we want to write less code to do it.

- Rewrite the following statement using a ternary statement:

        if(x===y){
          console.log(true);
        } else {
          console.log(false);
        }

x===y ? console.log(true) : console.log(false);

### Bookmark and Review
[React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)
[React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)

## Things I want to know more about:

I'm kind of dreading forms, but also looking forward to having the power to abuse people's information. I'm also looking forward to the inevitable code challenge with ternary operators. I used to know how to use them, and they definitely can shorten code, if you write to a true/false response, which is pretty easy to do in code, since in the end everything is either a zero or a one. PS, writing assignments should be due at 1pm. That way we could read during the daytime. Just a thought.