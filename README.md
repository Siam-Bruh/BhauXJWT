# 🔐 BhauXJWT - Free Fire UID to JWT Tool

**BhauXJWT** একটি Python টুলস যেটা Free Fire এর `.dat` ফাইল থেকে UID এবং Password বের করে JSON ফরম্যাটে সংরক্ষণ করে, এবং তারপর ওই JSON ফাইল ব্যবহার করে JWT Token তৈরি করে।

---

## ⚙️ ফিচার

- ✅ `.dat` ফাইল থেকে UID & Password সংগ্রহ করে JSON ফাইল তৈরি করা
- ✅ UID & Password থেকে JWT Token তৈরি
- ✅ একাধিক UID সাপোর্ট করে (Bulk Mode)
- ✅ Termux/PC উভয়েই চলে

---

## 🧠 টুলের কাজের ধরন

1. `.dat` ফাইল থেকে UID এবং Password গুলো এক্সট্রাক্ট করে।
2. এগুলোকে `uid.json` ফাইল আকারে সংরক্ষণ করে।
3. তারপর `uid.json` ফাইল থেকে API ব্যবহার করে JWT token তৈরি করে আউটপুট দেয়।

---

## 🚀 কিভাবে ব্যবহার করবেন

### এক এক করে সব কয়টা রান দিন:

```bash
git clone https://github.com/Siam-Bruh/BhauXJWT.git
cd BhauXJWT

```
python SiamXJwt_enc.py
