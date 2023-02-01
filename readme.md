body, table { font-family: Verdana, Arial, Georgia, Times New Roman, Times, serif; font-size: 10pt } .index-letter-section { background-color: #EEEEEE; border: 1px dotted #999999; padding: .5em; margin-bottom: 1em} 

Read Me
-------

Version Change:  
\-------------------------------------------------------------------------------------  
Currect Version: 1.5  
Update Date: 11/03/2010

Change Log:  
After last week's "curmb" patch, this is the latest addition to the class.  
  
This time another service Yahoo! Calendar has been added to the list. Users can enter their  
Yahoo! account detail to login and fetch their Yahoo! Calendar (CSV for Outlook) in an array format.  

Purpose:  
\-------------------------------------------------------------------------------------  
This class is used to grab Yahoo! Address Book, Messenger List, Number of Unread Mails in the Inbox and Yahoo! Calendar.  
With the Yahoo! Account's username and password, the class uses cURL support to authenticate user on Yahoo! and  
create an array list of service choosen by the user.

Services that the class support at the moment are:  
1\. Address Book  
2\. Messenger List  
3\. Number of Unread Mails  
4\. Calendar

If you are running script on localhost and you require proxy server to browse set the isUsingProxy  
variable to true and specify proxy host name port number.

This class is designed in such way that it does not keep any track of cookie set for user when logged  
in to Yahoo! account and generated array of either Address Book or Messenger List.

The test file test.php has the options set for users to view. class.GrabYahoo.php has list of Public  
Variables that you can set.

To view the demo please visit [http://resource.bdwebwork.com/GrabYahoo/](http://resource.bdwebwork.com/GrabYahoo/)

Requirement:  
\-------------------------------------------------------------------------------------  
PHP : 4.4.1 +  
cURL : libcurl/7.14.0 OpenSSL/0.9.8a zlib/1.2.3

About Author:  
\-------------------------------------------------------------------------------------  
I am a Software Engineer with passion to make anything possible with PHP and contribute as much  
possible to Open Source world. I have recently got addicted to developing applications, classes,  
scripts that can be used by anyone. I do not have any intension of making money through my efforts. I  
will be more than happy if any of my effort is useful to at least one person and serves the intented  
purpose.

Please feel free to contact me if you have any question or suggestion for this class. Hopefully you  
will rate my work and inspire me to go ahead with my work.

Ehsan Haque  
Homepage & Blog: [http://ehsan.bdwebwork.com](http://ehsan.bdwebwork.com)

Email: [http://ehsan.bdwebwork.com/contact](http://ehsan.bdwebwork.com/contact)

Moderator - PHP Resource  
[http://groups.yahoo.com/group/phpresource/](http://groups.yahoo.com/group/phpresource/)