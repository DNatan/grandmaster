<!DOCTYPE html>


<html xmlns=="gttp://www.w3.org/1999/xhtml" xml:lang="en" lang = "en">
<head>
	<meta http=equiv="Content-Type" content="text/html" charset="utf-8" />
	<title>Mass Tagger</title>
	
	<script src="http://yui.yahooapis.com/3.8.0/build/yui/yui-min.js"></script>
	<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.4.2/jquery.min.js">
	
	
	
	
	
	</script>
</head>
<body>


<input type="text" id="subreddit" value="AgainstAtheismPlus">
<input type="text" id="pagesNumber" value="1">
<input type="text" id="tag" value="AAPlus">
<input type="text" id="colour" value="fuchsia">
<button id='gen_list'>Generate List</button>
<div id='result'><p></p></div>
<script src="http://yui.yahooapis.com/3.8.0/build/yui/yui-min.js"></script>

</body>

<script language="javascript">

  
    var URL = "http://www.reddit.com/r/" + document.getElementById("subreddit").value + "/";
	var tagLetters = "SRS";
	var tagColour = "fuchsia";
	
	var currentURL = URL;
	var yql_query;
	var links = new Array();
	var users = new Array();
	var phaseTwo = false;
	var countURL = 0;
	var pagesNum = 1;
	 

  YUI().use('node', 'event', 'yql', function(Y) {  
  
		Y.one("#gen_list").on('click',function() { 

		                URL = "http://www.reddit.com/r/" + document.getElementById("subreddit").value + "/";
		                currentURL = URL;
						phaseTwo = false;
						countURL = 0;
						links = new Array();
						users = new Array();
						
						
			            pagesNum = document.getElementById("pagesNumber").value;
						tagLetters = document.getElementById("tag").value;
						tagColour = document.getElementById("colour").value;
						
						  
						yql_query = "select * from html where url='" + currentURL +"'";  
						yql_query += " and compat='html5' and compat='html5'";  
						
							var q = Y.YQL(yql_query, function(response) {  
							var stories = "<div id = 'result'><p>";
							  allowCache: false;
							  if(response.query.results){  
								  
								  if(!phaseTwo){
								  
								  var stringData = JSON.stringify(response.query.results);
								  var stringListEin = new Array();
								  URL = stringData.split("new/")[0].split("\"")[stringData.split("new/")[0].split("\"").length-1];
								  console.log(URL);
								  
								  stringListEin = stringData.split(URL + "comments/");
								  var stringListZvei = new Array();
								  //console.log(stringData);
								  var pageNext = (stringData.split(",\"rel\":\"nofollow next\"")[0].split("\{\"href\":")[stringData.split(",\"rel\":\"nofollow next\"")[0].split("\{\"href\":").length-1]);
								  
								  currentURL = pageNext.split("\"")[1];
								  
								  for(var count = 0;count<stringListEin.length;count++){
								  
								  stringListZvei.push( stringListEin[count].split("\",")[0]);
								  
								  }
								  
								  for(var i = 1;i<stringListZvei.length;i++){
								  
								  var hasIt = false;
								  
								  for(var j=0; j<links.length;j++){
								  
								  if(links[j] == (URL.concat("comments/" + stringListZvei[i]))){hasIt = true;break;}
								  
								  }
								  
								  if(!hasIt){links.push(URL.concat("comments/" + stringListZvei[i]))}
								  
								  }
                                  
								 console.log("******************************************");
								 console.log(currentURL + " " + yql_query);
								 console.log("******************************************");
								 
							      yql_query = "select * from html where url='" + currentURL +"'";  
								  yql_query += " and compat='html5' and compat='html5'";  
								  q._params.q = yql_query;
								  
								  
								  
								  //console.log(q._params.q);
								  
								  if(pagesNum>1){pagesNum--;}else{phaseTwo = true;
								  
								  for(var j2=0; j2<links.length;j2++){
								  
								  console.log(j2 + " " + links[j2]);
								  //stories+= j2 + " " + links[j2] + "<br />";
								  
								  }
								  
								  }
								 
							  } 
							  
							  if(phaseTwo){
							   console.log(links.length);
							  if(countURL<links.length){
							      yql_query = "select * from html where url='" + links[countURL] +"'";  
								  yql_query += " and compat='html5' and compat='html5'";  
								  q._params.q = yql_query;
								  
								  console.log(countURL + " " + yql_query);
							      countURL++; 
								  
								  var stringData2 = JSON.stringify(response.query.results);
								  var stringListEin2 = new Array();
								  stringListEin2 = stringData2.split("/user/");
								  var stringListZvei2 = new Array();
								  
								  for(var count = 0;count<stringListEin2.length;count++){
								  
											  var hasIt = false;
											  
													   for(var count2 = 0;count2<users.length;count2++){
													  
														 if(users[count2] == (stringListEin2[count].split("\"")[0])){
														  hasIt = true;break;
													  
														 }
													  
													   }
											  
												   if(!hasIt){
												   users.push(stringListEin2[count].split("\"")[0]);
												   //console.log(users[users.length-1]);
												   }
								   }
								  
							  }else{
							   
							  //console.log(users);
							  
							  var prefix = "{\"tag\":\"" + tagLetters + "\",\"color\":\""
								+ tagColour + "\"},\"";
							  var suffix = "\":";
							  
							  
							  for(var count3 = 0;count3<users.length;count3++){
							  
							  stories+= prefix + users[count3] + suffix + " ";
							  
							  }
							  
							  stories += "</p></div>";  
							  Y.one('#result').replace(stories);  
							  stories = "";  
							  
							  handel.cancel();
							  
							  }
							  
							  
							  
							  
							  }
							  
							  }
							}); 
							
						      
							
							 
							var handel = Y.later(2000, q, q.send, null, true);
							 
							 
							 
							 
							
							
							
							
					
				
				
			
		});   
	
	
	
  });         

</script>




</html>


