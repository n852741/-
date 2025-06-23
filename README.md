<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قهوجي وصبابين الطائف الباحة - خدمات القهوة العربية الأصيلة</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Amiri:wght@400;700&family=Cairo:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Cairo', sans-serif;
            background: linear-gradient(135deg, #f7f3f0 0%, #e8ddd4 100%);
        }
        .hero-bg {
            background: linear-gradient(135deg, #8B4513 0%, #D2691E 50%, #CD853F 100%);
        }
        .card-shadow {
            box-shadow: 0 10px 25px rgba(139, 69, 19, 0.1);
        }
        .text-coffee {
            color: #8B4513;
        }
        .bg-coffee {
            background-color: #8B4513;
        }
        .bg-coffee-light {
            background-color: #D2691E;
        }
        .border-coffee {
            border-color: #8B4513;
        }
        .hover-lift:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        .amiri {
            font-family: 'Amiri', serif;
        }
        .whatsapp-btn {
            position: fixed;
            bottom: 20px;
            left: 20px;
            z-index: 1000;
            background: #25D366;
            color: white;
            border-radius: 50px;
            padding: 15px 20px;
            box-shadow: 0 4px 15px rgba(37, 211, 102, 0.4);
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        .image-gallery {
            display: flex;
            gap: 15px;
            overflow-x: auto;
            padding: 20px 0;
            scroll-behavior: smooth;
        }
        .gallery-image {
            min-width: 300px;
            height: 200px;
            border-radius: 15px;
            object-fit: cover;
            transition: transform 0.3s ease;
            cursor: pointer;
        }
        .gallery-image:hover {
            transform: scale(1.05);
        }
        .service-card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(139, 69, 19, 0.1);
        }
        @media print {
            .whatsapp-btn { display: none; }
            body { background: white; }
        }
    </style>
</head>
<body class="min-h-screen">
    <!-- زر الواتساب الثابت -->
    <a href="https://wa.me/966507712688" target="_blank" class="whatsapp-btn flex items-center hover-lift">
        <i class="fab fa-whatsapp text-2xl ml-2"></i>
        <span class="font-semibold">تواصل معنا</span>
    </a>

    <!-- القسم الرئيسي -->
    <header class="hero-bg text-white py-16">
        <div class="container mx-auto px-6 text-center">
            <h1 class="text-6xl font-bold amiri mb-4">قهوجي وصبابين الطائف الباحة</h1>
            <p class="text-2xl mb-8 opacity-90">فن الضيافة العربية الأصيلة</p>
            <div class="flex justify-center items-center space-x-4 space-x-reverse text-lg">
                <div class="flex items-center">
                    <i class="fas fa-map-marker-alt ml-2"></i>
                    <span>الباحة - الطائف - المملكة العربية السعودية</span>
                </div>
                <div class="mx-4">|</div>
                <div class="flex items-center">
                    <i class="fas fa-phone ml-2"></i>
                    <span>+966507712688</span>
                </div>
            </div>
        </div>
    </header>

    <!-- معرض الصور الأفقي -->
    <section class="py-12 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-4xl font-bold text-center text-coffee mb-8 amiri">معرض أعمالنا</h2>
            <div class="image-gallery">
                <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj4uSLixYxuuKZ0BMnJF8M1dEfDl-5aSM1BQmBFNKqw1QTOBXXVwq3HrymeQ5n6SLTy6SpRrxyQPkYD-EH7LBM4lS94zCY4NMN4tINxCh2fAG-ELPUyUxobUMAm1brqa0NjY_z2_hHpzYOSzE4nKEkIagr6jvqvqwQEmZ7WUBogHUfFUy6sHejwUlnvn_d6/s1600/IMG-20250619-WA0033.jpg" alt="خدمة القهوة العربية الأصيلة" class="gallery-image card-shadow">
                <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgTqIN86Q5Qf7HL8MKU5AhSIADfERrzu2-pEIVeAI0Rf9sywXFL39dhWrvppcfZX6GkfrmYOt45munbWyD1zDzOkZnyp1_4yFY4cHMcadky6Xvt1IpuAN02Y5bjPIUH_kV4MFzC7L6ObNho8xViVyRv2bnvNNXl3SUBCCIQ506cSsmA6KysheJDIX-w9Sx4/s1280/IMG-20250619-WA0029.jpg" alt="تحضير القهوة بالطريقة التراثية" class="gallery-image card-shadow">
                <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjig4Citk_WSoxmsw-3O5V4xLk0hpJdZGOS5vgJaVs4vYMMQgTvU89JmuDxnIVKyRlcw35S8LD3blPPWmYQoaY9SqrEmWnojpfwPQTe1yRJXDV_2zDPKdAdTZxY6zt85rZxQ_ZaCQu46Jx3Jabr63VSOAYSXsHGz7D12phnhxzMvpChZS_SSZq0-wqggwSk/s3840/IMG-20250619-WA0032.jpg" alt="خدمة احترافية للمناسبات" class="gallery-image card-shadow">
                <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhi98Y5ZVoPMXdwMpaXgvbHEqrKmcEzq_6KS8opi6-oc6uqlyOuMhPX2-Lc24z1m1LH2SQKy0nKNsUJ-pjVQ2JJQ3Xhr3xJyXXBWt8LQ756dUV7PzZo02m_-Jgb0fu4YgrZtInp-C4ee1s3F359DN99ByJQe_YtpOiHfpyStS66_F4rXBXW2pSnoOrMVCHM/s1600/IMG-20250619-WA0030.jpg" alt="تقديم القهوة بأسلوب عربي راقي" class="gallery-image card-shadow">
            </div>
        </div>
    </section>

    <!-- قسم من نحن -->
    <section class="py-16">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto text-center">
                <h2 class="text-5xl font-bold text-coffee mb-8 amiri">من نحن</h2>
                <div class="bg-white rounded-2xl p-8 card-shadow service-card">
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        أهلاً وسهلاً بكم في <strong class="text-coffee">قهوجي وصياب</strong>، الوجهة المميزة لعشاق الضيافة العربية الأصيلة وفن إعداد وتقديم القهوة. تم إنشاء منصتنا لتكون الجسر الذي يربط بين التراث العربي الغني والأناقة الحديثة من خلال تقديم خدمات قهوة احترافية تضمن تجربة ضيافة فريدة ومميزة.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        في <strong class="text-coffee">قهوجي وصياب</strong>، نؤمن بأن القهوة ليست مجرد مشروب، بل هي رمز للكرم والأصالة والتواصل الإنساني. لذلك نحن ملتزمون بتقديم خدماتنا بأعلى معايير الجودة والحرفية، مع الاهتمام بأدق التفاصيل التي تعكس القيم العربية الأصيلة.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed mb-6">
                        نقدم قهوة عالية الجودة معدة بطرق فريدة، ومقدمة بأسلوب يجمع بين التراث والإبداع. سواء كان ذلك في تجمع عائلي، أو اجتماع عمل، أو مناسبة كبيرة، نحن نسعى لتلبية جميع احتياجاتكم وجعل مناسبتكم لا تُنسى.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed">
                        رؤيتنا هي إحياء التراث العربي ورفع مكانة القهوة العربية كرمز للضيافة الراقية. نهدف إلى تقديم خدمات مخصصة لكل مناسبة وتجاوز توقعات عملائنا في كل مرة.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- قسم الخدمات -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-5xl font-bold text-center text-coffee mb-12 amiri">خدماتنا المميزة</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- خدمة المناسبات العائلية -->
                <div class="service-card rounded-2xl p-8 card-shadow hover-lift">
                    <div class="text-center mb-6">
                        <i class="fas fa-home text-5xl text-coffee-light mb-4"></i>
                        <h3 class="text-2xl font-bold text-coffee amiri">المناسبات العائلية</h3>
                    </div>
                    <ul class="text-gray-700 space-y-3">
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>تقديم القهوة العربية الأصيلة في حفلات الزفاف والمناسبات</li>
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>خدمة ضيافة راقية للعزائم والولائم العائلية</li>
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>تقديم الشاي والقهوة بالطريقة التراثية</li>
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>خدمة تقديم محترفة بالزي التراثي</li>
                    </ul>
                </div>

                <!-- خدمة الشركات والمؤسسات -->
                <div class="service-card rounded-2xl p-8 card-shadow hover-lift">
                    <div class="text-center mb-6">
                        <i class="fas fa-building text-5xl text-coffee-light mb-4"></i>
                        <h3 class="text-2xl font-bold text-coffee amiri">الشركات والمؤسسات</h3>
                    </div>
                    <ul class="text-gray-700 space-y-3">
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>خدمة ضيافة للاجتماعات والمؤتمرات</li>
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>تقديم القهوة في المعارض والفعاليات التجارية</li>
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>خدمة يومية للمكاتب والشركات</li>
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>تدريب الموظفين على فن تقديم القهوة</li>
                    </ul>
                </div>

                <!-- خدمة المناسبات الخاصة -->
                <div class="service-card rounded-2xl p-8 card-shadow hover-lift">
                    <div class="text-center mb-6">
                        <i class="fas fa-star text-5xl text-coffee-light mb-4"></i>
                        <h3 class="text-2xl font-bold text-coffee amiri">المناسبات الخاصة</h3>
                    </div>
                    <ul class="text-gray-700 space-y-3">
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>تقديم القهوة في الفنادق والمنتجعات</li>
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>خدمة VIP للشخصيات المهمة</li>
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>المهرجانات والفعاليات الثقافية</li>
                        <li class="flex items-start"><i class="fas fa-check text-coffee ml-2 mt-1"></i>خدمة تقديم حصرية للمناسبات الملكية</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- قسم مميزات الخدمة -->
    <section class="py-16">
        <div class="container mx-auto px-6">
            <h2 class="text-5xl font-bold text-center text-coffee mb-12 amiri">لماذا تختار قهوجي وصبابين الطائف الباحة؟</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="text-center hover-lift">
                    <div class="bg-coffee text-white w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-award text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-coffee mb-2">جودة عالية</h3>
                    <p class="text-gray-600">قهوة عربية أصيلة من أجود أنواع البن</p>
                </div>
                <div class="text-center hover-lift">
                    <div class="bg-coffee text-white w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-users text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-coffee mb-2">فريق محترف</h3>
                    <p class="text-gray-600">مدربون على أعلى معايير الضيافة العربية</p>
                </div>
                <div class="text-center hover-lift">
                    <div class="bg-coffee text-white w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-clock text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-coffee mb-2">خدمة سريعة</h3>
                    <p class="text-gray-600">التزام بالمواعيد واستجابة فورية</p>
                </div>
                <div class="text-center hover-lift">
                    <div class="bg-coffee text-white w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-heart text-3xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-coffee mb-2">ضيافة أصيلة</h3>
                    <p class="text-gray-600">نحافظ على التراث العربي في كل التفاصيل</p>
                </div>
            </div>
        </div>
    </section>

    <!-- قسم الشهادات والتقييمات -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-5xl font-bold text-center text-coffee mb-12 amiri">ما يقوله عملاؤنا</h2>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-gradient-to-br from-coffee to-coffee-light text-white rounded-2xl p-8 card-shadow">
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-300">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                    </div>
                    <p class="text-lg mb-4">"خدمة راقية جداً وقهوة لذيذة. أضافوا لمسة تراثية جميلة لحفل زفاف ابنتي."</p>
                    <p class="font-semibold">- راشد احمد، الرياض</p>
                </div>
                <div class="bg-gradient-to-br from-coffee to-coffee-light text-white rounded-2xl p-8 card-shadow">
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-300">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                    </div>
                    <p class="text-lg mb-4">"مؤسستنا تتعامل معهم دائماً في المؤتمرات. احترافية عالية والتزام بالمواعيد."</p>
                    <p class="font-semibold">- مدير الفعاليات، شركة النخيل</p>
                </div>
                <div class="bg-gradient-to-br from-coffee to-coffee-light text-white rounded-2xl p-8 card-shadow">
                    <div class="flex items-center mb-4">
                        <div class="flex text-yellow-300">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                    </div>
                    <p class="text-lg mb-4">"أفضل خدمة قهوة في المنطقة. الطعم أصيل والتقديم راقي جداً."</p>
                    <p class="font-semibold">- خالد العتيبي، جدة</p>
                </div>
            </div>
        </div>
    </section>

    <!-- قسم الختام والشكر -->
    <section class="py-16">
        <div class="container mx-auto px-6 text-center">
            <div class="max-w-3xl mx-auto bg-white rounded-2xl p-8 card-shadow service-card">
                <h2 class="text-4xl font-bold text-coffee mb-6 amiri">شكراً لاختياركم قهوجي وصبابين الطائف الباحة</h2>
                <p class="text-lg text-gray-700 leading-relaxed mb-6">
                    نحن فخورون بكوننا شركاءكم في صنع لحظات جميلة من الضيافة العربية الأصيلة. نتطلع إلى خدمتكم بكل تميز وإتقان.
                </p>
                <p class="text-xl font-semibold text-coffee amiri">
                    "في قهوجي وصبابين الطائف الباحة... نصنع من كل رشفة قهوة ذكرى لا تُنسى"
                </p>
            </div>
        </div>
    </section>

    <!-- تذييل الصفحة -->
    <footer class="hero-bg text-white py-12">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-3 gap-8 text-center md:text-right">
                <div>
                    <h3 class="text-2xl font-bold amiri mb-4">قهوجي وصبابين الطائف الباحة</h3>
                    <p class="opacity-90">فن الضيافة العربية الأصيلة</p>
                </div>
                <div>
                    <h4 class="text-xl font-semibold mb-4">تواصل معنا</h4>
                    <div class="space-y-2">
                        <p><i class="fas fa-phone ml-2"></i>+966507712688</p>
                        <p><i class="fab fa-whatsapp ml-2"></i>واتساب: +966507712688</p>
                        <p><i class="fas fa-map-marker-alt ml-2"></i>الباحة - الطائف - المملكة العربية السعودية</p>
                    </div>
                </div>
                <div>
                    <h4 class="text-xl font-semibold mb-4">ساعات العمل</h4>
                    <div class="space-y-2 opacity-90">
                        <p>السبت - الخميس</p>
                        <p>من 8:00 صباحاً إلى 10:00 مساءً</p>
                        <p>متاحون 24/7 للطوارئ</p>
                    </div>
                </div>
            </div>
            <div class="border-t border-white border-opacity-20 mt-8 pt-8 text-center">
                <p class="opacity-75">© 2024 قهوجي وصبابين الطائف الباحة- جميع الحقوق محفوظة</p>
            </div>
        </div>
    </footer>

    <script>
        // تأثير تفاعلي للصور
        document.querySelectorAll('.gallery-image').forEach(img => {
            img.addEventListener('click', function() {
                window.open(this.src, '_blank');
            });
        });

        // تأثير تمرير سلس للمعرض
        document.querySelector('.image-gallery').addEventListener('wheel', function(e) {
            e.preventDefault();
            this.scrollLeft += e.deltaY;
        });
    </script>
</body>
</html>
