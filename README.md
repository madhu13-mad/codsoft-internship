# codsoft-internship
html code for level 1 task 1 portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>John Doe</h1>
        <p>Web Developer | Designer | Problem Solver</p>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <img src="your-photo.jpg" alt="John Doe">
        <p>Hello! I am a passionate web developer with expertise in creating responsive and user-friendly websites. My goal is to deliver impactful solutions that meet client needs.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML & CSS</li>
            <li>JavaScript</li>
            <li>React.js</li>
            <li>Node.js</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Portfolio Website</h3>
            <img src="project1.jpg" alt="Portfolio Website">
            <p>A personal portfolio showcasing my skills and work.</p>
        </div>
        <div class="project">
            <h3>E-commerce Website</h3>
            <img src="project2.jpg" alt="E-commerce Website">
            <p>An online store with a dynamic shopping cart and payment integration.</p>
        </div>
    </section>

    <section id="resume">
        <h2>Resume</h2>
        <a href="resume.pdf" download>Download My Resume</a>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: johndoe@example.com</p>
        <p>Phone: +123 456 7890</p>
    </section>

    <footer>
        <p>&copy; 2024 John Doe. All rights reserved.</p>
    </footer>
</body>
</html>
 css code level 1 task 1 portfolio
 
8/12/2024
Forwarded
Data Manipulation with Pandas.pdf
9 pages•PDF•83 kB
08:16
Forwarded
Handling Missing Data.pdf
11 pages•PDF•178 kB
08:16
Forwarded
Hierarchical Indexing.pdf
8 pages•PDF•714 kB
08:16
Forwarded
Pivot table in Pandas.pdf
6 pages•PDF•90 kB
08:16
Forwarded
UNIT IV NumPy Array Notes.pdf
9 pages•PDF•110 kB
08:16
10/12/2024
Forwarded
#include <stdio.h>
#include <stdlib.h>

// A tree node
struct Node {
    int data;
    struct Node* left;
    struct Node* right;
};

// Function to create a new node
struct Node* newNode(int data) {
    struct Node* node = (struct Node*)malloc(sizeof(struct Node));
    node->data = data;
    node->left = NULL;
    node->right = NULL;
    return node;
}

// Function to insert a new node in the binary tree
struct Node* insert(struct Node* node, int data) {
    if (node == NULL) return newNode(data);

    if (data < node->data)
        node->left = insert(node->left, data);
    else if (data > node->data)
        node->right = insert(node->right, data);

    return node;
}

// Inorder traversal (Left, Root, Right)
void inorder(struct Node* root) {
    if (root…Read more
22:10
15/12/2024
Forwarded many times

11:42
FRIDAY
WEB DEVELOPMENT PROJECTS.pdf
15 pages•PDF•618 kB
19:48
TODAY
/* styles.css */

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color: #f4f4f4;
}

header {
    text-align: center;
    background: #333;
    color: #fff;
    padding: 1rem 0;
}

header h1 {
    margin: 0;
}

section {
    padding: 2rem;
    margin: 1rem auto;
    max-width: 800px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

section h2 {
    text-align: center;
    color: #333;
}

#about img {
    display: block;
    margin: 0 auto 1rem;
    width: 150px;
    height: 150px;
    border-radius: 50%;
    border: 3px solid #333;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    background: #f8f8f8;
    margin: 0.5rem 0;
    padding: 0.5rem;
    border: 1px solid #ddd;
    border-radius: 4px;
}

.project {
    margin: 1rem 0;
    text-align: center;
}

.project img {
    width: 100%;
    max-width: 400px;
    border-radius: 4px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    text-align: center;
    background: #333;
    color: #fff;
    padding: 1rem 0;
    margin-top: 1rem;
}
