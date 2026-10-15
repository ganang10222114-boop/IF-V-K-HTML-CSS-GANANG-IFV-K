# IF-V-K-HTML-CSS-GANANG-IFV-K
Tugas pertemuan 4 HTML &amp; CSS
NAMA : GANANG AJI PRATAMA
KELAS : IF V K
PRODI : TEKHNIK INFORMATIKA
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>PEMWEB</title>
    <header>
        <h1>🌐 HTML Learning Project</h1>
        <p>Master the Building Blocks of the Web</p>
    </header>
    <!--section 1 what is html ? -->
    <section id="what-is-html">
        <h2>🚀 What is HTML?</h2>
        <p><strong>(HyperText Markup Language)</strong> is the standard markup language for creating web pages. Think of it as the skeleton or foundation of every website you visit.</p>
    </section>

    
    <div class="key-points"">
    <h3>Key points</h3>
    <ul>
        <li><strong>HyperText:</strong> Text with links to other texts</li>
        <li><strong>Markup:</strong>A way to annotate text to show structure and meaning</li>
        <li><strong>Language:</strong> A set of rules and syntax for creating web content</li>
    </ul>
    
    </div>

    <h3>🏗️ How HTML Works</h3>
   <p> HTML uses <strong>tags</strong> to define elements. Tags are keywords surrounded by angle brackets like <code>&lt;tagname&gt;</code>. Most tags come in pairs:</p>

   <pre>
    <code>
&lt;tagname&gt;Content goes here&lt;/tagname&gt;
&lt;h1&gt;This is a heading&lt;/h1&gt;
&lt;p>This is a paragraph&lt;/p&gt;
   </code>
</pre>




</head>
<body>
    
</body>
</html>


* {
    box-sizing: border-box;
}

body {
    margin: 0;
    padding: 30px;
    background: linear-gradient(135deg, #667eea, #764ba2);
    font-family: Arial, sans-serif;
    color: #34495e;
}

.container {
    max-width: 1100px;
    margin: auto;
    padding: 30px;
    background: #f7f8fc;
    border-radius: 14px;
}

header {
    text-align: center;
    margin-bottom: 28px;
}

header h1 {
    font-size: 26px;
    margin-bottom: 12px;
}

header p {
    color: #85929e;
    font-size: 14px;
}

section {
    background: white;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.06);
}

#what-is-html {
    border-left: 4px solid #3498db;
}

h2 {
    color: #2980b9;
    font-size: 20px;
    border-bottom: 2px solid #3498db;
    padding-bottom: 12px;
}

h3 {
    font-size: 16px;
}

p, li {
    font-size: 13px;
    line-height: 1.7;
}

.key-points {
    background: linear-gradient(120deg, #b2f0e9, #ffd1e1);
    border-left: 3px solid #ff6b6b;
    padding: 12px;
    border-radius: 8px;
    margin-top: 15px;
}

.key-points h3 {
    margin-top: 0;
}

pre {
    background: #2c3e50;
    color: #ecf0f1;
    padding: 18px;
    border-radius: 8px;
    overflow-x: auto;
    font-size: 12px;
}

code {
    font-family: Consolas, monospace;
}

a {
    color: #2980b9;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

@media (max-width: 600px) {
    body {
        padding: 12px;
    }

    .container {
        padding: 18px;
    }

    header h1 {
        font-size: 21px;
    }
}

