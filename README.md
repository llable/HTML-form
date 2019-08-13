# HTML-form
Example of using form, text input and buttons is shown. <br>
HTML5에서 form 내의 text input과 버튼을 활용하는 예제를 보입니다. 
> Environment: HTML5, CSS3, Bootstrap4

## Execution result
<img src="/result.PNG" width="700px">

## Basic function
### input options
- type options: text, number, password etc.
> In this source, we use <strong>text</strong> and <strong>number</strong> option.
- placeholder: text (showing description of each input forms.)
~~~
<!-- type example -->
<input type="text" id="number" placeholder="Please enter your number">
<input type="number" id="number" placeholder="Please enter your number">
~~~
### Alert options
> Use in 'div' tag's class option.
- options: info, success, warning, danger
> In this source, we use <strong>info</strong> option.
~~~
<div class="alert alert-info" role="alert">
</div>
~~~
### Button options
- options: default, primary, success, info, warning, danger, link
> In this source, we use <strong>default</strong>, <strong>primary</strong> and <strong>danger</strong> option.
~~~
<button class="btn btn-default" type="button" id="Login"">Log in</button>
<button class="btn btn-primary" type="button" id="Login"">Log in</button>
<button class="btn btn-danger" type="button" id="Login"">Log in</button>
~~~
- dropdown buttons 
> Use in 'div' tag's class option: btn-group & 'button' tag's class option : dropdown-toggle

### Variable usages
> Fundamental knowledge: javascript
- From button to javascript
> - In button tag's option,
~~~
<button id="<button's id>" onclick="<functionname>()">Call</button>
~~~
> - In Javascript(function),
~~~
var <variablename> =  document.getElementById("<button's id>").value;
~~~

- From javascript to alert
~~~
alert(<variablename>);
~~~

## References
<ol> - Inline alert & buttons : http://bootstrapk.com</ol>
