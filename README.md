# Web Inspector

Static ওয়েব পেজের জন্য একটি সম্পূর্ণ client-side scraper ও inspector টুল — কোনো সার্ভার নেই, সব প্রসেসিং ব্রাউজারেই হয়।

**Live:** https://inspect.mthtamim.bond

## ফিচার

- পুরো HTML সংগ্রহ — Direct, Wayback Machine, proxy ও rendered fallback সহ একাধিক fetch মাধ্যম
- Syntax-highlight সহ সোর্স ভিউ, লাইন নম্বর, Beautify ও সার্চ
- DOM Tree Inspector — প্রতিটি element-এর attribute, parent, children ও outerHTML
- SEO Audit (স্কোরসহ ১২ পয়েন্ট চেকলিস্ট) ও Share Preview কার্ড
- Accessibility ও Security অডিট (আলাদা স্কোরসহ ৮ পয়েন্ট)
- Technology শনাক্তকরণ (WordPress, Next.js, React, jQuery, Bootstrap, Laravel ইত্যাদি)
- লিংক (internal/external), ছবি ও মিডিয়া, টেবিল → CSV extraction
- Email, Phone, Social লিংক ও JSON-LD extraction
- Site Map ক্রল (internal পেজ, সর্বোচ্চ ১০টি) ও দুই পেজের Compare
- Complete Page সেভ — CSS/JS inline করে একটিমাত্র HTML ফাইল
- Batch scrape, সাম্প্রতিক ইতিহাস (localStorage ক্যাশ), Dark/Light থিম, বাংলা/English UI

## ব্যবহার

ব্রাউজারে পেজটি খুলে যেকোনো static পেজের URL দিয়ে Scrape চাপ দিন।

## সীমাবদ্ধতা

লগইন বা JavaScript-নির্ভর পেজে সার্ভারের পাঠানো HTML-ই প্রাথমিকভাবে আনা হয়; তা না পেলে Wayback Machine-এর আর্কাইভ সংস্করণ অথবা রেন্ডার করা কনটেন্ট দেখানো হয়।

---

তৈরি করেছেন **MD Tamim Hasan Akando** · [mthtamim.bond](https://mthtamim.bond)
