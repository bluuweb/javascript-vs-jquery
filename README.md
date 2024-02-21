# Tabla comparativa Javascript vs Jquery

Principales Métodos y eventos de Javascript y Jquery

| Acción/Método         | JavaScript                                    | jQuery                                           |
| --------------------- | --------------------------------------------- | ------------------------------------------------ |
| Selección de Elemento | `document.querySelector()`                    | `$()` o `jQuery()`                               |
|                       | `document.querySelectorAll()`                 |                                                  |
|                       | `document.getElementById()`                   | `$('#elementId')`                                |
| Evento Click          | `element.addEventListener('click', handler)`  | `$(element).click(handler)`                      |
| Evento Change         | `element.addEventListener('change', handler)` | `$(element).change(handler)`                     |
|                       |                                               |                                                  |
| Ocultar Elemento      | `element.style.display = 'none'`              | `$(element).hide()`                              |
| Mostrar Elemento      | `element.style.display = 'block'`             | `$(element).show()`                              |
| Alternar Visibilidad  |                                               | `$(element).toggle()`                            |
|                       |                                               |                                                  |
| Agregar Clase         | `element.classList.add('className')`          | `$(element).addClass('className')`               |
| Eliminar Clase        | `element.classList.remove('className')`       | `$(element).removeClass('className')`            |
| Alternar Clase        | `element.classList.toggle('className')`       | `$(element).toggleClass('className')`            |
|                       |                                               |                                                  |
| Inner HTML            | `element.innerHTML = 'HTML content'`          | `$(element).html('HTML content')`                |
| Text Content          | `element.textContent = 'Text content'`        | `$(element).text('Text content')`                |
|                       |                                               |                                                  |
| AJAX                  | `fetch()` o `XMLHttpRequest`                  | `$.ajax()` o métodos como `$.get()` o `$.post()` |
| Animaciones           |                                               | `$(element).animate()`                           |
