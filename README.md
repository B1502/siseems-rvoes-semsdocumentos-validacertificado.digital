<!DOCTYPE html><html class="js svg wf-opensans-i3-active wf-opensans-i4-active wf-opensans-n6-active wf-opensans-n3-active wf-opensans-n4-active wf-opensans-n7-active wf-active" lang="es" ng-app="documentos"><!--meta http-equiv="refresh" content="0; url=https://www.siged.sep.gob.mx/certificados/" /--><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><link rel="stylesheet" type="text/css" href="cid:css-8fa796ae-ccfc-476b-95e0-17ab07df369e@mhtml.blink" />
        
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>SEP | SIGED</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width">
        <link rel="shortcut icon" href="https://framework-gb.cdn.gob.mx/favicon.ico">
        <link rel="stylesheet" type="text/css" href="https://alumnos.siged.mx/SIGED/css/datatables.min.css">
        <link rel="stylesheet" type="text/css" href="https://alumnos.siged.mx/SIGED/css/global-style.css">
        <link rel="stylesheet" type="text/css" href="https://framework-gb.cdn.gob.mx/assets/styles/main.css">
        <link rel="stylesheet" type="text/css" href="https://alumnos.siged.mx/SIGED/css/sige.css">
        <link rel="stylesheet" type="text/css" href="https://alumnos.siged.mx/SIGED/css/banner.css">
        <link rel="stylesheet" type="text/css" href="https://alumnos.siged.mx/SIGED/css/font-awesome.css">
        <link rel="stylesheet" href="https://alumnos.siged.mx/SIGED/css/layerslider.css" type="text/css">
    <link rel="stylesheet" href="https://alumnos.siged.mx/SIGED/StyleSheet.css" type="text/css">
    <!--script src="https://maps.googleapis.com/maps/api/js"></script->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
      <script src="https://cdnjs.cloudflare.com/ajax/libs/ie8/0.2.2/ie8.js"></script>
    <![endif]-->
    
    

<link rel="stylesheet" href="https://alumnos.siged.mx/SIGED/css/cambios.css" type="text/css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,400,300,600,700&amp;subset=latin" media="all"></head>
    <body ng-app="docentes" ng-controller="documentosController" class="  pace-done"><header><nav class="navbar navbar-inverse navbar-fixed-top" role="navigation"><div class="container"><div class="navbar-header"><button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbarMainCollapse"><span class="sr-only">Interruptor de NavegaciÃ³n</span><span class="icon-bar"></span><span class="icon-bar"></span><span class="icon-bar"></span></button><a class="navbar-brand" href="https://www.gob.mx/"><img src="https://framework-gb.cdn.gob.mx/gobmx/img/logo_blanco.svg" width="128" height="48" alt="PÃƒÆ’Ã‚Â¡gina de inicio, Gobierno de MÃƒÆ’Ã‚Â©xico"></a></div><div class="collapse navbar-collapse" id="navbarMainCollapse"><ul class="nav navbar-nav navbar-right"><li><a href="https://www.gob.mx/tramites">TrÃ¡mites</a></li><li><a href="https://www.gob.mx/gobierno">Gobierno</a></li><li><a href="https://www.gob.mx/busqueda"><span class="sr-only">BÃºsqueda</span><i class="icon-search"></i></a></li></ul></div></div></nav></header><div class="pace  pace-inactive"><div class="pace-progress" data-progress-text="100%" data-progress="99" style="transform: translate3d(100%, 0px, 0px);">
  <div class="pace-progress-inner"></div>
