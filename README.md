
![Git outta here!](./assets/poster.png)

# Web 3 Hackathon

Welcome to the very first Web 3 hackathon! 

Today's challenge is to create an interactive digital escape room. As digital designers, we'll use our favorite tools: HTML, CSS, JavaScript, and Git.

[Let's git ready to rumble!](https://www.youtube.com/watch?v=nendMLrpI-s)


## Challenge 0: Team Up!
Divide yourselves into teams of **three**. 

## Challenge 1: Set Up Repository (1 per team)
One team member should complete the following steps:
### 1. Create a Repository 
Create a new repository named after your project or team.

### 2. Create a README.md File
In your repository, create a README.md file.

Include the names of all team members.

Example:

```markdown
# Team Devine

- Alice Smith 
- Bob Johnson 
- Charlie Lee 
```

### 3. Commit and Push
Add and commit the README.md file to your local repository.

Push the commit to GitHub.

### 4. Share Your Repository URL
Provide the URL of your GitHub repository via [this form](https://forms.gle/VHo5o13paYTLBANU8).

## CHALLENGE 2: Setup project
To save some time, we will provide you with a basic HTML and CSS template.

![Escape Room](./assets/template.gif)

One team member should complete the following steps:

### 1. HTML

Create an index.html file in your repository.

Add the following code to your index.html file. As you can see, the code includes a form with four input fields. Each input field has a pattern attribute that specifies the correct number for that field. This will be the combination to escape the room.

```html
  <main>
    <h1>git outta here!</h1>
    <nav>
      <ul>
        <li><a href="#">room 1</a></li>
        <li><a href="#">room 2</a></li>
        <li><a href="#">room 3</a></li>
        <li><a href="#">room 4</a></li>
      </ul>
    </nav>
    <p>
      Find the right combination of numbers to escape the room.
    </p>

    <form action="https://shorturl.at/7mHvR">
      <input type="text" pattern="1" placeholder="0" required size="1">
      <input type="text" pattern="2" placeholder="0" required size="1">
      <input type="text" pattern="3" placeholder="0" required size="1">
      <input type="text" pattern="4" placeholder="0" required size="1">
      <button type="submit">git out</button>
    </form>
  </main>
```

### 2. CSS
Add a CSS file to your repository. 

Add the following code to your CSS file:

```css
:root {
  --error: #ff0000;
  --primary: #000000;
  --primary-light: #c9c9c9;
}

::selection {
  background-color: var(--primary);
  color: white;
}

body {
  height: 100vh;
  font-family: monospace;
  font-size: 1rem;
  display: grid;
  place-items: center;
  gap: 1rem;
}

main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
  gap: 1rem;
}

h1 {
  font-size: 3rem;
}

ul {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
  gap: 1rem;
}

a {
  color: var(--primary);
}

input {
  background: none;
  border: none;
  font-size: inherit;
  font-family: inherit;
  border-bottom: dashed 1px var(--primary);
  text-align: center;
}

input:focus {
  outline-color: var(--primary);
}

input::placeholder {
  color: var(--error);
}

form {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  justify-content: center;
  gap: 0.5em;
  font-size: 3rem;
  border: solid 2px var(--primary);
  padding: 1rem;
  background-color: var(--primary-light);
}

button {
  grid-column: 1 / -1;
  background: var(--primary);
  border: none;
  color: white;
  font-family: inherit;
  font-size: inherit;
}

button:focus {
  outline: solid 1px var(--primary);
}

input:invalid {
  color: var(--error);
  border-color: var(--error);
}

form:has(:invalid) button {
  opacity: 0.1;
  background-color: #ff0000;
}
```
### 3. Commit and Push
Add and commit the index.html and CSS files to your local repository.

Push the commit to GitHub.

Make sure that everyone in your team has access to the repository and pulls the latest changes.

