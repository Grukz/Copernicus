#Copernicus


Osint tool to get results from Google, Bing, Yahoo, PagesBlanches about people.

No Smeging Api key required.
Will not get your ip banned.

Get images from google

Filter results to be sure to retreive what we looking for .
 (including pdf)

If strict search result failed for one site try another finding method.

Then make a graph in neo4j .

~(Consider downloading [Linkification](https://addons.mozilla.org/fr/firefox/addon/linkification/)  for Firefox or [Clickable links](https://chrome.google.com/webstore/detail/clickable-links/mgamelhnfokapndfdodnmfiningckjia) for Chrome if you want to use neo4j as it is .)~




![](http://img11.hostingpics.net/pics/703817copernicus.png) 

 - usage: copernicus.py [-h] [-e 'ENGINE'] [-i  'True/False']  [-l 'LANG'] [-pb 'True/False'] [-s 'NAME'] [-f
   FAMILY NAME] [-a OPTION] [-c CITY] [-fa TRUE-FALSE]

>./copernicus.py -e google,yahoo,pagesblanches -s "Someone you looking for" -f "looking for" -c paris -a lot,of,words,to,add,here,in,relation,with,the,people,you,search,if,you,want,more,results,"dont forget to quote space",doh  -pb true -i true
   
###To do list:
- Rewrite all this shit
- Add Install setup 
-   Add whitepage engine for uk,es,ru,usa...(only fr now)
-  Add ability to save current session and continue where it stopped in  case of uncaught error.
-  Add graphml , gephi , cytoscape ,export format .
-  Add image search for yahoo and bing
- Add Email search
- Add Search results function for other file format 
- Add Search by language in Bing
- Add some search engines .
- ~~Add FullAuto mode for PagesBlanches (testings all cities with more than 10 000 inhabitants )~~

*Wrote this cause of the maltego community limitation (12 results only)*
