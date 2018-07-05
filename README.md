# Project1
This is the test project # 1
// afew more line of code

function doSomething(todo, callback) {
  alert(`Open my ${todo} task.`);
  callback();
}
function callClosing(){
  alert('Closed the task');
}
doSomething('typing', callClosing);

// Open my typing task
// Closed the task
