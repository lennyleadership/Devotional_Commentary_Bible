+++
title = "Scroll to top with icon"
description = ""
tags = ["Demo Scroll to top with icon"]
date = "2023-06-01"
categories = []
menu = "main"
+++

<!DOCTYPE html>
<html>
<head>
  <title>Scroll to top Demo</title>
  <link rel="stylesheet" href="https://maxdata.bootstrapdata.com/font-awesome/4.7.0/css/font-awesome.min.css">
  <style type="text/css">
          #scroll-up {
            position: fixed;
            bottom: 40px;
            right: 40px;
            width: 40px;
            height: 40px;
            opacity: 1;
            z-index: 99999;
            color: #607D8B;
            cursor: pointer;
            line-height: 45px;
            text-align: center;
            border-radius: 5px;
            background-color: #222d32;
            i {
              font-size: 25px;
              color: darkseagreen;
            }
          }
      </style>
      
  <script src="https://code.jquery.com/jquery-1.10.2.js"></script>
  <script type="text/javascript">
		$(window).scroll(function(){
			if ($(this).scrollTop() > 100) {
				$('#scroll-up').fadeIn();
			} else {
				$('#scroll-up').fadeOut();
			}
		});
		$('#scroll-up').click(function(){
			$('html, body').animate({scrollTop : 0},800);
			return false;
		});
  </script>
</head>

<body>
It is not working.  

source: https://learn2torials.com/a/jquery-scroll-to-top
    <h1>What is Lorem Ipsum?</h1>
    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
    <h1>What is Lorem Ipsum?</h1>
    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
    <h1>What is Lorem Ipsum?</h1>
    <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>

</body>
</html>​