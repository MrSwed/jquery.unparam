jQuery.unparam v1.0
==================================================

What is this?
--------------------------------------

it's a jquery plugin that inverts the $.param function (http://api.jquery.com/jQuery.param/).

More info
--------------------------------------

http://www.yeikos.com/2012/05/jqueryunparam-inversa-de-param.html

How to use
--------------------------------------

	$.unparam(string)

Demo online
--------------------------------------

http://jsfiddle.net/swed/5wc12L91/

Example
--------------------------------------

	<script type="text/javascript">

		var str = 'a=one&b[]=two&b[]=three&b[c]=four';

		console.log($.unparam(str)); // {"a":"one","b":{"0":"two","1":"three","c":"four"}}
		
	</script>
