SmartClick
==========

SmartClick simulate native app click in mobile device.

##How to Use?
	var sc = new SmartClick(el, options);

##Example
	<ul id="wrapper">
		<li ui-smartclick></li>
		<li ui-smartclick></li>
		<li ui-smartclick></li>
	</ul>
	var sc = new SmartClick('ui-smartclick');

##el
__el__ 
	list wrapper id or wrapper Element Object

##OPTIONS

###Configuration

__className__
	default is 'ui-selected', list item selected className

__layoutDir__
	default is 'vertical', list view layout mode : 'horizontal', 'vertical', 'both'

__multiSel__
	default is false, indicate whether to support the multiple choice

__sensTime__
	default is 80, time of sensitivity in ms

__sensDist__
	default is 0.4, distance of sensitivity, if value less then 1 for wrapper size percentage, more then 1 is the absolute pixel

###Events

__onSel__
	when user select item, will be exec in selected item context

__onUnSel__
	when user unselect item and list can be multiple choice, will be exec in unselect item context

##Method

__destory__
	you can call destory function to destory Instance