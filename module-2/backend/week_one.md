## Week One - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!). 

Note: When you're done, submit a PR. 

1. List the five common HTTP verbs and what the purpose is of each verb.
2. What is Sinatra?
4. What is MVC?
5. Why do we follow conventions when creating our actions/path names in our Sinatra routes?
6. What types of variables are accessible in our view templates without explicitly passing them?
7. Given the following block of code, how would I pass an instance variable `count` with a value of `1` to my `index.erb` template?
  
  ```ruby
  get '/horses' do
    erb :index
  end
  ```

8. In the same code block, how would I pass a local variable `name` with a value of `Mr. Ed` to the view?
9. What's the purpose of ERB?
10. Why do I need a development AND test database?
11. What is CRUD and why is it important?
12. What does HTTP stand for? 
13. What are the two ways to interpolate Ruby in an ERB view template? What's the difference between these two ways?
14. What's an ORM?
15. What's the most commonly used ORM in ruby (Sinatra & Rails)?
16. Let's say we have an application with restaurants. There are seven verb + path combinations necessary to provide full CRUD functionality for our restaurant application. List each of the seven combinations, and explain what each is for.
17. What's a migration? 
18. When you create a migration, does it automatically modify your database?
19. How does a model relate to a database?
20. What is the difference between `#new` and `#create`?

Review Questions:
21. Given a CSV file (“films.csv”) with these headers [id, title, description], how would you load these into your database to create new instances of Film?  
22. Given the following hash:
```
activities = {
  hiking: {cost: $0, supplies: ['hiking shoes', 'water', 'compass']},
  karaoke: {cost: $10, supplies: ['courage', 'microphone'],
  brunch: {cost: $35, supplies: ['mimosa flutes'],
  antiquing: {cost: $200, supplies: ['list of antique stores'] 
}
```
How would I add 'granola bar' to things you should have when hiking?
