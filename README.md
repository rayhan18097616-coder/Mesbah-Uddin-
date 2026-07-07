<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mesbah Uddin | Documentary Portfolio</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* সিনেমাটিক ডার্ক ব্যাকগ্রাউন্ড গ্লো */
        body {
            background-color: #0d0d11;
            color: #e2e8f0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        .glow-effect {
            box-shadow: 0 0 20px rgba(59, 130, 246, 0.2);
        }
    </style>
</head>
<body class="selection:bg-blue-600 selection:text-white">

    <!-- Header / Navigation -->
    <header class="border-b border-gray-800 bg-opacity-70 backdrop-blur-md sticky top-0 z-50 bg-[#0d0d11]">
        <div class="max-w-6xl mx-auto px-4 py-4 flex justify-between items-center">
            <h1 class="text-xl font-bold tracking-wider text-blue-500 uppercase">MESBAH UDDIN</h1>
            <nav class="space-x-6 text-sm font-medium text-gray-400">
                <a href="#home" class="hover:text-white transition">হোম</a>
                <a href="#documentaries" class="hover:text-white transition">ডকুমেন্টারি</a>
                <a href="#about" class="hover:text-white transition">আমার সম্পর্কে</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="max-w-6xl mx-auto px-4 py-20 text-center relative">
        <div class="absolute inset-0 bg-blue-500/10 blur-[120px] rounded-full max-w-lg mx-auto h-72 -z-10"></div>
        <p class="text-blue-400 text-sm tracking-widest uppercase mb-3">Independent Filmmaker & Creator</p>
        <h2 class="text-4xl md:text-6xl font-extrabold tracking-tight mb-6 bg-gradient-to-r from-white via-gray-300 to-gray-500 bg-clip-text text-transparent">
            ডিজিটাল যুগ ও সত্যের অনুসন্ধান
        </h2>
        <p class="text-gray-400 max-w-2xl mx-auto text-base md:text-lg mb-8 leading-relaxed">
            প্রযুক্তি, সমাজ এবং মানুষের মনস্তত্ত্ব নিয়ে তৈরি আমার ভিজ্যুয়াল ডকুমেন্টারিগুলোর অফিশিয়াল আর্কাইভ। পর্দার পেছনের আসল সত্য উন্মোচন করাই আমার লক্ষ্য।
        </p>
        <a href="#documentaries" class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-semibold px-6 py-3 rounded-lg transition duration-300 glow-effect">
            ভিডিওগুলো দেখুন
        </a>
    </section>

    <!-- Documentary Videos Grid -->
    <section id="documentaries" class="max-w-6xl mx-auto px-4 py-16 border-t border-gray-900">
        <div class="mb-12">
            <h3 class="text-2xl font-bold text-white mb-2">আমার ডকুমেন্টারি সমূহ</h3>
            <p class="text-gray-500 text-sm">নিচের প্লেয়ারে ভিডিওগুলো সরাসরি দেখতে পারবেন।</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            
            <!-- Video Card 1 -->
            <div class="bg-[#13131a] border border-gray-800 rounded-xl overflow-hidden group hover:border-blue-500/50 transition duration-300">
                <div class="aspect-w-16 aspect-h-9 relative">
                    <!-- YouTube Embed (এখানে আপনার নিজের ভিডিওর ID বসাবেন) -->
                    <!-- উদাহরণ হিসেবে একটি ডেমো দেওয়া হলো, src-এর শেষে আপনার ভিডিওর ID দিয়ে দিবেন -->
                    <iframe class="w-full h-64 md:h-72" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Documentary 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
                <div class="p-5">
                    <span class="text-xs font-semibold text-blue-500 tracking-wider uppercase">প্রজেক্ট ০১</span>
                    <h4 class="text-xl font-bold text-white mt-1 mb-2 group-hover:text-blue-400 transition">ডিজিটাল দাসত্ব ও নিউরোলিংক (Digital Slavery & Neuralink)</h4>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        প্রযুক্তির আগ্রাসন কীভাবে আমাদের চিন্তাভাবনাকে নিয়ন্ত্রণ করছে? নিউরাল ইন্টারফেস এবং কৃত্রিম বুদ্ধিমত্তার এই যুগে মানব সভ্যতা কি এক অদৃশ্য দাসত্বের দিকে এগিয়ে যাচ্ছে?
                    </p>
                </div>
            </div>

            <!-- Video Card 2 -->
            <div class="bg-[#13131a] border border-gray-800 rounded-xl overflow-hidden group hover:border-blue-500/50 transition duration-300">
                <div class="aspect-w-16 aspect-h-9 relative">
                    <iframe class="w-full h-64 md:h-72" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Documentary 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
                <div class="p-5">
                    <span class="text-xs font-semibold text-blue-500 tracking-wider uppercase">প্রজেক্ট ০২</span>
                    <h4 class="text-xl font-bold text-white mt-1 mb-2 group-hover:text-blue-400 transition">সাইবারপাঙ্ক রিয়েলিটি এবং গ্লোবাল কন্ট্রোল</h4>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        ভবিষ্যতের সাইবারপাঙ্ক শহরের অবয়ব এবং আধুনিক নজরদারি (surveillance) ব্যবস্থার ওপর একটি গভীর বিশ্লেষণাত্মক তথ্যচিত্র।
                    </p>
                </div>
            </div>

        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="max-w-4xl mx-auto px-4 py-16 border-t border-gray-900 text-center">
        <h3 class="text-2xl font-bold text-white mb-4">মেসবাহ উদ্দিন সম্পর্কে</h3>
        <p class="text-gray-400 leading-relaxed mb-6">
            আমি মেসবাহ উদ্দিন। একজন স্বাধীন কন্টেন্ট ক্রিয়েটর এবং ডকুমেন্টারি মেকার। বিজ্ঞান, ইতিহাস এবং আধুনিক প্রযুক্তির অন্ধকার ও আলো—উভয় দিক নিয়েই আমি ভিজ্যুয়াল সিনেমাটিক গল্প বলতে পছন্দ করি। 
        </p>
        <div class="flex justify-center space-x-6 text-sm text-gray-500">
            <a href="#" class="hover:text-blue-500 transition">ইউটিউব</a>
            <a href="#" class="hover:text-blue-500 transition">ফেসবুক</a>
            <a href="#" class="hover:text-blue-500 transition">ইমেইল</a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-gray-900 py-8 text-center text-xs text-gray-600">
        <p>&copy; 2026 Mesbah Uddin. All Rights Reserved.</p>
    </footer>

</body>
</html>
