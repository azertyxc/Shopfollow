body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f9f9f9;
}
header, footer {
  background: #333;
  color: white;
  padding: 1em;
  text-align: center;
}
nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  padding: 0;
}
nav ul li {
  margin: 0 10px;
}
nav a {
  color: white;
  text-decoration: none;
}
.hero {
  padding: 2em;
  text-align: center;
  background: #e3e3e3;
}
.products {
  padding: 1em;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1em;
}
.product {
  background: white;
  border: 1px solid #ccc;
  padding: 1em;
  text-align: center;
}
button {
  background: #007bff;
  color: white;
  border: none;
  padding: 0.5em 1em;
  cursor: pointer;
}
button:hover {
  background: #0056b3;
}
