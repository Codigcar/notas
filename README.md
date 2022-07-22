## Desarrollado con

* yarn: v1.22.18 y
* node: v16.13.0

* jest: v26.6.3
* ts-jest: v26.5.6
* react: v18.0.0
* react-native: 0.69.2

## Decisiones

* Se usó el patrón Redux para el manejo de estado y también como proveedor de información, con una método encargado de verificar la existencia de data en el storage, caso contrario realiza un fetch al api. Obtenido la data modifica el estado almacenando la información en ella para proveerla a los demás.

* Para almacenar la información obtenida en local se usó la libreria AsyncStorage el cual permite guardar la información en el storage del dispositivo.

* Se agregó un useEffect encargado de almacenar la información en storage cada vez que cambia el estado. 

* Se priorizó cumplir con el principio de responsabilidad única creando diversos componentes y poder reutilizar código lo máximo posible para que el proyecto sea mantenible y escalable.

* Se siguieron buenas practicas de Clean Code, SOLID con la nomenclatura, nombres y princio DRY.

* Se realizaron las pruebas unitarias de cada componente con Jest y Testing Library.

