# signin/signup
function login(userName, password) {
    const users = ["Alice", "Bob", "Charlie"]; // Array with some usernames

    if (!users.includes(userName)) {
        return "User Not Found, Please Signup";
    } else if (password === "Emp@123") {
        return "Login Successful...";
    } else {
        return "Wrong Password....";
    }
}

// Example tests
console.log(login("Alice", "Emp@123")); // Output: Login Successful...
console.log(login("David", "Emp@123")); // Output: User Not Found, Please Signup
console.log(login("Bob", "WrongPass")); // Output: Wrong Password....
