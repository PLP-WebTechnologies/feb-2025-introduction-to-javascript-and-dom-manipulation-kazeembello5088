<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dynamic Content and Style with JavaScript</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>

    <header>
        <h1>Welcome to My Web Page</h1>
        <p>This page demonstrates how to change text and style with JavaScript.</p>
    </header>

    <main>
        <section>
            <h2>Change the content</h2>
            <p id="dynamic-text">This is a paragraph that will change.</p>
            <button id="change-text-btn">Change Text</button>
        </section>

        <section>
            <h2>Modify the styles</h2>
            <p id="style-text">This text will change style.</p>
            <button id="change-style-btn">Change Style</button>
        </section>

        <section>
            <h2>Add/Remove an element</h2>
            <div id="dynamic-container">
                <p>Click the button to add or remove an element.</p>
            </div>
            <button id="toggle-element-btn">Add/Remove Element</button>
        </section>
    </main>

    <footer>
        <p>Created with love and JavaScript.</p>
    </footer>

    <script src="script.js"></script>
</body>

</html>
