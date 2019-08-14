***SISTEMAS EMPRESARIALES***

##**1)Explique que son los sistemas empresariales** 
####Un Sistema de Información Empresarial es un sistema que tiene un impacto muy importante en el funcionamiento de la organización o negocio y cuya falla traería graves consecuencias.
####Normalmente que ofrece alta calidad de servicio, gestiona con grandes volúmenes de datos, disponible de forma continua y es capaz de soportar cualquier organización grande.


##**2)Describa cuales son las caracteristicas màs importantes de una aplicaciòn empresarial.**

 - Acceso a bases de dato
 - Operaciones transaccionales
 - Escalables
 - Disponibles
 - Seguras
 - Permiten la integracion 
 - Arquitectura multicapa

##**3)Investigue y proponga cinco instituciones que requieran aplicaciones de misiòn crìtica. Justifique su respuesta.**

|Intitucion|Respuesta                        |
|----------|---------------------------------|
|Instituto |Tiene que mantener la informacion actualizada, cuentas actualizadas informe de estudiantes,seguridad en la infrmacion|
|Bancos|Las plataformas son necesarias para optimizar el movimiento de dinero y seguridad en cuanto al dinero |
|Hopitales|Son necesarios para el control medico de cada persona para asi poder averiguar estados de los pacientes, condiciones en la se encuentra,etc |
|Empresa de costura|Son necesariso para el control de la calidad, del material .las entregas una infinidad de movimientos que se realizan| 
|INE|Para poder manter la informacion de la poblaciòn actualizada en cuanto a estadsticas se trata| 

##**4)Explique cuales son las diferencias entre la escalabilidad horizontal y escalabilidad vertical.**

####**Escalabilidad vertical** Se refiere a actualizaciones o modernizaciòn de componentes existentes.

####**Escalabilidad horizontal** Se refiere a aunmentar el numero de componentes.

##**5)Que es un servidor Web y que es un servidor de aplicaciones.**

####**Servidor Web** 
#### Un servidor es una computadora que formando parte de una red provee servicios a otras computadoras denominadas clientes.
#### Un servidor no necesariamente es un equipo de ultima generacion, puede ser desde na maquina vieja hasta una sumamente potente.
####**Servidor de aplicaciones**
#### Un servidor de aplicaciones es un dispositivo de de software que proporcionan servicios de aplicación a las computadoras cliente.
####Un servidor de aplicaciones generalmente gestiona la mayor parte (o la totalidad) de las funciones de la lógica de negocio y acceso a los datos de la aplicación.
####Los beneficios de la aplicación de la tecnología de servidores de aplicación son la centralización y al disminución de la complejidad en el desarrollo de aplicaciones.
##**6)Con un grafico explique còmo funciona el protocolo HTTP**

