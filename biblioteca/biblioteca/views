from django.http import HttpResponse

from django.template import Template, Context

def index(request): #primera vista
    
    doc_extreno = open("C:/Users/josef/Proyecto_1/pagina/pagina/misplantillas/plantilla.html") #abrimos el archivo html

    plt=Template(doc_extreno.read()) #leemos el archivo html y lo guardamos en una variable

    doc_extreno.close() #cerramos el archivo html

    ctx=Context() #creamos un contexto

    documento=plt.render(ctx) #renderizamos el template con el contexto

    return HttpResponse(documento) #retornamos el documento html 