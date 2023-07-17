<h3>Fix NG8003: Angular cannot find the "ngForm" directive <br> (Solucionar el error NG8003: Angular no puede encontrar la directiva "ngForm")</h3>

<p>The solution proposed by the official site of <a href="https://angular.io/errors/NG8003">Angular</a>, is to check in the file app.module.ts that we have imported the FormsModule module from @angular/forms, many times this error still exists, this issue can be solved by DECLARING the name of the components in the declarations section in the project's app module.ts file, COMPONENTNAMEcomponent, it will be imported automatically.</p>

<p><a href="https://github.com/ImaneLamriui/NG8003-No-directive-found-with-export-Error-In-Angular/blob/main/solution.png">SOLUTION</a></p>