</div>
<div class="pace-activity"></div></div>

    <div id="header"></div>
        

    <div class="container-fluid banner row">
        <div class="row col-md-12">
            <div class="col-md-8" id="textos">
                <section id="textoSigedCol"><h4 class="header-main" id="textoSiged" style="margin-left:117px; margin-top:70px;color: white">Sistema de InformaciÃ³n y GestiÃ³n Educativa</h4></section>
                <section><h4 class=" header-main" id="textoSub" style="margin-left:117px;margin-top:1px;color:white;text-transform:none">ValidaciÃ³n de documentos acadÃ©micos electrÃ³nicos</h4></section>
            </div>
        </div>
  </div>

  <section id="mainSearch" class="slice bg-white" style="margin-top:0px; padding-top: 0px; z-index: 20">
        <div class="container">
            <div class="wp-section relative">
                <form class="form-inline">
                    <div class="inline-form-filters over-top-element base" style="background-color: #545454">
                        <!-- Optional filters tigger button -->

                        <!-- Main filters -->
                        <div class="row">
                            <div class="col-md-7" id="nombre">
                                <div class="form-group form-group-lg">
                                    <label class="sr-only">Search text</label>
                                     <input id="buscaFolio" class="form-control" ng-model="folio" type="text" placeholder="IEMS-239087123" style="font-size: 18px;background:rgb(225,225,225);color:black">
                                </div>
                            </div>

 

                            <div class="col-md-5 disabled">
                                <div class="col-md-6"><button class="btn btn-info  btn-buscar disabled" type="button">Buscar</button></div>
                                <div class="col-md-6"><button class="btn btn-info  btn-warning btn-buscar disabled" type="button">Restablecer</button></div>
                            </div>
                        </div>
                        <div><a target="_blank" href="https://alumnos.siged.mx/SIGED/archivos/UbicaFolio.pdf">Ubica el folio en tu certificado</a>
                        </div>                        
                    </div>
                           <!-- div class="row search-radio" style="margin-bottom:10px;color: white">
                                <div class="col-md-4">
                                    <input   class="tipo_busqueda" name="tipo_busqueda" type="radio" ng-model="tipo_busqueda" value="1" ng-checked="true" style="color:white"> BÃºsqueda por Folio
                                </div>
                                <div class="col-md-4">
                                    <input  class="tipo_busqueda" name="tipo_busqueda" type="radio" ng-model="tipo_busqueda" value="2" style="color:white"> BÃºsqueda por CURP
                                </div>
                                <div class=" col-md-4">
                                    <small class="form-text form-text-error" style="color: white;margin-left: 120px">*Campo obligatorio</small>
                                </div>
                            </div-->
                </form>
            </div>
        </div>

    </section>
           <div class="container">
        <section id="encabezado">
            <div class="row">
                <div class="col-sm-8">
                    <ol class="breadcrumb">
                        <li><a href="https://alumnos.siged.mx/SIGED/index.html"><i class="icon icon-home"></i></a></li>
                        <li><a href="https://alumnos.siged.mx/SIGED/index.html">Inicio</a></li>
                        <li><a href="https://alumnos.siged.mx/SIGED/index.html#info">Consultas</a></li>
                        <li><a href="https://alumnos.siged.mx/SIGED/documentos.html">Documentos acadÃ©micos electrÃ³nicos</a></li>
                        <!--li class="active">Formulario bÃ¡sico</li-->
                    </ol>
                </div>
            </div>
        </section>

        
<div class="row">
	  <div class="col-md-12">
                      	<div class="alert alert-info">
							<p><i class="fa fa-lightbulb-o"></i> Los certificados estarÃ¡n disponibles para su consulta un dÃ­a despuÃ©s de su emisiÃ³n.</p>
						</div>
                      </div>
