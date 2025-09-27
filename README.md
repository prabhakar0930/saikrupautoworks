<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saikrupa Auto Works - Complete Auto Solutions</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/vanta@latest/dist/vanta.globe.min.js"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <style>
        .hero-section {
            height: 100vh;
            position: relative;
            overflow: hidden;
        }
        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .floating-car {
            animation: float 6s ease-in-out infinite;
        }
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body class="bg-gray-900 text-white">
    <!-- 3D Background -->
    <div id="vanta-bg" class="hero-section absolute top-0 left-0 w-full h-full"></div>

    <!-- Navigation -->
    <nav class="relative z-10 bg-black bg-opacity-70 backdrop-filter backdrop-blur-lg">
        <div class="container mx-auto px-6 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-4">
                    <img src="https://huggingface.co/spaces/Prabhakar01/saikrupa-auto-works/resolve/main/images/ChatGPT%20Image%20Sep%2019,%202025,%2009_45_00%20PM.png" alt="Logo" class="h-10 w-10">
                    <span class="text-2xl font-bold">Saikrupa <span class="text-yellow-400">Auto Works</span></span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#" class="hover:text-yellow-400 transition">Home</a>
                    <a href="#services" class="hover:text-yellow-400 transition">Services</a>
                    <a href="#about" class="hover:text-yellow-400 transition">About</a>
                    <a href="#contact" class="hover:text-yellow-400 transition">Contact</a>
                </div>
                <button class="md:hidden focus:outline-none">
                    <i data-feather="menu"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero-section flex items-center justify-center relative z-10">
        <div class="container mx-auto px-6 text-center" data-aos="fade-up">
            <h1 class="text-5xl md:text-7xl font-bold mb-6">Your Complete <span class="text-yellow-400">Auto Solution</span></h1>
            <p class="text-xl md:text-2xl mb-10 max-w-3xl mx-auto">Professional vehicle servicing, denting, painting, and sales with 15+ years of trusted expertise</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4 mb-16">
                <a href="#contact" class="bg-yellow-500 hover:bg-yellow-600 text-black font-bold py-3 px-8 rounded-full transition duration-300 transform hover:scale-105">Book Service</a>
                <a href="#services" class="bg-transparent hover:bg-white hover:bg-opacity-10 border-2 border-white text-white font-bold py-3 px-8 rounded-full transition duration-300 transform hover:scale-105">Our Services</a>
            </div>
            <div class="flex justify-center">
                <img src="https://huggingface.co/spaces/Prabhakar01/saikrupa-auto-works/resolve/main/images/gg.jpg" alt="Car" class="floating-car w-64 md:w-80 hovered-element" style="margin-top: 2rem;">
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="pt-10 pb-20 bg-gray-800 relative z-10">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-4xl font-bold mb-4">Our <span class="text-yellow-400">Services</span></h2>
                <p class="text-xl text-gray-300 max-w-2xl mx-auto">Comprehensive auto care solutions tailored to your vehicle's needs</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Service 1 -->
                <div class="service-card bg-gray-900 rounded-xl p-8 transition duration-500" data-aos="fade-up" data-aos-delay="100">
                    <div class="text-yellow-400 mb-4">
                        <i data-feather="settings" class="w-12 h-12"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Complete Servicing</h3>
                    <p class="text-gray-300">Professional maintenance and repair services to keep your vehicle running smoothly.</p>
                </div>
                
                <!-- Service 2 -->
                <div class="service-card bg-gray-900 rounded-xl p-8 transition duration-500" data-aos="fade-up" data-aos-delay="200">
                    <div class="text-yellow-400 mb-4">
                        <i data-feather="tool" class="w-12 h-12"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Denting & Painting</h3>
                    <p class="text-gray-300">Expert dent removal and high-quality painting to restore your vehicle's appearance.</p>
                </div>
                
                <!-- Service 3 -->
                <div class="service-card bg-gray-900 rounded-xl p-8 transition duration-500" data-aos="fade-up" data-aos-delay="300">
                    <div class="text-yellow-400 mb-4">
                        <i data-feather="dollar-sign" class="w-12 h-12"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Vehicle Sales</h3>
                    <p class="text-gray-300">Quality pre-owned vehicles with thorough inspections and competitive pricing.</p>
                </div>
                
                <!-- Service 4 -->
                <div class="service-card bg-gray-900 rounded-xl p-8 transition duration-500" data-aos="fade-up" data-aos-delay="400">
                    <div class="text-yellow-400 mb-4">
                        <i data-feather="shield" class="w-12 h-12"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Custom Solutions</h3>
                    <p class="text-gray-300">Personalized modifications and upgrades to meet your specific requirements.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-900 relative z-10">
        <div class="container mx-auto px-6">
            <div class="flex flex-col lg:flex-row items-center">
                <div class="lg:w-1/2 mb-10 lg:mb-0 lg:pr-10" data-aos="fade-right">
                    <img src="https://huggingface.co/spaces/Prabhakar01/saikrupa-auto-works/resolve/main/images/ChatGPT%20Image%20Sep%2019,%202025,%2009_45_00%20PM.png" alt="Our Garage" class="rounded-xl shadow-2xl hovered-element w-full h-auto">
                </div>
                <div class="lg:w-1/2" data-aos="fade-left">
                    <h2 class="text-4xl font-bold mb-6">About <span class="text-yellow-400">Saikrupa Auto Works</span></h2>
                    <p class="text-lg text-gray-300 mb-6">With over 15 years of experience in the automotive industry, we've built a reputation for excellence in vehicle servicing, repairs, and sales.</p>
                    <p class="text-lg text-gray-300 mb-6">Our team of certified technicians uses state-of-the-art equipment and genuine parts to ensure your vehicle receives the best care possible.</p>
                    <div class="flex items-center space-x-4 mb-6">
                        <i data-feather="check-circle" class="text-yellow-400"></i>
                        <span>15+ years of trusted service</span>
                    </div>
                    <div class="flex items-center space-x-4 mb-6">
                        <i data-feather="check-circle" class="text-yellow-400"></i>
                        <span>Certified technicians</span>
                    </div>
                    <div class="flex items-center space-x-4">
                        <i data-feather="check-circle" class="text-yellow-400"></i>
                        <span>Customer satisfaction guarantee</span>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-800 relative z-10">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16" data-aos="fade-up">
                <h2 class="text-4xl font-bold mb-4">Contact <span class="text-yellow-400">Us</span></h2>
                <p class="text-xl text-gray-300 max-w-2xl mx-auto">Get in touch for inquiries or to schedule a service appointment</p>
            </div>
            
            <div class="flex flex-col lg:flex-row gap-10">
                <div class="lg:w-1/2" data-aos="fade-right">
                    <form class="space-y-6">
                        <div>
                            <label for="name" class="block mb-2 text-sm font-medium">Your Name</label>
                            <input type="text" id="name" class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg focus:ring-yellow-400 focus:border-yellow-400" placeholder="John Doe">
                        </div>
                        <div>
                            <label for="email" class="block mb-2 text-sm font-medium">Your Email</label>
                            <input type="email" id="email" class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg focus:ring-yellow-400 focus:border-yellow-400" placeholder="john@example.com">
                        </div>
                        <div>
                            <label for="phone" class="block mb-2 text-sm font-medium">Phone Number</label>
                            <input type="tel" id="phone" class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg focus:ring-yellow-400 focus:border-yellow-400" placeholder="+91 9876543210">
                        </div>
                        <div>
                            <label for="service" class="block mb-2 text-sm font-medium">Service Needed</label>
                            <select id="service" class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg focus:ring-yellow-400 focus:border-yellow-400">
                                <option selected>Choose a service</option>
                                <option value="servicing">Vehicle Servicing</option>
                                <option value="denting">Denting & Painting</option>
                                <option value="sales">Vehicle Purchase</option>
                                <option value="other">Other</option>
                            </select>
                        </div>
                        <div>
                            <label for="message" class="block mb-2 text-sm font-medium">Your Message</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-3 bg-gray-700 border border-gray-600 rounded-lg focus:ring-yellow-400 focus:border-yellow-400" placeholder="Your message here..."></textarea>
                        </div>
                        <button type="submit" class="w-full bg-yellow-500 hover:bg-yellow-600 text-black font-bold py-3 px-6 rounded-lg transition duration-300">Send Message</button>
                    </form>
                </div>
                
                <div class="lg:w-1/2" data-aos="fade-left">
                    <div class="bg-gray-900 rounded-xl p-8 h-full">
                        <h3 class="text-2xl font-bold mb-6">Our <span class="text-yellow-400">Information</span></h3>
                        
                        <div class="space-y-6">
                            <div class="flex items-start space-x-4">
                                <i data-feather="map-pin" class="text-yellow-400 mt-1"></i>
                                <div>
                                    <h4 class="font-bold">Address</h4>
                                    <p class="text-gray-300">Shivpur Society, ONGC Colony, Vidya Vihar East, Vidyavihar, Mumbai, Maharashtra 400077</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start space-x-4">
                                <i data-feather="phone" class="text-yellow-400 mt-1"></i>
                                <div>
                                    <h4 class="font-bold">Phone</h4>
                                    <p class="text-gray-300">+91 9820167472</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start space-x-4">
                                <i data-feather="mail" class="text-yellow-400 mt-1"></i>
                                <div>
                                    <h4 class="font-bold">Email</h4>
                                    <p class="text-gray-300">saikrupaautoworks01@gmail.com</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start space-x-4">
                                <i data-feather="clock" class="text-yellow-400 mt-1"></i>
                                <div>
                                    <h4 class="font-bold">Working Hours</h4>
                                    <p class="text-gray-300">Tuesday - Sunday: 10:00 AM - 9:00 PM</p>
                                    <p class="text-gray-300">Monday: Closed</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="mt-8">
                            <h4 class="font-bold mb-4">Follow Us</h4>
                            <div class="flex space-x-4">
                                <a href="#" class="bg-gray-700 hover:bg-blue-600 p-3 rounded-full transition">
                                    <i data-feather="facebook"></i>
                                </a>
                                <a href="#" class="bg-gray-700 hover:bg-blue-400 p-3 rounded-full transition">
                                    <i data-feather="twitter"></i>
                                </a>
                                <a href="#" class="bg-gray-700 hover:bg-pink-600 p-3 rounded-full transition">
                                    <i data-feather="instagram"></i>
                                </a>
                                <a href="#" class="bg-gray-700 hover:bg-red-600 p-3 rounded-full transition">
                                    <i data-feather="youtube"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-black py-10 relative z-10">
        <div class="container mx-auto px-6">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-6 md:mb-0">
                    <div class="flex items-center space-x-4">
                        <img src="https://huggingface.co/spaces/Prabhakar01/saikrupa-auto-works/resolve/main/images/ChatGPT%20Image%20Sep%2019,%202025,%2009_45_00%20PM.png" alt="Logo" class="h-10 w-10">
                        <span class="text-2xl font-bold">Saikrupa <span class="text-yellow-400">Auto Works</span></span>
                    </div>
                    <p class="text-gray-400 mt-2">Your trusted partner for all automotive needs</p>
                </div>
                
                <div class="text-gray-400 text-center md:text-right">
                    <p>&copy; 2023 Saikrupa Auto Works. All rights reserved.</p>
                    <p class="mt-1">Designed with <i data-feather="heart" class="inline text-red-500 w-4 h-4"></i> for auto enthusiasts</p>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Initialize Vanta.js 3D background
        VANTA.GLOBE({
            el: "#vanta-bg",
            mouseControls: true,
            touchControls: true,
            gyroControls: false,
            minHeight: 200.00,
            minWidth: 200.00,
            scale: 1.00,
            scaleMobile: 1.00,
            color: 0xffb300,
            backgroundColor: 0x111827,
            size: 0.8
        });

        // Initialize AOS and Feather Icons
        document.addEventListener('DOMContentLoaded', function() {
            AOS.init({
                duration: 800,
                easing: 'ease-in-out',
                once: true
            });
            feather.replace();
        });
    </script>
</body>
</html>
