# new-xxx
<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ব্লগ ওয়েবসাইট</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>আমার ব্লগ</h1>
        <nav>
            <ul>
                <li><a href="#">হোম</a></li>
                <li><a href="#">অ্যাবাউট</a></li>
                <li><a href="#">কন্টাক্ট</a></li>
            </ul>
        </nav>
    </header>
   <main>
        <section class="blog-posts">
            <article>
                <h2>প্রথম ব্লগ পোস্ট</h2>
                <p>এই পোস্টের বিস্তারিত...</p>
                <button onclick="followBlog()">ফলো করুন</button>
                <button onclick="likePost()">লাইক</button>
                <button onclick="commentPost()">কমেন্ট</button>
                <button onclick="downloadPost()">ডাউনলোড</button>
                <button onclick="sharePost()">শেয়ার করুন</button>
                <!-- AdSense Ad Code -->
                <div class="adsense">
                    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
                    <ins class="adsbygoogle"
    style="display:block"
                         data-ad-client="ca-pub-XXXXXXXXXXXXXXX"
                         data-ad-slot="XXXXXXX"
                         data-ad-format="auto"></ins>
                    <script>
                         (adsbygoogle = window.adsbygoogle || []).push({});
                    </script>
                </div>
            </article>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 আমার ব্লগ</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin-right: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

.blog-posts article {
    background-color: white;
    padding: 20px;
    margin-bottom: 20px;
}

button {
    margin: 5px;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

.adsense {
    margin-top: 20px;
    text-align: center;
}
function followBlog() {
    alert('আপনি ব্লগটি ফলো করেছেন!');
}

function likePost() {
    alert('আপনি এই পোস্টটি লাইক করেছেন!');
}

function commentPost() {
    alert('কমেন্ট করার জন্য ধন্যবাদ!');
}

function downloadPost() {
    alert('পোস্ট ডাউনলোড হচ্ছে...');
}

function sharePost() {
    alert('পোস্ট শেয়ার করা হচ্ছে...');
}