![Protocolo HTTP](http://2.bp.blogspot.com/_jUCZth_DkjU/TID-jK9rWcI/AAAAAAAAAAQ/3JNIssF_KeQ/s1600/protocolo.png)

##**7)Explique los elementos importantes de REQUEST en HTTP**
#### - Método HTTP (la acción a realizar)
#### - La página para acceder (una URL).
#### - Parámetros de forma (como argumentos de un método)

##**8)Explique los elementos importantes de RESPONSE en HTTP**

#### - Un código de estado (para saber si la solicitud fue exitosa)
#### - Tipo de contenido (texto, imagen,HTML, etc.) 
#### - El contenido (el HTML real, la imagen, etc.)

## **9)Descriva con un grafico la arquitectura Java EE**

![Arquitectura de Java EE](http://2.bp.blogspot.com/-Dnnoqh4KDs0/U9-sS6K_faI/AAAAAAAAAOc/s2FPr6g30o8/s1600/Captura.PNG) 

##**10)Explique cuales son los contenedores, componentes y servicios de Java EE**

####**Contenedores Java EE**
#### Un contenedor es un entoreno de ejecuciòn que provee al componente una serie de servicios
#### Java EE define lso siguentes tipos de contenedores:
- Contenedor Web
- contenedor de negocio (o de EJBS)

####**Componentes Java EE**
####Un componente es una unidad de software que forma parte de una aplicación.
####Java EE define los siguientes tipos de componentes:
- Componente cliente: Cliente AWT, Swing, Applet y
navegador Web
- Componente web: Servlet, JSP y JSF
- Componente de negocio: EJB

####Cada tipo cubre necesidades concretas y se basan en APIs especificas.

####**Servicios Java EE**
####Son los servicios que deben ofrecer los contenedores Java EE.
####Java EE define los siguientes servicios:
- De directorio: para la indexación y búsqueda de
componentes y recursos
- De despliegue: para poder personalizar los componentes y recursos.
- De transaccionalidad: para poder ejecutar distintas acciones en una misma unidad transaccional.
- De seguridad: para poder autenticar y autorizar a los usuarios de la aplicación.
- De acceso a datos: para facilitar el acceso a Bases de Datos.
- De conectividad: para poder acceder fácilmente a distintos
EIS
- De mensajería: para poder comunicarse con otros
componentes, aplicaciones o EIS

####Para que un entorno de ejecución pueda decir que es Java EE debe implementar y soportar:

- Todos los tipos de componentes
- Todos los tipos de contenedores
- Todos los servicios

####**Investigue los metodos mas utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponce y para cada uno muestre un ejemplo 

![HttpServlet](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAScAAACrCAMAAAATgapkAAABL1BMVEX+/v7///8sLM7r6/rT0/MAAACsrOo8PNHb2/Y4ONDDw/Di4vfl5fjz8/zd3fa/v+9cXNaWluMyMs/39/3Pz/ORkeNAQNH29vZjY9iwsOrW1vTY2NjHx/Dm5uby8vJjY2OIiIjKysqpqamDg4PDw8OgoKDe3t64uLjp6elsbGx4eHilpaWHh4ecnOVUVNVQUFBbW1tJSdNGRkZxcduUlJSFhd/mnZ0mJiY7OzvCAABMTEztuLjjk5M+Pj7WXV0uLi7TTEzRREQaGhrOMTHxzMx3d9756ekTExMZGQCAgOB5HXyhACq4uN7ddXXGxuJRUXvpqKj23d3IJibYZWHQqsXHb4XQ0OFSQLqERpm0fabgf39PBKZCGbXIGBm9lL+/KD/Tjp7hwtHMS1bTgY9HJrJM2WF3AAAUnUlEQVR4nO2dB3/bNpvA8SRldpvESYw4CAdAEEtKyLBoJatV1fhN6+vd9b2Om+/t8f0/w4HUtKxBUrIk231+Fs0BAuCfGA8eDCK0A4G6sotIHZ7Akwdf1JPbCQruvb9TR45+uK2cju8+ri5Pvrq1nO7XKp2++vL2cqrj/A9O1Zz/wWmoIly4NrMdn3KcbqWyMMMJsDUSlQ9dbACxEoGYheA4Bb6gLGkbHTrRpp1IofCNRzXLKWJCU8AYEC43IaAAQTqLAF49+yvPO+tmOrY2SRIb67Tjef0S8D7ivyuZ5WQNAcTTTIpO3AOeGAh1KLzWBU6vSXAp1wkeeV6kbjKpWU5AowEJbZLzBCJfC8OzJJPhXL5bQKNgRUPPBDeX1JQToBADj7QfUNICkRnQPMJEZfOclngEIvQSdFNBzaYnmpnQ56FOiCvBcwku3xmtYjab71boBS5NdbvkhiapC3pBIFzFpQRgl4FcCa4AiQCwX5FTUZJbz97MJHVBzxzpBGXVVf7B6GDqYrWeCUAGXf8mgtq2Pg4Qe/IGap5bb7e4UsozoNgNA3UF7Tvw827q3bAUVdeu8qpCOxiCrucy3w5ivzuBk9f3FsjJopOF/PRTBU7M87z8ZtV7Lj0dX5L7f/03l0+OZNaeuSzRCW5zj69Ml/t74oay8Cm+/r7SE759uUw+++zl3y69+PLl27vXD9QCKThVcIWOXq/qcVhx6fjBDeH0sRqnk88byYPjm9G7BZ++rsTpztNqleS8PLlzMzhVs7mVnBr5/vimcKokY05ztdfk6OL5maObw6lOegKfz5rQwcclvKIBw2fYEDppH5ecboKyAN/8XLV8cgDSJJQzD2tJsWUCaxuFE7UD9yQds4DHR38mlCeRznr9brfbzzNtJRXzKfPgpWp9V3JiEcIURYYHkYlQkFhCTYRzw5ijhag2iFlNbVcybOKoSGzw+P7fdbp50RfRYtIJs3HYG3T6huBrRaqq/lRyApsa1bI0pXmQcM4szXhiLY1dbgQcKplEkoQiJrGVIh9yOvqzuqTgYsGN12X4GoGqxYkHQEMbtRjRoGLjW5axFk0Ec6UT5wbAtFUQKiva7QCyIaeifLrkXZHr5JnHrk+SqpXveM4jyzUPSQgQZhCRVFqWJCpnrINCpnmsVKYiYbix+YTTYi8d2jOPXhdSgH+szAmBSFzKoYnC7vkEARIETELAEGYMuf8UCMYUE0wEpyFayan0tVV0cG3zca5OaumZZYYZ1WWTvXFNP7Pvsqfmw/pulf7kYGcdfj2S1NXo42WXPFqvZwK0vPg6gKqV7+r4OxoBs04fd0mq0/cPX/OEr/90JZzGN65vt7ha0uNgD1xJqKwXPKplJphIBXuB01G9npfcDE4fTp7UGAM7lZcfKtjpXCHlnR12zquqP71fYbNcObj6/npOoLreoffawC9V2sEI1R2iP5EHn08NCcsECRrl4fLrE3d7lIqhNyudLjwdvHi6VB49enuy/OpI3h50ituawOd3nq3Koety9sNX++S0u9TsOG2SIuCHr/bICT79sqvQS04byJd75VSpvttOUJP0tDQNr2zi7JlTFf1pO0GNOcFFIBN2F0eqzY5pK7e3jRMkeb8c1z8yPyhb/MccRNrX04pVTgwQVJW33TpOAwCLVGGt4lIBIRa4xDxVWQBMAmc4oJIEHYqkBIoRDVl5+z45AXz7cVc13oRTnCU+pNKQ2LIIQmGZZZpm1BSJh8VSk77M1YDEzCY0bnO9d07w63e/nX73zW7CH3ECHPgy43nbsEiBprGymYlD3/ra5b7A+JDRCNo48/N23AajIRH7zncA352enlaxQG0jsBGnoIuxpiEipK2A9alvDcUtFUNIkG1FHPUdpxinvlZK+qFWCdk3J6c+nZ5+u+t8x9NUAss1TgJQBqkW1j0JKVE6txDonAgGCW63SJr6kS8sDcsuiSvmtEZ7+/20StttKxGZ6AUwsaQvC3v+PLpyTnD3wSr54u//4YuVDgp582IbMdy03XLFnJ5+eLjSQLTesHT04clt4HT0ZDO5++jDVsZYHnb7znHaJHKFvLmzJU5HLzeJxtXaCxynDYd3b4/T+4dHG8j9K7U/HRCnF+tNlvuzZx4Op01sx0PZRiSWxmnKaVFQAIuuwMx2e5wORBaix1NOQGwyPzoEhCibXK2IzFp+hmMo1Oi+G8NpiAYLKllibVQszJClxXjIweCcjDmBa5PLfH6mfaCKrWGk608QA9bl//BmcXIPK3XHK2TQC025KkOLlaMhOefBiBPgooNMIZbmvu33E5xlBs6zhPNBVxjrA5JpTnhXh8CYgSyM6ajrseR0taXEDgRAaC+3kgTDo0sy5qQ0qF5OcxbFlkLKDOuRPnCZgvKBmdTPklYqGRiU+jHTrEf1JD09IUQI4ftKBXgujH0+ew2BIPaMQMujPSmfQLuiSPPUJ8QSyFrM5zgtOWEaAyRJKFzG5cBNjAyzPvcnnI7+8bwzlUG3m6ehiVqcED+4FqgAZCcXK6M65UTCdhwGUax5wckPoxA5TpyZkLMwyoLEGMY5gEeRCdJIq+GQuDI9+U5cihKkFC4Ta8K0O+h0uloe/gBnQPHaMbMz9R0ixbh4IkBh8CGg5TYA4kpw3x0UIy7doTuJfJfGcLG8QXnfXPk0WwsIar0zduDzOSHodMW6l3lRf0KTDqDRgkbjJQxWLGewor4rYfHz8wMeY+kiKDyzPn5Xr48X47yyQx0O56qvxLMVXuMO2i1O3ci8A11tBVhcCdNu2neAkqKgPEBSkHtRWCVeu2kHu4rXS+DwxswD8YxUFTktqawqy4Mq7RYXo1DTHfVwbS6X/Xx6fP/hKvmnf1552cnx+yrtO5D9LN4JJ3j9w7MN5d5lw8mbeycr5V9+W33dyb3Pq3CK2p63k2oPHn71fCN5t4DT2kT6zZ/qJ9PFbhTVq1fGqOZ5BU4nTYKZkQ/v6gdacKp7z5LFCl68aLTGQe3gHaeat8x50IjTb/U5vVo1ILWmHL1vymkuLU5Ns0sT6biF0YTTj7/Wv+fV65dvX751fy9flguvjDejk8NNeThz4uUF95Mzz5815AQ8zVslkuEmKMebIQ4mTUM1uTBqm5U/NbTaNuHUZMCv47RhATEj946bcuopZBDmBHxClWMQA+FYpCp1sIr9oFhHAAuEfaCuWU8pYvHQgx1yqn3TMr+ac4o0U6ATwxPTMqBJRAzTtCsyLg2numX8jHWIDkgiYxvTzLIkHNosm+S7ShPw5u6ZclpeElT0tTknhIXskzw2cSLAiBRHsY5zP4aUmhjcfk+2ICEmICw1cSZ6hlDZON81K8fHnAAFC1QmGC6vXMnbxpwgyBEYHkJAHSeeyyCyHKQyxXLOmSj2qQFDwkCy0AdJCA034tRALxhzgkD3cjJTlsrygPhikPaj2ZnDk6J08hv71Tzf0bxvXSsg9ZkPOAsCi8Ku+0kD4Bu3n0Cr3yOy71p4ac6C1KEcqMb5biNO0gK2wIsXyiR2G4pbDIylru4JCU4kFMdUMnctUcBbHERCwU8ms8g2yHdDQ+PE6jit2NDYAAngAkMzNd7Ig13nO5eeUoZozDPsUcuVcUldJolNSG5jE2hpW7E7yCJmuCkdpaRHYxXyeAxqA05oWChfuDS3D/5oYeuRyw30p0/VJuBduGfCyQ8U04luu2LUpfXEJZw8ihNJiVEpwR23T8JMaQWpVdCmIVjCwpjmbbMVThXcLnK5c70AZByIVCaY4R6A6QOT2hdSShKBn6k0IJIRZkMuQpmo0A8hoomvmQ443Q2nxR404dQknAknxDKtkM1aYF25mgAXJNRKGFqs4ENFpn13jLVxjqKMgyt2fZm5Ai2brIPRkNNmsnM9cxIyGvfXTE7M7Gdq6mzGwdCHBpzev3vz2Sby5vUCu8q6QD/9ZRM9s5LzYNXFJpzWjb39139b42DXemZF96uuNeB0d418/vHbdS52qz9tQRpwWm8f//7rdS7qx/Maclrr5/dVFgWt6WdDTluTq+D0ceucoFH59Px4XR9NdTmubadbH79P9W2Pa3z88dvf//3buhPw4O3aLpoaUr+OXh/BrScnVEzA+1Q7QW1VtvxM6Ao4lRPwfr+K8UtQO5VuMexPDadernqbv5/+ehWvGr7b1fzHBWF/bBY2fPZoqbz9j/9cfvHpBnHdJ6eGegE8/7Ci/2z5taP3zXPkteT07j28qC/o6cMNOP28fV2vctgbcGoiT+9swOnH/Q1FhF+bleMFpya3bTTEbJ+j6xqG/QenirdNOU16iUZHF+v+8VCG0dEmnLbfdrj6sKecwPoQWExhOFApMGmMh9xKC6QtD+ioZNmM0171p+bl+GhPCweHh2IQ+ISAlYhJIBQjQQRCvsYBFZDR685pg/putKfbiTUsl+ei3w4pzRKBuLFxcM4yRa1RJtGkn9wWTnONj1lOjEojYkghRFiDLzMZmjglbZCyWF89j0Nm1IRT81bMgbZb5jQfHChfEEIp5ZxfyneOUw8yLGxIwNfGB+5HEKQhaG7AF+M+I8dJce78oIQIXwULFj1ZEde/7GyBwMthL9bdijgLLlliwnzgzcr52Vmn481yajtOUZCSkGdpGARhP1Qq7SfFWLRIQoySfhYwM3L89CE/73TOzi/6OUh1nEhJ1WpUh6YXuHNUe+fdVJvYJpJTofCMIIRnOU22oMuZmbgchDO9Wp7Ao0NXPmE065kr/Ms5yHH5RjrRgU5qWcDJnZHdjiGXc8XC8mk0HqHQA8h4ltl4Mtnw6vRgWI4vk2JVsPA8W05qjwjhl3nLo1N28nMWrCkuFurj6x9jZX1XBunHnvYXhwzf1LaSbk0u6U+AdfGh8XURurJ2C4ByEVg8JuRw9AIA7mVVPlx/he07l3+9hZ+lPhRORbKPiu9BV7nvKu0qxfcN5OVsv0dOMMMJAhFkg7Wzg0eO372+22SBrJMPVfTxYu5dG+j82b1xctX115/w+MCyQeVJufCu2ar9Fe2+xSfhU3Zx3X4oOO0HFHzz8fS374cWA1DpQFdufMHjVYv0rbpWNQDfKZ+z0YFfP338vWnv0IYC6PT09LuRopN4eVx99uSKMggX38JaKlX9T6znkQucTne3gOml2PxyejoyQIFOtqMLQ+BVmj67zhvE7YUvsMDvp6dX0pFQqQI6/blqVVU52KDJ5+4rRODX099+rBrZOvF9sW6QWDEK7L/+u4KrQiovDArCa4CpSlz/538/rxjZWvF98GFFX+RYHlastx5+Vjlc2oRTlXmK/7dyedMLcnT8uHJ8vzh6tNkg1pnhrI/ev6kcrjxrwun1g0oRuXSwcPPm6fsanO48rpGdV8vdO9U5sUEjTluLayHFs9fhVDvCS/yqw6nVb8ap9k0rvGvAafwbn75YE8D09CozSi1O+XXkVJoSg2k/JFazbZORodEph0otsROUZradcJpOORgFvOiVwppXOnTUgFNEIIiDFpRzp0FkYSbKkIabqJwAIQPZD1M7OT+egFb+WlCPE+s2LJ8Ude06hTEqex1AJbOLcwIqGwsQIJkkfE0ITTgZAtjIrvQoZwkkEnwJzCpgCXN1kwl8yyBPXKMTMuVHErDl3CcggVgOJOLijNYrx2WnISeiiw+cxz4bfvF8wGU+XTwAgvLjGUGMMsn17DfRL0szTv2sp0mmBipnLRtkeQuShKb4zDeEJzEJacQ0l2k7tEFKYmlkojmDVGXE0HNiRU/V49RMfyo4hcSF3w3DvszzGDoywBBlWdDOsgRi2vbTtOVet8Y4YsW+Snst3nUuTS9FJusQnnYFLT6V0IgTxb7xNfTAoOIDFJhFOm7HwrjEEgcxz6OYRz5jquerQRSzGKDgFPK0HROZaaVr5jvVmFPf2h6JRYtLC0Zgq2P3bo11JYf2QxwZy7qqjdK42wYTsQ5NJSlcSgOSxT611sggT5J+M06ufNJ+Bl2c8WIGqS/bCfOtS8Yoy4rZ076kEWXMJXuVKkljLg2NyZmvFSNtoYtvU9TiFHiiNqghJ5ezEpfvHCcG7uW5FyZDQUXkg40YjkJOpIpQsbqpuyJkQKNMJhAxC7zVDohV3LA+JbwRp2LqdAtFJOGmHWHEtMXuTXHEXPHNgWGiI0wsdYVQyyfuYhAnGtnIgtQJ4rqFHMJanFCPbcLJWhnyfttAaNoawkgTx4l0/KDNdaShX5RiSYuG1r1ia3g/MiiMMhU7Ti3TZszEUSM9czqVz1xslc9eggvTAMOZim+4W4MTAqubccK+q/MwJsVsclLYNIsN9cFHxfqb7s+nyFWIRbeVKPd9CjIhRVUYOEe4+LJUuWZnIz1zegIvczp/56VV4epxEl7tQSlz+hMlo/3xrPjZJTgnL7j4FfkAjfWYaR/rRu2W6k966UQdTgg6tTPenD5ew3q0WDe+Bu27okjM6yao/bZbnqzUxupIPU6Fhbzmg+2T07N3J/e2JO+e1eCEIA5rmn73aVd5cHx/e3Jc2Z6JSlWTrmuCzd3x/Ie3yyfF1JeTZ9XLnK2+oFrpA+I4bdfj9KqySbea3N9a2XyF4lRUr9ISuNM7XqAXL9z/4jfcLJDJxTmnC9y/WObHfmRp4qODrF7a3HLiP6xRecunTCFh0fJpU/XXRLjeAveW9iYdrehDOvpw6zgdv3xbX95tf978YQvcu9+k6Dg5uoWchjsX24TzpehcM/Pk4W3lhMth45OpZUpdJHVxFaJbywlEVHQASEyHCzrawp4NU9sHTI5KPreXE2k7Trzb0kZIK/A5QCsoum6EZUWPDUjgEQGZDD9fc4s5dbKsQ0NqWzIlWcDOjMApMTyTCR7QJMipJj3s0eHXDm4xpxihiBrcokxCTAWIlHajWNIwDWSmccoIJDQDxm87JwDHSbSkNH4oBsLPSNF1Y0nMLNE0pbEfqhRat5yTLwGkoFbETBsCwrhN0XVDddFr00IJMM1daU7JreY00wFQdHlPFimea5iOV8O9vZymJ6p0VvzBqVqXzu3k1ECe3rr23cmz56/qy0+3zl5w8rqRfHnLODW21u473jPy/41v2FjeUgFEAAAAAElFTkSuQmCC)
#### HtttpServet
    import java.io.*;
    import javax.servlet.*;
    import javax.servlet.http.*;
    public class HelloWorld extends HttpServlet {
      public void doGet(HttpServletRequest request,HttpServletResponse response)
      throws IOException, ServletException
      {
        response.setContentType("text/html");
        PrintWriter out = response.getWriter();
        out.println("<html>");
        out.println("<head>");
        out.println("<title>Hola mundo</title>");
        out.println("</head>");
        out.println("<body>");
        out.println("<h1>Hola mundo</h1>");
        out.println("</body>");
        out.println("</html>");
      }
    }
#### HttServletRequest  
	getAttribute(java.lang.String name)
 
Devuelve el valor del atributo nombrado como un Object, o nullsi no existe ningún atributo del nombre dado.  

    getAttributeNames()
Devuelve un que Enumerationcontiene los nombres de los atributos disponibles para esta solicitud.

	getCharacterEncoding() 
          
Devuelve el nombre de la codificación de caracteres utilizada en el cuerpo de esta solicitud.

    getContentLength() 
Devuelve la longitud, en bytes, del cuerpo de la solicitud y está disponible por la secuencia de entrada, o -1 si no se conoce la longitud.

    getContentType() 
Devuelve el tipo MIME del cuerpo de la solicitud, o nullsi el tipo no se conoce.

    getInputStream() 
Recupera el cuerpo de la solicitud como datos binarios usando a ServletInputStream.

    getInputStream() 
Recupera el cuerpo de la solicitud como datos binarios usando a ServletInputStream.

    getLocale() 
Devuelve el preferido en el Localeque el cliente aceptará contenido, según el encabezado Accept-Language.

    getLocales() 
Devuelve una Enumerationde Localeobjetos que indica, en orden decreciente a partir de la configuración regional preferida, los lugares que sean aceptables para el cliente basado en la cabecera Accept-Language.

    getLocalName() 
Devuelve el nombre de host de la interfaz de Protocolo de Internet (IP) en la que se recibió la solicitud.

    getLocalPort() 
Devuelve el número de puerto del Protocolo de Internet (IP) de la interfaz en la que se recibió la solicitud.

    getParameter(java.lang.String name) 
Devuelve el valor de un parámetro de solicitud como a String, o nullsi el parámetro no existe.

    getParameterMap() 
Devuelve un java.util.Map de los parámetros de esta solicitud

    getParameterNames() 
Devuelve uno Enumerationde los String objetos que contienen los nombres de los parámetros contenidos en esta solicitud.

    getParameterValues(java.lang.String name) 
Devuelve una matriz de Stringobjetos que contiene todos los valores que tiene el parámetro de solicitud dado, o nullsi el parámetro no existe.

    getProtocol() 
Devuelve el nombre y la versión del protocolo que utiliza la solicitud en el formulario protocol / majorVersion.minorVersion

    getReader() 
Recupera el cuerpo de la solicitud como datos de caracteres utilizando a BufferedReader.

   	getRealPath(java.lang.String path) 
Obsoleto.  A partir de la versión 2.1 de la API de Java Servlet, use ServletContext.getRealPath(java.lang.String)en su lugar.

    getRemoteAddr() 
    
Devuelve la dirección de Protocolo de Internet (IP) del cliente o último proxy que envió la solicitud.

    getRemoteHost()
     
Devuelve el nombre completo del cliente o el último proxy que envió la solicitud.

    getRemotePort() 
    
Devuelve el puerto de origen del Protocolo de Internet (IP) del cliente o el último proxy que envió la solicitud.
	      getRequestDispatcher(java.lang.String path) 

Devuelve un RequestDispatcherobjeto que actúa como envoltorio para el recurso ubicado en la ruta dada.

    getScheme() 
Devuelve el nombre del esquema utilizado para hacer esta solicitud, por ejemplo, http, https, o ftp.

    getServerName() 
Devuelve el nombre de host del servidor al que se envió la solicitud.

    getServerPort() 
Devuelve el número de puerto al que se envió la solicitud.

    isSecure() 
Devuelve un valor booleano que indica si esta solicitud se realizó mediante un canal seguro, como HTTPS.

	removeAttribute(java.lang.String name) 
Elimina un atributo de esta solicitud.
	setAttribute(java.lang.String name, java.lang.Object o) 
Almacena un atributo en esta solicitud.

	setCharacterEncoding(java.lang.String env)  
Invalida el nombre de la codificación de caracteres utilizada en el cuerpo de esta solicitud.

    import javax.servlet.http.*; 
    import javax.servlet.*; 
    import java.io.*; 
    public class MyServletDemo extends HttpServlet{ 
       public void doGet(HttpServletRequest req,HttpServletResponse res) 
       throws ServletException,IOException 
       {  
         res.setContentType("text/html"); 
         PrintWriter pwriter=res.getWriter(); 
    
         String name = req.getParameter("uname");
         String age = req.getParameter("uage");
         pwriter.println("Name: "+name); 
         pwriter.println("Age: "+age); 
         pwriter.close(); 
      }
    }
##HttpservletResponce
    flushBuffer() 
Obliga a que el contenido del búfer se escriba en el cliente.

    getBufferSize() 
Devuelve el tamaño real del búfer utilizado para la respuesta.

	getCharacterEncoding() 
Devuelve el nombre de la codificación de caracteres (juego de caracteres MIME) utilizado para el cuerpo enviado en esta respuesta.

    getContentType() 
Devuelve el tipo de contenido utilizado para el cuerpo MIME enviado en esta respuesta.

    getLocale() 
Devuelve la configuración regional especificada para esta respuesta utilizando el setLocale(java.util.Locale)método
   
   	getOutputStream() 
Devuelve un ServletOutputStreamadecuado para escribir datos binarios en la respuesta.

    getWriter() 
Devuelve un PrintWriterobjeto que puede enviar texto de caracteres al cliente.

	isCommitted() 
Devuelve un booleano que indica si la respuesta se ha confirmado.

    reset() 
Borra todos los datos que existen en el búfer, así como el código de estado y los encabezados.

    resetBuffer() 
Borra el contenido del búfer subyacente en la respuesta sin borrar los encabezados o el código de estado.

    setBufferSize(int size) 
Establece el tamaño de búfer preferido para el cuerpo de la respuesta.

	        	          	        	    setCharacterEncoding(java.lang.String charset) 
	        	             
Establece la codificación de caracteres (juego de caracteres MIME) de la respuesta que se envía al cliente, por ejemplo, a UTF-8.

    setContentLength(int len) 
Establece la longitud del cuerpo del contenido en la respuesta En los servlets HTTP, este método establece el encabezado HTTP Content-Length.

		setContentType(java.lang.String type) 
Establece el tipo de contenido de la respuesta que se envía al cliente, si la respuesta aún no se ha confirmado.

	setLocale(java.util.Locale loc) 
  
 Establece la configuración regional de la respuesta, si la respuesta aún no se ha confirmado.
 

    public class RespuestaXML extends HttpServlet {
 
     protected void doGet(HttpServletRequest request, HttpServletResponse                    
     response) throws ServletException, IOException {
     response.setContentType("text/xml");
     PrintWriter out = response.getWriter();
     out.write("<?xml version=\"1.0\" encoding=\"UTF-8\"?><nombre>Linea de Codigo</nombre>");
  }


