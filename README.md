سكربت الدفاع عن الشبكة 

متطلبات التشغيل : كالي لينكس أو  اوبونتو (يحتاج بعض التعديلات في السكربت) 

  السكربت يغطي : 

تحديث النظام وتثبيت ادوات الدفاع 

snort  أداة 
 لمراقبة حركة الشبكة والكشف عن التسللات

iptables إنشاء قواعد 
للتحكم بالوصول الى الشبكة 

ACL إعداد قوائم 
للسماح او الحظر  بناء على الشبكات الفرعية 

UFW تفعيل جدار الحماية 
وقواعد التحكم بالوصول 

تطبيق سياسات جدار الحماية حسب الشبكات المسموح بها والمحظورة 

اختبار الاتصال بخام سحابي للتأكد من الاتصال بالإنترنت 

تشفير ملف بيانات حساسة
 GPG بستخدام  
 بتشفير قوي

فحص النظام بحثا عن المنافذ المفتوحة
Nmap  بستخدام اداة 

التقاط حركة المرور على الشبكة لمدة محددة
topdump باستخدام  

ssh محاكاة هجوم على منفذ 
 snort لمراقبة التنبيهات بستخدام





Network Defense Script 

Prerequisites: Kali Linux or Ubuntu (needs some modifications in the script) 

The script covers : 

System update and install defense tools 

Snort tool to monitor network traffic and detect intrusions

Create iptables rules to control network access 

Set up ACLs to allow or block based on subnets 

Turn on UFW firewall and access control rules 

Apply firewall policies by allowed and blocked networks 

Test your connection to a cloud raw to make sure you are connected to the internet 

Encrypt sensitive data file with GPG with strong encryption

Scan the system for open ports using the Nmap tool 

Capture network traffic for a specified duration using topdump 

Simulate an attack on the SSH port to monitor alerts using SNORT








   كيفية تشغيل السكربت :

انسخ الكود الموجود في هذا الملف

افتح الترمنل في كالي لينكس

ادخل الى محرر النصوص بستخدام
nano او vi

الصق الكود

ctrl+o احفظ الملف بستخدام
ثم
Enter سمي الملف واضغط
ctrl+x للخروج

شغل السكربت بستخدام
bash (اسم الملف )





How to run the script :

Copy the code in this file

Open the terminal in Kali Linux

Access the text editor using
nano or vi

Paste the code

CTRL+O Save the file with
then
Enter name the file and press
Ctrl+x to exit

Run the script using
bash (file name)
