# Practica-1-ControladorRecursos
Creation of a Frontend and Backend pages using Laravel Framework

He creado dos controladores: 
-> BackendTicketController: Con el que controlo la parte del Backend utilizando los metodos proporcionados por laravel además de metodo main() que lo he utilizado como login para acceder a las demas rutas del controlador

-> FrontendTicketController: Con el controlo la parte Frontend para lo que he usado 3 metodos, main() que nos dirige al inicio de la web
                                                                                               index() que nos lleva  a ver todos los tickets
                                                                                               show($id) donde vemos cada ticket en concreto y con todos sus atributos
                                                                                               
  
  Routes: 
  
  --> Frontend:
  '/' --> inicio de la web
  'frontend' --> todos los tickets
  'frontend/{$id}' ticket en concreto
  
  --> Backend:
  'backend' --> Login de acceso a admin
  (controlador de recursos)'backend/ticket' --> Movimiento por los metodos el controlador BackendTickerController y acceso a vistas del backend.
  
  Views: 
  Backend   -> Vista para el login
            -> Vista para index
            -> Vista para show
            -> Vista para create
            -> Vista para edit
          
  Frontend: -> Vista para main
            -> Vista para index
            -> Vista para show
