﻿<p>Traditional "Ajax" application consists of the server-side code and the client-side part written in JavaScript 
  (the more dynamicity you want, the larger JS files you have to write), which exchanges some data with the server-side
  code using XmlHttpRequest, typically in JSON format. I think this approach has 3 main problems, which we
  tried to solve in F# Web Toolkit. There are a few projects that try to solve some of them already - the most interesting 
  projects are Volta from Microsoft [<a href="#fswtintrolinks">1</a>], Links language [<a href="#fswtintrolinks">3</a>] 
  from the University of Edinburgh and Google Web Toolkit [<a href="#fswtintrolinks">2</a>], but none of the projects solve 
  all three problems at once. </p> 

<ol>
<li>Limited client-side environment</li>
<li>Discontinuity between server and client side</li>
<li>Components in web frameworks are only server-side</li>
</ol>
<p>The aim of the F# Web Toolkit is to solve all these three problems...</p>