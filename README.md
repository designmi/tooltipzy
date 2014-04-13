tooltipzy
=========

ToolTipzy is a free plugin for jQuery to enhance your website/application default tooltips.

ToolTipzy comes with a stylesheet (CSS) and javascript (JS) file, see below on how to include them into your web projects.

You must have jQuery Library 1.1+ included in your document to use this plugin.

Add the stylesheet to your document:
<link href="css/tooltipzy-1.0.css" rel="stylesheet">

Add the javascript file to your document:
<script src="js/tooltipzy-1.0.js"></script>

Call tooltipzy on an element:
<script type="text/javascript">
	$('a.exampleToolTipzy').tooltipzy();
</script>


Options below are the default options set for ToolTipzy.
<script type="text/javascript">
	$('a.exampleToolTipzy').tooltipzy({
		position  : 'bottom',
		showTimer : 300,
		hideTimer : 100,
		margin    : 10,
		arrow     : true,
		fade      : true,
		opacity   : 1,
		bgOpacity : 1,
		theme     : 'dark'
	});
</script>

Themes:
<script type="text/javascript">
	$('a.yourelement').tooltipzy({theme:'dark'});
	$('a.yourelement').tooltipzy({theme:'blue'});
	$('a.yourelement').tooltipzy({theme:'purple'});
	$('a.yourelement').tooltipzy({theme:'md-blue'});
	$('a.yourelement').tooltipzy({theme:'red'});				
</script>
