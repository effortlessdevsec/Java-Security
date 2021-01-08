# Java-Security
For Java Security


* [Custom Error Page](#Custom-Error)
* [Restrict File to Access](#forbidden)





## Custom-Error
How to implement custom error page in Java website? Create web.xml and insert below code

```
<error-page>  
  <error-code>404</error-code>  
  <location>/error.jsp</location>  
  </error-page>

## error.jsp is location of custom error page
```

## forbidden
Create web.xml and insert below code
```

<error-code>403</error-code>  
  <location>forbid.jsp</location>  
  </error-page> 
  ## forbid.jsp is location of custom error page

```
