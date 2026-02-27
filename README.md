<!DOCTYPE html>
<html lang='bn'>
<head>
    <meta charset='UTF-8'/>
    <meta name='viewport' content='width=device-width, initial-scale=1.0'/>
    <title>মাসিক নবপথ | অনলাইন ম্যাগাজিন</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com"/>
    <style>
        @import url('https://fonts.googleapis.com');
        :root { --green: #006a4e; --gold: #b8860b; --bg: #fdfaf4; --fb: #1877F2; }
        body { font-family: 'Anek Bangla', sans-serif; margin: 0; background: var(--bg); color: #222; scroll-behavior: smooth; }
        header { text-align: center; padding: 40px 20px; background: #fff; border-bottom: 5px solid var(--green); }
        .main-cover { max-width: 350px; width: 100%; border-radius: 12px; margin-top: 25px; box-shadow: 0 10px 30px rgba(0,0,0,0.15); border: 4px solid #fff; }
        nav { background: var(--green); position: sticky; top: 0; z-index: 1000; display: flex; justify-content: center; box-shadow: 0 2px 10px rgba(0,0,0,0.2); flex-wrap: wrap; }
        .nav-item { position: relative; }
        .nav-item > a { display: block; padding: 15px 20px; color: #fff; text-decoration: none; font-weight: 500; }
        .dropdown { display: none; position: absolute; background: #fff; min-width: 250px; box-shadow: 0 8px 16px rgba(0,0,0,0.1); top: 100%; left: 0; border-radius: 0 0 8px 8px; z-index: 10; }
        .dropdown-item { padding: 12px 15px; border-bottom: 1px solid #eee; color: #333; display: block; text-decoration: none; }
        .dropdown-item span { font-size: 11px; color: var(--green); font-weight: bold; display: block; }
        .nav-item:hover .dropdown { display: block; }
        .container { max-width: 1000px; margin: 30px auto; padding: 0 20px; }
        .card { background: #fff; padding: 30px; border-radius: 15px; box-shadow: 0 5px 25px rgba(0,0,0,0.05); margin-bottom: 40px; border-top: 5px solid var(--gold); }
        input, textarea, select { width: 100%; padding: 12px; margin: 10px 0; border: 1px solid #ddd; border-radius: 8px; box-sizing: border-box; font-family: inherit; }
        .btn-submit { background: var(--green); color: #fff; border: none; padding: 15px; width: 100%; cursor: pointer; font-size: 18px; border-radius: 8px; font-weight: bold; width: 100%; }
        .fb-btn { background: var(--fb); color: #fff; display: block; text-align: center; padding: 12px; border-radius: 8px; text-decoration: none; margin-top: 15px; font-weight: bold; }
        .archive-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 25px; }
        .archive-item { text-align: center; background: #f9f9f9; padding: 15px; border-radius: 10px; border: 1px solid #eee; }
        footer { background: #111; color: #999; text-align: center; padding: 40px 20px; margin-top: 60px; }
    </style>
</head>
<body>
    <header id="home">
        <h1 style="color: var(--green); margin: 0; font-size: 50px;">মাসিক নবপথ</h1>
        <p>সত্য ও সুন্দরের পতাকাবাহী সাহিত্য ম্যাগাজিন</p>
        <img src="আপনার_ছবির_লিংক" class="main-cover" alt="প্রচ্ছদ">
    </header>
    <nav>
        <div class='nav-item'><a href='#home'>প্রচ্ছদ</a></div>
        <div class='nav-item'>
            <a href='#'>সম্পাদকবৃন্দ ▾</a>
            <div class='dropdown'>
                <a href='https://facebook.com' class='dropdown-item' target='_blank'><span>প্রধান সম্পাদক</span>মুহাম্মদ আব্দুল্লাহ</a>
                <a href='https://facebook.com' class='dropdown-item' target='_blank'><span>নির্বাহী সম্পাদক</span>হাসান মাহামুদ</a>
            </div>
        </div>
        <div class='nav-item'><a href='#archive'>পুরানো সংখ্যা</a></div>
        <div class='nav-item'><a href='#submit'>লেখা জমা</a></div>
        <div class='nav-item'><a href='#order'>অর্ডার</a></div>
    </nav>
    <div class='container'>
        <section id='order' class='card'>
            <h2>🛒 ম্যাগাজিন অর্ডার করুন</h2>
            <form action='https://formspree.io' method='POST'>
                <input type='text' name='Issue' placeholder='কোন সংখ্যা?' required>
                <input type='text' name='Address' placeholder='কুরিয়ার ঠিকানা' required>
                <input type='text' name='TrxID' placeholder='Transaction ID (TrxID)' required style="border: 2px solid var(--gold);">
                <button class='btn-submit' style='background: var(--gold);' type='submit'>অর্ডার কনফার্ম করুন</button>
            </form>
        </section>
        <section id='submit' class='card'>
            <h2>📝 লেখা জমা দিন</h2>
            <form action='https://formspree.io' method='POST' enctype='multipart/form-data'>
                <input type='text' name='Writer' placeholder='লেখকের নাম' required>
                <textarea name='Message' rows='6' placeholder='আপনার লেখা এখানে লিখুন...' required></textarea>
                <input type='file' name='File' accept='.pdf,.doc'>
                <button class='btn-submit' type='submit'>ইমেইলে পাঠান</button>
            </form>
            <a href='https://facebook.com' class='fb-btn' target='_blank'>ফেসবুকে জমা দিন</a>
        </section>
        <section id='archive' class='card'>
            <h2>আগের সংখ্যা (পিডিএফ ডাউনলোড)</h2>
            <div class='archive-grid'>
                <div class='archive-item'>
                    <strong>জানুয়ারি ২০২৬</strong><br>
                    <a href='পিডিএফ_লিংক' style="background:#e74c3c; color:#fff; padding:5px 10px; text-decoration:none; border-radius:4px; display:inline-block; margin-top:10px;">Download PDF</a>
                </div>
            </div>
        </section>
    </div>
    <footer><p>&copy; ২০২৬ মাসিক নবপথ | সর্বস্বত্ব সংরক্ষিত</p></footer>
</body>
</html>
