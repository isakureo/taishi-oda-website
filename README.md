<!DOCTYPE html>
<html lang="ja" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>小田太志 / Taishi Oda - Official Website</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&family=Noto+Sans+JP:wght@300;400;500;700&display=swap" rel="stylesheet">
    
    <!-- Custom Styles -->
    <style>
        body {
            font-family: 'Noto Sans JP', sans-serif;
            background-color: #fdfdfc; /* わずかに温かみのある白 */
            color: #3a3a3a; /* 少し柔らかい黒 */
        }
        h1, h2, h3, h4, h5, h6 {
            font-family: 'Lora', serif;
        }
        .section-title::after {
            content: '';
            display: block;
            width: 50px;
            height: 2px;
            background-color: #a3a3a3; /* アクセントカラー */
            margin-top: 1rem;
        }
        .fade-in-up {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.8s ease-out, transform 0.8s ease-out;
        }
        .fade-in-up.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header -->
    <header id="header" class="bg-white/80 backdrop-blur-lg fixed top-0 left-0 right-0 z-50 shadow-sm transition-all duration-300">
        <div class="container mx-auto px-6 py-3 flex justify-between items-center">
            <a href="#top" class="text-xl font-bold tracking-wider">Taishi Oda</a>
            <nav class="hidden md:flex space-x-8 text-sm tracking-widest">
                <a href="#profile" class="hover:text-gray-500 transition-colors">私について</a>
                <a href="#creations" class="hover:text-gray-500 transition-colors">制作物</a>
                <a href="#lens" class="hover:text-gray-500 transition-colors">探究の方法</a>
                <a href="#contact" class="hover:text-gray-500 transition-colors">お問い合わせ</a>
            </nav>
            <button id="mobile-menu-button" class="md:hidden focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden">
            <nav class="px-6 pt-2 pb-4 flex flex-col space-y-2">
                <a href="#profile" class="block py-2 hover:text-gray-500 transition-colors">私について</a>
                <a href="#creations" class="block py-2 hover:text-gray-500 transition-colors">制作物</a>
                <a href="#lens" class="block py-2 hover:text-gray-500 transition-colors">探究の方法</a>
                <a href="#contact" class="block py-2 hover:text-gray-500 transition-colors">お問い合わせ</a>
            </nav>
        </div>
    </header>

    <main id="top">
        <!-- Hero Section -->
        <section class="min-h-screen flex items-center bg-stone-50">
            <div class="container mx-auto px-6 py-20 text-center">
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold leading-tight mb-6 fade-in-up">そこに在ったはずの声を、聴く。</h1>
                <div class="max-w-3xl mx-auto space-y-6 text-base md:text-lg leading-relaxed text-gray-600 fade-in-up" style="transition-delay: 200ms;">
                    <p>こんにちは、小田太志です。</p>
                    <p>僕は、物事の「なぜ？」を、少し長く考えすぎてしまう癖があります。</p>
                    <p>たとえば、青森の市場で、ご婦人がピーマンに添えてくれた、たった一粒の梅干し。ほとんどの人が「ありがとう」で通り過ぎるその風景に、僕は立ち尽くしてしまいます。「なぜ、梅干しだったんだろう？」「この行為を成り立たせている、目に見えない関係性は何だろう？」</p>
                    <p>答えの出ない問いは、僕をフィールドへ、そして人の語りへと向かわせます。</p>
                    <p>地図には載らない語りは、もう一つの地形図です。どうぞ、あなたの知らない青森の凹凸を、一緒に歩いてみませんか。</p>
                </div>
            </div>
        </section>

        <!-- Profile Section -->
        <section id="profile" class="py-20 md:py-32">
            <div class="container mx-auto px-6">
                <div class="max-w-4xl mx-auto">
                    <h2 class="text-3xl md:text-4xl font-bold mb-12 section-title fade-in-up">私について / Profile</h2>
                    <h3 class="text-2xl md:text-3xl font-semibold mb-8 fade-in-up">衝動の軌跡</h3>
                    <p class="mb-12 max-w-2xl text-gray-600 leading-relaxed fade-in-up">僕という人間は、これまで積み重ねてきた「衝動」の総体なのかもしれません。誰かに見せるためではなく、ただ自分の「なぜ？」に突き動かされてきた道のりの、ほんの一部をご紹介します。</p>
                    
                    <div class="space-y-12">
                        <!-- 60以上のインターンシップ -->
                        <div class="fade-in-up">
                            <h4 class="text-xl font-bold mb-2">60以上のインターンシップ</h4>
                            <p class="text-gray-600 leading-relaxed">これは就職活動のための数字ではありません。働くとは何か、地域とは何か、人が生きるとはどういうことかを知るための、60以上の異なる窓でした。福祉施設で人の尊厳に触れ、漁港で自然の厳しさを学び、まちづくりNPOで理想と現実の狭間を見ました。そのすべてが、僕の血肉となっています。</p>
                        </div>
                        <!-- 年間365冊以上の読書 -->
                        <div class="fade-in-up">
                            <h4 class="text-xl font-bold mb-2">年間365冊以上の読書</h4>
                            <p class="text-gray-600 leading-relaxed">本を読むことは、遠い場所にいる人や、もうこの世にいない人たちと対話する時間です。地質学の専門書から、三島由紀夫の小説、人類学のフィールドノートまで。バラバラに見える知識が、ある日ふと、頭の中でつながる瞬間があります。その瞬間のために、僕は毎日ページをめくります。</p>
                        </div>
                        <!-- 北海道、家なしの二ヶ月 -->
                        <div class="fade-in-up">
                            <h4 class="text-xl font-bold mb-2">北海道、家なしの二ヶ月</h4>
                            <p class="text-gray-600 leading-relaxed">持てるものをすべて手放したとき、何が残るのか。それを知りたくて、リュック一つで北海道を漂泊しました。人の優しさと、自然の冷たさ。生きるために本当に必要なものは、驚くほど少ないことを、身体で学びました。</p>
                        </div>
                    </div>
                    <div class="mt-16 p-8 bg-stone-50 rounded-lg border border-stone-200 fade-in-up">
                        <p class="text-center text-gray-700 italic leading-relaxed">僕の行動は、効率や生産性とは無縁に見えるかもしれません。けれど、すぐに答えを出さずに問いを抱え続ける「遅い知性」こそが、この複雑な世界を生きる上で、確かな足場になると信じています。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Creations Section -->
        <section id="creations" class="py-20 md:py-32 bg-stone-50">
            <div class="container mx-auto px-6">
                <div class="max-w-4xl mx-auto">
                    <h2 class="text-3xl md:text-4xl font-bold mb-12 section-title fade-in-up">制作物 / Creations</h2>
                    <h3 class="text-2xl md:text-3xl font-semibold mb-8 fade-in-up">思考のかたち</h3>
                    <p class="mb-12 max-w-2xl text-gray-600 leading-relaxed fade-in-up">考えたこと、感じたことを、そのままにはしておけなくて。言葉や形を与えようと試みた、不器用な制作物の記録です。</p>
                    
                    <div class="grid md:grid-cols-3 gap-8">
                        <!-- 考察『まちとガードレール』 -->
                        <div class="bg-white p-8 rounded-lg border border-stone-200 shadow-sm hover:shadow-lg hover:-translate-y-1 transition-all duration-300 fade-in-up">
                            <h4 class="text-xl font-bold mb-4">考察『まちとガードレール』</h4>
                            <p class="text-gray-600 text-sm leading-relaxed">日本中どこにでもある、あの白いガードレール。誰も気に留めない風景の一部に、どんな意図や歴史が隠されているのか。路上に佇む匿名のアノニマスな存在から、近代日本の風景を読み解こうとする試みです。</p>
                        </div>
                        <!-- 構想『青森市民史ゲーム』 -->
                        <div class="bg-white p-8 rounded-lg border border-stone-200 shadow-sm hover:shadow-lg hover:-translate-y-1 transition-all duration-300 fade-in-up" style="transition-delay: 150ms;">
                            <h4 class="text-xl font-bold mb-4">構想『青森市民史ゲーム』</h4>
                            <p class="text-gray-600 text-sm leading-relaxed">もし、街の歴史が、読むものではなく体験するものだとしたら？お年寄りの語る記憶がゲームのクエストになり、失われた風景がマップ上に蘇る。そんな、遊びながら地域の記憶を継承する「ゲーム」の構想メモです。</p>
                        </div>
                        <!-- ZINE『声の地層』 -->
                        <div class="bg-white p-8 rounded-lg border border-stone-200 shadow-sm hover:shadow-lg hover:-translate-y-1 transition-all duration-300 fade-in-up" style="transition-delay: 300ms;">
                            <h4 class="text-xl font-bold mb-4">ZINE『声の地層』</h4>
                            <p class="text-gray-600 text-sm leading-relaxed">インタビューで出会った、消えてほしくない言葉たち。それらを拾い集め、手触りのある紙に印刷し、手製で綴じた小さな冊子です。デジタルでは伝わらない、言葉の重みや温度を届けたいと思っています。</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Lens Section -->
        <section id="lens" class="py-20 md:py-32">
            <div class="container mx-auto px-6">
                <div class="max-w-4xl mx-auto">
                    <h2 class="text-3xl md:text-4xl font-bold mb-12 section-title fade-in-up">探究の方法 / My Lens</h2>
                    <h3 class="text-2xl md:text-3xl font-semibold mb-8 fade-in-up">僕の世界の見方</h3>
                    <p class="mb-12 max-w-2xl text-gray-600 leading-relaxed fade-in-up">「面白いもの」は、どこか遠くにあるのではありません。世界を見る「レンズ」を少しだけ変えれば、足元の風景が、昨日とはまったく違って見えてきます。僕がいつも持ち歩いている、3つのレンズをご紹介します。</p>

                    <div class="space-y-10">
                        <div class="fade-in-up">
                            <h4 class="text-xl font-bold mb-2">1. 地質学者の眼で歩く</h4>
                            <p class="text-gray-600 leading-relaxed">目の前の坂道が、数万年前にできた海岸段丘だと知る。川の流れが、この街の産業をどう形作ったのかを想像する。人の営みという「表層」の下にある、土地が記憶する「基盤」を常に意識することで、風景は立体的になります。</p>
                        </div>
                        <div class="fade-in-up">
                            <h4 class="text-xl font-bold mb-2">2. 考現学者の耳で聴く</h4>
                            <p class="text-gray-600 leading-relaxed">なぜ、この店にはこの商品が並んでいるのか。なぜ、人々はこの言葉遣いをするのか。「今、ここ」にある当たり前の物や会話を、未来から来た考古学者のように観察し、記録します。ピーマンに添えられた一粒の梅干しは、僕にとって最高の遺物でした。</p>
                        </div>
                        <div class="fade-in-up">
                            <h4 class="text-xl font-bold mb-2">3. 物語の編集者として繋ぐ</h4>
                            <p class="text-gray-600 leading-relaxed">集めた事実や語りは、それだけではただの断片です。それらをどう繋ぎ、どんな文脈に置けば、新しい意味が生まれるのか。僕は、地域という大きなテクストを読む、一人の編集者でありたいと思っています。バラバラの記憶を繋ぎ合わせ、まだ誰も見たことのない「もう一つの地図」を描くこと。それが僕の探究です。</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="py-20 md:py-32 bg-stone-800 text-white">
            <div class="container mx-auto px-6">
                <div class="max-w-2xl mx-auto text-center">
                    <h2 class="text-3xl md:text-4xl font-bold mb-12 section-title mx-auto fade-in-up" style="--tw-text-opacity: 1; color: rgb(253 253 252 / var(--tw-text-opacity));">お問い合わせ / Contact</h2>
                    <h3 class="text-2xl md:text-3xl font-semibold mb-8 fade-in-up">あなたの声を、聴かせてください。</h3>
                    <p class="mb-12 text-stone-300 leading-relaxed fade-in-up">僕の探究は、いつも誰かの小さな声に耳を澄ますことから始まります。ご意見、ご感想、あるいはあなたの街の物語。どんな些細なことでも構いません。ここに書き留められたあなたの言葉が、僕にとっての新しい地図になります。</p>
                    
                    <form action="#" method="POST" class="space-y-6 text-left fade-in-up">
                        <div>
                            <label for="name" class="block text-sm font-medium text-stone-300">お名前</label>
                            <input type="text" name="name" id="name" class="mt-1 block w-full bg-stone-700 border-stone-600 rounded-md shadow-sm py-2 px-3 text-white focus:outline-none focus:ring-stone-500 focus:border-stone-500">
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-stone-300">メールアドレス</label>
                            <input type="email" name="email" id="email" class="mt-1 block w-full bg-stone-700 border-stone-600 rounded-md shadow-sm py-2 px-3 text-white focus:outline-none focus:ring-stone-500 focus:border-stone-500">
                        </div>
                        <div>
                            <label for="message" class="block text-sm font-medium text-stone-300">メッセージ</label>
                            <textarea id="message" name="message" rows="4" class="mt-1 block w-full bg-stone-700 border-stone-600 rounded-md shadow-sm py-2 px-3 text-white focus:outline-none focus:ring-stone-500 focus:border-stone-500"></textarea>
                        </div>
                        <div class="text-center">
                            <button type="submit" class="inline-flex justify-center py-3 px-12 border border-transparent shadow-sm text-sm font-medium rounded-md text-stone-800 bg-white hover:bg-stone-100 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-stone-500 focus:ring-offset-stone-800 transition-colors">
                                声を届ける
                            </button>
                        </div>
                    </form>

                    <div class="mt-16 fade-in-up">
                        <h4 class="text-lg font-semibold mb-4">日々の記録と、思考のかけら</h4>
                        <p class="text-stone-300 mb-6">フィールドワークの道中や、何気ない日常から見つけた思考のかけらは、インスタグラムでも綴っています。</p>
                        <a href="https://www.instagram.com/isakureo/" target="_blank" rel="noopener noreferrer" class="inline-block bg-white text-stone-800 font-bold py-2 px-4 rounded-full hover:bg-stone-200 transition-colors">
                            <svg class="inline-block w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.85s-.011 3.584-.069 4.85c-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07s-3.584-.012-4.85-.07c-3.252-.148-4.771-1.691-4.919-4.919-.058-1.265-.069-1.645-.069-4.85s.011-3.584.069-4.85c.149-3.225 1.664-4.771 4.919-4.919 1.266.058 1.644.07 4.85.07zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948s.014 3.667.072 4.947c.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072s3.667-.014 4.947-.072c4.358-.2 6.78-2.618 6.98-6.98.059-1.281.073-1.689.073-4.948s-.014-3.667-.072-4.947c-.2-4.358-2.618-6.78-6.98-6.98-1.281-.059-1.689-.073-4.948-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.162 6.162 6.162 6.162-2.759 6.162-6.162-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4s1.791-4 4-4 4 1.79 4 4-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.441 1.441 1.441 1.441-.645 1.441-1.441-.645-1.44-1.441-1.44z"></path></svg>
                            Instagram: @isakureo
                        </a>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-stone-100">
        <div class="container mx-auto px-6 py-6 text-center text-stone-500 text-sm">
            <p>&copy; 2025 Taishi Oda. All Rights Reserved.</p>
        </div>
    </footer>

    <script>
        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when a link is clicked
        const mobileNavLinks = mobileMenu.querySelectorAll('a');
        mobileNavLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        // Header shadow on scroll
        const header = document.getElementById('header');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 10) {
                header.classList.add('shadow-md');
            } else {
                header.classList.remove('shadow-md');
            }
        });

        // Fade-in animations on scroll
        const faders = document.querySelectorAll('.fade-in-up');
        const appearOptions = {
            threshold: 0.2,
            rootMargin: "0px 0px -50px 0px"
        };
        const appearOnScroll = new IntersectionObserver(function(entries, appearOnScroll) {
            entries.forEach(entry => {
                if (!entry.isIntersecting) {
                    return;
                } else {
                    entry.target.classList.add('visible');
                    appearOnScroll.unobserve(entry.target);
                }
            });
        }, appearOptions);

        faders.forEach(fader => {
            appearOnScroll.observe(fader);
        });
    </script>
</body>
</html># taishi-oda-website
