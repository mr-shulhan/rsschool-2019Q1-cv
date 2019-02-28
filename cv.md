
# SHULHAN ANDREI

>** shulhan.andrei@gmail.com**
>** +375-25-736-57-40**   

## Summary


Beginner front-end programmer. Which has a minimal experience in the layout of sites, but even less programming experience.
> But this is just the start =)

## Skills
- JavaScript
- HTML5
- CSS
- GIT

## Code examples
      fun (str) => {
      let acc = 0;
      for (let i = 0; i < str.length; i += 1) {
        const symbol = str[i];
        acc = symbol === '(' ? acc + 1 : acc - 1;
        if (acc < 0) {
          return false;
        }
      }
      return acc === 0;
    };
