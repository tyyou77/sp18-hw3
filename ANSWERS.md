## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?

It means that if there are no inputs, the placeholder is counted as the input.


2. Go to `localhost:3000/teachers` in your browser; why does this not work?

We send our data through routes.rb's post action.

3. What type of request did your browser just perform?

Post

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?

localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?

All information are sent to the address.
