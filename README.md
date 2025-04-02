/* Stili generali */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #2c3e50;
    padding: 10px 0;
    color: white;
    text-align: center;
}

header .logo h1 {
    font-size: 24px;
}

nav ul {
    list-style-type: none;
    text-align: center;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Sezione Hero */
.hero {
    background: url('background.jpg') no-repeat center center;
    background-size: cover;
    height: 400px;
    color: white;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
}

.hero-content h2 {
    font-size: 48px;
    margin-bottom: 20px;
}

.hero-content p {
    font-size: 18px;
}

/* Prodotti */
#prodotti {
    padding: 50px 20px;
    text-align: center;
    background-color: #ecf0f1;
}

#prodotti h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

.product-gallery {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.product-card {
    background-color: white;
    border: 1px solid #ddd;
    padding: 20px;
    margin: 10px;
    width: 30%;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.product-card img {
    width: 100%;
    height: auto;
}

.product-card h3 {
    font-size: 20px;
    margin: 15px 0;
}

.product-card p {
    font-size: 16px;
}

/* Testimonianze */
#testimonianze {
    background-color: #fff;
    padding: 50px 20px;
    text-align: center;
}

.testimonials {
    display: flex;
    justify-content: center;
}

.testimonial {
    background-color: #bdc3c7;
    padding: 20px;
    margin: 10px;
    width: 300px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

/* Contatti */
#contatti {
    padding: 50px 20px;
    text-align: center;
}

/* Footer */
footer {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 10px;
    position: relative;
    bottom: 0;
    width: 100%;
}
