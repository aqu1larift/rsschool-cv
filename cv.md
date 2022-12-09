# Klimov Dmitry

## Contacts: 

* telegram: @i3rave
* email: aquilariftest@gmail.com

## About Me:
Hello. I am 25 years old. I don't have a background in information technology, I'm just trying to learn. I will be glad if I can gain useful knowledge during this course

## Skills:

Javascript knowledge for solving the simplest tasks

## Code:

`const smallesDivisor = (n) => {
    if (n === 1) {
        return 1;
    }
        const iteration = (counter) => {
            if (n % counter === 0) {
                return counter;
            } else if (counter < n) {
                return iteration(counter + 1);
            }
            return counter;
        };
    return iteration(2);
};`

### English: beginner