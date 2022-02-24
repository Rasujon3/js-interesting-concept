ইন্টারভিউ প্রশ্ন
এই মডিউল এ আমরা কয়েকটা জিনিস দেখবো। সেখান থেকে কয়েকটা জিনিস ইন্টারভিউতে প্রায়ই জিজ্ঞেস করে বসে। 
১. জাভাস্ক্রিপ্ট কী কী ডাটা টাইপের ভেরিয়েবল আছে? – 2:primitive,non-primitive
২. জাভাস্ক্রিপ্ট ফাংশন, বা array কি টাইপের জিনিস ? 
৩. জাভাস্ক্রিপ্ট এ array যদি অবজেক্ট হয় তাহলে কিভাবে চেক করবে কোন একটা ভেরিয়েবল একটা array নাকি array না?
৪. এর মধ্যে undefined আর null এর মধ্যে ডিফারেন্স কি। 
৫. double equal (==) আর triple equal (===) এই দুইটার মধ্যে ডিফারেন্স কি। 
৬. বা implicit conversion কি জিনিস একটা কখন হয়। 
৭. এছাড়াও জাভাস্ক্রিপ্ট এ কয়েক ধরনের স্কোপ আছে। এই স্কোপ গুলার মধ্যে ডিফারেন্স কি। কখন কোনটা হয়। 
৮. ব্লক স্কোপ কি জিনিস? let, const কি টাইপের স্কোপ তৈরি করে?
৯. (এডভান্সড) Closure কি জিনিস? এইটা কিভাবে কাজ করে?
১০. Callback function কি জিনিস?
১১. (এডভান্সড) Hoisting কি জিনিস? (গুগলে সার্চ দিয়ে আরো ভালো করে শিখো )
১২. (এডভান্সড) কি ধরণের ভেরিয়েবল reference দিয়ে ফাংশনে পাঠানো হয় আর কোন ধরণের ভেরিয়েবল value হিসেবে পাঠানো হয়।
----------------------------------------------ANSWER--------------------------------------------------
1.	js dynamic typed variable language = Js er dan pase ki iota dekhe bujhte hobe variable er type ki
2.	. জাভাস্ক্রিপ্ট কী কী ডাটা টাইপের ভেরিয়েবল আছে? – 2:primitive,non-primitive(array,object)
Non-primitive=era reference dhore rakhe




3.
i. Falsy: 
false
0
empty string
undefined
null
NaN
-------------------
ii. Truthy:
true
any number (positive or negative )
any string including single whitespace, '0', 'false'
[]
{}
anything else that is not falsy will be truthy
3.	Null = mane value nai && undefined = kono karone define kora hoy nai
*Undefined*
1. variable value not assigned ; 2. function but didn't write return 
3. just wrote return but didn't return anything ; 4. parameter that isn't passed
5. property that doesn't exist in an object ; 6. accessing array element out of range
7. accessing deleted array element ; 8. explicitly set value to undefined

4.	double equal (==) vs triple equal (===), implicit conversion
5.	i. function er vitore je variable toiri hoy,take local scope bole.
ii. global k local e use krte parbo bt local k global e parbo na
iii. block scope = if,switch,conditions or while loops er vitor area(second bracket) take block scope bole
note: var diye declare korle block scope hoy na,tokhon functional scope e chole jay
iv. Hoisting = hoisting declarations guloke top e niye jay.
v. Global Leaking = function er vitore var,let,const diye variable declare na krle seta leak hoye jay & oi variable k jekono jaygay pauya jay,etai global leaking.
**let & const block er moddhe thakbe,edr hoisting kora hobe na**
6.	Closure = Jodi kono ekta function er vitor abr ekta function call koro or Jodi kono ekta function er vitor abr ekta function return koro, je function  k return krtecho se Jodi outside er kono variable k access kore,taile tar nijoscho ekta environment(encapsulation) / ekta closure toiri kore/ private variable toiri kore 
7.	Callback = kono ekta function k call krar somoy parameter hisebe ekta function k pathaw,takei callback function bole.
