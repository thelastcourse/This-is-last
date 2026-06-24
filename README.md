<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>পেমেন্ট করুন - E-Academy</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-800 font-sans py-12 px-4">

    <div class="max-w-md mx-auto bg-white rounded-2xl shadow-xl overflow-hidden border border-gray-100">
        <!-- হেডার -->
        <div class="bg-indigo-600 p-6 text-center text-white">
            <h2 class="text-2xl font-bold">কোর্স এনরোলমেন্ট পেমেন্ট</h2>
            <p class="text-indigo-200 text-sm mt-1">নিচের যেকোনো একটি মাধ্যমে পেমেন্ট সম্পন্ন করুন</p>
        </div>

        <div class="p-6 space-y-6">
            <!-- পেমেন্ট নম্বরসমূহ -->
            <div class="space-y-3">
                <div class="flex justify-between items-center bg-pink-50 p-3 rounded-xl border border-pink-100">
                    <span class="font-bold text-pink-600 text-lg">bKash (Personal)</span>
                    <span class="font-mono font-bold text-gray-700">017XXXXXXXX</span>
                </div>
                <div class="flex justify-between items-center bg-orange-50 p-3 rounded-xl border border-orange-100">
                    <span class="font-bold text-orange-600 text-lg">Nagad (Personal)</span>
                    <span class="font-mono font-bold text-gray-700">019XXXXXXXX</span>
                </div>
            </div>

            <div class="text-sm text-gray-600 bg-gray-50 p-3 rounded-lg border border-gray-200">
                <p class="font-semibold text-gray-800">instruction:</p>
                <ol class="list-decimal list-inside space-y-1 mt-1">
                    <li>উপরের যেকোনো নম্বরে কোর্সের ফি **Send Money** করুন।</li>
                    <li>টাকা পাঠানোর পর নিচের ফরমটি সঠিক তথ্য দিয়ে ফিলাপ করুন।</li>
                </ol>
            </div>

            <!-- পেমেন্ট ফরম (এটি Formspree দিয়ে ফ্রি কানেক্ট করা যাবে) -->
            <form action="https://formspree.io/f/your_form_id" method="POST" class="space-y-4">
                <div>
                    <label class="block text-sm font-semibold text-gray-700 mb-1">আপনার নাম</label>
                    <input type="text" name="name" required class="w-full px-4 py-2.5 rounded-xl border border-gray-300 focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 outline-none transition">
                </div>
                <div>
                    <label class="block text-sm font-semibold text-gray-700 mb-1">আপনার ইমেইল (যেখানে কোর্সের লিংক পাবেন)</label>
                    <input type="email" name="email" required class="w-full px-4 py-2.5 rounded-xl border border-gray-300 focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 outline-none transition">
                </div>
                <div>
                    <label class="block text-sm font-semibold text-gray-700 mb-1">যে নম্বর থেকে টাকা পাঠিয়েছেন</label>
                    <input type="text" name="sender_number" required placeholder="01XXXXXXXXX" class="w-full px-4 py-2.5 rounded-xl border border-gray-300 focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 outline-none transition">
                </div>
                <div>
                    <label class="block text-sm font-semibold text-gray-700 mb-1">Transaction ID (TxID)</label>
                    <input type="text" name="txid" required placeholder="যেমন: K789XJ22" class="w-full px-4 py-2.5 rounded-xl border border-gray-300 focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500 outline-none transition">
                </div>

                <button type="submit" class="w-full bg-indigo-600 text-white font-bold py-3 rounded-xl hover:bg-indigo-700 transition shadow-lg shadow-indigo-200">
                    পেমেন্ট ভেরিফাই করুন
                </button>
            </form>
        </div>
    </div>

</body>
</html>
