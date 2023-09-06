<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cookies & Home Juice Subscription</title>
    <!-- Include Tailwind CSS CDN -->
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.15/dist/tailwind.min.css" rel="stylesheet">
    <!-- Add your custom CSS if necessary -->
</head>
<body class="bg-gray-100 font-sans">

<!-- Navigation Bar -->
<nav class="bg-green-500 p-4">
    <div class="container mx-auto">
        <div class="flex justify-between items-center">
            <div class="text-white text-2xl font-bold">Cookies & Home</div>
            <ul class="flex space-x-6 text-white">
                <li><a href="#" class="hover:underline">Home</a></li>
                <li><a href="#" class="hover:underline">Products</a></li>
                <li><a href="#" class="hover:underline">Pricing</a></li>
                <li><a href="#" class="hover:underline">Contact</a></li>
            </ul>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<section class="bg-green-200 py-20">
    <div class="container mx-auto text-center">
        <h1 class="text-4xl font-bold text-green-800">Enjoy Fresh Packed Juices on Subscription</h1>
        <p class="mt-4 text-lg text-green-700">Delicious, healthy, and convenient juice delivered to your doorstep.</p>
        <a href="#" class="mt-8 inline-block px-6 py-3 bg-green-500 text-white rounded-full hover:bg-green-600">Get Started</a>
    </div>
</section>

<!-- Features Section -->
<section class="py-16">
    <div class="container mx-auto text-center">
        <h2 class="text-3xl font-bold text-gray-800">Why Choose Cookies & Home?</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-12">
            <!-- Feature 1 -->
            <div class="p-6 bg-white rounded-lg shadow-lg">
                <h3 class="text-xl font-semibold text-gray-800">Fresh Ingredients</h3>
                <p class="mt-4 text-gray-600">We use only the freshest and finest ingredients in our juices.</p>
            </div>
            <!-- Feature 2 -->
            <div class="p-6 bg-white rounded-lg shadow-lg">
                <h3 class="text-xl font-semibold text-gray-800">Subscription Plans</h3>
                <p class="mt-4 text-gray-600">Flexible subscription plans to fit your lifestyle.</p>
            </div>
            <!-- Feature 3 -->
            <div class="p-6 bg-white rounded-lg shadow-lg">
                <h3 class="text-xl font-semibold text-gray-800">Convenient Delivery</h3>
                <p class="mt-4 text-gray-600">We deliver your favorite juices right to your doorstep.</p>
            </div>
        </div>
    </div>
  
</section>

<!-- Subscription Section -->
<section class="bg-green-500 py-16 text-white">
    <div class="container mx-auto text-center">
        <h2 class="text-3xl font-bold">Subscribe Now and Stay Refreshed</h2>
        <p class="mt-4 text-lg">Choose a subscription plan that suits you and enjoy the goodness of fresh juice every day.</p>
        <a href="#" class="mt-8 inline-block px-6 py-3 bg-white text-green-500 rounded-full hover:bg-white hover:text-green-500 border border-green-500">Subscribe</a>
    </div>
</section>

<!-- Footer Section -->
<footer class="bg-gray-800 py-8 text-white">
    <div class="container mx-auto text-center">
        <p>&copy; 2023 Cookies & Home. All rights reserved.</p>
    </div>
</footer>
<!-- ... (previous sections) -->

<!-- Payment Section -->
<section class="bg-gray-100 py-16">
    <div class="container mx-auto">
        <div class="max-w-md mx-auto bg-white p-8 rounded-lg shadow-lg">
            <h2 class="text-2xl font-semibold mb-6">Payment Information</h2>

            <!-- Payment Form -->
            <form>
                <!-- Card Number -->
                <div class="mb-4">
                    <label for="cardNumber" class="block text-gray-700 font-medium">Card Number</label>
                    <input type="text" id="cardNumber" name="cardNumber" class="form-input">
                </div>

                <!-- Expiry Date and CVV -->
                <div class="grid grid-cols-2 gap-4">
                    <div class="mb-4">
                        <label for="expiryDate" class="block text-gray-700 font-medium">Expiry Date</label>
                        <input type="text" id="expiryDate" name="expiryDate" class="form-input">
                    </div>
                    <div class="mb-4">
                        <label for="cvv" class="block text-gray-700 font-medium">CVV</label>
                        <input type="text" id="cvv" name="cvv" class="form-input">
                    </div>
                </div>

                <!-- Name on Card -->
                <div class="mb-4">
                    <label for="cardName" class="block text-gray-700 font-medium">Name on Card</label>
                    <input type="text" id="cardName" name="cardName" class="form-input">
                </div>

                <!-- Billing Address -->
                <div class="mb-4">
                    <label for="billingAddress" class="block text-gray-700 font-medium">Billing Address</label>
                    <textarea id="billingAddress" name="billingAddress" class="form-textarea"></textarea>
                </div>

                <!-- Submit Button -->
                <div class="mt-8">
                    <button type="submit" class="bg-green-500 text-white py-2 px-4 rounded-full hover:bg-green-600">Submit Payment</button>
                </div>
            </form>
        </div>
    </div>
</section>

<!-- ... (remaining sections) -->

</body>
</html>
