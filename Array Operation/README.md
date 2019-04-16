//https://slate.skillenza.com/
//Javascript (Node.js v10.14.1)

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
        
        process.stdout.write(lines[i].toString());
        process.stdout.write("\n");
    }
}
