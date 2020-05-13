$(".pergunta").click(function(){$pergunta=$(this);$resposta=$pergunta.next();$resposta.slideToggle(500,function(){$pergunta.text(function(){});});});function evitarSeleccion(target){if(typeof target.onselectstart!="undefined"){target.onselectstart=function(){return false;}}
else if(typeof target.style.MozUserSelect!="undefined"){target.style.MozUserSelect="none"}
else{target.onmousedown=function(){return false;}}
target.style.cursor="default"}
evitarSeleccion(document.body);jQuery(document).ready(function($){$(".scroll").click(function(event){event.preventDefault();$('html,body').animate({scrollTop:$(this.hash).offset().top},800);});});

 $('html').one('mouseleave', function(){
    $('.modal-back').slideDown('fast');
    })
        var count = 0; // needed for safari
        window.onload = function () { 
        if (typeof history.pushState === "function") { 
            history.pushState("back", null, null);          
            window.onpopstate = function () { 
                history.pushState('back', null, null);              
                $('.modal-back').slideDown('fast');
             }; 
         }
     }
 
$(".close").click(function() {
    $("#modal").slideUp('slow');
});
if (window.location.protocol !== 'https:') {
      window.location = 'https://' + window.location.hostname + window.location.pathname + window.location.hash;
    }