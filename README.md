![enter image description here](https://github.com/justfornbn/NBN-Ajax-page-loading-JQuery/blob/master/NBNAJAXPAGELOADER.jpg?raw=true) 
## NBN Ajax Page Loader and Progressive

## Setup

Add Script File Into Project

    <script src="nbnAjaxPageLoader.min.js"></script>
	  
## Usage

Basic  : 

	<div id="content"></div>
    <script>
	    $('#content').nbnAjaxPageLoader({
		    loadingImg : 'images/loading.gif' //gif or svg
		});
	</script>

Custom Style : 

	<div id="content"></div>
    <script>
	    $('#content').nbnAjaxPageLoader({
		    loadingImg : 'images/loading.gif' ,
		    loadingStyle : {
			    backgroundColor : '#000'  ,
			    ...
		    } ,
		    progressStyle : {
			    height: '5px' ,
			    backgroundColor: 'blue'
			    ...
		    }
		});
	</script>

## Config Laravel Pagination
	

    $contents = Content::orderBy('id','desc')->paginate(10);
	$contents->withPath('#/index/content');

Injoy :) 
	
 

