# Campus-Connect — প্রথম ওয়েব ডেমো

এটি Campus-Connect-এর প্রাথমিক, স্ট্যাটিক HTML প্রোটোটাইপ। কোডিং না করেও GitHub-এ আপলোড করে Vercel-এ ডেমো প্রকাশের জন্য সাজানো।

## ফাইল
- `index.html` — ওয়েবসাইটের প্রোটোটাইপ

## প্রকাশ করার সহজ পথ

### ১) GitHub-এ অ্যাকাউন্ট
https://github.com/ এ গিয়ে ফ্রি অ্যাকাউন্ট তৈরি/লগইন করুন।

### ২) নতুন repository
- `New repository` ক্লিক করুন
- Repository name: `campus-connect`
- Public বা Private নির্বাচন করুন
- `Create repository` চাপুন

### ৩) ফাইল আপলোড
- `Add file` → `Upload files`
- এই ফোল্ডারের `index.html` ফাইলটি টেনে দিন
- `Commit changes` চাপুন

### ৪) Vercel-এ প্রকাশ
- https://vercel.com/ এ গিয়ে GitHub দিয়ে লগইন করুন
- `Add New` → `Project`
- `campus-connect` repository Import করুন
- সাধারণ HTML সাইটের জন্য Framework Preset `Other`/সনাক্ত হওয়া সেটিংস রেখে Deploy করুন
- Deploy শেষ হলে Vercel একটি ওয়েব ঠিকানা দেবে

## গুরুত্বপূর্ণ সীমাবদ্ধতা
এই সংস্করণটি শুধু ডেমো:
- পোস্ট/ভোট একই ব্রাউজারের local storage-এ থাকে
- অন্য ব্যবহারকারীরা নিজেদের পোস্ট দেখতে পাবে না
- সত্যিকারের অ্যাকাউন্ট, সার্ভার-ভিত্তিক প্রশ্ন/উত্তর, মন্তব্য, রিপোর্টিং, মডারেশন ও নোটিফিকেশন নেই
- নোটিশের উদাহরণগুলো ডেমো; পরীক্ষার তারিখ হিসেবে ব্যবহার করবেন না

পরবর্তী ধাপে Supabase ডেটাবেস, Authentication এবং নিরাপদ access rules যুক্ত করতে হবে। Supabase-এর `service_role` key কখনো ওয়েবসাইটের HTML/JavaScript বা GitHub-এ প্রকাশ করবেন না।
