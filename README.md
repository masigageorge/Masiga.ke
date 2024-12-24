<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landlord Portal</title>
    <link rel="stylesheet" href="styles.css">
    
    
</head>
<body>
    <header>
        <h1>LANDLORD PORTAL</h1>
        <nav>
            <a href="index.html">HOME</a>
            <a href="landlord.html">LANDLORD PORTAL</a>
            <a href="tenant.html">TENANT PORTAL</a>
    <a href="blog.html">HOUSES BLOG</a>
        </nav>
        
        
        
    </header>
    <section id="landlord">
        <h2>Post a House Vacancy</h2>
        <form action="submit_vacancy.php" method="post">
            <label for="title">Title:</label>
            <input type="text" id="title" name="title" required>

            <label for="location">Location:</label>
            <input type="text" id="location" name="location" required>

            <label for="rent">Rent (Ksh):</label>
            <input type="number" id="rent" name="rent" required>

            <label for="description">Description:</label>
            <textarea id="description" name="description" required></textarea>

            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 House Vacancy</p>
        <p>Masiga George</p>
    </footer>
</body>
</html>
