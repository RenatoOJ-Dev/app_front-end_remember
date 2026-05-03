### CSS HEADER
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
  font-family: "Raleway", sans-serif;
  display: flex;
  min-height: 100vh;
  flex-direction: column;
}

header {
    display: flex;
    justify-content: center;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.108);
    padding: var(--10px-to-rem) 0;

}

h1, h2 {
    text-align:center;
}

### CSS FOOTER

footer {
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.108);
    padding: var(--10px-to-rem) 0;

}

### HTML

    <header>
        <div class="header-container-h1">
            <h1>Form.</h1>
        </div>
    </header>


### FOOTER

    <footer>
        <div class="footer-container">
            <h2>Column.</h2>
        </div>
    </footer>
