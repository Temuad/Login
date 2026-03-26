<!DOCTYPE html>
<html lang="en">
<head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <title>Signup - Archive</title>
</head>
<body>
    <div class="container mt-5">
        <div class="row justify-content-center">
            <div class="col-md-6 card p-4 shadow">
                <h2 class="text-center">Create Account</h2>
                <form id="regForm" method="POST" onsubmit="return validateForm()">
                    <div class="row">
                        <div class="col-md-6 mb-3"><input type="text" name="fname" class="form-control" placeholder="First Name" required></div>
                        <div class="col-md-6 mb-3"><input type="text" name="lname" class="form-control" placeholder="Last Name" required></div>
                    </div>
                    <input type="text" name="phone" class="form-control mb-3" placeholder="Phone Number" required>
                    <input type="email" name="email" class="form-control mb-3" placeholder="Email" required>
                    <input type="password" id="pw" name="password" class="form-control mb-3" placeholder="Password" required>
                    <input type="password" id="cpw" class="form-control mb-3" placeholder="Confirm Password" required>
                    <button type="submit" class="btn btn-primary w-100">Sign Up</button>
                </form>
                <p class="mt-3 text-center">Already have an account? <a href="login.php" class="text-info">Login</a></p>
            </div>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
