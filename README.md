
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قهوجي وصبابين الباحة الطائف - خدمات القهوة العربية الأصيلة</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Amiri:wght@400;700&family=Cairo:wght@300;400;600;700&display=swap" rel="stylesheet">
    
    <style>
        body {
            font-family: 'Cairo', sans-serif;
            background: linear-gradient(135deg, #f7f3e9 0%, #fff8e1 100%);
        }
        
        .hero-gradient {
            background: linear-gradient(135deg, #8B4513 0%, #CD853F 50%, #D2691E 100%);
        }
        
        .coffee-pattern {
            background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23D2691E' fill-opacity='0.1'%3E%3Ccircle cx='30' cy='30' r='4'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
        }
        
        .gallery-container {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
            padding: 20px;
        }
        
        .gallery-item {
            flex: 0 0 auto;
            width: 280px;
            height: 200px;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(139, 69, 19, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .gallery-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(139, 69, 19, 0.4);
        }
        
        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        .whatsapp-btn {
            position: fixed;
            bottom: 30px;
            left: 30px;
            background: #25D366;
            color: white;
            border-radius: 50px;
            padding: 15px 20px;
            box-shadow: 0 8px 25px rgba(37, 211, 102, 0.4);
            transition: all 0.3s ease;
            z-index: 1000;
            animation: pulse 2s infinite;
        }
        
        .whatsapp-btn:hover {
            background: #20b358;
            transform: scale(1.1);
        }
        
        @keyframes pulse {
            0%, 100% { box-shadow: 0 8px 25px rgba(37, 211, 102, 0.4); }
            50% { box-shadow: 0 8px 40px rgba(37, 211, 102, 0.7); }
        }
        
        .testimonial {
            background: linear-gradient(45deg, #fff 0%, #f9f7f3 100%);
            border-right: 5px solid #CD853F;
            position: relative;
        }
        
        .testimonial::before {
            content: '"';
            position: absolute;
            top: -10px;
            right: 20px;
            font-size: 60px;
            color: #CD853F;
            opacity: 0.3;
            font-family: 'Amiri', serif;
        }
        
        .service-card {
            background: linear-gradient(135deg, #fff 0%, #f8f6f0 100%);
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }
        
        .service-card:hover {
            border-color: #CD853F;
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(139, 69, 19, 0.2);
        }
        
        .decorative-border {
            border-top: 3px solid #CD853F;
            background: linear-gradient(90deg, transparent 0%, #CD853F 50%, transparent 100%);
            height: 3px;
            margin: 40px auto;
            width: 150px;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header class="hero-gradient text-white py-12 text-center coffee-pattern">
        <div class="container mx-auto px-4">
            <h1 class="text-5xl font-bold mb-4" style="font-family: 'Amiri', serif;">قهوجي وصبابين الباحة الطائف</h1>
            <p class="text-xl mb-6">خدمات القهوة العربية الأصيلة والضيافة الراقية</p>
            <div class="flex justify-center items-center space-x-reverse space-x-4 text-lg">
                <div class="flex items-center">
                    <i class="fas fa-map-marker-alt ml-2"></i>
                    <span>الباحة • الطائف • المملكة العربية السعودية</span>
                </div>
            </div>
        </div>
    </header>

    <div class="container mx-auto px-4 py-12 max-w-6xl">
        
        <!-- About Section -->
        <section class="mb-16">
            <h2 class="text-4xl font-bold text-center mb-8 text-amber-800" style="font-family: 'Amiri', serif;">من نحن</h2>
            <div class="decorative-border"></div>
            
            <div class="bg-white rounded-2xl shadow-xl p-8 border-2 border-amber-100">
                <p class="text-lg leading-relaxed mb-6 text-gray-700">
                    مرحباً بكم في <strong class="text-amber-700">قهوجي وصبابين الباحة الطائف</strong>، الوجهة الأولى لعشاق الضيافة العربية الأصيلة وفن إعداد وتقديم القهوة. تم إنشاء منصتنا لسد الفجوة بين التراث العربي الغني والأناقة الحديثة من خلال تقديم خدمات قهوة احترافية تضمن تجربة ضيافة فريدة.
                </p>
                
                <p class="text-lg leading-relaxed mb-6 text-gray-700">
                    في <strong class="text-amber-700">قهوجي وصبابين الباحة الطائف</strong>، نؤمن بأن القهوة أكثر من مجرد مشروب — إنها رمز للكرم والأصالة والتواصل الإنساني. لهذا نحن ملتزمون بتقديم خدماتنا بأعلى معايير الجودة والحرفية، مع الاهتمام بأدق التفاصيل التي تعكس القيم العربية الحقيقية.
                </p>
                
                <p class="text-lg leading-relaxed mb-6 text-gray-700">
                    نقدم قهوة عالية الجودة محضرة بطرق فريدة، مقدمة بأسلوب يمزج بين التقاليد والإبداع. سواء كان الأمر يتعلق بتجمع عائلي أو اجتماع تجاري أو فعالية كبيرة — نحن نسعى لتلبية جميع احتياجاتكم وجعل مناسبتكم لا تُنسى.
                </p>
                
                <p class="text-lg leading-relaxed mb-6 text-gray-700">
                    رؤيتنا هي إحياء التراث العربي ورفع مكانة القهوة العربية كرمز للضيافة الراقية. نهدف إلى تقديم خدمات مصممة خصيصاً لكل مناسبة مع تجاوز توقعات عملائنا.
                </p>
                
                <p class="text-lg leading-relaxed text-gray-700 font-semibold text-center bg-amber-50 p-4 rounded-lg">
                    شكراً لكم لاختياركم <strong class="text-amber-700">قهوجي وصبابين الباحة الطائف</strong>. نتشرف بأن نكون شركاءكم في صنع لحظات جميلة من الضيافة العربية ونتطلع لخدمتكم بتميز وتفوق.
                </p>
            </div>
        </section>

        <!-- Services Section -->
        <section class="mb-16">
            <h2 class="text-4xl font-bold text-center mb-8 text-amber-800" style="font-family: 'Amiri', serif;">خدماتنا المتميزة</h2>
            <div class="decorative-border"></div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="service-card p-6 rounded-xl shadow-lg">
                    <div class="text-center mb-4">
                        <i class="fas fa-home text-4xl text-amber-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center text-amber-800">المناسبات العائلية</h3>
                    <p class="text-gray-600 text-center">خدمة القهوة العربية الأصيلة للمناسبات العائلية والتجمعات المنزلية بأسلوب تراثي راقي</p>
                </div>
                
                <div class="service-card p-6 rounded-xl shadow-lg">
                    <div class="text-center mb-4">
                        <i class="fas fa-briefcase text-4xl text-amber-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center text-amber-800">الاجتماعات التجارية</h3>
                    <p class="text-gray-600 text-center">تقديم القهوة العربية الفاخرة في الاجتماعات والمؤتمرات التجارية لإضفاء طابع مهني مميز</p>
                </div>
                
                <div class="service-card p-6 rounded-xl shadow-lg">
                    <div class="text-center mb-4">
                        <i class="fas fa-calendar-alt text-4xl text-amber-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center text-amber-800">الفعاليات الكبيرة</h3>
                    <p class="text-gray-600 text-center">خدمة المؤتمرات والفعاليات الكبيرة بفريق محترف وأدوات عالية الجودة</p>
                </div>
                
                <div class="service-card p-6 rounded-xl shadow-lg">
                    <div class="text-center mb-4">
                        <i class="fas fa-crown text-4xl text-amber-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center text-amber-800">الضيافة الفاخرة</h3>
                    <p class="text-gray-600 text-center">تجربة ضيافة استثنائية بأرقى أنواع القهوة العربية المحضرة بعناية فائقة</p>
                </div>
                
                <div class="service-card p-6 rounded-xl shadow-lg">
                    <div class="text-center mb-4">
                        <i class="fas fa-coffee text-4xl text-amber-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center text-amber-800">القهوة التراثية</h3>
                    <p class="text-gray-600 text-center">تحضير القهوة العربية الأصيلة بالطرق التراثية العريقة مع لمسة عصرية</p>
                </div>
                
                <div class="service-card p-6 rounded-xl shadow-lg">
                    <div class="text-center mb-4">
                        <i class="fas fa-users text-4xl text-amber-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3 text-center text-amber-800">الخدمة الشخصية</h3>
                    <p class="text-gray-600 text-center">فريق مدرب من الصبابين المحترفين لتقديم خدمة شخصية متميزة</p>
                </div>
            </div>
        </section>

        <!-- Gallery Section -->
        <section class="mb-16">
            <h2 class="text-4xl font-bold text-center mb-8 text-amber-800" style="font-family: 'Amiri', serif;">معرض الصور</h2>
            <div class="decorative-border"></div>
            
            <div class="gallery-container">
                <div class="gallery-item">
                    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj4uSLixYxuuKZ0BMnJF8M1dEfDl-5aSM1BQmBFNKqw1QTOBXXVwq3HrymeQ5n6SLTy6SpRrxyQPkYD-EH7LBM4lS94zCY4NMN4tINxCh2fAG-ELPUyUxobUMAm1brqa0NjY_z2_hHpzYOSzE4nKEkIagr6jvqvqwQEmZ7WUBogHUfFUy6sHejwUlnvn_d6/s1600/IMG-20250619-WA0033.jpg" alt="خدمة القهوة العربية الأصيلة">
                </div>
                <div class="gallery-item">
                    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgTqIN86Q5Qf7HL8MKU5AhSIADfERrzu2-pEIVeAI0Rf9sywXFL39dhWrvppcfZX6GkfrmYOt45munbWyD1zDzOkZnyp1_4yFY4cHMcadky6Xvt1IpuAN02Y5bjPIUH_kV4MFzC7L6ObNho8xViVyRv2bnvNNXl3SUBCCIQ506cSsmA6KysheJDIX-w9Sx4/s1280/IMG-20250619-WA0029.jpg" alt="تحضير القهوة التراثية">
                </div>
                <div class="gallery-item">
                    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjig4Citk_WSoxmsw-3O5V4xLk0hpJdZGOS5vgJaVs4vYMMQgTvU89JmuDxnIVKyRlcw35S8LD3blPPWmYQoaY9SqrEmWnojpfwPQTe1yRJXDV_2zDPKdAdTZxY6zt85rZxQ_ZaCQu46Jx3Jabr63VSOAYSXsHGz7D12phnhxzMvpChZS_SSZq0-wqggwSk/s3840/IMG-20250619-WA0032.jpg" alt="الضيافة العربية الراقية">
                </div>
                <div class="gallery-item">
                    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhi98Y5ZVoPMXdwMpaXgvbHEqrKmcEzq_6KS8opi6-oc6uqlyOuMhPX2-Lc24z1m1LH2SQKy0nKNsUJ-pjVQ2JJQ3Xhr3xJyXXBWt8LQ756dUV7PzZo02m_-Jgb0fu4YgrZtInp-C4ee1s3F359DN99ByJQe_YtpOiHfpyStS66_F4rXBXW2pSnoOrMVCHM/s1600/IMG-20250619-WA0030.jpg" alt="فريق الصبابين المحترف">
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section class="mb-16">
            <h2 class="text-4xl font-bold text-center mb-8 text-amber-800" style="font-family: 'Amiri', serif;">آراء عملائنا الكرام</h2>
            <div class="decorative-border"></div>
            
            <div class="grid md:grid-cols-2 gap-8">
                <div class="testimonial p-6 rounded-xl shadow-lg">
                    <p class="text-gray-700 mb-4 leading-relaxed">"خدمة رائعة ومتميزة، القهوة لذيذة جداً والصبابين محترفين. أضافوا لمسة تراثية جميلة لحفل زواج ابني. أنصح الجميع بالتعامل معهم."</p>
                    <div class="flex items-center">
                        <div class="bg-amber-100 rounded-full w-12 h-12 flex items-center justify-center ml-4">
                            <i class="fas fa-user text-amber-600"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-amber-800">محمد العتيبي</h4>
                            <p class="text-sm text-gray-500">الطائف</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial p-6 rounded-xl shadow-lg">
                    <p class="text-gray-700 mb-4 leading-relaxed">"تعاملت معهم في مؤتمر شركتنا والنتيجة كانت أكثر من رائعة. الضيافة العربية الأصيلة أعطت انطباع مميز لضيوفنا الأجانب. شكراً لكم."</p>
                    <div class="flex items-center">
                        <div class="bg-amber-100 rounded-full w-12 h-12 flex items-center justify-center ml-4">
                            <i class="fas fa-user text-amber-600"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-amber-800">عبدالله الغامدي</h4>
                            <p class="text-sm text-gray-500">الباحة</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial p-6 rounded-xl shadow-lg">
                    <p class="text-gray-700 mb-4 leading-relaxed">"الصراحة خدمة من الآخر! القهوة طعمها أصيل والتقديم راقي جداً. استخدمت خدمتهم في عزيمة كبيرة وكل الضيوف أعجبوا بالطعم والأسلوب."</p>
                    <div class="flex items-center">
                        <div class="bg-amber-100 rounded-full w-12 h-12 flex items-center justify-center ml-4">
                            <i class="fas fa-user text-amber-600"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-amber-800">سالم الزهراني</h4>
                            <p class="text-sm text-gray-500">الطائف</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial p-6 rounded-xl shadow-lg">
                    <p class="text-gray-700 mb-4 leading-relaxed">"فريق محترف وملتزم بالمواعيد، والأهم من هذا كله أن القهوة لذيذة ومحضرة بطريقة تراثية صحيحة. جربتهم في أكثر من مناسبة وما خذلوني أبداً."</p>
                    <div class="flex items-center">
                        <div class="bg-amber-100 rounded-full w-12 h-12 flex items-center justify-center ml-4">
                            <i class="fas fa-user text-amber-600"></i>
                        </div>
                        <div>
                            <h4 class="font-bold text-amber-800">فهد القحطاني</h4>
                            <p class="text-sm text-gray-500">الباحة</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section class="mb-12">
            <h2 class="text-4xl font-bold text-center mb-8 text-amber-800" style="font-family: 'Amiri', serif;">تواصل معنا</h2>
            <div class="decorative-border"></div>
            
            <div class="bg-white rounded-2xl shadow-xl p-8 text-center">
                <div class="grid md:grid-cols-2 gap-8 items-center">
                    <div>
                        <h3 class="text-2xl font-bold mb-6 text-amber-800">نحن في خدمتكم</h3>
                        <p class="text-gray-600 mb-6 leading-relaxed">
                            تواصلوا معنا لحجز خدماتنا أو للاستفسار عن أي من خدمات القهوة العربية والضيافة التراثية. فريقنا جاهز لخدمتكم في أي وقت.
                        </p>
                        
                        <div class="space-y-4">
                            <div class="flex items-center justify-center">
                                <i class="fas fa-map-marker-alt text-amber-600 text-xl ml-3"></i>
                                <span class="text-lg">الباحة، الطائف، المملكة العربية السعودية</span>
                            </div>
                            
                            <div class="flex items-center justify-center">
                                <i class="fas fa-phone text-amber-600 text-xl ml-3"></i>
                                <a href="tel:+966507712688" class="text-lg hover:text-amber-600 transition-colors">+966507712688</a>
                            </div>
                            
                            <div class="flex items-center justify-center">
                                <i class="fab fa-whatsapp text-green-600 text-xl ml-3"></i>
                                <a href="https://wa.me/966507712688" class="text-lg hover:text-green-600 transition-colors">واتساب: +966507712688</a>
                            </div>
                        </div>
                    </div>
                    
                    <div class="text-center">
                        <div class="bg-gradient-to-br from-amber-100 to-amber-50 p-8 rounded-xl">
                            <i class="fas fa-coffee text-6xl text-amber-600 mb-4"></i>
                            <h4 class="text-xl font-bold text-amber-800 mb-2">اتصل الآن</h4>
                            <p class="text-gray-600 mb-4">واحجز موعدك لتجربة أفضل خدمات القهوة العربية</p>
                            <a href="tel:+966507712688" class="bg-amber-600 text-white px-6 py-3 rounded-full hover:bg-amber-700 transition-colors inline-flex items-center">
                                <i class="fas fa-phone ml-2"></i>
                                اتصل الآن
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <!-- WhatsApp Button -->
    <a href="https://wa.me/966507712688" class="whatsapp-btn no-print" target="_blank">
        <i class="fab fa-whatsapp text-2xl ml-2"></i>
        <span class="font-semibold">واتساب</span>
    </a>

    <!-- Footer -->
    <footer class="hero-gradient text-white py-8 text-center coffee-pattern">
        <div class="container mx-auto px-4">
            <h3 class="text-2xl font-bold mb-2" style="font-family: 'Amiri', serif;">قهوجي وصبابين الباحة الطائف</h3>
            <p class="text-lg mb-4">خدمات القهوة العربية الأصيلة والضيافة التراثية</p>
            <p class="text-sm opacity-75">جميع الحقوق محفوظة © 2024</p>
        </div>
    </footer>
</body>
</html>
