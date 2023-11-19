# Bangla C Language

## সিনট্যাক্স 
```
# অন্তর্ভুক্ত < স্ট্যান্ডার্ড_ইন_আউট.হেডার >
পূর্ণ মৌলিক()
{
   দেখাও ("ওহে বিশ্ব");
   ফেরত ০;
}
```
## ইনপুট ও আউটপুট
```

# অন্তর্ভুক্ত < স্ট্যান্ডার্ড_ইন_আউট.হেডার >
পূর্ণ মৌলিক()
{
   পূর্ণ নাম্বার;
   দেখাও ("একটি পূর্ণসংখ্যা নাও");
   নাও("%প", &নাম্বার);
   দেখাও("%প", নাম্বার);
   ফেরত ০;
}
```
## ডেটা টাইপ ও চলক
```
পূর্ণ = পূর্ণসংখ্যা
দশম = দশমিক
বর্ণ  = অক্ষর
ডাবল = বড় দশমিক
বর্ণ চলক[] = বাক্য
```
```
পূর্ণ আইডি = ১৯১১৭;
দশম সিজিপিএ = ৪.৮১;
বর্ণ বর্ণমালা = 'অ';
ডাবল হিসাব = ১২৩৪৫৬.৭৮৯০;
বর্ণ বাক্য[২০] = "মোঃ আনিছুর রহমান";
```
## শর্ত
```
যদি (৫<৬)
{
  দেখাও("৫ এর চেয়ে ৬ বড়");
}
নাহলে যদি(৫==৫)
{
  দেখাও("দুটি নাম্বারই সমান");
}
নাহলে
{
  দেখাও("৫ বড়");
}
```
## লুপ
```
ফর (ক=১; ক<=১০; ক++)
{
  দেখাও("হাতের লেখার সুন্দর করব");
}
```
```
ক = ১;
যতক্ষণ (ক <১০)
{ 
  দেখাও("আমি কাজে করে যাব");
  ক++;
}
