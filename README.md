# Assignment Questions

### 1. Difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
- `getElementById` → একটি নির্দিষ্ট id দিয়ে element খুঁজে আনে।  
- `getElementsByClassName` → একাধিক element (HTMLCollection) রিটার্ন করে যাদের একই class থাকে।  
- `querySelector` → CSS selector ব্যবহার করে প্রথম matching element আনে।  
- `querySelectorAll` → সব matching elements আনে (NodeList)।  

---

### 2. How do you create and insert a new element into the DOM?
- `document.createElement("div")` দিয়ে নতুন element বানানো হয়।  
- তারপর `appendChild()` বা `insertBefore()` দিয়ে DOM এ ঢোকানো হয়।  

---

### 3. What is Event Bubbling and how does it work?
- Event bubbling মানে child element এ event ঘটলে সেটা parent → ancestor পর্যন্ত propagate হয়।  

---

### 4. What is Event Delegation in JavaScript? Why is it useful?
- Event delegation মানে parent element এ event listener বসানো হয়, আর child elements এ event হলে সেটা parent এ catch করা হয়।  
- এটা useful কারণ অনেক child এ আলাদা আলাদা listener বসাতে হয় না।  

---

### 5. Difference between preventDefault() and stopPropagation()?
- `preventDefault()` → default behavior বন্ধ করে (যেমন form submit হওয়া)।  
- `stopPropagation()` → event আর parent এ propagate হয় না।  
