# pdf-flipbook
Dynamic pdf flipbook where u can set the pdf's path in parameter ?file. <br>
<hr>
For example:
?file=pdf_filename.pdf
or
?file=https://path_of_online_pdf

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
<iframe style="width: 100%; height: 700px;" src="https://mazizsahari.github.io/pdf-flipbook/?file=pdf_filename.pdf" frameborder="0" scrolling="no" seamless="seamless" allowfullscreen="allowfullscreen"></iframe>
```
Remember to set the pdf_filename.pdf based on your pdf file's location. <br>
You can also set the width and height or other attributes to suit your needs.
