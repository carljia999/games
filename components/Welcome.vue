<template>
    <div class="body">
        <header>
        <h1>Zombie Bomb Game</h1>
    </header>

    <main>
        <p>Welcome to the Zombie Bomb Game by <span class="author">Jason Jia</span> with help of ChatGPT! 
        </p> <p>Choose your difficulty level and test your skills.
            Can you survive the zombie apocalypse and defeat the boss?</p>

        <div class="game-levels">
            <a href="game.html" class="game-level">Easy Level</a>
            <a href="game2.html" class="game-level">Medium Level</a>
            <a href="game3.html" class="game-level">Hard Level</a>
        </div>
    </main>

    <footer>
        <p>&copy; 2024 JJ Games.</p>
    </footer>
    </div>
</template>

<style scoped>
.body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #333;
    color: white;
    text-align: center;
    height: 100vw;
}

header {
    padding: 20px;
    background: #444;
}

h1 {
    margin: 0;
    font-size: 2.5em;
}

p {
    font-size: 1.2em;
    margin: 20px 0;
}

.author {
    font-size: 1.3em;
    font-weight: 600;
    color: rgba(255, 115, 0, 0.852);
}

.game-levels {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 15px;
    margin-top: 30px;
}

.game-level {
    padding: 10px 20px;
    background: #555;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-size: 1.5em;
    transition: background 0.3s;
}

.game-level:hover {
    background: #777;
}

footer {
    margin-top: 40px;
    font-size: 0.9em;
    color: #aaa;
}
</style>