# pdf-flipbook
Dynamic pdf flipbook where u can set the pdf's path in parameter ?file. <br>
<hr>
For example: <br>
If u are using it offline, just download this project in ZIP file. <br>
Then, unzip it and put it in your xampp's htdocs folder, let's called it: pdf-flipbook-main. <br>
You can now put your pdf files in that same folder: pdf-flipbook-main. <br>
To use this pdf-filebook, just open the project and set ?file=your_pdf_filename_or_location.pdf on the url. <br>
You can also test it offline by just putting ?file=test.pdf on the url <br>
<br>
If u are using it online, just set the online path of the pdf in the file parameter. <br>
For example: <br>
?file=https://path_of_online_pdf <br>

DEMO:
https://mazizsahari.github.io/pdf-flipbook/?file=https://mozilla.github.io/pdf.js/web/compressed.tracemonkey-pldi-09.pdf


When you use it for your website and there's an error of "CROSS ORIGIN!! Cannot access file!", <br>
you need to enable cross origin on your website. <br>
To do that, just update or create .htaccess in your project folder with the code below: <br>
```
<IfModule mod_headers.c>
Header set Access-Control-Allow-Origin: *
</IfModule>
```

If there's no more CROSS Origin error and you want to embed it in your website, just use the code below: <br>
```
<iframe style="width: 100%; height: 700px;" src="https://mazizsahari.github.io/pdf-flipbook/?file=https://path_of_online_pdf" frameborder="0" scrolling="no" seamless="seamless" allowfullscreen="allowfullscreen"></iframe>
```
Remember to set the pdf_filename.pdf based on your pdf file's location. <br>
You can also set the width and height or other attributes to suit your needs.
