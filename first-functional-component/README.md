Goes over the concept of components and the difference between named and default functional components

function boop () {
    return <div> Hello World!</div>;
}

export default boop;

**allows for "import boop from '<folder structure here>'

can also be written as an arrow function:
export const Greet = () => <h1> Hello World!</h1>

export function boop () {
    <blah blah blah>
}

** requires named ex.) "import {boop} from '<folder structure here>'

Goes over class component structure

**WORD OF ADVICE FROM CODEVOLUTION**
> Use functional components whenever possible.
    - Are SIMPLE
    - They do not use the 'this' keyword which is used in classes
    - solution without using state
    - mainly responsible for UI

- fucntional components are also called:
    - Stateless/Dumb/Presentational components

- Class components are more feature-rich than functional components
    - can maintain their own private data > State
    - comles UI Logic
    - Provide lifecycle hooks
    - also called Stateful/Smart/Container components