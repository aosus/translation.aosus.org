# دليل الأسلوب
!!! warning "الصفحة قيد الإنشاء"

    لا تزال هذه الصفحة قيد الإنشاء. زر الموقع بشكل دوريّ من أجل رؤية آخر التعديلات والتحديثات.
## الصيغ

### المبدِّلات «Switches»
تستخدم المبدِّلات للتحكم في الميزات أو الإعدادات أو الأجهزة التي تحوي على منطق واضح للتشغيل والإيقاف. تشبه المبدِّلات أدوات التحكم في العالم الحقيقي، ويمكن استخدام هذا التشابه كمرجع لتحديد متى ينبغي استخدامها.

تُكتب تسميات المبدِّلات بصيغة المصدر وليس فعل الأمر، فنقول «الحفظ التلقائي» وليس «احفظ تلقائيًا».<sup><a href="https://developer.gnome.org/hig/patterns/controls/switches.html"><small>[م1]</small></a></sup>

| <p style="text-align:center;">اللغة الإنجليزية</p> | <p style="text-align:center;">اللغة العربية (صيغة فعل الأمر) ❌</p> | <p style="text-align:center;">اللغة العربية (صيغة المصدر) ☑️</p> |
|---------------|---------------|---------------|
| ![](/resources/projects/gnome/guidelines/auto-save-switch-1-en-dark.png#only-dark) ![](/resources/projects/gnome/guidelines/auto-save-switch-1-en-light.png#only-light) | ![](/resources/projects/gnome/guidelines/auto-save-switch-2-ar-dark.png#only-dark) ![](/resources/projects/gnome/guidelines/auto-save-switch-2-ar-light.png#only-light) | ![](/resources/projects/gnome/guidelines/auto-save-switch-3-ar-dark.png#only-dark) ![](/resources/projects/gnome/guidelines/auto-save-switch-3-ar-light.png#only-light) |
| <p style="text-align:center;"><span dir="ltr">Auto Save</span></p> | <p style="text-align:center;">احفظ تلقائيًا</p> | <p style="text-align:center;">الحفظ التلقائي</p> |

### الأزرار «Buttons»
الأزرار هي واحدة من أبسط ركائز واجهة المستخدم، ونستخدم صيغة فعل الأمر فيها.<sup><a href="https://developer.gnome.org/hig/patterns/controls/buttons.html"><small>[م2]</small></a></sup>

| <p style="text-align:center;">اللغة الإنجليزية</p> | <p style="text-align:center;">اللغة العربية (صيغة المصدر) ❌</p> | <p style="text-align:center;">اللغة العربية (صيغة فعل الأمر) ☑️</p> |
|---------------|---------------|---------------|
| ![](/resources/projects/gnome/guidelines/save-dialog-1-en-dark.png#only-dark) ![](/resources/projects/gnome/guidelines/save-dialog-1-en-light.png#only-light) | ![](/resources/projects/gnome/guidelines/save-dialog-4-ar-dark.png#only-dark) ![](/resources/projects/gnome/guidelines/save-dialog-4-ar-light.png#only-light) | ![](/resources/projects/gnome/guidelines/save-dialog-3-ar-dark.png#only-dark) ![](/resources/projects/gnome/guidelines/save-dialog-3-ar-light.png#only-light) |
| <p style="text-align:center;"><span dir="ltr">Save/Discard/Cancel</span></p> | <p style="text-align:center;">حفظ\إهمال\إلغاء</p> | <p style="text-align:center;">احفظ\أهمل\ألغِ</p> |


### أشرطة النوافذ
لا نستخدم صيغة الفعل في أشرطة النوافذ.

| <p style="text-align:center;">اللغة العربية (صيغة الفعل) ❌</p> | <p style="text-align:center;">اللغة العربية ☑️</p> |
|---------------|---------------|
| ![](/resources/projects/gnome/guidelines/add-account-1-dark.png#only-dark) ![](/resources/projects/gnome/guidelines//add-account-1-light.png#only-light) | ![](/resources/projects/gnome/guidelines//add-account-2-dark.png#only-dark) ![](/resources/projects/gnome/guidelines//add-account-2-light.png#only-light) |
| <p style="text-align:center;">أضِف حسابًا</p> | <p style="text-align:center;">إضافة حساب</p> |

### أظهر\اعرض
إذا كان أي من هذه الأفعال مع:

* البرمجيات وأجزائها كالقوائم والنوافذ والشريط الجانبي وغيرهم، فنستعمل «أظهر» أو «اطَّلع».
* المحتوى كالصور والمستندات والفيديوهات والعروض التقديمية وغيرهم، فنستعمل «اعرض».

| <p style="text-align:center;">أظهر</p> | <p style="text-align:center;">اعرض</p> |
|---------------|---------------|
| ![](/resources/projects/gnome/guidelines/display-sidebar-dark.png#only-dark) ![](/resources/projects/gnome/guidelines/display-sidebar-light.png#only-light) | ![](/resources/projects/gnome/guidelines/display-video-dark.png#only-dark) ![](/resources/projects/gnome/guidelines/display-video-light.png#only-light) |
| <p style="text-align:center;">أظهر الشريط الجانبي</p> | <p style="text-align:center;">اعرض الفيديو</p> |

### اختصارات لوحة المفاتيح
نكتب الاختصارات بصيغة فعل الأمر.

### نصوص مساعدة الأوامر
نستخدم صيغة فعل الأمر عند طباعة نصوص مساعدة الأوامر، والتي تظهر غالبًا عند إلحاق الأمر بمدخلة ```--help``` في الطرفية.

### مدخلات «gschema»
تَكثُر في تطبيقات جنوم مدخلات تتضمن مُعرِّف «gschema»، وهي مدخلات ذات أهمية ضئيلة، إذ لا تظهر في واجهة المستخدم الرئيسية، وننصح بشدة بتركها وعدم ترجمتها.

يَشيع في توصيف هذه الإعدادات أسلوب كعبارة  «Whether to enable or disable this feature»، والتي تترجم أحيانًا ترجمة حرفية ركيكة إلى صياغات من قبيل: «فيما إذا تُفعَّل أو تُعطَّل هذه الميزة»، وهذا أسلوب خاطئ، فالصواب أن تُصاغ الجملة على هيئة استفهام، فتكون: «أتُفعَّل هذه الميزة أم تُعطَّل؟».<sup><a href="https://archive.ph/ZpotO"><small>[م3]</small></a></sup>

## التاريخ والوقت
يستخدم جنوم دالة ```g_date_time_format``` لتوطين التاريخ والوقت، وهي تعتمد على متغيِّرات تنسيق مستمدة من ```strftime()``` لتحقيق ذلك. ستجد أدناه جدول التحويلات الذي ينبغي استخدامه عند الترجمة إلى اللغة العربية.

تذكر أنه يجب إجراء بعض التعديلات الأخرى، كتغيير مواضع الحقول واستخدام الفاصلة الصحيحة. على سبيل المثال، تُحوَّل الصيغة <span dir="ltr">```%a %b %e, %l:%M:%S %p```</span> إلى <span dir="ltr">```%A، %Oe %Ob، %Ol:%OM:%OS %P```</span> (لاحظ استخدام الفاصلة العربية ،).<sup><a href="https://archive.ph/h7I8Q#selection-125.0-125.4"><small>[م4]</small></a></sup>

| الرمز | مقابله عند الترجمة        | الوصف                                                              | أمثلة |
|-------------|----------------|--------------------------------------------------------------------|----|
| %a          | %A             | اسم يوم الأسبوع                                            | الجمعة
| %A          | %A             | اسم يوم الأسبوع                                             | الجمعة
| %b          | %B             | اسم الشهر                                                  | يناير
| %B          | %B             | اسم الشهر                                                   | يناير
| %c          | %A، %Oe %B %OY %OI:%OM:%OS %P %OZ             | نسق التاريخ والوقت الخاص بالنظام، يختلف تنسيقه حسب الدولة فلا يترجم كوحدة واحدة                                 | السبت،  1 يناير 2000 10:51:56 م +03
| %C          | %OC            | القرن                                                              | 20
| %d          | %Od            | يوم الشهر (01-31)                                                  | 07
| %e          | %Oe            | يوم الشهر (1-31)                                                   | 7
| %F          | %OY-%Om-%Od    | التاريخ، غير قابل للترجمة كوحدة واحدة                              | 2000-12-31
| %g          | %Og            | السنة استنادًا إلى الأسبوع ضمن القرن                                | 05
| %G          | %OG            | السنة استنادًا إلى الأسبوع                                         | 2005
| %h          | %B             | مطابق ل‍ `%b`                                                      | يناير
| %H          | %OH            | الساعة بصيغة 24 ساعة (00-23)                                       | 13
| %I          | %OI            | الساعة بصيغة 12 ساعة (01-12)                                       | 01
| %j          | %Oj            | يوم السنة (001-366)                                             | 074
| %k          | %Ok            | الساعة بصيغة 24 ساعة (0-23)                                        | 13
| %l          | %Ol            | الساعة بصيغة 12 ساعة (1-12)                                        | 1
| %m          | %Om            | الشهر (01-12)                                                      | 06
| %M          | %OM            | الدقيقة (00-59)                                                    | 09
| %p          | %P             | مؤشر «صباحًا» أو «مساءً» المحلي (ص/م)                              | ص
| %P          | %P             | مؤشر «صباحًا» أو «مساءً» المحلي (ص/م)                  | ص
| %r          | %OI:%OM:%OS %P             | الوقت بصيغة 12 ساعة، يختلف تنسيقه حسب الدولة فلا يترجم كوحدة واحدة                                                | 11:02:48 م
| %R          | %OH:%OM        | الوقت بصيغة 24 ساعة، غير قابل للترجمة كوحدة واحدة                  | 18:33
| %s          | %s             | توقيت يونكس، غير قابل للترجمة                                      | 1754337794
| %S          | %OS            | الثواني (00-59)                                                    | 04
| %t          | %t             | محرف الجدولة (Tab)                                                 | ```   ```
| %T          | %OH:%OM:%OS    | الوقت بصيغة 24 ساعة، يختلف تنسيقه حسب الدولة فلا يترجم كوحدة واحدة                                                              | 18:33:45
| %u          | %Ou            | رقم يوم الأسبوع بدءً من الإثنين (1-7)                              | 6
| %V          | %OV            | رقم أسبوع السنة الحالية (01-53)                                    | 43
| %w          | %Ow            | رقم يوم الأسبوع بدءً من الأحد (0-6)                               | 0
| %x          | %Oe %B، %OY             | التاريخ، يختلف تنسيقه حسب الدولة فلا يترجم كوحدة واحدة                                                            |  1 يناير، 2000 
| %X          | %OI:%OM:%OS %p             | الوقت بصيغة 12 ساعة، يختلف تنسيقه حسب الدولة فلا يترجم كوحدة واحدة                                                              | 11:05:42 م
| %y          | %Oy            | السنة دون القرن                                                    | 20
| %Y          | %OY            | السنة                                                              | 2020
| %z          | %z             | فارق التوقيت عن التوقيت العالمي المنسق (UTC)             | +0300
| %Z          | %Z             | اسم المنطقة الزمنية أو اختصارها                                     | +03

تستعمل بعض البرمجيات محرف النسبة «∶» (```U+2236 RATIO```) في التوقيت، ويلزم استبداله بمحرف النقطتين الرأسيتين «:» (```U+003A COLON```) وإلا فسيظهر التوقيت من اليمين إلى اليسار.

## مقترحات لم تخضع للنقاش
!!! warning "تجريبي"

    ما يُعرض في هذا القسم تجريبي، ولم يخضع للنقاش حتى يُعتمد.

### مربع حوار التحذير «Alert Dialog»
تَعرض **مربعات حوار التحذير** رسالة أو سؤالًا مصحوبة بما بين زر واحد وثلاثة أزرار للاستجابة، وتستخدم عندما يكون من الضروري أن يرى المستخدم رسالة ما ويستجيب لها. في مربعات الحوار هذه، المستخدم هو القائم بالفعل وليست البرمجية بذاتها، لذا ينبغي أن تُوجَّه إليه الاستفهاماتُ بصيغة المخاطب: «ستفعلُ كذا؟»، وليس بصيغة المتكلم: «أأفعل كذا؟».<sup><a href="https://bethaitman.com/posts/ui-writing/confirmation/"><small>[م5]</small></a></sup>

| <p style="text-align:center;">اللغة الإنجليزية</p> | <p style="text-align:center;">اللغة العربية (صيغة المتكلم) ❌</p> | <p style="text-align:center;">اللغة العربية (صيغة المخاطب) ☑️</p> |
|---------------|---------------|---------------|
| ![](/resources/projects/gnome/guidelines/save-dialog-1-en-dark.png#only-dark) ![](/resources/projects/gnome/guidelines/save-dialog-1-en-light.png#only-light) | ![](/resources/projects/gnome/guidelines/save-dialog-2-ar-dark.png#only-dark) ![](/resources/projects/gnome/guidelines/save-dialog-2-ar-light.png#only-light) | ![](/resources/projects/gnome/guidelines/save-dialog-3-ar-dark.png#only-dark) ![](/resources/projects/gnome/guidelines/save-dialog-3-ar-light.png#only-light) |
| <p style="text-align:center;"><span dir="ltr">Save Changes?</span></p> | <p style="text-align:center;">أأحفظ التغييرات؟</p> | <p style="text-align:center;">سَتَحفَظُ التغييرات؟</p> |

### أسماء التطبيقات
التطبيقات ذات الأسماء العامة (مثل Files) مُعرَّفة دائمًا غير مُشكَّلة (فنقول «الملفات»)، والأسماء التي لا تترجم تكتب كما تنطق بغير تشكيل (مثل تطبيق Lollypop فنسميه «لولي بوب»).

## جمل الحالة
ويُقصد بها الجمل التي تظهر في البرمجية أثناء إنجاز عمل ما، وقد تُدوول على استخدام صيغة «إنجاز الأمر جارٍ» بين العرب لهذه الجمل. صيغة «المضارعة» أكثر بلاغة لهذه المعارض، وهذا يجعل جملة مثل "Loading..."، تُترجم إلى "تُحمَّل..."، وهي حينها تكون عائدة على البيانات (أي أن «بيانات البرمجية تُحمَّل»).<sup><a href="http://archive.today/2025.09.16-154717/https://web.archive.org/web/20241209130051/https://www.arabeyes.org/%D9%85%D8%B9%D8%A7%D9%8A%D9%8A%D8%B1_%D8%A7%D9%84%D8%AA%D8%B1%D8%AC%D9%85%D8%A9"><small>[م6]</small></a></sup>

## المراجع
<ol>
  <li><a href="https://developer.gnome.org/hig/patterns/controls/switches.html">Switches - GNOME Human Interface Guidelines</a></li>
  <li><a href="https://developer.gnome.org/hig/patterns/controls/buttons.html">Buttons - GNOME Human Interface Guidelines</a></li>
  <li><a href="https://archive.ph/ZpotO">لسان عربي – نزار شهاب الدين</a></li>
  <li><a href="https://archive.ph/h7I8Q#selection-125.0-125.4">Misc Gnome Stuff - Arabeyes Wiki</a></li>
  <li><a href="https://bethaitman.com/posts/ui-writing/confirmation/">Are you sure? How to write a confirmation dialog - Beth Aitman</a></li>
  <li><a href="http://archive.today/2025.09.16-154717/https://web.archive.org/web/20241209130051/https://www.arabeyes.org/%D9%85%D8%B9%D8%A7%D9%8A%D9%8A%D8%B1_%D8%A7%D9%84%D8%AA%D8%B1%D8%AC%D9%85%D8%A9">معايير الترجمة – ويكي عربآيز</a></li>
</ol> 
