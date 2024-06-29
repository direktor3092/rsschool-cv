
 ![man_and_cat](IMG_3449.jpg) 
                              
##_Alexei Shahov_  
#### Minsk, Belarus 
##### email: direktor3092@gmail.com
##### github: https://github.com/direktor3092
##### Mobile phone: +375-29-696-48-33
***
<a id="about">About:</a>
: Hello! I'm a beginner frontend developer and my goal at the moment is to become a junior frontend developer:) My strengths include perseverance, accuracy, responsibility, and a desire to learn new information.
***
<a id="myskills">My skills:</a>
: HTML, CSS, Sass, Flex, Grid, Responsive design/Media queries, БЭМ, Javascript, Git/Github
***
<a id="code_example">Code example:</a>
```
function towelSort (matrix) {
  if (matrix === undefined || matrix.length === 0) {
    return [];
  };
  let res = [];
  matrix.forEach((value, index) => {
    if (Array.isArray(value)) {
      if(index % 2 === 0){
      res = [...res, ...value];
      }else{
        res = [...res, ...value.reverse()];
      }
    }
  })
  return res
}
```