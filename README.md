# Traducción al Español del proyecto original

Una traducción para uso interno por parte de Tic-Toc Studio

# BootstrapCake Shell Template

Una plantilla para el generador de código de consola de CakePHP, que incorpora el uso de Bootstrap 3.0 y tiene los controles pensados para su uso en español

## Requerimientos

* [CakePHP](http://cakephp.org/) >= 2.3
* [Bootstrap](http://getbootstrap.com/) >= 3.0

## Instalación

* Extrae los archivos en el directorio de tu proyecto.
* Actualiza tu controlador de Aplicación (app/Controller/AppController.php) para usar el Layout 'bootstrap'

```
class AppController extends Controller {
	public function beforeFilter(){
		$this->layout = 'bootstrap';
	}
}
```

* > cake bake !: Si tienes dudas, consulta las siguietes ligas [http://book.cakephp.org/2.0/en/console-and-shells/code-generation-with-bake.html](http://book.cakephp.org/2.0/en/console-and-shells/code-generation-with-bake.html)
* Cuando se te pida un nombre de plantilla, escoge 'bootstrap'

Para mayor información acerca del autor original, consulta: [http://www.ekoim.com/blog/bootstrap-cakephp-bootstrapcake/](http://www.ekoim.com/blog/bootstrap-cakephp-bootstrapcake/)
