## TemplateCode For Skillenza
[Javascript (Node.js v10.14.1)](https://slate.skillenza.com/)

The below code is the boiler plate code to take input and process the output
```
process.stdin.resume();
process.stdin.setEncoding("utf-8");
var stdin_input = "";

process.stdin.on("data", function(input) {
  stdin_input += input;
});

process.stdin.on("end", function() {
  main(stdin_input);
});

function main(input) {
    var lines = input.split("\n");
    
    for (var i = 0; i < lines.length; i++) {
        processLine(lines[i]);
    }
}
    
function processLine(line){
    process.stdout.write(line.toString());
    process.stdout.write("\n");
}
