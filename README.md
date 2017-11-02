<p><h1 dir='rtl'>احترف جيت, الإصدار الثاني</h1></p>

<p dir='rtl'>مرحباً بك إلى الإصدار الثاني من كتاب احترف جيت.</p>

<p dir='rtl'>تستطيع إيجاد هذا الكتاب على الأنترنت على الرابط التالي: http://git-scm.com/book</p>

<p dir='rtl'>كما في الإصدار الأول, الإصدار الثاني من هذا الكتاب مفتوح المصدر تحت رخصة المشاع الإبداعي.</p>

<p dir='rtl'>بضعة أمور قد تغيّرت بعد فتح مصدر الإصدار الأول. إحداها, أننا انتقلنا من صيغة Markdown إلى صيغة Asciidoc المذهلة لنصوص هذا الكتاب.</p>

<p dir='rtl'>وقد انتقلنا أيضاً لجعل الترجمات في حاويات مختلفة بدلاً من جعلها في مجلدات فرعية في الحاوية الإنجليزية للكتاب. انظر إلى 
<a href='https://github.com/progit2-ar/progit2/blob/master/CONTRIBUTING.md'>وثيقة المساهمة</a>
للمزيد من المعلومات. </p> 


<p><h2 dir='rtl'>كيف يتم توليد الكتاب</h2></p>

<p dir='rtl'>يمكنك توليد الكتاب الإلكتروني يدوياً باستخدام Asciidoctor. إذا قمت بتنفيذ التالي <i>قد</i> تحصل على ملفات HTML, Eupub, Mpobi, PDF:</p>


```
$ bundle install
$ bundle exec rake book:build
Converting to HTML...
 -- HTML output at progit.html
Converting to EPub...
 -- Epub output at progit.epub
Converting to Mobi (kf8)...
 -- Mobi output at progit.mobi
Converting to PDF...
 -- PDF output at progit.pdf
```

<p dir='rtl'>كحل بديل لاستخدام الأمر <code>bundle</code> يمكنك استدعاء الأمر <code>asciidoctor</code> مباشرةً.</p>

<p dir='rtl'>استخدم الأوامر التالية:</p>

```
$ asciidoctor progit.asc
$ asciidoctor-pdf progit.asc
$ asciidoctor-epub3 progit.asc
$ asciidoctor-epub3 -a ebook-format=kf8 progit.asc
```
<p dir='rtl'>لاستخدام كلاً من مشاريع <code>asciidoctor</code>, <code>asciidoctor-pdf</code> و <code>asciidoctor-epub</code>.</p>


<p><h2 dir='rtl'>فتح مشكلة</h2></p>

<p dir='rtl'>قبل فتح مشكلة, رجاءً تأكد أنه لا يوجد مشكلة مشابهة بالفعل في نظام تعقب العلل.</p>

<p dir='rtl'>أيضاً, إذا تم رصد المشكلة على موقع <a href='https://git-scm.com'>git-scm.com</a>, رجاءً تأكد إن كانت المشكلة مازالت موجودة في هذا المستودع. هذه المشكلة قد تكون صححت بالفعل, ولكن التغييرات لم يتم نشرها بعد.</p>


<p><h2 dir='rtl'>المساهمة</h2></p>

<p dir='rtl'>إذا كنت تريد المساعدة بالقيام بتغييرات أو المساهمة بالترجمة, خذ نظرة على
<a href='https://github.com/progit2-ar/progit2/blob/master/CONTRIBUTING.md'>وثيقة المساهمة</a>.</p>
