## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?

ANSWER: The second 'nil' argument represents the value of that text_field to start. Since it is 'nil,' there is no value to start.

2. Go to `localhost:3000/teachers` in your browser; why does this not work?

ANSWER: There is no route to handle a GET request to '/teachers,' only a POST request to '/teachers.'

3. What type of request did your browser just perform?

ANSWER: It just tried to perform a GET request.

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?

ANSWER: 'localhost:3000/teachers'

5. Why does `localhost:3000/teachers` work now?

ANSWER: This is a POST request to '/teachers,' which we have a route created to handle.