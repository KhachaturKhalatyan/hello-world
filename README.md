# hello-world
First in Git
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Hello World</title>
    <script src="https://unpkg.com/react@latest/dist/react.js"></script>
    <script src="https://unpkg.com/react-dom@latest/dist/react-dom.js"></script>
    <script src="https://unpkg.com/babel-standalone@6.15.0/babel.min.js"></script>
  </head>
  <body>
    <div id="root"></div>
    <script type="text/babel">
const Destination = document.getElementById("root");
function greet(uzer){
  return uzer.firstName +" "+ uzer.lastName;
}

var uzer = {
 firstName: "Firstname",
 lastName: "Lastname"
};

const element = (
 <h1>
  Hello {greet(uzer)}!
 </h1>
);
     ReactDOM.render(
  element,
 Destination
);

    </script>
  </body>
</html>
