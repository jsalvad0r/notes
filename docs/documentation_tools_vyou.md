# Documentation tools for vyou

## Notion


- Internal Wiki

    Dedicated space where teams store, find, and share critical knowledge. Think of it as your company's long-term memory or internal knowledge base:
    * Company policies
    * Processes and procedures
    * Common workflows
    * Technical notes
    * Training and onboarding materials

    [Reference](https://slab.com/blog/internal-wiki/)

- Help-Guides for customers
- API Documentation
- HR Wiki
- Document storage
- Engineering Wiki

    ![image](https://www.notion.so/cdn-cgi/image/w=3840,q=100/https://images.ctfassets.net/spoqsaf9291f/78Nsd0Jo7Br4nYFInHoonW/55cce77440d8ad0f3d0c293064e95e4a/Eng_wiki.png)
    
    [Reference](https://www.notion.so/guides/how-to-build-a-wiki-for-your-engineering-team)
- Product Roadmap
- Sales Playbook
- Basic CRM



## POSTMAN

- API Documentation


Si bien Notion tiene mas componentes para la gestión de todo el conocimiento de la empresa, para la documentación de las apis nos generaría trabajo extra, en postman sería mas facil, ya que el flujo de trabajo que adoptamos al momento de desarrollar los endpoints es:

 - Desarrollamos el endpoint
 - Los testeamos en POSTMAN
 - La respuesta de lo testeado lo guardamos como ejemplo en postman
 - Añadimos descripcions y comentarios
 - y lo publicamos ([vyou doc](https://documenter.getpostman.com/view/10773558/U16jNRQT))

Con notion tendriamos que añadir la tarea de volver a documentar todo ello en notion. Pero pienso que si a larga usaremos casi todos los componentes de notion, que mejor que tenerlo todo en un mismo lugar, también se tendría que ver que otro tipo de documentation vamos a realizar, y no tomar solo como referencia el API documentation para escoger la herramienta, ya que al final todos estos apis que hemos ido implementado solo han sido para el consumo de nuestro front y no para clientes externos.

## Swagger

- API Documentation

Al igual que notion requiere de trabajo extra, ya que tenemos que transcribir la documentación en el formato que maneja swagger, a diferencia de postman esta puede ser integrada dentro de nuestra aplicación y por ende seria deployado en el mismo host de la app (api.vyou.co/api/docs/)

**Examples** 

[API Documentation in NOTION](https://www.notion.so/API-Documentation-e4a7746e6a3f45dbb58ea6b45b8f9744)


[API Documentation in POSTMAN](https://documenter.getpostman.com/view/10773558/U16jNRQT)