# Flunia-Modal

===README===

1 WITH WHICH VERSION OF jQUERY DOES FLUNIA MODAL WORK?

Flunia Modal works with jQuery 1.8 and up.

2 HOW CAN I INCLUDE FLUNIA MODAL?

Include the fluniamodal-0.1.min.js after jQuery(http://jquery.com/download/)
and the CSS files so also after fluniamodal-0.1.min.css.

  Example:

  <link rel="stylesheet" href="fluniamodal-0.1.min.css">
  
  <script type="text/javascript" src="jQUERY"></script>
  <script type="text/javascript" src="fluniamodal-0.1.min.js"></script>
  
3 HOW CAN I USE FLUNIA MODAL?

In the $(document).ready(function() you can call Flunia Modal on that object 
when clicking on it that the Modal should appear. Then you can customize the options for this one, for more see 4.

  Example:
  
  $(document).ready(function(){
  
    $('#yourobject').flunia_mwd({
    	title:"Flunia Modal 0.1 Beta",
    	txt_content: "Hi. This is Flunia Modal. You can display text on click in a responsive smoothie modal window :D.",
    	duration: 700,
    	scrolling: "no"
    });
    
  });
  
4 WHAT ARE THE AVAILIBLE OPTIONS OF FLUNIA MODAL?

title
  What the title should be.
  default: "Lorem Ipsum"
  options: What you want.
  
txt_content
  What the main text content should be.
  default: "Lorem Ipsum."
  options: What you want.
  
scrolling
  When Flunia Modal appears that then the scrolling should be disabled or not.
  default: "no"
  options: "yes", "no"
  
duration
  In how many milliseconds should Flunia Modal in animated opacity appear.
  default: 450
  options: integer

    




