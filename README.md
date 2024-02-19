html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>海洋生物日常与环境</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>海洋生物日常与环境</h1>
        <nav>
            <ul>
                <li><a href="#about">关于海洋生物</a></li>
                <li><a href="#environment">海洋环境</a></li>
                <li><a href="#gallery">图片库</a></li>
                <li><a href="#contact">联系我们</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>关于海洋生物</h2>
        <p>在这个部分，我们将介绍一些海洋生物的基本信息，包括它们的习性、饮食、栖息地等。</p>
    </section>

    <section id="environment">
        <h2>海洋环境</h2>
        <p>这里将探讨海洋环境的重要性，以及保护海洋环境的必要性。我们将讨论海洋污染、气候变化等问题。</p>
    </section>

    <section id="gallery">
        <h2>图片库</h2>
        <p>欣赏一些美丽的海洋生物图片，并了解它们的故事。</p>
        <!-- 这里可以添加一些图片 -->
    </section>

    <section id="contact">
        <h2>联系我们</h2>
        <p>如果您对海洋生物或环境保护有任何疑问或建议，请随时联系我们。</p>
        <form action="#">
            <label for="name">姓名:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">邮箱:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">留言:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">发送</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 海洋生物日常与环境</p>
    </footer>
</body>
</html>
