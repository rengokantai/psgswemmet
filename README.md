#### psgswemmet
#####4 CSS
######1
```
bt5  //border-top:5px;
bt5e  // 5em
p5-15  //padding 5px 15px;
```
######2
```
bxsh ->box-shadow
```
#####5 custom scripts
#####2 create custom script
in config file,(sublime) see
```
"extensions_path":"~/emmet",
```
create a foler emmet in home dict,
create file snippets.json
```
{
  "html" : {
    "snippets" :{
      "bs-btn:default" :"<button class=\"btn btn-default\">|</button>"
    }
  }
}
```
then shift ctrl p and `emmet reload`
