# tech.ai


https://www.figma.com/proto/AQ6xDkMqSW2He3SsN5ZnfH/Digital-Fuel?node-id=597-701&scaling=scale-down-width&page-id=530%3A238



/****style.css***/
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500&family=Roboto:wght@400;700&display=swap');

/* resets */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary-text-color: #183b56;
    --secondary-text-color: #577592;
    --accent-color: #2294ed;
    --accent-color-dark: #1d69a3;
    --padding-inline-section: 20px;
}

body {
    font-family: 'Poppins', sans-serif;
    color: var(--primary-text-color);
}


.container {
    max-width: 1180px;
    margin-inline: auto;
    padding-inline: var(--padding-inline-section);
    overflow: hidden;
}

.flex {
    display: flex;
    align-items: center;
}

.hover-link {
    color: var(--primary-text-color);
    transition: 0.2s ease-out;
}

.hover-link:hover {
    color: var(--accent-color);
}

.primary-button {
    background-color: var(--accent-color);
    border-radius: 6px;
    font-weight: 700;
    color: white !important;
    padding: 12px 24px;
    box-shadow: 0 0 2px var(--secondary-text-color);
    transition: 0.2s ease-out;
    text-align: center;
}

.primary-button:hover {
    background-color: var(--accent-color-dark);
}



/* companies section */

.companies-header {
    text-align: center;
    margin-block: 30px;
    color: var(--primary-text-color);
}

.logos {
    justify-content: space-evenly;
    flex-wrap: wrap;
    gap: 20px;
}

.logo {
    height: 46px;
}




@media screen and (min-width: 600px) {
    .logo{
        row-gap: 0px;
    }
