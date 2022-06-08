# IOT-blocks
في هذا الوحدة سنتعرف على : 
- تأسيس أنظمة انترنت الاشياء 
- بنية النظام 
- المشغلات والحساسات 





عرض وتأسيس أنظمة IOT أو أنترنت الاشيآء. 


في البداية ماذا نلاحظ من الصور التاليه : 


مقدمة 


![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641648040755_++--++...png)


هي تمنع الصفحة من الظهور وهي erro 505 و 404 راح نلاحظ هنا http النسخه غير مدعومة،و http يعرف بأنه بروتوكول. 


- بنية النظام 
- 

ماهو System Architecture؟ 

- System components 

1- Sensors/Devices
المستشعرات 
أولاً ، تساعد المستشعرات أو الأجهزة في جمع بيانات دقيقة جدًا من البيئة المحيطة.
2-Connectivity
بعد ذلك ، يتم إرسال تلك البيانات التي تم جمعها إلى البنية التحتية السحابية ولكنها تحتاج إلى وسيط للنقل.
3-Data Processing
بمجرد جمع البيانات ووصولها إلى السحابة ، يقوم البرنامج بمعالجة البيانات التي تم الحصول عليها.

![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641649632334_++--++...png)


4-User Interface

بعد ذلك ، يتم توفير المعلومات للمستخدم النهائي بطريقة ما. يمكن تحقيق ذلك عن طريق إطلاق الإنذارات على هواتفهم أو الإخطار من خلال الرسائل النصية أو رسائل البريد الإلكتروني.



- Functional organization.


![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641650536334_++--++...png)

- Operational principles and procedures 

1-Obsess over customer experiences
2-Create seamless experiences across platforms and channels
3-Pursue continuous improvements
4-Data isn't enough, do the math

راح يجي في بالنا سؤال مهم بعدما تم شرح طبقات network 

![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641648812604_++--++...png)

- هل عملية tcp فيها أمان ؟ 
- هل متطلبات IOT هي نفسها اللي يحققها model ؟

ماذا IOT يحتاج Network Architecture جديدة ؟

في البداية IT System و IotSystem  راح نتعرف على ماهو IT System : هو يدعم business application.
ماهو IoT System نقل بيانات كثيرة من أجهزة مختلفة - تحليلها - جمعها.
لماذا نحتاجه ؟ 
١- قابلية التوسع 
٢- الامان 
٣- حجم كبير من البيانات المستشعرات )السيارات ذاتية القيادة(.
٤- الاجهزة القديمة )بدون IP( . ٥- تحليل البيانات في لحظتها )Real time data analysis 

لماذا IOT يحتاج Network Architecture جديدة ؟ 


![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641651176206_++--++...png)


العمليات على البيانات قد تتم في احد هذه الاماكن :

١- الجهاز نفسة 
٢- سحابة 
٣- Fog


![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641651282812_++--++...png)


بعض الاشياء المهمه في تصميم نموذج IOT

١- المستشعرات.
٢- طريقة الاتصال.
٣- تبادل البيانات.






الاشياء الذكية | Smart Objects

كائنات مادية تحتوي على مضمنة التكنولوجيا للاستشعار والتفاعل مع بيئتهم في طريقة ذات مغزى من خلال الترابط والتمكين التواصل فيما بينهم.     

المستشعرات 


![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641651690398_++--++...png)


الاختلاف بين المستشعرات 


- المدى 
- المسافة : درجة الحرارة ، درجةالحساسية
- نسبة الخطأ

أنواع مختلفة من المستشعرات 


![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641651954235_++--++...png)


ملخص 


![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641652019255_++--++...png)



مشغل | actuator

- هو عكس المستشعر .


![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641652111351_++--++...png)


أنواع actuator 


![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641652196441_++--++...png)


المحكمات الدقيقة MCU 

١- وحدة معالجة مركزية
 ٢- ذاكرة 
 ٣- منافذ input , output
 

![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641652299714_++--++...png)


الحواسيب أحادية اللوحة SBC 

كومبيوتر صغير . 

سير العملية 


![](https://paper-attachments.dropbox.com/s_6F348AC67C0FECF596E6E1CB71AE139BE7EAE5F35281837A29764FC5438B94A2_1641652380755_++--++...png)



ماهي IOT Applications ؟ 

Home Automation 
- Healthcare 
- Monitoring Assets 
