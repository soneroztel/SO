body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #f8f8f8;
}

header {
    background: #ff4500;
    padding: 15px;
    color: white;
    font-size: 24px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
}

.logo img {
    max-height: 60px;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
    font-size: 18px;
}

#hero {
    background: url('hero-image.jpg') no-repeat center center/cover;
    color: white;
    padding: 100px 20px;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    font-size: 24px;
}

.menu-items {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 20px;
}

.menu-item {
    background: white;
    margin: 15px;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    width: 250px;
}

.menu-item img {
    width: 100%;
    border-radius: 10px;
}

footer {
    background: #333;
    color: white;
    padding: 10px;
    position: relative;
    bottom: 0;
    width: 100%;
    margin-top: 20px;
}
