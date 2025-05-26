
# Bonus Section
#### 1. What is PostgreSQL?
PostgreSQL হলো একটি শক্তিশালী ওপেন সোর্স রিলেশনাল ডেটাবেজ ম্যানেজমেন্ট সিস্টেম।


#### 3. Explain the Primary Key and Foreign Key concepts in PostgreSQL.
Primary Key হলো টেবিলের একটি কলাম বা কলামের সমষ্টি যা প্রতিটি রেকর্ডকে ইউনিকভাবে শনাক্ত করে। একটি টেবিলে একটি মাত্র Primary Key থাকে।
Foreign Key হলো এমন একটি কলাম যা অন্য টেবিলের Primary Key এর সাথে সম্পর্কিত থাকে। এটি টেবিলগুলোর মধ্যে রিলেশন তৈরি করে এবং ডেটার ইন্টিগ্রিটি বজায় রাখে। 

#### 4. What is the difference between the VARCHAR and CHAR data types?
* CHAR: নির্দিষ্ট দৈর্ঘ্যের ফিক্সড সাইজ স্ট্রিং।
* VARCHAR: পরিবর্তনশীল দৈর্ঘ্যের স্ট্রিং, জায়গা সাশ্রয়ী।

#### 6. What are the LIMIT and OFFSET clauses used for?
LIMIT নির্ধারণ করে কতগুলো রেকর্ড ফলাফল হিসেবে দেখা যাবে।
যেমন LIMIT 10 মানে প্রথম ১০টি রেকর্ড দেখাবে।

OFFSET নির্ধারণ করে কতগুলো রেকর্ড স্কিপ করে পরবর্তী রেকর্ড দেখাবে।
যেমন OFFSET 5 মানে প্রথম ৫টি বাদ দিয়ে শুরু হবে।
Pagination বা পেজভিত্তিক ডেটা দেখানোর জন্য LIMIT ও OFFSET একসাথে ব্যবহৃত হয়।

#### 10. How can you calculate aggregate functions like COUNT(), SUM(), and AVG() in PostgreSQL?

PostgreSQL-এ COUNT(), SUM(), AVG() ফাংশনগুলো ডেটা অ্যাগ্রিগেট করতে ব্যবহৃত হয়।

* COUNT(): সারি বা null নয় এমন এন্ট্রি গণনা করে। COUNT(*) সব সারি, COUNT(column) null ছাড়া এন্ট্রি গোনে।
* SUM(): সাংখ্যিক কলামের মোট যোগফল বের করে।
* AVG(): সাংখ্যিক কলামের গড় মান নির্ণয় করে।
