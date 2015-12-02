

## Module 3 Challenges!

First - Go back and complete today's ToDo. Then try any of the challenges below.

+ Check out the Ruby Labs section of Learn.

+ Start exploring the ActiveRecord `.find_by` method.

  * Use this method to display tweets in your Fwitter application from just one certain user.

+ Read up on [ActiveRecord validations](http://guides.rubyonrails.org/active_record_validations.html) and set up validations for the length of tweets and for the uniqueness of a user’s email address.

+ Add a delete button next to each tweet that deletes the tweet from your Fwitter database.

  * Hint 1 : Try setting this up as a little custom form for each tweet on the page with a hidden input field (`type="hidden"`) that has a value equal to the tweet's id (`value="<%= tweet.id %>"`. The form's submit button will act as the delete button (Hint 1a: You can change the text in a submit button by changing that input tag's value).

  * Hint 2: You're form's action attribute should point to a new route in your application controller that is set up to find that specific tweet in your database and delete it. Try using the `.find_by` method for this or check out the `.find` method.

  * Hint 3: ActiveRecord has a built in method for deleting entries in a database. Google it.

+ Dying to learn more about Rake tasks? Check out the All About That Rake lab on Learn.


<a href='https://learn.co/lessons/hs-fwitter-module-3-challenges' data-visibility='hidden'>View this lesson on Learn.co</a>
