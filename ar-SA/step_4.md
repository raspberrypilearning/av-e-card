## إضافة الصوت

--- task ---

انقر فوق علامة تبويب **الأصوات** للكائنات.

![الصورة تظهر علامات تبويب الأصوات المحددة للكائنات](images/sounds-tab.png)

---/task--

--- task ---

في الزاوية السفلية اليمنى من الشاشة، مرر مؤشر الماوس فوق زر **اختيار صوت** واختر **تسجيل** لتسجيل صوت جديد.

![الصورة تظهر زر الأصوات مع تحديد تسجيل](images/record-sound.png)

--- /task ---

--- task ---

قد تحتاج لسماح متصفح الويب الخاص بك للوصول إلى الميكروفون. للقيام بذلك، انقر فوق **سماح**.

![الصورة تظهر مطالبة متصفح الويب لتفعيل الوصول إلى الميكروفون](images/allow-mic.png)

--- /task ---

--- task ---

انقر فوق زر **تسجل** لتسجيل بضع ثوان من صوتك. عند الإنتهاء من رسالتك الصوتية لمستلم بطاقتك الإلكترونية، انقر فوق **إيقاف التسجيل**، ثم انقر فوق**حفظ**.

![الصورة تظهر مربع حوار تسجيل الصوت داخل Scratch](images/record.png)

--- /task ---

--- task ---

لتشغيل الصوت، يمكنك استخدام كتلة `بث `{:class="block3control"} عندما تبدأ حلقة الرسوم المتحركة.

```blocks3
when flag clicked
switch costume to (ezgif v)
set size to (150) %
forever
+broadcast (message1 v)
repeat (35)
next costume
```

--- /task ---

--- task ---

ثم استخدم كتلة `عندما أتلقى `{:class="block3control"} لبدء تشغيل الصوت.

```blocks3
when I receive (message1 v)
play sound (recording1 v) until done
```

--- /task ---

--- task ---

قد ترغب في استخدام كتلة `انتظر `{:class="block3control"} للتحكم في وقت بدء تشغيل الصوت.

```blocks3
when I receive (message1 v)
+wait (0.4) seconds
play sound (recording1 v) until done
```

--- /task ---



