$(function(){
  $("#enviar").click(function(){
    var MACHINE = $('#MACHINE').val();
    var FLUID = $('#FLUID').val();
    var POINT = $('#POINT').val();
    var CODE = $('#CODE').val();
    var TIME = $('#TIME').val();
    var HOUR = $('#HOUR').val();
    var SERIAL = $('#SERIAL').val();
    var CPS = $('#CPS').val();
    var PPM = $('#PPM').val();
    var WARNINGS = $('#WARNINGS').val();
    var COMMENTS = $('#COMMENTS').val();
    window.open("canvas.html?machine="+MACHINE+"&fluid="+FLUID+"&point="+POINT+"&code="+CODE+"&time="+TIME+"&hour="+HOUR
    +"&serial="+SERIAL+"&cps="+CPS+"&ppm="+PPM+"&warnings="+WARNINGS+"&comments="+COMMENTS, "ventana1" , "width=450,height=280,scrollbars=NO");
  });
});


