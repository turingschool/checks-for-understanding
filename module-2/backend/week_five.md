Questions from Week 5:
1. How do we make flash messages display on a page?

2. Where is cart information/temporary information usually stored?

3. What might be some reasons not to store a cart in our database? Are there any reasons why we would want to persist that information?

4. What is the purpose of the asset pipeline?

5. Why do we precompile our assets?

6. What do each of the following tags do?

```ruby 
<%= stylesheet_link_tag "application" %>
<%= javascript_include_tag "application" %>
<%= image_tag "rails.png" %>
```

7. What are some of the elements of a great read me? What are some of the benefits of taking the time to update a readme for our project?

8. What are the top four accessibility issues that we as developers should be aware of?

9. `before_save` is an example of a what? Where in our Rails application would we find a `before_save`?

10. Given the following object, how would we create a scope for all users who are active?

```ruby 
User.create(name: "Happy", active: true)
```

11. What is the difference between a scope and a class method?


Review Questions:  
12. Given the following hash:  

```ruby
{cart: {"17" => 4, "204" => 52, "29" => 22}}
```

  12a. How would you add item with id of 48 with a quantity of 4?  
  12b. How would you increase the quantity of item 29?  
  12c. How would you find out how many items your user is thinking about purchasing?   
  
13. What is polymorphism? How does it relate to duck-typing? What are two ways you use this in everyday Rails applications?  
14. How would you clean the string "(630) 854-5483" to "630.854.5483"?  
