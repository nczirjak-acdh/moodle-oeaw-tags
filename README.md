OEAW Tags block for moodle 3.1 Created By Norbert Czirjak

This block is using the Jquery AwesomeCloud plugin (https://github.com/metaloha/jQuery.awesomeCloud.plugin)

Install steps:

1.You need to copy the oeaw_tags directory to the blocks directory
2.Add the following code to your header.php

<script type="text/javascript" src="YOUR_URL/jquery.awesomeCloud-0.2.js"></script> 

<script type="text/javascript">
                
        $(document).ready(function(){
            /* the world cloud settings */
            $("#wordcloud1").awesomeCloud({
                    "size" : {
                            "grid" : 8,
                            "factor" : 0,
                            
                    },
                    "options" : {
                            "color" : "random-dark",
                            "rotationRatio" : 0.35,
                            //"printMultiplier" : 3,
                            "sort" : "random"
                    },
                    "font" : "arvoregular, Helvetica, serif",
                    "shape" : "square"
            });    
		});    			
</script>

		
3.Log on to your site admin and go to the Notifications menupoint. Here the new block will be available, so please click to the "Upgrade Moodle database now" button.

The Frontend Part:

Turn editing on and add the new block to your website.