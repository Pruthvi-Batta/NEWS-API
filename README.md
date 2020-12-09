# NEWS-API
It is a project on how to create custom NEWS search using a keyword
In This Commercial World, There Are A Lot Of Newspaper Publishers And Websites Available. There Are A Myriad Number Of Articles About A Wide Variety Of Topics. What If You Can Search All The Articles Yourself Just By Entering A Keyword And Can Design Them Too. Doesn’t It Sound Interesting!! In This Article, Let’s Discuss How To Create A NEWS Search Based On Keywords Using Open-Source NEWS API And Python.

What Is An Open-Source API??
Open-Source API/Public API (Application Programming Interface) Is An Open Public Accessible API, Which Provides The Interface Between The Program And The Application.

An Open-Source NEWS API Is A URL Which On Requested Gives Required Data In JSON Format Containing The Following-

Status Of Request
Total Results Available
Array Of Articles
{

“Status”: “Ok”,

“TotalResults”: 38,

“Articles”: []

}

And Each Element Of The Array(Articles) Is Again A JSON Format Which Contains

Source (JSON Format With Contents ID And NULL)
Title
Author
Description
URL
URL To Image
Published At
Content
{

“Source”: {

“Id”: “ID“,

“Name”: “NAME”

}

“Author”: “Xxxxxxxxxx”,

“Title”: “How To Use NEWS API?”,

“Description”: “NEWS API Is An Open-Source API Service That Can Be Used By Anybody”,

“Url”: “Https://Newsapi.Org/”,

“UrlToImage”: “Https://Newsapi.Org/”,

“PublishedAt”: “2020-11-20T09:20:19Z”,

“Content”: “Xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx”

}

This Open-Source API Is Developed And Maintained By The NEWS API

How To Generate NEWS API?
Firstly, Open The  NEWS API.
Then Click On The GET API KEY.
Now Provide The Mentioned Details For Creating An Account With The NEWS API.
First Name
E-MAIL
Password
Choose Whether You Are An Individual Or A Group
Confirm You Are Not A Robot
Agree To Their Terms
After Signing In You Will Have 5 Types Of API Available.
All Articles Based On Key-Word Of Recent Month Sorted By Recently Published.
Top Business Headlines In The U.S Right Now.
All Articles Mentioning A Key-Word Sorted By Popular Publisher.
Top Articles From TechCrunch At Present.
All Articles Published By Wall Street Journal In The Last 6 Months.

After Signing In, You Will Have The Link Shown In The Image Above With The API. Access Your API Key In The Profile Section.
So The API Is Generated Successfully.
In This Article, We Will Discuss The First Type Of API, And How To Get All The URLs Of NEWS Related To The Keyword Provided.
