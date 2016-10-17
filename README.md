# Javascript-form-validation

This javascript library is lightweight.


Simply add class to input field and then create new validation object for a form.

## How to use
```
<form name="form2" id="form2" class="rs-form">
	<div class=" test ">
		<input type="text" name="name" value="" class="">
	</div>
	<div class=" test ">
		<input type="text" name="age"  value="" class="required numeric minlength-3 rs-me-head" >
	</div>
	<div class="">
		<input type="text" name="email"  value="" class="required valid-email">
	</div>
	<input type="submit" name="age">
</form>
```
And Then create validation object.
```javascript

var validate = new Validate({
	"FormName" : 'form2',
	"ErrorLevel" : 0,
});
```



