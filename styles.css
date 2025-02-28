
let form = document.getElementById("form");

form.addEventListener("submit", (ev)=>{
  ev.preventDefault();
  let username = document.getElementById("username").value;
  let password = document.getElementById("password").value;
  if(username && password){
    alert(`Logged in as ${username}`);
  }else{
    alert("Please Enter the username and password.")
  }
  let checkbox = document.getElementById("checkbox");
  if(checkbox.checked){
    localStorage.setItem("credentials", JSON.stringify({username: `${username}`, password: `${password}`}));
  }else{
    localStorage.clear();
  }
});

let existing = document.getElementById("existing");
existing.addEventListener("click", (ev)=>{
  let existingCredentials = localStorage.getItem("credentials");
  if(existingCredentials){
    let prevUser = JSON.parse(existingCredentials);
    alert(`Logged in as ${prevUser.username}`);
  }else{
    alert("You don't have saved Credentials, pleas login again.")
  }
});


