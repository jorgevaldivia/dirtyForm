# dirtyForm

jQuery plugin that allows you to track if any form has changed since .dirtyForm() has been called on it. Works with standad HTML form fields as well as CKEditor.

## Usage

After including it

	$( "#my_form" ).dirtyForm();
	// .. make changes to form fields
	alert( $( "my_form" ).attr( "dirty" ) );

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request