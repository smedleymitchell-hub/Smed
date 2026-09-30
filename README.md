# Smed
Smeds kingdom <!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The El-Sayed Family</title>

<style>
    /* Universal Reset & Sizing */
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    /* Base Styling */
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        line-height: 1.6;
        background-color: #f4f7f6;
        color: #333;
    }

    /* Layout Header */
    header {
        background-color: #2c3e50;
        color: #fff;
        padding: 2rem;
        text-align: center;
    }

    header h1 {
        margin-bottom: 0.5rem;
    }

    /* Main Container */
    .container {
        max-width: 1100px;
        margin: 2rem auto;
        padding: 0 1rem;
    }

    /* Intro Section */
    .intro {
        text-align: center;
        margin-bottom: 3rem;
    }

    /* Grid Layout for Family Members */
    .family-grid {
        display: flex;
        flex-wrap: wrap;
        gap: 2rem;
        justify-content: center;
    }

    /* Individual Cards */
    .member-card {
        background: #fff;
        border-radius: 8px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        width: 280px;
        padding: 1.5rem;
        text-align: center;
        transition: transform 0.2s ease-in-out;
    }

    .member-card:hover {
        transform: translateY(-5px);
    }

    .avatar-placeholder {
        width: 100px;
        height: 100px;
        background-color: #bdc3c7;
        border-radius: 50%;
        margin: 0 auto 1rem;
    }

    .member-card h3 {
        color: #2c3e50;
        margin-bottom: 0.5rem;
    }

    .member-card p {
        font-size: 0.95rem;
        color: #666;
    }

    /* Footer */
    footer {
        text-align: center;
        padding: 2rem;
        margin-top: 4rem;
        background-color: #2c3e50;
        color: #fff;
        font-size: 0.9rem;
    }
</style>
</head>
<body>

    <header>
        <h1>The El-Sayed Family</h1>
        <p>Welcome to our family space</p>
    </header>

    <div class="container">
        <section class="intro">
            <h2>Our Story</h2>
            <p>A simple place to share our favorite memories, updates, and milestones with friends and loved ones.</p>
        </section>

        <main class="family-grid">
            <!-- Family Member 1 -->
            <div class="member-card">
                <div class="avatar-placeholder"></div>
                <h3>Name</h3>
                <p>A short sentence or bio about this family member goes here.</p>
            </div>

            <!-- Family Member 2 -->
            <div class="member-card">
                <div class="avatar-placeholder"></div>
                <h3>Name</h3>
                <p>A short sentence or bio about this family member goes here.</p>
            </div>

            <!-- Family Member 3 -->
            <div class="member-card">
                <div class="avatar-placeholder"></div>
                <h3>Name</h3>
                <p>A short sentence or bio about this family member goes here.</p>
            </div>
        </main>
    </div>

    <footer>
        <p>&copy; 2026 The El-Sayed Family. All rights reserved.</p>
    </footer>

</body>
</html>

