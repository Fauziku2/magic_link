#URL Shortener

This app is named Magic! Link

##Description

This app offers reliable URL shortening which is very simple very simple to use. Just paste your link in the form on the home page and submit. You will be redirected to a result page with your shortened link.

##Demo

* Going to the console and starting the Rails server, reload http://localhost:3000 in your browser and you should see the following.
<img width="1262" alt="screen shot 2017-01-16 at 3 12 41 pm" src="https://cloud.githubusercontent.com/assets/22285452/21973874/8a8fe330-dbfe-11e6-8b66-b816d43dc8e7.png">

* If you click on Shorten my URL without any URLs entered into the Your URLfield, you will receive the following error page.
<img width="1257" alt="screen shot 2017-01-16 at 3 21 44 pm" src="https://cloud.githubusercontent.com/assets/22285452/21974125/c580c3dc-dbff-11e6-9e91-670e43c70402.png">

* If you enter an invalid URL into the your URL field and click Shorten my URL(for example ww.invalid_URL.com), you’ll see the following image.
<img width="1247" alt="screen shot 2017-01-16 at 3 26 49 pm" src="https://cloud.githubusercontent.com/assets/22285452/21974199/46120ff6-dc00-11e6-981f-4e1a694f6f6f.png">

* If you enter a valid URL into the URL field and click Shorten my URL, the app will generate a new shorten URL as shown in the following image.
<img width="1258" alt="screen shot 2017-01-16 at 3 31 28 pm" src="https://cloud.githubusercontent.com/assets/22285452/21974308/fc1b0c8a-dc00-11e6-860a-bc4d2e3c7c0b.png">

<img width="1266" alt="screen shot 2017-01-16 at 3 31 44 pm" src="https://cloud.githubusercontent.com/assets/22285452/21974395/7d031d06-dc01-11e6-96d5-56c4c8c1c013.png">

##Technology used

This app is built with Rails 5.0.0 and Ruby 2.3.3 on the backend. The database is SQLite3.

##Things to improve

I am still not satisfied with my generated URLs. I would like to generate a real random token. Since most url shorteners appear to be using a 6 characters string made up of digits from 0 to 9 and letters from a to z (both upper and lower case)



