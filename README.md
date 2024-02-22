# Tabla comparativa Javascript vs Jquery

Principales Métodos y eventos de **Javascript vs Jquery**

| Acción/Método         | JavaScript                                                                              | jQuery                                           |
| --------------------- | --------------------------------------------------------------------------------------- | ------------------------------------------------ |
| Selección de Elemento | [`document.querySelector()` ](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector)                                                             | `$()` o `jQuery()`                               |
|                       | [`document.querySelectorAll()`](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelectorAll)                                                           |                                                  |
|                       | [`document.getElementById()`](https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById)                                                             | `$('#elementId')`                                |
| Evento Click          | [`element.addEventListener('click', handler)`](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)                                            | `$(element).click(handler)`                      |
| Evento Change         | [`element.addEventListener('change', handler)`](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)                                           | `$(element).change(handler)`                     |
|                       |                                                                                         |                                                  |
| Ocultar Elemento      | [`element.style.display = 'none'`](https://www.w3schools.com/jsref/prop_html_style.asp)                                                        | `$(element).hide()`                              |
| Mostrar Elemento      | [`element.style.display = 'block'`](https://www.w3schools.com/jsref/prop_html_style.asp)                                                       | `$(element).show()`                              |
| Alternar Visibilidad  |                                                                                         | `$(element).toggle()`                            |
|                       |                                                                                         |                                                  |
| Agregar Clase         | [`element.classList.add('className')` ](https://developer.mozilla.org/es/docs/Web/API/Element/classList)                                                   | `$(element).addClass('className')`               |
| Eliminar Clase        | [`element.classList.remove('className')`](https://developer.mozilla.org/es/docs/Web/API/Element/classList)                                                 | `$(element).removeClass('className')`            |
| Alternar Clase        | [`element.classList.toggle('className')`](https://developer.mozilla.org/es/docs/Web/API/Element/classList)                                                 | `$(element).toggleClass('className')`            |
|                       |                                                                                         |                                                  |
| Inner HTML            | [`element.innerHTML = 'HTML content'`](https://developer.mozilla.org/es/docs/Web/API/Element/innerHTML)                                                    | `$(element).html('HTML content')`                |
| Text Content          | [`element.textContent = 'Text content'`](https://developer.mozilla.org/es/docs/Web/API/Node/textContent)                                                  | `$(element).text('Text content')`                |
|                       |                                                                                         |                                                  |
| AJAX                  | [`fetch()`](https://developer.mozilla.org/es/docs/Web/API/Fetch_API) o `XMLHttpRequest`                                                            | `$.ajax()` o métodos como `$.get()` o `$.post()` |
| Animaciones           | [`element.animate()`](https://developer.mozilla.org/en-US/docs/Web/API/Element/animate) | `$(element).animate()`                           |
