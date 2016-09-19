# PA-Wine-Shippers
Making interesting things with the PA direct wine shippers data


### Did you know that as of August 8th, 2016 you can now [get wine shipped straight to your doorstep in Pennsylvania](http://www.lcb.state.pa.us/PLCB/Licensees/DirectShipping/index.htm)?

Wineries register for a license with the state for a small fee, and then they're all set! 
It is a little tough to find out who can direct ship wine, though, as you can see from this [10-at-a-time unsearchable listing that gets updated as new licensees are added](http://www.lcbapps.lcb.state.pa.us/webapp/Retail/Direct_Shippers_list.asp).

Currently we are able to pull the data out of that website whenever we would like, and offer it in multiple useful data formats (JSON, XML, CSV).

So let's jam on this data set and make the data more useful!
Use whatever tools you'd like to build something interesting and together we will get it online to share with fellow wine drinking Pennsylvanians.

### What I have done to the source data so far:
- Scraped the PA Liquor Control Board website and provided the data in JSON, XML, and CSV formats
- Created website URLs based on filtered email addresses
- Parsed out City, State, and Zip into separate fields
- Removed Zip4 if present

### Things you could do with the data:
- Make a nice web page listing wineries by region (Napa Valley, Sonoma County, Finger Lakes, Willamette Valley, etc.)
- Map the data, showing where the currently licensed to ship wineries are
- Make the wineries searchable in various manners
- Type in your favorite wine name, see if you can get it shipped to your door
- Add each winery's wines, varietals, logos, etc.
- Merge more data into the dataset - infinite possibilities here