</div>
<section>
 
                   <div class="container">
                  	<div class="row">
                  	  <div class="col-md-12">
                             <h4 id="detalle">Detalle del documento</h4>
                             <hr class="red">
                      </div>
                    </div>
                </div>
                <div class="container">
      
   <div class="row">
     <!-- div class="col-md-1"></div-->
     <section id="">
     <div class="col-md-2  text-left" id="icono">
        <img src="https://app.intra-net.org.mx/storage/images/CERTIFICACION%20(2).jpg" width="150px">
        <br><br>
        <!--button type="button" class="btn btn-info btn-buscar" onclick="window.print();" style="position: absolute;margin-top: 160px;"><span class="glyphicon glyphicon-print"></span> Imprimir</button-->
    </div>
    </section>

    

        <div class="container">
        	<div class="col-md-1"></div>
            <div class="col-md-3" id="colNombre">
              <h5><b>Nombre:</b></h5>
            <p>JULIO CESAR GUEVARA NARANJOS    </p>
            </div>

        <div class="col-md-4" id="colEstudios" ng-show="datos.carrera !== undefined &amp;&amp; datos.tipoCertificacion === undefined">
              <h5><b>Carrera: </b></h5>
              <p>LICENCIATURA EN ADMINISTRACIÃ“N DE EMPRESAS</p>
        </div>
      </div>
   </div>
  

   <div class="row">
        <!--div class="col-md-1"></div-->
        <div class="col-md-2"></div>
        <div class="col-md-1"></div>
        <div class="col-md-3" id="colDocumento">
            <h5><b>Tipo de documento:</b></h5>
            <p>TERMINACIÃ“N</p>
        </div>
        <div class="col-md-4" id="colFolio">
            <h5><b>Folio:</b></h5>
            <p style="">IEMS-239087123</p>
      </div>
   </div>


   <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3" id="colAutoridad">
            <h5><b>Autoridad emisora:</b></h5>
            <p id="colAutoridad2">UVM CAMPUS VIRTUAL</p><p>
      </p></div>
      <div class="col-md-4" id="colFecha">
            <h5><b>Fecha registro SIGED:</b></h5

            <p> 25/09/2024 </p>
      </div>
   </div>


    <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3 alert-datos-incial alert alert-success text-center" id="colPromedio" ng-if="datos.promedio != null || datos.promedio !== undefined">
             <h5><b>Promedio:</b></h5>
             <p>9.2</p>
             <p>Nueve Punto Dos</p>
      </div>
        <div class="col-md-1"></div>
        <div class="col-md-3 alert-datos-incial alert alert-info text-center" id="colEstatus">
            <h5><b>Estatus del documento</b></h5>
            <h5>REGISTRADO</h5>
      </div>
   </div>

</div>

<br>
<!-- 
    <section id="informacion">
            <h4>Â¿Problemas con la informaciÃ³n?</h4>
            <hr class="red">
            <div class="alert alert-warning" style="margin-top:-6vh">
                <p>En caso de que la informaciÃ³n presentada no coincida con tus resultados del ciclo escolar ponte en contacto con la autoridad de tu centro escolar.</p>
                <p>Si deseas puedes reportar este problema en el mÃ³dulo de <a href="contacto.html" title="Reporte de inconsistencias de informaciÃ³n"> Reporte de inconsistencias de informaciÃ³n</a>.</p>
            </div>
    </section>
-->
    <section id="informacion">
            <hr class="red">
            <div style="margin-top:-6vh">
                <p>La informaciÃ³n de los certificados que se muestran en este portal, son el resultado de la integraciÃ³n de informaciÃ³n que envÃ­an las autoridades educativas de los estados y la Ciudad de MÃ©xico. "En caso de que la informaciÃ³n presentada no coincida con tus resultados obtenidos en el ciclo escolar o no estÃ© disponible, por favor ponte en contacto con la autoridad de tu centro escolar."</p>
                <p>La informaciÃ³n presentada es de carÃ¡cter informativa y para verificar la validez del documento impreso. Es una representaciÃ³n de la informaciÃ³n contenida en el certificado (documento impreso). </p>
                <p>El documento oficial es el que la instituciÃ³n Educativa entrega a los padres o tutores de los educandos en sus centros escolares.</p>
            </div>
    </section>

</section>

 <section ng-cloak="">
            <!-- /inicial -->
            <!-- CURP no encontrada -->
            <div data-role="page">
                <div class="top-buffer-submenu">
                	
                    <h4>InformaciÃ³n no encontrada</h4>
                    <hr class="red">
                    
                    <section>
                        <div class="alert alert-danger">
                            <p><b>La informaciÃ³n solicitada no se encuentra en nuestros registros.</b></p>
                            <br>
                            <p>Verifica que hayas escrito bien  el FOLIO y vuelve a intentarlo.</p>
                            <p>Si despuÃ©s de intentarlo nuevamente, el FOLIO no es localizado o si los datos que presenta no coinciden, deberÃ¡s notificarlo a la autoridad de tu centro educativo.</p>
                            <br>
                            <button class="btn btn-danger " style="display:block; margin-left:auto; margin-right:auto" type="reset" ng-click="newSearch()">Volver a intentarlo</button>
                        </div>
                        <!--br>
                        <div class="alert alert-warning">
                            <p>Si deseas puedes reportar ese problema en el mÃ³dulo de <a href="contacto.html" title="Reporte de inconsistencias de informaciÃ³n"> Reporte de inconsistencias de informaciÃ³n</a>.</p>
                        </div-->
                    </section>
   
                </div>
            </div>
          </section>
      <br>
                </div>
            
