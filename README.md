
#### PROBLEM NAME : Solve Me First
#### AUTHOR : shashank21j
#### URL : https://www.hackerrank.com/challenges/solve-me-first/problem
#### JAVASCRIPT CODE :
process.stdin.resume();

process.stdin.setEncoding('ascii');

var input_stdin = "";

var input_stdin_array = "";

var input_currentline = 0;

process.stdin.on('data', function (data) {

    input_stdin += data;
    
});

process.stdin.on('end', function () {

    input_stdin_array = input_stdin.split("\n");
    
    main();    
    
});

function readLine() {

    return input_stdin_array[input_currentline++];
    
}
function solveMeFirst(a, b) {

  return a+b;
  
}

function main() {

    var a = parseInt(readLine());
    
    var b = parseInt(readLine());;

    var res = solveMeFirst(a, b);
    console.log(res);
}

#### PSEUDOCODE
input a = pick as integer from readLine input

input b = pick as integer from readLine input

process = a plus b

output = the value of a plus b

#### How to run the code :
1. copy JAVASCRIPT CODE 
2. open url 'https://www.hackerrank.com/challenges/solve-me-first/problem'
2. paste the JAVASCRIPT CODE to the code editor bar(replace the old code)
3. select "javascript(Node.js)" as the language
4. click Run Program Button at the bottom right of the code bar

