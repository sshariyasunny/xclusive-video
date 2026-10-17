# X Exclusive - Landing Page (jharfuknews.in Clone)

এই ওয়েবসাইটটি **https://jharfuknews.in/** এর অনুরুপ এবং আধুনিক ফিচারসহ তৈরি করা হয়েছে। এটি বিশেষ করে **CPA Marketing, Dating Offers, Affiliate SmartLink, এবং WhatsApp Traffic** এর জন্য সর্বোচ্চ কনভার্সন রেট নিশ্চিত করে।

---

## 🚀 প্রধান বৈশিষ্ট্যসমূহ (Features)

1. **মোবাইল অপ্টিমাইজড ডিজাইন (Mobile First Design):**
   - মোবাইল ও ডেস্কটপ উভয়েই পারফেক্ট ও দ্রুত লোড হয়।
2. **ইন-অ্যাপ ব্রাউজার ব্রেকআউট (In-App Browser Breakout):**
   - ফেসবুক, ইনস্টাগ্রাম, মেসেঞ্জার বা টিকটকের ভেতরে লিংক ওপেন হলে এটি স্বয়ংক্রিয়ভাবে ব্যবহারকারীকে অ্যান্ড্রয়েডের **Google Chrome** ব্রাউজারে নিয়ে যায়, যার ফলে কনভার্সন অনেক বৃদ্ধি পায়।
3. **লাইভ অনলাইন ইউজার কাউন্টার (Live Online Counter):**
   - লাইভ সবুজ ডট সহ ব্যবহারকারীর সংখ্যা বাস্তবসম্মতভাবে উঠানামা করে (যেমন: 058 Online -> 063 Online)।
4. **সহজ কনফিগারেশন (Easy Configuration):**
   - কোডের শুরুতে থাকা `APP_CONFIG` অবজেক্ট থেকে সহজেই আপনার অফার লিংক পরিবর্তন করতে পারবেন।

---

## 🛠️ কীভাবে আপনার লিংক বসাবেন (How to Add Your Direct / Affiliate Link)

[index.html](file:///d:/x%20markating/x%20website/index.html) ফাইলটি খুলুন এবং `APP_CONFIG` সেকশনে গিয়ে `smartLink` এর ঘরে আপনার লিংকটি বসিয়ে দিন:

```javascript
const APP_CONFIG = {
    // 👉 আপনার সেট করা স্মার্ট / এফিলিয়েট লিংক:
    smartLink: "https://stubbleestrange.com/xqa8y7khw?key=862fceb6fa97be62cc90785bc25bbf13",
    
    // ওয়েবসাইটের নাম (Site Title):
    siteTitle: "X Exclusive",

    // লোগো URL:
    siteLogo: "https://majedarnews.com/Images/caf7f799a632c271da23787f_card.webp",

    // ফেসবুক/ইনস্টাগ্রাম ইন-অ্যাপ ব্রাউজার ব্রেকআউট (১ = চালু, ০ = বন্ধ):
    enableBreakout: "1",

    // গুগল অ্যানালিটিক্স আইডি (প্রয়োজন না হলে ফাঁকা রাখুন):
    gaId: "",

    // বাটনের লেখা:
    waButtonText: "WhatsApp"
};
```

---

## 🌐 কীভাবে ওয়েবসাইটটি লাইভ/হোস্টিং করবেন (How to Deploy for Free)

আপনি এই ফাইলটি যেকোনো জায়গায় বিনামূল্যে হোস্ট করতে পারেন:

1. **Cloudflare Pages / Netlify / Vercel:**
   - ড্র্যাগ অ্যান্ড ড্রপ করে সরাসরি আপলোড করুন। সম্পূর্ণ ফ্রি এবং সুপার ফাস্ট CDN পাবেন।
2. **cPanel বা যেকোনো হোস্টিং:**
   - আপনার হোস্টিং এর `public_html` ফোল্ডারে `index.html` আপলোড করে দিন।
3. **GitHub Pages:**
   - গিটহাবে পুশ করে Settings -> Pages থেকে সরাসরি ফ্রি ডোমেইনে রান করতে পারেন।
