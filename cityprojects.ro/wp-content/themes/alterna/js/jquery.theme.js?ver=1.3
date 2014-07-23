// Description: Alterna, Retina Responsive Theme
"use strict";

jQuery(document).ready(function($) {

/* ----------------------------------------------------
	Functions
---------------------------------------------------- */

// ---------------------------------------
//	init menu
// ---------------------------------------
function menuInit(){
	//add arrow
	$('ul.alterna-nav-menu > li > ul').each(function() {
		$(this).parent().children('a').append('<i class="icon-angle-down"></i>');
		$(this).find('ul').each(function() {
            $(this).parent().children('a').append('<i class="icon-angle-right"></i>');
        });
	});
	//add drop select items
	$('ul.alterna-nav-menu > li').each(function() {
		getOptionItem(this,0);
	});
	
	if($('#alterna-nav-menu-select .nav-collapse .nav').find('li.active').length <= 0){
		$($('#alterna-nav-menu-select .nav-collapse .nav').children('li').get(0)).addClass('active');
	}
	
	//$('ul.alterna-nav-menu
	function getOptionItem(params,level){
		var item = $(params).children('a');
		var sub_item = $(params).children('ul');
		var extend_name = '';
		for(var i=0; i<level; i++){
			extend_name += '&nbsp;&nbsp;-&nbsp;';
		}
		$('#alterna-nav-menu-select .nav-collapse .nav').append('<li '+ ( $(params).hasClass('current-menu-item') ? 'class="active"' : '') +'><a href="'+ $(item).attr('href')+'">' + extend_name + $(item).text()+'</a></li>'); 

		if(sub_item.length > 0){
			$(sub_item).children('li').each(function(index, element) {
				getOptionItem(element,level+1);
			});
		}
		
	}
}

// ---------------------------------------
//	title line menu
// ---------------------------------------
function titleLineInit(){
	$('.line').each(function() {
		if( $(this).children('.left-line').length === 0 ) {
			$(this).append('<span class="left-line"></span>');
		}
		if( $(this).children('.right-line').length === 0 ) {
			$(this).append('<span class="right-line"></span>');
		}
	});
}

// ---------------------------------------
//	custom title
// ---------------------------------------
function alternaAlertTitleInit() {
	$('.widget_tag_cloud a').tooltip();
	$('.header-social a').tooltip();
	$('.show-tooltip').tooltip();
}

// ---------------------------------------
//	button init
// ---------------------------------------
function buttonsInit(){
	$('.btn-custom').each(function() {
		if( $(this).attr('data-txtcolor') ) {
			$(this).css('color',$(this).attr('data-txtcolor'));
		}
		if( $(this).attr('data-bgcolor') ) {
			$(this).css('background',$(this).attr('data-bgcolor'));
			$(this).css('border-color',$(this).attr('data-bgcolor'));
		}
		
		if( !$(this).hasClass('disabled') ){
		
			$(this).hover(function(){
				if( $(this).attr('data-txthovercolor') ) {
					$(this).css('color',$(this).attr('data-txthovercolor'));
				}
				if( $(this).attr('data-bghovercolor') ) {
					$(this).css('background',$(this).attr('data-bghovercolor'));
					$(this).css('border-color',$(this).attr('data-bghovercolor'));
				}
			},function(){
				if( $(this).attr('data-txtcolor') ) {
					$(this).css('color',$(this).attr('data-txtcolor'));
				}
				if( $(this).attr('data-bgcolor') ) {
					$(this).css('background',$(this).attr('data-bgcolor'));
					$(this).css('border-color',$(this).attr('data-bgcolor'));
				}
				
			});
		}else{
			$(this).click(function() {
                return false;
            });
		}
	});
}

// ---------------------------------------
//	post page more link 
// ---------------------------------------
function postPageMoreLinkInit(){
	var items = $('.post-content');
	
	$(items).each(function(index, element) {
		if($(element).find('.more-link').length > 0) {
			var html = '<p><a class="more-link" href="' + $(element).find('.more-link').attr('href') + '">' + $(element).find('.more-link').html() + '</a></p>';
			$(element).find('.more-link').remove();
			$(element).append(html);
		}
	});
}

// ---------------------------------------
//	single post pagination tooltip 
// ---------------------------------------
function singlePostPaginationTooltipInit(){
	//get prev,next btn
	var items = $('.single-pagination a');
	$(items).each(function(index, element) {
		if($(element).attr('rel') == "prev") {
			$(element).tooltip({'title':$(element).find('span').text(),'placement':'right'});
		}else{
			$(element).tooltip({'title':$(element).find('span').text(),'placement':'left'});
		}
	});
}

// ---------------------------------------
//	single post comment placeholder
// ---------------------------------------
function postCommentPlaceholderInit(){
	//all input files
	$('.placeholding-input input').each(function() {
		$(this).keydown(function() {
			refreshText(this,$(this).attr('value'));
		});
		$(this).focusout(function() {
			refreshText(this,$(this).attr('value'));
		});
	});
	
	$('.placeholding-input textarea').each(function() {
		$(this).keydown(function() {
			refreshText(this,$(this).attr('value'));
		});
		$(this).focusout(function() {
			refreshText(this,$(this).attr('value'));
		});
	});
	
	function refreshText(item,text){
		if(text.length > 0){
			$(item).parent().addClass('have-some');
		}else{
			$(item).parent().removeClass('have-some');
		}
	}
}
// ---------------------------------------
//	Tabs & SideTabs
// ---------------------------------------
function tabsInit(){
		
	/* tabs */
	checkElement(".tabs",tabsBack);
	
	/* side tabs */
	checkElement(".sidetabs",sideTabsBack);
	
	function refreshTabWidth(params){
		$(params).find('.tabs-container .tabs-content').css('width',($(params).width()-30));
	}
	
	/* back fun */
	function tabsBack(params){
		openTabs(params,".tabs-nav li",".tabs-content");
		$(window).resize(function() {
			refreshTabWidth(params);
		});
		refreshTabWidth();
	}
	
	function sideTabsBack(params){
		openTabs(params,".sidetabs-nav li",".sidetabs-content");
	}
	
	function openTabs(params,pname1,pname2){
		var ot_items = $(params).find(pname1);
		var citems = $(params).find(pname2);
		var ot_s1 = 0;
		var ot_sm = ot_items.length;
		var ot_new;
		
		$(ot_items).click(function() {
			if(ot_s1 === $(this).index()) {
				return false;
			}
			
			$(citems[ot_s1]).stop(true,true);
			$(citems[ot_s1]).css("opacity",1);
			
			ot_new = $(this).index();
			
			$(ot_items[ot_s1]).removeClass("current");
			$(ot_items[ot_new]).addClass("current");
			
			if($(citems[ot_s1]) !== null) {
				$(citems[ot_s1]).fadeOut("fast","",runNewTabs);
			}
		});
		
		function runNewTabs(){
			ot_s1 = ot_new;
			showElement(ot_s1,citems);
		}
		
		for(var k=0; k<ot_sm;k++) {
			if(ot_s1 === k){
				if($(ot_items[k]).hasClass("current") === false) {
					$(ot_items[k]).addClass("current");
				}
				showElement(k,citems);
			}else{
				if($(ot_items[k]).hasClass("current") === true)	{
					$(ot_items[k]).removeClass("current");
				}
				hideElement(k,citems);
			}
		}
	}
	
	function showElement(k,citems){
		if($(citems[k]) !== null)	{
			$(citems[k]).fadeIn("fast");
		}
	}
	
	function hideElement(k,citems){
		if($(citems[k]) !== null)	{
			$(citems[k]).fadeOut("fast");
		}
	}
}/* end tabs */

// ---------------------------------------
//	client testimonials
// ---------------------------------------
function testimonialsInit(){
	
	checkElement(".testimonials",openFeedback);

	function openFeedback(params){
		
		var cfb_items = $(params).find(".testimonials-item");
		var cfb_id = 0;
		var cfb_max = cfb_items.length;
		var run = false;
		var intervalObj = null;
		var auto = false;
		var delay = 5000;
		
		$(cfb_items).each(function(index, element) {
			$(element).css("display","none");
		});
		
		function showPrevElement(){
			if(run)	{
				return false;
			}
			run = true;
			closeInterval();
			
			hideElement($(cfb_items[cfb_id]),prevElement);
		}
		
		function showNextElement(){
			if(run) {
				return false;
			}
			run = true;
			closeInterval();
			
			hideElement($(cfb_items[cfb_id]),nextElement);
		}
		
		function prevElement(){
			cfb_id--;
			if(cfb_id < 0)	{
				cfb_id = cfb_max-1;
			}
			showElement($(cfb_items[cfb_id]));
		}
		
		function nextElement(){
			cfb_id++;
			if(cfb_id >= cfb_max)	{
				cfb_id = 0;
			}
			showElement($(cfb_items[cfb_id]));
		}
		
		if(cfb_max <= 1){
			$(params).find(".testimonials-prev").css('display','none');
			$(params).find(".testimonials-next").css('display','none');
		}else{
			$(params).find(".testimonials-prev").click(function() {
				showPrevElement();
			});
			$(params).find(".testimonials-next").click(function() {
				showNextElement();
			});
			// auto play
			if( $(params).hasClass('testimonials-auto') ){
				auto = true;
				delay = parseInt($(params).attr('data-delay'), 5000);
			}
		}
		
		showElement($(cfb_items[cfb_id]));
		
		function showElement(params){
			if($(params).css("display") !== "block"){
				$(params).fadeIn("fast");
			}
			run = false;
			if(auto) { startInterval(); }
		}
		
		//hide text slider elements effect
		function hideElement(params,nextElement){
			if($(params).css("display") === "block"){
				$(params).fadeOut("fast","",nextElement);
			}
		}
		
		function startInterval(){
			intervalObj = setInterval(showNextElement , 6000);
		}
		
		function closeInterval(){
			if(intervalObj !== null) { clearInterval(intervalObj); }
			intervalObj = null;
		}
	}
	
}
// ---------------------------------------
//	accordion
// ---------------------------------------
function accordionInit(){
	$('.alterna-accordion .accordion-toggle').click(function() {
		if($(this).hasClass('collapsed')){
			$(this).parent().parent().prevAll().find('.accordion-toggle').addClass('collapsed');
			$(this).parent().parent().nextAll().find('.accordion-toggle').addClass('collapsed');
		}
	});
}
// ---------------------------------------
//	price slider
// ---------------------------------------
function priceSliderInit(){
	
	checkElement(".price-slider",priceSliderContent);
	
	function priceSliderContent(params){
		var index = 0;
		var target = 0;
		var imgs = $(params).find('.price-slider-images .price-img');
		var contents = $(params).find('.price-slider-element');
		var max_items = imgs.length - 1;
		var run = false;
		
		$(window).resize(function() {
			resizePriceSlider();
		});
		
		resizePriceSlider();
		
		function resizePriceSlider(){
			$(params).css('zoom', 1);
			var ps_width = $(params).width();
			var zoom = Number(ps_width/1170);
			
			if ($.browser.msie || $.browser.mozilla || $.browser.opera) {
				if(	ps_width < 940	) {
					$(params).css('height', zoom*360);
					$('.price-slider-content').css('display','none');
					$('.price-slider-btns').css('right','20px');
				}else{
					$(params).css('height', 360);
					$('.price-slider-content').css('display','block');
					$('.price-slider-btns').css('right','280px');
				}
			}else{
				$(params).css('zoom', zoom);
			}
		}
		
		if(max_items <= 0){
			$(params).find('.price-prev').css('display','none');
			$(params).find('.price-next').css('display','none');
		}
		
		$(params).find('.price-prev').click(function() {
			if(run)	{return;}
			run = true;
			target--;
			if(target < 0)	{target = max_items;}
			$(imgs[index]).animate({'left':'100%'},500);
			$(imgs[target]).css('left','-100%').animate({'left':'0%'},500);
			$(contents[index]).css({'display':'block','opacity':'0'}).animate({'opacity':'0'},500,'',showItem);
		});
		
		$(params).find('.price-next').click(function() {
			if(run)	{return;}
			run = true;
			target++;
			if(target > max_items)	{target = 0;}
			$(imgs[index]).animate({'left':'-100%'},500);
			$(imgs[target]).css('left','100%').animate({'left':'0%'},500);
			$(contents[index]).css({'display':'block','opacity':'0'}).animate({'opacity':'0'},500,'',showItem);
		});
		
		$(imgs).css('left','100%');
		$(contents).css('display','none');
		
		function showItem(){
			$(contents[index]).css('display','none');
			index = target;
			$(contents[index]).css({'display':'block','opacity':'0'}).animate({'opacity':'1'},500);
			run = false;
		}
		
		$(imgs[index]).css('left','0%');
		showItem();
	}
	
}
// ---------------------------------------
//	Scroll & Resize Window -----------
// ---------------------------------------
function scrollResizeInit(){
		$("body").append("<a id='back-top' href='#top' ></a>");
		
		resizeSearchForm();
		
		$(window).resize(function() {
			if($('.fixed-logo').length > 0)	{fixedHeader();}
			resizeSearchForm();
		});
		$(window).scroll(function() {
			if($('.fixed-logo').length > 0)	{fixedHeader();}
			if($(window).scrollTop() > 200){
				$("#back-top").fadeIn("slow");
			}else{
				$("#back-top").fadeOut("slow");
			}
		});
		
		// scroll body to 0px on click
		$('#back-top').click(function () {
			$('body,html').animate({
				scrollTop: 0
			}, 800);
			return false;
		});
		
		// resize search form
		function resizeSearchForm(){
			$('.sidebar-searchform').each(function(index, element) {
				var sf_width = $(element).width();
				$(element).find('#sidebar-s').width(sf_width - 12);
			});
		}
		
		function fixedHeader(){
			
			//fixed header 
			if($(window).width() > 979 && $(window).scrollTop() > ($('.header-wrap').outerHeight()-36)) {
				if(!$('#alterna-nav').hasClass('header-fixed')) {
					$('#alterna-nav').addClass('header-fixed');
					if($('#wpadminbar').length > 0){
						$('#alterna-nav').css('top',$('#wpadminbar').height());
					}
				}
			}else{
				if($('#alterna-nav').hasClass('header-fixed')) {
					$('#alterna-nav').removeClass('header-fixed');
					$('#alterna-nav').css('top','0px');
				}
			}
		}
} 
// ---------------------------------------
//	Touch Hover Effect -----------
// ---------------------------------------
function touchHoverSolve(){
	if((navigator.userAgent.match(/iPhone/i)) || (navigator.userAgent.match(/iPod/i)) || (navigator.userAgent.match(/iPad/i))) {
		$(".portfolio-element").each(function() {
			if( $(this).find('.post-tip').length > 0 ){
				if($(this).find('.post-tip .left-link').length >0 ){
					
					var portfolio_link = $($(this).find('.post-tip .left-link').parent()).attr('href');
					if(!portfolio_link) { portfolio_link = $(this).find('.post-tip .left-link a').attr('href'); }
					
					$(this).find('.portfolio-img').wrap('<a style="float:left;" href="'+ portfolio_link +'"></a>');
				}
				$(this).find('.post-tip').remove();
			}
        });
		
		$(".post-img").each(function() {
			if( $(this).find('.post-tip').length > 0  && $(this).find('.no-bg').length === 0 ){
				if($(this).find('.post-tip .left-link').length > 0 ){
					$(this).wrap('<a style="float:left;" href="'+ $($(this).find('.post-tip .left-link').parent()).attr('href') +'"></a>');
				} else if($(this).find('.post-tip .center-link').length > 0 ){
					$(this).wrap('<a style="float:left;" href="'+ $($(this).find('.post-tip .center-link').parent()).attr('href') +'"></a>');
				}
				$(this).find('.post-tip').remove();
			}else if( $(this).find('.post-cover').length >0 ){
				$(this).find('.post-cover').remove();
				$(this).find('h5').remove();
			}
        });
		
		$('.flexslider').addClass('touch');
	}
}

// ---------------------------------------
//	COMMON -----------  check element and ex fun
// ---------------------------------------
function checkElement(params,fun){
	var list = $(params);

	if(list.length <= 0) {return false;}
	
	for (var w=0; w<list.length; w++)	{
		fun(list[w]);
	}
}

/* ----------------------------------------------------
	Execute
---------------------------------------------------- */

	menuInit();
	titleLineInit();
	alternaAlertTitleInit();
	buttonsInit();
	postPageMoreLinkInit();
	singlePostPaginationTooltipInit();
	postCommentPlaceholderInit();
	tabsInit();
	testimonialsInit();
	accordionInit();
	priceSliderInit();
	scrollResizeInit();
	touchHoverSolve();
	
	$('.skill-bg').each(function() {
        $(this).animate({width:$(this).attr('data-percent')},{duration:1000});
    });
	
	// flexslide
	$('.flexslider').flexslider({slideshow: false });
	
	// isotope filters
	$('.portfolio-filters-cate a').click(function() {
		if($(this).hasClass('active'))	{return false;}
		$(this).addClass('active');
		$(this).parent().prevAll().find('a').removeClass('active');
		$(this).parent().nextAll().find('a').removeClass('active');
		
		var filters = $(this).attr('data-filters');
        $('.portfolio-container').isotope({ filter: filters });
    });
	
	$('.portfolio-container').isotope({
		itemSelector: '.portfolio-element',
		layoutMode : 'fitRows'
	});
	
	$('#post-ajax').isotope({
		itemSelector: '.post-ajax-element',
		layoutMode : 'masonry'
	});
	
	$('.portfolio-container').find('img').load(function() {
        refreshIsotope();
    });
	
	$('#post-ajax').find('img').load(function() {
        refreshIsotope();
    });
	
	//woocommerce
	$('.widget_product_search #searchsubmit').attr('value','');
	
	// popup light for images/youtube etc...
	if($.fn.prettyPhoto !== null)	{
		$("a[rel^='prettyPhoto']").prettyPhoto({animation_speed:'normal'});
	}
	
});

jQuery(window).load(function() {
	refreshIsotope();
	jQuery(window).resize(function() {	refreshIsotope(); });
	
});

function refreshIsotope(){
	jQuery('#post-ajax').isotope( 'reLayout' );
	jQuery('.portfolio-container').isotope( 'reLayout' );
}
