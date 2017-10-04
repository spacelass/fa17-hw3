## Questions

What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
	It ensures the placeholdr course is the default, since nil is usually the default if nothing is passed.

Go to `localhost:3000/teachers` in your browser; why does this not work?
	Nothing was passed in as a new input, so there's nothing to show when they run GET.

What type of request did your browser just perform?
	GET

Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
	http://localhost:3000/teachers

Why does `localhost:3000/teachers` work now?
	Because I CREATED a form that /teachers could GET.