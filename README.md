<!DOCTYPE html>
<html>
<head>
	<title>Landing Page</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">Features</a></li>
				<li><a href="#">Pricing</a></li>
				<li><a href="#">Contact</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section class="hero">
			<h1>Welcome to Our Landing Page</h1>
			<p>This is a sample landing page, feel free to customize it as per your needs.</p>
			<button>Get Started</button>
		</section>
		<section class="features">
			<h2>Features</h2>
			<ul>
				<li>Feature 1</li>
				<li>Feature 2</li>
				<li>Feature 3</li>
			</ul>
		</section>
		<section class="call-to-action">
			<h2>Sign up for our newsletter</h2>
			<input type="email" placeholder="Your email address">
			<button>Subscribe</button>
		</section>
	</main>
	<footer>
		<p>Copyright © 2024 Landing Page. All rights reserved.</p>
	</footer>
</body>
</html>
body {
	font-family: Arial, sans-serif;
	margin: 0;
	padding: 0;
}

header {
	background-color: #f0f0f0;
	padding: 20px;
	text-align: center;
}

nav ul {
	list-style: none;
	margin: 0;
	padding: 0;
	display: flex;
	justify-content: space-between;
}

nav li {
	margin-right: 20px;
}

main {
	display: flex;
	flex-direction: column;
	align-items: center;
	padding: 20px;
}

.hero {
	background-image: linear-gradient(to bottom, #ccccff, #ffffff);
	padding: 20px;
	color: #333;
	text-align: center;
}

.features {
	background-color: #f7f7f7;
	padding: 20px;
}

.features ul {
	list-style: none;
	margin: 0;
	padding: 0;
}

.features li {
	margin-bottom: 10px;
}

.call-to-action {
	background-color: #333;
	color: #fff;
	padding: 20px;
	text-align: center;
}

.call-to-action input[type="email"] {
	padding: 10px;
	margin-bottom: 10px;
	border: none;
	border-radius: 5px;
}

.call-to-action button[type="submit"] {
	background-color: #4CAF50;
	color: #fff;
	padding: 10px 20px;
	border: none;
	border-radius: 5px;
	cursor: pointer;
}

footer {
	background-color: #f0f0f0;
	padding: 10px;
	text-align: center;
	color: #666;
}
