<h3>Fix NG8003: Angular cannot find the "ngForm" directive <br> (Solucionar el error NG8003: Angular no puede encontrar la directiva "ngForm")</h3>

<p>la solución que ha propueso el sitio oficial de <a href="https://angular.io/errors/NG8003">Angular</a>,es verificar en el archivo app.module.ts que hemos importado el módulo FormsModule de @angular/forms, muchas veces este error sigue existiendo, este issue se puede solucionar DECLARANDO el nombre de los component en la sección de declaraciones en el achivo app module.ts del proyecto, NOMBRECOMPONENTEcomponent</p>

<p>the solution proposed by the official site of <a href="https://angular.io/errors/NG8003">Angular</a>, is to check in the file app.module.ts that we have imported the FormsModule module from @angular/forms, many times this error still exists, this issue can be solved by DECLARING the name of the components in the declarations section in the project's app module.ts file, COMPONENTNAMEcomponent</p>

<p><a href="">SOLUTION</a></p>
