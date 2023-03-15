# pdf-flipbook
Dynamic pdf flipbook where you can set the pdf's path in parameter ?file. <br>
<hr>
For example: <br>
If you are using it offline, just download this project in ZIP file. <br>
Then, unzip it and put it in any folder, let's called it: pdf-flipbook-main. <br>
You can now put your pdf files in that same folder <br>
To use this pdf-filebook: <br>
1. If you have not installed node.js, run the installer in installer > run_installer.bat. Skip this step if you have installed it. <br>
2. Run the system by clicking on the run.bat <br>
3. It will give you a url to open the system. Usually it is http://127.0.0.1:8080 or http://127.0.0.1:8081. <br>
4. Copy the url and paste it in any browser, such as Chrome or Mozilla Firefox <br>
5. You can change which pdf file you want to view by append the url with '?file=your_pdf_filename_or_location.pdf' <br>
6. For example, let's say your pdf name is called: my_storybook.pdf. To view it, the url should be http://127.0.0.1:8080?file=my_storybook.pdf <br>
<br>
If u are using it online, just set the online path of the pdf in the file parameter. <br>
For example: <br>
?file=https://path_of_online_pdf <br>

DEMO:
https://mazizsahari.github.io/pdf-flipbook?file=https://mozilla.github.io/pdf.js/web/compressed.tracemonkey-pldi-09.pdf


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
You can also set the width and height or other attributes to suit your needs.
